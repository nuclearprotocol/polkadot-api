[Polkadot JS API](../README.md) › [Globals](../globals.md) › ["packages/types/src/primitive/I128"](../modules/_packages_types_src_primitive_i128_.md) › [I128](_packages_types_src_primitive_i128_.i128.md)

# Class: I128

**`name`** I128

**`description`** 
A 128-bit signed integer

## Hierarchy

  ↳ [Int](_packages_types_src_codec_int_.int.md)

  ↳ **I128**

## Implements

* [Codec](../interfaces/_packages_types_src_types_codec_.codec.md)

## Index

### Interfaces

* [MPrime](../interfaces/_packages_types_src_primitive_i128_.i128.mprime.md)
* [ReductionContext](../interfaces/_packages_types_src_primitive_i128_.i128.reductioncontext.md)

### Type aliases

* [Endianness](_packages_types_src_primitive_i128_.i128.md#static-endianness)
* [IPrimeName](_packages_types_src_primitive_i128_.i128.md#static-iprimename)

### Constructors

* [constructor](_packages_types_src_primitive_i128_.i128.md#constructor)

### Methods

* [with](_packages_types_src_primitive_i128_.i128.md#static-with)

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

\+ **new I128**(`registry`: [Registry](../interfaces/_packages_types_src_types_registry_.registry.md), `value`: [AnyNumber](../modules/_packages_types_src_types_helpers_.md#anynumber), `bitLength`: [UIntBitLength](../modules/_packages_types_src_codec_abstractint_.md#uintbitlength), `isHexJson`: boolean): *[I128](_packages_types_src_primitive_i128_.i128.md)*

*Inherited from [Int](_packages_types_src_codec_int_.int.md).[constructor](_packages_types_src_codec_int_.int.md#constructor)*

*Overrides void*

*Defined in [packages/types/src/codec/Int.ts:19](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/Int.ts#L19)*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`registry` | [Registry](../interfaces/_packages_types_src_types_registry_.registry.md) | - |
`value` | [AnyNumber](../modules/_packages_types_src_types_helpers_.md#anynumber) | 0 |
`bitLength` | [UIntBitLength](../modules/_packages_types_src_codec_abstractint_.md#uintbitlength) | DEFAULT_UINT_BITS |
`isHexJson` | boolean | true |

**Returns:** *[I128](_packages_types_src_primitive_i128_.i128.md)*

## Methods

### `Static` with

▸ **with**(`bitLength`: [UIntBitLength](../modules/_packages_types_src_codec_abstractint_.md#uintbitlength), `typeName?`: undefined | string): *[Constructor](../interfaces/_packages_types_src_types_codec_.constructor.md)‹[Int](_packages_types_src_codec_int_.int.md)›*

*Inherited from [Int](_packages_types_src_codec_int_.int.md).[with](_packages_types_src_codec_int_.int.md#static-with)*

*Defined in [packages/types/src/codec/Int.ts:24](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/Int.ts#L24)*

**Parameters:**

Name | Type |
------ | ------ |
`bitLength` | [UIntBitLength](../modules/_packages_types_src_codec_abstractint_.md#uintbitlength) |
`typeName?` | undefined &#124; string |

**Returns:** *[Constructor](../interfaces/_packages_types_src_types_codec_.constructor.md)‹[Int](_packages_types_src_codec_int_.int.md)›*
