---
title: PickupSettingsData
---

## Summary

### Constructors

|  |
| --- |
| **[PickupSettingsData](#constructor-0)**() |
| **[PickupSettingsData](#constructor-1)**(guid: [Guid](/vext/ref/shared/type/guid)) |

### Properties

| Name | Type |
| ---- | ---- |
| {{< prop "meshRenderOffset" >}} | [Vec3](/vext/ref/shared/type/vec3) |
| {{< prop "meshRenderRotation" >}} | [Vec3](/vext/ref/shared/type/vec3) |

### Methods

| Method | Returns |
| ------ | ------- |
| **[Clone](#clone)**() | [PickupSettingsData](/vext/ref/fb/pickupsettingsdata) |

### Static members

| Name | Type |
| ---- | ---- |
| {{< static "PickupSettingsData" "typeInfo" >}} | [TypeInformation](/vext/ref/shared/type/typeinformation) |

## Constructors

### PickupSettingsData {#constructor-0}

> **PickupSettingsData**()

Creates a new [PickupSettingsData](/vext/ref/fb/pickupsettingsdata) frostbite instance.

### PickupSettingsData {#constructor-1}

> **PickupSettingsData**(guid: [Guid](/vext/ref/shared/type/guid))

Creates a new [PickupSettingsData](/vext/ref/fb/pickupsettingsdata) frostbite instance and assigns it the provided [Guid](/vext/ref/shared/type/guid).

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **guid** | [Guid](/vext/ref/shared/type/guid) | The [Guid](/vext/ref/shared/type/guid) to assign to the newly created instance. |

## Properties

### {{% prop-heading "meshRenderOffset" %}}

> **[Vec3](/vext/ref/shared/type/vec3)**

### {{% prop-heading "meshRenderRotation" %}}

> **[Vec3](/vext/ref/shared/type/vec3)**

## Methods

### Clone {#clone}

> **Clone**(): [PickupSettingsData](/vext/ref/fb/pickupsettingsdata)

Creates a shallow-copy clone of this structure, which is essentially the equivalent of creating a new structure of the same type and assigning the values of this structure to all of its properties. Any properties that contain structure types (eg. [Vec3](/vext/ref/shared/type/vec3)) will be cloned when assigning, while properties that contain instance types (eg. [DataContainer](/vext/ref/shared/type/datacontainer)) will be referencing the same instance.

#### Returns

| Type | Description |
| ---- | ----------- |
| **[PickupSettingsData](/vext/ref/fb/pickupsettingsdata)** | The newly created structure. |

## Static members

### {{% static-heading "typeInfo" %}}

> **[TypeInformation](/vext/ref/shared/type/typeinformation)**

The type information for the [PickupSettingsData](/vext/ref/fb/pickupsettingsdata) type.

