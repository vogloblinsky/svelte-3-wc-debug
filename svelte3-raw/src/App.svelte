<script>
	import Inner from './Inner.svelte';

	function handleMessage(event) {
		console.log('handleMessage in parent: ', event.detail.text);
	}
</script>

<Inner on:message={handleMessage}/>