<script lang="ts">
    import Github from "../assets/Github.svg";
    import StackOverflow from "../assets/stackoverflow.svg";
    import Youtube from "../assets/youtube.svg";
    import Logo from "../assets/LogoOriginal.webp";
  </script>
  
  <section class="hero">
    <div class="container">
      <img src={Logo} class="logo" alt="Logo">
      <div class="info">
        <h1>Allstreamer<b class="blinker">_</b></h1>
        <h2>Hobbyist Developer</h2>
        <div class="accounts">
          <a target=”_blank” href="https://github.com/Allstreamer">
            <img src={Github} alt="Github" />
          </a>
          <a target=”_blank” href="https://stackoverflow.com/users/12520976/allstreamer">
            <img src={StackOverflow} alt="Stackoverflow" />
          </a>
          <a target=”_blank” href="https://www.youtube.com/@allstreamer_">
            <img src={Youtube} alt="Youtube" />
          </a>
        </div>
      </div>
    </div>
  </section>
  
  <style>
    .hero {
      width: 100%;
      height: 100vh;
      position: relative;
      overflow: hidden;
    }
    .logo {
      opacity: 20%;
      position: absolute;
      top: 0;
      z-index: -1;
    }
    .container {
      width: 90%;
      max-width: 1200px;
      margin: 0 auto;
      height: 100%;
  
      display: flex;
      align-items: center;
      justify-content: left;
    }
  
    .container .info h1 {
      font-size: 6rem;
      margin-bottom: 2rem;
    }
    .container .info h2 {
      font-size: 2rem;
      font-weight: 200;
  
      margin-bottom: 1rem;
    }
  
    .accounts {
      display: flex;
    }
    .accounts a img {
      width: 100px;
      opacity: 100%;
      transition: 0.1s;
    }
    .accounts a img:hover {
      width: 100px;
      opacity: 80%;
    }
  
    .blinker {
      animation: blink 4s ease-out 0s infinite normal forwards;
    }
  
    @keyframes blink {
      0%,
      50%,
      100% {
        opacity: 1;
      }
  
      25%,
      75% {
        opacity: 0;
      }
    }
  </style>
  