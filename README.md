# Andre Oleari

**Software Engineer — Mobile & Full-Stack** · Cork, Ireland 🇮🇪

Building and shipping cross-platform apps end to end. React Native, TypeScript,
Node.js and Firebase, with a soft spot for offline-first architecture and
release automation.

Open to engineering roles across the EU.

<a href="https://portfolio-xi-six-fj8lxwq2ku.vercel.app"><img src="https://img.shields.io/badge/Portfolio-0F5FC4?style=for-the-badge&logo=vercel&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/andre-oleari-83406520b/"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:andre.oleari1@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://github.com/AndreOleari015"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>

## 🚀 Shipped

Three apps designed, built and published on my own developer account.

| App | What it does | Store | Code |
|---|---|---|---|
| **Bus Times: Dublin & Ireland** | Live departures for bus, tram and rail, built on NTA/TFI open data | [App Store](https://apps.apple.com/us/app/bus-times-dublin-and-ireland/id6783506737) | [tfi-departures-worker](https://github.com/AndreOleari015/tfi-departures-worker) |
| **Lista Virtual** | Offline-first event check-in — 222 events and counting | [App Store](https://apps.apple.com/us/app/lista-virtual-guest-list/id6738919953) · [Play](https://play.google.com/store/apps/details?id=com.ROC) | — |
| **Scoreboard / Placar** | Tournament brackets, live scoring, works offline | [App Store](https://apps.apple.com/us/app/scoreboard-tournament-track/id6756669003) · [Play](https://play.google.com/store/apps/details?id=com.scoreboardapp.app) | [tournament-engine](https://github.com/AndreOleari015/tournament-engine) |

## 🛠 Built

**[job-tailor](https://github.com/AndreOleari015/job-tailor)** — LLM-assisted job application tooling.
The model may only **select** pre-written facts, never generate them: invented
references are dropped in code, thresholds are computed outside the LLM, and the
renderer refuses to produce a PDF from any unverified output.

**[tournament-engine](https://github.com/AndreOleari015/tournament-engine)** — the competition
engine behind Scoreboard, pulled out into a standalone TypeScript library. Seeded
draws, round-robin fixtures, knockout brackets and tiebreak ordering defined per
sport as data. No dependencies, 100 tests.

**[tfi-departures-worker](https://github.com/AndreOleari015/tfi-departures-worker)** — the
Cloudflare Worker behind Bus Times. Turns the 250 MB national GTFS feed into
per-stop JSON in R2, polls GTFS-Realtime on a cron, and serves it with LRU
caching, kill switches and a per-IP rate limit.

More, including the write-ups: **[portfolio-xi-six-fj8lxwq2ku.vercel.app](https://portfolio-xi-six-fj8lxwq2ku.vercel.app)**

## ⚡ Stack

- **Mobile** — React Native, Expo, TypeScript, SwiftUI, WidgetKit
- **Backend & data** — Node.js, Fastify, PostgreSQL, SQLite, Cloudflare Workers, Firestore
- **AI & computer vision** — Gemini, Claude, Python, FastAPI
- **Release & ops** — EAS Build, Fastlane, GitHub Actions, RevenueCat

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="40" height="40"/>&nbsp;&nbsp;<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" width="40" height="40"/>&nbsp;&nbsp;<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/expo/expo-original.svg" width="40" height="40"/>&nbsp;&nbsp;<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/swift/swift-original.svg" width="40" height="40"/>&nbsp;&nbsp;<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-plain.svg" width="40" height="40"/>&nbsp;&nbsp;<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" width="40" height="40"/>&nbsp;&nbsp;<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cloudflare/cloudflare-original.svg" width="40" height="40"/>&nbsp;&nbsp;<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/firebase/firebase-plain.svg" width="40" height="40"/>&nbsp;&nbsp;<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="40" height="40"/>&nbsp;&nbsp;<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-plain.svg" width="40" height="40"/>&nbsp;&nbsp;<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/figma/figma-original.svg" width="40" height="40"/>
