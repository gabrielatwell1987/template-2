<script>
	import Image from '$lib/components/Image.svelte';
</script>

<h1>Contact Me</h1>
<h2>Contact subtitle</h2>

<div class="image">
	<Image picture="cat.avif" desc="Placeholder" x="300" y="450" />

	<Image picture="lighthouse.avif" desc="Placeholder" x="300" y="450" />
</div>

<p>
	Place contact me links or your email for people to contact you.. Think about adding a form for
	people to contact you. You can successfully do the form by using a service called FormTaxi.
</p>

<Image picture="branches.avif" desc="Placeholder" x="1500" y="750" />

<style>
	h1 {
		font-size: 4rem;
		letter-spacing: 0.75rem;
		margin-right: 50%;
	}

	h2 {
		font-size: 1.75rem;
		letter-spacing: 0.75rem;
		margin-right: 53%;
	}

	.image {
		display: flex;
		gap: 50%;
		justify-content: space-between;
		margin: 5rem 20rem 4rem 0;
	}

	p {
		font-size: 1.25rem;
		width: 75%;
		line-height: 2.25;
		letter-spacing: 5px;
	}
</style>
