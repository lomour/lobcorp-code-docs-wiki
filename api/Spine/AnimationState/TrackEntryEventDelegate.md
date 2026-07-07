---
title: TrackEntryEventDelegate
description: 
published: true
date: 2026-02-20T22:45:59.046Z
tags: 
editor: markdown
dateCreated: 2026-01-15T05:57:04.165Z
---

# Delegate AnimationState.TrackEntryEventDelegate
**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

```csharp
public delegate void AnimationState.TrackEntryEventDelegate(TrackEntry trackEntry, Event e)
```

## Constructors
### TrackEntryEventDelegate(object, IntPtr)
```csharp
public TrackEntryEventDelegate(object @object, IntPtr method)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `object` | `System.Object` |  |
| `method` | `System.IntPtr` |  |

## Methods
### BeginInvoke(TrackEntry, Event, AsyncCallback, object)
```csharp
public virtual IAsyncResult BeginInvoke(TrackEntry trackEntry, Event e, AsyncCallback callback, object @object)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `trackEntry` | `Spine.TrackEntry` |  |
| `e` | `Spine.Event` |  |
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

### Invoke(TrackEntry, Event)
```csharp
public virtual void Invoke(TrackEntry trackEntry, Event e)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `trackEntry` | `Spine.TrackEntry` |  |
| `e` | `Spine.Event` |  |



