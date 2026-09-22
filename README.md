# Hi, I'm Anggun 👋

I'm a student interested in software engineering, quantitative research, and market structure.

**Seeking Summer 2027 internships** · Software engineering · Quant development · Fintech

[LinkedIn](https://www.linkedin.com/in/anggun-soracca-jaya-51a329236/?skipRedirect=true) · [Email](mailto:anggunsoraccaj@gmail.com)

---

## Selected projects

### [Redline Exchange](https://github.com/asoracca/redline-exchange)
`Python` `C++` · Exchange matching

Price-time matching with integer ticks, cancel/replace rules, and Python/C++ parity tests. [Synthetic benchmarks →](https://github.com/asoracca/redline-exchange/blob/main/docs/performance/STUDY.md) cover single-host API performance, excluding networking and persistence.

### [TradeGoons](https://github.com/asoracca/tradejournal)
`TypeScript` `Next.js` `Prisma` · Paper trading

A paper-trading journal with application routes, portfolio views, and optional Gemini commentary. [Explore the demo →](https://tradejournal-three-liard.vercel.app) External market data; authentication is not yet implemented.

### [Numerical Pricing](https://github.com/asoracca/soxl-vol-surface)
`Python` `NumPy` `SciPy` · Simulation methods

Price and delta estimators tested against Black–Scholes at equal payoff budgets, with cross-fitted controls and scrambled Sobol sampling. [Results and rare-payoff failure case →](https://github.com/asoracca/soxl-vol-surface/blob/main/docs/NUMERICAL_RESULTS.md)

### [Poker Solver](https://github.com/asoracca/pokeringdumdum)
`Python` · Game theory

CFR/CFR+ for hidden-information decisions in Kuhn poker, with exact best-response evaluation. [Equilibrium and exploitability tests →](https://github.com/asoracca/pokeringdumdum/blob/main/tests/test_solver.py)

### [Backtest Engine](https://github.com/asoracca/backtest-engine)
`Python` `pandas` · Portfolio simulation

Next-open execution, transaction costs, and auditable ledgers to prevent same-close look-ahead. [Timing and accounting tests →](https://github.com/asoracca/backtest-engine/blob/main/tests/test_engine.py) use synthetic bars.

---

<details>
<summary><strong>Skills in code</strong> — implementation and tests</summary>

| Skill | Evidence |
|---|---|
| Python | [Numerical estimators](https://github.com/asoracca/soxl-vol-surface/blob/main/src/numerical_methods.py) |
| C++ | [Matching core](https://github.com/asoracca/redline-exchange/blob/main/cpp/core.hpp) · [native tests](https://github.com/asoracca/redline-exchange/blob/main/cpp/test_core.cpp) |
| TypeScript | [Application routes](https://github.com/asoracca/tradejournal/blob/main/app/api/trades/route.ts) · [UI](https://github.com/asoracca/tradejournal/blob/main/app/trades/page.tsx) |

</details>

Also exploring: [momentum research](https://github.com/asoracca/momentum-factor-backtest) with a chronological holdout. Its separate historical demo regression did not find statistically significant alpha.
