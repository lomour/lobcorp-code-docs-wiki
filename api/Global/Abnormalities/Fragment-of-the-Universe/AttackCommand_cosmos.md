---
uid: Global.AttackCommand_cosmos
canonical_path: /api/Global/Misc/AttackCommandcosmos
---
# Class AttackCommand_cosmos
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AttackCommand_cosmos : AttackCommand_creature
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureCommand](/api/Global/Units/Unit-Commands/Creature-Commands/CreatureCommand) → [AttackCommand_creature](/api/Global/Creature/AttackCommandcreature) → AttackCommand_cosmos

## Constructors
### AttackCommand_cosmos(UnitModel)
```csharp
public AttackCommand_cosmos(UnitModel target)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

## Fields
### attackType
```csharp
private int attackType
```

#### Field Value
**Type:** System.Int32

### hitLeftEffect
```csharp
public const string hitLeftEffect = "Effect/Creature/Cosmos/Cosmos-lateral-left"
```

#### Field Value
**Type:** System.String

### hitLeftUpEffect
```csharp
public const string hitLeftUpEffect = "Effect/Creature/Cosmos/Cosmos-lateral-left-up"
```

#### Field Value
**Type:** System.String

### hitRightEffect
```csharp
public const string hitRightEffect = "Effect/Creature/Cosmos/Cosmos-lateral-right"
```

#### Field Value
**Type:** System.String

### hitRightUpEffect
```csharp
public const string hitRightUpEffect = "Effect/Creature/Cosmos/Cosmos-lateral-right-up"
```

#### Field Value
**Type:** System.String

## Methods
### GiveDamage()
```csharp
public override void GiveDamage()
```

### OnInit(CreatureModel, CreatureCommandQueue)
```csharp
public override void OnInit(CreatureModel creature, CreatureCommandQueue cmdQueue)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |
| `cmdQueue` | `Global.CreatureCommandQueue` |  |

### SetAttackType(int)
```csharp
public void SetAttackType(int attackType)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `attackType` | `System.Int32` |  |

## Inherited Members
[target](/api/Global/Units/Unit-Commands/Creature-Commands/CreatureCommand#actor), [cmdQueue](/api/Global/Units/Unit-Commands/Creature-Commands/CreatureCommand#cmdqueue), [isFinished](/api/Global/Units/Unit-Commands/Creature-Commands/CreatureCommand#isfinished), [endCmd](/api/Global/Units/Unit-Commands/Creature-Commands/CreatureCommand#endcmd), [OnStop()](/api/Global/Units/Unit-Commands/Creature-Commands/CreatureCommand#onstop), [Finish()](/api/Global/Units/Unit-Commands/Creature-Commands/CreatureCommand#finish), [SetEndCommand(OnCommandEnd)](/api/Global/Units/Unit-Commands/Creature-Commands/CreatureCommand#setendcommand-oncommandend), [MakeMove(MapNode)](/api/Global/Units/Unit-Commands/Creature-Commands/CreatureCommand#makemove-mapnode), [MakeMove(MovableObjectNode)](/api/Global/Units/Unit-Commands/Creature-Commands/CreatureCommand#makemove-movableobjectnode), [MakePursue(WorkerModel)](/api/Global/Units/Unit-Commands/Creature-Commands/CreatureCommand#makepursue-workermodel), [MakePursueAlter(WorkerModel)](/api/Global/Units/Unit-Commands/Creature-Commands/CreatureCommand#makepursuealter-workermodel), [MakePursueAlter(WorkerModel, float)](/api/Global/Units/Unit-Commands/Creature-Commands/CreatureCommand#makepursuealter-workermodel-float), [MakePursueAlter(WorkerModel, RwbpType, int, int)](/api/Global/Units/Unit-Commands/Creature-Commands/CreatureCommand#makepursuealter-workermodel-rwbptype-int-int), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)







