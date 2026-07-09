---
uid: Global.AttackCommand
canonical_path: /api/Global/Worker/AttackCommand
---
# Class AttackCommand
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AttackCommand : WorkerCommand
```
> This section may have incomplete or incorrect information.
{.is-warning}


Represents a command to an employee to suppress something.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitCommand](/api/Global/Units/Unit-Commands/Worker-Commands/WorkerCommand) → AttackCommand

## Constructors
### AttackCommand(UnitModel)
```csharp
public AttackCommand(UnitModel target)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

## Fields
### damage
```csharp
private int damage
```


#### Field Value
**Type:** System.Int32

### postDelay
```csharp
private float postDelay
```


#### Field Value
**Type:** System.Single

### preDelay
```csharp
private float preDelay
```


#### Field Value
**Type:** System.Single

### range
```csharp
private float range
```


#### Field Value
**Type:** System.Single

### retreat
```csharp
private bool retreat
```


#### Field Value
**Type:** System.Boolean

### retreatDelay
```csharp
private float retreatDelay
```


#### Field Value
**Type:** System.Single

### retreatDuration
```csharp
private float retreatDuration
```


#### Field Value
**Type:** System.Single

### target
```csharp
private UnitModel target
```


#### Field Value
**Type:** Global.UnitModel

## Methods
### CheckRange()
```csharp
private bool CheckRange()
```


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






