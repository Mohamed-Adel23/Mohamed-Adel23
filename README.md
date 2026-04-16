
<style>
  @import url('https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;500;700&family=Sora:wght@300;400;600;700&display=swap');
  *{box-sizing:border-box;margin:0;padding:0}
  .wrap{font-family:'Sora',sans-serif;color:var(--color-text-primary);padding:2rem 1.5rem;max-width:860px;margin:0 auto}
  .header{display:flex;align-items:center;gap:1.5rem;margin-bottom:2rem;padding-bottom:1.5rem;border-bottom:0.5px solid var(--color-border-tertiary)}
  .avatar{width:72px;height:72px;border-radius:50%;background:linear-gradient(135deg,#1D9E75,#185FA5);display:flex;align-items:center;justify-content:center;font-family:'JetBrains Mono',monospace;font-size:1.4rem;font-weight:700;color:#fff;flex-shrink:0}
  .hero-title{font-size:1.5rem;font-weight:700;letter-spacing:-0.03em;line-height:1.2}
  .hero-sub{font-size:.875rem;color:var(--color-text-secondary);margin-top:.3rem;line-height:1.5}
  .typing{font-family:'JetBrains Mono',monospace;font-size:.8rem;color:#1D9E75;background:var(--color-background-secondary);border:0.5px solid var(--color-border-tertiary);border-radius:6px;padding:.25rem .6rem;display:inline-block;margin-top:.5rem}
  .cursor{animation:blink 1s step-end infinite}
  @keyframes blink{50%{opacity:0}}
  .section{margin-bottom:1.75rem}
  .sec-label{font-size:.7rem;font-weight:600;letter-spacing:.12em;text-transform:uppercase;color:var(--color-text-tertiary);margin-bottom:.75rem}
  .badges{display:flex;flex-wrap:wrap;gap:.4rem}
  .badge{font-family:'JetBrains Mono',monospace;font-size:.72rem;padding:.3rem .65rem;border-radius:6px;font-weight:500;border:0.5px solid}
  .b-green{background:#EAF3DE;color:#3B6D11;border-color:#97C459}
  .b-blue{background:#E6F1FB;color:#185FA5;border-color:#85B7EB}
  .b-teal{background:#E1F5EE;color:#0F6E56;border-color:#5DCAA5}
  .b-amber{background:#FAEEDA;color:#854F0B;border-color:#EF9F27}
  .b-purple{background:#EEEDFE;color:#534AB7;border-color:#AFA9EC}
  .b-gray{background:#F1EFE8;color:#5F5E5A;border-color:#B4B2A9}
  .stats-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(140px,1fr));gap:.75rem}
  .stat-card{background:var(--color-background-secondary);border-radius:10px;padding:.85rem 1rem;border:0.5px solid var(--color-border-tertiary)}
  .stat-label{font-size:.72rem;color:var(--color-text-tertiary);margin-bottom:.25rem;font-weight:500}
  .stat-val{font-family:'JetBrains Mono',monospace;font-size:1.3rem;font-weight:700}
  .stat-val.green{color:#1D9E75}
  .stat-val.blue{color:#185FA5}
  .stat-val.amber{color:#BA7517}
  .stat-val.purple{color:#534AB7}
  .social-row{display:flex;flex-wrap:wrap;gap:.5rem}
  .soc-btn{display:inline-flex;align-items:center;gap:.4rem;font-size:.78rem;font-weight:500;padding:.35rem .8rem;border-radius:8px;border:0.5px solid var(--color-border-secondary);color:var(--color-text-secondary);text-decoration:none;background:var(--color-background-primary);transition:all .15s}
  .soc-btn:hover{background:var(--color-background-secondary);color:var(--color-text-primary);border-color:var(--color-border-primary)}
  .soc-icon{width:14px;height:14px;flex-shrink:0}
  .divider{height:0.5px;background:var(--color-border-tertiary);margin:1.5rem 0}
  .quote-bar{border-left:3px solid #1D9E75;padding-left:.85rem;font-size:.85rem;color:var(--color-text-secondary);font-style:italic;line-height:1.6}
  .lang-bar-wrap{margin-top:.6rem}
  .lang-row{display:flex;align-items:center;gap:.6rem;margin-bottom:.45rem}
  .lang-name{font-family:'JetBrains Mono',monospace;font-size:.72rem;width:60px;flex-shrink:0;color:var(--color-text-secondary)}
  .lang-track{flex:1;height:6px;background:var(--color-background-secondary);border-radius:99px;overflow:hidden}
  .lang-fill{height:100%;border-radius:99px;transition:width 1s ease}
  .lang-pct{font-family:'JetBrains Mono',monospace;font-size:.68rem;width:32px;text-align:right;color:var(--color-text-tertiary)}
  .readme-box{background:var(--color-background-secondary);border:0.5px solid var(--color-border-tertiary);border-radius:10px;padding:1rem 1.25rem;font-family:'JetBrains Mono',monospace;font-size:.75rem;color:var(--color-text-secondary);line-height:1.7;position:relative}
  .readme-bar{display:flex;align-items:center;gap:.4rem;margin-bottom:.75rem}
  .dot{width:10px;height:10px;border-radius:50%;flex-shrink:0}
  .copy-btn{margin-left:auto;font-size:.68rem;font-family:'Sora',sans-serif;padding:.2rem .6rem;border-radius:6px;border:0.5px solid var(--color-border-secondary);background:transparent;color:var(--color-text-secondary);cursor:pointer}
  .copy-btn:hover{background:var(--color-background-primary)}
  .readme-content{white-space:pre-wrap;word-break:break-word;max-height:340px;overflow-y:auto}
  .readme-content .comment{color:#1D9E75}
  .readme-content .heading{color:var(--color-text-primary);font-weight:700}
  .readme-content .tag{color:#185FA5}
  .readme-content .str{color:#BA7517}
</style>

<div class="wrap">
  <h2 class="sr-only" style="position:absolute;width:1px;height:1px;overflow:hidden">GitHub profile README preview for a backend software engineer</h2>

  <div class="header">
    <div class="avatar">&lt;/&gt;</div>
    <div>
      <div class="hero-title">Backend Engineer &amp; Systems Architect</div>
      <div class="hero-sub">Passionate about distributed systems · Scalable architecture · Clean code</div>
      <div class="typing">$ building things that scale<span class="cursor">_</span></div>
    </div>
  </div>

  <div class="section">
    <div class="sec-label">Languages</div>
    <div class="badges">
      <span class="badge b-blue">C++</span>
      <span class="badge b-blue">C#</span>
      <span class="badge b-blue">JavaScript</span>
      <span class="badge b-blue">Python</span>
      <span class="badge b-blue">GoLang</span>
      <span class="badge b-blue">HTML</span>
      <span class="badge b-blue">CSS</span>
    </div>
  </div>

  <div class="section">
    <div class="sec-label">Frameworks &amp; Libraries</div>
    <div class="badges">
      <span class="badge b-purple">ASP .NET Core</span>
      <span class="badge b-purple">NodeJS</span>
      <span class="badge b-purple">ReactJS</span>
      <span class="badge b-purple">Angular</span>
      <span class="badge b-purple">Bootstrap</span>
    </div>
  </div>

  <div class="section">
    <div class="sec-label">Databases</div>
    <div class="badges">
      <span class="badge b-teal">SQL Server</span>
      <span class="badge b-teal">PostgreSQL</span>
      <span class="badge b-teal">Redis</span>
      <span class="badge b-teal">MongoDB</span>
    </div>
  </div>

  <div class="section">
    <div class="sec-label">DevOps &amp; Tools</div>
    <div class="badges">
      <span class="badge b-amber">Docker</span>
      <span class="badge b-amber">Linux</span>
      <span class="badge b-amber">IIS</span>
      <span class="badge b-gray">VS Code</span>
      <span class="badge b-gray">Visual Studio</span>
      <span class="badge b-gray">GitHub</span>
    </div>
  </div>

  <div class="divider"></div>

  <div class="section">
    <div class="sec-label">Language activity</div>
    <div class="lang-bar-wrap" id="bars"></div>
  </div>

  <div class="section">
    <div class="sec-label">Profile stats</div>
    <div class="stats-grid">
      <div class="stat-card"><div class="stat-label">GitHub streak</div><div class="stat-val green">365 days</div></div>
      <div class="stat-card"><div class="stat-label">Total commits</div><div class="stat-val blue">1.2k+</div></div>
      <div class="stat-card"><div class="stat-label">Repositories</div><div class="stat-val amber">40+</div></div>
      <div class="stat-card"><div class="stat-label">Pull requests</div><div class="stat-val purple">200+</div></div>
    </div>
  </div>

  <div class="section">
    <div class="sec-label">Find me</div>
    <div class="social-row">
      <a class="soc-btn" href="#">
        <svg class="soc-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z"/><rect x="2" y="9" width="4" height="12"/><circle cx="4" cy="4" r="2"/></svg>
        LinkedIn
      </a>
      <a class="soc-btn" href="#">
        <svg class="soc-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"/><polyline points="22,6 12,13 2,6"/></svg>
        Email
      </a>
      <a class="soc-btn" href="#">
        <svg class="soc-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="12" cy="12" r="10"/><line x1="2" y1="12" x2="22" y2="12"/><path d="M12 2a15.3 15.3 0 0 1 4 10 15.3 15.3 0 0 1-4 10 15.3 15.3 0 0 1-4-10 15.3 15.3 0 0 1 4-10z"/></svg>
        LeetCode
      </a>
      <a class="soc-btn" href="#">
        <svg class="soc-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M23 3a10.9 10.9 0 0 1-3.14 1.53 4.48 4.48 0 0 0-7.86 3v1A10.66 10.66 0 0 1 3 4s-4 9 5 13a11.64 11.64 0 0 1-7 2c9 5 20 0 20-11.5a4.5 4.5 0 0 0-.08-.83A7.72 7.72 0 0 0 23 3z"/></svg>
        X (Twitter)
      </a>
      <a class="soc-btn" href="#">
        <svg class="soc-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M18 8h1a4 4 0 0 1 0 8h-1"/><path d="M2 8h16v9a4 4 0 0 1-4 4H6a4 4 0 0 1-4-4V8z"/><line x1="6" y1="1" x2="6" y2="4"/><line x1="10" y1="1" x2="10" y2="4"/><line x1="14" y1="1" x2="14" y2="4"/></svg>
        Buy me a coffee
      </a>
    </div>
  </div>

  <div class="divider"></div>

  <div class="section">
    <div class="sec-label">Quote</div>
    <div class="quote-bar">"First, solve the problem. Then, write the code." — John Johnson</div>
  </div>

  <div class="section">
    <div class="sec-label">Raw README.md — copy &amp; paste to your GitHub</div>
    <div class="readme-box">
      <div class="readme-bar">
        <div class="dot" style="background:#FF5F57"></div>
        <div class="dot" style="background:#FFBD2E"></div>
        <div class="dot" style="background:#28CA41"></div>
        <span style="font-size:.72rem;color:var(--color-text-tertiary);margin-left:.25rem">README.md</span>
        <button class="copy-btn" onclick="copyReadme()">copy</button>
      </div>
      <div class="readme-content" id="readme-out"></div>
    </div>
  </div>
</div>

<script>
const langs = [
  {name:'C#',pct:35,color:'#185FA5'},{name:'GoLang',pct:25,color:'#1D9E75'},
  {name:'JS',pct:20,color:'#BA7517'},{name:'Python',pct:12,color:'#534AB7'},{name:'C++',pct:8,color:'#993C1D'}
];
const barsEl = document.getElementById('bars');
langs.forEach(l => {
  barsEl.innerHTML += `<div class="lang-row"><span class="lang-name">${l.name}</span><div class="lang-track"><div class="lang-fill" data-w="${l.pct}" style="width:0;background:${l.color}"></div></div><span class="lang-pct">${l.pct}%</span></div>`;
});
setTimeout(() => {
  document.querySelectorAll('.lang-fill').forEach(el => el.style.width = el.dataset.w + '%');
}, 300);

const readme = `<h1 align="center">Hi there, I'm a Backend Engineer 👋</h1>

<p align="center">
  <em>Specialized in Backend Development · Passionate about Distributed & Scalable Systems</em>
</p>

---

## 🧑‍💻 About Me

- 🔭 I'm a **Software Engineer** focused on **Backend** and **System Design**
- ⚡ Passionate about **distributed systems**, **scalability**, and **clean architecture**
- 🌍 Always learning, always building

---

## 🛠️ Tech Stack

**Languages**

![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)

**Frameworks**

![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)

**Databases**

![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

**DevOps & Tools**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=tokyonight&hide_border=true" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=YOUR_USERNAME&theme=tokyonight&hide_border=true" />
</p>

---

## 🤝 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](YOUR_LINKEDIN)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:YOUR_EMAIL)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=flat-square&logo=leetcode&logoColor=black)](YOUR_LEETCODE)
[![X](https://img.shields.io/badge/X-000000?style=flat-square&logo=x&logoColor=white)](YOUR_X)
[![Buy Me A Coffee](https://img.shields.io/badge/Buy_Me_A_Coffee-FFDD00?style=flat-square&logo=buymeacoffee&logoColor=black)](YOUR_BMC)

---

<p align="center"><em>"First, solve the problem. Then, write the code."</em></p>`;

const out = document.getElementById('readme-out');
out.textContent = readme;

function copyReadme(){
  navigator.clipboard.writeText(readme).then(()=>{
    const btn = document.querySelector('.copy-btn');
    btn.textContent = 'copied!';
    setTimeout(()=>btn.textContent='copy', 2000);
  });
}
</script>
