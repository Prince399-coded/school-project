<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>School Project</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Welcome to My School Project</h1>
    <nav>
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#content">Content</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="about">
    <h2>About the Project</h2>
    <p>This is a simple website for my school project. Here, I’ll explain the purpose and details of my work.</p>
  </section>

  <section id="content">
    <h2>Project Content</h2>
    <p>Here you can add detailed information about your project, images, or videos.</p>
  </section>

  <footer>
    <p>© 2025 My School Project. All rights reserved.</p>
  </footer>
</body>
</html>
body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  margin: 0;
  padding: 0;
  background-color: #f4f4f9;
  color: #333;
}

header {
  background: #007BFF;
  color: white;
  padding: 1rem 0;
  text-align: center;
}

header h1 {
  margin: 0;
}

nav ul {
  list-style: none;
  padding: 0;
}

nav ul li {
  display: inline;
  margin: 0 10px;
}

nav ul li a {
  color: white;
  text-decoration: none;
}

section {
  padding: 2rem;
  margin: 1rem auto;
  max-width: 800px;
  background: white;
  border-radius: 8px;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

footer {
  text-align: center;
  padding: 1rem;
  background: #333;
  color: white;
}
