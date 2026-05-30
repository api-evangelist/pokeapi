# PokéAPI (pokeapi)
PokéAPI (pokeapi.co) is a free, open-source RESTful and GraphQL API serving comprehensive Pokémon data — including Pokémon species, abilities, moves, items, types, locations, evolution chains, encounters, berries, contests, games, and machines. Built as an educational tool licensed under BSD-3-Clause, it is community-funded via Open Collective and GitHub Sponsors, requires no authentication, and is hosted with a fair-use policy encouraging clients to cache responses locally. The API powers tutorials, fan apps, machine-learning experiments, and game tooling worldwide and consistently serves one billion-plus requests per month.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/pokeapi/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

- Pokémon, Open Source, Open Data, REST, GraphQL, Gaming, Educational, Community

## Timestamps

- **Created:** 2026-05-30
- **Modified:** 2026-05-30

## APIs

### PokéAPI REST API v2
The PokéAPI v2 REST API exposes the canonical Pokémon dataset across 12 resource families and roughly 60 endpoints — Pokémon, Pokémon Species, Abilities, Moves, Types, Items, Berries, Locations, Evolution Chains, Encounters, Games (Generations / Pokédex / Versions / Version Groups), Contests, Machines, and Utility (Languages). Every endpoint is GET-only, returns JSON, and is reachable under https://pokeapi.co/api/v2/ without authentication.

**Human URL:** [https://pokeapi.co/docs/v2](https://pokeapi.co/docs/v2)

#### Tags

- Pokémon, REST, Open Data, Educational, Open Source

#### Properties

- [Documentation](https://pokeapi.co/docs/v2)
- [APIReference](https://pokeapi.co/docs/v2)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/pokeapi/refs/heads/main/openapi/pokeapi-openapi.yml)
- [Fair Use Policy](https://pokeapi.co/docs/v2#fairuse)
- [JavaScript Wrapper (pokeapi-js-wrapper)](https://www.npmjs.com/package/pokeapi-js-wrapper)
- [Node.js Client (pokedex-promise-v2)](https://www.npmjs.com/package/pokedex-promise-v2)
- [Python Wrapper (pokebase)](https://pypi.org/project/pokebase/)
- [Python Wrapper (pokepy)](https://pypi.org/project/pokepy/)
- [Kotlin Multiplatform Client (pokekotlin)](https://github.com/PokeAPI/pokekotlin)

### PokéAPI GraphQL API (Beta)
The PokéAPI GraphQL beta exposes the same Pokémon dataset as the REST API through a single endpoint with field-level selection, joins, and filtering.

**Human URL:** [https://pokeapi.co/docs/graphql](https://pokeapi.co/docs/graphql)

#### Tags

- Pokémon, GraphQL, Open Data, Beta

#### Properties

- [Documentation](https://pokeapi.co/docs/graphql)
- [GraphQL Console](https://beta.pokeapi.co/graphql/console/)
- [GraphQL Endpoint](https://beta.pokeapi.co/graphql/v1beta)

## Common Properties

- [Portal](https://pokeapi.co)
- [GettingStarted](https://pokeapi.co/docs/v2)
- [GitHubOrganization](https://github.com/PokeAPI)
- [GitHubRepository](https://github.com/PokeAPI/pokeapi)
- [License - BSD-3-Clause](https://github.com/PokeAPI/pokeapi/blob/master/LICENSE.md)
- [Open Collective (Donations)](https://opencollective.com/pokeapi)
- [GitHub Sponsors](https://github.com/sponsors/PokeAPI)
- [About](https://pokeapi.co/about)
- [Fair Use Policy](https://pokeapi.co/docs/v2#fairuse)
- [Slack Community](https://pokeapi.slack.com)
- [StackOverflow](https://stackoverflow.com/questions/tagged/pokeapi)
- [Issue Tracker](https://github.com/PokeAPI/pokeapi/issues)
- [Changelog](https://github.com/PokeAPI/pokeapi/releases)
- [Docker Image](https://hub.docker.com/r/pokeapi/pokeapi)
- [Pokémon Sprites](https://github.com/PokeAPI/sprites)
- [Static API Data Dump](https://github.com/PokeAPI/api-data)
- [SpectralRules](https://raw.githubusercontent.com/api-evangelist/pokeapi/refs/heads/main/rules/pokeapi-rules.yml)
- [NaftikoCapability - Pokémon Research](https://raw.githubusercontent.com/api-evangelist/pokeapi/refs/heads/main/capabilities/pokemon-research.yaml)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/pokeapi/refs/heads/main/vocabulary/pokeapi-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| No Authentication | All endpoints are publicly accessible without API keys, tokens, or signup. |
| REST and GraphQL Interfaces | Choose REST under /api/v2 or GraphQL at beta.pokeapi.co/graphql/v1beta — same dataset, two access patterns. |
| Comprehensive Pokémon Dataset | Roughly 60 endpoints covering Pokémon, species, moves, abilities, items, berries, types, locations, encounters, evolution chains, contests, games, and machines. |
| Multi-Generation Coverage | Data spans every released generation of Pokémon games. |
| Multi-Language Localization | Names, flavor text, and descriptions returned in multiple languages. |
| Cacheable Resources | Resources are immutable game data — responses are highly cacheable. |
| Pokémon Sprites Library | Companion PokeAPI/sprites repo provides every artwork, sprite, and shiny variant. |
| Static Data Dump | PokeAPI/api-data publishes a static JSON snapshot for offline use. |
| Self-Hostable | Docker image, Kubernetes manifests, and Firebase scripts let teams run a private mirror. |
| Open Source (BSD-3-Clause) | Source code, sprites, GraphQL schema, and client wrappers are open source. |

## Use Cases

| Name | Description |
|------|-------------|
| Pokédex Apps | Build mobile, web, or desktop Pokédex applications with species, abilities, moves, and sprites. |
| Team Builders and Battle Simulators | Power competitive team-builder, damage-calculator, and battle-simulator tools. |
| Educational Coding Tutorials | Widely used in tutorials teaching REST, GraphQL, caching, and pagination. |
| Machine Learning Datasets | Train and benchmark recommendation, embedding, and image-classification models on Pokémon entities. |
| AI Assistant Demos | Favorite first example for MCP servers, agent demos, and tool-use tutorials. |
| Fan Wikis and Trading Apps | Provide reference data for fan-built wikis and card-collection trackers. |

## Integrations

| Name | Description |
|------|-------------|
| pokeapi-js-wrapper | Browser-friendly async JavaScript wrapper with built-in cache. |
| pokedex-promise-v2 | Node.js / TypeScript promise-based client. |
| pokebase | Python 3 wrapper covering all v2 endpoints. |
| pokepy | Alternative Python wrapper for PokéAPI. |
| pokekotlin | Kotlin Multiplatform client for PokéAPI. |
| PokeAPI Sprites | Companion repo of sprite images served alongside REST responses. |
| Static API Data Dump | GitHub-hosted JSON snapshot for offline / build-time consumption. |
| Model Context Protocol Servers | Numerous community MCP servers wrap PokéAPI as agent tools. |

## Tools

| Name | Description |
|------|-------------|
| [pokeapi-mcp-server (npm)](https://www.npmjs.com/package/pokeapi-mcp-server) | Community MCP server (Asthanaji05) exposing roughly 47 PokéAPI endpoints as MCP tools. |
| [poke-mcp (NaveenBandarage)](https://github.com/naveenbandarage/poke-mcp) | Reference MCP server connecting Claude Desktop, Continue, Cline via SSE. |
| [poke-mcp (ChiragAgg5k)](https://github.com/chiragagg5k/poke-mcp) | MCP server exposing stats, types, abilities, moves, and evolution chains. |
| [pokedex-mcp (hollanddd)](https://github.com/hollanddd/pokedex-mcp) | MCP server exposing Pokémon data, type-effectiveness charts, and encounter locations. |
| [Pokemon-MCP-Server (Sachin-crypto)](https://github.com/Sachin-crypto/Pokemon-MCP-Server) | MCP server with list-popular-Pokémon and tournament-squad-builder tools. |
| [pokemon-mcp-server (indroneelray)](https://github.com/indroneelray/pokemon-mcp-server) | MCP server fetching Pokémon data via the official API. |
| [poke-mcp (kaishin)](https://github.com/kaishin/poke-mcp) | Swift MCP wrapper around PokéAPI. |
| [poke_api_mcp_rb (katakyo)](https://github.com/katakyo/poke_api_mcp_rb) | Ruby MCP server built on mcp_rb for retrieving Pokémon information. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [PokéAPI OpenAPI](openapi/pokeapi-openapi.yml) — 60 GET operations across 11 tags covering Berries, Contests, Encounters, Evolution, Games, Items, Locations, Machines, Moves, Pokémon, and Utility.

### JSON Schema

54 JSON Schema files covering every PokéAPI resource — Pokemon, PokemonSpecies, Ability, Move, Type, Berry, Item, Location, EvolutionChain, Generation, Nature, Stat, and more.

### JSON Structure

54 JSON Structure (json-structure.org) files converted from JSON Schema.

### JSON-LD

- [PokéAPI Context](json-ld/pokeapi-context.jsonld) — Linked-data context aligning PokéAPI resources with schema.org.

### Examples

54 example JSON files generated from JSON Schema definitions.

## Capabilities

Naftiko capabilities organized as a shared per-API definition plus per-resource-family and cross-resource workflow capabilities.

### Shared Per-API Definitions

- [PokéAPI REST API](capabilities/shared/pokeapi-api.yaml) — 86 operations across 86 resources for the full v2 REST surface

### Per-Resource-Family Capabilities

| Capability | Resource Family |
|------------|----------------|
| [Berries](capabilities/pokeapi-berries.yaml) | Berries, berry firmness, berry flavors |
| [Contests](capabilities/pokeapi-contests.yaml) | Contest types, contest effects, super contest effects |
| [Encounters](capabilities/pokeapi-encounters.yaml) | Encounter methods, conditions, condition values |
| [Evolution](capabilities/pokeapi-evolution.yaml) | Evolution chains and triggers |
| [Games](capabilities/pokeapi-games.yaml) | Generations, Pokédexes, versions, version groups |
| [Items](capabilities/pokeapi-items.yaml) | Items, attributes, categories, fling effects, pockets |
| [Locations](capabilities/pokeapi-locations.yaml) | Locations, location areas, Pal Park areas, regions |
| [Machines](capabilities/pokeapi-machines.yaml) | TMs and HMs |
| [Moves](capabilities/pokeapi-moves.yaml) | Moves, ailments, battle styles, categories, damage classes, learn methods, targets |
| [Pokémon](capabilities/pokeapi-pokemon.yaml) | Pokémon, species, abilities, types, stats, natures, egg groups, growth rates, genders, characteristics |
| [Utility](capabilities/pokeapi-utility.yaml) | Languages |

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Pokémon Research](capabilities/pokemon-research.yaml) | PokéAPI v2 | 7 | Game Developer, Educator, Hobbyist, AI Agent |

## Vocabulary

- [PokéAPI Vocabulary](vocabulary/pokeapi-vocabulary.yaml) — Unified taxonomy mapping 17 resources, 2 actions, 4 workflows, and 5 personas across operational (OpenAPI) and capability (Naftiko) dimensions.

## Rules

- [PokéAPI Spectral Rules](rules/pokeapi-rules.yml) — 28 rules across info, OpenAPI version, servers, paths, operations, parameters, responses, tags, and schemas enforcing PokéAPI conventions.

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
