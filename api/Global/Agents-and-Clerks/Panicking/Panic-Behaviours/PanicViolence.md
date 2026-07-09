---
uid: Global.PanicViolence
canonical_path: /api/Global/Misc/PanicViolence
---
# Class PanicViolence
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PanicViolence : PanicAction
```
> This section may have incomplete or incorrect information.
{.is-warning}


Panic behaviour for an [agent](/api/Global/Agents-and-Clerks/Agents/AgentModel) to indiscriminately attack employees around them.



## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [PanicAction](/api/Global/Agents-and-Clerks/Panicking/Panic-Behaviours/PanicAction) → PanicViolence

## Constructors
### PanicViolence(AgentModel)
```csharp
public PanicViolence(AgentModel actor)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.AgentModel` |  |

## Fields
### actor
```csharp
private AgentModel actor
```


#### Field Value
**Type:** Global.AgentModel

### suicideCooltime
```csharp
private const int suicideCooltime = 60
```


#### Field Value
**Type:** System.Int32

### suicideTimer
```csharp
private Timer suicideTimer
```


#### Field Value
**Type:** Global.Timer

### target
```csharp
private UnitModel target
```


#### Field Value
**Type:** Global.UnitModel

### unit
```csharp
private AgentUnit unit
```


#### Field Value
**Type:** Global.AgentUnit

## Methods
### Execute()
```csharp
public override void Execute()
```


### GetAttackSpeedMultiplier()
```csharp
public override float GetAttackSpeedMultiplier()
```


#### Returns
**Type:** System.Single

### Init()
```csharp
public override void Init()
```


## Inherited Members
[OnDie()](/api/Global/Agents-and-Clerks/Panicking/Panic-Behaviours/PanicAction#ondie), [PanicEnd()](/api/Global/Agents-and-Clerks/Panicking/Panic-Behaviours/PanicAction#panicend), [GetMovementMultiplier()](/api/Global/Agents-and-Clerks/Panicking/Panic-Behaviours/PanicAction#getmovementmultiplier), [GetDefenseMultiplier()](/api/Global/Agents-and-Clerks/Panicking/Panic-Behaviours/PanicAction#getdefensemultiplier), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)






