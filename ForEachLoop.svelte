<script>
	let task=["Buy milk","Eat food","Take Bath"]
</script>

{#each task as t,i}
	<li>{i+1}.{t}</li>

{/each}
