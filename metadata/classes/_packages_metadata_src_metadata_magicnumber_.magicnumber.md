[Polkadot JS API](../README.md) › [Globals](../globals.md) › ["packages/metadata/src/Metadata/MagicNumber"](../modules/_packages_metadata_src_metadata_magicnumber_.md) › [MagicNumber](_packages_metadata_src_metadata_magicnumber_.magicnumber.md)

# Class: MagicNumber

## Hierarchy

* U32

  ↳ **MagicNumber**

## Implements

* Codec

## Index

### Interfaces

* [MPrime](../interfaces/_packages_metadata_src_metadata_magicnumber_.magicnumber.mprime.md)
* [ReductionContext](../interfaces/_packages_metadata_src_metadata_magicnumber_.magicnumber.reductioncontext.md)

### Type aliases

* [Endianness](_packages_metadata_src_metadata_magicnumber_.magicnumber.md#static-endianness)
* [IPrimeName](_packages_metadata_src_metadata_magicnumber_.magicnumber.md#static-iprimename)

### Constructors

* [constructor](_packages_metadata_src_metadata_magicnumber_.magicnumber.md#constructor)

### Properties

* [registry](_packages_metadata_src_metadata_magicnumber_.magicnumber.md#readonly-registry)

### Accessors

* [encodedLength](_packages_metadata_src_metadata_magicnumber_.magicnumber.md#encodedlength)
* [hash](_packages_metadata_src_metadata_magicnumber_.magicnumber.md#hash)
* [isEmpty](_packages_metadata_src_metadata_magicnumber_.magicnumber.md#isempty)
* [isUnsigned](_packages_metadata_src_metadata_magicnumber_.magicnumber.md#isunsigned)

### Methods

* [bitLength](_packages_metadata_src_metadata_magicnumber_.magicnumber.md#bitlength)
* [eq](_packages_metadata_src_metadata_magicnumber_.magicnumber.md#eq)
* [isMax](_packages_metadata_src_metadata_magicnumber_.magicnumber.md#ismax)
* [toBn](_packages_metadata_src_metadata_magicnumber_.magicnumber.md#tobn)
* [toHex](_packages_metadata_src_metadata_magicnumber_.magicnumber.md#tohex)
* [toHuman](_packages_metadata_src_metadata_magicnumber_.magicnumber.md#tohuman)
* [toJSON](_packages_metadata_src_metadata_magicnumber_.magicnumber.md#tojson)
* [toRawType](_packages_metadata_src_metadata_magicnumber_.magicnumber.md#torawtype)
* [toString](_packages_metadata_src_metadata_magicnumber_.magicnumber.md#tostring)
* [toU8a](_packages_metadata_src_metadata_magicnumber_.magicnumber.md#tou8a)
* [with](_packages_metadata_src_metadata_magicnumber_.magicnumber.md#static-with)

## Type aliases

### `Static` Endianness

Ƭ **Endianness**: *"le" | "be"*

Defined in node_modules/@types/bn.js/index.d.ts:11

___

### `Static` IPrimeName

Ƭ **IPrimeName**: *"k256" | "p224" | "p192" | "p25519"*

Defined in node_modules/@types/bn.js/index.d.ts:12

## Constructors

###  constructor

\+ **new MagicNumber**(`registry`: Registry, `value?`: AnyNumber): *[MagicNumber](_packages_metadata_src_metadata_magicnumber_.magicnumber.md)*

*Overrides void*

*Defined in [packages/metadata/src/Metadata/MagicNumber.ts:13](https://github.com/polkadot-js/api/blob/82e71fd51/packages/metadata/src/Metadata/MagicNumber.ts#L13)*

**Parameters:**

Name | Type |
------ | ------ |
`registry` | Registry |
`value?` | AnyNumber |

**Returns:** *[MagicNumber](_packages_metadata_src_metadata_magicnumber_.magicnumber.md)*

## Properties

### `Readonly` registry

• **registry**: *Registry*

*Inherited from [MagicNumber](_packages_metadata_src_metadata_magicnumber_.magicnumber.md).[registry](_packages_metadata_src_metadata_magicnumber_.magicnumber.md#readonly-registry)*

*Defined in [packages/types/src/codec/AbstractInt.ts:64](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/AbstractInt.ts#L64)*

## Accessors

###  encodedLength

• **get encodedLength**(): *number*

*Inherited from [MagicNumber](_packages_metadata_src_metadata_magicnumber_.magicnumber.md).[encodedLength](_packages_metadata_src_metadata_magicnumber_.magicnumber.md#encodedlength)*

*Defined in [packages/types/src/codec/AbstractInt.ts:87](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/AbstractInt.ts#L87)*

**`description`** The length of the value when encoded as a Uint8Array

**Returns:** *number*

___

###  hash

• **get hash**(): *H256*

*Inherited from [MagicNumber](_packages_metadata_src_metadata_magicnumber_.magicnumber.md).[hash](_packages_metadata_src_metadata_magicnumber_.magicnumber.md#hash)*

*Defined in [packages/types/src/codec/AbstractInt.ts:94](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/AbstractInt.ts#L94)*

**`description`** returns a hash of the contents

**Returns:** *H256*

___

###  isEmpty

• **get isEmpty**(): *boolean*

*Inherited from [MagicNumber](_packages_metadata_src_metadata_magicnumber_.magicnumber.md).[isEmpty](_packages_metadata_src_metadata_magicnumber_.magicnumber.md#isempty)*

*Defined in [packages/types/src/codec/AbstractInt.ts:101](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/AbstractInt.ts#L101)*

**`description`** Checks if the value is a zero value (align elsewhere)

**Returns:** *boolean*

___

###  isUnsigned

• **get isUnsigned**(): *boolean*

*Inherited from [MagicNumber](_packages_metadata_src_metadata_magicnumber_.magicnumber.md).[isUnsigned](_packages_metadata_src_metadata_magicnumber_.magicnumber.md#isunsigned)*

*Defined in [packages/types/src/codec/AbstractInt.ts:108](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/AbstractInt.ts#L108)*

**`description`** Checks if the value is an unsigned type

**Returns:** *boolean*

## Methods

###  bitLength

▸ **bitLength**(): *number*

*Inherited from [MagicNumber](_packages_metadata_src_metadata_magicnumber_.magicnumber.md).[bitLength](_packages_metadata_src_metadata_magicnumber_.magicnumber.md#bitlength)*

*Defined in [packages/types/src/codec/AbstractInt.ts:115](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/AbstractInt.ts#L115)*

**`description`** Returns the number of bits in the value

**Returns:** *number*

___

###  eq

▸ **eq**(`other?`: unknown): *boolean*

*Inherited from [MagicNumber](_packages_metadata_src_metadata_magicnumber_.magicnumber.md).[eq](_packages_metadata_src_metadata_magicnumber_.magicnumber.md#eq)*

*Defined in [packages/types/src/codec/AbstractInt.ts:123](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/AbstractInt.ts#L123)*

**`description`** Compares the value of the input to see if there is a match

**Parameters:**

Name | Type |
------ | ------ |
`other?` | unknown |

**Returns:** *boolean*

___

###  isMax

▸ **isMax**(): *boolean*

*Inherited from [MagicNumber](_packages_metadata_src_metadata_magicnumber_.magicnumber.md).[isMax](_packages_metadata_src_metadata_magicnumber_.magicnumber.md#ismax)*

*Defined in [packages/types/src/codec/AbstractInt.ts:136](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/AbstractInt.ts#L136)*

**`description`** True if this value is the max of the type

**Returns:** *boolean*

___

###  toBn

▸ **toBn**(): *BN*

*Inherited from [MagicNumber](_packages_metadata_src_metadata_magicnumber_.magicnumber.md).[toBn](_packages_metadata_src_metadata_magicnumber_.magicnumber.md#tobn)*

*Defined in [packages/types/src/codec/AbstractInt.ts:145](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/AbstractInt.ts#L145)*

**`description`** Returns the BN representation of the number. (Compatibility)

**Returns:** *BN*

___

###  toHex

▸ **toHex**(`isLe`: boolean): *string*

*Inherited from [MagicNumber](_packages_metadata_src_metadata_magicnumber_.magicnumber.md).[toHex](_packages_metadata_src_metadata_magicnumber_.magicnumber.md#tohex)*

*Defined in [packages/types/src/codec/AbstractInt.ts:152](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/AbstractInt.ts#L152)*

**`description`** Returns a hex string representation of the value

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`isLe` | boolean | false |

**Returns:** *string*

___

###  toHuman

▸ **toHuman**(`isExpanded?`: undefined | false | true): *string*

*Inherited from [MagicNumber](_packages_metadata_src_metadata_magicnumber_.magicnumber.md).[toHuman](_packages_metadata_src_metadata_magicnumber_.magicnumber.md#tohuman)*

*Defined in [packages/types/src/codec/AbstractInt.ts:165](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/AbstractInt.ts#L165)*

**`description`** Converts the Object to to a human-friendly JSON, with additional fields, expansion and formatting of information

**Parameters:**

Name | Type |
------ | ------ |
`isExpanded?` | undefined &#124; false &#124; true |

**Returns:** *string*

___

###  toJSON

▸ **toJSON**(): *any*

*Inherited from [MagicNumber](_packages_metadata_src_metadata_magicnumber_.magicnumber.md).[toJSON](_packages_metadata_src_metadata_magicnumber_.magicnumber.md#tojson)*

*Defined in [packages/types/src/codec/AbstractInt.ts:181](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/AbstractInt.ts#L181)*

**`description`** Converts the Object to JSON, typically used for RPC transfers

**Returns:** *any*

___

###  toRawType

▸ **toRawType**(): *string*

*Inherited from [MagicNumber](_packages_metadata_src_metadata_magicnumber_.magicnumber.md).[toRawType](_packages_metadata_src_metadata_magicnumber_.magicnumber.md#torawtype)*

*Defined in [packages/types/src/codec/AbstractInt.ts:193](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/AbstractInt.ts#L193)*

**`description`** Returns the base runtime type name for this instance

**Returns:** *string*

___

###  toString

▸ **toString**(`base?`: undefined | number): *string*

*Inherited from [MagicNumber](_packages_metadata_src_metadata_magicnumber_.magicnumber.md).[toString](_packages_metadata_src_metadata_magicnumber_.magicnumber.md#tostring)*

*Defined in [packages/types/src/codec/AbstractInt.ts:206](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/AbstractInt.ts#L206)*

**`description`** Returns the string representation of the value

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`base?` | undefined &#124; number | The base to use for the conversion  |

**Returns:** *string*

___

###  toU8a

▸ **toU8a**(`isBare?`: undefined | false | true): *Uint8Array*

*Inherited from [MagicNumber](_packages_metadata_src_metadata_magicnumber_.magicnumber.md).[toU8a](_packages_metadata_src_metadata_magicnumber_.magicnumber.md#tou8a)*

*Defined in [packages/types/src/codec/AbstractInt.ts:216](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/AbstractInt.ts#L216)*

**`description`** Encodes the value as a Uint8Array as per the SCALE specifications

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`isBare?` | undefined &#124; false &#124; true | true when the value has none of the type-specific prefixes (internal)  |

**Returns:** *Uint8Array*

___

### `Static` with

▸ **with**(`bitLength`: UIntBitLength, `typeName?`: undefined | string): *Constructor‹UInt›*

*Inherited from [MagicNumber](_packages_metadata_src_metadata_magicnumber_.magicnumber.md).[with](_packages_metadata_src_metadata_magicnumber_.magicnumber.md#static-with)*

*Defined in [packages/types/src/codec/UInt.ts:24](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/UInt.ts#L24)*

**Parameters:**

Name | Type |
------ | ------ |
`bitLength` | UIntBitLength |
`typeName?` | undefined &#124; string |

**Returns:** *Constructor‹UInt›*
