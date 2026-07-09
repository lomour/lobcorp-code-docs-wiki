---
uid: Global.AttackCommand_creature
canonical_path: /api/Global/Creature/AttackCommandcreature
---
# Class AttackCommand_creature
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AttackCommand_creature : CreatureCommand
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureCommand](/api/Global/Units/Unit-Commands/Creature-Commands/CreatureCommand) → AttackCommand_creature

## Derived
[AttackCommand_cosmos](/api/Global/Misc/AttackCommandcosmos), [AttackCommand_nothing](/api/Global/Misc/AttackCommandnothing)

## Constructors
### AttackCommand_creature(UnitModel)
```csharp
public AttackCommand_creature(UnitModel target)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

## Fields
### target
```csharp
protected UnitModel target
```

#### Field Value
**Type:** Global.UnitModel

## Methods
### Execute()
```csharp
public override void Execute()
```

### GetTarget()
```csharp
public UnitModel GetTarget()
```

#### Returns
**Type:** Global.UnitModel

### GiveDamage()
```csharp
public virtual void GiveDamage()
```

### MoveOrAttack()
```csharp
private void MoveOrAttack()
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






