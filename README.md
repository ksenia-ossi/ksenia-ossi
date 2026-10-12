# Hi, I'm Ksenia 👋

**Data / ML student at [42 Paris](https://42.fr), ex-QA engineer, looking for a 6-month Data internship (stage) in Paris / Île-de-France.**

My projects below cover the full data workflow: loading raw data into PostgreSQL and exploring it, building and evaluating ML models, and documenting the results. Before 42 I worked as a QA engineer and did a Master's in International Business.

- 🔎 Looking for: **Data Analyst / Data Scientist / ML internship**, 6 months, Paris (convention de stage from 42)
- 📅 Available from: **January 2027** <!-- TODO Ksenia: check the date -->
- 🗣️ English (professional) · French (B1) · Russian (native)
- 📫 [LinkedIn](https://www.linkedin.com/in/TODO) <!-- TODO Ksenia: LinkedIn URL -->

## 🛠 Tech stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-2E8B57?style=flat)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat)
![Power BI](https://img.shields.io/badge/Power_BI_(DAX)-F2C811?style=flat&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat&logo=pytest&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)

## 📊 Data projects

| Project | What it is | Stack | Result |
|---|---|---|---|
| **[ad-click-prediction](https://github.com/ksenia-ossi/ad-click-prediction)** | End-to-end CTR pipeline on the public Criteo dataset: raw TSV → PostgreSQL → SQL/pandas EDA → feature engineering (hashing trick, missing-value indicators, log1p) → models → calibrated metrics. Time-based split, baseline first. | Python, PostgreSQL (Docker), pandas, scikit-learn, LightGBM, pytest | Logistic regression **AUC 0.766 / log-loss 0.466** vs LightGBM 0.756, both beating the constant baseline (0.546) |
| **[tr-emea-supply-chain-dashboard](https://github.com/ksenia-ossi/tr-emea-supply-chain-dashboard)** | Supply-chain KPI dashboard for EMEA travel retail (synthetic data, 1 800 orders): star schema, OTIF / fill rate / lead time / cost per order, regional and seasonal breakdown. Power BI-ready data model with documented DAX measures. | Python, Excel, star schema, DAX | Found OTIF 2.7 pp below target, worst region (Africa, 73%) and the peak-season drop (66% in Dec) |
| **[stage-finder](https://github.com/ksenia-ossi/stage-finder)** | Small Flask tool that scrapes 3 job boards (LinkedIn, Welcome to the Jungle, HelloWork), de-duplicates offers, filters to Île-de-France internships and **ranks them against a configurable skills profile**. Tracks seen/saved/applied offers in SQLite, exports CSV. | Python, Flask, requests, SQLite | Used daily for my own internship search |

## 💻 Other projects

| Project | What it is | Stack |
|---|---|---|
| **[transcendence](https://github.com/ksenia-ossi/transcendence)** | Real-time multiplayer Pong (42 team project of 3). I built the frontend SPA and the WebSocket game flow. | React 19, TypeScript, Tailwind, Zustand, WebSockets, Docker |
| **[sound-access](https://github.com/ksenia-ossi/sound-access)** | SwiftUI music-player prototype exploring inclusive iOS UI: VoiceOver, Dynamic Type, Reduce Motion. | Swift, SwiftUI, XCTest |
| **[try](https://github.com/ksenia-ossi/try)** | Chrome extension (Manifest V3): save clothing images from any shop and run a virtual try-on through the Replicate API. | JavaScript, Chrome Extensions API, Replicate |

## 🎓 Background

- **42 Paris**: Common Core completed (RNCP level 7). ML projects: multiclass logistic regression (team), multilayer perceptron from scratch, linear regression, SQL/PostgreSQL.
- **Master's in World Economy & International Business**, Ural State University of Economics (statistics & econometrics coursework).
- **Hackathons:** winner of the LVMH Hackathon · participant, Agora / Assemblée Nationale hackathon.
- **Courses:** Hugging Face Agents Course (2025).
- **Previously:** QA Engineer (test design, regression testing, bug reporting).

<!-- Optional: GitHub stats card. Delete the comment markers to show it.
![Ksenia's GitHub stats](https://github-readme-stats.vercel.app/api?username=ksenia-ossi&show_icons=true&hide_rank=true)
-->
