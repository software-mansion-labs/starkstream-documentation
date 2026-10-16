# Starkstream Documentation

This repository contains the Starkstream documentation for indexing Starknet
data with DNA v2 and the TypeScript SDK. Shared features such as storage,
plugins, testing, and observability are included where they support Starknet indexers.

## Sources and scope

- [`software-mansion-labs/starkstream-dna`](https://github.com/software-mansion-labs/starkstream-dna):
  the server README, architecture, crate rustdoc, and protobuf definitions are
  the technical reference for the Starknet server and DNA protocol.
- [`software-mansion-labs/apibara-typescript-sdk`](https://github.com/software-mansion-labs/apibara-typescript-sdk):
  the TypeScript client, CLI, plugins, and Starknet examples are the reference
  for client-side APIs.

The current server distribution supports Starknet. Documentation for other
chains, adding a new chain, and discontinued client SDKs is outside this scope.
The `devlog` directory retains the historical changes relevant to Starknet and
the shared TypeScript tooling; its dates describe the original releases.

Current documentation lives in `docs`.

## Naming and compatibility

Starkstream builds on the original Apibara codebase. Product names in the current
documentation use Starkstream.

The TypeScript SDK migration is separate from the server rename. Keep the
published `apibara` and `@apibara/*` package names, the `apibara` CLI,
`apibara.config.ts`, `.apibara` build paths, and exported types such as
`ApibaraRuntimeConfig` until the SDK changes them. These are executable
interfaces, so replacing them with unverified Starkstream names breaks examples.

DNA remains the protocol name. Its protobuf packages, environment variables,
metrics, persisted keys, and release identifiers follow the server's
[compatibility contract](https://github.com/software-mansion-labs/starkstream-dna/blob/main/docs/compatibility.md).
The SDK's `airfoil` database schema and historical release records also keep
their existing names.

## Contributing

If you spot any issue with our documentation, or simply want to improve it,
feel free to contribute to it!

**Fixing issues**

 - Fork and clone the repository
 - Make your changes
 - Open a PR with the fix
 - Done!

**Adding new pages and sections**

 - Open an issue in [this repository](https://github.com/software-mansion-labs/apibara-documentation/issues)
   to discuss the proposed section.
 - Fork and clone the repository
 - Make your changes
 - Open a PR
 - Done!
