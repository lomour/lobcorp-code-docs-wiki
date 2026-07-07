---
title: DraggedObjectOnDropEnd
description: 
published: true
date: 2026-02-20T22:01:38.746Z
tags: 
editor: markdown
dateCreated: 2026-01-15T04:08:40.066Z
---

# Delegate DraggedObject.OnDropEnd
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public delegate void DraggedObject.OnDropEnd(Drop drop, bool state)
```

## Constructors
### OnDropEnd(object, IntPtr)
```csharp
public OnDropEnd(object @object, IntPtr method)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `object` | `System.Object` |  |
| `method` | `System.IntPtr` |  |

## Methods
### BeginInvoke(Drop, bool, AsyncCallback, object)
```csharp
public virtual IAsyncResult BeginInvoke(Drop drop, bool state, AsyncCallback callback, object @object)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `drop` | `Global.Drop` |  |
| `state` | `System.Boolean` |  |
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

### Invoke(Drop, bool)
```csharp
public virtual void Invoke(Drop drop, bool state)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `drop` | `Global.Drop` |  |
| `state` | `System.Boolean` |  |



