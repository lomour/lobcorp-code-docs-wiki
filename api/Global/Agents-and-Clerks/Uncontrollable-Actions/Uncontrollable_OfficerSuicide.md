---
uid: Global.Uncontrollable_OfficerSuicide
canonical_path: /api/Global/UncontrollableAction/UncontrollableOfficerSuicide
---
# Class Uncontrollable_OfficerSuicide
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Uncontrollable_OfficerSuicide : UncontrollableAction
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [HierarchicalData](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/UncontrollableAction) → Uncontrollable_OfficerSuicide

## Constructors
### Uncontrollable_OfficerSuicide(OfficerModel)
```csharp
public Uncontrollable_OfficerSuicide(OfficerModel om)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `om` | `Global.OfficerModel` |  |

## Fields
### _elapsedTime
```csharp
private float _elapsedTime
```

#### Field Value
**Type:** System.Single

### _suicideTime
```csharp
private float _suicideTime
```

#### Field Value
**Type:** System.Single

### actor
```csharp
private OfficerModel actor
```

#### Field Value
**Type:** Global.OfficerModel

## Methods
### Execute()
```csharp
public override void Execute()
```

### GunFire()
```csharp
private void GunFire()
```

### Init()
```csharp
public override void Init()
```

### OnOfficerAnimEvent(int)
```csharp
public void OnOfficerAnimEvent(int i)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

## Inherited Members
[OnStageEnd()](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#h-index), [InitialSetting()](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#initialsetting), [GetHierachicalName()](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#gethierachicalname), [SetHierarchicalIndex(int)](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#sethierarchicalindex-int), [Comparer(HierarchicalData)](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#comparer-hierarchicaldata), [isUpperHierarchy(HierarchicalData)](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#isupperhierarchy-hierarchicaldata), [Comparer(HierarchicalData, HierarchicalData)](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#comparer-hierarchicaldata-hierarchicaldata), [HierachicalIndex](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#hierachicalindex), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)







