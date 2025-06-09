# portfolio
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sagar Vinodiya | Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Helvetica+Neue:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: url('https://assets.nflxext.com/ffe/siteui/vlv3/8f59938f-3fa0-4fd8-b65a-e5ab14c7ea1f/08eae9ef-8e54-4c07-964f-82f44928f65d/IN-en-20240520-popsignuptwoweeks-perspective_alpha_website_small.jpg') no-repeat center center fixed;
      background-size: cover;
      color: #fff;
    }

    .overlay {
      background-color: rgba(0, 0, 0, 0.85);
      min-height: 100vh;
    }

    .navbar {
      background-color: #111;
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 40px;
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    .navbar h1 {
      color: #e50914;
      font-size: 1.8rem;
      margin: 0;
    }

    .navbar ul {
      list-style: none;
      display: flex;
      gap: 20px;
      margin: 0;
      padding: 0;
    }

    .navbar a {
      text-decoration: none;
      color: #fff;
      font-weight: 500;
      transition: color 0.3s;
    }

    .navbar a:hover {
      color: #e50914;
    }

    section {
      padding: 60px 20px;
    }

    h2 {
      text-align: center;
      font-size: 2.5rem;
      color: #e50914;
      position: relative;
    }

    h2::after {
      content: "";
      width: 60px;
      height: 4px;
      background-color: #e50914;
      display: block;
      margin: 10px auto 0;
      border-radius: 2px;
    }

    #photo {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      text-align: center;
      margin-top: 40px;
    }

    #photo img {
      width: 180px;
      height: 180px;
      border-radius: 50%;
      object-fit: cover;
      border: 4px solid #e50914;
      box-shadow: 0 0 15px rgba(229, 9, 20, 0.6);
    }

    #photo p {
      margin-top: 20px;
      font-size: 1.2rem;
      max-width: 800px;
      color: #ccc;
    }

    .container {
      max-width: 1200px;
      margin: auto;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      text-align: center;
    }

    #about, #skills, #projects, #contact {
      background-color: rgba(24, 24, 24, 0.9);
      border-radius: 20px;
      margin: 40px 0;
      padding: 20px;
      width: 100%;
    }

    #about p, #contact p {
      max-width: 800px;
      margin: 0 auto;
      font-size: 1.2rem;
      line-height: 1.6;
      color: #ccc;
      text-align: center;
    }

    .skills-grid, .projects-grid {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
      padding: 20px;
    }

    .card {
      background: #1f1f1f;
      border-radius: 12px;
      padding: 25px;
      width: 250px;
      text-align: center;
      box-shadow: 0 4px 12px rgba(0,0,0,0.4);
      transition: transform 0.3s, box-shadow 0.3s;
    }

    .card:hover {
      transform: scale(1.05);
      box-shadow: 0 6px 16px rgba(229, 9, 20, 0.5);
    }

    .card h4 {
      margin-bottom: 10px;
      color: #e50914;
    }

    .card p {
      font-size: 1rem;
      color: #ccc;
    }

    #contact form {
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 15px;
      padding: 20px;
    }

    #contact input, #contact textarea {
      width: 90%;
      max-width: 600px;
      padding: 10px;
      border: none;
      border-radius: 8px;
      background: #333;
      color: #fff;
    }

    #contact button {
      padding: 10px 20px;
      background: #e50914;
      border: none;
      border-radius: 8px;
      color: #fff;
      font-weight: bold;
      cursor: pointer;
      transition: background 0.3s;
    }

    #contact button:hover {
      background: #ff0a16;
    }

    footer {
      background: #111;
      color: #666;
      text-align: center;
      padding: 20px 10px;
      font-size: 0.9rem;
    }

    @media screen and (max-width: 768px) {
      .skills-grid, .projects-grid {
        flex-direction: column;
        align-items: center;
      }
    }
  </style>
</head>
<body>
  <div class="overlay">
    <nav class="navbar">
      <h1>Portfolio</h1>
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
        <li><a href="https://github.com/sagarvinodiya" target="_blank">GitHub</a></li>
        <li><a href="https://linktr.ee/sagarvinodiya" target="_blank">Linktree</a></li>
      </ul>
    </nav>

    <section id="photo">
      <img src="WhatsApp Image 2024-06-03 at 11.33.44 PM.jpeg" alt="Sagar Vinodiya">
      <p>Hi, I'm Sagar Vinodiya, an aspiring full-stack developer and electronics engineer passionate about turning innovative ideas into impactful digital experiences.</p>
    </section>

    <section id="about" class="container">
      <h2>About Me</h2>
      <p>I'm a final-year BTech student at SB Jain College of Engineering, specializing in Electronics & Telecommunication. With a strong foundation in Java, Python, SQL, and Streamlit, I build practical, user-friendly systems — from IoT water monitors to full-stack web apps. I thrive on solving real-world problems with clean code and smart design.</p>
    </section>

    <section id="skills" class="container">
      <h2>Skills</h2>
      <div class="skills-grid">
        <div class="card">
          <h4>Languages</h4>
          <p>Java, Python, SQL, VHDL</p>
        </div>
        <div class="card">
          <h4>Frameworks/Tools</h4>
          <p>Streamlit, MySQL, Bootstrap</p>
        </div>
        <div class="card">
          <h4>Concepts</h4>
          <p>Data Visualization, DB Design</p>
        </div>
        <div class="card">
          <h4>Platforms</h4>
          <p>NodeMCU, Raspberry Pi Pico W</p>
        </div>
        <div class="card">
          <h4>AI & Other</h4>
          <p>Circuit Sim, NLP, AI Chatbots</p>
        </div>
        <div class="card">
          <h4>Soft Skills</h4>
          <p>Teamwork, Communication</p>
        </div>
      </div>
    </section>

    <section id="projects" class="container">
      <h2>Projects</h2>
      <div class="projects-grid">
        <div class="card">
          <h4>IoT Water Monitor</h4>
          <p>Monitors water quality using sensors and uploads data to the cloud.</p>
        </div>
        <div class="card">
          <h4>Phone Recommendation System</h4>
          <p>Built using Streamlit & SQL, recommends phones based on user input.</p>
        </div>
        <div class="card">
          <h4>Job Recruitment Portal</h4>
          <p>Platform for job listings, applications, and employer analytics.</p>
        </div>
        <div class="card">
          <h4>AI Chatbot</h4>
          <p>Customer support chatbot with NLP & sentiment analysis.</p>
        </div>
      </div>
    </section>

    <section id="contact" class="container">
      <h2>Contact</h2>
      <p>Want to work together or have any questions? Reach out!</p>
      <form>
        <input type="text" placeholder="Your Name" required>
        <input type="email" placeholder="Your Email" required>
        <textarea rows="4" placeholder="Your Message" required></textarea>
        <button type="submit">Send Message</button>
      </form>
    </section>

    <footer>
      &copy; 2025 Sagar Vinodiya. All rights reserved.
    </footer>
  </div>
</body>
</html>
