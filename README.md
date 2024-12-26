# 👋 Hi there, I'm Abdullah!  

Welcome to my GitHub profile! I'm a  
<svg width="200" height="50">
  <text x="10" y="35" font-size="24" fill="blue" font-family="Arial">
    <animate attributeName="x" from="-200" to="200" dur="2s" repeatCount="indefinite" />
    Frontend
  </text>
</svg>  
Developer passionate about creating modern web experiences.

## 🛠️ My Skills  
Here are the tools and technologies I work with:  

<div align="center">  
  <img src="https://img.shields.io/badge/HTML5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />  
  <img src="https://img.shields.io/badge/CSS3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />  
  <img src="https://img.shields.io/badge/JavaScript-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />  
  <img src="https://img.shields.io/badge/Bootstrap-%23563D7C.svg?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap" />  
  <img src="https://img.shields.io/badge/TailwindCSS-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="TailwindCSS" />  
  <img src="https://img.shields.io/badge/jQuery-%230769AD.svg?style=for-the-badge&logo=jquery&logoColor=white" alt="jQuery" />  
  <img src="https://img.shields.io/badge/Sass-%23CC6699.svg?style=for-the-badge&logo=sass&logoColor=white" alt="Sass" />  
  <img src="https://img.shields.io/badge/Angular-%23DD0031.svg?style=for-the-badge&logo=angular&logoColor=white" alt="Angular" />  
</div>

---

## 🌟 GitHub Stats  

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=abdullah7417&show_icons=true&theme=radical" alt="GitHub Stats" height="180px" />  
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=abdullah7417&theme=radical" alt="GitHub Streak" height="180px" />  
</div>  

---

## 🎯 Fun Animation  

name: Generate Snake Animation

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v2
      - uses: Platane/snk@v2
        with:
          github_user_name: abdullah7417
          outputs: dist/snake.svg
      - uses: crazy-max/ghaction-github-pages@v2.6.0
        with:
          target_branch: output
          build_dir: dist

---

## 📫 Let's Connect!  
Feel free to reach out for collaborations or just to say hi:  

- **LinkedIn**: [https://www.linkedin.com/in/abdullah-mohammed-fathy/](#)  
- **Email**: [abdullahmohamedf330@gmail.com](mailto:your.email@example.com)  

Thanks for visiting my profile! 😊  
