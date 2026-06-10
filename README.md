# ArcFX Contracts

Smart contracts powering [ArcFX](https://arcfx.app) — non-custodial stablecoin
payment infrastructure on Arc, Circle's L1.

## Contracts

| Contract | Description | Arc Testnet address |
|----------|-------------|---------------------|
| `ArcFXPayments` | Single payments with a 0.15% protocol fee | `0xc37D88f17573f13F7A27D33a502f5f1fB7D545D3` |
| `ArcFXMultisender` | Batch transfers (up to 500 recipients); 0.15% fee on the Pro tier | `0xF7aeb369bB50b7d9E2DDe7d3aC386B5ed6e71398` |

Both are deployed and live on **Arc Testnet**. View them on
[ArcScan](https://testnet.arcscan.app/address/0xc37D88f17573f13F7A27D33a502f5f1fB7D545D3).

## Status

These contracts are on **testnet**. A professional security audit is scheduled
before any mainnet deployment. This source is published for transparency and
review; we welcome responsible disclosure of any issues to arcfxapp@gmail.com.

## License

MIT
