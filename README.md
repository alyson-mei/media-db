# Media Database

A personal knowledge database for tracking all media I've ever consumed. This project started as a way to remember and organize the artists whose music I've listened to over the years.

## Structure

The database uses a simple, unopinionated approach:
- **Tree-based directory structure** for organization
- **Markdown files** (`.md`) in the leaves for notes and metadata
- Alternative formats like `.csv`, `.yaml`, or `.json` can be used where appropriate
- No external apps or databases required

### Tradeoffs
- Lacks general graph structure (items can't have multiple parents easily)
- No built-in querying capabilities

## Future Plans

**Note:** This is an experimental project and the structure is subject to change as I discover what works best.

### Planned additions:
- Expand coverage to other media categories
- Add `.md` (or `.csv`/`.yaml`/`.json`) files to the leaves with detailed metadata and notes
- Develop Python scripts for database integrations

#### Possible integration options:
- Automatic creation and update of SQL database based on parsed data
- Introducing custom dependencies between entries (enabling DAG/graph structure)
- LLM agents + search engine integration for intelligent querying and interaction with the database
