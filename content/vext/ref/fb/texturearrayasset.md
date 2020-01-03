---
title: TextureArrayAsset
---
### Base Classes

[TextureAsset](TextureAsset)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                  | Description                                                                                                               |
| ---------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------- |
| TextureArrayAsset()                                                          | Create a new instance of this container type.                                                                             |
| TextureArrayAsset(TextureArrayAsset other)                                   | Create a reference copy of an instance of the same type.                                                                  |
| TextureArrayAsset([TextureAsset](TextureAsset) other)                        | Upcast an instance of type [TextureAsset](TextureAsset) to [TextureArrayAsset](TextureArrayAsset).                        |
| TextureArrayAsset([TextureBaseAsset](TextureBaseAsset) other)                | Upcast an instance of type [TextureBaseAsset](TextureBaseAsset) to [TextureArrayAsset](TextureArrayAsset).                |
| TextureArrayAsset([Asset](Asset) other)                                      | Upcast an instance of type [Asset](Asset) to [TextureArrayAsset](TextureArrayAsset).                                      |
| TextureArrayAsset([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [TextureArrayAsset](TextureArrayAsset). |

## Methods

| Type                                   | Name            | Parameters                                     |
| -------------------------------------- | --------------- | ---------------------------------------------- |
| [TextureArrayAsset](TextureArrayAsset) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [TextureArrayAsset](TextureArrayAsset) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |