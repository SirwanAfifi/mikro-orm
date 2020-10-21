---
id: "logger"
title: "Class: Logger"
sidebar_label: "Logger"
---

## Hierarchy

* **Logger**

## Constructors

### constructor

\+ **new Logger**(`logger`: (message: string) => void, `debugMode?`: boolean \| [LoggerNamespace](../globals.md#loggernamespace)[]): [Logger](logger.md)

*Defined in [packages/core/src/utils/Logger.ts:3](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/utils/Logger.ts#L3)*

#### Parameters:

Name | Type | Default value |
------ | ------ | ------ |
`logger` | (message: string) => void | - |
`debugMode` | boolean \| [LoggerNamespace](../globals.md#loggernamespace)[] | false |

**Returns:** [Logger](logger.md)

## Properties

### debugMode

•  **debugMode**: boolean \| [LoggerNamespace](../globals.md#loggernamespace)[]

*Defined in [packages/core/src/utils/Logger.ts:6](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/utils/Logger.ts#L6)*

___

### logger

• `Private` `Readonly` **logger**: (message: string) => void

*Defined in [packages/core/src/utils/Logger.ts:5](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/utils/Logger.ts#L5)*

## Methods

### isEnabled

▸ **isEnabled**(`namespace`: [LoggerNamespace](../globals.md#loggernamespace)): boolean

*Defined in [packages/core/src/utils/Logger.ts:28](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/utils/Logger.ts#L28)*

#### Parameters:

Name | Type |
------ | ------ |
`namespace` | [LoggerNamespace](../globals.md#loggernamespace) |

**Returns:** boolean

___

### log

▸ **log**(`namespace`: [LoggerNamespace](../globals.md#loggernamespace), `message`: string): void

*Defined in [packages/core/src/utils/Logger.ts:11](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/utils/Logger.ts#L11)*

Logs a message inside given namespace.

#### Parameters:

Name | Type |
------ | ------ |
`namespace` | [LoggerNamespace](../globals.md#loggernamespace) |
`message` | string |

**Returns:** void

___

### setDebugMode

▸ **setDebugMode**(`debugMode`: boolean \| [LoggerNamespace](../globals.md#loggernamespace)[]): void

*Defined in [packages/core/src/utils/Logger.ts:24](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/utils/Logger.ts#L24)*

Sets active namespaces. Pass `true` to enable all logging.

#### Parameters:

Name | Type |
------ | ------ |
`debugMode` | boolean \| [LoggerNamespace](../globals.md#loggernamespace)[] |

**Returns:** void
