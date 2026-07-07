---
title: Timeline
description: 
published: true
date: 2026-02-20T22:48:12.487Z
tags: 
editor: markdown
dateCreated: 2026-01-15T06:01:07.775Z
---

# Interface Timeline
**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public interface Timeline
```

## Properties
### PropertyId
```csharp
int PropertyId { get; }
```

#### Property Value
**Type:** System.Int32

## Methods
### Apply(Skeleton, float, float, ExposedList<Event>, float, MixPose, MixDirection)
```csharp
void Apply(Skeleton skeleton, float lastTime, float time, ExposedList<Event> events, float alpha, MixPose pose, MixDirection direction)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `skeleton` | `Spine.Skeleton` |  |
| `lastTime` | `System.Single` |  |
| `time` | `System.Single` |  |
| `events` | `Spine.ExposedList{Spine.Event}` |  |
| `alpha` | `System.Single` |  |
| `pose` | `Spine.MixPose` |  |
| `direction` | `Spine.MixDirection` |  |



