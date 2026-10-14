# Educators — GOGS_PRIOR_DOCS

**Project:** GOGS_PRIOR_DOCS  
**Category:** SOFTWARE_DEVELOPMENT  
**Upstream:** https://github.com/gogs/gogs  
**Pinned commit:** `dbbd717e923694c36f41b0360515b4374bbe6ee0`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `c1f4e04743c2f9f90c3307fa360834b8d7603b989113f873ed7f7201ae3d1932`  
**Date:** October 2026

## Teaching with GOGS_PRIOR_DOCS

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `c1f4e04743c2f9f90c3307fa360834b8d7603b989113f873ed7f7201ae3d1932` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
