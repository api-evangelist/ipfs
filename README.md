# IPFS

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
