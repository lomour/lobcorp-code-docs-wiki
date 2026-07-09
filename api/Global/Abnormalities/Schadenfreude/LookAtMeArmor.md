---
uid: Global.LookAtMeArmor
canonical_path: /api/Global/Armor/LookAtMeArmor
---
# Class LookAtMeArmor
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class LookAtMeArmor : EquipmentScriptBase
```
> This section may have incomplete or incorrect information.
{.is-warning}


Script for [Schadenfreude](/api/Global/Abnormalities/Schadenfreude/LookAtMe)'s EGO Suit: Gaze.

Increases attack speed by 10 while the equipped agent is in the camera.

Also, changes the defenses to 0.8 / 0.5 / 0.8 / 1.5 (hard-coded!) while in the camera.




## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [EquipmentScriptBase](/api/Global/EGO/EquipmentScriptBase) → LookAtMeArmor

## Constructors
### LookAtMeArmor()
```csharp
public LookAtMeArmor()
```

## Fields
### _justiceBuf
```csharp
private const int _justiceBuf = 10
```


#### Field Value
**Type:** System.Int32

### cameraSensor
```csharp
private GameObject cameraSensor
```


#### Field Value
**Type:** UnityEngine.GameObject

### cameraUtil
```csharp
private CreatureCameraUtil cameraUtil
```

#### Field Value
**Type:** CreatureCameraUtil.CreatureCameraUtil

### owner
```csharp
private WorkerModel owner
```


#### Field Value
**Type:** Global.WorkerModel

## Methods
### GetDefense(UnitModel)
```csharp
public override DefenseInfo GetDefense(UnitModel actor)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |

#### Returns
**Type:** Global.DefenseInfo

### IsInCamera()
```csharp
private bool IsInCamera()
```


#### Returns
**Type:** System.Boolean

### OnEquip(UnitModel)
```csharp
public override void OnEquip(UnitModel actor)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |

### OnFixedUpdate()
```csharp
public override void OnFixedUpdate()
```


### OnStageRelease()
```csharp
public override void OnStageRelease()
```


### OnStageStart()
```csharp
public override void OnStageStart()
```


### RemoveCamera()
```csharp
private void RemoveCamera()
```


### SetCamera()
```csharp
private void SetCamera()
```


## Inherited Members
[_model](/api/Global/EGO/EquipmentScriptBase#model), [_reinforcementLevel](/api/Global/EGO/EquipmentScriptBase#reinforcementlevel), [MAX_REINFORCEMENT_LEVEL](/api/Global/EGO/EquipmentScriptBase#max-reinforcement-level), [SetModel(EquipmentModel)](/api/Global/EGO/EquipmentScriptBase#setmodel-equipmentmodel), [OnRelease()](/api/Global/EGO/EquipmentScriptBase#onrelease), [OnPrepareWeapon(UnitModel)](/api/Global/EGO/EquipmentScriptBase#onprepareweapon-unitmodel), [OnCancelWeapon(UnitModel)](/api/Global/EGO/EquipmentScriptBase#oncancelweapon-unitmodel), [OnAttackStart(UnitModel, UnitModel)](/api/Global/EGO/EquipmentScriptBase#onattackstart-unitmodel-unitmodel), [OnAttackEnd(UnitModel, UnitModel)](/api/Global/EGO/EquipmentScriptBase#onattackend-unitmodel-unitmodel), [OnKillMainTarget(UnitModel, UnitModel)](/api/Global/EGO/EquipmentScriptBase#onkillmaintarget-unitmodel-unitmodel), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/Global/EGO/EquipmentScriptBase#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/EGO/EquipmentScriptBase#ongivedamageafter-unitmodel-unitmodel-damageinfo), [OnTakeDamage(UnitModel, ref DamageInfo)](/api/Global/EGO/EquipmentScriptBase#ontakedamage-unitmodel-ref-damageinfo), [OnTakeDamage_After(float, RwbpType)](/api/Global/EGO/EquipmentScriptBase#ontakedamage-after-float-rwbptype), [GetReinforcementDmg()](/api/Global/EGO/EquipmentScriptBase#getreinforcementdmg), [AddReinforcementLevel(int)](/api/Global/EGO/EquipmentScriptBase#addreinforcementlevel-int), [GetDamageFactor()](/api/Global/EGO/EquipmentScriptBase#getdamagefactor), [GetDamage(UnitModel)](/api/Global/EGO/EquipmentScriptBase#getdamage-unitmodel), [GetBonus(UnitModel)](/api/Global/EGO/EquipmentScriptBase#getbonus-unitmodel), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/EGO/EquipmentScriptBase#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OwnerHeal(bool, ref float)](/api/Global/EGO/EquipmentScriptBase#ownerheal-bool-ref-float), [model](/api/Global/EGO/EquipmentScriptBase#model), [reinforcementLevel](/api/Global/EGO/EquipmentScriptBase#reinforcementlevel), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)







