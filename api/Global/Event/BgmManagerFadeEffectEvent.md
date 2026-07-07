---
title: BgmManagerFadeEffectEvent
description: 
published: true
date: 2026-02-20T21:46:28.306Z
tags: 
editor: markdown
dateCreated: 2026-01-15T03:42:29.241Z
---

# Delegate BgmManager.FadeEffectEvent
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public delegate bool BgmManager.FadeEffectEvent()
```

## Constructors
### FadeEffectEvent(object, IntPtr)
```csharp
public FadeEffectEvent(object @object, IntPtr method)
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
public virtual bool EndInvoke(IAsyncResult result)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `result` | `System.IAsyncResult` |  |

#### Returns
**Type:** System.Boolean

### Invoke()
```csharp
public virtual bool Invoke()
```

#### Returns
**Type:** System.Boolean



