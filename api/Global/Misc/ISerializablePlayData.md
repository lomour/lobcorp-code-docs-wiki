---
title: ISerializablePlayData
description: 
published: true
date: 2026-02-20T22:05:19.876Z
tags: 
editor: markdown
dateCreated: 2026-01-15T04:14:57.254Z
---

# Interface ISerializablePlayData
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
internal interface ISerializablePlayData
```
> This section may have incomplete or incorrect information.
{.is-warning}

Interface for classes which have data that needs to be saved and loaded.

#### Methods
	Dictionary<string, object> GetSaveData()
	void LoadData(Dictionary<string, object> dic)


## Methods
### GetSaveData()
```csharp
Dictionary<string, object> GetSaveData()
```


#### Returns
**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### LoadData(Dictionary<string, object>)
```csharp
void LoadData(Dictionary<string, object> dic)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |



