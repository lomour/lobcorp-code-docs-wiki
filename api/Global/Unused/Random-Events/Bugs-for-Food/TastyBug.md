---
uid: Global.TastyBug
canonical_path: /api/Global/Misc/TastyBug
---
# Class TastyBug
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class TastyBug : StandingItemScriptBase
```
> This section may have incomplete or incorrect information.
{.is-warning}

> This class is not used.
{.is-info}





## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [StandingItemScriptBase](/api/Global/Unused/StandingItem/StandingItemScriptBase) → TastyBug

## Constructors
### TastyBug()
```csharp
public TastyBug()
```

## Fields
### _alive
```csharp
private TastyBug.BugAlive _alive
```

#### Field Value
**Type:** Global.TastyBug.BugAlive

### _bugState
```csharp
private TastyBug.BugState _bugState
```

#### Field Value
**Type:** Global.TastyBug.BugState

### _type
```csharp
private TastyBug.BugType _type
```

#### Field Value
**Type:** Global.TastyBug.BugType

### animScript
```csharp
public TastyBugAnim animScript
```


#### Field Value
**Type:** Global.TastyBugAnim

### appearEffectMake
```csharp
private bool appearEffectMake
```


#### Field Value
**Type:** System.Boolean

### creatureHeal
```csharp
public const int creatureHeal = 18
```


#### Field Value
**Type:** System.Int32

### defaultMoveFreq
```csharp
public const float defaultMoveFreq = 0
```


#### Field Value
**Type:** System.Single

### defaultSound
```csharp
public SoundEffectPlayer defaultSound
```


#### Field Value
**Type:** Global.SoundEffectPlayer

### eatRange
```csharp
public const float eatRange = 0.4
```


#### Field Value
**Type:** System.Single

### enableDelay
```csharp
public Timer enableDelay
```


#### Field Value
**Type:** Global.Timer

### healRange
```csharp
public const float healRange = 0.5
```


#### Field Value
**Type:** System.Single

### itemHeal
```csharp
public const int itemHeal = 18
```


#### Field Value
**Type:** System.Int32

### mentalDamage
```csharp
public const int mentalDamage = 6
```


#### Field Value
**Type:** System.Int32

### moveTimer
```csharp
public Timer moveTimer
```


#### Field Value
**Type:** Global.Timer

### nodeList
```csharp
public List<MapNode> nodeList
```


#### Field Value
**Type:** System.Collections.Generic.List{MapNode}

### randomEvent
```csharp
public BugsForFoodEvent randomEvent
```


#### Field Value
**Type:** Global.BugsForFoodEvent

### sound_default
```csharp
public const string sound_default = "RandomEvent/TastyBugs/TastyBug_Default"
```


#### Field Value
**Type:** System.String

### speed
```csharp
public const float speed = 0.2
```


#### Field Value
**Type:** System.Single

### textUI
```csharp
public Text textUI
```


#### Field Value
**Type:** UnityEngine.UI.Text

### volume
```csharp
public const float volume = 0.5
```


#### Field Value
**Type:** System.Single

### workerHeal
```csharp
public const int workerHeal = 12
```


#### Field Value
**Type:** System.Int32

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

### CheckDistance(UnitModel)
```csharp
public float CheckDistance(UnitModel target)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

#### Returns
**Type:** System.Single

### CheckInRange()
```csharp
public bool CheckInRange()
```


#### Returns
**Type:** System.Boolean

### DelayedEnable(float)
```csharp
public void DelayedEnable(float delay)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `delay` | `System.Single` |  |

### HealInRange()
```csharp
public void HealInRange()
```


### Init()
```csharp
public override void Init()
```


### IsActive()
```csharp
public bool IsActive()
```


#### Returns
**Type:** System.Boolean

### IsAttackable()
```csharp
public override bool IsAttackable()
```


#### Returns
**Type:** System.Boolean

### MoveAround()
```csharp
public void MoveAround()
```


### OnBreakDown()
```csharp
public override void OnBreakDown()
```


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

### ReadyToMove()
```csharp
public void ReadyToMove()
```


### SetActive(bool)
```csharp
public void SetActive(bool state)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### SetEvent(BugsForFoodEvent)
```csharp
public void SetEvent(BugsForFoodEvent bff)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `bff` | `Global.BugsForFoodEvent` |  |

### SetType(BugType)
```csharp
public void SetType(TastyBug.BugType type)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.TastyBug.BugType` |  |

### Type()
```csharp
public TastyBug.BugType Type()
```

#### Returns
**Type:** Global.TastyBug.BugType

## Inherited Members
[soundDistDobule](/api/Global/Unused/StandingItem/StandingItemScriptBase#sounddistdobule), [model](/api/Global/Unused/StandingItem/StandingItemScriptBase#model), [_animScript](/api/Global/Unused/StandingItem/StandingItemScriptBase#animscript), [_state](/api/Global/Unused/StandingItem/StandingItemScriptBase#state), [name](/api/Global/Unused/StandingItem/StandingItemScriptBase#name), [_maxHp](/api/Global/Unused/StandingItem/StandingItemScriptBase#maxhp), [_defense](/api/Global/Unused/StandingItem/StandingItemScriptBase#defense), [SetModel(StandingItemModel)](/api/Global/Unused/StandingItem/StandingItemScriptBase#setmodel-standingitemmodel), [OnNearUnitArrived(List<UnitModel>)](/api/Global/Unused/StandingItem/StandingItemScriptBase#onnearunitarrived-list-unitmodel), [SetAnimScript(StandingItemAnim)](/api/Global/Unused/StandingItem/StandingItemScriptBase#setanimscript-standingitemanim), [GetNearUnit()](/api/Global/Unused/StandingItem/StandingItemScriptBase#getnearunit), [IsInRange(UnitModel, float)](/api/Global/Unused/StandingItem/StandingItemScriptBase#isinrange-unitmodel-float), [OnIgnoreDamage(UnitModel)](/api/Global/Unused/StandingItem/StandingItemScriptBase#onignoredamage-unitmodel), [OnDestroyStandingItem()](/api/Global/Unused/StandingItem/StandingItemScriptBase#ondestroystandingitem), [OnTakePhyisclaDamage(float)](/api/Global/Unused/StandingItem/StandingItemScriptBase#ontakephyiscladamage-float), [GetName()](/api/Global/Unused/StandingItem/StandingItemScriptBase#getname), [SetName(string)](/api/Global/Unused/StandingItem/StandingItemScriptBase#setname-string), [HasName()](/api/Global/Unused/StandingItem/StandingItemScriptBase#hasname), [Prob(float)](/api/Global/Unused/StandingItem/StandingItemScriptBase#prob-float), [Prob(int)](/api/Global/Unused/StandingItem/StandingItemScriptBase#prob-int), [CheckCameraRange()](/api/Global/Unused/StandingItem/StandingItemScriptBase#checkcamerarange), [CheckCameraRange(float)](/api/Global/Unused/StandingItem/StandingItemScriptBase#checkcamerarange-float), [Model](/api/Global/Unused/StandingItem/StandingItemScriptBase#model), [Movable](/api/Global/Unused/StandingItem/StandingItemScriptBase#movable), [Passage](/api/Global/Unused/StandingItem/StandingItemScriptBase#passage), [State](/api/Global/Unused/StandingItem/StandingItemScriptBase#state), [MaxHp](/api/Global/Unused/StandingItem/StandingItemScriptBase#maxhp), [Defense](/api/Global/Unused/StandingItem/StandingItemScriptBase#defense), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)






