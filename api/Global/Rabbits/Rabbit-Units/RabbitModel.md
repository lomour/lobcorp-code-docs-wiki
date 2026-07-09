---
uid: Global.RabbitModel
canonical_path: /api/Global/Model/RabbitModel
---
# Class RabbitModel
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class RabbitModel : UnitModel, IMouseCommandTargetModel
```
> This section may have incomplete or incorrect information.
{.is-warning}


A rabbit, abstractly. Managed by [RabbitManager](/api/Global/Rabbits/RabbitManager).




## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitModel](/api/Global/Units/UnitModel) → RabbitModel

## Implements
[IMouseCommandTargetModel](/api/Global/Mouse-Usage/Mouse-Listeners/IMouseCommandTargetModel)

## Constructors
### RabbitModel(RwbpType)
```csharp
public RabbitModel(RwbpType rwbpType)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `rwbpType` | `Global.RwbpType` |  |

## Fields
### _activated
```csharp
private bool _activated
```


#### Field Value
**Type:** System.Boolean

### _commandQueue
```csharp
private RabbitCommandQueue _commandQueue
```


#### Field Value
**Type:** Global.RabbitCommandQueue

### _currentWeapon
```csharp
private RabbitWeaponEnum _currentWeapon
```


#### Field Value
**Type:** Global.RabbitWeaponEnum

### _encounterClearTimer
```csharp
private Timer _encounterClearTimer
```


#### Field Value
**Type:** Global.Timer

### _isDead
```csharp
private bool _isDead
```


#### Field Value
**Type:** System.Boolean

### _remainFireDelay
```csharp
private float _remainFireDelay
```


#### Field Value
**Type:** System.Single

### _rwbpType
```csharp
private RwbpType _rwbpType
```


#### Field Value
**Type:** Global.RwbpType

### _unit
```csharp
private RabbitUnit _unit
```


#### Field Value
**Type:** Global.RabbitUnit

### encountClearFreq
```csharp
private float encountClearFreq
```


#### Field Value
**Type:** System.Single

### encountered
```csharp
private List<UnitModel> encountered
```


#### Field Value
**Type:** System.Collections.Generic.List{UnitModel}

## Properties
### name
```csharp
public string name { get; }
```

#### Property Value
**Type:** System.String

### rwbpType
```csharp
public RwbpType rwbpType { get; }
```

#### Property Value
**Type:** Global.RwbpType

### Unit
```csharp
public RabbitUnit Unit { get; }
```

#### Property Value
**Type:** Global.RabbitUnit

## Methods
### Attack(UnitModel)
```csharp
public override void Attack(UnitModel target)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### CheckNear()
```csharp
public void CheckNear()
```


### ClearOperation()
```csharp
public void ClearOperation()
```


### Fire()
```csharp
public void Fire()
```


### GetAttackLevel()
```csharp
public override int GetAttackLevel()
```


#### Returns
**Type:** System.Int32

### GetCurrentCommand()
```csharp
public UnitCommand GetCurrentCommand()
```


#### Returns
**Type:** Global.UnitCommand

### GetDefenseLevel()
```csharp
public override int GetDefenseLevel()
```


#### Returns
**Type:** System.Int32

### GetRiskLevel()
```csharp
public override int GetRiskLevel()
```


#### Returns
**Type:** System.Int32

### IsAttackTargetable()
```csharp
public override bool IsAttackTargetable()
```


#### Returns
**Type:** System.Boolean

### IsDead()
```csharp
public bool IsDead()
```


#### Returns
**Type:** System.Boolean

### IsFireState()
```csharp
public bool IsFireState()
```


#### Returns
**Type:** System.Boolean

### IsHostile(UnitModel)
```csharp
public override bool IsHostile(UnitModel target)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

#### Returns
**Type:** System.Boolean

### MakeSound(string)
```csharp
public SoundEffectPlayer MakeSound(string src)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

#### Returns
**Type:** Global.SoundEffectPlayer

### OnAnimEventCalled(int)
```csharp
public void OnAnimEventCalled(int index)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### OnClearProtocol()
```csharp
public void OnClearProtocol()
```


### OnDie()
```csharp
public void OnDie()
```


### OnDieByMental()
```csharp
public void OnDieByMental()
```


### OnEndCycle()
```csharp
public void OnEndCycle()
```


### OnFixedUpdate()
```csharp
public void OnFixedUpdate()
```


### OnGiveDamage()
```csharp
public void OnGiveDamage()
```


### OnGiveDamageByRifle()
```csharp
private void OnGiveDamageByRifle()
```


### PlayAttackAnimation(string)
```csharp
protected override void PlayAttackAnimation(string animationName)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `animationName` | `System.String` |  |

### SetCommand(UnitCommand)
```csharp
public void SetCommand(UnitCommand cmd)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `cmd` | `Global.UnitCommand` |  |

### SetUnit(RabbitUnit)
```csharp
public void SetUnit(RabbitUnit unit)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.RabbitUnit` |  |

### SetUnitState(bool)
```csharp
public void SetUnitState(bool state)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### TakeDamage(UnitModel, DamageInfo)
```csharp
public override void TakeDamage(UnitModel actor, DamageInfo dmg)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |
| `dmg` | `Global.DamageInfo` |  |

### TakeDamageWithoutEffect(UnitModel, DamageInfo)
```csharp
public override void TakeDamageWithoutEffect(UnitModel actor, DamageInfo dmg)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |
| `dmg` | `Global.DamageInfo` |  |

## Inherited Members
[stunCriteria](/api/Global/Units/UnitModel#stuncriteria), [defaultStunEffectSrc](/api/Global/Units/UnitModel#defaultstuneffectsrc), [instanceId](/api/Global/Units/UnitModel#instanceid), [movableNode](/api/Global/Units/UnitModel#movablenode), [shield](/api/Global/Units/UnitModel#shield), [_equipment](/api/Global/Units/UnitModel#equipment), [tempAnim](/api/Global/Units/UnitModel#tempanim), [factionTypeInfo](/api/Global/Units/UnitModel#factiontypeinfo), [stunTimer](/api/Global/Units/UnitModel#stuntimer), [hp](/api/Global/Units/UnitModel#hp), [mental](/api/Global/Units/UnitModel#mental), [baseMaxHp](/api/Global/Units/UnitModel#basemaxhp), [baseMaxMental](/api/Global/Units/UnitModel#basemaxmental), [baseMovement](/api/Global/Units/UnitModel#basemovement), [baseRegeneration](/api/Global/Units/UnitModel#baseregeneration), [baseRegenerationDelay](/api/Global/Units/UnitModel#baseregenerationdelay), [additionalDef](/api/Global/Units/UnitModel#additionaldef), [superArmorMax](/api/Global/Units/UnitModel#superarmormax), [superArmor](/api/Global/Units/UnitModel#superarmor), [superArmorDefense](/api/Global/Units/UnitModel#superarmordefense), [remainMoveDelay](/api/Global/Units/UnitModel#remainmovedelay), [remainAttackDelay](/api/Global/Units/UnitModel#remainattackdelay), [isStun](/api/Global/Units/UnitModel#isstun), [damageTransform](/api/Global/Units/UnitModel#damagetransform), [basePhysicalDefense](/api/Global/Units/UnitModel#basephysicaldefense), [baseMentalDefense](/api/Global/Units/UnitModel#basementaldefense), [encounteredWorker](/api/Global/Units/UnitModel#encounteredworker), [_bufList](/api/Global/Units/UnitModel#buflist), [_statBufList](/api/Global/Units/UnitModel#statbuflist), [_barrierBufList](/api/Global/Units/UnitModel#barrierbuflist), [CanOpenDoor()](/api/Global/Units/UnitModel#canopendoor), [GetUnitName()](/api/Global/Units/UnitModel#getunitname), [InteractWithDoor(DoorObjectModel)](/api/Global/Units/UnitModel#interactwithdoor-doorobjectmodel), [OnStopMovableByShield(AgentModel)](/api/Global/Units/UnitModel#onstopmovablebyshield-agentmodel), [GetMovableNode()](/api/Global/Units/UnitModel#getmovablenode), [GetCurrentViewPosition()](/api/Global/Units/UnitModel#getcurrentviewposition), [SetWeapon(WeaponModel)](/api/Global/Units/UnitModel#setweapon-weaponmodel), [ReleaseWeaponV2()](/api/Global/Units/UnitModel#releaseweaponv2), [SetArmor(ArmorModel)](/api/Global/Units/UnitModel#setarmor-armormodel), [ReleaseArmor()](/api/Global/Units/UnitModel#releasearmor), [AttachEGOgift(EGOgiftModel)](/api/Global/Units/UnitModel#attachegogift-egogiftmodel), [ReleaseEGOgift(EGOgiftModel)](/api/Global/Units/UnitModel#releaseegogift-egogiftmodel), [ReleaseEGOGift(int)](/api/Global/Units/UnitModel#releaseegogift-int), [SetGiftDisplayState(EGOgiftModel, bool)](/api/Global/Units/UnitModel#setgiftdisplaystate-egogiftmodel-bool), [GetGiftDisplayState(EGOgiftModel)](/api/Global/Units/UnitModel#getgiftdisplaystate-egogiftmodel), [SetGiftLockState(EGOgiftModel, bool)](/api/Global/Units/UnitModel#setgiftlockstate-egogiftmodel-bool), [SetKitCreature(CreatureModel)](/api/Global/Units/UnitModel#setkitcreature-creaturemodel), [ReleaseKitCreature(bool)](/api/Global/Units/UnitModel#releasekitcreature-bool), [OnSetWeapon()](/api/Global/Units/UnitModel#onsetweapon), [OnReleaseWeapon()](/api/Global/Units/UnitModel#onreleaseweapon), [OnSetArmor()](/api/Global/Units/UnitModel#onsetarmor), [OnReleaseArmor()](/api/Global/Units/UnitModel#onreleasearmor), [OnChangeGift()](/api/Global/Units/UnitModel#onchangegift), [OnSetKitCreature()](/api/Global/Units/UnitModel#onsetkitcreature), [OnReleaseKitCreature()](/api/Global/Units/UnitModel#onreleasekitcreature), [GetWeaponSpriteSrc()](/api/Global/Units/UnitModel#getweaponspritesrc), [GetWeaponSprite()](/api/Global/Units/UnitModel#getweaponsprite), [PrepareWeapon()](/api/Global/Units/UnitModel#prepareweapon), [CancelWeapon()](/api/Global/Units/UnitModel#cancelweapon), [IsAttackState()](/api/Global/Units/UnitModel#isattackstate), [InWeaponRange(UnitModel)](/api/Global/Units/UnitModel#inweaponrange-unitmodel), [StopAttack()](/api/Global/Units/UnitModel#stopattack), [OnGiveDamageByWeapon()](/api/Global/Units/UnitModel#ongivedamagebyweapon), [GetDamageFactorByEquipment()](/api/Global/Units/UnitModel#getdamagefactorbyequipment), [GetDamageFactorBySefiraAbility()](/api/Global/Units/UnitModel#getdamagefactorbysefiraability), [OnEndAttackCycle()](/api/Global/Units/UnitModel#onendattackcycle), [EndAttackAnimation()](/api/Global/Units/UnitModel#endattackanimation), [GetEGObonus()](/api/Global/Units/UnitModel#getegobonus), [HasEquipment(int)](/api/Global/Units/UnitModel#hasequipment-int), [AddSuperArmorMax(float)](/api/Global/Units/UnitModel#addsuperarmormax-float), [SubSuperArmorMax(float)](/api/Global/Units/UnitModel#subsuperarmormax-float), [TakeDamage(DamageInfo)](/api/Global/Units/UnitModel#takedamage-damageinfo), [MakeDamageEffect(RwbpType, float, Type)](/api/Global/Units/UnitModel#makedamageeffect-rwbptype-float-type), [UnderAttack(UnitModel)](/api/Global/Units/UnitModel#underattack-unitmodel), [ClearWorkerEncounting()](/api/Global/Units/UnitModel#clearworkerencounting), [CheckNearWorkerEncounting()](/api/Global/Units/UnitModel#checknearworkerencounting), [IsStunned()](/api/Global/Units/UnitModel#isstunned), [OnSuperArmorBreak()](/api/Global/Units/UnitModel#onsuperarmorbreak), [SetMoveDelay(float)](/api/Global/Units/UnitModel#setmovedelay-float), [SetAttackDelay()](/api/Global/Units/UnitModel#setattackdelay), [SetAttackDelay(float)](/api/Global/Units/UnitModel#setattackdelay-float), [UpdateBufState()](/api/Global/Units/UnitModel#updatebufstate), [AddUnitBuf(UnitBuf)](/api/Global/Units/UnitModel#addunitbuf-unitbuf), [HasUnitBuf(UnitBufType)](/api/Global/Units/UnitModel#hasunitbuf-unitbuftype), [GetUnitBufByType(UnitBufType)](/api/Global/Units/UnitModel#getunitbufbytype-unitbuftype), [RemoveUnitBuf(UnitBuf)](/api/Global/Units/UnitModel#removeunitbuf-unitbuf), [GetMaxHpBuf()](/api/Global/Units/UnitModel#getmaxhpbuf), [GetMaxMentalBuf()](/api/Global/Units/UnitModel#getmaxmentalbuf), [GetCubeSpeedBuf()](/api/Global/Units/UnitModel#getcubespeedbuf), [GetWorkProbBuf()](/api/Global/Units/UnitModel#getworkprobbuf), [GetAttackSpeedBuf()](/api/Global/Units/UnitModel#getattackspeedbuf), [GetMovementBuf()](/api/Global/Units/UnitModel#getmovementbuf), [GetPrimaryStatBuf()](/api/Global/Units/UnitModel#getprimarystatbuf), [GetMovementScaleByBuf()](/api/Global/Units/UnitModel#getmovementscalebybuf), [SetFaction(FactionTypeInfo)](/api/Global/Units/UnitModel#setfaction-factiontypeinfo), [SetFaction(string)](/api/Global/Units/UnitModel#setfaction-string), [GetFaction()](/api/Global/Units/UnitModel#getfaction), [SetFactionForcely(string)](/api/Global/Units/UnitModel#setfactionforcely-string), [OnStun(float)](/api/Global/Units/UnitModel#onstun-float), [OnStunEnd()](/api/Global/Units/UnitModel#onstunend), [GetDmgMultiplierByEgoLevel(int, int)](/api/Global/Units/UnitModel#getdmgmultiplierbyegolevel-int-int), [GetBufDamageMultiplier(UnitModel, DamageInfo)](/api/Global/Units/UnitModel#getbufdamagemultiplier-unitmodel-damageinfo), [GetUnitBufByName(string)](/api/Global/Units/UnitModel#getunitbufbyname-string), [GetUnitBufList()](/api/Global/Units/UnitModel#getunitbuflist), [Equipment](/api/Global/Units/UnitModel#equipment), [radius](/api/Global/Units/UnitModel#radius), [maxHp](/api/Global/Units/UnitModel#maxhp), [maxMental](/api/Global/Units/UnitModel#maxmental), [movement](/api/Global/Units/UnitModel#movement), [regeneration](/api/Global/Units/UnitModel#regeneration), [regenerationDelay](/api/Global/Units/UnitModel#regenerationdelay), [defense](/api/Global/Units/UnitModel#defense), [attackSpeed](/api/Global/Units/UnitModel#attackspeed), [damage](/api/Global/Units/UnitModel#damage), [physicalDefense](/api/Global/Units/UnitModel#physicaldefense), [mentalDefense](/api/Global/Units/UnitModel#mentaldefense), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)







