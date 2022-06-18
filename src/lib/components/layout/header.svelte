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
		background-image: radial-gradient(
			circle 976px at 51.2% 51%,
			rgba(11, 27, 103, 1) 0%,
			rgba(16, 66, 157, 1) 0%,
			rgba(11, 27, 103, 1) 17.3%,
			rgba(11, 27, 103, 1) 58.8%,
			rgba(11, 27, 103, 1) 71.4%,
			rgba(16, 66, 157, 1) 100.2%,
			rgba(187, 187, 187, 1) 100.2%
		);
	}
	.header h1 {
		text-align: center;
		width: 100%;
		font-size: 50px;
		color: #fff;
	}
</style>
