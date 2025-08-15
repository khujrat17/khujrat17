<!-- Interactive Galaxy Simulation -->
<p align="center" style="position: relative; overflow: hidden; height: 300px; background:#0d0d0d;">
  <svg width="100%" height="300" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <linearGradient id="grad" x1="0" y1="0" x2="1" y2="0">
        <stop offset="0%" stop-color="#ff8a00"/>
        <stop offset="50%" stop-color="#e52e71"/>
        <stop offset="100%" stop-color="#4a00e0"/>
      </linearGradient>
    </defs>

    <!-- Background Stars -->
    <rect width="100%" height="100%" fill="#0d0d0d" />
    <g>
      <!-- 20+ Moving Stars -->
      ${Array.from({length: 20}, (_, i) => `
        <circle cx="${Math.random()*100}%" cy="${Math.random()*100}%" r="${Math.random()*1.5+0.5}" fill="white">
          <animate attributeName="cy" values="0%;100%;0%" dur="${Math.random()*6+4}s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0;1;0" dur="${Math.random()*5+2}s" repeatCount="indefinite"/>
        </circle>
      `).join('')}
    </g>

    <!-- Center Text -->
    <text x="50%" y="50%" dominant-baseline="middle" text-anchor="middle"
          font-family="Arial, sans-serif" font-size="36"
          fill="url(#grad)" stroke="white" stroke-width="0.5"
          style="paint-order: stroke fill;">
      Hi 👋, I'm Khujrat Shaikh
    </text>
    <text x="50%" y="75%" dominant-baseline="middle" text-anchor="middle"
          font-family="Arial, sans-serif" font-size="20"
          fill="#ffffff" opacity="0.85">
      🚀 Full-Stack .NET Software Engineer | 2.5+ Years
    </text>
  </svg>
</p>

<!-- Animated Gradient Title -->
<h1 align="center">
  <span style="background: linear-gradient(90deg, #ff8a00, #e52e71, #9d50bb, #00c6ff);
               background-size: 400% 400%;
               -webkit-background-clip: text;
               color: transparent;
               animation: gradientMove 8s ease infinite;
               text-shadow: 0 0 25px rgba(255,255,255,0.3);">
    ✨ Hi 👋, I'm Khujrat Shaikh ✨
  </span>
</h1>

<!-- Social & Profile Badges -->
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=khujrat17&label=Profile%20Views&color=0e75b6&style=flat" alt="Profile Views" />
  <a href="https://www.linkedin.com/in/khujrat-shaikh-8823a5203/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin" />
  </a>
  <a href="mailto:khujratshaikh1284@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact%20Me-red?style=flat&logo=gmail" />
  </a>
</p>

---

## 🧑‍💻 About Me
- 💼 **Currently working at:** Net Protector Antivirus  
- 🛠 **Experience:** 2.5+ years building dynamic, scalable, secure web apps  
- 🌱 **Learning:** Advanced Web & AI Technologies  
- 🤝 **Open to Collaborations:** Full-Stack Projects  
- 💬 **Ask me about:** `.NET`, `C#`, `Angular`, `Full-Stack Development`  
- 📧 **Reach me at:** [khujratshaikh1284@gmail.com](mailto:khujratshaikh1284@gmail.com)  

---

## 🛠 Tech Stack
<p align="center">
  <img src="https://skillicons.dev/icons?i=cs,dotnet,angular,bootstrap,html,css,js,ajax,jquery,mysql,postman,git,github,visualstudio" />
</p>

---

## 📊 GitHub Stats
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=khujrat17&theme=dark&show_icons=true&count_private=true&hide_border=true" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=khujrat17&layout=compact&theme=dark&hide_border=true" height="165" />
</p>

---

## 🏆 GitHub Trophies
<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=khujrat17&theme=dark&no-frame=true&margin-w=5&row=1" />
</p>

<!-- Starry Footer -->
<p align="center">
  <img src="https://raw.githubusercontent.com/klaudiasiewert/Galaxy-Animation/main/stars.gif" width="100%" height="120" />
</p>

<style>
@keyframes gradientMove {
  0% { background-position: 0% 50%; }
  50% { background-position: 100% 50%; }
  100% { background-position: 0% 50%; }
}
body {
  background-color: #0d0d0d;
  color: #ffffff;
}
</style>
