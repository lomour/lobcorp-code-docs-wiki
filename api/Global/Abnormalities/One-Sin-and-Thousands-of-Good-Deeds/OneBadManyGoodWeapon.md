---
uid: Global.OneBadManyGoodWeapon
canonical_path: /api/Global/Weapon/OneBadManyGoodWeapon
---
# Class OneBadManyGoodWeapon
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class OneBadManyGoodWeapon : EquipmentScriptBase
```
> This section may have incomplete or incorrect information.
{.is-warning}


Script for [One Sin and Thousands of Good Deeds](/api/Global/Abnormalities/One-Sin-and-Thousands-of-Good-Deeds/OneBadManyGood)'s EGO Weapon: Penitence.

If the user has at least 2 fortitude, recovers 10 SP at a 5% chance on hit.


Also, prints to log when equipped, when dealing damage, and when recovering SP.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [EquipmentScriptBase](/api/Global/EGO/EquipmentScriptBase) → OneBadManyGoodWeapon

## Constructors
### OneBadManyGoodWeapon()
```csharp
public OneBadManyGoodWeapon()
```

## Fields
### _AMOUNT_RECOVER_MENTAL
```csharp
private readonly float _AMOUNT_RECOVER_MENTAL
```


#### Field Value
**Type:** System.Single

### _CONDITION_FORTITUDE_LEVEL
```csharp
private readonly int _CONDITION_FORTITUDE_LEVEL
```


#### Field Value
**Type:** System.Int32

### _LOG_STATE
```csharp
private readonly bool _LOG_STATE
```


#### Field Value
**Type:** System.Boolean

### _PROB_RECOVERY_MENTAL
```csharp
private readonly float _PROB_RECOVERY_MENTAL
```


#### Field Value
**Type:** System.Single

## Methods
### OnEquip(UnitModel)
```csharp
public override void OnEquip(UnitModel actor)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |

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

### PrintLog(string)
```csharp
private void PrintLog(string s)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `s` | `System.String` |  |

## Inherited Members
[_model](/api/Global/EGO/EquipmentScriptBase#model), [_reinforcementLevel](/api/Global/EGO/EquipmentScriptBase#reinforcementlevel), [MAX_REINFORCEMENT_LEVEL](/api/Global/EGO/EquipmentScriptBase#max-reinforcement-level), [SetModel(EquipmentModel)](/api/Global/EGO/EquipmentScriptBase#setmodel-equipmentmodel), [OnRelease()](/api/Global/EGO/EquipmentScriptBase#onrelease), [OnStageStart()](/api/Global/EGO/EquipmentScriptBase#onstagestart), [OnStageRelease()](/api/Global/EGO/EquipmentScriptBase#onstagerelease), [OnPrepareWeapon(UnitModel)](/api/Global/EGO/EquipmentScriptBase#onprepareweapon-unitmodel), [OnCancelWeapon(UnitModel)](/api/Global/EGO/EquipmentScriptBase#oncancelweapon-unitmodel), [OnAttackStart(UnitModel, UnitModel)](/api/Global/EGO/EquipmentScriptBase#onattackstart-unitmodel-unitmodel), [OnAttackEnd(UnitModel, UnitModel)](/api/Global/EGO/EquipmentScriptBase#onattackend-unitmodel-unitmodel), [OnKillMainTarget(UnitModel, UnitModel)](/api/Global/EGO/EquipmentScriptBase#onkillmaintarget-unitmodel-unitmodel), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/EGO/EquipmentScriptBase#ongivedamageafter-unitmodel-unitmodel-damageinfo), [OnTakeDamage(UnitModel, ref DamageInfo)](/api/Global/EGO/EquipmentScriptBase#ontakedamage-unitmodel-ref-damageinfo), [OnTakeDamage_After(float, RwbpType)](/api/Global/EGO/EquipmentScriptBase#ontakedamage-after-float-rwbptype), [GetReinforcementDmg()](/api/Global/EGO/EquipmentScriptBase#getreinforcementdmg), [AddReinforcementLevel(int)](/api/Global/EGO/EquipmentScriptBase#addreinforcementlevel-int), [GetDefense(UnitModel)](/api/Global/EGO/EquipmentScriptBase#getdefense-unitmodel), [GetDamageFactor()](/api/Global/EGO/EquipmentScriptBase#getdamagefactor), [GetDamage(UnitModel)](/api/Global/EGO/EquipmentScriptBase#getdamage-unitmodel), [OnFixedUpdate()](/api/Global/EGO/EquipmentScriptBase#onfixedupdate), [GetBonus(UnitModel)](/api/Global/EGO/EquipmentScriptBase#getbonus-unitmodel), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/EGO/EquipmentScriptBase#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OwnerHeal(bool, ref float)](/api/Global/EGO/EquipmentScriptBase#ownerheal-bool-ref-float), [model](/api/Global/EGO/EquipmentScriptBase#model), [reinforcementLevel](/api/Global/EGO/EquipmentScriptBase#reinforcementlevel), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)







