---
uid: Global.SingingMachineWeapon
canonical_path: /api/Global/Weapon/SingingMachineWeapon
---
# Class SingingMachineWeapon
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SingingMachineWeapon : EquipmentScriptBase
```
> This section may have incomplete or incorrect information.
{.is-warning}


Script for [Singing Machine's](/api/Global/Abnormalities/Singing-Machine/SingingMachine) EGO Weapon: Harmony.

If the user has more than 10% HP, reduces current HP by 10% and does a special attack. Special attack has 30% higher minimum and maximum damage.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [EquipmentScriptBase](/api/Global/EGO/EquipmentScriptBase) → SingingMachineWeapon

## Constructors
### SingingMachineWeapon()
```csharp
public SingingMachineWeapon()
```

## Fields
### _buf_ratio
```csharp
private const float _buf_ratio = 1.3
```


#### Field Value
**Type:** System.Single

### _hp_condition
```csharp
private const float _hp_condition = 0.1
```


#### Field Value
**Type:** System.Single

### _hp_cost
```csharp
private const float _hp_cost = 0.1
```


#### Field Value
**Type:** System.Single

### isSpecial
```csharp
private bool isSpecial
```


#### Field Value
**Type:** System.Boolean

## Methods
### GetDamage(UnitModel)
```csharp
public override DamageInfo GetDamage(UnitModel actor)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |

#### Returns
**Type:** Global.DamageInfo

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

### OnStageRelease()
```csharp
public override void OnStageRelease()
```


### OnStageStart()
```csharp
public override void OnStageStart()
```


## Inherited Members
[_model](/api/Global/EGO/EquipmentScriptBase#model), [_reinforcementLevel](/api/Global/EGO/EquipmentScriptBase#reinforcementlevel), [MAX_REINFORCEMENT_LEVEL](/api/Global/EGO/EquipmentScriptBase#max-reinforcement-level), [SetModel(EquipmentModel)](/api/Global/EGO/EquipmentScriptBase#setmodel-equipmentmodel), [OnEquip(UnitModel)](/api/Global/EGO/EquipmentScriptBase#onequip-unitmodel), [OnRelease()](/api/Global/EGO/EquipmentScriptBase#onrelease), [OnPrepareWeapon(UnitModel)](/api/Global/EGO/EquipmentScriptBase#onprepareweapon-unitmodel), [OnCancelWeapon(UnitModel)](/api/Global/EGO/EquipmentScriptBase#oncancelweapon-unitmodel), [OnKillMainTarget(UnitModel, UnitModel)](/api/Global/EGO/EquipmentScriptBase#onkillmaintarget-unitmodel-unitmodel), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/Global/EGO/EquipmentScriptBase#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/EGO/EquipmentScriptBase#ongivedamageafter-unitmodel-unitmodel-damageinfo), [OnTakeDamage(UnitModel, ref DamageInfo)](/api/Global/EGO/EquipmentScriptBase#ontakedamage-unitmodel-ref-damageinfo), [OnTakeDamage_After(float, RwbpType)](/api/Global/EGO/EquipmentScriptBase#ontakedamage-after-float-rwbptype), [GetReinforcementDmg()](/api/Global/EGO/EquipmentScriptBase#getreinforcementdmg), [AddReinforcementLevel(int)](/api/Global/EGO/EquipmentScriptBase#addreinforcementlevel-int), [GetDefense(UnitModel)](/api/Global/EGO/EquipmentScriptBase#getdefense-unitmodel), [GetDamageFactor()](/api/Global/EGO/EquipmentScriptBase#getdamagefactor), [OnFixedUpdate()](/api/Global/EGO/EquipmentScriptBase#onfixedupdate), [GetBonus(UnitModel)](/api/Global/EGO/EquipmentScriptBase#getbonus-unitmodel), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/EGO/EquipmentScriptBase#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OwnerHeal(bool, ref float)](/api/Global/EGO/EquipmentScriptBase#ownerheal-bool-ref-float), [model](/api/Global/EGO/EquipmentScriptBase#model), [reinforcementLevel](/api/Global/EGO/EquipmentScriptBase#reinforcementlevel), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)







