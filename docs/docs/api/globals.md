---
id: "globals"
title: "@mikro-orm/core"
sidebar_label: "Globals"
---

## Index

### Enumerations

* [Cascade](enums/cascade.md)
* [ChangeSetType](enums/changesettype.md)
* [EventType](enums/eventtype.md)
* [GroupOperator](enums/groupoperator.md)
* [LoadStrategy](enums/loadstrategy.md)
* [LockMode](enums/lockmode.md)
* [NodeState](enums/nodestate.md)
* [QueryFlag](enums/queryflag.md)
* [QueryOperator](enums/queryoperator.md)
* [QueryOrder](enums/queryorder.md)
* [QueryOrderNumeric](enums/queryordernumeric.md)
* [ReferenceType](enums/referencetype.md)

### Classes

* [AbstractNamingStrategy](classes/abstractnamingstrategy.md)
* [ArrayCollection](classes/arraycollection.md)
* [ArrayType](classes/arraytype.md)
* [BaseEntity](classes/baseentity.md)
* [BigIntType](classes/biginttype.md)
* [BlobType](classes/blobtype.md)
* [ChangeSetComputer](classes/changesetcomputer.md)
* [ChangeSetPersister](classes/changesetpersister.md)
* [Collection](classes/collection.md)
* [CommitOrderCalculator](classes/commitordercalculator.md)
* [Configuration](classes/configuration.md)
* [ConfigurationLoader](classes/configurationloader.md)
* [Connection](classes/connection.md)
* [ConnectionException](classes/connectionexception.md)
* [ConstraintViolationException](classes/constraintviolationexception.md)
* [DatabaseDriver](classes/databasedriver.md)
* [DatabaseObjectExistsException](classes/databaseobjectexistsexception.md)
* [DatabaseObjectNotFoundException](classes/databaseobjectnotfoundexception.md)
* [DateType](classes/datetype.md)
* [DeadlockException](classes/deadlockexception.md)
* [DriverException](classes/driverexception.md)
* [EntityAssigner](classes/entityassigner.md)
* [EntityCaseNamingStrategy](classes/entitycasenamingstrategy.md)
* [EntityComparator](classes/entitycomparator.md)
* [EntityFactory](classes/entityfactory.md)
* [EntityHelper](classes/entityhelper.md)
* [EntityIdentifier](classes/entityidentifier.md)
* [EntityLoader](classes/entityloader.md)
* [EntityManager](classes/entitymanager.md)
* [EntityMetadata](classes/entitymetadata.md)
* [EntityRepository](classes/entityrepository.md)
* [EntitySchema](classes/entityschema.md)
* [EntityTransformer](classes/entitytransformer.md)
* [EntityValidator](classes/entityvalidator.md)
* [EnumArrayType](classes/enumarraytype.md)
* [EventManager](classes/eventmanager.md)
* [ExceptionConverter](classes/exceptionconverter.md)
* [FileCacheAdapter](classes/filecacheadapter.md)
* [ForeignKeyConstraintViolationException](classes/foreignkeyconstraintviolationexception.md)
* [Hydrator](classes/hydrator.md)
* [IdentityMap](classes/identitymap.md)
* [InvalidFieldNameException](classes/invalidfieldnameexception.md)
* [JavaScriptMetadataProvider](classes/javascriptmetadataprovider.md)
* [JsonType](classes/jsontype.md)
* [LockWaitTimeoutException](classes/lockwaittimeoutexception.md)
* [Logger](classes/logger.md)
* [MemoryCacheAdapter](classes/memorycacheadapter.md)
* [MetadataDiscovery](classes/metadatadiscovery.md)
* [MetadataError](classes/metadataerror.md)
* [MetadataProvider](classes/metadataprovider.md)
* [MetadataStorage](classes/metadatastorage.md)
* [MetadataValidator](classes/metadatavalidator.md)
* [MikroORM](classes/mikroorm.md)
* [MongoNamingStrategy](classes/mongonamingstrategy.md)
* [NonUniqueFieldNameException](classes/nonuniquefieldnameexception.md)
* [NotFoundError](classes/notfounderror.md)
* [NotNullConstraintViolationException](classes/notnullconstraintviolationexception.md)
* [NullCacheAdapter](classes/nullcacheadapter.md)
* [NullHighlighter](classes/nullhighlighter.md)
* [ObjectHydrator](classes/objecthydrator.md)
* [OptimisticLockError](classes/optimisticlockerror.md)
* [Platform](classes/platform.md)
* [QueryHelper](classes/queryhelper.md)
* [ReadOnlyException](classes/readonlyexception.md)
* [Reference](classes/reference.md)
* [ReflectMetadataProvider](classes/reflectmetadataprovider.md)
* [RequestContext](classes/requestcontext.md)
* [SerializationContext](classes/serializationcontext.md)
* [ServerException](classes/serverexception.md)
* [SyntaxErrorException](classes/syntaxerrorexception.md)
* [TableExistsException](classes/tableexistsexception.md)
* [TableNotFoundException](classes/tablenotfoundexception.md)
* [TimeType](classes/timetype.md)
* [Type](classes/type.md)
* [UnderscoreNamingStrategy](classes/underscorenamingstrategy.md)
* [UniqueConstraintViolationException](classes/uniqueconstraintviolationexception.md)
* [UnitOfWork](classes/unitofwork.md)
* [Utils](classes/utils.md)
* [ValidationError](classes/validationerror.md)
* [WrappedEntity](classes/wrappedentity.md)

### Interfaces

* [AssignOptions](interfaces/assignoptions.md)
* [CacheAdapter](interfaces/cacheadapter.md)
* [ChangeSet](interfaces/changeset.md)
* [ConnectionConfig](interfaces/connectionconfig.md)
* [ConnectionOptions](interfaces/connectionoptions.md)
* [CountOptions](interfaces/countoptions.md)
* [DeleteOptions](interfaces/deleteoptions.md)
* [Edge](interfaces/edge.md)
* [EntityProperty](interfaces/entityproperty.md)
* [EnumOptions](interfaces/enumoptions.md)
* [EventArgs](interfaces/eventargs.md)
* [EventSubscriber](interfaces/eventsubscriber.md)
* [FactoryOptions](interfaces/factoryoptions.md)
* [FindOneOptions](interfaces/findoneoptions.md)
* [FindOneOrFailOptions](interfaces/findoneorfailoptions.md)
* [FindOptions](interfaces/findoptions.md)
* [FlatQueryOrderMap](interfaces/flatqueryordermap.md)
* [FlushEventArgs](interfaces/flusheventargs.md)
* [Highlighter](interfaces/highlighter.md)
* [HydratorConstructor](interfaces/hydratorconstructor.md)
* [IConfiguration](interfaces/iconfiguration.md)
* [IDatabaseDriver](interfaces/idatabasedriver.md)
* [IEntityGenerator](interfaces/ientitygenerator.md)
* [IHydrator](interfaces/ihydrator.md)
* [IMetadataStorage](interfaces/imetadatastorage.md)
* [IMigrator](interfaces/imigrator.md)
* [ISchemaGenerator](interfaces/ischemagenerator.md)
* [IWrappedEntity](interfaces/iwrappedentity.md)
* [IWrappedEntityInternal](interfaces/iwrappedentityinternal.md)
* [IndexOptions](interfaces/indexoptions.md)
* [InitOptions](interfaces/initoptions.md)
* [LoadedCollection](interfaces/loadedcollection.md)
* [LoadedReference](interfaces/loadedreference.md)
* [ManyToManyOptions](interfaces/manytomanyoptions.md)
* [ManyToOneOptions](interfaces/manytooneoptions.md)
* [Migration](interfaces/migration.md)
* [MigrationObject](interfaces/migrationobject.md)
* [MikroORMOptions](interfaces/mikroormoptions.md)
* [NamingStrategy](interfaces/namingstrategy.md)
* [Node](interfaces/node.md)
* [OneToOneOptions](interfaces/onetooneoptions.md)
* [PoolConfig](interfaces/poolconfig.md)
* [PrimaryKeyOptions](interfaces/primarykeyoptions.md)
* [QueryOrderMap](interfaces/queryordermap.md)
* [QueryResult](interfaces/queryresult.md)
* [ReferenceOptions](interfaces/referenceoptions.md)
* [SerializedPrimaryKeyOptions](interfaces/serializedprimarykeyoptions.md)
* [Settings](interfaces/settings.md)
* [UniqueOptions](interfaces/uniqueoptions.md)
* [UpdateOptions](interfaces/updateoptions.md)

### Type aliases

* [AnyEntity](globals.md#anyentity)
* [Comparator](globals.md#comparator)
* [Constructor](globals.md#constructor)
* [DeepPartial](globals.md#deeppartial)
* [Dictionary](globals.md#dictionary)
* [EmbeddedOptions](globals.md#embeddedoptions)
* [EntityClass](globals.md#entityclass)
* [EntityClassGroup](globals.md#entityclassgroup)
* [EntityData](globals.md#entitydata)
* [EntityHydrator](globals.md#entityhydrator)
* [EntityName](globals.md#entityname)
* [EntityOptions](globals.md#entityoptions)
* [ExpandObject](globals.md#expandobject)
* [ExpandProperty](globals.md#expandproperty)
* [ExpandScalar](globals.md#expandscalar)
* [FilterDef](globals.md#filterdef)
* [FilterQuery](globals.md#filterquery)
* [FilterValue](globals.md#filtervalue)
* [FilterValue2](globals.md#filtervalue2)
* [GetRepository](globals.md#getrepository)
* [IPrimaryKey](globals.md#iprimarykey)
* [IPrimaryKeyValue](globals.md#iprimarykeyvalue)
* [IdentifiedReference](globals.md#identifiedreference)
* [Loaded](globals.md#loaded)
* [LoadedIfInKeyHint](globals.md#loadedifinkeyhint)
* [LoadedIfInNestedHint](globals.md#loadedifinnestedhint)
* [LoggerNamespace](globals.md#loggernamespace)
* [MarkLoaded](globals.md#markloaded)
* [Metadata](globals.md#metadata)
* [MigrateOptions](globals.md#migrateoptions)
* [MigrationResult](globals.md#migrationresult)
* [MigrationRow](globals.md#migrationrow)
* [MigrationsOptions](globals.md#migrationsoptions)
* [NestedLoadHint](globals.md#nestedloadhint)
* [New](globals.md#new)
* [NonFunctionPropertyNames](globals.md#nonfunctionpropertynames)
* [ORMDomain](globals.md#ormdomain)
* [OneToManyOptions](globals.md#onetomanyoptions)
* [OperatorMap](globals.md#operatormap)
* [Options](globals.md#options)
* [PkGetter](globals.md#pkgetter)
* [PkSerializer](globals.md#pkserializer)
* [Populate](globals.md#populate)
* [PopulateChildren](globals.md#populatechildren)
* [PopulateMap](globals.md#populatemap)
* [PopulateOptions](globals.md#populateoptions)
* [Primary](globals.md#primary)
* [Property](globals.md#property)
* [PropertyKey](globals.md#propertykey)
* [PropertyOptions](globals.md#propertyoptions)
* [QBFilterQuery](globals.md#qbfilterquery)
* [Query](globals.md#query)
* [QueryOrderKeys](globals.md#queryorderkeys)
* [QueryOrderKeysFlat](globals.md#queryorderkeysflat)
* [RelationsIn](globals.md#relationsin)
* [ResultMapper](globals.md#resultmapper)
* [Scalar](globals.md#scalar)
* [SnapshotGenerator](globals.md#snapshotgenerator)
* [SubType](globals.md#subtype)
* [Transaction](globals.md#transaction)
* [TypeDef](globals.md#typedef)
* [TypeType](globals.md#typetype)
* [UmzugMigration](globals.md#umzugmigration)

### Variables

* [ARRAY\_OPERATORS](globals.md#array_operators)
* [EntityManagerType](globals.md#entitymanagertype)
* [EntityRepositoryType](globals.md#entityrepositorytype)
* [ObjectBindingPattern](globals.md#objectbindingpattern)
* [PrimaryKeyType](globals.md#primarykeytype)
* [SCALAR\_TYPES](globals.md#scalar_types)
* [assign](globals.md#assign)
* [entityHelperSymbol](globals.md#entityhelpersymbol)
* [equalsFn](globals.md#equalsfn)
* [validator](globals.md#validator)

### Functions

* [AfterCreate](globals.md#aftercreate)
* [AfterDelete](globals.md#afterdelete)
* [AfterUpdate](globals.md#afterupdate)
* [BeforeCreate](globals.md#beforecreate)
* [BeforeDelete](globals.md#beforedelete)
* [BeforeUpdate](globals.md#beforeupdate)
* [Embeddable](globals.md#embeddable)
* [Embedded](globals.md#embedded)
* [Entity](globals.md#entity)
* [Enum](globals.md#enum)
* [Filter](globals.md#filter)
* [Formula](globals.md#formula)
* [Index](globals.md#index)
* [ManyToMany](globals.md#manytomany)
* [ManyToOne](globals.md#manytoone)
* [OnInit](globals.md#oninit)
* [OneToMany](globals.md#onetomany)
* [OneToOne](globals.md#onetoone)
* [PrimaryKey](globals.md#primarykey)
* [Property](globals.md#property)
* [Repository](globals.md#repository)
* [SerializedPrimaryKey](globals.md#serializedprimarykey)
* [Subscriber](globals.md#subscriber)
* [Unique](globals.md#unique)
* [compareArrays](globals.md#comparearrays)
* [compareBuffers](globals.md#comparebuffers)
* [compareObjects](globals.md#compareobjects)
* [createDecorator](globals.md#createdecorator)
* [createOneToDecorator](globals.md#createonetodecorator)
* [equals](globals.md#equals)
* [expr](globals.md#expr)
* [hook](globals.md#hook)
* [mapHydrator](globals.md#maphydrator)
* [wrap](globals.md#wrap)

## Type aliases

### AnyEntity

Ƭ  **AnyEntity**&#60;T>: Partial&#60;T> & { [EntityRepositoryType]?: unknown ; [PrimaryKeyType]?: unknown ; __helper?: [IWrappedEntityInternal](interfaces/iwrappedentityinternal.md)&#60;T, keyof T> ; __meta?: [EntityMetadata](classes/entitymetadata.md)&#60;T> ; __platform?: [Platform](classes/platform.md)  }

*Defined in [packages/core/src/typings.ts:101](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L101)*

#### Type parameters:

Name | Default |
------ | ------ |
`T` | any |

___

### Comparator

Ƭ  **Comparator**&#60;T>: (a: T, b: T) => [EntityData](globals.md#entitydata)&#60;T>

*Defined in [packages/core/src/utils/EntityComparator.ts:7](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/utils/EntityComparator.ts#L7)*

#### Type parameters:

Name |
------ |
`T` |

___

### Constructor

Ƭ  **Constructor**&#60;T>: {}

*Defined in [packages/core/src/typings.ts:8](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L8)*

#### Type parameters:

Name |
------ |
`T` |

___

### DeepPartial

Ƭ  **DeepPartial**&#60;T>: T & {}

*Defined in [packages/core/src/typings.ts:13](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L13)*

#### Type parameters:

Name |
------ |
`T` |

___

### Dictionary

Ƭ  **Dictionary**&#60;T>: { [k:string]: T;  }

*Defined in [packages/core/src/typings.ts:9](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L9)*

#### Type parameters:

Name | Default |
------ | ------ |
`T` | any |

___

### EmbeddedOptions

Ƭ  **EmbeddedOptions**: { entity?: string \| () => [AnyEntity](globals.md#anyentity) ; nullable?: boolean ; object?: boolean ; prefix?: string \| boolean ; type?: string  }

*Defined in [packages/core/src/decorators/Embedded.ts:19](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/decorators/Embedded.ts#L19)*

#### Type declaration:

Name | Type |
------ | ------ |
`entity?` | string \| () => [AnyEntity](globals.md#anyentity) |
`nullable?` | boolean |
`object?` | boolean |
`prefix?` | string \| boolean |
`type?` | string |

___

### EntityClass

Ƭ  **EntityClass**&#60;T>: Function & { prototype: T  }

*Defined in [packages/core/src/typings.ts:110](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L110)*

#### Type parameters:

Name | Type |
------ | ------ |
`T` | [AnyEntity](globals.md#anyentity)&#60;T> |

___

### EntityClassGroup

Ƭ  **EntityClassGroup**&#60;T>: { entity: [EntityClass](globals.md#entityclass)&#60;T> ; schema: [EntityMetadata](classes/entitymetadata.md)&#60;T> \| [EntitySchema](classes/entityschema.md)&#60;T>  }

*Defined in [packages/core/src/typings.ts:111](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L111)*

#### Type parameters:

Name | Type |
------ | ------ |
`T` | [AnyEntity](globals.md#anyentity)&#60;T> |

#### Type declaration:

Name | Type |
------ | ------ |
`entity` | [EntityClass](globals.md#entityclass)&#60;T> |
`schema` | [EntityMetadata](classes/entitymetadata.md)&#60;T> \| [EntitySchema](classes/entityschema.md)&#60;T> |

___

### EntityData

Ƭ  **EntityData**&#60;T>: {} & [Dictionary](globals.md#dictionary)

*Defined in [packages/core/src/typings.ts:113](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L113)*

#### Type parameters:

Name |
------ |
`T` |

___

### EntityHydrator

Ƭ  **EntityHydrator**&#60;T>: (entity: T, data: [EntityData](globals.md#entitydata)&#60;T>, factory: [EntityFactory](classes/entityfactory.md), newEntity: boolean, convertCustomTypes: boolean) => void

*Defined in [packages/core/src/hydration/ObjectHydrator.ts:9](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/hydration/ObjectHydrator.ts#L9)*

#### Type parameters:

Name |
------ |
`T` |

___

### EntityName

Ƭ  **EntityName**&#60;T>: string \| [EntityClass](globals.md#entityclass)&#60;T> \| [EntitySchema](classes/entityschema.md)&#60;T, any>

*Defined in [packages/core/src/typings.ts:112](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L112)*

#### Type parameters:

Name | Type |
------ | ------ |
`T` | [AnyEntity](globals.md#anyentity)&#60;T> |

___

### EntityOptions

Ƭ  **EntityOptions**&#60;T>: { abstract?: boolean ; collection?: string ; comment?: string ; customRepository?: () => [Constructor](globals.md#constructor)&#60;[EntityRepository](classes/entityrepository.md)&#60;T>> ; discriminatorColumn?: string ; discriminatorMap?: [Dictionary](globals.md#dictionary)&#60;string> ; discriminatorValue?: string ; readonly?: boolean ; tableName?: string  }

*Defined in [packages/core/src/decorators/Entity.ts:20](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/decorators/Entity.ts#L20)*

#### Type parameters:

Name |
------ |
`T` |

#### Type declaration:

Name | Type |
------ | ------ |
`abstract?` | boolean |
`collection?` | string |
`comment?` | string |
`customRepository?` | () => [Constructor](globals.md#constructor)&#60;[EntityRepository](classes/entityrepository.md)&#60;T>> |
`discriminatorColumn?` | string |
`discriminatorMap?` | [Dictionary](globals.md#dictionary)&#60;string> |
`discriminatorValue?` | string |
`readonly?` | boolean |
`tableName?` | string |

___

### ExpandObject

Ƭ  **ExpandObject**&#60;U>: {} \| [FilterValue](globals.md#filtervalue)&#60;[ExpandProperty](globals.md#expandproperty)&#60;U>>

*Defined in [packages/core/src/typings.ts:61](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L61)*

#### Type parameters:

Name |
------ |
`U` |

___

### ExpandProperty

Ƭ  **ExpandProperty**&#60;T>: T *extends* Reference&#60;*infer* U> ? NonNullable&#60;U> : T *extends* Collection&#60;*infer* U> ? NonNullable&#60;U> : NonNullable&#60;T>

*Defined in [packages/core/src/typings.ts:349](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L349)*

#### Type parameters:

Name |
------ |
`T` |

___

### ExpandScalar

Ƭ  **ExpandScalar**&#60;T>: null \| T *extends* string ? string \| RegExp : T *extends* Date ? Date \| string : T

*Defined in [packages/core/src/typings.ts:33](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L33)*

#### Type parameters:

Name |
------ |
`T` |

___

### FilterDef

Ƭ  **FilterDef**&#60;T>: { args?: boolean ; cond: [FilterQuery](globals.md#filterquery)&#60;T> \| (args: [Dictionary](globals.md#dictionary), type: &#34;read&#34; \| &#34;update&#34; \| &#34;delete&#34;) => [FilterQuery](globals.md#filterquery)&#60;T> \| Promise&#60;[FilterQuery](globals.md#filterquery)&#60;T>> ; default?: boolean ; entity?: string[] ; name: string  }

*Defined in [packages/core/src/typings.ts:341](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L341)*

#### Type parameters:

Name | Type |
------ | ------ |
`T` | [AnyEntity](globals.md#anyentity)&#60;T> |

#### Type declaration:

Name | Type |
------ | ------ |
`args?` | boolean |
`cond` | [FilterQuery](globals.md#filterquery)&#60;T> \| (args: [Dictionary](globals.md#dictionary), type: &#34;read&#34; \| &#34;update&#34; \| &#34;delete&#34;) => [FilterQuery](globals.md#filterquery)&#60;T> \| Promise&#60;[FilterQuery](globals.md#filterquery)&#60;T>> |
`default?` | boolean |
`entity?` | string[] |
`name` | string |

___

### FilterQuery

Ƭ  **FilterQuery**&#60;T>: NonNullable&#60;[Query](globals.md#query)&#60;T>> \| { [PrimaryKeyType]?: any  }

*Defined in [packages/core/src/typings.ts:68](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L68)*

#### Type parameters:

Name |
------ |
`T` |

___

### FilterValue

Ƭ  **FilterValue**&#60;T>: [OperatorMap](globals.md#operatormap)&#60;[FilterValue2](globals.md#filtervalue2)&#60;T>> \| [FilterValue2](globals.md#filtervalue2)&#60;T> \| [FilterValue2](globals.md#filtervalue2)&#60;T>[] \| null

*Defined in [packages/core/src/typings.ts:60](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L60)*

#### Type parameters:

Name |
------ |
`T` |

___

### FilterValue2

Ƭ  **FilterValue2**&#60;T>: T \| [ExpandScalar](globals.md#expandscalar)&#60;T> \| [Primary](globals.md#primary)&#60;T>

*Defined in [packages/core/src/typings.ts:59](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L59)*

#### Type parameters:

Name |
------ |
`T` |

___

### GetRepository

Ƭ  **GetRepository**&#60;T, U>: T[*typeof* EntityRepositoryType] *extends* EntityRepository&#60;any> \| undefined ? NonNullable&#60;T[*typeof* EntityRepositoryType]> : U

*Defined in [packages/core/src/typings.ts:114](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L114)*

#### Type parameters:

Name | Type |
------ | ------ |
`T` | [AnyEntity](globals.md#anyentity)&#60;T> |
`U` | - |

___

### IPrimaryKey

Ƭ  **IPrimaryKey**&#60;T>: T

*Defined in [packages/core/src/typings.ts:29](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L29)*

#### Type parameters:

Name | Type | Default |
------ | ------ | ------ |
`T` | [IPrimaryKeyValue](globals.md#iprimarykeyvalue) | IPrimaryKeyValue |

___

### IPrimaryKeyValue

Ƭ  **IPrimaryKeyValue**: number \| string \| bigint \| Date \| { toHexString: () => string  }

*Defined in [packages/core/src/typings.ts:28](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L28)*

___

### IdentifiedReference

Ƭ  **IdentifiedReference**&#60;T, PK>: {} & [Reference](classes/reference.md)&#60;T>

*Defined in [packages/core/src/entity/Reference.ts:4](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/entity/Reference.ts#L4)*

#### Type parameters:

Name | Type | Default |
------ | ------ | ------ |
`T` | [AnyEntity](globals.md#anyentity)&#60;T> | - |
`PK` | keyof T | &#34;id&#34; & keyof T |

___

### Loaded

Ƭ  **Loaded**&#60;T, P>: unknown *extends* P ? T : T & {}

*Defined in [packages/core/src/typings.ts:390](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L390)*

#### Type parameters:

Name | Type | Default |
------ | ------ | ------ |
`T` | [AnyEntity](globals.md#anyentity)&#60;T> | - |
`P` | - | unknown |

___

### LoadedIfInKeyHint

Ƭ  **LoadedIfInKeyHint**&#60;T, K, H>: K *extends* H ? MarkLoaded&#60;T, T[K]> : T[K]

*Defined in [packages/core/src/typings.ts:377](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L377)*

#### Type parameters:

Name | Type |
------ | ------ |
`T` | [AnyEntity](globals.md#anyentity)&#60;T> |
`K` | keyof T |
`H` | - |

___

### LoadedIfInNestedHint

Ƭ  **LoadedIfInNestedHint**&#60;T, K, H>: K *extends* keyof H ? MarkLoaded&#60;T, T[K], H[K]> : T[K]

*Defined in [packages/core/src/typings.ts:379](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L379)*

#### Type parameters:

Name | Type |
------ | ------ |
`T` | [AnyEntity](globals.md#anyentity)&#60;T> |
`K` | keyof T |
`H` | - |

___

### LoggerNamespace

Ƭ  **LoggerNamespace**: &#34;query&#34; \| &#34;query-params&#34; \| &#34;discovery&#34; \| &#34;info&#34;

*Defined in [packages/core/src/utils/Logger.ts:34](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/utils/Logger.ts#L34)*

___

### MarkLoaded

Ƭ  **MarkLoaded**&#60;T, P, H>: P *extends* Reference&#60;*infer* U> ? LoadedReference&#60;U, Loaded&#60;U, H>> : P *extends* Collection&#60;*infer* U> ? LoadedCollection&#60;U, Loaded&#60;U, H>> : P

*Defined in [packages/core/src/typings.ts:371](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L371)*

#### Type parameters:

Name | Type | Default |
------ | ------ | ------ |
`T` | [AnyEntity](globals.md#anyentity)&#60;T> | - |
`P` | - | - |
`H` | - | unknown |

___

### Metadata

Ƭ  **Metadata**&#60;T, U>: Omit&#60;Partial&#60;[EntityMetadata](classes/entitymetadata.md)&#60;T>>, &#34;name&#34; \| &#34;properties&#34;> & { name: string  } \| { class: [Constructor](globals.md#constructor)&#60;T> ; name?: string  } & { properties?: {}  }

*Defined in [packages/core/src/metadata/EntitySchema.ts:23](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/metadata/EntitySchema.ts#L23)*

#### Type parameters:

Name |
------ |
`T` |
`U` |

___

### MigrateOptions

Ƭ  **MigrateOptions**: { from?: string \| number ; migrations?: string[] ; to?: string \| number  }

*Defined in [packages/core/src/typings.ts:319](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L319)*

#### Type declaration:

Name | Type |
------ | ------ |
`from?` | string \| number |
`migrations?` | string[] |
`to?` | string \| number |

___

### MigrationResult

Ƭ  **MigrationResult**: { code: string ; diff: string[] ; fileName: string  }

*Defined in [packages/core/src/typings.ts:320](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L320)*

#### Type declaration:

Name | Type |
------ | ------ |
`code` | string |
`diff` | string[] |
`fileName` | string |

___

### MigrationRow

Ƭ  **MigrationRow**: { executed_at: Date ; name: string  }

*Defined in [packages/core/src/typings.ts:321](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L321)*

#### Type declaration:

Name | Type |
------ | ------ |
`executed_at` | Date |
`name` | string |

___

### MigrationsOptions

Ƭ  **MigrationsOptions**: { allOrNothing?: boolean ; disableForeignKeys?: boolean ; dropTables?: boolean ; emit?: &#34;js&#34; \| &#34;ts&#34; ; fileName?: (timestamp: string) => string ; migrationsList?: [MigrationObject](interfaces/migrationobject.md)[] ; path?: string ; pattern?: RegExp ; safe?: boolean ; tableName?: string ; transactional?: boolean  }

*Defined in [packages/core/src/utils/Configuration.ts:286](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/utils/Configuration.ts#L286)*

#### Type declaration:

Name | Type |
------ | ------ |
`allOrNothing?` | boolean |
`disableForeignKeys?` | boolean |
`dropTables?` | boolean |
`emit?` | &#34;js&#34; \| &#34;ts&#34; |
`fileName?` | (timestamp: string) => string |
`migrationsList?` | [MigrationObject](interfaces/migrationobject.md)[] |
`path?` | string |
`pattern?` | RegExp |
`safe?` | boolean |
`tableName?` | string |
`transactional?` | boolean |

___

### NestedLoadHint

Ƭ  **NestedLoadHint**&#60;T>: {}

*Defined in [packages/core/src/typings.ts:386](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L386)*

#### Type parameters:

Name |
------ |
`T` |

___

### New

Ƭ  **New**&#60;T, P>: [Loaded](globals.md#loaded)&#60;T, P>

*Defined in [packages/core/src/typings.ts:398](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L398)*

#### Type parameters:

Name | Type | Default |
------ | ------ | ------ |
`T` | [AnyEntity](globals.md#anyentity)&#60;T> | - |
`P` | - | string[] |

___

### NonFunctionPropertyNames

Ƭ  **NonFunctionPropertyNames**&#60;T>: NonNullable&#60;{}[keyof T]>

*Defined in [packages/core/src/typings.ts:11](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L11)*

#### Type parameters:

Name |
------ |
`T` |

___

### ORMDomain

Ƭ  **ORMDomain**: Domain & { __mikro_orm_context?: [RequestContext](classes/requestcontext.md)  }

*Defined in [packages/core/src/utils/RequestContext.ts:5](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/utils/RequestContext.ts#L5)*

___

### OneToManyOptions

Ƭ  **OneToManyOptions**&#60;T, O>: [ReferenceOptions](interfaces/referenceoptions.md)&#60;T, O> & { entity?: string \| () => [EntityName](globals.md#entityname)&#60;T> ; inverseJoinColumn?: string ; inverseJoinColumns?: string[] ; joinColumn?: string ; joinColumns?: string[] ; mappedBy: string & keyof T \| (e: T) => any ; orderBy?: { [field:string]: [QueryOrder](enums/queryorder.md);  } ; orphanRemoval?: boolean ; referenceColumnName?: string  }

*Defined in [packages/core/src/decorators/OneToMany.ts:40](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/decorators/OneToMany.ts#L40)*

#### Type parameters:

Name |
------ |
`T` |
`O` |

___

### OperatorMap

Ƭ  **OperatorMap**&#60;T>: { $and?: [Query](globals.md#query)&#60;T>[] ; $contained?: string[] ; $contains?: string[] ; $eq?: [ExpandScalar](globals.md#expandscalar)&#60;T> ; $gt?: [ExpandScalar](globals.md#expandscalar)&#60;T> ; $gte?: [ExpandScalar](globals.md#expandscalar)&#60;T> ; $ilike?: string ; $in?: [ExpandScalar](globals.md#expandscalar)&#60;T>[] ; $like?: string ; $lt?: [ExpandScalar](globals.md#expandscalar)&#60;T> ; $lte?: [ExpandScalar](globals.md#expandscalar)&#60;T> ; $ne?: [ExpandScalar](globals.md#expandscalar)&#60;T> ; $nin?: [ExpandScalar](globals.md#expandscalar)&#60;T>[] ; $not?: [Query](globals.md#query)&#60;T> ; $or?: [Query](globals.md#query)&#60;T>[] ; $overlap?: string[] ; $re?: string  }

*Defined in [packages/core/src/typings.ts:39](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L39)*

#### Type parameters:

Name |
------ |
`T` |

#### Type declaration:

Name | Type |
------ | ------ |
`$and?` | [Query](globals.md#query)&#60;T>[] |
`$contained?` | string[] |
`$contains?` | string[] |
`$eq?` | [ExpandScalar](globals.md#expandscalar)&#60;T> |
`$gt?` | [ExpandScalar](globals.md#expandscalar)&#60;T> |
`$gte?` | [ExpandScalar](globals.md#expandscalar)&#60;T> |
`$ilike?` | string |
`$in?` | [ExpandScalar](globals.md#expandscalar)&#60;T>[] |
`$like?` | string |
`$lt?` | [ExpandScalar](globals.md#expandscalar)&#60;T> |
`$lte?` | [ExpandScalar](globals.md#expandscalar)&#60;T> |
`$ne?` | [ExpandScalar](globals.md#expandscalar)&#60;T> |
`$nin?` | [ExpandScalar](globals.md#expandscalar)&#60;T>[] |
`$not?` | [Query](globals.md#query)&#60;T> |
`$or?` | [Query](globals.md#query)&#60;T>[] |
`$overlap?` | string[] |
`$re?` | string |

___

### Options

Ƭ  **Options**&#60;T, D>: Pick&#60;[MikroORMOptions](interfaces/mikroormoptions.md)&#60;D>, Exclude&#60;keyof [MikroORMOptions](interfaces/mikroormoptions.md)&#60;D>, keyof *typeof* [DEFAULTS](classes/configuration.md#defaults)>> & Partial&#60;[MikroORMOptions](interfaces/mikroormoptions.md)&#60;D>>

*Defined in [packages/core/src/entity/EntityLoader.ts:10](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/entity/EntityLoader.ts#L10)*

*Defined in [packages/core/src/utils/Configuration.ts:377](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/utils/Configuration.ts#L377)*

#### Type parameters:

Name | Type | Default |
------ | ------ | ------ |
`T` | [AnyEntity](globals.md#anyentity)&#60;T> | - |
`D` | [IDatabaseDriver](interfaces/idatabasedriver.md) | IDatabaseDriver |

___

### PkGetter

Ƭ  **PkGetter**&#60;T>: (entity: T) => [Primary](globals.md#primary)&#60;T>

*Defined in [packages/core/src/utils/EntityComparator.ts:10](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/utils/EntityComparator.ts#L10)*

#### Type parameters:

Name |
------ |
`T` |

___

### PkSerializer

Ƭ  **PkSerializer**&#60;T>: (entity: T) => string

*Defined in [packages/core/src/utils/EntityComparator.ts:11](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/utils/EntityComparator.ts#L11)*

#### Type parameters:

Name |
------ |
`T` |

___

### Populate

Ƭ  **Populate**&#60;T>: readonly keyof T[] \| readonly string[] \| boolean \| [PopulateMap](globals.md#populatemap)&#60;T>

*Defined in [packages/core/src/typings.ts:352](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L352)*

#### Type parameters:

Name |
------ |
`T` |

___

### PopulateChildren

Ƭ  **PopulateChildren**&#60;T>: {}

*Defined in [packages/core/src/typings.ts:350](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L350)*

#### Type parameters:

Name |
------ |
`T` |

___

### PopulateMap

Ƭ  **PopulateMap**&#60;T>: boolean \| [LoadStrategy](enums/loadstrategy.md) \| [PopulateChildren](globals.md#populatechildren)&#60;T>

*Defined in [packages/core/src/typings.ts:351](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L351)*

#### Type parameters:

Name |
------ |
`T` |

___

### PopulateOptions

Ƭ  **PopulateOptions**&#60;T>: { all?: boolean ; children?: [PopulateOptions](globals.md#populateoptions)&#60;T[keyof T]>[] ; field: string ; strategy?: [LoadStrategy](enums/loadstrategy.md)  }

*Defined in [packages/core/src/typings.ts:354](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L354)*

#### Type parameters:

Name |
------ |
`T` |

#### Type declaration:

Name | Type |
------ | ------ |
`all?` | boolean |
`children?` | [PopulateOptions](globals.md#populateoptions)&#60;T[keyof T]>[] |
`field` | string |
`strategy?` | [LoadStrategy](enums/loadstrategy.md) |

___

### Primary

Ƭ  **Primary**&#60;T>: T *extends* { [PrimaryKeyType]: *infer* PK  } ? PK : T *extends* { _id: *infer* PK  } ? PK \| string : T *extends* { uuid: *infer* PK  } ? PK : T *extends* { id: *infer* PK  } ? PK : never

*Defined in [packages/core/src/typings.ts:23](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L23)*

#### Type parameters:

Name |
------ |
`T` |

___

### Property

Ƭ  **Property**&#60;T, O>: { reference: [MANY\_TO\_ONE](enums/referencetype.md#many_to_one) \| &#34;m:1&#34;  } & [TypeDef](globals.md#typedef)&#60;T> & [ManyToOneOptions](interfaces/manytooneoptions.md)&#60;T, O> \| { reference: [ONE\_TO\_ONE](enums/referencetype.md#one_to_one) \| &#34;1:1&#34;  } & [TypeDef](globals.md#typedef)&#60;T> & [OneToOneOptions](interfaces/onetooneoptions.md)&#60;T, O> \| { reference: [ONE\_TO\_MANY](enums/referencetype.md#one_to_many) \| &#34;1:m&#34;  } & [TypeDef](globals.md#typedef)&#60;T> & [OneToManyOptions](globals.md#onetomanyoptions)&#60;T, O> \| { reference: [MANY\_TO\_MANY](enums/referencetype.md#many_to_many) \| &#34;m:n&#34;  } & [TypeDef](globals.md#typedef)&#60;T> & [ManyToManyOptions](interfaces/manytomanyoptions.md)&#60;T, O> \| { reference: [EMBEDDED](enums/referencetype.md#embedded) \| &#34;embedded&#34;  } & [TypeDef](globals.md#typedef)&#60;T> & [EmbeddedOptions](globals.md#embeddedoptions) & [PropertyOptions](globals.md#propertyoptions)&#60;O> \| { enum: true  } & [EnumOptions](interfaces/enumoptions.md)&#60;O> \| [TypeDef](globals.md#typedef)&#60;T> & [PropertyOptions](globals.md#propertyoptions)&#60;O>

*Defined in [packages/core/src/metadata/EntitySchema.ts:14](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/metadata/EntitySchema.ts#L14)*

#### Type parameters:

Name |
------ |
`T` |
`O` |

___

### PropertyKey

Ƭ  **PropertyKey**&#60;T, U>: [NonFunctionPropertyNames](globals.md#nonfunctionpropertynames)&#60;Omit&#60;T, keyof U>>

*Defined in [packages/core/src/metadata/EntitySchema.ts:22](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/metadata/EntitySchema.ts#L22)*

#### Type parameters:

Name |
------ |
`T` |
`U` |

___

### PropertyOptions

Ƭ  **PropertyOptions**&#60;T>: { columnType?: string ; comment?: string ; customType?: [Type](classes/type.md)&#60;any> ; default?: string \| string[] \| number \| number[] \| boolean \| null ; defaultRaw?: string ; fieldName?: string ; fieldNames?: string[] ; formula?: string \| (alias: string) => string ; hidden?: boolean ; index?: boolean \| string ; lazy?: boolean ; length?: number ; name?: string ; nullable?: boolean ; onCreate?: (entity: T) => any ; onUpdate?: (entity: T) => any ; persist?: boolean ; primary?: boolean ; serializedName?: string ; serializedPrimaryKey?: boolean ; serializer?: (value: any) => any ; type?: &#34;string&#34; \| &#34;number&#34; \| &#34;boolean&#34; \| &#34;bigint&#34; \| &#34;ObjectId&#34; \| string \| unknown \| bigint \| Date \| [Constructor](globals.md#constructor)&#60;[Type](classes/type.md)&#60;any>> \| [Type](classes/type.md)&#60;any> ; unique?: boolean \| string ; unsigned?: boolean ; version?: boolean  }

*Defined in [packages/core/src/decorators/Property.ts:37](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/decorators/Property.ts#L37)*

#### Type parameters:

Name |
------ |
`T` |

#### Type declaration:

Name | Type |
------ | ------ |
`columnType?` | string |
`comment?` | string |
`customType?` | [Type](classes/type.md)&#60;any> |
`default?` | string \| string[] \| number \| number[] \| boolean \| null |
`defaultRaw?` | string |
`fieldName?` | string |
`fieldNames?` | string[] |
`formula?` | string \| (alias: string) => string |
`hidden?` | boolean |
`index?` | boolean \| string |
`lazy?` | boolean |
`length?` | number |
`name?` | string |
`nullable?` | boolean |
`onCreate?` | (entity: T) => any |
`onUpdate?` | (entity: T) => any |
`persist?` | boolean |
`primary?` | boolean |
`serializedName?` | string |
`serializedPrimaryKey?` | boolean |
`serializer?` | (value: any) => any |
`type?` | &#34;string&#34; \| &#34;number&#34; \| &#34;boolean&#34; \| &#34;bigint&#34; \| &#34;ObjectId&#34; \| string \| unknown \| bigint \| Date \| [Constructor](globals.md#constructor)&#60;[Type](classes/type.md)&#60;any>> \| [Type](classes/type.md)&#60;any> |
`unique?` | boolean \| string |
`unsigned?` | boolean |
`version?` | boolean |

___

### QBFilterQuery

Ƭ  **QBFilterQuery**&#60;T>: [FilterQuery](globals.md#filterquery)&#60;T> & [Dictionary](globals.md#dictionary) \| [FilterQuery](globals.md#filterquery)&#60;T>

*Defined in [packages/core/src/typings.ts:69](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L69)*

#### Type parameters:

Name | Default |
------ | ------ |
`T` | any |

___

### Query

Ƭ  **Query**&#60;T>: T *extends* Scalar ? FilterValue&#60;T> : T *extends* Collection&#60;*infer* U> ? ExpandObject&#60;U> : ExpandObject&#60;T>

*Defined in [packages/core/src/typings.ts:63](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L63)*

#### Type parameters:

Name |
------ |
`T` |

___

### QueryOrderKeys

Ƭ  **QueryOrderKeys**: [QueryOrderKeysFlat](globals.md#queryorderkeysflat) \| [QueryOrderMap](interfaces/queryordermap.md)

*Defined in [packages/core/src/enums.ts:47](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/enums.ts#L47)*

___

### QueryOrderKeysFlat

Ƭ  **QueryOrderKeysFlat**: [QueryOrder](enums/queryorder.md) \| [QueryOrderNumeric](enums/queryordernumeric.md) \| keyof *typeof* [QueryOrder](enums/queryorder.md)

*Defined in [packages/core/src/enums.ts:46](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/enums.ts#L46)*

___

### RelationsIn

Ƭ  **RelationsIn**&#60;T>: [SubType](globals.md#subtype)&#60;T, [Collection](classes/collection.md)&#60;any> \| [Reference](classes/reference.md)&#60;any> \| undefined>

*Defined in [packages/core/src/typings.ts:384](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L384)*

#### Type parameters:

Name |
------ |
`T` |

___

### ResultMapper

Ƭ  **ResultMapper**&#60;T>: (result: [EntityData](globals.md#entitydata)&#60;T>) => [EntityData](globals.md#entitydata)&#60;T> \| null

*Defined in [packages/core/src/utils/EntityComparator.ts:8](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/utils/EntityComparator.ts#L8)*

#### Type parameters:

Name |
------ |
`T` |

___

### Scalar

Ƭ  **Scalar**: boolean \| number \| string \| bigint \| symbol \| Date \| RegExp \| Buffer \| { toHexString: () => string  }

*Defined in [packages/core/src/typings.ts:31](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L31)*

___

### SnapshotGenerator

Ƭ  **SnapshotGenerator**&#60;T>: (entity: T) => [EntityData](globals.md#entitydata)&#60;T>

*Defined in [packages/core/src/utils/EntityComparator.ts:9](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/utils/EntityComparator.ts#L9)*

#### Type parameters:

Name |
------ |
`T` |

___

### SubType

Ƭ  **SubType**&#60;T, C>: Pick&#60;T, {}[keyof T]>

*Defined in [packages/core/src/typings.ts:382](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L382)*

#### Type parameters:

Name |
------ |
`T` |
`C` |

___

### Transaction

Ƭ  **Transaction**&#60;T>: T

*Defined in [packages/core/src/connections/Connection.ts:140](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/connections/Connection.ts#L140)*

#### Type parameters:

Name | Default |
------ | ------ |
`T` | any |

___

### TypeDef

Ƭ  **TypeDef**&#60;T>: { type: [TypeType](globals.md#typetype)  } \| { customType: [Type](classes/type.md)&#60;any>  } \| { entity: string \| () => string \| [EntityName](globals.md#entityname)&#60;T>  }

*Defined in [packages/core/src/metadata/EntitySchema.ts:13](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/metadata/EntitySchema.ts#L13)*

#### Type parameters:

Name |
------ |
`T` |

___

### TypeType

Ƭ  **TypeType**: string \| NumberConstructor \| StringConstructor \| BooleanConstructor \| DateConstructor \| ArrayConstructor \| [Constructor](globals.md#constructor)&#60;[Type](classes/type.md)&#60;any>>

*Defined in [packages/core/src/metadata/EntitySchema.ts:12](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/metadata/EntitySchema.ts#L12)*

___

### UmzugMigration

Ƭ  **UmzugMigration**: { file: string ; path?: string  }

*Defined in [packages/core/src/typings.ts:318](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L318)*

#### Type declaration:

Name | Type |
------ | ------ |
`file` | string |
`path?` | string |

## Variables

### ARRAY\_OPERATORS

• `Const` **ARRAY\_OPERATORS**: string[] = ['$overlap', '$contains', '$contained']

*Defined in [packages/core/src/enums.ts:24](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/enums.ts#L24)*

___

### EntityManagerType

• `Const` **EntityManagerType**: unique symbol = Symbol('EntityManagerType')

*Defined in [packages/core/src/drivers/IDatabaseDriver.ts:10](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/drivers/IDatabaseDriver.ts#L10)*

___

### EntityRepositoryType

• `Const` **EntityRepositoryType**: unique symbol = Symbol('EntityRepositoryType')

*Defined in [packages/core/src/typings.ts:21](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L21)*

___

### ObjectBindingPattern

• `Const` **ObjectBindingPattern**: unique symbol = Symbol('ObjectBindingPattern')

*Defined in [packages/core/src/utils/Utils.ts:14](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/utils/Utils.ts#L14)*

___

### PrimaryKeyType

• `Const` **PrimaryKeyType**: unique symbol = Symbol('PrimaryKeyType')

*Defined in [packages/core/src/typings.ts:22](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/typings.ts#L22)*

___

### SCALAR\_TYPES

• `Const` **SCALAR\_TYPES**: string[] = ['string', 'number', 'boolean', 'Date', 'Buffer', 'RegExp']

*Defined in [packages/core/src/enums.ts:65](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/enums.ts#L65)*

___

### assign

• `Const` **assign**: [assign](classes/entityassigner.md#assign) = EntityAssigner.assign

*Defined in [packages/core/src/entity/EntityAssigner.ts:151](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/entity/EntityAssigner.ts#L151)*

___

### entityHelperSymbol

• `Const` **entityHelperSymbol**: unique symbol = Symbol('helper')

*Defined in [packages/core/src/entity/EntityHelper.ts:12](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/entity/EntityHelper.ts#L12)*

___

### equalsFn

• `Const` **equalsFn**: [equals](globals.md#equals) = equals

*Defined in [packages/core/src/utils/Utils.ts:114](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/utils/Utils.ts#L114)*

___

### validator

• `Const` **validator**: [EntityValidator](classes/entityvalidator.md) = new EntityValidator(false)

*Defined in [packages/core/src/entity/EntityAssigner.ts:10](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/entity/EntityAssigner.ts#L10)*

## Functions

### AfterCreate

▸ **AfterCreate**(): (Anonymous function)

*Defined in [packages/core/src/decorators/hooks.ts:20](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/decorators/hooks.ts#L20)*

**Returns:** (Anonymous function)

___

### AfterDelete

▸ **AfterDelete**(): (Anonymous function)

*Defined in [packages/core/src/decorators/hooks.ts:46](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/decorators/hooks.ts#L46)*

Called after deleting entity, but only when providing initialized entity to EM#remove()

**Returns:** (Anonymous function)

___

### AfterUpdate

▸ **AfterUpdate**(): (Anonymous function)

*Defined in [packages/core/src/decorators/hooks.ts:28](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/decorators/hooks.ts#L28)*

**Returns:** (Anonymous function)

___

### BeforeCreate

▸ **BeforeCreate**(): (Anonymous function)

*Defined in [packages/core/src/decorators/hooks.ts:16](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/decorators/hooks.ts#L16)*

**Returns:** (Anonymous function)

___

### BeforeDelete

▸ **BeforeDelete**(): (Anonymous function)

*Defined in [packages/core/src/decorators/hooks.ts:39](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/decorators/hooks.ts#L39)*

Called before deleting entity, but only when providing initialized entity to EM#remove()

**Returns:** (Anonymous function)

___

### BeforeUpdate

▸ **BeforeUpdate**(): (Anonymous function)

*Defined in [packages/core/src/decorators/hooks.ts:24](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/decorators/hooks.ts#L24)*

**Returns:** (Anonymous function)

___

### Embeddable

▸ **Embeddable**(): (Anonymous function)

*Defined in [packages/core/src/decorators/Embeddable.ts:4](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/decorators/Embeddable.ts#L4)*

**Returns:** (Anonymous function)

___

### Embedded

▸ **Embedded**(`options?`: [EmbeddedOptions](globals.md#embeddedoptions) \| () => [AnyEntity](globals.md#anyentity)): (Anonymous function)

*Defined in [packages/core/src/decorators/Embedded.ts:6](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/decorators/Embedded.ts#L6)*

#### Parameters:

Name | Type | Default value |
------ | ------ | ------ |
`options` | [EmbeddedOptions](globals.md#embeddedoptions) \| () => [AnyEntity](globals.md#anyentity) | {} |

**Returns:** (Anonymous function)

___

### Entity

▸ **Entity**(`options?`: [EntityOptions](globals.md#entityoptions)&#60;any>): (Anonymous function)

*Defined in [packages/core/src/decorators/Entity.ts:6](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/decorators/Entity.ts#L6)*

#### Parameters:

Name | Type | Default value |
------ | ------ | ------ |
`options` | [EntityOptions](globals.md#entityoptions)&#60;any> | {} |

**Returns:** (Anonymous function)

___

### Enum

▸ **Enum**(`options?`: [EnumOptions](interfaces/enumoptions.md)&#60;[AnyEntity](globals.md#anyentity)> \| () => [Dictionary](globals.md#dictionary)): (Anonymous function)

*Defined in [packages/core/src/decorators/Enum.ts:7](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/decorators/Enum.ts#L7)*

#### Parameters:

Name | Type | Default value |
------ | ------ | ------ |
`options` | [EnumOptions](interfaces/enumoptions.md)&#60;[AnyEntity](globals.md#anyentity)> \| () => [Dictionary](globals.md#dictionary) | {} |

**Returns:** (Anonymous function)

___

### Filter

▸ **Filter**&#60;T>(`options`: [FilterDef](globals.md#filterdef)&#60;T>): (Anonymous function)

*Defined in [packages/core/src/decorators/Filter.ts:4](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/decorators/Filter.ts#L4)*

#### Type parameters:

Name |
------ |
`T` |

#### Parameters:

Name | Type |
------ | ------ |
`options` | [FilterDef](globals.md#filterdef)&#60;T> |

**Returns:** (Anonymous function)

___

### Formula

▸ **Formula**(`formula`: string \| (alias: string) => string): (Anonymous function)

*Defined in [packages/core/src/decorators/Formula.ts:6](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/decorators/Formula.ts#L6)*

#### Parameters:

Name | Type |
------ | ------ |
`formula` | string \| (alias: string) => string |

**Returns:** (Anonymous function)

___

### Index

▸ **Index**&#60;T>(`options?`: [IndexOptions](interfaces/indexoptions.md)&#60;T>): (Anonymous function)

*Defined in [packages/core/src/decorators/Indexed.ts:20](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/decorators/Indexed.ts#L20)*

#### Type parameters:

Name |
------ |
`T` |

#### Parameters:

Name | Type | Default value |
------ | ------ | ------ |
`options` | [IndexOptions](interfaces/indexoptions.md)&#60;T> | {} |

**Returns:** (Anonymous function)

___

### ManyToMany

▸ **ManyToMany**&#60;T, O>(`entity?`: [ManyToManyOptions](interfaces/manytomanyoptions.md)&#60;T, O> \| string \| () => [EntityName](globals.md#entityname)&#60;T>, `mappedBy?`: string & keyof T \| (e: T) => any, `options?`: Partial&#60;[ManyToManyOptions](interfaces/manytomanyoptions.md)&#60;T, O>>): (Anonymous function)

*Defined in [packages/core/src/decorators/ManyToMany.ts:7](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/decorators/ManyToMany.ts#L7)*

#### Type parameters:

Name |
------ |
`T` |
`O` |

#### Parameters:

Name | Type | Default value |
------ | ------ | ------ |
`entity?` | [ManyToManyOptions](interfaces/manytomanyoptions.md)&#60;T, O> \| string \| () => [EntityName](globals.md#entityname)&#60;T> | - |
`mappedBy?` | string & keyof T \| (e: T) => any | - |
`options` | Partial&#60;[ManyToManyOptions](interfaces/manytomanyoptions.md)&#60;T, O>> | {} |

**Returns:** (Anonymous function)

___

### ManyToOne

▸ **ManyToOne**&#60;T, O>(`entity?`: [ManyToOneOptions](interfaces/manytooneoptions.md)&#60;T, O> \| string \| (e?: any) => [EntityName](globals.md#entityname)&#60;T>, `options?`: Partial&#60;[ManyToOneOptions](interfaces/manytooneoptions.md)&#60;T, O>>): (Anonymous function)

*Defined in [packages/core/src/decorators/ManyToOne.ts:7](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/decorators/ManyToOne.ts#L7)*

#### Type parameters:

Name |
------ |
`T` |
`O` |

#### Parameters:

Name | Type | Default value |
------ | ------ | ------ |
`entity` | [ManyToOneOptions](interfaces/manytooneoptions.md)&#60;T, O> \| string \| (e?: any) => [EntityName](globals.md#entityname)&#60;T> | {} |
`options` | Partial&#60;[ManyToOneOptions](interfaces/manytooneoptions.md)&#60;T, O>> | {} |

**Returns:** (Anonymous function)

___

### OnInit

▸ **OnInit**(): (Anonymous function)

*Defined in [packages/core/src/decorators/hooks.ts:32](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/decorators/hooks.ts#L32)*

**Returns:** (Anonymous function)

___

### OneToMany

▸ **OneToMany**&#60;T, O>(`entity`: string \| (e?: any) => [EntityName](globals.md#entityname)&#60;T>, `mappedBy`: string & keyof T \| (e: T) => any, `options?`: Partial&#60;[OneToManyOptions](globals.md#onetomanyoptions)&#60;T, O>>): function

*Defined in [packages/core/src/decorators/OneToMany.ts:24](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/decorators/OneToMany.ts#L24)*

#### Type parameters:

Name |
------ |
`T` |
`O` |

#### Parameters:

Name | Type |
------ | ------ |
`entity` | string \| (e?: any) => [EntityName](globals.md#entityname)&#60;T> |
`mappedBy` | string & keyof T \| (e: T) => any |
`options?` | Partial&#60;[OneToManyOptions](globals.md#onetomanyoptions)&#60;T, O>> |

**Returns:** function

▸ **OneToMany**&#60;T, O>(`options`: [OneToManyOptions](globals.md#onetomanyoptions)&#60;T, O>): function

*Defined in [packages/core/src/decorators/OneToMany.ts:29](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/decorators/OneToMany.ts#L29)*

#### Type parameters:

Name |
------ |
`T` |
`O` |

#### Parameters:

Name | Type |
------ | ------ |
`options` | [OneToManyOptions](globals.md#onetomanyoptions)&#60;T, O> |

**Returns:** function

___

### OneToOne

▸ **OneToOne**&#60;T, O>(`entity?`: [OneToOneOptions](interfaces/onetooneoptions.md)&#60;T, O> \| string \| (e?: any) => [EntityName](globals.md#entityname)&#60;T>, `mappedBy?`: string & keyof T \| (e: T) => any, `options?`: Partial&#60;[OneToOneOptions](interfaces/onetooneoptions.md)&#60;T, O>>): (Anonymous function)

*Defined in [packages/core/src/decorators/OneToOne.ts:5](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/decorators/OneToOne.ts#L5)*

#### Type parameters:

Name |
------ |
`T` |
`O` |

#### Parameters:

Name | Type | Default value |
------ | ------ | ------ |
`entity?` | [OneToOneOptions](interfaces/onetooneoptions.md)&#60;T, O> \| string \| (e?: any) => [EntityName](globals.md#entityname)&#60;T> | - |
`mappedBy?` | string & keyof T \| (e: T) => any | - |
`options` | Partial&#60;[OneToOneOptions](interfaces/onetooneoptions.md)&#60;T, O>> | {} |

**Returns:** (Anonymous function)

___

### PrimaryKey

▸ **PrimaryKey**&#60;T>(`options?`: [PrimaryKeyOptions](interfaces/primarykeyoptions.md)&#60;T>): (Anonymous function)

*Defined in [packages/core/src/decorators/PrimaryKey.ts:19](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/decorators/PrimaryKey.ts#L19)*

#### Type parameters:

Name |
------ |
`T` |

#### Parameters:

Name | Type | Default value |
------ | ------ | ------ |
`options` | [PrimaryKeyOptions](interfaces/primarykeyoptions.md)&#60;T> | {} |

**Returns:** (Anonymous function)

___

### Property

▸ **Property**&#60;T>(`options?`: [PropertyOptions](globals.md#propertyoptions)&#60;T>): (Anonymous function)

*Defined in [packages/core/src/decorators/Property.ts:7](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/decorators/Property.ts#L7)*

#### Type parameters:

Name |
------ |
`T` |

#### Parameters:

Name | Type | Default value |
------ | ------ | ------ |
`options` | [PropertyOptions](globals.md#propertyoptions)&#60;T> | {} |

**Returns:** (Anonymous function)

___

### Repository

▸ **Repository**&#60;T>(`entity`: [EntityClass](globals.md#entityclass)&#60;T>): (Anonymous function)

*Defined in [packages/core/src/decorators/Repository.ts:5](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/decorators/Repository.ts#L5)*

#### Type parameters:

Name | Type |
------ | ------ |
`T` | [AnyEntity](globals.md#anyentity) |

#### Parameters:

Name | Type |
------ | ------ |
`entity` | [EntityClass](globals.md#entityclass)&#60;T> |

**Returns:** (Anonymous function)

___

### SerializedPrimaryKey

▸ **SerializedPrimaryKey**&#60;T>(`options?`: [SerializedPrimaryKeyOptions](interfaces/serializedprimarykeyoptions.md)&#60;T>): (Anonymous function)

*Defined in [packages/core/src/decorators/PrimaryKey.ts:23](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/decorators/PrimaryKey.ts#L23)*

#### Type parameters:

Name |
------ |
`T` |

#### Parameters:

Name | Type | Default value |
------ | ------ | ------ |
`options` | [SerializedPrimaryKeyOptions](interfaces/serializedprimarykeyoptions.md)&#60;T> | {} |

**Returns:** (Anonymous function)

___

### Subscriber

▸ **Subscriber**(): (Anonymous function)

*Defined in [packages/core/src/decorators/Subscriber.ts:5](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/decorators/Subscriber.ts#L5)*

**Returns:** (Anonymous function)

___

### Unique

▸ **Unique**&#60;T>(`options?`: [UniqueOptions](interfaces/uniqueoptions.md)&#60;T>): (Anonymous function)

*Defined in [packages/core/src/decorators/Indexed.ts:24](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/decorators/Indexed.ts#L24)*

#### Type parameters:

Name |
------ |
`T` |

#### Parameters:

Name | Type | Default value |
------ | ------ | ------ |
`options` | [UniqueOptions](interfaces/uniqueoptions.md)&#60;T> | {} |

**Returns:** (Anonymous function)

___

### compareArrays

▸ **compareArrays**(`a`: any[], `b`: any[]): boolean

*Defined in [packages/core/src/utils/Utils.ts:58](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/utils/Utils.ts#L58)*

#### Parameters:

Name | Type |
------ | ------ |
`a` | any[] |
`b` | any[] |

**Returns:** boolean

___

### compareBuffers

▸ **compareBuffers**(`a`: Buffer, `b`: Buffer): boolean

*Defined in [packages/core/src/utils/Utils.ts:75](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/utils/Utils.ts#L75)*

#### Parameters:

Name | Type |
------ | ------ |
`a` | Buffer |
`b` | Buffer |

**Returns:** boolean

___

### compareObjects

▸ **compareObjects**(`a`: any, `b`: any): boolean

*Defined in [packages/core/src/utils/Utils.ts:16](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/utils/Utils.ts#L16)*

#### Parameters:

Name | Type |
------ | ------ |
`a` | any |
`b` | any |

**Returns:** boolean

___

### createDecorator

▸ **createDecorator**&#60;T>(`options`: [PrimaryKeyOptions](interfaces/primarykeyoptions.md)&#60;T> \| [SerializedPrimaryKeyOptions](interfaces/serializedprimarykeyoptions.md)&#60;T>, `serialized`: boolean): (Anonymous function)

*Defined in [packages/core/src/decorators/PrimaryKey.ts:7](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/decorators/PrimaryKey.ts#L7)*

#### Type parameters:

Name |
------ |
`T` |

#### Parameters:

Name | Type |
------ | ------ |
`options` | [PrimaryKeyOptions](interfaces/primarykeyoptions.md)&#60;T> \| [SerializedPrimaryKeyOptions](interfaces/serializedprimarykeyoptions.md)&#60;T> |
`serialized` | boolean |

**Returns:** (Anonymous function)

___

### createOneToDecorator

▸ **createOneToDecorator**&#60;T, O>(`entity`: [OneToManyOptions](globals.md#onetomanyoptions)&#60;T, O> \| string \| (e?: any) => [EntityName](globals.md#entityname)&#60;T>, `mappedBy`: string & keyof T \| (e: T) => any \| undefined, `options`: Partial&#60;[OneToManyOptions](globals.md#onetomanyoptions)&#60;T, O>>, `reference`: [ReferenceType](enums/referencetype.md)): (Anonymous function)

*Defined in [packages/core/src/decorators/OneToMany.ts:7](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/decorators/OneToMany.ts#L7)*

#### Type parameters:

Name |
------ |
`T` |
`O` |

#### Parameters:

Name | Type |
------ | ------ |
`entity` | [OneToManyOptions](globals.md#onetomanyoptions)&#60;T, O> \| string \| (e?: any) => [EntityName](globals.md#entityname)&#60;T> |
`mappedBy` | string & keyof T \| (e: T) => any \| undefined |
`options` | Partial&#60;[OneToManyOptions](globals.md#onetomanyoptions)&#60;T, O>> |
`reference` | [ReferenceType](enums/referencetype.md) |

**Returns:** (Anonymous function)

___

### equals

▸ **equals**(`a`: any, `b`: any): boolean

*Defined in [packages/core/src/utils/Utils.ts:94](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/utils/Utils.ts#L94)*

Checks if arguments are deeply (but not strictly) equal.

#### Parameters:

Name | Type |
------ | ------ |
`a` | any |
`b` | any |

**Returns:** boolean

___

### expr

▸ `Const`**expr**(`sql`: string): string

*Defined in [packages/core/src/utils/QueryHelper.ts:220](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/utils/QueryHelper.ts#L220)*

#### Parameters:

Name | Type |
------ | ------ |
`sql` | string |

**Returns:** string

___

### hook

▸ **hook**(`type`: [EventType](enums/eventtype.md)): (Anonymous function)

*Defined in [packages/core/src/decorators/hooks.ts:4](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/decorators/hooks.ts#L4)*

#### Parameters:

Name | Type |
------ | ------ |
`type` | [EventType](enums/eventtype.md) |

**Returns:** (Anonymous function)

___

### mapHydrator

▸ **mapHydrator**&#60;T>(`items`: T[] \| undefined, `hydrate`: (i: string) => T): function

*Defined in [packages/core/src/types/EnumArrayType.ts:6](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/types/EnumArrayType.ts#L6)*

#### Type parameters:

Name |
------ |
`T` |

#### Parameters:

Name | Type |
------ | ------ |
`items` | T[] \| undefined |
`hydrate` | (i: string) => T |

**Returns:** function

___

### wrap

▸ **wrap**&#60;T, PK>(`entity`: T, `preferHelper`: true): [IWrappedEntityInternal](interfaces/iwrappedentityinternal.md)&#60;T, PK>

*Defined in [packages/core/src/entity/wrap.ts:6](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/entity/wrap.ts#L6)*

returns WrappedEntity instance associated with this entity. This includes all the internal properties like `__meta` or `__em`.

#### Type parameters:

Name | Type |
------ | ------ |
`T` | - |
`PK` | keyof T |

#### Parameters:

Name | Type |
------ | ------ |
`entity` | T |
`preferHelper` | true |

**Returns:** [IWrappedEntityInternal](interfaces/iwrappedentityinternal.md)&#60;T, PK>

▸ **wrap**&#60;T, PK>(`entity`: T, `preferHelper?`: false): [IWrappedEntity](interfaces/iwrappedentity.md)&#60;T, PK>

*Defined in [packages/core/src/entity/wrap.ts:11](https://github.com/mikro-orm/mikro-orm/blob/d945b8a11/packages/core/src/entity/wrap.ts#L11)*

wraps entity type with WrappedEntity internal properties and helpers like init/isInitialized/populated/toJSON

#### Type parameters:

Name | Type |
------ | ------ |
`T` | - |
`PK` | keyof T |

#### Parameters:

Name | Type |
------ | ------ |
`entity` | T |
`preferHelper?` | false |

**Returns:** [IWrappedEntity](interfaces/iwrappedentity.md)&#60;T, PK>
