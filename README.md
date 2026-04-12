<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:0d1117&height=220&section=header&text=Ankit%20Saini&fontSize=75&fontColor=58a6ff&animation=fadeIn&fontAlignY=35&desc=Software%20Developer%20%7C%20Full%20Stack%20Engineer%20%7C%20Competitive%20Programmer&descSize=18&descColor=8b949e&descAlignY=55" width="100%" />

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&multiline=true&repeat=true&width=600&height=80&lines=Building+Egress+Proxy+Console+%F0%9F%9A%80;Full+Stack+Developer+%7C+800%2B+LeetCode+Solved;Turning+complex+problems+into+clean+code" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://linkedin.com/in/ankit-saini-74a3aa179/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:ankitsaini955831@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://leetcode.com/ankitcoder2001"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=white" /></a>
  <a href="https://www.codechef.com/users/sensei009"><img src="https://img.shields.io/badge/CodeChef-5B4638?style=for-the-badge&logo=codechef&logoColor=white" /></a>
  <img src="https://komarev.com/ghpvc/?username=ankittttss&label=Profile+Views&color=0e75b6&style=for-the-badge" />
</p>

---

## About Me

I'm a Software Developer who builds scalable full-stack applications and solves algorithmic challenges for fun. I work across the entire stack — from database design and backend APIs to frontend interfaces and infrastructure.

Currently building **Egress Proxy Console**, an open-source HTTP egress proxy platform that manages outbound API traffic with rate limiting, circuit breaking, and cost tracking.

```typescript
const ankit = {
    currentlyBuilding: "Egress Proxy Console — HTTP egress proxy platform",
    learning: ["System Design", "Distributed Systems", "Next.js"],
    askMeAbout: ["React", "Node.js", "TypeScript", "PostgreSQL", "DSA"],
    competitive: { leetcode: "800+ solved", codechef: "3-star rated" },
    funFact: "I debug distributed systems for fun"
};
```

---

## Featured Project

### [Egress Proxy Console](https://github.com/ankittttss/Egress) _(actively building)_

A developer-first HTTP egress proxy platform for managing, monitoring, and controlling outbound API calls. Built for teams making external API requests to services like OpenAI, Stripe, and Twilio.

<table>
<tr>
<td width="50%">

**What it does**
- **Rate Limiting** — Atomic token-bucket per domain (Redis Lua)
- **Circuit Breaking** — 3-state machine, fail fast not slow
- **Request Dedup** — Content-hash cache (1580ms → 9ms)
- **Cost Tracking** — Per-service budgets with monthly caps
- **Observability** — Prometheus + Grafana, auto-provisioned
- **Secrets Vault** — AES encrypted at rest
- **19-page Console** — Full admin dashboard

</td>
<td width="50%">

**Tech Stack**
- **Backend:** Node.js, Fastify, TypeScript, Zod
- **Database:** PostgreSQL 15 (Drizzle ORM)
- **Cache:** Redis 7 (ioredis)
- **Frontend:** React 18, Vite, Three.js
- **Auth:** JWT, SHA-256 keys, TOTP 2FA, Argon2
- **Infra:** Docker Compose, GitHub Actions
- **SDK:** Zero-dep TypeScript, drop-in `fetch()`
- **CLI:** Zero runtime dependencies

</td>
</tr>
</table>

```
Request → Auth → Rate Limit → Dedup → Circuit Breaker → Forward (retry + backoff) → Log → Cost → Respond
```

<p align="left">
  <a href="https://github.com/ankittttss/Egress">
    <img src="https://img.shields.io/badge/View_on_GitHub-100000?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

---

## Tech Stack

<table>
<tr>
<td valign="top" width="33%">

### Languages
<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black" />
  <img src="https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white" />
</p>

</td>
<td valign="top" width="33%">

### Frontend
<p>
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Redux-593D88?style=flat-square&logo=redux&logoColor=white" />
  <img src="https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" />
</p>

</td>
<td valign="top" width="33%">

### Backend & DB
<p>
  <img src="https://img.shields.io/badge/Node.js-43853D?style=flat-square&logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/Fastify-000000?style=flat-square&logo=fastify&logoColor=white" />
  <img src="https://img.shields.io/badge/Express-404D59?style=flat-square&logo=express&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/MongoDB-4EA94B?style=flat-square&logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-005C84?style=flat-square&logo=mysql&logoColor=white" />
</p>

</td>
</tr>
<tr>
<td valign="top" width="33%">

### DevOps & Tools
<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white" />
</p>

</td>
<td valign="top" width="33%">

### Observability
<p>
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" />
  <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenTelemetry-7B5EA7?style=flat-square&logo=opentelemetry&logoColor=white" />
</p>

</td>
<td valign="top" width="33%">

### Auth & Security
<p>
  <img src="https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white" />
  <img src="https://img.shields.io/badge/OAuth-3C78A9?style=flat-square&logo=oauth&logoColor=white" />
  <img src="https://img.shields.io/badge/Zod-3E67B1?style=flat-square&logo=zod&logoColor=white" />
</p>

</td>
</tr>
</table>

---

## GitHub Statistics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=ankittttss&show_icons=true&theme=github_dark&hide_border=true&count_private=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=c9d1d9" width="49%" alt="GitHub Stats" />
  <img src="https://github-readme-streak-stats.herokuapp.com?user=ankittttss&theme=github-dark-blue&hide_border=true&background=0D1117&stroke=30363d&ring=58a6ff&fire=58a6ff&currStreakLabel=58a6ff" width="49%" alt="GitHub Streak" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ankittttss&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&langs_count=8" width="49%" alt="Top Languages" />
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=ankittttss&theme=github-compact&hide_border=true&bg_color=0d1117&color=58a6ff&line=58a6ff&point=c9d1d9&area=true&area_color=1f6feb" width="49%" alt="Contribution Graph" />
</p>

---

## Trophies

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=ankittttss&theme=algolia&no-frame=true&no-bg=true&margin-w=4&row=1&column=7" alt="GitHub Trophies" />
</p>

---

## Competitive Programming

<p align="center">
  <a href="https://leetcode.com/ankitcoder2001">
    <img src="https://img.shields.io/badge/LeetCode-800%2B_Problems_Solved-FFA116?style=for-the-badge&logo=leetcode&logoColor=white" />
  </a>
  &nbsp;
  <a href="https://www.codechef.com/users/sensei009">
    <img src="https://img.shields.io/badge/CodeChef-3%E2%AD%90_Rated-5B4638?style=for-the-badge&logo=codechef&logoColor=white" />
  </a>
  &nbsp;
  <a href="https://codeforces.com/profile/anmolsainiii23">
    <img src="https://img.shields.io/badge/Codeforces-Active-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white" />
  </a>
  &nbsp;
  <a href="https://auth.geeksforgeeks.org/user/ankitsaini">
    <img src="https://img.shields.io/badge/GFG-Profile-2F8D46?style=for-the-badge&logo=geeksforgeeks&logoColor=white" />
  </a>
</p>

---

## Connect

<p align="center">
  <a href="https://linkedin.com/in/ankit-saini-74a3aa179/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  &nbsp;
  <a href="mailto:ankitsaini955831@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  &nbsp;
  <a href="https://instagram.com/ankittsainii__"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" /></a>
  &nbsp;
  <a href="https://www.youtube.com/c/screentime"><img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" /></a>
</p>

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:0d1117&height=100&section=footer" width="100%" />
</p>

<p align="center">
  <em>"First, solve the problem. Then, write the code."</em> — John Johnson
</p>
