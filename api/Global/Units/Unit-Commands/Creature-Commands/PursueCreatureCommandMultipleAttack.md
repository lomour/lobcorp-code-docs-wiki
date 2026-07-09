---
uid: Global.PursueCreatureCommandMultipleAttack
canonical_path: /api/Global/Creature/PursueCreatureCommandMultipleAttack
---
# Class PursueCreatureCommandMultipleAttack
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PursueCreatureCommandMultipleAttack : CreatureCommand
```
> This section may have incomplete or incorrect information.
{.is-warning}

> This class is not used.
{.is-info}


Command to an abnormality to chase a target, attack, and then never move again I guess? 

Doesn't seem used.




## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureCommand](/api/Global/Units/Unit-Commands/Creature-Commands/CreatureCommand) → PursueCreatureCommandMultipleAttack

## Constructors
### PursueCreatureCommandMultipleAttack(WorkerModel)
```csharp
public PursueCreatureCommandMultipleAttack(WorkerModel mainTarget)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `mainTarget` | `Global.WorkerModel` |  |

### PursueCreatureCommandMultipleAttack(WorkerModel, float)
```csharp
public PursueCreatureCommandMultipleAttack(WorkerModel mainTarget, float damage)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `mainTarget` | `Global.WorkerModel` |  |
| `damage` | `System.Single` |  |

### PursueCreatureCommandMultipleAttack(WorkerModel, float, float)
```csharp
public PursueCreatureCommandMultipleAttack(WorkerModel mainTarget, float damage, float range)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `mainTarget` | `Global.WorkerModel` |  |
| `damage` | `System.Single` |  |
| `range` | `System.Single` |  |

## Fields
### attackDelay
```csharp
private Timer attackDelay
```


#### Field Value
**Type:** Global.Timer

### canMove
```csharp
private bool canMove
```


#### Field Value
**Type:** System.Boolean

### damage
```csharp
private float damage
```


#### Field Value
**Type:** System.Single

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

### range
```csharp
private float range
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


### GetTargetsInRange()
```csharp
public List<UnitModel> GetTargetsInRange()
```


#### Returns
**Type:** System.Collections.Generic.List{UnitModel}

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


### SetRange(float)
```csharp
public void SetRange(float range)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `range` | `System.Single` |  |

## Inherited Members
[actor](/api/Global/Units/Unit-Commands/Creature-Commands/CreatureCommand#actor), [cmdQueue](/api/Global/Units/Unit-Commands/Creature-Commands/CreatureCommand#cmdqueue), [isFinished](/api/Global/Units/Unit-Commands/Creature-Commands/CreatureCommand#isfinished), [endCmd](/api/Global/Units/Unit-Commands/Creature-Commands/CreatureCommand#endcmd), [OnInit(CreatureModel, CreatureCommandQueue)](/api/Global/Units/Unit-Commands/Creature-Commands/CreatureCommand#oninit-creaturemodel-creaturecommandqueue), [OnStop()](/api/Global/Units/Unit-Commands/Creature-Commands/CreatureCommand#onstop), [Finish()](/api/Global/Units/Unit-Commands/Creature-Commands/CreatureCommand#finish), [SetEndCommand(OnCommandEnd)](/api/Global/Units/Unit-Commands/Creature-Commands/CreatureCommand#setendcommand-oncommandend), [MakeMove(MapNode)](/api/Global/Units/Unit-Commands/Creature-Commands/CreatureCommand#makemove-mapnode), [MakeMove(MovableObjectNode)](/api/Global/Units/Unit-Commands/Creature-Commands/CreatureCommand#makemove-movableobjectnode), [MakePursue(WorkerModel)](/api/Global/Units/Unit-Commands/Creature-Commands/CreatureCommand#makepursue-workermodel), [MakePursueAlter(WorkerModel)](/api/Global/Units/Unit-Commands/Creature-Commands/CreatureCommand#makepursuealter-workermodel), [MakePursueAlter(WorkerModel, float)](/api/Global/Units/Unit-Commands/Creature-Commands/CreatureCommand#makepursuealter-workermodel-float), [MakePursueAlter(WorkerModel, RwbpType, int, int)](/api/Global/Units/Unit-Commands/Creature-Commands/CreatureCommand#makepursuealter-workermodel-rwbptype-int-int), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)






