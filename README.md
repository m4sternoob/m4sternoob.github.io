# M4sterNoob — Portfolio Site

My portfolio site. Built by hand, no template.

Live: https://m4sternoob.github.io/portfolio/

## What is this

The site behind my job search. A tabbed hub at the root with four tabs:

- **Portfolio** — hero, selected work (click any card for the full breakdown), skills, about, contact
- **CV** — my one-page resume, prints straight to PDF (File > Print > Save as PDF)
- **Game** — playable Snake styled like a Nokia 1100: arrows, WASD, or the on-screen keypad
- **Pixel Market** — claim pixels on a shared wall. Saves locally, no payments, no accounts

The portfolio page has a "Gameplay clip coming soon" slot. No stock footage, no fakes — a real clip goes there when I record one.

## Tech

HTML, CSS, vanilla JavaScript. No framework, no build step, no third-party dependencies besides a Google Font.

- Binary-rain canvas background on the portfolio page
- Popup project cards with their own drifting particle background
- Snake and the pixel wall are plain JS/Canvas on the root page
- Deployed on GitHub Pages straight from `main`

## Run it locally

It is a static site. Clone it and open `portfolio/index.html` for the portfolio,
or the root `index.html` for the tabbed hub. No server, no build.

## The work shown

- **StumbleGuysClone** — multiplayer party game in Unreal Engine 5.6. Gameplay is
  100% C++, Blueprints are not allowed to touch it (in progress)
- **5IN1** — six mini-games in one app: macOS (Swift/SwiftUI) + Android
  (Kotlin/Compose), v1.4.0 shipped with two APK editions
- **Roadmap Tracker** — the kanban board I actually use for my own projects.
  React 19 + TypeScript, live on Vercel
- **Stumble Lite** — 3D physics party game: 4 players, 60-second rounds,
  hand-rolled collision in Swift/SceneKit on iOS (playable build)
- **Phone Mirror Pipeline** — Python script that auto-reconnects wireless
  Android debugging (adb + scrcpy)
- **Planned** — PathRush, Clean House, 1v1MEBIYAAACH. Concepts on the site,
  no code yet; listed as planned, not shipped

Every claim on the site maps to a repo, a release, or a live build linked
from the project cards.

## Contact

masternoob102030@gmail.com
