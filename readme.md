# Awesome Threshold Policies [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome configurations of threshold signature schemes.

## Contents

- [About](#about)
- [Threshold Policies](#threshold-policies)
- [Contribute](#contribute)

## About

This list should contain known policies that are either currently in use or can be considered interesting - therefore awesome.

## Threshold Policies

| Policy | Description | Miniscript | Source |
|---------------|---------------------|-------------|---------------|
| 1-out-of-n | One member must agree on a signature | thresh(1, pk(a), pk(b), pk(c), . , pk(n))| [common](http://example.com) |
| n-out-of-n | All parties must agree on a signature | thresh(n, pk(a), pk(b), pk(c), . , pk(n))| common |
| k-out-of-n | Basic multi-party signature with a threshold k | thresh(k, pk(a), pk(b), pk(c), . , pk(n))| common |
| 2-out-of-3 | Escrow between two parties with a trusted arbiter. Arbiter acts in case of dispute between two parties. | thresh(2, pk(a), pk(b), pk(c))| [HoldHold](https://hodlhodl.com/pages/help)  |
| 2-out-of-3 | Vault between user and recovery agent. User holds two keys, recovery agent one. Recovery agent can help to recover funds in case of loss of one user's key, but cannot move funds on its own | thresh(2, pk(a), pk(b), pk(c))| [Unchained](https://unchained.com/blog/why-2-of-3-multisig/)  |
| 2-out-of-2 with timelock into 2-out-of-2 | 2-of-2 escrow between two parties A and B. After timelock expires, another 2-of-2 escrow between A and C is valid. Protects party A against key loss or non-cooperativity of party B. | ? | ? |
| 2-out-of-3 with timelock 1-out-of-1 |  Escrow between two parties A and B with a trusted arbiter (e.g., loan) for a limited time period. After timelock expires, party A can withdraw all funds back (to prevent infinite lock of funds). | ? | [Bitcoin review, 1:04:00](https://bitcoin.review/podcast/episode-65/) |
| 11-out-of-15 | Bitcoin Liquid Federation threshold for signing valid blocks | ? | [Blockstream Liquid whitepaper](https://blockstream.com/assets/downloads/pdf/liquid-whitepaper.pdf) |

## Contribute

Contributions are welcome! Read the [contribution guidelines](contributing.md) first.
