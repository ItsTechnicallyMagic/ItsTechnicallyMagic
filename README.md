<svg viewBox="0 0 960 250" width="960" height="250" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="It's Technically Magic — Sanjana Putchala">
  <defs>
    <linearGradient id="heroBg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#151123" />
      <stop offset="55%" stop-color="#22173c" />
      <stop offset="100%" stop-color="#132533" />
    </linearGradient>

    <radialGradient id="heroOrbA" cx="22%" cy="28%" r="48%">
      <stop offset="0%" stop-color="#c084fc" stop-opacity="0.24" />
      <stop offset="100%" stop-color="#c084fc" stop-opacity="0" />
    </radialGradient>

    <radialGradient id="heroOrbB" cx="82%" cy="52%" r="42%">
      <stop offset="0%" stop-color="#f59e0b" stop-opacity="0.22" />
      <stop offset="60%" stop-color="#34d399" stop-opacity="0.10" />
      <stop offset="100%" stop-color="#34d399" stop-opacity="0" />
    </radialGradient>

    <linearGradient id="titleGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#f7f4ff" />
      <stop offset="58%" stop-color="#e9d5ff" />
      <stop offset="100%" stop-color="#fde68a" />
    </linearGradient>

    <linearGradient id="wingGradL" x1="12" y1="16" x2="60" y2="96" gradientUnits="userSpaceOnUse">
      <stop offset="0%" stop-color="#c084fc" />
      <stop offset="55%" stop-color="#f59e0b" />
      <stop offset="100%" stop-color="#34d399" />
    </linearGradient>

    <linearGradient id="wingGradR" x1="108" y1="16" x2="60" y2="96" gradientUnits="userSpaceOnUse">
      <stop offset="0%" stop-color="#c084fc" />
      <stop offset="55%" stop-color="#f59e0b" />
      <stop offset="100%" stop-color="#34d399" />
    </linearGradient>

    <pattern id="subtleGrid" width="40" height="40" patternUnits="userSpaceOnUse">
      <path d="M 40 0 L 0 0 0 40" fill="none" stroke="#e9d5ff" stroke-opacity="0.06" stroke-width="1" />
    </pattern>

    <style>
      @keyframes floatVertical {
        0%, 100% { transform: translate(735px, 64px) rotate(-4deg); }
        50% { transform: translate(735px, 46px) rotate(4deg); }
      }
      @keyframes flapL {
        0%, 100% { transform: scaleX(1); }
        50% { transform: scaleX(0.58); }
      }
      @keyframes flapR {
        0%, 100% { transform: scaleX(1); }
        50% { transform: scaleX(0.58); }
      }
      @keyframes twinkleA {
        0%, 100% { opacity: 0.25; transform: scale(0.75); }
        50% { opacity: 1; transform: scale(1.2); }
      }
      @keyframes twinkleB {
        0%, 100% { opacity: 0.9; transform: scale(1.1); }
        50% { opacity: 0.2; transform: scale(0.7); }
      }
      .bf-stage { animation: floatVertical 4.2s ease-in-out infinite; }
      .w-left { transform-origin: 60px 60px; animation: flapL 0.65s ease-in-out infinite; }
      .w-right { transform-origin: 60px 60px; animation: flapR 0.65s ease-in-out infinite; }
      .sp-1 { transform-box: fill-box; transform-origin: center; animation: twinkleA 2.6s ease-in-out infinite; }
      .sp-2 { transform-box: fill-box; transform-origin: center; animation: twinkleB 3.1s ease-in-out infinite; }
      .sp-3 { transform-box: fill-box; transform-origin: center; animation: twinkleA 2.9s ease-in-out infinite 0.8s; }
    </style>
  </defs>

  <!-- Main Banner Card -->
  <rect x="2" y="2" width="956" height="246" rx="24" fill="url(#heroBg)" stroke="#c084fc" stroke-opacity="0.32" stroke-width="1.5" />
  <rect x="2" y="2" width="956" height="246" rx="24" fill="url(#subtleGrid)" />
  <rect x="2" y="2" width="956" height="246" rx="24" fill="url(#heroOrbA)" />
  <rect x="2" y="2" width="956" height="246" rx="24" fill="url(#heroOrbB)" />

  <!-- Top Pill Badge -->
  <rect x="48" y="34" width="322" height="28" rx="14" fill="#c084fc" fill-opacity="0.16" stroke="#c084fc" stroke-opacity="0.42" stroke-width="1" />
  <circle cx="66" cy="48" r="4" fill="#34d399" />
  <text x="79" y="52" font-family="'JetBrains Mono', ui-monospace, monospace" font-size="11" font-weight="600" fill="#e9d5ff" letter-spacing="0.5">
    ANALYTICS &amp; INNOVATION • BUILDING IN PUBLIC
  </text>

  <!-- Hero Title & Editorial Subtitle -->
  <text x="48" y="114" font-family="'Plus Jakarta Sans', 'Segoe UI', system-ui, sans-serif" font-size="42" font-weight="800" fill="url(#titleGrad)" letter-spacing="-0.8">
    It's Technically Magic
  </text>

  <text x="48" y="148" font-family="'Plus Jakarta Sans', 'Segoe UI', system-ui, sans-serif" font-size="16.5" font-weight="700" fill="#c084fc">
    Sanjana Putchala  •  Creator @ItsTechnically-Magic
  </text>

  <text x="48" y="182" font-family="'Inter', 'Segoe UI', system-ui, sans-serif" font-size="14" fill="#bcb3d1">
    Turning tangled legacy reporting and manual chores into clean, scalable data products.
  </text>

  <!-- Bottom Metadata Pills -->
  <rect x="48" y="202" width="136" height="22" rx="11" fill="#1e1930" stroke="#e9d5ff" stroke-opacity="0.18" />
  <text x="116" y="216.5" text-anchor="middle" font-family="'JetBrains Mono', ui-monospace, monospace" font-size="10" fill="#bcb3d1">BI &amp; Semantic UX</text>

  <rect x="192" y="202" width="152" height="22" rx="11" fill="#1e1930" stroke="#e9d5ff" stroke-opacity="0.18" />
  <text x="268" y="216.5" text-anchor="middle" font-family="'JetBrains Mono', ui-monospace, monospace" font-size="10" fill="#bcb3d1">Cloud &amp; Automation</text>

  <rect x="352" y="202" width="144" height="22" rx="11" fill="#1e1930" stroke="#e9d5ff" stroke-opacity="0.18" />
  <text x="424" y="216.5" text-anchor="middle" font-family="'JetBrains Mono', ui-monospace, monospace" font-size="10" fill="#bcb3d1">Applied AI &amp; ML</text>

  <!-- Twinkling Ambient Sparkles -->
  <g class="sp-1">
    <path d="M715 44 L718 53 L727 56 L718 59 L715 68 L712 59 L703 56 L712 53 Z" fill="#fde68a" />
  </g>
  <g class="sp-2">
    <path d="M876 62 L878.5 70 L886.5 72.5 L878.5 75 L876 83 L873.5 75 L865.5 72.5 L873.5 70 Z" fill="#34d399" />
  </g>
  <g class="sp-3">
    <path d="M862 172 L864.5 179 L871.5 181.5 L864.5 184 L862 191 L859.5 184 L852.5 181.5 L859.5 179 Z" fill="#c084fc" />
  </g>
  <g class="sp-1">
    <path d="M712 164 L714 170 L720 172 L714 174 L712 180 L710 174 L704 172 L710 170 Z" fill="#f59e0b" />
  </g>

  <!-- Animated Iridescent Magic Butterfly -->
  <g class="bf-stage">
    <!-- Left Wings -->
    <g class="w-left">
      <path d="M59 56 C44 25, 16 16, 11 34 C6 50, 30 64, 58 61 Z" fill="url(#wingGradL)" fill-opacity="0.94" stroke="#ffffff" stroke-opacity="0.65" stroke-width="1.4" />
      <path d="M58 64 C34 65, 16 81, 25 94 C34 105, 54 88, 59 68 Z" fill="url(#wingGradL)" fill-opacity="0.86" stroke="#ffffff" stroke-opacity="0.55" stroke-width="1.4" />
      <path d="M55 56 C40 42, 28 36, 18 35" stroke="#ffffff" stroke-opacity="0.48" stroke-width="1.1" stroke-linecap="round" />
      <circle cx="25" cy="36" r="2.8" fill="#ffffff" fill-opacity="0.85" />
      <circle cx="32" cy="82" r="2.2" fill="#ffffff" fill-opacity="0.75" />
    </g>

    <!-- Right Wings -->
    <g class="w-right">
      <path d="M61 56 C76 25, 104 16, 109 34 C114 50, 90 64, 62 61 Z" fill="url(#wingGradR)" fill-opacity="0.94" stroke="#ffffff" stroke-opacity="0.65" stroke-width="1.4" />
      <path d="M62 64 C86 65, 104 81, 95 94 C86 105, 66 88, 61 68 Z" fill="url(#wingGradR)" fill-opacity="0.86" stroke="#ffffff" stroke-opacity="0.55" stroke-width="1.4" />
      <path d="M65 56 C80 42, 92 36, 102 35" stroke="#ffffff" stroke-opacity="0.48" stroke-width="1.1" stroke-linecap="round" />
      <circle cx="95" cy="36" r="2.8" fill="#ffffff" fill-opacity="0.85" />
      <circle cx="88" cy="82" r="2.2" fill="#ffffff" fill-opacity="0.75" />
    </g>

    <!-- Antennae -->
    <path d="M57 44 C53 33, 47 28, 42 26" stroke="#f7f4ff" stroke-width="1.7" stroke-linecap="round" fill="none" />
    <path d="M63 44 C67 33, 73 28, 78 26" stroke="#f7f4ff" stroke-width="1.7" stroke-linecap="round" fill="none" />
    <circle cx="42" cy="26" r="2.8" fill="#f59e0b" />
    <circle cx="78" cy="26" r="2.8" fill="#f59e0b" />

    <!-- Body -->
    <circle cx="60" cy="44" r="3.6" fill="#f7f4ff" />
    <ellipse cx="60" cy="53" rx="3.8" ry="8" fill="#f7f4ff" />
    <ellipse cx="60" cy="72" rx="3" ry="13.5" fill="#f7f4ff" />
  </g>
</svg>


<svg viewBox="0 0 960 350" width="960" height="350" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Capability Firefly Jar — Five Living Analytics Disciplines">
  <defs>
    <linearGradient id="jarCardBg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#161322" />
      <stop offset="100%" stop-color="#1e1930" />
    </linearGradient>

    <radialGradient id="jarGlow" cx="50%" cy="56%" r="48%">
      <stop offset="0%" stop-color="#c084fc" stop-opacity="0.26" />
      <stop offset="65%" stop-color="#f59e0b" stop-opacity="0.10" />
      <stop offset="100%" stop-color="#c084fc" stop-opacity="0" />
    </radialGradient>

    <linearGradient id="glassRim" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#ffffff" stop-opacity="0.72" />
      <stop offset="50%" stop-color="#c084fc" stop-opacity="0.35" />
      <stop offset="100%" stop-color="#34d399" stop-opacity="0.50" />
    </linearGradient>

    <linearGradient id="corkFill" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#b07d56" />
      <stop offset="50%" stop-color="#d4a373" />
      <stop offset="100%" stop-color="#9c6644" />
    </linearGradient>

    <radialGradient id="ffHalo" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#fef08a" stop-opacity="0.95" />
      <stop offset="45%" stop-color="#f59e0b" stop-opacity="0.42" />
      <stop offset="100%" stop-color="#c084fc" stop-opacity="0" />
    </radialGradient>

    <style>
      @keyframes driftA {
        0%, 100% { transform: translate(0px, 0px); }
        50% { transform: translate(6px, -8px); }
      }
      @keyframes driftB {
        0%, 100% { transform: translate(0px, 0px); }
        50% { transform: translate(-7px, -6px); }
      }
      @keyframes driftC {
        0%, 100% { transform: translate(0px, 0px); }
        50% { transform: translate(5px, 7px); }
      }
      @keyframes glowPulse {
        0%, 100% { opacity: 0.6; }
        50% { opacity: 1; }
      }
      .ff-a { animation: driftA 4.8s ease-in-out infinite; }
      .ff-b { animation: driftB 5.4s ease-in-out infinite; }
      .ff-c { animation: driftC 5.1s ease-in-out infinite; }
      .ff-pulse { animation: glowPulse 2.6s ease-in-out infinite; }
    </style>
  </defs>

  <!-- Outer Showcase Frame -->
  <rect x="2" y="2" width="956" height="346" rx="24" fill="url(#jarCardBg)" stroke="#c084fc" stroke-opacity="0.28" stroke-width="1.5" />

  <!-- ======================================================================
       LEFT SIDE: GLASS APOTHECARY JAR WITH 5 BIOLUMINESCENT FIREFLIES
       ====================================================================== -->
  <g transform="translate(22, 8)">
    <!-- Ground Shadow -->
    <ellipse cx="165" cy="322" rx="104" ry="9" fill="#c084fc" fill-opacity="0.18" />

    <!-- Pedestal Base -->
    <path d="M80 298 H250 L241 314 C239 317 235 319 231 319 H99 C95 319 91 317 89 314 Z" fill="#c084fc" fill-opacity="0.24" stroke="#e9d5ff" stroke-opacity="0.28" stroke-width="1.4" />
    <ellipse cx="165" cy="298" rx="85" ry="5.5" fill="#c084fc" fill-opacity="0.18" stroke="#e9d5ff" stroke-opacity="0.25" stroke-width="1.1" />

    <!-- Cork Stopper -->
    <path d="M131 20 C131 15 137 12 145 12 H185 C193 12 199 15 199 20 L194 45 H136 Z" fill="url(#corkFill)" stroke="#7f5539" stroke-width="1.4" />

    <!-- Glass Collar -->
    <rect x="120" y="43" width="90" height="11" rx="5.5" fill="#251f38" stroke="url(#glassRim)" stroke-width="1.8" />

    <!-- Main Jar Body -->
    <path d="M126 54 C126 67, 66 78, 66 120 V262 C66 283, 81 298, 104 298 H226 C249 298, 264 283, 264 262 V120 C264 78, 204 67, 204 54 Z"
          fill="url(#jarGlow)" stroke="url(#glassRim)" stroke-width="2.4" />

    <!-- Glass Specular Reflections -->
    <path d="M84 118 C84 92, 117 82, 132 76" fill="none" stroke="#ffffff" stroke-opacity="0.52" stroke-width="3" stroke-linecap="round" />
    <path d="M82 134 V248" fill="none" stroke="#ffffff" stroke-opacity="0.38" stroke-width="2.4" stroke-linecap="round" />
    <path d="M248 130 V236" fill="none" stroke="#ffffff" stroke-opacity="0.20" stroke-width="1.6" stroke-linecap="round" stroke-dasharray="16 10" />

    <!-- Firefly 1: BI Storytelling -->
    <g class="ff-a">
      <circle cx="122" cy="124" r="24" fill="url(#ffHalo)" class="ff-pulse" />
      <ellipse cx="116" cy="118" rx="6" ry="3" transform="rotate(-25 116 118)" fill="#ffffff" fill-opacity="0.72" />
      <ellipse cx="128" cy="118" rx="6" ry="3" transform="rotate(25 128 118)" fill="#ffffff" fill-opacity="0.72" />
      <circle cx="122" cy="122" r="3" fill="#f7f4ff" />
      <circle cx="122" cy="127" r="5.5" fill="#facc15" stroke="#ffffff" stroke-width="1.1" />
      <text x="122" y="145" text-anchor="middle" font-family="'Plus Jakarta Sans', 'Segoe UI', sans-serif" font-size="9.5" font-weight="700" fill="#f7f4ff">BI Storytelling</text>
    </g>

    <!-- Firefly 2: AI & Applied ML -->
    <g class="ff-b">
      <circle cx="208" cy="138" r="24" fill="url(#ffHalo)" class="ff-pulse" />
      <ellipse cx="202" cy="132" rx="6" ry="3" transform="rotate(-25 202 132)" fill="#ffffff" fill-opacity="0.72" />
      <ellipse cx="214" cy="132" rx="6" ry="3" transform="rotate(25 214 132)" fill="#ffffff" fill-opacity="0.72" />
      <circle cx="208" cy="136" r="3" fill="#f7f4ff" />
      <circle cx="208" cy="141" r="5.5" fill="#f472b6" stroke="#ffffff" stroke-width="1.1" />
      <text x="208" y="159" text-anchor="middle" font-family="'Plus Jakarta Sans', 'Segoe UI', sans-serif" font-size="9.5" font-weight="700" fill="#f7f4ff">AI &amp; ML</text>
    </g>

    <!-- Firefly 3: DevOps & Governance -->
    <g class="ff-c">
      <circle cx="165" cy="186" r="24" fill="url(#ffHalo)" class="ff-pulse" />
      <ellipse cx="159" cy="180" rx="6" ry="3" transform="rotate(-25 159 180)" fill="#ffffff" fill-opacity="0.72" />
      <ellipse cx="171" cy="180" rx="6" ry="3" transform="rotate(25 171 180)" fill="#ffffff" fill-opacity="0.72" />
      <circle cx="165" cy="184" r="3" fill="#f7f4ff" />
      <circle cx="165" cy="189" r="5.5" fill="#c084fc" stroke="#ffffff" stroke-width="1.1" />
      <text x="165" y="207" text-anchor="middle" font-family="'Plus Jakarta Sans', 'Segoe UI', sans-serif" font-size="9.5" font-weight="700" fill="#f7f4ff">Governance</text>
    </g>

    <!-- Firefly 4: Cloud & Data Eng -->
    <g class="ff-a">
      <circle cx="116" cy="238" r="24" fill="url(#ffHalo)" class="ff-pulse" />
      <ellipse cx="110" cy="232" rx="6" ry="3" transform="rotate(-25 110 232)" fill="#ffffff" fill-opacity="0.72" />
      <ellipse cx="122" cy="232" rx="6" ry="3" transform="rotate(25 122 232)" fill="#ffffff" fill-opacity="0.72" />
      <circle cx="116" cy="236" r="3" fill="#f7f4ff" />
      <circle cx="116" cy="241" r="5.5" fill="#34d399" stroke="#ffffff" stroke-width="1.1" />
      <text x="116" y="259" text-anchor="middle" font-family="'Plus Jakarta Sans', 'Segoe UI', sans-serif" font-size="9.5" font-weight="700" fill="#f7f4ff">Cloud Eng</text>
    </g>

    <!-- Firefly 5: Core Languages -->
    <g class="ff-b">
      <circle cx="212" cy="244" r="24" fill="url(#ffHalo)" class="ff-pulse" />
      <ellipse cx="206" cy="238" rx="6" ry="3" transform="rotate(-25 206 238)" fill="#ffffff" fill-opacity="0.72" />
      <ellipse cx="218" cy="238" rx="6" ry="3" transform="rotate(25 218 238)" fill="#ffffff" fill-opacity="0.72" />
      <circle cx="212" cy="242" r="3" fill="#f7f4ff" />
      <circle cx="212" cy="247" r="5.5" fill="#38bdf8" stroke="#ffffff" stroke-width="1.1" />
      <text x="212" y="265" text-anchor="middle" font-family="'Plus Jakarta Sans', 'Segoe UI', sans-serif" font-size="9.5" font-weight="700" fill="#f7f4ff">Query Craft</text>
    </g>
  </g>

  <!-- Subtle Luminous Connector Arcs -->
  <g fill="none" stroke="#c084fc" stroke-opacity="0.28" stroke-width="1.3" stroke-dasharray="4 4">
    <path d="M 296 125 C 325 125, 330 56, 360 56" />
    <path d="M 300 155 C 330 155, 332 115, 360 115" />
    <path d="M 300 185 L 360 175" />
    <path d="M 298 220 C 330 220, 332 235, 360 235" />
    <path d="M 294 252 C 325 252, 330 295, 360 295" />
  </g>

  <!-- ======================================================================
       RIGHT SIDE: 5 LIVING DISCIPLINE CARDS
       ====================================================================== -->
  <!-- Card 1 -->
  <g transform="translate(364, 28)">
    <rect width="564" height="50" rx="14" fill="#13101e" stroke="#facc15" stroke-opacity="0.38" stroke-width="1.2" />
    <circle cx="24" cy="25" r="7" fill="#facc15" />
    <text x="44" y="22" font-family="'Plus Jakarta Sans', 'Segoe UI', sans-serif" font-size="13.5" font-weight="800" fill="#f7f4ff">BI Storytelling &amp; Semantic UX</text>
    <text x="44" y="39" font-family="'Inter', 'Segoe UI', sans-serif" font-size="11.5" fill="#bcb3d1">Power BI • Advanced DAX • M Query • OBIEE • Tableau • MicroStrategy • Executive Dashboards</text>
  </g>

  <!-- Card 2 -->
  <g transform="translate(364, 88)">
    <rect width="564" height="50" rx="14" fill="#13101e" stroke="#f472b6" stroke-opacity="0.38" stroke-width="1.2" />
    <circle cx="24" cy="25" r="7" fill="#f472b6" />
    <text x="44" y="22" font-family="'Plus Jakarta Sans', 'Segoe UI', sans-serif" font-size="13.5" font-weight="800" fill="#f7f4ff">AI &amp; Applied Machine Learning</text>
    <text x="44" y="39" font-family="'Inter', 'Segoe UI', sans-serif" font-size="11.5" fill="#bcb3d1">Python (Pandas, Scikit-learn) • Autoencoders • Customer Segmentation • Forecasting • NLP • A/B Testing</text>
  </g>

  <!-- Card 3 -->
  <g transform="translate(364, 148)">
    <rect width="564" height="50" rx="14" fill="#13101e" stroke="#c084fc" stroke-opacity="0.38" stroke-width="1.2" />
    <circle cx="24" cy="25" r="7" fill="#c084fc" />
    <text x="44" y="22" font-family="'Plus Jakarta Sans', 'Segoe UI', sans-serif" font-size="13.5" font-weight="800" fill="#f7f4ff">Semantic DevOps &amp; Governance</text>
    <text x="44" y="39" font-family="'Inter', 'Segoe UI', sans-serif" font-size="11.5" fill="#bcb3d1">PBIP &amp; TMDL • Git Version Control &amp; CI/CD • Row-Level Security • AI Copilot DAX Review • Six Sigma</text>
  </g>

  <!-- Card 4 -->
  <g transform="translate(364, 208)">
    <rect width="564" height="50" rx="14" fill="#13101e" stroke="#34d399" stroke-opacity="0.38" stroke-width="1.2" />
    <circle cx="24" cy="25" r="7" fill="#34d399" />
    <text x="44" y="22" font-family="'Plus Jakarta Sans', 'Segoe UI', sans-serif" font-size="13.5" font-weight="800" fill="#f7f4ff">Cloud Platforms &amp; Data Engineering</text>
    <text x="44" y="39" font-family="'Inter', 'Segoe UI', sans-serif" font-size="11.5" fill="#bcb3d1">Databricks • Microsoft Azure (ADF, Synapse) • Snowflake • Amazon Redshift • Adaptive ELT Pipelines</text>
  </g>

  <!-- Card 5 -->
  <g transform="translate(364, 268)">
    <rect width="564" height="50" rx="14" fill="#13101e" stroke="#38bdf8" stroke-opacity="0.38" stroke-width="1.2" />
    <circle cx="24" cy="25" r="7" fill="#38bdf8" />
    <text x="44" y="22" font-family="'Plus Jakarta Sans', 'Segoe UI', sans-serif" font-size="13.5" font-weight="800" fill="#f7f4ff">Core Languages &amp; Query Craft</text>
    <text x="44" y="39" font-family="'Inter', 'Segoe UI', sans-serif" font-size="11.5" fill="#bcb3d1">SQL Performance Tuning (Views, CTEs, Indexing) • Python • DAX • M Query • R • SAS • VBA</text>
  </g>
</svg>
