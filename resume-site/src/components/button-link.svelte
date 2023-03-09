<script>
    export let link = "/";
</script>

<a href={link}><button class="text-center"><slot /></button></a>


<style>
	:global(html) {
		background-color: #2b2736;
		color: #f1f1f1;
		display: flex;
		justify-content: center;
		margin-top: 45vh;
	}
    button {
        background-color: #2b2736;
		border: .2em solid white;
		margin-top: 1em;
		transition: .5s;
		padding: .25em;
		font-weight: bold;
		font-size: large;
        display: flex;
        margin-left: 30%;
	}
	button:hover
	{
		color: #2b2736;
		background-color: #f1f1f1;
		border-color: #2b2736;
	}
</style>