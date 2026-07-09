---
uid: Global.ProjectileModel
canonical_path: /api/Global/Model/ProjectileModel
---
# Class ProjectileModel
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ProjectileModel : UnitModel
```
> This section may have incomplete or incorrect information.
{.is-warning}


Parent class for certain projectiles:
- [An Arbiter](/api/Global/Core-Suppressions/Binah-Suppression/BinahWave) in Binah's core suppression
- [Knight of Despair](/api/Global/Abnormalities/The-Knight-of-Despair/KnightOfDespair)'s swords
- [Laetitia](/api/Global/Abnormalities/Laetitia/LittleWitch)'s heart gift




## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitModel](/api/Global/Units/UnitModel) → ProjectileModel

## Constructors
### ProjectileModel(UnitModel)
```csharp
public ProjectileModel(UnitModel owner)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `owner` | `Global.UnitModel` |  |

### ProjectileModel(UnitModel, float)
```csharp
public ProjectileModel(UnitModel owner, float speed)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `owner` | `Global.UnitModel` |  |
| `speed` | `System.Single` |  |

## Fields
### damaged
```csharp
private List<UnitModel> damaged
```


#### Field Value
**Type:** System.Collections.Generic.List{UnitModel}

### destMovable
```csharp
private MovableObjectNode destMovable
```


#### Field Value
**Type:** Global.MovableObjectNode

### destNode
```csharp
private MapNode destNode
```


#### Field Value
**Type:** Global.MapNode

### dups
```csharp
private List<ProjectileModel.DuplicateDamage> dups
```

#### Field Value
**Type:** System.Collections.Generic.List{ProjectileModel.DuplicateDamage}

### fixedUpdateCmd
```csharp
private ProjectileModel.FixedUpdateCommand fixedUpdateCmd
```

#### Field Value
**Type:** Global.ProjectileModel.FixedUpdateCommand

### isMoveEnd
```csharp
private bool isMoveEnd
```


#### Field Value
**Type:** System.Boolean

### moveCompeleteCmd
```csharp
private ProjectileModel.MoveCompeleteCommand moveCompeleteCmd
```

#### Field Value
**Type:** Global.ProjectileModel.MoveCompeleteCommand

### owner
```csharp
public UnitModel owner
```


#### Field Value
**Type:** Global.UnitModel

### speed
```csharp
private float speed
```


#### Field Value
**Type:** System.Single

### unit
```csharp
public ProjectileUnit unit
```


#### Field Value
**Type:** Global.ProjectileUnit

## Properties
### duplicateFreq
```csharp
public float duplicateFreq { get; set; }
```

#### Property Value
**Type:** System.Single

### isDuplicatable
```csharp
public bool isDuplicatable { get; set; }
```

#### Property Value
**Type:** System.Boolean

### range
```csharp
public float range { get; set; }
```

#### Property Value
**Type:** System.Single

## Methods
### CheckRange(UnitModel)
```csharp
public bool CheckRange(UnitModel target)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

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


### GiveDamage(UnitModel, float)
```csharp
public void GiveDamage(UnitModel actor, float damage)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |
| `damage` | `System.Single` |  |

### MoveToMovable(MovableObjectNode)
```csharp
public void MoveToMovable(MovableObjectNode movable)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `movable` | `Global.MovableObjectNode` |  |

### MoveToNode(MapNode)
```csharp
public void MoveToNode(MapNode mapNode)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `mapNode` | `Global.MapNode` |  |

### OnFixedUpdate()
```csharp
public void OnFixedUpdate()
```


### OnMoveCompelete()
```csharp
public void OnMoveCompelete()
```


### SetFixedUpdateCommand(FixedUpdateCommand)
```csharp
public void SetFixedUpdateCommand(ProjectileModel.FixedUpdateCommand cmd)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `cmd` | `Global.ProjectileModel.FixedUpdateCommand` |  |

### SetMoveCompeleteCommand(MoveCompeleteCommand)
```csharp
public void SetMoveCompeleteCommand(ProjectileModel.MoveCompeleteCommand cmd)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `cmd` | `Global.ProjectileModel.MoveCompeleteCommand` |  |

### SetPosToOwner(UnitModel)
```csharp
private void SetPosToOwner(UnitModel owner)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `owner` | `Global.UnitModel` |  |

### SetUnit(ProjectileUnit)
```csharp
public void SetUnit(ProjectileUnit unit)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.ProjectileUnit` |  |

## Inherited Members
[stunCriteria](/api/Global/Units/UnitModel#stuncriteria), [defaultStunEffectSrc](/api/Global/Units/UnitModel#defaultstuneffectsrc), [instanceId](/api/Global/Units/UnitModel#instanceid), [movableNode](/api/Global/Units/UnitModel#movablenode), [shield](/api/Global/Units/UnitModel#shield), [_equipment](/api/Global/Units/UnitModel#equipment), [tempAnim](/api/Global/Units/UnitModel#tempanim), [factionTypeInfo](/api/Global/Units/UnitModel#factiontypeinfo), [stunTimer](/api/Global/Units/UnitModel#stuntimer), [hp](/api/Global/Units/UnitModel#hp), [mental](/api/Global/Units/UnitModel#mental), [baseMaxHp](/api/Global/Units/UnitModel#basemaxhp), [baseMaxMental](/api/Global/Units/UnitModel#basemaxmental), [baseMovement](/api/Global/Units/UnitModel#basemovement), [baseRegeneration](/api/Global/Units/UnitModel#baseregeneration), [baseRegenerationDelay](/api/Global/Units/UnitModel#baseregenerationdelay), [additionalDef](/api/Global/Units/UnitModel#additionaldef), [superArmorMax](/api/Global/Units/UnitModel#superarmormax), [superArmor](/api/Global/Units/UnitModel#superarmor), [superArmorDefense](/api/Global/Units/UnitModel#superarmordefense), [remainMoveDelay](/api/Global/Units/UnitModel#remainmovedelay), [remainAttackDelay](/api/Global/Units/UnitModel#remainattackdelay), [isStun](/api/Global/Units/UnitModel#isstun), [damageTransform](/api/Global/Units/UnitModel#damagetransform), [basePhysicalDefense](/api/Global/Units/UnitModel#basephysicaldefense), [baseMentalDefense](/api/Global/Units/UnitModel#basementaldefense), [encounteredWorker](/api/Global/Units/UnitModel#encounteredworker), [_bufList](/api/Global/Units/UnitModel#buflist), [_statBufList](/api/Global/Units/UnitModel#statbuflist), [_barrierBufList](/api/Global/Units/UnitModel#barrierbuflist), [CanOpenDoor()](/api/Global/Units/UnitModel#canopendoor), [GetUnitName()](/api/Global/Units/UnitModel#getunitname), [InteractWithDoor(DoorObjectModel)](/api/Global/Units/UnitModel#interactwithdoor-doorobjectmodel), [OnStopMovableByShield(AgentModel)](/api/Global/Units/UnitModel#onstopmovablebyshield-agentmodel), [GetMovableNode()](/api/Global/Units/UnitModel#getmovablenode), [GetCurrentViewPosition()](/api/Global/Units/UnitModel#getcurrentviewposition), [SetWeapon(WeaponModel)](/api/Global/Units/UnitModel#setweapon-weaponmodel), [ReleaseWeaponV2()](/api/Global/Units/UnitModel#releaseweaponv2), [SetArmor(ArmorModel)](/api/Global/Units/UnitModel#setarmor-armormodel), [ReleaseArmor()](/api/Global/Units/UnitModel#releasearmor), [AttachEGOgift(EGOgiftModel)](/api/Global/Units/UnitModel#attachegogift-egogiftmodel), [ReleaseEGOgift(EGOgiftModel)](/api/Global/Units/UnitModel#releaseegogift-egogiftmodel), [ReleaseEGOGift(int)](/api/Global/Units/UnitModel#releaseegogift-int), [SetGiftDisplayState(EGOgiftModel, bool)](/api/Global/Units/UnitModel#setgiftdisplaystate-egogiftmodel-bool), [GetGiftDisplayState(EGOgiftModel)](/api/Global/Units/UnitModel#getgiftdisplaystate-egogiftmodel), [SetGiftLockState(EGOgiftModel, bool)](/api/Global/Units/UnitModel#setgiftlockstate-egogiftmodel-bool), [SetKitCreature(CreatureModel)](/api/Global/Units/UnitModel#setkitcreature-creaturemodel), [ReleaseKitCreature(bool)](/api/Global/Units/UnitModel#releasekitcreature-bool), [OnSetWeapon()](/api/Global/Units/UnitModel#onsetweapon), [OnReleaseWeapon()](/api/Global/Units/UnitModel#onreleaseweapon), [OnSetArmor()](/api/Global/Units/UnitModel#onsetarmor), [OnReleaseArmor()](/api/Global/Units/UnitModel#onreleasearmor), [OnChangeGift()](/api/Global/Units/UnitModel#onchangegift), [OnSetKitCreature()](/api/Global/Units/UnitModel#onsetkitcreature), [OnReleaseKitCreature()](/api/Global/Units/UnitModel#onreleasekitcreature), [GetWeaponSpriteSrc()](/api/Global/Units/UnitModel#getweaponspritesrc), [GetWeaponSprite()](/api/Global/Units/UnitModel#getweaponsprite), [PrepareWeapon()](/api/Global/Units/UnitModel#prepareweapon), [CancelWeapon()](/api/Global/Units/UnitModel#cancelweapon), [Attack(UnitModel)](/api/Global/Units/UnitModel#attack-unitmodel), [IsAttackState()](/api/Global/Units/UnitModel#isattackstate), [InWeaponRange(UnitModel)](/api/Global/Units/UnitModel#inweaponrange-unitmodel), [StopAttack()](/api/Global/Units/UnitModel#stopattack), [OnGiveDamageByWeapon()](/api/Global/Units/UnitModel#ongivedamagebyweapon), [GetDamageFactorByEquipment()](/api/Global/Units/UnitModel#getdamagefactorbyequipment), [GetDamageFactorBySefiraAbility()](/api/Global/Units/UnitModel#getdamagefactorbysefiraability), [OnEndAttackCycle()](/api/Global/Units/UnitModel#onendattackcycle), [PlayAttackAnimation(string)](/api/Global/Units/UnitModel#playattackanimation-string), [EndAttackAnimation()](/api/Global/Units/UnitModel#endattackanimation), [GetEGObonus()](/api/Global/Units/UnitModel#getegobonus), [HasEquipment(int)](/api/Global/Units/UnitModel#hasequipment-int), [AddSuperArmorMax(float)](/api/Global/Units/UnitModel#addsuperarmormax-float), [SubSuperArmorMax(float)](/api/Global/Units/UnitModel#subsuperarmormax-float), [TakeDamage(DamageInfo)](/api/Global/Units/UnitModel#takedamage-damageinfo), [TakeDamage(UnitModel, DamageInfo)](/api/Global/Units/UnitModel#takedamage-unitmodel-damageinfo), [TakeDamageWithoutEffect(UnitModel, DamageInfo)](/api/Global/Units/UnitModel#takedamagewithouteffect-unitmodel-damageinfo), [MakeDamageEffect(RwbpType, float, Type)](/api/Global/Units/UnitModel#makedamageeffect-rwbptype-float-type), [UnderAttack(UnitModel)](/api/Global/Units/UnitModel#underattack-unitmodel), [ClearWorkerEncounting()](/api/Global/Units/UnitModel#clearworkerencounting), [CheckNearWorkerEncounting()](/api/Global/Units/UnitModel#checknearworkerencounting), [IsStunned()](/api/Global/Units/UnitModel#isstunned), [OnSuperArmorBreak()](/api/Global/Units/UnitModel#onsuperarmorbreak), [IsAttackTargetable()](/api/Global/Units/UnitModel#isattacktargetable), [IsHostile(UnitModel)](/api/Global/Units/UnitModel#ishostile-unitmodel), [SetMoveDelay(float)](/api/Global/Units/UnitModel#setmovedelay-float), [SetAttackDelay()](/api/Global/Units/UnitModel#setattackdelay), [SetAttackDelay(float)](/api/Global/Units/UnitModel#setattackdelay-float), [UpdateBufState()](/api/Global/Units/UnitModel#updatebufstate), [GetRiskLevel()](/api/Global/Units/UnitModel#getrisklevel), [GetAttackLevel()](/api/Global/Units/UnitModel#getattacklevel), [GetDefenseLevel()](/api/Global/Units/UnitModel#getdefenselevel), [AddUnitBuf(UnitBuf)](/api/Global/Units/UnitModel#addunitbuf-unitbuf), [HasUnitBuf(UnitBufType)](/api/Global/Units/UnitModel#hasunitbuf-unitbuftype), [GetUnitBufByType(UnitBufType)](/api/Global/Units/UnitModel#getunitbufbytype-unitbuftype), [RemoveUnitBuf(UnitBuf)](/api/Global/Units/UnitModel#removeunitbuf-unitbuf), [GetMaxHpBuf()](/api/Global/Units/UnitModel#getmaxhpbuf), [GetMaxMentalBuf()](/api/Global/Units/UnitModel#getmaxmentalbuf), [GetCubeSpeedBuf()](/api/Global/Units/UnitModel#getcubespeedbuf), [GetWorkProbBuf()](/api/Global/Units/UnitModel#getworkprobbuf), [GetAttackSpeedBuf()](/api/Global/Units/UnitModel#getattackspeedbuf), [GetMovementBuf()](/api/Global/Units/UnitModel#getmovementbuf), [GetPrimaryStatBuf()](/api/Global/Units/UnitModel#getprimarystatbuf), [GetMovementScaleByBuf()](/api/Global/Units/UnitModel#getmovementscalebybuf), [SetFaction(FactionTypeInfo)](/api/Global/Units/UnitModel#setfaction-factiontypeinfo), [SetFaction(string)](/api/Global/Units/UnitModel#setfaction-string), [GetFaction()](/api/Global/Units/UnitModel#getfaction), [SetFactionForcely(string)](/api/Global/Units/UnitModel#setfactionforcely-string), [OnStun(float)](/api/Global/Units/UnitModel#onstun-float), [OnStunEnd()](/api/Global/Units/UnitModel#onstunend), [GetDmgMultiplierByEgoLevel(int, int)](/api/Global/Units/UnitModel#getdmgmultiplierbyegolevel-int-int), [GetBufDamageMultiplier(UnitModel, DamageInfo)](/api/Global/Units/UnitModel#getbufdamagemultiplier-unitmodel-damageinfo), [GetUnitBufByName(string)](/api/Global/Units/UnitModel#getunitbufbyname-string), [GetUnitBufList()](/api/Global/Units/UnitModel#getunitbuflist), [Equipment](/api/Global/Units/UnitModel#equipment), [radius](/api/Global/Units/UnitModel#radius), [maxHp](/api/Global/Units/UnitModel#maxhp), [maxMental](/api/Global/Units/UnitModel#maxmental), [movement](/api/Global/Units/UnitModel#movement), [regeneration](/api/Global/Units/UnitModel#regeneration), [regenerationDelay](/api/Global/Units/UnitModel#regenerationdelay), [defense](/api/Global/Units/UnitModel#defense), [attackSpeed](/api/Global/Units/UnitModel#attackspeed), [damage](/api/Global/Units/UnitModel#damage), [physicalDefense](/api/Global/Units/UnitModel#physicaldefense), [mentalDefense](/api/Global/Units/UnitModel#mentaldefense), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)








