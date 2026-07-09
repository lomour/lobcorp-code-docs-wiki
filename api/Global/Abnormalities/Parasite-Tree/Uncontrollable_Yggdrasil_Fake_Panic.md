---
uid: Global.Uncontrollable_Yggdrasil_Fake_Panic
canonical_path: /api/Global/UncontrollableAction/UncontrollableYggdrasilFakePanic
---
# Class Uncontrollable_Yggdrasil_Fake_Panic
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Uncontrollable_Yggdrasil_Fake_Panic : UncontrollableAction
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [HierarchicalData](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/UncontrollableAction) → Uncontrollable_Yggdrasil_Fake_Panic

## Constructors
### Uncontrollable_Yggdrasil_Fake_Panic(WorkerModel, Yggdrasil)
```csharp
public Uncontrollable_Yggdrasil_Fake_Panic(WorkerModel worker, Yggdrasil script)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |
| `script` | `Global.Yggdrasil` |  |

## Fields
### script
```csharp
private Yggdrasil script
```

#### Field Value
**Type:** Global.Yggdrasil

### suicideTimeMax
```csharp
private float suicideTimeMax
```

#### Field Value
**Type:** System.Single

### suicideTimeMin
```csharp
private float suicideTimeMin
```

#### Field Value
**Type:** System.Single

### suicideTimer
```csharp
private Timer suicideTimer
```

#### Field Value
**Type:** Global.Timer

### worker
```csharp
private WorkerModel worker
```

#### Field Value
**Type:** Global.WorkerModel

## Properties
### SuicideTime
```csharp
private float SuicideTime { get; }
```

#### Property Value
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

### OnDie()
```csharp
public override void OnDie()
```

## Inherited Members
[OnStageEnd()](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#h-index), [InitialSetting()](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#initialsetting), [GetHierachicalName()](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#gethierachicalname), [SetHierarchicalIndex(int)](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#sethierarchicalindex-int), [Comparer(HierarchicalData)](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#comparer-hierarchicaldata), [isUpperHierarchy(HierarchicalData)](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#isupperhierarchy-hierarchicaldata), [Comparer(HierarchicalData, HierarchicalData)](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#comparer-hierarchicaldata-hierarchicaldata), [HierachicalIndex](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#hierachicalindex), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)







