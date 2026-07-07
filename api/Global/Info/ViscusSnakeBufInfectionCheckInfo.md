---
title: ViscusSnakeBufInfectionCheckInfo
description: 
published: true
date: 2026-02-20T21:51:44.823Z
tags: 
editor: markdown
dateCreated: 2026-01-15T03:51:30.003Z
---

# Class ViscusSnakeBuf.InfectionCheckInfo
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ViscusSnakeBuf.InfectionCheckInfo
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → ViscusSnakeBuf.InfectionCheckInfo

## Constructors
### InfectionCheckInfo(WorkerModel)
```csharp
public InfectionCheckInfo(WorkerModel worker)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

## Fields
### _isExpired
```csharp
private bool _isExpired
```

#### Field Value
**Type:** System.Boolean

### timer
```csharp
private Timer timer
```

#### Field Value
**Type:** Global.Timer

### worker
```csharp
public WorkerModel worker
```

#### Field Value
**Type:** Global.WorkerModel

## Properties
### CheckTime
```csharp
private float CheckTime { get; }
```

#### Property Value
**Type:** System.Single

### IsExpired
```csharp
public bool IsExpired { get; }
```

#### Property Value
**Type:** System.Boolean

## Methods
### FixedUpdate()
```csharp
public void FixedUpdate()
```

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)



