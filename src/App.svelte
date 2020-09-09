<script>
	export let name;
</script>

<style lang='scss'>
	$color: red;

	@import '../node_modules/bootstrap/scss/bootstrap.scss';

	h1 {
		color: $color;
	}
</style>

<h1>Hello {name}!</h1>
