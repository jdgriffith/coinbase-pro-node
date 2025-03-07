[coinbase-pro-node](../README.md) / [Exports](../modules.md) / FeeAPI

# Class: FeeAPI

## Table of contents

### Constructors

- [constructor](feeapi.md#constructor)

### Properties

- [URL](feeapi.md#url)

### Methods

- [getCurrentFees](feeapi.md#getcurrentfees)

## Constructors

### constructor

\+ **new FeeAPI**(`apiClient`: AxiosInstance): [_FeeAPI_](feeapi.md)

#### Parameters:

| Name        | Type          |
| :---------- | :------------ |
| `apiClient` | AxiosInstance |

**Returns:** [_FeeAPI_](feeapi.md)

Defined in: [fee/FeeAPI.ts:20](https://github.com/bennycode/coinbase-pro-node/blob/baa73d4/src/fee/FeeAPI.ts#L20)

## Properties

### URL

▪ `Static` `Readonly` **URL**: _object_

#### Type declaration:

| Name   | Type     |
| :----- | :------- |
| `FEES` | _string_ |

Defined in: [fee/FeeAPI.ts:18](https://github.com/bennycode/coinbase-pro-node/blob/baa73d4/src/fee/FeeAPI.ts#L18)

## Methods

### getCurrentFees

▸ **getCurrentFees**(): _Promise_<[_FeeTier_](../interfaces/feetier.md)\>

Get your current maker & taker fee rates, as well as your 30-day trailing volume. Quoted rates are subject to change.

**`see`** https://docs.pro.coinbase.com/#fees

**`see`** https://help.coinbase.com/en/pro/trading-and-funding/trading-rules-and-fees/fees.html

**Returns:** _Promise_<[_FeeTier_](../interfaces/feetier.md)\>

Defined in: [fee/FeeAPI.ts:31](https://github.com/bennycode/coinbase-pro-node/blob/baa73d4/src/fee/FeeAPI.ts#L31)
