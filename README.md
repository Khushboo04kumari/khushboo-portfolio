# khushboo-portfolio
My personal portfolio website using HTML &amp; CSS
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Khushboo Kumari - Portfolio</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <img src="images/khushboo.jpg" alt="Khushboo Kumari" class="profile-pic"/>
    <h1>Khushboo Kumari</h1>
    <p>MCA Student | Web Developer</p>
  </header>

  <section class="about">
    <h2>About Me</h2>
    <p>
      I have completed my graduation with BCA from BRABU, Bihar.<br>
      Currently pursuing MCA from Kalinga University, Raipur, Chhattisgarh.<br>
      Passionate about learning web technologies and development.
    </p>
  </section>

  <section class="skills">
    <h2>Skills</h2>
    <ul>
      <li>HTML</li>
      <li>CSS</li>
      <li>JavaScript</li>
      <li>Python</li>
    </ul>
  </section>

  <section class="projects">
    <h2>Projects</h2>
    <ol>
      <li>Simple Calculator using HTML, CSS, JS</li>
      <li>Digital Clock with Real Time</li>
      <li>Sentiment Analysis (Python & ML)</li>
    </ol>
  </section>

  <section class="contact">
    <h2>Contact</h2>
    <p>Email: khushboo.info2003@gmail.com</p>
    <p>Phone: 9471298174</p>
  </section>

  <footer>
    <p>&copy; 2025 Khushboo Kumari. All rights reserved.</p>
  </footer>
</body>
</html>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body {
  font-family: 'Segoe UI', sans-serif;
  background: #f4f4f9;
  color: #333;
  line-height: 1.6;
  padding: 20px;
}
header {
  text-align: center;
  margin-bottom: 30px;
}
.profile-pic {
  width: 130px;
  height: 130px;
  border-radius: 50%;
  border: 3px solid #555;
  object-fit: cover;
}
h1 {
  font-size: 32px;
  margin-top: 10px;
}
h2 {
  color: #333;
  margin-bottom: 10px;
}
section {
  background: #fff;
  padding: 20px;
  margin-bottom: 20px;
  border-radius: 10px;
  box-shadow: 0 2px 6px rgba(0,0,0,0.1);
}
ul, ol {
  margin-left: 20px;
}
footer {
  text-align: center;
  margin-top: 20px;
  font-size: 14px;
}
