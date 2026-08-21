# Manus Public UI Research

This repository is the **research lane** for publicly available userscripts, open-source libraries, and public documentation that reference `manus.im` or `manus.app`.

## Purpose

The repository records reproducible source inventories, license/provenance assessments, static capability classifications, and synthetic-fixture research notes. It does not contain copied third-party source code unless a later, item-specific review confirms license compatibility and records the upstream revision and notices.

## Boundaries

Research is limited to public material and local, synthetic fixtures. The repository must not contain tokens, cookies, browser profiles, session data, account replays, hidden reasoning, task interaction streams, or private endpoint material. No browser automation or network probing runs in CI.

## Structure

| Path | Purpose |
|---|---|
| `inventory/` | Immutable public-source manifests and collection metadata. |
| `assessments/` | Static capability, license, and supply-chain reviews. |
| `fixtures/` | Synthetic DOM and data fixtures with no production hostnames or account data. |
| `docs/` | Research methodology and decision records. |

## Governance

Every inventory entry must identify a canonical public URL, collection date, version/revision when available, license evidence, and a capability tier. New claims must cite source locations. Any source requiring broad cross-origin permissions, page-world access, network interception, credential handling, conversation export, or unattended automation is recorded as a risk finding and cannot be imported by default.
