# Students — GOGS_PRIOR_DOCS

**Project:** GOGS_PRIOR_DOCS  
**Category:** SOFTWARE_DEVELOPMENT  
**Upstream:** https://github.com/gogs/gogs  
**Pinned commit:** `dbbd717e923694c36f41b0360515b4374bbe6ee0`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `c1f4e04743c2f9f90c3307fa360834b8d7603b989113f873ed7f7201ae3d1932`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `dbbd717e923694c36f41b0360515b4374bbe6ee0`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `c1f4e04743c2f9f90c3307fa360834b8d7603b989113f873ed7f7201ae3d1932`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
