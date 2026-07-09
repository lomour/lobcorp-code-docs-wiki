---
uid: Global.AlriuneAuraBuf
canonical_path: /api/Global/UnitBuf/AlriuneAuraBuf
---
# Class AlriuneAuraBuf
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class AlriuneAuraBuf : UnitBuf
```
> This section may have incomplete or incorrect information.
{.is-warning}


Effect that kills agents when they panic near [Alriune](/api/Global/Abnormalities/Alriune/Alriune).




## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitBuf](/api/Global/Buffs/UnitBuf) → AlriuneAuraBuf

## Constructors
### AlriuneAuraBuf()
```csharp
public AlriuneAuraBuf()
```
Sets the [UnitBufType](/api/Global/Buffs/UnitBufType) to ALRIUNE_AURA.


## Fields
### curtainAnimator
```csharp
private Animator curtainAnimator
```
Animator for curtain effects on affected agents.


#### Field Value
**Type:** UnityEngine.Animator

### delay
```csharp
private const float delay = 3
```


#### Field Value
**Type:** System.Single

### worker
```csharp
private WorkerModel worker
```
The agent with this buff.


#### Field Value
**Type:** Global.WorkerModel

## Methods
### Init(UnitModel)
```csharp
public override void Init(UnitModel model)
```
If this is a worker, loads the curtain prefab on the agent, then sets a special death animation and kills the worker. Sets a timer to destroy the buff in 3 seconds.


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.UnitModel` |  |

### OnDestroy()
```csharp
public override void OnDestroy()
```
Tells the curtainAnimator that the agent is dead and sets the special death animation randomly to one of four animations.


## Inherited Members
[type](/api/Global/Buffs/UnitBuf#type), [remainTime](/api/Global/Buffs/UnitBuf#remaintime), [model](/api/Global/Buffs/UnitBuf#model), [effectSrc](/api/Global/Buffs/UnitBuf#effectsrc), [duplicateType](/api/Global/Buffs/UnitBuf#duplicatetype), [FixedUpdate()](/api/Global/Buffs/UnitBuf#fixedupdate), [Destroy()](/api/Global/Buffs/UnitBuf#destroy), [MovementScale()](/api/Global/Buffs/UnitBuf#movementscale), [OnUnitDie()](/api/Global/Buffs/UnitBuf#onunitdie), [OnUnitPanic()](/api/Global/Buffs/UnitBuf#onunitpanic), [OnStageRelease()](/api/Global/Buffs/UnitBuf#onstagerelease), [OnTakeDamage(UnitModel, DamageInfo)](/api/Global/Buffs/UnitBuf#ontakedamage-unitmodel-damageinfo), [GetDamageFactor()](/api/Global/Buffs/UnitBuf#getdamagefactor), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Buffs/UnitBuf#getdamagefactor-unitmodel-damageinfo), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/Global/Buffs/UnitBuf#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Buffs/UnitBuf#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/Buffs/UnitBuf#ongivedamageafter-unitmodel-unitmodel-damageinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)








