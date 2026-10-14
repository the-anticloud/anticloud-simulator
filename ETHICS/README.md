# Ethics — SIMULATOR

**Project:** SIMULATOR  
**Category:** AUTOMOTIVE  
**Upstream:** https://github.com/lgsvl/simulator  
**Pinned commit:** `4c342fd39c5eca6ce6538a144f51d5929812e417`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `46e731c4c836d0e52281316d8ab213004a154831aacafa5dec07e1d1e58daa59`  
**Date:** October 2026

## Position

SIMULATOR is packaged for offline deployment with a verifiable audit trail. The
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
