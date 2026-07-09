---
uid: Global.ArmorModel
canonical_path: /api/Global/Model/ArmorModel
---
# Class ArmorModel
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ArmorModel : EquipmentModel
```
> This section may have incomplete or incorrect information.
{.is-warning}


Parent class for EGO Suits.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [EquipmentModel](/api/Global/EGO/EquipmentModel) → ArmorModel

## Constructors
### ArmorModel()
```csharp
public ArmorModel()
```

## Methods
### GetDefense(UnitModel)
```csharp
public DefenseInfo GetDefense(UnitModel actor)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |

#### Returns
**Type:** Global.DefenseInfo

### GetDummyArmor()
```csharp
public static ArmorModel GetDummyArmor()
```


#### Returns
**Type:** Global.ArmorModel

### MakeArmor(EquipmentTypeInfo)
```csharp
public static ArmorModel MakeArmor(EquipmentTypeInfo info)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `info` | `Global.EquipmentTypeInfo` |  |

#### Returns
**Type:** Global.ArmorModel

### OnFixedUpdate()
```csharp
public override void OnFixedUpdate()
```


## Inherited Members
[metaInfo](/api/Global/EGO/EquipmentModel#metainfo), [instanceId](/api/Global/EGO/EquipmentModel#instanceid), [_owner](/api/Global/EGO/EquipmentModel#owner), [script](/api/Global/EGO/EquipmentModel#script), [currentTarget](/api/Global/EGO/EquipmentModel#currenttarget), [OnPrepareWeapon(UnitModel)](/api/Global/EGO/EquipmentModel#onprepareweapon-unitmodel), [GetDamageFactor()](/api/Global/EGO/EquipmentModel#getdamagefactor), [OnCancelWeapon(UnitModel)](/api/Global/EGO/EquipmentModel#oncancelweapon-unitmodel), [OnEquip(UnitModel)](/api/Global/EGO/EquipmentModel#onequip-unitmodel), [OnRelease()](/api/Global/EGO/EquipmentModel#onrelease), [OnTakeDamage(UnitModel, ref DamageInfo)](/api/Global/EGO/EquipmentModel#ontakedamage-unitmodel-ref-damageinfo), [OnTakeDamage_After(float, RwbpType)](/api/Global/EGO/EquipmentModel#ontakedamage-after-float-rwbptype), [CheckRequire(UnitModel)](/api/Global/EGO/EquipmentModel#checkrequire-unitmodel), [GetBonus(UnitModel)](/api/Global/EGO/EquipmentModel#getbonus-unitmodel), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/EGO/EquipmentModel#getworkprobspecialbonus-unitmodel-skilltypeinfo), [owner](/api/Global/EGO/EquipmentModel#owner), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)








