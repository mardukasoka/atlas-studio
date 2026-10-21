# Indigo six-workstream integration register (review draft)

Status: **reference-only; not a deployed agent integration**. Updated 2026-10-22. Source URLs are repository anchors, not assertions of working interfaces.

| WS | Canonical source | Proposed integration | Evidence / gate |
|---|---|---|---|
| 1 Scientific harness | https://github.com/mardukasoka/harness2/pull/1 | Scientific tool-call envelope and Rosetta result adapter | PR open; mock tests; no Rosetta execution; require provenance and integration validation |
| 2 Chess Atlas | https://github.com/mardukasoka/chess-atlas | Shared 5D game-state graph and game-specific rules | Abacus reported Jest baseline passing; mobile/browser and 5D adapter acceptance unverified |
| 3 Uranometria | https://github.com/mardukasoka/uranometria/pull/6 | Coordinate math used by cosmic map views | PR open; Abacus reports six passing Node tests; downstream callers and mobile views need regression checks |
| 4 AI Evolution Observatory | Existing Observatory location **not yet established** | Curated research references and evidence classes; no new Observatory application | Resolve canonical owner before write; source register below is provisional |
| 5 Indigo Business Registry | Existing ClickUp supplier registry; do not duplicate | Partnerships, supplier research and verified commercial terms | Confirm registry location and verify each offer from official program terms |
| 6 Integration governance | https://github.com/mardukasoka/atlas-studio | Project map, canonical references, status and provenance | This document is the initial dependency map; not a runtime bridge |

## Dependencies and handoff

Scientific agents → **harness2** typed calls / evidence → reviewed reference entries → **Atlas Studio** project graph; simulation outputs may be *linked* to **Uranometria** only after coordinate frame, units, epoch, and uncertainty are recorded. **Chess Atlas** retains its own game rules and shared 5D engine; no parallel state engine. ClickUp is the operational task registry, not a replacement scientific database.

## WS4 provisional scientific references (not installation claims)

| Source | Role | Validation before adoption |
|---|---|---|
| https://github.com/PolymathicAI/agent-rosetta | LLM orchestration of protein-design tools | Rosetta license, tool boundaries, cost, external evaluation |
| https://github.com/mardukasoka/the_well | Scientific simulation dataset loaders / benchmarks | Dataset-specific terms, sampling, storage, physical units |
| https://github.com/PolymathicAI/walrus | Learned continuum dynamics | Weights, training/evaluation splits, domain transfer |
| https://github.com/PolymathicAI/AstroCLIP | Galaxy images and spectra | Survey provenance, license, model validation |
| https://github.com/PolymathicAI/AION | Astronomy foundation model | Publication, weights, input modalities, costs |
| https://github.com/mardukasoka/awesome-world-model-evolution | Curated research index | Source-level provenance; distinguish generative models from scientific simulators |
| https://github.com/mardukasoka/open-oasis | Action-conditioned generative environment | Not a calibrated physical simulator |
| https://github.com/mardukasoka/ChatDev | Multi-agent software-team framework | No claim of autonomous reliability |

## WS5 provisional partner research queue (NOT verified affiliate offers)

| Organization | Role to investigate | Unverified fields |
|---|---|---|
| Xometry | Manufacturing marketplace | Referral program, Australia eligibility, pricing |
| Protolabs | Rapid manufacturing | Partner program, geography, terms |
| Zoo | CAD automation | API access, commercial integration terms |
| CloudNC | CNC automation | Developer access, partnerships |
| Automated Solutions Australia | Robotic machine tending | Integrator coverage, quote, safety |
| Pamba | AI video/marketing | MCP/API terms, referral eligibility |

**Rule:** No affiliate program is marked confirmed without a current official program URL, eligibility and date checked. No company has been contacted.

## Acceptance gates

1. All code changes in feature branches with PR links, exact commits, tests, failure cases and no direct production deploy.
2. WS1: malformed inputs, evidence file existence/checksums, numeric score validation, mock/real provenance separation, actual Rosetta integration before scientific production use.
3. WS2: test one real mobile browser interaction and one timeline branch/undo across game-specific rules.
4. WS3: check numerical accuracy at poles, RA wrap, sub-mas angles and verify UI callers handle thrown errors.
5. WS4: canonical Observatory repo resolved; sources deduplicated; evidence class, licenses and compute recorded.
6. WS5: canonical ClickUp registry resolved; at least three official commercial-program terms verified before marking commercial research complete.
7. WS6: review PRs, close security gaps, and retain unmerged changes until human approval.

## Remaining blockers

- No independent Rosetta runtime integration test or full scientific harness regression.
- No browser-based Chess Atlas mobile regression.
- No verified canonical Observatory repository or ClickUp registry ID in this artifact.
- No verified affiliate/partner terms.
- No PR merged or deployed as part of this integration register.
