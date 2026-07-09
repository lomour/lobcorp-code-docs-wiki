---
uid: Global.PursueCreatureCommandAlter
canonical_path: /api/Global/Creature/PursueCreatureCommandAlter
---
# Class PursueCreatureCommandAlter
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PursueCreatureCommandAlter : CreatureCommand
```
> This section may have incomplete or incorrect information.
{.is-warning}


Command to pursue a nearby worker.

Attacks if close enough, and otherwise moves towards the target worker.
Every second, checks if there is a valid target within 5 units, and switches targets to them (sort of randomly); otherwise, starts roaming.

Ends when this creature is no longer breaching or the target is dead #verify.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureCommand](/api/Global/Units/Unit-Commands/Creature-Commands/CreatureCommand) → PursueCreatureCommandAlter

## Constructors
### PursueCreatureCommandAlter(WorkerModel)
```csharp
public PursueCreatureCommandAlter(WorkerModel target)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |

### PursueCreatureCommandAlter(WorkerModel, float)
```csharp
public PursueCreatureCommandAlter(WorkerModel target, float damage)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |
| `damage` | `System.Single` |  |

### PursueCreatureCommandAlter(WorkerModel, RwbpType, int, int)
```csharp
public PursueCreatureCommandAlter(WorkerModel target, RwbpType dmgType, int dmgMin, int dmgMax)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |
| `dmgType` | `Global.RwbpType` |  |
| `dmgMin` | `System.Int32` |  |
| `dmgMax` | `System.Int32` |  |

## Fields
### changeTargetTimer
```csharp
private Timer changeTargetTimer
```


#### Field Value
**Type:** Global.Timer

### damage
```csharp
private float damage
```


#### Field Value
**Type:** System.Single

### dmgMax
```csharp
private int dmgMax
```


#### Field Value
**Type:** System.Int32

### dmgMin
```csharp
private int dmgMin
```


#### Field Value
**Type:** System.Int32

### dmgType
```csharp
private RwbpType dmgType
```


#### Field Value
**Type:** Global.RwbpType

### elapsedTime
```csharp
private float elapsedTime
```


#### Field Value
**Type:** System.Single

### maxWaitTime
```csharp
private const float maxWaitTime = 10
```


#### Field Value
**Type:** System.Single

### targetWorker
```csharp
private WorkerModel targetWorker
```


#### Field Value
**Type:** Global.WorkerModel

### waitingTime
```csharp
private float waitingTime
```


#### Field Value
**Type:** System.Single

## Methods
### CheckPursueTarget()
```csharp
private void CheckPursueTarget()
```


### Execute()
```csharp
public override void Execute()
```


### GiveDamage()
```csharp
public void GiveDamage()
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






