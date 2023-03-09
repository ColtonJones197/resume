<script>

</script>

<nav>
    <ul>
        <li><a href="./">HOME</a></li>
        <li><a href="/about">ABOUT</a></li>
        <li><a href="./">PROJECTS</a></li>
        <li><a href="./">RESUME</a></li>
    </ul>
</nav>
<div class="content"><slot /></div>

<style>
    nav{
        position: absolute;
        display: flex;
        left: 0%;
        top: 4%;
        width: 20%;
        min-width: 14vh;
        height: 92vh;
        border-right: 2.5px solid #d3d3d3;
        padding-left: 2vh;
        padding-top: 2vh;
        font-size: x-large;
        font-weight: bold;
    }
    li{
        margin-bottom: .5em;
        border-left: 2px solid #a3a3a3;
        width: 14vh;
    }
    li:hover{
        color: #2b2736;
		background-color: #f1f1f1;
		border-color: #2b2736;
    }
    a{
        margin-left: 10px;
    }
    .content
    {
        padding-top: 2vh;
        left: 0%;
        top: 4%;
    }
</style>