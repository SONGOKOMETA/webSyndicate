<script>
  import "../assets/styles/navStyle.css";
  import syndicateLogo from "../assets/resources/synd-logo.png";
  import seatLogo from "../assets/resources/seat-logo.png";
</script>

<div class="nav-Wrapper">
  <div class="nav-Wrapper-Body">
    <div class="nav-Wrapper-Body-Left">
      <img src={syndicateLogo} alt="synd-logo.png" />
      <h1 id="main-Text"><a href="/">Syndicate.</a></h1>
      <nav id="sub-Text">
        <a href="/">RD13X</a>
        <a href="/">RXSK</a>
        <a href="/">PRGCO</a>
      </nav>
    </div>
    <div class="nav-Wrapper-Body-Right">
      <a href="https://seat.syndicate-alliance.net/home">
        <div class="seat-Button">
          <div class="seat-Button-Content">
            <img src={seatLogo} alt="seat-logo" />
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
