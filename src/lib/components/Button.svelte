<script>
	export let title;
	export let link;
</script>

<a href={link} target="_blank">
	<button>{title}</button>
</a>

<style>
	button {
		background-color: var(--blue);
		border: none;
		color: white;
		padding: 0.5rem 1.25rem;
		text-align: center;
		display: inline-block;
		font-size: 1.5rem;
		font-weight: 600;
		cursor: pointer;
		border-radius: 5px;
		letter-spacing: 0.25rem;
		font-family: var(--oswald);
	}
</style>
