---
id: "changeset"
title: "Interface: ChangeSet<T>"
sidebar_label: "ChangeSet"
---

## Type parameters

Name | Type |
------ | ------ |
`T` | [AnyEntity](../globals.md#anyentity)&#60;T> |

## Hierarchy

* **ChangeSet**

## Properties

### collection

•  **collection**: string

*Defined in [packages/core/src/unit-of-work/ChangeSet.ts:5](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/ChangeSet.ts#L5)*

___

### entity

•  **entity**: T

*Defined in [packages/core/src/unit-of-work/ChangeSet.ts:7](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/ChangeSet.ts#L7)*

___

### name

•  **name**: string

*Defined in [packages/core/src/unit-of-work/ChangeSet.ts:4](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/ChangeSet.ts#L4)*

___

### originalEntity

• `Optional` **originalEntity**: [EntityData](../globals.md#entitydata)&#60;T>

*Defined in [packages/core/src/unit-of-work/ChangeSet.ts:10](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/ChangeSet.ts#L10)*

___

### payload

•  **payload**: [EntityData](../globals.md#entitydata)&#60;T>

*Defined in [packages/core/src/unit-of-work/ChangeSet.ts:8](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/ChangeSet.ts#L8)*

___

### persisted

•  **persisted**: boolean

*Defined in [packages/core/src/unit-of-work/ChangeSet.ts:9](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/ChangeSet.ts#L9)*

___

### type

•  **type**: [ChangeSetType](../enums/changesettype.md)

*Defined in [packages/core/src/unit-of-work/ChangeSet.ts:6](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/unit-of-work/ChangeSet.ts#L6)*
