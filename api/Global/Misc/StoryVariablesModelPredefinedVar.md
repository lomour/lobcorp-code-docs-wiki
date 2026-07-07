---
title: StoryVariablesModelPredefinedVar
description: 
published: true
date: 2026-02-20T22:16:31.984Z
tags: 
editor: markdown
dateCreated: 2026-01-15T04:34:51.938Z
---

# Delegate StoryVariablesModel.PredefinedVar
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
private delegate int StoryVariablesModel.PredefinedVar()
```

## Constructors
### PredefinedVar(object, IntPtr)
```csharp
public PredefinedVar(object @object, IntPtr method)
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
public virtual int EndInvoke(IAsyncResult result)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `result` | `System.IAsyncResult` |  |

#### Returns
**Type:** System.Int32

### Invoke()
```csharp
public virtual int Invoke()
```

#### Returns
**Type:** System.Int32



