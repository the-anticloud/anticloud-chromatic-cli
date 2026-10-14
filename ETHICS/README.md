# Ethics — CHROMATIC_CLI

**Project:** CHROMATIC_CLI  
**Category:** DESIGN_TOOLS  
**Upstream:** https://github.com/chromaui/chromatic-cli  
**Pinned commit:** `1949e36dc886796caafbb459c3aadae43268c1d0`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `eb3757a91dd9285f5bf80895da22b38a3577c97c328681c98a6e13a604515634`  
**Date:** October 2026

## Position

CHROMATIC_CLI is packaged for offline deployment with a verifiable audit trail. The
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
