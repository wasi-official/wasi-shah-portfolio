# Syed Wasi Shah — Portfolio

A responsive single-page portfolio for **Syed Wasi Shah**, Software Engineering Student, focused on machine learning and Python.

The site is a self-contained static page: `index.html` includes the copy, styles, interactions, project artwork, and the embedded monochrome hero photograph. There is no build step and no server-side runtime.

## Live site

<https://wasi-shah-portfolio-gold.vercel.app>

## Stack

- HTML, CSS, and vanilla JavaScript
- Inline SVG project artwork
- Mona Sans webfonts from jsDelivr
- Static hosting on Vercel

## Local preview

From the project root:

```bash
python -m http.server 8899
```

Then open <http://127.0.0.1:8899/index.html>.

Any static file server works; no dependencies need to be installed.

## Featured projects

- [Habit Breaker](https://github.com/wasi-official/andiod-app-habit-breaker) — Android / AI
- [Fitness App](https://github.com/wasi-official/fitness-app) — Android / Kotlin
- [Weather App](https://github.com/wasi-official/wheather-python-app) — Python
- [Python Projects](https://github.com/wasi-official/python-projects-) — Python
- [Personal Web](https://github.com/wasi-official/my-personal-web) — Flask / Web
- [AI Assistant](https://github.com/wasi-official/AI-assistant-cecos) — AI experiment

## Deployment

The site deploys to Vercel as a static project with no framework preset, no build command, and the repository root as the output directory.

No environment variables or secrets are required.

## Project layout

```text
.
├── index.html       # Standalone site (all markup, styles, scripts, and artwork)
├── assets/
│   └── hero.jpg     # Source hero photograph (also embedded in index.html)
├── .gitignore
├── .vercelignore
└── README.md
```

The embedded hero image is a licensed Pexels photograph (Pexels #6963944), cropped and graded for this site.
