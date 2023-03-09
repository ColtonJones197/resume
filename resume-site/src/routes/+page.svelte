<script>
	const about_link = './about/+page.svelte';
</script>

<h1 class="text-3xl font-bold text-center">Colton Jones</h1>
<p>Software | Smash | Fitness | Rackets</p>
<a href="/about"><div class="text-center"><button class="text-center">About Me</button></div></a>


<style>
	:global(html) {
		background-color: #2b2736;
		color: #f1f1f1;
		display: flex;
		justify-content: center;
		margin-top: 45vh;
	}

	button {
		border: .2em solid white;
		margin-top: 1em;
		transition: .5s;
		padding: .25em;
		font-weight: bold;
		font-size: large;
	}
	button:hover
	{
		color: #2b2736;
		background-color: #f1f1f1;
		border-color: #2b2736;
	}
</style>
