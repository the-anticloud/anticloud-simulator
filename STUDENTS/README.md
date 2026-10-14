# Students — SIMULATOR

**Project:** SIMULATOR  
**Category:** AUTOMOTIVE  
**Upstream:** https://github.com/lgsvl/simulator  
**Pinned commit:** `4c342fd39c5eca6ce6538a144f51d5929812e417`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `46e731c4c836d0e52281316d8ab213004a154831aacafa5dec07e1d1e58daa59`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `4c342fd39c5eca6ce6538a144f51d5929812e417`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `46e731c4c836d0e52281316d8ab213004a154831aacafa5dec07e1d1e58daa59`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
