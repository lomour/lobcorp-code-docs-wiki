---
uid: Global.BossBirdGateway
canonical_path: /api/Global/Misc/BossBirdGateway
---
# Class BossBirdGateway
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BossBirdGateway : StandingItemScriptBase
```
> This section may have incomplete or incorrect information.
{.is-warning}

> This class is not used.
{.is-info}


Unused version of Entrance to the Black Forest, as seen in [Apocalypse Bird](/api/Global/Abnormalities/Apocalypse-Bird/BossBird)'s fight.

See [BossGateWay](/api/Global/Abnormalities/Apocalypse-Bird/Entrance-to-the-Black-Forest/BossGateWay) for the used version of this.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [StandingItemScriptBase](/api/Global/Unused/StandingItem/StandingItemScriptBase) → BossBirdGateway

## Constructors
### BossBirdGateway()
```csharp
public BossBirdGateway()
```

## Fields
### __GatewayState
```csharp
private BossBirdGateway.GateWayState __GatewayState
```

#### Field Value
**Type:** Global.BossBirdGateway.GateWayState

### bigBird
```csharp
private BigBird bigBird
```


#### Field Value
**Type:** Global.BigBird

### longBird
```csharp
private LongBird longBird
```


#### Field Value
**Type:** Global.LongBird

### mentalDamage
```csharp
private const float mentalDamage = 2
```


#### Field Value
**Type:** System.Single

### mentalDamageFreq
```csharp
private const float mentalDamageFreq = 1
```


#### Field Value
**Type:** System.Single

### mentalDamageTimer
```csharp
private Timer mentalDamageTimer
```


#### Field Value
**Type:** Global.Timer

### smallBird
```csharp
private SmallBird smallBird
```


#### Field Value
**Type:** Global.SmallBird

### stateChecker
```csharp
private Timer stateChecker
```


#### Field Value
**Type:** Global.Timer

### stateCheckFreq
```csharp
private const float stateCheckFreq = 5
```


#### Field Value
**Type:** System.Single

## Properties
### animScript
```csharp
public BossBirdGatewayAnim animScript { get; }
```

#### Property Value
**Type:** Global.BossBirdGatewayAnim

### gateWayState
```csharp
public BossBirdGateway.GateWayState gateWayState { get; }
```

#### Property Value
**Type:** Global.BossBirdGateway.GateWayState

## Methods
### BirdsCheck()
```csharp
private void BirdsCheck()
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

### Init()
```csharp
public override void Init()
```


### OnEnterBird()
```csharp
public void OnEnterBird()
```


### OnFixedUpdate(StandingItemModel)
```csharp
public override void OnFixedUpdate(StandingItemModel model)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.StandingItemModel` |  |

### OnSetState()
```csharp
private void OnSetState()
```


### SetBirds(BigBird, SmallBird, LongBird)
```csharp
public void SetBirds(BigBird big, SmallBird small, LongBird @long)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `big` | `Global.BigBird` |  |
| `small` | `Global.SmallBird` |  |
| `long` | `Global.LongBird` |  |

### SetName(string)
```csharp
public override void SetName(string str)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `str` | `System.String` |  |

### TakeNearMentalDamage()
```csharp
private void TakeNearMentalDamage()
```


## Inherited Members
[soundDistDobule](/api/Global/Unused/StandingItem/StandingItemScriptBase#sounddistdobule), [model](/api/Global/Unused/StandingItem/StandingItemScriptBase#model), [_animScript](/api/Global/Unused/StandingItem/StandingItemScriptBase#animscript), [_state](/api/Global/Unused/StandingItem/StandingItemScriptBase#state), [name](/api/Global/Unused/StandingItem/StandingItemScriptBase#name), [_maxHp](/api/Global/Unused/StandingItem/StandingItemScriptBase#maxhp), [_defense](/api/Global/Unused/StandingItem/StandingItemScriptBase#defense), [SetModel(StandingItemModel)](/api/Global/Unused/StandingItem/StandingItemScriptBase#setmodel-standingitemmodel), [OnNearUnitArrived(List<UnitModel>)](/api/Global/Unused/StandingItem/StandingItemScriptBase#onnearunitarrived-list-unitmodel), [SetAnimScript(StandingItemAnim)](/api/Global/Unused/StandingItem/StandingItemScriptBase#setanimscript-standingitemanim), [GetNearUnit()](/api/Global/Unused/StandingItem/StandingItemScriptBase#getnearunit), [IsInRange(UnitModel, float)](/api/Global/Unused/StandingItem/StandingItemScriptBase#isinrange-unitmodel-float), [CanTakePhsyicalDamage(UnitModel)](/api/Global/Unused/StandingItem/StandingItemScriptBase#cantakephsyicaldamage-unitmodel), [IsAttackable()](/api/Global/Unused/StandingItem/StandingItemScriptBase#isattackable), [OnBreakDown()](/api/Global/Unused/StandingItem/StandingItemScriptBase#onbreakdown), [OnIgnoreDamage(UnitModel)](/api/Global/Unused/StandingItem/StandingItemScriptBase#onignoredamage-unitmodel), [OnDestroyStandingItem()](/api/Global/Unused/StandingItem/StandingItemScriptBase#ondestroystandingitem), [OnTakePhyisclaDamage(float)](/api/Global/Unused/StandingItem/StandingItemScriptBase#ontakephyiscladamage-float), [Prob(float)](/api/Global/Unused/StandingItem/StandingItemScriptBase#prob-float), [Prob(int)](/api/Global/Unused/StandingItem/StandingItemScriptBase#prob-int), [CheckCameraRange()](/api/Global/Unused/StandingItem/StandingItemScriptBase#checkcamerarange), [CheckCameraRange(float)](/api/Global/Unused/StandingItem/StandingItemScriptBase#checkcamerarange-float), [Model](/api/Global/Unused/StandingItem/StandingItemScriptBase#model), [Movable](/api/Global/Unused/StandingItem/StandingItemScriptBase#movable), [Passage](/api/Global/Unused/StandingItem/StandingItemScriptBase#passage), [State](/api/Global/Unused/StandingItem/StandingItemScriptBase#state), [MaxHp](/api/Global/Unused/StandingItem/StandingItemScriptBase#maxhp), [Defense](/api/Global/Unused/StandingItem/StandingItemScriptBase#defense), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)






