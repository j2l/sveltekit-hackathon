<script lang="ts">
    import { user, auth, supabase } from '$lib/db'
    import Auth from 'supabase-ui-svelte'
</script>

{#if $user}
    <p>You are signed in as {$user.email}</p>
    <button on:click={() => auth.signOut()}>Sign out</button>
    {:else}
    <div class="container">
        <h1>Sign in</h1>
      
        <Auth supabaseClient={supabase} providers={['gitlab', 'github']}/>
      </div>
{/if}
