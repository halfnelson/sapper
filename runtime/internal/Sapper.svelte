<script>
	import { setContext } from 'svelte';
	import { CONTEXT_KEY } from './shared';

	export let Root;
	export let props;
	export let session;

	setContext(CONTEXT_KEY, session);
</script>

<Root {...props}/>