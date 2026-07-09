---
uid: Global.PanicReady
canonical_path: /api/Global/Misc/PanicReady
---
# Class PanicReady
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PanicReady : PanicAction
```
> This section may have incomplete or incorrect information.
{.is-warning}


Panic behaviour for an [agent](/api/Global/Agents-and-Clerks/Agents/AgentModel) getting ready to panic.
Changes the face, instructs the agent to leave a containment unit if applicable, then brings out their weapon.

Ends by telling the agent to choose a panic behaviour. (AgentModel.PanicReadyComplete())


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [PanicAction](/api/Global/Agents-and-Clerks/Panicking/Panic-Behaviours/PanicAction) → PanicReady

## Derived
[BlackLovePanicReady](/api/Global/Abnormalities/Army-in-Black/BlackLovePanicReady)

## Constructors
### PanicReady(WorkerModel)
```csharp
public PanicReady(WorkerModel target)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |

## Fields
### actor
```csharp
protected WorkerModel actor
```


#### Field Value
**Type:** Global.WorkerModel

### elapsedTime
```csharp
protected float elapsedTime
```


#### Field Value
**Type:** System.Single

### waitTime
```csharp
protected float waitTime
```


#### Field Value
**Type:** System.Single

## Methods
### Execute()
```csharp
public override void Execute()
```


### Init()
```csharp
public override void Init()
```


### PanicEnd()
```csharp
public override void PanicEnd()
```


### StartPanicAction()
```csharp
public void StartPanicAction()
```


## Inherited Members
[OnDie()](/api/Global/Agents-and-Clerks/Panicking/Panic-Behaviours/PanicAction#ondie), [GetAttackSpeedMultiplier()](/api/Global/Agents-and-Clerks/Panicking/Panic-Behaviours/PanicAction#getattackspeedmultiplier), [GetMovementMultiplier()](/api/Global/Agents-and-Clerks/Panicking/Panic-Behaviours/PanicAction#getmovementmultiplier), [GetDefenseMultiplier()](/api/Global/Agents-and-Clerks/Panicking/Panic-Behaviours/PanicAction#getdefensemultiplier), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)






