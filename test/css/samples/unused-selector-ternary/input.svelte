<script>
	export let active;
</script>

<div class='{active ? "active": "inactive"}'></div>

<style>
	.active {
		color: red;
	}

	.inactive {
		color: blue;
	}

	.maybeactive {
		color: green;
	}
</style>