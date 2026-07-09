---
uid: Global.BoomerCircusEvent
canonical_path: /api/Global/Event/BoomerCircusEvent
---
# Class BoomerCircusEvent
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BoomerCircusEvent : RandomEventBase
```
> This section may have incomplete or incorrect information.
{.is-warning}

> This class is not used.
{.is-info}

The Noon of Crimson, The Harmony of Skin. I think. 

No, wait, that would be [CircusNoon](/api/Global/Abnormalities/Ordeals/Crimson-Ordeals/Crimson-Noon/CircusNoon). Uh. Hm. Older version?




## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [RandomEventBase](/api/Global/Unused/Random-Events/RandomEventBase) → BoomerCircusEvent

## Constructors
### BoomerCircusEvent()
```csharp
public BoomerCircusEvent()
```

## Fields
### boomerId
```csharp
public const long boomerId = 10052
```


#### Field Value
**Type:** System.Int64

### boomerMax
```csharp
public static int boomerMax
```


#### Field Value
**Type:** System.Int32

### boomers
```csharp
private List<CircusBoomer> boomers
```


#### Field Value
**Type:** System.Collections.Generic.List{CircusBoomer}

### boomerSrc
```csharp
public const string boomerSrc = "StandingItem/BoomerCircus/CircusBoomer"
```


#### Field Value
**Type:** System.String

### circusBgm
```csharp
public const string circusBgm = ""
```


#### Field Value
**Type:** System.String

### numOfBoomers
```csharp
private int numOfBoomers
```


#### Field Value
**Type:** System.Int32

### numOfTents
```csharp
private int numOfTents
```


#### Field Value
**Type:** System.Int32

### tentId
```csharp
public const long tentId = 10051
```


#### Field Value
**Type:** System.Int64

### tentMax
```csharp
public static int tentMax
```


#### Field Value
**Type:** System.Int32

### tents
```csharp
private List<CircusTent> tents
```


#### Field Value
**Type:** System.Collections.Generic.List{CircusTent}

### tentSrc
```csharp
public const string tentSrc = "StandingItem/BoomerCircus/CircusTent"
```


#### Field Value
**Type:** System.String

## Methods
### DisableCircus(BoomerCircusScript)
```csharp
public void DisableCircus(BoomerCircusScript script)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `script` | `Global.BoomerCircusScript` |  |

### EnableCircus(CircusType, MapNode)
```csharp
public void EnableCircus(BoomerCircusScript.CircusType type, MapNode node)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.BoomerCircusScript.CircusType` |  |
| `node` | `Global.MapNode` |  |

### LoadCircus(string, long, out BoomerCircusScript)
```csharp
public GameObject LoadCircus(string src, long metaId, out BoomerCircusScript script)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |
| `metaId` | `System.Int64` |  |
| `script` | `Global.BoomerCircusScript` |  |

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


## Inherited Members
[rootObjectSrc](/api/Global/Unused/Random-Events/RandomEventBase#rootobjectsrc), [rootObjectId](/api/Global/Unused/Random-Events/RandomEventBase#rootobjectid), [type](/api/Global/Unused/Random-Events/RandomEventBase#type), [rank](/api/Global/Unused/Random-Events/RandomEventBase#rank), [metaInfo](/api/Global/Unused/Random-Events/RandomEventBase#metainfo), [rootGameObject](/api/Global/Unused/Random-Events/RandomEventBase#rootgameobject), [rootStanding](/api/Global/Unused/Random-Events/RandomEventBase#rootstanding), [enableCheckConditions](/api/Global/Unused/Random-Events/RandomEventBase#enablecheckconditions), [instanceId](/api/Global/Unused/Random-Events/RandomEventBase#instanceid), [_isEnabled](/api/Global/Unused/Random-Events/RandomEventBase#isenabled), [GenerateCondition()](/api/Global/Unused/Random-Events/RandomEventBase#generatecondition), [GenerateCondition(ConditionInfo, ref List<int>)](/api/Global/Unused/Random-Events/RandomEventBase#generatecondition-conditioninfo-ref-list-int), [OnDestroy()](/api/Global/Unused/Random-Events/RandomEventBase#ondestroy), [OnEnd()](/api/Global/Unused/Random-Events/RandomEventBase#onend), [IsDuplicatable()](/api/Global/Unused/Random-Events/RandomEventBase#isduplicatable), [CheckEquivalent(string)](/api/Global/Unused/Random-Events/RandomEventBase#checkequivalent-string), [CheckCondition()](/api/Global/Unused/Random-Events/RandomEventBase#checkcondition), [ManualDisable()](/api/Global/Unused/Random-Events/RandomEventBase#manualdisable), [ManualDisable(string)](/api/Global/Unused/Random-Events/RandomEventBase#manualdisable-string), [GenerateTypo(TypoType, string)](/api/Global/Unused/Random-Events/RandomEventBase#generatetypo-typotype-string), [GenerateTypo(TypoType)](/api/Global/Unused/Random-Events/RandomEventBase#generatetypo-typotype), [GenerateTypo(string)](/api/Global/Unused/Random-Events/RandomEventBase#generatetypo-string), [OnUpdate()](/api/Global/Unused/Random-Events/RandomEventBase#onupdate), [GetCondition(string)](/api/Global/Unused/Random-Events/RandomEventBase#getcondition-string), [MakeRootObject()](/api/Global/Unused/Random-Events/RandomEventBase#makerootobject), [GetTimerCondition()](/api/Global/Unused/Random-Events/RandomEventBase#gettimercondition), [SetTimerConditionTime(float)](/api/Global/Unused/Random-Events/RandomEventBase#settimerconditiontime-float), [RootTransform](/api/Global/Unused/Random-Events/RandomEventBase#roottransform), [HasRootObject](/api/Global/Unused/Random-Events/RandomEventBase#hasrootobject), [MetaDataId](/api/Global/Unused/Random-Events/RandomEventBase#metadataid), [IsEnabled](/api/Global/Unused/Random-Events/RandomEventBase#isenabled), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)






