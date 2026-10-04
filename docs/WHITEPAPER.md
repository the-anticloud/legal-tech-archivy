# Technical Whitepaper — ARCHIVY

**Model:** PAX L5 Narrow L2 General 27B
**Company:** Anticloud FZ LLE
**Upstream:** https://github.com/archivy/archivy
**Category:** LEGAL_TECH

## Abstract

This whitepaper describes the Anticloud integration of `ARCHIVY` (Self-hosted knowledge base for legal research)
with PAX L5 Narrow L2 General 27B, the offline-first AI model developed by Anticloud FZ LLE.
The integration produces a zero-cloud, single-binary deployment that exceeds upstream
capabilities while eliminating all third-party API dependencies.

## Technical Improvements

1. PAX L5 Narrow L2 General 27B local contract analysis and clause extraction — air-gapped
2. AIOSS tamper-evident document version chain (eDiscovery-ready)
3. AES-256 encryption for all client documents and privileged communications
4. Single-binary legal tool for secure client networks
5. Zero-cloud: all NLP analysis and search run locally
6. GPU/CPU equalizer: large document analysis on GPU or CPU
7. Zero-telemetry: removes all usage reporting
8. Open format: exports to LEDES billing and EDGAR submission formats

## Architecture

See TECHNICAL/01_Architecture.md for the full architectural description.

## Benchmarks

See OFFICIAL_BENCHMARKS/04_PAX_Results.md for performance targets and measured results.