# Spearhead Data (AoS)

Structured JSON data for Warhammer Age of Sigmar Spearhead armies.

## What is in this repo

- [spearheads.json](spearheads.json): Spearhead lists, traits, regiment abilities, enhancements, and unit composition.
- [units.json](units.json): unit profiles (stats, weapons, abilities, keywords).

## Data structure

### spearheads.json

Each spearhead entry contains:

- id, name, faction
- generalId
- unitComposition
- battleTraits
- regimentAbilities
- enhancements
- version, isLatest
- totalUnits, totalModels

Each unit in unitComposition includes:

- unitId
- count
- unitLink (relative link to units.json using unitId)

### units.json

Each unit entry contains:

- id, name
- keywords
- stats
- weapons (melee/ranged)
- abilities

## Goal

This project provides a clean, machine-readable dataset for tooling, experimentation, and hobby-side integrations.

## Legal and ownership notice

- I am not the creator or owner of the original Warhammer rules/lore content.
- Warhammer, Age of Sigmar, Spearhead, and related names/concepts are the intellectual property of Games Workshop.
- This repository is an unofficial fan data project and is not affiliated with, endorsed by, or sponsored by Games Workshop.
- If you are a rights holder and want content adjusted or removed, open an issue and it will be handled promptly.
