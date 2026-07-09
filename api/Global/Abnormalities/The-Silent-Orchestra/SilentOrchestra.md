---
uid: Global.SilentOrchestra
canonical_path: /api/Global/Misc/SilentOrchestra
---
# Class SilentOrchestra
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SilentOrchestra : CreatureBase
```
> This section may have incomplete or incorrect information.
{.is-warning}


The Silent Orchestra.




## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase](/api/Global/Abnormalities/CreatureBase/CreatureBase) → SilentOrchestra

## Constructors
### SilentOrchestra()
```csharp
public SilentOrchestra()
```

## Fields
### _animScript
```csharp
private SilentOrchestraAnim _animScript
```


#### Field Value
**Type:** Global.SilentOrchestraAnim

### _appearDelayTime
```csharp
private const float _appearDelayTime = 6
```


#### Field Value
**Type:** System.Single

### _appearDelayTimer
```csharp
private Timer _appearDelayTimer
```


#### Field Value
**Type:** Global.Timer

### _audioChange
```csharp
private bool _audioChange
```


#### Field Value
**Type:** System.Boolean

### _cameraSensing
```csharp
private CreatureBase.SensingModule _cameraSensing
```

#### Field Value
**Type:** Global.CreatureBase.SensingModule

### _currentMovement
```csharp
private SilentOrchestra.Movement _currentMovement
```

#### Field Value
**Type:** Global.SilentOrchestra.Movement

### _curtainReady
```csharp
private bool _curtainReady
```


#### Field Value
**Type:** System.Boolean

### _damageTick
```csharp
private const float _damageTick = 5
```


#### Field Value
**Type:** System.Single

### _dayFlag
```csharp
private bool _dayFlag
```


#### Field Value
**Type:** System.Boolean

### _deadSceneDelayMax
```csharp
private const float _deadSceneDelayMax = 3
```


#### Field Value
**Type:** System.Single

### _deadSceneDelayMin
```csharp
private const float _deadSceneDelayMin = 2
```


#### Field Value
**Type:** System.Single

### _escapeReady
```csharp
private bool _escapeReady
```


#### Field Value
**Type:** System.Boolean

### _executeDeadCommand
```csharp
private bool _executeDeadCommand
```


#### Field Value
**Type:** System.Boolean

### _finaleActivated
```csharp
private bool _finaleActivated
```


#### Field Value
**Type:** System.Boolean

### _finaleStarted
```csharp
private bool _finaleStarted
```


#### Field Value
**Type:** System.Boolean

### _finaleTargets
```csharp
private List<WorkerModel> _finaleTargets
```


#### Field Value
**Type:** System.Collections.Generic.List{WorkerModel}

### _finaleTimmingCheck
```csharp
private Timer _finaleTimmingCheck
```


#### Field Value
**Type:** Global.Timer

### _isEscaped
```csharp
private bool _isEscaped
```


#### Field Value
**Type:** System.Boolean

### _loop
```csharp
private SoundEffectPlayer _loop
```


#### Field Value
**Type:** Global.SoundEffectPlayer

### _suppressed
```csharp
private bool _suppressed
```


#### Field Value
**Type:** System.Boolean

### DamageTick
```csharp
public Timer DamageTick
```


#### Field Value
**Type:** Global.Timer

### dmgAry
```csharp
public static float[,] dmgAry
```


#### Field Value
**Type:** System.Single[,]

### effectRadius
```csharp
public static float[] effectRadius
```


#### Field Value
**Type:** System.Single[]

### FactionCode
```csharp
public const string FactionCode = "10"
```


#### Field Value
**Type:** System.String

### FinaleTimer
```csharp
public Timer FinaleTimer
```


#### Field Value
**Type:** Global.Timer

### movementTime
```csharp
public static float[] movementTime
```


#### Field Value
**Type:** System.Single[]

### MovementTimer
```csharp
public Timer MovementTimer
```


#### Field Value
**Type:** Global.Timer

## Properties
### AnimScript
```csharp
public SilentOrchestraAnim AnimScript { get; }
```

#### Property Value
**Type:** Global.SilentOrchestraAnim

### CurrentDamageInfo
```csharp
private DamageInfo CurrentDamageInfo { get; }
```

#### Property Value
**Type:** Global.DamageInfo

### CurrentMovement
```csharp
public SilentOrchestra.Movement CurrentMovement { get; }
```

#### Property Value
**Type:** Global.SilentOrchestra.Movement

### CurrentMovementTime
```csharp
private float CurrentMovementTime { get; }
```

#### Property Value
**Type:** System.Single

### EffectRange
```csharp
private float EffectRange { get; }
```

#### Property Value
**Type:** System.Single

### randDeadSceneDealy
```csharp
private float randDeadSceneDealy { get; }
```

#### Property Value
**Type:** System.Single

## Methods
### ActivateFinale()
```csharp
private void ActivateFinale()
```


### ActivateQliphothCounter()
```csharp
public override void ActivateQliphothCounter()
```


### CheckCamera()
```csharp
private void CheckCamera()
```


### DamageCalc(float)
```csharp
public DamageInfo DamageCalc(float factor)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `factor` | `System.Single` |  |

#### Returns
**Type:** Global.DamageInfo

### Escape()
```csharp
public override void Escape()
```


### ForcelyReturn()
```csharp
private void ForcelyReturn()
```


### ForcelySuppressed()
```csharp
private void ForcelySuppressed()
```


### GetAllWorkers()
```csharp
private List<WorkerModel> GetAllWorkers()
```


#### Returns
**Type:** System.Collections.Generic.List{WorkerModel}

### GetDamage(Movement, Movement)
```csharp
public static float GetDamage(SilentOrchestra.Movement currentMovement, SilentOrchestra.Movement targetPosition)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `currentMovement` | `Global.SilentOrchestra.Movement` |  |
| `targetPosition` | `Global.SilentOrchestra.Movement` |  |

#### Returns
**Type:** System.Single

### GetDesc(int)
```csharp
public CreatureStaticData.ParameterData GetDesc(int index)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

#### Returns
**Type:** Global.CreatureStaticData.ParameterData

### GetSoundSrc(string)
```csharp
public string GetSoundSrc(string key)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |

#### Returns
**Type:** System.String

### GetTeleportNode()
```csharp
private MapNode GetTeleportNode()
```


#### Returns
**Type:** Global.MapNode

### HasUniqueFaction()
```csharp
public override bool HasUniqueFaction()
```


#### Returns
**Type:** System.Boolean

### IsInArea(MovableObjectNode, out Movement)
```csharp
private bool IsInArea(MovableObjectNode mov, out SilentOrchestra.Movement type)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `mov` | `Global.MovableObjectNode` |  |
| `type` | `Global.SilentOrchestra.Movement` |  |

#### Returns
**Type:** System.Boolean

### IsInRange(float, MovableObjectNode)
```csharp
private bool IsInRange(float rad, MovableObjectNode target)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `rad` | `System.Single` |  |
| `target` | `Global.MovableObjectNode` |  |

#### Returns
**Type:** System.Boolean

### MakeSound(string)
```csharp
public override SoundEffectPlayer MakeSound(string src)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

#### Returns
**Type:** Global.SoundEffectPlayer

### OnConductorReady()
```csharp
public void OnConductorReady()
```


### OnCurtainAppear()
```csharp
public void OnCurtainAppear()
```


### OnCurtainStartOpen()
```csharp
public void OnCurtainStartOpen()
```


### OnFinale()
```csharp
private void OnFinale()
```


### OnFinaleEnd()
```csharp
public void OnFinaleEnd()
```


### OnFinaleStartDead()
```csharp
public void OnFinaleStartDead()
```


### OnFixedUpdate(CreatureModel)
```csharp
public override void OnFixedUpdate(CreatureModel creature)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |

### OnInit()
```csharp
public override void OnInit()
```


### OnMovementEnd()
```csharp
public void OnMovementEnd()
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


### OnSuppressed()
```csharp
public override void OnSuppressed()
```


### OnViewInit(CreatureUnit)
```csharp
public override void OnViewInit(CreatureUnit unit)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.CreatureUnit` |  |

### OnWorkCoolTimeEnd(CreatureFeelingState)
```csharp
public override void OnWorkCoolTimeEnd(CreatureFeelingState oldState)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `oldState` | `Global.CreatureFeelingState` |  |

### ParamInit()
```csharp
public override void ParamInit()
```


### RoomSpriteInit()
```csharp
public override void RoomSpriteInit()
```


### SetBackGroundLoop(string)
```csharp
public void SetBackGroundLoop(string key)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |

### SetDefenseType()
```csharp
private void SetDefenseType()
```


### SetSpaceState(bool)
```csharp
public void SetSpaceState(bool state)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### StartFinaleEffect()
```csharp
private void StartFinaleEffect()
```


### Teleport()
```csharp
private void Teleport()
```


### TerminateAudio()
```csharp
private void TerminateAudio()
```


### UniqueEscape()
```csharp
public override void UniqueEscape()
```


## Inherited Members
[isolateSpriteSrc](/api/Global/Abnormalities/CreatureBase/CreatureBase#isolatespritesrc), [model](/api/Global/Abnormalities/CreatureBase/CreatureBase#model), [skill](/api/Global/Abnormalities/CreatureBase/CreatureBase#skill), [kitEvent](/api/Global/Abnormalities/CreatureBase/CreatureBase#kitevent), [hasUniqueEscapeLogic](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueescapelogic), [isWorkAllocated](/api/Global/Abnormalities/CreatureBase/CreatureBase#isworkallocated), [_allocatedAgent](/api/Global/Abnormalities/CreatureBase/CreatureBase#allocatedagent), [damage](/api/Global/Abnormalities/CreatureBase/CreatureBase#damage), [OnReleaseSpecialTip](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleasespecialtip), [specialSkillTipParamList](/api/Global/Abnormalities/CreatureBase/CreatureBase#specialskilltipparamlist), [_check](/api/Global/Abnormalities/CreatureBase/CreatureBase#check), [SetModel(CreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#setmodel-creaturemodel), [OnViewInitPrev(CreatureUnit)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onviewinitprev-creatureunit), [OnFixedUpdateInSkill(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfixedupdateinskill-useskill), [OnSkillFailWorkTick(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillfailworktick-useskill), [OnSkillSuccessWorkTick(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillsuccessworktick-useskill), [OnSkillTickUpdate(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskilltickupdate-useskill), [OnSkillGoalComplete(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillgoalcomplete-useskill), [PermitCancelCurrentWork()](/api/Global/Abnormalities/CreatureBase/CreatureBase#permitcancelcurrentwork), [GetKitCreatureProcessTime()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getkitcreatureprocesstime), [OnBonusWorkProb()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onbonusworkprob), [GetDamageMultiplierInWork(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdamagemultiplierinwork-useskill), [TranformWorkProb(float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#tranformworkprob-float), [OnEnterRoom(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onenterroom-useskill), [OnFinishWork(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfinishwork-useskill), [GetSpecialSkill()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getspecialskill), [GetDebugText()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdebugtext), [OnTimerEnd()](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontimerend), [MakeEffect(IsolateRoom, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffect-isolateroom-int), [MakeEffectAlter(IsolateRoom, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectalter-isolateroom-int), [Prob(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#prob-int), [isAttackInWorkProcess()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isattackinworkprocess), [OnAttackInWorkProcess(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onattackinworkprocess-useskill), [AttackProcess(UnitModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#attackprocess-unitmodel), [AutoFeelingDown()](/api/Global/Abnormalities/CreatureBase/CreatureBase#autofeelingdown), [AgentAnimCalled(int, WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#agentanimcalled-int-workermodel), [MakingEffect(string, float, string, Transform, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float-string-transform-int), [MakingEffect(string, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float), [MakeEffectAttachedToHead(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectattachedtohead-string), [MakingEffect(string, float, string, Vector3, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float-string-vector3-int), [OnAgentWorkEndAnimationPlayed(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentworkendanimationplayed-useskill), [OnAgentAllocateWork(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentallocatework-agentmodel), [OnAllocatedWork(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onallocatedwork-agentmodel), [OnReleaseWorkAllocated()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleaseworkallocated), [ObserveLevelChangeForSpecialSkillTip()](/api/Global/Abnormalities/CreatureBase/CreatureBase#observelevelchangeforspecialskilltip), [OnObserveLevelChanged()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onobservelevelchanged), [HasUniqueProcessWorkNarration()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueprocessworknarration), [UniqueProcessWorkNarration(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniqueprocessworknarration-useskill), [RoomEscapeSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomescapespriteon), [RoomEscapeSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomescapespriteoff), [RoomSkillSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomskillspriteon), [RoomSkillSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomskillspriteoff), [RoomStateSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomstatespriteon), [RoomStateSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomstatespriteoff), [OnForceSpecialSkillTipReveal(string, params object[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onforcespecialskilltipreveal-string-params-object), [OnWorkReleaseSpeicalSkillTipReveal(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkreleasespeicalskilltipreveal-string), [OnWorkReleaseTipUpdate(params object[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkreleasetipupdate-params-object), [OnAgentAnimatorReseted()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentanimatorreseted), [SpecialEnergyTick()](/api/Global/Abnormalities/CreatureBase/CreatureBase#specialenergytick), [OnFeverTimeOver()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfevertimeover), [OnOverlayIsolateWork()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onoverlayisolatework), [OnOverlayIsolateObserve()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onoverlayisolateobserve), [OnOpenObserveWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopenobservewindow), [OnOpenWorkWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopenworkwindow), [OnOpenCollectionWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopencollectionwindow), [DelayAttackMotion(float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#delayattackmotion-float), [IsAttackTargetable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isattacktargetable), [GetRealTargets()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getrealtargets), [HasScriptSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasscriptsavedata), [GetSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getsavedata), [LoadData(Dictionary<string, object>)](/api/Global/Abnormalities/CreatureBase/CreatureBase#loaddata-dictionary-string-object), [LoadScriptData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#loadscriptdata), [SaveScriptData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#savescriptdata), [ExistSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#existsavedata), [RemoveSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#removesavedata), [ReplaceCommand(CreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#replacecommand-creaturemodel), [OnGamemanagerInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#ongamemanagerinit), [MakeEffectGlobalPos(string, Vector3)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectglobalpos-string-vector3), [MakeEffectGlobalPosNonTrans(string, Vector3)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectglobalposnontrans-string-vector3), [CanObservedByAgent(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#canobservedbyagent-agentmodel), [MakeSound(string, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string-float), [MakeSound(string, AudioRolloffMode)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string-audiorolloffmode), [MakeSoundQueue(params string[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesoundqueue-params-string), [MakeSoundLoop(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesoundloop-string), [OnViewDestroy()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onviewdestroy), [IsWorkable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isworkable), [HasUniqueMaxObservationFinish()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquemaxobservationfinish), [UniqueMaxObservationFinish(Desc)](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquemaxobservationfinish-desc), [OnChildSuppressed(ChildCreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onchildsuppressed-childcreaturemodel), [MakeChildCreature(UnitModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makechildcreature-unitmodel), [OnKillWorker(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onkillworker-workermodel), [GenPursueCommandAlter(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#genpursuecommandalter-workermodel), [OnAfterSuppressed()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onaftersuppressed), [hasUniqueDeadScene()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquedeadscene), [SetHpSlider(Slider)](/api/Global/Abnormalities/CreatureBase/CreatureBase#sethpslider-slider), [SetCastingSlider(Slider)](/api/Global/Abnormalities/CreatureBase/CreatureBase#setcastingslider-slider), [HasUniqueAttackDealy()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueattackdealy), [CanTakeDamage(UnitModel, DamageInfo)](/api/Global/Abnormalities/CreatureBase/CreatureBase#cantakedamage-unitmodel-damageinfo), [OnTakePhysicalDamage(UnitModel, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontakephysicaldamage-unitmodel-float), [OnWorkerPanic(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkerpanic-workermodel), [OnSelectMaxObservation(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onselectmaxobservation-int), [OnLoadCreatureName(ref string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onloadcreaturename-ref-string), [IsSuppressable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#issuppressable), [IsSuppressableByRoom()](/api/Global/Abnormalities/CreatureBase/CreatureBase#issuppressablebyroom), [IsAutoSuppressable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isautosuppressable), [OnWorkWindowSkillClicked(long)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkwindowskillclicked-long), [UseDefaultDamageIgnoreMessage(DamageTextEffect)](/api/Global/Abnormalities/CreatureBase/CreatureBase#usedefaultdamageignoremessage-damagetexteffect), [OnWorkAllocated(SkillTypeInfo, AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkallocated-skilltypeinfo-agentmodel), [GetPhysicalDamage(out float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getphysicaldamage-out-float), [GetMentalDamage(out float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getmentaldamage-out-float), [OnSuperArmorBreak()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onsuperarmorbreak), [UniqueStunEffect()](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquestuneffect), [HasEscapeUI()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasescapeui), [HasRoomCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasroomcounter), [RoomCounterInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomcounterinit), [ResetQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#resetqliphothcounter), [GetMaxWorkCountView()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getmaxworkcountview), [GetQliphothCounterMax()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getqliphothcountermax), [ReducedQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#reducedqliphothcounter), [AddedQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#addedqliphothcounter), [OnTakeDamage(UnitModel, DamageInfo, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontakedamage-unitmodel-damageinfo-float), [GetRadius()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getradius), [OnElevatorStuck()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onelevatorstuck), [OnWorkClosed(UseSkill, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkclosed-useskill-int), [IsActivatedWorkDesc()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isactivatedworkdesc), [IsSensoredInPassage()](/api/Global/Abnormalities/CreatureBase/CreatureBase#issensoredinpassage), [IsIndirectSuppressable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isindirectsuppressable), [GetRiskLevel()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getrisklevel), [GetName()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getname), [UniqueMoveControl()](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquemovecontrol), [HasUniqueName()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquename), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdamagefactor-unitmodel-damageinfo), [OnInitialBuild()](/api/Global/Abnormalities/CreatureBase/CreatureBase#oninitialbuild), [HasUniqueCollectionCost(string, out string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquecollectioncost-string-out-string), [OnOpenCommandWindow(Button[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopencommandwindow-button), [HasUniqueCommandAction(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquecommandaction-int), [HasUniqueWorkSelect(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueworkselect-int), [ForcelySuccess(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#forcelysuccess-useskill), [ForcelyFail(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#forcelyfail-useskill), [TryRabbitTeleport(MapNode)](/api/Global/Abnormalities/CreatureBase/CreatureBase#tryrabbitteleport-mapnode), [CanEnterRoom()](/api/Global/Abnormalities/CreatureBase/CreatureBase#canenterroom), [AllocatedAgent](/api/Global/Abnormalities/CreatureBase/CreatureBase#allocatedagent), [skillTriggerCheck](/api/Global/Abnormalities/CreatureBase/CreatureBase#skilltriggercheck), [Unit](/api/Global/Abnormalities/CreatureBase/CreatureBase#unit), [GetSaveSrc](/api/Global/Abnormalities/CreatureBase/CreatureBase#getsavesrc), [movable](/api/Global/Abnormalities/CreatureBase/CreatureBase#movable), [currentPassage](/api/Global/Abnormalities/CreatureBase/CreatureBase#currentpassage), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)







