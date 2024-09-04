<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Profile</title>
  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Lato:wght@400;700&family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">
  
  <!-- Custom Styles -->
  <style>
    body {
      font-family: 'Roboto', sans-serif;
      background-color: #f4f4f9;
      color: #333;
      margin: 0;
      padding: 0;
      font-size: 1rem;
      line-height: 1.6;
    }
    
    h1, h2 {
      font-family: 'Lato', sans-serif;
    }

    h1 {
      font-size: 2.5em;
    }

    h2 {
      font-size: 2em;
      margin-bottom: 0.5em;
    }

    p {
      font-size: 1.2em;
      margin: 0.5em 0;
    }

    .icon {
      margin: 0 10px;
      transition: transform 0.2s ease-in-out;
    }

    .icon:hover {
      transform: scale(1.2);
    }

    .section:nth-child(even) {
      background-color: #f9f9f9;
    }

    .section {
      padding: 2em 0;
      margin-bottom: 1em;
    }

    .profile-container {
      text-align: center;
      margin-top: 2em;
    }

    .profile-container img {
      border-radius: 50%;
      box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1);
    }

    footer {
      background-color: #333;
      color: white;
      padding: 1em 0;
      text-align: center;
    }

    footer a {
      color: white;
      margin: 0 10px;
      text-decoration: none;
    }

    footer a:hover {
      text-decoration: underline;
    }

    /* Dark mode */
    .dark-mode {
      background-color: #333;
      color: white;
    }

    .dark-mode a {
      color: #4caf50;
    }

    /* Responsive Design */
    @media (max-width: 768px) {
      h1 {
        font-size: 1.5em;
      }

      .section {
        padding: 1em;
      }

      img {
        width: 80px;
      }
    }
  </style>
</head>
<body>

  <!-- Profile Section -->
  <div class="profile-container">
    <img src="img/photo2.jpg" width="128">
    <h1>Data Science Consultant | Machine Learning Expert</h1>
    <p>I'm a seasoned data science consultant based in Washington, D.C. I bring over two decades of data analysis, data science, and machine learning expertise. My background as a senior researcher at Mitsubishi Research Institute in Tokyo has equipped me with the skills to drive impactful projects across diverse domains.</p>
  </div>

  <!-- Contact Section -->
  <div style="text-align: center; margin-top: 2em;">
    <a href="https://github.com/shrmtmt">
      <img src="img/github-icon.png" width="32" class="icon">
    </a>
    <a href="https://www.linkedin.com/in/srmtmt/">
      <img src="img/linkedin-icon.png" width="32" class="icon">
    </a>
    <a href="https://medium.com/@shrmtmt">
      <img src="img/medium-icon.png" width="32" class="icon">
    </a>
    <a href="https://www.facebook.com/shiromatz">
      <img src="img/facebook-icon.png" width="32" class="icon">
    </a>
    <a href="https://twitter.com/shrmtmt">
      <img src="img/twitter-icon.png" width="32" class="icon">
    </a>
  </div>

  <!-- Achievements Section -->
  <div class="section">
    <h2>Recent Achievements</h2>
    <ul>
      <li>Led ML-driven demand forecasting projects in the railroad and food distribution industries, resulting in hundreds of millions of dollars in increased sales and cost savings.</li>
      <li>Pioneered a deep learning and NLP-based model that predicted employability from applicant resumes, elevating the market share of a human resource company to become the industry leader in Japan.</li>
      <li>Streamlined operations at an international logistics container yard by building a DL and NLP model that predicts the removal time of imported goods, significantly reducing costs.</li>
      <li>Developed an innovative solution to extract critical information from high-resolution images of items stacked on pallets using edge devices and cloud servers, leading to substantial resource and cost savings.</li>
    </ul>
  </div>

  <!-- Career Section -->
  <div class="section">
    <h2>Career</h2>
    <ul>
      <li>Independent Consultant, Washington D.C. & Tokyo (2022-)</li>
      <li>Senior Researcher, Mitsubishi Research Institute, Tokyo (2010-2022)</li>
      <li>Researcher, Mitsubishi Research Institute, Tokyo (2002-2010)</li>
      <li>Assistant Manager, Houseplus Housing Warranty Corporation (secondment) (1999-2002)</li>
      <li>Junior Researcher, Mitsubishi Research Institute, Tokyo (1997-1999)</li>
    </ul>
  </div>

  <!-- Dark Mode Toggle -->
  <div style="text-align: center; margin-top: 2em;">
    <button onclick="toggleDarkMode()">Toggle Dark Mode</button>
  </div>

  <script>
    function toggleDarkMode() {
      document.body.classList.toggle('dark-mode');
    }
  </script>

  <!-- Footer Section -->
  <footer>
    <p>&copy; 2024 Shiro Matsumoto</p>
    <div>
      <a href="https://github.com/shrmtmt">GitHub</a>
      <a href="https://www.linkedin.com/in/srmtmt/">LinkedIn</a>
      <a href="https://medium.com/@shrmtmt">Medium</a>
      <a href="https://www.facebook.com/shiromatz">Facebook</a>
      <a href="https://twitter.com/shrmtmt">Twitter</a>
    </div>
  </footer>

</body>
</html>
