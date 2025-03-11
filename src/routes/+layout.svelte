<script lang="ts">
	import '../app.css';
	let { children } = $props();
</script>

{@render children()}

<style>
	:global(body) {
		font-family: 'Roboto', sans-serif;
	}

	@media (prefers-color-scheme: dark) {
		:global(body) {
			background-color: #1a202c;
			color: #e2e8f0;
		}
	}
</style>