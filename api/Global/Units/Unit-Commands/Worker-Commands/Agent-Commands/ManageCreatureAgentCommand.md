---
uid: Global.ManageCreatureAgentCommand
canonical_path: /api/Global/Worker/ManageCreatureAgentCommand
---
# Class ManageCreatureAgentCommand
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ManageCreatureAgentCommand : WorkerCommand
```
> This section may have incomplete or incorrect information.
{.is-warning}


Commands an [agent](/api/Global/Agents-and-Clerks/Agents/AgentUnit) to attack a target creature.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitCommand](/api/Global/Units/Unit-Commands/Worker-Commands/WorkerCommand) → ManageCreatureAgentCommand

## Constructors
### ManageCreatureAgentCommand(CreatureModel, AgentModel, SkillTypeInfo, Sprite)
```csharp
public ManageCreatureAgentCommand(CreatureModel targetCreature, AgentModel self, SkillTypeInfo skill, Sprite skillSprite)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `targetCreature` | `Global.CreatureModel` |  |
| `self` | `Global.AgentModel` |  |
| `skill` | `Global.SkillTypeInfo` |  |
| `skillSprite` | `UnityEngine.Sprite` |  |

### ManageCreatureAgentCommand(CreatureModel, AgentModel[], SkillTypeInfo)
```csharp
public ManageCreatureAgentCommand(CreatureModel targetCreature, AgentModel[] coopAgents, SkillTypeInfo skill)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `targetCreature` | `Global.CreatureModel` |  |
| `coopAgents` | `Global.AgentModel[]` |  |
| `skill` | `Global.SkillTypeInfo` |  |

## Fields
### coopAgents
```csharp
private AgentModel[] coopAgents
```


#### Field Value
**Type:** Global.AgentModel[]

### skill
```csharp
private SkillTypeInfo skill
```


#### Field Value
**Type:** Global.SkillTypeInfo

### skillSprite
```csharp
private Sprite skillSprite
```


#### Field Value
**Type:** UnityEngine.Sprite

### targetCreature
```csharp
private CreatureModel targetCreature
```


#### Field Value
**Type:** Global.CreatureModel

### useSkill
```csharp
private UseSkill useSkill
```


#### Field Value
**Type:** Global.UseSkill

### waiting
```csharp
private bool waiting
```


#### Field Value
**Type:** System.Boolean

## Methods
### Cancle()
```csharp
public void Cancle()
```


### CheckStarting(AgentModel)
```csharp
private void CheckStarting(AgentModel agent)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |

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

## Inherited Members
[MakeManageCreature(CreatureModel, AgentModel, SkillTypeInfo, Sprite)](/api/Global/Units/Unit-Commands/UnitCommand#actor), [isFinished](/api/Global/Units/Unit-Commands/UnitCommand#isfinished), [isRemoved](/api/Global/Units/Unit-Commands/UnitCommand#isremoved), [OnInit(UnitModel)](/api/Global/Units/Unit-Commands/UnitCommand#oninit-unitmodel), [OnInit(StandingItemModel)](/api/Global/Units/Unit-Commands/UnitCommand#oninit-standingitemmodel), [OnStart()](/api/Global/Units/Unit-Commands/UnitCommand#onstart), [OnStop()](/api/Global/Units/Unit-Commands/UnitCommand#onstop), [Finish()](/api/Global/Units/Unit-Commands/UnitCommand#finish), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)






