<script>
	let count = 0;

	function handleClick() {
		count += 1;
        console.log('count:', count);
	}
</script>

<button on:click={handleClick}>
	Clicked {count}
	{count === 1 ? 'time' : 'times'}
</button>
