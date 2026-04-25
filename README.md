<!-- TERMINAL HEADER SVG -->
<div align="center">

<svg width="800" height="160" viewBox="0 0 800 160" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="termGrad" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" style="stop-color:#0d1117;stop-opacity:1"/>
      <stop offset="100%" style="stop-color:#0a0f0a;stop-opacity:1"/>
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="2" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>

  <!-- Terminal window -->
  <rect width="800" height="160" rx="10" ry="10" fill="url(#termGrad)" stroke="#30363d" stroke-width="1"/>

  <!-- Title bar -->
  <rect width="800" height="36" rx="10" ry="10" fill="#161b22"/>
  <rect y="26" width="800" height="10" fill="#161b22"/>
  <rect y="36" width="800" height="1" fill="#30363d"/>

  <!-- Traffic lights -->
  <circle cx="20" cy="18" r="6" fill="#f85149" opacity="0.9"/>
  <circle cx="42" cy="18" r="6" fill="#e3b341" opacity="0.9"/>
  <circle cx="64" cy="18" r="6" fill="#4ade80" opacity="0.9"/>

  <!-- Title text -->
  <text x="400" y="23" text-anchor="middle" fill="#8b949e" font-family="'SF Mono', 'Fira Mono', monospace" font-size="12">bash — vishwesh@arch: ~</text>

  <!-- Boot lines -->
  <text x="24" y="65" fill="#4ade80" font-family="'SF Mono', 'Fira Mono', monospace" font-size="11" filter="url(#glow)">[  OK  ]</text>
  <text x="90" y="65" fill="#8b949e" font-family="'SF Mono', 'Fira Mono', monospace" font-size="11">Reached target — Multi-User System</text>

  <text x="24" y="82" fill="#4ade80" font-family="'SF Mono', 'Fira Mono', monospace" font-size="11" filter="url(#glow)">[  OK  ]</text>
  <text x="90" y="82" fill="#8b949e" font-family="'SF Mono', 'Fira Mono', monospace" font-size="11">Started — neovim.service (mouse.support: masked)</text>

  <text x="24" y="99" fill="#e3b341" font-family="'SF Mono', 'Fira Mono', monospace" font-size="11">[ WARN ]</text>
  <text x="90" y="99" fill="#8b949e" font-family="'SF Mono', 'Fira Mono', monospace" font-size="11">social-battery.service — low charge detected, continuing anyway</text>

  <text x="24" y="116" fill="#4ade80" font-family="'SF Mono', 'Fira Mono', monospace" font-size="11" filter="url(#glow)">[  OK  ]</text>
  <text x="90" y="116" fill="#8b949e" font-family="'SF Mono', 'Fira Mono', monospace" font-size="11">Started — coffee.service (mode: do-not-reduce)</text>

  <text x="24" y="133" fill="#4ade80" font-family="'SF Mono', 'Fira Mono', monospace" font-size="11" filter="url(#glow)">[  OK  ]</text>
  <text x="90" y="133" fill="#8b949e" font-family="'SF Mono', 'Fira Mono', monospace" font-size="11">Loaded — mesh-protocol.service (status: rebuilding, again)</text>

  <!-- Prompt -->
  <text x="24" y="152" fill="#4ade80" font-family="'SF Mono', 'Fira Mono', monospace" font-size="12" font-weight="bold" filter="url(#glow)">vishwesh@arch:~$</text>
  <text x="158" y="152" fill="#f0f0f0" font-family="'SF Mono', 'Fira Mono', monospace" font-size="12"> cat README.md</text>
  <rect x="270" y="141" width="8" height="13" fill="#4ade80" opacity="0.9">
    <animate attributeName="opacity" values="0.9;0;0.9" dur="1.1s" repeatCount="indefinite"/>
  </rect>
</svg>

</div>

<!-- TYPING SVG -->
<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=14&pause=1200&color=4ADE80&center=true&vCenter=true&width=680&lines=CE+undergrad+%40+MMCOE%2C+Pune+%2F%2F+IEEE+Member;arch+linux.+yes.+every+time.+unprompted.;neovim+user+%E2%80%94+mouse+support+disabled%2C+weakness+uninstalled;builds+things+offline-first+%E2%80%94+like+his+social+life;runner-up+%C3%973.+winner+%C3%971.+currently+rebuilding+the+mesh.;open+to+summer+2026+internships+%E2%86%97+hire+accordingly)](https://git.io/typing-svg)

</div>

<!-- SVG DIVIDER -->
<div align="center">
<svg width="800" height="20" viewBox="0 0 800 20" xmlns="http://www.w3.org/2000/svg">
  <line x1="0" y1="10" x2="340" y2="10" stroke="#21262d" stroke-width="1"/>
  <text x="400" y="15" text-anchor="middle" fill="#4ade80" font-family="'SF Mono', monospace" font-size="11" opacity="0.6">◈</text>
  <line x1="460" y1="10" x2="800" y2="10" stroke="#21262d" stroke-width="1"/>
</svg>
</div>

<br/>

## `$ whoami`

<img align="right" alt="Coding" width="320" src="https://user-images.githubusercontent.com/74038190/229223263-cf2e4b07-2615-4f87-9c38-e37600f8381a.gif"/>

```python
class VishweshBhilare:
    def __init__(self):
        self.role        = "CE Undergrad · IEEE Member"
        self.os          = "Arch Linux (you knew this was coming)"
        self.editor      = "neovim — mouse: disabled, weakness: uninstalled"
        self.location    = "Pune, India  ·  UTC+5:30"
        self.focus       = [
            "Systems & Embedded Engineering",
            "Local AI & Video Intelligence",
            "Offline-First Architecture",
            "Making sensors do unreasonable things",
        ]
        self.wip         = "rebuilding the mesh protocol. again. don't ask."
        self.seeking     = "Summer 2026 Internship (Systems · Infra · R&D)"
        self.compiles_at = "2am"

    def coffee(self) -> str:
        return "do not reduce."

    def __repr__(self) -> str:
        return "works offline — like me socially"
```

<br clear="both"/>

<!-- SVG DIVIDER -->
<div align="center">
<svg width="800" height="20" viewBox="0 0 800 20" xmlns="http://www.w3.org/2000/svg">
  <line x1="0" y1="10" x2="340" y2="10" stroke="#21262d" stroke-width="1"/>
  <text x="400" y="15" text-anchor="middle" fill="#4ade80" font-family="'SF Mono', monospace" font-size="11" opacity="0.6">◈</text>
  <line x1="460" y1="10" x2="800" y2="10" stroke="#21262d" stroke-width="1"/>
</svg>
</div>

## `$ ls ~/projects/ -1`

<!-- WIP BADGE SVG -->
<div align="center">
<svg width="480" height="36" viewBox="0 0 480 36" xmlns="http://www.w3.org/2000/svg">
  <rect width="480" height="36" rx="6" fill="#0d1117" stroke="#fbbf2440" stroke-width="1"/>
  <circle cx="16" cy="18" r="4" fill="#fbbf24">
    <animate attributeName="opacity" values="1;0.2;1" dur="1.8s" repeatCount="indefinite"/>
  </circle>
  <text x="28" y="23" fill="#fbbf24" font-family="'SF Mono', monospace" font-size="11" font-weight="600">WIP</text>
  <text x="60" y="23" fill="#8b949e" font-family="'SF Mono', monospace" font-size="11">mesh-protocol.service — migrating to cleaner framework</text>
</svg>
</div>

<br/>

<div align="center">

| `project` | `stack` | `result` |
|:---|:---|:---|
| **[SceneForge](https://github.com/Vishwesh-Bhilare/SceneForge)** | YOLOv8 · SAM · ControlNet · SD | removes players from live football footage. offline. ~60% SSIM. no, i won't explain why. |
| **[ReachlyEngine](https://github.com/Vishwesh-Bhilare/ReachlyEngine)** | Python · Ollama · SQLite | local LLM outreach engine. zero cloud. zero shame. four channels. one persona. |
| **Mesh Protocol** | Embedded · BLE / LoRa | internet-free mesh with TTL routing. built for when civilization has a bad day. |
| **[XGestura](https://github.com/Vishwesh-Bhilare/XGestura)** | C++ · ESP32 · MPU6050 | glove → IMU → bluetooth → HID. you wave. PC obeys. jedi energy. |
| **ExamCell Tool** | MMCOE · IEEE | exam cell automation. deployed live. 3 days. no fatalities. shipped. |

</div>

<!-- SVG DIVIDER -->
<div align="center">
<svg width="800" height="20" viewBox="0 0 800 20" xmlns="http://www.w3.org/2000/svg">
  <line x1="0" y1="10" x2="340" y2="10" stroke="#21262d" stroke-width="1"/>
  <text x="400" y="15" text-anchor="middle" fill="#4ade80" font-family="'SF Mono', monospace" font-size="11" opacity="0.6">◈</text>
  <line x1="460" y1="10" x2="800" y2="10" stroke="#21262d" stroke-width="1"/>
</svg>
</div>

## `$ cat ~/skills.txt`

<div align="center">

[![My Skills](https://skillicons.dev/icons?i=cpp,c,python,java,linux,neovim,git,arduino,opencv,pytorch&theme=dark&perline=10)](https://skillicons.dev)

[![My Skills](https://skillicons.dev/icons?i=sqlite,github,bash,raspberrypi&theme=dark&perline=10)](https://skillicons.dev)

</div>

<div align="center">

<!-- Extra badges for things skillicons doesn't cover -->
![YOLOv8](https://img.shields.io/badge/YOLOv8-00FFFF?style=flat-square&logo=yolo&logoColor=black)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![Stable Diffusion](https://img.shields.io/badge/Stable_Diffusion-FF6B6B?style=flat-square&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![BLE](https://img.shields.io/badge/BLE-0082FC?style=flat-square&logo=bluetooth&logoColor=white)
![LoRa](https://img.shields.io/badge/LoRa-FF6600?style=flat-square&logoColor=white)
![SAM](https://img.shields.io/badge/SAM-5C3EE8?style=flat-square&logoColor=white)
![Mesh Protocols](https://img.shields.io/badge/Mesh_Protocols-4ADE80?style=flat-square&logoColor=black)

</div>

<!-- SVG DIVIDER -->
<div align="center">
<svg width="800" height="20" viewBox="0 0 800 20" xmlns="http://www.w3.org/2000/svg">
  <line x1="0" y1="10" x2="340" y2="10" stroke="#21262d" stroke-width="1"/>
  <text x="400" y="15" text-anchor="middle" fill="#4ade80" font-family="'SF Mono', monospace" font-size="11" opacity="0.6">◈</text>
  <line x1="460" y1="10" x2="800" y2="10" stroke="#21262d" stroke-width="1"/>
</svg>
</div>

## `$ cat ~/achievements.log`

<div align="center">

<!-- Achievements SVG card -->
<svg width="720" height="210" viewBox="0 0 720 210" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="cardGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0d1117"/>
      <stop offset="100%" style="stop-color:#0a0f0a"/>
    </linearGradient>
  </defs>
  <rect width="720" height="210" rx="8" fill="url(#cardGrad)" stroke="#21262d" stroke-width="1"/>

  <!-- Left accent bar -->
  <rect x="0" y="0" width="3" height="210" rx="2" fill="#4ade80" opacity="0.6"/>

  <!-- Header -->
  <text x="20" y="28" fill="#4ade80" font-family="'SF Mono', monospace" font-size="11" opacity="0.6">── competitions</text>
  <line x1="150" y1="22" x2="700" y2="22" stroke="#21262d" stroke-width="1"/>

  <!-- WIN row -->
  <rect x="16" y="38" width="44" height="18" rx="3" fill="#4ade8020" stroke="#4ade8040" stroke-width="1"/>
  <text x="38" y="51" text-anchor="middle" fill="#4ade80" font-family="'SF Mono', monospace" font-size="10" font-weight="700">WIN</text>
  <text x="72" y="51" fill="#f0f0f0" font-family="'SF Mono', monospace" font-size="11">In-house Project Competition</text>
  <text x="310" y="51" fill="#4ade80" font-family="'SF Mono', monospace" font-size="11">──  MMCOE</text>
  <text x="430" y="51" fill="#8b949e" font-family="'SF Mono', monospace" font-size="10">deployed live. still standing.</text>

  <!-- #2 rows -->
  <rect x="16" y="64" width="44" height="18" rx="3" fill="#e3b34120" stroke="#e3b34140" stroke-width="1"/>
  <text x="38" y="77" text-anchor="middle" fill="#e3b341" font-family="'SF Mono', monospace" font-size="10" font-weight="700">#2</text>
  <text x="72" y="77" fill="#f0f0f0" font-family="'SF Mono', monospace" font-size="11">Xenia '26</text>
  <text x="310" y="77" fill="#4ade80" font-family="'SF Mono', monospace" font-size="11">──  PICT</text>
  <text x="430" y="77" fill="#8b949e" font-family="'SF Mono', monospace" font-size="10">we don't talk about #1.</text>

  <rect x="16" y="90" width="44" height="18" rx="3" fill="#e3b34120" stroke="#e3b34140" stroke-width="1"/>
  <text x="38" y="103" text-anchor="middle" fill="#e3b341" font-family="'SF Mono', monospace" font-size="10" font-weight="700">#2</text>
  <text x="72" y="103" fill="#f0f0f0" font-family="'SF Mono', monospace" font-size="11">Avinya 2k26</text>
  <text x="310" y="103" fill="#4ade80" font-family="'SF Mono', monospace" font-size="11">──  IEEE MMCOE</text>
  <text x="430" y="103" fill="#8b949e" font-family="'SF Mono', monospace" font-size="10">we don't talk about #1.</text>

  <rect x="16" y="116" width="44" height="18" rx="3" fill="#e3b34120" stroke="#e3b34140" stroke-width="1"/>
  <text x="38" y="129" text-anchor="middle" fill="#e3b341" font-family="'SF Mono', monospace" font-size="10" font-weight="700">#2</text>
  <text x="72" y="129" fill="#f0f0f0" font-family="'SF Mono', monospace" font-size="11">UI/UX Challenge</text>
  <text x="310" y="129" fill="#4ade80" font-family="'SF Mono', monospace" font-size="11">──  WebsiteVikreta</text>
  <text x="430" y="129" fill="#8b949e" font-family="'SF Mono', monospace" font-size="10">we don't talk about #1.</text>

  <!-- Cert section -->
  <text x="20" y="160" fill="#4ade80" font-family="'SF Mono', monospace" font-size="11" opacity="0.6">── certification</text>
  <line x1="152" y1="154" x2="700" y2="154" stroke="#21262d" stroke-width="1"/>

  <rect x="16" y="168" width="44" height="18" rx="3" fill="#f8519420" stroke="#f8519440" stroke-width="1"/>
  <text x="38" y="181" text-anchor="middle" fill="#f85149" font-family="'SF Mono', monospace" font-size="9" font-weight="700">OCI</text>
  <text x="72" y="181" fill="#f0f0f0" font-family="'SF Mono', monospace" font-size="11">Oracle Cloud Infrastructure 2025 Generative AI Professional</text>
  <text x="72" y="198" fill="#8b949e" font-family="'SF Mono', monospace" font-size="10">ID: 323468573OCI25GAIOCP  ·  valid 2025–2027  ·  yes, it's real. i was surprised too.</text>
</svg>

<br/>

> *runner-up ×3 independently in the same year is either a pattern or a conspiracy. investigating.*

</div>

<!-- SVG DIVIDER -->
<div align="center">
<svg width="800" height="20" viewBox="0 0 800 20" xmlns="http://www.w3.org/2000/svg">
  <line x1="0" y1="10" x2="340" y2="10" stroke="#21262d" stroke-width="1"/>
  <text x="400" y="15" text-anchor="middle" fill="#4ade80" font-family="'SF Mono', monospace" font-size="11" opacity="0.6">◈</text>
  <line x1="460" y1="10" x2="800" y2="10" stroke="#21262d" stroke-width="1"/>
</svg>
</div>

<!-- MATRIX GIF — the machine breathes -->
<div align="center">
  <img src="https://media.giphy.com/media/l0MYt5jPR6QX5pnqM/giphy.gif" width="100%" alt="the machine breathes"/>
</div>

<!-- SVG DIVIDER -->
<div align="center">
<svg width="800" height="20" viewBox="0 0 800 20" xmlns="http://www.w3.org/2000/svg">
  <line x1="0" y1="10" x2="340" y2="10" stroke="#21262d" stroke-width="1"/>
  <text x="400" y="15" text-anchor="middle" fill="#4ade80" font-family="'SF Mono', monospace" font-size="11" opacity="0.6">◈</text>
  <line x1="460" y1="10" x2="800" y2="10" stroke="#21262d" stroke-width="1"/>
</svg>
</div>

## `$ github --stats`

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Vishwesh-Bhilare&show_icons=true&theme=chartreuse-dark&border_color=4ADE80&title_color=4ADE80&icon_color=4ADE80&hide_border=false&rank_icon=github" height="165"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs?username=Vishwesh-Bhilare&layout=compact&theme=chartreuse-dark&border_color=4ADE80&title_color=4ADE80&hide_border=false" height="165"/>

</div>

<div align="center">

![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=Vishwesh-Bhilare&theme=github-compact&hide_border=false&area=true&color=4ADE80&line=4ADE80&point=ffffff&custom_title=commit+history+%2F%2F+mostly+2am)

</div>

<!-- SVG DIVIDER -->
<div align="center">
<svg width="800" height="20" viewBox="0 0 800 20" xmlns="http://www.w3.org/2000/svg">
  <line x1="0" y1="10" x2="340" y2="10" stroke="#21262d" stroke-width="1"/>
  <text x="400" y="15" text-anchor="middle" fill="#4ade80" font-family="'SF Mono', monospace" font-size="11" opacity="0.6">◈</text>
  <line x1="460" y1="10" x2="800" y2="10" stroke="#21262d" stroke-width="1"/>
</svg>
</div>

## `$ uptime --human`

<div align="center">

<!-- Uptime SVG card -->
<svg width="620" height="162" viewBox="0 0 620 162" xmlns="http://www.w3.org/2000/svg">
  <rect width="620" height="162" rx="8" fill="#0d1117" stroke="#21262d" stroke-width="1"/>
  <rect x="0" y="0" width="3" height="162" rx="2" fill="#4ade80" opacity="0.5"/>

  <!-- Row 1 -->
  <text x="18" y="32" fill="#8b949e" font-family="'SF Mono', monospace" font-size="11">social battery</text>
  <text x="160" y="32" fill="#30363d" font-family="'SF Mono', monospace" font-size="11">▓▓░░░░░░░░░░░░░░</text>
  <text x="160" y="32" fill="#f85149" font-family="'SF Mono', monospace" font-size="11">▓▓</text>
  <text x="330" y="32" fill="#8b949e" font-family="'SF Mono', monospace" font-size="10">critically low — DMs still open though</text>

  <!-- Row 2 -->
  <text x="18" y="58" fill="#8b949e" font-family="'SF Mono', monospace" font-size="11">coffee intake</text>
  <text x="160" y="58" fill="#30363d" font-family="'SF Mono', monospace" font-size="11">▓▓▓▓▓▓▓▓▓▓▓▓░░░░</text>
  <text x="160" y="58" fill="#e3b341" font-family="'SF Mono', monospace" font-size="11">▓▓▓▓▓▓▓▓▓▓▓▓</text>
  <text x="330" y="58" fill="#8b949e" font-family="'SF Mono', monospace" font-size="10">stable. do not reduce.</text>

  <!-- Row 3 -->
  <text x="18" y="84" fill="#8b949e" font-family="'SF Mono', monospace" font-size="11">currently wip</text>
  <text x="160" y="84" fill="#30363d" font-family="'SF Mono', monospace" font-size="11">▓▓▓▓▓▓▓░░░░░░░░░</text>
  <text x="160" y="84" fill="#58a6ff" font-family="'SF Mono', monospace" font-size="11">▓▓▓▓▓▓▓</text>
  <text x="330" y="84" fill="#8b949e" font-family="'SF Mono', monospace" font-size="10">rebuilding the mesh protocol (again)</text>

  <!-- Row 4 -->
  <text x="18" y="110" fill="#8b949e" font-family="'SF Mono', monospace" font-size="11">nvim config</text>
  <text x="160" y="110" fill="#4ade80" font-family="'SF Mono', monospace" font-size="11">▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓</text>
  <text x="330" y="110" fill="#8b949e" font-family="'SF Mono', monospace" font-size="10">never finished. never will be. that's the point.</text>

  <!-- Row 5 -->
  <text x="18" y="136" fill="#8b949e" font-family="'SF Mono', monospace" font-size="11">internship hunt</text>
  <text x="160" y="136" fill="#30363d" font-family="'SF Mono', monospace" font-size="11">▓▓▓▓▓▓▓▓▓▓▓░░░░░</text>
  <text x="160" y="136" fill="#4ade80" font-family="'SF Mono', monospace" font-size="11">▓▓▓▓▓▓▓▓▓▓▓</text>
  <text x="330" y="136" fill="#4ade80" font-family="'SF Mono', monospace" font-size="10">actively seeking summer 2026 — hire accordingly ↗</text>

  <!-- Row dividers -->
  <line x1="16" y1="40" x2="604" y2="40" stroke="#21262d" stroke-width="0.5"/>
  <line x1="16" y1="66" x2="604" y2="66" stroke="#21262d" stroke-width="0.5"/>
  <line x1="16" y1="92" x2="604" y2="92" stroke="#21262d" stroke-width="0.5"/>
  <line x1="16" y1="118" x2="604" y2="118" stroke="#21262d" stroke-width="0.5"/>
</svg>

</div>

<!-- SVG DIVIDER -->
<div align="center">
<svg width="800" height="20" viewBox="0 0 800 20" xmlns="http://www.w3.org/2000/svg">
  <line x1="0" y1="10" x2="340" y2="10" stroke="#21262d" stroke-width="1"/>
  <text x="400" y="15" text-anchor="middle" fill="#4ade80" font-family="'SF Mono', monospace" font-size="11" opacity="0.6">◈</text>
  <line x1="460" y1="10" x2="800" y2="10" stroke="#21262d" stroke-width="1"/>
</svg>
</div>

## `$ cat ~/contact.txt`

<div align="center">

<!-- Contact SVG card -->
<svg width="580" height="130" viewBox="0 0 580 130" xmlns="http://www.w3.org/2000/svg">
  <rect width="580" height="130" rx="8" fill="#0d1117" stroke="#21262d" stroke-width="1"/>
  <rect x="0" y="0" width="3" height="130" rx="2" fill="#4ade80" opacity="0.5"/>

  <!-- Email -->
  <text x="20" y="32" fill="#4ade80" font-family="'SF Mono', monospace" font-size="11">email</text>
  <text x="90" y="32" fill="#8b949e" font-family="'SF Mono', monospace" font-size="11">·</text>
  <text x="106" y="32" fill="#f0f0f0" font-family="'SF Mono', monospace" font-size="11">bhilarevishwesh@gmail.com</text>

  <!-- GitHub -->
  <text x="20" y="56" fill="#4ade80" font-family="'SF Mono', monospace" font-size="11">github</text>
  <text x="90" y="56" fill="#8b949e" font-family="'SF Mono', monospace" font-size="11">·</text>
  <text x="106" y="56" fill="#f0f0f0" font-family="'SF Mono', monospace" font-size="11">github.com/Vishwesh-Bhilare</text>

  <!-- LinkedIn -->
  <text x="20" y="80" fill="#4ade80" font-family="'SF Mono', monospace" font-size="11">linkedin</text>
  <text x="90" y="80" fill="#8b949e" font-family="'SF Mono', monospace" font-size="11">·</text>
  <text x="106" y="80" fill="#f0f0f0" font-family="'SF Mono', monospace" font-size="11">linkedin.com/in/vishwesh-bhilare</text>

  <!-- Website -->
  <text x="20" y="104" fill="#4ade80" font-family="'SF Mono', monospace" font-size="11">web</text>
  <text x="90" y="104" fill="#8b949e" font-family="'SF Mono', monospace" font-size="11">·</text>
  <text x="106" y="104" fill="#f0f0f0" font-family="'SF Mono', monospace" font-size="11">vishweshbh.in</text>

  <!-- dividers -->
  <line x1="16" y1="40" x2="564" y2="40" stroke="#21262d" stroke-width="0.5"/>
  <line x1="16" y1="64" x2="564" y2="64" stroke="#21262d" stroke-width="0.5"/>
  <line x1="16" y1="88" x2="564" y2="88" stroke="#21262d" stroke-width="0.5"/>
</svg>

<br/>

[![Email](https://img.shields.io/badge/─_Email-4ADE80?style=for-the-badge&logo=gmail&logoColor=black)](mailto:bhilarevishwesh@gmail.com)
[![LinkedIn](https://img.shields.io/badge/─_LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/vishwesh-bhilare)
[![GitHub](https://img.shields.io/badge/─_GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Vishwesh-Bhilare)
[![Portfolio](https://img.shields.io/badge/─_Portfolio-4ADE80?style=for-the-badge&logo=googlechrome&logoColor=black)](https://vishweshbh.in)

</div>

<!-- SVG DIVIDER -->
<div align="center">
<svg width="800" height="20" viewBox="0 0 800 20" xmlns="http://www.w3.org/2000/svg">
  <line x1="0" y1="10" x2="340" y2="10" stroke="#21262d" stroke-width="1"/>
  <text x="400" y="15" text-anchor="middle" fill="#4ade80" font-family="'SF Mono', monospace" font-size="11" opacity="0.6">◈</text>
  <line x1="460" y1="10" x2="800" y2="10" stroke="#21262d" stroke-width="1"/>
</svg>
</div>

<div align="center">

![Snake animation](https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake-dark.svg)

</div>

<!-- SHUTDOWN SEQUENCE SVG -->
<div align="center">

<svg width="680" height="110" viewBox="0 0 680 110" xmlns="http://www.w3.org/2000/svg">
  <rect width="680" height="110" rx="8" fill="#0d1117" stroke="#21262d" stroke-width="1"/>
  <rect x="0" y="0" width="3" height="110" rx="2" fill="#f85149" opacity="0.4"/>

  <text x="20" y="28" fill="#4ade80" font-family="'SF Mono', monospace" font-size="12" font-weight="bold">vishwesh@arch:~$</text>
  <text x="170" y="28" fill="#f0f0f0" font-family="'SF Mono', monospace" font-size="12"> sudo shutdown -h now</text>

  <text x="20" y="50" fill="#8b949e" font-family="'SF Mono', monospace" font-size="11">[  OK  ] Stopped — readme.service</text>
  <text x="20" y="68" fill="#8b949e" font-family="'SF Mono', monospace" font-size="11">[  OK  ] Reached target — Shutdown</text>
  <text x="20" y="86" fill="#8b949e" font-family="'SF Mono', monospace" font-size="11">         thanks for reading. touch grass. or hire me. preferably both.</text>

  <text x="20" y="104" fill="#4ade80" font-family="'SF Mono', monospace" font-size="10" opacity="0.5">-- System halted. --</text>
  <rect x="452" y="93" width="7" height="12" fill="#4ade80" opacity="0.7">
    <animate attributeName="opacity" values="0.7;0;0.7" dur="1.1s" repeatCount="indefinite"/>
  </rect>
</svg>

<br/>

[![Visitors](https://komarev.com/ghpvc/?username=Vishwesh-Bhilare&label=profile+views&color=4ADE80&style=flat-square)](https://github.com/Vishwesh-Bhilare)

</div>
