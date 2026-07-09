---
uid: Global.FallingLegEvent
canonical_path: /api/Global/Event/FallingLegEvent
---
# Class FallingLegEvent
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class FallingLegEvent : RandomEventBase
```
> This section may have incomplete or incorrect information.
{.is-warning}

> This class is not used.
{.is-info}




## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [RandomEventBase](/api/Global/Unused/Random-Events/RandomEventBase) → FallingLegEvent

## Constructors
### FallingLegEvent()
```csharp
public FallingLegEvent()
```

## Fields
### animSrc
```csharp
private const string animSrc = "StandingItem/ChopLeg"
```


#### Field Value
**Type:** System.String

### animSrcA
```csharp
private const string animSrcA = "StandingItem/ChopLegA"
```


#### Field Value
**Type:** System.String

### animSrcB
```csharp
private const string animSrcB = "StandingItem/ChopLegB"
```


#### Field Value
**Type:** System.String

### animSrcC
```csharp
private const string animSrcC = "StandingItem/ChopLegC"
```


#### Field Value
**Type:** System.String

### AttackFreq
```csharp
public const float AttackFreq = 3
```


#### Field Value
**Type:** System.Single

### disableCheck
```csharp
private bool disableCheck
```


#### Field Value
**Type:** System.Boolean

### disableTime
```csharp
private const float disableTime = 120
```


#### Field Value
**Type:** System.Single

### disableTimer
```csharp
public Timer disableTimer
```


#### Field Value
**Type:** Global.Timer

### legId
```csharp
private const long legId = 1002
```


#### Field Value
**Type:** System.Int64

### legs
```csharp
private List<StandingItemModel> legs
```


#### Field Value
**Type:** System.Collections.Generic.List{StandingItemModel}

### management
```csharp
public List<FallingLegEvent.SefiraManagement> management
```

#### Field Value
**Type:** System.Collections.Generic.List{FallingLegEvent.SefiraManagement}

## Methods
### DelayedDisable()
```csharp
private void DelayedDisable()
```


### DisableLeb(string)
```csharp
public void DisableLeb(string sefira)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `System.String` |  |

### EnableLeg(string)
```csharp
public void EnableLeg(string sefira)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `System.String` |  |

### GetLegType()
```csharp
public ChopLeg.LegType GetLegType()
```


#### Returns
**Type:** Global.ChopLeg.LegType

### GetSefiraManagement(string)
```csharp
public FallingLegEvent.SefiraManagement GetSefiraManagement(string sefira)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `System.String` |  |

#### Returns
**Type:** Global.FallingLegEvent.SefiraManagement

### LoadLeg(out ChopLeg)
```csharp
public GameObject LoadLeg(out ChopLeg leg)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `leg` | `Global.ChopLeg` |  |

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






