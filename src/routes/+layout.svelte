<script lang="ts">
	import '../app.css'
	import { page } from '$app/stores'
</script>

<main class="container">
	<nav>
		<ul>
			<li>
				<a href="/"> home</a>
			</li>
			<li>
				<a href="/posts"> posts</a>
			</li>
			<li>
				<a href="/{$page.params.slug}">{$page.params.slug}</a>
			</li>
		</ul>
	</nav>
	<slot />
</main>
