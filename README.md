# SupplyChain Sentinel — AI Package Incident Response Lab

A single-file, interactive tabletop simulator for AI tooling supply-chain incidents (inspired by the LiteLLM 1.82.7–1.82.8 malicious PyPI releases).

## What you can do
- Configure scenario presets (AI proxy compromise, CI toolchain compromise, typosquatting, transitive dependency swap)
- Advance simulated time and correlate detection signals (EDR, egress, DNS, advisory)
- Execute response actions (freeze deploys, rollback, isolate, rotate secrets, preserve evidence)
- Plan and track secret rotation completeness
- Generate a postmortem draft locally (no API calls)
- Export a JSON incident report
- Share scenario configuration via a copyable URL hash

## Live demo
Once GitHub Pages is enabled:
- https://joho777.github.io/ai-app-2026-03-25/

## Source inspiration
- The Hacker News: https://thehackernews.com/2026/03/teampcp-backdoors-litellm-versions.html

## Notes
This project is an educational simulation. It does not download packages, execute code, or send data to external endpoints.
