---
title: OnCloseAction
description: 
published: true
date: 2026-07-07T17:21:14.557Z
tags: 
editor: markdown
dateCreated: 2026-01-15T02:56:12.312Z
---

# Delegate AppearanceUI.OnCloseAction
**Namespace:** [Customizing](/api/Customizing)
**Assembly:** Assembly-CSharp.dll

```csharp
public delegate void AppearanceUI.OnCloseAction(AgentData data)
```

## Constructors
### OnCloseAction(object, IntPtr)
```csharp
public OnCloseAction(object @object, IntPtr method)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `object` | `System.Object` |  |
| `method` | `System.IntPtr` |  |

## Methods
### BeginInvoke(AgentData, AsyncCallback, object)
```csharp
public virtual IAsyncResult BeginInvoke(AgentData data, AsyncCallback callback, object @object)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `data` | `Customizing.AgentData` |  |
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

### Invoke(AgentData)
```csharp
public virtual void Invoke(AgentData data)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `data` | `Customizing.AgentData` |  |



