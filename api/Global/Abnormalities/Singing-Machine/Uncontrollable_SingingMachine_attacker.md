---
uid: Global.Uncontrollable_SingingMachine_attacker
canonical_path: /api/Global/UncontrollableAction/UncontrollableSingingMachineattacker
---
# Class Uncontrollable_SingingMachine_attacker
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Uncontrollable_SingingMachine_attacker : UncontrollableAction
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [HierarchicalData](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/UncontrollableAction) → Uncontrollable_SingingMachine_attacker

## Constructors
### Uncontrollable_SingingMachine_attacker(WorkerModel, SingingMachine)
```csharp
public Uncontrollable_SingingMachine_attacker(WorkerModel model, SingingMachine singingMachine)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.WorkerModel` |  |
| `singingMachine` | `Global.SingingMachine` |  |

## Fields
### _deadBackHairReRenderer
```csharp
private SpriteRenderer _deadBackHairReRenderer
```

#### Field Value
**Type:** UnityEngine.SpriteRenderer

### _deadFrontHairReRenderer
```csharp
private SpriteRenderer _deadFrontHairReRenderer
```

#### Field Value
**Type:** UnityEngine.SpriteRenderer

### _killTarget
```csharp
private WorkerModel _killTarget
```

#### Field Value
**Type:** Global.WorkerModel

### _model
```csharp
private WorkerModel _model
```

#### Field Value
**Type:** Global.WorkerModel

### _singingMachine
```csharp
private SingingMachine _singingMachine
```

#### Field Value
**Type:** Global.SingingMachine

### _waitingTimer
```csharp
private Timer _waitingTimer
```

#### Field Value
**Type:** Global.Timer

### deadBackhairBoneName
```csharp
public const string deadBackhairBoneName = "bone_BACKHAIR_dead_Agent"
```

#### Field Value
**Type:** System.String

### deadFronthairBoneName
```csharp
public const string deadFronthairBoneName = "bone4bone_FRONTHAIR_dead_Agent"
```

#### Field Value
**Type:** System.String

### maxHpRatio
```csharp
private const float maxHpRatio = 1
```

#### Field Value
**Type:** System.Single

## Methods
### Execute()
```csharp
public override void Execute()
```

### GetNearWorkerEncounted()
```csharp
public List<WorkerModel> GetNearWorkerEncounted()
```

#### Returns
**Type:** System.Collections.Generic.List{WorkerModel}

### Init()
```csharp
public override void Init()
```

### MakeMovement()
```csharp
private void MakeMovement()
```

### OnClick()
```csharp
public override void OnClick()
```

### OnDie()
```csharp
public override void OnDie()
```

### OnStageEnd()
```csharp
public override void OnStageEnd()
```

### StopMovement()
```csharp
private void StopMovement()
```

## Inherited Members
[OnDestroy()](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#h-index), [InitialSetting()](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#initialsetting), [GetHierachicalName()](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#gethierachicalname), [SetHierarchicalIndex(int)](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#sethierarchicalindex-int), [Comparer(HierarchicalData)](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#comparer-hierarchicaldata), [isUpperHierarchy(HierarchicalData)](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#isupperhierarchy-hierarchicaldata), [Comparer(HierarchicalData, HierarchicalData)](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#comparer-hierarchicaldata-hierarchicaldata), [HierachicalIndex](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#hierachicalindex), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)







