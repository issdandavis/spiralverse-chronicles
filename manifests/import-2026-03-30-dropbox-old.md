# Import Manifest — 2026-03-30

Initial Avalon lore/training import staged from:

`C:\Users\issda\Dropbox (Old)\SCBE\backup-2026-03-30`

## Imported Files

### Manuscript and chapter corpus

- `training\runs\multi_agent_offload\20260321T201547Z\bundles\The-Avalon-Codex-Complete-Unified.txt-The-Avalon-Codex-Complete-Unified-f8a22026\payload\# The Avalon Codex Complete Unified.txt`
- `training\runs\multi_agent_offload\20260321T201547Z\bundles\Revised-Chapters-with-Ancient-Tra.txt-Revised-Chapters-with-Ancient-Tra-27d85bfe\payload\# Revised Chapters with Ancient Tra.txt`
- `training\runs\multi_agent_offload\20260321T201547Z\bundles\The-Avalon-Codex-Complete-Unified.3.txt-The-Avalon-Codex-Complete-Unifi-7a4a274a\payload\# The Avalon Codex Complete Unified.3.txt`

### Lore session training data

- `training-data\lore_sessions\characters_and_world.jsonl`
- `training-data\lore_sessions\everweave_canon.jsonl`
- `training-data\lore_sessions\everweave_rp_sessions.jsonl`
- `training-data\lore_sessions\thalorion_compendium.jsonl`
- `training-data\lore_sessions\world_deep_lore.jsonl`

### Articles

- `articles\01_the_spiralverse_introduction.md`
- `articles\02_izack_thorne_dimensional_architect.md`
- `articles\03_aria_ravencrest_mother_of_avalon.md`
- `articles\04_polly_the_raven_who_remembers.md`
- `articles\05_six_sacred_tongues.md`
- `articles\06_collaborative_magic_strongest_edge.md`
- `articles\07_hyperbolic_geometry_ai_safety.md`
- `articles\08_14_layer_security_pipeline.md`
- `articles\09_post_quantum_cryptography_scbe.md`
- `articles\10_energy_aware_compute_governor.md`
- `articles\11_honest_benchmark_34_percent.md`
- `articles\12_trichromatic_forgery_resistance.md`
- `articles\devto_seo_post.md`

## Duplicate Variants Not Imported

These files existed in the source backup but were byte-identical to the imported canonical files:

- `training\runs\multi_agent_offload\20260321T201547Z\bundles\The-Avalon-Codex-Complete-Unified.2.txt-The-Avalon-Codex-Complete-Unifi-af2a8bb5\payload\# The Avalon Codex Complete Unified.2.txt`
- `training\runs\multi_agent_offload\20260321T201547Z\bundles\Revised-Chapters-with-Ancient-Tra-Copy.txt-Revised-Chapters-with-Ancien-9214d0b2\payload\# Revised Chapters with Ancient Tra - Copy.txt`

## Import Rationale

- Prefer stable restore sources over a currently shifting cloud root.
- Preserve one canonical copy for each identical manuscript/chapter body.
- Bring the training JSONL lore sessions into the same repo as the supporting article and manuscript corpus so downstream training jobs have one lore home.
