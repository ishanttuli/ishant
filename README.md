<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Ishant | Designer Portfolio</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }
    body {
      background-color: #fdfdfd;
      color: #333;
      line-height: 1.6;
    }
    header {
      background: #ffffff;
      padding: 2rem 1rem;
      text-align: center;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    }
    header h1 {
      font-size: 2.5rem;
    }
    header p {
      font-size: 1.2rem;
      color: #777;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 2rem;
      background-color: #fafafa;
      padding: 1rem 0;
      position: sticky;
      top: 0;
      z-index: 10;
    }
    nav a {
      text-decoration: none;
      color: #333;
      font-weight: bold;
    }
    nav a:hover {
      color: #0077ff;
    }
    section {
      padding: 3rem 2rem;
      max-width: 900px;
      margin: auto;
    }
    .portfolio-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5rem;
      margin-top: 1rem;
    }
    .project-card {
      background: #fff;
      padding: 1rem;
      border: 1px solid #eee;
      box-shadow: 0 2px 5px rgba(0,0,0,0.05);
      border-radius: 8px;
      transition: transform 0.3s ease;
    }
    .project-card:hover {
      transform: scale(1.03);
    }
    footer {
      text-align: center;
      padding: 2rem;
      color: #aaa;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Ishant</h1>
    <p>Creative Designer</p>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#about">About Me</a>
    <a href="#portfolio">Portfolio</a>
  </nav>

  <section id="home">
    <h2>Welcome</h2>
    <p>Hello! I'm Ishant, a passionate designer who loves turning ideas into visual stories. Explore my work below!</p>
  </section>

  <section id="about">
    <h2>About Me</h2>
    <p>I'm a creative designer with a focus on clean, user-friendly visuals. I enjoy creating logos, posters, and UI elements that make a lasting impact.</p>
  </section>

  <section id="portfolio">
    <h2>My Work</h2>
    <div class="portfolio-grid">
      <div class="project-card">
        <h3>Project One</h3>
        <p>A brief description of your design project goes here.</p>
      </div>
      <div class="project-card">
        <h3>Project Two</h3>
        <p>Add more details about this project and what tools you used.</p>
      </div>
      <div class="project-card">
        <h3>Project Three</h3>
        <p>This is where you can showcase another amazing piece of work.</p>
      </div>
    </div>
  </section>

  <footer>
    &copy; 2025 Ishant | All rights reserved.
  </footer>
</body>
</html>
