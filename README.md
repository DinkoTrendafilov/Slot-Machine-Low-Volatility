# 🎰 Slot-Machine-Low-Volatility

A mathematically validated low volatility slot machine with **5 reels**, **4 rows**, **20 paylines**, and **30 symbols**. Validated with **10,000,000+ Monte Carlo simulations**.

---

## 🎮 Play the Live Demo

**Try the slot machine directly in your browser:**

👉 **[Play Dark Fortune Low Volatility](https://dinkotrendafilov.github.io/Slot-Machine-Low-Volatility/DEMO_dark_fortune_low_volatility.html)**

No installation needed. Just click and play!

---

## 📊 Key Metrics

| Metric | Value |
|--------|-------|
| **Theoretical RTP** | 94.822% |
| **Simulated RTP** | 94.947% (10M spins) |
| **RTP Deviation** | 0.124% ✅ |
| **Volatility Index (CV)** | 3.38 |
| **Hit Rate** | 96.29% |
| **Jackpot Frequency** | 1 in 810,000 |
| **Max Win Potential** | 200,000x |
| **Survival at 2,000 spins** | 100% |

---

## 🎮 Features

- **5 Reels × 4 Rows** with 20 paylines
- **30 dark-themed symbols** (🖤💀🌙🐦‍⬛🔮🌑🕷️🦇🌫️⚰️👻🧛🧙‍♀️🌒🩸🗡️🏚️🌌⚡🌀🕯️☠️💫🌩️🌪️🔥❄️👁️🎃🌕)
- **Low volatility** — frequent small wins, extended gameplay
- **10,000,000+ Monte Carlo simulations** for validation
- **Bayesian analysis** with 95% credible intervals
- **Survival analysis** across 500–10,000 spins
- **Interactive HTML demo** — playable slot in your browser

---

## 📁 Project Structure

Slot-Machine-Low-Volatility/
│
├── low_volatility.ipynb # Python code + full analysis
├── DEMO_dark_fortune_low_volatility.html # Interactive HTML demo
├── Software_Design_Document.ipynb # Full SDD (20+ sections)
└── README.md # This file


---

## 🛠 Technologies

| Component | Technology |
|-----------|------------|
| Core Language | Python 3.14 |
| Numerical Computing | NumPy |
| Statistical Analysis | SciPy (Beta, Binomial) |
| Visualization | Matplotlib |
| Demo | HTML, CSS, JavaScript (no external libraries) |

---

## 🎯 What's Inside

### 1. Combinatorial Analysis
- Full enumeration of **24,300,000** possible combinations
- Distribution by max matching symbols (2, 3, 4, 5 matches)

### 2. Monte Carlo Simulation
- **10,000,000 spins** simulated
- RTP validated with only **0.124% deviation**
- Win distribution, hit rate, and volatility metrics

### 3. Bankroll Survival Analysis
- **1,000 sessions** simulated per spin target
- Starting balance: **10,000 credits**
- Bet: **20 credits per spin** (1 credit × 20 lines)
- **100% survival** up to 2,000 spins

### 4. Bayesian Analysis
- Jackpot frequency validation
- **95% credible intervals** for 5-match probability
- Observed frequency: 1 in 757,576 (vs theoretical 1 in 810,000)

### 5. Interactive HTML Demo
- Fully playable slot with all game logic
- Real-time HUD (credits, bet, last win)
- Autoplay mode ("spin until broke")
- Audio feedback (spin, win, jackpot sounds)
- Win line highlighting
- Jackpot celebration (flash + 3.5-minute melody)

---

## 📈 Paytable

| Match Type | Coefficient | RTP Contribution |
|------------|-------------|------------------|
| 2 matches | 2x | 60.26% |
| 3 matches | 32x | 35.04% |
| 4 matches | 180x | 3.40% |
| 5 matches (Jackpot) | 10,000x | 1.30% |

---

## 🚀 How to Run

### Python Code
1. Open `low_volatility.ipynb` in Jupyter Notebook
2. Run all cells
3. Enter RTP coefficient (e.g., 95) and number of iterations (e.g., 10,000,000)

### HTML Demo
1. Open `DEMO_dark_fortune_low_volatility.html` in any modern browser
2. No server required — works locally
3. Adjust bet, spin, and observe real-time results

---

## 📊 Validation Summary

| Metric | Theoretical | Simulated | Difference |
|--------|-------------|-----------|------------|
| RTP | 94.822% | 94.947% | 0.124% ✅ |
| Hit Rate | 99.91% | 96.29% | 3.62% |
| Jackpot Frequency | 1 in 810,000 | 1 in 757,576 | 6.5% |

**The game's mathematical model is fully validated.**

---

## 👤 Author

**Dinko Trendafilov**

---

## 📄 License

MIT License

---

## 🔗 Next Phases

- [ ] Medium Volatility Slot Machine
- [ ] High Volatility Slot Machine
- [ ] Bonus Features (wild symbols, free spins, multipliers)
- [ ] Performance Optimization (vectorized NumPy)

---

**Happy spinning!** 🍀
