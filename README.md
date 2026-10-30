# IPFS

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

InterPlanetary File System (IPFS) is a peer-to-peer hypermedia protocol and distributed content-addressed storage system. The Kubo implementation exposes an HTTP RPC API (/api/v0/) for adding, pinning, and retrieving content-addressed files, managing DAG (Directed Acyclic Graph) nodes, key management, and network peer operations. The HTTP Gateway API provides read-only access to IPFS and IPNS content over standard HTTP. The Delegated Routing V1 HTTP API enables clients to discover content providers and resolve peer records without running a full DHT node.

**Areas:** IPFS · Distributed Storage · Content-Addressed · Decentralized · Peer-to-Peer · File Storage · DAG · Pinning · Gateways

## IPFS on APIs.io

Everything profiled for IPFS is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/ipfs/](https://apis.io/providers/ipfs/)** — or go straight to one of the APIs or properties below.

### APIs (40)

- [IPFS HTTP Gateway API](https://apis.io/apis/ipfs/ipfs-http-gateway-api/) — The IPFS HTTP Gateway API is an implementation-agnostic interface for retrieving content-addressed data from IPFS over standard HTTP. Path gateways expose…
- [IPFS Delegated Routing V1 HTTP API](https://apis.io/apis/ipfs/ipfs-delegated-routing-v1-http-api/) — The Delegated Routing V1 HTTP API allows IPFS clients to offload content routing, peer routing, and IPNS resolution to a remote server without running a…
- [IPFS Add API](https://apis.io/apis/ipfs/ipfs-add-api/) — The Add API from IPFS — 1 operation(s) for add.
- [IPFS Bitswap API](https://apis.io/apis/ipfs/ipfs-bitswap-api/) — The Bitswap API from IPFS — 4 operation(s) for bitswap.
- [IPFS Block API](https://apis.io/apis/ipfs/ipfs-block-api/) — The Block API from IPFS — 4 operation(s) for block.
- [IPFS Bootstrap API](https://apis.io/apis/ipfs/ipfs-bootstrap-api/) — The Bootstrap API from IPFS — 6 operation(s) for bootstrap.
- [IPFS Cat API](https://apis.io/apis/ipfs/ipfs-cat-api/) — The Cat API from IPFS — 1 operation(s) for cat.
- [IPFS Cid API](https://apis.io/apis/ipfs/ipfs-cid-api/) — The Cid API from IPFS — 5 operation(s) for cid.
- [IPFS Commands API](https://apis.io/apis/ipfs/ipfs-commands-api/) — The Commands API from IPFS — 1 operation(s) for commands.
- [IPFS Config API](https://apis.io/apis/ipfs/ipfs-config-api/) — The Config API from IPFS — 4 operation(s) for config.
- [IPFS Dag API](https://apis.io/apis/ipfs/ipfs-dag-api/) — The Dag API from IPFS — 6 operation(s) for dag.
- [IPFS Dht API](https://apis.io/apis/ipfs/ipfs-dht-api/) — The Dht API from IPFS — 6 operation(s) for dht.
- [IPFS Diag API](https://apis.io/apis/ipfs/ipfs-diag-api/) — The Diag API from IPFS — 5 operation(s) for diag.
- [IPFS Dns API](https://apis.io/apis/ipfs/ipfs-dns-api/) — The Dns API from IPFS — 1 operation(s) for dns.
- [IPFS File API](https://apis.io/apis/ipfs/ipfs-file-api/) — The File API from IPFS — 1 operation(s) for file.
- [IPFS Files API](https://apis.io/apis/ipfs/ipfs-files-api/) — The Files API from IPFS — 10 operation(s) for files.
- [IPFS Get API](https://apis.io/apis/ipfs/ipfs-get-api/) — The Get API from IPFS — 1 operation(s) for get.
- [IPFS Id API](https://apis.io/apis/ipfs/ipfs-id-api/) — The Id API from IPFS — 1 operation(s) for id.
- [IPFS Key API](https://apis.io/apis/ipfs/ipfs-key-api/) — The Key API from IPFS — 5 operation(s) for key.
- [IPFS Log API](https://apis.io/apis/ipfs/ipfs-log-api/) — The Log API from IPFS — 3 operation(s) for log.
- [IPFS Ls API](https://apis.io/apis/ipfs/ipfs-ls-api/) — The Ls API from IPFS — 1 operation(s) for ls.
- [IPFS Mount API](https://apis.io/apis/ipfs/ipfs-mount-api/) — The Mount API from IPFS — 1 operation(s) for mount.
- [IPFS Multibase API](https://apis.io/apis/ipfs/ipfs-multibase-api/) — The Multibase API from IPFS — 4 operation(s) for multibase.
- [IPFS Name API](https://apis.io/apis/ipfs/ipfs-name-api/) — The Name API from IPFS — 6 operation(s) for name.
- [IPFS Object API](https://apis.io/apis/ipfs/ipfs-object-api/) — The Object API from IPFS — 11 operation(s) for object.
- [IPFS Pin API](https://apis.io/apis/ipfs/ipfs-pin-api/) — The Pin API from IPFS — 11 operation(s) for pin.
- [IPFS Ping API](https://apis.io/apis/ipfs/ipfs-ping-api/) — The Ping API from IPFS — 1 operation(s) for ping.
- [IPFS Pins API](https://apis.io/apis/ipfs/ipfs-pins-api/) — The pins API from IPFS — 2 operation(s) for pins.
- [IPFS Pubsub API](https://apis.io/apis/ipfs/ipfs-pubsub-api/) — The Pubsub API from IPFS — 4 operation(s) for pubsub.
- [IPFS Refs API](https://apis.io/apis/ipfs/ipfs-refs-api/) — The Refs API from IPFS — 2 operation(s) for refs.
- [IPFS Repo API](https://apis.io/apis/ipfs/ipfs-repo-api/) — The Repo API from IPFS — 5 operation(s) for repo.
- [IPFS Resolve API](https://apis.io/apis/ipfs/ipfs-resolve-api/) — The Resolve API from IPFS — 1 operation(s) for resolve.
- [IPFS Routing API](https://apis.io/apis/ipfs/ipfs-routing-api/) — The Routing API from IPFS — 5 operation(s) for routing.
- [IPFS Shutdown API](https://apis.io/apis/ipfs/ipfs-shutdown-api/) — The Shutdown API from IPFS — 1 operation(s) for shutdown.
- [IPFS Stats API](https://apis.io/apis/ipfs/ipfs-stats-api/) — The Stats API from IPFS — 5 operation(s) for stats.
- [IPFS Swarm API](https://apis.io/apis/ipfs/ipfs-swarm-api/) — The Swarm API from IPFS — 13 operation(s) for swarm.
- [IPFS Tar API](https://apis.io/apis/ipfs/ipfs-tar-api/) — The Tar API from IPFS — 2 operation(s) for tar.
- [IPFS Version API](https://apis.io/apis/ipfs/ipfs-version-api/) — The Version API from IPFS — 2 operation(s) for version.
- [IPFS P2p API](https://apis.io/apis/ipfs/ipfs-p2p-api/) — The P2p API from IPFS — 6 operation(s) for p2p.
- [IPFS File Store API](https://apis.io/apis/ipfs/ipfs-file-store-api/) — The File Store API from IPFS — 3 operation(s) for file store.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Ipfs Agentic Access](https://apis.io/agentic-access/ipfs/ipfs-agentic-access/)

#### JSON Schema (11)

The data models the API reads and writes.

- [Delegates](https://apis.io/schemas/ipfs/delegates/)
- [Failure](https://apis.io/schemas/ipfs/failure/)
- [Kubo Rpc Responses](https://apis.io/schemas/ipfs/kubo-rpc-responses/)
- [Origins](https://apis.io/schemas/ipfs/origins/)
- [Pin](https://apis.io/schemas/ipfs/pin/)
- [PinMeta](https://apis.io/schemas/ipfs/pinmeta/)
- [PinResults](https://apis.io/schemas/ipfs/pinresults/)
- [PinStatus](https://apis.io/schemas/ipfs/pinstatus/)
- [Status](https://apis.io/schemas/ipfs/status/)
- [StatusInfo](https://apis.io/schemas/ipfs/statusinfo/)
- [TextMatchingStrategy](https://apis.io/schemas/ipfs/textmatchingstrategy/)

#### JSON-LD (2)

Linked-data contexts for the provider's vocabulary.

- [Ipfs Context](https://apis.io/jsonld/ipfs/ipfs-context/)
- [Ipfs Provider Context](https://apis.io/jsonld/ipfs/ipfs-provider/)

#### Examples (2)

Example requests and responses.

- [Ipfs Kubo Rpc Examples](https://apis.io/examples/ipfs/ipfs-kubo-rpc-examples/)
- [Ipfs Pinning Service Schema Examples](https://apis.io/examples/ipfs/ipfs-pinning-service-schema-examples/)

#### Collections (38)

Postman and Open Collection request collections.

- [IPFS RPC Add API](https://apis.io/collections/ipfs/open-ipfs-add-api/)
- [IPFS RPC Add Bitswap API](https://apis.io/collections/ipfs/open-ipfs-bitswap-api/)
- [IPFS RPC Add Block API](https://apis.io/collections/ipfs/open-ipfs-block-api/)
- [IPFS RPC Add Bootstrap API](https://apis.io/collections/ipfs/open-ipfs-bootstrap-api/)
- [IPFS RPC Add Cat API](https://apis.io/collections/ipfs/open-ipfs-cat-api/)
- [IPFS RPC Add Cid API](https://apis.io/collections/ipfs/open-ipfs-cid-api/)
- [IPFS RPC Add Commands API](https://apis.io/collections/ipfs/open-ipfs-commands-api/)
- [IPFS RPC Add Config API](https://apis.io/collections/ipfs/open-ipfs-config-api/)
- [IPFS RPC Add Dag API](https://apis.io/collections/ipfs/open-ipfs-dag-api/)
- [IPFS RPC Add Dht API](https://apis.io/collections/ipfs/open-ipfs-dht-api/)
- [IPFS RPC Add Diag API](https://apis.io/collections/ipfs/open-ipfs-diag-api/)
- [IPFS RPC Add Dns API](https://apis.io/collections/ipfs/open-ipfs-dns-api/)
- [IPFS RPC Add File API](https://apis.io/collections/ipfs/open-ipfs-file-api/)
- [IPFS RPC Add Files API](https://apis.io/collections/ipfs/open-ipfs-files-api/)
- [IPFS RPC Add Filestore API](https://apis.io/collections/ipfs/open-ipfs-filestore-api/)
- [IPFS RPC Add Get API](https://apis.io/collections/ipfs/open-ipfs-get-api/)
- [IPFS RPC Add Id API](https://apis.io/collections/ipfs/open-ipfs-id-api/)
- [IPFS RPC Add Key API](https://apis.io/collections/ipfs/open-ipfs-key-api/)
- [IPFS RPC Add Log API](https://apis.io/collections/ipfs/open-ipfs-log-api/)
- [IPFS RPC Add Ls API](https://apis.io/collections/ipfs/open-ipfs-ls-api/)
- [IPFS RPC Add Mount API](https://apis.io/collections/ipfs/open-ipfs-mount-api/)
- [IPFS RPC Add Multibase API](https://apis.io/collections/ipfs/open-ipfs-multibase-api/)
- [IPFS RPC Add Name API](https://apis.io/collections/ipfs/open-ipfs-name-api/)
- [IPFS RPC Add Object API](https://apis.io/collections/ipfs/open-ipfs-object-api/)
- [IPFS RPC Add P2p API](https://apis.io/collections/ipfs/open-ipfs-p2p-api/)
- …and 13 more published on APIs.io

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [IPFS — jsonschema rules](https://apis.io/rules/ipfs/ipfs-jsonschema-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Ipfs Authentication](https://apis.io/security/ipfs/ipfs-authentication/)
- [Ipfs Domain Security](https://apis.io/security/ipfs/ipfs-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Plans](https://apis.io/plans/ipfs/plans/)

#### Rate limits (1)

Published request limits.

- [Rate Limits](https://apis.io/rate-limits/ipfs/rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Finops](https://apis.io/finops/ipfs/finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://ipfs.tech)
- [Blog](https://blog.ipfs.tech/index.xml)

## API Evangelist rating

**Kin Score 27.0** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 62.5 |
| Contract quality | 43.8 |
| Contract governance | 9.8 |
| Operational transparency | 21.1 |
| Developer ergonomics | 23.8 |
| Access clarity | 7.9 |

**Agent readiness 27.5** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | verified |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | yes |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 16.7** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/ipfs/](https://apis.io/providers/ipfs/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for IPFS: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/ipfs/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
