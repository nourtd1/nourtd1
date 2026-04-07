<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=timeGradient&height=250&section=header&text=Annour%20Mahamat%20Abdoulaye&fontSize=50&fontAlignY=35&desc=Software%20Engineer%20%7C%20App%20Creator%20%7C%20Tech%20Innovator&descAlignY=55&descAlign=50" alt="Header Banner" />
</div>

<div align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&duration=3000&pause=1000&color=3ECF8E&center=true&vCenter=true&width=600&lines=Software+Engineer+%40+ChadNova;Building+Mobile+Apps+with+React+Native;Strict+TypeScript+Advocate;Content+Creator+%26+Tech+Educator" alt="Typing SVG" />
  </a>
</div>

<p align="center">
  <em>📍 Originally from Chad | 🌍 Based in Gisenyi/Kigali, Rwanda | 🎓 3rd-year Software Engineering (ULK)</em><br>
  <b>Publishing on Google Play & App Store as: <code>Nourdevtd</code> & <code>Mahamat Abdoulaye Annour</code></b>
</p>

<br>

<div align="center">
  <a href="mailto:nourdevtd@gmail.com"><img src="https://img.shields.io/badge/Hire_Me-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://www.linkedin.com/in/annour-mahamat-abdoulaye-a799ba310"><img src="https://img.shields.io/badge/Connect_on-LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
</div>

<br>
<hr>
<br>

name: Generate Pac-Man Animation

on:
  schedule:
    # S'exécute automatiquement toutes les 24 heures
    - cron: "0 */24 * * *"
  workflow_dispatch: # Permet de le lancer manuellement
  push:
    branches:
      - main

jobs:
  generate:
    permissions:
      contents: write
    runs-on: ubuntu-latest
    timeout-minutes: 5
    steps:
      - name: Generate pacman-contribution-graph.svg
        uses: abozanona/pacman-contribution-graph@main
        with:
          github_user_name: ${{ github.repository_owner }}

      - name: Push pacman-contribution-graph.svg to the output branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
          env:
            GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

## ⚡ Executive Summary & Current Focus

I am a Software Engineer dedicated to bridging the gap between innovative ideas and production-ready applications. Working remotely as a developer for **ChadNova** (ID: CN-DEV-006), I specialize in the modern mobile and web ecosystem, building solutions that solve real-world problems in Africa and beyond.

- 🔭 **Currently Architecting:** `QuickBill`, an advanced offline-first AI invoicing mobile application.
- 📱 **Currently Scaling:** `Rently (InzuHub) v2.0`, integrating real-time audio translation and mobile money payments.
- 🌱 **Actively Learning:** Advanced Next.js rendering patterns, complex Supabase RLS policies, and Kinyarwanda.
- 💬 **Ask Me About:** React Native performance optimization, strict TypeScript implementation, and app monetization.
- 🎯 **Next Major Goal:** Securing a scholarship to pursue advanced Software Engineering studies in **Canada**.

<br>
<hr>
<br>

## 👨‍💻 The Engineering Philosophy

Great software isn't just about making things work; it's about making them secure, scalable, and maintainable. I approach every codebase with a strict set of rules to ensure enterprise-grade quality.

> 🛡️ **Zero `any` Tolerance:** > TypeScript loses its power when developers take shortcuts. I enforce strict typing across all my codebases. No exceptions. This guarantees better DX, fewer runtime errors, and rock-solid reliability.

> 🔒 **Security First (RLS by Default):** > When building with Supabase, security is never an afterthought. Row Level Security (RLS) must be implemented and meticulously configured by default on every single table I design.

> 📶 **Offline-First Architecture:** > Building for the African market requires robust offline capabilities. I heavily utilize local databases (like SQLite) synced with cloud backends (Supabase) to ensure uninterrupted user experiences.

<br>
<hr>
<br>

## 🛠️ Complete Technical Arsenal

Here is a comprehensive breakdown of the technologies, frameworks, and tools I use daily to bring ideas to life.

### 📱 Mobile & Frontend Development
<p align="left">
  <img src="https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
</p>

### ⚙️ Backend, Database & APIs
<p align="left">
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white" />
  <img src="https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white" />
  <img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=white" />
</p>

### 🧠 AI & Machine Learning
<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenAI_API-412991?style=for-the-badge&logo=openai&logoColor=white" />
</p>

### 🔧 Core Languages & DevOps Tools
<p align="left">
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" />
  <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" />
</p>

<br>
<hr>
<br>

## 🚀 Deep Dive: Featured Projects & Shipments

I take pride in seeing projects through from the initial Figma wireframe to successful store deployment. Here are my flagship applications:

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">🏢 Rently (InzuHub) v2.0</h3>
      <p align="center"><b>Status: Live on Apple App Store 🟢</b></p>
      <p>A next-generation mobile application revolutionizing the rental property market in Kigali and Gisenyi.</p>
      <ul>
        <li><b>Tech Stack:</b> React Native, Expo, Supabase.</li>
        <li><b>Key Features:</b> Advanced Google Maps integration for property tracking.</li>
        <li><b>Innovation:</b> Real-time audio translation to bridge language gaps between landlords and tenants.</li>
        <li><b>Business Logic:</b> Freemium model powered by MTN MoMo and Airtel Money integrations.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">💼 QuickBill</h3>
      <p align="center"><b>Status: In Active Development 🟡</b></p>
      <p>A smart, offline-first mobile invoicing application designed for local businesses and freelancers.</p>
      <ul>
        <li><b>Tech Stack:</b> React Native, SQLite, Supabase, AI APIs.</li>
        <li><b>Architecture:</b> Built with a robust offline-first synchronization engine. Data is stored locally via SQLite and securely synced to Supabase when online.</li>
        <li><b>Smart Features:</b> AI-driven invoice generation and receipt parsing.</li>
      </ul>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">🛍️ Chadito</h3>
      <p align="center"><b>Status: Live on iOS & Android 🟢</b></p>
      <p>A robust mobile marketplace specifically tailored to bridge the e-commerce and digital transaction gap in the Chadian market.</p>
      <ul>
        <li><b>Tech Stack:</b> React Native, Firebase.</li>
        <li><b>Impact:</b> Facilitating local commerce with an interface designed for the specific needs of Chadian users.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">🎓 Ecosystem & Hackathons</h3>
      <p align="center"><b>Status: Multiple Releases 🟢</b></p>
      <p>Building for the community through rapid prototyping and specific problem-solving.</p>
      <ul>
        <li><b>Kaminuza Hub:</b> Dedicated mobile platform for university students in Rwanda.</li>
        <li><b>Kenda:</b> Urban mobility mobile app successfully developed during a high-paced hackathon.</li>
        <li><b>Cheikh Ahmad Al-Nour:</b> Islamic educational mobile app, successfully published on Google Play.</li>
      </ul>
    </td>
  </tr>
</table>

<br>
<hr>
<br>

## 🎥 Content Creation & Mentorship

*"To teach is to learn twice."*

Beyond writing code, I am building a digital presence to document my journey, share technical insights, and ultimately monetize my content. You can find my short-form technical content, coding tips, and day-in-the-life vlogs across major platforms:

<div align="center">
  <a href="https://youtube.com/@callme_nour"><img src="https://img.shields.io/badge/YouTube_Shorts-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube" /></a>
  <a href="https://www.tiktok.com/@callme_nour"><img src="https://img.shields.io/badge/TikTok-000000?style=for-the-badge&logo=tiktok&logoColor=white" alt="TikTok" /></a>
  <a href="https://www.instagram.com/nourrmind"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" /></a>
  <a href="#"><img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook" /></a>
</div>

<br>
<hr>
<br>

## 🧠 Beyond the Keyboard

Building great software requires a clear mind and a strong foundation. Here is what fuels my drive and discipline outside of the IDE:

1. **The Iron Discipline:** I am an avid practitioner of bodybuilding. The consistency required to build muscle perfectly mirrors the discipline needed to master complex codebases. (My fuel: a strict regimen of eggs, rice, potatoes, and beans!).
2. **Mental Architecture:** I am deeply invested in psychology and self-improvement. Books like *"Se libérer de nos traumatismes"* and *"Vous pouvez changer votre vie"* profoundly influence my mindset and approach to challenges.
3. **Immersive Worlds:** To decompress, I dive into rich High/Heroic fantasy lore. You'll often find me exploring the universes of *Warcraft*, *The Witcher*, or *The Wheel of Time*.
4. **Cultural Integration:** Living in Rwanda, I am actively learning **Kinyarwanda** to connect more deeply with the local community and my peers at ULK.

<br>
<hr>
<br>

## 🏆 Certifications & GitHub Analytics

<div align="center">
  <h3>🎓 Certified: Harvard CS50's Introduction to Programming with Python</h3>
</div>

<br>

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=nourtd1&theme=tokyonight&margin-w=15&margin-h=15&column=7&no-frame=true" alt="GitHub Trophies" />
</div>

<br>

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=nourtd1&show_icons=true&theme=react&hide_border=true&include_all_commits=true&count_private=true" width="48%" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=nourtd1&theme=react&hide_border=true" width="48%" />
</div>

<br>

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=nourtd1&layout=compact&theme=react&hide_border=true" width="60%" />
</div>

<br>
<hr>
<br>

### 📊 Impact & Activity
<br>
<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/nourtd1/nourtd1/output/pacman-contribution-graph-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/nourtd1/nourtd1/output/pacman-contribution-graph-light.svg">
    <img alt="Pacman Contribution Graph" src="https://raw.githubusercontent.com/nourtd1/nourtd1/output/pacman-contribution-graph-dark.svg" width="100%" />
  </picture>
</div>

## 📫 Let's Connect & Build Something Great

Whether you want to discuss mobile architecture, content creation strategies, scholarship opportunities in Canada, or just debate the best build in The Witcher, my inbox is always open.

<div align="center">
  <a href="mailto:nourdevtd@gmail.com"><img src="https://img.shields.io/badge/Email_Me-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://www.linkedin.com/in/annour-mahamat-abdoulaye-a799ba310"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
</div>

<br>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=nourtd1&label=Profile%20Views&color=0e75b6&style=flat" alt="Profile Views" />
</p>

<p align="center">
  <i>"Technology is not just about code — it's about impact."</i>
</p>
