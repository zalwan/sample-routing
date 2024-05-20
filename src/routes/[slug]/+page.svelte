<script lang="ts">
	import { page } from '$app/stores'
</script>

<h1>{$page.params.slug}</h1>
<p>{$page.url}</p>

<pre>
  {JSON.stringify($page, null, 2)}
</pre>

<style>
	h1 {
		color: red;
		/* text-transform: uppercase; */
	}
</style>
