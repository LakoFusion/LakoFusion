<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1180 610" width="1180" height="610" role="img" aria-label="Lê Duy Nhật - Python Developer and Backend Specialist">
  <defs>
    <!-- Background Gradient -->
    <radialGradient id="bg-grad-dark" cx="70%" cy="30%" r="80%">
      <stop offset="0%" stop-color="#0c192c" />
      <stop offset="50%" stop-color="#080f1a" />
      <stop offset="100%" stop-color="#030712" />
    </radialGradient>

    <!-- Subtle Glow Accents -->
    <radialGradient id="cyan-glow" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#00f2fe" stop-opacity="0.18" />
      <stop offset="100%" stop-color="#00f2fe" stop-opacity="0" />
    </radialGradient>
    <radialGradient id="purple-glow" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#7928ca" stop-opacity="0.22" />
      <stop offset="100%" stop-color="#7928ca" stop-opacity="0" />
    </radialGradient>

    <!-- Card Linear Gradient -->
    <linearGradient id="card-grad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#1e293b" stop-opacity="0.45" />
      <stop offset="100%" stop-color="#0f172a" stop-opacity="0.30" />
    </linearGradient>

    <linearGradient id="cyan-accent" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#00f2fe" />
      <stop offset="100%" stop-color="#4facfe" />
    </linearGradient>

    <!-- Subtle Scanline Pattern -->
    <pattern id="scanlines" width="100" height="4" patternUnits="userSpaceOnUse">
      <line x1="0" y1="0" x2="100" y2="0" stroke="#ffffff" stroke-opacity="0.02" stroke-width="1" />
    </pattern>

    <style>
      .mono { font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace; }
      .title { font-weight: 700; fill: #f8fafc; letter-spacing: -0.5px; }
      .accent { fill: #38bdf8; font-weight: 600; }
      .muted { fill: #64748b; font-size: 13px; }
      .lbl { fill: #00f2fe; font-size: 13px; font-weight: 600; }
      .val { fill: #e2e8f0; font-size: 13px; }
      .ascii-art { font-size: 9.5px; line-height: 11px; fill: #38bdf8; opacity: 0.82; }
      .pill-bg { fill: #0f172a; stroke: #334155; stroke-width: 1; rx: 6px; }
      .pill-text { fill: #94a3b8; font-size: 11px; font-weight: 500; }
    </style>
  </defs>

  <!-- Canvas Background -->
  <rect width="1180" height="610" rx="24" fill="url(#bg-grad-dark)" stroke="#1e293b" stroke-width="1.5" />
  <circle cx="200" cy="150" r="280" fill="url(#cyan-glow)" />
  <circle cx="950" cy="450" r="320" fill="url(#purple-glow)" />
  <rect width="1180" height="610" rx="24" fill="url(#scanlines)" />

  <!-- Top Terminal Bar -->
  <g transform="translate(30, 24)">
    <circle cx="12" cy="12" r="5.5" fill="#ef4444" />
    <circle cx="28" cy="12" r="5.5" fill="#f59e0b" />
    <circle cx="44" cy="12" r="5.5" fill="#10b981" />
    <text x="70" y="16" class="mono muted" font-size="12">lako@core-terminal: ~ (prod)</text>
    <rect x="990" y="2" width="130" height="20" rx="10" fill="#0f172a" stroke="#1e293b" />
    <circle cx="1004" cy="12" r="3" fill="#10b981">
      <animate attributeName="opacity" values="1;0.3;1" dur="2s" repeatCount="indefinite" />
    </circle>
    <text x="1015" y="16" class="mono" font-size="10" fill="#10b981" font-weight="600">SYSTEM ACTIVE</text>
  </g>

  <!-- ==================== LEFT PANEL: VISUAL.MAP ==================== -->
  <g transform="translate(30, 65)">
    <rect width="440" height="515" rx="16" fill="url(#card-grad)" stroke="#1e293b" stroke-width="1" />
    
    <!-- Header -->
    <path d="M 20 20 L 30 20" stroke="#00f2fe" stroke-width="2" />
    <text x="40" y="25" class="mono lbl" font-size="11">VISUAL.IDENTITY // MATRIX_PORTRAIT</text>
    <line x1="20" y1="38" x2="420" y2="38" stroke="#1e293b" stroke-width="1" />

    <!-- ASCII Portrait Render -->
    <g transform="translate(68, 62)">
      <rect width="304" height="300" rx="12" fill="#030712" fill-opacity="0.75" stroke="#334155" stroke-dasharray="3,3" />
      <text x="152" y="35" text-anchor="middle" class="mono ascii-art">
        <tspan x="152" dy="0">    .:::---==++++==---:::.    </tspan>
        <tspan x="152" dy="13">  .::+*###%@@@@@@@@%###*+::.  </tspan>
        <tspan x="152" dy="13"> :+*%@@@@@@@@@@@@@@@@@@@@%*+: </tspan>
        <tspan x="152" dy="13">:*#@@@@@@@@@@@@@@@@@@@@@@@@#*:</tspan>
        <tspan x="152" dy="13">=*@@@@@@@@@@@@@@@@@@@@@@@@@@*=</tspan>
        <tspan x="152" dy="13">#%@@@@@@%SSSSSSSSSS%@@@@@@@@%#</tspan>
        <tspan x="152" dy="13">#%@@@@@@*::......::*@@@@@@@@%#</tspan>
        <tspan x="152" dy="13">*#@@@@@@: [O]  [O] :@@@@@@@@#*</tspan>
        <tspan x="152" dy="13">:*@@@@@@.    ||    .@@@@@@@@*: </tspan>
        <tspan x="152" dy="13"> :*#@@@@+   \==/   +@@@@@@#*: </tspan>
        <tspan x="152" dy="13">  .=*%@@@*-......-*@@@@%*=.  </tspan>
        <tspan x="152" dy="13">   :+*#@@@@@@@@@@@@@@#*+:   </tspan>
        <tspan x="152" dy="13">  .=*%@@@@@@@@@@@@@@@@%*=.  </tspan>
        <tspan x="152" dy="13"> :*#@@@@@@@@@@@@@@@@@@@@#*: </tspan>
        <tspan x="152" dy="13">:*%@@@@@@@@@@@@@@@@@@@@@@%*:</tspan>
        <tspan x="152" dy="13">=*@@@@@@@@@@@@@@@@@@@@@@@@@@*=</tspan>
        <tspan x="152" dy="13">#%@@@@@@@@@@@@@@@@@@@@@@@@@@%#</tspan>
        <tspan x="152" dy="13">==============================</tspan>
        <animate attributeName="opacity" values="0.75;0.95;0.75" dur="3s" repeatCount="indefinite" />
      </text>

      <!-- Scanline beam animation inside portrait -->
      <line x1="0" y1="0" x2="304" y2="0" stroke="#00f2fe" stroke-width="1.5" opacity="0.4">
        <animateTransform attributeName="transform" type="translate" from="0 0" to="0 300" dur="4s" repeatCount="indefinite" />
      </line>
    </g>

    <!-- Terminal Command Info -->
    <g transform="translate(25, 410)">
      <rect width="390" height="78" rx="8" fill="#030712" fill-opacity="0.6" stroke="#1e293b" />
      <text x="16" y="24" class="mono" font-size="12" fill="#10b981">~/workspace/lako $</text>
      <text x="170" y="24" class="mono" font-size="12" fill="#e2e8f0">./deploy --status</text>
      <text x="16" y="46" class="mono muted" font-size="11">[OK] Workflows, APIs &amp; Daemons Synchronized</text>
      <text x="16" y="64" class="mono" font-size="11" fill="#38bdf8">&gt; ARCH: Automation &amp; Backend Infrastructure</text>
    </g>
  </g>

  <!-- ==================== RIGHT PANEL: SYSTEM.INFO ==================== -->
  <g transform="translate(490, 65)">
    <rect width="660" height="515" rx="16" fill="url(#card-grad)" stroke="#1e293b" stroke-width="1" />

    <!-- Terminal Prompt / Header -->
    <g transform="translate(30, 24)">
      <text x="0" y="0" class="mono lbl" font-size="11">SYSTEM.INFO // DEVELOPER_PROFILE</text>
      <line x1="0" y1="12" x2="600" y2="12" stroke="#1e293b" stroke-width="1" />
    </g>

    <!-- Identity & Role -->
    <g transform="translate(30, 75)">
      <text x="0" y="0" class="mono title" font-size="28">Lê Duy Nhật</text>
      <text x="210" y="-3" class="mono muted" font-size="15">(@lakofusion)</text>
      
      <!-- Animated Role Switcher -->
      <g transform="translate(0, 24)">
        <text class="mono accent" font-size="15">&gt; Python Developer &amp; Automation Engineer
          <animate attributeName="opacity" values="1;1;0;0;1" keyTimes="0;0.45;0.5;0.95;1" dur="7s" repeatCount="indefinite" />
        </text>
        <text class="mono accent" font-size="15">&gt; Backend Utilities &amp; Systems Builder
          <animate attributeName="opacity" values="0;0;1;1;0" keyTimes="0;0.45;0.5;0.95;1" dur="7s" repeatCount="indefinite" />
        </text>
        <line x1="395" y1="-14" x2="395" y2="2" stroke="#00f2fe" stroke-width="2">
          <animate attributeName="opacity" values="0;1;0" dur="0.8s" repeatCount="indefinite" />
        </line>
      </g>
      <text x="0" y="52" class="mono muted" font-size="13">Specialized in automated scripts, scalable backends &amp; microservices.</text>
    </g>

    <line x1="30" y1="165" x2="630" y2="165" stroke="#1e293b" stroke-width="1" />

    <!-- Specifications Table -->
    <g transform="translate(30, 195)">
      <!-- Row 1 -->
      <text x="0" y="0" class="mono lbl">&gt; PRIMARY</text>
      <text x="120" y="0" class="mono val">Python, Go, Lua</text>

      <text x="310" y="0" class="mono lbl">&gt; FRAMEWORKS</text>
      <text x="440" y="0" class="mono val">FastAPI, Flask, Socket.io</text>

      <!-- Row 2 -->
      <text x="0" y="32" class="mono lbl">&gt; AUTOMATION</text>
      <text x="120" y="32" class="mono val">Selenium, OpenCV, NumPy</text>

      <text x="310" y="32" class="mono lbl">&gt; PLATFORMS</text>
      <text x="440" y="32" class="mono val">Docker, Vercel, Netlify</text>

      <!-- Row 3 -->
      <text x="0" y="64" class="mono lbl">&gt; DESIGN</text>
      <text x="120" y="64" class="mono val">Figma, Canva</text>

      <text x="310" y="64" class="mono lbl">&gt; COMMITS</text>
      <text x="440" y="64" class="mono val" fill="#10b981">CI/CD &amp; Git Workflows</text>
    </g>

    <line x1="30" y1="285" x2="630" y2="285" stroke="#1e293b" stroke-width="1" />

    <!-- Tech Stack Matrix Pills -->
    <g transform="translate(30, 310)">
      <text x="0" y="0" class="mono lbl" font-size="11">DEPLOYED TECH MATRIX</text>
      <g transform="translate(0, 16)">
        <!-- Pill 1 -->
        <rect x="0" y="0" width="76" height="26" class="pill-bg" />
        <circle cx="10" cy="13" r="3" fill="#38bdf8" />
        <text x="20" y="17" class="mono pill-text">Python</text>

        <!-- Pill 2 -->
        <rect x="84" y="0" width="60" height="26" class="pill-bg" />
        <circle cx="94" cy="13" r="3" fill="#00add8" />
        <text x="104" y="17" class="mono pill-text">Go</text>

        <!-- Pill 3 -->
        <rect x="152" y="0" width="64" height="26" class="pill-bg" />
        <circle cx="162" cy="13" r="3" fill="#5865f2" />
        <text x="172" y="17" class="mono pill-text">Lua</text>

        <!-- Pill 4 -->
        <rect x="224" y="0" width="80" height="26" class="pill-bg" />
        <circle cx="234" cy="13" r="3" fill="#059669" />
        <text x="244" y="17" class="mono pill-text">FastAPI</text>

        <!-- Pill 5 -->
        <rect x="312" y="0" width="70" height="26" class="pill-bg" />
        <circle cx="322" cy="13" r="3" fill="#f8fafc" />
        <text x="332" y="17" class="mono pill-text">Flask</text>

        <!-- Pill 6 -->
        <rect x="390" y="0" width="80" height="26" class="pill-bg" />
        <circle cx="400" cy="13" r="3" fill="#2496ed" />
        <text x="410" y="17" class="mono pill-text">Docker</text>

        <!-- Pill 7 -->
        <rect x="478" y="0" width="90" height="26" class="pill-bg" />
        <circle cx="488" cy="13" r="3" fill="#10b981" />
        <text x="498" y="17" class="mono pill-text">Selenium</text>
      </g>
    </g>

    <!-- Social Signals / Status -->
    <g transform="translate(30, 400)">
      <rect width="600" height="85" rx="10" fill="#030712" fill-opacity="0.6" stroke="#1e293b" />
      <text x="20" y="24" class="mono lbl" font-size="11">&gt; CHANNELS &amp; ENDPOINTS</text>
      <text x="20" y="48" class="mono val">Discord: <tspan fill="#38bdf8">rxw8Hwk3qA</tspan></text>
      <text x="240" y="48" class="mono val">YouTube: <tspan fill="#38bdf8">@lakofusion2010</tspan></text>
      <text x="20" y="68" class="mono val">TikTok: <tspan fill="#38bdf8">@lakofusion</tspan></text>
      <text x="240" y="68" class="mono muted">Status: <tspan fill="#10b981">Available for Automation Projects</tspan></text>
    </g>
  </g>
</svg>
