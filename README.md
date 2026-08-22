# PokéAPI (pokeapi)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

PokéAPI (pokeapi.co) is a free, open-source RESTful and GraphQL API serving comprehensive Pokémon data — including Pokémon species, abilities, moves, items, types, locations, evolution chains, encounters, berries, contests, games, and machines. Built as an educational tool licensed under BSD-3-Clause, it is community-funded via Open Collective and GitHub Sponsors, requires no authentication, and is hosted with a fair-use policy encouraging clients to cache responses locally. The API powers tutorials, fan apps, machine-learning experiments, and game tooling worldwide and consistently serves one billion-plus requests per month.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/pokeapi/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/pokeapi/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Pokémon
- Open Source
- Open Data
- REST
- GraphQL
- Gaming
- Educational
- Community

## Timestamps

- **Created:** 2026-05-30
- **Modified:** 2026-05-30

## APIs

### PokéAPI REST API v2

The PokéAPI v2 REST API exposes the canonical Pokémon dataset across 12 resource families and roughly 60 endpoints — Pokémon, Pokémon Species, Abilities, Moves, Types, Items, Berries, Locations, Evolution Chains, Encounters, Games (Generations / Pokédex / Versions / Version Groups), Contests, Machines, and Utility (Languages). Every endpoint is GET-only, returns JSON, and is reachable under https://pokeapi.co/api/v2/ without authentication.

- **Human URL:** [https://pokeapi.co/docs/v2](https://pokeapi.co/docs/v2)
- **Base URL:** `https://pokeapi.co/api/v2`

#### Tags

- Pokémon
- REST
- Open Data
- Educational
- Open Source

#### Properties

- [Documentation](https://pokeapi.co/docs/v2)
- [API Reference](https://pokeapi.co/docs/v2)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/pokeapi/refs/heads/main/openapi/pokeapi-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Terms of Service](https://pokeapi.co/docs/v2#fairuse)
- [SDK](https://www.npmjs.com/package/pokeapi-js-wrapper)
- [SDK](https://www.npmjs.com/package/pokedex-promise-v2)
- [SDK](https://pypi.org/project/pokebase/)
- [SDK](https://pypi.org/project/pokepy/)
- [SDK](https://github.com/PokeAPI/pokekotlin)
- [Postman Collection](collections/pokeapi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pokeapi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PokéAPI GraphQL API (Beta)

The PokéAPI GraphQL beta exposes the same Pokémon dataset as the REST API through a single endpoint with field-level selection, joins, and filtering. It is well suited to clients that want to cherry-pick fields across Pokémon, species, moves, and abilities in a single round trip.

- **Human URL:** [https://pokeapi.co/docs/graphql](https://pokeapi.co/docs/graphql)
- **Base URL:** `https://beta.pokeapi.co/graphql/v1beta`

#### Tags

- Pokémon
- GraphQL
- Open Data
- Beta

#### Properties

- [Documentation](https://pokeapi.co/docs/graphql)
- [Getting Started](https://beta.pokeapi.co/graphql/console/)
- [Endpoint](https://beta.pokeapi.co/graphql/v1beta)
- [Postman Collection](collections/pokeapi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pokeapi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://pokeapi.co)
- [Getting Started](https://pokeapi.co/docs/v2)
- [GitHub Organization](https://github.com/PokeAPI)
- [GitHub Repository](https://github.com/PokeAPI/pokeapi)
- [License](https://github.com/PokeAPI/pokeapi/blob/master/LICENSE.md)
- [Pricing](https://opencollective.com/pokeapi)
- [Pricing](https://github.com/sponsors/PokeAPI)
- [About](https://pokeapi.co/about)
- [Terms of Service](https://pokeapi.co/docs/v2#fairuse)
- [Support](https://pokeapi.slack.com)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/pokeapi)
- [Issue Tracker](https://github.com/PokeAPI/pokeapi/issues)
- [Changelog](https://github.com/PokeAPI/pokeapi/releases)
- [SDK](https://hub.docker.com/r/pokeapi/pokeapi)
- [SDK](https://github.com/PokeAPI/sprites)
- [SDK](https://github.com/PokeAPI/api-data)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Tools](undefined)
- [Spectral Rules](https://raw.githubusercontent.com/api-evangelist/pokeapi/refs/heads/main/rules/pokeapi-rules.yml)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/pokeapi/refs/heads/main/vocabulary/pokeapi-vocabulary.yaml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
