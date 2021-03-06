# polarfox-lib

[![Tests](https://github.com/Polarfox-Labs-Research/polarfox-lib/workflows/Tests/badge.svg)](https://github.com/Polarfox-Labs-Research/polarfox-lib/actions?query=workflow%3ATests)
[![Static Analysis](https://github.com/Polarfox-Labs-Research/polarfox-lib/workflows/Static%20Analysis/badge.svg)](https://github.com/Polarfox-Labs-Research/polarfox-lib/actions?query=workflow%3A%22Static+Analysis%22)
[![Lint](https://github.com/Polarfox-Labs-Research/polarfox-lib/workflows/Lint/badge.svg)](https://github.com/Polarfox-Labs-Research/polarfox-lib/actions?query=workflow%3ALint)
[![Fuzz Testing](https://github.com/Polarfox-Labs-Research/polarfox-lib/workflows/Fuzz%20Testing/badge.svg)](https://github.com/Polarfox-Labs-Research/polarfox-lib/actions?query=workflow%3A%22Fuzz+Testing%22)
[![npm](https://img.shields.io/npm/v/@polarfox/lib)](https://unpkg.com/@polarfox/lib@latest/)

Solidity libraries that are shared across Polarfox contracts. This package focuses on safety and execution gas efficiency.
Adapted from Uniswap.

## Install

Run `yarn` to install dependencies.

## Test

Run `yarn test` to execute the test suite.

## Usage

Install this in another project via `yarn add @polarfox/lib`

Then import the contracts via:

```solidity
import '@polarfox/lib/contracts/libraries/Babylonian.sol';

```
