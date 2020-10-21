---
id: "foreignkeyconstraintviolationexception"
title: "Class: ForeignKeyConstraintViolationException"
sidebar_label: "ForeignKeyConstraintViolationException"
---

Exception for a foreign key constraint violation detected in the driver.

## Hierarchy

* [ConstraintViolationException](constraintviolationexception.md)

  ↳ **ForeignKeyConstraintViolationException**

## Constructors

### constructor

\+ **new ForeignKeyConstraintViolationException**(`previous`: [Error](driverexception.md#error)): [ForeignKeyConstraintViolationException](foreignkeyconstraintviolationexception.md)

*Inherited from [DriverException](driverexception.md).[constructor](driverexception.md#constructor)*

*Defined in [packages/core/src/exceptions.ts:10](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/exceptions.ts#L10)*

#### Parameters:

Name | Type |
------ | ------ |
`previous` | [Error](driverexception.md#error) |

**Returns:** [ForeignKeyConstraintViolationException](foreignkeyconstraintviolationexception.md)

## Properties

### code

• `Optional` **code**: string

*Inherited from [DriverException](driverexception.md).[code](driverexception.md#code)*

*Defined in [packages/core/src/exceptions.ts:6](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/exceptions.ts#L6)*

___

### errmsg

• `Optional` **errmsg**: string

*Inherited from [DriverException](driverexception.md).[errmsg](driverexception.md#errmsg)*

*Defined in [packages/core/src/exceptions.ts:10](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/exceptions.ts#L10)*

___

### errno

• `Optional` **errno**: number

*Inherited from [DriverException](driverexception.md).[errno](driverexception.md#errno)*

*Defined in [packages/core/src/exceptions.ts:7](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/exceptions.ts#L7)*

___

### message

•  **message**: string

*Inherited from [DriverException](driverexception.md).[message](driverexception.md#message)*

*Defined in node_modules/typescript/lib/lib.es5.d.ts:974*

___

### name

•  **name**: string

*Inherited from [DriverException](driverexception.md).[name](driverexception.md#name)*

*Defined in node_modules/typescript/lib/lib.es5.d.ts:973*

___

### sqlMessage

• `Optional` **sqlMessage**: string

*Inherited from [DriverException](driverexception.md).[sqlMessage](driverexception.md#sqlmessage)*

*Defined in [packages/core/src/exceptions.ts:9](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/exceptions.ts#L9)*

___

### sqlState

• `Optional` **sqlState**: string

*Inherited from [DriverException](driverexception.md).[sqlState](driverexception.md#sqlstate)*

*Defined in [packages/core/src/exceptions.ts:8](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/exceptions.ts#L8)*

___

### stack

• `Optional` **stack**: string

*Inherited from [DriverException](driverexception.md).[stack](driverexception.md#stack)*

*Defined in node_modules/typescript/lib/lib.es5.d.ts:975*
