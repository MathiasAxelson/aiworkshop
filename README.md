# aiworkshop

AI Workshop - OpenEdge ABL Project (from ProjectGengar, Step-16 branch).

OpenEdge 12.8 ABL sample project built around the sports2000 database, demonstrating the Business Entity pattern:

- `src/business/` - `CustomerEntity` (inherits `OpenEdge.BusinessLogic.BusinessEntity`), `EntityFactory` (singleton), `CustomerDataset.i` (temp-table + ProDataset definition)
- `src/*.w` - AppBuilder windows consuming entities via datasets
- `doc/business-entity-pattern.md` - architecture pattern documentation for refactoring legacy code
- `dump/sports2000-schema.txt` - summarized database schema
- `.windsurf/` - AI assistant rules and workflows

Requires an OpenEdge 12.8 runtime (`DLC`) and a sports2000 database.
