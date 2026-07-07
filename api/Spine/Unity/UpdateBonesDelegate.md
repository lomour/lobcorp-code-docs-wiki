---
title: UpdateBonesDelegate
description: 
published: true
date: 2026-02-20T22:50:47.757Z
tags: 
editor: markdown
dateCreated: 2026-01-15T06:05:53.396Z
---

# Delegate UpdateBonesDelegate
**Namespace:** [Spine](/api/Spine) . [Unity](/api/Spine/Unity)
**Assembly:** Assembly-CSharp.dll

```csharp
public delegate void UpdateBonesDelegate(ISkeletonAnimation animated)
```

## Constructors
### UpdateBonesDelegate(object, IntPtr)
```csharp
public UpdateBonesDelegate(object @object, IntPtr method)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `object` | `System.Object` |  |
| `method` | `System.IntPtr` |  |

## Methods
### BeginInvoke(ISkeletonAnimation, AsyncCallback, object)
```csharp
public virtual IAsyncResult BeginInvoke(ISkeletonAnimation animated, AsyncCallback callback, object @object)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `animated` | `Spine.Unity.ISkeletonAnimation` |  |
| `callback` | `System.AsyncCallback` |  |
| `object` | `System.Object` |  |

#### Returns
**Type:** System.IAsyncResult

### EndInvoke(IAsyncResult)
```csharp
public virtual void EndInvoke(IAsyncResult result)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `result` | `System.IAsyncResult` |  |

### Invoke(ISkeletonAnimation)
```csharp
public virtual void Invoke(ISkeletonAnimation animated)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `animated` | `Spine.Unity.ISkeletonAnimation` |  |



