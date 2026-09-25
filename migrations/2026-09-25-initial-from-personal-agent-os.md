# Initial Elder Scrolls knowledge migration

Date: 2026-09-25

## Source
- Repository: `unwit1/personal-agent-os`
- Source root: `knowledge/libraries/elder-scrolls/`
- Source commit pinned for this batch: `a84d5adf3f7e21a89943c023620a81361cc2f85c`
- Migration mode: non-destructive copy
- Destination repository: `unwit1/knowledge-tes`

## Files copied in batch 1

| Source path | Destination path | Source blob SHA |
|---|---|---|
| `knowledge/libraries/elder-scrolls/books/README.md` | `books/README.md` | `f5ac118ce96f750a3632735e265d94bd7b0167af` |
| `knowledge/libraries/elder-scrolls/books/catalog.jsonl` | `books/catalog.jsonl` | `b0908eb176942d4aa5951391bd14875755d016d5` |
| `knowledge/libraries/elder-scrolls/books/works/tes.work.fundaments-of-alchemy.json` | `books/works/tes.work.fundaments-of-alchemy.json` | `fc4584f8edfb2e65209ca34932f43876109d281e` |
| `knowledge/libraries/elder-scrolls/books/works/tes.work.gallus-encoded-journal.json` | `books/works/tes.work.gallus-encoded-journal.json` | `b7b67f9c75aa6b8be86fa210e1d9e096a373dd1d` |
| `knowledge/libraries/elder-scrolls/topics/README.md` | `topics/README.md` | `4c777588762b8d0863fd004ab819a924581a3617` |
| `knowledge/libraries/elder-scrolls/topics/locations/README.md` | `topics/locations/README.md` | `5b104896ed2ec06905674cae88b58a16b624be61` |
| `knowledge/libraries/elder-scrolls/topics/locations/apocrypha.md` | `topics/locations/apocrypha.md` | `4e4da284456774fbe3c0bd88645934062a1dbbed` |
| `knowledge/libraries/elder-scrolls/topics/locations/necrom.md` | `topics/locations/necrom.md` | `ad55650ee52cda2be3ef28a88eceb996278fa631` |
| `knowledge/libraries/elder-scrolls/topics/locations/telvanni-peninsula.md` | `topics/locations/telvanni-peninsula.md` | `9fccdb814a08ae1b54daa1b9f570bded731a3ed1` |
| `knowledge/libraries/elder-scrolls/topics/deities-and-spirits/README.md` | `topics/deities-and-spirits/README.md` | `a807c71dfab62f98a3f790a5043b9b0eece4da8b` |
| `knowledge/libraries/elder-scrolls/topics/deities-and-spirits/tribunal.md` | `topics/deities-and-spirits/tribunal.md` | `90eec77dcd4b2632724c114e349277412b7742b7` |
| `knowledge/libraries/elder-scrolls/developer-texts/README.md` | `developer-texts/README.md` | `bf8c4cdcd8a8757fef21d0f1c5aabc50f4f2af84` |
| `knowledge/libraries/elder-scrolls/developer-texts/catalog/pantheon-design-document.md` | `developer-texts/catalog/pantheon-design-document.md` | `99c95e98d9f04373bb84915cb65b8cf805663472` |
| `knowledge/libraries/elder-scrolls/sources/README.md` | `sources/README.md` | `a2d308f5c5ed32efc0746a29e61c954628945097` |

## Validation
The copied content was written without modifying the source files. Where checked after writing, destination blob SHAs match the source blob SHAs exactly.

## Known follow-up work
- Migrate referenced source corpora under `sources/` so relative links resolve inside this repository.
- Migrate the remaining topic categories, claims/contradiction indexes, dialogue, game-specific records, entities, indexes, developer-text catalog, and continuity-separated mod lore.
- Normalize machine-readable path fields that still contain the legacy `knowledge/libraries/elder-scrolls/` prefix, but preserve the original path as migration provenance.
- Search other Agent OS and Skyrim-related locations for TES lore that exists outside the current Elder Scrolls library and reconcile it here.
- Do not delete or deprecate the source library until record counts, hashes, links, and retrieval behavior have been validated.
