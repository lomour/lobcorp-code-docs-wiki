---
uid: Global.SmallBird
canonical_path: /api/Global/Misc/SmallBird
---
# Class SmallBird
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SmallBird : BirdCreatureBase, IObserver, IBirdControl
```
> This section may have incomplete or incorrect information.
{.is-warning}


Punishing Bird.




## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase](/api/Global/Abnormalities/Apocalypse-Bird/BirdCreatureBase) → SmallBird

## Implements
[IObserver](/api/Global/Abnormalities/Apocalypse-Bird/IBirdControl)

## Constructors
### SmallBird()
```csharp
public SmallBird()
```

## Fields
### _animScript
```csharp
private SmallBirdAnim _animScript
```


#### Field Value
**Type:** Global.SmallBirdAnim

### _otherBirdState
```csharp
private BossBird.OtherBirdState _otherBirdState
```


#### Field Value
**Type:** Global.BossBird.OtherBirdState

### attackPattern
```csharp
private SmallBird.AttackPattern attackPattern
```

#### Field Value
**Type:** Global.SmallBird.AttackPattern

### boss
```csharp
private BossBird boss
```


#### Field Value
**Type:** Global.BossBird

### boss_activated
```csharp
private bool boss_activated
```


#### Field Value
**Type:** System.Boolean

### changeTargetFreq
```csharp
private const float changeTargetFreq = 3
```


#### Field Value
**Type:** System.Single

### changeTargetTimer
```csharp
private Timer changeTargetTimer
```


#### Field Value
**Type:** Global.Timer

### currentAttackedDamage
```csharp
private float currentAttackedDamage
```


#### Field Value
**Type:** System.Single

### distanceRange
```csharp
private const float distanceRange = 1.7
```


#### Field Value
**Type:** System.Single

### elevatorBlockTime
```csharp
private const float elevatorBlockTime = 10
```


#### Field Value
**Type:** System.Single

### elevatorEscapeTimer
```csharp
private Timer elevatorEscapeTimer
```


#### Field Value
**Type:** Global.Timer

### encountered
```csharp
private List<WorkerModel> encountered
```


#### Field Value
**Type:** System.Collections.Generic.List{WorkerModel}

### escapePattern
```csharp
private SmallBird.EscapePattern escapePattern
```

#### Field Value
**Type:** Global.SmallBird.EscapePattern

### escapeProb
```csharp
private const float escapeProb = 0.2
```


#### Field Value
**Type:** System.Single

### FactionCode
```csharp
private const string FactionCode = "11"
```


#### Field Value
**Type:** System.String

### isAttacking
```csharp
private bool isAttacking
```


#### Field Value
**Type:** System.Boolean

### madDmgMax
```csharp
private const float madDmgMax = 1200
```


#### Field Value
**Type:** System.Single

### madDmgMin
```csharp
private const float madDmgMin = 800
```


#### Field Value
**Type:** System.Single

### madMode
```csharp
private bool madMode
```


#### Field Value
**Type:** System.Boolean

### mentalHealMax
```csharp
private const float mentalHealMax = 5
```


#### Field Value
**Type:** System.Single

### mentalHealMin
```csharp
private const float mentalHealMin = 3
```


#### Field Value
**Type:** System.Single

### oldTargetNode
```csharp
private MapNode oldTargetNode
```


#### Field Value
**Type:** Global.MapNode

### redDmgMax
```csharp
private const float redDmgMax = 1
```


#### Field Value
**Type:** System.Single

### redDmgMin
```csharp
private const float redDmgMin = 1
```


#### Field Value
**Type:** System.Single

### returnCommandActivated
```csharp
private bool returnCommandActivated
```


#### Field Value
**Type:** System.Boolean

### targetAgent
```csharp
private AgentModel targetAgent
```


#### Field Value
**Type:** Global.AgentModel

### totalDmgMax
```csharp
private const int totalDmgMax = 12
```


#### Field Value
**Type:** System.Int32

### totalDmgMin
```csharp
private const int totalDmgMin = 8
```


#### Field Value
**Type:** System.Int32

## Properties
### animScript
```csharp
public SmallBirdAnim animScript { get; }
```

#### Property Value
**Type:** Global.SmallBirdAnim

### Boss
```csharp
public BossBird Boss { get; }
```

#### Property Value
**Type:** Global.BossBird

### Boss_Activated
```csharp
public bool Boss_Activated { get; }
```

#### Property Value
**Type:** System.Boolean

### madDmg
```csharp
private static float madDmg { get; }
```

#### Property Value
**Type:** System.Single

### mentalHeal
```csharp
private static float mentalHeal { get; }
```

#### Property Value
**Type:** System.Single

### OtherBirdState
```csharp
public BossBird.OtherBirdState OtherBirdState { get; }
```

#### Property Value
**Type:** Global.BossBird.OtherBirdState

### redDmg
```csharp
private static float redDmg { get; }
```

#### Property Value
**Type:** System.Single

### totalDmg
```csharp
private static int totalDmg { get; }
```

#### Property Value
**Type:** System.Int32

## Methods
### ActivateQliphothCounter()
```csharp
public override void ActivateQliphothCounter()
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

### CheckDistance()
```csharp
private bool CheckDistance()
```


#### Returns
**Type:** System.Boolean

### CheckNearWorkerEncounting(out List<WorkerModel>)
```csharp
public List<AgentModel> CheckNearWorkerEncounting(out List<WorkerModel> nearWorkers)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `nearWorkers` | `System.Collections.Generic.List{WorkerModel}` |  |

#### Returns
**Type:** System.Collections.Generic.List{AgentModel}

### EndAttack()
```csharp
public void EndAttack()
```


### Escape()
```csharp
public override void Escape()
```


### GiveDamage()
```csharp
public void GiveDamage()
```


### HasUniqueFaction()
```csharp
public override bool HasUniqueFaction()
```


#### Returns
**Type:** System.Boolean

### IsAttackTargetable()
```csharp
public override bool IsAttackTargetable()
```


#### Returns
**Type:** System.Boolean

### IsAutoSuppressable()
```csharp
public override bool IsAutoSuppressable()
```


#### Returns
**Type:** System.Boolean

### IsSuppressable()
```csharp
public override bool IsSuppressable()
```


#### Returns
**Type:** System.Boolean

### MadRelease()
```csharp
public void MadRelease()
```


### MakeExplodeEffect(UnitDirection, WorkerModel, float)
```csharp
public void MakeExplodeEffect(UnitDirection dir, WorkerModel target, float size)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `dir` | `Global.UnitDirection` |  |
| `target` | `Global.WorkerModel` |  |
| `size` | `System.Single` |  |

### MakeMovement()
```csharp
private void MakeMovement()
```


### MakeMoveToGate(MapNode)
```csharp
public void MakeMoveToGate(MapNode dest)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `dest` | `Global.MapNode` |  |

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

### OnArrivedAndHide()
```csharp
public void OnArrivedAndHide()
```


### OnBossActivate()
```csharp
public void OnBossActivate()
```


### OnBossSuppressed()
```csharp
public void OnBossSuppressed()
```


### OnEnterRoom(UseSkill)
```csharp
public override void OnEnterRoom(UseSkill skill)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

### OnGateSuppressed()
```csharp
public void OnGateSuppressed()
```


### OnInit()
```csharp
public override void OnInit()
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

### OnOpenCollectionWindow()
```csharp
public override bool OnOpenCollectionWindow()
```


#### Returns
**Type:** System.Boolean

### OnReturn()
```csharp
public override void OnReturn()
```


### OnStageRelease()
```csharp
public override void OnStageRelease()
```


### OnStageStart()
```csharp
public override void OnStageStart()
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


### ReturnCommand()
```csharp
private void ReturnCommand()
```


### ReturnExecute()
```csharp
private void ReturnExecute()
```


### SetBoss(BossBird)
```csharp
public void SetBoss(BossBird boss)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `boss` | `Global.BossBird` |  |

### SetDirection(MovableObjectNode)
```csharp
private void SetDirection(MovableObjectNode targetNode)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `targetNode` | `Global.MovableObjectNode` |  |

### SetObserver(bool)
```csharp
public void SetObserver(bool activate)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `activate` | `System.Boolean` |  |

### SetPattern(EscapePattern)
```csharp
private void SetPattern(SmallBird.EscapePattern pattern)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `pattern` | `Global.SmallBird.EscapePattern` |  |

### StartAttackProcess(AttackPattern)
```csharp
private void StartAttackProcess(SmallBird.AttackPattern pattern)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `pattern` | `Global.SmallBird.AttackPattern` |  |

### StartMadMode(AgentModel)
```csharp
private void StartMadMode(AgentModel target)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.AgentModel` |  |

### StopMovement()
```csharp
private void StopMovement()
```


### UniqueEscape()
```csharp
public override void UniqueEscape()
```


## Inherited Members
[isolateSpriteSrc](/api/Global/Abnormalities/CreatureBase/CreatureBase#isolatespritesrc), [model](/api/Global/Abnormalities/CreatureBase/CreatureBase#model), [skill](/api/Global/Abnormalities/CreatureBase/CreatureBase#skill), [kitEvent](/api/Global/Abnormalities/CreatureBase/CreatureBase#kitevent), [hasUniqueEscapeLogic](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueescapelogic), [isWorkAllocated](/api/Global/Abnormalities/CreatureBase/CreatureBase#isworkallocated), [_allocatedAgent](/api/Global/Abnormalities/CreatureBase/CreatureBase#allocatedagent), [damage](/api/Global/Abnormalities/CreatureBase/CreatureBase#damage), [OnReleaseSpecialTip](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleasespecialtip), [specialSkillTipParamList](/api/Global/Abnormalities/CreatureBase/CreatureBase#specialskilltipparamlist), [_check](/api/Global/Abnormalities/CreatureBase/CreatureBase#check), [SetModel(CreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#setmodel-creaturemodel), [OnViewInitPrev(CreatureUnit)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onviewinitprev-creatureunit), [OnFixedUpdate(CreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfixedupdate-creaturemodel), [OnFixedUpdateInSkill(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfixedupdateinskill-useskill), [OnSkillFailWorkTick(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillfailworktick-useskill), [OnSkillSuccessWorkTick(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillsuccessworktick-useskill), [OnSkillTickUpdate(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskilltickupdate-useskill), [OnSkillGoalComplete(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillgoalcomplete-useskill), [PermitCancelCurrentWork()](/api/Global/Abnormalities/CreatureBase/CreatureBase#permitcancelcurrentwork), [GetKitCreatureProcessTime()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getkitcreatureprocesstime), [OnBonusWorkProb()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onbonusworkprob), [GetDamageMultiplierInWork(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdamagemultiplierinwork-useskill), [TranformWorkProb(float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#tranformworkprob-float), [OnReleaseWork(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleasework-useskill), [OnFinishWork(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfinishwork-useskill), [GetSpecialSkill()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getspecialskill), [GetDebugText()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdebugtext), [OnTimerEnd()](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontimerend), [MakeEffect(IsolateRoom, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffect-isolateroom-int), [MakeEffectAlter(IsolateRoom, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectalter-isolateroom-int), [Prob(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#prob-int), [isAttackInWorkProcess()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isattackinworkprocess), [OnAttackInWorkProcess(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onattackinworkprocess-useskill), [AttackProcess(UnitModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#attackprocess-unitmodel), [AutoFeelingDown()](/api/Global/Abnormalities/CreatureBase/CreatureBase#autofeelingdown), [AgentAnimCalled(int, WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#agentanimcalled-int-workermodel), [MakingEffect(string, float, string, Transform, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float-string-transform-int), [MakingEffect(string, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float), [MakeEffectAttachedToHead(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectattachedtohead-string), [MakingEffect(string, float, string, Vector3, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float-string-vector3-int), [OnAgentWorkEndAnimationPlayed(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentworkendanimationplayed-useskill), [OnAgentAllocateWork(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentallocatework-agentmodel), [OnSuppressed()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onsuppressed), [OnAllocatedWork(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onallocatedwork-agentmodel), [OnReleaseWorkAllocated()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleaseworkallocated), [ObserveLevelChangeForSpecialSkillTip()](/api/Global/Abnormalities/CreatureBase/CreatureBase#observelevelchangeforspecialskilltip), [OnObserveLevelChanged()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onobservelevelchanged), [HasUniqueProcessWorkNarration()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueprocessworknarration), [UniqueProcessWorkNarration(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniqueprocessworknarration-useskill), [RoomSpriteInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomspriteinit), [RoomEscapeSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomescapespriteon), [RoomEscapeSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomescapespriteoff), [RoomSkillSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomskillspriteon), [RoomSkillSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomskillspriteoff), [RoomStateSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomstatespriteon), [RoomStateSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomstatespriteoff), [OnForceSpecialSkillTipReveal(string, params object[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onforcespecialskilltipreveal-string-params-object), [OnWorkReleaseSpeicalSkillTipReveal(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkreleasespeicalskilltipreveal-string), [OnWorkReleaseTipUpdate(params object[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkreleasetipupdate-params-object), [OnAgentAnimatorReseted()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentanimatorreseted), [SpecialEnergyTick()](/api/Global/Abnormalities/CreatureBase/CreatureBase#specialenergytick), [OnStageEnd()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onstageend), [OnFeverTimeOver()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfevertimeover), [OnOverlayIsolateWork()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onoverlayisolatework), [OnOverlayIsolateObserve()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onoverlayisolateobserve), [OnOpenObserveWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopenobservewindow), [OnOpenWorkWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopenworkwindow), [DelayAttackMotion(float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#delayattackmotion-float), [GetRealTargets()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getrealtargets), [HasScriptSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasscriptsavedata), [GetSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getsavedata), [LoadData(Dictionary<string, object>)](/api/Global/Abnormalities/CreatureBase/CreatureBase#loaddata-dictionary-string-object), [LoadScriptData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#loadscriptdata), [SaveScriptData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#savescriptdata), [ExistSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#existsavedata), [RemoveSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#removesavedata), [ReplaceCommand(CreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#replacecommand-creaturemodel), [OnGamemanagerInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#ongamemanagerinit), [MakeEffectGlobalPos(string, Vector3)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectglobalpos-string-vector3), [MakeEffectGlobalPosNonTrans(string, Vector3)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectglobalposnontrans-string-vector3), [CanObservedByAgent(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#canobservedbyagent-agentmodel), [MakeSound(string, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string-float), [MakeSound(string, AudioRolloffMode)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string-audiorolloffmode), [MakeSoundQueue(params string[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesoundqueue-params-string), [MakeSoundLoop(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesoundloop-string), [OnViewDestroy()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onviewdestroy), [IsWorkable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isworkable), [HasUniqueMaxObservationFinish()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquemaxobservationfinish), [UniqueMaxObservationFinish(Desc)](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquemaxobservationfinish-desc), [OnChildSuppressed(ChildCreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onchildsuppressed-childcreaturemodel), [MakeChildCreature(UnitModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makechildcreature-unitmodel), [OnKillWorker(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onkillworker-workermodel), [GenPursueCommandAlter(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#genpursuecommandalter-workermodel), [OnAfterSuppressed()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onaftersuppressed), [hasUniqueDeadScene()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquedeadscene), [SetHpSlider(Slider)](/api/Global/Abnormalities/CreatureBase/CreatureBase#sethpslider-slider), [SetCastingSlider(Slider)](/api/Global/Abnormalities/CreatureBase/CreatureBase#setcastingslider-slider), [HasUniqueAttackDealy()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueattackdealy), [OnTakePhysicalDamage(UnitModel, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontakephysicaldamage-unitmodel-float), [OnWorkerPanic(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkerpanic-workermodel), [OnSelectMaxObservation(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onselectmaxobservation-int), [OnLoadCreatureName(ref string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onloadcreaturename-ref-string), [IsSuppressableByRoom()](/api/Global/Abnormalities/CreatureBase/CreatureBase#issuppressablebyroom), [OnWorkWindowSkillClicked(long)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkwindowskillclicked-long), [UseDefaultDamageIgnoreMessage(DamageTextEffect)](/api/Global/Abnormalities/CreatureBase/CreatureBase#usedefaultdamageignoremessage-damagetexteffect), [OnWorkAllocated(SkillTypeInfo, AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkallocated-skilltypeinfo-agentmodel), [GetPhysicalDamage(out float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getphysicaldamage-out-float), [GetMentalDamage(out float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getmentaldamage-out-float), [OnSuperArmorBreak()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onsuperarmorbreak), [UniqueStunEffect()](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquestuneffect), [HasEscapeUI()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasescapeui), [HasRoomCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasroomcounter), [RoomCounterInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomcounterinit), [ResetQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#resetqliphothcounter), [GetMaxWorkCountView()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getmaxworkcountview), [GetQliphothCounterMax()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getqliphothcountermax), [ReducedQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#reducedqliphothcounter), [AddedQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#addedqliphothcounter), [OnTakeDamage(UnitModel, DamageInfo, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontakedamage-unitmodel-damageinfo-float), [GetRadius()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getradius), [OnElevatorStuck()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onelevatorstuck), [OnWorkClosed(UseSkill, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkclosed-useskill-int), [IsActivatedWorkDesc()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isactivatedworkdesc), [IsSensoredInPassage()](/api/Global/Abnormalities/CreatureBase/CreatureBase#issensoredinpassage), [IsIndirectSuppressable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isindirectsuppressable), [GetRiskLevel()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getrisklevel), [GetName()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getname), [UniqueMoveControl()](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquemovecontrol), [HasUniqueName()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquename), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdamagefactor-unitmodel-damageinfo), [OnInitialBuild()](/api/Global/Abnormalities/CreatureBase/CreatureBase#oninitialbuild), [HasUniqueCollectionCost(string, out string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquecollectioncost-string-out-string), [OnOpenCommandWindow(Button[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopencommandwindow-button), [HasUniqueCommandAction(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquecommandaction-int), [HasUniqueWorkSelect(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueworkselect-int), [ForcelySuccess(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#forcelysuccess-useskill), [ForcelyFail(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#forcelyfail-useskill), [TryRabbitTeleport(MapNode)](/api/Global/Abnormalities/CreatureBase/CreatureBase#tryrabbitteleport-mapnode), [CanEnterRoom()](/api/Global/Abnormalities/CreatureBase/CreatureBase#canenterroom), [AllocatedAgent](/api/Global/Abnormalities/CreatureBase/CreatureBase#allocatedagent), [skillTriggerCheck](/api/Global/Abnormalities/CreatureBase/CreatureBase#skilltriggercheck), [Unit](/api/Global/Abnormalities/CreatureBase/CreatureBase#unit), [GetSaveSrc](/api/Global/Abnormalities/CreatureBase/CreatureBase#getsavesrc), [movable](/api/Global/Abnormalities/CreatureBase/CreatureBase#movable), [currentPassage](/api/Global/Abnormalities/CreatureBase/CreatureBase#currentpassage), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)







