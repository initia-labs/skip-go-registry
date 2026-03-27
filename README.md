# skip-go-registry

Fork of [skip-go/skip-go-registry](https://github.com/skip-mev/skip-go-registry) with Initia chain, asset, and bridge configurations.

## Structure

| Directory | Description |
|-----------|-------------|
| `chains/` | Chain configurations (chain.json per network) |
| `bridges/` | Bridge provider configurations |
| `swap-venues/` | Swap venue configurations |
| `scripts/` | Validation and utility scripts |

## Schemas

- `chain.schema.json` - Standard chain config schema
- `initia.chain.schema.json` - Initia-specific chain config schema
- `assetlist.schema.json` - Asset list schema
- `group_assets.schema.json` / `groups.schema.json` - Asset grouping schemas

## Validation

```sh
cd scripts/config-validator
npm install
npm run validate
```

See [`scripts/README.md`](./scripts/README.md) for CoinGecko validation and other utilities.
