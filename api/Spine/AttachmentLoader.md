---
title: AttachmentLoader
description: 
published: true
date: 2026-02-20T22:46:15.385Z
tags: 
editor: markdown
dateCreated: 2026-01-15T05:57:33.163Z
---

# Interface AttachmentLoader
**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public interface AttachmentLoader
```

## Methods
### NewBoundingBoxAttachment(Skin, string)
```csharp
BoundingBoxAttachment NewBoundingBoxAttachment(Skin skin, string name)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `skin` | `Spine.Skin` |  |
| `name` | `System.String` |  |

#### Returns
**Type:** Spine.BoundingBoxAttachment

### NewClippingAttachment(Skin, string)
```csharp
ClippingAttachment NewClippingAttachment(Skin skin, string name)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `skin` | `Spine.Skin` |  |
| `name` | `System.String` |  |

#### Returns
**Type:** Spine.ClippingAttachment

### NewMeshAttachment(Skin, string, string)
```csharp
MeshAttachment NewMeshAttachment(Skin skin, string name, string path)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `skin` | `Spine.Skin` |  |
| `name` | `System.String` |  |
| `path` | `System.String` |  |

#### Returns
**Type:** Spine.MeshAttachment

### NewPathAttachment(Skin, string)
```csharp
PathAttachment NewPathAttachment(Skin skin, string name)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `skin` | `Spine.Skin` |  |
| `name` | `System.String` |  |

#### Returns
**Type:** Spine.PathAttachment

### NewPointAttachment(Skin, string)
```csharp
PointAttachment NewPointAttachment(Skin skin, string name)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `skin` | `Spine.Skin` |  |
| `name` | `System.String` |  |

#### Returns
**Type:** Spine.PointAttachment

### NewRegionAttachment(Skin, string, string)
```csharp
RegionAttachment NewRegionAttachment(Skin skin, string name, string path)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `skin` | `Spine.Skin` |  |
| `name` | `System.String` |  |
| `path` | `System.String` |  |

#### Returns
**Type:** Spine.RegionAttachment



