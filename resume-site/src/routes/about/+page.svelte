<script>
  import PageLayout from "../../components/page-layout.svelte";
</script>

<section>
	<PageLayout>
		<div class="flex-template">
			<div class="left-side">content</div>
			<div class="right-side">other content</div>
		</div>
	</PageLayout>
</section>

<style>
	.flex-template{
		display: grid;
		grid-template-columns: 33% auto;
		position: relative;
	}
	.left-side{
		flex-grow: 2;
		background-color: brown;
		padding: 100%;
	}
	.right-side{
		flex-grow: 4;
		background-color: green;
		padding: 100%;
	}
</style>
