---
uid: Global.YoungPrinceSlowBuf
canonical_path: /api/Global/UnitBuf/YoungPrinceSlowBuf
---
# Class YoungPrinceSlowBuf
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class YoungPrinceSlowBuf : UnitBuf
```
> This section may have incomplete or incorrect information.
{.is-warning}


Slowing buff given by [The Little Prince's minions](/api/Global/Abnormalities/The-Little-Prince/YoungPrinceFriend) ^\[verify\]^.

Slows movement by 0.5x for 1 second.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitBuf](/api/Global/Buffs/UnitBuf) → YoungPrinceSlowBuf

## Constructors
### YoungPrinceSlowBuf()
```csharp
public YoungPrinceSlowBuf()
```


## Fields
### _remainTime
```csharp
private const float _remainTime = 1
```


#### Field Value
**Type:** System.Single

### _slowScale
```csharp
private const float _slowScale = 0.5
```


#### Field Value
**Type:** System.Single

## Methods
### Init(UnitModel)
```csharp
public override void Init(UnitModel model)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.UnitModel` |  |

### MovementScale()
```csharp
public override float MovementScale()
```


#### Returns
**Type:** System.Single

## Inherited Members
[type](/api/Global/Buffs/UnitBuf#type), [remainTime](/api/Global/Buffs/UnitBuf#remaintime), [model](/api/Global/Buffs/UnitBuf#model), [effectSrc](/api/Global/Buffs/UnitBuf#effectsrc), [duplicateType](/api/Global/Buffs/UnitBuf#duplicatetype), [FixedUpdate()](/api/Global/Buffs/UnitBuf#fixedupdate), [Destroy()](/api/Global/Buffs/UnitBuf#destroy), [OnDestroy()](/api/Global/Buffs/UnitBuf#ondestroy), [OnUnitDie()](/api/Global/Buffs/UnitBuf#onunitdie), [OnUnitPanic()](/api/Global/Buffs/UnitBuf#onunitpanic), [OnStageRelease()](/api/Global/Buffs/UnitBuf#onstagerelease), [OnTakeDamage(UnitModel, DamageInfo)](/api/Global/Buffs/UnitBuf#ontakedamage-unitmodel-damageinfo), [GetDamageFactor()](/api/Global/Buffs/UnitBuf#getdamagefactor), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Buffs/UnitBuf#getdamagefactor-unitmodel-damageinfo), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/Global/Buffs/UnitBuf#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Buffs/UnitBuf#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/Buffs/UnitBuf#ongivedamageafter-unitmodel-unitmodel-damageinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)







