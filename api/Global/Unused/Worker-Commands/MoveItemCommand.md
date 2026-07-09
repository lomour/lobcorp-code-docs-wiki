---
uid: Global.MoveItemCommand
canonical_path: /api/Global/Standing/MoveItemCommand
---
# Class MoveItemCommand
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class MoveItemCommand : StandingCommand
```
> This section may have incomplete or incorrect information.
{.is-warning}

> This class is not used.
{.is-info}




## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitCommand](/api/Global/Unused/StandingItem/StandingCommand) → MoveItemCommand

## Constructors
### MoveItemCommand(MapNode)
```csharp
public MoveItemCommand(MapNode targetNode)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `targetNode` | `Global.MapNode` |  |

### MoveItemCommand(MovableObjectNode)
```csharp
public MoveItemCommand(MovableObjectNode targetMovable)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `targetMovable` | `Global.MovableObjectNode` |  |

## Fields
### targetMovable
```csharp
public MovableObjectNode targetMovable
```


#### Field Value
**Type:** Global.MovableObjectNode

### targetNode
```csharp
public MapNode targetNode
```


#### Field Value
**Type:** Global.MapNode

## Methods
### Execute()
```csharp
public override void Execute()
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
[endCmd](/api/Global/Units/Unit-Commands/UnitCommand#actor), [isFinished](/api/Global/Units/Unit-Commands/UnitCommand#isfinished), [isRemoved](/api/Global/Units/Unit-Commands/UnitCommand#isremoved), [OnInit(WorkerModel)](/api/Global/Units/Unit-Commands/UnitCommand#oninit-workermodel), [OnInit(UnitModel)](/api/Global/Units/Unit-Commands/UnitCommand#oninit-unitmodel), [OnInit(StandingItemModel)](/api/Global/Units/Unit-Commands/UnitCommand#oninit-standingitemmodel), [OnDestroy()](/api/Global/Units/Unit-Commands/UnitCommand#ondestroy), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)






