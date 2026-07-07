---
title: EndEvent
description: 
published: true
date: 2026-02-20T22:51:12.346Z
tags: 
editor: markdown
dateCreated: 2026-01-15T06:14:43.185Z
---

# Delegate AdventClockUI.EndEvent
**Namespace:** [WhiteNightSpace](/api/WhiteNightSpace)
**Assembly:** Assembly-CSharp.dll

```csharp
public delegate void AdventClockUI.EndEvent()
```

## Constructors
### EndEvent(object, IntPtr)
```csharp
public EndEvent(object @object, IntPtr method)
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



