<script>
	import Card from '$lib/components/Card.svelte';
	import Button from '$lib/components/Button.svelte';
</script>

<h1>Home Page</h1>

<p>
	This is a home page template. You can add your own content here. You can add a button below to
	link to whatever you want. You can also add cards below to display information. You can also add
	images to make your page more visually appealing.
</p>

<div class="button">
	<Button title="Call to action" link="https://google.com" />
</div>

<hr />

<div class="card">
	<Card title="Example" img="img_avatar.png" content="Name: John Doe" />

	<Card title="Example 2" img="img_avatar2.png" content="Name: Jane Doe" />
</div>

<style>
	h1 {
		font-size: 4rem;
		letter-spacing: 0.5rem;
	}

	p {
		font-size: 1.25rem;
		width: 50%;
		line-height: 2.25;
		margin-bottom: 3rem;
	}

	.card {
		display: flex;
		gap: 1rem;
	}

	hr {
		margin: 0 0 5% 0;
		width: 85%;
	}

	.button {
		margin-bottom: 10%;
		margin-left: 20%;
	}
</style>
