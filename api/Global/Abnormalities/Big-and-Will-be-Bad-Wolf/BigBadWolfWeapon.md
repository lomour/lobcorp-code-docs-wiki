---
uid: Global.BigBadWolfWeapon
canonical_path: /api/Global/Weapon/BigBadWolfWeapon
---
# Class BigBadWolfWeapon
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BigBadWolfWeapon : EquipmentScriptBase
```
> This section may have incomplete or incorrect information.
{.is-warning}


Script for [Big and Will Be Bad Wolf](/api/Global/Abnormalities/Big-and-Will-be-Bad-Wolf/BigBadWolf)'s EGO Weapon: Cobalt Scar.




## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [EquipmentScriptBase](/api/Global/EGO/EquipmentScriptBase) → BigBadWolfWeapon

## Constructors
### BigBadWolfWeapon()
```csharp
public BigBadWolfWeapon()
```

## Fields
### _attackBuf
```csharp
private const float _attackBuf = 1.5
```


#### Field Value
**Type:** System.Single

### _defaultRange
```csharp
private const int _defaultRange = 3
```


#### Field Value
**Type:** System.Int32

### _effect_src
```csharp
private const string _effect_src = "Effect/Agent/BigBadWolfWeaponAura"
```


#### Field Value
**Type:** System.String

### _skillHpRatio
```csharp
private const float _skillHpRatio = 0.5
```


#### Field Value
**Type:** System.Single

### _specialProb
```csharp
private const float _specialProb = 0.2
```


#### Field Value
**Type:** System.Single

### _specialRange
```csharp
private const int _specialRange = 8
```


#### Field Value
**Type:** System.Int32

### aura
```csharp
private GameObject aura
```


#### Field Value
**Type:** UnityEngine.GameObject

### defaultInfo
```csharp
private SplashInfo defaultInfo
```


#### Field Value
**Type:** Global.SplashInfo

### isSpecial
```csharp
private bool isSpecial
```


#### Field Value
**Type:** System.Boolean

### specialInfo
```csharp
private SplashInfo specialInfo
```


#### Field Value
**Type:** Global.SplashInfo

### worker
```csharp
private WorkerModel worker
```


#### Field Value
**Type:** Global.WorkerModel

## Properties
### isRaged
```csharp
private bool isRaged { get; }
```

#### Property Value
**Type:** System.Boolean

## Methods
### AttachEffect()
```csharp
private GameObject AttachEffect()
```


#### Returns
**Type:** UnityEngine.GameObject

### GetDamage(int)
```csharp
private DamageInfo GetDamage(int index)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

#### Returns
**Type:** Global.DamageInfo

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

### Init()
```csharp
private void Init()
```


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

### OnFixedUpdate()
```csharp
public override void OnFixedUpdate()
```


### OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)
```csharp
public override void OnGiveDamageAfter(UnitModel actor, UnitModel target, DamageInfo dmg)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |
| `target` | `Global.UnitModel` |  |
| `dmg` | `Global.DamageInfo` |  |

### OnStageStart()
```csharp
public override void OnStageStart()
```


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

### RemoveEffect()
```csharp
private void RemoveEffect()
```


### SetNextAttackType()
```csharp
private void SetNextAttackType()
```


## Inherited Members
[_model](/api/Global/EGO/EquipmentScriptBase#model), [_reinforcementLevel](/api/Global/EGO/EquipmentScriptBase#reinforcementlevel), [MAX_REINFORCEMENT_LEVEL](/api/Global/EGO/EquipmentScriptBase#max-reinforcement-level), [SetModel(EquipmentModel)](/api/Global/EGO/EquipmentScriptBase#setmodel-equipmentmodel), [OnEquip(UnitModel)](/api/Global/EGO/EquipmentScriptBase#onequip-unitmodel), [OnRelease()](/api/Global/EGO/EquipmentScriptBase#onrelease), [OnStageRelease()](/api/Global/EGO/EquipmentScriptBase#onstagerelease), [OnPrepareWeapon(UnitModel)](/api/Global/EGO/EquipmentScriptBase#onprepareweapon-unitmodel), [OnCancelWeapon(UnitModel)](/api/Global/EGO/EquipmentScriptBase#oncancelweapon-unitmodel), [OnKillMainTarget(UnitModel, UnitModel)](/api/Global/EGO/EquipmentScriptBase#onkillmaintarget-unitmodel-unitmodel), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/Global/EGO/EquipmentScriptBase#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [OnTakeDamage(UnitModel, ref DamageInfo)](/api/Global/EGO/EquipmentScriptBase#ontakedamage-unitmodel-ref-damageinfo), [GetReinforcementDmg()](/api/Global/EGO/EquipmentScriptBase#getreinforcementdmg), [AddReinforcementLevel(int)](/api/Global/EGO/EquipmentScriptBase#addreinforcementlevel-int), [GetDefense(UnitModel)](/api/Global/EGO/EquipmentScriptBase#getdefense-unitmodel), [GetDamageFactor()](/api/Global/EGO/EquipmentScriptBase#getdamagefactor), [GetBonus(UnitModel)](/api/Global/EGO/EquipmentScriptBase#getbonus-unitmodel), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/EGO/EquipmentScriptBase#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OwnerHeal(bool, ref float)](/api/Global/EGO/EquipmentScriptBase#ownerheal-bool-ref-float), [model](/api/Global/EGO/EquipmentScriptBase#model), [reinforcementLevel](/api/Global/EGO/EquipmentScriptBase#reinforcementlevel), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)








