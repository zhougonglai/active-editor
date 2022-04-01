<script context="module">
	export const prerender = true;
</script>

<script>
	const activities = [496];
</script>

<svelte:head>
	<title>首页</title>
</svelte:head>

<section class="grid grid-cols-4">
	{#each activities as active}
		<div class="shadow-dark-500 rounded">
			{active}
		</div>
	{/each}
</section>
