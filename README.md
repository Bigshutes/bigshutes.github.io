<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ZIPPY'S PIZZA | Pop-Up Pizza Catering</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

  <!-- Top Announcement / Banner -->
  <div class="top-banner">
    *** ZIPPY'S PIZZA - POP-UP CATERING & EVENTS ***
  </div>

  <!-- Header & Hero -->
  <header class="hero-section">
    <!-- Replace 'images/logo.png' with your actual logo image path -->
    <img src="images/logo.png" alt="Zippy's Pizza Logo" class="logo">
    <h1 class="main-title">ZIPPY'S PIZZA</h1>
    <p class="tagline">HOT. FRESH. POP-UP CATERING.</p>
  </header>

  <!-- Navigation Bar -->
  <nav class="nav-bar">
    <a href="#menu">[ MENU ]</a>
    <a href="#gallery">[ GALLERY ]</a>
    <a href="#contact">[ BOOK CATERING ]</a>
  </nav>

  <main class="container">

    <!-- Menu Section -->
    <section id="menu" class="content-box">
      <h2 class="section-title">// THE MENU</h2>
      <p class="section-desc">Handcrafted pop-up pies made on-site.</p>

      <div class="menu-grid">
        <!-- Item 1 -->
        <div class="menu-item">
          <div class="menu-header">
            <span class="item-name">CLASSIC MARGHERITA</span>
            <span class="item-price">$18</span>
          </div>
          <p class="item-desc">San Marzano tomato sauce, fresh mozzarella, basil, extra virgin olive oil.</p>
        </div>

        <!-- Item 2 -->
        <div class="menu-item">
          <div class="menu-header">
            <span class="item-name">DOUBLE PEPPERONI</span>
            <span class="item-price">$20</span>
          </div>
          <p class="item-desc">Crispy cupping pepperoni, mozzarella, hot honey drizzle, fresh oregano.</p>
        </div>

        <!-- Item 3 -->
        <div class="menu-item">
          <div class="menu-header">
            <span class="item-name">HOT GARLIC PIE</span>
            <span class="item-price">$19</span>
          </div>
          <p class="item-desc">Garlic cream base, roasted garlic cloves, chili flakes, pecorino romano.</p>
        </div>
      </div>
    </section>

    <!-- Gallery Section -->
    <section id="gallery" class="content-box">
      <h2 class="section-title">// PHOTO GALLERY</h2>
      <p class="section-desc">Scenes from our recent pop-ups.</p>

      <div class="gallery-grid">
        <!-- Replace src attributes with your actual photo filenames -->
        <div class="gallery-card">
          <img src="images/pizza1.jpg" alt="Wood-fired pizza">
          <div class="caption">Fresh out of the oven</div>
        </div>
        <div class="gallery-card">
          <img src="images/pizza2.jpg" alt="Pop-up event setup">
          <div class="caption">Pop-up setup</div>
        </div>
        <div class="gallery-card">
          <img src="images/pizza3.jpg" alt="Slicing pizza">
          <div class="caption">Crispy crust close-up</div>
        </div>
      </div>
    </section>

    <!-- Booking / Contact Section -->
    <section id="contact" class="content-box">
      <h2 class="section-title">// BOOK CATERING</h2>
      <p class="section-desc">Want Zippy's at your private event, wedding, or party?</p>
      
      <div class="contact-box">
        <p><strong>EMAIL US:</strong> <a href="mailto:info@zippyspizza.ca">info@zippyspizza.ca</a></p>
        <p><strong>INSTAGRAM:</strong> <a href="https://instagram.com" target="_blank">@zippyspizza</a></p>
      </div>
    </section>

  </main>

  <!-- Footer -->
  <footer>
    <p>&copy; 2026 ZIPPY'S PIZZA. ALL RIGHTS RESERVED.</p>
  </footer>

</body>
</html>
/* ===================================================
   ZIPPY'S PIZZA - EARLY 2000s RETRO HIGH-CONTRAST STYLE
   =================================================== */

/* Color Palette Variables */
:root {
  --bg-color: #000000;         /* Pure black background */
  --text-color: #ffffff;       /* High-contrast crisp white */
  --accent-yellow: #ffff00;    /* Classic 2000s bright yellow accent */
  --border-color: #ffffff;     /* Solid white borders */
  --card-bg: #111111;          /* Dark gray container background */
  --font-mono: 'Courier New', Courier, monospace;
  --font-sans: Arial, Helvetica, sans-serif;
}

/* Global Reset */
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  background-color: var(--bg-color);
  color: var(--text-color);
  font-family: var(--font-mono);
  line-height: 1.5;
}

/* Banner */
.top-banner {
  background-color: var(--accent-yellow);
  color: #000000;
  font-weight: bold;
  text-align: center;
  padding: 6px;
  font-size: 0.9rem;
  letter-spacing: 1px;
}

/* Header & Hero */
.hero-section {
  text-align: center;
  padding: 40px 20px 20px 20px;
}

.logo {
  max-width: 150px;
  height: auto;
  margin-bottom: 15px;
  border: 2px solid var(--border-color);
}

.main-title {
  font-family: var(--font-sans);
  font-size: 3rem;
  font-weight: 900;
  letter-spacing: 3px;
  color: var(--accent-yellow);
  text-transform: uppercase;
}

.tagline {
  font-size: 1.1rem;
  font-weight: bold;
  margin-top: 5px;
}

/* Retro Navigation Bar */
.nav-bar {
  display: flex;
  justify-content: center;
  gap: 15px;
  background-color: #222;
  padding: 12px;
  border-top: 2px solid var(--border-color);
  border-bottom: 2px solid var(--border-color);
  margin-bottom: 30px;
}

.nav-bar a {
  color: var(--accent-yellow);
  text-decoration: none;
  font-weight: bold;
  font-size: 1rem;
}

.nav-bar a:hover {
  background-color: var(--accent-yellow);
  color: #000;
}

/* Main Container */
.container {
  max-width: 900px;
  margin: 0 auto;
  padding: 0 15px 40px 15px;
}

/* Section Box Styling */
.content-box {
  background-color: var(--card-bg);
  border: 3px double var(--border-color);
  padding: 25px;
  margin-bottom: 35px;
}

.section-title {
  font-family: var(--font-sans);
  font-size: 1.8rem;
  color: var(--accent-yellow);
  border-bottom: 2px solid var(--border-color);
  padding-bottom: 5px;
  margin-bottom: 10px;
  text-transform: uppercase;
}

.section-desc {
  margin-bottom: 20px;
  font-size: 0.95rem;
}

/* Menu Grid */
.menu-grid {
  display: flex;
  flex-direction: column;
  gap: 20px;
}

.menu-item {
  border: 1px dashed var(--border-color);
  padding: 15px;
  background-color: #000;
}

.menu-header {
  display: flex;
  justify-content: space-between;
  font-weight: bold;
  font-size: 1.1rem;
  color: var(--accent-yellow);
  margin-bottom: 5px;
}

.item-desc {
  font-size: 0.9rem;
  color: #ccc;
}

/* Gallery Grid */
.gallery-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 15px;
}

.gallery-card {
  border: 2px solid var(--border-color);
  background-color: #000;
  padding: 8px;
  text-align: center;
}

.gallery-card img {
  width: 100%;
  height: 200px;
  object-fit: cover;
  border: 1px solid #444;
}

.caption {
  font-size: 0.85rem;
  margin-top: 6px;
  color: var(--accent-yellow);
}

/* Contact Box */
.contact-box {
  border: 2px solid var(--border-color);
  padding: 15px;
  background-color: #000;
  font-size: 1.1rem;
}

.contact-box a {
  color: var(--accent-yellow);
}

/* Footer */
footer {
  text-align: center;
  padding: 20px;
  border-top: 1px solid #333;
  font-size: 0.8rem;
  color: #888;
}
