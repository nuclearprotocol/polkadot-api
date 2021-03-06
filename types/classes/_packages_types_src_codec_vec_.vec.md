[Polkadot JS API](../README.md) › [Globals](../globals.md) › ["packages/types/src/codec/Vec"](../modules/_packages_types_src_codec_vec_.md) › [Vec](_packages_types_src_codec_vec_.vec.md)

# Class: Vec ‹**T**›

**`name`** Vec

**`description`** 
This manages codec arrays. Internally it keeps track of the length (as decoded) and allows
construction with the passed `Type` in the constructor. It is an extension to Array, providing
specific encoding/decoding on top of the base type.

## Type parameters

▪ **T**: *[Codec](../interfaces/_packages_types_src_types_codec_.codec.md)*

## Hierarchy

  ↳ [AbstractArray](_packages_types_src_codec_abstractarray_.abstractarray.md)‹T›

  ↳ **Vec**

## Implements

* [Codec](../interfaces/_packages_types_src_types_codec_.codec.md)

## Indexable

* \[ **n**: *number*\]: T

**`name`** Vec

**`description`** 
This manages codec arrays. Internally it keeps track of the length (as decoded) and allows
construction with the passed `Type` in the constructor. It is an extension to Array, providing
specific encoding/decoding on top of the base type.

## Index

### Constructors

* [constructor](_packages_types_src_codec_vec_.vec.md#constructor)

### Properties

* [registry](_packages_types_src_codec_vec_.vec.md#readonly-registry)

### Accessors

* [Type](_packages_types_src_codec_vec_.vec.md#type)
* [encodedLength](_packages_types_src_codec_vec_.vec.md#encodedlength)
* [hash](_packages_types_src_codec_vec_.vec.md#hash)
* [isEmpty](_packages_types_src_codec_vec_.vec.md#isempty)
* [length](_packages_types_src_codec_vec_.vec.md#length)

### Methods

* [eq](_packages_types_src_codec_vec_.vec.md#eq)
* [filter](_packages_types_src_codec_vec_.vec.md#filter)
* [includes](_packages_types_src_codec_vec_.vec.md#includes)
* [indexOf](_packages_types_src_codec_vec_.vec.md#indexof)
* [map](_packages_types_src_codec_vec_.vec.md#map)
* [toArray](_packages_types_src_codec_vec_.vec.md#toarray)
* [toHex](_packages_types_src_codec_vec_.vec.md#tohex)
* [toHuman](_packages_types_src_codec_vec_.vec.md#tohuman)
* [toJSON](_packages_types_src_codec_vec_.vec.md#tojson)
* [toRawType](_packages_types_src_codec_vec_.vec.md#torawtype)
* [toString](_packages_types_src_codec_vec_.vec.md#tostring)
* [toU8a](_packages_types_src_codec_vec_.vec.md#tou8a)
* [with](_packages_types_src_codec_vec_.vec.md#static-with)

## Constructors

###  constructor

\+ **new Vec**(`registry`: [Registry](../interfaces/_packages_types_src_types_registry_.registry.md), `Type`: [Constructor](../interfaces/_packages_types_src_types_codec_.constructor.md)‹T› | keyof InterfaceTypes, `value`: [Vec](_packages_types_src_codec_vec_.vec.md)‹[Codec](../interfaces/_packages_types_src_types_codec_.codec.md)› | [Uint8Array](_packages_types_src_codec_raw_.raw.md#static-uint8array) | string | unknown[]): *[Vec](_packages_types_src_codec_vec_.vec.md)*

*Overrides void*

*Defined in [packages/types/src/codec/Vec.ts:23](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/Vec.ts#L23)*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`registry` | [Registry](../interfaces/_packages_types_src_types_registry_.registry.md) | - |
`Type` | [Constructor](../interfaces/_packages_types_src_types_codec_.constructor.md)‹T› &#124; keyof InterfaceTypes | - |
`value` | [Vec](_packages_types_src_codec_vec_.vec.md)‹[Codec](../interfaces/_packages_types_src_types_codec_.codec.md)› &#124; [Uint8Array](_packages_types_src_codec_raw_.raw.md#static-uint8array) &#124; string &#124; unknown[] | [] |

**Returns:** *[Vec](_packages_types_src_codec_vec_.vec.md)*

## Properties

### `Readonly` registry

• **registry**: *[Registry](../interfaces/_packages_types_src_types_registry_.registry.md)*

*Implementation of [Codec](../interfaces/_packages_types_src_types_codec_.codec.md).[registry](../interfaces/_packages_types_src_types_codec_.codec.md#readonly-registry)*

*Inherited from [AbstractArray](_packages_types_src_codec_abstractarray_.abstractarray.md).[registry](_packages_types_src_codec_abstractarray_.abstractarray.md#readonly-registry)*

*Defined in [packages/types/src/codec/AbstractArray.ts:23](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/AbstractArray.ts#L23)*

## Accessors

###  Type

• **get Type**(): *string*

*Defined in [packages/types/src/codec/Vec.ts:69](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/Vec.ts#L69)*

**`description`** The type for the items

**Returns:** *string*

___

###  encodedLength

• **get encodedLength**(): *number*

*Inherited from [AbstractArray](_packages_types_src_codec_abstractarray_.abstractarray.md).[encodedLength](_packages_types_src_codec_abstractarray_.abstractarray.md#encodedlength)*

*Defined in [packages/types/src/codec/AbstractArray.ts:34](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/AbstractArray.ts#L34)*

**`description`** The length of the value when encoded as a Uint8Array

**Returns:** *number*

___

###  hash

• **get hash**(): *H256*

*Inherited from [AbstractArray](_packages_types_src_codec_abstractarray_.abstractarray.md).[hash](_packages_types_src_codec_abstractarray_.abstractarray.md#hash)*

*Defined in [packages/types/src/codec/AbstractArray.ts:43](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/AbstractArray.ts#L43)*

**`description`** returns a hash of the contents

**Returns:** *H256*

___

###  isEmpty

• **get isEmpty**(): *boolean*

*Inherited from [AbstractArray](_packages_types_src_codec_abstractarray_.abstractarray.md).[isEmpty](_packages_types_src_codec_abstractarray_.abstractarray.md#isempty)*

*Defined in [packages/types/src/codec/AbstractArray.ts:50](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/AbstractArray.ts#L50)*

**`description`** Checks if the value is an empty value

**Returns:** *boolean*

___

###  length

• **get length**(): *number*

*Inherited from [AbstractArray](_packages_types_src_codec_abstractarray_.abstractarray.md).[length](_packages_types_src_codec_abstractarray_.abstractarray.md#length)*

*Overrides void*

*Defined in [packages/types/src/codec/AbstractArray.ts:57](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/AbstractArray.ts#L57)*

**`description`** The length of the value

**Returns:** *number*

## Methods

###  eq

▸ **eq**(`other?`: unknown): *boolean*

*Implementation of [Codec](../interfaces/_packages_types_src_types_codec_.codec.md)*

*Inherited from [AbstractArray](_packages_types_src_codec_abstractarray_.abstractarray.md).[eq](_packages_types_src_codec_abstractarray_.abstractarray.md#eq)*

*Defined in [packages/types/src/codec/AbstractArray.ts:65](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/AbstractArray.ts#L65)*

**`description`** Compares the value of the input to see if there is a match

**Parameters:**

Name | Type |
------ | ------ |
`other?` | unknown |

**Returns:** *boolean*

___

###  filter

▸ **filter**(`callbackfn`: function, `thisArg?`: unknown): *T[]*

*Inherited from [AbstractArray](_packages_types_src_codec_abstractarray_.abstractarray.md).[filter](_packages_types_src_codec_abstractarray_.abstractarray.md#filter)*

*Overrides void*

*Defined in [packages/types/src/codec/AbstractArray.ts:144](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/AbstractArray.ts#L144)*

**`description`** Filters the array with the callback

**Parameters:**

▪ **callbackfn**: *function*

The filter function

▸ (`value`: T, `index`: number, `array`: T[]): *boolean*

**Parameters:**

Name | Type |
------ | ------ |
`value` | T |
`index` | number |
`array` | T[] |

▪`Optional`  **thisArg**: *unknown*

The `this` object to apply the result to

**Returns:** *T[]*

___

###  includes

▸ **includes**(`check`: unknown): *boolean*

*Inherited from [AbstractArray](_packages_types_src_codec_abstractarray_.abstractarray.md).[includes](_packages_types_src_codec_abstractarray_.abstractarray.md#includes)*

*Defined in [packages/types/src/codec/AbstractArray.ts:160](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/AbstractArray.ts#L160)*

**`description`** Checks if the array includes a specific value

**Parameters:**

Name | Type |
------ | ------ |
`check` | unknown |

**Returns:** *boolean*

___

###  indexOf

▸ **indexOf**(`_other?`: unknown): *number*

*Overrides void*

*Defined in [packages/types/src/codec/Vec.ts:76](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/Vec.ts#L76)*

**`description`** Finds the index of the value in the array

**Parameters:**

Name | Type |
------ | ------ |
`_other?` | unknown |

**Returns:** *number*

___

###  map

▸ **map**‹**U**›(`callbackfn`: function, `thisArg?`: unknown): *U[]*

*Inherited from [AbstractArray](_packages_types_src_codec_abstractarray_.abstractarray.md).[map](_packages_types_src_codec_abstractarray_.abstractarray.md#map)*

*Overrides void*

*Defined in [packages/types/src/codec/AbstractArray.ts:153](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/AbstractArray.ts#L153)*

**`description`** Maps the array with the callback

**Type parameters:**

▪ **U**

**Parameters:**

▪ **callbackfn**: *function*

The mapping function

▸ (`value`: T, `index`: number, `array`: T[]): *U*

**Parameters:**

Name | Type |
------ | ------ |
`value` | T |
`index` | number |
`array` | T[] |

▪`Optional`  **thisArg**: *unknown*

The `this` onject to apply the result to

**Returns:** *U[]*

___

###  toArray

▸ **toArray**(): *T[]*

*Inherited from [AbstractArray](_packages_types_src_codec_abstractarray_.abstractarray.md).[toArray](_packages_types_src_codec_abstractarray_.abstractarray.md#toarray)*

*Defined in [packages/types/src/codec/AbstractArray.ts:72](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/AbstractArray.ts#L72)*

**`description`** Converts the Object to an standard JavaScript Array

**Returns:** *T[]*

___

###  toHex

▸ **toHex**(): *string*

*Inherited from [AbstractArray](_packages_types_src_codec_abstractarray_.abstractarray.md).[toHex](_packages_types_src_codec_abstractarray_.abstractarray.md#tohex)*

*Defined in [packages/types/src/codec/AbstractArray.ts:79](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/AbstractArray.ts#L79)*

**`description`** Returns a hex string representation of the value

**Returns:** *string*

___

###  toHuman

▸ **toHuman**(`isExtended?`: undefined | false | true): *[AnyJson](../modules/_packages_types_src_types_helpers_.md#anyjson)*

*Implementation of [Codec](../interfaces/_packages_types_src_types_codec_.codec.md)*

*Inherited from [AbstractArray](_packages_types_src_codec_abstractarray_.abstractarray.md).[toHuman](_packages_types_src_codec_abstractarray_.abstractarray.md#tohuman)*

*Defined in [packages/types/src/codec/AbstractArray.ts:86](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/AbstractArray.ts#L86)*

**`description`** Converts the Object to to a human-friendly JSON, with additional fields, expansion and formatting of information

**Parameters:**

Name | Type |
------ | ------ |
`isExtended?` | undefined &#124; false &#124; true |

**Returns:** *[AnyJson](../modules/_packages_types_src_types_helpers_.md#anyjson)*

___

###  toJSON

▸ **toJSON**(): *[AnyJson](../modules/_packages_types_src_types_helpers_.md#anyjson)*

*Implementation of [Codec](../interfaces/_packages_types_src_types_codec_.codec.md)*

*Inherited from [AbstractArray](_packages_types_src_codec_abstractarray_.abstractarray.md).[toJSON](_packages_types_src_codec_abstractarray_.abstractarray.md#tojson)*

*Defined in [packages/types/src/codec/AbstractArray.ts:95](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/AbstractArray.ts#L95)*

**`description`** Converts the Object to JSON, typically used for RPC transfers

**Returns:** *[AnyJson](../modules/_packages_types_src_types_helpers_.md#anyjson)*

___

###  toRawType

▸ **toRawType**(): *string*

*Implementation of [Codec](../interfaces/_packages_types_src_types_codec_.codec.md)*

*Overrides [AbstractArray](_packages_types_src_codec_abstractarray_.abstractarray.md).[toRawType](_packages_types_src_codec_abstractarray_.abstractarray.md#abstract-torawtype)*

*Defined in [packages/types/src/codec/Vec.ts:94](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/Vec.ts#L94)*

**`description`** Returns the base runtime type name for this instance

**Returns:** *string*

___

###  toString

▸ **toString**(): *string*

*Implementation of [Codec](../interfaces/_packages_types_src_types_codec_.codec.md)*

*Inherited from [AbstractArray](_packages_types_src_codec_abstractarray_.abstractarray.md).[toString](_packages_types_src_codec_abstractarray_.abstractarray.md#tostring)*

*Overrides void*

*Defined in [packages/types/src/codec/AbstractArray.ts:109](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/AbstractArray.ts#L109)*

**`description`** Returns the string representation of the value

**Returns:** *string*

___

###  toU8a

▸ **toU8a**(`isBare?`: undefined | false | true): *[Uint8Array](_packages_types_src_codec_raw_.raw.md#static-uint8array)*

*Inherited from [AbstractArray](_packages_types_src_codec_abstractarray_.abstractarray.md).[toU8a](_packages_types_src_codec_abstractarray_.abstractarray.md#tou8a)*

*Defined in [packages/types/src/codec/AbstractArray.ts:122](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/AbstractArray.ts#L122)*

**`description`** Encodes the value as a Uint8Array as per the SCALE specifications

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`isBare?` | undefined &#124; false &#124; true | true when the value has none of the type-specific prefixes (internal)  |

**Returns:** *[Uint8Array](_packages_types_src_codec_raw_.raw.md#static-uint8array)*

___

### `Static` with

▸ **with**‹**O**›(`Type`: [Constructor](../interfaces/_packages_types_src_types_codec_.constructor.md)‹O› | keyof InterfaceTypes): *[Constructor](../interfaces/_packages_types_src_types_codec_.constructor.md)‹[Vec](_packages_types_src_codec_vec_.vec.md)‹O››*

*Defined in [packages/types/src/codec/Vec.ts:58](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/Vec.ts#L58)*

**Type parameters:**

▪ **O**: *[Codec](../interfaces/_packages_types_src_types_codec_.codec.md)*

**Parameters:**

Name | Type |
------ | ------ |
`Type` | [Constructor](../interfaces/_packages_types_src_types_codec_.constructor.md)‹O› &#124; keyof InterfaceTypes |

**Returns:** *[Constructor](../interfaces/_packages_types_src_types_codec_.constructor.md)‹[Vec](_packages_types_src_codec_vec_.vec.md)‹O››*
