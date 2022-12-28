<script lang="ts">
	import '../app.css';
	import { SvelteToast } from '@zerodevx/svelte-toast';
	import { inject } from '@vercel/analytics';

	inject();
</script>

<SvelteToast />
<slot />
