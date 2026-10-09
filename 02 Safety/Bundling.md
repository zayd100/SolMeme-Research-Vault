---
tags: [safety, bundling, pumpfun]
aliases: [bundle, bundled launch, bundles]
status: verified-partial
created: 2026-10-09
---

# Bundling
**One actor buys a big chunk of supply through many wallets in the *same block/slot* as the token's creation.** Looks like many holders; is really one.

## Why it hurts you
- Bundled supply can **exit in a single slot** -> instant cliff.
- Authority/LP checks can all pass and the token can *still* be bundled. (Bundling passes the naive rug checklist.)

## Bundled vs sniper vs organic
| Type | Timing | Who | Risk |
|---|---|---|---|
| Bundled | same slot as creation, atomic | dev + pre-funded wallets | coordinated, single-slot dump |
| Sniper | first seconds/blocks, separate txs | bots/fast traders | smeared selling |
| Organic | trickles in over minutes | varied buyers w/ history | normal |

## Thresholds (heuristic, not law)
- **<5% bundled** = background noise, endemic on Pump.fun
- Higher = scrutinize. Raiden's guide ranks risk by share; exact bands vary by tool.

## Not every bundle is a scam
- Some creators bundle **defensively** to block snipers and give their community a fair start. Heavy, hidden, funded-from-one-source bundling is the warning sign.

## What to do
1. Run [[Bundle Detection Checklist]]
2. If you already hold: confirm bundled vs sniped, **size down**, set exit. See [[Exit Strategy and Scaling Out]]
3. Log it. See [[Trade Journal]]

Related: [[Snipers and Bots]] | [[Rug Pull Patterns]] | [[Venue Defenses]] | [[Case Study - 20 to 350 and Back]]
