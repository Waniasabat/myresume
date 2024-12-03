# myresume
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>wania sabat - Resume</title>
  <!-- Link to Font Awesome CDN -->
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css" rel="stylesheet">
  <style>
    /* Resetting some default styles */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      background-color: #babeed;
      color: #000; /* Black text */
      line-height: 1.6;
      display: flex;
      justify-content: flex-start;
      padding: 0;
    }

    /* Sidebar Styling */
    nav {
      position: fixed;
      top: 0;
      left: 0;
      width: 250px;
      height: 100%;
      background-color: #c9d3f1;
      padding-top: 20px;
      box-shadow: 2px 0 10px rgba(0, 0, 0, 0.1);
      z-index: 1000;
    }

    nav ul {
      list-style: none;
      padding: 0;
    }

    nav ul li {
      margin: 20px 0;
    }

    nav ul li a {
      color: white;
      text-decoration: none;
      font-size: 18px;
      display: block;
      padding: 10px;
      transition: background-color 0.3s ease;
    }

    nav ul li a:hover {
      background-color: #4c89af;
      color: white;
    }

    /* Main Content Styling */
    .container {
      margin-left: 270px; /* Space for the sidebar */
      width: 75%;
      padding: 20px;
    }

    header {
      text-align: center;
      margin-bottom: 30px;
    }

    header h1 {
      font-size: 36px;
      margin-bottom: 10px;
      color: #0a0c0c;
    }

    header p {
      font-size: 18px;
      color: #000; /* Black text */
    }

    section {
      margin-bottom: 30px;
      padding: 20px;
      background-color: #fff;
      border-radius: 8px;
      box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
      transition: transform 0.3s ease-in-out;
    }

    section:hover {
      transform: scale(1.02);
    }

    h2 {
      font-size: 24px;
      margin-bottom: 15px;
      color: #b0b7c5;
    }

    /* Section Title Bars - Light Pink Background */
    section h2 {
      background-color: #7a9aac; /* Light pink background */
      padding: 10px;
      border-radius: 5px;
    }

    ul {
      list-style: none;
      padding: 0;
    }

    li {
      margin-bottom: 10px;
    }

    footer {
      text-align: center;
      font-size: 14px;
      color: #777;
      margin-top: 30px;
    }

    /* Social Media Icons Styling */
    .social-media {
      display: flex;
      justify-content: center;
      gap: 30px; /* Space between the icons */
    }

    .social-media a {
      text-decoration: none;
      color: #333;
      font-size: 60px; /* Larger icon size */
      transition: transform 0.3s ease;
    }

    .social-media a:hover {
      color: #4CAF50;
      transform: scale(1.2); /* Slight zoom effect on hover */
    }

    /* Smooth scrolling */
    html {
      scroll-behavior: smooth;
    }

  </style>
</head>
<body>
  <!-- Sidebar Navigation -->
  <nav>
    <ul>
      <li><a href="#header">Home</a></li>
      <li><a href="#contact-info">Contact</a></li>
      <li><a href="#social-media">Social Media</a></li>
      <li><a href="#summary">Summary</a></li>
      <li><a href="#skills">Skills</a></li>
      <li><a href="#experience">Experience</a></li>
      <li><a href="#education">Education</a></li>
    </ul>
  </nav>

  <!-- Main Content -->
  <div class="container">
    <!-- Header Section -->
    <section id="header">
      <header>
        <h1>wania sabat</h1>
        <p>Software Engineering Major | Fall Semester 2024</p>
      </header>
    </section>

    <!-- Contact Info Section -->
    <section id="contact-info">
      <h2>Contact Information</h2>
      <ul>
        <li>Email: waniasabat@gmail.com</li>
        <li>Phone: 03152694431</li>
      </ul>
    </section>

    <!-- Social Media Section with Icons Only in a Row -->
    <section id="social-media">
      <h2>Social Media</h2>
      <div class="social-media">
        <a href="https://www.linkedin.com/in/wania-sabat-215b3a2b0/" target="_blank">
          <i class="fab fa-linkedin"></i>
        </a>
        <a href="https://github.com/Waniasabat" target="_blank">
          <i class="fab fa-github"></i>
        </a>
        </a>
        <a href="https://www.instagram.com/wania_sabat/" target="_blank">
          <i class="fab fa-instagram"></i>
        </a>
        <a href="https://learn.microsoft.com/en-us/users/wania-3815/" target="_blank">
          <i class="fab fa-microsoft"></i>
        
        </a>
      </div>
    </section>

    <!-- Professional Summary Section -->
    <section id="summary">
      <h2>Professional Summary</h2>
      <p>I am a Software Engineering student with a strong interest in game development, focused on learning programming languages and game design principles. Eager to apply my skills in coding and creativity to develop engaging, interactive gaming experiences.</p>
    </section>

    <!-- Skills Section -->
    <section id="skills">
      <h2>Skills</h2>
      <ul>
        <li>HTML, CSS</li>
        <li>C/C++</li>
        <li>Problem Solving</li>
        <li>Visual Studio Code, GitHub, Scratch</li>
      </ul>
    </section>

    <!-- Work Experience Section -->
    <section id="experience">
      <h2>Work Experience</h2>
      <ul>
        <li>
          <strong>SE Major</strong> 
          <ul>
            <li>Made Menus and Calculator in C++</li>
            <li>Collaborated with cross-functional teams to deliver projects on time.</li>
            <li>Worked with Python on small projects.</li>
          </ul>
        </li>
        <li>
          <strong>Junior Web Developer</strong> 
          <ul>
            <li>Built responsive websites with HTML, CSS.</li>
          </ul>
        </li>
      </ul>
    </section>

    <!-- Education Section -->
    <section id="education">
      <h2>Education</h2>
      <ul>
        <li>  
          <strong>saint lawrence college</strong>(2022-2023)
        </li>
        <li>  
            <strong>Bachelor of Science in Software Engineering</strong> - Fast NU University (2024-2028)
          </li>

      </ul>
    </section>

    <!-- Footer Section -->
    <footer>
      <p>&copy; 2024 wania sabat | All Rights Reserved</p>
    </footer>
  </div>
</body>
</html>
