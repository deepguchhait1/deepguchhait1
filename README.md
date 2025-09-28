<p align="center">
      <img src="https://i.pinimg.com/originals/90/70/32/9070324cdfc07c68d60eed0c39e77573.gif" height="200px" />
    </p>
<h1 align="center">Hi 👋, I'm Deep Guchhait</h1>
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=deepguchhait1&label=Profile%20Views&color=0e75b6&style=flat" alt="Profile Views" />
  <img src="https://img.shields.io/github/followers/deepguchhait1?label=Followers&style=flat&color=blue" alt="GitHub Followers" />
  <img src="https://img.shields.io/github/stars/deepguchhait1?label=Stars&style=flat&color=yellow" alt="GitHub Stars" />
  <img src="https://img.shields.io/badge/commits%20this%20month-50+-red?style=flat" alt="Monthly Commits" />
</p>
<h3 align="center">🚀 MERN Stack Developer | Backend Enthusiast | Open Source Explorer</h3>

---

### 👨‍💻 About Me
<div align="center">
  <img src="https://mir-s3-cdn-cf.behance.net/project_modules/max_1200/79731568097599.5b50bca477735.jpg" alt="coding-gif" width="100%" style="max-width: 700px; border-radius: 10px;" />
</div>
<br>

```js
// Import Express
const express = require("express");
const app = express();
const PORT = 5000;

// Developer Class
class Developer {
  constructor() {
    this.name = "Deep Guchhait";
    this.role = "3rd Year Student & Developer";
    this.languages = ["JavaScript", "C++","Python", "Java"];
    this.speaks = ["Bengali", "English", "Hindi"];
    this.focus = "MERN";
    this.interests = ["Web Security", "System Design", "Soket.io","JWT"];
  }

  hello() {
    return "Thanks for visiting! Let's build something amazing 🚀";
  }

  projects() {
    return [
      "Scalable Microservices",
      "Pentesting Tools",
      "CI/CD Automation",
      "3D Web Interfaces"
    ];
  }
}

// Create instance
const dev = new Developer();

// Routes
app.get("/", (req, res) => {
  res.send(dev.hello());
});

app.get("/about", (req, res) => {
  res.json({
    name: dev.name,
    role: dev.role,
    languages: dev.languages,
    speaks: dev.speaks,
    focus: dev.focus,
    interests: dev.interests,
  });
});

app.get("/projects", (req, res) => {
  res.json(dev.projects());
});

// Start Server
app.listen(PORT, () => {
  console.log(`🚀 Server running at http://localhost:${PORT}`);
});
```




---

### 🛠️ Tech Stack 
<p align="center">
  <img src="https://skillicons.dev/icons?i=mongodb,express,react,nodejs,javascript,typescript,tailwind,bootstrap,html,css,git,github,postman,python,java,php,aws,gcp" />
</p>

---

### 📊 GitHub Stats
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=deepguchhait1&layout=compact&theme=radical" alt="Top Languages" />
  
</p>

---

## 🐍 Contribution Graph


<div align="center">
  <img src="https://github.com/Platane/snk/raw/output/github-contribution-grid-snake.svg" alt="Snake animation" />
</div>


### 🌐 Connect with Me
<p align="center">
  <a href="https://www.linkedin.com/in/deepguchhait/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:deepguchhait01@gmail.com" target="_blank">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://github.com/deepguchhait1" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

<br>

<div align="center">
  <img height="120" alt="Thanks for visiting me" width="100%" src="https://raw.githubusercontent.com/BrunnerLivio/brunnerlivio/master/images/marquee.svg" />
</div>
