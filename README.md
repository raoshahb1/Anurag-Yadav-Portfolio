<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Anurag Yadav – Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * {
      box-sizing: border-box;
    }
    body {
      font-family: 'Inter', sans-serif;
      background-color: #0d0d0d;
      color: #f2f2f2;
      margin: 0;
      padding: 0;
    }
    header, footer {
      text-align: center;
      padding: 2rem 1rem;
      background: #1a1a1a;
    }
    h1, h2, h3 {
      color: #ffcc00;
    }
    section {
      padding: 2rem 10%;
    }
    .contact-info a {
      color: #4ea1f3;
      text-decoration: none;
    }
    .project, .skills, .interests {
      margin-bottom: 2rem;
      background: #1a1a1a;
      padding: 1rem;
      border-radius: 10px;
    }
    input, textarea, button {
      width: 100%;
      margin: 0.5rem 0;
      padding: 0.75rem;
      border-radius: 5px;
      border: none;
      font-size: 1rem;
    }
    button {
      background-color: #ffcc00;
      color: #000;
      cursor: pointer;
    }
    .profile-photo {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      object-fit: cover;
      margin-top: 1rem;
    }
    .gallery {
      display: flex;
      overflow-x: auto;
      scroll-snap-type: x mandatory;
      gap: 1rem;
      padding: 1rem 0;
    }
    .gallery img {
      width: 300px;
      border-radius: 10px;
      scroll-snap-align: center;
      transition: transform 0.3s;
    }
    .gallery img:hover {
      transform: scale(1.05);
    }
    @media (max-width: 768px) {
      section {
        padding: 2rem 5%;
      }
      .gallery {
        flex-direction: column;
        align-items: center;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Anurag Yadav</h1>
    <p>B.Tech Computer Science Engineering Student</p>
    <p><em>"Learning, building, and evolving — one project at a time."</em></p>
    <img src="profile.jpg" alt="Anurag Yadav" class="profile-photo">
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>Hello! I’m Anurag Yadav, a dedicated and enthusiastic B.Tech student with a strong interest in technology, generative AI, and problem-solving.</p>
    <div class="interests">
      <h3>Interests</h3>
      <ul>
        <li>Programming & Generative AI</li>
        <li>Web Technologies & Design</li>
        <li>Emerging Tech: AI, IoT</li>
        <li>Open-source Collaboration</li>
        <li>Team Projects & Leadership</li>
      </ul>
    </div>
    <div class="skills">
      <h3>Skills</h3>
      <ul>
        <li>Languages: C, C++, Python, Java (basic)</li>
        <li>Web: HTML, CSS, JavaScript (beginner)</li>
        <li>Tools: Git & GitHub, VS Code</li>
        <li>Soft Skills: Communication, Teamwork, Problem-Solving</li>
      </ul>
    </div>
    <p><strong>Aspiration:</strong> To become a generative AI engineer who creates impactful tech solutions and continuously learns by working on real-world projects.</p>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="project">
      <h3>🚜 FarmoTrade</h3>
      <p>A digital platform connecting farmers directly with buyers to ensure fair trade and reduce middlemen.</p>
      <ul>
        <li>Tech Used: HTML, CSS, PHP, MySQL</li>
        <li>Features: Farmer/buyer login, product listing, direct orders, dashboard analytics</li>
        <li>Improved UI and multilingual support for better accessibility</li>
        <li>Goal: Empower farmers through agri-tech and transparency</li>
      </ul>
      <div class="gallery">
        <img src="farmotrade1.jpg" alt="FarmoTrade Screenshot 1">
        <img src="farmotrade2.jpg" alt="FarmoTrade Screenshot 2">
      </div>
    </div>
    <div class="project">
      <h3>🚌 Real-Time Bus Tracking System</h3>
      <p>A GPS-based tracking system to help students and parents view live bus locations and arrival estimates.</p>
      <ul>
        <li>Tech Used: Android, Java/Kotlin, Firebase, Google Maps API</li>
        <li>Features: Live tracking, login system, ETA display, route management</li>
        <li>Goal: Improve safety and convenience in student transportation</li>
      </ul>
      <div class="gallery">
        <img src="busapp1.jpg" alt="Bus Tracker Screenshot 1">
        <img src="busapp2.jpg" alt="Bus Tracker Screenshot 2">
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Feel free to reach out via the form below or connect on social media.</p>
    <form action="https://formspree.io/f/your-form-id" method="POST">
      <input type="text" name="name" placeholder="Your Name" required>
      <input type="email" name="email" placeholder="Your Email" required>
      <textarea name="message" placeholder="Your Message" rows="4" required></textarea>
      <button type="submit">Send Message</button>
    </form>
    <div class="contact-info">
      <p>Email: <a href="mailto:anuragyadav2480@gmail.com">anuragyadav2480@gmail.com</a></p>
      <p>Phone: <a href="tel:+919138487721">+91 9138487721</a></p>
      <p>LinkedIn: <a href="https://www.linkedin.com/in/anurag-yadav-2029ba2b0" target="_blank">Anurag Yadav</a></p>
    </div>
  </section>

  <footer>
    <p>© 2025 Anurag Yadav. All rights reserved.</p>
  </footer>
</body>
</html>
