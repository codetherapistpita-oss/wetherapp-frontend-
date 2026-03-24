# SkyPulse Weather

A **modern, responsive weather dashboard** (HTML, CSS, vanilla JavaScript) with city search, hourly / weekly toggles, °C / °F units, and a highlights grid (UV, wind, sunrise/sunset, humidity, visibility, wind direction).  
This repo is a **redesign and hardening** of the open-source **WeatherVista** project, adapted and maintained by **Code Therapist**.

### Live demo (GitHub Pages)

After you enable **Pages** for this repository, your site will be available at:

**[https://codetherapistpita-oss.github.io/wetherapp-frontend-/](https://codetherapistpita-oss.github.io/wetherapp-frontend/)**

> **Important:** Weather data requires a **free [Visual Crossing Weather API](https://www.visualcrossing.com/weather-api/)** key. Add it to `weather-config.js` (see [Setup](#setup)).

---

## Screenshots

<p align="center">
  <img src="readme-assets/screenshot-01-dashboard.png" alt="SkyPulse Weather — dashboard view" width="720" />
</p>
<p align="center"><em>Main layout — sidebar, forecast strip, and highlights (API key banner shows until configured).</em></p>

<p align="center">
  <img src="readme-assets/screenshot-02-scroll.png" alt="SkyPulse Weather — full page" width="720" />
</p>
<p align="center"><em>Full-page view including highlight cards.</em></p>

---

## Features

- Responsive **sidebar + main** layout (mobile-first, large screens side-by-side)
- **Visual Crossing** timeline API (metric units in request; °F converted in UI when selected)
- **Today / Week** forecast modes and **°C / °F** toggle
- **City autocomplete** (bundled city list)
- **Phosphor** icons (no Font Awesome kit dependency)
- **Wind direction** card shows degrees + compass label (replaces misleading “air quality” mapping on wind data)
- **API key** kept out of source history going forward — configure locally via `weather-config.js`
- Clear **status banner** when the API key is missing or a request fails

---

## Setup

1. **Clone**
   ```bash
   git clone https://github.com/codetherapistpita-oss/wetherapp-frontend-.git
   cd wetherapp-frontend-
   ```
   *(Folder name matches the repo; if Git uses a different directory, `cd` into it.)*

2. **API key** — create a free account at [Visual Crossing](https://www.visualcrossing.com/weather-api/), copy your key, and paste it into **`weather-config.js`**:
   ```javascript
   window.WEATHER_VC_KEY = "YOUR_KEY_HERE";
   ```
3. **Run locally** — open `index.html` via a local server (recommended so `fetch` behaves predictably):
   ```bash
   npx serve .
   ```
4. **GitHub Pages** — Repository → **Settings** → **Pages** → deploy from branch **`main`** (root). Then open the **live demo** URL above.

---

## Tech stack

- HTML5 · CSS3 (custom properties, flexbox, grid) · JavaScript (ES5-compatible style)
- [Phosphor Icons](https://phosphoricons.com/) · [Outfit](https://fonts.google.com/specimen/Outfit) (Google Fonts)
- [Visual Crossing Weather API](https://www.visualcrossing.com/weather-api/)

---

## Project structure

```
├── index.html
├── style.css
├── script.js
├── weather-config.js   ← add your API key here
├── readme-assets/      ← README screenshots
├── images/             ← optional assets
├── LICENSE.md
└── README.md
```

---

## Credits & license

- **SkyPulse Weather** — UI/UX refresh, API key handling, wind-direction card, responsive layout, documentation: **Code Therapist** (see below).
- **Original app — WeatherVista** by **Mohammad Wasim Tikki**: [WeatherVista-Interactive-Weather-App](https://github.com/wasimtikki120/WeatherVista-Interactive-Weather-App) (MIT). This derivative retains **MIT** terms — see [`LICENSE.md`](LICENSE.md).

---

## Built by — Code Therapist

| | |
|--|--|
| **Role** | Creative developer · full-stack & UI-focused builds |
| **GitHub** | [@codetherapistpita-oss](https://github.com/codetherapistpita-oss) |
| **Portfolio** | [codetherapistpita-oss.github.io/codetherapist-portfolio](https://codetherapistpita-oss.github.io/codetherapist-portfolio/) |
| **LinkedIn** | [linkedin.com/in/code-therapist-1142243b5](https://www.linkedin.com/in/code-therapist-1142243b5) |

The **in-app footer** credits **Code Therapist** by name only (no outbound links), so forks stay clean for other users.

---

## Contributing

Issues and PRs are welcome in **[this repository](https://github.com/codetherapistpita-oss/wetherapp-frontend-)**. Please respect the original MIT license and keep API keys out of commits (use `weather-config.js` locally or private env patterns).
