---
uid: Global.UnitStatBuf
canonical_path: /api/Global/UnitBuf/UnitStatBuf
---
# Class UnitStatBuf
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class UnitStatBuf : UnitBuf
```
> This section may have incomplete or incorrect information.
{.is-warning}


Buff which increases stats.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitBuf](/api/Global/Buffs/UnitBuf) → UnitStatBuf

## Derived
[BinahJusticeDebuf](/api/BinahBoss/BinahJusticeDebuf), [DesireHeart.DesireHeartEquipBuf](/api/Global/Abnormalities/Yin-and-Yang/Yang/YangEquipBuf), [YouMustHappy.YouMustHappyBuf](/api/Global/UnitStatBuf/YouMustHappyYouMustHappyBuf)

## Constructors
### UnitStatBuf(float)
```csharp
public UnitStatBuf(float time)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `time` | `System.Single` |  |

### UnitStatBuf(float, UnitBufType)
```csharp
public UnitStatBuf(float time, UnitBufType type)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `time` | `System.Single` |  |
| `type` | `Global.UnitBufType` |  |

## Fields
### attackSpeed
```csharp
public float attackSpeed
```


#### Field Value
**Type:** System.Single

### cubeSpeed
```csharp
public int cubeSpeed
```


#### Field Value
**Type:** System.Int32

### maxHp
```csharp
public int maxHp
```


#### Field Value
**Type:** System.Int32

### maxMental
```csharp
public int maxMental
```


#### Field Value
**Type:** System.Int32

### movementSpeed
```csharp
public float movementSpeed
```


#### Field Value
**Type:** System.Single

### primaryStat
```csharp
public WorkerPrimaryStatBonus primaryStat
```


#### Field Value
**Type:** Global.WorkerPrimaryStatBonus

### workProb
```csharp
public int workProb
```


#### Field Value
**Type:** System.Int32

## Inherited Members
[type](/api/Global/Buffs/UnitBuf#type), [remainTime](/api/Global/Buffs/UnitBuf#remaintime), [model](/api/Global/Buffs/UnitBuf#model), [effectSrc](/api/Global/Buffs/UnitBuf#effectsrc), [duplicateType](/api/Global/Buffs/UnitBuf#duplicatetype), [Init(UnitModel)](/api/Global/Buffs/UnitBuf#init-unitmodel), [FixedUpdate()](/api/Global/Buffs/UnitBuf#fixedupdate), [Destroy()](/api/Global/Buffs/UnitBuf#destroy), [OnDestroy()](/api/Global/Buffs/UnitBuf#ondestroy), [MovementScale()](/api/Global/Buffs/UnitBuf#movementscale), [OnUnitDie()](/api/Global/Buffs/UnitBuf#onunitdie), [OnUnitPanic()](/api/Global/Buffs/UnitBuf#onunitpanic), [OnStageRelease()](/api/Global/Buffs/UnitBuf#onstagerelease), [OnTakeDamage(UnitModel, DamageInfo)](/api/Global/Buffs/UnitBuf#ontakedamage-unitmodel-damageinfo), [GetDamageFactor()](/api/Global/Buffs/UnitBuf#getdamagefactor), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Buffs/UnitBuf#getdamagefactor-unitmodel-damageinfo), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/Global/Buffs/UnitBuf#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Buffs/UnitBuf#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/Buffs/UnitBuf#ongivedamageafter-unitmodel-unitmodel-damageinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)









