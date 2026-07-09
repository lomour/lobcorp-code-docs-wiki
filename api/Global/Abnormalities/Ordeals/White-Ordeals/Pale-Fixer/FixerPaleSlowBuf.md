---
uid: Global.FixerPaleSlowBuf
canonical_path: /api/Global/UnitBuf/FixerPaleSlowBuf
---
# Class FixerPaleSlowBuf
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class FixerPaleSlowBuf : UnitBuf
```
> This section may have incomplete or incorrect information.
{.is-warning}


Buff which stops movement, for the target of the [Pale Fixer](/api/Global/Abnormalities/Ordeals/White-Ordeals/Pale-Fixer/FixerPale)'s teleport attack.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitBuf](/api/Global/Buffs/UnitBuf) → FixerPaleSlowBuf

## Constructors
### FixerPaleSlowBuf()
```csharp
public FixerPaleSlowBuf()
```


## Fields
### _movementScale
```csharp
private const float _movementScale = 0
```


#### Field Value
**Type:** System.Single

### _remainMax
```csharp
private const float _remainMax = 2
```


#### Field Value
**Type:** System.Single

### _remainMin
```csharp
private const float _remainMin = 1
```


#### Field Value
**Type:** System.Single

## Properties
### remain
```csharp
private static float remain { get; }
```

#### Property Value
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






