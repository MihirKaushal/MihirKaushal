<p align="center">
  <img
    src="./assets/profile-banner.svg"
    alt="Mihir Kaushal — UW–Madison Computer Science and Data Science student focused on software development, AI, and full-stack engineering"
    width="100%"
  >
</p>

## About

I'm a **Computer Science & Data Science student at the University of Wisconsin–Madison**. I build full-stack applications across web, mobile, and data-focused team projects.

<p align="center">
  <a href="mailto:mihir.kaushal.13@gmail.com"><img alt="Email Mihir" src="https://img.shields.io/badge/Email-Say%20hello-319A9A?style=for-the-badge&logo=gmail&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/mihir-kaushal"><img alt="Connect with Mihir on LinkedIn" src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="https://playchass.vercel.app"><img alt="Play Chass" src="https://img.shields.io/badge/Live-Play%20Chass!-061747?style=for-the-badge&logo=vercel&logoColor=white"></a>
</p>

## Current projects

<details open>
<summary><h3>Chass! · Full-Stack AI Chess Platform</h3></summary>

[Live game](https://playchass.vercel.app) · [Source code](https://github.com/MihirKaushal/Chass)

Built a full-stack chess platform combining customizable gameplay, real-time multiplayer, and computer-vision board scanning.

The scanner uses an SSDLite detector and fine-tuned ResNet18 classifier, deployed through ONNX Runtime on the server or in-browser. Evaluated on **338 images containing 6,283 annotated pieces**, it correctly localized and classified **89.6% of real pieces; type-and-color accuracy among located pieces reached 97.95%**. Includes dataset curation, capture-grouped splits, class-specific error analysis, versioned benchmarks, and user correction before game import.

- Integrated **Stockfish 18, Fairy-Stockfish, and a custom alpha-beta engine** for live analysis and **12 bot profiles**. Supports **4×4–16×16 boards, 7 custom pieces and 7 special abilities**, and WebSocket multiplayer backed by authoritative validation and Firestore/SQLite persistence.

- **Stack:** Python, PyTorch, ONNX Runtime, FastAPI, React, WebSockets, Firestore, SQLAlchemy, SQLite, Pytest, Playwright.

</details>

<details open>
<summary><h3>Studi · Team mobile app</h3></summary>

 [App Store](https://apps.apple.com/us/app/studi-study-together/id6804290285) · [Product site](https://joinstudi.com) · [Source code](https://github.com/Kgan3039/studi)

Contributing to a UW–Madison study-partner app for finding classmates, coordinating availability, and meeting at campus study spaces. My work includes session editing and attendee notifications, search improvements, authentication and account-deletion reliability, profile draft protection, and the root Expo setup.

- Launched a UW–Madison study-partner app on the **Apple App Store**, generating **50+ downloads** and **350+ product-page views** in the first week while earning a **5.0/5.0 average across 13+ ratings**
- Developed **26 Expo Router screens and layouts** across **5 tabs**, integrating **Firebase Auth/Firestore**, study sessions, chat, push notifications, moderation, and campus locations
- **Stack:** TypeScript, React Native, Expo Router, Firebase, Firestore

</details>

<details open>
<summary><h3>AI Market Sentiment Dashboard · Backend engineer, 5-person team</h3></summary>

[Source code](https://github.com/Kgan3039/ai-market-sentiment-dashboard)

Built **3 fixture-backed Phase 0 FastAPI endpoints** across a **5-ticker** demo dataset, connected the React dashboard to the API, and hardened the integration around validation, errors, freshness metadata, and production routing.

- **22 targeted tests passing**: 14 backend + 8 frontend
- Separates data ingestion, NLP, prediction, API, and dashboard responsibilities behind explicit contracts
- **Stack:** Python, FastAPI, REST APIs, React, SQLite, Vitest

</details>

## Skills

| Area | Technologies |
| --- | --- |
| Languages | Python, Java, C, JavaScript/TypeScript, R, SQL, HTML/CSS |
| Frontend and Mobile | React, React Native, Expo Router, Vite |
| Backend and Data | FastAPI, REST APIs, WebSockets, Firebase/Firestore, SQLite, SQLAlchemy |
| Quality and Delivery | Pytest, Mocha, Vitest, Ruff, ESLint, Git/GitHub, Vercel, Render |
