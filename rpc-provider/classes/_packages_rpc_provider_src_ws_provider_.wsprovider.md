[Polkadot JS API](../README.md) › [Globals](../globals.md) › ["packages/rpc-provider/src/ws/Provider"](../modules/_packages_rpc_provider_src_ws_provider_.md) › [WsProvider](_packages_rpc_provider_src_ws_provider_.wsprovider.md)

# Class: WsProvider

# @polkadot/rpc-provider/ws

**`name`** WsProvider

**`description`** The WebSocket Provider allows sending requests using WebSocket to a WebSocket RPC server TCP port. Unlike the [[HttpProvider]], it does support subscriptions and allows listening to events such as new blocks or balance changes.

**`example`** 
<BR>

```javascript
import Api from '@polkadot/api/promise';
import WsProvider from '@polkadot/rpc-provider/ws';

const provider = new WsProvider('ws://127.0.0.1:9944');
const api = new Api(provider);
```

**`see`** [[HttpProvider]]

## Hierarchy

* **WsProvider**

## Implements

* WSProviderInterface

## Index

### Constructors

* [constructor](_packages_rpc_provider_src_ws_provider_.wsprovider.md#constructor)

### Accessors

* [hasSubscriptions](_packages_rpc_provider_src_ws_provider_.wsprovider.md#hassubscriptions)

### Methods

* [clone](_packages_rpc_provider_src_ws_provider_.wsprovider.md#clone)
* [connect](_packages_rpc_provider_src_ws_provider_.wsprovider.md#connect)
* [disconnect](_packages_rpc_provider_src_ws_provider_.wsprovider.md#disconnect)
* [isConnected](_packages_rpc_provider_src_ws_provider_.wsprovider.md#isconnected)
* [on](_packages_rpc_provider_src_ws_provider_.wsprovider.md#on)
* [send](_packages_rpc_provider_src_ws_provider_.wsprovider.md#send)
* [subscribe](_packages_rpc_provider_src_ws_provider_.wsprovider.md#subscribe)
* [unsubscribe](_packages_rpc_provider_src_ws_provider_.wsprovider.md#unsubscribe)

## Constructors

###  constructor

\+ **new WsProvider**(`endpoint`: string | string[], `autoConnectMs`: number | false, `headers`: Record‹string, string›): *[WsProvider](_packages_rpc_provider_src_ws_provider_.wsprovider.md)*

*Defined in [packages/rpc-provider/src/ws/Provider.ts:88](https://github.com/polkadot-js/api/blob/82e71fd51/packages/rpc-provider/src/ws/Provider.ts#L88)*

**Parameters:**

Name | Type | Default | Description |
------ | ------ | ------ | ------ |
`endpoint` | string &#124; string[] | defaults.WS_URL | The endpoint url. Usually `ws://ip:9944` or `wss://ip:9944`, may provide an array of endpoint strings. |
`autoConnectMs` | number &#124; false | 1000 | - |
`headers` | Record‹string, string› | {} | - |

**Returns:** *[WsProvider](_packages_rpc_provider_src_ws_provider_.wsprovider.md)*

## Accessors

###  hasSubscriptions

• **get hasSubscriptions**(): *boolean*

*Defined in [packages/rpc-provider/src/ws/Provider.ts:122](https://github.com/polkadot-js/api/blob/82e71fd51/packages/rpc-provider/src/ws/Provider.ts#L122)*

**`summary`** `true` when this provider supports subscriptions

**Returns:** *boolean*

## Methods

###  clone

▸ **clone**(): *[WsProvider](_packages_rpc_provider_src_ws_provider_.wsprovider.md)*

*Defined in [packages/rpc-provider/src/ws/Provider.ts:129](https://github.com/polkadot-js/api/blob/82e71fd51/packages/rpc-provider/src/ws/Provider.ts#L129)*

**`description`** Returns a clone of the object

**Returns:** *[WsProvider](_packages_rpc_provider_src_ws_provider_.wsprovider.md)*

___

###  connect

▸ **connect**(): *Promise‹void›*

*Defined in [packages/rpc-provider/src/ws/Provider.ts:138](https://github.com/polkadot-js/api/blob/82e71fd51/packages/rpc-provider/src/ws/Provider.ts#L138)*

**`summary`** Manually connect

**`description`** The [WsProvider](_packages_rpc_provider_src_ws_provider_.wsprovider.md) connects automatically by default, however if you decided otherwise, you may
connect manually using this method.

**Returns:** *Promise‹void›*

___

###  disconnect

▸ **disconnect**(): *void*

*Defined in [packages/rpc-provider/src/ws/Provider.ts:161](https://github.com/polkadot-js/api/blob/82e71fd51/packages/rpc-provider/src/ws/Provider.ts#L161)*

**`description`** Manually disconnect from the connection, clearing autoconnect logic

**Returns:** *void*

___

###  isConnected

▸ **isConnected**(): *boolean*

*Defined in [packages/rpc-provider/src/ws/Provider.ts:178](https://github.com/polkadot-js/api/blob/82e71fd51/packages/rpc-provider/src/ws/Provider.ts#L178)*

**`summary`** Whether the node is connected or not.

**Returns:** *boolean*

true if connected

___

###  on

▸ **on**(`type`: ProviderInterfaceEmitted, `sub`: ProviderInterfaceEmitCb): *function*

*Defined in [packages/rpc-provider/src/ws/Provider.ts:188](https://github.com/polkadot-js/api/blob/82e71fd51/packages/rpc-provider/src/ws/Provider.ts#L188)*

**`summary`** Listens on events after having subscribed using the [subscribe](_packages_rpc_provider_src_ws_provider_.wsprovider.md#subscribe) function.

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`type` | ProviderInterfaceEmitted | Event |
`sub` | ProviderInterfaceEmitCb | Callback |

**Returns:** *function*

unsubscribe function

▸ (): *void*

___

###  send

▸ **send**(`method`: string, `params`: any[], `subscription?`: SubscriptionHandler): *Promise‹any›*

*Defined in [packages/rpc-provider/src/ws/Provider.ts:202](https://github.com/polkadot-js/api/blob/82e71fd51/packages/rpc-provider/src/ws/Provider.ts#L202)*

**`summary`** Send JSON data using WebSockets to configured HTTP Endpoint or queue.

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`method` | string | The RPC methods to execute |
`params` | any[] | Encoded paramaters as appliucable for the method |
`subscription?` | SubscriptionHandler | Subscription details (internally used)  |

**Returns:** *Promise‹any›*

___

###  subscribe

▸ **subscribe**(`type`: string, `method`: string, `params`: any[], `callback`: ProviderInterfaceCallback): *Promise‹number | string›*

*Defined in [packages/rpc-provider/src/ws/Provider.ts:257](https://github.com/polkadot-js/api/blob/82e71fd51/packages/rpc-provider/src/ws/Provider.ts#L257)*

**`name`** subscribe

**`summary`** Allows subscribing to a specific event.

**`example`** 
<BR>

```javascript
const provider = new WsProvider('ws://127.0.0.1:9944');
const rpc = new Rpc(provider);

rpc.state.subscribeStorage([[storage.system.account, <Address>]], (_, values) => {
  console.log(values)
}).then((subscriptionId) => {
  console.log('balance changes subscription id: ', subscriptionId)
})
```

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`type` | string | Subscription type |
`method` | string | Subscription method |
`params` | any[] | Parameters |
`callback` | ProviderInterfaceCallback | Callback |

**Returns:** *Promise‹number | string›*

Promise resolving to the dd of the subscription you can use with [unsubscribe](_packages_rpc_provider_src_ws_provider_.wsprovider.md#unsubscribe).

___

###  unsubscribe

▸ **unsubscribe**(`type`: string, `method`: string, `id`: number | string): *Promise‹boolean›*

*Defined in [packages/rpc-provider/src/ws/Provider.ts:266](https://github.com/polkadot-js/api/blob/82e71fd51/packages/rpc-provider/src/ws/Provider.ts#L266)*

**`summary`** Allows unsubscribing to subscriptions made with [subscribe](_packages_rpc_provider_src_ws_provider_.wsprovider.md#subscribe).

**Parameters:**

Name | Type |
------ | ------ |
`type` | string |
`method` | string |
`id` | number &#124; string |

**Returns:** *Promise‹boolean›*
