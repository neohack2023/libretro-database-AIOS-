# AIOS SNES Derived Corpus

This namespace contains AIOS/SNES-derived indexes and receipts built from the upstream Libretro database while leaving upstream-owned `cht/`, `dat/`, `metadat/`, and other source material untouched.

## Provenance

Preferred controlled mirror: `neohack2023/libretro-database-AIOS-`

Original upstream: `libretro/libretro-database`

Pinned source revision for this seed: `ff28a5e5bca21f7ae2001602d2e0585cf66c9b5c`

All derived records must retain both mirror and original-upstream provenance.

## Evidence rule

Derived cheat records are historical reconnaissance candidates, not ROM facts. A record can be promoted into ROM-local knowledge only after ROM fingerprint matching plus static inspection and runtime validation.

## Layout

```text
aios/snes/
├── README.md
├── CHANGELOG.md
├── manifests/
│   └── corpus-manifest.json
├── indexes/
│   ├── decoded-cheats.seed.jsonl
│   └── behavior-clusters.seed.jsonl
└── receipts/
    └── seed-harvest-receipt.json
```

## Seed slice

The first bounded derived slice contains 16 records from two actual SNES Game Genie files:

- `Super Bomberman 2 (USA, Europe) (Game Genie).cht`
- `Mega Man X (USA, Europe) (Game Genie).cht`

It yields three same-address clusters and deliberately includes malformed and multi-code historical forms so downstream tooling cannot assume clean input.

This seed is not the full Libretro SNES corpus. Future full-corpus generation should be reproducible from the pinned source revision using the Cheat Intelligence Harvester in `neohack2023/snes-rom-toolkit`.
