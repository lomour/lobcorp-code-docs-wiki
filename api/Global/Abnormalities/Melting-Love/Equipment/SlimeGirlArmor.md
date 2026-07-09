---
uid: Global.SlimeGirlArmor
canonical_path: /api/Global/Armor/SlimeGirlArmor
---
# Class SlimeGirlArmor
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SlimeGirlArmor : EquipmentScriptBase
```
> This section may have incomplete or incorrect information.
{.is-warning}


Script for [Melting Love](/api/Global/Abnormalities/Melting-Love/SlimeGirl)'s EGO Suit: Adoration.

When the user has the corresponding EGO Gift and is at $\leq$ 20% HP, isn't on cooldown, and takes more than 10 damage:
- Give them a red shield (100 hp, 3 seconds)
- Slow them to 30% movements speed for 3 seconds
- Play a slime noise

Has a 12 second cooldown.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [EquipmentScriptBase](/api/Global/EGO/EquipmentScriptBase) → SlimeGirlArmor

## Constructors
### SlimeGirlArmor()
```csharp
public SlimeGirlArmor()
```

## Fields
### BARRIER_COOL_TIME
```csharp
private const float BARRIER_COOL_TIME = 12
```


#### Field Value
**Type:** System.Single

### BARRIER_TIME
```csharp
private const float BARRIER_TIME = 3
```


#### Field Value
**Type:** System.Single

### BARRIER_VALUE
```csharp
private const float BARRIER_VALUE = 100
```


#### Field Value
**Type:** System.Single

### barrierCoolTimer
```csharp
private Timer barrierCoolTimer
```


#### Field Value
**Type:** Global.Timer

### DMG_CONDITION
```csharp
private const float DMG_CONDITION = 10
```


#### Field Value
**Type:** System.Single

### HP_CONDITION
```csharp
private const float HP_CONDITION = 0.2
```


#### Field Value
**Type:** System.Single

### SLIME_GIFT_ID
```csharp
private const int SLIME_GIFT_ID = 400063
```


#### Field Value
**Type:** System.Int32

## Methods
### CheckCondition(WorkerModel)
```csharp
private bool CheckCondition(WorkerModel owner)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `owner` | `Global.WorkerModel` |  |

#### Returns
**Type:** System.Boolean

### GiveBarrier(WorkerModel)
```csharp
private void GiveBarrier(WorkerModel owner)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `owner` | `Global.WorkerModel` |  |

### OnFixedUpdate()
```csharp
public override void OnFixedUpdate()
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

## Inherited Members
[_model](/api/Global/EGO/EquipmentScriptBase#model), [_reinforcementLevel](/api/Global/EGO/EquipmentScriptBase#reinforcementlevel), [MAX_REINFORCEMENT_LEVEL](/api/Global/EGO/EquipmentScriptBase#max-reinforcement-level), [SetModel(EquipmentModel)](/api/Global/EGO/EquipmentScriptBase#setmodel-equipmentmodel), [OnEquip(UnitModel)](/api/Global/EGO/EquipmentScriptBase#onequip-unitmodel), [OnRelease()](/api/Global/EGO/EquipmentScriptBase#onrelease), [OnStageStart()](/api/Global/EGO/EquipmentScriptBase#onstagestart), [OnStageRelease()](/api/Global/EGO/EquipmentScriptBase#onstagerelease), [OnPrepareWeapon(UnitModel)](/api/Global/EGO/EquipmentScriptBase#onprepareweapon-unitmodel), [OnCancelWeapon(UnitModel)](/api/Global/EGO/EquipmentScriptBase#oncancelweapon-unitmodel), [OnAttackStart(UnitModel, UnitModel)](/api/Global/EGO/EquipmentScriptBase#onattackstart-unitmodel-unitmodel), [OnAttackEnd(UnitModel, UnitModel)](/api/Global/EGO/EquipmentScriptBase#onattackend-unitmodel-unitmodel), [OnKillMainTarget(UnitModel, UnitModel)](/api/Global/EGO/EquipmentScriptBase#onkillmaintarget-unitmodel-unitmodel), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/Global/EGO/EquipmentScriptBase#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/EGO/EquipmentScriptBase#ongivedamageafter-unitmodel-unitmodel-damageinfo), [OnTakeDamage_After(float, RwbpType)](/api/Global/EGO/EquipmentScriptBase#ontakedamage-after-float-rwbptype), [GetReinforcementDmg()](/api/Global/EGO/EquipmentScriptBase#getreinforcementdmg), [AddReinforcementLevel(int)](/api/Global/EGO/EquipmentScriptBase#addreinforcementlevel-int), [GetDefense(UnitModel)](/api/Global/EGO/EquipmentScriptBase#getdefense-unitmodel), [GetDamageFactor()](/api/Global/EGO/EquipmentScriptBase#getdamagefactor), [GetDamage(UnitModel)](/api/Global/EGO/EquipmentScriptBase#getdamage-unitmodel), [GetBonus(UnitModel)](/api/Global/EGO/EquipmentScriptBase#getbonus-unitmodel), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/EGO/EquipmentScriptBase#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OwnerHeal(bool, ref float)](/api/Global/EGO/EquipmentScriptBase#ownerheal-bool-ref-float), [model](/api/Global/EGO/EquipmentScriptBase#model), [reinforcementLevel](/api/Global/EGO/EquipmentScriptBase#reinforcementlevel), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)






