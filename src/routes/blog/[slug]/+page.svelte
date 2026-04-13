<script>
  let { data } = $props()

  let Post = $derived(data.post.component)
</script>

<article>
  <img src="/{data.post.meta.image}" alt="">
  <h1>{data.post.meta.title}</h1>
  <div>{data.post.meta.date}</div>
  <Post></Post>
</article>