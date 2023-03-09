<script>
  import PageLayout from "../../components/page-layout.svelte";
</script>

<h1>About Me</h1>
<section>
	<p>Sup brother</p>
	<PageLayout>child element</PageLayout>
</section>

<style>
	:global(html) {
		background-color: #2b2736;
		color: #f1f1f1;
		display: flex;
		justify-content: center;
		padding-top: 4vh;
	}
</style>
