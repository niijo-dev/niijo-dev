<!-- Niijo GitHub Profile README -->

<!-- Banner: place the SVG below in your repo at ./assets/niijo-banner.svg and the image tag will render -->
<p align="center">
  <img src="./assets/niijo-banner.svg" alt="Niijo – Building the Future of AI in Nepal banner" />
</p>


<p align="center">
  <img src="https://img.shields.io/badge/Welcome%20to-Niijo-1abc9c?style=for-the-badge&logo=github" alt="Niijo Welcome Badge" />
</p>

<h1 align="center">🌟 Niijo – Building the Future of AI in Nepal 🇳🇵</h1>

<p align="center">
  <strong>Empowering Nepalese Students with AI, LLMs & Emerging Technologies</strong>
</p>

---

## 🎨 Brand Banner Asset (copy to `./assets/niijo-banner.svg`)

> **How to use:** Create a folder named `assets` in the root of your org profile repo (for example: `niijo/.github/profile/README.md` lives alongside `niijo/.github/profile/assets/niijo-banner.svg`). Save the SVG below as `niijo-banner.svg`. The banner reference at the top of this README will then render automatically on GitHub.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1600 400" role="img" aria-labelledby="title desc">
  <title id="title">Niijo – Building the Future of AI in Nepal</title>
  <desc id="desc">Gradient banner with Nepal mountains, circuit/AI nodes, and Niijo logotype.</desc>
  <defs>
    <!-- Brand Colors -->
    <!-- Primary Teal borrowed from shields (#1abc9c); tweak as needed -->
    <linearGradient id="niijoGradient" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#1abc9c"/>
      <stop offset="100%" stop-color="#16a085"/>
    </linearGradient>
    <linearGradient id="mountainShadow" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" stop-color="rgba(0,0,0,0.25)"/>
      <stop offset="100%" stop-color="rgba(0,0,0,0.65)"/>
    </linearGradient>
    <clipPath id="softMask">
      <rect x="0" y="0" width="1600" height="400" rx="32" ry="32"/>
    </clipPath>
    <filter id="glow" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="6" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <!-- Background -->
  <rect width="1600" height="400" fill="url(#niijoGradient)" clip-path="url(#softMask)"/>

  <!-- Abstract circuit network nodes -->
  <g stroke="rgba(255,255,255,0.25)" stroke-width="1.5" fill="none">
    <!-- simple procedural grid lines -->
    <path d="M100 80 L300 120 L500 60 L700 160 L900 100 L1100 180 L1300 140 L1500 200"/>
    <path d="M150 220 L350 200 L550 260 L750 220 L950 300 L1150 260 L1350 320 L1550 300"/>
    <path d="M80 330 L280 300 L480 340 L680 320 L880 360 L1080 340 L1280 360 L1480 340"/>
    <!-- connecting verticals -->
    <path d="M300 120 L350 200 L280 300"/>
    <path d="M700 160 L750 220 L680 320"/>
    <path d="M1100 180 L1150 260 L1080 340"/>
  </g>

  <!-- Nodes -->
  <g fill="rgba(255,255,255,0.85)" filter="url(#glow)">
    <circle cx="300" cy="120" r="5"/>
    <circle cx="700" cy="160" r="5"/>
    <circle cx="1100" cy="180" r="5"/>
    <circle cx="350" cy="200" r="5"/>
    <circle cx="750" cy="220" r="5"/>
    <circle cx="1150" cy="260" r="5"/>
  </g>

  <!-- Mountain silhouette (Nepal inspiration) -->
  <path d="M0 300 L200 250 L320 280 L500 200 L650 260 L800 180 L980 260 L1150 210 L1300 260 L1600 220 L1600 400 L0 400 Z" fill="url(#mountainShadow)"/>

  <!-- Nepal flag stylized (right side) -->
  <g transform="translate(1380,70) scale(0.8)">
    <!-- simplified triangular flag -->
    <path d="M0 0 L0 200 L150 140 L0 80 Z" fill="#DC143C" stroke="#ffffff" stroke-width="6"/>
    <!-- sun/moon icons simplified -->
    <circle cx="45" cy="60" r="22" fill="none" stroke="#ffffff" stroke-width="6"/>
    <circle cx="60" cy="150" r="28" fill="none" stroke="#ffffff" stroke-width="6"/>
  </g>

  <!-- Text Group -->
  <g font-family="'Segoe UI', 'Inter', 'Helvetica Neue', Arial, sans-serif" text-anchor="middle" fill="#ffffff">
    <text x="800" y="185" font-size="96" font-weight="700" letter-spacing="1">Niijo</text>
    <text x="800" y="235" font-size="36" font-weight="400" opacity="0.95">Building the Future of AI in Nepal</text>
    <text x="800" y="275" font-size="28" font-weight="300" opacity="0.85">Empowering Nepalese Students • AI Tools • LLMs • Agents</text>
  </g>

  <!-- Founders strip -->
  <g font-family="'Segoe UI', 'Inter', 'Helvetica Neue', Arial, sans-serif" fill="#ffffff" opacity="0.8" font-size="24" text-anchor="middle">
    <text x="800" y="330">Founded by Rajan Neupane &amp; Mukesh Adhikari</text>
  </g>
</svg>
```

---

## 🚀 About Us

**Niijo** is a tech-driven initiative founded by **Rajan Neupane** and **Mukesh Adhikari**, with a mission to empower Nepalese students and developers by providing:

- **Training on AI Tools** – Helping students master modern AI productivity tools.  
- **LLMs & AI Agents** – Exploring large language models, autonomous agents, and advanced AI systems.  
- **Tech Mentorship** – Guiding the next generation of developers and innovators in Nepal.  
- **Open Source Projects** – Creating real-world solutions for the local and global community.

---

## 🛠 Tech Stack We Love

<p align="center">
  <img src="https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/-JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/-Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/-Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white" />
  <img src="https://img.shields.io/badge/-LangChain-000000?style=for-the-badge&logo=chainlink&logoColor=white" />
  <img src="https://img.shields.io/badge/-OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/-Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white" />
</p>

---

## 👥 Founders

- **Rajan Neupane** – AI Enthusiast & Visionary Mentor  
- **Mukesh Adhikari** – Tech Explorer & Builder of Future Solutions  

---

## 📈 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=niijo&show_icons=true&theme=radical" alt="Niijo Stats" height="150" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=niijo&layout=compact&theme=radical" alt="Top Languages" height="150" />
</p>

---

## 🔗 Connect With Us

<p align="center">
  <a href="https://github.com/niijo">
    <img src="https://img.shields.io/badge/GitHub-Niijo-181717?style=for-the-badge&logo=github" alt="GitHub" />
  </a>
  <!-- Future links -->
  <img src="https://img.shields.io/badge/Website-Coming%20Soon-1abc9c?style=for-the-badge&logo=google-chrome" alt="Website Coming Soon" />
</p>

---

### ⭐ Let's build the future of AI – together!
<p align="center">With ❤️ from Nepal 🇳🇵</p>
