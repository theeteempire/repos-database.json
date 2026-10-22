# PS5 Repository Database

This repository stores the curated PS5 projects tracked alongside the [Repository Catalog](https://github.com/theeteempire/repository-catalog).

- Database: [json/repos-database.json](json/repos-database.json)
- The database distinguishes projects by canonical repository URL and records verified release links when available.
- Direct payload assets are separately listed in the catalog's `curated_payloads.json` only when a direct ELF release asset was verified.
- Non-GitHub resources and entries with unverified canonical URLs are recorded separately and are not treated as verified GitHub repositories.
- Firmware compatibility is not inferred from inclusion in this database.
