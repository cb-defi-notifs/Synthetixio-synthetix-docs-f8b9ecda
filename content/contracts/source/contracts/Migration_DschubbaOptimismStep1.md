# Migration_DschubbaOptimismStep1

## Description

**Source:** [contracts/migrations/Migration_DschubbaOptimismStep1.sol](https://github.com/Synthetixio/synthetix/tree/v2.90.2-alpha/contracts/migrations/Migration_DschubbaOptimismStep1.sol)

## Variables

### `OWNER`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.90.2-alpha/contracts/migrations/Migration_DschubbaOptimismStep1.sol#L19)</sub>

**Type:** `address`

### `exchangerates_i`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.90.2-alpha/contracts/migrations/Migration_DschubbaOptimismStep1.sol#L40)</sub>

**Type:** `contract ExchangeRates`

### `futuresmarketmanager_i`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.90.2-alpha/contracts/migrations/Migration_DschubbaOptimismStep1.sol#L32)</sub>

**Type:** `contract FuturesMarketManager`

### `perpsv2exchangerate_i`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.90.2-alpha/contracts/migrations/Migration_DschubbaOptimismStep1.sol#L29)</sub>

**Type:** `contract PerpsV2ExchangeRate`

### `perpsv2marketsettings_i`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.90.2-alpha/contracts/migrations/Migration_DschubbaOptimismStep1.sol#L35)</sub>

**Type:** `contract PerpsV2MarketSettings`

### `perpsv2marketstateldoperp_i`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.90.2-alpha/contracts/migrations/Migration_DschubbaOptimismStep1.sol#L26)</sub>

**Type:** `contract PerpsV2MarketState`

### `systemstatus_i`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.90.2-alpha/contracts/migrations/Migration_DschubbaOptimismStep1.sol#L38)</sub>

**Type:** `contract SystemStatus`

## Constructor

### `constructor`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.90.2-alpha/contracts/migrations/Migration_DschubbaOptimismStep1.sol#L46)</sub>

??? example "Details"

    **Signature**

    `constructor()`

    **Visibility**

    `public`

    **State Mutability**

    ``

## Views

### `contractsRequiringOwnership`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.90.2-alpha/contracts/migrations/Migration_DschubbaOptimismStep1.sol#L48)</sub>

??? example "Details"

    **Signature**

    `contractsRequiringOwnership() pure returns (address[] contracts)`

    **Visibility**

    `public`

    **State Mutability**

    `pure`

## Restricted Functions

### `migrate`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.90.2-alpha/contracts/migrations/Migration_DschubbaOptimismStep1.sol#L58)</sub>

??? example "Details"

    **Signature**

    `migrate()`

    **Visibility**

    `external`

    **State Mutability**

    ``

    **Modifiers**

    * [onlyOwner](#onlyowner)

## Internal Functions

### `acceptAll`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.90.2-alpha/contracts/migrations/Migration_DschubbaOptimismStep1.sol#L184)</sub>

??? example "Details"

    **Signature**

    `acceptAll()`

    **Visibility**

    `internal`

    **State Mutability**

    ``

### `futuresmarketmanager_addProxiedMarkets_2`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.90.2-alpha/contracts/migrations/Migration_DschubbaOptimismStep1.sol#L209)</sub>

??? example "Details"

    **Signature**

    `futuresmarketmanager_addProxiedMarkets_2()`

    **Visibility**

    `internal`

    **State Mutability**

    ``

### `nominateAll`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.90.2-alpha/contracts/migrations/Migration_DschubbaOptimismStep1.sol#L191)</sub>

??? example "Details"

    **Signature**

    `nominateAll()`

    **Visibility**

    `internal`

    **State Mutability**

    ``

### `perpsv2exchangerate_addAssociatedContracts_1`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.90.2-alpha/contracts/migrations/Migration_DschubbaOptimismStep1.sol#L198)</sub>

??? example "Details"

    **Signature**

    `perpsv2exchangerate_addAssociatedContracts_1()`

    **Visibility**

    `internal`

    **State Mutability**

    ``
