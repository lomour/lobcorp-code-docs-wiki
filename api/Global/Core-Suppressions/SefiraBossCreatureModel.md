---
uid: Global.SefiraBossCreatureModel
canonical_path: /api/Global/Creature/SefiraBossCreatureModel
---
# Class SefiraBossCreatureModel
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SefiraBossCreatureModel : CreatureModel, IObserver, ISerializablePlayData, IMouseCommandTargetModel
```
> This section may have incomplete or incorrect information.
{.is-warning}


Represents a sephirah's physical model during their [core suppression](/api/Global/Core-Suppressions/SefiraBossBase). ^\[verify\]^




## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [UnitModel](/api/Global/Abnormalities/CreatureModel) → SefiraBossCreatureModel

## Implements
[IObserver](/api/Global/Mouse-Usage/Mouse-Listeners/IMouseCommandTargetModel)

## Constructors
### SefiraBossCreatureModel(long)
```csharp
public SefiraBossCreatureModel(long instanceId)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `instanceId` | `System.Int64` |  |

## Fields
### _sefiraBoss
```csharp
private SefiraBossBase _sefiraBoss
```


#### Field Value
**Type:** Global.SefiraBossBase

### speed
```csharp
public float speed
```


#### Field Value
**Type:** System.Single

## Properties
### SefiraBoss
```csharp
public SefiraBossBase SefiraBoss { get; private set; }
```

#### Property Value
**Type:** Global.SefiraBossBase

## Methods
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

### OnDestroy()
```csharp
public void OnDestroy()
```


### OnFixedUpdate()
```csharp
public override void OnFixedUpdate()
```


### SetSefiraBoss(SefiraBossBase)
```csharp
public void SetSefiraBoss(SefiraBossBase sefiraBoss)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `sefiraBoss` | `Global.SefiraBossBase` |  |

## Inherited Members
[regionName](/api/Global/Units/UnitModel#stuncriteria), [defaultStunEffectSrc](/api/Global/Units/UnitModel#defaultstuneffectsrc), [instanceId](/api/Global/Units/UnitModel#instanceid), [movableNode](/api/Global/Units/UnitModel#movablenode), [shield](/api/Global/Units/UnitModel#shield), [_equipment](/api/Global/Units/UnitModel#equipment), [tempAnim](/api/Global/Units/UnitModel#tempanim), [factionTypeInfo](/api/Global/Units/UnitModel#factiontypeinfo), [stunTimer](/api/Global/Units/UnitModel#stuntimer), [hp](/api/Global/Units/UnitModel#hp), [mental](/api/Global/Units/UnitModel#mental), [baseMaxHp](/api/Global/Units/UnitModel#basemaxhp), [baseMaxMental](/api/Global/Units/UnitModel#basemaxmental), [baseMovement](/api/Global/Units/UnitModel#basemovement), [baseRegeneration](/api/Global/Units/UnitModel#baseregeneration), [baseRegenerationDelay](/api/Global/Units/UnitModel#baseregenerationdelay), [additionalDef](/api/Global/Units/UnitModel#additionaldef), [superArmorMax](/api/Global/Units/UnitModel#superarmormax), [superArmor](/api/Global/Units/UnitModel#superarmor), [superArmorDefense](/api/Global/Units/UnitModel#superarmordefense), [remainMoveDelay](/api/Global/Units/UnitModel#remainmovedelay), [remainAttackDelay](/api/Global/Units/UnitModel#remainattackdelay), [isStun](/api/Global/Units/UnitModel#isstun), [damageTransform](/api/Global/Units/UnitModel#damagetransform), [basePhysicalDefense](/api/Global/Units/UnitModel#basephysicaldefense), [baseMentalDefense](/api/Global/Units/UnitModel#basementaldefense), [encounteredWorker](/api/Global/Units/UnitModel#encounteredworker), [_bufList](/api/Global/Units/UnitModel#buflist), [_statBufList](/api/Global/Units/UnitModel#statbuflist), [_barrierBufList](/api/Global/Units/UnitModel#barrierbuflist), [CanOpenDoor()](/api/Global/Units/UnitModel#canopendoor), [GetMovableNode()](/api/Global/Units/UnitModel#getmovablenode), [GetCurrentViewPosition()](/api/Global/Units/UnitModel#getcurrentviewposition), [SetWeapon(WeaponModel)](/api/Global/Units/UnitModel#setweapon-weaponmodel), [ReleaseWeaponV2()](/api/Global/Units/UnitModel#releaseweaponv2), [SetArmor(ArmorModel)](/api/Global/Units/UnitModel#setarmor-armormodel), [ReleaseArmor()](/api/Global/Units/UnitModel#releasearmor), [AttachEGOgift(EGOgiftModel)](/api/Global/Units/UnitModel#attachegogift-egogiftmodel), [ReleaseEGOgift(EGOgiftModel)](/api/Global/Units/UnitModel#releaseegogift-egogiftmodel), [ReleaseEGOGift(int)](/api/Global/Units/UnitModel#releaseegogift-int), [SetGiftDisplayState(EGOgiftModel, bool)](/api/Global/Units/UnitModel#setgiftdisplaystate-egogiftmodel-bool), [GetGiftDisplayState(EGOgiftModel)](/api/Global/Units/UnitModel#getgiftdisplaystate-egogiftmodel), [SetGiftLockState(EGOgiftModel, bool)](/api/Global/Units/UnitModel#setgiftlockstate-egogiftmodel-bool), [SetKitCreature(CreatureModel)](/api/Global/Units/UnitModel#setkitcreature-creaturemodel), [ReleaseKitCreature(bool)](/api/Global/Units/UnitModel#releasekitcreature-bool), [OnSetWeapon()](/api/Global/Units/UnitModel#onsetweapon), [OnReleaseWeapon()](/api/Global/Units/UnitModel#onreleaseweapon), [OnSetArmor()](/api/Global/Units/UnitModel#onsetarmor), [OnReleaseArmor()](/api/Global/Units/UnitModel#onreleasearmor), [OnChangeGift()](/api/Global/Units/UnitModel#onchangegift), [OnSetKitCreature()](/api/Global/Units/UnitModel#onsetkitcreature), [OnReleaseKitCreature()](/api/Global/Units/UnitModel#onreleasekitcreature), [GetWeaponSpriteSrc()](/api/Global/Units/UnitModel#getweaponspritesrc), [GetWeaponSprite()](/api/Global/Units/UnitModel#getweaponsprite), [PrepareWeapon()](/api/Global/Units/UnitModel#prepareweapon), [CancelWeapon()](/api/Global/Units/UnitModel#cancelweapon), [Attack(UnitModel)](/api/Global/Units/UnitModel#attack-unitmodel), [IsAttackState()](/api/Global/Units/UnitModel#isattackstate), [InWeaponRange(UnitModel)](/api/Global/Units/UnitModel#inweaponrange-unitmodel), [StopAttack()](/api/Global/Units/UnitModel#stopattack), [OnGiveDamageByWeapon()](/api/Global/Units/UnitModel#ongivedamagebyweapon), [GetDamageFactorByEquipment()](/api/Global/Units/UnitModel#getdamagefactorbyequipment), [GetDamageFactorBySefiraAbility()](/api/Global/Units/UnitModel#getdamagefactorbysefiraability), [OnEndAttackCycle()](/api/Global/Units/UnitModel#onendattackcycle), [EndAttackAnimation()](/api/Global/Units/UnitModel#endattackanimation), [GetEGObonus()](/api/Global/Units/UnitModel#getegobonus), [HasEquipment(int)](/api/Global/Units/UnitModel#hasequipment-int), [AddSuperArmorMax(float)](/api/Global/Units/UnitModel#addsuperarmormax-float), [SubSuperArmorMax(float)](/api/Global/Units/UnitModel#subsuperarmormax-float), [TakeDamage(DamageInfo)](/api/Global/Units/UnitModel#takedamage-damageinfo), [TakeDamageWithoutEffect(UnitModel, DamageInfo)](/api/Global/Units/UnitModel#takedamagewithouteffect-unitmodel-damageinfo), [MakeDamageEffect(RwbpType, float, Type)](/api/Global/Units/UnitModel#makedamageeffect-rwbptype-float-type), [UnderAttack(UnitModel)](/api/Global/Units/UnitModel#underattack-unitmodel), [ClearWorkerEncounting()](/api/Global/Units/UnitModel#clearworkerencounting), [CheckNearWorkerEncounting()](/api/Global/Units/UnitModel#checknearworkerencounting), [IsStunned()](/api/Global/Units/UnitModel#isstunned), [SetMoveDelay(float)](/api/Global/Units/UnitModel#setmovedelay-float), [SetAttackDelay()](/api/Global/Units/UnitModel#setattackdelay), [SetAttackDelay(float)](/api/Global/Units/UnitModel#setattackdelay-float), [UpdateBufState()](/api/Global/Units/UnitModel#updatebufstate), [AddUnitBuf(UnitBuf)](/api/Global/Units/UnitModel#addunitbuf-unitbuf), [HasUnitBuf(UnitBufType)](/api/Global/Units/UnitModel#hasunitbuf-unitbuftype), [GetUnitBufByType(UnitBufType)](/api/Global/Units/UnitModel#getunitbufbytype-unitbuftype), [RemoveUnitBuf(UnitBuf)](/api/Global/Units/UnitModel#removeunitbuf-unitbuf), [GetMaxHpBuf()](/api/Global/Units/UnitModel#getmaxhpbuf), [GetMaxMentalBuf()](/api/Global/Units/UnitModel#getmaxmentalbuf), [GetCubeSpeedBuf()](/api/Global/Units/UnitModel#getcubespeedbuf), [GetWorkProbBuf()](/api/Global/Units/UnitModel#getworkprobbuf), [GetAttackSpeedBuf()](/api/Global/Units/UnitModel#getattackspeedbuf), [GetMovementBuf()](/api/Global/Units/UnitModel#getmovementbuf), [GetPrimaryStatBuf()](/api/Global/Units/UnitModel#getprimarystatbuf), [GetMovementScaleByBuf()](/api/Global/Units/UnitModel#getmovementscalebybuf), [GetFaction()](/api/Global/Units/UnitModel#getfaction), [SetFactionForcely(string)](/api/Global/Units/UnitModel#setfactionforcely-string), [OnStun(float)](/api/Global/Units/UnitModel#onstun-float), [OnStunEnd()](/api/Global/Units/UnitModel#onstunend), [GetDmgMultiplierByEgoLevel(int, int)](/api/Global/Units/UnitModel#getdmgmultiplierbyegolevel-int-int), [GetBufDamageMultiplier(UnitModel, DamageInfo)](/api/Global/Units/UnitModel#getbufdamagemultiplier-unitmodel-damageinfo), [GetUnitBufByName(string)](/api/Global/Units/UnitModel#getunitbufbyname-string), [GetUnitBufList()](/api/Global/Units/UnitModel#getunitbuflist), [Equipment](/api/Global/Units/UnitModel#equipment), [maxHp](/api/Global/Units/UnitModel#maxhp), [maxMental](/api/Global/Units/UnitModel#maxmental), [movement](/api/Global/Units/UnitModel#movement), [regeneration](/api/Global/Units/UnitModel#regeneration), [regenerationDelay](/api/Global/Units/UnitModel#regenerationdelay), [attackSpeed](/api/Global/Units/UnitModel#attackspeed), [damage](/api/Global/Units/UnitModel#damage), [physicalDefense](/api/Global/Units/UnitModel#physicaldefense), [mentalDefense](/api/Global/Units/UnitModel#mentaldefense), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)








