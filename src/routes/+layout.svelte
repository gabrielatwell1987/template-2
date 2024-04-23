<script>
	import '../app.css';
	import Nav from '$lib/components/Nav.svelte';
	import Footer from '$lib/components/Footer.svelte';
</script>

<Nav />

<main>
	<slot />
</main>

<Footer copyright="&copy; 2024 Atwell" />

<style>
	:global(body) {
		background: linear-gradient(to top, #0f0f0f 50%, #1b1a55 100%) no-repeat center center/cover
			fixed;
		color: white;
	}

	main {
		display: grid;
		place-items: center;
		margin-top: 5rem;
	}
</style>
