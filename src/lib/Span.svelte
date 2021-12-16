<script lang="ts">
	export { className as class };
	let className: string = null;
</script>

<span class={'text-red-500' + (className ? ' ' + className : '')}>
	<slot />
</span>
