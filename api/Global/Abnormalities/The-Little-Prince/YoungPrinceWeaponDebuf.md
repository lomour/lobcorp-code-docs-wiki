---
uid: Global.YoungPrinceWeaponDebuf
canonical_path: /api/Global/UnitBuf/YoungPrinceWeaponDebuf
---
# Class YoungPrinceWeaponDebuf
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class YoungPrinceWeaponDebuf : UnitBuf
```
> This section may have incomplete or incorrect information.
{.is-warning}


Applied by [Spore](/api/Global/Abnormalities/The-Little-Prince/YoungPrinceWeapon).

Increases white damage taken by 50% for 3 seconds.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitBuf](/api/Global/Buffs/UnitBuf) → YoungPrinceWeaponDebuf

## Constructors
### YoungPrinceWeaponDebuf()
```csharp
public YoungPrinceWeaponDebuf()
```


## Fields
### _debufDmgRatio
```csharp
private const float _debufDmgRatio = 1.5
```


#### Field Value
**Type:** System.Single

### _remain_time
```csharp
private const float _remain_time = 3
```


#### Field Value
**Type:** System.Single

### _targetType
```csharp
private const RwbpType _targetType = W
```


#### Field Value
**Type:** Global.RwbpType

## Methods
### Init(UnitModel)
```csharp
public override void Init(UnitModel model)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.UnitModel` |  |

### OnTakeDamage(UnitModel, DamageInfo)
```csharp
public override float OnTakeDamage(UnitModel attacker, DamageInfo damageInfo)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `attacker` | `Global.UnitModel` |  |
| `damageInfo` | `Global.DamageInfo` |  |

#### Returns
**Type:** System.Single

## Inherited Members
[type](/api/Global/Buffs/UnitBuf#type), [remainTime](/api/Global/Buffs/UnitBuf#remaintime), [model](/api/Global/Buffs/UnitBuf#model), [effectSrc](/api/Global/Buffs/UnitBuf#effectsrc), [duplicateType](/api/Global/Buffs/UnitBuf#duplicatetype), [FixedUpdate()](/api/Global/Buffs/UnitBuf#fixedupdate), [Destroy()](/api/Global/Buffs/UnitBuf#destroy), [OnDestroy()](/api/Global/Buffs/UnitBuf#ondestroy), [MovementScale()](/api/Global/Buffs/UnitBuf#movementscale), [OnUnitDie()](/api/Global/Buffs/UnitBuf#onunitdie), [OnUnitPanic()](/api/Global/Buffs/UnitBuf#onunitpanic), [OnStageRelease()](/api/Global/Buffs/UnitBuf#onstagerelease), [GetDamageFactor()](/api/Global/Buffs/UnitBuf#getdamagefactor), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Buffs/UnitBuf#getdamagefactor-unitmodel-damageinfo), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/Global/Buffs/UnitBuf#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Buffs/UnitBuf#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/Buffs/UnitBuf#ongivedamageafter-unitmodel-unitmodel-damageinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)







