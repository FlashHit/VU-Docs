---
title: PartInfoData
---
## Description

A structure type representing a Frostbite data type.

## Constructors

| Constructor                      | Description                                              |
| -------------------------------- | -------------------------------------------------------- |
| PartInfoData()                   | Create a new instance of this structure type.            |
| PartInfoData(PartInfoData other) | Create a reference copy of a structure of the same type. |

## Properties

| Name        | Type                                                  | Description |
| ----------- | ----------------------------------------------------- | ----------- |
| aabb        | [AxisAlignedBox](/vext/ref/shared/class/AxisAlignedBox) |             |
| translation | [Vec3](/vext/ref/shared/class/Vec3)                     |             |

## Methods

| Type                         | Name            | Parameters |
| ---------------------------- | --------------- | ---------- |
| [PartInfoData](PartInfoData) | [Clone](#clone) |            |

### Clone

> [PartInfoData](PartInfoData) **Clone**()

Creates a shallow-copy clone of the structure. Works similarly to [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone).