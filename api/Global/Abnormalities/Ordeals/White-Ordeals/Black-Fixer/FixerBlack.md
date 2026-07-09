---
uid: Global.FixerBlack
canonical_path: /api/Global/Misc/FixerBlack
---
# Class FixerBlack
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class FixerBlack : FixerCreature
```
> This section may have incomplete or incorrect information.
{.is-warning}


Black Fixer.




## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase](/api/Global/Abnormalities/Ordeals/White-Ordeals/FixerCreature) → FixerBlack

## Constructors
### FixerBlack()
```csharp
public FixerBlack()
```

## Fields
### _animScript
```csharp
private FixerBlackAnim _animScript
```


#### Field Value
**Type:** Global.FixerBlackAnim

### _atkDmgMax
```csharp
private const int _atkDmgMax = 16
```


#### Field Value
**Type:** System.Int32

### _atkDmgMin
```csharp
private const int _atkDmgMin = 8
```


#### Field Value
**Type:** System.Int32

### _atkDmgRange
```csharp
private const float _atkDmgRange = 3.5
```


#### Field Value
**Type:** System.Single

### _atkType
```csharp
private const RwbpType _atkType = B
```


#### Field Value
**Type:** Global.RwbpType

### _attackRange
```csharp
private const float _attackRange = 3
```


#### Field Value
**Type:** System.Single

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

### _recognizeRange
```csharp
private const float _recognizeRange = 15
```


#### Field Value
**Type:** System.Single

### _skillCoolTimeMax
```csharp
private const float _skillCoolTimeMax = 60
```


#### Field Value
**Type:** System.Single

### _skillCoolTimeMin
```csharp
private const float _skillCoolTimeMin = 50
```


#### Field Value
**Type:** System.Single

### _skillDmgMax
```csharp
private const int _skillDmgMax = 12
```


#### Field Value
**Type:** System.Int32

### _skillDmgMin
```csharp
private const int _skillDmgMin = 10
```


#### Field Value
**Type:** System.Int32

### _skillInitCoolTimeMax
```csharp
private const float _skillInitCoolTimeMax = 31
```


#### Field Value
**Type:** System.Single

### _skillInitCoolTimeMin
```csharp
private const float _skillInitCoolTimeMin = 29
```


#### Field Value
**Type:** System.Single

### _skillType
```csharp
private const RwbpType _skillType = B
```


#### Field Value
**Type:** Global.RwbpType

### _specialAtkProb
```csharp
private const int _specialAtkProb = 25
```


#### Field Value
**Type:** System.Int32

### _specialDmgMax_1st
```csharp
private const int _specialDmgMax_1st = 25
```


#### Field Value
**Type:** System.Int32

### _specialDmgMax_2nd
```csharp
private const int _specialDmgMax_2nd = 5
```


#### Field Value
**Type:** System.Int32

### _specialDmgMax_3rd
```csharp
private const int _specialDmgMax_3rd = 7
```


#### Field Value
**Type:** System.Int32

### _specialDmgMin_1st
```csharp
private const int _specialDmgMin_1st = 20
```


#### Field Value
**Type:** System.Int32

### _specialDmgMin_2nd
```csharp
private const int _specialDmgMin_2nd = 4
```


#### Field Value
**Type:** System.Int32

### _specialDmgMin_3rd
```csharp
private const int _specialDmgMin_3rd = 5
```


#### Field Value
**Type:** System.Int32

### _specialDmgRange
```csharp
private const float _specialDmgRange = 4
```


#### Field Value
**Type:** System.Single

### _specialType_1st
```csharp
private const RwbpType _specialType_1st = B
```


#### Field Value
**Type:** Global.RwbpType

### _specialType_2nd
```csharp
private const RwbpType _specialType_2nd = B
```


#### Field Value
**Type:** Global.RwbpType

### _specialType_3rd
```csharp
private const RwbpType _specialType_3rd = B
```


#### Field Value
**Type:** Global.RwbpType

### currentSefira
```csharp
private Sefira currentSefira
```


#### Field Value
**Type:** Global.Sefira

### motionDelayTimer
```csharp
private Timer motionDelayTimer
```


#### Field Value
**Type:** Global.Timer

### moveTarget
```csharp
private UnitModel moveTarget
```


#### Field Value
**Type:** Global.UnitModel

### oldPassage
```csharp
private PassageObjectModel oldPassage
```


#### Field Value
**Type:** Global.PassageObjectModel

### skillCoolTimer
```csharp
private Timer skillCoolTimer
```


#### Field Value
**Type:** Global.Timer

## Properties
### animScript
```csharp
public FixerBlackAnim animScript { get; }
```

#### Property Value
**Type:** Global.FixerBlackAnim

### atkDmg
```csharp
private static DamageInfo atkDmg { get; }
```

#### Property Value
**Type:** Global.DamageInfo

### motionDelay
```csharp
private static float motionDelay { get; }
```

#### Property Value
**Type:** System.Single

### skillCoolTime
```csharp
private static float skillCoolTime { get; }
```

#### Property Value
**Type:** System.Single

### skillDmg
```csharp
private static DamageInfo skillDmg { get; }
```

#### Property Value
**Type:** Global.DamageInfo

### skillInitCoolTime
```csharp
private static float skillInitCoolTime { get; }
```

#### Property Value
**Type:** System.Single

### specialDmg_1st
```csharp
private static DamageInfo specialDmg_1st { get; }
```

#### Property Value
**Type:** Global.DamageInfo

### specialDmg_2nd
```csharp
private static DamageInfo specialDmg_2nd { get; }
```

#### Property Value
**Type:** Global.DamageInfo

### specialDmg_3rd
```csharp
private static DamageInfo specialDmg_3rd { get; }
```

#### Property Value
**Type:** Global.DamageInfo

## Methods
### AttackStart()
```csharp
private void AttackStart()
```


### GetCreaturesInPassage()
```csharp
private List<CreatureModel> GetCreaturesInPassage()
```


#### Returns
**Type:** System.Collections.Generic.List{CreatureModel}

### IsAttacking()
```csharp
private bool IsAttacking()
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

### MakeMovement()
```csharp
private void MakeMovement()
```


### OnAfterSuppressed()
```csharp
public override bool OnAfterSuppressed()
```


#### Returns
**Type:** System.Boolean

### OnAttackDamageTimeCalled()
```csharp
public void OnAttackDamageTimeCalled()
```


### OnAttackEnd()
```csharp
public void OnAttackEnd()
```


### OnDeadSceneEffect()
```csharp
public void OnDeadSceneEffect()
```


### OnFixedUpdate(CreatureModel)
```csharp
public override void OnFixedUpdate(CreatureModel creature)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |

### OnSkillDamage()
```csharp
public void OnSkillDamage()
```


### OnSkillEnd()
```csharp
public void OnSkillEnd()
```


### OnSpecialDamageTimeCalled(int)
```csharp
public void OnSpecialDamageTimeCalled(int type)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `type` | `System.Int32` |  |

### OnViewInit(CreatureUnit)
```csharp
public override void OnViewInit(CreatureUnit unit)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.CreatureUnit` |  |

### SkillStart()
```csharp
private void SkillStart()
```


### StopMovement()
```csharp
private void StopMovement()
```


## Inherited Members
[_ordealScript](/api/Global/Abnormalities/CreatureBase/CreatureBase#isolatespritesrc), [model](/api/Global/Abnormalities/CreatureBase/CreatureBase#model), [skill](/api/Global/Abnormalities/CreatureBase/CreatureBase#skill), [kitEvent](/api/Global/Abnormalities/CreatureBase/CreatureBase#kitevent), [hasUniqueEscapeLogic](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueescapelogic), [isWorkAllocated](/api/Global/Abnormalities/CreatureBase/CreatureBase#isworkallocated), [_allocatedAgent](/api/Global/Abnormalities/CreatureBase/CreatureBase#allocatedagent), [damage](/api/Global/Abnormalities/CreatureBase/CreatureBase#damage), [OnReleaseSpecialTip](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleasespecialtip), [specialSkillTipParamList](/api/Global/Abnormalities/CreatureBase/CreatureBase#specialskilltipparamlist), [_check](/api/Global/Abnormalities/CreatureBase/CreatureBase#check), [SetModel(CreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#setmodel-creaturemodel), [OnInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#oninit), [OnStageStart()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onstagestart), [OnViewInitPrev(CreatureUnit)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onviewinitprev-creatureunit), [OnFixedUpdateInSkill(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfixedupdateinskill-useskill), [OnSkillFailWorkTick(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillfailworktick-useskill), [OnSkillSuccessWorkTick(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillsuccessworktick-useskill), [OnSkillTickUpdate(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskilltickupdate-useskill), [OnSkillGoalComplete(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillgoalcomplete-useskill), [PermitCancelCurrentWork()](/api/Global/Abnormalities/CreatureBase/CreatureBase#permitcancelcurrentwork), [GetKitCreatureProcessTime()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getkitcreatureprocesstime), [OnBonusWorkProb()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onbonusworkprob), [GetDamageMultiplierInWork(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdamagemultiplierinwork-useskill), [TranformWorkProb(float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#tranformworkprob-float), [OnEnterRoom(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onenterroom-useskill), [OnReleaseWork(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleasework-useskill), [OnFinishWork(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfinishwork-useskill), [OnWorkCoolTimeEnd(CreatureFeelingState)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkcooltimeend-creaturefeelingstate), [OnReturn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreturn), [UniqueEscape()](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniqueescape), [Escape()](/api/Global/Abnormalities/CreatureBase/CreatureBase#escape), [GetSpecialSkill()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getspecialskill), [GetDebugText()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdebugtext), [OnTimerEnd()](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontimerend), [MakeEffect(IsolateRoom, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffect-isolateroom-int), [MakeEffectAlter(IsolateRoom, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectalter-isolateroom-int), [Prob(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#prob-int), [isAttackInWorkProcess()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isattackinworkprocess), [OnAttackInWorkProcess(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onattackinworkprocess-useskill), [AttackProcess(UnitModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#attackprocess-unitmodel), [AutoFeelingDown()](/api/Global/Abnormalities/CreatureBase/CreatureBase#autofeelingdown), [AgentAnimCalled(int, WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#agentanimcalled-int-workermodel), [MakingEffect(string, float, string, Transform, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float-string-transform-int), [MakingEffect(string, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float), [MakeEffectAttachedToHead(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectattachedtohead-string), [MakingEffect(string, float, string, Vector3, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float-string-vector3-int), [OnAgentWorkEndAnimationPlayed(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentworkendanimationplayed-useskill), [OnAgentAllocateWork(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentallocatework-agentmodel), [OnSuppressed()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onsuppressed), [OnStageRelease()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onstagerelease), [OnAllocatedWork(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onallocatedwork-agentmodel), [OnReleaseWorkAllocated()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleaseworkallocated), [ObserveLevelChangeForSpecialSkillTip()](/api/Global/Abnormalities/CreatureBase/CreatureBase#observelevelchangeforspecialskilltip), [OnObserveLevelChanged()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onobservelevelchanged), [HasUniqueProcessWorkNarration()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueprocessworknarration), [UniqueProcessWorkNarration(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniqueprocessworknarration-useskill), [RoomSpriteInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomspriteinit), [RoomEscapeSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomescapespriteon), [RoomEscapeSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomescapespriteoff), [RoomSkillSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomskillspriteon), [RoomSkillSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomskillspriteoff), [RoomStateSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomstatespriteon), [RoomStateSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomstatespriteoff), [OnForceSpecialSkillTipReveal(string, params object[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onforcespecialskilltipreveal-string-params-object), [OnWorkReleaseSpeicalSkillTipReveal(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkreleasespeicalskilltipreveal-string), [OnWorkReleaseTipUpdate(params object[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkreleasetipupdate-params-object), [OnAgentAnimatorReseted()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentanimatorreseted), [SpecialEnergyTick()](/api/Global/Abnormalities/CreatureBase/CreatureBase#specialenergytick), [OnStageEnd()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onstageend), [OnFeverTimeOver()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfevertimeover), [OnOverlayIsolateWork()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onoverlayisolatework), [OnOverlayIsolateObserve()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onoverlayisolateobserve), [OnOpenObserveWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopenobservewindow), [OnOpenWorkWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopenworkwindow), [OnOpenCollectionWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopencollectionwindow), [DelayAttackMotion(float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#delayattackmotion-float), [IsAttackTargetable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isattacktargetable), [GetRealTargets()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getrealtargets), [HasScriptSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasscriptsavedata), [GetSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getsavedata), [LoadData(Dictionary<string, object>)](/api/Global/Abnormalities/CreatureBase/CreatureBase#loaddata-dictionary-string-object), [LoadScriptData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#loadscriptdata), [SaveScriptData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#savescriptdata), [ExistSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#existsavedata), [RemoveSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#removesavedata), [ReplaceCommand(CreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#replacecommand-creaturemodel), [OnGamemanagerInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#ongamemanagerinit), [MakeEffectGlobalPos(string, Vector3)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectglobalpos-string-vector3), [MakeEffectGlobalPosNonTrans(string, Vector3)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectglobalposnontrans-string-vector3), [CanObservedByAgent(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#canobservedbyagent-agentmodel), [MakeSound(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string), [MakeSound(string, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string-float), [MakeSound(string, AudioRolloffMode)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string-audiorolloffmode), [MakeSoundQueue(params string[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesoundqueue-params-string), [MakeSoundLoop(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesoundloop-string), [OnViewDestroy()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onviewdestroy), [IsWorkable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isworkable), [ParamInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#paraminit), [HasUniqueMaxObservationFinish()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquemaxobservationfinish), [UniqueMaxObservationFinish(Desc)](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquemaxobservationfinish-desc), [OnChildSuppressed(ChildCreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onchildsuppressed-childcreaturemodel), [MakeChildCreature(UnitModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makechildcreature-unitmodel), [OnKillWorker(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onkillworker-workermodel), [GenPursueCommandAlter(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#genpursuecommandalter-workermodel), [hasUniqueDeadScene()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquedeadscene), [SetHpSlider(Slider)](/api/Global/Abnormalities/CreatureBase/CreatureBase#sethpslider-slider), [SetCastingSlider(Slider)](/api/Global/Abnormalities/CreatureBase/CreatureBase#setcastingslider-slider), [HasUniqueAttackDealy()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueattackdealy), [CanTakeDamage(UnitModel, DamageInfo)](/api/Global/Abnormalities/CreatureBase/CreatureBase#cantakedamage-unitmodel-damageinfo), [OnTakePhysicalDamage(UnitModel, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontakephysicaldamage-unitmodel-float), [HasUniqueFaction()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquefaction), [OnWorkerPanic(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkerpanic-workermodel), [OnSelectMaxObservation(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onselectmaxobservation-int), [OnLoadCreatureName(ref string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onloadcreaturename-ref-string), [IsSuppressable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#issuppressable), [IsSuppressableByRoom()](/api/Global/Abnormalities/CreatureBase/CreatureBase#issuppressablebyroom), [IsAutoSuppressable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isautosuppressable), [OnWorkWindowSkillClicked(long)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkwindowskillclicked-long), [UseDefaultDamageIgnoreMessage(DamageTextEffect)](/api/Global/Abnormalities/CreatureBase/CreatureBase#usedefaultdamageignoremessage-damagetexteffect), [OnWorkAllocated(SkillTypeInfo, AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkallocated-skilltypeinfo-agentmodel), [GetPhysicalDamage(out float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getphysicaldamage-out-float), [GetMentalDamage(out float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getmentaldamage-out-float), [OnSuperArmorBreak()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onsuperarmorbreak), [UniqueStunEffect()](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquestuneffect), [HasEscapeUI()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasescapeui), [HasRoomCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasroomcounter), [RoomCounterInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomcounterinit), [ResetQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#resetqliphothcounter), [GetMaxWorkCountView()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getmaxworkcountview), [GetQliphothCounterMax()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getqliphothcountermax), [ActivateQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#activateqliphothcounter), [ReducedQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#reducedqliphothcounter), [AddedQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#addedqliphothcounter), [OnTakeDamage(UnitModel, DamageInfo, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontakedamage-unitmodel-damageinfo-float), [GetRadius()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getradius), [OnElevatorStuck()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onelevatorstuck), [OnWorkClosed(UseSkill, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkclosed-useskill-int), [IsActivatedWorkDesc()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isactivatedworkdesc), [IsSensoredInPassage()](/api/Global/Abnormalities/CreatureBase/CreatureBase#issensoredinpassage), [IsIndirectSuppressable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isindirectsuppressable), [GetRiskLevel()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getrisklevel), [GetName()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getname), [UniqueMoveControl()](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquemovecontrol), [HasUniqueName()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquename), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdamagefactor-unitmodel-damageinfo), [OnInitialBuild()](/api/Global/Abnormalities/CreatureBase/CreatureBase#oninitialbuild), [HasUniqueCollectionCost(string, out string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquecollectioncost-string-out-string), [OnOpenCommandWindow(Button[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopencommandwindow-button), [HasUniqueCommandAction(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquecommandaction-int), [HasUniqueWorkSelect(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueworkselect-int), [ForcelySuccess(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#forcelysuccess-useskill), [ForcelyFail(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#forcelyfail-useskill), [TryRabbitTeleport(MapNode)](/api/Global/Abnormalities/CreatureBase/CreatureBase#tryrabbitteleport-mapnode), [CanEnterRoom()](/api/Global/Abnormalities/CreatureBase/CreatureBase#canenterroom), [AllocatedAgent](/api/Global/Abnormalities/CreatureBase/CreatureBase#allocatedagent), [skillTriggerCheck](/api/Global/Abnormalities/CreatureBase/CreatureBase#skilltriggercheck), [Unit](/api/Global/Abnormalities/CreatureBase/CreatureBase#unit), [GetSaveSrc](/api/Global/Abnormalities/CreatureBase/CreatureBase#getsavesrc), [movable](/api/Global/Abnormalities/CreatureBase/CreatureBase#movable), [currentPassage](/api/Global/Abnormalities/CreatureBase/CreatureBase#currentpassage), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)






