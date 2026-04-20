# Hi, I'm Manal👋

**Data Science | AI | Software Engineering | Quantitative Finance | QA**

*Open to a Summer 2026 Internship!*

I'm a second-year University of Waterloo student pursuing a double major in **Computer Science and Finance**. 

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)

## 🔧 Technical Skills
**Languages:** Python, C, HTML/CSS, SQL, JavaScript, Racket

**Libraries:** scikit-learn, SciPy, NumPy, Pandas, Matplotlib, yfinance

**Web Development:** React.js, Node.js, Tailwind CSS

**Tools:** REST APIs, Git, Jupyter Notebook, Looker, Tableau, LaTeX

## 💼 Featured Projects
---

### 🔐 EvidenceLog — Blockchain-Based Digital Evidence Management
*Python, hashlib, json*

Built a forensic chain of custody system that logs files as SHA-256 fingerprints
on a tamper-proof blockchain — any modification to a file or the chain itself is
immediately detectable.

**Technical Highlights:**
- SHA-256 file hashing with chunked reading for large files
- Linked block structure where each block stores the previous block's hash
- Full chain integrity validation catching both file-level and chain-level tampering
- CLI covering the complete evidence workflow: log, verify, and audit

**Outcome:** Any tampering — to a file or the chain itself — is mathematically impossible to hide.

---
### 💳 Credit Card Spending Prediction & Model Simplification
*Python, NumPy, Pandas, Matplotlib, Scikit-learn*

Built a full ML pipeline on 100,000 synthetic credit card customers to evaluate 
whether a simplified challenger model could replace a complex production model 
without sacrificing predictive power.

**Technical Highlights:**
- Trained and compared 3 models: Linear Regression, Gradient Boosting, and Random Forest
- Performed feature importance analysis to identify key spending drivers
- Engineered `spending_velocity` (transaction frequency × avg amount) — captured **99.5%** of model decisions
- Built simplified 5-feature challenger model achieving identical R² (**0.9984**) to 13-feature full model
- Quantified operational trade-offs: 62% feature reduction, ~40–60% faster inference, no accuracy loss
- Generated executive-style strategic recommendation report with phased deployment roadmap

**Outcome:** Demonstrated that model complexity is not a prerequisite for accuracy — 
the simplified model matched full performance while delivering significant gains in 
interpretability, deployment cost, and regulatory explainability.

---
### 📈 Risk-Averse Portfolio Robo-Advisor
*Python, NumPy, Pandas, Matplotlib, SciPy, yfinance*

**🏆 2nd Place** in UW CFM 101 Robo-Advisor Competition

Built a market-neutral portfolio optimizer designed to achieve returns closest to zero during a 5-day live trading period.

**Technical Highlights:**
- Implemented Markowitz minimum-variance optimization using SLSQP solver
- Filtered random TSX/S&P 500 securities by volatility, correlation, and beta
- Applied sophisticated constraints: sector caps (≤40%), position limits (0.5–15%), market cap requirements, transaction cost modeling
- Constructed defensive portfolio with **beta of 0.32** and **10.8% annualized volatility**
- Validated strategy with 1-year historical backtest on $1M CAD across multiple sectors

**Outcome:** Demonstrated strong understanding of portfolio theory and risk management in a competitive, real-money simulation environment.

---
### 📊 Inventory Risk Management System
*Python, SQL, scikit-learn, NumPy, Pandas, Matplotlib*

Tackled a real-world critical overstock crisis by developing a Monte Carlo-based inventory risk management system.

**Key Achievements:**
- Engineered probabilistic demand forecasting system using Monte Carlo simulation (10,000 iterations per SKU) and negative binomial distributions to quantify uncertainty across 44-product portfolio
- Calculated VaR and CVaR metrics, quantifying **$1,635 expected portfolio profit**
- Generated time-sensitive recommendations for 20 critical SKUs (1,447 units total)
- Identified **7 products facing 100% stockout within 14 days** and flagged 3 negative-margin items for immediate liquidation
- Built risk segmentation model classifying 24 high-risk products
- Currently developing React-based visualization dashboard for stakeholder reporting

**Outcome:** Delivered actionable inventory strategy that balanced stockout risk against holding costs, demonstrating advanced capability in stochastic modeling, financial risk quantification, and data-driven decision-making under uncertainty in a real-world supply chain context.

---
### 📚 Library Reading Tracker
*React.js, JavaScript, Tailwind CSS, Open Library API*

Built a full-featured reading management application for tracking, rating, and reviewing books with automated metadata retrieval.

**Features:**
- Integrated Open Library REST API for automatic metadata and cover image population
- Responsive UI built with Tailwind CSS supporting real-time filtering across multiple attributes
- Currently developing Node.js backend with MongoDB for user authentication and cross-device synchronization

**Outcome:** Solved a personal pain point while demonstrating full-stack capabilities—from API integration to database design to responsive UI development. Full-stack development, API integration, responsive design, database architecture

---

### 🎮 Trivia Rush — Multiplayer Trivia Game
*JavaScript, Node.js, WebSockets, Playwright*

Built a real-time multiplayer trivia game from scratch, including the game server, browser client, and a full automated test suite.

**Technical Highlights:**
- Engineered a WebSocket game server in Node.js managing concurrent player sessions, round lifecycle, and authoritative game-state synchronisation across all clients
- Handled server-side race-condition edge cases — simultaneous answer submissions, mid-round disconnections, and session recovery within a 30-second reconnection window
- Built a Playwright automation suite simulating 10+ concurrent browser sessions, validating state consistency under adversarial timing conditions
- Produced structured bug reports with reproduction steps, session logs, and expected-vs-actual results, mirroring industry QA workflows
- Delivered iteratively across Agile sprints with planning, demos, and retrospectives

**Outcome:** Deepened practical understanding of real-time systems, concurrency bugs,
and test-driven QA — directly applicable to software engineering and QA internship workflows.

---

## 🎯 What I'm Working On

- Expanding the Inventory Risk Management dashboard with interactive React visualizations
- Building authentication and database layers for the Reading Tracker application
- Exploring quantitative trading strategies and backtesting frameworks

## 💬 Ask me about
- How I built a risk management system for a real client
- What I'm currently reading (always happy to share recommendations!)
- Quantitative finance projects
- React and data visualization projects

## 📫 How to reach me

- **LinkedIn:** www.linkedin.com/in/manal-khan123
- **Email:** m544khan@uwaterloo.ca

## ⚡ Fun fact: 
- I read **120+ books in 2024** through E-libraries that didn't track them — so I built ReadNest to rate, review, and organize my favorites. Now I keep adding features to it to make it even better! 📚

---
