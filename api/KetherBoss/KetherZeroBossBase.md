---
uid: KetherBoss.KetherZeroBossBase
canonical_path: /api/KetherBoss/KetherZeroBossBase
---
# Class KetherZeroBossBase
**Namespace:** [KetherBoss](/api/KetherBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class KetherZeroBossBase : KetherBossBase, IObserver
```
> This section may have incomplete or incorrect information.
{.is-warning}

Day 46 suppression


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [SefiraBossBase](/api/Global/Core-Suppressions/SefiraBossBase) → [KetherBossBase](/api/KetherBoss/KetherBossBase) → KetherZeroBossBase

## Implements
[IObserver](/api/Global/Notices/IObserver)

## Constructors
### KetherZeroBossBase()
```csharp
public KetherZeroBossBase()
```


## Fields
### _clawAppeared
```csharp
private bool _clawAppeared
```


#### Field Value
**Type:** System.Boolean

### _clawSuppressed
```csharp
private bool _clawSuppressed
```


#### Field Value
**Type:** System.Boolean

### clearQliphothLevel
```csharp
private const int clearQliphothLevel = 10
```


#### Field Value
**Type:** System.Int32

### fixerClaw
```csharp
private FixerClaw fixerClaw
```


#### Field Value
**Type:** Global.FixerClaw

### max
```csharp
private float max
```


#### Field Value
**Type:** System.Single

## Methods
### IsCleared()
```csharp
public override bool IsCleared()
```


#### Returns
**Type:** System.Boolean

### IsReadyToClose()
```csharp
public override bool IsReadyToClose()
```


#### Returns
**Type:** System.Boolean

### OnDestroy()
```csharp
public override void OnDestroy()
```


### OnFixerClawSuppressed()
```csharp
public void OnFixerClawSuppressed()
```


### OnNotice(string, params object[])
```csharp
public void OnNotice(string notice, params object[] param)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `notice` | `System.String` |  |
| `param` | `System.Object[]` |  |

### OnStageStart()
```csharp
public override void OnStageStart()
```


## Inherited Members
[ModelHPFactor](/api/KetherBoss/KetherBossBase#modelhpfactor), [type](/api/KetherBoss/KetherBossBase#type), [builder](/api/KetherBoss/KetherBossBase#builder), [bossBaseList](/api/KetherBoss/KetherBossBase#bossbaselist), [_currentQliphothLevel](/api/KetherBoss/KetherBossBase#currentqliphothlevel), [StringFormat(string, params object[])](/api/KetherBoss/KetherBossBase#stringformat-string-params-object), [OnCleared()](/api/KetherBoss/KetherBossBase#oncleared), [Update()](/api/KetherBoss/KetherBossBase#update), [FixedUpdate()](/api/KetherBoss/KetherBossBase#fixedupdate), [OnOverloadActivated(int)](/api/KetherBoss/KetherBossBase#onoverloadactivated-int), [QliphothOverloadLevel](/api/KetherBoss/KetherBossBase#qliphothoverloadlevel), [_closeEffectTime](/api/Global/Core-Suppressions/SefiraBossBase#closeeffecttime), [_defaultDescFreq](/api/Global/Core-Suppressions/SefiraBossBase#defaultdescfreq), [_descAppearProb](/api/Global/Core-Suppressions/SefiraBossBase#descappearprob), [generalScript](/api/Global/Core-Suppressions/SefiraBossBase#generalscript), [generalAnim](/api/Global/Core-Suppressions/SefiraBossBase#generalanim), [bgmSoundPrefix](/api/Global/Core-Suppressions/SefiraBossBase#bgmsoundprefix), [currentCloseEffectParam](/api/Global/Core-Suppressions/SefiraBossBase#currentcloseeffectparam), [modelList](/api/Global/Core-Suppressions/SefiraBossBase#modellist), [sefiraEnum](/api/Global/Core-Suppressions/SefiraBossBase#sefiraenum), [closeEffectType](/api/Global/Core-Suppressions/SefiraBossBase#closeeffecttype), [DefaultDamageInfo](/api/Global/Core-Suppressions/SefiraBossBase#defaultdamageinfo), [DefaultDefenseInfo](/api/Global/Core-Suppressions/SefiraBossBase#defaultdefenseinfo), [_closeTimer](/api/Global/Core-Suppressions/SefiraBossBase#closetimer), [_closeEffectMethod](/api/Global/Core-Suppressions/SefiraBossBase#closeeffectmethod), [_cameraDescTimer](/api/Global/Core-Suppressions/SefiraBossBase#cameradesctimer), [descList](/api/Global/Core-Suppressions/SefiraBossBase#desclist), [OnKetherStart()](/api/Global/Core-Suppressions/SefiraBossBase#onketherstart), [OnStageEnd()](/api/Global/Core-Suppressions/SefiraBossBase#onstageend), [OnRemoveDesc(SefiraBossDescUI)](/api/Global/Core-Suppressions/SefiraBossBase#onremovedesc-sefirabossdescui), [DefaultClearEffect(params object[])](/api/Global/Core-Suppressions/SefiraBossBase#defaultcleareffect-params-object), [GetDamageInfo()](/api/Global/Core-Suppressions/SefiraBossBase#getdamageinfo), [GetDefenseInfo()](/api/Global/Core-Suppressions/SefiraBossBase#getdefenseinfo), [GetDescType(float)](/api/Global/Core-Suppressions/SefiraBossBase#getdesctype-float), [GetDescFreq()](/api/Global/Core-Suppressions/SefiraBossBase#getdescfreq), [OnChangePhase()](/api/Global/Core-Suppressions/SefiraBossBase#onchangephase), [ClearDescTexts()](/api/Global/Core-Suppressions/SefiraBossBase#cleardesctexts), [MakeSound(string)](/api/Global/Core-Suppressions/SefiraBossBase#makesound-string), [MakeSoundAttachCamera(string)](/api/Global/Core-Suppressions/SefiraBossBase#makesoundattachcamera-string), [IsStartEmergencyBgm()](/api/Global/Core-Suppressions/SefiraBossBase#isstartemergencybgm), [Sefira](/api/Global/Core-Suppressions/SefiraBossBase#sefira), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)










