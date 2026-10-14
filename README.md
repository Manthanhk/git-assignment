<h1 align="center">Hi 👋, I'm Manthan</h1>
<h3 align="center">A passionate developer building things that (hopefully) work</h3>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=2E9EF7&center=true&vCenter=true&width=435&lines=Full-Stack+Developer;Open+Source+Contributor;Always+Learning+New+Things" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Manthanhk&label=Profile%20Views&color=2E9EF7&style=flat" alt="profile views" />
  <a href="https://github.com/Manthanhk?tab=followers">
    <img src="https://img.shields.io/github/followers/Manthanhk?label=Followers&style=social" alt="followers" />
  </a>
</p>

---

### 🚀 About Me

- 🔭 I'm currently working on **your current project**
- 🌱 I'm currently learning **new technology / language**
- 👯 I'm looking to collaborate on **type of projects**
- 💬 Ask me about **your expertise areas**
- 📫 How to reach me: **your.email@example.com**
- ⚡ Fun fact: **something interesting about you**

---

### 🛠️ Languages & Tools

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,js,ts,react,nodejs,html,css,git,docker,linux" />
</p>

---

### 📊 GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Manthanhk&show_icons=true&theme=tokyonight&hide_border=true" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Manthanhk&layout=compact&theme=tokyonight&hide_border=true" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Manthanhk&theme=tokyonight&hide_border=true" />
</p>

---


---

## 🏆 GitHub Trophies


name: Generate GitHub Trophies

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:
  push:
    branches:
      - main

permissions:
  contents: write

jobs:
  trophies:
    runs-on: ubuntu-latest

    steps:
      - name: Generate Trophy SVG
        uses: soulteary/github-profile-trophy-action@v1.0.0
        with:
          options: "username=Manthanhk&theme=onedark&no-frame=true&no-bg=true&column=6"
          path: trophy.svg

      - name: Checkout repository
        uses: actions/checkout@v4

      - name: Commit Trophy SVG
        run: |
          mkdir -p profile
          cp trophy.svg profile/trophy.svg
          git config user.name "github-actions[bot]"
          git config user.email "41898282+github-actions[bot]@users.noreply.github.com"
          git add profile/trophy.svg
          git diff --cached --quiet || git commit -m "Update GitHub trophies"
          git push


---

### 🌐 Connect With Me

<p align="center">
  <a href="https://linkedin.com/in/yourusername" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://twitter.com/yourusername" target="_blank">
    <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" />
  </a>
  <a href="mailto:your.email@example.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://yourportfolio.com" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" />
  </a>
</p>

---

<p align="center"><i>⭐️ From <a href="https://github.com/Manthanhk">Manthanhk</a> — thanks for stopping by!</i></p>
