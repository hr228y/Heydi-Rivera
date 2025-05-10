<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Heydi Rivera</h1>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#resume">Resume</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="home">
    <h2>Welcome to My Portfolio</h2>
    <p>Introduction about yourself.</p>
  </section>

  <section id="about">
    <h2>About Me</h2>
    <p>Your skills, experiences, and educational background.</p>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <ul>
      <li><a href="https://github.com/yourusername/project1">Project 1</a></li>
      <li><a href="https://github.com/yourusername/project2">Project 2</a></li>
    </ul>
  </section>

  <section id="resume">
  <h2>Resume</h2>
 <a href="Heydi-Rivera.pdf" download>Download my resume</a>
</section>

  
## 🤖 Chatbot Feature

This portfolio includes a simple chatbot that responds to questions about my skills, experience, and projects.

**🔧 Built With:**  
- JavaScript + [BotUI](https://botui.org/) (or replace with Dialogflow if you used it)
- Code is in `chatbot.js`

**📍 Location on site:**  
Appears on the homepage and other sections for interactive Q&A.

**🔗 Live Site:**  
[https://hr228y.github.io/portfolio](https://hr228y.github.io/portfolio)
<div class="chatbot-container" id="chatbot">
  <div class="chat-header">Chat with Me!</div>
  <div class="chat-box" id="chat-box"></div>
  <input type="text" id="user-input" placeholder="Ask something..." />
  <button onclick="sendMessage()">Send</button>
</div>


  <section id="contact">
    <h2>Contact Me</h2>
    <form>
      <label for="name">Your Name</label>
      <input type="text" id="name" name="name" required>
      <label for="message">Your Message</label>
      <textarea id="message" name="message" required></textarea>
      <button type="submit">Send</button>
    </form>
  </section>

 


