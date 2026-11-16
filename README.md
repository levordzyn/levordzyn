<!-- Header banner -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:e10600,100:0b0b0b&height=190&section=header&text=levordash&fontSize=56&fontColor=ffffff&fontAlignY=36&desc=Information%20Systems%20%C3%97%20Formula%201&descSize=18&descAlignY=58&animation=fadeIn" alt="levordash — Information Systems × Formula 1" />

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&pause=1200&color=E10600&center=true&vCenter=true&width=520&lines=Turning+data+into+decisions%2C+lap+by+lap;Building+a+tyre+deg+%26+strategy+sim)](https://github.com/levordzyn)

</div>

---

## 🎙️ Pit Wall

Hi,

- 🎓 Information Systems student  
- 🏎️ During races, I'm usually wondering what data drove the strategy call on lap 24  
- 📊 I build systems that turn raw data into decisions, the same job a pit wall does every weekend  
- 🌱 Currently deep in data pipelines, statistical modeling, and race strategy simulation

---

## 🛠️ Garage

![Python](https://img.shields.io/badge/Python-0b0b0b?style=for-the-badge&logo=python&logoColor=e10600)
![SQL](https://img.shields.io/badge/SQL-0b0b0b?style=for-the-badge&logo=postgresql&logoColor=e10600)
![SQLite](https://img.shields.io/badge/SQLite-0b0b0b?style=for-the-badge&logo=sqlite&logoColor=e10600)
![Pandas](https://img.shields.io/badge/Pandas-0b0b0b?style=for-the-badge&logo=pandas&logoColor=e10600)
![SciPy](https://img.shields.io/badge/SciPy-0b0b0b?style=for-the-badge&logo=scipy&logoColor=e10600)
![scikit-learn](https://img.shields.io/badge/scikit--learn-0b0b0b?style=for-the-badge&logo=scikitlearn&logoColor=e10600)
![XGBoost](https://img.shields.io/badge/XGBoost-0b0b0b?style=for-the-badge&logo=xgboost&logoColor=e10600)
![Git](https://img.shields.io/badge/Git-0b0b0b?style=for-the-badge&logo=git&logoColor=e10600)

---

## Results

| Pos | Project | What it does | Status |
|:---:|:--------|:-------------|:------:|
| **P1** | **F1 Tyre & Strategy Simulator** | Predicts tyre drop-off and tests pit-stop strategies with Monte Carlo runs (`OpenF1`, `SQLite`). | 🚧 Building |
| **P2** | **[F1 Race Predictor](https://github.com/levordzyn/f1race-prediction-analyst)** | Predicts Grand Prix winners using quali deltas, sprint data, track temp & weather (`FastF1` / `OpenF1`). Benchmarks Ridge vs. XGBoost. | ✅ Live |
| **P3** | **[ml-football27](https://github.com/levordzyn/ml-football27)** | Companion tool for eFootball Master League saves (fork of [tjgg260/eFootball-Master-League](https://github.com/tjgg260/eFootball-Master-League)). | ✅ Live |

<details>
<summary><b> In the Garage: F1 Tyre & Strategy Simulator</b></summary>
<br>

**The question:** How much pace do tyres actually lose once you strip out fuel burn, and when is pitting worth the 20+ seconds?

**The plan:** First, model tyre wear and stint length from OpenF1 lap/stint data (accounting for pit stops cutting stints short). Then plug that into a Monte Carlo race simulator with pit-loss and Safety Car odds to see which strategy holds up—and backtest it against real races.

**Main thing I'm testing:** Cars and tyres change every season, so I'm running walk-forward checks to see if older seasons still help or just add noise.

**Stack:** Python, SQLite, Pandas, SciPy, Statsmodels, OpenF1

</details>

<details>
<summary><b> Behind the Build: F1 Race Predictor</b></summary>
<br>

**The question:** How much signal lives in pre-race sessions (quali pace, sprint results, track temp) to predict Sunday's podium?

**The approach:** Ingested timing data via FastF1/OpenF1, engineered rolling performance features, compared linear (Ridge) vs. non-linear (XGBoost) baselines.

**Key finding:** XGBoost edged Ridge on non-linear interactions (track temp x tyre compound, quali-sprint delta).

**Stack:** Python, FastF1, Pandas, scikit-learn, XGBoost

</details>

---

## 🔧 Next Stint

- **Build the Tyre & Strategy Sim** — get the OpenF1 pipeline clean, test whether old seasons still predict new tyres, and backtest strategies against real races
- **Keep my models honest** — stick to walk-forward validation, uncertainty ranges, and writing down what failed in `LIMITATIONS.md`
- **Dream project** — real-time telemetry into lightweight AI race engineer concept

---

## 💬 Paddock Talk

| Favorite| |
|---|---|
| **Drivers** | Kimi Antonelli, Pierre Gasly, Charles Leclerc |
| **Team** | Mercedes-AMG PETRONAS F1 Team |
| **Circuit** | Interlagos (São Paulo) |

---

## 📫 Radio Check

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0b0b0b?style=for-the-badge&logo=linkedin&logoColor=e10600)](https://linkedin.com)
[![Email](https://img.shields.io/badge/Email-0b0b0b?style=for-the-badge&logo=gmail&logoColor=e10600)](mailto:-)

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0b0b0b,100:e10600&height=100&section=footer" alt="" />
