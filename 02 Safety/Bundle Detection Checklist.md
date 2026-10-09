---
tags: [safety, checklist, bundling]
status: verified-partial
created: 2026-10-09
---

# Bundle Detection Checklist (60 seconds)
Mnemonic: **"SLOT"**
- **S**ame-block buys at creation? (3+ buys in block 1-2 = almost certainly bundled)
- **L**arge back-to-back buys (2%+ each)?
- **O**rigin of funds - wallets funded from the same source/just before launch?
- **T**ools say so? (GMGN / RugCheck bundled+sniper panels / Raiden / Bubblemaps cluster view)

## Steps
1. Open token on **GMGN** -> early buyers / bundle flag.
2. **RugCheck**: read *bundled* and *sniper* supply separately.
3. **Solscan**: sort earliest txs; identical timestamps/slots = bundle. Cross-check buyer wallets.
4. Visual cluster map (e.g., Bubblemaps - general knowledge, verify current).
5. Compute bundled %. <5% noise; above that, scale down or skip.
6. Check **dev behavior**: dev buying immediately? dev sold?

## Green flags
- Buys trickle in over minutes, varied sizes, buyers with history
- Top holders unconnected

## Red flags
- Wallets with zero history all buying together
- Top-10 concentrated
- Funding trail goes to one wallet

## Remember
- Pass != safe. See [[Rug Pull Patterns]], then [[Pre-Trade Checklist]].

Tools list: [[Tools and Trackers]]
