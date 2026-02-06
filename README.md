/* ===== Global ===== */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Poppins', sans-serif;
}

body {
  color: #333;
  line-height: 1.6;
  background: #fafafa;
}

a {
  text-decoration: none;
  color: inherit;
}

/* ===== Navbar ===== */
nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background: #f7931e;
  padding: 12px 50px;
  flex-wrap: wrap;
}

.logo {
  display: flex;
  align-items: center;
  gap: 10px;
}

.logo img {
  height: 50px;
  width: auto;
}

.logo span {
  font-size: 1.5rem;
  font-weight: 700;
  color: #fff;
}

nav ul {
  list-style: none;
  display: flex;
  flex-wrap: wrap;
}

nav ul li {
  margin: 0 15px;
}

nav ul li a {
  color: #fff;
  font-weight: 600;
}

nav ul li a:hover, nav ul li a.active {
  text-decoration: underline;
}

/* ===== Header ===== */
header {
  height: 80vh;
  color: #fff;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  padding: 0 20px;
}

header h1 {
  font-size: 3rem;
  margin-bottom: 10px;
}

header p {
  font-size: 1.2rem;
}

.btn {
  background: #fff;
  color: #f7931e;
  padding: 10px 25px;
  border-radius: 25px;
  margin-top: 20px;
  font-weight: 600;
  transition: 0.3s ease;
}

.btn:hover {
  background: #f0f0f0;
  transform: translateY(-2px);
}

/* ===== Sections ===== */
section {
  padding: 60px 50px;
  text-align: center;
}

section h2 {
  color: #f7931e;
  font-size: 2rem;
  margin-bottom: 20px;
}

/* ===== Gallery ===== */
.gallery {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
  padding-top: 20px;
}

.gallery img {
  width: 300px;
  height: 200px;
  object-fit: cover;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.2);
  transition: transform 0.3s ease;
}

.gallery img:hover {
  transform: scale(1.05);
}

/* ===== Cards (Packages) ===== */
.packages {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
}

.card {
  background: #fff;
  border-radius: 10px;
  padding: 20px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
  width: 300px;
}

.card img {
  width: 100%;
  border-radius: 10px;
}

/* ===== Footer ===== */
footer {
  background: #111;
  color: #fff;
  text-align: center;
  padding: 25px 10px;
  font-size: 0.9rem;
}

/* ===== Responsive ===== */
@media (max-width: 768px) {
  nav {
    flex-direction: column;
    text-align: center;
  }
  nav ul {
    margin-top: 10px;
  }
  header h1 {
    font-size: 2rem;
  }
}
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Uforo Tours & Travel - Explore Zanzibar</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <nav>
    <div class="logo">
      <img src="logo.png" alt="Uforo Tours & Travel Logo">
      <span>Uforo Tours & Travel</span>
    </div>
    <ul>
      <li><a href="index.html" class="active">Home</a></li>
      <li><a href="about.html">About</a></li>
      <li><a href="packages.html">Packages</a></li>
      <li><a href="contact.html">Contact</a></li>
    </ul>
  </nav>

  <header style="background: url('https://images.unsplash.com/photo-1613514788074-9b4f7d05e8a4?auto=format&fit=crop&w=1500&q=80') no-repeat center center/cover;">
    <h1>Welcome to Zanzibar</h1>
    <p>Experience the island of spice, culture, and paradise with Uforo Tours & Travel</p>
    <a href="packages.html" class="btn">View Zanzibar Packages</a>
  </header>

  <section>
    <h2>Discover Zanzibar Tours</h2>
    <p>Explore the beauty of Zanzibar with our expert-led excursions.</p>
    <div class="gallery">
      <img src="https://images.unsplash.com/photo-1591606729070-3d48c4df5d40?auto=format&fit=crop&w=800&q=80" alt="Nungwi Beach">
      <img src="https://images.unsplash.com/photo-1614325505794-ac38c8c6ca7d?auto=format&fit=crop&w=800&q=80" alt="Stone Town">
      <img src="https://images.unsplash.com/photo-1615953004235-6a870a5280d3?auto=format&fit=crop&w=800&q=80" alt="Mnemba Atoll">
      <img src="https://images.unsplash.com/photo-1615225233491-5277f04e56cc?auto=format&fit=crop&w=800&q=80" alt="The Rock Restaurant">
    </div>
  </section>

  <footer>
    <p>&copy; 2024 Uforo Tours & Travel | Contact: <strong>+255717766384</strong> | <strong>uforotourandtravel@gmail.com</strong></p>
  </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>About Us - Uforo Tours & Travel</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <nav>
    <div class="logo">
      <img src="logo.png" alt="Uforo Tours & Travel Logo">
      <span>Uforo Tours & Travel</span>
    </div>
    <ul>
      <li><a href="index.html">Home</a></li>
      <li><a href="about.html" class="active">About</a></li>
      <li><a href="packages.html">Packages</a></li>
      <li><a href="contact.html">Contact</a></li>
    </ul>
  </nav>

  <section>
    <h2>About Uforo Tours & Travel</h2>
    <p>We are a Tanzanian-based travel agency specializing in unique Zanzibar experiences. Our passion for discovery drives us to deliver unforgettable adventures filled with beauty, culture, and connection.</p>
    <p>Whether it’s a romantic getaway, a cultural exploration, or a group excursion — we make your journey personal, safe, and memorable.</p>
  </section>

  <footer>
    <p>&copy; 2024 Uforo Tours & Travel | Contact: <strong>+255717766384</strong> | <strong>uforotourandtravel@gmail.com</strong></p>
  </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Contact - Uforo Tours & Travel</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <nav>
    <div class="logo">
      <img src="logo.png" alt="Uforo Tours & Travel Logo">
      <span>Uforo Tours & Travel</span>
    </div>
    <ul>
      <li><a href="index.html">Home</a></li>
      <li><a href="about.html">About</a></li>
      <li><a href="packages.html">Packages</a></li>
      <li><a href="contact.html" class="active">Contact</a></li>
    </ul>
  </nav>

  <section>
    <h2>Contact Us</h2>
    <p>Let's plan your next unforgettable Zanzibar experience! Reach us today:</p>
    <p>Email: <strong>uforotourandtravel@gmail.com</strong></p>
    <p>Phone: <strong>+255717766384</strong></p>
    <p>Office: 123 Sunrise Street, Zanzibar, Tanzania</p>
  </section>

  <footer>
    <p>&copy; 2024 Uforo Tours & Travel | Contact: <strong>+255717766384</strong> | <strong>uforotourandtravel@gmail.com</strong></p>
  </footer>
</body>
</html>
