<!-- Modern GitHub README with Animations & Dark Mode -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Anthony Muhoro | GitHub Profile</title>
  <style>
    /* Smooth Fade-In Animation */
    @keyframes fadeIn {
      0% { opacity: 0; transform: translateY(-20px); }
      100% { opacity: 1; transform: translateY(0); }
    }

    /* Neon Text Effect */
    .neon-text {
      color: #0ef;
      text-shadow: 0 0 5px #0ef, 0 0 10px #0ef, 0 0 20px #0ef;
    }

    /* 3D Hover Effect */
    .icon:hover {
      transform: scale(1.2);
      transition: transform 0.3s ease-in-out;
    }

    /* Dark Mode Styles */
    body {
      font-family: Arial, sans-serif;
      background: linear-gradient(135deg, #1a1a2e, #16213e);
      color: white;
      text-align: center;
      animation: fadeIn 1.5s ease-in-out;
    }
    
    .container {
      max-width: 900px;
      margin: auto;
      padding: 20px;
    }

    .toggle-btn {
      background: #0ef;
      border: none;
      padding: 10px 20px;
      font-size: 16px;
      cursor: pointer;
      margin-bottom: 20px;
      border-radius: 5px;
      transition: 0.3s;
    }

    .toggle-btn:hover {
      background: #00a8ff;
    }
  </style>
</head>
<body>

  <button class="toggle-btn" onclick="toggleTheme()">Toggle Dark/Light Mode</button>

  <div class="container">
    <h1 class="neon-text">👋 Hi, I'm Anthony Muhoro</h1>
    <h3>A Passionate Fullstack Developer from Kenya</h3>

    <p>
      🔭 I’m currently working on <strong>Rental Management System</strong><br>
      🌱 I’m skilled in <strong>Next.js, React, TypeScript, Express.js, React Native</strong><br>
      👯 Open to collaborations on <strong>Fullstack Projects</strong><br>
      📫 Reach me at <a href="mailto:anthonymuhoro@gmail.com" class="neon-text">anthonymuhoro@gmail.com</a>
    </p>

    <h3>🌍 Connect with me:</h3>
    <p>
      <a href="https://linkedin.com/in/anthony-muhoro" target="_blank">
        <img class="icon" src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
      </a>
      <a href="https://dev.to/anthonymuhoro" target="_blank">
        <img class="icon" src="https://img.shields.io/badge/Dev.to-0A0A0A?style=for-the-badge&logo=dev.to&logoColor=white" />
      </a>
      <a href="https://hashnode.com/@anthonymuhoro" target="_blank">
        <img class="icon" src="https://img.shields.io/badge/Hashnode-2962FF?style=for-the-badge&logo=hashnode&logoColor=white" />
      </a>
      <a href="https://medium.com/@anthonymuhoro" target="_blank">
        <img class="icon" src="https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white" />
      </a>
    </p>

    <h3>🚀 Languages & Tools:</h3>
    <p>
      <img class="icon" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" width="40" height="40" />
      <img class="icon" src="https://cdn.worldvectorlogo.com/logos/nextjs-2.svg" width="40" height="40" />
      <img class="icon" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" width="40" height="40" />
      <img class="icon" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" width="40" height="40" />
      <img class="icon" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" width="40" height="40" />
      <img class="icon" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" width="40" height="40" />
      <img class="icon" src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" width="40" height="40" />
      <img class="icon" src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" width="40" height="40" />
      <img class="icon" src="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg" width="40" height="40" />
    </p>

    <h3>📊 GitHub Stats:</h3>
    <p>
      <img src="https://github-readme-stats.vercel.app/api?username=anthony-muhoro&show_icons=true&count_private=true&theme=radical" />
    </p>
    <p>
      <img src="https://github-readme-streak-stats.herokuapp.com/?user=anthony-muhoro&theme=tokyonight" />
    </p>
  </div>

  <script>
    function toggleTheme() {
      if (document.body.style.background.includes("1a1a2e")) {
        document.body.style.background = "white";
        document.body.style.color = "black";
      } else {
        document.body.style.background = "linear-gradient(135deg, #1a1a2e, #16213e)";
        document.body.style.color = "white";
      }
    }
  </script>

</body>
</html>
