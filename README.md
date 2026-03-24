<div align="center">

# 🌤️ SkyPulse Weather

[![Live demo](https://img.shields.io/badge/🌐_Live-GitHub_Pages-6c63ff?style=for-the-badge&logo=github)](https://codetherapistpita-oss.github.io/wetherapp-frontend-/)
[![License](https://img.shields.io/badge/License-MIT-22c55e?style=for-the-badge)](LICENSE.md)
[![API](https://img.shields.io/badge/API-Visual_Crossing-f59e0b?style=for-the-badge)](https://www.visualcrossing.com/weather-api/)

<img src="https://readme-typing-svg.demolab.com?font=Outfit&weight=600&size=22&duration=3000&pause=1200&color=6C63FF&center=true&vCenter=true&width=520&lines=Responsive+weather+dashboard;HTML+%E2%80%A2+CSS+%E2%80%A2+Vanilla+JavaScript;Search+%E2%80%A2+hourly%2Fweek+%E2%80%A2+%C2%B0C+%2F+%C2%B0F" alt="Typing intro" />

<br/>

<img src="https://skillicons.dev/icons?i=html,css,js,git,github,vscode&perline=6" alt="Tech stack icons" />

<sub>Icons via <a href="https://skillicons.dev">skillicons.dev</a> · Typing line via <a href="https://github.com/DenverCoder1/readme-typing-svg">readme-typing-svg</a></sub>

<br/>

### 🔗 Open the live site (GitHub Pages)

**👉 [https://codetherapistpita-oss.github.io/wetherapp-frontend-/](https://codetherapistpita-oss.github.io/wetherapp-frontend-/)**

*Click the URL above to open SkyPulse Weather in your browser. Add your API key in `weather-config.js` for live weather data.*

</div>

---

## 👀 Preview

*Click a screenshot to open the **[live app](https://codetherapistpita-oss.github.io/wetherapp-frontend-/)**.*

| | |
|:---:|:---:|
| <a href="https://codetherapistpita-oss.github.io/wetherapp-frontend-/"><img src="readme-assets/screenshot-01-dashboard.png" width="360" alt="Dashboard — click to open live site" /></a> | <a href="https://codetherapistpita-oss.github.io/wetherapp-frontend-/"><img src="readme-assets/screenshot-02-scroll.png" width="360" alt="Full page — click to open live site" /></a> |
| **Dashboard** | **Highlights & cards** |

---

## 📊 At a glance

```mermaid
pie title Code focus (approx.)
    "JavaScript" : 72
    "CSS" : 18
    "HTML" : 10
```

```mermaid
pie title App features (concept split)
    "Forecast views" : 35
    "Highlights cards" : 25
    "Search + list" : 22
    "Units + location" : 18
```

```mermaid
flowchart LR
  subgraph Browser
    A[index.html]
    B[style.css]
    C[script.js]
  end
  subgraph APIs
    D[Visual Crossing]
    E[Geo lookup]
  end
  A --> C
  B --> A
  C --> D
  C --> E
```

---

## ✨ Features (quick)

| | |
|--|--|
| 📱 | **Responsive** sidebar + main panel |
| 🔎 | **City search** + bundled autocomplete list |
| ⏰ | **Today** (hourly) / **Week** toggle |
| 🌡️ | **°C** / **°F** switch |
| 🧭 | **Wind direction** (° + compass) — not fake “AQI” |
| 🔑 | **API key** in `weather-config.js` only (no keys in `script.js`) |
| ⚠️ | **Banner** if key missing or request fails |

---

## 🛠️ Stack

| ![html](https://img.shields.io/badge/HTML5-e34f26?style=flat&logo=html5&logoColor=white) | ![css](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white) | ![js](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) | ![api](https://img.shields.io/badge/API-Visual_Crossing-f59e0b?style=flat) |
|:---:|:---:|:---:|:---:|
| Structure | Variables · flex · grid | `fetch` · DOM | Timeline weather |

<p align="center">
<img src="https://img.shields.io/badge/Icons-Phosphor-6c63ff?style=for-the-badge" alt="Phosphor" />
<img src="https://img.shields.io/badge/Font-Outfit-0f172a?style=for-the-badge" alt="Outfit" />
</p>

---

## 🚀 Setup

<details>
<summary><b>1 · Clone</b></summary>

```bash
git clone https://github.com/codetherapistpita-oss/wetherapp-frontend-.git
cd wetherapp-frontend-
```

</details>

<details>
<summary><b>2 · API key → <code>weather-config.js</code></b></summary>

```javascript
window.WEATHER_VC_KEY = "YOUR_KEY_HERE";
```

Free key: [visualcrossing.com/weather-api](https://www.visualcrossing.com/weather-api/)

</details>

<details>
<summary><b>3 · Run locally</b></summary>

```bash
npx serve .
```

</details>

<details>
<summary><b>4 · GitHub Pages</b></summary>

**Settings → Pages →** branch `main` / root → then open the **Live demo** badge at the top.

</details>

---

## 📁 Files

```mermaid
flowchart LR
  I[index.html] --> J[script.js]
  I --> S[style.css]
  J --> W[weather-config.js]
  R[readme-assets] --- I
```

---

## 🙏 Credits

| | |
|--|--|
| **SkyPulse** | UI refresh, API safety, docs — **Code Therapist** |
| **WeatherVista** | Original app — [wasimtikki120/WeatherVista…](https://github.com/wasimtikki120/WeatherVista-Interactive-Weather-App) · MIT |

---

## 👤 Code Therapist

<p align="center">

[![GitHub](https://img.shields.io/badge/GitHub-codetherapistpita--oss-181717?style=flat&logo=github)](https://github.com/codetherapistpita-oss)
[![Portfolio](https://img.shields.io/badge/Portfolio-live-6c63ff?style=flat&logo=googlechrome)](https://codetherapistpita-oss.github.io/codetherapist-portfolio/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-connect-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/code-therapist-1142243b5)

</p>

<sub>In-app footer: name only · no links (fork-friendly).</sub>

---

<div align="center">

**[🌐 Open live site](https://codetherapistpita-oss.github.io/wetherapp-frontend-/)** · **⭐ Star the repo** if this helped · PRs welcome · keep API keys out of git

</div>
