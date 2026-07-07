---
title: OnClickEvent
description: 
published: true
date: 2026-02-20T22:40:43.536Z
tags: 
editor: markdown
dateCreated: 2026-01-15T05:22:15.552Z
---

# Delegate InventoryAgentSlot.OnClickEvent
**Namespace:** [Inventory](/api/Inventory)
**Assembly:** Assembly-CSharp.dll

```csharp
public delegate void InventoryAgentSlot.OnClickEvent()
```

## Constructors
### OnClickEvent(object, IntPtr)
```csharp
public OnClickEvent(object @object, IntPtr method)
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



