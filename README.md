## Hi there 👋

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=250&color=gradient&customColorList=6,11,20,24,30&text=KARTHEESWARAN%20K&fontSize=45&fontColor=ffffff&animation=fadeIn&fontAlignY=40&desc=Full%20Stack%20Developer%20|%20React%20Native%20Developer%20|%20AI%20Enthusiast&descAlignY=60"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Poppins&weight=600&size=24&duration=3000&pause=1000&center=true&vCenter=true&width=850&lines=Full+Stack+Developer;React+Native+Developer;AI-Powered+Application+Developer;Node.js+%7C+MySQL+%7C+Angular;Always+Learning+Something+New)](https://git.io/typing-svg)

<p>
<img src="https://img.shields.io/badge/B.E.-Computer%20Science-blueviolet?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Location-Tamil%20Nadu,%20India-blue?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Open%20to-Software%20Engineering-success?style=for-the-badge"/>
</p>

<p>
<a href="https://kartheeswaran0512.github.io/my-portfolio/">
<img src="https://img.shields.io/badge/Portfolio-Visit-6f42c1?style=for-the-badge"/>
</a>

<a href="http://www.linkedin.com/in/kartheeswaran-k-14579a217">
<img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge"/>
</a>

<a href="mailto:kartheeswarank0512@gmail.com">
<img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge"/>
</a>

<a href="https://github.com/Kartheeswaran0512">
<img src="https://img.shields.io/badge/GitHub-Profile-181717?style=for-the-badge"/>
</a>
</p>

<p>
<img src="https://komarev.com/ghpvc/?username=Kartheeswaran0512&style=for-the-badge&color=blueviolet"/>
<img src="https://img.shields.io/github/followers/Kartheeswaran0512?style=for-the-badge"/>
<img src="https://img.shields.io/github/stars/Kartheeswaran0512?affiliations=OWNER&style=for-the-badge"/>
</p>

</div>

### 🧑‍💻 About Me

```text
import { useState, useEffect } from "react";

export default function KartheeswaranCard() {
  const kartheeswaran = {
    role: "Full Stack Developer @ AI-Integrated Web Apps",
    location: "Madurai, Tamil Nadu, India",
    education: "B.E. Computer Science, CIT (CGPA: 8.0/10)",
    currentFocus: ["React Native", "System Design", "DSA"],
    goal: "Software Engineer @ a top product company",
  };

  const [typedGoal, setTypedGoal] = useState("");

  useEffect(() => {
    let i = 0;
    const interval = setInterval(() => {
      setTypedGoal(kartheeswaran.goal.slice(0, i + 1));
      i++;
      if (i === kartheeswaran.goal.length) clearInterval(interval);
    }, 40);
    return () => clearInterval(interval);
  }, []);

  return (
    <div className="min-h-screen bg-slate-950 flex items-center justify-center p-6">
      <div className="w-full max-w-2xl rounded-2xl border border-slate-800 bg-slate-900 shadow-2xl overflow-hidden">
        {/* Title bar */}
        <div className="flex items-center gap-2 px-4 py-3 bg-slate-800 border-b border-slate-700">
          <span className="w-3 h-3 rounded-full bg-red-500" />
          <span className="w-3 h-3 rounded-full bg-yellow-500" />
          <span className="w-3 h-3 rounded-full bg-green-500" />
          <span className="ml-3 text-slate-400 text-sm font-mono">kartheeswaran.js</span>
        </div>

        {/* Code body */}
        <div className="p-6 font-mono text-sm sm:text-base leading-relaxed">
          <p className="text-purple-400">
            const <span className="text-blue-400">kartheeswaran</span> ={" "}
            <span className="text-slate-300">{"{"}</span>
          </p>

          <p className="pl-6">
            <span className="text-sky-300">role</span>
            <span className="text-slate-400">: </span>
            <span className="text-emerald-400">
              "{kartheeswaran.role}"
            </span>
            <span className="text-slate-400">,</span>
          </p>

          <p className="pl-6">
            <span className="text-sky-300">location</span>
            <span className="text-slate-400">: </span>
            <span className="text-emerald-400">
              "{kartheeswaran.location}"
            </span>
            <span className="text-slate-400">,</span>
          </p>

          <p className="pl-6">
            <span className="text-sky-300">education</span>
            <span className="text-slate-400">: </span>
            <span className="text-emerald-400">
              "{kartheeswaran.education}"
            </span>
            <span className="text-slate-400">,</span>
          </p>

          <p className="pl-6">
            <span className="text-sky-300">currentFocus</span>
            <span className="text-slate-400">: [</span>
          </p>
          {kartheeswaran.currentFocus.map((item, idx) => (
            <p key={idx} className="pl-12">
              <span className="text-emerald-400">"{item}"</span>
              <span className="text-slate-400">
                {idx < kartheeswaran.currentFocus.length - 1 ? "," : ""}
              </span>
            </p>
          ))}
          <p className="pl-6">
            <span className="text-slate-400">],</span>
          </p>

          <p className="pl-6">
            <span className="text-sky-300">goal</span>
            <span className="text-slate-400">: </span>
            <span className="text-amber-300">
              "{typedGoal}
              <span className="animate-pulse">|</span>"
            </span>
            <span className="text-slate-400">,</span>
          </p>

          <p className="text-slate-300">{"};"}</p>
        </div>
      </div>
    </div>
  );
}
```

---

### 🛠️ Tech Stack

<p align="left">
<img src="https://skillicons.dev/icons?i=cpp,java,js,html,css,angular,tailwind,nodejs,express,mysql,redis,git,github,docker,postman,linux,figma&theme=dark" />
</p>

<p align="left">
<img src="https://img.shields.io/badge/OpenAI%20API-412991?style=flat-square&logo=openai&logoColor=white"/>
<img src="https://img.shields.io/badge/Anthropic%20Claude%20SDK-D97757?style=flat-square&logo=anthropic&logoColor=white"/>
<img src="https://img.shields.io/badge/ReAct%20Agents-6f42c1?style=flat-square"/>
<img src="https://img.shields.io/badge/JWT%20%2F%20RBAC-000000?style=flat-square&logo=jsonwebtokens&logoColor=white"/>
</p>

---

### 💼 Experience

<table>
<tr>
<td>🗓️</td>
<td>

**Full Stack Developer Intern** · Agaram Solution
<sub>June 2025 – August 2025</sub>

- Built 3+ responsive modules with **Angular 17 standalone components**, Angular Material & Tailwind CSS
- Implemented **JWT auth with 3-tier RBAC** (Admin / Agent / User) across API & UI layers
- Collaborated via Git/GitHub (branching, PRs); tested REST APIs with Postman
- Managed **Linux & Docker** environments; optimized large MySQL tables with indexing

</td>
</tr>
</table>

---

### 🚀 Featured Projects

<p align="left">
<a href="https://github.com/Kartheeswaran0512/job-scam-detector">
<img src="https://github-readme-stats.vercel.app/api/pin/?username=Kartheeswaran0512&repo=job-scam-detector&theme=radical" />
</a>
<a href="https://github.com/Kartheeswaran0512/support_ticket_system">
<img src="https://github-readme-stats.vercel.app/api/pin/?username=Kartheeswaran0512&repo=support_ticket_system&theme=radical" />
</a>
</p>
<p align="left">
<a href="https://github.com/Kartheeswaran0512/url-shortener-node">
<img src="https://github-readme-stats.vercel.app/api/pin/?username=Kartheeswaran0512&repo=url-shortener-node&theme=radical" />
</a>
</p>

> 🔍 **Job Scam Detector** — Agentic AI (ReAct loop) analyzing job postings across 5 risk dimensions to flag fraud before you apply. `Claude API` `Node.js` `Express`
>
> 🎫 **AI Support Ticket System** — Full-stack ticketing with JWT/RBAC, AI auto-responses, and a priority queue for urgent tickets. `Angular` `Node.js` `MySQL` `OpenAI API`
>
> 🔗 **URL Shortener** — Cache-Aside pattern with Redis, cutting MySQL load by **40%**. `Node.js` `MySQL` `Redis`

---

### 🏆 Achievements & Certifications

- 🧩 **250+ DSA problems** solved on LeetCode — Arrays, DP, Graphs
- 🥇 HackerRank Certified — Problem Solving, C++, C, SQL

---

### 📊 GitHub Stats

<p align="center">
<img src="https://github-readme-stats.vercel.app/api?username=Kartheeswaran0512&show_icons=true&theme=radical&hide_border=true&count_private=true" height="165"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=Kartheeswaran0512&theme=radical&hide_border=true" height="165"/>
</p>

<p align="center">
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Kartheeswaran0512&layout=compact&theme=radical&hide_border=true" height="165"/>
<img src="https://github-profile-trophy.vercel.app/?username=Kartheeswaran0512&theme=radical&no-frame=true&row=2&column=3" height="165"/>
</p>

---

<div align="center">

### 📫 Let's Connect

<a href="https://kartheeswaran0512.github.io/my-portfolio/"><img src="https://img.shields.io/badge/Portfolio-6f42c1?style=for-the-badge"/></a>
<a href="http://www.linkedin.com/in/kartheeswaran-k-14579a217"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:kartheeswarank0512@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20,24,30&height=100&section=footer"/>

</div>
<!--
**Kartheeswaran0512/Kartheeswaran0512** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
