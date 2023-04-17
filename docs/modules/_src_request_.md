**[pushover-js](../README.md)**

> [Globals](../globals.md) / "src/request"

# Module: "src/request"

## Index

### Classes

* [ResponseError](../classes/_src_request_.responseerror.md)

### Interfaces

* [IResponse](../interfaces/_src_request_.iresponse.md)

### Variables

* [https](_src_request_.md#https)

### Functions

* [processFile](_src_request_.md#processfile)
* [processParam](_src_request_.md#processparam)
* [responseCallback](_src_request_.md#responsecallback)

## Variables

### https

• `Const` **https**: any = require('https')

*Defined in [src/request.ts:4](https://github.com/spraot/pushover-js/blob/a89b195/src/request.ts#L4)*

## Functions

### processFile

▸ `Const`**processFile**(`file`: [INotificationFileData](../interfaces/_src_pushover_.inotificationfiledata.md), `boundary`: string): Promise\<Buffer>

*Defined in [src/request.ts:28](https://github.com/spraot/pushover-js/blob/a89b195/src/request.ts#L28)*

#### Parameters:

Name | Type |
------ | ------ |
`file` | [INotificationFileData](../interfaces/_src_pushover_.inotificationfiledata.md) |
`boundary` | string |

**Returns:** Promise\<Buffer>

___

### processParam

▸ `Const`**processParam**(`name`: string, `value`: string): Promise\<string>

*Defined in [src/request.ts:24](https://github.com/spraot/pushover-js/blob/a89b195/src/request.ts#L24)*

#### Parameters:

Name | Type |
------ | ------ |
`name` | string |
`value` | string |

**Returns:** Promise\<string>

___

### responseCallback

▸ `Const`**responseCallback**(`res`: IncomingMessage): Promise\<[IResponse](../interfaces/_src_request_.iresponse.md)>

*Defined in [src/request.ts:54](https://github.com/spraot/pushover-js/blob/a89b195/src/request.ts#L54)*

#### Parameters:

Name | Type |
------ | ------ |
`res` | IncomingMessage |

**Returns:** Promise\<[IResponse](../interfaces/_src_request_.iresponse.md)>
