# Ethics — GOGS_PRIOR_DOCS

**Project:** GOGS_PRIOR_DOCS  
**Category:** SOFTWARE_DEVELOPMENT  
**Upstream:** https://github.com/gogs/gogs  
**Pinned commit:** `dbbd717e923694c36f41b0360515b4374bbe6ee0`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `c1f4e04743c2f9f90c3307fa360834b8d7603b989113f873ed7f7201ae3d1932`  
**Date:** October 2026

## Position

GOGS_PRIOR_DOCS is packaged for offline deployment with a verifiable audit trail. The
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
