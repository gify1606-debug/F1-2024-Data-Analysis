# 🏎️ F1 2024 Season Data Analysis  

<img src="figures/F1-Logo.png" alt="F1 Logo" width="500"/>  

A **data-driven analysis** of the 2024 Formula 1 season using Python, Pandas, Matplotlib, and Plotly.  
The project explores **driver performance, team dynamics, and season trends** through reproducible data science workflows.  

📊 **Interactive charts live here** → [GitHub Pages](https://gify1606-debug.github.io/F1-2024-Data-Analysis/)  

---

## 🔍 Goal  
Turn raw Formula 1 results into clear insights on:  
- Driver championship performance  
- Constructor dominance  
- Qualifying vs race performance  
- DNFs and reliability patterns  
- Sprint vs main race dynamics  

---

## 📦 Dataset  

- Original dataset: [Formula 1 World Championship (1950–2020) – Kaggle](https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020/data) by **Rohan Rao**  
- I **separated and cleaned only the 2024 season data**, keeping drivers, teams, race results, qualifying, sprints, and votes.  
- Stored in `/Data/` as multiple CSVs:  
  - `Formula1_2024season_drivers.csv`  
  - `Formula1_2024season_teams.csv`  
  - `Formula1_2024season_raceResults.csv`  
  - `Formula1_2024season_qualifyingResults.csv`  
  - `Formula1_2024season_sprintResults.csv`  
  - `driver_summary_2024.csv`  
  - *(see repo for full list)*  

---

## ⚙️ Features  

- **Data Cleaning & Prep**  
  - Standardized team/driver names  
  - Converted fastest laps to seconds  
  - Flagged DNFs  

- **Analysis & Visualisation**  
  - 🏆 Points, wins, podiums per driver  
  - 🏎️ Constructor points share (donut chart)  
  - 📈 Cumulative championship progression  
  - ⏱️ Fastest lap analysis  
  - 🔁 Position change (grid vs finish)  
  - 🟩 Sprint vs Main race comparison  
  - 📉 DNFs by driver, team, track  

- **Interactive Charts** (via Plotly + GitHub Pages)  
  - [Constructor Share](https://gify1606-debug.github.io/F1-2024-Data-Analysis/constructor_share.html)  
  - [Qualifying vs Race Result](https://gify1606-debug.github.io/F1-2024-Data-Analysis/Qualifying_vs_Race_Result.html)  

---

## 📊 Key Findings  

- **Championship picture** → Verstappen leads; Norris & Leclerc chase.  
- **Constructors** → McLaren, Ferrari, Red Bull, Mercedes = ~70% of all points.  
- **Qualifying vs Race** → Strong correlation (Pearson ≈ 0.78).  
- **Fastest Laps** → Norris often set late-race push laps.  
- **DNFs** → Williams struggled with most retirements; incident-heavy tracks = Lusail, Montreal, Interlagos, Monaco.  

---

## 🚀 Repo Structure

- **Data/** → CSV datasets (2024 season only)  
- **figures/** → Static figures and logos  
- **docs/** → HTML interactive charts (for GitHub Pages)  
  - `index.html` → entry point for GitHub Pages  
- **F1_2024_Analysis_Project_Template.ipynb** → main Jupyter Notebook  
- **README.md** → project documentation  
- **LICENSE** → project license  
- **.gitignore** → ignored files configuration  

---

## 🛠️ Tech Stack  

- Python 3.9  
- Pandas / NumPy  
- Matplotlib  
- Plotly (interactive charts)  
- GitHub Pages (deployment)  

---

## ✅ Conclusion

This project takes raw 2024 F1 results → cleans them → analyzes them → publishes
interactive charts. It shows:

- Solid data-wrangling (schema standardization, DNFs, time parsing).
- Clear visual storytelling (Matplotlib for static, Plotly for interactive).
- Reproducibility and deployment (helpers, consistent color maps, GitHub Pages).

**What you can do next**
- Add teammate head-to-head and per-track profiles.
- Try a simple predictive model (finish ~ grid + team + track effects).
- Enrich with strategy/weather where available.

📌 This was my first end-to-end data project — demonstrating data cleaning, analysis, and interactive visualisation with deployment via GitHub Pages.  

---

## 🙌 Acknowledgements

- Dataset by [Rohan Rao](https://www.kaggle.com/rohanrao) on Kaggle  
- IBM Coursera Course: *Python for Data Science, AI & Development* — foundation in Python and data analysis  
- Official Docs: [Pandas](https://pandas.pydata.org/), [Matplotlib](https://matplotlib.org/), [Plotly](https://plotly.com/python/)  
- [Stack Overflow](https://stackoverflow.com/) — troubleshooting errors and bugs  
- General Python syntax references (W3Schools, tutorials)  
- Logos & visuals belong to Formula 1® (for non-commercial/educational use)  

---
