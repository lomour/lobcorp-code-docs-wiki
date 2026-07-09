---
uid: Global.Uncontrollable_Censored
canonical_path: /api/Global/UncontrollableAction/UncontrollableCensored
---
# Class Uncontrollable_Censored
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Uncontrollable_Censored : UncontrollableAction, IObserver
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [HierarchicalData](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/UncontrollableAction) → Uncontrollable_Censored

## Implements
[IObserver](/api/Global/Notices/IObserver)

## Constructors
### Uncontrollable_Censored(WorkerModel, Censored)
```csharp
public Uncontrollable_Censored(WorkerModel worker, Censored script)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |
| `script` | `Global.Censored` |  |

## Fields
### arrived
```csharp
private bool arrived
```

#### Field Value
**Type:** System.Boolean

### init
```csharp
private bool init
```

#### Field Value
**Type:** System.Boolean

### model
```csharp
private WorkerModel model
```

#### Field Value
**Type:** Global.WorkerModel

### script
```csharp
private Censored script
```

#### Field Value
**Type:** Global.Censored

### waitTime
```csharp
private float waitTime
```

#### Field Value
**Type:** System.Single

### workSpace
```csharp
private MapNode workSpace
```

#### Field Value
**Type:** Global.MapNode

## Methods
### AfterInit()
```csharp
private void AfterInit()
```

### Destroy()
```csharp
private void Destroy()
```

### Execute()
```csharp
public override void Execute()
```

### Init()
```csharp
public override void Init()
```

### Move()
```csharp
private void Move()
```

### OnArrived()
```csharp
public void OnArrived()
```

### OnDie()
```csharp
public override void OnDie()
```

### OnNotice(string, params object[])
```csharp
public void OnNotice(string notice, params object[] param)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `notice` | `System.String` |  |
| `param` | `System.Object[]` |  |

### OnStageEnd()
```csharp
public override void OnStageEnd()
```

### Update()
```csharp
private void Update()
```

## Inherited Members
[OnDestroy()](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#h-index), [InitialSetting()](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#initialsetting), [GetHierachicalName()](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#gethierachicalname), [SetHierarchicalIndex(int)](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#sethierarchicalindex-int), [Comparer(HierarchicalData)](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#comparer-hierarchicaldata), [isUpperHierarchy(HierarchicalData)](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#isupperhierarchy-hierarchicaldata), [Comparer(HierarchicalData, HierarchicalData)](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#comparer-hierarchicaldata-hierarchicaldata), [HierachicalIndex](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#hierachicalindex), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)








