<script>
	import Image from '$lib/components/Image.svelte';
</script>

<h1>Blog</h1>
<h2>Example blog</h2>

<div class="image">
	<Image picture="city.avif" desc="Placeholder" x="1500" y="600" />
</div>

<p>
	This is a blog post. You can write about anything you want here. You can write about your day,
	your favorite things, your least favorite things, etc.
</p>

<p>You can use mdsvex for markdown on this blog.</p>

<style>
	h1 {
		font-size: 4rem;
		letter-spacing: 0.75rem;
		margin-right: -50%;
	}

	h2 {
		font-size: 1.75rem;
		letter-spacing: 0.75rem;
		margin-right: -41.5%;
	}

	p {
		font-size: 1.25rem;
		width: 75%;
		line-height: 2.25;
		letter-spacing: 5px;
	}

	.image {
		margin: 5rem 0 4rem 0;
	}
</style>
