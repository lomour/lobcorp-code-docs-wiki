---
uid: Global.SuperArmorBuf
canonical_path: /api/Global/UnitBuf/SuperArmorBuf
---
# Class SuperArmorBuf
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SuperArmorBuf : UnitBuf
```
> This section may have incomplete or incorrect information.
{.is-warning}


Used by [Punishing Bird](/api/Global/Abnormalities/Punishing-Bird/SmallBird), but shouldn't do anything other than a visual effect, maybe... 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitBuf](/api/Global/Buffs/UnitBuf) → SuperArmorBuf

## Constructors
### SuperArmorBuf(UnitBufType, float, float)
```csharp
public SuperArmorBuf(UnitBufType type, float superArmor, float defense)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.UnitBufType` |  |
| `superArmor` | `System.Single` |  |
| `defense` | `System.Single` |  |

## Fields
### defense
```csharp
private float defense
```


#### Field Value
**Type:** System.Single

### superArmor
```csharp
private float superArmor
```


#### Field Value
**Type:** System.Single

### superArmorEffect
```csharp
private SuperArmorEffect superArmorEffect
```


#### Field Value
**Type:** Global.SuperArmorEffect

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

### OnDestroy()
```csharp
public override void OnDestroy()
```


## Inherited Members
[type](/api/Global/Buffs/UnitBuf#type), [remainTime](/api/Global/Buffs/UnitBuf#remaintime), [model](/api/Global/Buffs/UnitBuf#model), [effectSrc](/api/Global/Buffs/UnitBuf#effectsrc), [duplicateType](/api/Global/Buffs/UnitBuf#duplicatetype), [Destroy()](/api/Global/Buffs/UnitBuf#destroy), [MovementScale()](/api/Global/Buffs/UnitBuf#movementscale), [OnUnitDie()](/api/Global/Buffs/UnitBuf#onunitdie), [OnUnitPanic()](/api/Global/Buffs/UnitBuf#onunitpanic), [OnStageRelease()](/api/Global/Buffs/UnitBuf#onstagerelease), [OnTakeDamage(UnitModel, DamageInfo)](/api/Global/Buffs/UnitBuf#ontakedamage-unitmodel-damageinfo), [GetDamageFactor()](/api/Global/Buffs/UnitBuf#getdamagefactor), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Buffs/UnitBuf#getdamagefactor-unitmodel-damageinfo), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/Global/Buffs/UnitBuf#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Buffs/UnitBuf#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/Buffs/UnitBuf#ongivedamageafter-unitmodel-unitmodel-damageinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)









