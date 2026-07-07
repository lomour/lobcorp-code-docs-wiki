---
title: BulletFunc
description: 
published: true
date: 2026-02-20T22:40:20.213Z
tags: 
editor: markdown
dateCreated: 2026-01-15T05:19:23.901Z
---

# Delegate GlobalBulletManager.BulletFunc
**Namespace:** [GlobalBullet](/api/GlobalBullet)
**Assembly:** Assembly-CSharp.dll

```csharp
private delegate void GlobalBulletManager.BulletFunc(UnitModel target)
```

## Constructors
### BulletFunc(object, IntPtr)
```csharp
public BulletFunc(object @object, IntPtr method)
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



