# Awesome Threshold Policies [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome configurations of threshold signature schemes.

## Contents

- [Awesome Threshold Policies ](#awesome-threshold-policies-)
  - [Contents](#contents)
  - [About](#about)
  - [Threshold Policies](#threshold-policies)
  - [Contribute](#contribute)


## About

This list should contain known policies that are either currently in use or can be considered interesting - therefore awesome.

## Threshold Policies


| Policy | Description | Miniscript | Source |
|---------------|---------------------|-------------|---------------|
| 1-out-of-n      | One member must agree on a signature          | thresh(1, pk(a), pk(b), pk(c), ... , pk(n))        | [common](http://example.com)             |
| n-out-of-n      | All parties must agree on a signature          | thresh(n, pk(a), pk(b), pk(c), ... , pk(n))        | [common](http://example.com)             |
| k-out-of-n      | Basic multi-party signature with a threshold k         | thresh(k, pk(a), pk(b), pk(c), ... , pk(n))        | [common](http://example.com)             |
| 2-out-of-3      | Escrow between two parties        | thresh(2, pk(a), pk(b), pk(c))        | [common](http://example.com)             |

## Contribute

Contributions are welcome! Read the [contribution guidelines](contributing.md) first.
