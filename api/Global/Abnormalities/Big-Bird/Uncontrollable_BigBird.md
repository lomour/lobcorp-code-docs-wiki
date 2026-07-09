---
uid: Global.Uncontrollable_BigBird
canonical_path: /api/Global/UncontrollableAction/UncontrollableBigBird
---
# Class Uncontrollable_BigBird
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Uncontrollable_BigBird : UncontrollableAction
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [HierarchicalData](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/UncontrollableAction) → Uncontrollable_BigBird

## Constructors
### Uncontrollable_BigBird(WorkerModel, BigBird)
```csharp
public Uncontrollable_BigBird(WorkerModel model, BigBird script)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.WorkerModel` |  |
| `script` | `Global.BigBird` |  |

### Uncontrollable_BigBird(WorkerModel, BossBird)
```csharp
public Uncontrollable_BigBird(WorkerModel model, BossBird bossScript)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.WorkerModel` |  |
| `bossScript` | `Global.BossBird` |  |

## Fields
### bossEffect
```csharp
private GameObject bossEffect
```

#### Field Value
**Type:** UnityEngine.GameObject

### bossScript
```csharp
private BossBird bossScript
```

#### Field Value
**Type:** Global.BossBird

### deadSceneRange
```csharp
private const float deadSceneRange = 2.5
```

#### Field Value
**Type:** System.Single

### model
```csharp
private WorkerModel model
```

#### Field Value
**Type:** Global.WorkerModel

### script
```csharp
private BigBird script
```

#### Field Value
**Type:** Global.BigBird

## Methods
### AttachBossEffect()
```csharp
private GameObject AttachBossEffect()
```

#### Returns
**Type:** UnityEngine.GameObject

### Execute()
```csharp
public override void Execute()
```

### OnDestroy()
```csharp
public override void OnDestroy()
```

### OnDie()
```csharp
public override void OnDie()
```

## Inherited Members
[Init()](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#h-index), [InitialSetting()](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#initialsetting), [GetHierachicalName()](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#gethierachicalname), [SetHierarchicalIndex(int)](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#sethierarchicalindex-int), [Comparer(HierarchicalData)](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#comparer-hierarchicaldata), [isUpperHierarchy(HierarchicalData)](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#isupperhierarchy-hierarchicaldata), [Comparer(HierarchicalData, HierarchicalData)](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#comparer-hierarchicaldata-hierarchicaldata), [HierachicalIndex](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#hierachicalindex), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)








