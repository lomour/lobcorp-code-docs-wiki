---
title: ISkeletonAnimation
description: 
published: true
date: 2026-02-20T22:48:43.082Z
tags: 
editor: markdown
dateCreated: 2026-01-15T06:02:04.620Z
---

# Interface ISkeletonAnimation
**Namespace:** [Spine](/api/Spine) . [Unity](/api/Spine/Unity)
**Assembly:** Assembly-CSharp.dll

```csharp
public interface ISkeletonAnimation
```

## Properties
### Skeleton
```csharp
Skeleton Skeleton { get; }
```

#### Property Value
**Type:** Spine.Skeleton

## Methods
### LateUpdate()
```csharp
void LateUpdate()
```

## Events
### UpdateComplete
```csharp
event UpdateBonesDelegate UpdateComplete
```

#### Returns
**Type:** Spine.Unity.UpdateBonesDelegate

### UpdateLocal
```csharp
event UpdateBonesDelegate UpdateLocal
```

#### Returns
**Type:** Spine.Unity.UpdateBonesDelegate

### UpdateWorld
```csharp
event UpdateBonesDelegate UpdateWorld
```

#### Returns
**Type:** Spine.Unity.UpdateBonesDelegate



