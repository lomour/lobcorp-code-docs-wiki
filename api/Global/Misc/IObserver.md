---
title: IObserver
description: 
published: true
date: 2026-07-07T17:11:51.317Z
tags: 
editor: markdown
dateCreated: 2026-01-06T04:09:26.343Z
---

# Interface IObserver
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public interface IObserver
```
> This section may have incomplete or incorrect information.
{.is-warning}

Interface for all things which listen for events.

Note: *some* events will have additional information, which needs to be grabbed from param.

#### Method
void OnNotice(string notice, params object[] param)


%% An aside: This should probably not be implemented this way. %%




## Methods
### OnNotice(string, params object[])
```csharp
void OnNotice(string notice, params object[] param)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `notice` | `System.String` |  |
| `param` | `System.Object[]` |  |



