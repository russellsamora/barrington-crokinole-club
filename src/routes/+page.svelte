<script>
	import { setContext } from "svelte";
	import { browser } from "$app/environment";
	import Meta from "$components/Meta.svelte";
	import Index from "$components/Index.svelte";
	import version from "$utils/version.js";

	version();
</script>

<Meta />
<Index />
