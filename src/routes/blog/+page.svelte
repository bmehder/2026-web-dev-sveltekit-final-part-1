<script>
	let { data } = $props()
</script>

<h1>Blog</h1>

{#each data.posts as post}
	<article>
		<a href="/blog/{post.slug}"><img src={post.meta.image} alt="" /></a>
		<h3>
			<a href="/blog/{post.slug}">{post.meta.title}</a>
		</h3>
		<div>{post.meta.date}</div>
		<p>{post.meta.excerpt}</p>
		<a href="/blog/{post.slug}">Read More</a>
	</article>
{/each}