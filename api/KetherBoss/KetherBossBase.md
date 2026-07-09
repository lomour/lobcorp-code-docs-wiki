---
uid: KetherBoss.KetherBossBase
canonical_path: /api/KetherBoss/KetherBossBase
---
# Class KetherBossBase
**Namespace:** [KetherBoss](/api/KetherBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class KetherBossBase : SefiraBossBase
```
> This section may have incomplete or incorrect information.
{.is-warning}

Parent class for day 46-50 suppressions


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [SefiraBossBase](/api/Global/Core-Suppressions/SefiraBossBase) → KetherBossBase

## Derived
[KetherLastBossBase](/api/KetherBoss/KetherLastBossBase), [KetherLowerBossBase](/api/KetherBoss/KetherLowerBossBase), [KetherMiddleBossBase](/api/KetherBoss/KetherMiddleBossBase), [KetherUpperBossBase](/api/KetherBoss/KetherUpperBossBase), [KetherZeroBossBase](/api/KetherBoss/KetherZeroBossBase)

## Constructors
### KetherBossBase()
```csharp
public KetherBossBase()
```

## Fields
### _currentQliphothLevel
```csharp
protected int _currentQliphothLevel
```


#### Field Value
**Type:** System.Int32

### bossBaseList
```csharp
public List<SefiraBossBase> bossBaseList
```


#### Field Value
**Type:** System.Collections.Generic.List{SefiraBossBase}

### builder
```csharp
protected StringBuilder builder
```


#### Field Value
**Type:** System.Text.StringBuilder

### ModelHPFactor
```csharp
public const float ModelHPFactor = 0.6
```


#### Field Value
**Type:** System.Single

### type
```csharp
public KetherBossType type
```


#### Field Value
**Type:** Global.KetherBossType

## Properties
### QliphothOverloadLevel
```csharp
public override int QliphothOverloadLevel { get; }
```

#### Property Value
**Type:** System.Int32

## Methods
### FixedUpdate()
```csharp
public override void FixedUpdate()
```


### OnCleared()
```csharp
public override void OnCleared()
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


### StringFormat(string, params object[])
```csharp
public string StringFormat(string format, params object[] param)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `format` | `System.String` |  |
| `param` | `System.Object[]` |  |

#### Returns
**Type:** System.String

### Update()
```csharp
public override void Update()
```


## Inherited Members
[_closeEffectTime](/api/Global/Core-Suppressions/SefiraBossBase#closeeffecttime), [_defaultDescFreq](/api/Global/Core-Suppressions/SefiraBossBase#defaultdescfreq), [_descAppearProb](/api/Global/Core-Suppressions/SefiraBossBase#descappearprob), [generalScript](/api/Global/Core-Suppressions/SefiraBossBase#generalscript), [generalAnim](/api/Global/Core-Suppressions/SefiraBossBase#generalanim), [bgmSoundPrefix](/api/Global/Core-Suppressions/SefiraBossBase#bgmsoundprefix), [currentCloseEffectParam](/api/Global/Core-Suppressions/SefiraBossBase#currentcloseeffectparam), [modelList](/api/Global/Core-Suppressions/SefiraBossBase#modellist), [sefiraEnum](/api/Global/Core-Suppressions/SefiraBossBase#sefiraenum), [closeEffectType](/api/Global/Core-Suppressions/SefiraBossBase#closeeffecttype), [DefaultDamageInfo](/api/Global/Core-Suppressions/SefiraBossBase#defaultdamageinfo), [DefaultDefenseInfo](/api/Global/Core-Suppressions/SefiraBossBase#defaultdefenseinfo), [_closeTimer](/api/Global/Core-Suppressions/SefiraBossBase#closetimer), [_closeEffectMethod](/api/Global/Core-Suppressions/SefiraBossBase#closeeffectmethod), [_cameraDescTimer](/api/Global/Core-Suppressions/SefiraBossBase#cameradesctimer), [descList](/api/Global/Core-Suppressions/SefiraBossBase#desclist), [OnKetherStart()](/api/Global/Core-Suppressions/SefiraBossBase#onketherstart), [OnStageEnd()](/api/Global/Core-Suppressions/SefiraBossBase#onstageend), [OnRemoveDesc(SefiraBossDescUI)](/api/Global/Core-Suppressions/SefiraBossBase#onremovedesc-sefirabossdescui), [DefaultClearEffect(params object[])](/api/Global/Core-Suppressions/SefiraBossBase#defaultcleareffect-params-object), [OnDestroy()](/api/Global/Core-Suppressions/SefiraBossBase#ondestroy), [IsCleared()](/api/Global/Core-Suppressions/SefiraBossBase#iscleared), [IsReadyToClose()](/api/Global/Core-Suppressions/SefiraBossBase#isreadytoclose), [GetDamageInfo()](/api/Global/Core-Suppressions/SefiraBossBase#getdamageinfo), [GetDefenseInfo()](/api/Global/Core-Suppressions/SefiraBossBase#getdefenseinfo), [GetDescType(float)](/api/Global/Core-Suppressions/SefiraBossBase#getdesctype-float), [GetDescFreq()](/api/Global/Core-Suppressions/SefiraBossBase#getdescfreq), [OnChangePhase()](/api/Global/Core-Suppressions/SefiraBossBase#onchangephase), [ClearDescTexts()](/api/Global/Core-Suppressions/SefiraBossBase#cleardesctexts), [MakeSound(string)](/api/Global/Core-Suppressions/SefiraBossBase#makesound-string), [MakeSoundAttachCamera(string)](/api/Global/Core-Suppressions/SefiraBossBase#makesoundattachcamera-string), [IsStartEmergencyBgm()](/api/Global/Core-Suppressions/SefiraBossBase#isstartemergencybgm), [Sefira](/api/Global/Core-Suppressions/SefiraBossBase#sefira), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)










