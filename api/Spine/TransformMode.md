---
title: TransformMode
description: 
published: true
date: 2026-02-23T23:21:28.946Z
tags: 
editor: markdown
dateCreated: 2026-01-15T06:01:28.017Z
---

# Enum TransformMode
**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

[`[System.FlagsAttribute]`](#)

```csharp
[Flags]
public enum TransformMode
```

## Extension Methods
- [InheritsRotation(TransformMode)](Spine.SkeletonExtensions.html#Spine_SkeletonExtensions_InheritsRotation_Spine_TransformMode_)
- [InheritsScale(TransformMode)](Spine.SkeletonExtensions.html#Spine_SkeletonExtensions_InheritsScale_Spine_TransformMode_)

## Fields
### Normal
```csharp
Normal = 0
```

#### Field Value
**Type:** Spine.TransformMode

### NoRotationOrReflection
```csharp
NoRotationOrReflection = 1
```

#### Field Value
**Type:** Spine.TransformMode

### NoScale
```csharp
NoScale = 2
```

#### Field Value
**Type:** Spine.TransformMode

### NoScaleOrReflection
```csharp
NoScaleOrReflection = 6
```

#### Field Value
**Type:** Spine.TransformMode

### OnlyTranslation
```csharp
OnlyTranslation = NoRotationOrReflection | NoScaleOrReflection
```

#### Field Value
**Type:** Spine.TransformMode




