---
uid: Global.NamelessFetusWeapon
canonical_path: /api/Global/Weapon/NamelessFetusWeapon
---
# Class NamelessFetusWeapon
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class NamelessFetusWeapon : EquipmentScriptBase
```
> This section may have incomplete or incorrect information.
{.is-warning}


Script for [Nameless Fetus](/api/Global/Abnormalities/Nameless-Fetus/NamelessFetus)'s EGO Weapon: Syrinx.

Plays a *GOD-AWFUL* noise when it deals damage. Randomly selects from:
- Weapons/fetus1
- Weapons/fetus2
- Weapons/fetus3
- Weapons/fetus4


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [EquipmentScriptBase](/api/Global/EGO/EquipmentScriptBase) → NamelessFetusWeapon

## Constructors
### NamelessFetusWeapon()
```csharp
public NamelessFetusWeapon()
```

## Fields
### soundInit
```csharp
private bool soundInit
```


#### Field Value
**Type:** System.Boolean

### soundSrc
```csharp
private const string soundSrc = "Weapons/fetus"
```


#### Field Value
**Type:** System.String

### soundSrcCnt
```csharp
private const int soundSrcCnt = 3
```


#### Field Value
**Type:** System.Int32

## Methods
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

### OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)
```csharp
public override bool OnGiveDamage(UnitModel actor, UnitModel target, ref DamageInfo dmg)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |
| `target` | `Global.UnitModel` |  |
| `dmg` | `Global.DamageInfo` |  |

#### Returns
**Type:** System.Boolean

## Inherited Members
[_model](/api/Global/EGO/EquipmentScriptBase#model), [_reinforcementLevel](/api/Global/EGO/EquipmentScriptBase#reinforcementlevel), [MAX_REINFORCEMENT_LEVEL](/api/Global/EGO/EquipmentScriptBase#max-reinforcement-level), [SetModel(EquipmentModel)](/api/Global/EGO/EquipmentScriptBase#setmodel-equipmentmodel), [OnEquip(UnitModel)](/api/Global/EGO/EquipmentScriptBase#onequip-unitmodel), [OnRelease()](/api/Global/EGO/EquipmentScriptBase#onrelease), [OnStageStart()](/api/Global/EGO/EquipmentScriptBase#onstagestart), [OnStageRelease()](/api/Global/EGO/EquipmentScriptBase#onstagerelease), [OnPrepareWeapon(UnitModel)](/api/Global/EGO/EquipmentScriptBase#onprepareweapon-unitmodel), [OnCancelWeapon(UnitModel)](/api/Global/EGO/EquipmentScriptBase#oncancelweapon-unitmodel), [OnAttackEnd(UnitModel, UnitModel)](/api/Global/EGO/EquipmentScriptBase#onattackend-unitmodel-unitmodel), [OnKillMainTarget(UnitModel, UnitModel)](/api/Global/EGO/EquipmentScriptBase#onkillmaintarget-unitmodel-unitmodel), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/EGO/EquipmentScriptBase#ongivedamageafter-unitmodel-unitmodel-damageinfo), [OnTakeDamage(UnitModel, ref DamageInfo)](/api/Global/EGO/EquipmentScriptBase#ontakedamage-unitmodel-ref-damageinfo), [OnTakeDamage_After(float, RwbpType)](/api/Global/EGO/EquipmentScriptBase#ontakedamage-after-float-rwbptype), [GetReinforcementDmg()](/api/Global/EGO/EquipmentScriptBase#getreinforcementdmg), [AddReinforcementLevel(int)](/api/Global/EGO/EquipmentScriptBase#addreinforcementlevel-int), [GetDefense(UnitModel)](/api/Global/EGO/EquipmentScriptBase#getdefense-unitmodel), [GetDamageFactor()](/api/Global/EGO/EquipmentScriptBase#getdamagefactor), [GetDamage(UnitModel)](/api/Global/EGO/EquipmentScriptBase#getdamage-unitmodel), [OnFixedUpdate()](/api/Global/EGO/EquipmentScriptBase#onfixedupdate), [GetBonus(UnitModel)](/api/Global/EGO/EquipmentScriptBase#getbonus-unitmodel), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/EGO/EquipmentScriptBase#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OwnerHeal(bool, ref float)](/api/Global/EGO/EquipmentScriptBase#ownerheal-bool-ref-float), [model](/api/Global/EGO/EquipmentScriptBase#model), [reinforcementLevel](/api/Global/EGO/EquipmentScriptBase#reinforcementlevel), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)







