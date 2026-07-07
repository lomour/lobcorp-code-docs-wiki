---
title: SkeletonUtilityDelegate
description: 
published: true
date: 2026-02-20T22:50:14.494Z
tags: 
editor: markdown
dateCreated: 2026-01-15T06:04:51.480Z
---

# Delegate SkeletonUtility.SkeletonUtilityDelegate
**Namespace:** [Spine](/api/Spine) . [Unity](/api/Spine/Unity)
**Assembly:** Assembly-CSharp.dll

```csharp
public delegate void SkeletonUtility.SkeletonUtilityDelegate()
```

## Constructors
### SkeletonUtilityDelegate(object, IntPtr)
```csharp
public SkeletonUtilityDelegate(object @object, IntPtr method)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `object` | `System.Object` |  |
| `method` | `System.IntPtr` |  |

## Methods
### BeginInvoke(AsyncCallback, object)
```csharp
public virtual IAsyncResult BeginInvoke(AsyncCallback callback, object @object)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
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

### Invoke()
```csharp
public virtual void Invoke()
```



