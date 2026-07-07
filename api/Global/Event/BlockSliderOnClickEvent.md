---
title: BlockSliderOnClickEvent
description: 
published: true
date: 2026-02-20T21:46:30.109Z
tags: 
editor: markdown
dateCreated: 2026-01-15T03:42:32.637Z
---

# Delegate BlockSlider.OnClickEvent
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public delegate void BlockSlider.OnClickEvent(float rate)
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
### BeginInvoke(float, AsyncCallback, object)
```csharp
public virtual IAsyncResult BeginInvoke(float rate, AsyncCallback callback, object @object)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `rate` | `System.Single` |  |
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

### Invoke(float)
```csharp
public virtual void Invoke(float rate)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `rate` | `System.Single` |  |



