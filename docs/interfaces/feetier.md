[coinbase-pro-node](../README.md) / [Exports](../modules.md) / FeeTier

# Interface: FeeTier

Your fee tier is based upon total USD trading volume over the trailing 30 day period.

**`see`** https://help.coinbase.com/en/pro/trading-and-funding/trading-rules-and-fees/fees.html

## Table of contents

### Properties

- [maker_fee_rate](feetier.md#maker_fee_rate)
- [taker_fee_rate](feetier.md#taker_fee_rate)
- [usd_volume](feetier.md#usd_volume)

## Properties

### maker_fee_rate

• **maker_fee_rate**: _string_

A maker fee is paid when you create ("make") liquidity on the order book, i.e. you create an order which is not matched immediately.

Defined in: [fee/FeeAPI.ts:10](https://github.com/bennycode/coinbase-pro-node/blob/baa73d4/src/fee/FeeAPI.ts#L10)

---

### taker_fee_rate

• **taker_fee_rate**: _string_

A taker fee is paid when you remove ("take") liquidity from the order book, i.e. you create an order which matches an existing order (this includes all market orders).

Defined in: [fee/FeeAPI.ts:12](https://github.com/bennycode/coinbase-pro-node/blob/baa73d4/src/fee/FeeAPI.ts#L12)

---

### usd_volume

• **usd_volume**: `null` \| _string_

Your 30-day trailing volume which impacts your fee rates.

Defined in: [fee/FeeAPI.ts:14](https://github.com/bennycode/coinbase-pro-node/blob/baa73d4/src/fee/FeeAPI.ts#L14)
