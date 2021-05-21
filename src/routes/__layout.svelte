<script lang="ts">
	import Header from '$lib/Header/index.svelte';
	//import '../app.css';
	import '../style.css';
</script>

<Header />

<main>
	<slot />
</main>

<footer>
	<p>visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to learn SvelteKit</p>
</footer>

<style>
	@import "@fortawesome/fontawesome-free/css/all.min.css";
	/* check https://bulma.io/documentation/overview/start/ */
	/* @import "bulma/css/bulma.min.css"; */

	/* coming with SvelteKit, uncomment if you remove Bulma */
	/* main {
		flex: 1;
		display: flex;
		flex-direction: column;
		padding: 1rem;
		width: 100%;
		max-width: 1024px;
		margin: 0 auto;
		box-sizing: border-box;
	}

	footer {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		padding: 40px;
	}

	footer a {
		font-weight: bold;
	}

	@media (min-width: 480px) {
		footer {
			padding: 40px 0;
		}
	} */
</style>
