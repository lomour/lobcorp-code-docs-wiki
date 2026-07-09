---
uid: Global.DaughterBug
canonical_path: /api/Global/Misc/DaughterBug
---
# Class DaughterBug
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DaughterBug : HordeOfBugsScript
```
> This section may have incomplete or incorrect information.
{.is-warning}

> This class is not used.
{.is-info}




## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [StandingItemScriptBase](/api/Global/Unused/Random-Events/Horde-of-Bugs/HordeOfBugsScript) → DaughterBug

## Constructors
### DaughterBug()
```csharp
public DaughterBug()
```

## Fields
### _attackCount
```csharp
private int _attackCount
```


#### Field Value
**Type:** System.Int32

### _currentTarget
```csharp
private UnitModel _currentTarget
```


#### Field Value
**Type:** Global.UnitModel

### _dState
```csharp
private DaughterBug.DaughterState _dState
```

#### Field Value
**Type:** Global.DaughterBug.DaughterState

### _phase
```csharp
private DaughterBug.DaughterPhase _phase
```

#### Field Value
**Type:** Global.DaughterBug.DaughterPhase

### animScript
```csharp
public DaughterBugAnim animScript
```


#### Field Value
**Type:** Global.DaughterBugAnim

### appearEffectMake
```csharp
private bool appearEffectMake
```


#### Field Value
**Type:** System.Boolean

### attackDelay
```csharp
public const float attackDelay = 0.5
```


#### Field Value
**Type:** System.Single

### attackDelayTimer
```csharp
public Timer attackDelayTimer
```


#### Field Value
**Type:** Global.Timer

### attackDirection
```csharp
private UnitDirection attackDirection
```


#### Field Value
**Type:** Global.UnitDirection

### attackRange
```csharp
public const float attackRange = 5
```


#### Field Value
**Type:** System.Single

### damagedUnits
```csharp
private List<UnitModel> damagedUnits
```


#### Field Value
**Type:** System.Collections.Generic.List{UnitModel}

### defaultRange
```csharp
public const float defaultRange = 2
```


#### Field Value
**Type:** System.Single

### enableDelay
```csharp
public Timer enableDelay
```


#### Field Value
**Type:** Global.Timer

### makeChildFreq
```csharp
public const float makeChildFreq = 10
```


#### Field Value
**Type:** System.Single

### oldPosX
```csharp
private float oldPosX
```


#### Field Value
**Type:** System.Single

### sound_default
```csharp
public const string sound_default = "RandomEvent/Default"
```


#### Field Value
**Type:** System.String

### teleportDelay
```csharp
public const float teleportDelay = 2
```


#### Field Value
**Type:** System.Single

### teleportDelayTimer
```csharp
public Timer teleportDelayTimer
```


#### Field Value
**Type:** Global.Timer

### teleportFreq
```csharp
public const float teleportFreq = 2
```


#### Field Value
**Type:** System.Single

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

### DelayedEnable(float)
```csharp
public void DelayedEnable(float delay)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `delay` | `System.Single` |  |

### Enable(UnitDirection)
```csharp
public void Enable(UnitDirection direction)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `direction` | `Global.UnitDirection` |  |

### EncounterWorker()
```csharp
private void EncounterWorker()
```


### FindTarget()
```csharp
private void FindTarget()
```


### GiveDamageInRange(float, float)
```csharp
public void GiveDamageInRange(float range, float dmg)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `range` | `System.Single` |  |
| `dmg` | `System.Single` |  |

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

### IsHostile(UnitModel)
```csharp
private bool IsHostile(UnitModel u)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `u` | `Global.UnitModel` |  |

#### Returns
**Type:** System.Boolean

### OnBreakDown()
```csharp
public override void OnBreakDown()
```


### OnClick()
```csharp
public void OnClick()
```


### OnEnable()
```csharp
public void OnEnable()
```


### OnEndAttack()
```csharp
public void OnEndAttack()
```


### OnEndDigIn()
```csharp
public void OnEndDigIn()
```


### OnEndDigOut()
```csharp
public void OnEndDigOut()
```


### OnFixedUpdate(StandingItemModel)
```csharp
public override void OnFixedUpdate(StandingItemModel model)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.StandingItemModel` |  |

### ProccessAttack(float)
```csharp
private void ProccessAttack(float baseRange)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `baseRange` | `System.Single` |  |

### ProccessMoving()
```csharp
private void ProccessMoving()
```


### ReadyToTeleport()
```csharp
public void ReadyToTeleport()
```


### SetActive(bool)
```csharp
public void SetActive(bool state)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### SetEvent(HordeOfBugs)
```csharp
public override void SetEvent(HordeOfBugs hob)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `hob` | `Global.HordeOfBugs` |  |

### SetSpawnPosition(GrandmaBug)
```csharp
public void SetSpawnPosition(GrandmaBug grand)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `grand` | `Global.GrandmaBug` |  |

### StartAttack()
```csharp
private void StartAttack()
```


### StartTeleport()
```csharp
private void StartTeleport()
```


## Inherited Members
[randomEvent](/api/Global/Unused/StandingItem/StandingItemScriptBase#sounddistdobule), [model](/api/Global/Unused/StandingItem/StandingItemScriptBase#model), [_animScript](/api/Global/Unused/StandingItem/StandingItemScriptBase#animscript), [_state](/api/Global/Unused/StandingItem/StandingItemScriptBase#state), [name](/api/Global/Unused/StandingItem/StandingItemScriptBase#name), [_maxHp](/api/Global/Unused/StandingItem/StandingItemScriptBase#maxhp), [_defense](/api/Global/Unused/StandingItem/StandingItemScriptBase#defense), [SetModel(StandingItemModel)](/api/Global/Unused/StandingItem/StandingItemScriptBase#setmodel-standingitemmodel), [OnNearUnitArrived(List<UnitModel>)](/api/Global/Unused/StandingItem/StandingItemScriptBase#onnearunitarrived-list-unitmodel), [SetAnimScript(StandingItemAnim)](/api/Global/Unused/StandingItem/StandingItemScriptBase#setanimscript-standingitemanim), [GetNearUnit()](/api/Global/Unused/StandingItem/StandingItemScriptBase#getnearunit), [IsInRange(UnitModel, float)](/api/Global/Unused/StandingItem/StandingItemScriptBase#isinrange-unitmodel-float), [IsAttackable()](/api/Global/Unused/StandingItem/StandingItemScriptBase#isattackable), [OnIgnoreDamage(UnitModel)](/api/Global/Unused/StandingItem/StandingItemScriptBase#onignoredamage-unitmodel), [OnDestroyStandingItem()](/api/Global/Unused/StandingItem/StandingItemScriptBase#ondestroystandingitem), [OnTakePhyisclaDamage(float)](/api/Global/Unused/StandingItem/StandingItemScriptBase#ontakephyiscladamage-float), [GetName()](/api/Global/Unused/StandingItem/StandingItemScriptBase#getname), [SetName(string)](/api/Global/Unused/StandingItem/StandingItemScriptBase#setname-string), [HasName()](/api/Global/Unused/StandingItem/StandingItemScriptBase#hasname), [Prob(float)](/api/Global/Unused/StandingItem/StandingItemScriptBase#prob-float), [Prob(int)](/api/Global/Unused/StandingItem/StandingItemScriptBase#prob-int), [CheckCameraRange()](/api/Global/Unused/StandingItem/StandingItemScriptBase#checkcamerarange), [CheckCameraRange(float)](/api/Global/Unused/StandingItem/StandingItemScriptBase#checkcamerarange-float), [Model](/api/Global/Unused/StandingItem/StandingItemScriptBase#model), [Movable](/api/Global/Unused/StandingItem/StandingItemScriptBase#movable), [Passage](/api/Global/Unused/StandingItem/StandingItemScriptBase#passage), [State](/api/Global/Unused/StandingItem/StandingItemScriptBase#state), [MaxHp](/api/Global/Unused/StandingItem/StandingItemScriptBase#maxhp), [Defense](/api/Global/Unused/StandingItem/StandingItemScriptBase#defense), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)






