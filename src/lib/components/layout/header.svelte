<script>
	export let text;
</script>

<div class="header">
	<h1><em>{text}</em></h1>
</div>

<style>
	.header {
		display: flex;
		align-items: center;
		height: 150px;
		width: 100%;
		margin: 0 auto;
		background: #01025f;
		background: -webkit-linear-gradient(top left, #01025f, #0188d5);
		background: -moz-linear-gradient(top left, #01025f, #0188d5);
		background: linear-gradient(to bottom right, #01025f, #0188d5);
	}
	.header h1 {
		text-align: center;
		width: 100%;
		font-size: 50px;
		color: #fff;
	}
</style>
