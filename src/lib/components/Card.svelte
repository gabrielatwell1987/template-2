<script>
	export let title;
	export let content;
	export let img;
</script>

<section class="card">
	<img src={img} alt="Avatar" style="width:50%" />
	<div class="container">
		<h4><b>{title}</b></h4>
		<p>{content}</p>
	</div>
</section>

<style>
	.card {
		box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
		transition: 0.3s;
		border-radius: 5px;
		margin-top: 1rem;
		display: inline-block;
	}

	.card:hover {
		box-shadow: 0 8px 16px 0 rgba(0, 0, 0, 0.2);
	}

	.container {
		padding: 2px 16px;
		text-align: center;
	}

	img {
		border-radius: 15px 15px 5px 5px;
		margin-left: 25%;
	}

	h4 {
		font-size: 1.5rem;
		font-weight: 700;
		margin-bottom: 1rem;
		font-family: var(--serif);
		letter-spacing: 0.05rem;
	}

	p {
		font-size: 1.25rem;
	}
</style>
