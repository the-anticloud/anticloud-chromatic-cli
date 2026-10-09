# Students — CHROMATIC_CLI

**Project:** CHROMATIC_CLI  
**Category:** DESIGN_TOOLS  
**Upstream:** https://github.com/chromaui/chromatic-cli  
**Pinned commit:** `1949e36dc886796caafbb459c3aadae43268c1d0`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `eb3757a91dd9285f5bf80895da22b38a3577c97c328681c98a6e13a604515634`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `1949e36dc886796caafbb459c3aadae43268c1d0`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `eb3757a91dd9285f5bf80895da22b38a3577c97c328681c98a6e13a604515634`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
