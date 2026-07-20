<p align="center">
  <img src="https://avatars.githubusercontent.com/u/42321349?v=4" alt="Daksh Kumar" width="120" height="120" style="border-radius: 50%;" />
</p>

<h1 align="center">Daksh Kumar</h1>

<p align="center">
  <strong>MS in Financial Mathematics @ NC State &nbsp;|&nbsp; CFA Level I Candidate</strong><br/>
  Quantitative research and machine learning at the intersection of AI engineering and finance.
</p>

<p align="center">
  <a href="mailto:dakshdhull@gmail.com">Email</a> &nbsp;&middot;&nbsp;
  <a href="https://www.linkedin.com/in/daksh1069/">LinkedIn</a> &nbsp;&middot;&nbsp;
  Raleigh, North Carolina
</p>

---

## About

MS Financial Mathematics student at NC State working on quantitative research, derivatives, and volatility modeling. Previously a founding engineer at two startups, building production ML and data systems. Current focus areas: leveraged-ETF hedging, variance risk premium replication, and volatility surface calibration.

---

## Selected Projects

### Optimal Hedging of Leveraged ETF Positions (Convexity Protection) — NC State
*May 2026 – Present*
- Multi-tranche hedging engine on Tesla's 2x leveraged ETF (TSLL) — short the LETF, long ATM calls, short OTM puts (collar) — harvesting structural volatility decay with maximum drawdown capped ex ante by a closed-form, model-free bound of 15.0%.
- The bound derives from no-arbitrage worst-case loss limits on each position, valid continuously rather than only at expiry; the realized equity path never breached it in-sample, out-of-sample, or across seven risk-limit configurations (960 trading days each).
- Delivered +15.7% CAGR (Sharpe 0.90, -12.3% max drawdown, Calmar 1.28) vs. -81% max drawdown for the unhedged short; built the 1M+-row TSLA/TSLL options dataset (2020–2026) via a Bloomberg (BDH) + OpenFIGI pipeline.

### Variance Risk Premium & Variance-Swap Replication (SPX) — Independent
*Jun 2026*
- Replicated a 30-day SPX variance swap from option strips (model-free implied variance, CBOE VIX methodology), validating the synthetic index against the live VIX across 2017–2023 (1,676 days) to a 0.57 vol-point mean error and 0.99 correlation.
- Diagnosed and fixed three data-integrity bugs in the Databento OPRA pipeline (stale-tick forward selection, out-of-bracket extrapolation, instrument-ID reuse) that were corrupting the replication across regimes.
- Measured the variance risk premium at +3.75 vol points on average (positive 84% of days); backtested a cost-aware short-variance carry at net Sharpe 1.84 / 18% CAGR, reporting the -71% COVID-regime drawdown explicitly; shipped an interactive Streamlit dashboard.

### Calibration and Hedging of Local, Stochastic, and Hybrid Volatility Models — NC State
*Jan 2026 – May 2026*
- Unified calibration and hedging framework for Local (Dupire), Stochastic (Heston), and Stochastic-Local Volatility models on 5,000+ SPX option contracts.
- Arbitrage-free SVI volatility surface (RMSE 2.47%); finite-difference PDE solver for the Dupire model; ~15% lower pricing error in deep out-of-the-money strikes and a 12% reduction in delta-hedging P&L leakage.

### Additional Projects
- **BCI Electrode Optimization (EEG):** Particle Swarm Optimization with a composite-kernel SVM on motor-imagery tasks; 45% fewer electrodes (120 to 67) with maintained accuracy and 25% better signal differentiability via CSP / Stationary-CSP.
- **CPI Forecasting & Analysis:** Forecast CPI inflation from unemployment, gilt rates, and ROI using statistical ML models, with comparative model evaluation.

---

## Experience

### CBCatalyst — Founding AI Engineer
*Mar 2025 – Jan 2026*
- Built a multi-modal recommendation engine (CLIP, BART, GPT-2), improving Top-10 recall by 35% and CTR by 50%.
- Pioneered OCR and LLM-powered data pipelines, accelerating company onboarding by 38%.
- Optimized RDBMS performance via indexing (GIN, HNSW), achieving 2.6x faster search and 3.7x faster lookups.
- Deployed a production RAG system with Milvus vector indexing and cross-encoder re-ranking.

### PropReturns (YC S21) — Founding Data Science Engineer
*Jun 2022 – Mar 2024*
- Profiled 100+ clients for pitchbook customization, increasing conversion by 25%.
- Engineered serverless ETL pipelines (AWS Lambda, Glue), reducing data-processing costs 3.5x.
- Built serverless scrapers that cut lead-acquisition cost from Rs.150–200 to Rs.4–7 (~97% reduction).
- Shipped PropPulse, a SaaS analytics product serving 500+ monthly active users across 1M+ real-time transactions.

---

## Technical Skills

- **Languages:** Python, Java, C/C++, SQL, MATLAB, Verilog
- **ML / AI:** PyTorch, TensorFlow, Keras, Transformers, CLIP, CUDA
- **Quant / Data:** NumPy, SciPy, pandas, Bloomberg Terminal, Databento
- **Infrastructure:** PostgreSQL, MongoDB, AWS (Lambda, Glue, EC2), Docker, Milvus

---

## Education

**MS, Financial Mathematics** — North Carolina State University · *Jan 2026 – Present* · GPA: 3.66/4.0

Completed Coursework: Numerical Methods, Linear Algebra, Advanced Mathematics for Engineers and Scientists, Financial Market Operations.

Present Coursework: Options and Derivative Pricing, Probability, and Stochastic for Finance.

**MS, Management & B.Tech, Electronics & Communication Engineering** — Jawaharlal Nehru University · *Aug 2018 – Jul 2023*
B.Tech GPA: 3.64/4.0.

---

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=daksh1069&show_icons=true&theme=github_dark&hide_border=true&count_private=true" height="165" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=daksh1069&layout=compact&theme=github_dark&hide_border=true" height="165" alt="Top Languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=daksh1069&theme=github-dark&hide_border=true" alt="GitHub Streak" />
</p>

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=daksh1069&theme=github_dark" alt="GitHub Profile Details" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=daksh1069&theme=github-compact&hide_border=true" height="300" alt="Contribution Graph" />
</p>

---

<p align="center">
  Open to conversations on quantitative finance, machine learning, and scalable ML systems.<br/>
  <a href="mailto:dakshdhull@gmail.com">dakshdhull@gmail.com</a> &nbsp;&middot;&nbsp;
  <a href="https://www.linkedin.com/in/daksh1069/">LinkedIn</a>
</p>
