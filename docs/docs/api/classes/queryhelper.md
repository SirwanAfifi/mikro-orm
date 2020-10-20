---
id: "queryhelper"
title: "Class: QueryHelper"
sidebar_label: "QueryHelper"
---

## Hierarchy

* **QueryHelper**

## Properties

### SUPPORTED\_OPERATORS

▪ `Static` `Readonly` **SUPPORTED\_OPERATORS**: string[] = ['>', '&#60;', '&#60;=', '>=', '!', '!=', ':in', ':nin', ':gt', ':gte', ':lt', ':lte', ':ne', ':not']

*Defined in [packages/core/src/utils/QueryHelper.ts:10](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/utils/QueryHelper.ts#L10)*

## Methods

### getActiveFilters

▸ `Static`**getActiveFilters**(`entityName`: string, `options`: [Dictionary](../globals.md#dictionary)&#60;boolean \| [Dictionary](../globals.md#dictionary)> \| string[] \| boolean, `filters`: [Dictionary](../globals.md#dictionary)&#60;[FilterDef](../globals.md#filterdef)&#60;any>>): [FilterDef](../globals.md#filterdef)&#60;any>[]

*Defined in [packages/core/src/utils/QueryHelper.ts:144](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/utils/QueryHelper.ts#L144)*

#### Parameters:

Name | Type |
------ | ------ |
`entityName` | string |
`options` | [Dictionary](../globals.md#dictionary)&#60;boolean \| [Dictionary](../globals.md#dictionary)> \| string[] \| boolean |
`filters` | [Dictionary](../globals.md#dictionary)&#60;[FilterDef](../globals.md#filterdef)&#60;any>> |

**Returns:** [FilterDef](../globals.md#filterdef)&#60;any>[]

___

### inlinePrimaryKeyObjects

▸ `Static`**inlinePrimaryKeyObjects**&#60;T>(`where`: [Dictionary](../globals.md#dictionary), `meta`: [EntityMetadata](entitymetadata.md)&#60;T>, `metadata`: [MetadataStorage](metadatastorage.md), `key?`: string): boolean

*Defined in [packages/core/src/utils/QueryHelper.ts:44](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/utils/QueryHelper.ts#L44)*

#### Type parameters:

Name | Type |
------ | ------ |
`T` | [AnyEntity](../globals.md#anyentity)&#60;T> |

#### Parameters:

Name | Type |
------ | ------ |
`where` | [Dictionary](../globals.md#dictionary) |
`meta` | [EntityMetadata](entitymetadata.md)&#60;T> |
`metadata` | [MetadataStorage](metadatastorage.md) |
`key?` | string |

**Returns:** boolean

___

### isFilterActive

▸ `Static`**isFilterActive**(`entityName`: string, `filterName`: string, `filter`: [FilterDef](../globals.md#filterdef)&#60;any>, `options`: [Dictionary](../globals.md#dictionary)&#60;boolean \| [Dictionary](../globals.md#dictionary)>): boolean

*Defined in [packages/core/src/utils/QueryHelper.ts:165](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/utils/QueryHelper.ts#L165)*

#### Parameters:

Name | Type |
------ | ------ |
`entityName` | string |
`filterName` | string |
`filter` | [FilterDef](../globals.md#filterdef)&#60;any> |
`options` | [Dictionary](../globals.md#dictionary)&#60;boolean \| [Dictionary](../globals.md#dictionary)> |

**Returns:** boolean

___

### isSupportedOperator

▸ `Static` `Private`**isSupportedOperator**(`key`: string): boolean

*Defined in [packages/core/src/utils/QueryHelper.ts:214](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/utils/QueryHelper.ts#L214)*

#### Parameters:

Name | Type |
------ | ------ |
`key` | string |

**Returns:** boolean

___

### processCustomType

▸ `Static`**processCustomType**&#60;T>(`prop`: [EntityProperty](../interfaces/entityproperty.md)&#60;T>, `cond`: [FilterQuery](../globals.md#filterquery)&#60;T>, `platform`: [Platform](platform.md), `key?`: string, `fromQuery?`: boolean): [FilterQuery](../globals.md#filterquery)&#60;T>

*Defined in [packages/core/src/utils/QueryHelper.ts:177](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/utils/QueryHelper.ts#L177)*

#### Type parameters:

Name |
------ |
`T` |

#### Parameters:

Name | Type |
------ | ------ |
`prop` | [EntityProperty](../interfaces/entityproperty.md)&#60;T> |
`cond` | [FilterQuery](../globals.md#filterquery)&#60;T> |
`platform` | [Platform](platform.md) |
`key?` | string |
`fromQuery?` | boolean |

**Returns:** [FilterQuery](../globals.md#filterquery)&#60;T>

___

### processEntity

▸ `Static` `Private`**processEntity**(`entity`: [AnyEntity](../globals.md#anyentity), `root?`: boolean): any

*Defined in [packages/core/src/utils/QueryHelper.ts:192](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/utils/QueryHelper.ts#L192)*

#### Parameters:

Name | Type |
------ | ------ |
`entity` | [AnyEntity](../globals.md#anyentity) |
`root?` | boolean |

**Returns:** any

___

### processExpression

▸ `Static` `Private`**processExpression**&#60;T>(`expr`: string, `value`: T): [Dictionary](../globals.md#dictionary)&#60;T>

*Defined in [packages/core/src/utils/QueryHelper.ts:202](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/utils/QueryHelper.ts#L202)*

#### Type parameters:

Name |
------ |
`T` |

#### Parameters:

Name | Type |
------ | ------ |
`expr` | string |
`value` | T |

**Returns:** [Dictionary](../globals.md#dictionary)&#60;T>

___

### processObjectParams

▸ `Static`**processObjectParams**(`params?`: [Dictionary](../globals.md#dictionary)): any

*Defined in [packages/core/src/utils/QueryHelper.ts:36](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/utils/QueryHelper.ts#L36)*

#### Parameters:

Name | Type | Default value |
------ | ------ | ------ |
`params` | [Dictionary](../globals.md#dictionary) | {} |

**Returns:** any

___

### processParams

▸ `Static`**processParams**(`params`: any, `root?`: boolean): any

*Defined in [packages/core/src/utils/QueryHelper.ts:12](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/utils/QueryHelper.ts#L12)*

#### Parameters:

Name | Type |
------ | ------ |
`params` | any |
`root?` | boolean |

**Returns:** any

___

### processWhere

▸ `Static`**processWhere**&#60;T>(`where`: [FilterQuery](../globals.md#filterquery)&#60;T>, `entityName`: string, `metadata`: [MetadataStorage](metadatastorage.md), `platform`: [Platform](platform.md), `convertCustomTypes?`: boolean, `root?`: boolean): [FilterQuery](../globals.md#filterquery)&#60;T>

*Defined in [packages/core/src/utils/QueryHelper.ts:72](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/utils/QueryHelper.ts#L72)*

#### Type parameters:

Name | Type |
------ | ------ |
`T` | [AnyEntity](../globals.md#anyentity)&#60;T> |

#### Parameters:

Name | Type | Default value |
------ | ------ | ------ |
`where` | [FilterQuery](../globals.md#filterquery)&#60;T> | - |
`entityName` | string | - |
`metadata` | [MetadataStorage](metadatastorage.md) | - |
`platform` | [Platform](platform.md) | - |
`convertCustomTypes` | boolean | true |
`root` | boolean | true |

**Returns:** [FilterQuery](../globals.md#filterquery)&#60;T>
