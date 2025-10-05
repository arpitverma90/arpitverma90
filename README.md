# Hi there 👋 I'm Abhay

<!-- Hero: Animated colorful SVG -->

<svg width="100%" height="220" viewBox="0 0 1200 220" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="g1" x1="0" x2="1">
      <stop offset="0%" stop-color="#ff6b6b">
        <animate attributeName="offset" values="0%;15%;0%" dur="6s" repeatCount="indefinite" />
      </stop>
      <stop offset="50%" stop-color="#fbc531">
        <animate attributeName="offset" values="50%;65%;50%" dur="6s" repeatCount="indefinite" />
      </stop>
      <stop offset="100%" stop-color="#4cd137">
        <animate attributeName="offset" values="100%;85%;100%" dur="6s" repeatCount="indefinite" />
      </stop>
    </linearGradient>

```
<filter id="f1" x="-20%" y="-20%" width="140%" height="140%">
  <feGaussianBlur stdDeviation="20" result="blur" />
  <feBlend in="SourceGraphic" in2="blur" mode="normal"/>
</filter>
```

  </defs>

  <!-- Background blobs -->

  <g filter="url(#f1)">
    <circle cx="150" cy="80" r="90" fill="url(#g1)">
      <animate attributeName="cx" dur="8s" values="120;180;120" repeatCount="indefinite"/>
      <animate attributeName="cy" dur="10s" values="70;110;70" repeatCount="indefinite"/>
    </circle>

```
<circle cx="1040" cy="120" r="120" fill="#7f8fa6" opacity="0.18">
  <animate attributeName="cx" dur="12s" values="980;1100;980" repeatCount="indefinite"/>
</circle>

<ellipse cx="600" cy="30" rx="240" ry="40" fill="#6a89cc" opacity="0.12">
  <animate attributeName="cx" dur="9s" values="580;640;580" repeatCount="indefinite"/>
</ellipse>
```

  </g>

  <!-- Text -->

  <g>
    <text x="40" y="80" font-family="Segoe UI, Roboto, Helvetica, Arial, sans-serif" font-size="38" font-weight="700" fill="#0f172a">Hey, I'm <tspan fill="#ff6b6b">Abhay</tspan></text>
    <text x="40" y="120" font-family="Segoe UI, Roboto, Helvetica, Arial, sans-serif" font-size="18" fill="#0f172a" opacity="0.85">Data analyst • Power BI enthusiast • Problem solver</text>
  </g>

  <!-- Floating icons (simple geometric) -->

  <g opacity="0.95">
    <rect x="980" y="20" width="30" height="30" rx="6" fill="#ff4757">
      <animateTransform attributeName="transform" attributeType="XML" type="translate" dur="5s" values="0 0; -10 8; 0 0" repeatCount="indefinite"/>
    </rect>

```
<circle cx="930" cy="60" r="14" fill="#1e90ff">
  <animate attributeName="cy" dur="4s" values="60;40;60" repeatCount="indefinite"/>
</circle>

<polygon points="880,30 900,60 860,60" fill="#2ed573" opacity="0.95">
  <animateTransform attributeName="transform" attributeType="XML" type="rotate" dur="6s" values="0 880 45; 15 880 45; 0 880 45" repeatCount="indefinite"/>
</polygon>
```

  </g>
</svg>

---

## ✨ Quick Highlights

* 🎯 Passionate about turning messy data into clear insights.
* 📊 Power BI, Excel, SQL, Python (pandas) — comfortable across the stack.
* 🚀 Building visuals, dashboards, and automation to speed decisions.

---

## 💼 Skills & Tools

<details>
<summary>Click to expand — colorful SVG skill bars</summary>

<!-- Animated skill bars built with inline SVG (works in GitHub README) -->

<svg width="100%" height="220" viewBox="0 0 800 220" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="xMinYMin">
  <style>
    .label { font: 14px/1.2 "Segoe UI", Roboto, Arial; fill: #0f172a }
    .percent { font: 12px/1.2 "Segoe UI", Roboto, Arial; fill: #0f172a }
  </style>

  <!-- Progress background -->

  <rect x="20" y="20" width="760" height="28" rx="14" fill="#e6e9ef" />
  <rect x="20" y="64" width="760" height="28" rx="14" fill="#e6e9ef" />
  <rect x="20" y="108" width="760" height="28" rx="14" fill="#e6e9ef" />

  <!-- Animated fills -->

  <linearGradient id="p1" x1="0" x2="1">
    <stop offset="0%" stop-color="#ff6b6b" />
    <stop offset="100%" stop-color="#fbc531" />
  </linearGradient>
  <rect x="20" y="20" width="0" height="28" rx="14" fill="url(#p1)">
    <animate attributeName="width" from="0" to="520" dur="1.6s" begin="0.2s" fill="freeze" />
  </rect>

  <linearGradient id="p2" x1="0" x2="1">
    <stop offset="0%" stop-color="#7bed9f" />
    <stop offset="100%" stop-color="#1e90ff" />
  </linearGradient>
  <rect x="20" y="64" width="0" height="28" rx="14" fill="url(#p2)">
    <animate attributeName="width" from="0" to="640" dur="1.8s" begin="0.5s" fill="freeze" />
  </rect>

  <linearGradient id="p3" x1="0" x2="1">
    <stop offset="0%" stop-color="#9b59b6" />
    <stop offset="100%" stop-color="#e84393" />
  </linearGradient>
  <rect x="20" y="108" width="0" height="28" rx="14" fill="url(#p3)">
    <animate attributeName="width" from="0" to="600" dur="1.7s" begin="0.8s" fill="freeze" />
  </rect>

  <!-- Labels -->

<text x="20" y="18" class="label">Power BI</text> <text x="740" y="38" class="percent">65%</text>

<text x="20" y="62" class="label">SQL / Data Modeling</text> <text x="740" y="82" class="percent">80%</text>

<text x="20" y="106" class="label">Python (pandas)</text> <text x="740" y="126" class="percent">75%</text> </svg>

</details>

---

## 📌 GitHub Stats

<!-- Example: GitHub readme stats cards. Replace `your-username` with your GitHub username. -->

[![Abhay's GitHub stats](https://github-readme-stats.vercel.app/api?username=your-username\&show_icons=true\&theme=transparent\&count_private=true)](https://github.com/your-username)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=your-username\&layout=compact\&theme=transparent)](https://github.com/your-username)

---

## 📫 Connect with me

* Twitter: [@yourhandle](https://twitter.com/yourhandle)
* LinkedIn: [your name](https://www.linkedin.com/in/your-linkedin)
* Email: [your.email@example.com](mailto:your.email@example.com)

---

## ✅ How to use

1. Click **Edit** on your GitHub profile repository's `README.md` (the one named same as your username).
2. Replace `your-username`, `yourhandle`, `your-linkedin`, and `your.email@example.com` with your values.
3. Commit — the animated header and SVGs will render directly on your profile README.

---

> Want it more customized? I can:

* change the color palette to match your brand
* add an animated job title carousel
* include dynamic contribution art or a custom SVG avatar

---

*Made with ❤️ — copy this into your `README.md` and tweak the numbers & links.*
