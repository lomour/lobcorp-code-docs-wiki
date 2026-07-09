---
uid: Global.PursueCreatureCommand
canonical_path: /api/Global/Creature/PursueCreatureCommand
---
# Class PursueCreatureCommand
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PursueCreatureCommand : CreatureCommand
```
> This section may have incomplete or incorrect information.
{.is-warning}

> This class is not used.
{.is-info}


Command to an abnormality to pursue a worker.

Targets the closest agent. Attacks if close enough, otherwise moves after that agent.

Seems unused... maybe they all just use [PursueCreatureCommandAlter](/api/Global/Units/Unit-Commands/Creature-Commands/PursueCreatureCommandAlter)?





## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureCommand](/api/Global/Units/Unit-Commands/Creature-Commands/CreatureCommand) → PursueCreatureCommand

## Constructors
### PursueCreatureCommand(WorkerModel)
```csharp
public PursueCreatureCommand(WorkerModel target)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |

## Fields
### elapsedTime
```csharp
private float elapsedTime
```


#### Field Value
**Type:** System.Single

### targetWorker
```csharp
private WorkerModel targetWorker
```


#### Field Value
**Type:** Global.WorkerModel

## Methods
### CheckPursueTarget()
```csharp
private void CheckPursueTarget()
```


### Execute()
```csharp
public override void Execute()
```


### OnDestroy()
```csharp
public override void OnDestroy()
```


### OnStart()
```csharp
public override void OnStart()
```


## Inherited Members
[actor](/api/Global/Units/Unit-Commands/Creature-Commands/CreatureCommand#actor), [cmdQueue](/api/Global/Units/Unit-Commands/Creature-Commands/CreatureCommand#cmdqueue), [isFinished](/api/Global/Units/Unit-Commands/Creature-Commands/CreatureCommand#isfinished), [endCmd](/api/Global/Units/Unit-Commands/Creature-Commands/CreatureCommand#endcmd), [OnInit(CreatureModel, CreatureCommandQueue)](/api/Global/Units/Unit-Commands/Creature-Commands/CreatureCommand#oninit-creaturemodel-creaturecommandqueue), [OnStop()](/api/Global/Units/Unit-Commands/Creature-Commands/CreatureCommand#onstop), [Finish()](/api/Global/Units/Unit-Commands/Creature-Commands/CreatureCommand#finish), [SetEndCommand(OnCommandEnd)](/api/Global/Units/Unit-Commands/Creature-Commands/CreatureCommand#setendcommand-oncommandend), [MakeMove(MapNode)](/api/Global/Units/Unit-Commands/Creature-Commands/CreatureCommand#makemove-mapnode), [MakeMove(MovableObjectNode)](/api/Global/Units/Unit-Commands/Creature-Commands/CreatureCommand#makemove-movableobjectnode), [MakePursue(WorkerModel)](/api/Global/Units/Unit-Commands/Creature-Commands/CreatureCommand#makepursue-workermodel), [MakePursueAlter(WorkerModel)](/api/Global/Units/Unit-Commands/Creature-Commands/CreatureCommand#makepursuealter-workermodel), [MakePursueAlter(WorkerModel, float)](/api/Global/Units/Unit-Commands/Creature-Commands/CreatureCommand#makepursuealter-workermodel-float), [MakePursueAlter(WorkerModel, RwbpType, int, int)](/api/Global/Units/Unit-Commands/Creature-Commands/CreatureCommand#makepursuealter-workermodel-rwbptype-int-int), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)






