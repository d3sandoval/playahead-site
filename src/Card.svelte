<script>
  export let href;
  export let title;
  export let content;
  export let image;
</script>

<a class="card" {href}>
  <div class="content">
    <img src={image} alt="Screenshot of {title}" />
    <div class="text">
      <h3>{title}</h3>
      <p>{content}</p>
    </div>
  </div>
</a>

<!-- <a class="card" {href}>
  <img src={image} alt="Screenshot of the treasure tracker UI" />
  <h2>{title}</h2>
  <p>{content}</p>
</a> -->
