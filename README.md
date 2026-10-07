# Apibara Documentation

This repository contains documentation for indexing Starknet data with DNA v2
and the TypeScript SDK. Shared features such as storage, plugins, testing, and
observability are included where they support Starknet indexers.

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
The `docs/v1` directory is a legacy reference for existing Starknet indexers.
Its CLI, sinks, service URLs, and screenshots describe the original v1 software;
they are not current deployment instructions. New development should use `docs/v2`.

## Contributing

If you spot any issue with our documentation, or simply want to improve it,
feel free to contribute to it!

**Fixing issues**

 - Fork and clone the repository
 - Make your changes
 - Open a PR with the fix
 - Done!

**Adding new pages and sections**

 - Join [our Discord](https://discord.gg/m7B92CNFNt) and get in touch with the
   team to discuss your ideas. This is to optimize your contribution for maximum
   impact.
 - Fork and clone the repository
 - Make your changes
 - Open a PR
 - Done!
