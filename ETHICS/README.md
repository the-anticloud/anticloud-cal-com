# Ethics — CAL_COM

**Project:** CAL_COM  
**Category:** MARKETING_TOOLS  
**Upstream:** https://github.com/calcom/cal.com  
**Pinned commit:** `54343aa685ae8f33159d2f485ec4a57bad5c574a`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `c549c7e8cc496320b19420b29e6f492b5c6b50ce49532c01af185a94d8090734`  
**Date:** October 2026

## Position

CAL_COM is packaged for offline deployment with a verifiable audit trail. The
ethical questions this raises are answered by making the system's behaviour
checkable rather than by policy statements.

## The four commitments

1. **No hidden egress.** The deployment has no external API dependency; this is
   testable by running it with the network disconnected.
2. **Attributable output.** Every artifact is recorded in a hash chain, so what
   the system produced can be reconstructed.
3. **Operator control.** The institution owns the hardware and the keys.
4. **Refusal to overclaim.** Where a certification is not held, the project says
   so rather than implying it.

## Dual use

This project is packaged for civilian and public-sector deployment. Where an
upstream has dual-use characteristics, the licence gate and the reference-only
marking in `BENCH.json` record that.
