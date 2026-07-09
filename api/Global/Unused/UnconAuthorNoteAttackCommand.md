---
uid: Global.UnconAuthorNoteAttackCommand
canonical_path: /api/Global/Worker/UnconAuthorNoteAttackCommand
---
# Class UnconAuthorNoteAttackCommand
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class UnconAuthorNoteAttackCommand : WorkerCommand, WorkerAttackCommand
```
> This section may have incomplete or incorrect information.
{.is-warning}

> This class is not used.
{.is-info}




## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitCommand](/api/Global/Units/Unit-Commands/Worker-Commands/WorkerCommand) → UnconAuthorNoteAttackCommand

## Implements
[WorkerAttackCommand](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/WorkerAttackCommand)

## Constructors
### UnconAuthorNoteAttackCommand(AuthorNote, WorkerModel)
```csharp
public UnconAuthorNoteAttackCommand(AuthorNote note, WorkerModel target)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `note` | `Global.AuthorNote` |  |
| `target` | `Global.WorkerModel` |  |

## Fields
### elapsedTime
```csharp
public float elapsedTime
```


#### Field Value
**Type:** System.Single

### missTargetTime
```csharp
public float missTargetTime
```


#### Field Value
**Type:** System.Single

### note
```csharp
private AuthorNote note
```


#### Field Value
**Type:** Global.AuthorNote

### range
```csharp
private float range
```


#### Field Value
**Type:** System.Single

### target
```csharp
private WorkerModel target
```


#### Field Value
**Type:** Global.WorkerModel

### workerActor
```csharp
private WorkerModel workerActor
```


#### Field Value
**Type:** Global.WorkerModel

## Methods
### CheckRanage()
```csharp
private void CheckRanage()
```


### Execute()
```csharp
public override void Execute()
```


### GiveDamage()
```csharp
public void GiveDamage()
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


### OnStop()
```csharp
public override void OnStop()
```


## Inherited Members
[MakeManageCreature(CreatureModel, AgentModel, SkillTypeInfo, Sprite)](/api/Global/Units/Unit-Commands/UnitCommand#actor), [isFinished](/api/Global/Units/Unit-Commands/UnitCommand#isfinished), [isRemoved](/api/Global/Units/Unit-Commands/UnitCommand#isremoved), [OnInit(UnitModel)](/api/Global/Units/Unit-Commands/UnitCommand#oninit-unitmodel), [OnInit(StandingItemModel)](/api/Global/Units/Unit-Commands/UnitCommand#oninit-standingitemmodel), [OnDestroy()](/api/Global/Units/Unit-Commands/UnitCommand#ondestroy), [Finish()](/api/Global/Units/Unit-Commands/UnitCommand#finish), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)








