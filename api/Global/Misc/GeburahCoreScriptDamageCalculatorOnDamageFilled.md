---
title: GeburahCoreScriptDamageCalculatorOnDamageFilled
description: 
published: true
date: 2026-02-20T22:03:56.328Z
tags: 
editor: markdown
dateCreated: 2026-01-15T04:12:40.898Z
---

# Delegate GeburahCoreScript.DamageCalculator.OnDamageFilled
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public delegate void GeburahCoreScript.DamageCalculator.OnDamageFilled()
```

## Constructors
### OnDamageFilled(object, IntPtr)
```csharp
public OnDamageFilled(object @object, IntPtr method)
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



