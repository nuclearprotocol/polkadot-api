[Polkadot JS API](../README.md) › [Globals](../globals.md) › ["packages/api-derive/src/type/HeaderExtended"](../modules/_packages_api_derive_src_type_headerextended_.md) › [HeaderExtended](_packages_api_derive_src_type_headerextended_.headerextended.md)

# Class: HeaderExtended ‹**S, T, V, E**›

**`name`** HeaderExtended

**`description`** 
A [[Block]] header with an additional `author` field that indicates the block author

## Type parameters

▪ **S**: *TypesDef*

▪ **T**: *object*

▪ **V**: *object*

▪ **E**: *object*

## Hierarchy

* Header

  ↳ **HeaderExtended**

## Implements

* Codec

## Index

### Constructors

* [constructor](_packages_api_derive_src_type_headerextended_.headerextended.md#constructor)

### Properties

* [digest](_packages_api_derive_src_type_headerextended_.headerextended.md#readonly-digest)
* [extrinsicsRoot](_packages_api_derive_src_type_headerextended_.headerextended.md#readonly-extrinsicsroot)
* [number](_packages_api_derive_src_type_headerextended_.headerextended.md#readonly-number)
* [parentHash](_packages_api_derive_src_type_headerextended_.headerextended.md#readonly-parenthash)
* [registry](_packages_api_derive_src_type_headerextended_.headerextended.md#readonly-registry)
* [size](_packages_api_derive_src_type_headerextended_.headerextended.md#readonly-size)
* [stateRoot](_packages_api_derive_src_type_headerextended_.headerextended.md#readonly-stateroot)

### Accessors

* [Type](_packages_api_derive_src_type_headerextended_.headerextended.md#type)
* [author](_packages_api_derive_src_type_headerextended_.headerextended.md#author)
* [defKeys](_packages_api_derive_src_type_headerextended_.headerextended.md#defkeys)
* [encodedLength](_packages_api_derive_src_type_headerextended_.headerextended.md#encodedlength)
* [hash](_packages_api_derive_src_type_headerextended_.headerextended.md#hash)
* [isEmpty](_packages_api_derive_src_type_headerextended_.headerextended.md#isempty)

### Methods

* [clear](_packages_api_derive_src_type_headerextended_.headerextended.md#clear)
* [delete](_packages_api_derive_src_type_headerextended_.headerextended.md#delete)
* [eq](_packages_api_derive_src_type_headerextended_.headerextended.md#eq)
* [forEach](_packages_api_derive_src_type_headerextended_.headerextended.md#foreach)
* [get](_packages_api_derive_src_type_headerextended_.headerextended.md#get)
* [getAtIndex](_packages_api_derive_src_type_headerextended_.headerextended.md#getatindex)
* [has](_packages_api_derive_src_type_headerextended_.headerextended.md#has)
* [set](_packages_api_derive_src_type_headerextended_.headerextended.md#set)
* [toArray](_packages_api_derive_src_type_headerextended_.headerextended.md#toarray)
* [toHex](_packages_api_derive_src_type_headerextended_.headerextended.md#tohex)
* [toHuman](_packages_api_derive_src_type_headerextended_.headerextended.md#tohuman)
* [toJSON](_packages_api_derive_src_type_headerextended_.headerextended.md#tojson)
* [toRawType](_packages_api_derive_src_type_headerextended_.headerextended.md#torawtype)
* [toString](_packages_api_derive_src_type_headerextended_.headerextended.md#tostring)
* [toU8a](_packages_api_derive_src_type_headerextended_.headerextended.md#tou8a)
* [typesToMap](_packages_api_derive_src_type_headerextended_.headerextended.md#static-typestomap)
* [with](_packages_api_derive_src_type_headerextended_.headerextended.md#static-with)

## Constructors

###  constructor

\+ **new HeaderExtended**(`registry`: Registry, `header?`: Header, `sessionValidators?`: AccountId[]): *[HeaderExtended](_packages_api_derive_src_type_headerextended_.headerextended.md)*

*Overrides void*

*Defined in [packages/api-derive/src/type/HeaderExtended.ts:20](https://github.com/polkadot-js/api/blob/82e71fd51/packages/api-derive/src/type/HeaderExtended.ts#L20)*

**Parameters:**

Name | Type |
------ | ------ |
`registry` | Registry |
`header?` | Header |
`sessionValidators?` | AccountId[] |

**Returns:** *[HeaderExtended](_packages_api_derive_src_type_headerextended_.headerextended.md)*

## Properties

### `Readonly` digest

• **digest**: *Digest*

*Inherited from [HeaderExtended](_packages_api_derive_src_type_headerextended_.headerextended.md).[digest](_packages_api_derive_src_type_headerextended_.headerextended.md#readonly-digest)*

*Defined in [packages/types/src/interfaces/runtime/types.ts:124](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/interfaces/runtime/types.ts#L124)*

___

### `Readonly` extrinsicsRoot

• **extrinsicsRoot**: *Hash*

*Inherited from [HeaderExtended](_packages_api_derive_src_type_headerextended_.headerextended.md).[extrinsicsRoot](_packages_api_derive_src_type_headerextended_.headerextended.md#readonly-extrinsicsroot)*

*Defined in [packages/types/src/interfaces/runtime/types.ts:123](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/interfaces/runtime/types.ts#L123)*

___

### `Readonly` number

• **number**: *Compact‹BlockNumber›*

*Inherited from [HeaderExtended](_packages_api_derive_src_type_headerextended_.headerextended.md).[number](_packages_api_derive_src_type_headerextended_.headerextended.md#readonly-number)*

*Defined in [packages/types/src/interfaces/runtime/types.ts:121](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/interfaces/runtime/types.ts#L121)*

___

### `Readonly` parentHash

• **parentHash**: *Hash*

*Inherited from [HeaderExtended](_packages_api_derive_src_type_headerextended_.headerextended.md).[parentHash](_packages_api_derive_src_type_headerextended_.headerextended.md#readonly-parenthash)*

*Defined in [packages/types/src/interfaces/runtime/types.ts:120](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/interfaces/runtime/types.ts#L120)*

___

### `Readonly` registry

• **registry**: *Registry*

*Inherited from [HeaderExtended](_packages_api_derive_src_type_headerextended_.headerextended.md).[registry](_packages_api_derive_src_type_headerextended_.headerextended.md#readonly-registry)*

*Defined in [packages/types/src/codec/Struct.ts:112](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/Struct.ts#L112)*

___

### `Readonly` size

• **size**: *number*

*Inherited from [HeaderExtended](_packages_api_derive_src_type_headerextended_.headerextended.md).[size](_packages_api_derive_src_type_headerextended_.headerextended.md#readonly-size)*

Defined in node_modules/typescript/lib/lib.es2015.collection.d.ts:28

___

### `Readonly` stateRoot

• **stateRoot**: *Hash*

*Inherited from [HeaderExtended](_packages_api_derive_src_type_headerextended_.headerextended.md).[stateRoot](_packages_api_derive_src_type_headerextended_.headerextended.md#readonly-stateroot)*

*Defined in [packages/types/src/interfaces/runtime/types.ts:122](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/interfaces/runtime/types.ts#L122)*

## Accessors

###  Type

• **get Type**(): *E*

*Inherited from [HeaderExtended](_packages_api_derive_src_type_headerextended_.headerextended.md).[Type](_packages_api_derive_src_type_headerextended_.headerextended.md#type)*

*Defined in [packages/types/src/codec/Struct.ts:175](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/Struct.ts#L175)*

**`description`** Returns the Type description to sthe structure

**Returns:** *E*

___

###  author

• **get author**(): *AccountId | undefined*

*Defined in [packages/api-derive/src/type/HeaderExtended.ts:53](https://github.com/polkadot-js/api/blob/82e71fd51/packages/api-derive/src/type/HeaderExtended.ts#L53)*

**`description`** Convenience method, returns the author for the block

**Returns:** *AccountId | undefined*

___

###  defKeys

• **get defKeys**(): *string[]*

*Inherited from [HeaderExtended](_packages_api_derive_src_type_headerextended_.headerextended.md).[defKeys](_packages_api_derive_src_type_headerextended_.headerextended.md#defkeys)*

*Defined in [packages/types/src/codec/Struct.ts:153](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/Struct.ts#L153)*

**`description`** The available keys for this enum

**Returns:** *string[]*

___

###  encodedLength

• **get encodedLength**(): *number*

*Inherited from [HeaderExtended](_packages_api_derive_src_type_headerextended_.headerextended.md).[encodedLength](_packages_api_derive_src_type_headerextended_.headerextended.md#encodedlength)*

*Defined in [packages/types/src/codec/Struct.ts:189](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/Struct.ts#L189)*

**`description`** The length of the value when encoded as a Uint8Array

**Returns:** *number*

___

###  hash

• **get hash**(): *H256*

*Inherited from [HeaderExtended](_packages_api_derive_src_type_headerextended_.headerextended.md).[hash](_packages_api_derive_src_type_headerextended_.headerextended.md#hash)*

*Defined in [packages/types/src/codec/Struct.ts:200](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/Struct.ts#L200)*

**`description`** returns a hash of the contents

**Returns:** *H256*

___

###  isEmpty

• **get isEmpty**(): *boolean*

*Inherited from [HeaderExtended](_packages_api_derive_src_type_headerextended_.headerextended.md).[isEmpty](_packages_api_derive_src_type_headerextended_.headerextended.md#isempty)*

*Defined in [packages/types/src/codec/Struct.ts:160](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/Struct.ts#L160)*

**`description`** Checks if the value is an empty value

**Returns:** *boolean*

## Methods

###  clear

▸ **clear**(): *void*

*Inherited from [HeaderExtended](_packages_api_derive_src_type_headerextended_.headerextended.md).[clear](_packages_api_derive_src_type_headerextended_.headerextended.md#clear)*

Defined in node_modules/typescript/lib/lib.es2015.collection.d.ts:22

**Returns:** *void*

___

###  delete

▸ **delete**(`key`: keyof S): *boolean*

*Inherited from [HeaderExtended](_packages_api_derive_src_type_headerextended_.headerextended.md).[delete](_packages_api_derive_src_type_headerextended_.headerextended.md#delete)*

Defined in node_modules/typescript/lib/lib.es2015.collection.d.ts:23

**Parameters:**

Name | Type |
------ | ------ |
`key` | keyof S |

**Returns:** *boolean*

___

###  eq

▸ **eq**(`other?`: unknown): *boolean*

*Inherited from [HeaderExtended](_packages_api_derive_src_type_headerextended_.headerextended.md).[eq](_packages_api_derive_src_type_headerextended_.headerextended.md#eq)*

*Defined in [packages/types/src/codec/Struct.ts:207](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/Struct.ts#L207)*

**`description`** Compares the value of the input to see if there is a match

**Parameters:**

Name | Type |
------ | ------ |
`other?` | unknown |

**Returns:** *boolean*

___

###  forEach

▸ **forEach**(`callbackfn`: function, `thisArg?`: any): *void*

*Inherited from [HeaderExtended](_packages_api_derive_src_type_headerextended_.headerextended.md).[forEach](_packages_api_derive_src_type_headerextended_.headerextended.md#foreach)*

Defined in node_modules/typescript/lib/lib.es2015.collection.d.ts:24

**Parameters:**

▪ **callbackfn**: *function*

▸ (`value`: Codec, `key`: keyof S, `map`: Map‹keyof S, Codec›): *void*

**Parameters:**

Name | Type |
------ | ------ |
`value` | Codec |
`key` | keyof S |
`map` | Map‹keyof S, Codec› |

▪`Optional`  **thisArg**: *any*

**Returns:** *void*

___

###  get

▸ **get**(`name`: keyof S): *Codec | undefined*

*Inherited from [HeaderExtended](_packages_api_derive_src_type_headerextended_.headerextended.md).[get](_packages_api_derive_src_type_headerextended_.headerextended.md#get)*

*Overrides void*

*Defined in [packages/types/src/codec/Struct.ts:215](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/Struct.ts#L215)*

**`description`** Returns a specific names entry in the structure

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`name` | keyof S | The name of the entry to retrieve  |

**Returns:** *Codec | undefined*

___

###  getAtIndex

▸ **getAtIndex**(`index`: number): *Codec*

*Inherited from [HeaderExtended](_packages_api_derive_src_type_headerextended_.headerextended.md).[getAtIndex](_packages_api_derive_src_type_headerextended_.headerextended.md#getatindex)*

*Defined in [packages/types/src/codec/Struct.ts:222](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/Struct.ts#L222)*

**`description`** Returns the values of a member at a specific index (Rather use get(name) for performance)

**Parameters:**

Name | Type |
------ | ------ |
`index` | number |

**Returns:** *Codec*

___

###  has

▸ **has**(`key`: keyof S): *boolean*

*Inherited from [HeaderExtended](_packages_api_derive_src_type_headerextended_.headerextended.md).[has](_packages_api_derive_src_type_headerextended_.headerextended.md#has)*

Defined in node_modules/typescript/lib/lib.es2015.collection.d.ts:26

**Parameters:**

Name | Type |
------ | ------ |
`key` | keyof S |

**Returns:** *boolean*

___

###  set

▸ **set**(`key`: keyof S, `value`: Codec): *this*

*Inherited from [HeaderExtended](_packages_api_derive_src_type_headerextended_.headerextended.md).[set](_packages_api_derive_src_type_headerextended_.headerextended.md#set)*

Defined in node_modules/typescript/lib/lib.es2015.collection.d.ts:27

**Parameters:**

Name | Type |
------ | ------ |
`key` | keyof S |
`value` | Codec |

**Returns:** *this*

___

###  toArray

▸ **toArray**(): *Codec[]*

*Inherited from [HeaderExtended](_packages_api_derive_src_type_headerextended_.headerextended.md).[toArray](_packages_api_derive_src_type_headerextended_.headerextended.md#toarray)*

*Defined in [packages/types/src/codec/Struct.ts:229](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/Struct.ts#L229)*

**`description`** Converts the Object to an standard JavaScript Array

**Returns:** *Codec[]*

___

###  toHex

▸ **toHex**(): *string*

*Inherited from [HeaderExtended](_packages_api_derive_src_type_headerextended_.headerextended.md).[toHex](_packages_api_derive_src_type_headerextended_.headerextended.md#tohex)*

*Defined in [packages/types/src/codec/Struct.ts:236](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/Struct.ts#L236)*

**`description`** Returns a hex string representation of the value

**Returns:** *string*

___

###  toHuman

▸ **toHuman**(`isExtended?`: undefined | false | true): *AnyJson*

*Overrides void*

*Defined in [packages/api-derive/src/type/HeaderExtended.ts:60](https://github.com/polkadot-js/api/blob/82e71fd51/packages/api-derive/src/type/HeaderExtended.ts#L60)*

**`description`** Creates a human-friendly JSON representation

**Parameters:**

Name | Type |
------ | ------ |
`isExtended?` | undefined &#124; false &#124; true |

**Returns:** *AnyJson*

___

###  toJSON

▸ **toJSON**(): *AnyJson*

*Overrides void*

*Defined in [packages/api-derive/src/type/HeaderExtended.ts:72](https://github.com/polkadot-js/api/blob/82e71fd51/packages/api-derive/src/type/HeaderExtended.ts#L72)*

**`description`** Creates the JSON representation

**Returns:** *AnyJson*

___

###  toRawType

▸ **toRawType**(): *string*

*Inherited from [HeaderExtended](_packages_api_derive_src_type_headerextended_.headerextended.md).[toRawType](_packages_api_derive_src_type_headerextended_.headerextended.md#torawtype)*

*Defined in [packages/types/src/codec/Struct.ts:280](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/Struct.ts#L280)*

**`description`** Returns the base runtime type name for this instance

**Returns:** *string*

___

###  toString

▸ **toString**(): *string*

*Inherited from [HeaderExtended](_packages_api_derive_src_type_headerextended_.headerextended.md).[toString](_packages_api_derive_src_type_headerextended_.headerextended.md#tostring)*

*Defined in [packages/types/src/codec/Struct.ts:289](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/Struct.ts#L289)*

**`description`** Returns the string representation of the value

**Returns:** *string*

___

###  toU8a

▸ **toU8a**(`isBare?`: BareOpts): *Uint8Array*

*Inherited from [HeaderExtended](_packages_api_derive_src_type_headerextended_.headerextended.md).[toU8a](_packages_api_derive_src_type_headerextended_.headerextended.md#tou8a)*

*Defined in [packages/types/src/codec/Struct.ts:297](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/Struct.ts#L297)*

**`description`** Encodes the value as a Uint8Array as per the SCALE specifications

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`isBare?` | BareOpts | true when the value has none of the type-specific prefixes (internal)  |

**Returns:** *Uint8Array*

___

### `Static` typesToMap

▸ **typesToMap**(`registry`: Registry, `Types`: Record‹string, Constructor›): *Record‹string, string›*

*Inherited from [HeaderExtended](_packages_api_derive_src_type_headerextended_.headerextended.md).[typesToMap](_packages_api_derive_src_type_headerextended_.headerextended.md#static-typestomap)*

*Defined in [packages/types/src/codec/Struct.ts:269](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/Struct.ts#L269)*

**Parameters:**

Name | Type |
------ | ------ |
`registry` | Registry |
`Types` | Record‹string, Constructor› |

**Returns:** *Record‹string, string›*

___

### `Static` with

▸ **with**‹**S**›(`Types`: S, `jsonMap?`: Map‹keyof S, string›): *Constructor‹Struct‹S››*

*Inherited from [HeaderExtended](_packages_api_derive_src_type_headerextended_.headerextended.md).[with](_packages_api_derive_src_type_headerextended_.headerextended.md#static-with)*

*Defined in [packages/types/src/codec/Struct.ts:129](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/Struct.ts#L129)*

**Type parameters:**

▪ **S**: *TypesDef*

**Parameters:**

Name | Type |
------ | ------ |
`Types` | S |
`jsonMap?` | Map‹keyof S, string› |

**Returns:** *Constructor‹Struct‹S››*
