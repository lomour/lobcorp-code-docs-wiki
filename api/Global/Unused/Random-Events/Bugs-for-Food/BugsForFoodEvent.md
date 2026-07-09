---
uid: Global.BugsForFoodEvent
canonical_path: /api/Global/Event/BugsForFoodEvent
---
# Class BugsForFoodEvent
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BugsForFoodEvent : RandomEventBase
```
> This section may have incomplete or incorrect information.
{.is-warning}

> This class is not used.
{.is-info}

Old version of amber ordeal?



## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [RandomEventBase](/api/Global/Unused/Random-Events/RandomEventBase) → BugsForFoodEvent

## Constructors
### BugsForFoodEvent()
```csharp
public BugsForFoodEvent()
```

## Fields
### bugBgm
```csharp
public const string bugBgm = ""
```


#### Field Value
**Type:** System.String

### bugID
```csharp
public const long bugID = 1003
```


#### Field Value
**Type:** System.Int64

### bugs
```csharp
private List<TastyBug> bugs
```


#### Field Value
**Type:** System.Collections.Generic.List{TastyBug}

### bugsPerPassageMax
```csharp
public const int bugsPerPassageMax = 4
```


#### Field Value
**Type:** System.Int32

### bugsPerPassageMin
```csharp
public const int bugsPerPassageMin = 3
```


#### Field Value
**Type:** System.Int32

### bugSrcA
```csharp
public const string bugSrcA = "StandingItem/TastyBugs/TastyBug_A"
```


#### Field Value
**Type:** System.String

### bugSrcB
```csharp
public const string bugSrcB = "StandingItem/TastyBugs/TastyBug_B"
```


#### Field Value
**Type:** System.String

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

## Methods
### DisableBugs(TastyBug)
```csharp
public void DisableBugs(TastyBug bug)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `bug` | `Global.TastyBug` |  |

### GenBugsInPassage(PassageObjectModel)
```csharp
public void GenBugsInPassage(PassageObjectModel passage)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `passage` | `Global.PassageObjectModel` |  |

### GetBugType()
```csharp
private TastyBug.BugType GetBugType()
```


#### Returns
**Type:** Global.TastyBug.BugType

### LoadBug(BugType, out TastyBug)
```csharp
public GameObject LoadBug(TastyBug.BugType type, out TastyBug script)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.TastyBug.BugType` |  |
| `script` | `Global.TastyBug` |  |

#### Returns
**Type:** UnityEngine.GameObject

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


### SetBugType(TastyBug, StandingItemUnit, BugType)
```csharp
public void SetBugType(TastyBug script, StandingItemUnit unit, TastyBug.BugType type)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `script` | `Global.TastyBug` |  |
| `unit` | `Global.StandingItemUnit` |  |
| `type` | `Global.TastyBug.BugType` |  |

## Inherited Members
[rootObjectSrc](/api/Global/Unused/Random-Events/RandomEventBase#rootobjectsrc), [rootObjectId](/api/Global/Unused/Random-Events/RandomEventBase#rootobjectid), [type](/api/Global/Unused/Random-Events/RandomEventBase#type), [rank](/api/Global/Unused/Random-Events/RandomEventBase#rank), [metaInfo](/api/Global/Unused/Random-Events/RandomEventBase#metainfo), [rootGameObject](/api/Global/Unused/Random-Events/RandomEventBase#rootgameobject), [rootStanding](/api/Global/Unused/Random-Events/RandomEventBase#rootstanding), [enableCheckConditions](/api/Global/Unused/Random-Events/RandomEventBase#enablecheckconditions), [instanceId](/api/Global/Unused/Random-Events/RandomEventBase#instanceid), [_isEnabled](/api/Global/Unused/Random-Events/RandomEventBase#isenabled), [GenerateCondition()](/api/Global/Unused/Random-Events/RandomEventBase#generatecondition), [GenerateCondition(ConditionInfo, ref List<int>)](/api/Global/Unused/Random-Events/RandomEventBase#generatecondition-conditioninfo-ref-list-int), [OnDestroy()](/api/Global/Unused/Random-Events/RandomEventBase#ondestroy), [OnEnd()](/api/Global/Unused/Random-Events/RandomEventBase#onend), [IsDuplicatable()](/api/Global/Unused/Random-Events/RandomEventBase#isduplicatable), [CheckEquivalent(string)](/api/Global/Unused/Random-Events/RandomEventBase#checkequivalent-string), [CheckCondition()](/api/Global/Unused/Random-Events/RandomEventBase#checkcondition), [ManualDisable()](/api/Global/Unused/Random-Events/RandomEventBase#manualdisable), [ManualDisable(string)](/api/Global/Unused/Random-Events/RandomEventBase#manualdisable-string), [GenerateTypo(TypoType, string)](/api/Global/Unused/Random-Events/RandomEventBase#generatetypo-typotype-string), [GenerateTypo(TypoType)](/api/Global/Unused/Random-Events/RandomEventBase#generatetypo-typotype), [GenerateTypo(string)](/api/Global/Unused/Random-Events/RandomEventBase#generatetypo-string), [OnUpdate()](/api/Global/Unused/Random-Events/RandomEventBase#onupdate), [GetCondition(string)](/api/Global/Unused/Random-Events/RandomEventBase#getcondition-string), [MakeRootObject()](/api/Global/Unused/Random-Events/RandomEventBase#makerootobject), [GetTimerCondition()](/api/Global/Unused/Random-Events/RandomEventBase#gettimercondition), [SetTimerConditionTime(float)](/api/Global/Unused/Random-Events/RandomEventBase#settimerconditiontime-float), [RootTransform](/api/Global/Unused/Random-Events/RandomEventBase#roottransform), [HasRootObject](/api/Global/Unused/Random-Events/RandomEventBase#hasrootobject), [MetaDataId](/api/Global/Unused/Random-Events/RandomEventBase#metadataid), [IsEnabled](/api/Global/Unused/Random-Events/RandomEventBase#isenabled), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)






