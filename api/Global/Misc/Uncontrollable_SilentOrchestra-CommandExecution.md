---
title: Uncontrollable_SilentOrchestra-CommandExecution
description: 
published: true
date: 2026-02-23T20:06:44.509Z
tags: 
editor: markdown
dateCreated: 2026-01-15T04:37:43.702Z
---

# Delegate Uncontrollable_SilentOrchestra.CommandExecution
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
private delegate void Uncontrollable_SilentOrchestra.CommandExecution()
```

## Constructors
### CommandExecution(object, IntPtr)
```csharp
public CommandExecution(object @object, IntPtr method)
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



