---
title: PlaySpeedSettingUIBlockedUIEvent
description: 
published: true
date: 2026-02-20T21:47:03.902Z
tags: 
editor: markdown
dateCreated: 2026-01-15T03:43:30.307Z
---

# Delegate PlaySpeedSettingUI.BlockedUIEvent
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public delegate void PlaySpeedSettingUI.BlockedUIEvent(int index)
```

## Constructors
### BlockedUIEvent(object, IntPtr)
```csharp
public BlockedUIEvent(object @object, IntPtr method)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `object` | `System.Object` |  |
| `method` | `System.IntPtr` |  |

## Methods
### BeginInvoke(int, AsyncCallback, object)
```csharp
public virtual IAsyncResult BeginInvoke(int index, AsyncCallback callback, object @object)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |
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

### Invoke(int)
```csharp
public virtual void Invoke(int index)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |



