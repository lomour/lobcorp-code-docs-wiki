---
title: IMouseOnPointListener
description: 
published: true
date: 2026-07-07T17:11:42.512Z
tags: 
editor: markdown
dateCreated: 2026-01-06T04:09:20.965Z
---

# Interface IMouseOnPointListener
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public interface IMouseOnPointListener
```
> This section may have incomplete or incorrect information.
{.is-warning}

Interface for things which react to being hovered over by the cursor.

Implemented by [AgentUnit](/api/Global/Worker/AgentUnit) and [PassageObject](/api/Global/Object/PassageObject).

Used by [UnitMouseEventManager](/api/Global/Unit/UnitMouseEventManager).


#### Methods
	bool HasPointListener()
	void OnPointEnter()
	void OnPointExit()


## Methods
### HasPointListener()
```csharp
bool HasPointListener()
```


#### Returns
**Type:** System.Boolean

### OnPointEnter()
```csharp
void OnPointEnter()
```


### OnPointExit()
```csharp
void OnPointExit()
```




