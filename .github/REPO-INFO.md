---
# Canonical repo classification — see docs/REPO-CLASSIFICATION.md.
# This front-matter is the source of truth; GitHub topics mirror from it.
content: code
domain: product
exposure: customer-facing
layer: shared-lib
lifecycle: inactive
---

# rebar3_hex

> A fork/vendored copy of the upstream `rebar3_hex` Rebar3 plugin — the Erlang tooling for publishing packages and docs to Hex (hex.pm).

## What it contains
Erlang plugin providing Rebar3 providers for Hex operations: `publish`, `cut`, `build`, `search`, `retire`, plus user/key/owner/organization management (`src/rebar3_hex_*.erl`). Standard rebar3 plugin layout (`rebar.config`, `src/*.app.src`) with Common Test suites under `test/` and GitHub Actions CI. README/badges point at the upstream erlef/rebar3_hex project (mirrored into the Sonetel org).

## Ownership
- **Code owner:** Venkata Kuna (Venkatakuna)

## Notes
Keep temporarily. Remove with MIM decommission
