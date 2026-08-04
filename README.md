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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

InterPlanetary File System (IPFS) is a peer-to-peer hypermedia protocol and distributed content-addressed storage system. This repository contains the APIs.json 0.19 provider profile for IPFS, covering three public HTTP APIs:

1. **Kubo RPC API** (`/api/v0/`) — RPC-style HTTP API for managing a Kubo IPFS node: adding files, pinning content, managing DAG nodes, resolving IPNS names, and controlling swarm peers.
2. **HTTP Gateway API** — Implementation-agnostic read-only API for retrieving IPFS/IPNS content over standard HTTP. Public gateways at `ipfs.io`, `dweb.link`, and `trustless-gateway.link`.
3. **Delegated Routing V1 HTTP API** — HTTP API for content provider and peer discovery without a full DHT node. Public endpoint at `delegated-ipfs.dev`.

## Links

- Website: https://ipfs.tech/
- Documentation: https://docs.ipfs.tech/
- Kubo RPC API Reference: https://docs.ipfs.tech/reference/kubo/rpc/
- Gateway Specification: https://specs.ipfs.tech/http-gateways/path-gateway/
- Delegated Routing Specification: https://specs.ipfs.tech/routing/http-routing-v1/
- GitHub (Kubo): https://github.com/ipfs/kubo
- GitHub (Specs): https://github.com/ipfs/specs
- Forums: https://discuss.ipfs.tech/

## Repository Contents

| Path | Description |
|------|-------------|
| `apis.yml` | APIs.json 0.19 provider profile |
| `plans/plans.yml` | Access plans (self-hosted, public gateways, pinning services) |
| `rate-limits/rate-limits.yml` | Rate limit documentation per API |
| `finops/finops.yml` | Cost drivers and optimization guidance |
