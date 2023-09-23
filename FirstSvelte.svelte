<script>
	let name="Hardik Sharma";
	let src="https://img.freepik.com/premium-vector/ninja-shinobi-position-fight-enemy-with-his-katana-hand-drawn-illustration_73644-31.jpg?w=2000";
	let alt="image";

	function print(){
		alert("I am being clicked");
	}
</script>
<h1>Good Morning {name.toUpperCase()}</h1>
<button on:click={print}>Click Me</button>
<img {src} {alt}/>
<style>
	h1{
		color:blue
	}
</style>




