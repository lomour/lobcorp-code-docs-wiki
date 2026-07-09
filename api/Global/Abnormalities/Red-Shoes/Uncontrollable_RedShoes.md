---
uid: Global.Uncontrollable_RedShoes
canonical_path: /api/Global/UncontrollableAction/UncontrollableRedShoes
---
# Class Uncontrollable_RedShoes
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Uncontrollable_RedShoes : UncontrollableAction
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [HierarchicalData](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/UncontrollableAction) → Uncontrollable_RedShoes

## Constructors
### Uncontrollable_RedShoes(WorkerModel, RedShoesSkill, int)
```csharp
public Uncontrollable_RedShoes(WorkerModel model, RedShoesSkill redShoesSkill, int startType)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.WorkerModel` |  |
| `redShoesSkill` | `Global.RedShoesSkill` |  |
| `startType` | `System.Int32` |  |

## Fields
### _curTarget
```csharp
private UnitModel _curTarget
```

#### Field Value
**Type:** Global.UnitModel

### _killTarget
```csharp
private WorkerModel _killTarget
```

#### Field Value
**Type:** Global.WorkerModel

### deadSceneRange
```csharp
private const float deadSceneRange = 0.2
```

#### Field Value
**Type:** System.Single

### dying
```csharp
private bool dying
```

#### Field Value
**Type:** System.Boolean

### encounteredWorker
```csharp
private List<WorkerModel> encounteredWorker
```

#### Field Value
**Type:** System.Collections.Generic.List{WorkerModel}

### isPursing
```csharp
public bool isPursing
```

#### Field Value
**Type:** System.Boolean

### killing
```csharp
private bool killing
```

#### Field Value
**Type:** System.Boolean

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

### startWaitTimer
```csharp
private float startWaitTimer
```

#### Field Value
**Type:** System.Single

### timer
```csharp
public CreatureBase.CreatureTimer timer
```

#### Field Value
**Type:** Global.CreatureBase.CreatureTimer

### waitTimer
```csharp
private float waitTimer
```

#### Field Value
**Type:** System.Single

## Methods
### CheckNearWorker()
```csharp
private void CheckNearWorker()
```

### Execute()
```csharp
public override void Execute()
```

### Init()
```csharp
public override void Init()
```

### Killing()
```csharp
private void Killing()
```

### OnAnimCalled(int)
```csharp
public void OnAnimCalled(int i)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### OnClick()
```csharp
public override void OnClick()
```

### OnDie()
```csharp
public override void OnDie()
```

### OnKill(WorkerModel)
```csharp
public void OnKill(WorkerModel target)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |

### OnStageEnd()
```csharp
public override void OnStageEnd()
```

### StartSettingPos()
```csharp
public void StartSettingPos()
```

## Inherited Members
[OnDestroy()](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#h-index), [InitialSetting()](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#initialsetting), [GetHierachicalName()](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#gethierachicalname), [SetHierarchicalIndex(int)](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#sethierarchicalindex-int), [Comparer(HierarchicalData)](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#comparer-hierarchicaldata), [isUpperHierarchy(HierarchicalData)](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#isupperhierarchy-hierarchicaldata), [Comparer(HierarchicalData, HierarchicalData)](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#comparer-hierarchicaldata-hierarchicaldata), [HierachicalIndex](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#hierachicalindex), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)







