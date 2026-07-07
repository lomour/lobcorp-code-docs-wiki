---
title: OnSetSpriteAction
description: 
published: true
date: 2026-07-07T17:21:25.988Z
tags: 
editor: markdown
dateCreated: 2026-01-15T02:56:30.168Z
---

# Delegate SpriteSelector.OnSetSpriteAction
**Namespace:** [Customizing](/api/Customizing)
**Assembly:** Assembly-CSharp.dll

```csharp
public delegate void SpriteSelector.OnSetSpriteAction()
```

## Constructors
### OnSetSpriteAction(object, IntPtr)
```csharp
public OnSetSpriteAction(object @object, IntPtr method)
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



