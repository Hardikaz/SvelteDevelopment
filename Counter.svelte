<script>
	let counter=0;

	function increase(){
		counter+=1;
	}
</script>
<button on:click={increase}>Click {counter} me</button>
