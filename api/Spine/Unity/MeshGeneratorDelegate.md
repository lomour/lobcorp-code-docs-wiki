---
title: MeshGeneratorDelegate
description: 
published: true
date: 2026-02-20T22:48:53.589Z
tags: 
editor: markdown
dateCreated: 2026-01-15T06:02:24.179Z
---

# Delegate MeshGeneratorDelegate
**Namespace:** [Spine](/api/Spine) . [Unity](/api/Spine/Unity)
**Assembly:** Assembly-CSharp.dll

```csharp
public delegate void MeshGeneratorDelegate(MeshGeneratorBuffers buffers)
```

## Constructors
### MeshGeneratorDelegate(object, IntPtr)
```csharp
public MeshGeneratorDelegate(object @object, IntPtr method)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `object` | `System.Object` |  |
| `method` | `System.IntPtr` |  |

## Methods
### BeginInvoke(MeshGeneratorBuffers, AsyncCallback, object)
```csharp
public virtual IAsyncResult BeginInvoke(MeshGeneratorBuffers buffers, AsyncCallback callback, object @object)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `buffers` | `Spine.Unity.MeshGeneratorBuffers` |  |
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

### Invoke(MeshGeneratorBuffers)
```csharp
public virtual void Invoke(MeshGeneratorBuffers buffers)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `buffers` | `Spine.Unity.MeshGeneratorBuffers` |  |



