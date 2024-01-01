<script>
  import "../styles/navStyle.css";
</script>

<div class="nav-Wrapper">
  <div class="nav-Wrapper-Body">
    <div class="nav-Wrapper-Body-Left">
      <img src="src/static/synd-logo.png" alt="synd-logo.png" />
      <h1 id="main-Text"><a href="/">Syndicate.</a></h1>
      <nav id="sub-Text">
        <a href="/corp1">RD13X</a>
        <a href="/corp2">RXSK</a>
        <a href="/corp3">PRGCO</a>
      </nav>
    </div>
    <div class="nav-Wrapper-Body-Right">
      <a href="/">
        <div class="seat-Button">
          <div class="seat-Button-Content">
            <img src="src/static/seat-logo.png" alt="seat-logo" />
            <span>
              S<b>e</b>AT
            </span>
          </div>
        </div>
      </a>
    </div>
  </div>
</div>

<slot />
