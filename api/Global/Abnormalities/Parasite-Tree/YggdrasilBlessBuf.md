---
uid: Global.YggdrasilBlessBuf
canonical_path: /api/Global/UnitBuf/YggdrasilBlessBuf
---
# Class YggdrasilBlessBuf
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class YggdrasilBlessBuf : UnitBuf
```
> This section may have incomplete or incorrect information.
{.is-warning}


Buff applied to [Parasite Tree](/api/Global/Abnormalities/Parasite-Tree/Yggdrasil)'s blessed employees. Last forever.

When destroyed, removes the blessed employee from Parasite Tree's list. Overwritten by [DeathAngelBetrayerBuf](/api/Global/Abnormalities/WhiteNight/DeathAngelBetrayerBuf).



## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitBuf](/api/Global/Buffs/UnitBuf) → YggdrasilBlessBuf

## Constructors
### YggdrasilBlessBuf(WorkerModel, Yggdrasil)
```csharp
public YggdrasilBlessBuf(WorkerModel worker, Yggdrasil script)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |
| `script` | `Global.Yggdrasil` |  |

## Fields
### script
```csharp
private Yggdrasil script
```


#### Field Value
**Type:** Global.Yggdrasil

### worker
```csharp
private WorkerModel worker
```


#### Field Value
**Type:** Global.WorkerModel

## Methods
### FixedUpdate()
```csharp
public override void FixedUpdate()
```


### OnDestroy()
```csharp
public override void OnDestroy()
```


### OnUnitDie()
```csharp
public override void OnUnitDie()
```


## Inherited Members
[type](/api/Global/Buffs/UnitBuf#type), [remainTime](/api/Global/Buffs/UnitBuf#remaintime), [model](/api/Global/Buffs/UnitBuf#model), [effectSrc](/api/Global/Buffs/UnitBuf#effectsrc), [duplicateType](/api/Global/Buffs/UnitBuf#duplicatetype), [Init(UnitModel)](/api/Global/Buffs/UnitBuf#init-unitmodel), [Destroy()](/api/Global/Buffs/UnitBuf#destroy), [MovementScale()](/api/Global/Buffs/UnitBuf#movementscale), [OnUnitPanic()](/api/Global/Buffs/UnitBuf#onunitpanic), [OnStageRelease()](/api/Global/Buffs/UnitBuf#onstagerelease), [OnTakeDamage(UnitModel, DamageInfo)](/api/Global/Buffs/UnitBuf#ontakedamage-unitmodel-damageinfo), [GetDamageFactor()](/api/Global/Buffs/UnitBuf#getdamagefactor), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Buffs/UnitBuf#getdamagefactor-unitmodel-damageinfo), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/Global/Buffs/UnitBuf#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Buffs/UnitBuf#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/Buffs/UnitBuf#ongivedamageafter-unitmodel-unitmodel-damageinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)







