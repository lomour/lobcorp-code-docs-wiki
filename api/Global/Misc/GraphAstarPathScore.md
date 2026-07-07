---
title: GraphAstarPathScore
description: 
published: true
date: 2026-02-20T22:04:18.824Z
tags: 
editor: markdown
dateCreated: 2026-01-15T04:13:20.024Z
---

# Class GraphAstar.PathScore
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class GraphAstar.PathScore : IComparable<GraphAstar.PathScore>
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → GraphAstar.PathScore

## Implements
[IComparable<GraphAstar.PathScore>](https://learn.microsoft.com/dotnet/api/system.icomparable-1)

## Constructors
### PathScore()
```csharp
public PathScore()
```

### PathScore(MapNode)
```csharp
public PathScore(MapNode node)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |

## Fields
### cost
```csharp
public float cost
```

#### Field Value
**Type:** System.Single

### h
```csharp
public float h
```

#### Field Value
**Type:** System.Single

### node
```csharp
public MapNode node
```

#### Field Value
**Type:** Global.MapNode

## Methods
### CompareTo(PathScore)
```csharp
public int CompareTo(GraphAstar.PathScore other)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `other` | `Global.GraphAstar.PathScore` |  |

#### Returns
**Type:** System.Int32

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)



