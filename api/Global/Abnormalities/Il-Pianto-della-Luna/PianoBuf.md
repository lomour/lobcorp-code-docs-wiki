---
uid: Global.PianoBuf
canonical_path: /api/Global/UnitStatBuf/PianoBuf
---
# Class PianoBuf
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PianoBuf : UnitStatBuf
```
> This section may have incomplete or incorrect information.
{.is-warning}


Buff applied to agents while an agent is playing [Il Pianto della Luna](/api/Global/Abnormalities/Il-Pianto-della-Luna/Piano)'s piano.

Adds 5 to justice and temperance.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitBuf](/api/Global/Buffs/UnitStatBuf) → PianoBuf

## Constructors
### PianoBuf()
```csharp
public PianoBuf()
```


## Fields
### agent
```csharp
private AgentModel agent
```


#### Field Value
**Type:** Global.AgentModel

### JUSTICE_BUF
```csharp
private const int JUSTICE_BUF = 5
```


#### Field Value
**Type:** System.Int32

### TEMPERANCE_BUF
```csharp
private const int TEMPERANCE_BUF = 5
```


#### Field Value
**Type:** System.Int32

## Methods
### Init(UnitModel)
```csharp
public override void Init(UnitModel model)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.UnitModel` |  |

### OnUnitDie()
```csharp
public override void OnUnitDie()
```


## Inherited Members
[primaryStat](/api/Global/Buffs/UnitBuf#type), [remainTime](/api/Global/Buffs/UnitBuf#remaintime), [model](/api/Global/Buffs/UnitBuf#model), [effectSrc](/api/Global/Buffs/UnitBuf#effectsrc), [duplicateType](/api/Global/Buffs/UnitBuf#duplicatetype), [FixedUpdate()](/api/Global/Buffs/UnitBuf#fixedupdate), [Destroy()](/api/Global/Buffs/UnitBuf#destroy), [OnDestroy()](/api/Global/Buffs/UnitBuf#ondestroy), [MovementScale()](/api/Global/Buffs/UnitBuf#movementscale), [OnUnitPanic()](/api/Global/Buffs/UnitBuf#onunitpanic), [OnStageRelease()](/api/Global/Buffs/UnitBuf#onstagerelease), [OnTakeDamage(UnitModel, DamageInfo)](/api/Global/Buffs/UnitBuf#ontakedamage-unitmodel-damageinfo), [GetDamageFactor()](/api/Global/Buffs/UnitBuf#getdamagefactor), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Buffs/UnitBuf#getdamagefactor-unitmodel-damageinfo), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/Global/Buffs/UnitBuf#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Buffs/UnitBuf#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/Buffs/UnitBuf#ongivedamageafter-unitmodel-unitmodel-damageinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)







