---
title: IMouseCommandTarget
description: 
published: true
date: 2026-07-07T17:11:36.109Z
tags: 
editor: markdown
dateCreated: 2026-01-06T04:09:12.902Z
---

# Interface IMouseCommandTarget
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public interface IMouseCommandTarget
```
> This section may have incomplete or incorrect information.
{.is-warning}

Interface with one method, which gets the [IMouseCommandTargetModel](/api/Global/Model/IMouseCommandTargetModel) user.

For getting certain things which can be targeted with the mouse:
- [Agents](/api/Global/Worker/AgentUnit)
- [Clerks](/api/Global/Worker/OfficerUnit)
- [Abnormalities](/api/Global/Unit/CreatureUnit)
- [Rabbit units](/api/Global/Unit/RabbitUnit)
- [Passageways](/api/Global/Object/PassageObject)

Used by [UnitMouseEventManager](/api/Global/Unit/UnitMouseEventManager) (for selection and ordering agents to move) and for [bullet research](/api/GlobalBullet/GlobalBulletWindow).


#### Method
	IMouseCommandTargetModel GetCommandTargetModel


## Methods
### GetCommandTargetModel()
```csharp
IMouseCommandTargetModel GetCommandTargetModel()
```


#### Returns
**Type:** Global.IMouseCommandTargetModel



