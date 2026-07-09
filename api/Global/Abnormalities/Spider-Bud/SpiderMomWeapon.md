---
uid: Global.SpiderMomWeapon
canonical_path: /api/Global/Weapon/SpiderMomWeapon
---
# Class SpiderMomWeapon
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SpiderMomWeapon : EquipmentScriptBase
```
> This section may have incomplete or incorrect information.
{.is-warning}


Script for [Spider Bud](/api/Global/Abnormalities/Spider-Bud/SpiderMom)'s EGO Weapon: Red Eyes.

(Prints debug text on equip.)

While held out, if the user has at least 4 fortitude ^\[verify\]^, gives a +2.5 movement speed buff for 30000 seconds or until put away.

Note that the description says this is supposed to be at least 2 fortitude.

(When put away, also prints a debug log.)


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [EquipmentScriptBase](/api/Global/EGO/EquipmentScriptBase) → SpiderMomWeapon

## Constructors
### SpiderMomWeapon()
```csharp
public SpiderMomWeapon()
```

## Fields
### _AMOUNT_MOVEMENT_SPEED
```csharp
private readonly float _AMOUNT_MOVEMENT_SPEED
```


#### Field Value
**Type:** System.Single

### _CONDITION_FORTITUDE_LEVEL
```csharp
private readonly int _CONDITION_FORTITUDE_LEVEL
```


#### Field Value
**Type:** System.Int32

### _DURATION_BUF
```csharp
private readonly float _DURATION_BUF
```


#### Field Value
**Type:** System.Single

### _LOG_STATE
```csharp
private readonly bool _LOG_STATE
```


#### Field Value
**Type:** System.Boolean

## Methods
### OnCancelWeapon(UnitModel)
```csharp
public override void OnCancelWeapon(UnitModel actor)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |

### OnEquip(UnitModel)
```csharp
public override void OnEquip(UnitModel actor)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |

### OnPrepareWeapon(UnitModel)
```csharp
public override void OnPrepareWeapon(UnitModel actor)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |

### PrintLog(string)
```csharp
private void PrintLog(string s)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `s` | `System.String` |  |

## Inherited Members
[_model](/api/Global/EGO/EquipmentScriptBase#model), [_reinforcementLevel](/api/Global/EGO/EquipmentScriptBase#reinforcementlevel), [MAX_REINFORCEMENT_LEVEL](/api/Global/EGO/EquipmentScriptBase#max-reinforcement-level), [SetModel(EquipmentModel)](/api/Global/EGO/EquipmentScriptBase#setmodel-equipmentmodel), [OnRelease()](/api/Global/EGO/EquipmentScriptBase#onrelease), [OnStageStart()](/api/Global/EGO/EquipmentScriptBase#onstagestart), [OnStageRelease()](/api/Global/EGO/EquipmentScriptBase#onstagerelease), [OnAttackStart(UnitModel, UnitModel)](/api/Global/EGO/EquipmentScriptBase#onattackstart-unitmodel-unitmodel), [OnAttackEnd(UnitModel, UnitModel)](/api/Global/EGO/EquipmentScriptBase#onattackend-unitmodel-unitmodel), [OnKillMainTarget(UnitModel, UnitModel)](/api/Global/EGO/EquipmentScriptBase#onkillmaintarget-unitmodel-unitmodel), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/Global/EGO/EquipmentScriptBase#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/EGO/EquipmentScriptBase#ongivedamageafter-unitmodel-unitmodel-damageinfo), [OnTakeDamage(UnitModel, ref DamageInfo)](/api/Global/EGO/EquipmentScriptBase#ontakedamage-unitmodel-ref-damageinfo), [OnTakeDamage_After(float, RwbpType)](/api/Global/EGO/EquipmentScriptBase#ontakedamage-after-float-rwbptype), [GetReinforcementDmg()](/api/Global/EGO/EquipmentScriptBase#getreinforcementdmg), [AddReinforcementLevel(int)](/api/Global/EGO/EquipmentScriptBase#addreinforcementlevel-int), [GetDefense(UnitModel)](/api/Global/EGO/EquipmentScriptBase#getdefense-unitmodel), [GetDamageFactor()](/api/Global/EGO/EquipmentScriptBase#getdamagefactor), [GetDamage(UnitModel)](/api/Global/EGO/EquipmentScriptBase#getdamage-unitmodel), [OnFixedUpdate()](/api/Global/EGO/EquipmentScriptBase#onfixedupdate), [GetBonus(UnitModel)](/api/Global/EGO/EquipmentScriptBase#getbonus-unitmodel), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/EGO/EquipmentScriptBase#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OwnerHeal(bool, ref float)](/api/Global/EGO/EquipmentScriptBase#ownerheal-bool-ref-float), [model](/api/Global/EGO/EquipmentScriptBase#model), [reinforcementLevel](/api/Global/EGO/EquipmentScriptBase#reinforcementlevel), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)







