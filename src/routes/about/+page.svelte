<script>
	import Image from '$lib/components/Image.svelte';
</script>

<h1>About</h1>
<h2>About me subtitle</h2>

<div class="image">
	<Image picture="moon.avif" desc="Placeholder" x="750" y="400" />
</div>

<p>
	This page is your about me page.. You can list hobbys you're into, links to sites you frequently
	encounter, recommendations and testimonials, etc.
</p>

<p>You can include anything you want.</p>

<style>
	h1 {
		font-size: 4rem;
		letter-spacing: 0.75rem;
		margin-right: 50%;
	}

	h2 {
		font-size: 1.75rem;
		letter-spacing: 0.25rem;
		margin-right: 47%;
		margin-top: -0.5rem;
	}

	p {
		font-size: 1.25rem;
		width: 50%;
		line-height: 1.25;
		letter-spacing: 2px;
		margin-bottom: 2%;
		margin-right: 14%;
	}

	.image {
		margin: 5rem 0 4rem 40%;
	}
</style>
