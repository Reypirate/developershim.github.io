<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Justin Bieber Fanpage 💜</title>
  <style>
    body {
      margin: 0;
      background: #c0c0c0; /* Classic Mac gray */
      font-family: 'Chicago', 'Geneva', sans-serif;
      scroll-behavior: smooth;
      cursor: url('https://cur.cursors-4u.net/cursors/cur-2/cur114.cur'), auto; /* Retro Mac cursor */
      overflow-x: hidden;
    }

    /* Mouse trail dots */
    .trail {
      position: fixed;
      width: 12px;
      height: 12px;
      background: rgba(255, 255, 255, 0.8);
      border: 2px solid #000;
      border-radius: 50%;
      pointer-events: none;
      animation: fadeOut 1s forwards;
      z-index: 9999;
    }
    @keyframes fadeOut {
      to { transform: scale(0); opacity: 0; }
    }

    /* Mac-style top menu bar */
    .menubar {
      position: fixed;
      top: 0;
      width: 100%;
      background: #e0e0e0;
      border-bottom: 2px solid #888;
      padding: 5px 15px;
      display: flex;
      justify-content: flex-start;
      gap: 20px;
      font-size: 14px;
      z-index: 1000;
    }

    .menubar a {
      text-decoration: none;
      color: black;
      transition: 0.2s;
    }
    .menubar a:hover {
      background: #000080;
      color: white;
      padding: 2px 6px;
      border-radius: 3px;
      transform: scale(1.1);
    }

    /* Mac window style */
    .window {
      margin: 100px auto;
      max-width: 800px;
      background: #fff;
      border: 2px solid #000;
      box-shadow: 3px 3px #555;
      padding: 15px;
      transition: transform 0.3s ease;
    }
    .window:hover {
      transform: scale(1.02);
    }

    .titlebar {
      background: linear-gradient(#dcdcdc, #b0b0b0);
      padding: 5px;
      border-bottom: 2px solid #888;
      display: flex;
      justify-content: space-between;
      align-items: center;
      font-weight: bold;
    }

    .content {
      padding: 20px;
      text-align: center;
    }

    /* Gallery */
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 15px;
    }
    .gallery img {
      width: 100%;
      border: 2px solid #000;
      box-shadow: 2px 2px #555;
      transition: transform 0.4s ease, filter 0.3s ease;
    }
    .gallery img:hover {
      transform: rotate(-3deg) scale(1.1);
      filter: brightness(1.2);
    }

    iframe {
      width: 80%;
      max-width: 600px;
      height: 340px;
      border: 2px solid #000;
      box-shadow: 2px 2px #555;
      margin-top: 20px;
      transition: transform 0.4s;
    }
    iframe:hover {
      transform: scale(1.05);
    }

    footer {
      margin: 50px 0;
      text-align: center;
      font-size: 14px;
    }
  </style>
</head>
<body>

  <!-- Menu Bar -->
  <div class="menubar">
    <a href="#hero">Apple</a>
    <a href="#gallery">File</a>
    <a href="#albums">Edit</a>
    <a href="#videos">Special</a>
    <a href="#footer">Help</a>
  </div>

  <!-- Hero Window -->
  <div class="window" id="hero">
    <div class="titlebar">
      <span>✨ Justin Bieber Forever ✨</span>
      <span>◻︎ ◼︎ ◾</span>
    </div>
    <div class="content">
      <h2>Beliebers are forever loyal 💜</h2>
      <img src="https://wallpapercrafter.com/desktop2/751784-justin-bieber-famous-singer-handsome-white-skin.jpg" alt="Justin Bieber" width="300">
    </div>
  </div>

  <!-- Gallery Window -->
  <div class="window" id="gallery">
    <div class="titlebar">
      <span>📸 Gallery</span>
      <span>◻︎ ◼︎ ◾</span>
    </div>
    <div class="content">
      <div class="gallery">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQMSZCwEb-JmYgWKwTl0-jbZnEfAsogCpiBgQ&s" alt="Justin 1">
        <img src="https://people.com/thmb/CRbK2g33oaTNI7Y9nDuO_7s3Nu4=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():focal(749x0:751x2)/justin-bieber-1-fb959de5e2504823b3feffd098f2b401.jpg" alt="Justin 2">
        <img src="https://people.com/thmb/itt_VTN8Bi1Nl7aMu2vuADH_kis=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():focal(337x360:339x362)/Justin-Bieber-Cuddles-Baby-Jack-040625-d6644471d4c248dcbb26f8eeaea76def.jpg" alt="Justin 3">
      </div>
    </div>
  </div>

  <!-- Albums Window -->
  <div class="window" id="albums">
    <div class="titlebar">
      <span>🎶 Albums</span>
      <span>◻︎ ◼︎ ◾</span>
    </div>
    <div class="content">
      <p>From <i>My World</i> to <i>Justice</i>, his music continues to inspire 💜</p>
      <ul style="list-style:none; font-size:1.2rem; padding:0;">
        <li>2009 - My World</li>
        <li>2010 - My World 2.0</li>
        <li>2012 - Believe</li>
        <li>2015 - Purpose</li>
        <li>2021 - Justice</li>
      </ul>
    </div>
  </div>

  <!-- Videos Window -->
  <div class="window" id="videos">
    <div class="titlebar">
      <span>🎥 Music Videos</span>
      <span>◻︎ ◼︎ ◾</span>
    </div>
    <div class="content">
      <p>Watch some of Justin’s iconic hits:</p>
      <iframe src="https://www.youtube.com/embed/kffacxfA7G4" allowfullscreen></iframe>
      <iframe src="https://www.youtube.com/embed/8EJ3zbKTWQ8" allowfullscreen></iframe>
    </div>
  </div>

  <!-- Footer -->
  <footer id="footer">
    💜 Made with love by a true Belieber 💜  
    <br> Styled like Mac OS 9 ✨
  </footer>

  <script>
    // Mouse trail effect
    document.addEventListener("mousemove", function(e) {
      let trail = document.createElement("div");
      trail.className = "trail";
      document.body.appendChild(trail);
      trail.style.left = (e.pageX - 6) + "px";
      trail.style.top = (e.pageY - 6) + "px";
      setTimeout(() => {
        trail.remove();
      }, 1000);
    });
  </script>
</body>
</html>
