---
id: "metadatastorage"
title: "Class: MetadataStorage"
sidebar_label: "MetadataStorage"
---

## Hierarchy

* **MetadataStorage**

## Constructors

### constructor

\+ **new MetadataStorage**(`metadata?`: [Dictionary](../globals.md#dictionary)&#60;[EntityMetadata](entitymetadata.md)>): [MetadataStorage](metadatastorage.md)

*Defined in [packages/core/src/metadata/MetadataStorage.ts:12](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/metadata/MetadataStorage.ts#L12)*

#### Parameters:

Name | Type | Default value |
------ | ------ | ------ |
`metadata` | [Dictionary](../globals.md#dictionary)&#60;[EntityMetadata](entitymetadata.md)> | {} |

**Returns:** [MetadataStorage](metadatastorage.md)

## Properties

### metadata

• `Private` `Readonly` **metadata**: [Dictionary](../globals.md#dictionary)&#60;[EntityMetadata](entitymetadata.md)>

*Defined in [packages/core/src/metadata/MetadataStorage.ts:12](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/metadata/MetadataStorage.ts#L12)*

___

### metadata

▪ `Static` `Private` `Readonly` **metadata**: [Dictionary](../globals.md#dictionary)&#60;[EntityMetadata](entitymetadata.md)> = Utils.getGlobalStorage('metadata')

*Defined in [packages/core/src/metadata/MetadataStorage.ts:10](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/metadata/MetadataStorage.ts#L10)*

___

### subscribers

▪ `Static` `Private` `Readonly` **subscribers**: [Dictionary](../globals.md#dictionary)&#60;[EventSubscriber](../interfaces/eventsubscriber.md)> = Utils.getGlobalStorage('subscribers')

*Defined in [packages/core/src/metadata/MetadataStorage.ts:11](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/metadata/MetadataStorage.ts#L11)*

## Methods

### decorate

▸ **decorate**(`em`: [EntityManager](entitymanager.md)): void

*Defined in [packages/core/src/metadata/MetadataStorage.ts:86](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/metadata/MetadataStorage.ts#L86)*

#### Parameters:

Name | Type |
------ | ------ |
`em` | [EntityManager](entitymanager.md) |

**Returns:** void

___

### find

▸ **find**&#60;T>(`entity`: string): [EntityMetadata](entitymetadata.md)&#60;T> \| undefined

*Defined in [packages/core/src/metadata/MetadataStorage.ts:70](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/metadata/MetadataStorage.ts#L70)*

#### Type parameters:

Name | Type | Default |
------ | ------ | ------ |
`T` | [AnyEntity](../globals.md#anyentity)&#60;T> | any |

#### Parameters:

Name | Type |
------ | ------ |
`entity` | string |

**Returns:** [EntityMetadata](entitymetadata.md)&#60;T> \| undefined

___

### get

▸ **get**&#60;T>(`entity`: string, `init?`: boolean, `validate?`: boolean): [EntityMetadata](entitymetadata.md)&#60;T>

*Defined in [packages/core/src/metadata/MetadataStorage.ts:58](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/metadata/MetadataStorage.ts#L58)*

#### Type parameters:

Name | Type | Default |
------ | ------ | ------ |
`T` | [AnyEntity](../globals.md#anyentity)&#60;T> | any |

#### Parameters:

Name | Type | Default value |
------ | ------ | ------ |
`entity` | string | - |
`init` | boolean | false |
`validate` | boolean | true |

**Returns:** [EntityMetadata](entitymetadata.md)&#60;T>

___

### getAll

▸ **getAll**(): [Dictionary](../globals.md#dictionary)&#60;[EntityMetadata](entitymetadata.md)>

*Defined in [packages/core/src/metadata/MetadataStorage.ts:54](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/metadata/MetadataStorage.ts#L54)*

**Returns:** [Dictionary](../globals.md#dictionary)&#60;[EntityMetadata](entitymetadata.md)>

___

### has

▸ **has**(`entity`: string): boolean

*Defined in [packages/core/src/metadata/MetadataStorage.ts:74](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/metadata/MetadataStorage.ts#L74)*

#### Parameters:

Name | Type |
------ | ------ |
`entity` | string |

**Returns:** boolean

___

### reset

▸ **reset**(`entity`: string): void

*Defined in [packages/core/src/metadata/MetadataStorage.ts:82](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/metadata/MetadataStorage.ts#L82)*

#### Parameters:

Name | Type |
------ | ------ |
`entity` | string |

**Returns:** void

___

### set

▸ **set**(`entity`: string, `meta`: [EntityMetadata](entitymetadata.md)): [EntityMetadata](entitymetadata.md)

*Defined in [packages/core/src/metadata/MetadataStorage.ts:78](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/metadata/MetadataStorage.ts#L78)*

#### Parameters:

Name | Type |
------ | ------ |
`entity` | string |
`meta` | [EntityMetadata](entitymetadata.md) |

**Returns:** [EntityMetadata](entitymetadata.md)

___

### getMetadata

▸ `Static`**getMetadata**(): [Dictionary](../globals.md#dictionary)&#60;[EntityMetadata](entitymetadata.md)>

*Defined in [packages/core/src/metadata/MetadataStorage.ts:18](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/metadata/MetadataStorage.ts#L18)*

**Returns:** [Dictionary](../globals.md#dictionary)&#60;[EntityMetadata](entitymetadata.md)>

▸ `Static`**getMetadata**&#60;T>(`entity`: string, `path`: string): [EntityMetadata](entitymetadata.md)&#60;T>

*Defined in [packages/core/src/metadata/MetadataStorage.ts:19](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/metadata/MetadataStorage.ts#L19)*

#### Type parameters:

Name | Type | Default |
------ | ------ | ------ |
`T` | [AnyEntity](../globals.md#anyentity)&#60;T> | any |

#### Parameters:

Name | Type |
------ | ------ |
`entity` | string |
`path` | string |

**Returns:** [EntityMetadata](entitymetadata.md)&#60;T>

___

### getMetadataFromDecorator

▸ `Static`**getMetadataFromDecorator**&#60;T>(`target`: T & [Dictionary](../globals.md#dictionary)): [EntityMetadata](entitymetadata.md)&#60;T>

*Defined in [packages/core/src/metadata/MetadataStorage.ts:38](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/metadata/MetadataStorage.ts#L38)*

#### Type parameters:

Name | Default |
------ | ------ |
`T` | any |

#### Parameters:

Name | Type |
------ | ------ |
`target` | T & [Dictionary](../globals.md#dictionary) |

**Returns:** [EntityMetadata](entitymetadata.md)&#60;T>

___

### getSubscriberMetadata

▸ `Static`**getSubscriberMetadata**(): [Dictionary](../globals.md#dictionary)&#60;[EventSubscriber](../interfaces/eventsubscriber.md)>

*Defined in [packages/core/src/metadata/MetadataStorage.ts:46](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/metadata/MetadataStorage.ts#L46)*

**Returns:** [Dictionary](../globals.md#dictionary)&#60;[EventSubscriber](../interfaces/eventsubscriber.md)>

___

### init

▸ `Static`**init**(): [MetadataStorage](metadatastorage.md)

*Defined in [packages/core/src/metadata/MetadataStorage.ts:50](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/metadata/MetadataStorage.ts#L50)*

**Returns:** [MetadataStorage](metadatastorage.md)

___

### isKnownEntity

▸ `Static`**isKnownEntity**(`name`: string): boolean

*Defined in [packages/core/src/metadata/MetadataStorage.ts:34](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/metadata/MetadataStorage.ts#L34)*

#### Parameters:

Name | Type |
------ | ------ |
`name` | string |

**Returns:** boolean
