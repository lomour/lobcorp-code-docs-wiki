---
uid: Global.GeburahBossBase
canonical_path: /api/Global/Misc/GeburahBossBase
---
# Class GeburahBossBase
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class GeburahBossBase : SefiraBossBase
```
> This section may have incomplete or incorrect information.
{.is-warning}


extends [SefiraBossBase](/api/Global/Core-Suppressions/SefiraBossBase)

Gebura's core suppression. Ends when [The Red Mist](/api/Global/Core-Suppressions/Gebura-Suppression/GeburahCoreScript) is defeated. 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [SefiraBossBase](/api/Global/Core-Suppressions/SefiraBossBase) → GeburahBossBase

## Constructors
### GeburahBossBase()
```csharp
public GeburahBossBase()
```


## Fields
### _hexaEffect
```csharp
private UnscaledTimer _hexaEffect
```


#### Field Value
**Type:** Global.UnscaledTimer

### _hexagonTime
```csharp
private const float _hexagonTime = 4
```


#### Field Value
**Type:** System.Single

### _isInit
```csharp
private bool _isInit
```


#### Field Value
**Type:** System.Boolean

### _phase
```csharp
private int _phase
```


#### Field Value
**Type:** System.Int32

### animSrc
```csharp
private const string animSrc = "GeburahCoreAnim"
```


#### Field Value
**Type:** System.String

### bgm1
```csharp
private const string bgm1 = "Geburah/1_Tilarids - Distorted Night"
```


#### Field Value
**Type:** System.String

### bgm2
```csharp
private const string bgm2 = "Geburah/2_Tilarids - Insignia Decay"
```


#### Field Value
**Type:** System.String

### blackColor
```csharp
private const string blackColor = "#350000FF"
```


#### Field Value
**Type:** System.String

### geburahBase
```csharp
private const string geburahBase = "GeburahCoreScript"
```


#### Field Value
**Type:** System.String

### hexa_black
```csharp
private Color hexa_black
```


#### Field Value
**Type:** UnityEngine.Color

### hexa_red
```csharp
private Color hexa_red
```


#### Field Value
**Type:** UnityEngine.Color

### hexagon
```csharp
private CameraFilterPack_AAA_SuperHexagon hexagon
```


#### Field Value
**Type:** Global.CameraFilterPack_AAA_SuperHexagon

### model
```csharp
public SefiraBossCreatureModel model
```


#### Field Value
**Type:** Global.SefiraBossCreatureModel

### redColor
```csharp
private const string redColor = "#FF0000FF"
```


#### Field Value
**Type:** System.String

### startNode
```csharp
private const string startNode = "dept-geburah-4"
```


#### Field Value
**Type:** System.String

### superComputer
```csharp
private CameraFilterPack_AAA_SuperComputer superComputer
```


#### Field Value
**Type:** Global.CameraFilterPack_AAA_SuperComputer

### vignetting
```csharp
private CameraFilterPack_TV_Vignetting vignetting
```


#### Field Value
**Type:** Global.CameraFilterPack_TV_Vignetting

## Properties
### Script
```csharp
private GeburahCoreScript Script { get; }
```

#### Property Value
**Type:** Global.GeburahCoreScript

## Methods
### FixedUpdate()
```csharp
public override void FixedUpdate()
```


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

### InitModel()
```csharp
public void InitModel()
```


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


### OnStageStart()
```csharp
public override void OnStageStart()
```


### StartCameraMoveEndFirst()
```csharp
private void StartCameraMoveEndFirst()
```


### StartHexagonEffect()
```csharp
public void StartHexagonEffect()
```


### Update()
```csharp
public override void Update()
```


## Inherited Members
[_closeEffectTime](/api/Global/Core-Suppressions/SefiraBossBase#closeeffecttime), [_defaultDescFreq](/api/Global/Core-Suppressions/SefiraBossBase#defaultdescfreq), [_descAppearProb](/api/Global/Core-Suppressions/SefiraBossBase#descappearprob), [generalScript](/api/Global/Core-Suppressions/SefiraBossBase#generalscript), [generalAnim](/api/Global/Core-Suppressions/SefiraBossBase#generalanim), [bgmSoundPrefix](/api/Global/Core-Suppressions/SefiraBossBase#bgmsoundprefix), [currentCloseEffectParam](/api/Global/Core-Suppressions/SefiraBossBase#currentcloseeffectparam), [modelList](/api/Global/Core-Suppressions/SefiraBossBase#modellist), [sefiraEnum](/api/Global/Core-Suppressions/SefiraBossBase#sefiraenum), [closeEffectType](/api/Global/Core-Suppressions/SefiraBossBase#closeeffecttype), [DefaultDamageInfo](/api/Global/Core-Suppressions/SefiraBossBase#defaultdamageinfo), [DefaultDefenseInfo](/api/Global/Core-Suppressions/SefiraBossBase#defaultdefenseinfo), [_closeTimer](/api/Global/Core-Suppressions/SefiraBossBase#closetimer), [_closeEffectMethod](/api/Global/Core-Suppressions/SefiraBossBase#closeeffectmethod), [_cameraDescTimer](/api/Global/Core-Suppressions/SefiraBossBase#cameradesctimer), [descList](/api/Global/Core-Suppressions/SefiraBossBase#desclist), [OnStageEnd()](/api/Global/Core-Suppressions/SefiraBossBase#onstageend), [OnRemoveDesc(SefiraBossDescUI)](/api/Global/Core-Suppressions/SefiraBossBase#onremovedesc-sefirabossdescui), [DefaultClearEffect(params object[])](/api/Global/Core-Suppressions/SefiraBossBase#defaultcleareffect-params-object), [OnOverloadActivated(int)](/api/Global/Core-Suppressions/SefiraBossBase#onoverloadactivated-int), [OnDestroy()](/api/Global/Core-Suppressions/SefiraBossBase#ondestroy), [IsReadyToClose()](/api/Global/Core-Suppressions/SefiraBossBase#isreadytoclose), [GetDamageInfo()](/api/Global/Core-Suppressions/SefiraBossBase#getdamageinfo), [GetDefenseInfo()](/api/Global/Core-Suppressions/SefiraBossBase#getdefenseinfo), [GetDescFreq()](/api/Global/Core-Suppressions/SefiraBossBase#getdescfreq), [ClearDescTexts()](/api/Global/Core-Suppressions/SefiraBossBase#cleardesctexts), [MakeSound(string)](/api/Global/Core-Suppressions/SefiraBossBase#makesound-string), [MakeSoundAttachCamera(string)](/api/Global/Core-Suppressions/SefiraBossBase#makesoundattachcamera-string), [IsStartEmergencyBgm()](/api/Global/Core-Suppressions/SefiraBossBase#isstartemergencybgm), [QliphothOverloadLevel](/api/Global/Core-Suppressions/SefiraBossBase#qliphothoverloadlevel), [Sefira](/api/Global/Core-Suppressions/SefiraBossBase#sefira), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)







