# PORTFOLIO

<!DOCTYPE html>
<html>
<head>
  <title>Tejas Dandgaval - Portfolio</title>
  <link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
  <header>
    <h1>Tejas Dandgaval</h1>
    <h2>Student of Vellore Institute of Technology</h2>
    <h3>B. Tech in Mechanical with Specialization in Computer Science</h3>
    <nav>
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>
  
  <section id="about">
    <h2>About Me</h2>
    <p>Welcome to my portfolio website. I am Tejas Dandgaval, a first-year student pursuing B. Tech in Mechanical with specialization in Computer Science at Vellore Institute of Technology. I am passionate about exploring the intersection of mechanical engineering and computer science.</p>
    <p>I have a keen interest in UI/UX design and enjoy creating visually appealing and user-friendly interfaces. Additionally, I am fascinated by the field of artificial intelligence and its potential applications.</p>
    <p>Aside from my technical pursuits, I have a creative side as well. I love sketching and find it to be a great way to express my ideas and bring them to life.</p>
    <p>In terms of programming, I have experience with Python and enjoy leveraging its power to solve problems and develop applications. I am also familiar with various flavors of Linux, which enhances my proficiency in software development and system administration.</p>
</section>

  
  <section id="projects">
    <h2>Projects</h2>
    <div class="project">
        <h3>Project 1 - Arduino Auto Lock System</h3>
        <p>In this project, the Arduino UNO is connected to the Bluetooth modem to make a working model of an automatic lock. The user can provide the system with a particular MAC address so that only those specific devices can open the lock. The door will automatically lock after 5 seconds.</p>
        <a href="https://github.com/LegitNotT/Arduino_autoLOCK">Click Here for GitHub Repository</a>
    </div>
    <div class="project">
        <h3>Project 2 - Song Recognition</h3>
        <p>In this project, a basic Python program is designed to listen to the user and play that particular song on Spotify. The program searches for the song on Spotify based on the user's input and plays it if available.</p>
        <a href="https://github.com/LegitNotT/AutoSongRecognizationSpotifyExtension">Click Here for GitHub Repository</a>
    </div>
    <div class="project">
        <h3>Project 3 - URL Opener</h3>
        <p>In this project, the user provides a particular URL. The program changes the proxy, and once the site is fully loaded, it automatically restarts the app and opens the same site until the user commands to "Stop".</p>
        <a href="https://github.com/LegitNotT/URL_opener">Click Here for GitHub Repository</a>
    </div>
</section>

# CSS
  
  <section id="contact">
    <h2>Contact Me</h2>
    <form>
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" placeholder="Your name">
      
      <label for="email">Email:</label>
      <input type="email" id="email" name="email" placeholder="Your email">
      
      <label for="message">Message:</label>
      <textarea id="message" name="message" placeholder="Your message"></textarea>
      
      <input type="submit" value="Send">
    </form>
  </section>
  
  <footer>
    <p>2023 Tejas Dandgaval. All rights reserved.</p>
  </footer>
</body>
</html>

body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

header {
  background-color: #4169e1;
  color: #fff;
  padding: 20px;
}

nav ul {
  list-style: none;
  margin: 0;
  padding: 0;
}

nav ul li {
  display: inline;
  margin-right: 20px;
}

nav ul li a {
  color: #fff;
  text-decoration: none;
}

section {
  padding: 50px;
}

.project {
  margin-bottom: 20px;
}

footer {
  background-color: #4169e1;
  color: #fff;
  padding: 20px;
  text-align: center;
}
