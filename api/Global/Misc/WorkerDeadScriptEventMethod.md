---
title: WorkerDeadScriptEventMethod
description: 
published: true
date: 2026-02-20T22:19:03.019Z
tags: 
editor: markdown
dateCreated: 2026-01-15T04:39:25.517Z
---

# Delegate WorkerDeadScript.EventMethod
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public delegate void WorkerDeadScript.EventMethod(int index)
```

## Constructors
### EventMethod(object, IntPtr)
```csharp
public EventMethod(object @object, IntPtr method)
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



