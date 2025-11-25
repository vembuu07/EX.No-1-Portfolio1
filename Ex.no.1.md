# Ex01 Portfolio
## Date:29/8/25
## Name - VEMBARASAN P
## REG NO - 212223220123

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
Portfolio.Html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Dhanuskarthi - Developer</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <nav class="nav-menu" aria-label="Main navigation">
    <button class="nav-button" onclick="scrollToSection('home')">Home</button>
    <button class="nav-button" onclick="scrollToSection('about')">About</button>
    <button class="nav-button" onclick="scrollToSection('skills')">Skills</button>
    <button class="nav-button" onclick="scrollToSection('projects')">Projects</button>
    <button class="nav-button" onclick="scrollToSection('contact')"> Contact</button>
  </nav>

  <main class="container">
    <header class="header" id="home">
      <div class="emoji" aria-hidden="true">Hello</div>
      <h1>Hi, I'm Sanjeev D!</h1>
      <p id="typing-text" class="subtitle">Web Developer</p>
      <div class="cta">
        <button class="button" onclick="scrollToSection('about')">About Me</button>
        <button class="button" onclick="scrollToSection('contact')">Contact</button>
      </div>
    </header>

    <section class="section" id="about" aria-labelledby="about-heading">
      <h2 id="about-heading">About Me </h2>
      <p>I'm a passionate web developer who loves creating websites and applications. I enjoy learning new technologies and solving problems with code!</p>

      <div class="projects">
        <article class="project" tabindex="0">
          <div class="emoji" aria-hidden="true">🎨</div>
          <h3>Creative Design</h3>
          <p>I love making beautiful websites</p>
        </article>

        <article class="project" tabindex="0">
          <div class="emoji" aria-hidden="true">⚡</div>
          <h3>Fast Coding</h3>
          <p>Quick and clean code solutions</p>
        </article>

        <article class="project" tabindex="0">
          <div class="emoji" aria-hidden="true">🔧</div>
          <h3>Problem Solving</h3>
          <p>Finding solutions to challenges</p>
        </article>
      </div>
    </section>

    <section class="section" id="skills" aria-labelledby="skills-heading">
      <h2 id="skills-heading">My Skills 💪</h2>
      <p>Click on any skill to see more info!</p>

      <div class="skills">
        <button class="skill">HTML</button>
        <button class="skill">CSS</button>
        <button class="skill">JavaScript</button>
        <button class="skill">Python</button>
        <button class="skill">Node.js</button>
      </div>

      <div id="skill-info" class="skill-info" hidden>
        <p id="skill-text"></p>
      </div>
    </section>

    <section class="section" id="projects" aria-labelledby="projects-heading">
      <h2 id="projects-heading">My Projects 📁</h2>

      <div class="projects">
        <article class="project" tabindex="0">
          <div class="emoji" aria-hidden="true">🌐</div>
          <h3>Personal Website</h3>
          <p>My first website built with HTML and CSS</p>
        </article>

        <article class="project" tabindex="0">
          <div class="emoji" aria-hidden="true">🛒</div>
          <h3>Shopping App</h3>
          <p>E-commerce app with JavaScript</p>
        </article>

        <article class="project" tabindex="0">
          <div class="emoji" aria-hidden="true">📱</div>
          <h3>Mobile Game</h3>
          <p>Simple game using React</p>
        </article>
      </div>
    </section>

    <section class="contact" id="contact" aria-labelledby="contact-heading">
      <h2 id="contact-heading">Let's Connect! 📞</h2>
      <p>I'd love to hear from you!</p>

      <div class="contact-info">
        <div class="contact-item">
          <div class="emoji" aria-hidden="true">📧</div>
          <p><a href="mailto:dhanuskarthi24@gmail.com">SanjeevD21@duck.com</a></p>
        </div>

        <div class="contact-item">
          <div class="emoji" aria-hidden="true">📱</div>
          <p><center><a href="tel:+91 9047385377">+91 8667215617</a></center></p>
        </div>

        <div class="contact-item">
          <div class="emoji" aria-hidden="true">📍</div>
          <p>Tamilnadu,India</p>
        </div>
      </div>

      <button class="button">Send Message</button>
    </section>
  </main>

  <footer class="footer">
    <p>Made by Sanjeev D</p>
    <p>© 2025 - Thanks for visiting!</p>
  </footer>
</body>
</html>
```
3.CSS
```


body {
  font-family: Arial, sans-serif;
  background-color: #f9f9f9;
  color: #060606;
  line-height: 1.5;
}

.container {
  max-width: 1000px;
  margin: 0 auto;
  padding: 28px;
}

.nav-menu {
  background-color: rgb(13, 9, 11);
  padding: 12px;
  text-align: center;
  box-shadow: 0 2px 5px rgba(226, 224, 224, 0.905);
  position: sticky;
  top: 0;
  z-index: 100;
}

.nav-button {
  background-color: #3498db;
  color: rgb(223, 227, 221);
  padding: 8px 14px;
  border: none;
  border-radius: 12px;
  margin: 0 6px;
  cursor: pointer;
  font-size: 14px;
}

.nav-button:hover,
.nav-button:focus {
  background-color: #020b11;
  outline: none;
  transform: translateY(-1px);
}

.header {
  background: linear-gradient(45deg, #20f70d, #04aed4);
  color: white;
  text-align: center;
  padding: 56px 20px;
  border-radius: 10px;
  margin: 20px 0 30px;
}

.header h1 {
  font-size: 48px;
  margin-bottom: 8px;
}

.subtitle {
  font-size: 20px;
  margin-bottom: 18px;
}

.cta .button {
  margin: 8px;
}
.button {
  background-color: white;
  color: #3498db;
  padding: 12px 22px;
  border: none;
  border-radius: 25px;
  font-size: 16px;
  cursor: pointer;
}

.button:hover,
.button:focus {
  background-color: #f0f0f0;
  outline: none;
  transform: translateY(-1px);
}
.section {
  background-color: white;
  padding: 28px;
  margin: 20px 0;
  border-radius: 10px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.06);
}

.section h2 {
  color: #2c3e50;
  font-size: 28px;
  margin-bottom: 14px;
}
.skills {
  display: flex;
  flex-wrap: wrap;
  gap: 12px;
  margin-top: 14px;
}

.skill {
  background-color: #3498db;
  color: white;
  padding: 10px 16px;
  border-radius: 20px;
  cursor: pointer;
  border: none;
  font-size: 14px;
}

.skill:hover,
.skill:focus {
  background-color: #2980b9;
  outline: none;
  transform: translateY(-2px);
}

.skill-info {
  margin-top: 18px;
  padding: 14px;
  background-color: #f8f9fa;
  border-radius: 6px;
}
.projects {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
  gap: 18px;
  margin-top: 18px;
}

.project {
  background-color: #ecf0f1;
  padding: 18px;
  border-radius: 8px;
  text-align: center;
  cursor: pointer;
  transition: background-color 160ms ease, transform 120ms ease;
}

.project:hover,
.project:focus {
  background-color: #d5dbdb;
  transform: translateY(-6px);
  outline: none;
}
.contact {
  background: linear-gradient(45deg, #2e302e, #0a1014);
  color: rgb(241, 243, 245);
  text-align: center;
  padding: 34px 20px;
  border-radius: 10px;
}

.contact-info {
  display: flex;
  justify-content: space-around;
  gap: 12px;
  flex-wrap: wrap;
  margin: 18px 0;
}

.contact-item p,
.contact-item a {
  color: inherit;
  text-decoration: none;
}
.footer {
  text-align: center;
  padding: 18px;
  background-color: #0ba74a;
  color: rgb(237, 232, 232);
  margin-top: 24px;
  border-radius: 6px;
}
.emoji {
  font-size: 26px;
  margin-bottom: 6px;
}
@media (max-width: 600px) {
  .header h1 {
    font-size: 32px;
  }

  .skills {
    justify-content: center;
  }

  .nav-button {
    padding: 8px 10px;

    margin: 4px 2px;
  }
}
```

## OUTPUT

<img width="1898" height="902" alt="image" src="https://github.com/user-attachments/assets/1c2dd879-21ee-4df9-8d3d-aa5f1fce9e76" />

## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
