---
uid: Global.FollowWorkerCommand
canonical_path: /api/Global/Worker/FollowWorkerCommand
---
# Class FollowWorkerCommand
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class FollowWorkerCommand : WorkerCommand
```
> This section may have incomplete or incorrect information.
{.is-warning}


Sets a worker to follow a worker.

Seems to only be used by Singing Machine's uncontrollable effect...



## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitCommand](/api/Global/Units/Unit-Commands/Worker-Commands/WorkerCommand) → FollowWorkerCommand

## Constructors
### FollowWorkerCommand(MovableObjectNode)
```csharp
public FollowWorkerCommand(MovableObjectNode target)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.MovableObjectNode` |  |

## Fields
### elapsedTime
```csharp
public float elapsedTime
```


#### Field Value
**Type:** System.Single

### targetMovable
```csharp
public MovableObjectNode targetMovable
```


#### Field Value
**Type:** Global.MovableObjectNode

## Methods
### Execute()
```csharp
public override void Execute()
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

### OnStart()
```csharp
public override void OnStart()
```


## Inherited Members
[MakeManageCreature(CreatureModel, AgentModel, SkillTypeInfo, Sprite)](/api/Global/Units/Unit-Commands/UnitCommand#actor), [isFinished](/api/Global/Units/Unit-Commands/UnitCommand#isfinished), [isRemoved](/api/Global/Units/Unit-Commands/UnitCommand#isremoved), [OnInit(UnitModel)](/api/Global/Units/Unit-Commands/UnitCommand#oninit-unitmodel), [OnInit(StandingItemModel)](/api/Global/Units/Unit-Commands/UnitCommand#oninit-standingitemmodel), [OnStop()](/api/Global/Units/Unit-Commands/UnitCommand#onstop), [Finish()](/api/Global/Units/Unit-Commands/UnitCommand#finish), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)






