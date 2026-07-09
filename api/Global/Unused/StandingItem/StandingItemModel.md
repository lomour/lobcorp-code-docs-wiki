---
uid: Global.StandingItemModel
canonical_path: /api/Global/Model/StandingItemModel
---
# Class StandingItemModel
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class StandingItemModel : UnitModel
```
> This section may have incomplete or incorrect information.
{.is-warning}

> This class is not used.
{.is-info}





## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitModel](/api/Global/Units/UnitModel) → StandingItemModel

## Constructors
### StandingItemModel(UnitModel, MapNode)
```csharp
public StandingItemModel(UnitModel owner, MapNode position)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `owner` | `Global.UnitModel` |  |
| `position` | `Global.MapNode` |  |

## Fields
### blockActionUpdate
```csharp
public bool blockActionUpdate
```


#### Field Value
**Type:** System.Boolean

### blockPosition
```csharp
public bool blockPosition
```


#### Field Value
**Type:** System.Boolean

### blockScaling
```csharp
public bool blockScaling
```


#### Field Value
**Type:** System.Boolean

### commandQueue
```csharp
private StandingCommandQueue commandQueue
```


#### Field Value
**Type:** Global.StandingCommandQueue

### currentNode
```csharp
protected MapNode currentNode
```


#### Field Value
**Type:** Global.MapNode

### currentSefira
```csharp
protected Sefira currentSefira
```


#### Field Value
**Type:** Global.Sefira

### damageEvent
```csharp
private StandingItemModel.TakeDamageEvent damageEvent
```

#### Field Value
**Type:** Global.StandingItemModel.TakeDamageEvent

### data
```csharp
public ItemObjectData data
```


#### Field Value
**Type:** Global.ItemObjectData

### defaultMovement
```csharp
private const float defaultMovement = 1
```


#### Field Value
**Type:** System.Single

### owner
```csharp
public UnitModel owner
```


#### Field Value
**Type:** Global.UnitModel

### script
```csharp
public StandingItemScriptBase script
```


#### Field Value
**Type:** Global.StandingItemScriptBase

### speedMult
```csharp
public float speedMult
```


#### Field Value
**Type:** System.Single

### unit
```csharp
public StandingItemUnit unit
```


#### Field Value
**Type:** Global.StandingItemUnit

### useGlobalPosition
```csharp
public bool useGlobalPosition
```


#### Field Value
**Type:** System.Boolean

## Methods
### BuildScript(string)
```csharp
public void BuildScript(string scriptName)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `scriptName` | `System.String` |  |

### CheckRange(UnitModel, float)
```csharp
public bool CheckRange(UnitModel target, float range)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `range` | `System.Single` |  |

#### Returns
**Type:** System.Boolean

### CommonGenerator()
```csharp
private void CommonGenerator()
```


### DestroyUnit()
```csharp
public void DestroyUnit()
```


### GetCurrentCmd()
```csharp
public StandingCommand GetCurrentCmd()
```


#### Returns
**Type:** Global.StandingCommand

### GetSefira()
```csharp
public Sefira GetSefira()
```


#### Returns
**Type:** Global.Sefira

### GetState()
```csharp
public StandingItemScriptBase.StandingItemState GetState()
```


#### Returns
**Type:** Global.StandingItemScriptBase.StandingItemState

### GiveDamage(UnitModel, float)
```csharp
public void GiveDamage(UnitModel target, float damage)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `damage` | `System.Single` |  |

### IsAttackTargetable()
```csharp
public override bool IsAttackTargetable()
```


#### Returns
**Type:** System.Boolean

### LoadData(long)
```csharp
public void LoadData(long id)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

### MoveToMovable(MovableObjectNode)
```csharp
public void MoveToMovable(MovableObjectNode targetMovable)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `targetMovable` | `Global.MovableObjectNode` |  |

### MoveToMovable(MovableObjectNode, bool)
```csharp
public void MoveToMovable(MovableObjectNode targetMovable, bool resetCommand)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `targetMovable` | `Global.MovableObjectNode` |  |
| `resetCommand` | `System.Boolean` |  |

### MoveToMovable(MovableObjectNode, bool, OnCommandEnd)
```csharp
public void MoveToMovable(MovableObjectNode targetMovable, bool resetCommand, StandingCommand.OnCommandEnd end)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `targetMovable` | `Global.MovableObjectNode` |  |
| `resetCommand` | `System.Boolean` |  |
| `end` | `Global.StandingCommand.OnCommandEnd` |  |

### MoveToMovable(MovableObjectNode, OnCommandEnd)
```csharp
public void MoveToMovable(MovableObjectNode targetMovable, StandingCommand.OnCommandEnd end)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `targetMovable` | `Global.MovableObjectNode` |  |
| `end` | `Global.StandingCommand.OnCommandEnd` |  |

### MoveToNode(MapNode)
```csharp
public void MoveToNode(MapNode targetNode)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `targetNode` | `Global.MapNode` |  |

### MoveToNode(MapNode, bool)
```csharp
public void MoveToNode(MapNode targetNode, bool resetCommand)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `targetNode` | `Global.MapNode` |  |
| `resetCommand` | `System.Boolean` |  |

### MoveToNode(MapNode, bool, OnCommandEnd)
```csharp
public void MoveToNode(MapNode targetNode, bool resetCommand, StandingCommand.OnCommandEnd end)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `targetNode` | `Global.MapNode` |  |
| `resetCommand` | `System.Boolean` |  |
| `end` | `Global.StandingCommand.OnCommandEnd` |  |

### MoveToNode(MapNode, OnCommandEnd)
```csharp
public void MoveToNode(MapNode targetNode, StandingCommand.OnCommandEnd end)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `targetNode` | `Global.MapNode` |  |
| `end` | `Global.StandingCommand.OnCommandEnd` |  |

### OnBreakDown()
```csharp
public virtual void OnBreakDown()
```


### OnFixedUpdate()
```csharp
public void OnFixedUpdate()
```


### OnTryAttack()
```csharp
public virtual bool OnTryAttack()
```


#### Returns
**Type:** System.Boolean

### ProcessAction()
```csharp
public void ProcessAction()
```


### Reset()
```csharp
public virtual void Reset()
```


### SetDamageEvent(TakeDamageEvent)
```csharp
public void SetDamageEvent(StandingItemModel.TakeDamageEvent e)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `e` | `Global.StandingItemModel.TakeDamageEvent` |  |

### SetPosition(MapNode)
```csharp
public void SetPosition(MapNode node)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |

### SetSpeedMult()
```csharp
public void SetSpeedMult()
```


### SetSpeedMult(float)
```csharp
public void SetSpeedMult(float value)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Single` |  |

### SetUnit(StandingItemUnit)
```csharp
public void SetUnit(StandingItemUnit unit)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.StandingItemUnit` |  |

### StopCommand()
```csharp
public void StopCommand()
```


## Inherited Members
[stunCriteria](/api/Global/Units/UnitModel#stuncriteria), [defaultStunEffectSrc](/api/Global/Units/UnitModel#defaultstuneffectsrc), [instanceId](/api/Global/Units/UnitModel#instanceid), [movableNode](/api/Global/Units/UnitModel#movablenode), [shield](/api/Global/Units/UnitModel#shield), [_equipment](/api/Global/Units/UnitModel#equipment), [tempAnim](/api/Global/Units/UnitModel#tempanim), [factionTypeInfo](/api/Global/Units/UnitModel#factiontypeinfo), [stunTimer](/api/Global/Units/UnitModel#stuntimer), [hp](/api/Global/Units/UnitModel#hp), [mental](/api/Global/Units/UnitModel#mental), [baseMaxHp](/api/Global/Units/UnitModel#basemaxhp), [baseMaxMental](/api/Global/Units/UnitModel#basemaxmental), [baseMovement](/api/Global/Units/UnitModel#basemovement), [baseRegeneration](/api/Global/Units/UnitModel#baseregeneration), [baseRegenerationDelay](/api/Global/Units/UnitModel#baseregenerationdelay), [additionalDef](/api/Global/Units/UnitModel#additionaldef), [superArmorMax](/api/Global/Units/UnitModel#superarmormax), [superArmor](/api/Global/Units/UnitModel#superarmor), [superArmorDefense](/api/Global/Units/UnitModel#superarmordefense), [remainMoveDelay](/api/Global/Units/UnitModel#remainmovedelay), [remainAttackDelay](/api/Global/Units/UnitModel#remainattackdelay), [isStun](/api/Global/Units/UnitModel#isstun), [damageTransform](/api/Global/Units/UnitModel#damagetransform), [basePhysicalDefense](/api/Global/Units/UnitModel#basephysicaldefense), [baseMentalDefense](/api/Global/Units/UnitModel#basementaldefense), [encounteredWorker](/api/Global/Units/UnitModel#encounteredworker), [_bufList](/api/Global/Units/UnitModel#buflist), [_statBufList](/api/Global/Units/UnitModel#statbuflist), [_barrierBufList](/api/Global/Units/UnitModel#barrierbuflist), [CanOpenDoor()](/api/Global/Units/UnitModel#canopendoor), [GetUnitName()](/api/Global/Units/UnitModel#getunitname), [InteractWithDoor(DoorObjectModel)](/api/Global/Units/UnitModel#interactwithdoor-doorobjectmodel), [OnStopMovableByShield(AgentModel)](/api/Global/Units/UnitModel#onstopmovablebyshield-agentmodel), [GetMovableNode()](/api/Global/Units/UnitModel#getmovablenode), [GetCurrentViewPosition()](/api/Global/Units/UnitModel#getcurrentviewposition), [SetWeapon(WeaponModel)](/api/Global/Units/UnitModel#setweapon-weaponmodel), [ReleaseWeaponV2()](/api/Global/Units/UnitModel#releaseweaponv2), [SetArmor(ArmorModel)](/api/Global/Units/UnitModel#setarmor-armormodel), [ReleaseArmor()](/api/Global/Units/UnitModel#releasearmor), [AttachEGOgift(EGOgiftModel)](/api/Global/Units/UnitModel#attachegogift-egogiftmodel), [ReleaseEGOgift(EGOgiftModel)](/api/Global/Units/UnitModel#releaseegogift-egogiftmodel), [ReleaseEGOGift(int)](/api/Global/Units/UnitModel#releaseegogift-int), [SetGiftDisplayState(EGOgiftModel, bool)](/api/Global/Units/UnitModel#setgiftdisplaystate-egogiftmodel-bool), [GetGiftDisplayState(EGOgiftModel)](/api/Global/Units/UnitModel#getgiftdisplaystate-egogiftmodel), [SetGiftLockState(EGOgiftModel, bool)](/api/Global/Units/UnitModel#setgiftlockstate-egogiftmodel-bool), [SetKitCreature(CreatureModel)](/api/Global/Units/UnitModel#setkitcreature-creaturemodel), [ReleaseKitCreature(bool)](/api/Global/Units/UnitModel#releasekitcreature-bool), [OnSetWeapon()](/api/Global/Units/UnitModel#onsetweapon), [OnReleaseWeapon()](/api/Global/Units/UnitModel#onreleaseweapon), [OnSetArmor()](/api/Global/Units/UnitModel#onsetarmor), [OnReleaseArmor()](/api/Global/Units/UnitModel#onreleasearmor), [OnChangeGift()](/api/Global/Units/UnitModel#onchangegift), [OnSetKitCreature()](/api/Global/Units/UnitModel#onsetkitcreature), [OnReleaseKitCreature()](/api/Global/Units/UnitModel#onreleasekitcreature), [GetWeaponSpriteSrc()](/api/Global/Units/UnitModel#getweaponspritesrc), [GetWeaponSprite()](/api/Global/Units/UnitModel#getweaponsprite), [PrepareWeapon()](/api/Global/Units/UnitModel#prepareweapon), [CancelWeapon()](/api/Global/Units/UnitModel#cancelweapon), [Attack(UnitModel)](/api/Global/Units/UnitModel#attack-unitmodel), [IsAttackState()](/api/Global/Units/UnitModel#isattackstate), [InWeaponRange(UnitModel)](/api/Global/Units/UnitModel#inweaponrange-unitmodel), [StopAttack()](/api/Global/Units/UnitModel#stopattack), [OnGiveDamageByWeapon()](/api/Global/Units/UnitModel#ongivedamagebyweapon), [GetDamageFactorByEquipment()](/api/Global/Units/UnitModel#getdamagefactorbyequipment), [GetDamageFactorBySefiraAbility()](/api/Global/Units/UnitModel#getdamagefactorbysefiraability), [OnEndAttackCycle()](/api/Global/Units/UnitModel#onendattackcycle), [PlayAttackAnimation(string)](/api/Global/Units/UnitModel#playattackanimation-string), [EndAttackAnimation()](/api/Global/Units/UnitModel#endattackanimation), [GetEGObonus()](/api/Global/Units/UnitModel#getegobonus), [HasEquipment(int)](/api/Global/Units/UnitModel#hasequipment-int), [AddSuperArmorMax(float)](/api/Global/Units/UnitModel#addsuperarmormax-float), [SubSuperArmorMax(float)](/api/Global/Units/UnitModel#subsuperarmormax-float), [TakeDamage(DamageInfo)](/api/Global/Units/UnitModel#takedamage-damageinfo), [TakeDamage(UnitModel, DamageInfo)](/api/Global/Units/UnitModel#takedamage-unitmodel-damageinfo), [TakeDamageWithoutEffect(UnitModel, DamageInfo)](/api/Global/Units/UnitModel#takedamagewithouteffect-unitmodel-damageinfo), [MakeDamageEffect(RwbpType, float, Type)](/api/Global/Units/UnitModel#makedamageeffect-rwbptype-float-type), [UnderAttack(UnitModel)](/api/Global/Units/UnitModel#underattack-unitmodel), [ClearWorkerEncounting()](/api/Global/Units/UnitModel#clearworkerencounting), [CheckNearWorkerEncounting()](/api/Global/Units/UnitModel#checknearworkerencounting), [IsStunned()](/api/Global/Units/UnitModel#isstunned), [OnSuperArmorBreak()](/api/Global/Units/UnitModel#onsuperarmorbreak), [IsHostile(UnitModel)](/api/Global/Units/UnitModel#ishostile-unitmodel), [SetMoveDelay(float)](/api/Global/Units/UnitModel#setmovedelay-float), [SetAttackDelay()](/api/Global/Units/UnitModel#setattackdelay), [SetAttackDelay(float)](/api/Global/Units/UnitModel#setattackdelay-float), [UpdateBufState()](/api/Global/Units/UnitModel#updatebufstate), [GetRiskLevel()](/api/Global/Units/UnitModel#getrisklevel), [GetAttackLevel()](/api/Global/Units/UnitModel#getattacklevel), [GetDefenseLevel()](/api/Global/Units/UnitModel#getdefenselevel), [AddUnitBuf(UnitBuf)](/api/Global/Units/UnitModel#addunitbuf-unitbuf), [HasUnitBuf(UnitBufType)](/api/Global/Units/UnitModel#hasunitbuf-unitbuftype), [GetUnitBufByType(UnitBufType)](/api/Global/Units/UnitModel#getunitbufbytype-unitbuftype), [RemoveUnitBuf(UnitBuf)](/api/Global/Units/UnitModel#removeunitbuf-unitbuf), [GetMaxHpBuf()](/api/Global/Units/UnitModel#getmaxhpbuf), [GetMaxMentalBuf()](/api/Global/Units/UnitModel#getmaxmentalbuf), [GetCubeSpeedBuf()](/api/Global/Units/UnitModel#getcubespeedbuf), [GetWorkProbBuf()](/api/Global/Units/UnitModel#getworkprobbuf), [GetAttackSpeedBuf()](/api/Global/Units/UnitModel#getattackspeedbuf), [GetMovementBuf()](/api/Global/Units/UnitModel#getmovementbuf), [GetPrimaryStatBuf()](/api/Global/Units/UnitModel#getprimarystatbuf), [GetMovementScaleByBuf()](/api/Global/Units/UnitModel#getmovementscalebybuf), [SetFaction(FactionTypeInfo)](/api/Global/Units/UnitModel#setfaction-factiontypeinfo), [SetFaction(string)](/api/Global/Units/UnitModel#setfaction-string), [GetFaction()](/api/Global/Units/UnitModel#getfaction), [SetFactionForcely(string)](/api/Global/Units/UnitModel#setfactionforcely-string), [OnStun(float)](/api/Global/Units/UnitModel#onstun-float), [OnStunEnd()](/api/Global/Units/UnitModel#onstunend), [GetDmgMultiplierByEgoLevel(int, int)](/api/Global/Units/UnitModel#getdmgmultiplierbyegolevel-int-int), [GetBufDamageMultiplier(UnitModel, DamageInfo)](/api/Global/Units/UnitModel#getbufdamagemultiplier-unitmodel-damageinfo), [GetUnitBufByName(string)](/api/Global/Units/UnitModel#getunitbufbyname-string), [GetUnitBufList()](/api/Global/Units/UnitModel#getunitbuflist), [Equipment](/api/Global/Units/UnitModel#equipment), [radius](/api/Global/Units/UnitModel#radius), [maxHp](/api/Global/Units/UnitModel#maxhp), [maxMental](/api/Global/Units/UnitModel#maxmental), [movement](/api/Global/Units/UnitModel#movement), [regeneration](/api/Global/Units/UnitModel#regeneration), [regenerationDelay](/api/Global/Units/UnitModel#regenerationdelay), [defense](/api/Global/Units/UnitModel#defense), [attackSpeed](/api/Global/Units/UnitModel#attackspeed), [damage](/api/Global/Units/UnitModel#damage), [physicalDefense](/api/Global/Units/UnitModel#physicaldefense), [mentalDefense](/api/Global/Units/UnitModel#mentaldefense), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)






