<script>
	let fruit=["apples","oranges"];

	function addItem()
		{
			// fruit.push("lemons");
			// fruit=fruit;

			fruit=[...fruit,"Lemon"];
		}
	$: fruitsList=fruit.join(', ');
</script>
<h1>Available fruits: {fruitsList}</h1>
<button on:click={addItem}>Add Item</button>
