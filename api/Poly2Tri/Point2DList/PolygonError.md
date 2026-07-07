---
title: PolygonError
description: 
published: true
date: 2026-02-23T23:20:53.538Z
tags: 
editor: markdown
dateCreated: 2026-01-15T05:42:19.717Z
---

# Enum Point2DList.PolygonError
**Namespace:** [Poly2Tri](/api/Poly2Tri)
**Assembly:** Assembly-CSharp.dll

[`[System.FlagsAttribute]`](#)

```csharp
[Flags]
public enum Point2DList.PolygonError : uint
```

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | |
| NotEnoughVertices | 1 | |
| NotConvex | 2 | |
| NotSimple | 4 | |
| AreaTooSmall | 8 | |
| SidesTooCloseToParallel | 16 | |
| TooThin | 32 | |
| Degenerate | 64 | |
| Unknown | 1073741824 | |

