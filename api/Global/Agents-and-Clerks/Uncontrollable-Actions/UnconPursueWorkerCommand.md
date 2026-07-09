---
uid: Global.UnconPursueWorkerCommand
canonical_path: /api/Global/Worker/UnconPursueWorkerCommand
---
# Class UnconPursueWorkerCommand
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class UnconPursueWorkerCommand : WorkerCommand, WorkerAttackCommand
```
> This section may have incomplete or incorrect information.
{.is-warning}


Command to make a worker try to suppress a target.

Used by Singing Machine and Red Shoes' uncontrollable actions.




## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitCommand](/api/Global/Units/Unit-Commands/Worker-Commands/WorkerCommand) → UnconPursueWorkerCommand

## Implements
[WorkerAttackCommand](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/WorkerAttackCommand)

## Constructors
### UnconPursueWorkerCommand(UnitModel)
```csharp
public UnconPursueWorkerCommand(UnitModel target)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

## Fields
### elapsedTime
```csharp
public float elapsedTime
```


#### Field Value
**Type:** System.Single

### range
```csharp
private float range
```


#### Field Value
**Type:** System.Single

### target
```csharp
private UnitModel target
```


#### Field Value
**Type:** Global.UnitModel

### workerActor
```csharp
private WorkerModel workerActor
```


#### Field Value
**Type:** Global.WorkerModel

## Methods
### CheckBattleState(ref AgentModel)
```csharp
private bool CheckBattleState(ref AgentModel attackingAgent)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `attackingAgent` | `Global.AgentModel` |  |

#### Returns
**Type:** System.Boolean

### Execute()
```csharp
public override void Execute()
```


### GiveDamage()
```csharp
public void GiveDamage()
```


### MoveOrAttack()
```csharp
private void MoveOrAttack()
```


### OnDestroy()
```csharp
public override void OnDestroy()
```


### OnInit(WorkerModel)
```csharp
public override void OnInit(WorkerModel agent)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.WorkerModel` |  |

### OnKillTarget()
```csharp
private void OnKillTarget()
```


### OnStart()
```csharp
public override void OnStart()
```


## Inherited Members
[MakeManageCreature(CreatureModel, AgentModel, SkillTypeInfo, Sprite)](/api/Global/Units/Unit-Commands/UnitCommand#actor), [isFinished](/api/Global/Units/Unit-Commands/UnitCommand#isfinished), [isRemoved](/api/Global/Units/Unit-Commands/UnitCommand#isremoved), [OnInit(UnitModel)](/api/Global/Units/Unit-Commands/UnitCommand#oninit-unitmodel), [OnInit(StandingItemModel)](/api/Global/Units/Unit-Commands/UnitCommand#oninit-standingitemmodel), [OnStop()](/api/Global/Units/Unit-Commands/UnitCommand#onstop), [Finish()](/api/Global/Units/Unit-Commands/UnitCommand#finish), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)







