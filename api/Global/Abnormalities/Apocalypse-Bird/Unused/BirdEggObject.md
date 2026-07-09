---
uid: Global.BirdEggObject
canonical_path: /api/Global/Object/BirdEggObject
---
# Class BirdEggObject
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BirdEggObject : StandingItemScriptBase
```
> This section may have incomplete or incorrect information.
{.is-warning}

> This class is not used.
{.is-info}


Unused version of the eggs for [Apocalypse Bird](/api/Global/Abnormalities/Apocalypse-Bird/BossBird)'s fight.

See [BossEggBase](/api/Global/Abnormalities/Apocalypse-Bird/Eggs/BossEggBase) for the used version



## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [StandingItemScriptBase](/api/Global/Unused/StandingItem/StandingItemScriptBase) → BirdEggObject

## Constructors
### BirdEggObject()
```csharp
public BirdEggObject()
```

## Fields
### breakDown
```csharp
private bool breakDown
```


#### Field Value
**Type:** System.Boolean

### halfActivated
```csharp
private bool halfActivated
```


#### Field Value
**Type:** System.Boolean

### sep
```csharp
private SoundEffectPlayer sep
```


#### Field Value
**Type:** Global.SoundEffectPlayer

## Properties
### animScript
```csharp
private BirdEggAnim animScript { get; }
```

#### Property Value
**Type:** Global.BirdEggAnim

## Methods
### ActivateAnimHalf()
```csharp
public void ActivateAnimHalf()
```


### ActivateScript()
```csharp
public void ActivateScript()
```


### GetName()
```csharp
public override string GetName()
```


#### Returns
**Type:** System.String

### HasName()
```csharp
public override bool HasName()
```


#### Returns
**Type:** System.Boolean

### IsEnabled()
```csharp
public bool IsEnabled()
```


#### Returns
**Type:** System.Boolean

### OnBreakDown()
```csharp
public override void OnBreakDown()
```


### OnTakePhyisclaDamage(float)
```csharp
public override void OnTakePhyisclaDamage(float damage)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `damage` | `System.Single` |  |

### SetSound(SoundEffectPlayer)
```csharp
public void SetSound(SoundEffectPlayer sep)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `sep` | `Global.SoundEffectPlayer` |  |

## Inherited Members
[soundDistDobule](/api/Global/Unused/StandingItem/StandingItemScriptBase#sounddistdobule), [model](/api/Global/Unused/StandingItem/StandingItemScriptBase#model), [_animScript](/api/Global/Unused/StandingItem/StandingItemScriptBase#animscript), [_state](/api/Global/Unused/StandingItem/StandingItemScriptBase#state), [name](/api/Global/Unused/StandingItem/StandingItemScriptBase#name), [_maxHp](/api/Global/Unused/StandingItem/StandingItemScriptBase#maxhp), [_defense](/api/Global/Unused/StandingItem/StandingItemScriptBase#defense), [SetModel(StandingItemModel)](/api/Global/Unused/StandingItem/StandingItemScriptBase#setmodel-standingitemmodel), [OnNearUnitArrived(List<UnitModel>)](/api/Global/Unused/StandingItem/StandingItemScriptBase#onnearunitarrived-list-unitmodel), [Init()](/api/Global/Unused/StandingItem/StandingItemScriptBase#init), [SetAnimScript(StandingItemAnim)](/api/Global/Unused/StandingItem/StandingItemScriptBase#setanimscript-standingitemanim), [GetNearUnit()](/api/Global/Unused/StandingItem/StandingItemScriptBase#getnearunit), [IsInRange(UnitModel, float)](/api/Global/Unused/StandingItem/StandingItemScriptBase#isinrange-unitmodel-float), [CanTakePhsyicalDamage(UnitModel)](/api/Global/Unused/StandingItem/StandingItemScriptBase#cantakephsyicaldamage-unitmodel), [IsAttackable()](/api/Global/Unused/StandingItem/StandingItemScriptBase#isattackable), [OnFixedUpdate(StandingItemModel)](/api/Global/Unused/StandingItem/StandingItemScriptBase#onfixedupdate-standingitemmodel), [OnIgnoreDamage(UnitModel)](/api/Global/Unused/StandingItem/StandingItemScriptBase#onignoredamage-unitmodel), [OnDestroyStandingItem()](/api/Global/Unused/StandingItem/StandingItemScriptBase#ondestroystandingitem), [SetName(string)](/api/Global/Unused/StandingItem/StandingItemScriptBase#setname-string), [Prob(float)](/api/Global/Unused/StandingItem/StandingItemScriptBase#prob-float), [Prob(int)](/api/Global/Unused/StandingItem/StandingItemScriptBase#prob-int), [CheckCameraRange()](/api/Global/Unused/StandingItem/StandingItemScriptBase#checkcamerarange), [CheckCameraRange(float)](/api/Global/Unused/StandingItem/StandingItemScriptBase#checkcamerarange-float), [Model](/api/Global/Unused/StandingItem/StandingItemScriptBase#model), [Movable](/api/Global/Unused/StandingItem/StandingItemScriptBase#movable), [Passage](/api/Global/Unused/StandingItem/StandingItemScriptBase#passage), [State](/api/Global/Unused/StandingItem/StandingItemScriptBase#state), [MaxHp](/api/Global/Unused/StandingItem/StandingItemScriptBase#maxhp), [Defense](/api/Global/Unused/StandingItem/StandingItemScriptBase#defense), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)






