<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Godwin J // Cybersecurity • Software Developer • Audio Engineer</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Fira+Code:wght@400;500;600;700&family=Outfit:wght@400;600;700;800;900&family=Space+Grotesk:wght@400;500;600;700&display=swap" rel="stylesheet">
  <style>
    :root {
      --bg-dark: #070b12;
      --card-bg: rgba(13, 21, 37, 0.75);
      --card-border: rgba(0, 242, 254, 0.18);
      --cyber-cyan: #00f2fe;
      --terminal-green: #00ff88;
      --audio-amber: #ffb703;
      --peak-red: #ff3366;
      --gold: #ffd700;
      --text: #f0f6fc;
      --text-muted: #8ca0ba;
    }
    body {
      background-color: var(--bg-dark);
      color: var(--text);
      font-family: 'Space Grotesk', -apple-system, sans-serif;
      margin: 0;
      padding: 24px 16px 80px;
      line-height: 1.6;
    }
    .profile-container {
      max-width: 920px;
      margin: 0 auto;
    }
    /* SVG Equalizer Animation */
    @keyframes eqBarPulse {
      0%, 100% { transform: scaleY(0.2); }
      50% { transform: scaleY(1); }
    }
    @keyframes waveOscillate {
      0% { stroke-dashoffset: 0; }
      100% { stroke-dashoffset: 900; }
    }
    @keyframes signalPulse {
      0% { left: 0%; opacity: 0; }
      20% { opacity: 1; }
      80% { opacity: 1; }
      100% { left: 95%; opacity: 0; }
    }
    @keyframes glowBlink {
      0%, 100% { opacity: 1; filter: drop-shadow(0 0 6px var(--terminal-green)); }
      50% { opacity: 0.4; filter: drop-shadow(0 0 1px var(--terminal-green)); }
    }
    .eq-bar {
      transform-origin: bottom;
      animation: eqBarPulse 1.2s ease-in-out infinite alternate;
    }
    .card {
      background: var(--card-bg);
      border: 1px solid var(--card-border);
      border-radius: 14px;
      padding: 20px 24px;
      margin-bottom: 24px;
      backdrop-filter: blur(12px);
      transition: transform 0.2s ease, border-color 0.2s ease;
    }
    .card:hover {
      transform: translateY(-2px);
      border-color: var(--cyber-cyan);
    }
    .signal-chain-box {
      background: #04070d;
      border: 1px solid rgba(255, 183, 3, 0.25);
      border-radius: 12px;
      padding: 16px;
      margin: 16px 0;
      overflow-x: auto;
    }
    .cable-flow {
      position: relative;
      height: 4px;
      background: rgba(255,255,255,0.1);
      border-radius: 2px;
      margin: 12px 0;
    }
    .cable-flow::after {
      content: '';
      position: absolute;
      top: -2px;
      left: 0;
      width: 24px;
      height: 8px;
      border-radius: 4px;
      background: linear-gradient(90deg, var(--audio-amber), var(--terminal-green));
      box-shadow: 0 0 8px var(--terminal-green);
      animation: signalPulse 2.4s linear infinite;
    }
  </style>
</head>
<body>

<div class="profile-container">

<div align="center">

  <!-- ══════════════════════════════════════════════════════════════════
       ANIMATED CYBER-AUDIO HERO BANNER (Capsule Render Waving Waveform)
       ══════════════════════════════════════════════════════════════════ -->
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0:00f2fe,2:4facfe,6:00ff88,10:ffb703&height=220&section=header&text=GODWIN%20J&fontSize=62&fontAlignY=36&fontColor=ffffff&desc=Cybersecurity%20%E2%80%A2%20Software%20Developer%20%E2%80%A2%20Audio%20Engineer&descFontSize=20&descAlignY=58&descAlign=50&animation=twinkling" width="100%" alt="Godwin J Banner" />

  <h3 align="center" style="font-family:'Outfit',sans-serif; margin-top:10px;">
    🛡️ Cybersecurity Student &nbsp;|&nbsp; 💻 Software Developer &nbsp;|&nbsp; 🎚️ Live Sound & Audio Engineer
  </h3>

  <p align="center" style="font-size: 1.1em; color: #a0aec0;">
    <strong>Securing systems. Building solutions. Shaping sound.</strong>
  </p>

  <!-- ══════════════════════════════════════════════════════════════════
       LIVE SYSTEM & AUDIO TELEMETRY STATUS PILLS
       ══════════════════════════════════════════════════════════════════ -->
  <p align="center">
    <a href="https://github.com/Godwin-J-08">
      <img src="https://img.shields.io/badge/SYSTEM-SECURED%20%2F%2F%20ONLINE-00ff88?style=for-the-badge&logo=gnubash&logoColor=black&labelColor=0a101d" alt="System Status" />
    </a>
    <a href="#-live-sound--audio-engineering">
      <img src="https://img.shields.io/badge/LIVE%20SOUND-25%2B%20SHOWS%20MIXED-ffb703?style=for-the-badge&logo=apple&logoColor=white&labelColor=0a101d" alt="Live Sound" />
    </a>
    <a href="https://github.com/AUSTIN-JR/AUTOBOTZZ-Proof-Carrying-Data-Analyst">
      <img src="https://img.shields.io/badge/AI%20VERIFICATION-AUTOBOTZZ%20QUALIFIER-00f2fe?style=for-the-badge&logo=python&logoColor=white&labelColor=0a101d" alt="AUTOBOTZZ" />
    </a>
    <a href="#-beyond-the-code">
      <img src="https://img.shields.io/badge/ATHLETICS-STATE%20THROWBALL%20MEDALIST-ffd700?style=for-the-badge&logo=target&logoColor=black&labelColor=0a101d" alt="State Medalist" />
    </a>
  </p>

  <!-- ══════════════════════════════════════════════════════════════════
       DYNAMIC MULTI-LINE TYPING ANIMATION (THEMED TO PILLARS)
       ══════════════════════════════════════════════════════════════════ -->
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=2600&pause=900&color=00F2FE&center=true&vCenter=true&width=860&lines=B.Tech+CSE+%7C+Cybersecurity+Specialization+@+Karunya;Software+Development+%26+Adversarial+Data+Benchmarking;25%2B+Live+Events+Mixed+%7C+Behringer+WING+%26+MIDAS+M32;Live+Sound+Routing+%E2%80%A2+S32+Stagebox+%E2%80%A2+Waves+SuperRack;AUTOBOTZZ+%7C+Proof-Carrying+Data+Analyst+(HackNex);State-Level+Throwball+Athlete+%E2%80%A2+Gold+%26+Bronze+Medalist" alt="Typing SVG Animation" />
  </a>

  <!-- ══════════════════════════════════════════════════════════════════
       ANIMATED CYBER-AUDIO WAVEFORM & VU EQUALIZER (INLINE ANIMATED SVG)
       ══════════════════════════════════════════════════════════════════ -->
  <svg width="100%" max-width="860" height="90" viewBox="0 0 860 90" xmlns="http://www.w3.org/2000/svg" style="margin: 12px 0 16px;">
    <defs>
      <linearGradient id="eqGradient" x1="0%" y1="100%" x2="0%" y2="0%">
        <stop offset="0%" stop-color="#00ff88" />
        <stop offset="60%" stop-color="#00f2fe" />
        <stop offset="82%" stop-color="#ffb703" />
        <stop offset="98%" stop-color="#ff3366" />
      </linearGradient>
      <linearGradient id="waveGrad" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#00f2fe" />
        <stop offset="40%" stop-color="#00ff88" />
        <stop offset="75%" stop-color="#ffb703" />
        <stop offset="100%" stop-color="#ff3366" />
      </linearGradient>
      <filter id="neonGlow" x="-20%" y="-20%" width="140%" height="140%">
        <feGaussianBlur stdDeviation="3" result="blur" />
        <feComposite in="SourceGraphic" in2="blur" operator="over" />
      </filter>
    </defs>

    <style>
      .eq-b1 { animation: eqBarPulse 1.0s ease-in-out infinite alternate; animation-delay: 0.1s; transform-origin: 0 75px; }
      .eq-b2 { animation: eqBarPulse 0.8s ease-in-out infinite alternate; animation-delay: 0.3s; transform-origin: 0 75px; }
      .eq-b3 { animation: eqBarPulse 1.4s ease-in-out infinite alternate; animation-delay: 0.0s; transform-origin: 0 75px; }
      .eq-b4 { animation: eqBarPulse 0.9s ease-in-out infinite alternate; animation-delay: 0.4s; transform-origin: 0 75px; }
      .eq-b5 { animation: eqBarPulse 1.2s ease-in-out infinite alternate; animation-delay: 0.2s; transform-origin: 0 75px; }
      .eq-b6 { animation: eqBarPulse 0.7s ease-in-out infinite alternate; animation-delay: 0.5s; transform-origin: 0 75px; }
      .eq-b7 { animation: eqBarPulse 1.1s ease-in-out infinite alternate; animation-delay: 0.15s; transform-origin: 0 75px; }
      .eq-b8 { animation: eqBarPulse 0.85s ease-in-out infinite alternate; animation-delay: 0.35s; transform-origin: 0 75px; }
      .oscilloscope-line {
        stroke-dasharray: 860;
        animation: waveOscillate 4s linear infinite;
      }
    </style>

    <!-- Background Plate -->
    <rect x="5" y="5" width="850" height="80" rx="8" fill="#080e1a" stroke="rgba(0, 242, 254, 0.25)" stroke-width="1" />

    <!-- Oscilloscope Harmonic Sine Wave Curve -->
    <path class="oscilloscope-line" d="M 15 45 Q 65 15, 115 45 T 215 45 T 315 45 T 415 45 T 515 45 T 615 45 T 715 45 T 815 45 T 845 45" fill="none" stroke="url(#waveGrad)" stroke-width="2" opacity="0.65" filter="url(#neonGlow)" />

    <!-- 24-Band Graphic Equalizer VU Spectrum -->
    <g fill="url(#eqGradient)">
      <rect class="eq-b1" x="40"  y="20" width="8" height="55" rx="2" />
      <rect class="eq-b3" x="72"  y="15" width="8" height="60" rx="2" />
      <rect class="eq-b2" x="104" y="24" width="8" height="51" rx="2" />
      <rect class="eq-b5" x="136" y="12" width="8" height="63" rx="2" />
      <rect class="eq-b4" x="168" y="28" width="8" height="47" rx="2" />
      <rect class="eq-b7" x="200" y="18" width="8" height="57" rx="2" />
      <rect class="eq-b6" x="232" y="10" width="8" height="65" rx="2" />
      <rect class="eq-b2" x="264" y="22" width="8" height="53" rx="2" />
      <rect class="eq-b8" x="296" y="14" width="8" height="61" rx="2" />
      <rect class="eq-b3" x="328" y="26" width="8" height="49" rx="2" />
      <rect class="eq-b1" x="360" y="16" width="8" height="59" rx="2" />
      <rect class="eq-b5" x="392" y="10" width="8" height="65" rx="2" />
      <rect class="eq-b4" x="424" y="20" width="8" height="55" rx="2" />
      <rect class="eq-b7" x="456" y="14" width="8" height="61" rx="2" />
      <rect class="eq-b2" x="488" y="25" width="8" height="50" rx="2" />
      <rect class="eq-b6" x="520" y="12" width="8" height="63" rx="2" />
      <rect class="eq-b8" x="552" y="22" width="8" height="53" rx="2" />
      <rect class="eq-b3" x="584" y="15" width="8" height="60" rx="2" />
      <rect class="eq-b1" x="616" y="28" width="8" height="47" rx="2" />
      <rect class="eq-b5" x="648" y="18" width="8" height="57" rx="2" />
      <rect class="eq-b4" x="680" y="24" width="8" height="51" rx="2" />
      <rect class="eq-b7" x="712" y="11" width="8" height="64" rx="2" />
      <rect class="eq-b2" x="744" y="20" width="8" height="55" rx="2" />
      <rect class="eq-b6" x="776" y="16" width="8" height="59" rx="2" />
      <rect class="eq-b3" x="808" y="27" width="8" height="48" rx="2" />
    </g>

    <!-- Telemetry Markers & Frequency Axis -->
    <text x="40" y="82" fill="#54657e" font-family="'Fira Code', monospace" font-size="9">32Hz</text>
    <text x="136" y="82" fill="#54657e" font-family="'Fira Code', monospace" font-size="9">125Hz</text>
    <text x="264" y="82" fill="#54657e" font-family="'Fira Code', monospace" font-size="9">500Hz</text>
    <text x="392" y="82" fill="#00f2fe" font-family="'Fira Code', monospace" font-size="9" font-weight="bold">1kHz (VOCAL)</text>
    <text x="552" y="82" fill="#54657e" font-family="'Fira Code', monospace" font-size="9">4kHz</text>
    <text x="680" y="82" fill="#54657e" font-family="'Fira Code', monospace" font-size="9">8kHz</text>
    <text x="776" y="82" fill="#ffb703" font-family="'Fira Code', monospace" font-size="9">16kHz AIR</text>
  </svg>

  <!-- GitHub Metrics & Engagement -->
  <p align="center">
    <a href="https://github.com/Godwin-J-08?tab=followers">
      <img src="https://img.shields.io/github/followers/Godwin-J-08?style=for-the-badge&logo=github&label=Followers&color=00f2fe&labelColor=0d1525" alt="GitHub Followers" />
    </a>
    <a href="https://github.com/Godwin-J-08?tab=repositories">
      <img src="https://img.shields.io/github/stars/Godwin-J-08?style=for-the-badge&logo=github&label=Stars&color=ffb703&labelColor=0d1525" alt="GitHub Stars" />
    </a>
    <a href="https://github.com/Godwin-J-08">
      <img src="https://komarev.com/ghpvc/?username=Godwin-J-08&style=for-the-badge&color=00ff88&label=PROFILE%20VIEWS" alt="Profile Views" />
    </a>
  </p>

</div>

---

## 👨‍💻 About Me

<div class="card">

I'm a **B.Tech Computer Science and Engineering student specializing in Cybersecurity at Karunya Institute of Technology and Sciences**. My technical journey combines software engineering rigor, network and operating system security defense, and high-stakes live sound engineering.

Whether I'm building automated test verification pipelines in Python, analyzing network packets in Linux, or operating digital mixing consoles for audiences of hundreds, my approach is centered on **precision, signal flow architecture, and continuous technical experimentation**.

* 🎓 **Education:** B.Tech CSE — Cybersecurity @ Karunya Institute of Technology and Sciences
* 🔐 **Cybersecurity:** Network security, Linux administration, system security, threat modeling, and defense telemetry
* 💻 **Software Development:** Python, C, C++, Data Structures, modern HTML5/CSS, and Web Development
* 🤖 **AI & Data Verification:** Adversarial datasets, agent benchmarking, and proof-carrying data analysis
* 🎚️ **Live Sound & Audio:** 25+ live events & church productions mixed on Behringer WING, MIDAS M32, and Allen & Heath consoles
* 🏆 **Competitive Athletics:** State-level Throwball participant — **Gold and Bronze Medalist**
* 🤝 **Open To:** Cybersecurity opportunities, software engineering collaborations, and live audio production projects

> *"My goal is to become an engineer who can analyze problems critically, build reliable solutions, and continuously learn across technology and creative engineering."*

</div>

---

## 🎚️ Live Sound & Audio Engineering

<div class="card" style="border-color: rgba(255, 183, 3, 0.35);">

🎤 **Live Sound Track Record:** Mixed **25+ live shows and church events**, gaining deep practical mastery in FOH mixing, stage monitoring, digital console operation, remote stagebox patching, and live DSP plugin hosting.

### 🌐 Live Digital Audio Signal Chain & Routing Architecture

<!-- Animated Signal Flow Diagram -->
<div class="signal-chain-box">
  <table width="100%" border="0" style="text-align:center; color:#ffffff; font-family:'Fira Code', monospace; font-size:12px;">
    <tr>
      <td width="20%">
        <strong>🎤 Stage Sources</strong><br>
        <span style="color:#8ca0ba; font-size:10px;">Vocals • Drums • DIs</span>
      </td>
      <td width="5%" style="color:#ffb703;">➔</td>
      <td width="20%">
        <strong>🔌 Behringer S32</strong><br>
        <span style="color:#8ca0ba; font-size:10px;">32 Midas Preamps</span>
      </td>
      <td width="5%" style="color:#00ff88;">➔</td>
      <td width="25%">
        <strong>🎛️ FOH Console</strong><br>
        <span style="color:#00f2fe; font-size:10px;">WING • X32 • M32</span>
      </td>
      <td width="5%" style="color:#a855f7;">➔</td>
      <td width="20%">
        <strong>⚡ Waves SuperRack</strong><br>
        <span style="color:#8ca0ba; font-size:10px;">Live Dynamic Plugins</span>
      </td>
      <td width="5%" style="color:#ff3366;">➔</td>
      <td width="20%">
        <strong>🔊 PA & Monitors</strong><br>
        <span style="color:#8ca0ba; font-size:10px;">Main Stereo & IEMs</span>
      </td>
    </tr>
  </table>
  <div class="cable-flow"></div>
  <div align="center" style="font-family:'Fira Code',monospace; font-size:11px; color:#ffb703; margin-top:6px;">
    [ AES50 Digital Snake • Cat5e Shielded Transmission • Low Latency Bus Matrix Routing ]
  </div>
</div>

### 🎛️ Digital Consoles & Gear In Production
* **Behringer Consoles:** WING (48-channel personal stereo routing, custom fader banks) & X32
* **MIDAS Systems:** M32 and high-precision live mixing workflows with Midas Pro preamps
* **Allen & Heath:** SQ Series (SQ-5/SQ-6), QU Series & Avantis 96kHz FPGA systems
* **Digital Stageboxes:** Behringer S32 digital stagebox connectivity, remote I/O, AES50 sync
* **Waves Audio:** Waves SuperRack Performer live plugin hosting, precision dynamic EQ, compression & vocal DSP
* **Studio Production:** Logic Pro multitrack recording, audio editing, and acoustic signal structuring

**My Mixing Philosophy:** Clean gain structure, controlled dynamics, clear vocal intelligibility, reliable signal routing, and consistent sonic fidelity across the entire room.

</div>

---

## 🚀 Featured Projects

### 🤖 AUTOBOTZZ — Proof-Carrying Data Analyst

<div class="card" style="border-color: rgba(0, 242, 254, 0.35);">

[![AUTOBOTZZ Repository](https://img.shields.io/badge/GitHub-AUTOBOTZZ--Proof--Carrying--Data--Analyst-00f2fe?style=for-the-badge&logo=github&labelColor=0d1525)](https://github.com/AUSTIN-JR/AUTOBOTZZ-Proof-Carrying-Data-Analyst)
&nbsp;
<img src="https://img.shields.io/badge/HackNex-Qualifier%20Project-00ff88?style=for-the-badge&logo=target&logoColor=black" alt="HackNex" />

A collaborative framework developed for the **HackNex qualifier** focused on verifiable data analysis and verification:

* **Adversarial & Clean Dataset Design:** Engineered test cases to benchmark reasoning accuracy and catch hallucinations.
* **Ground-Truth Validation:** Prepared baselines for automated evaluation against known ground truths.
* **Benchmarking Infrastructure:** Evaluated agent performance under perturbations and complex analytical prompts.
* **Verification Workflows:** Structured dataset handoff and reproducible execution traces.

</div>

### 🌐 Web Development & Interactive Systems

<div class="card">

[![Explore Repositories](https://img.shields.io/badge/Explore-My%20Repositories-00ff88?style=for-the-badge&logo=github&labelColor=0d1525)](https://github.com/Godwin-J-08?tab=repositories)

* **Interactive Frontend:** Building responsive interfaces with semantic HTML5, modern CSS architectures, and JavaScript.
* **Developer Workflows:** Version control with Git & GitHub, deployment workflows, and clean code principles.

</div>

---

## 🛠️ Tech Stack & Tooling

<div align="center">

### 💻 Programming Languages
[![Languages](https://skillicons.dev/icons?i=python,c,cpp,js,html,css&theme=dark)](https://github.com/Godwin-J-08)

### 🔐 Cybersecurity & Operating Systems
[![Security & Tools](https://skillicons.dev/icons?i=linux,bash,git,github,vscode&theme=dark)](https://github.com/Godwin-J-08)

### 🌐 Web & Backend
[![Web Frameworks](https://skillicons.dev/icons?i=react,nodejs,fastapi&theme=dark)](https://github.com/Godwin-J-08)

### 🎛️ Audio Engineering & DSP
<p>
  <img src="https://img.shields.io/badge/Apple-Logic%20Pro-000000?style=for-the-badge&logo=apple&logoColor=white" alt="Logic Pro" />
  <img src="https://img.shields.io/badge/Live%20Sound-25%2B%20Shows%20FOH%20%26%20Monitors-153448?style=for-the-badge" alt="Live Sound" />
  <img src="https://img.shields.io/badge/Digital%20Consoles-WING%20%7C%20X32%20%7C%20M32-176B87?style=for-the-badge" alt="Consoles" />
  <img src="https://img.shields.io/badge/Allen%20%26%20Heath-SQ%20%7C%20Avantis-007A78?style=for-the-badge" alt="Allen and Heath" />
  <img src="https://img.shields.io/badge/Stageboxes-Behringer%20S32%20AES50-222222?style=for-the-badge" alt="Stageboxes" />
  <img src="https://img.shields.io/badge/Waves-SuperRack%20Performer-0066CC?style=for-the-badge" alt="Waves" />
</p>

</div>

---

## 🎯 Current Learning Roadmap

```text
Programming & Problem Solving
    └── Python • C • C++ • Data Structures & Algorithms

Cybersecurity Fundamentals
    └── Linux Administration • Network Defense • System Threat Analysis

Software Development
    └── Responsive Web Apps • REST APIs • Git Collaboration

AI & Data Engineering
    └── Adversarial Benchmarking • Ground-Truth Validation • Verification Workflows

Audio Engineering
    └── Advanced FOH Routing • Waves SuperRack DSP • Multitrack Post-Production
```

---

## 🧠 Beyond the Code

<div class="card">

<table width="100%" border="0">
  <tr>
    <td width="15%" align="center" valign="middle">
      <h1 style="font-size:42px; margin:0; color:#ffd700;">🏅</h1>
    </td>
    <td width="85%">
      <h3 style="margin:0 0 6px 0; color:#ffd700; font-family:'Outfit',sans-serif;">State-Level Throwball Athlete (Gold & Bronze Medalist)</h3>
      <p style="margin:0; font-size:14px; color:#8ca0ba;">
        High-stakes athletic competition has reinforced discipline, strategic court awareness, rapid reaction under pressure, and collective teamwork—qualities that directly translate to live concert sound mixing and technical problem solving.
      </p>
    </td>
  </tr>
</table>

<hr style="border:0; border-top:1px solid rgba(255,255,255,0.08); margin:16px 0;">

* **Analytical Thinking:** Deconstructing multi-layered problems into isolated, testable signal paths.
* **Teamwork Under Pressure:** Coordinating with musicians, organizers, and engineers for flawless execution.
* **Precision to Detail:** Managing signal headroom—whether memory buffers in software or decibels on an audio bus.
* **Continuous Growth:** Lifelong dedication to debugging, learning, and improving.

</div>

---

## 📊 GitHub Overview

<div align="center">

[![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Godwin-J-08&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github)](https://github.com/Godwin-J-08)

[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Godwin-J-08&layout=compact&theme=tokyonight&hide_border=true)](https://github.com/Godwin-J-08?tab=repositories)

[![GitHub Streak](https://streak-stats.demolab.com?user=Godwin-J-08&theme=tokyonight&hide_border=true&ring=00f2fe&fire=ffb703&currStreakLabel=00ff88)](https://github.com/Godwin-J-08)

</div>

---

## 🤝 Let's Connect

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-Godwin--J--08-181717?style=for-the-badge&logo=github)](https://github.com/Godwin-J-08)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/godwinj-engineer/)
[![Email](https://img.shields.io/badge/Email-Contact%20Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:godwinbalan08@gmail.com)

<!-- Animated Footer Wave -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0:00f2fe,5:00ff88,10:ffb703&height=120&section=footer&animation=twinkling" width="100%" alt="Footer Wave" />

### 💡 Learn. Build. Secure. Create.

*Thanks for visiting my profile! Feel free to explore my repositories and connect.*

</div>

</div>

</body>
</html>
