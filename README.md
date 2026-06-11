# ⚽ AI Simulated the 2026 FIFA World Cup 5,000 Times

Can artificial intelligence predict the winner of the 2026 FIFA World Cup?

In this project, I built a machine learning and Monte Carlo simulation pipeline to simulate the entire tournament 5,000 times and estimate the probability of every team reaching each stage of the competition.

## 🎥 YouTube Video

Watch the full project breakdown here:

https://www.youtube.com/watch?v=xn7CIsdEjGU

---

## 📌 Project Overview

The simulation combines:

- Team Elo ratings
- Recent match performance
- Goals scored and conceded
- Expected goals (xG)
- Head-to-head statistics
- Monte Carlo tournament simulation

Using these features, the model predicts match outcomes and simulates the entire World Cup bracket thousands of times.

---

## 🔍 Methodology

### 1. Data Collection

Data was collected for all qualified teams, including:

- Recent form
- Goals scored
- Goals conceded
- Historical performance

### 2. Match Prediction Model

A machine learning model was trained on historical international matches to estimate:

- Home win probability
- Draw probability
- Away win probability

### 3. Tournament Simulation

The tournament was simulated 5,000 times.

For each simulation:

1. Group stage matches were played.
2. Teams advanced according to FIFA rules.
3. Knockout rounds were generated.
4. A champion was crowned.

Results were aggregated across all simulations.

---

## 📊 Output

| Team | Win Probability |
|--------|--------|
| France | 12.6% |
| Spain | 11.1% |
| Uruguay | 15.9% |
| England | 16.1% |
| Brazil | 6.8% |

---

## 📁 Repository Structure

```text
WorldCupAISimulation/
│
├── notebooks/
│   └── WorldCup2026Simulation.ipynb
│
├── data/
│   ├── train.csv
│   └── test.csv
│
├── outputs/
│   └── wc2026_probabilities.csv
│
├── images/
│   └── Result.png
│
├── requirements.txt
└── README.md
```

---

## 🚀 Running the Project

Install dependencies:

```bash
pip install -r requirements.txt
```

Open the notebook:

```bash
jupyter notebook
```

Run:

```text
WorldCup2026Simulation.ipynb
```

---

## 🧠 Technologies Used

- Python
- Pandas
- NumPy
- XGBoost
- Scikit-Learn
- Google Colab
- Monte Carlo Simulation

---

## ⚠️ Disclaimer

This project is intended for educational and entertainment purposes.

Football matches are inherently unpredictable, and real-world outcomes may differ significantly from simulated results.

---

## 📺 About

This repository accompanies the YouTube video:

**"I Simulated the 2026 FIFA World Cup Using AI 5,000 Times"**

If you found the project interesting, consider starring the repository and checking out the video.
