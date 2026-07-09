---
uid: Global.Uncontrollable_Yggdrasil
canonical_path: /api/Global/UncontrollableAction/UncontrollableYggdrasil
---
# Class Uncontrollable_Yggdrasil
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Uncontrollable_Yggdrasil : UncontrollableAction
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [HierarchicalData](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/UncontrollableAction) → Uncontrollable_Yggdrasil

## Constructors
### Uncontrollable_Yggdrasil(WorkerModel, Yggdrasil)
```csharp
public Uncontrollable_Yggdrasil(WorkerModel model, Yggdrasil script)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.WorkerModel` |  |
| `script` | `Global.Yggdrasil` |  |

## Fields
### _neededClicked
```csharp
private const int _neededClicked = 5
```

#### Field Value
**Type:** System.Int32

### model
```csharp
private WorkerModel model
```

#### Field Value
**Type:** Global.WorkerModel

### remainClicked
```csharp
private int remainClicked
```

#### Field Value
**Type:** System.Int32

### script
```csharp
private Yggdrasil script
```

#### Field Value
**Type:** Global.Yggdrasil

### slowTimer
```csharp
private float slowTimer
```

#### Field Value
**Type:** System.Single

### waitTimer
```csharp
private float waitTimer
```

#### Field Value
**Type:** System.Single

### wakeUp
```csharp
private bool wakeUp
```

#### Field Value
**Type:** System.Boolean

### wakeUpTimer
```csharp
private float wakeUpTimer
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

### OnClick()
```csharp
public override void OnClick()
```

### OnDestroy()
```csharp
public override void OnDestroy()
```

### OnDie()
```csharp
public override void OnDie()
```

### WakeUp()
```csharp
private void WakeUp()
```

## Inherited Members
[OnStageEnd()](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#h-index), [InitialSetting()](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#initialsetting), [GetHierachicalName()](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#gethierachicalname), [SetHierarchicalIndex(int)](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#sethierarchicalindex-int), [Comparer(HierarchicalData)](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#comparer-hierarchicaldata), [isUpperHierarchy(HierarchicalData)](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#isupperhierarchy-hierarchicaldata), [Comparer(HierarchicalData, HierarchicalData)](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#comparer-hierarchicaldata-hierarchicaldata), [HierachicalIndex](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#hierachicalindex), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)







