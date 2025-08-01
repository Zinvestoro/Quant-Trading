
# Comprehensive Comparison of 100 Quantitative Trading Strategies

**Hardware target:** Intel i7‑14700KF · 32 GB RAM · NVIDIA RTX 4070 (12 GB VRAM) · 2 TB SSD  
**Assumed backtest window:** 3 years (consistent period across strategies)

## What’s included
- 100 strategies across 10 families (10 each).
- Columns: Performance (Sharpe, Sortino, Max DD, Annual Return), Method, Asset class, Frequency, Resource usage (CPU/GPU/RAM/Storage), Tech dependencies, Risk management, Scalability.

## Caveats
- Metrics are indicative ranges. Replace with your own backtests (same data/same costs).
- Resource footprints reflect your workstation and typical data sizes.

## Reproduce
Run the generator to rebuild the CSV/HTML/MD deterministically (seeded).

## References (indicative)
- Time‑Series Momentum (Moskowitz, Ooi, Pedersen) – diversified futures, high Sharpe in literature.
- CFM: “Trend Following – a Persistent Market Anomaly” – long‑run Sharpe ≈ 0.7.
- Earnings announcement strategies (Lamont & Frazzini et al.) – strong risk‑adjusted returns in research.
- Daniel, Hodrick & Lu: “The Carry Trade: Risks and Drawdowns” – FX carry Sharpe ~0.5–1.0, tail risks.
- Quantpedia summaries: Time‑Series Momentum (~Sharpe 1.3), Volatility Risk Premium (~Sharpe 1.1), Risk Parity comparisons.

Generated on 2025-08-01.
