# EdwinPAI

**EdwinPAI** is a sovereign, local-first personal AI runtime: a gateway, desktop app, and supporting packages for running your own assistant on your own devices.

This repository is the public landing page for the EdwinPAI beta. It intentionally points to the sanitized public release surfaces rather than duplicating the implementation here.

## Start here

- **Docs:** <https://docs.edwinpai.com>
- **Getting started:** <https://docs.edwinpai.com/start/getting-started>
- **License:** [Business Source License 1.1](./LICENSE)

## Public repositories

| Surface | Repository | Purpose |
| --- | --- | --- |
| Gateway / CLI package snapshot | <https://github.com/edwinpai/gateway> | Sanitized public package snapshot for the Gateway/CLI npm wrapper. |
| Desktop app | <https://github.com/edwinpai/desktop> | Sanitized public Desktop app snapshot and release artifacts. |
| Landing page | <https://github.com/edwinpai/edwinpai> | This hub: links to repos, docs, npm packages, and beta status. |

## npm packages

Install the current public beta CLI wrapper:

```bash
npm install -g @edwinpai/edwinpai@beta
edwinpai --help
```

Published beta packages:

| Package | npm |
| --- | --- |
| CLI wrapper | <https://www.npmjs.com/package/@edwinpai/edwinpai> |
| Gateway runtime | <https://www.npmjs.com/package/@edwinpai/gateway-core> |
| Identity/crypto boundary | <https://www.npmjs.com/package/@edwinpai/identity-core> |
| Shad memory/search boundary | <https://www.npmjs.com/package/@edwinpai/shad-core> |
| Workflows extension | <https://www.npmjs.com/package/@edwinpai/workflows> |

Current beta note: use `@edwinpai/edwinpai@beta` for the latest coordinated beta (`1.0.0-beta.8`).

## Desktop downloads

Desktop beta builds are published from the Desktop repository:

- <https://github.com/edwinpai/desktop/releases>

Supported beta artifact targets include macOS, Linux, and Windows.

## What is sanitized here?

The public repositories are release surfaces, not a dump of every internal development file. Private/internal-only material, secrets, local workspace state, and non-public source slices are excluded from the sanitized snapshots.

## Status

EdwinPAI is in public beta. APIs, packaging, and repository layout may still change before a stable v1 release.
