---
uid: Global.YesodBossBase
canonical_path: /api/Global/Misc/YesodBossBase
---
# Class YesodBossBase
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class YesodBossBase : SefiraBossBase
```
> This section may have incomplete or incorrect information.
{.is-warning}


Yesod's core suppression.




## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [SefiraBossBase](/api/Global/Core-Suppressions/SefiraBossBase) → YesodBossBase

## Constructors
### YesodBossBase()
```csharp
public YesodBossBase()
```


## Fields
### _phase
```csharp
private int _phase
```


#### Field Value
**Type:** System.Int32

### _startEffectTimer
```csharp
private Timer _startEffectTimer
```


#### Field Value
**Type:** Global.Timer

### animSrc
```csharp
private const string animSrc = "YesodCoreAnim"
```


#### Field Value
**Type:** System.String

### bgm1
```csharp
private const string bgm1 = "Yesod/1_Tilarids - untitled9877645623413123325"
```


#### Field Value
**Type:** System.String

### bgm2
```csharp
private const string bgm2 = "Yesod/2_Tilarids - Faded"
```


#### Field Value
**Type:** System.String

### cameraScript
```csharp
private YesodBossCameraScript cameraScript
```


#### Field Value
**Type:** Global.YesodBossCameraScript

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

### glitch3
```csharp
private CameraFilterPack_FX_Glitch3 glitch3
```


#### Field Value
**Type:** Global.CameraFilterPack_FX_Glitch3

### model
```csharp
private SefiraBossCreatureModel model
```


#### Field Value
**Type:** Global.SefiraBossCreatureModel

### noiseDefaultValue
```csharp
private const float noiseDefaultValue = 0.075
```


#### Field Value
**Type:** System.Single

### noiseTv
```csharp
private CameraFilterPack_Noise_TV noiseTv
```


#### Field Value
**Type:** Global.CameraFilterPack_Noise_TV

### phaseSound
```csharp
private const string phaseSound = "SefiraBoss/Boss_Yesod"
```


#### Field Value
**Type:** System.String

### pixelisation
```csharp
private CameraFilterPack_Pixel_Pixelisation pixelisation
```


#### Field Value
**Type:** Global.CameraFilterPack_Pixel_Pixelisation

### totalEnergy
```csharp
private float totalEnergy
```


#### Field Value
**Type:** System.Single

### vignetting
```csharp
private CameraFilterPack_TV_Vignetting vignetting
```


#### Field Value
**Type:** Global.CameraFilterPack_TV_Vignetting

### yesodBase
```csharp
private const string yesodBase = "YesodCoreScript"
```


#### Field Value
**Type:** System.String

## Properties
### Script
```csharp
private YesodCoreScript Script { get; }
```

#### Property Value
**Type:** Global.YesodCoreScript

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


### SetCameraScript(YesodBossCameraScript)
```csharp
public void SetCameraScript(YesodBossCameraScript cameraScript)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `cameraScript` | `Global.YesodBossCameraScript` |  |

### StartEffect()
```csharp
public void StartEffect()
```


## Inherited Members
[_closeEffectTime](/api/Global/Core-Suppressions/SefiraBossBase#closeeffecttime), [_defaultDescFreq](/api/Global/Core-Suppressions/SefiraBossBase#defaultdescfreq), [_descAppearProb](/api/Global/Core-Suppressions/SefiraBossBase#descappearprob), [generalScript](/api/Global/Core-Suppressions/SefiraBossBase#generalscript), [generalAnim](/api/Global/Core-Suppressions/SefiraBossBase#generalanim), [bgmSoundPrefix](/api/Global/Core-Suppressions/SefiraBossBase#bgmsoundprefix), [currentCloseEffectParam](/api/Global/Core-Suppressions/SefiraBossBase#currentcloseeffectparam), [modelList](/api/Global/Core-Suppressions/SefiraBossBase#modellist), [sefiraEnum](/api/Global/Core-Suppressions/SefiraBossBase#sefiraenum), [closeEffectType](/api/Global/Core-Suppressions/SefiraBossBase#closeeffecttype), [DefaultDamageInfo](/api/Global/Core-Suppressions/SefiraBossBase#defaultdamageinfo), [DefaultDefenseInfo](/api/Global/Core-Suppressions/SefiraBossBase#defaultdefenseinfo), [_closeTimer](/api/Global/Core-Suppressions/SefiraBossBase#closetimer), [_closeEffectMethod](/api/Global/Core-Suppressions/SefiraBossBase#closeeffectmethod), [_cameraDescTimer](/api/Global/Core-Suppressions/SefiraBossBase#cameradesctimer), [descList](/api/Global/Core-Suppressions/SefiraBossBase#desclist), [OnStageEnd()](/api/Global/Core-Suppressions/SefiraBossBase#onstageend), [OnRemoveDesc(SefiraBossDescUI)](/api/Global/Core-Suppressions/SefiraBossBase#onremovedesc-sefirabossdescui), [Update()](/api/Global/Core-Suppressions/SefiraBossBase#update), [DefaultClearEffect(params object[])](/api/Global/Core-Suppressions/SefiraBossBase#defaultcleareffect-params-object), [OnDestroy()](/api/Global/Core-Suppressions/SefiraBossBase#ondestroy), [IsReadyToClose()](/api/Global/Core-Suppressions/SefiraBossBase#isreadytoclose), [GetDamageInfo()](/api/Global/Core-Suppressions/SefiraBossBase#getdamageinfo), [GetDefenseInfo()](/api/Global/Core-Suppressions/SefiraBossBase#getdefenseinfo), [GetDescType(float)](/api/Global/Core-Suppressions/SefiraBossBase#getdesctype-float), [ClearDescTexts()](/api/Global/Core-Suppressions/SefiraBossBase#cleardesctexts), [MakeSound(string)](/api/Global/Core-Suppressions/SefiraBossBase#makesound-string), [MakeSoundAttachCamera(string)](/api/Global/Core-Suppressions/SefiraBossBase#makesoundattachcamera-string), [IsStartEmergencyBgm()](/api/Global/Core-Suppressions/SefiraBossBase#isstartemergencybgm), [QliphothOverloadLevel](/api/Global/Core-Suppressions/SefiraBossBase#qliphothoverloadlevel), [Sefira](/api/Global/Core-Suppressions/SefiraBossBase#sefira), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)







