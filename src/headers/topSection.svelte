<script>
  import "../assets/styles/topSectionStyle.css";
  import discordLogo from "../assets/resources/discord-logo.png";
  import textDictionary from "$lib/data/content.json";
</script>

<div class="main-Container">
  <h1>{textDictionary.topSectionTopText}</h1>
  <br />
  <span id="main-Container-Flavor-Text">
    {textDictionary.topSectionFlavorText}
  </span>
  <br />

  <a href="https://discord.gg/3mfCC5cYW3">
    <div class="main-Container-Discord-Button">
      <img src={discordLogo} alt="discord button" />
    </div>
  </a>
</div>
