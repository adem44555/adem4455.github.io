
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Adem Oncu – Portfolio</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #0d0d0d;
      color: #eaeaea;
    }
    a { color: #4caf50; text-decoration: none; }

    /* NAV */
    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 8%;
      background: #121212;
      position: sticky;
      top: 0;
    }
    nav h2 { margin: 0; font-size: 24px; letter-spacing: 1px; }
    nav a { margin-left: 20px; }

    /* HERO */
    .hero {
      text-align: center;
      padding: 120px 20px;
    }
    .hero h1 {
      font-size: 48px;
      margin-bottom: 10px;
    }
    .hero p {
      font-size: 20px;
      color: #b5b5b5;
    }

    /* SECTION */
    section {
      padding: 60px 10%;
      max-width: 900px;
      margin: auto;
    }
    h2 {
      font-size: 32px;
      margin-bottom: 20px;
      border-left: 5px solid #4caf50;
      padding-left: 12px;
    }

    /* PROJECT CARD */
    .project-card {
      background: #161616;
      padding: 30px;
      border-radius: 12px;
      border: 1px solid #222;
    }
    iframe {
      width: 100%;
      aspect-ratio: 16/9;
      border: none;
      margin-top: 20px;
      border-radius: 8px;
    }

    /* FOOTER */
    footer {
      padding: 40px;
      text-align: center;
      background: #121212;
      color: #777;
      margin-top: 40px;
    }
  </style>
</head>

<body>
  <nav>
    <h2>Adem Oncu</h2>
    <div>
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </div>
  </nav>

  <div class="hero">
    <h1>Game Developer</h1>
    <p>Unity • C# • Action RPG Systems • Always Learning</p>
  </div>

  <section id="about">
    <h2>About Me</h2>
    <p>
      I am <strong>Adem Oncu</strong>, a dedicated Unity game developer currently studying Game Development at UWS.
      I focus on building immersive gameplay systems such as movement, combat, and exploration.
      I'm hard-working, always on time, reliable, and constantly improving my skills.
    </p>
  </section>

  <section id="projects">
    <h2>Projects</h2>

    <div class="project-card">
      <h3>Path of Pain – Action Adventure RPG</h3>
      <p>
        <strong>Path of Pain</strong> is a semi open-world action-adventure RPG built in Unity.
        The game features core mechanics such as:
      </p>
      <ul>
        <li>Fluid character movement</li>
        <li>Melee attack and combat system</li>
        <li>World exploration mechanics</li>
        <li>Healing & health system</li>
      </ul>
      <p>
        This project strengthened my Unity programming, system design, and problem-solving abilities.
      </p>

      <iframe src="https://drive.google.com/file/d/1qbzQoxThhohVNib5cGtc3MITlE29Awem/preview" allow="autoplay; fullscreen"></iframe>
    </div>

  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Email: <a href="mailto:ademoncu07@gmail.com">ademoncu07@gmail.com</a></p>
  </section>

  <footer>
    © 2025 Adem Oncu — Portfolio
  </footer>
</body>
</html>
