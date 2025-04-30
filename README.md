<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Fashion by [Your Name] </title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <header class="hero">
    <h1>Fashion by [Your Name] </h1>
    <p>Elegant. Bold. Unique. </p>
  </header>

  <nav class="navbar">
    <a href="#about">About</a>
    <a href="#portfolio">Portfolio</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about" class="about">
    <h2>About Me</h2>
<p>I’m a fashion designer passionate about creating bold, contemporary styles that reflect individuality and confidence. Welcome to my design world. </p>
  </section>

  <section id="portfolio" class="portfolio">
    <h2>Portfolio</h2>
    <div class="gallery">
      <img src="https://via.placeholder.com/300x400" alt="Design 1">
      <img src="https://via.placeholder.com/300x400" alt="Design 2">
      <img src="https://via.placeholder.com/300x400" alt="Design 3">
    </div>
  </section>

  <section id="contact" class="contact">
    <h2>Contact Me</h2>
    <form>
      <input type="text" placeholder="Name" required />
      <input type="email" placeholder="Email" required />
      <textarea placeholder="Message" rows="5" required></textarea>
      <button type="submit">Send</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Fashion by [Your Name]. All rights reserved. </p>
  </footer>

</body>
</html>


* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Helvetica Neue', sans-serif;
}

body {
  background-color: #fff;
  color: #333;
  line-height: 1.6;
}

.hero {
  background: url('https://via.placeholder.com/1200x600') center/cover no-repeat;
  color: white;
  text-align: center;
  padding: 100px 20px;
}

.hero h1 {
  font-size: 3em;
}

.navbar {
  display: flex;
  justify-content: center;
  background-color: #111;
}

.navbar a {
  color: white;
  padding: 15px 20px;
  text-decoration: none;
}

.navbar a:hover {
  background-color: #555;
}

.about, .portfolio, .contact {
  padding: 60px 20px;
  text-align: center;
}

.gallery {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 20px;
}

.gallery img {
  width: 300px;
  height: 400px;
  object-fit: cover;
  border-radius: 8px;
}

form {
  max-width: 500px;
  margin: auto;
  display: flex;
  flex-direction: column;
  gap: 15px;
}

form input, form textarea {
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 5px;
}

form button {
  padding: 10px;
  border: none;
  background-color: #111;
  color: white;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

form button:hover {
  background-color: #555;
}

footer {
  background-color: #111;
  color: white;
  text-align: center;
  padding: 20px;
}
