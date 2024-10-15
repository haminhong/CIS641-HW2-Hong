<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Hamin Hong's Portfolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #1e1e1e;
      color: #e0e0e0;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #282c34;
      padding: 20px;
      text-align: center;
      color: white;
    }
    h1 {
      font-size: 2.5rem;
      margin: 0;
    }
    nav a {
      color: #61dafb;
      text-decoration: none;
      margin: 0 10px;
      font-size: 1.2rem;
    }
    section {
      padding: 40px;
      max-width: 900px;
      margin: auto;
      background-color: #2b2b2b;
      margin-top: 20px;
      border-radius: 8px;
      box-shadow: 0 0 15px rgba(0, 0, 0, 0.6);
    }
    h2 {
      color: #61dafb;
    }
    ul {
      list-style-type: none;
      padding: 0;
    }
    li {
      padding: 8px 0;
    }
    footer {
      text-align: center;
      padding: 10px;
      background-color: #282c34;
      color: white;
      position: fixed;
      width: 100%;
      bottom: 0;
    }
    img {
      width: 100%;
      max-width: 400px;
      display: block;
      margin: 20px auto;
      border-radius: 8px;
    }
    .github-link {
      display: block;
      text-align: center;
      margin-top: 20px;
    }
    .github-link a {
      color: #61dafb;
      font-size: 1.2rem;
    }
  </style>
</head>
<body>

<header>
  <h1>Hamin Hong</h1>
  <nav>
    <a href="#about">About Me</a>
    <a href="#technical-background">Technical Background</a>
    <a href="#term-project">Term Project</a>
  </nav>
</header>

<section id="about">
  <h2>About Me</h2>
  <ul>
    <li>🏂 I love snowboarding</li>
    <li>🎮 I've been playing League of Legends for over 10 years</li>
    <li>💻 I enjoy algorithms and coding challenges</li>
  </ul>
  <img src="https://ichef.bbci.co.uk/ace/standard/976/cpsprodpb/16620/production/_91408619_55df76d5-2245-41c1-8031-07a4da3f313f.jpg.webp" alt="My Favorite Meme">
</section>

<section id="technical-background">
  <h2>Technical Background</h2>
  <p>I have worked at a data analysis company specializing in visualizing public school data for superintendents. Currently, I am with Dematic, where I focus on developing onboard software for automated vehicles.</p>
  
  <h3>Programming Languages:</h3>
  <ul>
    <li>Python: Data analysis, automation scripts, and machine learning models</li>
    <li>Java: Backend development and personal projects</li>
    <li>Delphi/Pascal: Familiar with this language used by our development team</li>
  </ul>

  <h3>Frameworks and Libraries:</h3>
  <ul>
    <li>TensorFlow and PyTorch: Used for neural network design and implementation</li>
  </ul>

  <h3>Version Control:</h3>
  <ul>
    <li>Git: Practiced branching, merging, and version control using GitHub/GitLab</li>
  </ul>

  <h3>Databases:</h3>
  <ul>
    <li>Microsoft SQL Server: Database design, query writing, and performance optimization</li>
  </ul>

  <h3>Tools and Environments:</h3>
  <ul>
    <li>Docker: For containerization and environment isolation</li>
    <li>VSCode and PyCharm: Preferred IDEs</li>
  </ul>
</section>

<section id="term-project">
  <h2>Term Project: Music Generation using VAEs</h2>
  <p>For this project, I am developing a music generation system powered by Variational Autoencoders (VAEs). The goal is to create an AI model capable of generating new, unique compositions based on input parameters such as genre, chord progressions, and tempo. The project focuses not only on generating music but also on providing users with customization options to shape the creative process.</p>
  
  <p>The system will feature real-time generation capabilities, allowing users to experiment with different musical styles dynamically. Users will also be able to save their outputs as MIDI or audio files for future use. The entire system is built with TensorFlow and PyTorch frameworks, leveraging Python for implementation. This project is a testament to my passion for algorithms and machine learning, showcasing my ability to apply these concepts creatively.</p>

  <div class="github-link">
    <a href="[INSERT_TEAM_GITHUB_PAGE_LINK]">Visit our Team's GitHub Page</a>
  </div>
</section>

<footer>
  <p>&copy; 2024 Hamin Hong. All rights reserved.</p>
</footer>

</body>
</html>
