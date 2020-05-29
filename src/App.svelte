<script>
  import Card from "./Card.svelte";
</script>

<style>
  header img {
    max-width: 300px;
  }
  .projects-row {
    margin-top: 1em;
  }

  @media (max-width: 640px) {
    header img {
      max-width: 124px;
    }
  }
</style>

<header>
  <img src="/playahead-logo-white.png" alt="Play Ahead Games Logo" />
</header>
<body>
  <h1>Projects</h1>
  <div class="projects-row">
    <Card
      href="https://treasure.playaheadgames.com"
      title="Treasure Tracker"
      content="A treasure generator for the popular tabletop RPG: Castles and
      Crusades."
      image="https://treasure.playaheadgames.com/img/meta.png" />
  </div>
  <!-- <a href="https://treasure.playaheadgames.com">Treasure Tracker</a>
  <a href="alert('coming soon')">Realtime RPG (working title)</a> -->
</body>
