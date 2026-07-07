---
title: FactionTypeInfo
description: 
published: true
date: 2026-07-07T17:10:11.968Z
tags: 
editor: markdown
dateCreated: 2026-01-06T03:59:25.767Z
---

# Class FactionTypeInfo
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class FactionTypeInfo
```
> This section may have incomplete or incorrect information.
{.is-warning}

Contains a layer of units which are considered in the same group for targetting, e.g., workers, or idle creatures, or panicked workers.

Contains a list of factions which are considered hostile.




## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → FactionTypeInfo

## Constructors
### FactionTypeInfo()
```csharp
public FactionTypeInfo()
```

## Fields
### code
```csharp
public string code
```


#### Field Value
**Type:** System.String

### except
```csharp
public FactionTypeInfo.ExceptType except
```

#### Field Value
**Type:** Global.FactionTypeInfo.ExceptType

### lib
```csharp
public Dictionary<string, FactionActionType> lib
```


#### Field Value
**Type:** System.Collections.Generic.Dictionary{System.String,FactionActionType}

### name
```csharp
public string name
```


#### Field Value
**Type:** System.String

### type
```csharp
public string type
```


#### Field Value
**Type:** System.String

## Methods
### Check(UnitModel)
```csharp
public FactionActionType Check(UnitModel unit)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.UnitModel` |  |

#### Returns
**Type:** Global.FactionActionType

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)



