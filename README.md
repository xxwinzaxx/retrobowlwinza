# retrobowlwinza
Retro Bowl For School

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <link rel="shortcut icon" href="retro bowl.jpg" type="image">
    <title>Retro Bowl | xxwinzaxx</title>
</head>
<body>

  <h2> Retro Bowl</h2>

  <div class="topnav">
    <a href="games.html">
    <button title="Games" id="Games" class="divbutton"> Games </button> 
  </a> 

    <a href="Apps.html">
    <button title="Apps" id="Apps" class="divbutton"> Apps</button>
    </a>

  <a href="index.html">
    <button title="home" id="home" class="divbutton">home</button>
  </a>

  <a href="shooter.html">
    <button title="shooter" class="divbutton">shooter</button>
  </a>

  <a href="sports.html">
    <button title="sports" class="divbutton">Sports</button>
  </a>

  <a href="cars.html">
    <button title="cars" class="divbutton">Cars</button>
  </a>
  </div>

   
    <iframe src="https://ultimateunblocked.onrender.com/games/retrobowl/index.html" class="retro-bowl-iframe"></iframe>

    <button 
    onclick="iffs('https://ultimateunblocked.onrender.com/games/retrobowl/index.html')"
     class="fullscreen"></button>
    
     <script>
      function iffs(href) {
    const iframe = document.querySelector("iframe");
    const stl = iframe.style;
    stl.border = stl.outline = 'none';
    stl.width = '100vw';
    stl.height = '100vh';
    stl.position = 'fixed';
    stl.left = stl.right = stl.top = stl.bottom = '0';
    iframe.src = href;
    }
    </script>

<script>
  document.addEventListener("keydown", 
  async (e) => { if ("`" == e.key) window.parent.window.location.replace("https://google.com/") });
</script>

</body>
</html>
