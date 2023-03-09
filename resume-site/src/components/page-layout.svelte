<script>
  import Nav from "./nav.svelte";


</script>

<Nav/>
<main>
    <slot/>
</main>

<style>
    :global(html) {
		background-color: #2b2736;
		color: #f1f1f1;
		display: flex;
		justify-content: center;
		margin-top: 45vh;
	}
    main{
        position: absolute;
        top: 4%;
    }
</style>