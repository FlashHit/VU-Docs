---
title: PhysicsEntity
---

Inherits from [GameEntity](/vext/ref/server/type/gameentity)

## Summary

### Constructors

|  |
| --- |
| **[PhysicsEntity](#constructor-0)**(other: [EntityBusPeer](/vext/ref/shared/type/entitybuspeer)) |
| **[PhysicsEntity](#constructor-1)**(other: [Entity](/vext/ref/shared/type/entity)) |
| **[PhysicsEntity](#constructor-2)**(other: [SpatialEntity](/vext/ref/shared/type/spatialentity)) |
| **[PhysicsEntity](#constructor-3)**(other: [GameEntity](/vext/ref/server/type/gameentity)) |

### Properties

| Name | Type |
| ---- | ---- |
| {{< prop "internalHealth" >}} | float |
| {{< prop "velocity" >}} | [Vec3](/vext/ref/shared/type/vec3) |
| {{< prop "defaultMaterial" true >}} | [DataContainer](/vext/ref/shared/type/datacontainer) \| nil |
| {{< prop "belongsInPhysicsWorld" true >}} | bool |
| {{< prop "isPredestructible" true >}} | bool |
| {{< prop "physicsEntityBase" true >}} | [PhysicsEntityBase](/vext/ref/shared/type/physicsentitybase) \| nil |

### Methods

| Method | Returns |
| ------ | ------- |
| **[GetMaterial](#getmaterial)**(position: [Vec3](/vext/ref/shared/type/vec3)) | [DataContainer](/vext/ref/shared/type/datacontainer) \| nil |
| **[SetActiveHealthState](#setactivehealthstate)**(state: int) | void |
| **[ApplyDamage](#applydamage)**(damageInfo: [DamageInfo](/vext/ref/server/type/damageinfo)) | void |
| **[ApplyImpulse](#applyimpulse)**(impulseData: [ImpulseData](/vext/ref/shared/type/impulsedata)) | void |
| **[RegisterCollisionCallback](#registercollisioncallback)**(callback: callable) | int |
| **[RegisterCollisionCallback](#registercollisioncallback-1)**(context: any, callback: callable) | int |
| **[UnregisterCollisionCallback](#unregistercollisioncallback)**(handle: int) | void |
| **[RegisterDamageCallback](#registerdamagecallback)**(callback: callable) | int |
| **[RegisterDamageCallback](#registerdamagecallback-1)**(context: any, callback: callable) | int |
| **[UnregisterDamageCallback](#unregisterdamagecallback)**(handle: int) | void |
| **[RegisterInteractCallback](#registerinteractcallback)**(callback: callable) | int |
| **[RegisterInteractCallback](#registerinteractcallback-1)**(context: any, callback: callable) | int |
| **[UnregisterInteractCallback](#unregisterinteractcallback)**(handle: int) | void |
| **[RegisterImpulseCallback](#registerimpulsecallback)**(callback: callable) | int |
| **[RegisterImpulseCallback](#registerimpulsecallback-1)**(context: any, callback: callable) | int |
| **[UnregisterImpulseCallback](#unregisterimpulsecallback)**(handle: int) | void |

## Constructors

### PhysicsEntity {#constructor-0}

> **PhysicsEntity**(other: [EntityBusPeer](/vext/ref/shared/type/entitybuspeer))

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [EntityBusPeer](/vext/ref/shared/type/entitybuspeer) |  |

### PhysicsEntity {#constructor-1}

> **PhysicsEntity**(other: [Entity](/vext/ref/shared/type/entity))

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [Entity](/vext/ref/shared/type/entity) |  |

### PhysicsEntity {#constructor-2}

> **PhysicsEntity**(other: [SpatialEntity](/vext/ref/shared/type/spatialentity))

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [SpatialEntity](/vext/ref/shared/type/spatialentity) |  |

### PhysicsEntity {#constructor-3}

> **PhysicsEntity**(other: [GameEntity](/vext/ref/server/type/gameentity))

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [GameEntity](/vext/ref/server/type/gameentity) |  |

## Properties

### {{% prop-heading "internalHealth" %}}

> **float**

### {{% prop-heading "velocity" %}}

> **[Vec3](/vext/ref/shared/type/vec3)**

### {{% prop-heading "defaultMaterial" true %}}

> **[DataContainer](/vext/ref/shared/type/datacontainer)** \| **nil**

### {{% prop-heading "belongsInPhysicsWorld" true %}}

> **bool**

### {{% prop-heading "isPredestructible" true %}}

> **bool**

### {{% prop-heading "physicsEntityBase" true %}}

> **[PhysicsEntityBase](/vext/ref/shared/type/physicsentitybase)** \| **nil**

## Methods

### GetMaterial {#getmaterial}

> **GetMaterial**(position: [Vec3](/vext/ref/shared/type/vec3)): [DataContainer](/vext/ref/shared/type/datacontainer) \| nil

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **position** | [Vec3](/vext/ref/shared/type/vec3) |  |

#### Returns

| Type | Description |
| ---- | ----------- |
| **[DataContainer](/vext/ref/shared/type/datacontainer)** \| **nil** |  |

### SetActiveHealthState {#setactivehealthstate}

> **SetActiveHealthState**(state: int)

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **state** | int |  |

### ApplyDamage {#applydamage}

> **ApplyDamage**(damageInfo: [DamageInfo](/vext/ref/server/type/damageinfo))

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **damageInfo** | [DamageInfo](/vext/ref/server/type/damageinfo) |  |

### ApplyImpulse {#applyimpulse}

> **ApplyImpulse**(impulseData: [ImpulseData](/vext/ref/shared/type/impulsedata))

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **impulseData** | [ImpulseData](/vext/ref/shared/type/impulsedata) |  |

### RegisterCollisionCallback {#registercollisioncallback}

> **RegisterCollisionCallback**(callback: callable): int

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **callback** | callable | A callback in the form `function(entity: Entity, info: CollisionInfo): bool`. |

#### Returns

| Type | Description |
| ---- | ----------- |
| **int** |  |

### RegisterCollisionCallback {#registercollisioncallback-1}

> **RegisterCollisionCallback**(context: any, callback: callable): int

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **context** | any | A context value to pass to the callback. |
| **callback** | callable | A callback in the form `function(context: any, entity: Entity, info: CollisionInfo): bool`. |

#### Returns

| Type | Description |
| ---- | ----------- |
| **int** |  |

### UnregisterCollisionCallback {#unregistercollisioncallback}

> **UnregisterCollisionCallback**(handle: int)

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **handle** | int |  |

### RegisterDamageCallback {#registerdamagecallback}

> **RegisterDamageCallback**(callback: callable): int

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **callback** | callable | A callback in the form `function(entity: Entity, damageInfo: DamageInfo, damageGiverInfo: DamageGiverInfo | nil): bool`. |

#### Returns

| Type | Description |
| ---- | ----------- |
| **int** |  |

### RegisterDamageCallback {#registerdamagecallback-1}

> **RegisterDamageCallback**(context: any, callback: callable): int

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **context** | any | A context value to pass to the callback. |
| **callback** | callable | A callback in the form `function(context: any, entity: Entity, damageInfo: DamageInfo, damageGiverInfo: DamageGiverInfo | nil): bool`. |

#### Returns

| Type | Description |
| ---- | ----------- |
| **int** |  |

### UnregisterDamageCallback {#unregisterdamagecallback}

> **UnregisterDamageCallback**(handle: int)

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **handle** | int |  |

### RegisterInteractCallback {#registerinteractcallback}

> **RegisterInteractCallback**(callback: callable): int

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **callback** | callable | A callback in the form `function(entity: Entity, soldier: SoldierEntity | nil): bool`. |

#### Returns

| Type | Description |
| ---- | ----------- |
| **int** |  |

### RegisterInteractCallback {#registerinteractcallback-1}

> **RegisterInteractCallback**(context: any, callback: callable): int

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **context** | any | A context value to pass to the callback. |
| **callback** | callable | A callback in the form `function(context: any, entity: Entity, soldier: SoldierEntity | nil): bool`. |

#### Returns

| Type | Description |
| ---- | ----------- |
| **int** |  |

### UnregisterInteractCallback {#unregisterinteractcallback}

> **UnregisterInteractCallback**(handle: int)

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **handle** | int |  |

### RegisterImpulseCallback {#registerimpulsecallback}

> **RegisterImpulseCallback**(callback: callable): int

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **callback** | callable | A callback in the form `function(entity: Entity, impulseData: ImpulseData | nil): bool`. |

#### Returns

| Type | Description |
| ---- | ----------- |
| **int** |  |

### RegisterImpulseCallback {#registerimpulsecallback-1}

> **RegisterImpulseCallback**(context: any, callback: callable): int

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **context** | any | A context value to pass to the callback. |
| **callback** | callable | A callback in the form `function(context: any, entity: Entity, impulseData: ImpulseData | nil): bool`. |

#### Returns

| Type | Description |
| ---- | ----------- |
| **int** |  |

### UnregisterImpulseCallback {#unregisterimpulsecallback}

> **UnregisterImpulseCallback**(handle: int)

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **handle** | int |  |

