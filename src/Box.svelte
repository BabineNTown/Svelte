<div class="box">
	<slot>
		<em>no content was provided</em>
	</slot>
</div>

<style>
    .box
    {
        box-shadow: 0px 0px 0px black,
                    0px 0px 10px black;
        width: 28%;
        height: 120%;
        background-color: white;
        margin-bottom: 20%;
    }
    .box:hover
    {
        background-color: gray;
        transition: 0.4s;
        color: white;
    }
</style>