<script lang="ts">
	export let message: string;
	export let okay: boolean;
</script>

{message}

{#if okay}
	{message} again
{/if}
