**[pushover-js](../README.md)**

> [Globals](../globals.md) / ["src/pushover"](../modules/_src_pushover_.md) / Pushover

# Class: Pushover

## Hierarchy

* **Pushover**

## Index

### Constructors

* [constructor](_src_pushover_.pushover.md#constructor)

### Properties

* [\_hostname](_src_pushover_.pushover.md#_hostname)
* [\_path](_src_pushover_.pushover.md#_path)

### Methods

* [send](_src_pushover_.pushover.md#send)
* [setAttachment](_src_pushover_.pushover.md#setattachment)
* [setAttachmentFromBuffer](_src_pushover_.pushover.md#setattachmentfrombuffer)
* [setDevice](_src_pushover_.pushover.md#setdevice)
* [setHtml](_src_pushover_.pushover.md#sethtml)
* [setMessage](_src_pushover_.pushover.md#setmessage)
* [setPriority](_src_pushover_.pushover.md#setpriority)
* [setSound](_src_pushover_.pushover.md#setsound)
* [setTimestamp](_src_pushover_.pushover.md#settimestamp)
* [setTitle](_src_pushover_.pushover.md#settitle)
* [setUrl](_src_pushover_.pushover.md#seturl)

### Object literals

* [\_notification](_src_pushover_.pushover.md#_notification)

## Constructors

### constructor

\+ **new Pushover**(`user`: string, `token`: string): [Pushover](_src_pushover_.pushover.md)

*Defined in [src/pushover.ts:67](https://github.com/spraot/pushover-js/blob/a89b195/src/pushover.ts#L67)*

#### Parameters:

Name | Type |
------ | ------ |
`user` | string |
`token` | string |

**Returns:** [Pushover](_src_pushover_.pushover.md)

## Properties

### \_hostname

• `Private` **\_hostname**: string = "api.pushover.net"

*Defined in [src/pushover.ts:55](https://github.com/spraot/pushover-js/blob/a89b195/src/pushover.ts#L55)*

___

### \_path

• `Private` **\_path**: string = "/1/messages.json"

*Defined in [src/pushover.ts:56](https://github.com/spraot/pushover-js/blob/a89b195/src/pushover.ts#L56)*

## Methods

### send

▸ **send**(`title?`: undefined \| string, `message?`: undefined \| string): Promise\<[IResponse](../interfaces/_src_request_.iresponse.md)>

*Defined in [src/pushover.ts:142](https://github.com/spraot/pushover-js/blob/a89b195/src/pushover.ts#L142)*

#### Parameters:

Name | Type |
------ | ------ |
`title?` | undefined \| string |
`message?` | undefined \| string |

**Returns:** Promise\<[IResponse](../interfaces/_src_request_.iresponse.md)>

___

### setAttachment

▸ **setAttachment**(`name`: string, `path`: string): [Pushover](_src_pushover_.pushover.md)

*Defined in [src/pushover.ts:99](https://github.com/spraot/pushover-js/blob/a89b195/src/pushover.ts#L99)*

#### Parameters:

Name | Type |
------ | ------ |
`name` | string |
`path` | string |

**Returns:** [Pushover](_src_pushover_.pushover.md)

___

### setAttachmentFromBuffer

▸ **setAttachmentFromBuffer**(`name`: string, `data`: Buffer): [Pushover](_src_pushover_.pushover.md)

*Defined in [src/pushover.ts:107](https://github.com/spraot/pushover-js/blob/a89b195/src/pushover.ts#L107)*

#### Parameters:

Name | Type |
------ | ------ |
`name` | string |
`data` | Buffer |

**Returns:** [Pushover](_src_pushover_.pushover.md)

___

### setDevice

▸ **setDevice**(`device`: string): [Pushover](_src_pushover_.pushover.md)

*Defined in [src/pushover.ts:74](https://github.com/spraot/pushover-js/blob/a89b195/src/pushover.ts#L74)*

#### Parameters:

Name | Type |
------ | ------ |
`device` | string |

**Returns:** [Pushover](_src_pushover_.pushover.md)

___

### setHtml

▸ **setHtml**(): [Pushover](_src_pushover_.pushover.md)

*Defined in [src/pushover.ts:79](https://github.com/spraot/pushover-js/blob/a89b195/src/pushover.ts#L79)*

**Returns:** [Pushover](_src_pushover_.pushover.md)

___

### setMessage

▸ **setMessage**(`message`: string): [Pushover](_src_pushover_.pushover.md)

*Defined in [src/pushover.ts:89](https://github.com/spraot/pushover-js/blob/a89b195/src/pushover.ts#L89)*

#### Parameters:

Name | Type |
------ | ------ |
`message` | string |

**Returns:** [Pushover](_src_pushover_.pushover.md)

___

### setPriority

▸ **setPriority**(`priority`: [Priority](../modules/_src_pushover_.md#priority), `expire?`: undefined \| number, `retry?`: undefined \| number): [Pushover](_src_pushover_.pushover.md)

*Defined in [src/pushover.ts:115](https://github.com/spraot/pushover-js/blob/a89b195/src/pushover.ts#L115)*

#### Parameters:

Name | Type |
------ | ------ |
`priority` | [Priority](../modules/_src_pushover_.md#priority) |
`expire?` | undefined \| number |
`retry?` | undefined \| number |

**Returns:** [Pushover](_src_pushover_.pushover.md)

___

### setSound

▸ **setSound**(`sound`: [Sound](../modules/_src_pushover_.md#sound)): [Pushover](_src_pushover_.pushover.md)

*Defined in [src/pushover.ts:94](https://github.com/spraot/pushover-js/blob/a89b195/src/pushover.ts#L94)*

#### Parameters:

Name | Type |
------ | ------ |
`sound` | [Sound](../modules/_src_pushover_.md#sound) |

**Returns:** [Pushover](_src_pushover_.pushover.md)

___

### setTimestamp

▸ **setTimestamp**(`timestamp`: number): [Pushover](_src_pushover_.pushover.md)

*Defined in [src/pushover.ts:137](https://github.com/spraot/pushover-js/blob/a89b195/src/pushover.ts#L137)*

#### Parameters:

Name | Type |
------ | ------ |
`timestamp` | number |

**Returns:** [Pushover](_src_pushover_.pushover.md)

___

### setTitle

▸ **setTitle**(`title`: string): [Pushover](_src_pushover_.pushover.md)

*Defined in [src/pushover.ts:84](https://github.com/spraot/pushover-js/blob/a89b195/src/pushover.ts#L84)*

#### Parameters:

Name | Type |
------ | ------ |
`title` | string |

**Returns:** [Pushover](_src_pushover_.pushover.md)

___

### setUrl

▸ **setUrl**(`url`: string, `title?`: undefined \| string): [Pushover](_src_pushover_.pushover.md)

*Defined in [src/pushover.ts:129](https://github.com/spraot/pushover-js/blob/a89b195/src/pushover.ts#L129)*

#### Parameters:

Name | Type |
------ | ------ |
`url` | string |
`title?` | undefined \| string |

**Returns:** [Pushover](_src_pushover_.pushover.md)

## Object literals

### \_notification

▪ `Private` **\_notification**: object

*Defined in [src/pushover.ts:58](https://github.com/spraot/pushover-js/blob/a89b195/src/pushover.ts#L58)*

#### Properties:

Name | Type | Value |
------ | ------ | ------ |
`expire` | number | 0 |
`message` | string | "" |
`priority` | number | 0 |
`retry` | number | 0 |
`sound` | \"pushover\" | "pushover" |
`title` | string | "" |
`token` | string | "" |
`user` | string | "" |
