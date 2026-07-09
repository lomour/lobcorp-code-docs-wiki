---
uid: Global.CircusTent
canonical_path: /api/Global/Misc/CircusTent
---
# Class CircusTent
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CircusTent : BoomerCircusScript
```
> This section may have incomplete or incorrect information.
{.is-warning}

> This class is not used.
{.is-info}

old tent ordeal thing



## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [StandingItemScriptBase](/api/Global/Unused/Random-Events/Circus/BoomerCircusScript) → CircusTent

## Constructors
### CircusTent()
```csharp
public CircusTent()
```

## Fields
### _tState
```csharp
private CircusTent.TentState _tState
```

#### Field Value
**Type:** Global.CircusTent.TentState

### animScript
```csharp
public CircusTentAnim animScript
```


#### Field Value
**Type:** Global.CircusTentAnim

### appearEffectMake
```csharp
private bool appearEffectMake
```


#### Field Value
**Type:** System.Boolean

### defaultSound
```csharp
public SoundEffectPlayer defaultSound
```


#### Field Value
**Type:** Global.SoundEffectPlayer

### enableDelay
```csharp
public Timer enableDelay
```


#### Field Value
**Type:** Global.Timer

### textUI
```csharp
public Text textUI
```


#### Field Value
**Type:** UnityEngine.UI.Text

## Methods
### AppearEffect()
```csharp
private void AppearEffect()
```


### CanRangeInCamera()
```csharp
public bool CanRangeInCamera()
```


#### Returns
**Type:** System.Boolean

### CanTakePhsyicalDamage(UnitModel)
```csharp
public override bool CanTakePhsyicalDamage(UnitModel target)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

#### Returns
**Type:** System.Boolean

### CreateBoomer()
```csharp
public void CreateBoomer()
```


### DelayedEnable(float)
```csharp
public void DelayedEnable(float delay)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `delay` | `System.Single` |  |

### Init()
```csharp
public override void Init()
```


### IsActive()
```csharp
public override bool IsActive()
```


#### Returns
**Type:** System.Boolean

### IsAttackable()
```csharp
public override bool IsAttackable()
```


#### Returns
**Type:** System.Boolean

### OnEnable()
```csharp
public void OnEnable()
```


### OnFixedUpdate(StandingItemModel)
```csharp
public override void OnFixedUpdate(StandingItemModel model)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.StandingItemModel` |  |

### SetActive(bool)
```csharp
public override void SetActive(bool state)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### SetEvent(BoomerCircusEvent)
```csharp
public override void SetEvent(BoomerCircusEvent bce)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `bce` | `Global.BoomerCircusEvent` |  |

## Inherited Members
[randomEvent](/api/Global/Unused/StandingItem/StandingItemScriptBase#sounddistdobule), [model](/api/Global/Unused/StandingItem/StandingItemScriptBase#model), [_animScript](/api/Global/Unused/StandingItem/StandingItemScriptBase#animscript), [_state](/api/Global/Unused/StandingItem/StandingItemScriptBase#state), [name](/api/Global/Unused/StandingItem/StandingItemScriptBase#name), [_maxHp](/api/Global/Unused/StandingItem/StandingItemScriptBase#maxhp), [_defense](/api/Global/Unused/StandingItem/StandingItemScriptBase#defense), [SetModel(StandingItemModel)](/api/Global/Unused/StandingItem/StandingItemScriptBase#setmodel-standingitemmodel), [OnNearUnitArrived(List<UnitModel>)](/api/Global/Unused/StandingItem/StandingItemScriptBase#onnearunitarrived-list-unitmodel), [SetAnimScript(StandingItemAnim)](/api/Global/Unused/StandingItem/StandingItemScriptBase#setanimscript-standingitemanim), [GetNearUnit()](/api/Global/Unused/StandingItem/StandingItemScriptBase#getnearunit), [IsInRange(UnitModel, float)](/api/Global/Unused/StandingItem/StandingItemScriptBase#isinrange-unitmodel-float), [OnBreakDown()](/api/Global/Unused/StandingItem/StandingItemScriptBase#onbreakdown), [OnIgnoreDamage(UnitModel)](/api/Global/Unused/StandingItem/StandingItemScriptBase#onignoredamage-unitmodel), [OnDestroyStandingItem()](/api/Global/Unused/StandingItem/StandingItemScriptBase#ondestroystandingitem), [OnTakePhyisclaDamage(float)](/api/Global/Unused/StandingItem/StandingItemScriptBase#ontakephyiscladamage-float), [GetName()](/api/Global/Unused/StandingItem/StandingItemScriptBase#getname), [SetName(string)](/api/Global/Unused/StandingItem/StandingItemScriptBase#setname-string), [HasName()](/api/Global/Unused/StandingItem/StandingItemScriptBase#hasname), [Prob(float)](/api/Global/Unused/StandingItem/StandingItemScriptBase#prob-float), [Prob(int)](/api/Global/Unused/StandingItem/StandingItemScriptBase#prob-int), [CheckCameraRange()](/api/Global/Unused/StandingItem/StandingItemScriptBase#checkcamerarange), [CheckCameraRange(float)](/api/Global/Unused/StandingItem/StandingItemScriptBase#checkcamerarange-float), [Model](/api/Global/Unused/StandingItem/StandingItemScriptBase#model), [Movable](/api/Global/Unused/StandingItem/StandingItemScriptBase#movable), [Passage](/api/Global/Unused/StandingItem/StandingItemScriptBase#passage), [State](/api/Global/Unused/StandingItem/StandingItemScriptBase#state), [MaxHp](/api/Global/Unused/StandingItem/StandingItemScriptBase#maxhp), [Defense](/api/Global/Unused/StandingItem/StandingItemScriptBase#defense), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)






