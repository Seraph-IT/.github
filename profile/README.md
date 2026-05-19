<!--
============================================================================
  SERAPH-IT · GitHub Organization Profile
  ----------------------------------------------------------------------------
  File:    profile/README.md
  Renders: https://github.com/Seraph-IT
  Brand:   seraph-it.de  ·  "IT that takes responsibility."
  ----------------------------------------------------------------------------
  Notes for maintainers:
    · Inline SVGs are embedded via <img> data-tags or render services so
      GitHub renders them on .github org profiles.
    · Do NOT move the <picture> blocks — they deliver light/dark variants.
    · Full brand palette in the "Brand System" comment at the bottom.
============================================================================
-->

<!-- ════════════════════════════════════════════════════════════════════════
     ░▒▓█ HERO · ANIMATED ENTRANCE  █▓▒░
     ════════════════════════════════════════════════════════════════════════ -->

<div align="center">

<a href="https://seraph-it.de">
  <img
    src="https://capsule-render.vercel.app/api?type=waving&color=0:0B0F1A,15:1D4ED8,50:FFFFFF,85:E63946,100:0B0F1A&height=280&section=header&text=SERAPH-IT&fontSize=110&fontColor=FFFFFF&animation=fadeIn&fontAlignY=36&desc=IT%20That%20Takes%20Responsibility.&descAlignY=58&descSize=22&stroke=E63946&strokeWidth=1"
    width="100%"
    alt="Seraph-IT — IT That Takes Responsibility."
  />
</a>

<!-- ─── Animated typing manifest ─────────────────────────────────────── -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=800&size=26&pause=900&color=E63946&center=true&vCenter=true&multiline=false&width=900&height=46&lines=%E2%96%B6+Defensive+Security+%C2%B7+ITSM+%C2%B7+Compliance+Engineering;%E2%96%B6+Frappe+%C2%B7+ERPNext+%C2%B7+Wazuh+%C2%B7+Helpdesk+%C2%B7+M365;%E2%96%B6+NIS2+%C2%B7+ISO%E2%80%AF27001+%C2%B7+BSI+Grundschutz+%C2%B7+GDPR+Art.%E2%80%AF28;%E2%96%B6+70%25+of+all+tickets+answered+in+%E2%89%A4+2+hours;%E2%96%B6+Engineered+in+Germany+%E2%80%94+Hardened+for+Europe"/>
  <img alt="Seraph-IT manifest" src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=800&size=26&pause=900&color=DC2626&center=true&vCenter=true&multiline=false&width=900&height=46&lines=%E2%96%B6+Defensive+Security+%C2%B7+ITSM+%C2%B7+Compliance+Engineering;%E2%96%B6+Frappe+%C2%B7+ERPNext+%C2%B7+Wazuh+%C2%B7+Helpdesk+%C2%B7+M365;%E2%96%B6+NIS2+%C2%B7+ISO%E2%80%AF27001+%C2%B7+BSI+Grundschutz+%C2%B7+GDPR+Art.%E2%80%AF28;%E2%96%B6+70%25+of+all+tickets+answered+in+%E2%89%A4+2+hours;%E2%96%B6+Engineered+in+Germany+%E2%80%94+Hardened+for+Europe"/>
</picture>

<br/>

<!-- ─── Inline animated SVG · Pulse Beacon (Red / White / Blue) ────────── -->
<svg width="92%" height="64" viewBox="0 0 960 64" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Seraph-IT live pulse">
  <defs>
    <linearGradient id="bgFade" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   stop-color="#0B0F1A" stop-opacity="0"/>
      <stop offset="50%"  stop-color="#0B0F1A" stop-opacity="0.65"/>
      <stop offset="100%" stop-color="#0B0F1A" stop-opacity="0"/>
    </linearGradient>
    <linearGradient id="seraphLine" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#1D4ED8">
        <animate attributeName="stop-color" values="#1D4ED8;#FFFFFF;#E63946;#FFFFFF;#1D4ED8" dur="7s" repeatCount="indefinite"/>
      </stop>
      <stop offset="50%" stop-color="#FFFFFF">
        <animate attributeName="stop-color" values="#FFFFFF;#E63946;#FFFFFF;#1D4ED8;#FFFFFF" dur="7s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" stop-color="#E63946">
        <animate attributeName="stop-color" values="#E63946;#1D4ED8;#FFFFFF;#E63946;#1D4ED8" dur="7s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>
    <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="2.5" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>

  <rect x="0" y="0" width="960" height="64" fill="url(#bgFade)"/>
  <line x1="20" y1="32" x2="940" y2="32" stroke="url(#seraphLine)" stroke-width="2" stroke-linecap="round" filter="url(#glow)"/>

  <!-- pulse orb -->
  <circle cx="0" cy="32" r="9" fill="#E63946" filter="url(#glow)">
    <animate attributeName="cx"   values="20;940;20"               dur="7s" repeatCount="indefinite"/>
    <animate attributeName="fill" values="#E63946;#1D4ED8;#E63946" dur="7s" repeatCount="indefinite"/>
    <animate attributeName="r"    values="9;14;9"                  dur="1.4s" repeatCount="indefinite"/>
  </circle>

  <!-- anchors -->
  <circle cx="20"  cy="32" r="5" fill="#1D4ED8"><animate attributeName="opacity" values="1;0.35;1" dur="1.6s" repeatCount="indefinite"/></circle>
  <circle cx="940" cy="32" r="5" fill="#E63946"><animate attributeName="opacity" values="0.35;1;0.35" dur="1.6s" repeatCount="indefinite"/></circle>

  <!-- center label -->
  <text x="480" y="22" text-anchor="middle" font-family="JetBrains Mono, monospace" font-size="11" letter-spacing="6" fill="#FFFFFF" opacity="0.85">
    G U A R D I A N S   A T   T H E   G A T E
    <animate attributeName="opacity" values="0.45;1;0.45" dur="3.2s" repeatCount="indefinite"/>
  </text>
</svg>

<!-- ─── Compliance & Trust Badges ────────────────────────────────────── -->
<p>
  <img alt="NIS2 Art. 21"    src="https://img.shields.io/badge/NIS2-Article%2021-E63946?style=for-the-badge&logo=shieldsdotio&logoColor=white&labelColor=0B0F1A"/>
  <img alt="ISO 27001"       src="https://img.shields.io/badge/ISO%2027001-Aligned-1D4ED8?style=for-the-badge&logo=verizon&logoColor=white&labelColor=0B0F1A"/>
  <img alt="BSI Grundschutz" src="https://img.shields.io/badge/BSI-Grundschutz-E63946?style=for-the-badge&logo=lock&logoColor=white&labelColor=0B0F1A"/>
  <img alt="GDPR Art. 28"    src="https://img.shields.io/badge/GDPR-Art.%2028-FFFFFF?style=for-the-badge&logo=gnuprivacyguard&logoColor=0B0F1A&labelColor=FFFFFF"/>
  <img alt="DORA-ready"      src="https://img.shields.io/badge/DORA-Ready-1D4ED8?style=for-the-badge&logo=europeanunion&logoColor=white&labelColor=0B0F1A"/>
  <img alt="VDS 10000"       src="https://img.shields.io/badge/VDS-10000-E63946?style=for-the-badge&logo=verizon&logoColor=white&labelColor=0B0F1A"/>
  <img alt="CIS Benchmarks"  src="https://img.shields.io/badge/CIS-Benchmarks-1D4ED8?style=for-the-badge&logo=cisco&logoColor=white&labelColor=0B0F1A"/>
  <img alt="Made in Germany" src="https://img.shields.io/badge/Made%20in-Germany-FFFFFF?style=for-the-badge&logo=mapbox&logoColor=0B0F1A&labelColor=FFFFFF"/>
</p>

</div>

<!-- ════════════════════════════════════════════════════════════════════════
     ░▒▓█ MANIFEST  █▓▒░
     ════════════════════════════════════════════════════════════════════════ -->

<h2 align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=900&size=28&pause=2500&color=E63946&center=true&vCenter=true&width=720&height=44&lines=%E2%9D%96+Who+We+Are"/>
    <img alt="Who We Are" src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=900&size=28&pause=2500&color=DC2626&center=true&vCenter=true&width=720&height=44&lines=%E2%9D%96+Who+We+Are"/>
  </picture>
</h2>

<p align="center">
  <b>Seraph-IT</b> is the IT &amp; Security partner from <b>Cologne, Germany</b> for manufacturing,
  trades, and technical service providers in the Rhine region.<br/>
  We take ownership of your IT operations so you can focus on your core business — with
  <b>clear SLAs</b>, <b>transparent processes</b>, and zero vendor lock-in.<br/><br/>
  <i>"We solve problems within guaranteed timeframes.<br/>Not with excuses."</i>
</p>

---

<!-- ════════════════════════════════════════════════════════════════════════
     ░▒▓█ LIVE METRICS  █▓▒░
     ════════════════════════════════════════════════════════════════════════ -->

<div align="center">

<table>
<tr>
<td align="center" width="25%">
<img src="https://img.shields.io/badge/-%E2%89%A4%202%20h-E63946?style=for-the-badge&labelColor=0B0F1A&label=RESPONSE%20SLA"/>
<br/><sub>70% of all tickets answered</sub>
</td>
<td align="center" width="25%">
<img src="https://img.shields.io/badge/-4-1D4ED8?style=for-the-badge&labelColor=0B0F1A&label=LOCATIONS%20DE"/>
<br/><sub>Cologne · Rhine region · Remote</sub>
</td>
<td align="center" width="25%">
<img src="https://img.shields.io/badge/-3%E2%80%93200-FFFFFF?style=for-the-badge&labelColor=0B0F1A&label=TARGET%20CLIENTS"/>
<br/><sub>technical SMEs &amp; critical infrastructure-adjacent</sub>
</td>
<td align="center" width="25%">
<img src="https://img.shields.io/badge/-0-E63946?style=for-the-badge&labelColor=0B0F1A&label=VENDOR%20LOCK-IN"/>
<br/><sub>Open-Source-First</sub>
</td>
</tr>
</table>

</div>

---

<!-- ════════════════════════════════════════════════════════════════════════
     ░▒▓█ DIVISIONS  █▓▒░
     ════════════════════════════════════════════════════════════════════════ -->

<h2 align="center">⚙️&nbsp;&nbsp;Two Divisions — One Promise</h2>

<table>
<tr>
<td width="50%" valign="top">

### 🛡️ &nbsp;Division&nbsp;I &nbsp;·&nbsp; IT&nbsp;&amp;&nbsp;Security

<sub>Audit-first. Test-first. Defense-in-depth.</sub>

- 🖥️ &nbsp; **Workplace** — PC / Mac / Linux, onboarding, device leasing
- ☁️ &nbsp; **Microsoft 365 & Communications** — licensing, security, VoIP
- 🧱 &nbsp; **Server & Infrastructure** — Proxmox, storage, backup, virtualisation
- 🔥 &nbsp; **Network Security** — firewall management, segmentation, VPN
- 🚨 &nbsp; **Defensive Security** — Wazuh SOC, incident response, threat hunting
- 📜 &nbsp; **Compliance Engineering** — NIS2 · ISO 27001 · BSI · DORA · VDS 10000
- 🛰️ &nbsp; **Proactive Monitoring** — 24/7, patch & vulnerability management
- 🇪🇺 &nbsp; **Digital Sovereignty** — Nextcloud, Proxmox, open-source stack

</td>
<td width="50%" valign="top">

### 🤖 &nbsp;Division&nbsp;II &nbsp;·&nbsp; AI&nbsp;&amp;&nbsp;Automation

<sub>From process audit to production-ready agent.</sub>

- 📄 &nbsp; **Document Automation** — extraction, classification, routing
- 🔍 &nbsp; **Process Analysis** — bottleneck mapping, ROI modelling
- 🧠 &nbsp; **Assistance Systems** — RAG, internal copilots, knowledge bases
- 📊 &nbsp; **AI-Driven Evaluations** — forecasting, anomaly detection, reporting
- 🧾 &nbsp; **Automated Accounting** — document recognition, DATEV bridges
- 🏗️ &nbsp; **VOB/B Automation** — construction workflows, digital site logs
- 🛒 &nbsp; **Site Ordering Systems** — mobile, offline-capable, ERPNext-bound
- 🧭 &nbsp; **Software Selection Consulting** — vendor-neutral, fully documented

</td>
</tr>
</table>

---

<!-- ════════════════════════════════════════════════════════════════════════
     ░▒▓█ HOW WE BUILD  █▓▒░
     ════════════════════════════════════════════════════════════════════════ -->

<h2 align="center">🏗️&nbsp;&nbsp;How We Build</h2>

<div align="center">

<table>
<tr>
  <td align="center" width="20%"><b>🔒 Audit-first</b><br/><sub>Every workflow tags its<br/>compliance obligations in code</sub></td>
  <td align="center" width="20%"><b>✅ Test-first</b><br/><sub>No PR without green CI,<br/>no merge without review</sub></td>
  <td align="center" width="20%"><b>📝 ADR-driven</b><br/><sub>Architecture decisions are<br/>documented, not verbal</sub></td>
  <td align="center" width="20%"><b>♻️ Idempotent</b><br/><sub>Migrations, crons, hooks —<br/>everything re-runnable</sub></td>
  <td align="center" width="20%"><b>🧱 Defense-in-depth</b><br/><sub>Tenant binding, PII redaction,<br/>fail-closed validators</sub></td>
</tr>
</table>

</div>

---

<!-- ════════════════════════════════════════════════════════════════════════
     ░▒▓█ INDUSTRIES  █▓▒░
     ════════════════════════════════════════════════════════════════════════ -->

<h2 align="center">🏭&nbsp;&nbsp;Industries We Understand</h2>

<div align="center">

<img src="https://img.shields.io/badge/Manufacturing-1D4ED8?style=for-the-badge&labelColor=0B0F1A"/>
<img src="https://img.shields.io/badge/Trades%20%26%20Crafts-E63946?style=for-the-badge&labelColor=0B0F1A"/>
<img src="https://img.shields.io/badge/Construction%20%26%20VOB-FFFFFF?style=for-the-badge&labelColor=0B0F1A"/>
<img src="https://img.shields.io/badge/Property%20Management-1D4ED8?style=for-the-badge&labelColor=0B0F1A"/>
<img src="https://img.shields.io/badge/Real%20Estate%20Brokers-E63946?style=for-the-badge&labelColor=0B0F1A"/>
<img src="https://img.shields.io/badge/Logistics-FFFFFF?style=for-the-badge&labelColor=0B0F1A"/>
<br/>
<img src="https://img.shields.io/badge/Accounting%20Firms-1D4ED8?style=for-the-badge&labelColor=0B0F1A"/>
<img src="https://img.shields.io/badge/Marketing%20Agencies-E63946?style=for-the-badge&labelColor=0B0F1A"/>
<img src="https://img.shields.io/badge/E--Commerce-FFFFFF?style=for-the-badge&labelColor=0B0F1A"/>
<img src="https://img.shields.io/badge/Software%20Developers-1D4ED8?style=for-the-badge&labelColor=0B0F1A"/>
<img src="https://img.shields.io/badge/Photography-E63946?style=for-the-badge&labelColor=0B0F1A"/>
<img src="https://img.shields.io/badge/Technical%20Services-FFFFFF?style=for-the-badge&labelColor=0B0F1A"/>

</div>

---

<!-- ════════════════════════════════════════════════════════════════════════
     ░▒▓█ TECH STACK  █▓▒░
     ════════════════════════════════════════════════════════════════════════ -->

<h2 align="center">🧰&nbsp;&nbsp;Tech Stack</h2>

<div align="center">

<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=python,bash,linux,docker,kubernetes,nginx,mariadb,redis,git,github,githubactions,grafana,prometheus,vscode&theme=dark&perline=14" alt="Engineering"/>
</a>
<br/><br/>

<img src="https://img.shields.io/badge/Frappe-v15-E63946?style=flat-square&labelColor=0B0F1A"/>
<img src="https://img.shields.io/badge/ERPNext-v15-1D4ED8?style=flat-square&logo=erpnext&logoColor=white&labelColor=0B0F1A"/>
<img src="https://img.shields.io/badge/Helpdesk-v15-FFFFFF?style=flat-square&labelColor=0B0F1A"/>
<img src="https://img.shields.io/badge/Wazuh-SIEM-E63946?style=flat-square&labelColor=0B0F1A"/>
<img src="https://img.shields.io/badge/Proxmox-VE-1D4ED8?style=flat-square&logo=proxmox&logoColor=white&labelColor=0B0F1A"/>
<img src="https://img.shields.io/badge/Nextcloud-Hub-FFFFFF?style=flat-square&logo=nextcloud&logoColor=0B0F1A&labelColor=FFFFFF"/>
<img src="https://img.shields.io/badge/Microsoft%20365-Managed-E63946?style=flat-square&logo=microsoft365&logoColor=white&labelColor=0B0F1A"/>
<img src="https://img.shields.io/badge/Windows-Endpoint-1D4ED8?style=flat-square&logo=windows11&logoColor=white&labelColor=0B0F1A"/>
<img src="https://img.shields.io/badge/macOS-Endpoint-FFFFFF?style=flat-square&logo=apple&logoColor=0B0F1A&labelColor=FFFFFF"/>
<img src="https://img.shields.io/badge/Linux-Endpoint-E63946?style=flat-square&logo=linux&logoColor=white&labelColor=0B0F1A"/>
<br/>
<img src="https://img.shields.io/badge/Ruff-Lint-1D4ED8?style=flat-square&logo=ruff&logoColor=white&labelColor=0B0F1A"/>
<img src="https://img.shields.io/badge/pytest-CI-E63946?style=flat-square&logo=pytest&logoColor=white&labelColor=0B0F1A"/>
<img src="https://img.shields.io/badge/Pre--Commit-Hooks-FFFFFF?style=flat-square&logo=precommit&logoColor=0B0F1A&labelColor=FFFFFF"/>
<img src="https://img.shields.io/badge/Renovate-Updates-1D4ED8?style=flat-square&logo=renovatebot&logoColor=white&labelColor=0B0F1A"/>
<img src="https://img.shields.io/badge/Discord-Bridge-E63946?style=flat-square&logo=discord&logoColor=white&labelColor=0B0F1A"/>

</div>

---

<!-- ════════════════════════════════════════════════════════════════════════
     ░▒▓█ TERMINAL DEMO  █▓▒░
     ════════════════════════════════════════════════════════════════════════ -->

<h2 align="center">🖥️&nbsp;&nbsp;Live Console</h2>

```bash
$ ssh you@your-business.local
[+] Audit-trail enabled   · NIS2 Art. 21 · GDPR Art. 28
[+] Wazuh-Agent connected · 0 critical · 0 high · 0 medium
[+] ERPNext               ok · 14 ms RTT
[+] Helpdesk              ok · SLA p95 = 1h 42m
[+] Backup chain          ok · last verified 04:12 UTC

$ seraph status
─────────────────────────────────────────────
  Tickets  open : 12   · in-sla : 12/12 (100%)
  Hosts    up   : 84/84 · patched: 84/84
  Incidents     : 0    · MTTR p90: 23 min
─────────────────────────────────────────────

$ # IT that takes responsibility.
```

---

<!-- ════════════════════════════════════════════════════════════════════════
     ░▒▓█ GITHUB STATS  █▓▒░
     ════════════════════════════════════════════════════════════════════════ -->

<h2 align="center">📈&nbsp;&nbsp;Org Signals</h2>

<div align="center">

<a href="https://github.com/Seraph-IT">
  <img
    height="170"
    src="https://github-readme-stats.vercel.app/api?username=GaaraSeraph&show_icons=true&hide_border=true&bg_color=0B0F1A&title_color=E63946&icon_color=1D4ED8&text_color=FFFFFF&include_all_commits=true&count_private=true"
    alt="Seraph-IT GitHub stats"
  />
  <img
    height="170"
    src="https://github-readme-stats.vercel.app/api/top-langs/?username=GaaraSeraph&layout=compact&hide_border=true&bg_color=0B0F1A&title_color=E63946&text_color=FFFFFF&langs_count=8"
    alt="Top languages"
  />
</a>
<br/>
<a href="https://github.com/Seraph-IT">
  <img
    src="https://github-readme-streak-stats.herokuapp.com/?user=GaaraSeraph&theme=black-ice&hide_border=true&background=0B0F1A&stroke=1D4ED8&ring=E63946&fire=E63946&currStreakLabel=E63946&sideLabels=FFFFFF&dates=FFFFFF&currStreakNum=FFFFFF&sideNums=FFFFFF"
    alt="Streak"
  />
</a>
<br/><br/>
<a href="https://github.com/Seraph-IT">
  <img
    src="https://github-readme-activity-graph.vercel.app/graph?username=GaaraSeraph&bg_color=0B0F1A&color=FFFFFF&line=E63946&point=1D4ED8&area=true&area_color=1D4ED8&hide_border=true&custom_title=Engineering%20Activity"
    width="98%"
    alt="Activity graph"
  />
</a>

</div>

---

<!-- ════════════════════════════════════════════════════════════════════════
     ░▒▓█ CTA · CONTACT  █▓▒░
     ════════════════════════════════════════════════════════════════════════ -->

<h2 align="center">🤝&nbsp;&nbsp;Get in Touch</h2>

<p align="center">
  <i>Free initial consultation · Response in ≤ 2 h · Teams, phone, or email — your choice.</i>
</p>

<div align="center">

<a href="https://seraph-it.de"><img src="https://img.shields.io/badge/REQUEST%20NOW-E63946?style=for-the-badge&logo=rocket&logoColor=white&labelColor=0B0F1A"/></a>
<a href="https://seraph-it.de"><img src="https://img.shields.io/badge/Free%20Consultation-1D4ED8?style=for-the-badge&logo=calendar&logoColor=white&labelColor=0B0F1A"/></a>
<a href="mailto:engineering@seraph-it.de"><img src="https://img.shields.io/badge/engineering@seraph--it.de-FFFFFF?style=for-the-badge&logo=protonmail&logoColor=0B0F1A&labelColor=FFFFFF"/></a>

<br/><br/>

<a href="https://seraph-it.de"><img src="https://img.shields.io/badge/Website-seraph--it.de-1D4ED8?style=flat-square&logo=firefoxbrowser&logoColor=white&labelColor=0B0F1A"/></a>
<a href="https://www.linkedin.com/company/seraph-it/"><img src="https://img.shields.io/badge/LinkedIn-Follow-1D4ED8?style=flat-square&logo=linkedin&logoColor=white&labelColor=0B0F1A"/></a>
<a href="https://www.instagram.com/seraph_it/"><img src="https://img.shields.io/badge/Instagram-@seraph__it-E63946?style=flat-square&logo=instagram&logoColor=white&labelColor=0B0F1A"/></a>
<a href="https://www.facebook.com/seraphit/"><img src="https://img.shields.io/badge/Facebook-seraphit-1D4ED8?style=flat-square&logo=facebook&logoColor=white&labelColor=0B0F1A"/></a>
<a href="https://www.youtube.com/@seraph-it"><img src="https://img.shields.io/badge/YouTube-Channel-E63946?style=flat-square&logo=youtube&logoColor=white&labelColor=0B0F1A"/></a>
<a href="https://seraph-it.de"><img src="https://img.shields.io/badge/Location-Cologne%20%C2%B7%20DE-FFFFFF?style=flat-square&logo=googlemaps&logoColor=0B0F1A&labelColor=FFFFFF"/></a>

</div>

---

<!-- ════════════════════════════════════════════════════════════════════════
     ░▒▓█ SIGNATURE · ANIMATED SHIELD  █▓▒░
     ════════════════════════════════════════════════════════════════════════ -->

<div align="center">

<svg width="220" height="220" viewBox="0 0 220 220" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Seraph-IT crest">
  <defs>
    <radialGradient id="shieldFill" cx="50%" cy="40%" r="70%">
      <stop offset="0%"  stop-color="#1D4ED8"/>
      <stop offset="60%" stop-color="#0B0F1A"/>
      <stop offset="100%" stop-color="#0B0F1A"/>
    </radialGradient>
    <linearGradient id="ringGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%"   stop-color="#E63946"/>
      <stop offset="50%"  stop-color="#FFFFFF"/>
      <stop offset="100%" stop-color="#1D4ED8"/>
    </linearGradient>
    <filter id="shieldGlow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="3" result="b"/>
      <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>

  <!-- rotating outer rings -->
  <g transform="translate(110 110)">
    <circle r="98" fill="none" stroke="url(#ringGrad)" stroke-width="2" stroke-dasharray="8 6" opacity="0.85">
      <animateTransform attributeName="transform" type="rotate" from="0" to="360" dur="22s" repeatCount="indefinite"/>
    </circle>
    <circle r="86" fill="none" stroke="#FFFFFF" stroke-width="0.6" stroke-dasharray="2 4" opacity="0.45">
      <animateTransform attributeName="transform" type="rotate" from="360" to="0" dur="34s" repeatCount="indefinite"/>
    </circle>
  </g>

  <!-- shield body -->
  <path d="M110 24 L184 56 V120 C184 162 150 188 110 200 C70 188 36 162 36 120 V56 Z"
        fill="url(#shieldFill)" stroke="url(#ringGrad)" stroke-width="2" filter="url(#shieldGlow)"/>

  <!-- seraph wings (stylised) -->
  <g stroke="#FFFFFF" stroke-width="1.4" fill="none" opacity="0.9">
    <path d="M58 92 Q90 78 110 96 Q130 78 162 92" />
    <path d="M64 110 Q92 100 110 116 Q128 100 156 110" />
    <path d="M72 128 Q94 122 110 134 Q126 122 148 128" />
  </g>

  <!-- pulse halo -->
  <circle cx="110" cy="110" r="78" fill="none" stroke="#E63946" stroke-width="1.4" opacity="0.7">
    <animate attributeName="r" values="78;104;78" dur="3.6s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.7;0;0.7" dur="3.6s" repeatCount="indefinite"/>
  </circle>
</svg>

<br/>

<sub>
  <img src="https://komarev.com/ghpvc/?username=Seraph-IT&style=for-the-badge&color=E63946&label=PROFILE+VIEWS&labelColor=0B0F1A"/>
  &nbsp;
  <img src="https://img.shields.io/github/followers/Seraph-IT?style=for-the-badge&color=1D4ED8&logo=github&logoColor=white&label=FOLLOWERS&labelColor=0B0F1A"/>
  &nbsp;
  <img src="https://img.shields.io/badge/STATUS-OPERATIONAL-FFFFFF?style=for-the-badge&logo=statuspage&logoColor=0B0F1A&labelColor=FFFFFF"/>
</sub>

</div>

<!-- ─── Footer Wave · mirrored ──────────────────────────────────────── -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B0F1A,15:E63946,50:FFFFFF,85:1D4ED8,100:0B0F1A&height=160&section=footer&animation=twinkling" width="100%" alt=""/>

<div align="center">

<sub><i>"Seraphim — guardians at the gate."</i></sub><br/>
<sub>© Seraph-IT GmbH · Cologne · made with ❤️ &amp; <code>ruff check --fix</code></sub>

</div>

<!--
============================================================================
  BRAND SYSTEM (keep at the bottom — used by tooling, not rendered)
  ----------------------------------------------------------------------------
  Primary    #E63946   Seraph Red       (alerts, accents, CTA)
  Secondary  #1D4ED8   Trust Blue       (links, infra, calm states)
  Neutral    #FFFFFF   Signal White     (contrast, dividers)
  Surface    #0B0F1A   Obsidian         (backgrounds, terminals)
  Font       JetBrains Mono / Inter
  Voice      Direct · Accountable · No jargon · Responsible
============================================================================
-->
