---
uid: KetherBoss.KetherMiddleBossBase
canonical_path: /api/KetherBoss/KetherMiddleBossBase
---
# Class KetherMiddleBossBase
**Namespace:** [KetherBoss](/api/KetherBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class KetherMiddleBossBase : KetherBossBase
```
> This section may have incomplete or incorrect information.
{.is-warning}

Day 48 suppression


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [SefiraBossBase](/api/Global/Core-Suppressions/SefiraBossBase) → [KetherBossBase](/api/KetherBoss/KetherBossBase) → KetherMiddleBossBase

## Constructors
### KetherMiddleBossBase()
```csharp
public KetherMiddleBossBase()
```


## Fields
### _artefactEffectTime
```csharp
private float _artefactEffectTime
```


#### Field Value
**Type:** System.Single

### _artefactEffectTimer
```csharp
private UnscaledTimer _artefactEffectTimer
```


#### Field Value
**Type:** Global.UnscaledTimer

### _chesed
```csharp
private ChesedBossBase _chesed
```


#### Field Value
**Type:** Global.ChesedBossBase

### _clearEnergyValue
```csharp
private float _clearEnergyValue
```


#### Field Value
**Type:** System.Single

### _fade
```csharp
private MinMax _fade
```


#### Field Value
**Type:** Global.MinMax

### _fps
```csharp
private MinMax _fps
```


#### Field Value
**Type:** Global.MinMax

### _geburah
```csharp
private GeburahBossBase _geburah
```


#### Field Value
**Type:** Global.GeburahBossBase

### _movieEffectTime
```csharp
private float _movieEffectTime
```


#### Field Value
**Type:** System.Single

### _movieEffectTimer
```csharp
private UnscaledTimer _movieEffectTimer
```


#### Field Value
**Type:** Global.UnscaledTimer

### _tiphereth
```csharp
private TipherethBossBase _tiphereth
```


#### Field Value
**Type:** Global.TipherethBossBase

### artefact
```csharp
private CameraFilterPack_TV_Artefact artefact
```


#### Field Value
**Type:** Global.CameraFilterPack_TV_Artefact

### bgm0
```csharp
private const string bgm0 = "Sounds/BGM/Boss/Event/48/1_Dark Fantasy Scene"
```


#### Field Value
**Type:** System.String

### bgm1
```csharp
private const string bgm1 = "Sounds/BGM/Boss/Event/48/2_Tilarids - Insignia Decay"
```


#### Field Value
**Type:** System.String

### bgm2
```csharp
private const string bgm2 = "Sounds/BGM/Boss/Event/48/3_Battle_-_Urgent_Encounter"
```


#### Field Value
**Type:** System.String

### ClearQliphothLevel
```csharp
private const int ClearQliphothLevel = 10
```


#### Field Value
**Type:** System.Int32

### fadeEffect
```csharp
private MinMax fadeEffect
```


#### Field Value
**Type:** Global.MinMax

### fpsEffect
```csharp
private MinMax fpsEffect
```


#### Field Value
**Type:** Global.MinMax

### movie
```csharp
private CameraFilterPack_TV_Old_Movie_2 movie
```


#### Field Value
**Type:** Global.CameraFilterPack_TV_Old_Movie_2

### tvOldEnableLevel
```csharp
private const int tvOldEnableLevel = 7
```


#### Field Value
**Type:** System.Int32

### tvOldEndLevel
```csharp
private const int tvOldEndLevel = 10
```


#### Field Value
**Type:** System.Int32

### vignetting
```csharp
private CameraFilterPack_TV_Vignetting vignetting
```


#### Field Value
**Type:** Global.CameraFilterPack_TV_Vignetting

## Methods
### GetDescType(float)
```csharp
public override SefiraBossDescType GetDescType(float defaultProb = 0.5)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `defaultProb` | `System.Single` |  |

#### Returns
**Type:** Global.SefiraBossDescType

### IsCleared()
```csharp
public override bool IsCleared()
```


#### Returns
**Type:** System.Boolean

### IsStartEmergencyBgm()
```csharp
public override bool IsStartEmergencyBgm()
```


#### Returns
**Type:** System.Boolean

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


### Update()
```csharp
public override void Update()
```


## Inherited Members
[ModelHPFactor](/api/KetherBoss/KetherBossBase#modelhpfactor), [type](/api/KetherBoss/KetherBossBase#type), [builder](/api/KetherBoss/KetherBossBase#builder), [bossBaseList](/api/KetherBoss/KetherBossBase#bossbaselist), [_currentQliphothLevel](/api/KetherBoss/KetherBossBase#currentqliphothlevel), [StringFormat(string, params object[])](/api/KetherBoss/KetherBossBase#stringformat-string-params-object), [OnCleared()](/api/KetherBoss/KetherBossBase#oncleared), [FixedUpdate()](/api/KetherBoss/KetherBossBase#fixedupdate), [QliphothOverloadLevel](/api/KetherBoss/KetherBossBase#qliphothoverloadlevel), [_closeEffectTime](/api/Global/Core-Suppressions/SefiraBossBase#closeeffecttime), [_defaultDescFreq](/api/Global/Core-Suppressions/SefiraBossBase#defaultdescfreq), [_descAppearProb](/api/Global/Core-Suppressions/SefiraBossBase#descappearprob), [generalScript](/api/Global/Core-Suppressions/SefiraBossBase#generalscript), [generalAnim](/api/Global/Core-Suppressions/SefiraBossBase#generalanim), [bgmSoundPrefix](/api/Global/Core-Suppressions/SefiraBossBase#bgmsoundprefix), [currentCloseEffectParam](/api/Global/Core-Suppressions/SefiraBossBase#currentcloseeffectparam), [modelList](/api/Global/Core-Suppressions/SefiraBossBase#modellist), [sefiraEnum](/api/Global/Core-Suppressions/SefiraBossBase#sefiraenum), [closeEffectType](/api/Global/Core-Suppressions/SefiraBossBase#closeeffecttype), [DefaultDamageInfo](/api/Global/Core-Suppressions/SefiraBossBase#defaultdamageinfo), [DefaultDefenseInfo](/api/Global/Core-Suppressions/SefiraBossBase#defaultdefenseinfo), [_closeTimer](/api/Global/Core-Suppressions/SefiraBossBase#closetimer), [_closeEffectMethod](/api/Global/Core-Suppressions/SefiraBossBase#closeeffectmethod), [_cameraDescTimer](/api/Global/Core-Suppressions/SefiraBossBase#cameradesctimer), [descList](/api/Global/Core-Suppressions/SefiraBossBase#desclist), [OnKetherStart()](/api/Global/Core-Suppressions/SefiraBossBase#onketherstart), [OnStageEnd()](/api/Global/Core-Suppressions/SefiraBossBase#onstageend), [OnRemoveDesc(SefiraBossDescUI)](/api/Global/Core-Suppressions/SefiraBossBase#onremovedesc-sefirabossdescui), [DefaultClearEffect(params object[])](/api/Global/Core-Suppressions/SefiraBossBase#defaultcleareffect-params-object), [OnDestroy()](/api/Global/Core-Suppressions/SefiraBossBase#ondestroy), [IsReadyToClose()](/api/Global/Core-Suppressions/SefiraBossBase#isreadytoclose), [GetDamageInfo()](/api/Global/Core-Suppressions/SefiraBossBase#getdamageinfo), [GetDefenseInfo()](/api/Global/Core-Suppressions/SefiraBossBase#getdefenseinfo), [GetDescFreq()](/api/Global/Core-Suppressions/SefiraBossBase#getdescfreq), [OnChangePhase()](/api/Global/Core-Suppressions/SefiraBossBase#onchangephase), [ClearDescTexts()](/api/Global/Core-Suppressions/SefiraBossBase#cleardesctexts), [MakeSound(string)](/api/Global/Core-Suppressions/SefiraBossBase#makesound-string), [MakeSoundAttachCamera(string)](/api/Global/Core-Suppressions/SefiraBossBase#makesoundattachcamera-string), [Sefira](/api/Global/Core-Suppressions/SefiraBossBase#sefira), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)










