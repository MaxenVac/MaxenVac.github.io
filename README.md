<!doctype html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="referrer" content="no-referrer" />
    <meta http-equiv="X-Content-Type-Options" content="nosniff" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="shortcut icon" id="tab-favicon" href="favicon.png" />
    <title id="tab-title">Home</title>
    <link rel="stylesheet" href="/assets/styles/main.css?v=2" />
    <link rel="stylesheet" href="/assets/styles/themes/default.css?v=4" />
    <script src="jquery-3.7.1.min.js"></script>
  </head>
  <body class="center" onload="splashtext()">
    <div class="fixed-nav-bar">
      <div class="fixed-nav-bar-container">
        <a class="icon" href="/./"><img alt="nav" id="INImg" src="/assets/media/favicon/main.png" /></a>
      </div>
      <div class="fixed-nav-bar-right">
        <a class="navbar-link" href="/./-"><i class="fa-solid fa-gamepad navbar-icon"></i>Games</a>
        <a class="navbar-link" href="/./~"><i class="fa-solid fa-phone navbar-icon"></i>Apps</a>
        <a class="navbar-link" href="/./0"><i class="fa-solid fa-laptop navbar-icon"></i>Tabs</a>
        <a class="navbar-link" href="/./!"><i class="fa-solid fa-gear navbar-icon settings-icon"></i>Settings</a>
      </div>
    </div>
    <div id="particles-js">
      <script rel="preload" src="https://cdn.jsdelivr.net/particles.js/2.0.0/particles.min.js"></script>
      <div class="main">
        <h1 class="title">Interstellar</h1>
        <p id="splash">Unknown</p>
        <div class="search-container">
          <form id="fs" method="POST">
            <input id="is" class="main-search" placeholder="Search with Google or enter address" type="text" />
          </form>
        </div>
        <!--- <div class="sug">
          <div class="sugelement" onclick="blank('https://google.com/')">Google</div></a><div class="sugelement" onclick="blank('https://youtube.com/')">Youtube</div></a> <div class="sugelement" onclick="blank('https://play.geforcenow.com')">GeForce</div></a> <div onclick="blank('https://now.gg/play/roblox-corporation/5349/roblox')" class="sugelement">Roblox</div>
        </div> --->
      </div>
    </div>
    <script src="/assets/scripts/home.js?v=4"></script>
    <script src="assets/scripts/index.js?v=5"></script>
    <script src="./m/bundle.js"></script>
    <script src="./m/config.js"></script>
    <script src="https://kit.fontawesome.com/1237c86ba0.js" crossorigin="anonymous"></script>
    <script async src="https://www.googletagmanager.com/gtag/js?id=G-WKJQ5QHQTJ"></script>
    <script>
      window.dataLayer = window.dataLayer || []

      function gtag() {
        dataLayer.push(arguments)
      }
      gtag('js', new Date())
      gtag('config', 'G-WKJQ5QHQTJ')
    </script>
    <script src="/assets/scripts/global.js?v=6"></script>
    <script src="/assets/scripts/settings.js?v=1"></script>
  </body>
</html>
