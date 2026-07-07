---
title: PolygonSet
description: 
published: true
date: 2026-02-20T22:44:55.751Z
tags: 
editor: markdown
dateCreated: 2026-01-15T05:42:49.864Z
---

# Class PolygonSet
**Namespace:** [Poly2Tri](/api/Poly2Tri)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PolygonSet
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → PolygonSet

## Constructors
### PolygonSet()
```csharp
public PolygonSet()
```

### PolygonSet(Polygon)
```csharp
public PolygonSet(Polygon poly)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `poly` | `Poly2Tri.Polygon` |  |

## Fields
### _polygons
```csharp
protected List<Polygon> _polygons
```

#### Field Value
**Type:** System.Collections.Generic.List{Poly2Tri.Polygon}

## Properties
### Polygons
```csharp
public IEnumerable<Polygon> Polygons { get; }
```

#### Property Value
**Type:** System.Collections.Generic.IEnumerable{Poly2Tri.Polygon}

## Methods
### Add(Polygon)
```csharp
public void Add(Polygon p)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `p` | `Poly2Tri.Polygon` |  |

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)



