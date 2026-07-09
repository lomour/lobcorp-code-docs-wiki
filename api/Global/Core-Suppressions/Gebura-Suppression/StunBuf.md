---
uid: Global.StunBuf
canonical_path: /api/Global/UnitBuf/StunBuf
---
# Class StunBuf
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class StunBuf : UnitBuf
```
> This section may have incomplete or incorrect information.
{.is-warning}


extends [UnitBuf](/api/Global/Buffs/UnitBuf)

Sets movement speed to 0.01x for 10000 seconds or until removed. Used by [The Red Mist's third phase Smile attack](/api/GeburahBoss/DangoAttackAction).


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitBuf](/api/Global/Buffs/UnitBuf) → StunBuf

## Constructors
### StunBuf()
```csharp
public StunBuf()
```


### StunBuf(float)
```csharp
public StunBuf(float time)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `time` | `System.Single` |  |

## Methods
### MovementScale()
```csharp
public override float MovementScale()
```


#### Returns
**Type:** System.Single

### RemoveBuf()
```csharp
public void RemoveBuf()
```


## Inherited Members
[type](/api/Global/Buffs/UnitBuf#type), [remainTime](/api/Global/Buffs/UnitBuf#remaintime), [model](/api/Global/Buffs/UnitBuf#model), [effectSrc](/api/Global/Buffs/UnitBuf#effectsrc), [duplicateType](/api/Global/Buffs/UnitBuf#duplicatetype), [Init(UnitModel)](/api/Global/Buffs/UnitBuf#init-unitmodel), [FixedUpdate()](/api/Global/Buffs/UnitBuf#fixedupdate), [Destroy()](/api/Global/Buffs/UnitBuf#destroy), [OnDestroy()](/api/Global/Buffs/UnitBuf#ondestroy), [OnUnitDie()](/api/Global/Buffs/UnitBuf#onunitdie), [OnUnitPanic()](/api/Global/Buffs/UnitBuf#onunitpanic), [OnStageRelease()](/api/Global/Buffs/UnitBuf#onstagerelease), [OnTakeDamage(UnitModel, DamageInfo)](/api/Global/Buffs/UnitBuf#ontakedamage-unitmodel-damageinfo), [GetDamageFactor()](/api/Global/Buffs/UnitBuf#getdamagefactor), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Buffs/UnitBuf#getdamagefactor-unitmodel-damageinfo), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/Global/Buffs/UnitBuf#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Buffs/UnitBuf#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/Buffs/UnitBuf#ongivedamageafter-unitmodel-unitmodel-damageinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)







