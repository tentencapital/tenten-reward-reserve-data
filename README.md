# TEN Reward Reserve — public data

Machine-generated output of [tenten-reward-indexer-v2](https://github.com/dryymartini/tenten-reward-indexer-v2), published here so the claim site can fetch it over a plain URL.

- `eligibility.json` — who currently holds TEN long enough to be reward-eligible (30-day rule), and a countdown for everyone else. Independent of any distribution round; regenerated periodically and simply overwritten.
- `epochs/N.json` (added after the first real distribution) — the Merkle-proof data for epoch `N`'s claims.

Every file is reproducible from public mainnet data by re-running the indexer with the same config; nothing here is authoritative on its own — the on-chain contract at `0xC05ddFbd4f9a46ae297b286D4D6998a0c0Ea27FE` is.
