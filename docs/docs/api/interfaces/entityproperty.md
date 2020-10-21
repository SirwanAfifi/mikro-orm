---
id: "entityproperty"
title: "Interface: EntityProperty<T>"
sidebar_label: "EntityProperty"
---

## Type parameters

Name | Type | Default |
------ | ------ | ------ |
`T` | [AnyEntity](../globals.md#anyentity)&#60;T> | any |

## Hierarchy

* **EntityProperty**

## Properties

### array

• `Optional` **array**: boolean

*Defined in [packages/core/src/typings.ts:125](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L125)*

___

### cascade

•  **cascade**: [Cascade](../enums/cascade.md)[]

*Defined in [packages/core/src/typings.ts:154](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L154)*

___

### columnTypes

•  **columnTypes**: string[]

*Defined in [packages/core/src/typings.ts:120](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L120)*

___

### comment

• `Optional` **comment**: string

*Defined in [packages/core/src/typings.ts:174](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L174)*

___

### customType

•  **customType**: [Type](../classes/type.md)&#60;any>

*Defined in [packages/core/src/typings.ts:121](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L121)*

___

### default

• `Optional` **default**: string \| number \| boolean \| null

*Defined in [packages/core/src/typings.ts:131](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L131)*

___

### defaultRaw

• `Optional` **defaultRaw**: string

*Defined in [packages/core/src/typings.ts:132](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L132)*

___

### eager

• `Optional` **eager**: boolean

*Defined in [packages/core/src/typings.ts:150](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L150)*

___

### embeddable

•  **embeddable**: [Constructor](../globals.md#constructor)&#60;T>

*Defined in [packages/core/src/typings.ts:136](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L136)*

___

### embedded

• `Optional` **embedded**: [string, string]

*Defined in [packages/core/src/typings.ts:135](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L135)*

___

### embeddedProps

•  **embeddedProps**: [Dictionary](../globals.md#dictionary)&#60;[EntityProperty](entityproperty.md)>

*Defined in [packages/core/src/typings.ts:137](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L137)*

___

### entity

•  **entity**: () => [EntityName](../globals.md#entityname)&#60;T>

*Defined in [packages/core/src/typings.ts:118](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L118)*

___

### enum

• `Optional` **enum**: boolean

*Defined in [packages/core/src/typings.ts:147](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L147)*

___

### fieldNameRaw

• `Optional` **fieldNameRaw**: string

*Defined in [packages/core/src/typings.ts:130](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L130)*

___

### fieldNames

•  **fieldNames**: string[]

*Defined in [packages/core/src/typings.ts:129](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L129)*

___

### fixedOrder

• `Optional` **fixedOrder**: boolean

*Defined in [packages/core/src/typings.ts:165](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L165)*

___

### fixedOrderColumn

• `Optional` **fixedOrderColumn**: string

*Defined in [packages/core/src/typings.ts:166](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L166)*

___

### formula

• `Optional` **formula**: (alias: string) => string

*Defined in [packages/core/src/typings.ts:133](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L133)*

___

### getter

• `Optional` **getter**: boolean

*Defined in [packages/core/src/typings.ts:152](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L152)*

___

### getterName

• `Optional` **getterName**: keyof T

*Defined in [packages/core/src/typings.ts:153](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L153)*

___

### hidden

• `Optional` **hidden**: boolean

*Defined in [packages/core/src/typings.ts:146](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L146)*

___

### index

• `Optional` **index**: boolean \| string

*Defined in [packages/core/src/typings.ts:139](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L139)*

___

### inherited

• `Optional` **inherited**: boolean

*Defined in [packages/core/src/typings.ts:142](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L142)*

___

### inverseJoinColumns

•  **inverseJoinColumns**: string[]

*Defined in [packages/core/src/typings.ts:169](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L169)*

___

### inversedBy

•  **inversedBy**: string

*Defined in [packages/core/src/typings.ts:162](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L162)*

___

### items

• `Optional` **items**: (number \| string)[]

*Defined in [packages/core/src/typings.ts:148](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L148)*

___

### joinColumns

•  **joinColumns**: string[]

*Defined in [packages/core/src/typings.ts:168](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L168)*

___

### lazy

• `Optional` **lazy**: boolean

*Defined in [packages/core/src/typings.ts:124](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L124)*

___

### length

• `Optional` **length**: any

*Defined in [packages/core/src/typings.ts:126](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L126)*

___

### mapToPk

• `Optional` **mapToPk**: boolean

*Defined in [packages/core/src/typings.ts:144](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L144)*

___

### mappedBy

•  **mappedBy**: string

*Defined in [packages/core/src/typings.ts:163](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L163)*

___

### name

•  **name**: string & keyof T

*Defined in [packages/core/src/typings.ts:117](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L117)*

___

### nullable

• `Optional` **nullable**: boolean

*Defined in [packages/core/src/typings.ts:141](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L141)*

___

### object

• `Optional` **object**: boolean

*Defined in [packages/core/src/typings.ts:138](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L138)*

___

### onCreate

• `Optional` **onCreate**: (entity: T) => any

*Defined in [packages/core/src/typings.ts:156](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L156)*

___

### onDelete

• `Optional` **onDelete**: &#34;cascade&#34; \| &#34;no action&#34; \| &#34;set null&#34; \| &#34;set default&#34; \| string

*Defined in [packages/core/src/typings.ts:158](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L158)*

___

### onUpdate

• `Optional` **onUpdate**: (entity: T) => any

*Defined in [packages/core/src/typings.ts:157](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L157)*

___

### onUpdateIntegrity

• `Optional` **onUpdateIntegrity**: &#34;cascade&#34; \| &#34;no action&#34; \| &#34;set null&#34; \| &#34;set default&#34; \| string

*Defined in [packages/core/src/typings.ts:159](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L159)*

___

### orderBy

• `Optional` **orderBy**: { [field:string]: [QueryOrder](../enums/queryorder.md);  }

*Defined in [packages/core/src/typings.ts:164](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L164)*

___

### orphanRemoval

• `Optional` **orphanRemoval**: boolean

*Defined in [packages/core/src/typings.ts:155](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L155)*

___

### owner

•  **owner**: boolean

*Defined in [packages/core/src/typings.ts:161](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L161)*

___

### persist

• `Optional` **persist**: boolean

*Defined in [packages/core/src/typings.ts:145](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L145)*

___

### pivotTable

•  **pivotTable**: string

*Defined in [packages/core/src/typings.ts:167](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L167)*

___

### prefix

• `Optional` **prefix**: string \| boolean

*Defined in [packages/core/src/typings.ts:134](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L134)*

___

### primary

•  **primary**: boolean

*Defined in [packages/core/src/typings.ts:122](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L122)*

___

### reference

•  **reference**: [ReferenceType](../enums/referencetype.md)

*Defined in [packages/core/src/typings.ts:127](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L127)*

___

### referencedColumnNames

•  **referencedColumnNames**: string[]

*Defined in [packages/core/src/typings.ts:170](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L170)*

___

### referencedTableName

•  **referencedTableName**: string

*Defined in [packages/core/src/typings.ts:171](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L171)*

___

### serializedName

• `Optional` **serializedName**: string

*Defined in [packages/core/src/typings.ts:173](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L173)*

___

### serializedPrimaryKey

•  **serializedPrimaryKey**: boolean

*Defined in [packages/core/src/typings.ts:123](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L123)*

___

### serializer

• `Optional` **serializer**: (value: any) => any

*Defined in [packages/core/src/typings.ts:172](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L172)*

___

### setter

• `Optional` **setter**: boolean

*Defined in [packages/core/src/typings.ts:151](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L151)*

___

### strategy

• `Optional` **strategy**: [LoadStrategy](../enums/loadstrategy.md)

*Defined in [packages/core/src/typings.ts:160](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L160)*

___

### type

•  **type**: string

*Defined in [packages/core/src/typings.ts:119](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L119)*

___

### unique

• `Optional` **unique**: boolean \| string

*Defined in [packages/core/src/typings.ts:140](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L140)*

___

### unsigned

•  **unsigned**: boolean

*Defined in [packages/core/src/typings.ts:143](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L143)*

___

### userDefined

• `Optional` **userDefined**: boolean

*Defined in [packages/core/src/typings.ts:175](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L175)*

___

### version

• `Optional` **version**: boolean

*Defined in [packages/core/src/typings.ts:149](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L149)*

___

### wrappedReference

• `Optional` **wrappedReference**: boolean

*Defined in [packages/core/src/typings.ts:128](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L128)*
