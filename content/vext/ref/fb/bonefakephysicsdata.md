---
title: BoneFakePhysicsData
---
### Base Classes

[DataContainer](/vext/ref/shared/class/datacontainer)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                    | Description                                                                                                                   |
| ------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------- |
| BoneFakePhysicsData()                                                          | Create a new instance of this container type.                                                                                 |
| BoneFakePhysicsData(BoneFakePhysicsData other)                                 | Create a reference copy of an instance of the same type.                                                                      |
| BoneFakePhysicsData([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [BoneFakePhysicsData](BoneFakePhysicsData). |

## Properties

| Name        | Type                               | Description |
| ----------- | ---------------------------------- | ----------- |
| fakePhysics | [FakePhysicsData](FakePhysicsData) |             |
| boneName    | string                             |             |
| boneId      | number                             |             |

## Methods

| Type                                       | Name            | Parameters                                     |
| ------------------------------------------ | --------------- | ---------------------------------------------- |
| [BoneFakePhysicsData](BoneFakePhysicsData) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [BoneFakePhysicsData](BoneFakePhysicsData) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |