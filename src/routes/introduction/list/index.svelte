<script>
    let items = [{name: 'a'}, {name: 'b', desc: 'lol'}, {name: 'c', desc:'hey'}]
</script>

<h1>list</h1>
<ul>
	{#each items as item}
		<a href={`./list/${item.name}`}><li>{item.name} x {item.desc}</li></a>
	{/each}
</ul>