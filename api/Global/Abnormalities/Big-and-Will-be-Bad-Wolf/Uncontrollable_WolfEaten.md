---
uid: Global.Uncontrollable_WolfEaten
canonical_path: /api/Global/UncontrollableAction/UncontrollableWolfEaten
---
# Class Uncontrollable_WolfEaten
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Uncontrollable_WolfEaten : UncontrollableAction
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [HierarchicalData](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/UncontrollableAction) → Uncontrollable_WolfEaten

## Constructors
### Uncontrollable_WolfEaten(AgentModel, BigBadWolf)
```csharp
public Uncontrollable_WolfEaten(AgentModel agent, BigBadWolf wolf)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |
| `wolf` | `Global.BigBadWolf` |  |

## Fields
### agent
```csharp
public AgentModel agent
```

#### Field Value
**Type:** Global.AgentModel

### wolf
```csharp
private BigBadWolf wolf
```

#### Field Value
**Type:** Global.BigBadWolf

## Methods
### HideUnit()
```csharp
private void HideUnit()
```

### Init()
```csharp
public override void Init()
```

### OnDieByWolf()
```csharp
public void OnDieByWolf()
```

### OnRelease(bool)
```csharp
public void OnRelease(bool isInRoom)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `isInRoom` | `System.Boolean` |  |

## Inherited Members
[OnStageEnd()](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#h-index), [InitialSetting()](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#initialsetting), [GetHierachicalName()](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#gethierachicalname), [SetHierarchicalIndex(int)](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#sethierarchicalindex-int), [Comparer(HierarchicalData)](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#comparer-hierarchicaldata), [isUpperHierarchy(HierarchicalData)](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#isupperhierarchy-hierarchicaldata), [Comparer(HierarchicalData, HierarchicalData)](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#comparer-hierarchicaldata-hierarchicaldata), [HierachicalIndex](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#hierachicalindex), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)








