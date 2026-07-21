# Andre Oleari

**Software Engineer — Mobile & Full-Stack** · Cork, Ireland

I build and ship cross-platform applications end to end. Four years of
production experience across React Native, TypeScript, Node.js and Firebase,
with a focus on offline-first architecture, third-party integrations and
release automation.

Currently open to engineering roles across the EU.
Eligible for the EU Blue Card as an IT specialist under §18g AufenthG.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/andre-oleari-83406520b/)
[![Email](https://img.shields.io/badge/Email-333333?style=flat&logo=gmail&logoColor=white)](mailto:andre.oleari1@gmail.com)

---

## Shipped

**[Bus Times: Dublin & Ireland](#)** — live public transport for Ireland
Real-time and scheduled departures for bus, tram and rail, built on NTA/TFI
open data. Stop search, saved stops, live vehicle maps, reminders and service
alerts. Designed, built and published solo.
`React Native` `Expo` `TypeScript` `Open Data APIs` `Maps`

**[Lista Virtual](#)** — event guest list, RSVP and live check-in
Offline-first check-in platform used across 222 events. WhatsApp and email
invitations, spreadsheet import, PDF/Excel reporting, multi-user receptionist
access, multilingual.
`React Native` `Firebase` `Firestore` `Offline-first` `i18n`

**[Scoreboard / Placar](#)** — tournament and scorekeeping manager
Live scoring, timers and bracket generation for group stage, round-robin and
knockout formats, with local persistence for venues without connectivity.
`React Native` `State machines` `Local storage`

---

## Selected work

**[job-tailor](https://github.com/AndreOleari015/job-tailor)** — LLM-assisted
job application tooling
Parses a job description into structured data, then selects and orders CV
bullets and drafts a cover letter against a structured profile.

The design constraint is the interesting part: the model may only **select**
pre-written facts, never generate them. Bullet IDs returned by the model are
reconciled against the real profile and invented ones are dropped; threshold
comparisons are computed in code, not by the LLM; and the renderer refuses to
produce a PDF from any application carrying an unverified-claim flag. A
provider abstraction runs the same prompts across Anthropic and Gemini for
output comparison.

`TypeScript` `Zod` `Handlebars` `Puppeteer` `Anthropic SDK` `Gemini SDK`

---

## Stack

**Languages** TypeScript · JavaScript · PHP · SQL
**Mobile** React Native · Expo · Expo Router · EAS Build · Fastlane
**Web & backend** React · Node.js · Firebase Cloud Functions · REST APIs
**Data** Firestore · MySQL
**Infrastructure** GitHub Actions · Cloudflare Workers · Git

---

## Experience highlights

- Contributed to 30+ cross-platform applications from concept to App Store and
  Google Play publication
- Authored internal tooling — a shared Expo utility library and Fastlane
  release pipelines — cutting the store release process from a full working
  day to a few hours
- Built CI/CD with GitHub Actions and Expo EAS, RevenueCat subscription flows,
  and Cloudflare Workers edge services
- Delivered features spanning AI image recognition, price comparison, public
  open data and event management

---

<img src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=AndreOleari015&layout=compact&langs_count=6&hide_border=true&theme=github_dark" height="150"/>
