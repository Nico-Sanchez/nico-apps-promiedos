<div align="center">

# ⚽ Promiedos

**A mobile UI prototype for following Argentine football: matches, live scores and league standings.**

[![Live demo](https://img.shields.io/badge/demo-live-2ea44f?style=flat-square&logo=githubpages&logoColor=white)](https://nico-sanchez.github.io/nico-apps-promiedos/)
[![pages-build-deployment](https://github.com/Nico-Sanchez/nico-apps-promiedos/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/Nico-Sanchez/nico-apps-promiedos/actions/workflows/pages/pages-build-deployment)
![Status](https://img.shields.io/badge/status-prototype-orange?style=flat-square)
![PWA](https://img.shields.io/badge/PWA-5A0FC8?style=flat-square&logo=pwa&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-vanilla-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

<img src="docs/screenshot.png" alt="Matches tab" width="280">&nbsp;&nbsp;
<img src="docs/standings.png" alt="Standings tab" width="280">

</div>

> [!NOTE]
> This is a design prototype. Matches and standings are **hard-coded sample data**, not live results.
> It is a personal project and is not affiliated with promiedos.com.ar.

## What's in it

- **Partidos** — match cards grouped by competition (Liga Profesional, Copa Libertadores), with a highlighted *EN VIVO* card, upcoming kick-off times and final scores.
- **Posiciones** — league table with played, won, drawn, lost, goal difference and points.
- **Pull to refresh** — swiping down from the top reloads the page.
- **PWA shell** — manifest and service worker so it can be added to the home screen.

## Roadmap

- [ ] Fetch real fixtures, results and standings from a football data API
- [ ] Relegation averages (*promedios*) table
- [ ] More competitions

## Run locally

```bash
python3 -m http.server 8000
```

Then browse to <http://localhost:8000>.

## More apps

Part of a small collection of web apps — see the [apps landing page](https://nico-sanchez.github.io/apps-landing/).
