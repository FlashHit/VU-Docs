---
title: MedicBagHealingSphereWeaponData
---
### Base Classes

[WeaponData](WeaponData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                                | Description                                                                                                                                           |
| ------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| MedicBagHealingSphereWeaponData()                                                          | Create a new instance of this container type.                                                                                                         |
| MedicBagHealingSphereWeaponData(MedicBagHealingSphereWeaponData other)                     | Create a reference copy of an instance of the same type.                                                                                              |
| MedicBagHealingSphereWeaponData([WeaponData](WeaponData) other)                            | Upcast an instance of type [WeaponData](WeaponData) to [MedicBagHealingSphereWeaponData](MedicBagHealingSphereWeaponData).                            |
| MedicBagHealingSphereWeaponData([ToolData](ToolData) other)                                | Upcast an instance of type [ToolData](ToolData) to [MedicBagHealingSphereWeaponData](MedicBagHealingSphereWeaponData).                                |
| MedicBagHealingSphereWeaponData([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [MedicBagHealingSphereWeaponData](MedicBagHealingSphereWeaponData). |

## Properties

| Name                    | Type                                   | Description |
| ----------------------- | -------------------------------------- | ----------- |
| healer                  | [HealingSphereData](HealingSphereData) |             |
| healthPointsRefillSpeed | number                                 |             |
| healthPointsPerBag      | number                                 |             |

## Methods

| Type                                                               | Name            | Parameters                                     |
| ------------------------------------------------------------------ | --------------- | ---------------------------------------------- |
| [MedicBagHealingSphereWeaponData](MedicBagHealingSphereWeaponData) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [MedicBagHealingSphereWeaponData](MedicBagHealingSphereWeaponData) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |