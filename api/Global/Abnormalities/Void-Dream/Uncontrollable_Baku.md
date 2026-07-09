---
uid: Global.Uncontrollable_Baku
canonical_path: /api/Global/UncontrollableAction/UncontrollableBaku
---
# Class Uncontrollable_Baku
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Uncontrollable_Baku : UncontrollableAction
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [HierarchicalData](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/UncontrollableAction) → Uncontrollable_Baku

## Constructors
### Uncontrollable_Baku(WorkerModel, Baku)
```csharp
public Uncontrollable_Baku(WorkerModel model, Baku script)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.WorkerModel` |  |
| `script` | `Global.Baku` |  |

## Fields
### _neededClicked
```csharp
private const int _neededClicked = 5
```

#### Field Value
**Type:** System.Int32

### _woundToBeAnnoyed
```csharp
private const float _woundToBeAnnoyed = 0.2
```

#### Field Value
**Type:** System.Single

### hp
```csharp
private float hp
```

#### Field Value
**Type:** System.Single

### model
```csharp
private WorkerModel model
```

#### Field Value
**Type:** Global.WorkerModel

### mp
```csharp
private float mp
```

#### Field Value
**Type:** System.Single

### remainClicked
```csharp
private int remainClicked
```

#### Field Value
**Type:** System.Int32

### script
```csharp
private Baku script
```

#### Field Value
**Type:** Global.Baku

### waked
```csharp
private bool waked
```

#### Field Value
**Type:** System.Boolean

## Methods
### Annoyed()
```csharp
private void Annoyed()
```

### CheckAnnoyed()
```csharp
public void CheckAnnoyed()
```

### Execute()
```csharp
public override void Execute()
```

### OnAnnoyed()
```csharp
public void OnAnnoyed()
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

### OnStageEnd()
```csharp
public override void OnStageEnd()
```

### WakeUp()
```csharp
private void WakeUp()
```

## Inherited Members
[Init()](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#h-index), [InitialSetting()](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#initialsetting), [GetHierachicalName()](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#gethierachicalname), [SetHierarchicalIndex(int)](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#sethierarchicalindex-int), [Comparer(HierarchicalData)](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#comparer-hierarchicaldata), [isUpperHierarchy(HierarchicalData)](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#isupperhierarchy-hierarchicaldata), [Comparer(HierarchicalData, HierarchicalData)](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#comparer-hierarchicaldata-hierarchicaldata), [HierachicalIndex](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#hierachicalindex), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)







