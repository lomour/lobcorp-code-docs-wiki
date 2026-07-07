---
title: IScrollTarget
description: 
published: true
date: 2026-07-07T17:12:00.459Z
tags: 
editor: markdown
dateCreated: 2026-01-06T04:09:37.204Z
---

# Interface IScrollTarget
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public interface IScrollTarget
```
> This section may have incomplete or incorrect information.
{.is-warning}

Interface for things that can be scrolled in.

Example: [CommandWindow](/api/CommandWindow) registers itself to listen to mouse scroll while the cursor is over an [agent](/api/CommandWindow/AgentSlot), and unregisters itself when the cursor exits.

 (used for the work log) does the same.


#### Methods
	void Regist()
	void DeRegist()
	void AddTrigger()


## Methods
### AddTrigger()
```csharp
void AddTrigger()
```


### DeRegist()
```csharp
void DeRegist()
```


### Regist()
```csharp
void Regist()
```




