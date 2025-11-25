<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Udhay Sapkal - Portfolio</title>

  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;800&display=swap" rel="stylesheet" />

  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: "Poppins", sans-serif;
      background: #0d0d0d;
      color: #ffffff;
      line-height: 1.6;
    }

    /* Center Container */
    .container {
      width: 90%;
      max-width: 900px;
      margin: auto;
      padding-top: 30px;
    }

    /* Animated Name */
    .animated-title {
      text-align: center;
      font-size: 50px;
      font-weight: 800;
      margin-top: 40px;
      background: linear-gradient(90deg, #ff8c00, #ff0077, #6a5acd);
      -webkit-background-clip: text;
      color: transparent;
      animation: glow 2s infinite alternate ease-in-out;
    }

    @keyframes glow {
      0% { text-shadow: 0 0 12px rgba(255, 0, 150, 0.4); }
      100% { text-shadow: 0 0 25px rgba(0, 150, 255, 0.9); }
    }

    .cursor {
      font-weight: bold;
      animation: blink 0.7s infinite;
    }

    @keyframes blink {
      50% { opacity: 0; }
    }

    h2 {
      margin-top: 40px;
      color: #ff9f43;
    }

    .section {
      background: #1a1a1a;
      padding: 20px;
      border-radius: 10px;
      margin-top: 15px;
      box-shadow: 0px 0px 10px rgba(255, 255, 255, 0.08);
    }

    ul {
      margin: 0;
      padding-left: 20px;
    }

    a {
      color: #ffbe76;
      font-weight: 600;
      text-decoration: none;
    }

    a:hover {
      color: #f0932b;
    }
  </style>
</head>
<body>

  <!-- Animated Title -->
  <h1 class="animated-title">
    <span id="typing"></span><span class="cursor">|</span>
  </h1>

  <script>
    const text = "👋 Hi, I'm Udhay Sapkal";
    let index = 0;

    function typeEffect() {
      const typingElement = document.getElementById("typing");
      typingElement.innerHTML = text.slice(0, index);
      index++;

      if (index <= text.length) {
        setTimeout(typeEffect, 120);
      }
    }

    setTimeout(typeEffect, 500);
  </script>

  <div class="container">

    <!-- About Me -->
    <h2>🌐 About Me</h2>
    <div class="section">
      Motivated and detail-oriented tech enthusiast skilled in
      <strong>full-stack development, software testing, API testing, and cloud applications</strong>.
      I focus on writing clean code, building useful real-world projects, and improving my technical abilities.
    </div>

    <!-- Tech Stack -->
    <h2>🛠 Tech Stack</h2>
    <div class="section">
      <strong>Languages:</strong> C++, C#, Java, JavaScript, SQL <br>
      <strong>Web:</strong> HTML5, CSS3, Angular, React, .NET 8, Node.js, Bootstrap <br>
      <strong>Databases & Cloud:</strong> MySQL, AWS S3 <br>
      <strong>Testing & QA:</strong> Manual Testing, API Testing (Postman) <br>
      <strong>Tools:</strong> VS Code, Git, Swagger, Postman, Maven
    </div>

    <!-- Projects -->
    <h2>📌 Projects</h2>

    <div class="section">
      <h3>1. AWS S3 Cloud Storage Web App</h3>
      Full CRUD cloud application using AWS S3 buckets.  
      <strong>Tech:</strong> J2EE, Spring, JDBC, Maven, MySQL, HTML, CSS, Bootstrap
    </div>

    <div class="section">
      <h3>2. Full-Stack Contacts Application</h3>
      CRUD contact management website using Angular + ASP.NET Core Web API.  
      <strong>Tech:</strong> Angular 17, .NET 8, Tailwind CSS
    </div>

    <div class="section">
      <h3>3. Amazon Homepage Clone</h3>
      A pixel-perfect responsive clone of Amazon’s UI.  
      <strong>Tech:</strong> HTML, CSS
    </div>

    <div class="section">
      <h3>4. Personal Portfolio Website</h3>
      Your personal responsive portfolio showcasing all your work.  
      <strong>Tech:</strong> HTML, CSS, JavaScript, Bootstrap
    </div>

    <div class="section">
      <h3>5. JavaScript Calculator</h3>
      Fully functional arithmetic calculator built with vanilla JS.  
      <strong>Tech:</strong> HTML, CSS, JavaScript
    </div>

    <!-- Focus -->
    <h2>🚀 What I’m Focusing On</h2>
    <div class="section">
      - Strengthening full-stack development skills <br>
      - Improving API testing & automation <br>
      - Building scalable real-world projects <br>
      - Learning DevOps, CI/CD & cloud workflows
    </div>

    <!-- Contact -->
    <h2>📫 Connect With Me</h2>
    <div class="section">
      📧 Email: <a href="mailto:udaysapkal135@gmail.com">udaysapkal135@gmail.com</a><br>
      🔗 LinkedIn: <a href="https://www.linkedin.com/in/udaysapkal15/">linkedin.com/in/udaysapkal15</a>
    </div>

    <p style="margin-top:40px; text-align:center; opacity:0.6;">
      ⭐ If you like my projects, consider starring the repos!
    </p>

  </div>

</body>
</html>
