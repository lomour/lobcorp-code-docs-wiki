---
title: StorySeedUIStorySeedEnd
description: 
published: true
date: 2026-02-20T22:16:16.558Z
tags: 
editor: markdown
dateCreated: 2026-01-15T04:34:22.701Z
---

# Delegate StorySeedUI.StorySeedEnd
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public delegate void StorySeedUI.StorySeedEnd(string angelaStory)
```

## Constructors
### StorySeedEnd(object, IntPtr)
```csharp
public StorySeedEnd(object @object, IntPtr method)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `object` | `System.Object` |  |
| `method` | `System.IntPtr` |  |

## Methods
### BeginInvoke(string, AsyncCallback, object)
```csharp
public virtual IAsyncResult BeginInvoke(string angelaStory, AsyncCallback callback, object @object)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `angelaStory` | `System.String` |  |
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

### Invoke(string)
```csharp
public virtual void Invoke(string angelaStory)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `angelaStory` | `System.String` |  |



