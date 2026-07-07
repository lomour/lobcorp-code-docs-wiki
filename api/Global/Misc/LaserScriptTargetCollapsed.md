---
title: LaserScriptTargetCollapsed
description: 
published: true
date: 2026-02-20T22:06:28.511Z
tags: 
editor: markdown
dateCreated: 2026-01-15T04:16:58.099Z
---

# Delegate LaserScript.TargetCollapsed
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public delegate void LaserScript.TargetCollapsed(UnitModel target)
```

## Constructors
### TargetCollapsed(object, IntPtr)
```csharp
public TargetCollapsed(object @object, IntPtr method)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `object` | `System.Object` |  |
| `method` | `System.IntPtr` |  |

## Methods
### BeginInvoke(UnitModel, AsyncCallback, object)
```csharp
public virtual IAsyncResult BeginInvoke(UnitModel target, AsyncCallback callback, object @object)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
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

### Invoke(UnitModel)
```csharp
public virtual void Invoke(UnitModel target)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |



