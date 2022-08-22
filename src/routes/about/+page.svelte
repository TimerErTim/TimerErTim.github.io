<script>
    import GitHubLink from '$lib/components/github/GitHubLink.svelte'
</script>

<svelte:head>
    <title>About</title>
    <meta content='About this app' name='description' />
</svelte:head>

<div class='content space-y-6'>
    <h1>About this app</h1>

    <p class='text-center'>
        This is a <a href='https://kit.svelte.dev'>SvelteKit</a> app. The source code is hosted on
        <GitHubLink target='https://github.com/timerertim/timerertim.github.io' />
    </p>
</div>

<style>
    .content {
        width: 100%;
        max-width: var(--column-width);
        margin: var(--column-margin-top) auto 0 auto;
    }
</style>
