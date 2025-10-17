<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Portfolio - KL Student</title>
  <style>
    /* Global Styles */
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
    }

    body {
      line-height: 1.6;
      background-color: #f4f4f4;
      color: #333;
    }

    header, section, footer {
      padding: 20px;
      max-width: 1200px;
      margin: auto;
    }

    header {
      background: #007bff;
      color: #fff;
      text-align: center;
    }

    header h1 {
      font-size: 2rem;
    }

    header p {
      font-size: 1.1rem;
      margin-top: 8px;
    }

    /* Layout Container */
    .container {
      display: flex;
      gap: 20px;
      margin-top: 20px;
    }

    /* About Section */
    .about {
      flex: 1;
      background: #fff;
      padding: 20px;
      border-radius: 8px;
    }

    /* Projects Section */
    .projects {
      flex: 2;
      background: #fff;
      padding: 20px;
      border-radius: 8px;
    }

    .projects h2 {
      margin-bottom: 10px;
    }

    .project-card {
      background: #e9ecef;
      padding: 15px;
      border-radius: 5px;
      margin-bottom: 10px;
    }

    footer {
      background: #222;
      color: #fff;
      text-align: center;
      padding: 15px;
      margin-top: 20px;
    }

    /* Responsive for smaller screens */
    @media (max-width: 768px) {
      .container {
        flex-direction: column;
      }

      header h1 {
        font-size: 1.6rem;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Vyshnavi Bhavirisetty</h1>
    <p>👩‍💻 Aspiring Web Developer | KL University Student</p>
  </header>

  <div class="container">
    <section class="about">
      <h2>About Me</h2>
      <p>
        Hi! I'm Vyshnavi, a passionate learner exploring the world of web development.
        I love creating clean, responsive, and user-friendly websites.
      </p>
    </section>

    <section class="projects">
      <h2>My Projects</h2>

      <div class="project-card">
        <h3>📱 Responsive Portfolio</h3>
        <p>A simple and modern portfolio layout using HTML & CSS.</p>
      </div>

      <div class="project-card">
        <h3>🌐 Weather App</h3>
        <p>An app that shows live weather updates using an API.</p>
      </div>

      <div class="project-card">
        <h3>💻 To-Do List</h3>
        <p>A minimal task manager built with JavaScript.</p>
      </div>
    </section>
  </div>

  <footer>
    <p>© 2025 Vyshnavi Bhavirisetty | KL University</p>
  </footer>

</body>
</html>
