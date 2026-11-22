# Neural Engine Byte (NEB) mining on AethelBlock

Independent NEBHash v2 mining pool. Choose PPLNS or SOLO and track your workers on the public dashboard.

**Start here:** https://aethelblock.com/neb/?lang=en

## Connection settings

| Mode | Stratum URL |
| --- | --- |
| PPLNS | stratum+tcp://neb-pool.aethelblock.com:3084 |
| SOLO | stratum+tcp://neb-solo.aethelblock.com:3085 |

Use your own public NEB receiving address. Follow the current website guide for miner-specific wallet and worker syntax. Never share your wallet seed or private keys.

## Suprminer setup

Download Suprminer from its official repository: https://github.com/ocminer/suprminer

The NEB release guide is https://github.com/ocminer/suprminer/blob/main/docs/NEB_RELEASE_GUIDE.md . Use a release that supports the current NEB mainnet. Choose one of the two pool URLs above and configure your NEB wallet address according to the official guide. Check for accepted shares in the miner log, then look up the same address and mode in our dashboard.

## Rewards and payouts

- Pool fee: 1%.
- Minimum payout: 0.1 NEB.
- Automatic hourly payouts when the confirmed, mature balance reaches the minimum.
- Smaller balances accumulate. A newly found block must mature before it becomes payable.
- PPLNS shares pool rewards; SOLO rewards depend on blocks found by your miner. Neither mode guarantees income or a time to find a block.

The live website is the source for current terms, network-fee details and connection settings. Miner software can have its own separate developer fee.

## Statistics and support

- Dashboard and setup: https://aethelblock.com/neb/?lang=en
- Public pool statistics API: https://aethelblock.com/api/pools
- Pool operator: https://aethelblock.com/
- Support: soporte@aethelblock.com

When asking for setup help, include your operating system, miner version and error text. Do not send secrets.

## NEB project

- Official website and explorer: https://neuralenginebyte.org/
- Source and protocol: https://github.com/SilasEigen/neb

AethelBlock is an independent pool operator and is not the NEB core development team. This repository contains documentation, not node or miner binaries.

---

## All coins available on AethelBlock

NEB, NEXC, GAEL, PRL, QTC (Quantus), ETC, BTC, XMR, BEAM, RVN, XNA, ERG, ZANO, AE and ALPH.

Browse current pools: https://aethelblock.com/?lang=en
