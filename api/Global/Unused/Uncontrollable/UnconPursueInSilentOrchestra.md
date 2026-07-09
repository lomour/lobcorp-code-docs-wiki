---
uid: Global.UnconPursueInSilentOrchestra
canonical_path: /api/Global/Worker/UnconPursueInSilentOrchestra
---
# Class UnconPursueInSilentOrchestra
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class UnconPursueInSilentOrchestra : WorkerCommand
```
> This section may have incomplete or incorrect information.
{.is-warning}

> This class is not used.
{.is-info}


Unused uncontrollable effect for [The Silent Orchestra](/api/Global/Abnormalities/The-Silent-Orchestra/SilentOrchestra).



## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitCommand](/api/Global/Units/Unit-Commands/Worker-Commands/WorkerCommand) → UnconPursueInSilentOrchestra

## Constructors
### UnconPursueInSilentOrchestra(UnitModel, SilentOrchestra)
```csharp
public UnconPursueInSilentOrchestra(UnitModel target, SilentOrchestra orchestra)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `orchestra` | `Global.SilentOrchestra` |  |

## Fields
### attackRange
```csharp
public float attackRange
```


#### Field Value
**Type:** System.Single

### currentTarget
```csharp
private UnitModel currentTarget
```


#### Field Value
**Type:** Global.UnitModel

### miss
```csharp
private float miss
```


#### Field Value
**Type:** System.Single

### orchestra
```csharp
private SilentOrchestra orchestra
```


#### Field Value
**Type:** Global.SilentOrchestra

### randomMoveTimer
```csharp
private Timer randomMoveTimer
```


#### Field Value
**Type:** Global.Timer

### uncon
```csharp
private Uncontrollable_SilentOrchestra uncon
```


#### Field Value
**Type:** Global.Uncontrollable_SilentOrchestra

## Properties
### workerActor
```csharp
private WorkerModel workerActor { get; }
```

#### Property Value
**Type:** Global.WorkerModel

## Methods
### CheckRange()
```csharp
private void CheckRange()
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
public void OnKillTarget()
```


### OnStart()
```csharp
public override void OnStart()
```


### RandomMove()
```csharp
private void RandomMove()
```


## Inherited Members
[MakeManageCreature(CreatureModel, AgentModel, SkillTypeInfo, Sprite)](/api/Global/Units/Unit-Commands/UnitCommand#actor), [isFinished](/api/Global/Units/Unit-Commands/UnitCommand#isfinished), [isRemoved](/api/Global/Units/Unit-Commands/UnitCommand#isremoved), [OnInit(UnitModel)](/api/Global/Units/Unit-Commands/UnitCommand#oninit-unitmodel), [OnInit(StandingItemModel)](/api/Global/Units/Unit-Commands/UnitCommand#oninit-standingitemmodel), [OnStop()](/api/Global/Units/Unit-Commands/UnitCommand#onstop), [Finish()](/api/Global/Units/Unit-Commands/UnitCommand#finish), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)






