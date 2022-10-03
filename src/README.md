# Soulbound 👻 Token Smart Contracts

#### Installation

```
$ npm install @auroralabs/contracts
```

#### Usage

- Contract

```solidity

// SPDX-License-Identifier: MIT
pragma solidity ^0.8.16;

import "@auroralabs/contracts/SBT.sol";

contract MySoulboundToken is SBT {
    constructor() SBT("My Soulbound", "SBT", 16) {}
}

```

- Interface

```solidity
import "@auroralabs/contracts/interfaces/ISBT.sol";
```
