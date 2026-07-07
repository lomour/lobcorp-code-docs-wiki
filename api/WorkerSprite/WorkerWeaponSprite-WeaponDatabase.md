---
title: WorkerWeaponSprite-WeaponDatabase
description: 
published: true
date: 2026-03-03T08:31:53.349Z
tags: 
editor: markdown
dateCreated: 2026-01-15T06:21:25.050Z
---

# Class WorkerWeaponSprite.WeaponDatabase
**Namespace:** [WorkerSprite](/api/WorkerSprite)
**Assembly:** Assembly-CSharp.dll

```csharp
public class WorkerWeaponSprite.WeaponDatabase
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → WorkerWeaponSprite.WeaponDatabase

## Constructors
### WeaponDatabase()
```csharp
public WeaponDatabase()
```

## Fields
### data
```csharp
private Dictionary<string, Sprite> data
```

#### Field Value
**Type:** System.Collections.Generic.Dictionary{System.String,UnityEngine.Sprite}

## Methods
### Add(SpriteResourceLoadData)
```csharp
public void Add(SpriteResourceLoadData s)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `s` | `WorkerSprite.SpriteResourceLoadData` |  |

### GetSprite(string, out Sprite)
```csharp
public bool GetSprite(string name, out Sprite sprite)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |
| `sprite` | `UnityEngine.Sprite` |  |

#### Returns
**Type:** System.Boolean

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)



