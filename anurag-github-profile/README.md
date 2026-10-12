<p align="center">
  <img src="./assets/header.svg" width="100%" alt="Anurag Raghav Sinha, full-stack developer" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3000&pause=900&color=1BA3B5&center=true&vCenter=true&width=680&lines=Built+a+client+helpdesk+solo+%E2%80%94+350%2B+tickets+resolved;Own+the+quotation+%26+approval+engine+of+a+live+CRM;%22Choice+of+CSK%22+award+from+the+CEO%2C+May+2026" alt="Typing intro" />
</p>

<p align="center">
  <a href="https://anuragraghavsinha.vercel.app"><img src="https://img.shields.io/badge/Portfolio-0B1F24?style=for-the-badge&logo=vercel&logoColor=1BA3B5" alt="Portfolio" /></a>
  <a href="https://linkedin.com/in/anurag-sinha945"><img src="https://img.shields.io/badge/LinkedIn-0B1F24?style=for-the-badge&logo=linkedin&logoColor=1BA3B5" alt="LinkedIn" /></a>
  <a href="mailto:anuragraghavsinha@gmail.com"><img src="https://img.shields.io/badge/Email_me-0B1F24?style=for-the-badge&logo=gmail&logoColor=5EE6C7" alt="Email" /></a>
  <a href="https://anuragraghavsinha.vercel.app/Anurag_Raghav_Sinha_Resume.pdf"><img src="https://img.shields.io/badge/Resume-0B1F24?style=for-the-badge&logo=googledocs&logoColor=5EE6C7" alt="Resume" /></a>
  <img src="https://img.shields.io/badge/Open_to-Remote-1F8A5B?style=for-the-badge" alt="Open to remote" />
  <img src="https://komarev.com/ghpvc/?username=Anurag945&style=for-the-badge&color=12525E&label=Profile+views" alt="Profile views" />
</p>

---

## 👨‍💻 About me

I'm a full-stack developer at **CSK Infotech**, Greater Noida, with close to two years of shipping production systems. I like the part of software most people never see: the rules, permissions and background jobs that keep a business running correctly.

- 🏗️ I own the **quotation, approval and automation modules** of the CRM that runs the company's live sales pipeline
- 🛠️ I designed, built and deployed a **client IT helpdesk on my own**: 150+ faculty, a 10-person field team, **350+ tickets** resolved
- 🏆 Won the **"Choice of CSK"** award from the CEO (May 2026) for the CRM modules
- 📈 Joined as a trainee in April 2025, promoted to Software Engineer in October 2025
- 🎓 B.Tech in Computer Science, AKTU (2021 to 2025)

**What I'm good at:** access control · SLA design · audit logging · background jobs · login and SSO integration

---

## 🚀 Featured work

<table>
<tr>
<td width="50%" valign="top">

### 📊 Central CRM: quotation and approval engine
The enterprise B2B platform running the company's **live sales pipeline**.

<img src="https://img.shields.io/badge/React-0B1F24?style=flat-square&logo=react&logoColor=61DAFB" /> <img src="https://img.shields.io/badge/Node.js-0B1F24?style=flat-square&logo=nodedotjs&logoColor=5FA04E" /> <img src="https://img.shields.io/badge/Express-0B1F24?style=flat-square&logo=express&logoColor=white" /> <img src="https://img.shields.io/badge/MongoDB-0B1F24?style=flat-square&logo=mongodb&logoColor=47A248" />

- Compares prices from multiple vendors per item, with GST, freight and installation worked in
- Pending → Approved / Rejected flow; totals are recalculated on the server, never trusted from the browser
- Salespeople see only their own records, enforced in the database query, not just hidden in the UI
- A daily job flags deals stuck for 15+ days and sends each salesperson one summary email
- Connected to a central JWT / SSO login server; unknown roles get the lowest access by default

<sub>🏆 "Choice of CSK" award · 🔒 Internal company project, code is private</sub>

</td>
<td width="50%" valign="top">

### 🎫 Client IT helpdesk: built solo
Designed, built and deployed **alone** for an external client on a multi-year contract.

<img src="https://img.shields.io/badge/PHP_8-0B1F24?style=flat-square&logo=php&logoColor=777BB4" /> <img src="https://img.shields.io/badge/MariaDB-0B1F24?style=flat-square&logo=mariadb&logoColor=C0765A" /> <img src="https://img.shields.io/badge/cPanel-0B1F24?style=flat-square&logo=cpanel&logoColor=FF6C2C" />

- Used by **150+ faculty** and a 10-person field team, with **350+ tickets** resolved so far
- Live SLA engine that works out deadlines in business hours, so they can't drift
- Escalation chain that checks every 5 minutes, with a full audit trail
- Access control for 4 roles
- Old MD5 passwords upgraded to bcrypt silently at login, with no forced reset

<sub>🔒 Client project, code is private</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🥤 Genzy Sip: scroll-driven product film
Scrolling plays a **540-frame film**, drawn frame by frame on a canvas. There's no video, so the motion stays locked to your scroll.

<img src="https://img.shields.io/badge/React_18-0B1F24?style=flat-square&logo=react&logoColor=61DAFB" /> <img src="https://img.shields.io/badge/TypeScript-0B1F24?style=flat-square&logo=typescript&logoColor=3178C6" /> <img src="https://img.shields.io/badge/GSAP-0B1F24?style=flat-square&logo=greensock&logoColor=88CE02" /> <img src="https://img.shields.io/badge/Vite-0B1F24?style=flat-square&logo=vite&logoColor=646CFF" />

- Frames load in waves, so you can scroll through it within seconds
- If a frame isn't ready, the nearest loaded one is shown, so the canvas never goes blank

**[Live demo](https://genzysip.vercel.app)** · [Code]([GENZY_SIP_REPO_URL])

</td>
<td width="50%" valign="top">

### 🏥 SmartCare: AI healthcare portal
A hospital management portal that automates patient workflows.

<img src="https://img.shields.io/badge/React-0B1F24?style=flat-square&logo=react&logoColor=61DAFB" /> <img src="https://img.shields.io/badge/Node.js-0B1F24?style=flat-square&logo=nodedotjs&logoColor=5FA04E" /> <img src="https://img.shields.io/badge/MongoDB-0B1F24?style=flat-square&logo=mongodb&logoColor=47A248" /> <img src="https://img.shields.io/badge/Generative_AI-0B1F24?style=flat-square&logo=openai&logoColor=white" />

- A generative-AI chatbot answers patient questions

**[Live demo](https://smart-care-frontend.vercel.app)** · [Code]([SMARTCARE_REPO_URL])

</td>
</tr>
</table>

---

## 🧭 Experience

| Role | Company | When |
|---|---|---|
| **Software Engineer** | CSK Infotech, Greater Noida | Oct 2025 – Present |
| Software Engineer Trainee | CSK Infotech, Greater Noida | Apr 2025 – Oct 2025 |
| Software Engineer Intern | Mangoesorange, Noida (hybrid) | Oct 2024 – Mar 2025 |

<sub>🏆 **"Choice of CSK"**, awarded by the CEO in May 2026 for the CRM modules that streamlined the sales team's daily work.</sub>

---

## 🧰 Tech I work with

<table>
<tr><td><b>Backend</b></td><td><img src="https://skillicons.dev/icons?i=nodejs,express,php&theme=dark" /></td></tr>
<tr><td><b>Frontend</b></td><td><img src="https://skillicons.dev/icons?i=react,ts,js,tailwind,vite,html,css&theme=dark" /></td></tr>
<tr><td><b>Databases</b></td><td><img src="https://skillicons.dev/icons?i=mongodb,mysql&theme=dark" /> &nbsp; <img src="https://img.shields.io/badge/MariaDB-0B1F24?style=for-the-badge&logo=mariadb&logoColor=C0765A" /></td></tr>
<tr><td><b>Tools</b></td><td><img src="https://skillicons.dev/icons?i=git,github,githubactions&theme=dark" /></td></tr>
<tr><td><b>Also</b></td><td>
<img src="https://img.shields.io/badge/JWT_%2F_SSO-0B1F24?style=flat-square&logo=jsonwebtokens&logoColor=white" />
<img src="https://img.shields.io/badge/node--cron-0B1F24?style=flat-square&logo=nodedotjs&logoColor=5FA04E" />
<img src="https://img.shields.io/badge/REST_APIs-0B1F24?style=flat-square&logo=postman&logoColor=FF6C37" />
<img src="https://img.shields.io/badge/LLM_integration-0B1F24?style=flat-square&logo=openai&logoColor=white" />
<img src="https://img.shields.io/badge/GSAP-0B1F24?style=flat-square&logo=greensock&logoColor=88CE02" />
<img src="https://img.shields.io/badge/Recharts-0B1F24?style=flat-square&logo=chartdotjs&logoColor=22B5BF" />
</td></tr>
</table>

---

## 📈 On GitHub

<p align="center">
  <img src="https://streak-stats.demolab.com?user=Anurag945&hide_border=true&background=0B1F24&stroke=1E4148&ring=1BA3B5&fire=5EE6C7&currStreakNum=E8F1F2&sideNums=E8F1F2&currStreakLabel=1BA3B5&sideLabels=8FA3A8&dates=8FA3A8" width="80%" alt="Contribution streak" />
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Anurag945/Anurag945/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Anurag945/Anurag945/output/github-snake.svg" />
    <img alt="Snake eating my contribution graph" src="https://raw.githubusercontent.com/Anurag945/Anurag945/output/github-snake-dark.svg" />
  </picture>
</p>

---

## 🤝 Let's connect

<p align="center">
  Hiring for backend or full-stack work, or need a system that has to stay correct? Let's talk.
</p>

<p align="center">
  <a href="https://linkedin.com/in/anurag-sinha945"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:anuragraghavsinha@gmail.com"><img src="https://img.shields.io/badge/anuragraghavsinha@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://anuragraghavsinha.vercel.app"><img src="https://img.shields.io/badge/Portfolio-12525E?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B1F24,50:12525E,100:1BA3B5&height=110&section=footer" width="100%" alt="" />
</p>
