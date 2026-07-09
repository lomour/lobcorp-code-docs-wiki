---
uid: Global.SlimeGirlWeaponDebuf
canonical_path: /api/Global/UnitBuf/SlimeGirlWeaponDebuf
---
# Class SlimeGirlWeaponDebuf
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SlimeGirlWeaponDebuf : UnitBuf
```
> This section may have incomplete or incorrect information.
{.is-warning}


Debuff applied by [Adoration (weapon)](/api/Global/Abnormalities/Melting-Love/Equipment/SlimeGirlWeapon).

Slows movement to 0.7x and does 2 black damage every second for 5 seconds. (Also, spawns an extra [damage effect](/api/Global/Damage/Visual-Effects/DamageParticleEffect)...)


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitBuf](/api/Global/Buffs/UnitBuf) → SlimeGirlWeaponDebuf

## Constructors
### SlimeGirlWeaponDebuf()
```csharp
public SlimeGirlWeaponDebuf()
```


## Fields
### _dmg
```csharp
private const float _dmg = 2
```


#### Field Value
**Type:** System.Single

### _dmgType
```csharp
private RwbpType _dmgType
```


#### Field Value
**Type:** Global.RwbpType

### _remain
```csharp
private const float _remain = 5
```


#### Field Value
**Type:** System.Single

### _tickTime
```csharp
private const float _tickTime = 1
```


#### Field Value
**Type:** System.Single

### tickTimer
```csharp
private Timer tickTimer
```


#### Field Value
**Type:** Global.Timer

## Methods
### FixedUpdate()
```csharp
public override void FixedUpdate()
```


### Init(UnitModel)
```csharp
public override void Init(UnitModel model)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.UnitModel` |  |

### MovementScale()
```csharp
public override float MovementScale()
```


#### Returns
**Type:** System.Single

### OnUnitDie()
```csharp
public override void OnUnitDie()
```


## Inherited Members
[type](/api/Global/Buffs/UnitBuf#type), [remainTime](/api/Global/Buffs/UnitBuf#remaintime), [model](/api/Global/Buffs/UnitBuf#model), [effectSrc](/api/Global/Buffs/UnitBuf#effectsrc), [duplicateType](/api/Global/Buffs/UnitBuf#duplicatetype), [Destroy()](/api/Global/Buffs/UnitBuf#destroy), [OnDestroy()](/api/Global/Buffs/UnitBuf#ondestroy), [OnUnitPanic()](/api/Global/Buffs/UnitBuf#onunitpanic), [OnStageRelease()](/api/Global/Buffs/UnitBuf#onstagerelease), [OnTakeDamage(UnitModel, DamageInfo)](/api/Global/Buffs/UnitBuf#ontakedamage-unitmodel-damageinfo), [GetDamageFactor()](/api/Global/Buffs/UnitBuf#getdamagefactor), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Buffs/UnitBuf#getdamagefactor-unitmodel-damageinfo), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/Global/Buffs/UnitBuf#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Buffs/UnitBuf#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/Buffs/UnitBuf#ongivedamageafter-unitmodel-unitmodel-damageinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)






