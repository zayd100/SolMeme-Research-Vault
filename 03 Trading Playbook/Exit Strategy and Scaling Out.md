---
tags: [trading, exits]
status: framework
created: 2026-10-09
---

# Exit Strategy and Scaling Out
**Write it before entry.**

## Ladder example (adjust to your style)
- At **2x**: sell enough to recover principal (free roll)
- At **5x**: sell ~25% of remainder
- At **10x+**: sell ~25% more; keep a small "moonbag"
- Time stop: no momentum in X minutes/hours -> exit

## Invalidation
- Dev sells, bundle wallets move, top holders dump, volume dies
- Can't set reliable stops on illiquid tokens (slippage) -> **size small instead**

## Practicals
- Account for graduation/migration volatility ([[Pump.fun]])
- Sell into strength, not into the dump
- Partial exits beat "all or nothing"

## After
- Move profit to the vault. See [[The Big Win Protocol]]
- Log result in [[Trade Journal]]

Related: [[Position Sizing and Bankroll]]
