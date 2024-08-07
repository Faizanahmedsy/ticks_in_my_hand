<script>
	import Button from '$lib/components/ui/button/button.svelte';
</script>

<h1 class="text-3xl font-bold underline">Hello world!</h1>

<Button>Click Me</Button>

<style lang="postcss">
	:global(html) {
		background-color: theme(colors.gray.100);
	}
</style>
