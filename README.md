# Elder Scrolls Knowledge Library

Canonical, GitHub-browsable home for Elder Scrolls lore material used by writing agents and Personal Agent OS.

## Browse
- `sources/` — provenance/source-specific material and indexes
- `games/` — game-specific lore, books, dialogue, quests, and extracted records
- `books/` — normalized book catalog/index
- `dialogue/` — normalized dialogue catalog/index
- `developer-texts/` — developer and obscure texts
- `mods/continuities/` — mod-specific continuities kept separate from Bethesda/ZeniMax continuity
- `entities/` — structured people, places, factions, concepts, artifacts
- `claims/` — evidence-backed claims and contradiction tracking
- `topics/` — human-browsable lore dossiers
- `indexes/` — generated browse/search indexes
- `migrations/` — migration manifests and validation records

## Provenance rule
Every imported item should retain its source, source URL or game/plugin origin when available, retrieval/extraction date, continuity, and confidence/status. Mod lore must not silently merge into Bethesda/ZeniMax continuity.

## Migration
Initial material is being migrated from `unwit1/personal-agent-os/knowledge/libraries/elder-scrolls/`. Stable work IDs and source-specific witness/provenance data are preserved. Source files remain untouched until the new repository has been validated.
