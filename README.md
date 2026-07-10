# ZQM Public Tools

Curated, sanitized Windows security tooling surfaced for public review.

## Included tooling

- `scripts/` — reviewed PowerShell utilities suitable for endpoint visibility
- `README.md` — how each tool maps to CIS/Windows security controls
- `integration.md` — deploy into SOC/MSP environments

## What’s excluded

- Internal node-specific configuration
- LAN hostnames / internal IP space
- Bug-bounty dogfood inventory
- Keys, tokens, and credential material

## Relationship to upstream

This repo exists so public reviewers can evaluate methodology without exposing operational internals. Full commercial product lives at `ZQM-Computing/zqm-attestation-toolkit`.

License

- Public samples: MIT
- Upstream commercial terms: see `ZQM-Computing/zqm-attestation-toolkit` COMMERCIAL.md
