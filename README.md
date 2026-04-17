# Spearhead API Data

This repository contains a single data source for Warhammer Age of Sigmar Spearhead armies.

## Files

- `spearheads.json`: all spearhead entries and their structured data.

## Data Model (high level)

Each spearhead object includes fields such as:

- `id`, `name`, `faction`
- `generalId`
- `unitComposition`
- `battleTraits`
- `regimentAbilities`
- `enhancements`
- `version`, `isLatest`
- `totalUnits`, `totalModels`

## Notes

- This repository is intentionally minimal for publication.
- Local audit scripts and generated reports are kept out of version control.
