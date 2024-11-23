<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Aditya Karki Portfolio</title>
  <style>
    /* Import Open Sans Font Locally */
@import url('https://fonts.googleapis.com/css2?family=Comfortaa:wght@300..700&family=Open+Sans:ital,wght@0,300..800;1,300..800&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&family=Source+Code+Pro:ital,wght@0,200..900;1,200..900&display=swap');
    @font-face {
      font-family: 'Open Sans';
      font-weight: normal;
      font-style: normal;
    }

    /* Global Styles */
    body {
      font-family: 'Open Sans', sans-serif;
      background-color: #181818; /* Dark background */
      color: #e0e0e0; /* Light text */
      margin: 0;
      padding: 0;
    }

    h2 {
      color: #4CAF50; /* Green for headings */
      text-align: center;
      margin-top: 20px;
    }

    .grid-container {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 20px;
      justify-content: center;
      margin: 20px auto;
      padding: 0 10px;
    }

    .grid-item {
      background: #242424; /* Dark card background */
      border: 1px solid #333; /* Border color */
      border-radius: 10px; /* Rounded corners */
      padding: 20px; /* Padding for spacing */
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.5); /* Subtle shadow */
      text-align: center;
      color: #e0e0e0; /* Light text */
    }

    a {
      color: #4CAF50; /* Green for links */
      text-decoration: none;
    }

    a:hover {
      color: #76ff03; /* Bright green on hover */
    }

    .centered {
      text-align: center;
      margin: 20px 0;
    }

    .box {
      background-color: #242424; /* Dark box color matching the theme */
      border: 1px solid #333; /* Border color */
      border-radius: 10px; /* Rounded corners */
      padding: 10px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.5); /* Subtle shadow for elevation */
      text-align: center; /* Center-align the content */
      margin: 20px auto; /* Center the box with auto margin */
      max-width: 200px; /* Limit the width of the box */
    }

    /* Code Styling */
    .styled-code {
      background-color: #242424; /* Match the theme */
      border: 1px solid #4CAF50; /* Green border for distinction */
      border-radius: 5px; /* Rounded corners */
      padding: 10px; /* Padding inside the code block */
      color: #76ff03; /* Light green text for syntax highlight effect */
      font-family: 'Courier New', monospace; /* Monospace font for code */
      font-size: 1em; /* Adjust font size for readability */
      line-height: 1.6; /* Space between lines */
      display: inline-block; /* Fit content width */
      text-align: left; /* Align text within */
    }
  </style>
</head>
<body>
  <!-- Profile Image -->
  <div class="box">
    <p align="center">
      <img src="./images/profile.jpeg" alt="Profile Picture" />
    </p>
  </div>

  <!-- About Me Section -->
  <div style="background-color: #242424; border-radius: 10px; padding: 20px; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.5); margin: 20px auto; max-width: 800px; color: #e0e0e0; font-family: 'Open Sans', sans-serif; line-height: 1.6;">
    <p align="center">
      Hi there! I'm <strong>Aditya Karki</strong>.
    </p>
    <p>
      I’m deeply interested in <strong>Machine Learning</strong>, <strong>iOS Development</strong>, and <strong>System Design</strong>. I enjoy hands-on projects that blend creativity with technical depth.
    </p>
    <center>
      <code class="styled-code">☕ Proactiveness</code>
      <code class="styled-code">🧘‍♂️ Meditation</code>
      <code class="styled-code">🏃‍♂️ Marathon</code>
      <code class="styled-code">💡 Leadership</code>
    </center>
  </div>

  <!-- Badges -->
  <p align="center">
    <img src="https://badges.pufler.dev/visits/KarkiAdit/KarkiAdit" alt="Profile Visits"/> 
    <img src="https://badges.pufler.dev/repos/KarkiAdit" alt="Repositories"/>
    <img src="https://badges.pufler.dev/commits/monthly/KarkiAdit" alt="Monthly Commits"/>
  </p>

  <!-- Technology Stack -->
  <h2>Technology Stack <img src="./images/laptop.gif" width="50"></h2>
  <p class="centered">
    <img src="https://img.shields.io/badge/-Python-black?style=flat-square&logo=python"/>
    <img src="https://img.shields.io/badge/-Go-black?style=flat-square&logo=go"/>
    <img src="https://img.shields.io/badge/-Java-black?style=flat-square&logo=java"/>
    <img src="https://img.shields.io/badge/-JavaScript-black?style=flat-square&logo=javascript"/>
    <img src="https://img.shields.io/badge/-HTML-black?style=flat-square&logo=html5"/>
    <img src="https://img.shields.io/badge/-CSS-black?style=flat-square&logo=css3"/>
    <img src="https://img.shields.io/badge/-React-black?style=flat-square&logo=react"/>
    <img src="https://img.shields.io/badge/-Node.js-black?style=flat-square&logo=node.js"/>
    <img src="https://img.shields.io/badge/-MongoDB-black?style=flat-square&logo=mongodb"/>
    <img src="https://img.shields.io/badge/-PostgreSQL-black?style=flat-square&logo=postgresql"/>
    <img src="https://img.shields.io/badge/-Google%20Cloud-black?style=flat-square&logo=google-cloud"/>
    <img src="https://img.shields.io/badge/-Docker-black?style=flat-square&logo=docker"/>
    <img src="https://img.shields.io/badge/-Kubernetes-black?style=flat-square&logo=kubernetes"/>
    <img src="https://img.shields.io/badge/-Git-black?style=flat-square&logo=git"/>
    <img src="https://img.shields.io/badge/-GitHub-black?style=flat-square&logo=github"/>
    <img src="https://img.shields.io/badge/-Figma-black?style=flat-square&logo=figma"/>
  </p>

  <!-- Contact Links -->
  <h2>Reach Me Out On <img src="https://media0.giphy.com/media/jqNPzdTTxQfOgOqpO4/source.gif" width="50"></h2>
  <p class="centered">
    <a href="mailto:adityakarki728@gmail.com">
      <img src="https://img.shields.io/badge/-karkiaditya-c14438?style=flat-square&logo=Gmail&logoColor=white" alt="Email"/>
    </a>
    <a href="https://www.linkedin.com/in/aditya-karki-2977821ab/">
      <img src="https://img.shields.io/badge/-aditya--karki-blue?style=flat-square&logo=Linkedin&logoColor=white" alt="LinkedIn"/>
    </a>
    <a href="https://www.adityakarki.com.np/">
      <img src="https://img.shields.io/badge/-Personal%20Website-black?style=flat-square&logo=internet-explorer&logoColor=white" alt="Personal Website"/>
    </a>
  </p>

  <!-- GitHub Stats -->
  <h2>My GitHub Stats <img src="https://media.giphy.com/media/VgCDAzcKvsR6OM0uWg/giphy.gif" width="50"></h2>
  <div class="grid-container">
    <div class="grid-item">
      <img src="https://github-readme-streak-stats.herokuapp.com/?user=KarkiAdit&show_icons=true&locale=en&layout=compact&theme=radical&line_height=0" alt="GitHub Streak"/>
    </div>
    <div class="grid-item">
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=KarkiAdit&hide=html,css,shaderlab,basic, jupyter notebook,hlsl&theme=radical" alt="Top Languages"/>
    </div>
  </div>
</body>
</html>
