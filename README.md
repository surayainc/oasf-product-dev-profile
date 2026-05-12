# oasf-product-dev-profile

OASF / AGNTCY extension package for product-development engineering observations.

MIT-licensed. Companion to the public schema documentation at `suraya.ai/schema`. Mirrors the actual brain schema as currently shipped in `surayainc/suraya-brain`, presented as a candidate **product-dev profile sub-schema** for AGNTCY's OASF.

> **Sandbox note.** Lives in the suraya meta repo at `apps/oasf-product-dev-profile/` until `surayainc/oasf-product-dev-profile` is created (OQ-13). On creation, this directory moves to that repo.

## What's in here

- `schema/observation.schema.json` — JSON Schema v0.6 for a single observation record
- `schema/memory-node.schema.json` — JSON Schema for a clustered memory node
- `schema/reinforcement-axes.schema.json` — the six-axis weighting model
- `examples/` — sample observation records covering each type
- `CHANGELOG.md` — every shape change with rationale

## Versioning

Semver from day 1. Current major is v0 (pre-1.0); breaking changes are explicitly possible while v0.6 iterates. Each version's schema is immutable — corrections ship as new versions.

## RFC plan

After 30 days of public iteration on v0.6 (target: 2026-06-22), draft a formal RFC for an OASF product-dev profile sub-schema and submit it through the AGNTCY working-group process. The extension package keeps shipping as the MIT-licensed reference implementation regardless of whether the RFC is accepted as-is.

## Comment

File an issue at `surayainc/oasf-product-dev-profile` (once the repo exists) tagged `schema-v0.6`. Threaded discussion stays public; resolution lands in the next CHANGELOG entry.
