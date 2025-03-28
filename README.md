<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Sung Jin-Woo - Solo Leveling</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header>
    <h1>Sung Jin-Woo</h1>
    <p>The Shadow Monarch from <em>Solo Leveling</em></p>
  </header>

  <nav>
    <ul>
      <li><a href="#bio">Biography</a></li>
      <li><a href="#abilities">Abilities</a></li>
      <li><a href="#gallery">Gallery</a></li>
    </ul>
  </nav>

  <section id="bio">
    <h2>Biography</h2>
    <p>Sung Jin-Woo was initially known as the weakest hunter in humanity. After a series of events, he acquired the mysterious power of a 'Player,' allowing him to level up in strength. Eventually, he became the Shadow Monarch, commanding an army of shadows.</p>
  </section>

  <section id="abilities">
    <h2>Abilities</h2>
    <ul>
      <li>Shadow Extraction</li>
      <li>Monarch's Domain</li>
      <li>Incredible Regeneration</li>
      <li>Immense Physical Strength</li>
    </ul>
  </section>

  <section id="gallery">
    <h2>Gallery</h2>
    <img src="sungjinwoo.jpg" alt="Sung Jin-Woo" width="300" />
  </section>

  <footer>
    <p>© 2025 Solo Leveling Fanpage. All rights reserved.</p>
  </footer>

  <script>
    const navLinks = document.querySelectorAll('nav a');
    navLinks.forEach(link => {
      link.addEventListener('click', function(e) {
        e.preventDefault();
        const target = document.querySelector(this.getAttribute('href'));
        window.scrollTo({
          top: target.offsetTop - 50,
          behavior: 'smooth'
        });
      });
    });
  </script>
</body>
</html>
