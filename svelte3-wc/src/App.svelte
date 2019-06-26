<svelte:options tag="my-app" />

<script>
	import Inner from './Inner.svelte';

	function handleMessage(event) {
		console.log('handleMessage in parent: ', event.detail.text);
	}
</script>

<inner-btn on:message={handleMessage}/>