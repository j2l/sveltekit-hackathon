<script context="module" lang="ts">
	export const prerender = true;
	import { createClient } from '@supabase/supabase-js'
	import {appName, publictable} from '$lib/Env.js';
	export const supabase = createClient(
		import.meta.env.VITE_SUPABASE_URL,
		import.meta.env.VITE_SUPABASE_ANON_KEY
	)
	
	// load table from db
	export async function load() {
		const { data } = await supabase.from(publictable).select('*')
		return { 
			props: {
				data
			}
		}
	}
</script>

<script lang="ts">
	import Counter from '$lib/Counter/index.svelte';
	// import {appName} from '$lib/Env.js';
	export let data;
</script>

<svelte:head>
	<title>{appName}</title>
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<script defer src="https://use.fontawesome.com/releases/v5.15.2/js/all.js"></script>
</svelte:head>

<section class="section">
	<h1>
		<div class="column is-half is-centered">
			<picture>
				<source srcset="svelte-welcome.webp" type="image/webp" />
				<img src="svelte-welcome.png" alt="Welcome" />
			</picture>
		<div class="bd-notification is-primary title">	to {appName}</div>
		</div>
	</h1>
	<p>There are {data.length} items in the public table (.env).</p>
	{#each data as item}
  <article>
    <a href="/item/{item.permalink}">{item.name}</a>
  </article>
{/each}
	<h2>
		edit this component at <strong>src/routes/index.svelte</strong>
	</h2>

	<Counter />
</section>

<style>
	/* section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 1;
	}

	h1 {
		width: 100%;
	}

	.welcome {
		position: relative;
		width: 100%;
		height: 0;
		padding: 0 0 calc(100% * 495 / 2048) 0;
	}

	.welcome img {
		position: absolute;
		width: 100%;
		height: 100%;
		top: 0;
		display: block;
	} */
</style>
