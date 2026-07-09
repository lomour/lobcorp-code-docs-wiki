---
uid: Global.CensoredWeapon
canonical_path: /api/Global/Weapon/CensoredWeapon
---
# Class CensoredWeapon
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CensoredWeapon : EquipmentScriptBase
```
> This section may have incomplete or incorrect information.
{.is-warning}


Script for [CENSORED](/api/Global/Abnormalities/CENSORED/Censored)'s EGO Weapon: CENSORED. Heals 40% of damage taken.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [EquipmentScriptBase](/api/Global/EGO/EquipmentScriptBase) → CensoredWeapon

## Constructors
### CensoredWeapon()
```csharp
public CensoredWeapon()
```


## Fields
### _defaultRange
```csharp
private const int _defaultRange = 3
```


#### Field Value
**Type:** System.Int32

### _healRatio
```csharp
private const float _healRatio = 0.4
```


#### Field Value
**Type:** System.Single

### _specialProb
```csharp
private const float _specialProb = 0.1
```


#### Field Value
**Type:** System.Single

### _specialRange
```csharp
private const int _specialRange = 10
```


#### Field Value
**Type:** System.Int32

### defaultInfo
```csharp
private SplashInfo defaultInfo
```


#### Field Value
**Type:** Global.SplashInfo

### hp_old
```csharp
private float hp_old
```


#### Field Value
**Type:** System.Single

### isSpecial
```csharp
private bool isSpecial
```


#### Field Value
**Type:** System.Boolean

### mp_old
```csharp
private float mp_old
```


#### Field Value
**Type:** System.Single

### specialInfo
```csharp
private SplashInfo specialInfo
```


#### Field Value
**Type:** Global.SplashInfo

## Methods
### OnAttackEnd(UnitModel, UnitModel)
```csharp
public override void OnAttackEnd(UnitModel actor, UnitModel target)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |
| `target` | `Global.UnitModel` |  |

### OnAttackStart(UnitModel, UnitModel)
```csharp
public override EquipmentScriptBase.WeaponDamageInfo OnAttackStart(UnitModel actor, UnitModel target)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |
| `target` | `Global.UnitModel` |  |

#### Returns
**Type:** Global.EquipmentScriptBase.WeaponDamageInfo

### OnStageStart()
```csharp
public override void OnStageStart()
```


### OnTakeDamage(UnitModel, ref DamageInfo)
```csharp
public override bool OnTakeDamage(UnitModel actor, ref DamageInfo dmg)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |
| `dmg` | `Global.DamageInfo` |  |

#### Returns
**Type:** System.Boolean

### OnTakeDamage_After(float, RwbpType)
```csharp
public override bool OnTakeDamage_After(float value, RwbpType type)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Single` |  |
| `type` | `Global.RwbpType` |  |

#### Returns
**Type:** System.Boolean

### SetNextAttackType()
```csharp
private void SetNextAttackType()
```


## Inherited Members
[_model](/api/Global/EGO/EquipmentScriptBase#model), [_reinforcementLevel](/api/Global/EGO/EquipmentScriptBase#reinforcementlevel), [MAX_REINFORCEMENT_LEVEL](/api/Global/EGO/EquipmentScriptBase#max-reinforcement-level), [SetModel(EquipmentModel)](/api/Global/EGO/EquipmentScriptBase#setmodel-equipmentmodel), [OnEquip(UnitModel)](/api/Global/EGO/EquipmentScriptBase#onequip-unitmodel), [OnRelease()](/api/Global/EGO/EquipmentScriptBase#onrelease), [OnStageRelease()](/api/Global/EGO/EquipmentScriptBase#onstagerelease), [OnPrepareWeapon(UnitModel)](/api/Global/EGO/EquipmentScriptBase#onprepareweapon-unitmodel), [OnCancelWeapon(UnitModel)](/api/Global/EGO/EquipmentScriptBase#oncancelweapon-unitmodel), [OnKillMainTarget(UnitModel, UnitModel)](/api/Global/EGO/EquipmentScriptBase#onkillmaintarget-unitmodel-unitmodel), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/Global/EGO/EquipmentScriptBase#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/EGO/EquipmentScriptBase#ongivedamageafter-unitmodel-unitmodel-damageinfo), [GetReinforcementDmg()](/api/Global/EGO/EquipmentScriptBase#getreinforcementdmg), [AddReinforcementLevel(int)](/api/Global/EGO/EquipmentScriptBase#addreinforcementlevel-int), [GetDefense(UnitModel)](/api/Global/EGO/EquipmentScriptBase#getdefense-unitmodel), [GetDamageFactor()](/api/Global/EGO/EquipmentScriptBase#getdamagefactor), [GetDamage(UnitModel)](/api/Global/EGO/EquipmentScriptBase#getdamage-unitmodel), [OnFixedUpdate()](/api/Global/EGO/EquipmentScriptBase#onfixedupdate), [GetBonus(UnitModel)](/api/Global/EGO/EquipmentScriptBase#getbonus-unitmodel), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/EGO/EquipmentScriptBase#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OwnerHeal(bool, ref float)](/api/Global/EGO/EquipmentScriptBase#ownerheal-bool-ref-float), [model](/api/Global/EGO/EquipmentScriptBase#model), [reinforcementLevel](/api/Global/EGO/EquipmentScriptBase#reinforcementlevel), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)








