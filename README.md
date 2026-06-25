# RCV Outage Track

**Outage Track** is an outage / cutover monitoring and handoff module for the
Root Chain Ventures NOC Portal platform.

This repository is an **operator pointer only**. Outage Track is distributed as a
container image from GHCR and is installed **through the NOC Portal** — not on
its own.

## License

**RCV Community License 1.0** — free for personal / home-lab use and any
organization's own internal operations; a paid commercial license is required to
offer it to third parties as a hosted/managed/SaaS service. See [`LICENSE`](LICENSE).
Commercial inquiries: **legal@rootchainventures.com**.

## Install

Outage Track is added from the Portal — you never hand-wire its credentials:

1. Install the **NOC Portal** first — see
   [RCV-NOC-Portal](https://github.com/Root-Chain-Ventures-LLC/RCV-NOC-Portal).
2. Sign in, open **Modules**, choose **Outage Track**, and click **Install**. The
   Portal mints its OIDC client + API key and deploys it into the Portal's namespace.

Image: `ghcr.io/root-chain-ventures-llc/outage-track`.
