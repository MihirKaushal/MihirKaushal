<p align="center">
  <img
    src="./assets/profile-banner.svg"
    alt="Mihir Kaushal — software development, full-stack engineering, and data science"
    width="100%"
  >
</p>

## About

I'm a **Computer Science & Data Science student at the University of Wisconsin–Madison**. I build full-stack applications across web, mobile, and data-focused team projects.

<p align="center">
  <a href="mailto:mihir.kaush@gmail.com"><img alt="Email Mihir" src="https://img.shields.io/badge/Email-Say%20hello-319A9A?style=for-the-badge&logo=gmail&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/mihir-kaushal"><img alt="Connect with Mihir on LinkedIn" src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="https://playchass.vercel.app"><img alt="Play Chass" src="https://img.shields.io/badge/Live-Play%20Chass!-061747?style=for-the-badge&logo=vercel&logoColor=white"></a>
</p>

## Current projects

<details open>
<summary><h3>Chass! · Full-stack game platform</h3></summary>

[Live game](https://playchass.vercel.app) · [Source code](https://github.com/MihirKaushal/Chass)

Engineered a browser chess platform for classic play and deeply configurable variants. The FastAPI backend stays authoritative over real-time games, with versioned state, reconnect recovery, private setup flows, and interchangeable Firestore/SQLite persistence.

- Built a **3-engine AI pipeline** using **Stockfish 18**, **Fairy-Stockfish**, and a custom alpha-beta **Chass Engine** to power live Match Analysis and **12 bot profiles spanning an estimated 500–2500 Elo**; enforced engine-rule parity and validated the system with a **408-test automated suite**
- **24 REST/WebSocket routes**, boards from **4×4 to 16×16**, **7 custom pieces**, **7 abilities**, and **9 victory modes**
- **Stack:** Python, FastAPI, React, WebSockets, Firestore, SQLAlchemy, SQLite, Pytest

</details>

<details open>
<summary><h3>Studi · Team mobile app</h3></summary>

 [App Store](https://apps.apple.com/us/app/studi-study-together/id6804290285) · [Product site](https://joinstudi.com) · [Source code](https://github.com/Kgan3039/studi)

Contributing to a UW–Madison study-partner app for finding classmates, coordinating availability, and meeting at campus study spaces. My work includes session editing and attendee notifications, search improvements, authentication and account-deletion reliability, profile draft protection, and the root Expo setup.

- **351 passing tests across 17 suites**, including blocked-session safety, push-token ownership, and notification validation
- **23 screens** organized through **3 Expo Router layouts** and **5 main tabs**, plus **12 Firebase Cloud Function exports**
- **Stack:** TypeScript, React Native, Expo Router, Firebase, Firestore

</details>

<details open>
<summary><h3>AI Market Sentiment Dashboard · Backend engineer, 6-person team</h3></summary>

[Source code](https://github.com/Kgan3039/ai-market-sentiment-dashboard)

Built **3 fixture-backed Phase 0 FastAPI endpoints** across a **5-ticker** demo dataset, connected the React dashboard to the API, and hardened the integration around validation, errors, freshness metadata, and production routing.

- **22 targeted tests passing**: 14 backend + 8 frontend
- Separates data ingestion, NLP, prediction, API, and dashboard responsibilities behind explicit contracts
- **Stack:** Python, FastAPI, REST APIs, React, SQLite, Vitest

</details>

## Skills

| Area | Technologies |
| --- | --- |
| Languages | Python, Java, JavaScript/TypeScript, R, SQL, HTML/CSS |
| Frontend and Mobile | React, React Native, Expo Router, Vite |
| Backend and Data | FastAPI, REST APIs, WebSockets, Firebase/Firestore, SQLite, SQLAlchemy |
| Quality and Delivery | Pytest, Mocha, Vitest, Ruff, ESLint, Git/GitHub, Vercel, Render |
