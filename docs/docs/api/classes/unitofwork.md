---
id: "unitofwork"
title: "Class: UnitOfWork"
sidebar_label: "UnitOfWork"
---

## Hierarchy

* **UnitOfWork**

## Constructors

### constructor

\+ **new UnitOfWork**(`em`: [EntityManager](entitymanager.md)): [UnitOfWork](unitofwork.md)

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:31](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L31)*

#### Parameters:

Name | Type |
------ | ------ |
`em` | [EntityManager](entitymanager.md) |

**Returns:** [UnitOfWork](unitofwork.md)

## Properties

### changeSetComputer

• `Private` `Readonly` **changeSetComputer**: [ChangeSetComputer](changesetcomputer.md) = new ChangeSetComputer(this.em.getValidator(), this.collectionUpdates, this.removeStack, this.metadata, this.platform, this.em.config)

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:29](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L29)*

___

### changeSetPersister

• `Private` `Readonly` **changeSetPersister**: [ChangeSetPersister](changesetpersister.md) = new ChangeSetPersister(this.em.getDriver(), this.metadata, this.em.config.getHydrator(this.metadata), this.em.getEntityFactory(), this.em.config)

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:30](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L30)*

___

### changeSets

• `Private` `Readonly` **changeSets**: Map&#60;[AnyEntity](../globals.md#anyentity)&#60;any>, [ChangeSet](../interfaces/changeset.md)&#60;[AnyEntity](../globals.md#anyentity)&#60;any>>> = new Map&#60;AnyEntity, ChangeSet&#60;AnyEntity>>()

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:22](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L22)*

___

### collectionUpdates

• `Private` `Readonly` **collectionUpdates**: Set&#60;[Collection](collection.md)&#60;[AnyEntity](../globals.md#anyentity)&#60;any>, unknown>> = new Set&#60;Collection&#60;AnyEntity>>()

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:23](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L23)*

___

### comparator

• `Private` `Readonly` **comparator**: [EntityComparator](entitycomparator.md) = this.em.getComparator()

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:28](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L28)*

___

### em

• `Private` `Readonly` **em**: [EntityManager](entitymanager.md)

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:33](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L33)*

___

### eventManager

• `Private` `Readonly` **eventManager**: [EventManager](eventmanager.md) = this.em.getEventManager()

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:27](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L27)*

___

### extraUpdates

• `Private` `Readonly` **extraUpdates**: Set&#60;[[AnyEntity](../globals.md#anyentity)&#60;any>, string, [AnyEntity](../globals.md#anyentity)&#60;any> \| [Reference](reference.md)&#60;any> \| [Collection](collection.md)&#60;any, unknown>]> = new Set&#60;[AnyEntity, string, AnyEntity \| Reference&#60;any> \| Collection&#60;any>]>()

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:24](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L24)*

___

### identityMap

• `Private` `Readonly` **identityMap**: [IdentityMap](identitymap.md) = new IdentityMap()

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:17](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L17)*

map of references to managed entities

___

### metadata

• `Private` `Readonly` **metadata**: [MetadataStorage](metadatastorage.md) = this.em.getMetadata()

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:25](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L25)*

___

### orphanRemoveStack

• `Private` `Readonly` **orphanRemoveStack**: Set&#60;[AnyEntity](../globals.md#anyentity)&#60;any>> = new Set&#60;AnyEntity>()

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:21](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L21)*

___

### persistStack

• `Private` `Readonly` **persistStack**: Set&#60;[AnyEntity](../globals.md#anyentity)&#60;any>> = new Set&#60;AnyEntity>()

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:19](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L19)*

___

### platform

• `Private` `Readonly` **platform**: [Platform](platform.md) = this.em.getDriver().getPlatform()

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:26](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L26)*

___

### removeStack

• `Private` `Readonly` **removeStack**: Set&#60;[AnyEntity](../globals.md#anyentity)&#60;any>> = new Set&#60;AnyEntity>()

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:20](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L20)*

___

### working

• `Private` **working**: boolean = false

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:31](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L31)*

## Methods

### addCommitDependency

▸ `Private`**addCommitDependency**(`calc`: [CommitOrderCalculator](commitordercalculator.md), `prop`: [EntityProperty](../interfaces/entityproperty.md), `entityName`: string): void

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:674](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L674)*

#### Parameters:

Name | Type |
------ | ------ |
`calc` | [CommitOrderCalculator](commitordercalculator.md) |
`prop` | [EntityProperty](../interfaces/entityproperty.md) |
`entityName` | string |

**Returns:** void

___

### cancelOrphanRemoval

▸ **cancelOrphanRemoval**(`entity`: [AnyEntity](../globals.md#anyentity)): void

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:291](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L291)*

#### Parameters:

Name | Type |
------ | ------ |
`entity` | [AnyEntity](../globals.md#anyentity) |

**Returns:** void

___

### cascade

▸ `Private`**cascade**&#60;T>(`entity`: T, `type`: [Cascade](../enums/cascade.md), `visited`: WeakSet&#60;[AnyEntity](../globals.md#anyentity)>, `options?`: { checkRemoveStack?: boolean  }): void

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:412](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L412)*

#### Type parameters:

Name | Type |
------ | ------ |
`T` | [AnyEntity](../globals.md#anyentity)&#60;T> |

#### Parameters:

Name | Type | Default value |
------ | ------ | ------ |
`entity` | T | - |
`type` | [Cascade](../enums/cascade.md) | - |
`visited` | WeakSet&#60;[AnyEntity](../globals.md#anyentity)> | - |
`options` | { checkRemoveStack?: boolean  } | {} |

**Returns:** void

___

### cascadeReference

▸ `Private`**cascadeReference**&#60;T>(`entity`: T, `prop`: [EntityProperty](../interfaces/entityproperty.md)&#60;T>, `type`: [Cascade](../enums/cascade.md), `visited`: WeakSet&#60;[AnyEntity](../globals.md#anyentity)>, `options`: { checkRemoveStack?: boolean  }): void

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:430](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L430)*

#### Type parameters:

Name | Type |
------ | ------ |
`T` | [AnyEntity](../globals.md#anyentity)&#60;T> |

#### Parameters:

Name | Type |
------ | ------ |
`entity` | T |
`prop` | [EntityProperty](../interfaces/entityproperty.md)&#60;T> |
`type` | [Cascade](../enums/cascade.md) |
`visited` | WeakSet&#60;[AnyEntity](../globals.md#anyentity)> |
`options` | { checkRemoveStack?: boolean  } |

**Returns:** void

___

### checkOrphanRemoval

▸ `Private`**checkOrphanRemoval**&#60;T>(`changeSet`: [ChangeSet](../interfaces/changeset.md)&#60;T>): void

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:323](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L323)*

#### Type parameters:

Name | Type |
------ | ------ |
`T` | [AnyEntity](../globals.md#anyentity)&#60;T> |

#### Parameters:

Name | Type |
------ | ------ |
`changeSet` | [ChangeSet](../interfaces/changeset.md)&#60;T> |

**Returns:** void

___

### clear

▸ **clear**(): void

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:251](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L251)*

**Returns:** void

___

### commit

▸ **commit**(): Promise&#60;void>

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:205](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L205)*

**Returns:** Promise&#60;void>

___

### commitCreateChangeSets

▸ `Private`**commitCreateChangeSets**&#60;T>(`changeSets`: [ChangeSet](../interfaces/changeset.md)&#60;T>[], `ctx?`: [Transaction](../globals.md#transaction)): Promise&#60;void>

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:562](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L562)*

#### Type parameters:

Name | Type |
------ | ------ |
`T` | [AnyEntity](../globals.md#anyentity)&#60;T> |

#### Parameters:

Name | Type |
------ | ------ |
`changeSets` | [ChangeSet](../interfaces/changeset.md)&#60;T>[] |
`ctx?` | [Transaction](../globals.md#transaction) |

**Returns:** Promise&#60;void>

___

### commitDeleteChangeSets

▸ `Private`**commitDeleteChangeSets**&#60;T>(`changeSets`: [ChangeSet](../interfaces/changeset.md)&#60;T>[], `ctx?`: [Transaction](../globals.md#transaction)): Promise&#60;void>

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:619](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L619)*

#### Type parameters:

Name | Type |
------ | ------ |
`T` | [AnyEntity](../globals.md#anyentity)&#60;T> |

#### Parameters:

Name | Type |
------ | ------ |
`changeSets` | [ChangeSet](../interfaces/changeset.md)&#60;T>[] |
`ctx?` | [Transaction](../globals.md#transaction) |

**Returns:** Promise&#60;void>

___

### commitUpdateChangeSets

▸ `Private`**commitUpdateChangeSets**&#60;T>(`changeSets`: [ChangeSet](../interfaces/changeset.md)&#60;T>[], `ctx?`: [Transaction](../globals.md#transaction)): Promise&#60;void>

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:602](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L602)*

#### Type parameters:

Name | Type |
------ | ------ |
`T` | [AnyEntity](../globals.md#anyentity)&#60;T> |

#### Parameters:

Name | Type |
------ | ------ |
`changeSets` | [ChangeSet](../interfaces/changeset.md)&#60;T>[] |
`ctx?` | [Transaction](../globals.md#transaction) |

**Returns:** Promise&#60;void>

___

### computeChangeSet

▸ **computeChangeSet**&#60;T>(`entity`: T): void

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:147](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L147)*

#### Type parameters:

Name | Type |
------ | ------ |
`T` | [AnyEntity](../globals.md#anyentity)&#60;T> |

#### Parameters:

Name | Type |
------ | ------ |
`entity` | T |

**Returns:** void

___

### computeChangeSets

▸ **computeChangeSets**(): void

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:263](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L263)*

**Returns:** void

___

### findExtraUpdates

▸ `Private`**findExtraUpdates**&#60;T>(`changeSet`: [ChangeSet](../interfaces/changeset.md)&#60;T>, `props`: [EntityProperty](../interfaces/entityproperty.md)&#60;T>[]): void

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:585](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L585)*

#### Type parameters:

Name | Type |
------ | ------ |
`T` | [AnyEntity](../globals.md#anyentity)&#60;T> |

#### Parameters:

Name | Type |
------ | ------ |
`changeSet` | [ChangeSet](../interfaces/changeset.md)&#60;T> |
`props` | [EntityProperty](../interfaces/entityproperty.md)&#60;T>[] |

**Returns:** void

___

### findNewEntities

▸ `Private`**findNewEntities**&#60;T>(`entity`: T, `visited?`: WeakSet&#60;[AnyEntity](../globals.md#anyentity)&#60;any>>): void

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:295](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L295)*

#### Type parameters:

Name | Type |
------ | ------ |
`T` | [AnyEntity](../globals.md#anyentity)&#60;T> |

#### Parameters:

Name | Type | Default value |
------ | ------ | ------ |
`entity` | T | - |
`visited` | WeakSet&#60;[AnyEntity](../globals.md#anyentity)&#60;any>> | new WeakSet&#60;AnyEntity>() |

**Returns:** void

___

### fixMissingReference

▸ `Private`**fixMissingReference**&#60;T>(`entity`: T, `prop`: [EntityProperty](../interfaces/entityproperty.md)&#60;T>): void

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:506](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L506)*

#### Type parameters:

Name | Type |
------ | ------ |
`T` | [AnyEntity](../globals.md#anyentity)&#60;T> |

#### Parameters:

Name | Type |
------ | ------ |
`entity` | T |
`prop` | [EntityProperty](../interfaces/entityproperty.md)&#60;T> |

**Returns:** void

___

### getById

▸ **getById**&#60;T>(`entityName`: string, `id`: [Primary](../globals.md#primary)&#60;T> \| [Primary](../globals.md#primary)&#60;T>[]): T

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:80](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L80)*

Returns entity from the identity map. For composite keys, you need to pass an array of PKs in the same order as they are defined in `meta.primaryKeys`.

#### Type parameters:

Name | Type |
------ | ------ |
`T` | [AnyEntity](../globals.md#anyentity)&#60;T> |

#### Parameters:

Name | Type |
------ | ------ |
`entityName` | string |
`id` | [Primary](../globals.md#primary)&#60;T> \| [Primary](../globals.md#primary)&#60;T>[] |

**Returns:** T

___

### getChangeSetGroups

▸ `Private`**getChangeSetGroups**(): object

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:639](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L639)*

Orders change sets so FK constrains are maintained, ensures stable order (needed for node < 11)

**Returns:** object

___

### getChangeSets

▸ **getChangeSets**(): [ChangeSet](../interfaces/changeset.md)&#60;[AnyEntity](../globals.md#anyentity)>[]

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:135](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L135)*

**Returns:** [ChangeSet](../interfaces/changeset.md)&#60;[AnyEntity](../globals.md#anyentity)>[]

___

### getCollectionUpdates

▸ **getCollectionUpdates**(): [Collection](collection.md)&#60;[AnyEntity](../globals.md#anyentity)>[]

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:139](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L139)*

**Returns:** [Collection](collection.md)&#60;[AnyEntity](../globals.md#anyentity)>[]

___

### getCommitOrder

▸ `Private`**getCommitOrder**(): string[]

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:655](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L655)*

**Returns:** string[]

___

### getExtraUpdates

▸ **getExtraUpdates**(): Set&#60;[[AnyEntity](../globals.md#anyentity), string, [AnyEntity](../globals.md#anyentity) \| [Reference](reference.md)&#60;any> \| [Collection](collection.md)&#60;any>]>

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:143](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L143)*

**Returns:** Set&#60;[[AnyEntity](../globals.md#anyentity), string, [AnyEntity](../globals.md#anyentity) \| [Reference](reference.md)&#60;any> \| [Collection](collection.md)&#60;any>]>

___

### getIdentityMap

▸ **getIdentityMap**(): [IdentityMap](identitymap.md)

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:100](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L100)*

Returns map of all managed entities.

**Returns:** [IdentityMap](identitymap.md)

___

### getOriginalEntityData

▸ **getOriginalEntityData**&#60;T>(): [AnyEntity](../globals.md#anyentity)[]

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:107](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L107)*

Returns stored snapshot of entity state that is used for change set computation.

**`deprecated`** use `uow.getOriginalEntityData(entity)`

#### Type parameters:

Name | Type |
------ | ------ |
`T` | [AnyEntity](../globals.md#anyentity)&#60;T> |

**Returns:** [AnyEntity](../globals.md#anyentity)[]

▸ **getOriginalEntityData**&#60;T>(`entity`: T): [EntityData](../globals.md#entitydata)&#60;T> \| undefined

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:112](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L112)*

Returns stored snapshot of entity state that is used for change set computation.

#### Type parameters:

Name | Type |
------ | ------ |
`T` | [AnyEntity](../globals.md#anyentity)&#60;T> |

#### Parameters:

Name | Type |
------ | ------ |
`entity` | T |

**Returns:** [EntityData](../globals.md#entitydata)&#60;T> \| undefined

___

### getPersistStack

▸ **getPersistStack**(): Set&#60;[AnyEntity](../globals.md#anyentity)>

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:127](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L127)*

**Returns:** Set&#60;[AnyEntity](../globals.md#anyentity)>

___

### getRemoveStack

▸ **getRemoveStack**(): Set&#60;[AnyEntity](../globals.md#anyentity)>

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:131](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L131)*

**Returns:** Set&#60;[AnyEntity](../globals.md#anyentity)>

___

### initIdentifier

▸ `Private`**initIdentifier**&#60;T>(`entity`: T): void

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:338](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L338)*

#### Type parameters:

Name | Type |
------ | ------ |
`T` | [AnyEntity](../globals.md#anyentity)&#60;T> |

#### Parameters:

Name | Type |
------ | ------ |
`entity` | T |

**Returns:** void

___

### isCollectionSelfReferenced

▸ `Private`**isCollectionSelfReferenced**(`collection`: [Collection](collection.md)&#60;[AnyEntity](../globals.md#anyentity)>, `visited`: WeakSet&#60;[AnyEntity](../globals.md#anyentity)>): boolean

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:458](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L458)*

#### Parameters:

Name | Type |
------ | ------ |
`collection` | [Collection](collection.md)&#60;[AnyEntity](../globals.md#anyentity)> |
`visited` | WeakSet&#60;[AnyEntity](../globals.md#anyentity)> |

**Returns:** boolean

___

### lock

▸ **lock**&#60;T>(`entity`: T, `mode`: [LockMode](../enums/lockmode.md), `version?`: number \| Date): Promise&#60;void>

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:237](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L237)*

#### Type parameters:

Name | Type |
------ | ------ |
`T` | [AnyEntity](../globals.md#anyentity)&#60;T> |

#### Parameters:

Name | Type |
------ | ------ |
`entity` | T |
`mode` | [LockMode](../enums/lockmode.md) |
`version?` | number \| Date |

**Returns:** Promise&#60;void>

___

### lockOptimistic

▸ `Private`**lockOptimistic**&#60;T>(`entity`: T, `meta`: [EntityMetadata](entitymetadata.md)&#60;T>, `version`: number \| Date): Promise&#60;void>

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:484](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L484)*

#### Type parameters:

Name | Type |
------ | ------ |
`T` | [AnyEntity](../globals.md#anyentity)&#60;T> |

#### Parameters:

Name | Type |
------ | ------ |
`entity` | T |
`meta` | [EntityMetadata](entitymetadata.md)&#60;T> |
`version` | number \| Date |

**Returns:** Promise&#60;void>

___

### lockPessimistic

▸ `Private`**lockPessimistic**&#60;T>(`entity`: T, `mode`: [LockMode](../enums/lockmode.md)): Promise&#60;void>

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:476](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L476)*

#### Type parameters:

Name | Type |
------ | ------ |
`T` | [AnyEntity](../globals.md#anyentity)&#60;T> |

#### Parameters:

Name | Type |
------ | ------ |
`entity` | T |
`mode` | [LockMode](../enums/lockmode.md) |

**Returns:** Promise&#60;void>

___

### merge

▸ **merge**&#60;T>(`entity`: T, `visited?`: WeakSet&#60;[AnyEntity](../globals.md#anyentity)>): void

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:35](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L35)*

#### Type parameters:

Name | Type |
------ | ------ |
`T` | [AnyEntity](../globals.md#anyentity)&#60;T> |

#### Parameters:

Name | Type |
------ | ------ |
`entity` | T |
`visited?` | WeakSet&#60;[AnyEntity](../globals.md#anyentity)> |

**Returns:** void

___

### persist

▸ **persist**&#60;T>(`entity`: T, `visited?`: WeakSet&#60;[AnyEntity](../globals.md#anyentity)&#60;any>>, `checkRemoveStack?`: boolean): void

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:177](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L177)*

#### Type parameters:

Name | Type |
------ | ------ |
`T` | [AnyEntity](../globals.md#anyentity)&#60;T> |

#### Parameters:

Name | Type | Default value |
------ | ------ | ------ |
`entity` | T | - |
`visited` | WeakSet&#60;[AnyEntity](../globals.md#anyentity)&#60;any>> | new WeakSet&#60;AnyEntity>() |
`checkRemoveStack` | boolean | false |

**Returns:** void

___

### persistToDatabase

▸ `Private`**persistToDatabase**(`groups`: {}, `tx?`: [Transaction](../globals.md#transaction)): Promise&#60;void>

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:522](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L522)*

#### Parameters:

Name | Type |
------ | ------ |
`groups` | {} |
`tx?` | [Transaction](../globals.md#transaction) |

**Returns:** Promise&#60;void>

___

### postCommitCleanup

▸ `Private`**postCommitCleanup**(): void

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:402](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L402)*

**Returns:** void

___

### processReference

▸ `Private`**processReference**&#60;T>(`parent`: T, `prop`: [EntityProperty](../interfaces/entityproperty.md)&#60;T>, `reference`: any, `visited`: WeakSet&#60;[AnyEntity](../globals.md#anyentity)>): void

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:348](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L348)*

#### Type parameters:

Name | Type |
------ | ------ |
`T` | [AnyEntity](../globals.md#anyentity)&#60;T> |

#### Parameters:

Name | Type |
------ | ------ |
`parent` | T |
`prop` | [EntityProperty](../interfaces/entityproperty.md)&#60;T> |
`reference` | any |
`visited` | WeakSet&#60;[AnyEntity](../globals.md#anyentity)> |

**Returns:** void

___

### processToManyReference

▸ `Private`**processToManyReference**&#60;T>(`reference`: [Collection](collection.md)&#60;[AnyEntity](../globals.md#anyentity)>, `visited`: WeakSet&#60;[AnyEntity](../globals.md#anyentity)>, `parent`: T, `prop`: [EntityProperty](../interfaces/entityproperty.md)&#60;T>): void

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:366](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L366)*

#### Type parameters:

Name | Type |
------ | ------ |
`T` | [AnyEntity](../globals.md#anyentity)&#60;T> |

#### Parameters:

Name | Type |
------ | ------ |
`reference` | [Collection](collection.md)&#60;[AnyEntity](../globals.md#anyentity)> |
`visited` | WeakSet&#60;[AnyEntity](../globals.md#anyentity)> |
`parent` | T |
`prop` | [EntityProperty](../interfaces/entityproperty.md)&#60;T> |

**Returns:** void

___

### processToOneReference

▸ `Private`**processToOneReference**&#60;T>(`reference`: any, `visited`: WeakSet&#60;[AnyEntity](../globals.md#anyentity)>): void

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:360](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L360)*

#### Type parameters:

Name | Type |
------ | ------ |
`T` | [AnyEntity](../globals.md#anyentity)&#60;T> |

#### Parameters:

Name | Type |
------ | ------ |
`reference` | any |
`visited` | WeakSet&#60;[AnyEntity](../globals.md#anyentity)> |

**Returns:** void

___

### recomputeSingleChangeSet

▸ **recomputeSingleChangeSet**&#60;T>(`entity`: T): void

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:161](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L161)*

#### Type parameters:

Name | Type |
------ | ------ |
`T` | [AnyEntity](../globals.md#anyentity)&#60;T> |

#### Parameters:

Name | Type |
------ | ------ |
`entity` | T |

**Returns:** void

___

### registerManaged

▸ **registerManaged**&#60;T>(`entity`: T, `data?`: [EntityData](../globals.md#entitydata)&#60;T>, `refresh?`: boolean, `newEntity?`: boolean): T

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:60](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L60)*

**`internal`** 

#### Type parameters:

Name | Type |
------ | ------ |
`T` | [AnyEntity](../globals.md#anyentity)&#60;T> |

#### Parameters:

Name | Type |
------ | ------ |
`entity` | T |
`data?` | [EntityData](../globals.md#entitydata)&#60;T> |
`refresh?` | boolean |
`newEntity?` | boolean |

**Returns:** T

___

### remove

▸ **remove**(`entity`: [AnyEntity](../globals.md#anyentity), `visited?`: WeakSet&#60;[AnyEntity](../globals.md#anyentity)&#60;any>>): void

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:191](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L191)*

#### Parameters:

Name | Type | Default value |
------ | ------ | ------ |
`entity` | [AnyEntity](../globals.md#anyentity) | - |
`visited` | WeakSet&#60;[AnyEntity](../globals.md#anyentity)&#60;any>> | new WeakSet&#60;AnyEntity>() |

**Returns:** void

___

### runHooks

▸ `Private`**runHooks**&#60;T>(`type`: [EventType](../enums/eventtype.md), `changeSet`: [ChangeSet](../interfaces/changeset.md)&#60;T>, `sync?`: boolean): Promise&#60;unknown>

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:379](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L379)*

#### Type parameters:

Name | Type |
------ | ------ |
`T` | [AnyEntity](../globals.md#anyentity)&#60;T> |

#### Parameters:

Name | Type | Default value |
------ | ------ | ------ |
`type` | [EventType](../enums/eventtype.md) | - |
`changeSet` | [ChangeSet](../interfaces/changeset.md)&#60;T> | - |
`sync` | boolean | false |

**Returns:** Promise&#60;unknown>

___

### scheduleOrphanRemoval

▸ **scheduleOrphanRemoval**(`entity`: [AnyEntity](../globals.md#anyentity)): void

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:287](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L287)*

#### Parameters:

Name | Type |
------ | ------ |
`entity` | [AnyEntity](../globals.md#anyentity) |

**Returns:** void

___

### shouldCascade

▸ `Private`**shouldCascade**(`prop`: [EntityProperty](../interfaces/entityproperty.md), `type`: [Cascade](../enums/cascade.md)): boolean

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:463](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L463)*

#### Parameters:

Name | Type |
------ | ------ |
`prop` | [EntityProperty](../interfaces/entityproperty.md) |
`type` | [Cascade](../enums/cascade.md) |

**Returns:** boolean

___

### tryGetById

▸ **tryGetById**&#60;T>(`entityName`: string, `where`: [FilterQuery](../globals.md#filterquery)&#60;T>, `strict?`: boolean): T \| null

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:87](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L87)*

#### Type parameters:

Name | Type |
------ | ------ |
`T` | [AnyEntity](../globals.md#anyentity)&#60;T> |

#### Parameters:

Name | Type | Default value |
------ | ------ | ------ |
`entityName` | string | - |
`where` | [FilterQuery](../globals.md#filterquery)&#60;T> | - |
`strict` | boolean | true |

**Returns:** T \| null

___

### unsetIdentity

▸ **unsetIdentity**(`entity`: [AnyEntity](../globals.md#anyentity)): void

*Defined in [packages/core/src/unit-of-work/UnitOfWork.ts:256](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/UnitOfWork.ts#L256)*

#### Parameters:

Name | Type |
------ | ------ |
`entity` | [AnyEntity](../globals.md#anyentity) |

**Returns:** void
