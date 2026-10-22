# PS5 Repository Database

This repository stores a synchronized database of the PS5 projects tracked alongside the [Repository Catalog](https://github.com/theeteempire/repository-catalog).

- Database: [json/repos-database.json](json/repos-database.json)
- `repos` includes every repository in the catalog's `curated_repositories.json`, plus tracked non-GitHub projects such as AnyPad PS5 from Codeberg.
- `payloads` mirrors the verified entries in the catalog's `curated_payloads.json`, preserving direct asset URLs, source links, versions, checksums, and IDs where available.
- `resources` records PS5 reference pages from the ChatGPT PS5 project library.
- `unresolved` records mentioned projects whose canonical source URL is not yet verified; these are not fabricated or treated as confirmed repositories.
- Similar project names are kept separate by canonical source URL/owner.
- Firmware compatibility is not inferred from inclusion in this database.
