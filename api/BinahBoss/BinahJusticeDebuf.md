---
uid: BinahBoss.BinahJusticeDebuf
canonical_path: /api/BinahBoss/BinahJusticeDebuf
---
# Class BinahJusticeDebuf
**Namespace:** [BinahBoss](/api/BinahBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BinahJusticeDebuf : UnitStatBuf
```
> This section may have incomplete or incorrect information.
{.is-warning}

Binah slowing debuf


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitBuf](/api/Global/Buffs/UnitStatBuf) → BinahJusticeDebuf

## Constructors
### BinahJusticeDebuf(float)
```csharp
public BinahJusticeDebuf(float time)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `time` | `System.Single` |  |

## Fields
### _reduceVal
```csharp
private float _reduceVal
```


#### Field Value
**Type:** System.Single

### agent
```csharp
private AgentModel agent
```


#### Field Value
**Type:** Global.AgentModel

### attach
```csharp
private GameObject attach
```


#### Field Value
**Type:** UnityEngine.GameObject

### lateInit
```csharp
private bool lateInit
```


#### Field Value
**Type:** System.Boolean

### P_min
```csharp
private const float P_min = 10
```


#### Field Value
**Type:** System.Single

### unitEffectSrc
```csharp
private const string unitEffectSrc = "Effect/SefiraBoss/BinahBoss/Effect/BinahAgentSlow"
```


#### Field Value
**Type:** System.String

## Properties
### P_buf
```csharp
private float P_buf { get; }
```

#### Property Value
**Type:** System.Single

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

### LateInit()
```csharp
private void LateInit()
```


### OnDestroy()
```csharp
public override void OnDestroy()
```


### OnUnitDie()
```csharp
public override void OnUnitDie()
```


### SetReduceValue(float)
```csharp
public void SetReduceValue(float val)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `val` | `System.Single` |  |

## Inherited Members
[primaryStat](/api/Global/Buffs/UnitBuf#type), [remainTime](/api/Global/Buffs/UnitBuf#remaintime), [model](/api/Global/Buffs/UnitBuf#model), [effectSrc](/api/Global/Buffs/UnitBuf#effectsrc), [duplicateType](/api/Global/Buffs/UnitBuf#duplicatetype), [Destroy()](/api/Global/Buffs/UnitBuf#destroy), [MovementScale()](/api/Global/Buffs/UnitBuf#movementscale), [OnUnitPanic()](/api/Global/Buffs/UnitBuf#onunitpanic), [OnStageRelease()](/api/Global/Buffs/UnitBuf#onstagerelease), [OnTakeDamage(UnitModel, DamageInfo)](/api/Global/Buffs/UnitBuf#ontakedamage-unitmodel-damageinfo), [GetDamageFactor()](/api/Global/Buffs/UnitBuf#getdamagefactor), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Buffs/UnitBuf#getdamagefactor-unitmodel-damageinfo), [OnGiveDamage(UnitModel, UnitModel, ref DamageInfo)](/api/Global/Buffs/UnitBuf#ongivedamage-unitmodel-unitmodel-ref-damageinfo), [GetWorkProbSpecialBonus(UnitModel, SkillTypeInfo)](/api/Global/Buffs/UnitBuf#getworkprobspecialbonus-unitmodel-skilltypeinfo), [OnGiveDamageAfter(UnitModel, UnitModel, DamageInfo)](/api/Global/Buffs/UnitBuf#ongivedamageafter-unitmodel-unitmodel-damageinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)











