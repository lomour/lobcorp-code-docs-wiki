---
uid: Global.DeathAngelBetrayerBuf
canonical_path: /api/Global/UnitBuf/DeathAngelBetrayerBuf
---
# Class DeathAngelBetrayerBuf
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DeathAngelBetrayerBuf : UnitBuf
```
> This section may have incomplete or incorrect information.
{.is-warning}


Effect for the special twelth apostle, The Heretic.
Gives immunity to all damage and allows a special work type with One Sin.



## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitBuf](/api/Global/Buffs/UnitBuf) → DeathAngelBetrayerBuf

## Constructors
### DeathAngelBetrayerBuf(DeathAngel, ApostleData)
```csharp
public DeathAngelBetrayerBuf(DeathAngel angel, ApostleData data)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `angel` | `WhiteNightSpace.DeathAngel` |  |
| `data` | `WhiteNightSpace.ApostleData` |  |

## Fields
### agent
```csharp
private AgentModel agent
```


#### Field Value
**Type:** Global.AgentModel

### angel
```csharp
private DeathAngel angel
```


#### Field Value
**Type:** WhiteNightSpace.DeathAngel

### data
```csharp
private ApostleData data
```


#### Field Value
**Type:** WhiteNightSpace.ApostleData

### oneBadManyGood
```csharp
private CreatureModel oneBadManyGood
```


#### Field Value
**Type:** Global.CreatureModel

### position
```csharp
private static Vector3 position
```


#### Field Value
**Type:** UnityEngine.Vector3

### rotation
```csharp
private static Vector3 rotation
```


#### Field Value
**Type:** UnityEngine.Vector3

### scale
```csharp
private static Vector3 scale
```


#### Field Value
**Type:** UnityEngine.Vector3

## Methods
### Confess()
```csharp
public void Confess()
```


### Destroy()
```csharp
public override void Destroy()
```


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

### OnDeathAngelSuppressed()
```csharp
public void OnDeathAngelSuppressed()
```


### OnStageRelease()
```csharp
public override void OnStageRelease()
```


### OnSuppress()
```csharp
public bool OnSuppress()
```


#### Returns
**Type:** System.Boolean

### OnWork()
```csharp
public bool OnWork()
```


#### Returns
**Type:** System.Boolean

## Inherited Members
[type](/api/Global/Buffs/UnitBuf#type), [remainTime](/api/Global/Buffs/UnitBuf#remaintime), [model](/api/Global/Buffs/UnitBuf#model), [effectSrc](/api/Global/Buffs/UnitBuf#effectsrc), [duplicateType](/api/Global/Buffs/UnitBuf#duplicatetype), [OnDestroy()](/api/Global/Buffs/UnitBuf#ondestroy), [MovementScale()](/api/Global/Buffs/UnitBuf#movementscale), [OnUnitDie()](/api/Global/Buffs/UnitBuf#onunitdie), [OnUnitPanic()](/api/Global/Buffs/UnitBuf#onunitpanic), [OnTakeDamage(UnitModel, DamageInfo)](/api/Global/Buffs/UnitBuf#ontakedamage-unitmodel-damageinfo), [GetDamageFactor()](/api/Global/Buffs/UnitBuf#getdamagefactor), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Buffs/UnitBuf#getdamagefactor-unitmodel-damageinfo), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/Global/Buffs/UnitBuf#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Buffs/UnitBuf#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/Buffs/UnitBuf#ongivedamageafter-unitmodel-unitmodel-damageinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)







