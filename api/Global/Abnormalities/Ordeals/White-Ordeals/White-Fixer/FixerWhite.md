---
uid: Global.FixerWhite
canonical_path: /api/Global/Misc/FixerWhite
---
# Class FixerWhite
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class FixerWhite : FixerCreature
```
> This section may have incomplete or incorrect information.
{.is-warning}


White Fixer.




## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase](/api/Global/Abnormalities/Ordeals/White-Ordeals/FixerCreature) → FixerWhite

## Constructors
### FixerWhite()
```csharp
public FixerWhite()
```

## Fields
### _animScript
```csharp
private FixerWhiteAnim _animScript
```


#### Field Value
**Type:** Global.FixerWhiteAnim

### _bladeCoolTimeMax
```csharp
private const float _bladeCoolTimeMax = 60
```


#### Field Value
**Type:** System.Single

### _bladeCoolTimeMin
```csharp
private const float _bladeCoolTimeMin = 55
```


#### Field Value
**Type:** System.Single

### _bladeInitCoolTimeMax
```csharp
private const float _bladeInitCoolTimeMax = 45
```


#### Field Value
**Type:** System.Single

### _bladeInitCoolTimeMin
```csharp
private const float _bladeInitCoolTimeMin = 40
```


#### Field Value
**Type:** System.Single

### _cannonCoolTimeMax
```csharp
private const float _cannonCoolTimeMax = 21
```


#### Field Value
**Type:** System.Single

### _cannonCoolTimeMin
```csharp
private const float _cannonCoolTimeMin = 19
```


#### Field Value
**Type:** System.Single

### _cannonInitCoolTimeMax
```csharp
private const float _cannonInitCoolTimeMax = 15
```


#### Field Value
**Type:** System.Single

### _cannonInitCoolTimeMin
```csharp
private const float _cannonInitCoolTimeMin = 12
```


#### Field Value
**Type:** System.Single

### _cloudDmgMax
```csharp
private const int _cloudDmgMax = 6
```


#### Field Value
**Type:** System.Int32

### _cloudDmgMin
```csharp
private const int _cloudDmgMin = 4
```


#### Field Value
**Type:** System.Int32

### _cloudType
```csharp
private const RwbpType _cloudType = W
```


#### Field Value
**Type:** Global.RwbpType

### _dSceneDmgMax
```csharp
private const int _dSceneDmgMax = 15
```


#### Field Value
**Type:** System.Int32

### _dSceneDmgMin
```csharp
private const int _dSceneDmgMin = 12
```


#### Field Value
**Type:** System.Int32

### _dSceneType
```csharp
private const RwbpType _dSceneType = W
```


#### Field Value
**Type:** Global.RwbpType

### _laserDmgMax
```csharp
private const int _laserDmgMax = 12
```


#### Field Value
**Type:** System.Int32

### _laserDmgMin
```csharp
private const int _laserDmgMin = 10
```


#### Field Value
**Type:** System.Int32

### _laserType
```csharp
private const RwbpType _laserType = W
```


#### Field Value
**Type:** Global.RwbpType

### _motionDelayMax
```csharp
private const float _motionDelayMax = 1.5
```


#### Field Value
**Type:** System.Single

### _motionDelayMin
```csharp
private const float _motionDelayMin = 1
```


#### Field Value
**Type:** System.Single

### bladeCoolTimer
```csharp
private Timer bladeCoolTimer
```


#### Field Value
**Type:** Global.Timer

### cannonCoolTimer
```csharp
private Timer cannonCoolTimer
```


#### Field Value
**Type:** Global.Timer

### motionDelayTimer
```csharp
private Timer motionDelayTimer
```


#### Field Value
**Type:** Global.Timer

### prayCnt
```csharp
private int prayCnt
```


#### Field Value
**Type:** System.Int32

## Properties
### animScript
```csharp
public FixerWhiteAnim animScript { get; }
```

#### Property Value
**Type:** Global.FixerWhiteAnim

### bladeCoolTime
```csharp
private static float bladeCoolTime { get; }
```

#### Property Value
**Type:** System.Single

### bladeInitCoolTime
```csharp
private static float bladeInitCoolTime { get; }
```

#### Property Value
**Type:** System.Single

### cannonCoolTime
```csharp
private static float cannonCoolTime { get; }
```

#### Property Value
**Type:** System.Single

### cannonInitCoolTime
```csharp
private static float cannonInitCoolTime { get; }
```

#### Property Value
**Type:** System.Single

### CloudDamage
```csharp
public static DamageInfo CloudDamage { get; }
```

#### Property Value
**Type:** Global.DamageInfo

### dSceneDamage
```csharp
private static DamageInfo dSceneDamage { get; }
```

#### Property Value
**Type:** Global.DamageInfo

### LaserDamage
```csharp
public static DamageInfo LaserDamage { get; }
```

#### Property Value
**Type:** Global.DamageInfo

### motionDelay
```csharp
private static float motionDelay { get; }
```

#### Property Value
**Type:** System.Single

## Methods
### BladeStart()
```csharp
private void BladeStart()
```


### CannonStart()
```csharp
private void CannonStart()
```


### CanTakeDamage(UnitModel, DamageInfo)
```csharp
public override bool CanTakeDamage(UnitModel attacker, DamageInfo dmg)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `attacker` | `Global.UnitModel` |  |
| `dmg` | `Global.DamageInfo` |  |

#### Returns
**Type:** System.Boolean

### IsMovable()
```csharp
private bool IsMovable()
```


#### Returns
**Type:** System.Boolean

### IsPraying()
```csharp
private bool IsPraying()
```


#### Returns
**Type:** System.Boolean

### IsShootingCannon()
```csharp
private bool IsShootingCannon()
```


#### Returns
**Type:** System.Boolean

### IsUsingBlade()
```csharp
private bool IsUsingBlade()
```


#### Returns
**Type:** System.Boolean

### MakeMovement()
```csharp
private void MakeMovement()
```


### MakeReflectSound()
```csharp
private SoundEffectPlayer MakeReflectSound()
```


#### Returns
**Type:** Global.SoundEffectPlayer

### MoveAround()
```csharp
private void MoveAround()
```


### OnAfterSuppressed()
```csharp
public override bool OnAfterSuppressed()
```


#### Returns
**Type:** System.Boolean

### OnBladeEnd()
```csharp
public void OnBladeEnd()
```


### OnCannonEnd()
```csharp
public void OnCannonEnd()
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

### OnPrayEnd()
```csharp
public void OnPrayEnd()
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

### Pray()
```csharp
private void Pray()
```


### PrepareAttack(UnitModel)
```csharp
private void PrepareAttack(UnitModel target)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### StopMovement()
```csharp
private void StopMovement()
```


### TryAttack(UnitModel)
```csharp
private bool TryAttack(UnitModel nearest)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `nearest` | `Global.UnitModel` |  |

#### Returns
**Type:** System.Boolean

## Inherited Members
[_ordealScript](/api/Global/Abnormalities/CreatureBase/CreatureBase#isolatespritesrc), [model](/api/Global/Abnormalities/CreatureBase/CreatureBase#model), [skill](/api/Global/Abnormalities/CreatureBase/CreatureBase#skill), [kitEvent](/api/Global/Abnormalities/CreatureBase/CreatureBase#kitevent), [hasUniqueEscapeLogic](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueescapelogic), [isWorkAllocated](/api/Global/Abnormalities/CreatureBase/CreatureBase#isworkallocated), [_allocatedAgent](/api/Global/Abnormalities/CreatureBase/CreatureBase#allocatedagent), [damage](/api/Global/Abnormalities/CreatureBase/CreatureBase#damage), [OnReleaseSpecialTip](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleasespecialtip), [specialSkillTipParamList](/api/Global/Abnormalities/CreatureBase/CreatureBase#specialskilltipparamlist), [_check](/api/Global/Abnormalities/CreatureBase/CreatureBase#check), [SetModel(CreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#setmodel-creaturemodel), [OnInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#oninit), [OnStageStart()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onstagestart), [OnViewInitPrev(CreatureUnit)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onviewinitprev-creatureunit), [OnFixedUpdateInSkill(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfixedupdateinskill-useskill), [OnSkillFailWorkTick(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillfailworktick-useskill), [OnSkillSuccessWorkTick(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillsuccessworktick-useskill), [OnSkillTickUpdate(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskilltickupdate-useskill), [OnSkillGoalComplete(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillgoalcomplete-useskill), [PermitCancelCurrentWork()](/api/Global/Abnormalities/CreatureBase/CreatureBase#permitcancelcurrentwork), [GetKitCreatureProcessTime()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getkitcreatureprocesstime), [OnBonusWorkProb()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onbonusworkprob), [GetDamageMultiplierInWork(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdamagemultiplierinwork-useskill), [TranformWorkProb(float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#tranformworkprob-float), [OnEnterRoom(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onenterroom-useskill), [OnReleaseWork(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleasework-useskill), [OnFinishWork(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfinishwork-useskill), [OnWorkCoolTimeEnd(CreatureFeelingState)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkcooltimeend-creaturefeelingstate), [OnReturn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreturn), [UniqueEscape()](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniqueescape), [Escape()](/api/Global/Abnormalities/CreatureBase/CreatureBase#escape), [GetSpecialSkill()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getspecialskill), [GetDebugText()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdebugtext), [OnTimerEnd()](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontimerend), [MakeEffect(IsolateRoom, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffect-isolateroom-int), [MakeEffectAlter(IsolateRoom, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectalter-isolateroom-int), [Prob(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#prob-int), [isAttackInWorkProcess()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isattackinworkprocess), [OnAttackInWorkProcess(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onattackinworkprocess-useskill), [AttackProcess(UnitModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#attackprocess-unitmodel), [AutoFeelingDown()](/api/Global/Abnormalities/CreatureBase/CreatureBase#autofeelingdown), [AgentAnimCalled(int, WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#agentanimcalled-int-workermodel), [MakingEffect(string, float, string, Transform, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float-string-transform-int), [MakingEffect(string, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float), [MakeEffectAttachedToHead(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectattachedtohead-string), [MakingEffect(string, float, string, Vector3, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float-string-vector3-int), [OnAgentWorkEndAnimationPlayed(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentworkendanimationplayed-useskill), [OnAgentAllocateWork(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentallocatework-agentmodel), [OnSuppressed()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onsuppressed), [OnStageRelease()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onstagerelease), [OnAllocatedWork(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onallocatedwork-agentmodel), [OnReleaseWorkAllocated()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleaseworkallocated), [ObserveLevelChangeForSpecialSkillTip()](/api/Global/Abnormalities/CreatureBase/CreatureBase#observelevelchangeforspecialskilltip), [OnObserveLevelChanged()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onobservelevelchanged), [HasUniqueProcessWorkNarration()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueprocessworknarration), [UniqueProcessWorkNarration(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniqueprocessworknarration-useskill), [RoomSpriteInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomspriteinit), [RoomEscapeSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomescapespriteon), [RoomEscapeSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomescapespriteoff), [RoomSkillSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomskillspriteon), [RoomSkillSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomskillspriteoff), [RoomStateSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomstatespriteon), [RoomStateSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomstatespriteoff), [OnForceSpecialSkillTipReveal(string, params object[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onforcespecialskilltipreveal-string-params-object), [OnWorkReleaseSpeicalSkillTipReveal(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkreleasespeicalskilltipreveal-string), [OnWorkReleaseTipUpdate(params object[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkreleasetipupdate-params-object), [OnAgentAnimatorReseted()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentanimatorreseted), [SpecialEnergyTick()](/api/Global/Abnormalities/CreatureBase/CreatureBase#specialenergytick), [OnStageEnd()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onstageend), [OnFeverTimeOver()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfevertimeover), [OnOverlayIsolateWork()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onoverlayisolatework), [OnOverlayIsolateObserve()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onoverlayisolateobserve), [OnOpenObserveWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopenobservewindow), [OnOpenWorkWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopenworkwindow), [OnOpenCollectionWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopencollectionwindow), [DelayAttackMotion(float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#delayattackmotion-float), [IsAttackTargetable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isattacktargetable), [GetRealTargets()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getrealtargets), [HasScriptSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasscriptsavedata), [GetSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getsavedata), [LoadData(Dictionary<string, object>)](/api/Global/Abnormalities/CreatureBase/CreatureBase#loaddata-dictionary-string-object), [LoadScriptData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#loadscriptdata), [SaveScriptData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#savescriptdata), [ExistSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#existsavedata), [RemoveSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#removesavedata), [ReplaceCommand(CreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#replacecommand-creaturemodel), [OnGamemanagerInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#ongamemanagerinit), [MakeEffectGlobalPos(string, Vector3)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectglobalpos-string-vector3), [MakeEffectGlobalPosNonTrans(string, Vector3)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectglobalposnontrans-string-vector3), [CanObservedByAgent(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#canobservedbyagent-agentmodel), [MakeSound(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string), [MakeSound(string, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string-float), [MakeSound(string, AudioRolloffMode)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string-audiorolloffmode), [MakeSoundQueue(params string[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesoundqueue-params-string), [MakeSoundLoop(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesoundloop-string), [OnViewDestroy()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onviewdestroy), [IsWorkable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isworkable), [ParamInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#paraminit), [HasUniqueMaxObservationFinish()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquemaxobservationfinish), [UniqueMaxObservationFinish(Desc)](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquemaxobservationfinish-desc), [OnChildSuppressed(ChildCreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onchildsuppressed-childcreaturemodel), [MakeChildCreature(UnitModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makechildcreature-unitmodel), [OnKillWorker(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onkillworker-workermodel), [GenPursueCommandAlter(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#genpursuecommandalter-workermodel), [hasUniqueDeadScene()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquedeadscene), [SetHpSlider(Slider)](/api/Global/Abnormalities/CreatureBase/CreatureBase#sethpslider-slider), [SetCastingSlider(Slider)](/api/Global/Abnormalities/CreatureBase/CreatureBase#setcastingslider-slider), [HasUniqueAttackDealy()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueattackdealy), [OnTakePhysicalDamage(UnitModel, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontakephysicaldamage-unitmodel-float), [HasUniqueFaction()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquefaction), [OnWorkerPanic(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkerpanic-workermodel), [OnSelectMaxObservation(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onselectmaxobservation-int), [OnLoadCreatureName(ref string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onloadcreaturename-ref-string), [IsSuppressable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#issuppressable), [IsSuppressableByRoom()](/api/Global/Abnormalities/CreatureBase/CreatureBase#issuppressablebyroom), [IsAutoSuppressable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isautosuppressable), [OnWorkWindowSkillClicked(long)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkwindowskillclicked-long), [UseDefaultDamageIgnoreMessage(DamageTextEffect)](/api/Global/Abnormalities/CreatureBase/CreatureBase#usedefaultdamageignoremessage-damagetexteffect), [OnWorkAllocated(SkillTypeInfo, AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkallocated-skilltypeinfo-agentmodel), [GetPhysicalDamage(out float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getphysicaldamage-out-float), [GetMentalDamage(out float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getmentaldamage-out-float), [OnSuperArmorBreak()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onsuperarmorbreak), [UniqueStunEffect()](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquestuneffect), [HasEscapeUI()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasescapeui), [HasRoomCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasroomcounter), [RoomCounterInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomcounterinit), [ResetQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#resetqliphothcounter), [GetMaxWorkCountView()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getmaxworkcountview), [GetQliphothCounterMax()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getqliphothcountermax), [ActivateQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#activateqliphothcounter), [ReducedQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#reducedqliphothcounter), [AddedQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#addedqliphothcounter), [GetRadius()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getradius), [OnElevatorStuck()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onelevatorstuck), [OnWorkClosed(UseSkill, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkclosed-useskill-int), [IsActivatedWorkDesc()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isactivatedworkdesc), [IsSensoredInPassage()](/api/Global/Abnormalities/CreatureBase/CreatureBase#issensoredinpassage), [IsIndirectSuppressable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isindirectsuppressable), [GetRiskLevel()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getrisklevel), [GetName()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getname), [UniqueMoveControl()](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquemovecontrol), [HasUniqueName()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquename), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdamagefactor-unitmodel-damageinfo), [OnInitialBuild()](/api/Global/Abnormalities/CreatureBase/CreatureBase#oninitialbuild), [HasUniqueCollectionCost(string, out string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquecollectioncost-string-out-string), [OnOpenCommandWindow(Button[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopencommandwindow-button), [HasUniqueCommandAction(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquecommandaction-int), [HasUniqueWorkSelect(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueworkselect-int), [ForcelySuccess(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#forcelysuccess-useskill), [ForcelyFail(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#forcelyfail-useskill), [TryRabbitTeleport(MapNode)](/api/Global/Abnormalities/CreatureBase/CreatureBase#tryrabbitteleport-mapnode), [CanEnterRoom()](/api/Global/Abnormalities/CreatureBase/CreatureBase#canenterroom), [AllocatedAgent](/api/Global/Abnormalities/CreatureBase/CreatureBase#allocatedagent), [skillTriggerCheck](/api/Global/Abnormalities/CreatureBase/CreatureBase#skilltriggercheck), [Unit](/api/Global/Abnormalities/CreatureBase/CreatureBase#unit), [GetSaveSrc](/api/Global/Abnormalities/CreatureBase/CreatureBase#getsavesrc), [movable](/api/Global/Abnormalities/CreatureBase/CreatureBase#movable), [currentPassage](/api/Global/Abnormalities/CreatureBase/CreatureBase#currentpassage), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)






