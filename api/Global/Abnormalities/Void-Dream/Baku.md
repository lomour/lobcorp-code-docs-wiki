---
uid: Global.Baku
canonical_path: /api/Global/Misc/Baku
---
# Class Baku
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Baku : CreatureBase
```
> This section may have incomplete or incorrect information.
{.is-warning}


Void Dream.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase](/api/Global/Abnormalities/CreatureBase/CreatureBase) → Baku

## Constructors
### Baku()
```csharp
public Baku()
```

## Fields
### _agentSleepConditionInWork
```csharp
private const int _agentSleepConditionInWork = 2
```


#### Field Value
**Type:** System.Int32

### _animScript
```csharp
private BakuAnim _animScript
```


#### Field Value
**Type:** Global.BakuAnim

### _chickenMovement
```csharp
private const float _chickenMovement = 3
```


#### Field Value
**Type:** System.Single

### _cryCoolTimeMax
```csharp
private const float _cryCoolTimeMax = 8
```


#### Field Value
**Type:** System.Single

### _cryCoolTimeMin
```csharp
private const float _cryCoolTimeMin = 6
```


#### Field Value
**Type:** System.Single

### _cryDmgMax
```csharp
private const int _cryDmgMax = 5
```


#### Field Value
**Type:** System.Int32

### _cryDmgMin
```csharp
private const int _cryDmgMin = 3
```


#### Field Value
**Type:** System.Int32

### _cryDmgType
```csharp
private const RwbpType _cryDmgType = W
```


#### Field Value
**Type:** Global.RwbpType

### _cryInitCoolTimeMax
```csharp
private const float _cryInitCoolTimeMax = 7
```


#### Field Value
**Type:** System.Single

### _cryInitCoolTimeMin
```csharp
private const float _cryInitCoolTimeMin = 4
```


#### Field Value
**Type:** System.Single

### _cryTimeMax
```csharp
private const float _cryTimeMax = 4
```


#### Field Value
**Type:** System.Single

### _cryTimeMin
```csharp
private const float _cryTimeMin = 4
```


#### Field Value
**Type:** System.Single

### _effect_chicken_cry
```csharp
private const string _effect_chicken_cry = "BakuChickenCryEffect"
```


#### Field Value
**Type:** System.String

### _effect_sheep_skill
```csharp
private const string _effect_sheep_skill = "BakuSheepSkillObject"
```


#### Field Value
**Type:** System.String

### _effect_sheep_skill_bg
```csharp
private const string _effect_sheep_skill_bg = "BakuSheepSkillBg"
```


#### Field Value
**Type:** System.String

### _effectSrc
```csharp
private const string _effectSrc = "Effect/Creature/Baku/"
```


#### Field Value
**Type:** System.String

### _motionDelayMax
```csharp
private const float _motionDelayMax = 1
```


#### Field Value
**Type:** System.Single

### _motionDelayMin
```csharp
private const float _motionDelayMin = 0.5
```


#### Field Value
**Type:** System.Single

### _qliphothMax
```csharp
private const int _qliphothMax = 2
```


#### Field Value
**Type:** System.Int32

### _sheepMovement
```csharp
private const float _sheepMovement = 1
```


#### Field Value
**Type:** System.Single

### _sheepReturnTimeMax
```csharp
private const float _sheepReturnTimeMax = 70
```


#### Field Value
**Type:** System.Single

### _sheepReturnTimeMin
```csharp
private const float _sheepReturnTimeMin = 50
```


#### Field Value
**Type:** System.Single

### _sheepSkillAmmo
```csharp
private const int _sheepSkillAmmo = 5
```


#### Field Value
**Type:** System.Int32

### _sleepCoolTimeMax
```csharp
private const float _sleepCoolTimeMax = 15
```


#### Field Value
**Type:** System.Single

### _sleepCoolTimeMin
```csharp
private const float _sleepCoolTimeMin = 10
```


#### Field Value
**Type:** System.Single

### _sleepInitCoolTimeMax
```csharp
private const float _sleepInitCoolTimeMax = 15
```


#### Field Value
**Type:** System.Single

### _sleepInitCoolTimeMin
```csharp
private const float _sleepInitCoolTimeMin = 10
```


#### Field Value
**Type:** System.Single

### _soundTimeMax
```csharp
private const float _soundTimeMax = 10
```


#### Field Value
**Type:** System.Single

### _soundTimeMin
```csharp
private const float _soundTimeMin = 6
```


#### Field Value
**Type:** System.Single

### _state
```csharp
private Baku.BakuState _state
```

#### Field Value
**Type:** Global.Baku.BakuState

### annoyed
```csharp
private Queue<WorkerModel> annoyed
```


#### Field Value
**Type:** System.Collections.Generic.Queue{WorkerModel}

### cryCoolTimer
```csharp
private Timer cryCoolTimer
```


#### Field Value
**Type:** Global.Timer

### cryTimer
```csharp
private Timer cryTimer
```


#### Field Value
**Type:** Global.Timer

### motionDelayTimer
```csharp
private Timer motionDelayTimer
```


#### Field Value
**Type:** Global.Timer

### sheepReturnTimer
```csharp
private Timer sheepReturnTimer
```


#### Field Value
**Type:** Global.Timer

### sleepCoolTimer
```csharp
private Timer sleepCoolTimer
```


#### Field Value
**Type:** Global.Timer

### soundTimer
```csharp
private Timer soundTimer
```


#### Field Value
**Type:** Global.Timer

### wakeup
```csharp
private Queue<WorkerModel> wakeup
```


#### Field Value
**Type:** System.Collections.Generic.Queue{WorkerModel}

## Properties
### animScript
```csharp
public BakuAnim animScript { get; }
```

#### Property Value
**Type:** Global.BakuAnim

### cryCoolTime
```csharp
private static float cryCoolTime { get; }
```

#### Property Value
**Type:** System.Single

### cryDmg
```csharp
private static DamageInfo cryDmg { get; }
```

#### Property Value
**Type:** Global.DamageInfo

### cryInitCoolTime
```csharp
private static float cryInitCoolTime { get; }
```

#### Property Value
**Type:** System.Single

### cryTime
```csharp
private static float cryTime { get; }
```

#### Property Value
**Type:** System.Single

### motionDelay
```csharp
private static float motionDelay { get; }
```

#### Property Value
**Type:** System.Single

### sheepReturnTime
```csharp
private static float sheepReturnTime { get; }
```

#### Property Value
**Type:** System.Single

### sleepCoolTime
```csharp
private static float sleepCoolTime { get; }
```

#### Property Value
**Type:** System.Single

### sleepInitCoolTime
```csharp
private static float sleepInitCoolTime { get; }
```

#### Property Value
**Type:** System.Single

### soundTime
```csharp
private static float soundTime { get; }
```

#### Property Value
**Type:** System.Single

## Methods
### ActivateQliphothCounter()
```csharp
public override void ActivateQliphothCounter()
```


### ActivateSkill_Chicken()
```csharp
private void ActivateSkill_Chicken()
```


### ActivateSkill_Sheep()
```csharp
private void ActivateSkill_Sheep()
```


### AnnoyedWorkerWakeUp(WorkerModel)
```csharp
private void AnnoyedWorkerWakeUp(WorkerModel worker)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

### AnnoyWorker(WorkerModel)
```csharp
public void AnnoyWorker(WorkerModel worker)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

### BecomeChicken()
```csharp
public void BecomeChicken()
```


### BecomeSheep()
```csharp
public void BecomeSheep()
```


### CheckReturn()
```csharp
private void CheckReturn()
```


### CheckSleep(WorkerModel)
```csharp
public bool CheckSleep(WorkerModel worker)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

#### Returns
**Type:** System.Boolean

### ChickenDefaultSound()
```csharp
private void ChickenDefaultSound()
```


### EndCrying()
```csharp
private void EndCrying()
```


### Escape()
```csharp
public override void Escape()
```


### FixedUpdate_Chicken()
```csharp
private void FixedUpdate_Chicken()
```


### FixedUpdate_Sheep()
```csharp
private void FixedUpdate_Sheep()
```


### IsAutoSuppressable()
```csharp
public override bool IsAutoSuppressable()
```


#### Returns
**Type:** System.Boolean

### IsCrying()
```csharp
private bool IsCrying()
```


#### Returns
**Type:** System.Boolean

### IsInSkill()
```csharp
private bool IsInSkill()
```


#### Returns
**Type:** System.Boolean

### IsMovable()
```csharp
private bool IsMovable()
```


#### Returns
**Type:** System.Boolean

### MakeEffect(string, GameObject, bool)
```csharp
private GameObject MakeEffect(string src, GameObject pivot, bool isGlobal = true)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |
| `pivot` | `UnityEngine.GameObject` |  |
| `isGlobal` | `System.Boolean` |  |

#### Returns
**Type:** UnityEngine.GameObject

### MakeMovement()
```csharp
private void MakeMovement()
```


### Movement_Chicken()
```csharp
private void Movement_Chicken()
```


### Movement_Sheep()
```csharp
private void Movement_Sheep()
```


### OnAfterSuppressed()
```csharp
public override bool OnAfterSuppressed()
```


#### Returns
**Type:** System.Boolean

### OnCryDamage()
```csharp
public void OnCryDamage()
```


### OnReleaseWork(UseSkill)
```csharp
public override void OnReleaseWork(UseSkill skill)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

### OnReturn()
```csharp
public override void OnReturn()
```


### OnSkillEnd()
```csharp
public void OnSkillEnd()
```


### OnStageEnd()
```csharp
public override void OnStageEnd()
```


### OnStageRelease()
```csharp
public override void OnStageRelease()
```


### OnStageStart()
```csharp
public override void OnStageStart()
```


### OnStartCrying()
```csharp
public void OnStartCrying()
```


### OnTakeDamage(UnitModel, DamageInfo, float)
```csharp
public override void OnTakeDamage(UnitModel actor, DamageInfo dmg, float value)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `actor` | `Global.UnitModel` |  |
| `dmg` | `Global.DamageInfo` |  |
| `value` | `System.Single` |  |

### OnViewInit(CreatureUnit)
```csharp
public override void OnViewInit(CreatureUnit unit)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.CreatureUnit` |  |

### OnWorkerAnimCalled(int)
```csharp
public void OnWorkerAnimCalled(int i)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### ParamInit()
```csharp
public override void ParamInit()
```


### SkillShoot_Sheep()
```csharp
private void SkillShoot_Sheep()
```


### SleepWorker(WorkerModel)
```csharp
public void SleepWorker(WorkerModel worker)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

### StopMovement()
```csharp
private void StopMovement()
```


### UniqueEscape()
```csharp
public override void UniqueEscape()
```


### WakedWorkerWakeUp(WorkerModel)
```csharp
private void WakedWorkerWakeUp(WorkerModel worker)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

### WakeWorker(WorkerModel)
```csharp
public void WakeWorker(WorkerModel worker)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

## Inherited Members
[isolateSpriteSrc](/api/Global/Abnormalities/CreatureBase/CreatureBase#isolatespritesrc), [model](/api/Global/Abnormalities/CreatureBase/CreatureBase#model), [skill](/api/Global/Abnormalities/CreatureBase/CreatureBase#skill), [kitEvent](/api/Global/Abnormalities/CreatureBase/CreatureBase#kitevent), [hasUniqueEscapeLogic](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueescapelogic), [isWorkAllocated](/api/Global/Abnormalities/CreatureBase/CreatureBase#isworkallocated), [_allocatedAgent](/api/Global/Abnormalities/CreatureBase/CreatureBase#allocatedagent), [damage](/api/Global/Abnormalities/CreatureBase/CreatureBase#damage), [OnReleaseSpecialTip](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleasespecialtip), [specialSkillTipParamList](/api/Global/Abnormalities/CreatureBase/CreatureBase#specialskilltipparamlist), [_check](/api/Global/Abnormalities/CreatureBase/CreatureBase#check), [SetModel(CreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#setmodel-creaturemodel), [OnInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#oninit), [OnViewInitPrev(CreatureUnit)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onviewinitprev-creatureunit), [OnFixedUpdate(CreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfixedupdate-creaturemodel), [OnFixedUpdateInSkill(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfixedupdateinskill-useskill), [OnSkillFailWorkTick(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillfailworktick-useskill), [OnSkillSuccessWorkTick(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillsuccessworktick-useskill), [OnSkillTickUpdate(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskilltickupdate-useskill), [OnSkillGoalComplete(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillgoalcomplete-useskill), [PermitCancelCurrentWork()](/api/Global/Abnormalities/CreatureBase/CreatureBase#permitcancelcurrentwork), [GetKitCreatureProcessTime()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getkitcreatureprocesstime), [OnBonusWorkProb()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onbonusworkprob), [GetDamageMultiplierInWork(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdamagemultiplierinwork-useskill), [TranformWorkProb(float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#tranformworkprob-float), [OnEnterRoom(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onenterroom-useskill), [OnFinishWork(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfinishwork-useskill), [OnWorkCoolTimeEnd(CreatureFeelingState)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkcooltimeend-creaturefeelingstate), [GetSpecialSkill()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getspecialskill), [GetDebugText()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdebugtext), [OnTimerEnd()](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontimerend), [MakeEffect(IsolateRoom, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffect-isolateroom-int), [MakeEffectAlter(IsolateRoom, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectalter-isolateroom-int), [Prob(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#prob-int), [isAttackInWorkProcess()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isattackinworkprocess), [OnAttackInWorkProcess(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onattackinworkprocess-useskill), [AttackProcess(UnitModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#attackprocess-unitmodel), [AutoFeelingDown()](/api/Global/Abnormalities/CreatureBase/CreatureBase#autofeelingdown), [AgentAnimCalled(int, WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#agentanimcalled-int-workermodel), [MakingEffect(string, float, string, Transform, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float-string-transform-int), [MakingEffect(string, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float), [MakeEffectAttachedToHead(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectattachedtohead-string), [MakingEffect(string, float, string, Vector3, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float-string-vector3-int), [OnAgentWorkEndAnimationPlayed(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentworkendanimationplayed-useskill), [OnAgentAllocateWork(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentallocatework-agentmodel), [OnSuppressed()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onsuppressed), [OnAllocatedWork(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onallocatedwork-agentmodel), [OnReleaseWorkAllocated()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleaseworkallocated), [ObserveLevelChangeForSpecialSkillTip()](/api/Global/Abnormalities/CreatureBase/CreatureBase#observelevelchangeforspecialskilltip), [OnObserveLevelChanged()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onobservelevelchanged), [HasUniqueProcessWorkNarration()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueprocessworknarration), [UniqueProcessWorkNarration(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniqueprocessworknarration-useskill), [RoomSpriteInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomspriteinit), [RoomEscapeSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomescapespriteon), [RoomEscapeSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomescapespriteoff), [RoomSkillSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomskillspriteon), [RoomSkillSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomskillspriteoff), [RoomStateSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomstatespriteon), [RoomStateSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomstatespriteoff), [OnForceSpecialSkillTipReveal(string, params object[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onforcespecialskilltipreveal-string-params-object), [OnWorkReleaseSpeicalSkillTipReveal(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkreleasespeicalskilltipreveal-string), [OnWorkReleaseTipUpdate(params object[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkreleasetipupdate-params-object), [OnAgentAnimatorReseted()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentanimatorreseted), [SpecialEnergyTick()](/api/Global/Abnormalities/CreatureBase/CreatureBase#specialenergytick), [OnFeverTimeOver()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfevertimeover), [OnOverlayIsolateWork()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onoverlayisolatework), [OnOverlayIsolateObserve()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onoverlayisolateobserve), [OnOpenObserveWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopenobservewindow), [OnOpenWorkWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopenworkwindow), [OnOpenCollectionWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopencollectionwindow), [DelayAttackMotion(float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#delayattackmotion-float), [IsAttackTargetable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isattacktargetable), [GetRealTargets()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getrealtargets), [HasScriptSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasscriptsavedata), [GetSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getsavedata), [LoadData(Dictionary<string, object>)](/api/Global/Abnormalities/CreatureBase/CreatureBase#loaddata-dictionary-string-object), [LoadScriptData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#loadscriptdata), [SaveScriptData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#savescriptdata), [ExistSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#existsavedata), [RemoveSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#removesavedata), [ReplaceCommand(CreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#replacecommand-creaturemodel), [OnGamemanagerInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#ongamemanagerinit), [MakeEffectGlobalPos(string, Vector3)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectglobalpos-string-vector3), [MakeEffectGlobalPosNonTrans(string, Vector3)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectglobalposnontrans-string-vector3), [CanObservedByAgent(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#canobservedbyagent-agentmodel), [MakeSound(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string), [MakeSound(string, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string-float), [MakeSound(string, AudioRolloffMode)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string-audiorolloffmode), [MakeSoundQueue(params string[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesoundqueue-params-string), [MakeSoundLoop(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesoundloop-string), [OnViewDestroy()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onviewdestroy), [IsWorkable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isworkable), [HasUniqueMaxObservationFinish()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquemaxobservationfinish), [UniqueMaxObservationFinish(Desc)](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquemaxobservationfinish-desc), [OnChildSuppressed(ChildCreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onchildsuppressed-childcreaturemodel), [MakeChildCreature(UnitModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makechildcreature-unitmodel), [OnKillWorker(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onkillworker-workermodel), [GenPursueCommandAlter(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#genpursuecommandalter-workermodel), [hasUniqueDeadScene()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquedeadscene), [SetHpSlider(Slider)](/api/Global/Abnormalities/CreatureBase/CreatureBase#sethpslider-slider), [SetCastingSlider(Slider)](/api/Global/Abnormalities/CreatureBase/CreatureBase#setcastingslider-slider), [HasUniqueAttackDealy()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueattackdealy), [CanTakeDamage(UnitModel, DamageInfo)](/api/Global/Abnormalities/CreatureBase/CreatureBase#cantakedamage-unitmodel-damageinfo), [OnTakePhysicalDamage(UnitModel, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontakephysicaldamage-unitmodel-float), [HasUniqueFaction()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquefaction), [OnWorkerPanic(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkerpanic-workermodel), [OnSelectMaxObservation(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onselectmaxobservation-int), [OnLoadCreatureName(ref string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onloadcreaturename-ref-string), [IsSuppressable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#issuppressable), [IsSuppressableByRoom()](/api/Global/Abnormalities/CreatureBase/CreatureBase#issuppressablebyroom), [OnWorkWindowSkillClicked(long)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkwindowskillclicked-long), [UseDefaultDamageIgnoreMessage(DamageTextEffect)](/api/Global/Abnormalities/CreatureBase/CreatureBase#usedefaultdamageignoremessage-damagetexteffect), [OnWorkAllocated(SkillTypeInfo, AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkallocated-skilltypeinfo-agentmodel), [GetPhysicalDamage(out float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getphysicaldamage-out-float), [GetMentalDamage(out float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getmentaldamage-out-float), [OnSuperArmorBreak()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onsuperarmorbreak), [UniqueStunEffect()](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquestuneffect), [HasEscapeUI()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasescapeui), [HasRoomCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasroomcounter), [RoomCounterInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomcounterinit), [ResetQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#resetqliphothcounter), [GetMaxWorkCountView()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getmaxworkcountview), [GetQliphothCounterMax()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getqliphothcountermax), [ReducedQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#reducedqliphothcounter), [AddedQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#addedqliphothcounter), [GetRadius()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getradius), [OnElevatorStuck()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onelevatorstuck), [OnWorkClosed(UseSkill, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkclosed-useskill-int), [IsActivatedWorkDesc()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isactivatedworkdesc), [IsSensoredInPassage()](/api/Global/Abnormalities/CreatureBase/CreatureBase#issensoredinpassage), [IsIndirectSuppressable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isindirectsuppressable), [GetRiskLevel()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getrisklevel), [GetName()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getname), [UniqueMoveControl()](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquemovecontrol), [HasUniqueName()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquename), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdamagefactor-unitmodel-damageinfo), [OnInitialBuild()](/api/Global/Abnormalities/CreatureBase/CreatureBase#oninitialbuild), [HasUniqueCollectionCost(string, out string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquecollectioncost-string-out-string), [OnOpenCommandWindow(Button[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopencommandwindow-button), [HasUniqueCommandAction(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquecommandaction-int), [HasUniqueWorkSelect(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueworkselect-int), [ForcelySuccess(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#forcelysuccess-useskill), [ForcelyFail(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#forcelyfail-useskill), [TryRabbitTeleport(MapNode)](/api/Global/Abnormalities/CreatureBase/CreatureBase#tryrabbitteleport-mapnode), [CanEnterRoom()](/api/Global/Abnormalities/CreatureBase/CreatureBase#canenterroom), [AllocatedAgent](/api/Global/Abnormalities/CreatureBase/CreatureBase#allocatedagent), [skillTriggerCheck](/api/Global/Abnormalities/CreatureBase/CreatureBase#skilltriggercheck), [Unit](/api/Global/Abnormalities/CreatureBase/CreatureBase#unit), [GetSaveSrc](/api/Global/Abnormalities/CreatureBase/CreatureBase#getsavesrc), [movable](/api/Global/Abnormalities/CreatureBase/CreatureBase#movable), [currentPassage](/api/Global/Abnormalities/CreatureBase/CreatureBase#currentpassage), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)







