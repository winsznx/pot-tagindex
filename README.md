# pot-tagindex

Companion package for **Pot**. Aggregates the live tag cloud from on-chain `Tagged` events on both chains so clients can render "trending tags" without re-indexing every load.

Pairs with the main SDK [`@winsznx/potforge`](https://github.com/winsznx/potforge).

## Status

Reference scaffold for the indexer. Implementation pulls the lookback slice from `@winsznx/potforge/celo`'s `getLogs` helper and folds it into a `Map<bytes32, number>`.

## License

MIT
