# AIOS SNES Derived Changelog

Track meaningful changes to `aios/snes/` here. Upstream Libretro history remains in upstream Git history; this file records only the AIOS-derived layer.

## Unreleased

### Added
- Initial `aios/snes/` derived-corpus namespace.
- Seed manifest pinned to Libretro revision `ff28a5e5bca21f7ae2001602d2e0585cf66c9b5c`.
- First 16 normalized historical cheat records from Super Bomberman 2 and Mega Man X.
- Three same-address behavior clusters for Bomberman bomb count, Bomberman power, and Mega Man X starting lives.
- Seed harvest receipt with output digest and explicit limitations.

### Changed
- None. Upstream-owned Libretro source directories remain untouched.

### Notes
- All derived entries remain `historical_unverified` until ROM fingerprint matching plus static/runtime validation.
- Future changes to this derived namespace must update this changelog in the same change set.
