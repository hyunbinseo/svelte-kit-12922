<script>
	import { page } from '$app/stores';

	$effect(() => {
		if ($page.url.hash) window.location.hash = $page.url.hash;
	});
</script>

<p>You are on A!</p>
<ol>
	<li>Now click the browser's back button</li>
</ol>
