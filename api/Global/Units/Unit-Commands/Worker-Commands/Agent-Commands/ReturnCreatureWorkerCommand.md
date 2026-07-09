---
uid: Global.ReturnCreatureWorkerCommand
canonical_path: /api/Global/Worker/ReturnCreatureWorkerCommand
---
# Class ReturnCreatureWorkerCommand
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ReturnCreatureWorkerCommand : WorkerCommand
```
> This section may have incomplete or incorrect information.
{.is-warning}

> This class is not used.
{.is-info}


Unused command for an agent to return an abnormality to its unit.




## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitCommand](/api/Global/Units/Unit-Commands/Worker-Commands/WorkerCommand) → ReturnCreatureWorkerCommand

## Constructors
### ReturnCreatureWorkerCommand(CreatureModel)
```csharp
public ReturnCreatureWorkerCommand(CreatureModel target)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.CreatureModel` |  |

## Fields
### creatureGet
```csharp
private bool creatureGet
```


#### Field Value
**Type:** System.Boolean

### target
```csharp
private CreatureModel target
```


#### Field Value
**Type:** Global.CreatureModel

## Methods
### CheckRanage()
```csharp
private void CheckRanage()
```


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






