# efp-workspace

A root developer workspace for monorepo-style development of Ethereum Follow Protocol.

This repository does not use submodules.

To clone an EFP repository for development, run one of the `clone:*` targets in the `scripts` directory, or `bun clone` to clone all supported repositories.

```bash
$ bun clone
> bun clone:api && bun clone:app && bun clone:contracts-beta && bun clone:docs && bun clone:indexer
> [ -d 'api' ] || git clone --recurse-submodules git@github.com:ethereumfollowprotocol/api.git api
> [ -d 'app' ] || git clone --recurse-submodules git@github.com:ethereumfollowprotocol/app.git app
> [ -d 'contracts-beta' ] || git clone --recurse-submodules git@github.com:ethereumfollowprotocol/contracts-beta.git contracts-beta
> [ -d 'docs' ] || git clone --recurse-submodules git@github.com:ethereumfollowprotocol/docs.git docs
> [ -d 'indexer' ] || git clone --recurse-submodules git@github.com:ethereumfollowprotocol/indexer.git indexer
```