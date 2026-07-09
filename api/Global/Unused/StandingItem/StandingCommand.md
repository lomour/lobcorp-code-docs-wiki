---
uid: Global.StandingCommand
canonical_path: /api/Global/Misc/StandingCommand
---
# Class StandingCommand
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class StandingCommand : UnitCommand
```
> This section may have incomplete or incorrect information.
{.is-warning}

> This class is not used.
{.is-info}





## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitCommand](/api/Global/Units/Unit-Commands/UnitCommand) → StandingCommand

## Derived
[MoveItemCommand](/api/Global/Unused/Worker-Commands/MoveItemCommand)

## Constructors
### StandingCommand()
```csharp
public StandingCommand()
```

## Fields
### endCmd
```csharp
private StandingCommand.OnCommandEnd endCmd
```

#### Field Value
**Type:** Global.StandingCommand.OnCommandEnd

## Methods
### Finish()
```csharp
public virtual void Finish()
```

### MoveCommand(MapNode)
```csharp
public static MoveItemCommand MoveCommand(MapNode mapNode)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `mapNode` | `Global.MapNode` |  |

#### Returns
**Type:** Global.MoveItemCommand

### MoveCommand(MapNode, OnCommandEnd)
```csharp
public static MoveItemCommand MoveCommand(MapNode mapNode, StandingCommand.OnCommandEnd end)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `mapNode` | `Global.MapNode` |  |
| `end` | `Global.StandingCommand.OnCommandEnd` |  |

#### Returns
**Type:** Global.MoveItemCommand

### MoveCommand(MovableObjectNode)
```csharp
public static MoveItemCommand MoveCommand(MovableObjectNode movable)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `movable` | `Global.MovableObjectNode` |  |

#### Returns
**Type:** Global.MoveItemCommand

### MoveCommand(MovableObjectNode, OnCommandEnd)
```csharp
public static MoveItemCommand MoveCommand(MovableObjectNode movable, StandingCommand.OnCommandEnd end)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `movable` | `Global.MovableObjectNode` |  |
| `end` | `Global.StandingCommand.OnCommandEnd` |  |

#### Returns
**Type:** Global.MoveItemCommand

### SetEndCommand(OnCommandEnd)
```csharp
public virtual void SetEndCommand(StandingCommand.OnCommandEnd cmd)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `cmd` | `Global.StandingCommand.OnCommandEnd` |  |

## Inherited Members
[actor](/api/Global/Units/Unit-Commands/UnitCommand#actor), [isFinished](/api/Global/Units/Unit-Commands/UnitCommand#isfinished), [isRemoved](/api/Global/Units/Unit-Commands/UnitCommand#isremoved), [OnInit(WorkerModel)](/api/Global/Units/Unit-Commands/UnitCommand#oninit-workermodel), [OnInit(UnitModel)](/api/Global/Units/Unit-Commands/UnitCommand#oninit-unitmodel), [OnInit(StandingItemModel)](/api/Global/Units/Unit-Commands/UnitCommand#oninit-standingitemmodel), [OnStart()](/api/Global/Units/Unit-Commands/UnitCommand#onstart), [Execute()](/api/Global/Units/Unit-Commands/UnitCommand#execute), [OnStop()](/api/Global/Units/Unit-Commands/UnitCommand#onstop), [OnDestroy()](/api/Global/Units/Unit-Commands/UnitCommand#ondestroy), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)






