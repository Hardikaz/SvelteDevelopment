<script>
	let celcius=0;
	$:  fahrenheit=celcius*1.8 +32;
</script>

<h1>Type in celcius</h1>
<input type="number" bind:value={celcius}>

<p>The temp in Fahrenheit is {fahrenheit}</p>
