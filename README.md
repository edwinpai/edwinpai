# EdwinPAI

EdwinPAI is the public entrypoint for the Edwin personal AI runtime and desktop ecosystem.

## Repositories

- [edwinpai/gateway](https://github.com/edwinpai/gateway) — gateway/runtime source snapshot
- [edwinpai/desktop](https://github.com/edwinpai/desktop) — desktop application source snapshot

## Packages

Protected runtime components are distributed through npm packages under the `@edwinpai` scope:

- `@edwinpai/identity-core`
- `@edwinpai/shad-core`
- `@edwinpai/workflows`

The root package `@edwinpai/edwinpai` is intentionally published from the sanitized gateway release path, not from private development repositories.

## Release model

Private development happens in private `jonesj38/*` repositories. Public `edwinpai/*` repositories are populated by controlled copy/snapshot exports so private development history is not published.
