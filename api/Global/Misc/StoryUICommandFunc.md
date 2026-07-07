---
title: StoryUICommandFunc
description: 
published: true
date: 2026-02-20T22:16:24.975Z
tags: 
editor: markdown
dateCreated: 2026-01-15T04:34:38.756Z
---

# Delegate StoryUI.CommandFunc
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public delegate bool StoryUI.CommandFunc(StoryUI.StoryScriptCommandEventEnum e)
```

## Constructors
### CommandFunc(object, IntPtr)
```csharp
public CommandFunc(object @object, IntPtr method)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `object` | `System.Object` |  |
| `method` | `System.IntPtr` |  |

## Methods
### BeginInvoke(StoryScriptCommandEventEnum, AsyncCallback, object)
```csharp
public virtual IAsyncResult BeginInvoke(StoryUI.StoryScriptCommandEventEnum e, AsyncCallback callback, object @object)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `e` | `Global.StoryUI.StoryScriptCommandEventEnum` |  |
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

### Invoke(StoryScriptCommandEventEnum)
```csharp
public virtual bool Invoke(StoryUI.StoryScriptCommandEventEnum e)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `e` | `Global.StoryUI.StoryScriptCommandEventEnum` |  |

#### Returns
**Type:** System.Boolean



