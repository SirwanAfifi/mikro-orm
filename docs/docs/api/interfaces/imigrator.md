---
id: "imigrator"
title: "Interface: IMigrator"
sidebar_label: "IMigrator"
---

## Hierarchy

* **IMigrator**

## Methods

### createMigration

▸ **createMigration**(`path?`: string, `blank?`: boolean, `initial?`: boolean): Promise&#60;[MigrationResult](../globals.md#migrationresult)>

*Defined in [packages/core/src/typings.ts:324](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L324)*

#### Parameters:

Name | Type |
------ | ------ |
`path?` | string |
`blank?` | boolean |
`initial?` | boolean |

**Returns:** Promise&#60;[MigrationResult](../globals.md#migrationresult)>

___

### down

▸ **down**(`options?`: string \| string[] \| [MigrateOptions](../globals.md#migrateoptions)): Promise&#60;[UmzugMigration](../globals.md#umzugmigration)[]>

*Defined in [packages/core/src/typings.ts:328](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L328)*

#### Parameters:

Name | Type |
------ | ------ |
`options?` | string \| string[] \| [MigrateOptions](../globals.md#migrateoptions) |

**Returns:** Promise&#60;[UmzugMigration](../globals.md#umzugmigration)[]>

___

### getExecutedMigrations

▸ **getExecutedMigrations**(): Promise&#60;[MigrationRow](../globals.md#migrationrow)[]>

*Defined in [packages/core/src/typings.ts:325](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L325)*

**Returns:** Promise&#60;[MigrationRow](../globals.md#migrationrow)[]>

___

### getPendingMigrations

▸ **getPendingMigrations**(): Promise&#60;[UmzugMigration](../globals.md#umzugmigration)[]>

*Defined in [packages/core/src/typings.ts:326](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L326)*

**Returns:** Promise&#60;[UmzugMigration](../globals.md#umzugmigration)[]>

___

### up

▸ **up**(`options?`: string \| string[] \| [MigrateOptions](../globals.md#migrateoptions)): Promise&#60;[UmzugMigration](../globals.md#umzugmigration)[]>

*Defined in [packages/core/src/typings.ts:327](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L327)*

#### Parameters:

Name | Type |
------ | ------ |
`options?` | string \| string[] \| [MigrateOptions](../globals.md#migrateoptions) |

**Returns:** Promise&#60;[UmzugMigration](../globals.md#umzugmigration)[]>
