---
title: AgentModelCheckCommandState
description: 
published: true
date: 2026-02-20T22:24:15.312Z
tags: 
editor: markdown
dateCreated: 2026-01-15T04:48:44.754Z
---

# Delegate AgentModel.CheckCommandState
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public delegate bool AgentModel.CheckCommandState()
```

## Constructors
### CheckCommandState(object, IntPtr)
```csharp
public CheckCommandState(object @object, IntPtr method)
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



