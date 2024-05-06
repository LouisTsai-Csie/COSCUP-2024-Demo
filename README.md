# COSCUP-2024-Demo

## Introduction

It is the demonstration repository for *Exploring Contract Analysis Tools by Unveiling Real-World Upgradeable Proxy Vulnerabilities*, *COSCUP 2024 Blockchain and Distributed Ledger*

## Preliminaries

1. Git / GitHub Account
2. Python
3. Node
4. Rust (Cargo)

## Tools
1. [Slither](https://github.com/crytic/slither?tab=readme-ov-file)
2. [Slitherin](https://github.com/pessimistic-io/slitherin?tab=readme-ov-file)
3. [Mythril](https://github.com/Consensys/mythril)
4. [Aderyn](https://github.com/Cyfrin/aderyn)
5. [Ityfuzz](https://github.com/fuzzland/ityfuzz)
6. [Echidna](https://github.com/crytic/echidna)

## Attack Incidents

| Date | Incident | Loss | Chain | Root Cause | PoC |
| --- | ---- | --- | --- | --- | --- |
| 2022-07-23 | Audius | 1.08 M | Ethereum | Storage Collision | [PoC](https://github.com/SunWeb3Sec/DeFiHackLabs/blob/main/past/2022/README.md#20220723-audius---storage-collision--malicious-proposal) |
| 2023-02-24 | EFVault | 5.1 M | Ethereum | Storage Collison | [PoC](https://github.com/SunWeb3Sec/DeFiHackLabs/blob/main/past/2023/README.md#20230224---efvault---storage-collision) |
| 2023-12-25 | Telcoin | 1.24 M | Polygon | Storage Collision | [PoC](https://github.com/SunWeb3Sec/DeFiHackLabs/blob/main/past/2023/README.md#20231225-telcoin---storage-collision) |
| 2024-02-10 | FLIX | 200K | Ethereum | Access Control | [PoC](https://github.com/SunWeb3Sec/DeFiHackLabs/blob/main/README.md#20240210-filx-dn404---access-control) |
| 2024-04-30 | Pike Finance | 1.4 M | Ethereum | Storage Collision | [PoC](https://github.com/SunWeb3Sec/DeFiHackLabs/blob/main/README.md#20240430-pikefinance---uninitialized-proxy) |

## Note

Use `solc-select` to set certain solidity compiler version

1. Install necessary compiler version
```bash
solc-select install <version>
```

2. Set certain compiler version
```bash
solc-select use <version>
```

* You can use `solc --version` to check current version.