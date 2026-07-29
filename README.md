from pathlib import Path

readme = r'''<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:4F46E5,100:06B6D4&height=140&section=header&text=Mrunal%20Shende&fontSize=38&fontColor=ffffff&animation=fadeIn&fontAlignY=40&desc=Full-Stack%20Developer%20%7C%20MERN%20%7C%20AI%20Integration&descAlignY=62&descSize=15" width="100%" />

<a href="mailto:your-email@gmail.com">
<img src="https://img.shields.io/badge/Email-6366F1?style=flat-square&logo=gmail&logoColor=white" />
</a>
&nbsp;
<a href="https://linkedin.com/in/mrunal-shende">
<img src="https://img.shields.io/badge/LinkedIn-6366F1?style=flat-square&logo=linkedin&logoColor=white" />
</a>
&nbsp;
<a href="https://github.com/mrunal-shende">
<img src="https://img.shields.io/badge/GitHub-6366F1?style=flat-square&logo=github&logoColor=white" />
</a>
&nbsp;
<img src="https://komarev.com/ghpvc/?username=mrunal-shende&style=flat-square&color=06B6D4&label=PROFILE+VIEWS" />

</div>

---

## 👋 About Me

I'm **Mrunal Shende**, a Full-Stack Developer and MCA student focused on building practical, user-focused web applications.

I mainly work with the **MERN stack** and enjoy working across the complete development cycle — from designing databases and REST APIs to building responsive interfaces and deploying applications.

- 💻 Full-Stack & Backend Development
- ⚙️ REST APIs & Database Integration
- 🤖 AI & Chatbot Integration
- ☁️ Cloud Deployment & DevOps
- 🚀 Learning by building real-world projects

---

## 💼 Experience

| Role | Company | Duration |
| :--- | :--- | :---: |
| **Junior Software Development Engineer Intern** | Chetan's Royals Webtech Pvt. Ltd. | Jan 2026 – Present |
| **AI & ML Virtual Intern** | Google | Jan 2025 – Mar 2025 |

**Current Role:** Working with React.js, Node.js, Express.js, and Supabase on client-facing applications across travel, logistics, real estate, and financial domains.

**AI & ML Internship:** Completed a 10-week virtual internship focused on AI/ML concepts and practical AI-based solutions.

---

## 🛠️ Tech Stack

<div align="center">

### Languages
<img src="https://skillicons.dev/icons?i=js,python,java" />

### Frontend & Backend
<img src="https://skillicons.dev/icons?i=react,html,css,vite,nodejs,express" />

### Databases
<img src="https://skillicons.dev/icons?i=mongodb,mysql,redis,supabase" />

### Tools & DevOps
<img src="https://skillicons.dev/icons?i=git,github,docker,nginx,postman,aws" />

</div>

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🏥 Am Well
**Virtual Healthcare Assistant**

A healthcare platform combining AI chatbot support with emergency assistance and real-time communication.

**Tech:** `Node.js` `Express.js` `MongoDB` `Socket.IO` `AI API`

</td>
<td width="50%" valign="top">

### 🛒 E-Commerce Microservices
**Backend & Microservices Platform**

A modular e-commerce backend with independent services, authentication, caching, and containerized deployment.

**Tech:** `Node.js` `MongoDB` `Redis` `Docker` `Nginx` `JWT`

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 👥 Student-Hub
**Campus Collaboration Platform**

A MERN-based platform for academic resource sharing and campus updates with authentication and admin management.

**Tech:** `React.js` `Node.js` `Express.js` `MongoDB`

</td>
<td width="50%" valign="top">

### 🧳 Express Travel Corp
**Tour & Travel Website**

A responsive commercial travel website featuring tour packages, company information, and interactive UI sections.

**Tech:** `HTML5` `CSS3` `JavaScript`

</td>
</tr>
</table>

---

## 📊 GitHub Analytics

<div align="center">

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=mrunal-shende&theme=tokyonight" width="95%" />

<br/>

<img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=mrunal-shende&theme=tokyonight" width="46%" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/top-languages?username=mrunal-shende&theme=tokyonight" width="46%" />

</div>

---

## 🎓 Education

| Degree | Institute | Timeline | Result |
| :--- | :--- | :---: | :---: |
| **MCA** | P. R. Pote Patil College of Engineering, Amravati | 2024 – Present | **9.3 / 10** |
| **BCCA** | Kamala Nehru College, Nagpur | 2021 – 2024 | **7.4 / 10** |

---

## 🏆 Achievements

<div align="center">

| 🥇 Project Showcase | 🐍 Python Gold Badge | 🏆 Hackathon Winner |
| :---: | :---: | :---: |
| Department-Level | HackerRank | College Hackathon |

| 🎯 SIH 2025 | 🤖 AI & ML Internship | 💻 Developer Simulation |
| :---: | :---: | :---: |
| Institutional Selection | 10-Week Program | Accenture |

</div>

---

## 🌱 Currently Exploring

<div align="center">

`AI Integration` &nbsp; `System Design` &nbsp; `Microservices` &nbsp; `Cloud` &nbsp; `DevOps`

</div>

---

## 🤝 Let's Connect

<div align="center">

I'm open to connecting with developers, recruiters, and teams working on interesting technology projects.

<br/>

<a href="mailto:your-email@gmail.com">
<img src="https://img.shields.io/badge/Email-6366F1?style=for-the-badge&logo=gmail&logoColor=white" />
</a>
&nbsp;
<a href="https://linkedin.com/in/mrunal-shende">
<img src="https://img.shields.io/badge/LinkedIn-06B6D4?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:06B6D4,100:4F46E5&height=90&section=footer" width="100%" />

</div>
'''

path = Path("/mnt/data/README.md")
path.write_text(readme, encoding="utf-8")
print(path)
