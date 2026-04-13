<script>
	import { formatDate } from '$lib/utils.js'

  let { data } = $props()

  let Post = $derived(data.post.component)
</script>

<article>
  <div class="outer">
    <div class="inner">
      <img src="/{data.post.meta.image}" alt="">
      <div class="content">
        <h1>{data.post.meta.title}</h1>
        <div class="date">{formatDate(data.post.meta.date)}</div>
        <Post></Post>
      </div>
    </div>
  </div>
</article>

<style>
  .content  {
    max-width: 65ch;
  }

  h1 {
    margin-bottom: 0;
  }

  .date {
    opacity: 0.6;
  }
</style>