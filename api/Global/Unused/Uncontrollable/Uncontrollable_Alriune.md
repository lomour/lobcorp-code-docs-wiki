---
uid: Global.Uncontrollable_Alriune
canonical_path: /api/Global/UncontrollableAction/UncontrollableAlriune
---
# Class Uncontrollable_Alriune
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Uncontrollable_Alriune : UncontrollableAction
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [HierarchicalData](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/UncontrollableAction) → Uncontrollable_Alriune

## Constructors
### Uncontrollable_Alriune(WorkerModel, Alriune)
```csharp
public Uncontrollable_Alriune(WorkerModel model, Alriune alriune)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.WorkerModel` |  |
| `alriune` | `Global.Alriune` |  |

## Fields
### alriune
```csharp
private Alriune alriune
```

#### Field Value
**Type:** Global.Alriune

### animSrc
```csharp
private const string animSrc = "Agent/Dead/AlriuneWorkerDead"
```

#### Field Value
**Type:** System.String

### clickCounter
```csharp
private int clickCounter
```

#### Field Value
**Type:** System.Int32

### curtainAnim
```csharp
private const string curtainAnim = "Effect/Creature/Alriune/AlriuneCurtain"
```

#### Field Value
**Type:** System.String

### curtainAnimator
```csharp
private Animator curtainAnimator
```

#### Field Value
**Type:** UnityEngine.Animator

### deathTime
```csharp
private const float deathTime = 3
```

#### Field Value
**Type:** System.Single

### deathTimer
```csharp
private Timer deathTimer
```

#### Field Value
**Type:** Global.Timer

### model
```csharp
private WorkerModel model
```

#### Field Value
**Type:** Global.WorkerModel

### wakeUpTimer
```csharp
private Timer wakeUpTimer
```

#### Field Value
**Type:** Global.Timer

## Methods
### ClickEffect(Vector3)
```csharp
public void ClickEffect(Vector3 pos)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `pos` | `UnityEngine.Vector3` |  |

### ClickTest()
```csharp
private void ClickTest()
```

### Execute()
```csharp
public override void Execute()
```

### Init()
```csharp
public override void Init()
```

### IsPreferredTouch()
```csharp
public override bool IsPreferredTouch()
```

#### Returns
**Type:** System.Boolean

### OnDie()
```csharp
public override void OnDie()
```

## Inherited Members
[OnStageEnd()](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#h-index), [InitialSetting()](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#initialsetting), [GetHierachicalName()](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#gethierachicalname), [SetHierarchicalIndex(int)](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#sethierarchicalindex-int), [Comparer(HierarchicalData)](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#comparer-hierarchicaldata), [isUpperHierarchy(HierarchicalData)](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#isupperhierarchy-hierarchicaldata), [Comparer(HierarchicalData, HierarchicalData)](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#comparer-hierarchicaldata-hierarchicaldata), [HierachicalIndex](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#hierachicalindex), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)






