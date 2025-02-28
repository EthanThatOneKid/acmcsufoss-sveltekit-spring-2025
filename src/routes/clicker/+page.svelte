<script>
	let count = 0;
</script>

<h1>Clicker</h1>

<button class="cookie-button" on:click={() => count++}>
	<img
		class="cookie-image"
		src="https://placecats.com/100/100"
		alt="Cookie Cat from Steven Universe"
	/>

	The count is {count}</button
>

<style>
	.cookie-button {
		border: none;
	}

	.cookie-image {
		width: 100px;
		height: 100px;
	}
</style>
