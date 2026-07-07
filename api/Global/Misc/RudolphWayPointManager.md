---
title: RudolphWayPointManager
description: 
published: true
date: 2026-02-20T22:12:35.623Z
tags: 
editor: markdown
dateCreated: 2026-01-15T04:27:45.427Z
---

# Class Rudolph.WayPointManager
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Rudolph.WayPointManager
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → Rudolph.WayPointManager

## Constructors
### WayPointManager(Rudolph)
```csharp
public WayPointManager(Rudolph script)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `script` | `Global.Rudolph` |  |

## Fields
### script
```csharp
private Rudolph script
```

#### Field Value
**Type:** Global.Rudolph

### wayPoints
```csharp
private Queue<MapNode> wayPoints
```

#### Field Value
**Type:** System.Collections.Generic.Queue{MapNode}

## Methods
### Gen()
```csharp
private void Gen()
```

### Init()
```csharp
public void Init()
```

### NextWayPoint()
```csharp
public MapNode NextWayPoint()
```

#### Returns
**Type:** Global.MapNode

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)



