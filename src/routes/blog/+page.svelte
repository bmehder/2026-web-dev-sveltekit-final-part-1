<script>
	import PageTitle from '$lib/components/PageTitle.svelte'
	import { formatDate } from '$lib/utils.js'

	let { data } = $props()
</script>

<PageTitle title="Blog"></PageTitle>

{#each data.posts as post}
	<article>
		<div class="outer">
			<div class="inner">
				<div class="content">
					<a href="/blog/{post.slug}"><img src={post.meta.image} alt="" /></a>
					<h3>
						<a href="/blog/{post.slug}">{post.meta.title}</a>
					</h3>
					<div class="date">{formatDate(post.meta.date)}</div>
					<p>{post.meta.excerpt}</p>
					<a href="/blog/{post.slug}">Read More</a>
				</div>
			</div>
		</div>
	</article>
{/each}

<style>
	.content {
		max-width: 65ch;
	}

	h3 {
		margin-bottom: 0;
	}

	.date {
		opacity: 0.6;
	}
</style>