---
title: NoticeReciever
description: 
published: true
date: 2026-07-07T17:13:27.258Z
tags: 
editor: markdown
dateCreated: 2026-01-06T04:26:43.828Z
---

# Delegate NoticeReciever
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public delegate void NoticeReciever(params object[] param)
```

## Constructors
### NoticeReciever(object, IntPtr)
```csharp
public NoticeReciever(object @object, IntPtr method)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `object` | `System.Object` |  |
| `method` | `System.IntPtr` |  |

## Methods
### BeginInvoke(object[], AsyncCallback, object)
```csharp
public virtual IAsyncResult BeginInvoke(object[] param, AsyncCallback callback, object @object)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `param` | `System.Object[]` |  |
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

### Invoke(params object[])
```csharp
public virtual void Invoke(params object[] param)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `param` | `System.Object[]` |  |



