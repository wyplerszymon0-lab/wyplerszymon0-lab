# Hi, I'm Szymon Wypler 👋

**Junior developer** from Poland working where **data**, **AI** and **geospatial / GIS** meet: from geodetic survey data to machine-learning models and LLM evaluation.

> 🔎 **Open to work:** I'm looking for my **first professional role**, a junior position or an internship in **data**, **AI / machine learning** or **GIS and geospatial analysis**. I have hands-on field experience from geodetic surveys for photovoltaic sites (Erasmus+ internship in Portugal). The projects below show how I work: measured results instead of claims, tests and CI on every repository, and every change going through a pull request. Get in touch on [LinkedIn](https://www.linkedin.com/in/szymon-wypler-bb7650394/).

## Featured projects

| Project | What it is | Stack |
|---|---|---|
| [**PV Site Screening — Poland**](https://github.com/wyplerszymon0-lab/pv-site-screening-pl) | Finds where a ground-mounted solar farm could go in any Polish *gmina*, from open data only: PRG boundaries, NMT terrain (5 m slope/aspect), GDOŚ protected areas, OSM or BDOT10k exclusions, a weighted suitability score and NASA POWER yield. Validated against farms already built; styled QGIS project and print map; PostGIS version of the overlay. | Python, GeoPandas, rasterio, PostGIS, QGIS (PyQGIS) |
| [**Solar Site Intelligence**](https://github.com/wyplerszymon0-lab/Solar-site-intelligence) · [live demo](https://wyplerszymon0-lab.github.io/Solar-site-intelligence/) | Turns raw geodetic survey data into photovoltaic site assessments: interactive map, optimal tilt, yield and row-spacing estimates. Built from my experience doing PV site surveys during an Erasmus+ internship in Portugal. Yield model on NASA POWER satellite data, 3.6% mean deviation from PVGIS. The AI site report runs through my own backend on Google Cloud Run, so visitors need no API key, and the backend stores none either (workload identity federation). | JavaScript, Leaflet, Node, Google Cloud Run |
| [**Reinforcement Learning Agents**](https://github.com/wyplerszymon0-lab/reinforcement-learning-agents) | DQN (Double, Dueling) and PPO (GAE, clipped objective) written from scratch in PyTorch, with vectorised environments and TensorBoard logging. Both solve LunarLander on 3 of 3 seeds; the PPO tuning history, including the change that made it worse, is in the results. | Python, PyTorch, Gymnasium |
| [**CryptoPulse**](https://github.com/wyplerszymon0-lab/cryptopulse) · [live dashboard](https://wyplerszymon0-lab.github.io/cryptopulse/) | Crypto technical-analysis engine with a lookahead-free backtester and walk-forward optimisation that reports only out-of-sample results. A GitHub Action rebuilds the dashboard daily. Zero dependencies. | Go, GitHub Actions/Pages |
| [**LLM State-Consistency Audit**](https://github.com/wyplerszymon0-lab/llm-state-consistency-audit) · [live leaderboard](https://wyplerszymon0-lab.github.io/llm-state-consistency-audit/) | Benchmark that checks whether LLM-generated programs keep global state consistent across dependent operations. Four business simulations, submissions run in a locked-down Docker sandbox, Wilson confidence intervals, and a prompt study (a worked example did not help small models). | Python |

## Tech

- **Languages:** main: Python, SQL · also: TypeScript / JavaScript, Go, C#
- **GIS & geodesy:** QGIS (PyQGIS) | GeoPandas, rasterio, Shapely | PostGIS | PL-1992 / PL-2000 | Polish open geodata: PRG, NMT, BDOT10k, GDOŚ (WFS/WCS) | geodetic field surveys | Leaflet web maps
- **ML:** PyTorch | scikit-learn | reinforcement learning | LLM APIs and evaluation
- **AI-assisted development:** Claude Code
- **Cloud:** Google Cloud: Cloud Run, Firestore, IAM service accounts, workload identity federation (keyless auth to the Claude API), budget alerts
- **Engineering:** Docker | GitHub Actions (CI, Pages, releases) | REST APIs | testing (pytest, Go tests, node:test)

## Contact

📍 Poland · [LinkedIn](https://www.linkedin.com/in/szymon-wypler-bb7650394/)
