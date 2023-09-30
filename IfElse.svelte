<script>
let count=0;	

function add()
	{
		count+=1;
	}
</script>
<button on:click={add}>Click me {count} times</button>
{#if count > 10}
	<p>Count is greater than 10</p>
{:else if count==10}
	<p>Count is equal to 10</p>

	{:else}
	<p>Count is less than 10</p>
{/if}
