---
uid: Global.HordeOfBugs
canonical_path: /api/Global/Misc/HordeOfBugs
---
# Class HordeOfBugs
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class HordeOfBugs : RandomEventBase
```
> This section may have incomplete or incorrect information.
{.is-warning}

> This class is not used.
{.is-info}


Unused random event.




## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [RandomEventBase](/api/Global/Unused/Random-Events/RandomEventBase) → HordeOfBugs

## Constructors
### HordeOfBugs()
```csharp
public HordeOfBugs()
```

## Fields
### bugs
```csharp
private List<TastyBug> bugs
```


#### Field Value
**Type:** System.Collections.Generic.List{TastyBug}

### daughterBugs
```csharp
private List<DaughterBug> daughterBugs
```


#### Field Value
**Type:** System.Collections.Generic.List{DaughterBug}

### daughterBugSrc
```csharp
public const string daughterBugSrc = "StandingItem/DaughterBugAnim"
```


#### Field Value
**Type:** System.String

### daughterId
```csharp
public const long daughterId = 10043
```


#### Field Value
**Type:** System.Int64

### daughterMax
```csharp
public const int daughterMax = 100
```


#### Field Value
**Type:** System.Int32

### DelayEnableMax
```csharp
public const float DelayEnableMax = 3
```


#### Field Value
**Type:** System.Single

### DelayEnableMin
```csharp
public const float DelayEnableMin = 1
```


#### Field Value
**Type:** System.Single

### grandBug
```csharp
private GrandmaBug grandBug
```


#### Field Value
**Type:** Global.GrandmaBug

### grandBugSrc
```csharp
public const string grandBugSrc = "StandingItem/TastyBugs/GrandBug"
```


#### Field Value
**Type:** System.String

### grandmaId
```csharp
public const long grandmaId = 10041
```


#### Field Value
**Type:** System.Int64

### hordeBgm
```csharp
public const string hordeBgm = ""
```


#### Field Value
**Type:** System.String

### motherBugs
```csharp
private List<MotherBug> motherBugs
```


#### Field Value
**Type:** System.Collections.Generic.List{MotherBug}

### motherBugSrc
```csharp
public const string motherBugSrc = "StandingItem/HordeOfBugs/MotherBug"
```


#### Field Value
**Type:** System.String

### motherId
```csharp
public const long motherId = 10042
```


#### Field Value
**Type:** System.Int64

### motherMax
```csharp
public const int motherMax = 20
```


#### Field Value
**Type:** System.Int32

### numOfDaughters
```csharp
public int numOfDaughters
```


#### Field Value
**Type:** System.Int32

### numOfMothers
```csharp
public int numOfMothers
```


#### Field Value
**Type:** System.Int32

### sefiraPassages
```csharp
public List<PassageObjectModel> sefiraPassages
```


#### Field Value
**Type:** System.Collections.Generic.List{PassageObjectModel}

## Methods
### EnableBugs(BugType, MapNode, params UnitDirection[])
```csharp
public void EnableBugs(HordeOfBugsScript.BugType type, MapNode node, params UnitDirection[] direction)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.HordeOfBugsScript.BugType` |  |
| `node` | `Global.MapNode` |  |
| `direction` | `Global.UnitDirection[]` |  |

### GetOtherpassage(PassageObjectModel)
```csharp
public PassageObjectModel GetOtherpassage(PassageObjectModel current)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `current` | `Global.PassageObjectModel` |  |

#### Returns
**Type:** Global.PassageObjectModel

### GetRandomTargetPassage()
```csharp
public PassageObjectModel GetRandomTargetPassage()
```


#### Returns
**Type:** Global.PassageObjectModel

### LoadBug(string, long, out HordeOfBugsScript)
```csharp
public GameObject LoadBug(string src, long metaId, out HordeOfBugsScript script)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |
| `metaId` | `System.Int64` |  |
| `script` | `Global.HordeOfBugsScript` |  |

#### Returns
**Type:** UnityEngine.GameObject

### ManualDisable()
```csharp
public override void ManualDisable()
```


### OnDisable()
```csharp
public override void OnDisable()
```


### OnEnable()
```csharp
public override void OnEnable()
```


### OnFixedUpdate()
```csharp
public override void OnFixedUpdate()
```


### OnInit()
```csharp
public override void OnInit()
```


### SetTime(float)
```csharp
public void SetTime(float time)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `time` | `System.Single` |  |

## Inherited Members
[rootObjectSrc](/api/Global/Unused/Random-Events/RandomEventBase#rootobjectsrc), [rootObjectId](/api/Global/Unused/Random-Events/RandomEventBase#rootobjectid), [type](/api/Global/Unused/Random-Events/RandomEventBase#type), [rank](/api/Global/Unused/Random-Events/RandomEventBase#rank), [metaInfo](/api/Global/Unused/Random-Events/RandomEventBase#metainfo), [rootGameObject](/api/Global/Unused/Random-Events/RandomEventBase#rootgameobject), [rootStanding](/api/Global/Unused/Random-Events/RandomEventBase#rootstanding), [enableCheckConditions](/api/Global/Unused/Random-Events/RandomEventBase#enablecheckconditions), [instanceId](/api/Global/Unused/Random-Events/RandomEventBase#instanceid), [_isEnabled](/api/Global/Unused/Random-Events/RandomEventBase#isenabled), [GenerateCondition()](/api/Global/Unused/Random-Events/RandomEventBase#generatecondition), [GenerateCondition(ConditionInfo, ref List<int>)](/api/Global/Unused/Random-Events/RandomEventBase#generatecondition-conditioninfo-ref-list-int), [OnDestroy()](/api/Global/Unused/Random-Events/RandomEventBase#ondestroy), [OnEnd()](/api/Global/Unused/Random-Events/RandomEventBase#onend), [IsDuplicatable()](/api/Global/Unused/Random-Events/RandomEventBase#isduplicatable), [CheckEquivalent(string)](/api/Global/Unused/Random-Events/RandomEventBase#checkequivalent-string), [CheckCondition()](/api/Global/Unused/Random-Events/RandomEventBase#checkcondition), [ManualDisable(string)](/api/Global/Unused/Random-Events/RandomEventBase#manualdisable-string), [GenerateTypo(TypoType, string)](/api/Global/Unused/Random-Events/RandomEventBase#generatetypo-typotype-string), [GenerateTypo(TypoType)](/api/Global/Unused/Random-Events/RandomEventBase#generatetypo-typotype), [GenerateTypo(string)](/api/Global/Unused/Random-Events/RandomEventBase#generatetypo-string), [OnUpdate()](/api/Global/Unused/Random-Events/RandomEventBase#onupdate), [GetCondition(string)](/api/Global/Unused/Random-Events/RandomEventBase#getcondition-string), [MakeRootObject()](/api/Global/Unused/Random-Events/RandomEventBase#makerootobject), [GetTimerCondition()](/api/Global/Unused/Random-Events/RandomEventBase#gettimercondition), [SetTimerConditionTime(float)](/api/Global/Unused/Random-Events/RandomEventBase#settimerconditiontime-float), [RootTransform](/api/Global/Unused/Random-Events/RandomEventBase#roottransform), [HasRootObject](/api/Global/Unused/Random-Events/RandomEventBase#hasrootobject), [MetaDataId](/api/Global/Unused/Random-Events/RandomEventBase#metadataid), [IsEnabled](/api/Global/Unused/Random-Events/RandomEventBase#isenabled), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)






