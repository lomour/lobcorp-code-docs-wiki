---
uid: Global.MalkutBossBase
canonical_path: /api/Global/Misc/MalkutBossBase
---
# Class MalkutBossBase
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class MalkutBossBase : SefiraBossBase
```
> This section may have incomplete or incorrect information.
{.is-warning}


Malkuth's core suppression.




## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [SefiraBossBase](/api/Global/Core-Suppressions/SefiraBossBase) → MalkutBossBase

## Constructors
### MalkutBossBase()
```csharp
public MalkutBossBase()
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
private const string animSrc = "MalkutCoreAnim"
```


#### Field Value
**Type:** System.String

### auraDistortion
```csharp
private CameraFilterPack_Vision_AuraDistortion auraDistortion
```


#### Field Value
**Type:** Global.CameraFilterPack_Vision_AuraDistortion

### bgm1
```csharp
private const string bgm1 = "Malkuth/1_Tilarids - Violation Of Black Colors"
```


#### Field Value
**Type:** System.String

### bgm2
```csharp
private const string bgm2 = "Malkuth/2_Tilarids - Red Dots"
```


#### Field Value
**Type:** System.String

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

### grain
```csharp
private CameraFilterPack_Film_Grain grain
```


#### Field Value
**Type:** Global.CameraFilterPack_Film_Grain

### malkutBase
```csharp
private const string malkutBase = "MalkutCoreScript"
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
private const string phaseSound = "SefiraBoss/Boss_Malkut"
```


#### Field Value
**Type:** System.String

### psycho
```csharp
private CameraFilterPack_Vision_Psycho psycho
```


#### Field Value
**Type:** Global.CameraFilterPack_Vision_Psycho

### totalEnergy
```csharp
private float totalEnergy
```


#### Field Value
**Type:** System.Single

## Properties
### Script
```csharp
private MalkutCoreScript Script { get; }
```

#### Property Value
**Type:** Global.MalkutCoreScript

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


### StartEffect()
```csharp
public void StartEffect()
```


## Inherited Members
[_closeEffectTime](/api/Global/Core-Suppressions/SefiraBossBase#closeeffecttime), [_defaultDescFreq](/api/Global/Core-Suppressions/SefiraBossBase#defaultdescfreq), [_descAppearProb](/api/Global/Core-Suppressions/SefiraBossBase#descappearprob), [generalScript](/api/Global/Core-Suppressions/SefiraBossBase#generalscript), [generalAnim](/api/Global/Core-Suppressions/SefiraBossBase#generalanim), [bgmSoundPrefix](/api/Global/Core-Suppressions/SefiraBossBase#bgmsoundprefix), [currentCloseEffectParam](/api/Global/Core-Suppressions/SefiraBossBase#currentcloseeffectparam), [modelList](/api/Global/Core-Suppressions/SefiraBossBase#modellist), [sefiraEnum](/api/Global/Core-Suppressions/SefiraBossBase#sefiraenum), [closeEffectType](/api/Global/Core-Suppressions/SefiraBossBase#closeeffecttype), [DefaultDamageInfo](/api/Global/Core-Suppressions/SefiraBossBase#defaultdamageinfo), [DefaultDefenseInfo](/api/Global/Core-Suppressions/SefiraBossBase#defaultdefenseinfo), [_closeTimer](/api/Global/Core-Suppressions/SefiraBossBase#closetimer), [_closeEffectMethod](/api/Global/Core-Suppressions/SefiraBossBase#closeeffectmethod), [_cameraDescTimer](/api/Global/Core-Suppressions/SefiraBossBase#cameradesctimer), [descList](/api/Global/Core-Suppressions/SefiraBossBase#desclist), [OnStageEnd()](/api/Global/Core-Suppressions/SefiraBossBase#onstageend), [OnRemoveDesc(SefiraBossDescUI)](/api/Global/Core-Suppressions/SefiraBossBase#onremovedesc-sefirabossdescui), [Update()](/api/Global/Core-Suppressions/SefiraBossBase#update), [DefaultClearEffect(params object[])](/api/Global/Core-Suppressions/SefiraBossBase#defaultcleareffect-params-object), [OnDestroy()](/api/Global/Core-Suppressions/SefiraBossBase#ondestroy), [IsReadyToClose()](/api/Global/Core-Suppressions/SefiraBossBase#isreadytoclose), [GetDamageInfo()](/api/Global/Core-Suppressions/SefiraBossBase#getdamageinfo), [GetDefenseInfo()](/api/Global/Core-Suppressions/SefiraBossBase#getdefenseinfo), [GetDescType(float)](/api/Global/Core-Suppressions/SefiraBossBase#getdesctype-float), [ClearDescTexts()](/api/Global/Core-Suppressions/SefiraBossBase#cleardesctexts), [MakeSound(string)](/api/Global/Core-Suppressions/SefiraBossBase#makesound-string), [MakeSoundAttachCamera(string)](/api/Global/Core-Suppressions/SefiraBossBase#makesoundattachcamera-string), [IsStartEmergencyBgm()](/api/Global/Core-Suppressions/SefiraBossBase#isstartemergencybgm), [QliphothOverloadLevel](/api/Global/Core-Suppressions/SefiraBossBase#qliphothoverloadlevel), [Sefira](/api/Global/Core-Suppressions/SefiraBossBase#sefira), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)







