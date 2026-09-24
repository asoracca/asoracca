# Hi, I'm Anggun 👋

I'm a UW–Madison student building software to explore markets, uncertainty, and decision-making. My projects span Python/C++ systems, numerical research, full-stack applications, and bounded AI workflows.

**Seeking Summer 2027 internships** · Software engineering · Quant development · Fintech

[LinkedIn](https://www.linkedin.com/in/anggun-soracca-jaya-51a329236/?skipRedirect=true) · [Email](mailto:anggunsoraccaj@gmail.com)

## Selected projects

### [Redline Research Copilot & Exchange](https://github.com/asoracca/redline-exchange)
`Python` `C++17` `TypeScript / React` `SQLite`

A research application that turns supported market-microstructure questions into validated simulation plans, runs experiments across seeds, and produces reports linked to evidence.

- Bounded orchestration with work budgets, cancellation, checkpoint recovery, and transactional run history.
- Optional AI planning and review; Python controls execution, numerical results, and report validation.
- An underlying price-time matching engine with cancel/replace rules, Python/C++ parity tests, and repeated API benchmarks.

The public demo uses **scripted planning and real simulations**. Live-model integration is implemented with mocked-transport tests; live behavior and any multi-agent advantage remain unmeasured.

[Try the demo](https://redline-research-copilot.onrender.com/) · [Workflow, evaluations & recovery](https://github.com/asoracca/redline-exchange/blob/main/docs/RELIABILITY.md)  
*The free demo may take a minute to wake up.*

### [Options Numerical Methods Lab](https://github.com/asoracca/soxl-vol-surface)
`Python` `NumPy` `SciPy`

How much pricing error remains for a given compute budget? Compare Monte Carlo, antithetic sampling, control variates, scrambled Sobol, and importance sampling using reproducible synthetic contracts. Measure price and delta error, runtime, and rare-payoff failure cases against analytical references.

[Study design & reproducibility](https://github.com/asoracca/soxl-vol-surface/blob/main/docs/STUDY_RUNNER.md)

### [Backtest Engine](https://github.com/asoracca/backtest-engine)
`Python` `pandas` `SQLite`

An event-driven portfolio simulator with next-open execution, explicit costs, cash reservation, and auditable ledgers. Stored configurations and price inputs support exact replay; a separate selection-bias study examines how searching many strategies can manufacture an impressive in-sample winner.

[Experiment storage & replay](https://github.com/asoracca/backtest-engine/blob/main/docs/EXPERIMENTS.md)

### [Kuhn Poker Solver](https://github.com/asoracca/pokeringdumdum)
`Python` `TypeScript`

CFR/CFR+ for decisions under hidden information, with exact best-response and exploitability evaluation. Includes resumable training experiments and an interactive explorer for inspecting action probabilities, regrets, and playing against a saved policy.

[Game rules & evaluation](https://github.com/asoracca/pokeringdumdum/blob/main/docs/METHODOLOGY.md)

### [TradeGoons](https://github.com/asoracca/tradejournal)
`TypeScript` `Next.js` `Prisma` `PostgreSQL`

A paper-trading journal for stocks, options, and futures, with portfolio views, market-data integrations, and optional Gemini educational commentary. An application demo; authentication and user isolation are still future work.

[Explore the demo](https://tradejournal-three-liard.vercel.app)

## More research

| Project | Focus |
|---|---|
| [Momentum Factor Research](https://github.com/asoracca/momentum-factor-backtest) | Monthly momentum experiments with explicit costs, missing-data coverage, leakage tests, block-bootstrap inference, and SQLite provenance. |
| [New Space Radar](https://github.com/asoracca/new-space-radar) | Source-aware event research for space equities, exchange-calendar alignment, synthetic validation, and a TypeScript evidence explorer. |
| [Leveraged ETF Risk Lab](https://github.com/asoracca/leveraged-etf-risk-lab) | Portfolio accounting, risk attribution, and daily-reset leverage, with hand-calculated fixtures and reproducible offline reports. |

## How I build

- **Make results reproducible:** preserve configurations, seeds, inputs, and evidence.
- **Test the failure cases:** invalid plans, interrupted runs, timing errors, and misleading estimates.
- **Keep claims tied to measurements:** distinguish synthetic examples, historical research, and live-model evaluations.

**Tools:** Python · C++ · TypeScript · React / Next.js · SQL · SQLite · PostgreSQL · NumPy · SciPy · pandas
