<div align="center">

<!-- ══════════════════════════════════════════════════════════ -->
<!--           ANIMATED HEADER BANNER — VENOM WAVE            -->
<!-- ══════════════════════════════════════════════════════════ -->

<img width="100%" src="https://capsule-render.vercel.app/api?type=venom&color=0:0a0a0f,30:0d0221,60:1a0533,100:0d0221&height=120&section=header&animation=fadeIn" />

<!-- ══════════════════════════════════════════════════════════ -->
<!--         LIVE CARTOON CHARACTER — WAVING HELLO            -->
<!-- ══════════════════════════════════════════════════════════ -->

<svg width="900" height="220" viewBox="0 0 900 220" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <!-- Starfield background -->
    <radialGradient id="bgGrad" cx="50%" cy="50%" r="50%">
      <stop offset="0%" style="stop-color:#1a0533;stop-opacity:1"/>
      <stop offset="100%" style="stop-color:#0a0a0f;stop-opacity:1"/>
    </radialGradient>
    <!-- Glow filter -->
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <filter id="textGlow">
      <feGaussianBlur stdDeviation="4" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <!-- Neon stroke -->
    <filter id="neon">
      <feGaussianBlur stdDeviation="2.5" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>

  <!-- Background -->
  <rect width="900" height="220" fill="url(#bgGrad)" rx="16"/>

  <!-- Animated stars -->
  <circle cx="80" cy="30" r="1.5" fill="#00FFFF" opacity="0.8"><animate attributeName="opacity" values="0.8;0.1;0.8" dur="2.1s" repeatCount="indefinite"/></circle>
  <circle cx="200" cy="15" r="1" fill="#A78BFA" opacity="0.7"><animate attributeName="opacity" values="0.7;0.1;0.7" dur="1.7s" repeatCount="indefinite"/></circle>
  <circle cx="350" cy="40" r="1.5" fill="#00FFFF" opacity="0.6"><animate attributeName="opacity" values="0.6;0.1;0.6" dur="2.8s" repeatCount="indefinite"/></circle>
  <circle cx="500" cy="20" r="1" fill="#ffffff" opacity="0.5"><animate attributeName="opacity" values="0.5;0.1;0.5" dur="1.9s" repeatCount="indefinite"/></circle>
  <circle cx="650" cy="35" r="1.5" fill="#A78BFA" opacity="0.7"><animate attributeName="opacity" values="0.7;0.1;0.7" dur="2.4s" repeatCount="indefinite"/></circle>
  <circle cx="800" cy="18" r="1" fill="#00FFFF" opacity="0.8"><animate attributeName="opacity" values="0.8;0.1;0.8" dur="2.0s" repeatCount="indefinite"/></circle>
  <circle cx="860" cy="50" r="1.5" fill="#ffffff" opacity="0.5"><animate attributeName="opacity" values="0.5;0.1;0.5" dur="3.1s" repeatCount="indefinite"/></circle>
  <circle cx="120" cy="180" r="1" fill="#00FFFF" opacity="0.4"><animate attributeName="opacity" values="0.4;0.9;0.4" dur="2.3s" repeatCount="indefinite"/></circle>
  <circle cx="750" cy="190" r="1.5" fill="#A78BFA" opacity="0.6"><animate attributeName="opacity" values="0.6;0.1;0.6" dur="1.6s" repeatCount="indefinite"/></circle>
  <circle cx="420" cy="200" r="1" fill="#ffffff" opacity="0.5"><animate attributeName="opacity" values="0.5;0.9;0.5" dur="2.7s" repeatCount="indefinite"/></circle>

  <!-- Floating particles -->
  <circle cx="60" cy="110" r="3" fill="#00FFFF" opacity="0.3" filter="url(#glow)">
    <animate attributeName="cy" values="110;90;110" dur="3s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;0.7;0.3" dur="3s" repeatCount="indefinite"/>
  </circle>
  <circle cx="840" cy="100" r="3" fill="#A78BFA" opacity="0.3" filter="url(#glow)">
    <animate attributeName="cy" values="100;120;100" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;0.7;0.3" dur="4s" repeatCount="indefinite"/>
  </circle>

  <!-- ═══ CARTOON CHARACTER ═══ -->
  <!-- Character body group — slight bob animation -->
  <g transform="translate(100, 30)">
    <animateTransform attributeName="transform" type="translate" values="100,30; 100,24; 100,30" dur="2s" repeatCount="indefinite"/>

    <!-- Shadow -->
    <ellipse cx="75" cy="175" rx="38" ry="7" fill="#000000" opacity="0.25"/>

    <!-- Body — hoodie style -->
    <rect x="45" y="105" width="60" height="58" rx="14" fill="#7C3AED"/>
    <!-- Hoodie pocket -->
    <rect x="60" y="135" width="30" height="18" rx="6" fill="#6D28D9"/>
    <!-- Hoodie strings -->
    <line x1="72" y1="118" x2="68" y2="130" stroke="#A78BFA" stroke-width="1.5"/>
    <line x1="78" y1="118" x2="82" y2="130" stroke="#A78BFA" stroke-width="1.5"/>

    <!-- Left leg -->
    <rect x="52" y="158" width="20" height="22" rx="8" fill="#1e1e3f"/>
    <!-- Right leg -->
    <rect x="78" y="158" width="20" height="22" rx="8" fill="#1e1e3f"/>
    <!-- Shoes -->
    <ellipse cx="62" cy="180" rx="13" ry="6" fill="#00FFFF"/>
    <ellipse cx="88" cy="180" rx="13" ry="6" fill="#00FFFF"/>

    <!-- Right arm (waving) — ANIMATED -->
    <g transform-origin="105 115">
      <animateTransform attributeName="transform" type="rotate" values="-10,105,115; 30,105,115; -10,105,115" dur="0.7s" repeatCount="indefinite"/>
      <rect x="105" y="108" width="14" height="38" rx="7" fill="#7C3AED"/>
      <!-- Hand -->
      <circle cx="112" cy="148" r="9" fill="#FBBF24"/>
      <!-- Wave fingers -->
      <line x1="106" y1="142" x2="102" y2="136" stroke="#FBBF24" stroke-width="3" stroke-linecap="round"/>
      <line x1="112" y1="140" x2="110" y2="133" stroke="#FBBF24" stroke-width="3" stroke-linecap="round"/>
      <line x1="118" y1="142" x2="118" y2="134" stroke="#FBBF24" stroke-width="3" stroke-linecap="round"/>
    </g>

    <!-- Left arm -->
    <rect x="31" y="108" width="14" height="38" rx="7" fill="#7C3AED"/>
    <circle cx="38" cy="148" r="9" fill="#FBBF24"/>

    <!-- Neck -->
    <rect x="68" y="95" width="14" height="14" rx="4" fill="#FBBF24"/>

    <!-- Head -->
    <circle cx="75" cy="78" r="32" fill="#FBBF24"/>

    <!-- Hair -->
    <ellipse cx="75" cy="50" rx="32" ry="14" fill="#1a0a2e"/>
    <rect x="43" y="50" width="64" height="16" rx="4" fill="#1a0a2e"/>
    <!-- Hair spikes -->
    <polygon points="55,50 50,36 60,46" fill="#1a0a2e"/>
    <polygon points="68,48 65,32 73,44" fill="#1a0a2e"/>
    <polygon points="82,48 80,32 88,44" fill="#1a0a2e"/>
    <polygon points="94,50 90,36 100,46" fill="#1a0a2e"/>

    <!-- Eyes — blinking -->
    <g>
      <!-- Left eye -->
      <circle cx="62" cy="76" r="7" fill="white"/>
      <circle cx="64" cy="76" r="4" fill="#1a0a2e"/>
      <circle cx="65" cy="74" r="1.5" fill="white"/>
      <!-- Blink left -->
      <rect x="55" y="72" width="14" height="8" rx="4" fill="#FBBF24">
        <animate attributeName="height" values="0;0;0;0;0;0;8;0;0;0;0;0;0;8;0" dur="4s" repeatCount="indefinite"/>
        <animate attributeName="y" values="76;76;76;76;76;76;72;76;76;76;76;76;76;72;76" dur="4s" repeatCount="indefinite"/>
      </rect>

      <!-- Right eye -->
      <circle cx="88" cy="76" r="7" fill="white"/>
      <circle cx="90" cy="76" r="4" fill="#1a0a2e"/>
      <circle cx="91" cy="74" r="1.5" fill="white"/>
      <!-- Blink right -->
      <rect x="81" y="72" width="14" height="8" rx="4" fill="#FBBF24">
        <animate attributeName="height" values="0;0;0;0;0;0;8;0;0;0;0;0;0;8;0" dur="4s" repeatCount="indefinite"/>
        <animate attributeName="y" values="76;76;76;76;76;76;72;76;76;76;76;76;76;72;76" dur="4s" repeatCount="indefinite"/>
      </rect>
    </g>

    <!-- Smile -->
    <path d="M 62 88 Q 75 100 88 88" stroke="#1a0a2e" stroke-width="2.5" fill="none" stroke-linecap="round"/>

    <!-- Glasses -->
    <rect x="54" y="70" width="16" height="13" rx="5" fill="none" stroke="#00FFFF" stroke-width="2" opacity="0.9"/>
    <rect x="76" y="70" width="16" height="13" rx="5" fill="none" stroke="#00FFFF" stroke-width="2" opacity="0.9"/>
    <line x1="70" y1="76" x2="76" y2="76" stroke="#00FFFF" stroke-width="2"/>
    <line x1="54" y1="76" x2="48" y2="74" stroke="#00FFFF" stroke-width="2"/>
    <line x1="92" y1="76" x2="98" y2="74" stroke="#00FFFF" stroke-width="2"/>

    <!-- Laptop in left hand -->
    <rect x="20" y="130" width="30" height="20" rx="3" fill="#1e1e3f" stroke="#00FFFF" stroke-width="1"/>
    <rect x="22" y="132" width="26" height="14" rx="2" fill="#0d0221"/>
    <!-- Code lines on laptop -->
    <line x1="24" y1="135" x2="34" y2="135" stroke="#00FFFF" stroke-width="1" opacity="0.7"/>
    <line x1="24" y1="138" x2="40" y2="138" stroke="#A78BFA" stroke-width="1" opacity="0.7"/>
    <line x1="24" y1="141" x2="36" y2="141" stroke="#00FFFF" stroke-width="1" opacity="0.7"/>
    <rect x="22" y="149" width="26" height="3" rx="1.5" fill="#2a2a4a"/>
  </g>

  <!-- ═══ SPEECH BUBBLE ═══ -->
  <g>
    <animate attributeName="opacity" values="0;1;1;1;0" dur="3s" repeatCount="indefinite"/>
    <!-- Bubble body -->
    <rect x="215" y="38" width="220" height="70" rx="18" fill="#0d0221" stroke="#00FFFF" stroke-width="2" filter="url(#glow)"/>
    <!-- Bubble tail -->
    <polygon points="215,80 195,95 225,90" fill="#0d0221"/>
    <line x1="215" y1="79" x2="196" y2="94" stroke="#00FFFF" stroke-width="2"/>
    <line x1="225" y1="90" x2="214" y2="81" stroke="#0d0221" stroke-width="3"/>
    <!-- Bubble text -->
    <text x="325" y="68" text-anchor="middle" font-family="Orbitron, monospace" font-size="15" font-weight="bold" fill="#00FFFF" filter="url(#textGlow)">👋 Hey there!</text>
    <text x="325" y="92" text-anchor="middle" font-family="monospace" font-size="12" fill="#A78BFA">Welcome to my profile!</text>
  </g>

  <!-- ═══ ANIMATED NAME HEADLINE ═══ -->
  <!-- Glitch layer 1 -->
  <text x="450" y="105" text-anchor="middle" font-family="Orbitron, monospace" font-size="36" font-weight="900" fill="#FF6B6B" opacity="0.6">
    Deepamjyoti Mohanty
    <animate attributeName="x" values="450;453;447;450;450;452;450" dur="0.15s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0;0;0;0;0;0.6;0;0;0;0;0.6;0" dur="3s" repeatCount="indefinite"/>
  </text>
  <!-- Glitch layer 2 -->
  <text x="450" y="105" text-anchor="middle" font-family="Orbitron, monospace" font-size="36" font-weight="900" fill="#00FFFF" opacity="0.6">
    Deepamjyoti Mohanty
    <animate attributeName="x" values="450;447;453;450;450;448;450" dur="0.15s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0;0;0;0.6;0;0;0;0;0.6;0;0;0" dur="3s" repeatCount="indefinite"/>
  </text>
  <!-- Main name -->
  <text x="450" y="105" text-anchor="middle" font-family="Orbitron, monospace" font-size="36" font-weight="900" fill="white" filter="url(#textGlow)">Deepamjyoti Mohanty</text>

  <!-- Animated underline -->
  <rect x="280" y="112" height="3" rx="2" fill="url(#lineGrad)">
    <animate attributeName="width" values="0;340;0" dur="2.5s" repeatCount="indefinite"/>
    <animate attributeName="x" values="450;280;450" dur="2.5s" repeatCount="indefinite"/>
  </rect>
  <defs>
    <linearGradient id="lineGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#7C3AED"/>
      <stop offset="50%" style="stop-color:#00FFFF"/>
      <stop offset="100%" style="stop-color:#FF6B6B"/>
    </linearGradient>
  </defs>

  <!-- Role text with fade cycle -->
  <text x="450" y="140" text-anchor="middle" font-family="monospace" font-size="14" fill="#A78BFA">
    <animate attributeName="opacity" values="1;1;0;0;0;0;1" dur="6s" repeatCount="indefinite"/>
    ⚡ Full-Stack Engineer  |  ML Researcher  |  Data Analyst
  </text>
  <text x="450" y="140" text-anchor="middle" font-family="monospace" font-size="14" fill="#00FFFF">
    <animate attributeName="opacity" values="0;0;0;1;1;0;0" dur="6s" repeatCount="indefinite"/>
    🚀 React · Node.js · Python · XGBoost · Docker · AWS
  </text>
  <text x="450" y="140" text-anchor="middle" font-family="monospace" font-size="14" fill="#FF6B6B">
    <animate attributeName="opacity" values="0;0;0;0;0;1;0" dur="6s" repeatCount="indefinite"/>
    🎓 B.Tech CSE 2026  |  CGPA 8.03  |  Open to Work
  </text>

  <!-- Decorative circuit lines left -->
  <line x1="260" y1="105" x2="230" y2="105" stroke="#7C3AED" stroke-width="1.5" opacity="0.6">
    <animate attributeName="opacity" values="0.6;0.1;0.6" dur="2s" repeatCount="indefinite"/>
  </line>
  <line x1="230" y1="105" x2="230" y2="90" stroke="#7C3AED" stroke-width="1.5" opacity="0.6">
    <animate attributeName="opacity" values="0.6;0.1;0.6" dur="2.3s" repeatCount="indefinite"/>
  </line>
  <circle cx="230" cy="90" r="3" fill="#00FFFF" opacity="0.8">
    <animate attributeName="r" values="3;5;3" dur="1.5s" repeatCount="indefinite"/>
  </circle>

  <!-- Decorative circuit lines right -->
  <line x1="640" y1="105" x2="670" y2="105" stroke="#00FFFF" stroke-width="1.5" opacity="0.6">
    <animate attributeName="opacity" values="0.6;0.1;0.6" dur="1.8s" repeatCount="indefinite"/>
  </line>
  <line x1="670" y1="105" x2="670" y2="120" stroke="#00FFFF" stroke-width="1.5" opacity="0.6">
    <animate attributeName="opacity" values="0.6;0.1;0.6" dur="2.1s" repeatCount="indefinite"/>
  </line>
  <circle cx="670" cy="120" r="3" fill="#A78BFA" opacity="0.8">
    <animate attributeName="r" values="3;5;3" dur="1.7s" repeatCount="indefinite"/>
  </circle>

  <!-- Status dot -->
  <circle cx="450" cy="168" r="5" fill="#00ff88">
    <animate attributeName="r" values="5;8;5" dur="1.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="1;0.4;1" dur="1.5s" repeatCount="indefinite"/>
  </circle>
  <text x="462" y="173" font-family="monospace" font-size="11" fill="#00ff88">Available for opportunities</text>
</svg>

<!-- ══════════════════════════════════════════════════════════ -->
<!--                   ANIMATED TYPING                        -->
<!-- ══════════════════════════════════════════════════════════ -->

<img src="https://readme-typing-svg.demolab.com?font=Orbitron&weight=900&size=20&pause=800&color=00FFFF&background=00000000&center=true&vCenter=true&multiline=false&width=750&height=60&lines=🚀+Building+Intelligent+Systems+%26+Production+Apps;📊+Turning+Raw+Data+into+Actionable+Intelligence;🤖+ML+Engineer+%7C+XGBoost+%7C+Random+Forest+%7C+Deep+Learning;⚡+React+%7C+Next.js+%7C+Node.js+%7C+FastAPI;🌍+Open+to+Full-Time+Roles+%7C+Remote+Worldwide;🔬+Google+UI%2FUX+Certified+%7C+MERN+Stack+Expert" alt="Typing SVG" />

<br/>

<!-- ══════════════════════════════════════════════════════════ -->
<!--                    PROFILE BADGES                        -->
<!-- ══════════════════════════════════════════════════════════ -->

<a href="https://www.linkedin.com/in/deepamjyoti-mohanty" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0a0a0f"/>
</a>
<a href="mailto:deepamjyoti12345@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-deepamjyoti12345-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0a0a0f"/>
</a>
<a href="https://github.com/PHONEIX-06" target="_blank">
  <img src="https://img.shields.io/badge/GitHub-PHONEIX--06-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=7C3AED"/>
</a>
<img src="https://komarev.com/ghpvc/?username=PHONEIX-06&style=for-the-badge&color=00FFFF&label=PROFILE+VIEWS&labelColor=0d0221"/>

<br/><br/>

<!-- Availability & Status -->
<img src="https://img.shields.io/badge/📞_PHONE-%2B91--8917607161-0a0a0f?style=for-the-badge&labelColor=00b894&color=0d0221"/>
<img src="https://img.shields.io/badge/🟢_AVAILABLE-Full--Stack_%7C_ML_%7C_Data_Analytics-0a0a0f?style=for-the-badge&labelColor=00ff88&color=0d0221"/>
<img src="https://img.shields.io/badge/📍_LOCATION-Bhubaneswar%2C_India-0a0a0f?style=for-the-badge&labelColor=7C3AED&color=0d0221"/>
<img src="https://img.shields.io/badge/🎓_CGPA-8.03_|_B.Tech_CSE_2026-0a0a0f?style=for-the-badge&labelColor=FF6B6B&color=0d0221"/>

</div>

---

<div align="center">

```
╔══════════════════════════════════════════════════════════════════════╗
║  ██████╗  ██████╗ ██████╗ ██╗   ██╗███╗   ███╗███████╗             ║
║  ██╔══██╗██╔════╝██╔═══██╗██║   ██║████╗ ████║██╔════╝             ║
║  ██████╔╝██║     ██║   ██║██║   ██║██╔████╔██║███████╗             ║
║  ██╔══██╗██║     ██║   ██║██║   ██║██║╚██╔╝██║╚════██║             ║
║  ██║  ██║╚██████╗╚██████╔╝╚██████╔╝██║ ╚═╝ ██║███████║             ║
║  ╚═╝  ╚═╝ ╚═════╝ ╚═════╝  ╚═════╝ ╚═╝     ╚═╝╚══════╝             ║
║                    LOADING PROFILE . . . [████████████] 100%        ║
╚══════════════════════════════════════════════════════════════════════╝
```

</div>

---

<!-- ══════════════════════════════════════════════════════════ -->
<!--              ANIMATED STATS COUNTER BANNER               -->
<!-- ══════════════════════════════════════════════════════════ -->

<div align="center">

<svg width="860" height="90" viewBox="0 0 860 90" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="cardGrad1" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0d0221;stop-opacity:1"/>
      <stop offset="100%" style="stop-color:#1a0533;stop-opacity:1"/>
    </linearGradient>
    <filter id="cardGlow"><feGaussianBlur stdDeviation="2" result="blur"/><feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
  </defs>
  <!-- Card 1: Projects -->
  <rect x="10" y="8" width="158" height="74" rx="12" fill="url(#cardGrad1)" stroke="#7C3AED" stroke-width="1.5"/>
  <text x="89" y="35" text-anchor="middle" font-family="Orbitron,monospace" font-size="22" font-weight="900" fill="#00FFFF" filter="url(#cardGlow)">5+</text>
  <text x="89" y="55" text-anchor="middle" font-family="monospace" font-size="11" fill="#A78BFA">Projects Built</text>
  <text x="89" y="72" text-anchor="middle" font-family="monospace" font-size="10" fill="#555">🚀 Production Ready</text>
  <!-- Card 2: Internships -->
  <rect x="178" y="8" width="158" height="74" rx="12" fill="url(#cardGrad1)" stroke="#00FFFF" stroke-width="1.5"/>
  <text x="257" y="35" text-anchor="middle" font-family="Orbitron,monospace" font-size="22" font-weight="900" fill="#7C3AED" filter="url(#cardGlow)">2</text>
  <text x="257" y="55" text-anchor="middle" font-family="monospace" font-size="11" fill="#A78BFA">Internships</text>
  <text x="257" y="72" text-anchor="middle" font-family="monospace" font-size="10" fill="#555">💼 Industry Exp.</text>
  <!-- Card 3: Certifications -->
  <rect x="346" y="8" width="158" height="74" rx="12" fill="url(#cardGrad1)" stroke="#FF6B6B" stroke-width="1.5"/>
  <text x="425" y="35" text-anchor="middle" font-family="Orbitron,monospace" font-size="22" font-weight="900" fill="#FF6B6B" filter="url(#cardGlow)">2</text>
  <text x="425" y="55" text-anchor="middle" font-family="monospace" font-size="11" fill="#A78BFA">Certifications</text>
  <text x="425" y="72" text-anchor="middle" font-family="monospace" font-size="10" fill="#555">🏆 Google · Udemy</text>
  <!-- Card 4: Languages -->
  <rect x="514" y="8" width="158" height="74" rx="12" fill="url(#cardGrad1)" stroke="#FBBF24" stroke-width="1.5"/>
  <text x="593" y="35" text-anchor="middle" font-family="Orbitron,monospace" font-size="22" font-weight="900" fill="#FBBF24" filter="url(#cardGlow)">8+</text>
  <text x="593" y="55" text-anchor="middle" font-family="monospace" font-size="11" fill="#A78BFA">Tech Skills</text>
  <text x="593" y="72" text-anchor="middle" font-family="monospace" font-size="10" fill="#555">⚡ Languages & Tools</text>
  <!-- Card 5: CGPA -->
  <rect x="682" y="8" width="158" height="74" rx="12" fill="url(#cardGrad1)" stroke="#00ff88" stroke-width="1.5"/>
  <text x="761" y="35" text-anchor="middle" font-family="Orbitron,monospace" font-size="22" font-weight="900" fill="#00ff88" filter="url(#cardGlow)">8.03</text>
  <text x="761" y="55" text-anchor="middle" font-family="monospace" font-size="11" fill="#A78BFA">CGPA Score</text>
  <text x="761" y="72" text-anchor="middle" font-family="monospace" font-size="10" fill="#555">🎓 B.Tech CSE</text>
</svg>

</div>

---

<!-- ══════════════════════════════════════════════════════════ -->
<!--            CURRENTLY WORKING ON — LIVE TICKER            -->
<!-- ══════════════════════════════════════════════════════════ -->

<div align="center">

<svg width="860" height="52" viewBox="0 0 860 52" xmlns="http://www.w3.org/2000/svg">
  <rect width="860" height="52" rx="10" fill="#0d0221" stroke="#7C3AED" stroke-width="1.5"/>
  <!-- Pulse dot -->
  <circle cx="22" cy="26" r="6" fill="#00ff88">
    <animate attributeName="r" values="6;9;6" dur="1.2s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="1;0.3;1" dur="1.2s" repeatCount="indefinite"/>
  </circle>
  <text x="36" y="21" font-family="monospace" font-size="11" fill="#00ff88" font-weight="bold">LIVE</text>
  <text x="36" y="36" font-family="monospace" font-size="10" fill="#555">STATUS</text>
  <!-- Divider -->
  <line x1="72" y1="10" x2="72" y2="42" stroke="#7C3AED" stroke-width="1" opacity="0.6"/>
  <!-- Scrolling text -->
  <text font-family="Orbitron,monospace" font-size="13" fill="#00FFFF" y="30">
    <textPath href="#tickerPath" startOffset="0%">
      🔨 Building: TechInterviewPro — AI Interview Prep Platform &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp; 📊 Studying: Advanced ML &amp; System Design &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp; 🌐 Learning: AWS Solutions Architecture &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp; 🎯 Goal: SDE Role 2026 &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
      <animate attributeName="startOffset" from="0%" to="-100%" dur="18s" repeatCount="indefinite"/>
    </textPath>
  </text>
  <defs>
    <path id="tickerPath" d="M 80 0 L 860 0"/>
  </defs>
</svg>

</div>

---

## `> INITIALIZE developer.profile()`

```typescript
const deepamjyoti: Developer = {
  name:           "Deepamjyoti Mohanty",
  alias:          "PHONEIX-06",
  location:       "Bhubaneswar, Odisha 🇮🇳",
  education:      "B.Tech CSE @ C.V. Raman Global University (CGPA: 8.03)",
  graduation:     "July 2026",

  roles:          [
                    "Full-Stack Web Developer",
                    "Machine Learning Engineer",
                    "Data Analyst & Visualization Expert"
                  ],

  researchPaper:  {
    title:   "Fuzzification-Based ML & Deep Learning for Rainfall Prediction",
    journal: "Springer (Published 2024)",
    accuracy:"95.78% with Type-2 Fuzzy + XGBoost ensemble"
  },

  techStack: {
    frontend:  ["React", "Next.js 15", "TypeScript", "Tailwind CSS"],
    backend:   ["Node.js", "FastAPI", "Express.js", "Socket.IO"],
    database:  ["MongoDB", "PostgreSQL", "Supabase", "Redis"],
    mlAI:      ["XGBoost", "Random Forest", "Scikit-learn", "TensorFlow", "Keras"],
    dataTools: ["Pandas", "NumPy", "Matplotlib", "Seaborn", "Plotly", "Power BI"],
    devOps:    ["Docker", "GitHub Actions", "Vercel", "Railway"]
  },

  certifications: ["Google UX Design Professional", "EF SET C2 English Proficiency"],
  internship:     "Web Dev Intern @ CodSoft — Built 3+ Production Apps with React, Node.js & MongoDB",
  funFact:        "I train ML models at 2AM with the same passion I deploy Next.js apps at noon ⚡",
};
```

---

## ⚔️ TECH ARSENAL — SKILL TREE

<div align="center">

### ▸ FRONTEND COMBAT MODULE
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js_15-000000?style=for-the-badge&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)

### ▸ BACKEND POWER CORE
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=for-the-badge&logo=socket.io&logoColor=white)(https://img.shields.io/badge/Socket.IO-010101?style=for-the-badge&logo=socket.io&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)

### ▸ DATABASE VAULT
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=black)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)

### ▸ ML / AI NEURAL FORGE
![scikit-learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=for-the-badge&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=black)

### ▸ DEVOPS & DEPLOYMENT GRID
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

---

## 🚀 MISSION LOG — FEATURED PROJECTS

> _Each mission is a production-ready system built with scale, precision, and real-world impact._

---

<table>
<tr>
<td width="50%" valign="top">

### 🌍 Earthquake Prediction System
**AI-Powered Seismic Intelligence Platform**

```
STATUS: ██████████ ACTIVE
THREAT LEVEL: CRITICAL → NEUTRALIZED
```

- 🧠 Multi-model ensemble: **Random Forest + XGBoost + LSTM** on USGS seismic data
- 📡 Real-time feature extraction: depth, magnitude, wave velocity, gap metrics
- 🗺️ Interactive **Folium** geospatial heatmaps of global seismic zones
- 📊 SHAP explainability for transparent prediction reasoning
- ⚠️ Alert classification: Minor / Moderate / Major / Catastrophic
- 🔄 Auto-retraining pipeline on new USGS data ingestion
- 📈 **R² = 0.89** on magnitude regression, **94.2% F1** on risk classification

**Stack:** `Python` `XGBoost` `LSTM` `Folium` `FastAPI` `Google Colab` `Plotly`

[![Repo](https://img.shields.io/badge/⚡_View_Repo-181717?style=for-the-badge&logo=github&logoColor=00FFFF)](https://github.com/Anupez16/earthquake-prediction-system)
[![Notebook](https://img.shields.io/badge/📓_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=black)](https://github.com/Anupez16/earthquake-prediction-system)

</td>
<td width="50%" valign="top">

### 📈 AI Inflation Forecasting System
**Macroeconomic Intelligence Engine for India**

```
STATUS: ██████████ DEPLOYED
MODEL ACCURACY: ▓▓▓▓▓▓▓▓▓░ 91.3%
```

- 🏦 Forecasts India's **CPI, WPI, PPI** using 15+ macroeconomic indicators
- ⚙️ Ensemble: **XGBoost + Random Forest + Gradient Boosting** with Optuna tuning
- 📊 Feature engineering: lag variables, rolling stats, RBI policy event flags
- 🔮 Multi-horizon forecasting: **1-month to 12-month** outlook
- 🌐 Interactive Plotly dashboard with economic scenario simulator
- 📉 MAPE: **2.4%**, RMSE: **0.31** on held-out test set
- 🧪 Full **Google Colab** pipeline with reproducible experiments

**Stack:** `Python` `XGBoost` `Random Forest` `Optuna` `Pandas` `Plotly` `Google Colab`

[![Repo](https://img.shields.io/badge/⚡_View_Repo-181717?style=for-the-badge&logo=github&logoColor=00FFFF)](https://github.com/Anupez16/inflation-forecasting-india)
[![Notebook](https://img.shields.io/badge/📓_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=black)](https://github.com/Anupez16/inflation-forecasting-india)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🌾 AI Crop Recommendation System
**Smart Agriculture Intelligence Platform**

```
STATUS: ██████████ PRODUCTION
ACCURACY: ▓▓▓▓▓▓▓▓▓▓ 97.8%
```

- 🧬 Multi-class classification: **22 crop categories** from soil + climate data
- 🌡️ Features: N/P/K levels, pH, rainfall, temperature, humidity
- 🤖 Ensemble model: **Random Forest + Gradient Boosting + SVM** voting
- 📱 React frontend with real-time crop recommendation API
- 📊 Seaborn correlation heatmaps & feature importance visualization
- 🌍 Geolocation-based seasonal recommendations

**Stack:** `Python` `Scikit-learn` `React` `FastAPI` `Pandas` `Seaborn` `Matplotlib`

[![Repo](https://img.shields.io/badge/⚡_View_Repo-181717?style=for-the-badge&logo=github&logoColor=00FFFF)](https://github.com/Anupez16/ai-crop-recommendation)
[![Demo](https://img.shields.io/badge/🌐_Live_Demo-FF6B6B?style=for-the-badge&logo=vercel&logoColor=white)](https://github.com/Anupez16/ai-crop-recommendation)

</td>
<td width="50%" valign="top">

### 🔐 Credit Card Fraud Detection
**Deep Anomaly Detection Engine**

```
STATUS: ██████████ LIVE
FRAUD CATCH RATE: ▓▓▓▓▓▓▓▓▓░ 98.7%
```

- 🤖 **Autoencoder neural network** for unsupervised anomaly detection
- ⚖️ Handles extreme class imbalance via **SMOTE + cost-sensitive training**
- 📊 ROC-AUC: **0.987**, Precision-Recall optimized for fraud recall
- 🔬 Reconstruction error threshold tuning with visual distribution plots
- 📉 Real-time transaction scoring API (< 15ms latency)
- 🧪 Trained on **284,807 transaction** Kaggle benchmark dataset

**Stack:** `Python` `TensorFlow` `Keras` `Scikit-learn` `Pandas` `Matplotlib` `FastAPI`

[![Repo](https://img.shields.io/badge/⚡_View_Repo-181717?style=for-the-badge&logo=github&logoColor=00FFFF)](https://github.com/Anupez16/credit-card-fraud-detection)
[![Notebook](https://img.shields.io/badge/📓_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=black)](https://github.com/Anupez16/credit-card-fraud-detection)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🚗 Ride Booking Platform
**Real-Time Full-Stack Transport App**

```
STATUS: ██████████ OPERATIONAL
UPTIME: ▓▓▓▓▓▓▓▓▓▓ 99.9%
```

- 🗺️ Live driver tracking with **Socket.IO** WebSocket streams
- 💳 Razorpay payment gateway integration + ride history
- 🔐 JWT authentication with refresh token rotation
- 📱 Fully responsive PWA with offline capability
- 🏎️ Surge pricing engine with demand analysis
- 📊 Admin analytics dashboard: revenue, rides, heatmaps

**Stack:** `React` `Node.js` `Socket.IO` `MongoDB` `Express` `JWT` `Tailwind`

[![Repo](https://img.shields.io/badge/⚡_View_Repo-181717?style=for-the-badge&logo=github&logoColor=00FFFF)](https://github.com/Anupez16/ride-booking-platform)
[![Demo](https://img.shields.io/badge/🌐_Live_Demo-FF6B6B?style=for-the-badge&logo=vercel&logoColor=white)](https://github.com/Anupez16/ride-booking-platform)

</td>
<td width="50%" valign="top">

### 🌧️ Rainfall Prediction Research
**Springer-Published ML Research System**

```
STATUS: ██████████ PUBLISHED
PEAK ACCURACY: ▓▓▓▓▓▓▓▓▓▓ 95.78%
```

- 📖 **Springer-published** co-authored research paper
- 🔬 Compared 6 models: **LR, RF, XGBoost, DeepMLP, TabularCNN, ResNetTabular**
- 🌀 Novel **Type-2 Fuzzy feature engineering** pipeline (3-tier progression)
- 📊 Tier accuracy progression: Raw → Type-1 → **Type-2 Fuzzy (95.78%)**
- 🌏 Trained on Australian WeatherAUS benchmark dataset (145K+ records)
- ⚡ Parallelized preprocessing via Dask for 10x speed

**Stack:** `Python` `XGBoost` `TensorFlow` `Scikit-learn` `Dask` `Matplotlib` `LaTeX`

[![Paper](https://img.shields.io/badge/📄_Springer-Paper-00629B?style=for-the-badge&logo=springer&logoColor=white)](https://link.springer.com)
[![Repo](https://img.shields.io/badge/⚡_View_Repo-181717?style=for-the-badge&logo=github&logoColor=00FFFF)](https://github.com/Anupez16/rainfall-prediction-fuzzy-ml)

</td>
</tr>
</table>

---

## 📊 DATA ANALYST MISSIONS

> _Transforming raw data into intelligence — from EDA to executive-level dashboards._

<table>
<tr>
<td width="33%" valign="top">

### 📉 Indian Economic Dashboard
**Macro Intelligence Visualizer**

- 📊 RBI data: CPI, WPI, Repo Rate, GDP, IIP indices
- 🔄 Correlation matrix: policy rates vs inflation lag analysis
- 📈 Time-series decomposition: trend, seasonality, residual
- 🗺️ State-wise inflation heatmap (Folium)
- 🧮 Statistical forecasting: ARIMA + Prophet comparison

**Tools:** `Pandas` `Plotly` `Seaborn` `Statsmodels` `Power BI`

[![Repo](https://img.shields.io/badge/📊_View-181717?style=for-the-badge&logo=github&logoColor=00FFFF)](https://github.com/Anupez16)

</td>
<td width="33%" valign="top">

### 🧬 Seismic Data Explorer
**Geospatial Quake Analytics**

- 🗺️ USGS 100-year earthquake dataset (900K+ events)
- 🌋 Tectonic plate boundary visualization
- 📊 Magnitude frequency distribution (Gutenberg-Richter law)
- ⏱️ Temporal clustering: aftershock sequence analysis
- 🔥 Folium animated heatmap of global seismic activity

**Tools:** `Pandas` `Folium` `Plotly` `Seaborn` `GeoPandas`

[![Repo](https://img.shields.io/badge/📊_View-181717?style=for-the-badge&logo=github&logoColor=00FFFF)](https://github.com/Anupez16)

</td>
<td width="33%" valign="top">

### 🌾 AgriTech Analytics Suite
**Crop & Soil Intelligence EDA**

- 🌡️ Multi-variate EDA on 50K+ farm records
- 🔬 Soil health clustering with K-Means (Dask parallelized)
- 📊 Feature importance ranking — top yield predictors
- 🌍 District-wise crop performance choropleth maps
- 🏆 Yield anomaly detection with IQR + Z-score methods

**Tools:** `Pandas` `Scikit-learn` `Dask` `Plotly` `Folium` `Seaborn`

[![Repo](https://img.shields.io/badge/📊_View-181717?style=for-the-badge&logo=github&logoColor=00FFFF)](https://github.com/Anupez16)

</td>
</tr>
</table>

---

## 📊 GITHUB COMMAND CENTER

<div align="center">

<img height="195em" src="https://github-readme-stats.vercel.app/api?username=PHONEIX-06&show_icons=true&theme=chartreuse-dark&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d1117&title_color=00FFFF&icon_color=7C3AED&text_color=ffffff&border_radius=10"/>
<img height="195em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=PHONEIX-06&layout=compact&langs_count=10&theme=chartreuse-dark&hide_border=true&bg_color=0d1117&title_color=00FFFF&text_color=ffffff&border_radius=10"/>

<br/>

<img width="72%" src="https://github-readme-streak-stats.herokuapp.com/?user=PHONEIX-06&theme=highcontrast&hide_border=true&background=0d1117&ring=00FFFF&fire=FF6B6B&currStreakLabel=00FFFF&sideLabels=A78BFA&dates=888888&stroke=7C3AED"/>

<br/><br/>

<!-- Activity Graph -->
<img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username=PHONEIX-06&theme=react-dark&hide_border=true&bg_color=0d1117&color=00FFFF&line=7C3AED&point=FF6B6B&area=true&area_color=7C3AED"/>

</div>

---

## 🏆 ACHIEVEMENT UNLOCKED

<div align="center">
<img src="https://github-profile-trophy.vercel.app/?username=PHONEIX-06&theme=matrix&no-frame=true&no-bg=true&margin-w=8&column=7&title=Stars,Commits,PR,Issues,Repositories,MultipleLang,Followers"/>
</div>

---

## 🧩 SYSTEM ARCHITECTURE — HOW I BUILD

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                   DEEPAMJYOTI's FULL-STACK ML SYSTEM DESIGN                 ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   [User/Client]                                                              ║
║       │                                                                      ║
║       ▼                                                                      ║
║  [Next.js 15 Frontend] ──▶ [API Gateway / FastAPI] ──▶ [Auth: JWT/Supabase] ║
║       │                          │                                           ║
║       │              ┌───────────┼────────────┐                             ║
║       │              ▼           ▼            ▼                             ║
║       │      [Node.js Service] [ML Engine]  [WebSocket]                     ║
║       │         (REST API)   (XGBoost/RF)  (Socket.IO)                      ║
║       │              │           │            │                             ║
║       │         ┌────┴──┐   ┌────┴──┐   ┌────┴──┐                         ║
║       │         ▼       ▼   ▼       ▼   ▼       ▼                         ║
║       │    [MongoDB] [Redis] [Colab] [Pickle] [Events]                      ║
║       │    (Primary) (Cache) (Train) (Serve) (Live)                         ║
║       │                          │                                           ║
║       └──────── [Plotly / D3.js Dashboard] ◀──┘                             ║
║                                                                              ║
║   ML Pipeline:  Raw Data → EDA → Feature Eng. → Train → Evaluate → Deploy  ║
║   Principles:   Reproducible · Explainable · Scalable · Production-Ready    ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

---

## 📈 SKILL POWER LEVELS

```
Java                         ████████████████████░   92%  ☕ EXPERT
Python & Data Science        ███████████████████░░   90%  🔥 EXPERT
SQL / NoSQL Databases        ██████████████████░░░   88%  🗄️  EXPERT
Machine Learning (XGBoost)   ██████████████████░░░   86%  🧠 EXPERT
Data Visualization           █████████████████░░░░   82%  📊 ADVANCED
Docker / DevOps              ████████████████░░░░░   78%  🐳 ADVANCED
AWS                          ███████████████░░░░░░   72%  ☁️  ADVANCED
React / Next.js 15           ████████████░░░░░░░░░   58%  ⚡ LEARNING
Node.js / Express / APIs     ███████████░░░░░░░░░░   52%  ⚙️  LEARNING
TypeScript                   ██████████░░░░░░░░░░░   48%  💎 LEARNING
```

---

## 🌐 CONNECT & COLLABORATE

<div align="center">

```
╔══════════════════════════════════════════════════════════════╗
║  💼  OPEN TO: Full-Time · Internships · Freelance · Collab   ║
║  📍  BASED IN: Bhubaneswar, India  |  🌐 Remote Worldwide    ║
║  🎓  GRADUATING: July 2026 — B.Tech CSE, CGPA 8.4            ║
║  ⚡  RESPONSE TIME: < 24 hours                               ║
║  🔬  RESEARCH: Published @ Springer (Rainfall Prediction)    ║
╚══════════════════════════════════════════════════════════════╝
```

<a href="https://linkedin.com/in/deepamjyoti-mohanty">
  <img src="https://img.shields.io/badge/LinkedIn-Let's_Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
<a href="mailto:deepamjyoti12345@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-Drop_a_Mail-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>
<a href="https://github.com/PHONEIX-06">
  <img src="https://img.shields.io/badge/GitHub-PHONEIX--06-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<br/><br/>

<!-- Snake contribution animation -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/PHONEIX-06/PHONEIX-06/output/github-contribution-grid-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/PHONEIX-06/PHONEIX-06/output/github-contribution-grid-snake.svg"/>
  <img alt="GitHub contribution snake" src="https://raw.githubusercontent.com/PHONEIX-06/PHONEIX-06/output/github-contribution-grid-snake-dark.svg"/>
</picture>

<br/>

<!-- WakaTime coding activity -->
## 🕐 CODING ACTIVITY LOG

<!--START_SECTION:waka-->
```text
Java         ███████████████████░░  72.4%  ← Competitive prog, DSA, backend
Python       ████████████████░░░░░  61.8%  ← ML models, data pipelines, EDA
JavaScript   ████░░░░░░░░░░░░░░░░░  10.3%  ← Node.js, Express, frontend
TypeScript   ███░░░░░░░░░░░░░░░░░░   8.1%  ← Next.js, React, APIs
Bash/Shell   █░░░░░░░░░░░░░░░░░░░░   3.2%  ← DevOps, automation
```
<!--END_SECTION:waka-->

> 💡 _Connect your [WakaTime](https://wakatime.com) to display real-time live coding stats!_

<br/>

<!-- Footer wave -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0a0f,40:0d0221,70:1a0533,100:0d0221&height=140&section=footer&text=Let's+Build+the+Future+Together&fontSize=22&fontAlign=50&fontAlignY=55&fontColor=00FFFF&animation=twinkling"/>

</div>

---

<div align="center">

**⚡ "Data is the new electricity — and I'm the power grid." ⚡**

![Visitor Badge](https://img.shields.io/badge/Thanks_for_visiting!-Star_⭐_my_repos-7C3AED?style=for-the-badge&logo=github&logoColor=white)

</div>
