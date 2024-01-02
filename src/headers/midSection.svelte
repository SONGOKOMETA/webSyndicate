<script>
  import "../assets/styles/midSectionStyle.css";
  import drakeImg from "../assets/resources/drake.jpg";
  import textDictionary from "$lib/data/content.json";
</script>

<div class="main-Container">
  <h2>{textDictionary.midSectionTopText}</h2>
  <span id="flavor-Text_mid">{textDictionary.midSectionFlavorText} </span>
  <br />
  <br />
  <div class="mid-Gallery">
    <div class="mid-Gallery_content">
      <img src={drakeImg} alt="contentImg" />
      <div class="mid-Gallery_content_text">
        <h3>{textDictionary.galleryTopTextTL}</h3>
        <span>
          {textDictionary.galleryFlavorTextTL}
        </span>
      </div>
    </div>
    <div class="mid-Gallery_content">
      <img src={drakeImg} alt="contentImg" />
      <div class="mid-Gallery_content_text">
        <h3>{textDictionary.galleryTopTextTM}</h3>
        <span>
          {textDictionary.galleryFlavorTextTM}
        </span>
      </div>
    </div>
    <div class="mid-Gallery_content">
      <img src={drakeImg} alt="contentImg" />
      <div class="mid-Gallery_content_text">
        <h3>{textDictionary.galleryTopTextTR}</h3>
        <span>
          {textDictionary.galleryFlavorTextTR}
        </span>
      </div>
    </div>
    <div class="mid-Gallery_content">
      <img src={drakeImg} alt="contentImg" />
      <div class="mid-Gallery_content_text">
        <h3>{textDictionary.galleryTopTextML}</h3>
        <span>
          {textDictionary.galleryFlavorTextML}
        </span>
      </div>
    </div>
    <div class="mid-Gallery_content">
      <img src={drakeImg} alt="contentImg" />
      <div class="mid-Gallery_content_text">
        <h3>{textDictionary.galleryTopTextMM}</h3>
        <span>
          {textDictionary.galleryFlavorTextMM}
        </span>
      </div>
    </div>
    <div class="mid-Gallery_content">
      <img src={drakeImg} alt="contentImg" />
      <div class="mid-Gallery_content_text">
        <h3>{textDictionary.galleryTopTextMR}</h3>
        <span>
          {textDictionary.galleryFlavorTextMR}
        </span>
      </div>
    </div>
    <div class="mid-Gallery_content">
      <img src={drakeImg} alt="contentImg" />
      <div class="mid-Gallery_content_text">
        <h3>{textDictionary.galleryTopTextBL}</h3>
        <span>
          {textDictionary.galleryFlavorTextBL}
        </span>
      </div>
    </div>
    <div class="mid-Gallery_content">
      <img src={drakeImg} alt="contentImg" />
      <div class="mid-Gallery_content_text">
        <h3>{textDictionary.galleryTopTextBM}</h3>
        <span>
          {textDictionary.galleryFlavorTextBM}
        </span>
      </div>
    </div>
    <div class="mid-Gallery_content">
      <img src={drakeImg} alt="contentImg" />
      <div class="mid-Gallery_content_text">
        <h3>{textDictionary.galleryTopTextBR}</h3>
        <span>
          {textDictionary.galleryFlavorTextBR}
        </span>
      </div>
    </div>
  </div>
</div>
