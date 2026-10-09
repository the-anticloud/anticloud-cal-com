# Students — CAL_COM

**Project:** CAL_COM  
**Category:** MARKETING_TOOLS  
**Upstream:** https://github.com/calcom/cal.com  
**Pinned commit:** `54343aa685ae8f33159d2f485ec4a57bad5c574a`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `c549c7e8cc496320b19420b29e6f492b5c6b50ce49532c01af185a94d8090734`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `54343aa685ae8f33159d2f485ec4a57bad5c574a`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `c549c7e8cc496320b19420b29e6f492b5c6b50ce49532c01af185a94d8090734`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
