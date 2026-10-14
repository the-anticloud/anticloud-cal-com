# Educators — CAL_COM

**Project:** CAL_COM  
**Category:** MARKETING_TOOLS  
**Upstream:** https://github.com/calcom/cal.com  
**Pinned commit:** `54343aa685ae8f33159d2f485ec4a57bad5c574a`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `c549c7e8cc496320b19420b29e6f492b5c6b50ce49532c01af185a94d8090734`  
**Date:** October 2026

## Teaching with CAL_COM

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `c549c7e8cc496320b19420b29e6f492b5c6b50ce49532c01af185a94d8090734` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
