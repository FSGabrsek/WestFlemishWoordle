<script>
	import Header from './Header.svelte';
</script>

<main>
	<Header id="header"/>
</main>

<style>
	main {
		position: absolute;
		left: 50%;
		transform: translate(-50%, 0);
		
		max-width: var(--game-max-width);
		width: 100%;
	}
</style>