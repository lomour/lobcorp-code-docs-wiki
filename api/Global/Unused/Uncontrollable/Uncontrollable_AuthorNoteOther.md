---
uid: Global.Uncontrollable_AuthorNoteOther
canonical_path: /api/Global/UncontrollableAction/UncontrollableAuthorNoteOther
---
# Class Uncontrollable_AuthorNoteOther
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Uncontrollable_AuthorNoteOther : UncontrollableAction
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [HierarchicalData](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/UncontrollableAction) → Uncontrollable_AuthorNoteOther

## Constructors
### Uncontrollable_AuthorNoteOther(WorkerModel, AuthorNote, int)
```csharp
public Uncontrollable_AuthorNoteOther(WorkerModel model, AuthorNote note, int spriteId)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.WorkerModel` |  |
| `note` | `Global.AuthorNote` |  |
| `spriteId` | `System.Int32` |  |

## Fields
### balloon
```csharp
private AuthorNoteWorkerBalloon balloon
```

#### Field Value
**Type:** Global.AuthorNoteWorkerBalloon

### effectObject
```csharp
private GameObject effectObject
```

#### Field Value
**Type:** UnityEngine.GameObject

### faceDir
```csharp
public const string faceDir = "Sprites/Agent/OtherFace/Sacrifice/face_sacrifice_"
```

#### Field Value
**Type:** System.String

### faceList
```csharp
public int[] faceList
```

#### Field Value
**Type:** System.Int32[]

### model
```csharp
private WorkerModel model
```

#### Field Value
**Type:** Global.WorkerModel

### note
```csharp
private AuthorNote note
```

#### Field Value
**Type:** Global.AuthorNote

### spriteId
```csharp
public int spriteId
```

#### Field Value
**Type:** System.Int32

## Methods
### Execute()
```csharp
public override void Execute()
```

### Init()
```csharp
public override void Init()
```

### OnDestroy()
```csharp
public override void OnDestroy()
```

### OnDie()
```csharp
public override void OnDie()
```

### RemoveBalloon()
```csharp
private void RemoveBalloon()
```

## Inherited Members
[OnStageEnd()](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#h-index), [InitialSetting()](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#initialsetting), [GetHierachicalName()](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#gethierachicalname), [SetHierarchicalIndex(int)](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#sethierarchicalindex-int), [Comparer(HierarchicalData)](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#comparer-hierarchicaldata), [isUpperHierarchy(HierarchicalData)](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#isupperhierarchy-hierarchicaldata), [Comparer(HierarchicalData, HierarchicalData)](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#comparer-hierarchicaldata-hierarchicaldata), [HierachicalIndex](/api/Global/Agents-and-Clerks/Uncontrollable-Actions/Hierarchical-Data/HierarchicalData#hierachicalindex), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)






