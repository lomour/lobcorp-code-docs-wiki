---
uid: Global.OfficerModel
canonical_path: /api/Global/Worker/OfficerModel
---
# Class OfficerModel
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class OfficerModel : WorkerModel, IObserver, IMouseCommandTargetModel
```
> This section may have incomplete or incorrect information.
{.is-warning}


A clerk, abstractly.




## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitModel](/api/Global/Agents-and-Clerks/WorkerModel) → OfficerModel

## Implements
[IObserver](/api/Global/Mouse-Usage/Mouse-Listeners/IMouseCommandTargetModel)

## Constructors
### OfficerModel(long, string)
```csharp
public OfficerModel(long id, string area)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |
| `area` | `System.String` |  |

## Fields
### _panicImmuneTimer
```csharp
private Timer _panicImmuneTimer
```


#### Field Value
**Type:** Global.Timer

### _readyToSuicide
```csharp
private bool _readyToSuicide
```


#### Field Value
**Type:** System.Boolean

### _state
```csharp
private OfficerAIState _state
```


#### Field Value
**Type:** Global.OfficerAIState

### _unit
```csharp
private OfficerUnit _unit
```


#### Field Value
**Type:** Global.OfficerUnit

### currentSpecialAction
```csharp
private OfficerSpecialAction currentSpecialAction
```


#### Field Value
**Type:** Global.OfficerSpecialAction

### deadInit
```csharp
private bool deadInit
```


#### Field Value
**Type:** System.Boolean

### elapsedTime
```csharp
private float elapsedTime
```


#### Field Value
**Type:** System.Single

### isDebugger
```csharp
public bool isDebugger
```


#### Field Value
**Type:** System.Boolean

### isMoving
```csharp
private bool isMoving
```


#### Field Value
**Type:** System.Boolean

### lookingDir
```csharp
public LOOKINGDIR lookingDir
```


#### Field Value
**Type:** Global.LOOKINGDIR

### mentalReturn
```csharp
public int mentalReturn
```


#### Field Value
**Type:** System.Int32

### recoverElapsed
```csharp
private float recoverElapsed
```


#### Field Value
**Type:** System.Single

### recoveryRate
```csharp
public int recoveryRate
```


#### Field Value
**Type:** System.Int32

### screamElapsed
```csharp
private float screamElapsed
```


#### Field Value
**Type:** System.Single

### screamMax
```csharp
private float screamMax
```


#### Field Value
**Type:** System.Single

### shouldPanic
```csharp
private bool shouldPanic
```


#### Field Value
**Type:** System.Boolean

### startSpecialAction
```csharp
public bool startSpecialAction
```


#### Field Value
**Type:** System.Boolean

## Properties
### defense
```csharp
public override DefenseInfo defense { get; }
```

#### Property Value
**Type:** Global.DefenseInfo

### deptNum
```csharp
public int deptNum { get; set; }
```


#### Property Value
**Type:** System.Int32

### state
```csharp
public OfficerAIState state { get; set; }
```

#### Property Value
**Type:** Global.OfficerAIState

## Methods
### CancelWeapon()
```csharp
public override void CancelWeapon()
```


### CannotControll()
```csharp
public override bool CannotControll()
```


#### Returns
**Type:** System.Boolean

### ChangeHairSprite(SpriteInfo)
```csharp
public override void ChangeHairSprite(SpriteInfo spriteInfo)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `spriteInfo` | `Global.SpriteInfo` |  |

### ChangePuppetAnimToDie(string)
```csharp
public override WorkerDeadScript ChangePuppetAnimToDie(string src)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

#### Returns
**Type:** Global.WorkerDeadScript

### ChangePuppetAnimToUncon(string)
```csharp
public override void ChangePuppetAnimToUncon(string src)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

### ClearEffect()
```csharp
public override void ClearEffect()
```


### ClearUnconCommand()
```csharp
public override void ClearUnconCommand()
```


### EncounterCreature(UnitModel)
```csharp
public override void EncounterCreature(UnitModel encounteredCreature)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `encounteredCreature` | `Global.UnitModel` |  |

### EncounterStandingItem(StandingItemModel)
```csharp
public override void EncounterStandingItem(StandingItemModel standing)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `standing` | `Global.StandingItemModel` |  |

### EndSpecialAction()
```csharp
public void EndSpecialAction()
```


### GetControl()
```csharp
public override void GetControl()
```


### GetCurrentSefira()
```csharp
public override Sefira GetCurrentSefira()
```


#### Returns
**Type:** Global.Sefira

### GetState()
```csharp
public OfficerAIState GetState()
```


#### Returns
**Type:** Global.OfficerAIState

### GetUnit()
```csharp
public OfficerUnit GetUnit()
```


#### Returns
**Type:** Global.OfficerUnit

### GetUnitName()
```csharp
public override string GetUnitName()
```


#### Returns
**Type:** System.String

### GetWorkerUnit()
```csharp
public override WorkerUnit GetWorkerUnit()
```


#### Returns
**Type:** Global.WorkerUnit

### HaltSpecialAction()
```csharp
public void HaltSpecialAction()
```


### InitialEncounteredCreature(RiskLevel)
```csharp
public override void InitialEncounteredCreature(RiskLevel level)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `level` | `Global.RiskLevel` |  |

### InitialEncounteredCreature(UnitModel)
```csharp
public override void InitialEncounteredCreature(UnitModel encountered)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `encountered` | `Global.UnitModel` |  |

### IsCrazy()
```csharp
public override bool IsCrazy()
```


#### Returns
**Type:** System.Boolean

### IsPanic()
```csharp
public override bool IsPanic()
```


#### Returns
**Type:** System.Boolean

### LoseControl()
```csharp
public override void LoseControl()
```


### MakeCreatureEffect(long)
```csharp
public override GameObject MakeCreatureEffect(long id)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

#### Returns
**Type:** UnityEngine.GameObject

### MakeCreatureEffectHead(CreatureModel)
```csharp
public override GameObject MakeCreatureEffectHead(CreatureModel creature)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |

#### Returns
**Type:** UnityEngine.GameObject

### MakeCreatureEffectHead(CreatureModel, bool)
```csharp
public override GameObject MakeCreatureEffectHead(CreatureModel model, bool addlist)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.CreatureModel` |  |
| `addlist` | `System.Boolean` |  |

#### Returns
**Type:** UnityEngine.GameObject

### OnClick()
```csharp
public void OnClick()
```


### OnDie()
```csharp
public override void OnDie()
```


### OnFixedUpdate()
```csharp
public override void OnFixedUpdate()
```


### OnMemoEnd()
```csharp
public void OnMemoEnd()
```


### OnResurrect()
```csharp
public override void OnResurrect()
```


### OnSetWeapon()
```csharp
protected override void OnSetWeapon()
```


### OnStageEnd()
```csharp
public override void OnStageEnd()
```


### OnStageRelease()
```csharp
public override void OnStageRelease()
```


### Panic()
```csharp
public override void Panic()
```


### PanicOfficer(bool)
```csharp
public void PanicOfficer(bool force)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `force` | `System.Boolean` |  |

### PanicReadyComplete()
```csharp
public override void PanicReadyComplete()
```


### PrepareToSuicide()
```csharp
public void PrepareToSuicide()
```


### PrepareWeapon()
```csharp
public override void PrepareWeapon()
```


### ProcessAction()
```csharp
public override void ProcessAction()
```


### ProcessActionNormalOfficer()
```csharp
private void ProcessActionNormalOfficer()
```


### PursueUnconAgent(UnitModel)
```csharp
public override void PursueUnconAgent(UnitModel target)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### RecoverMental(float)
```csharp
public override void RecoverMental(float amount)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `amount` | `System.Single` |  |

### ResetAnimator()
```csharp
public override void ResetAnimator()
```


### ReturnSpecialAction()
```csharp
public void ReturnSpecialAction()
```


### ReturnToSefira()
```csharp
public override void ReturnToSefira()
```


### ReturnToSefiraFromWork()
```csharp
public void ReturnToSefiraFromWork()
```


### SetUncontrollableAction(UncontrollableAction)
```csharp
public override void SetUncontrollableAction(UncontrollableAction uncon)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `uncon` | `Global.UncontrollableAction` |  |

### SetUnit(OfficerUnit)
```csharp
public void SetUnit(OfficerUnit unit)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.OfficerUnit` |  |

### ShowCreatureActionSpeech(long, string)
```csharp
public override void ShowCreatureActionSpeech(long creatureID, string key)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `creatureID` | `System.Int64` |  |
| `key` | `System.String` |  |

### SpecialAction(OfficerSpecialAction)
```csharp
public void SpecialAction(OfficerSpecialAction action)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `action` | `Global.OfficerSpecialAction` |  |

### SpecialActionReturn()
```csharp
public void SpecialActionReturn()
```


### SpecialActionUpdate()
```csharp
public void SpecialActionUpdate()
```


### StartAction()
```csharp
public IEnumerator<WaitForSeconds> StartAction()
```


#### Returns
**Type:** System.Collections.Generic.IEnumerator{UnityEngine.WaitForSeconds}

### StopAction()
```csharp
public override void StopAction()
```


### StopPanic()
```csharp
public override void StopPanic()
```


### StopPanicWithoutStun()
```csharp
public override void StopPanicWithoutStun()
```


### Suicide()
```csharp
private void Suicide()
```


## Inherited Members
[commandQueue](/api/Global/Units/UnitModel#stuncriteria), [defaultStunEffectSrc](/api/Global/Units/UnitModel#defaultstuneffectsrc), [instanceId](/api/Global/Units/UnitModel#instanceid), [movableNode](/api/Global/Units/UnitModel#movablenode), [shield](/api/Global/Units/UnitModel#shield), [_equipment](/api/Global/Units/UnitModel#equipment), [tempAnim](/api/Global/Units/UnitModel#tempanim), [factionTypeInfo](/api/Global/Units/UnitModel#factiontypeinfo), [stunTimer](/api/Global/Units/UnitModel#stuntimer), [hp](/api/Global/Units/UnitModel#hp), [mental](/api/Global/Units/UnitModel#mental), [baseMaxHp](/api/Global/Units/UnitModel#basemaxhp), [baseMaxMental](/api/Global/Units/UnitModel#basemaxmental), [baseMovement](/api/Global/Units/UnitModel#basemovement), [baseRegeneration](/api/Global/Units/UnitModel#baseregeneration), [baseRegenerationDelay](/api/Global/Units/UnitModel#baseregenerationdelay), [additionalDef](/api/Global/Units/UnitModel#additionaldef), [superArmorMax](/api/Global/Units/UnitModel#superarmormax), [superArmor](/api/Global/Units/UnitModel#superarmor), [superArmorDefense](/api/Global/Units/UnitModel#superarmordefense), [remainMoveDelay](/api/Global/Units/UnitModel#remainmovedelay), [remainAttackDelay](/api/Global/Units/UnitModel#remainattackdelay), [isStun](/api/Global/Units/UnitModel#isstun), [damageTransform](/api/Global/Units/UnitModel#damagetransform), [basePhysicalDefense](/api/Global/Units/UnitModel#basephysicaldefense), [baseMentalDefense](/api/Global/Units/UnitModel#basementaldefense), [encounteredWorker](/api/Global/Units/UnitModel#encounteredworker), [_bufList](/api/Global/Units/UnitModel#buflist), [_statBufList](/api/Global/Units/UnitModel#statbuflist), [_barrierBufList](/api/Global/Units/UnitModel#barrierbuflist), [CanOpenDoor()](/api/Global/Units/UnitModel#canopendoor), [OnStopMovableByShield(AgentModel)](/api/Global/Units/UnitModel#onstopmovablebyshield-agentmodel), [GetMovableNode()](/api/Global/Units/UnitModel#getmovablenode), [GetCurrentViewPosition()](/api/Global/Units/UnitModel#getcurrentviewposition), [SetWeapon(WeaponModel)](/api/Global/Units/UnitModel#setweapon-weaponmodel), [ReleaseWeaponV2()](/api/Global/Units/UnitModel#releaseweaponv2), [SetArmor(ArmorModel)](/api/Global/Units/UnitModel#setarmor-armormodel), [ReleaseArmor()](/api/Global/Units/UnitModel#releasearmor), [AttachEGOgift(EGOgiftModel)](/api/Global/Units/UnitModel#attachegogift-egogiftmodel), [ReleaseEGOgift(EGOgiftModel)](/api/Global/Units/UnitModel#releaseegogift-egogiftmodel), [ReleaseEGOGift(int)](/api/Global/Units/UnitModel#releaseegogift-int), [SetGiftDisplayState(EGOgiftModel, bool)](/api/Global/Units/UnitModel#setgiftdisplaystate-egogiftmodel-bool), [GetGiftDisplayState(EGOgiftModel)](/api/Global/Units/UnitModel#getgiftdisplaystate-egogiftmodel), [SetGiftLockState(EGOgiftModel, bool)](/api/Global/Units/UnitModel#setgiftlockstate-egogiftmodel-bool), [SetKitCreature(CreatureModel)](/api/Global/Units/UnitModel#setkitcreature-creaturemodel), [ReleaseKitCreature(bool)](/api/Global/Units/UnitModel#releasekitcreature-bool), [OnReleaseWeapon()](/api/Global/Units/UnitModel#onreleaseweapon), [OnReleaseArmor()](/api/Global/Units/UnitModel#onreleasearmor), [OnChangeGift()](/api/Global/Units/UnitModel#onchangegift), [OnSetKitCreature()](/api/Global/Units/UnitModel#onsetkitcreature), [OnReleaseKitCreature()](/api/Global/Units/UnitModel#onreleasekitcreature), [GetWeaponSpriteSrc()](/api/Global/Units/UnitModel#getweaponspritesrc), [Attack(UnitModel)](/api/Global/Units/UnitModel#attack-unitmodel), [IsAttackState()](/api/Global/Units/UnitModel#isattackstate), [InWeaponRange(UnitModel)](/api/Global/Units/UnitModel#inweaponrange-unitmodel), [StopAttack()](/api/Global/Units/UnitModel#stopattack), [OnGiveDamageByWeapon()](/api/Global/Units/UnitModel#ongivedamagebyweapon), [GetDamageFactorByEquipment()](/api/Global/Units/UnitModel#getdamagefactorbyequipment), [GetDamageFactorBySefiraAbility()](/api/Global/Units/UnitModel#getdamagefactorbysefiraability), [OnEndAttackCycle()](/api/Global/Units/UnitModel#onendattackcycle), [EndAttackAnimation()](/api/Global/Units/UnitModel#endattackanimation), [GetEGObonus()](/api/Global/Units/UnitModel#getegobonus), [HasEquipment(int)](/api/Global/Units/UnitModel#hasequipment-int), [AddSuperArmorMax(float)](/api/Global/Units/UnitModel#addsuperarmormax-float), [SubSuperArmorMax(float)](/api/Global/Units/UnitModel#subsuperarmormax-float), [TakeDamage(DamageInfo)](/api/Global/Units/UnitModel#takedamage-damageinfo), [MakeDamageEffect(RwbpType, float, Type)](/api/Global/Units/UnitModel#makedamageeffect-rwbptype-float-type), [UnderAttack(UnitModel)](/api/Global/Units/UnitModel#underattack-unitmodel), [ClearWorkerEncounting()](/api/Global/Units/UnitModel#clearworkerencounting), [CheckNearWorkerEncounting()](/api/Global/Units/UnitModel#checknearworkerencounting), [IsStunned()](/api/Global/Units/UnitModel#isstunned), [OnSuperArmorBreak()](/api/Global/Units/UnitModel#onsuperarmorbreak), [SetMoveDelay(float)](/api/Global/Units/UnitModel#setmovedelay-float), [SetAttackDelay()](/api/Global/Units/UnitModel#setattackdelay), [SetAttackDelay(float)](/api/Global/Units/UnitModel#setattackdelay-float), [UpdateBufState()](/api/Global/Units/UnitModel#updatebufstate), [GetRiskLevel()](/api/Global/Units/UnitModel#getrisklevel), [GetAttackLevel()](/api/Global/Units/UnitModel#getattacklevel), [GetDefenseLevel()](/api/Global/Units/UnitModel#getdefenselevel), [AddUnitBuf(UnitBuf)](/api/Global/Units/UnitModel#addunitbuf-unitbuf), [HasUnitBuf(UnitBufType)](/api/Global/Units/UnitModel#hasunitbuf-unitbuftype), [GetUnitBufByType(UnitBufType)](/api/Global/Units/UnitModel#getunitbufbytype-unitbuftype), [RemoveUnitBuf(UnitBuf)](/api/Global/Units/UnitModel#removeunitbuf-unitbuf), [GetMaxHpBuf()](/api/Global/Units/UnitModel#getmaxhpbuf), [GetMaxMentalBuf()](/api/Global/Units/UnitModel#getmaxmentalbuf), [GetCubeSpeedBuf()](/api/Global/Units/UnitModel#getcubespeedbuf), [GetWorkProbBuf()](/api/Global/Units/UnitModel#getworkprobbuf), [GetAttackSpeedBuf()](/api/Global/Units/UnitModel#getattackspeedbuf), [GetMovementBuf()](/api/Global/Units/UnitModel#getmovementbuf), [GetPrimaryStatBuf()](/api/Global/Units/UnitModel#getprimarystatbuf), [GetMovementScaleByBuf()](/api/Global/Units/UnitModel#getmovementscalebybuf), [SetFaction(FactionTypeInfo)](/api/Global/Units/UnitModel#setfaction-factiontypeinfo), [SetFaction(string)](/api/Global/Units/UnitModel#setfaction-string), [GetFaction()](/api/Global/Units/UnitModel#getfaction), [SetFactionForcely(string)](/api/Global/Units/UnitModel#setfactionforcely-string), [OnStunEnd()](/api/Global/Units/UnitModel#onstunend), [GetDmgMultiplierByEgoLevel(int, int)](/api/Global/Units/UnitModel#getdmgmultiplierbyegolevel-int-int), [GetBufDamageMultiplier(UnitModel, DamageInfo)](/api/Global/Units/UnitModel#getbufdamagemultiplier-unitmodel-damageinfo), [GetUnitBufByName(string)](/api/Global/Units/UnitModel#getunitbufbyname-string), [GetUnitBufList()](/api/Global/Units/UnitModel#getunitbuflist), [Equipment](/api/Global/Units/UnitModel#equipment), [radius](/api/Global/Units/UnitModel#radius), [maxHp](/api/Global/Units/UnitModel#maxhp), [maxMental](/api/Global/Units/UnitModel#maxmental), [movement](/api/Global/Units/UnitModel#movement), [regeneration](/api/Global/Units/UnitModel#regeneration), [regenerationDelay](/api/Global/Units/UnitModel#regenerationdelay), [attackSpeed](/api/Global/Units/UnitModel#attackspeed), [damage](/api/Global/Units/UnitModel#damage), [physicalDefense](/api/Global/Units/UnitModel#physicaldefense), [mentalDefense](/api/Global/Units/UnitModel#mentaldefense), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)







