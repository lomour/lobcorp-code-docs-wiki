---
uid: Global.ChildCreatureModel
canonical_path: /api/Global/Creature/ChildCreatureModel
---
# Class ChildCreatureModel
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ChildCreatureModel : CreatureModel, ISerializablePlayData, IMouseCommandTargetModel, IObserver
```
> This section may have incomplete or incorrect information.
{.is-warning}


Parent class for [CreatureModels](/api/Global/Abnormalities/CreatureModel) of child creatures.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitModel](/api/Global/Abnormalities/CreatureModel) → ChildCreatureModel

## Implements
[ISerializablePlayData](/api/Global/Notices/IObserver)

## Constructors
### ChildCreatureModel(long)
```csharp
public ChildCreatureModel(long instanceId)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `instanceId` | `System.Int64` |  |

## Fields
### _parent
```csharp
private CreatureModel _parent
```


#### Field Value
**Type:** Global.CreatureModel

### _unit
```csharp
private ChildCreatureUnit _unit
```

#### Field Value
**Type:** Global.ChildCreatureUnit

### activateState
```csharp
public bool activateState
```


#### Field Value
**Type:** System.Boolean

### animAutoSet
```csharp
public bool animAutoSet
```


#### Field Value
**Type:** System.Boolean

### destroied
```csharp
public bool destroied
```


#### Field Value
**Type:** System.Boolean

### PortraitSrc
```csharp
public string PortraitSrc
```


#### Field Value
**Type:** System.String

### RiskLevel
```csharp
public RiskLevel RiskLevel
```


#### Field Value
**Type:** Global.RiskLevel

### Speed
```csharp
private float Speed
```


#### Field Value
**Type:** System.Single

## Properties
### childMetaInfo
```csharp
public ChildCreatureTypeInfo childMetaInfo { get; }
```

#### Property Value
**Type:** Global.ChildCreatureTypeInfo

### parent
```csharp
public CreatureModel parent { get; }
```

#### Property Value
**Type:** Global.CreatureModel

### Unit
```csharp
public ChildCreatureUnit Unit { get; }
```

#### Property Value
**Type:** Global.ChildCreatureUnit

## Methods
### CheckNearWorkerEncounting()
```csharp
public List<WorkerModel> CheckNearWorkerEncounting()
```

#### Returns
**Type:** System.Collections.Generic.List{WorkerModel}

### ChildInitialEncounter(WorkerModel)
```csharp
public void ChildInitialEncounter(WorkerModel worker)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

### Escape()
```csharp
public override void Escape()
```


### GenCreatureUnit(string)
```csharp
public ChildCreatureUnit GenCreatureUnit(string prefabSrc = null)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `prefabSrc` | `System.String` |  |

#### Returns
**Type:** Global.ChildCreatureUnit

### GetBaseMetaInfo()
```csharp
public CreatureTypeInfo GetBaseMetaInfo()
```


#### Returns
**Type:** Global.CreatureTypeInfo

### GetRiskLevel()
```csharp
public override int GetRiskLevel()
```


#### Returns
**Type:** System.Int32

### GetUnitName()
```csharp
public override string GetUnitName()
```


#### Returns
**Type:** System.String

### IsAttackTargetable()
```csharp
public override bool IsAttackTargetable()
```


#### Returns
**Type:** System.Boolean

### LoadCustom(ChildCreatureUnit, string)
```csharp
public void LoadCustom(ChildCreatureUnit component, string Src)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `component` | `Global.ChildCreatureUnit` |  |
| `Src` | `System.String` |  |

### LoadScript(string)
```csharp
private void LoadScript(string src)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

### OnDeleted()
```csharp
public void OnDeleted()
```


### OnEscapeUpdate()
```csharp
public override void OnEscapeUpdate()
```


### OnFixedUpdate()
```csharp
public override void OnFixedUpdate()
```


### OnNotice(string, params object[])
```csharp
public void OnNotice(string notice, params object[] param)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `notice` | `System.String` |  |
| `param` | `System.Object[]` |  |

### OnStageRelease()
```csharp
public override void OnStageRelease()
```


### PursueWorker(WorkerModel)
```csharp
public override void PursueWorker(WorkerModel target)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |

### SelfDestroy()
```csharp
public void SelfDestroy()
```


### SendAnimMessage(string)
```csharp
public override void SendAnimMessage(string name)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `name` | `System.String` |  |

### SetMoveAnimState(bool)
```csharp
public override void SetMoveAnimState(bool b)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `b` | `System.Boolean` |  |

### SetParent(CreatureModel)
```csharp
public void SetParent(CreatureModel creature)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |

### SetParent(CreatureModel, string, string)
```csharp
public void SetParent(CreatureModel creature, string childScriptSrc, string childPrefab)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |
| `childScriptSrc` | `System.String` |  |
| `childPrefab` | `System.String` |  |

### SetSpeed(float)
```csharp
public void SetSpeed(float speed = -1)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `speed` | `System.Single` |  |

### Suppressed()
```csharp
public override void Suppressed()
```


## Inherited Members
[regionName](/api/Global/Units/UnitModel#stuncriteria), [defaultStunEffectSrc](/api/Global/Units/UnitModel#defaultstuneffectsrc), [instanceId](/api/Global/Units/UnitModel#instanceid), [movableNode](/api/Global/Units/UnitModel#movablenode), [shield](/api/Global/Units/UnitModel#shield), [_equipment](/api/Global/Units/UnitModel#equipment), [tempAnim](/api/Global/Units/UnitModel#tempanim), [factionTypeInfo](/api/Global/Units/UnitModel#factiontypeinfo), [stunTimer](/api/Global/Units/UnitModel#stuntimer), [hp](/api/Global/Units/UnitModel#hp), [mental](/api/Global/Units/UnitModel#mental), [baseMaxHp](/api/Global/Units/UnitModel#basemaxhp), [baseMaxMental](/api/Global/Units/UnitModel#basemaxmental), [baseMovement](/api/Global/Units/UnitModel#basemovement), [baseRegeneration](/api/Global/Units/UnitModel#baseregeneration), [baseRegenerationDelay](/api/Global/Units/UnitModel#baseregenerationdelay), [additionalDef](/api/Global/Units/UnitModel#additionaldef), [superArmorMax](/api/Global/Units/UnitModel#superarmormax), [superArmor](/api/Global/Units/UnitModel#superarmor), [superArmorDefense](/api/Global/Units/UnitModel#superarmordefense), [remainMoveDelay](/api/Global/Units/UnitModel#remainmovedelay), [remainAttackDelay](/api/Global/Units/UnitModel#remainattackdelay), [isStun](/api/Global/Units/UnitModel#isstun), [damageTransform](/api/Global/Units/UnitModel#damagetransform), [basePhysicalDefense](/api/Global/Units/UnitModel#basephysicaldefense), [baseMentalDefense](/api/Global/Units/UnitModel#basementaldefense), [encounteredWorker](/api/Global/Units/UnitModel#encounteredworker), [_bufList](/api/Global/Units/UnitModel#buflist), [_statBufList](/api/Global/Units/UnitModel#statbuflist), [_barrierBufList](/api/Global/Units/UnitModel#barrierbuflist), [CanOpenDoor()](/api/Global/Units/UnitModel#canopendoor), [GetMovableNode()](/api/Global/Units/UnitModel#getmovablenode), [GetCurrentViewPosition()](/api/Global/Units/UnitModel#getcurrentviewposition), [SetWeapon(WeaponModel)](/api/Global/Units/UnitModel#setweapon-weaponmodel), [ReleaseWeaponV2()](/api/Global/Units/UnitModel#releaseweaponv2), [SetArmor(ArmorModel)](/api/Global/Units/UnitModel#setarmor-armormodel), [ReleaseArmor()](/api/Global/Units/UnitModel#releasearmor), [AttachEGOgift(EGOgiftModel)](/api/Global/Units/UnitModel#attachegogift-egogiftmodel), [ReleaseEGOgift(EGOgiftModel)](/api/Global/Units/UnitModel#releaseegogift-egogiftmodel), [ReleaseEGOGift(int)](/api/Global/Units/UnitModel#releaseegogift-int), [SetGiftDisplayState(EGOgiftModel, bool)](/api/Global/Units/UnitModel#setgiftdisplaystate-egogiftmodel-bool), [GetGiftDisplayState(EGOgiftModel)](/api/Global/Units/UnitModel#getgiftdisplaystate-egogiftmodel), [SetGiftLockState(EGOgiftModel, bool)](/api/Global/Units/UnitModel#setgiftlockstate-egogiftmodel-bool), [SetKitCreature(CreatureModel)](/api/Global/Units/UnitModel#setkitcreature-creaturemodel), [ReleaseKitCreature(bool)](/api/Global/Units/UnitModel#releasekitcreature-bool), [OnSetWeapon()](/api/Global/Units/UnitModel#onsetweapon), [OnReleaseWeapon()](/api/Global/Units/UnitModel#onreleaseweapon), [OnSetArmor()](/api/Global/Units/UnitModel#onsetarmor), [OnReleaseArmor()](/api/Global/Units/UnitModel#onreleasearmor), [OnChangeGift()](/api/Global/Units/UnitModel#onchangegift), [OnSetKitCreature()](/api/Global/Units/UnitModel#onsetkitcreature), [OnReleaseKitCreature()](/api/Global/Units/UnitModel#onreleasekitcreature), [GetWeaponSpriteSrc()](/api/Global/Units/UnitModel#getweaponspritesrc), [GetWeaponSprite()](/api/Global/Units/UnitModel#getweaponsprite), [PrepareWeapon()](/api/Global/Units/UnitModel#prepareweapon), [CancelWeapon()](/api/Global/Units/UnitModel#cancelweapon), [Attack(UnitModel)](/api/Global/Units/UnitModel#attack-unitmodel), [IsAttackState()](/api/Global/Units/UnitModel#isattackstate), [InWeaponRange(UnitModel)](/api/Global/Units/UnitModel#inweaponrange-unitmodel), [StopAttack()](/api/Global/Units/UnitModel#stopattack), [OnGiveDamageByWeapon()](/api/Global/Units/UnitModel#ongivedamagebyweapon), [GetDamageFactorByEquipment()](/api/Global/Units/UnitModel#getdamagefactorbyequipment), [GetDamageFactorBySefiraAbility()](/api/Global/Units/UnitModel#getdamagefactorbysefiraability), [OnEndAttackCycle()](/api/Global/Units/UnitModel#onendattackcycle), [EndAttackAnimation()](/api/Global/Units/UnitModel#endattackanimation), [GetEGObonus()](/api/Global/Units/UnitModel#getegobonus), [HasEquipment(int)](/api/Global/Units/UnitModel#hasequipment-int), [AddSuperArmorMax(float)](/api/Global/Units/UnitModel#addsuperarmormax-float), [SubSuperArmorMax(float)](/api/Global/Units/UnitModel#subsuperarmormax-float), [TakeDamage(DamageInfo)](/api/Global/Units/UnitModel#takedamage-damageinfo), [TakeDamageWithoutEffect(UnitModel, DamageInfo)](/api/Global/Units/UnitModel#takedamagewithouteffect-unitmodel-damageinfo), [MakeDamageEffect(RwbpType, float, Type)](/api/Global/Units/UnitModel#makedamageeffect-rwbptype-float-type), [UnderAttack(UnitModel)](/api/Global/Units/UnitModel#underattack-unitmodel), [ClearWorkerEncounting()](/api/Global/Units/UnitModel#clearworkerencounting), [IsStunned()](/api/Global/Units/UnitModel#isstunned), [SetMoveDelay(float)](/api/Global/Units/UnitModel#setmovedelay-float), [SetAttackDelay()](/api/Global/Units/UnitModel#setattackdelay), [SetAttackDelay(float)](/api/Global/Units/UnitModel#setattackdelay-float), [UpdateBufState()](/api/Global/Units/UnitModel#updatebufstate), [AddUnitBuf(UnitBuf)](/api/Global/Units/UnitModel#addunitbuf-unitbuf), [HasUnitBuf(UnitBufType)](/api/Global/Units/UnitModel#hasunitbuf-unitbuftype), [GetUnitBufByType(UnitBufType)](/api/Global/Units/UnitModel#getunitbufbytype-unitbuftype), [RemoveUnitBuf(UnitBuf)](/api/Global/Units/UnitModel#removeunitbuf-unitbuf), [GetMaxHpBuf()](/api/Global/Units/UnitModel#getmaxhpbuf), [GetMaxMentalBuf()](/api/Global/Units/UnitModel#getmaxmentalbuf), [GetCubeSpeedBuf()](/api/Global/Units/UnitModel#getcubespeedbuf), [GetWorkProbBuf()](/api/Global/Units/UnitModel#getworkprobbuf), [GetAttackSpeedBuf()](/api/Global/Units/UnitModel#getattackspeedbuf), [GetMovementBuf()](/api/Global/Units/UnitModel#getmovementbuf), [GetPrimaryStatBuf()](/api/Global/Units/UnitModel#getprimarystatbuf), [GetMovementScaleByBuf()](/api/Global/Units/UnitModel#getmovementscalebybuf), [GetFaction()](/api/Global/Units/UnitModel#getfaction), [SetFactionForcely(string)](/api/Global/Units/UnitModel#setfactionforcely-string), [OnStun(float)](/api/Global/Units/UnitModel#onstun-float), [OnStunEnd()](/api/Global/Units/UnitModel#onstunend), [GetDmgMultiplierByEgoLevel(int, int)](/api/Global/Units/UnitModel#getdmgmultiplierbyegolevel-int-int), [GetBufDamageMultiplier(UnitModel, DamageInfo)](/api/Global/Units/UnitModel#getbufdamagemultiplier-unitmodel-damageinfo), [GetUnitBufByName(string)](/api/Global/Units/UnitModel#getunitbufbyname-string), [GetUnitBufList()](/api/Global/Units/UnitModel#getunitbuflist), [Equipment](/api/Global/Units/UnitModel#equipment), [maxHp](/api/Global/Units/UnitModel#maxhp), [maxMental](/api/Global/Units/UnitModel#maxmental), [movement](/api/Global/Units/UnitModel#movement), [regeneration](/api/Global/Units/UnitModel#regeneration), [regenerationDelay](/api/Global/Units/UnitModel#regenerationdelay), [attackSpeed](/api/Global/Units/UnitModel#attackspeed), [damage](/api/Global/Units/UnitModel#damage), [physicalDefense](/api/Global/Units/UnitModel#physicaldefense), [mentalDefense](/api/Global/Units/UnitModel#mentaldefense), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)








