<script lang="ts">
	export let className: string = null;
</script>

<span class={'text-red-500' + (className ? ' ' + className : '')}>
	<slot />
</span>
