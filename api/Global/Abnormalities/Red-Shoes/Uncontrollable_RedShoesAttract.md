---
uid: Global.Uncontrollable_RedShoesAttract
canonical_path: /api/Global/UncontrollableAction/UncontrollableRedShoesAttract
---
# Class Uncontrollable_RedShoesAttract
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Uncontrollable_RedShoesAttract : UncontrollableAction
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [HierarchicalData](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/UncontrollableAction) → Uncontrollable_RedShoesAttract

## Constructors
### Uncontrollable_RedShoesAttract(WorkerModel, RedShoesSkill)
```csharp
public Uncontrollable_RedShoesAttract(WorkerModel model, RedShoesSkill redShoesSkill)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.WorkerModel` |  |
| `redShoesSkill` | `Global.RedShoesSkill` |  |

## Fields
### model
```csharp
private WorkerModel model
```

#### Field Value
**Type:** Global.WorkerModel

### redShoesSkill
```csharp
private RedShoesSkill redShoesSkill
```

#### Field Value
**Type:** Global.RedShoesSkill

### remainClicked
```csharp
private int remainClicked
```

#### Field Value
**Type:** System.Int32

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

### IsPreferredTouch()
```csharp
public override bool IsPreferredTouch()
```

#### Returns
**Type:** System.Boolean

### OnClick()
```csharp
public override void OnClick()
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
[Init()](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#h-index), [InitialSetting()](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#initialsetting), [GetHierachicalName()](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#gethierachicalname), [SetHierarchicalIndex(int)](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#sethierarchicalindex-int), [Comparer(HierarchicalData)](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#comparer-hierarchicaldata), [isUpperHierarchy(HierarchicalData)](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#isupperhierarchy-hierarchicaldata), [Comparer(HierarchicalData, HierarchicalData)](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#comparer-hierarchicaldata-hierarchicaldata), [HierachicalIndex](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#hierachicalindex), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)







