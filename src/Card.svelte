<script>
  export let href;
  export let title;
  export let content;
  export let image;
</script>

<style>
  a {
    text-decoration: none;
    display: block;
    background-color: #fff;
    border-radius: 3px;
    max-width: 300px;
    box-shadow: 0 1px 3px rgba(0, 0, 0, 0.12), 0 1px 2px rgba(0, 0, 0, 0.24);
    transition: all 0.3s cubic-bezier(0.25, 0.8, 0.25, 1);
  }

  a:hover {
    box-shadow: 0 14px 28px rgba(0, 0, 0, 0.25), 0 10px 10px rgba(0, 0, 0, 0.22);
  }

  h2 {
    margin: 0;
    margin-top: 0.14em;
    margin-left: 0.25em;
    margin-right: 0.25em;
  }

  p {
    margin-left: 0.4em;
    margin-right: 0.25em;
    padding-bottom: 0.5em;
  }

  img {
    width: 100%;
    border-top-left-radius: 3px;
    border-top-right-radius: 3px;
    transition: all 0.3s cubic-bezier(0.25, 0.8, 0.25, 1);
  }

  a:hover img {
    filter: brightness(115%);
  }
</style>

<a {href}>
  <img src={image} alt="Screenshot of the treasure tracker UI" />
  <h2>{title}</h2>
  <p>{content}</p>
</a>
