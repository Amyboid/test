<script>
  const { data } = $props();
  const post = data.post;
</script>

<h1>
  {post.title}
</h1>
<h2>{post.content}</h2>
