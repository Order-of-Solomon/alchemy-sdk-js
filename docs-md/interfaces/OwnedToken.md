[alchemy-sdk](../README.md) / [Exports](../modules.md) / OwnedToken

# Interface: OwnedToken

Represents an owned token on a [GetTokensForOwnerResponse](GetTokensForOwnerResponse.md).

## Table of contents

### Properties

- [balance](OwnedToken.md#balance)
- [contractAddress](OwnedToken.md#contractaddress)
- [decimals](OwnedToken.md#decimals)
- [error](OwnedToken.md#error)
- [logo](OwnedToken.md#logo)
- [name](OwnedToken.md#name)
- [rawBalance](OwnedToken.md#rawbalance)
- [symbol](OwnedToken.md#symbol)

## Properties

### balance

• `Optional` **balance**: `string`

The formatted value of the balance field as a hex string. This value is
undefined if the [error](OwnedToken.md#error) field is present, or if the `decimals` field=
is undefined.

#### Defined in

[src/types/types.ts:212](https://github.com/alchemyplatform/alchemy-sdk-js/blob/7bf2430/src/types/types.ts#L212)

___

### contractAddress

• **contractAddress**: `string`

The contract address of the token.

#### Defined in

[src/types/types.ts:201](https://github.com/alchemyplatform/alchemy-sdk-js/blob/7bf2430/src/types/types.ts#L201)

___

### decimals

• `Optional` **decimals**: `number`

The number of decimals of the token. Is undefined if not defined in the
contract and not available from other sources.

#### Defined in

[src/types/types.ts:228](https://github.com/alchemyplatform/alchemy-sdk-js/blob/7bf2430/src/types/types.ts#L228)

___

### error

• `Optional` **error**: `string`

Error from fetching the token balances. If this field is defined, none of
the other fields will be defined.

#### Defined in

[src/types/types.ts:235](https://github.com/alchemyplatform/alchemy-sdk-js/blob/7bf2430/src/types/types.ts#L235)

___

### logo

• `Optional` **logo**: `string`

URL link to the token's logo. Is undefined if the logo is not available.

#### Defined in

[src/types/types.ts:230](https://github.com/alchemyplatform/alchemy-sdk-js/blob/7bf2430/src/types/types.ts#L230)

___

### name

• `Optional` **name**: `string`

The token's name. Is undefined if the name is not defined in the contract and
not available from other sources.

#### Defined in

[src/types/types.ts:218](https://github.com/alchemyplatform/alchemy-sdk-js/blob/7bf2430/src/types/types.ts#L218)

___

### rawBalance

• `Optional` **rawBalance**: `string`

The raw value of the balance field as a hex string. This value is undefined
if the [error](OwnedToken.md#error) field is present.

#### Defined in

[src/types/types.ts:206](https://github.com/alchemyplatform/alchemy-sdk-js/blob/7bf2430/src/types/types.ts#L206)

___

### symbol

• `Optional` **symbol**: `string`

The token's symbol. Is undefined if the symbol is not defined in the contract
and not available from other sources.

#### Defined in

[src/types/types.ts:223](https://github.com/alchemyplatform/alchemy-sdk-js/blob/7bf2430/src/types/types.ts#L223)
