<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=KIRUBA%20SANKAR%20S&fontSize=42&fontColor=ffffff&fontAlignY=38&animation=fadeIn" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1000&color=CFD8FF&center=true&vCenter=true&width=600&lines=AI+%C2%B7+DATA+%C2%B7+FULL+STACK;Turning+data+into+decisions;Building+things+that+matter;Open+to+collaborations" alt="Typing SVG" />

<br/>

<img src="https://img.shields.io/badge/machine%20learning-2b2b40?style=flat-square" />
<img src="https://img.shields.io/badge/full%20stack-2b2b40?style=flat-square" />
<img src="https://img.shields.io/badge/open%20source-2b2b40?style=flat-square" />

</div>

<br/>

<table width="100%">
<tr>
<td width="65%" valign="top">

<div align="center">

### 🧠 ABOUT

**Turning data into decisions.**

<sub>› open to collaborations_</sub>

</div>

</td>
<td width="35%" valign="top">

<div align="center">

🎯 **ALWAYS LEARNING**

⭐ **PROBLEM SOLVER**

</div>

</td>
</tr>
</table>

<br/>

<div align="center">

### ⚙️ STACK

<img src="https://img.shields.io/badge/Python-2b2b40?style=flat-square" />
<img src="https://img.shields.io/badge/Java-2b2b40?style=flat-square" />
<img src="https://img.shields.io/badge/C-2b2b40?style=flat-square" />
<img src="https://img.shields.io/badge/React-2b2b40?style=flat-square" />
<img src="https://img.shields.io/badge/Node.js-2b2b40?style=flat-square" />
<img src="https://img.shields.io/badge/MongoDB-2b2b40?style=flat-square" />
<br/>
<img src="https://img.shields.io/badge/MySQL-2b2b40?style=flat-square" />
<img src="https://img.shields.io/badge/PostgreSQL-2b2b40?style=flat-square" />
<img src="https://img.shields.io/badge/AWS-2b2b40?style=flat-square" />
<img src="https://img.shields.io/badge/Docker-2b2b40?style=flat-square" />
<img src="https://img.shields.io/badge/Power%20BI-2b2b40?style=flat-square" />
<img src="https://img.shields.io/badge/Tableau-2b2b40?style=flat-square" />

</div>

<br/>

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/kirubasankar068-cmd)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/kirubasankar-s)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kirubasankar.s2024laids@sece.ac.in)

</div>

<br/>

---

## 💻 Featured Projects

**🍽️ Food Calorie Measurement using Machine Learning** (2025)
Engineered an ML-based system that estimates food calorie content from food images and nutritional data using image processing and classification algorithms.

**📸 Event Photo Gallery** (2025)
Built a dynamic Event Photo Gallery web app using the MERN stack — upload, store, and showcase event photos with a real-time, responsive UI.

---

## 📜 Certifications

- React — Infosys Springboard (2025)
- AWS Developer — Infosys Springboard (2025)
- Claude on Amazon Bedrock — Anthropic (2026)

---

## 🏆 Achievements

- LeetCode: Solved 69+ problems
- Skillrack: Solved 100+ problems

---

## 🐍 Contribution Snake

<img src="https://raw.githubusercontent.com/kirubasankar068-cmd/kirubasankar068-cmd/output/github-contribution-grid-snake-dark.svg" width="100%" alt="snake animation"/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,100:0f0c29&height=100&section=footer" width="100%"/>

name: generate animated snake

on:
  schedule:
    - cron: "0 */6 * * *"
  workflow_dispatch: {}
  push:
    branches: [ "main" ]

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: kirubasankar068-cmd
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
      - uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
