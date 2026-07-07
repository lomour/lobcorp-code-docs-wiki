---
title: IMouseOnSelectListener
description: 
published: true
date: 2026-07-07T17:11:48.576Z
tags: 
editor: markdown
dateCreated: 2026-01-06T04:09:23.683Z
---

# Interface IMouseOnSelectListener
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public interface IMouseOnSelectListener
```
> This section may have incomplete or incorrect information.
{.is-warning}

Interface for listeners of being selected by the mouse (presumably, by clicking).

Implemented by:
- [Agents](/api/Global/Worker/AgentUnit)
- [Abnormalities](/api/Global/Unit/CreatureUnit)
- [Clerks](/api/Global/Worker/OfficerUnit)
- [Rabbit units](/api/Global/Unit/RabbitUnit)

Used by [UnitMouseEventManager](/api/Global/Unit/UnitMouseEventManager).


#### Methods
	bool IsSelectable()
	void OnSelect()
	void OnUnselect()


## Methods
### IsSelectable()
```csharp
bool IsSelectable()
```


#### Returns
**Type:** System.Boolean

### OnSelect()
```csharp
void OnSelect()
```


### OnUnselect()
```csharp
void OnUnselect()
```




