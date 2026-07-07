---
title: UnitAnimatorControllerDeadMotionDelegate
description: 
published: true
date: 2026-02-20T22:18:09.712Z
tags: 
editor: markdown
dateCreated: 2026-01-15T04:37:50.560Z
---

# Delegate UnitAnimatorController.DeadMotionDelegate
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public delegate void UnitAnimatorController.DeadMotionDelegate()
```

## Constructors
### DeadMotionDelegate(object, IntPtr)
```csharp
public DeadMotionDelegate(object @object, IntPtr method)
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



