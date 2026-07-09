---
uid: Global.MoveWorkerCommand
canonical_path: /api/Global/Worker/MoveWorkerCommand
---
# Class MoveWorkerCommand
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class MoveWorkerCommand : WorkerCommand
```
> This section may have incomplete or incorrect information.
{.is-warning}


Command for a [worker](/api/Global/Agents-and-Clerks/WorkerUnit) to move to a target node.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitCommand](/api/Global/Units/Unit-Commands/Worker-Commands/WorkerCommand) → MoveWorkerCommand

## Constructors
### MoveWorkerCommand(MapNode)
```csharp
public MoveWorkerCommand(MapNode targetNode)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `targetNode` | `Global.MapNode` |  |

### MoveWorkerCommand(MovableObjectNode)
```csharp
public MoveWorkerCommand(MovableObjectNode movableNode)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `movableNode` | `Global.MovableObjectNode` |  |

## Fields
### targetMovable
```csharp
public MovableObjectNode targetMovable
```


#### Field Value
**Type:** Global.MovableObjectNode

### targetNode
```csharp
public MapNode targetNode
```


#### Field Value
**Type:** Global.MapNode

## Methods
### Execute()
```csharp
public override void Execute()
```


### OnStart()
```csharp
public override void OnStart()
```


### OnStop()
```csharp
public override void OnStop()
```


## Inherited Members
[MakeManageCreature(CreatureModel, AgentModel, SkillTypeInfo, Sprite)](/api/Global/Units/Unit-Commands/UnitCommand#actor), [isFinished](/api/Global/Units/Unit-Commands/UnitCommand#isfinished), [isRemoved](/api/Global/Units/Unit-Commands/UnitCommand#isremoved), [OnInit(WorkerModel)](/api/Global/Units/Unit-Commands/UnitCommand#oninit-workermodel), [OnInit(UnitModel)](/api/Global/Units/Unit-Commands/UnitCommand#oninit-unitmodel), [OnInit(StandingItemModel)](/api/Global/Units/Unit-Commands/UnitCommand#oninit-standingitemmodel), [OnDestroy()](/api/Global/Units/Unit-Commands/UnitCommand#ondestroy), [Finish()](/api/Global/Units/Unit-Commands/UnitCommand#finish), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)






