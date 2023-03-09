<script>
  import ButtonLink from "../components/button-link.svelte";

	const about_link = './about/+page.svelte';
</script>

<h1 class="text-3xl font-bold text-center">Colton Jones</h1>
<p>Software | Smash | Fitness | Rackets</p>
<ButtonLink link="/about">About Me</ButtonLink>


<style>
	:global(html) {
		background-color: #2b2736;
		color: #f1f1f1;
		display: flex;
		justify-content: center;
		margin-top: 45vh;
	}
</style>
