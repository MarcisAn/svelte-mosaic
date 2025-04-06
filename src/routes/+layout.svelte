<script lang="ts">
	import '../app.css';
	import '@fontsource-variable/jetbrains-mono';
	
	interface Props {
		children?: import('svelte').Snippet;
	}

	let { children }: Props = $props();
</script>

{@render children?.()}
