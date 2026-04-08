<script>
	import favicon from '$lib/assets/favicon.svg';

	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>

{@render children()}

<footer>
	<p>©️Polimi 2026</p>
</footer>

// Global styles are defined in the layout, so they are applied to all pages
<style>
    :global(p) {
        color: deeppink;
    }
</style>