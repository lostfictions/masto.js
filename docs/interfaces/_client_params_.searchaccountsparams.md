[masto](../README.md) > ["client/params"](../modules/_client_params_.md) > [SearchAccountsParams](../interfaces/_client_params_.searchaccountsparams.md)

# Interface: SearchAccountsParams

## Hierarchy

↳  [SearchParams](_client_params_.searchparams.md)

**↳ SearchAccountsParams**

## Index

### Properties

* [account_id](_client_params_.searchaccountsparams.md#account_id)
* [following](_client_params_.searchaccountsparams.md#following)
* [limit](_client_params_.searchaccountsparams.md#limit)
* [max_id](_client_params_.searchaccountsparams.md#max_id)
* [min_id](_client_params_.searchaccountsparams.md#min_id)
* [q](_client_params_.searchaccountsparams.md#q)
* [resolve](_client_params_.searchaccountsparams.md#resolve)
* [since_id](_client_params_.searchaccountsparams.md#since_id)

---

## Properties

<a id="account_id"></a>

### `<Optional>` account_id

**● account_id**: *`undefined` \| `string`*

*Inherited from [SearchParams](_client_params_.searchparams.md).[account_id](_client_params_.searchparams.md#account_id)*

*Defined in [client/params.ts:201](https://github.com/neet/masto.js/blob/c1501e9/src/client/params.ts#L201)*

Account id to search

___
<a id="following"></a>

### `<Optional>` following

**● following**: *`boolean` \| `null`*

*Defined in [client/params.ts:208](https://github.com/neet/masto.js/blob/c1501e9/src/client/params.ts#L208)*

Only who the user is following

___
<a id="limit"></a>

### `<Optional>` limit

**● limit**: *`number` \| `null`*

*Overrides [PaginationParams](_client_params_.paginationparams.md).[limit](_client_params_.paginationparams.md#limit)*

*Defined in [client/params.ts:206](https://github.com/neet/masto.js/blob/c1501e9/src/client/params.ts#L206)*

Maximum number of matching accounts to return (default: `40`)

___
<a id="max_id"></a>

### `<Optional>` max_id

**● max_id**: *`string` \| `null`*

*Inherited from [PaginationParams](_client_params_.paginationparams.md).[max_id](_client_params_.paginationparams.md#max_id)*

*Defined in [client/params.ts:13](https://github.com/neet/masto.js/blob/c1501e9/src/client/params.ts#L13)*

Get a list of items with ID less than this value

___
<a id="min_id"></a>

### `<Optional>` min_id

**● min_id**: *`string` \| `null`*

*Inherited from [PaginationParams](_client_params_.paginationparams.md).[min_id](_client_params_.paginationparams.md#min_id)*

*Defined in [client/params.ts:17](https://github.com/neet/masto.js/blob/c1501e9/src/client/params.ts#L17)*

Get a list of items with ID greater than this value exluding this ID

___
<a id="q"></a>

###  q

**● q**: *`string`*

*Inherited from [SearchParams](_client_params_.searchparams.md).[q](_client_params_.searchparams.md#q)*

*Defined in [client/params.ts:197](https://github.com/neet/masto.js/blob/c1501e9/src/client/params.ts#L197)*

The search query

___
<a id="resolve"></a>

### `<Optional>` resolve

**● resolve**: *`boolean` \| `null`*

*Inherited from [SearchParams](_client_params_.searchparams.md).[resolve](_client_params_.searchparams.md#resolve)*

*Defined in [client/params.ts:199](https://github.com/neet/masto.js/blob/c1501e9/src/client/params.ts#L199)*

Attempt WebFinger look-up

___
<a id="since_id"></a>

### `<Optional>` since_id

**● since_id**: *`string` \| `null`*

*Inherited from [PaginationParams](_client_params_.paginationparams.md).[since_id](_client_params_.paginationparams.md#since_id)*

*Defined in [client/params.ts:15](https://github.com/neet/masto.js/blob/c1501e9/src/client/params.ts#L15)*

Get a list of items with ID greater than this value including this ID

___

