<script>
  import Card from "./Card.svelte";
</script>

<main>
  <div class="left">
    <img src="/playahead-logo.svg" alt="Play Ahead Games Logo" />
    <h3 class="contact">
      <a href="mailto:hello@playaheadgames.com">Contact</a>
    </h3>
    <p>
      <a href="https://www.patreon.com/playaheadgames">Support us on Patreon</a>
      for access to early game builds, a private Discord, and more!
    </p>
  </div>
  <div class="right">
    <h2>Games</h2>
    <Card
      href="https://treasure.playaheadgames.com"
      title="Treasure Tracker"
      content="A treasure generator for the popular tabletop RPG: Castles and
      Crusades."
      image="https://treasure.playaheadgames.com/img/meta.png" />
    <Card
      href="https://rtcrpg.playaheadgames.com"
      title="RTCRPG (Working Title)"
      content="A end-of-the-world dungeon crawler with real-time combat mechanics (Coming Soon)"
      image="/rtc-screenshot.png" />
  </div>
</main>
