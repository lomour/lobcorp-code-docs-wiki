---
uid: Global.HodBossBase
canonical_path: /api/Global/Misc/HodBossBase
---
# Class HodBossBase
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class HodBossBase : SefiraBossBase
```
> This section may have incomplete or incorrect information.
{.is-warning}


Hod's core suppression. 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [SefiraBossBase](/api/Global/Core-Suppressions/SefiraBossBase) → HodBossBase

## Constructors
### HodBossBase()
```csharp
public HodBossBase()
```


## Fields
### _80
```csharp
private CameraFilterPack_TV_80 _80
```


#### Field Value
**Type:** Global.CameraFilterPack_TV_80

### _firstReduce
```csharp
public static float _firstReduce
```


#### Field Value
**Type:** System.Single

### _phase
```csharp
private int _phase
```


#### Field Value
**Type:** System.Int32

### _secondReduce
```csharp
public static float _secondReduce
```


#### Field Value
**Type:** System.Single

### _thirdReduce
```csharp
public static float _thirdReduce
```


#### Field Value
**Type:** System.Single

### animSrc
```csharp
private const string animSrc = "HodCoreAnim"
```


#### Field Value
**Type:** System.String

### bgm1
```csharp
private const string bgm1 = "Hod/1_Theme_-_Retro_Time_ALT"
```


#### Field Value
**Type:** System.String

### bgm2
```csharp
private const string bgm2 = "Hod/2_Theme_-_Retro_Time_ALT(Mix)"
```


#### Field Value
**Type:** System.String

### bufList
```csharp
public List<HodBossBuf> bufList
```


#### Field Value
**Type:** System.Collections.Generic.List{HodBossBuf}

### changeQliphothLevel
```csharp
private const int changeQliphothLevel = 3
```


#### Field Value
**Type:** System.Int32

### clearQliphothLevel
```csharp
private const int clearQliphothLevel = 6
```


#### Field Value
**Type:** System.Int32

### descDelay
```csharp
private const float descDelay = 15
```


#### Field Value
**Type:** System.Single

### hodBase
```csharp
private const string hodBase = "HodCoreScript"
```


#### Field Value
**Type:** System.String

### model
```csharp
private SefiraBossCreatureModel model
```


#### Field Value
**Type:** Global.SefiraBossCreatureModel

### phaseSound
```csharp
private const string phaseSound = "SefiraBoss/Boss_Nezach"
```


#### Field Value
**Type:** System.String

### totalEnergy
```csharp
private float totalEnergy
```


#### Field Value
**Type:** System.Single

### vhs
```csharp
private CameraFilterPack_Real_VHS vhs
```


#### Field Value
**Type:** Global.CameraFilterPack_Real_VHS

### vignetting
```csharp
private CameraFilterPack_TV_Vignetting vignetting
```


#### Field Value
**Type:** Global.CameraFilterPack_TV_Vignetting

## Properties
### Script
```csharp
private HodCoreScript Script { get; }
```

#### Property Value
**Type:** Global.HodCoreScript

## Methods
### FixedUpdate()
```csharp
public override void FixedUpdate()
```


### GetDescFreq()
```csharp
public override float GetDescFreq()
```


#### Returns
**Type:** System.Single

### IsCleared()
```csharp
public override bool IsCleared()
```


#### Returns
**Type:** System.Boolean

### OnChangePhase()
```csharp
public override void OnChangePhase()
```


### OnCleared()
```csharp
public override void OnCleared()
```


### OnKetherStart()
```csharp
public override void OnKetherStart()
```


### OnOverloadActivated(int)
```csharp
public override void OnOverloadActivated(int currentLevel)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `currentLevel` | `System.Int32` |  |

### OnStageStart()
```csharp
public override void OnStageStart()
```


## Inherited Members
[_closeEffectTime](/api/Global/Core-Suppressions/SefiraBossBase#closeeffecttime), [_defaultDescFreq](/api/Global/Core-Suppressions/SefiraBossBase#defaultdescfreq), [_descAppearProb](/api/Global/Core-Suppressions/SefiraBossBase#descappearprob), [generalScript](/api/Global/Core-Suppressions/SefiraBossBase#generalscript), [generalAnim](/api/Global/Core-Suppressions/SefiraBossBase#generalanim), [bgmSoundPrefix](/api/Global/Core-Suppressions/SefiraBossBase#bgmsoundprefix), [currentCloseEffectParam](/api/Global/Core-Suppressions/SefiraBossBase#currentcloseeffectparam), [modelList](/api/Global/Core-Suppressions/SefiraBossBase#modellist), [sefiraEnum](/api/Global/Core-Suppressions/SefiraBossBase#sefiraenum), [closeEffectType](/api/Global/Core-Suppressions/SefiraBossBase#closeeffecttype), [DefaultDamageInfo](/api/Global/Core-Suppressions/SefiraBossBase#defaultdamageinfo), [DefaultDefenseInfo](/api/Global/Core-Suppressions/SefiraBossBase#defaultdefenseinfo), [_closeTimer](/api/Global/Core-Suppressions/SefiraBossBase#closetimer), [_closeEffectMethod](/api/Global/Core-Suppressions/SefiraBossBase#closeeffectmethod), [_cameraDescTimer](/api/Global/Core-Suppressions/SefiraBossBase#cameradesctimer), [descList](/api/Global/Core-Suppressions/SefiraBossBase#desclist), [OnStageEnd()](/api/Global/Core-Suppressions/SefiraBossBase#onstageend), [OnRemoveDesc(SefiraBossDescUI)](/api/Global/Core-Suppressions/SefiraBossBase#onremovedesc-sefirabossdescui), [Update()](/api/Global/Core-Suppressions/SefiraBossBase#update), [DefaultClearEffect(params object[])](/api/Global/Core-Suppressions/SefiraBossBase#defaultcleareffect-params-object), [OnDestroy()](/api/Global/Core-Suppressions/SefiraBossBase#ondestroy), [IsReadyToClose()](/api/Global/Core-Suppressions/SefiraBossBase#isreadytoclose), [GetDamageInfo()](/api/Global/Core-Suppressions/SefiraBossBase#getdamageinfo), [GetDefenseInfo()](/api/Global/Core-Suppressions/SefiraBossBase#getdefenseinfo), [GetDescType(float)](/api/Global/Core-Suppressions/SefiraBossBase#getdesctype-float), [ClearDescTexts()](/api/Global/Core-Suppressions/SefiraBossBase#cleardesctexts), [MakeSound(string)](/api/Global/Core-Suppressions/SefiraBossBase#makesound-string), [MakeSoundAttachCamera(string)](/api/Global/Core-Suppressions/SefiraBossBase#makesoundattachcamera-string), [IsStartEmergencyBgm()](/api/Global/Core-Suppressions/SefiraBossBase#isstartemergencybgm), [QliphothOverloadLevel](/api/Global/Core-Suppressions/SefiraBossBase#qliphothoverloadlevel), [Sefira](/api/Global/Core-Suppressions/SefiraBossBase#sefira), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)







