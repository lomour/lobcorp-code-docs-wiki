---
uid: Global.PinkCorps
canonical_path: /api/Global/IOBserver/PinkCorps
---
# Class PinkCorps
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PinkCorps : CreatureBase, IObserver
```
> This section may have incomplete or incorrect information.
{.is-warning}


Army in Black.




## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase](/api/Global/Abnormalities/CreatureBase/CreatureBase) → PinkCorps

## Implements
[IObserver](/api/Global/Notices/IObserver)

## Constructors
### PinkCorps()
```csharp
public PinkCorps()
```

## Fields
### _blackCorpGenCount
```csharp
private const int _blackCorpGenCount = 4
```


#### Field Value
**Type:** System.Int32

### _blackCorps
```csharp
private Dictionary<long, PinkCorps.BlackCorpsData> _blackCorps
```

#### Field Value
**Type:** System.Collections.Generic.Dictionary{System.Int64,PinkCorps.BlackCorpsData}

### _corpState
```csharp
private PinkCorps.CorpsState _corpState
```

#### Field Value
**Type:** Global.PinkCorps.CorpsState

### _currentAttackEndAction
```csharp
private PinkCorps.PinkCorpsAction _currentAttackEndAction
```

#### Field Value
**Type:** Global.PinkCorps.PinkCorpsAction

### _currentSkillTarget
```csharp
private AgentModel _currentSkillTarget
```


#### Field Value
**Type:** Global.AgentModel

### _deadWorkers
```csharp
private List<WorkerModel> _deadWorkers
```


#### Field Value
**Type:** System.Collections.Generic.List{WorkerModel}

### _followMaxDistance
```csharp
private const float _followMaxDistance = 1
```


#### Field Value
**Type:** System.Single

### _isMoveAllowed
```csharp
private bool _isMoveAllowed
```


#### Field Value
**Type:** System.Boolean

### _patrolDelay
```csharp
private MinMax _patrolDelay
```


#### Field Value
**Type:** Global.MinMax

### _patrolDelayTimer
```csharp
private Timer _patrolDelayTimer
```


#### Field Value
**Type:** Global.Timer

### _protectionBufTime
```csharp
private const float _protectionBufTime = 120
```


#### Field Value
**Type:** System.Single

### _protectionBufTimer
```csharp
private Timer _protectionBufTimer
```


#### Field Value
**Type:** Global.Timer

### _recoverFreq
```csharp
private const float _recoverFreq = 10
```


#### Field Value
**Type:** System.Single

### _recoverHpValue
```csharp
private const float _recoverHpValue = 12
```


#### Field Value
**Type:** System.Single

### _recoverMentalValue
```csharp
private const float _recoverMentalValue = 12
```


#### Field Value
**Type:** System.Single

### _recoverTimer
```csharp
private Timer _recoverTimer
```


#### Field Value
**Type:** Global.Timer

### _removed
```csharp
private List<ChildCreatureModel> _removed
```


#### Field Value
**Type:** System.Collections.Generic.List{ChildCreatureModel}

### _state
```csharp
private PinkCorps.PinkCorpsState _state
```

#### Field Value
**Type:** Global.PinkCorps.PinkCorpsState

### _workerDeadCount
```csharp
private const int _workerDeadCount = 5
```


#### Field Value
**Type:** System.Int32

### _workerDeadCounter
```csharp
private int _workerDeadCounter
```


#### Field Value
**Type:** System.Int32

### loveBufLevel
```csharp
private const int loveBufLevel = 3
```


#### Field Value
**Type:** System.Int32

## Properties
### AnimScript
```csharp
public PinkCorpsAnim AnimScript { get; private set; }
```


#### Property Value
**Type:** Global.PinkCorpsAnim

### State
```csharp
public PinkCorps.PinkCorpsState State { get; set; }
```

#### Property Value
**Type:** Global.PinkCorps.PinkCorpsState

## Methods
### ActivateQliphothCounter()
```csharp
public override void ActivateQliphothCounter()
```


### ActivateSkill(AgentModel)
```csharp
private void ActivateSkill(AgentModel target)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.AgentModel` |  |

### AddBuf(AgentModel)
```csharp
private bool AddBuf(AgentModel target)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.AgentModel` |  |

#### Returns
**Type:** System.Boolean

### AddBufRoutine(AgentModel)
```csharp
private IEnumerator AddBufRoutine(AgentModel target)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.AgentModel` |  |

#### Returns
**Type:** System.Collections.IEnumerator

### ClearCorps()
```csharp
private void ClearCorps()
```


### CloseSkill()
```csharp
private void CloseSkill()
```


### EndSkill()
```csharp
public void EndSkill()
```


### ExecuteRequest(AgentModel)
```csharp
public void ExecuteRequest(AgentModel target)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.AgentModel` |  |

### FollowUpdate()
```csharp
private void FollowUpdate()
```


### GetBlackCorpsData(long, out BlackCorpsData)
```csharp
public bool GetBlackCorpsData(long id, out PinkCorps.BlackCorpsData output)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |
| `output` | `Global.PinkCorps.BlackCorpsData` |  |

#### Returns
**Type:** System.Boolean

### GetHealTargets()
```csharp
private List<WorkerModel> GetHealTargets()
```


#### Returns
**Type:** System.Collections.Generic.List{WorkerModel}

### GetRandomPassage(Sefira)
```csharp
private PassageObjectModel GetRandomPassage(Sefira sefira)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.Sefira` |  |

#### Returns
**Type:** Global.PassageObjectModel

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

### HasRoomCounter()
```csharp
public override bool HasRoomCounter()
```


#### Returns
**Type:** System.Boolean

### HasUniqueCommandAction(int)
```csharp
public override bool HasUniqueCommandAction(int workType)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `workType` | `System.Int32` |  |

#### Returns
**Type:** System.Boolean

### IsAutoSuppressable()
```csharp
public override bool IsAutoSuppressable()
```


#### Returns
**Type:** System.Boolean

### IsSensoredInPassage()
```csharp
public override bool IsSensoredInPassage()
```


#### Returns
**Type:** System.Boolean

### IsSuppressable()
```csharp
public override bool IsSuppressable()
```


#### Returns
**Type:** System.Boolean

### IsSuppressableByRoom()
```csharp
public override bool IsSuppressableByRoom()
```


#### Returns
**Type:** System.Boolean

### IsWorkable()
```csharp
public override bool IsWorkable()
```


#### Returns
**Type:** System.Boolean

### Log(string, bool)
```csharp
public static void Log(string log, bool isError = false)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `log` | `System.String` |  |
| `isError` | `System.Boolean` |  |

### MakeAppearEffect(MovableObjectNode)
```csharp
public void MakeAppearEffect(MovableObjectNode target)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.MovableObjectNode` |  |

### MakeBlackCorps()
```csharp
public void MakeBlackCorps()
```


### MakeChildCreature(UnitModel)
```csharp
public override ChildCreatureModel MakeChildCreature(UnitModel origin)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `origin` | `Global.UnitModel` |  |

#### Returns
**Type:** Global.ChildCreatureModel

### MakeHeartEffect(int, MovableObjectNode)
```csharp
public static GameObject MakeHeartEffect(int type, MovableObjectNode pivot)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `type` | `System.Int32` |  |
| `pivot` | `Global.MovableObjectNode` |  |

#### Returns
**Type:** UnityEngine.GameObject

### MakeRecoverHeartEffect()
```csharp
private void MakeRecoverHeartEffect()
```


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

### MakeTeleportEffect()
```csharp
public void MakeTeleportEffect()
```


### OnAttackEnd(int)
```csharp
public void OnAttackEnd(int attackType)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `attackType` | `System.Int32` |  |

### OnBlackCropsSuppressed(long)
```csharp
public void OnBlackCropsSuppressed(long id)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

### OnFixedUpdate(CreatureModel)
```csharp
public override void OnFixedUpdate(CreatureModel creature)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |

### OnNotice(string, params object[])
```csharp
public void OnNotice(string notice, params object[] param)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `notice` | `System.String` |  |
| `param` | `System.Object[]` |  |

### OnOpenCommandWindow(Button[])
```csharp
public override void OnOpenCommandWindow(Button[] buttons)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `buttons` | `UnityEngine.UI.Button[]` |  |

### OnOpenWorkWindow()
```csharp
public override bool OnOpenWorkWindow()
```


#### Returns
**Type:** System.Boolean

### OnReadyForTeleport()
```csharp
public void OnReadyForTeleport()
```


### OnReturn()
```csharp
public override void OnReturn()
```


### OnSetState(PinkCorpsState)
```csharp
public void OnSetState(PinkCorps.PinkCorpsState state)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `state` | `Global.PinkCorps.PinkCorpsState` |  |

### OnSkillGoalComplete(UseSkill)
```csharp
public override void OnSkillGoalComplete(UseSkill skill)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

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

### PatrolUpdate()
```csharp
private void PatrolUpdate()
```


### RecoverAnimEnd()
```csharp
public void RecoverAnimEnd()
```


### RecoverGlobal()
```csharp
public void RecoverGlobal()
```


### RecoverUpdate()
```csharp
private void RecoverUpdate()
```


### RequestReturn()
```csharp
public void RequestReturn()
```


### SetObserver(bool)
```csharp
private void SetObserver(bool listen)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `listen` | `System.Boolean` |  |

### SubDeadCounter()
```csharp
private void SubDeadCounter()
```


### TeleportNear(UnitModel)
```csharp
private void TeleportNear(UnitModel targetUnit)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `targetUnit` | `Global.UnitModel` |  |

### TeleportReturn()
```csharp
private void TeleportReturn()
```


### TryRequest()
```csharp
public void TryRequest()
```


## Inherited Members
[isolateSpriteSrc](/api/Global/Abnormalities/CreatureBase/CreatureBase#isolatespritesrc), [model](/api/Global/Abnormalities/CreatureBase/CreatureBase#model), [skill](/api/Global/Abnormalities/CreatureBase/CreatureBase#skill), [kitEvent](/api/Global/Abnormalities/CreatureBase/CreatureBase#kitevent), [hasUniqueEscapeLogic](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueescapelogic), [isWorkAllocated](/api/Global/Abnormalities/CreatureBase/CreatureBase#isworkallocated), [_allocatedAgent](/api/Global/Abnormalities/CreatureBase/CreatureBase#allocatedagent), [damage](/api/Global/Abnormalities/CreatureBase/CreatureBase#damage), [OnReleaseSpecialTip](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleasespecialtip), [specialSkillTipParamList](/api/Global/Abnormalities/CreatureBase/CreatureBase#specialskilltipparamlist), [_check](/api/Global/Abnormalities/CreatureBase/CreatureBase#check), [SetModel(CreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#setmodel-creaturemodel), [OnInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#oninit), [OnViewInitPrev(CreatureUnit)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onviewinitprev-creatureunit), [OnFixedUpdateInSkill(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfixedupdateinskill-useskill), [OnSkillFailWorkTick(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillfailworktick-useskill), [OnSkillSuccessWorkTick(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillsuccessworktick-useskill), [OnSkillTickUpdate(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskilltickupdate-useskill), [PermitCancelCurrentWork()](/api/Global/Abnormalities/CreatureBase/CreatureBase#permitcancelcurrentwork), [GetKitCreatureProcessTime()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getkitcreatureprocesstime), [OnBonusWorkProb()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onbonusworkprob), [GetDamageMultiplierInWork(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdamagemultiplierinwork-useskill), [TranformWorkProb(float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#tranformworkprob-float), [OnEnterRoom(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onenterroom-useskill), [OnReleaseWork(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleasework-useskill), [OnFinishWork(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfinishwork-useskill), [UniqueEscape()](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniqueescape), [Escape()](/api/Global/Abnormalities/CreatureBase/CreatureBase#escape), [GetSpecialSkill()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getspecialskill), [GetDebugText()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdebugtext), [OnTimerEnd()](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontimerend), [MakeEffect(IsolateRoom, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffect-isolateroom-int), [MakeEffectAlter(IsolateRoom, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectalter-isolateroom-int), [Prob(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#prob-int), [isAttackInWorkProcess()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isattackinworkprocess), [OnAttackInWorkProcess(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onattackinworkprocess-useskill), [AttackProcess(UnitModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#attackprocess-unitmodel), [AutoFeelingDown()](/api/Global/Abnormalities/CreatureBase/CreatureBase#autofeelingdown), [AgentAnimCalled(int, WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#agentanimcalled-int-workermodel), [MakingEffect(string, float, string, Transform, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float-string-transform-int), [MakingEffect(string, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float), [MakeEffectAttachedToHead(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectattachedtohead-string), [MakingEffect(string, float, string, Vector3, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float-string-vector3-int), [OnAgentWorkEndAnimationPlayed(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentworkendanimationplayed-useskill), [OnAgentAllocateWork(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentallocatework-agentmodel), [OnSuppressed()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onsuppressed), [OnAllocatedWork(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onallocatedwork-agentmodel), [OnReleaseWorkAllocated()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleaseworkallocated), [ObserveLevelChangeForSpecialSkillTip()](/api/Global/Abnormalities/CreatureBase/CreatureBase#observelevelchangeforspecialskilltip), [OnObserveLevelChanged()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onobservelevelchanged), [HasUniqueProcessWorkNarration()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueprocessworknarration), [UniqueProcessWorkNarration(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniqueprocessworknarration-useskill), [RoomSpriteInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomspriteinit), [RoomEscapeSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomescapespriteon), [RoomEscapeSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomescapespriteoff), [RoomSkillSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomskillspriteon), [RoomSkillSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomskillspriteoff), [RoomStateSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomstatespriteon), [RoomStateSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomstatespriteoff), [OnForceSpecialSkillTipReveal(string, params object[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onforcespecialskilltipreveal-string-params-object), [OnWorkReleaseSpeicalSkillTipReveal(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkreleasespeicalskilltipreveal-string), [OnWorkReleaseTipUpdate(params object[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkreleasetipupdate-params-object), [OnAgentAnimatorReseted()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentanimatorreseted), [SpecialEnergyTick()](/api/Global/Abnormalities/CreatureBase/CreatureBase#specialenergytick), [OnStageEnd()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onstageend), [OnFeverTimeOver()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfevertimeover), [OnOverlayIsolateWork()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onoverlayisolatework), [OnOverlayIsolateObserve()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onoverlayisolateobserve), [OnOpenObserveWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopenobservewindow), [OnOpenCollectionWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopencollectionwindow), [DelayAttackMotion(float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#delayattackmotion-float), [IsAttackTargetable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isattacktargetable), [GetRealTargets()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getrealtargets), [HasScriptSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasscriptsavedata), [GetSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getsavedata), [LoadData(Dictionary<string, object>)](/api/Global/Abnormalities/CreatureBase/CreatureBase#loaddata-dictionary-string-object), [LoadScriptData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#loadscriptdata), [SaveScriptData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#savescriptdata), [ExistSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#existsavedata), [RemoveSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#removesavedata), [ReplaceCommand(CreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#replacecommand-creaturemodel), [OnGamemanagerInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#ongamemanagerinit), [MakeEffectGlobalPos(string, Vector3)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectglobalpos-string-vector3), [MakeEffectGlobalPosNonTrans(string, Vector3)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectglobalposnontrans-string-vector3), [CanObservedByAgent(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#canobservedbyagent-agentmodel), [MakeSound(string, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string-float), [MakeSound(string, AudioRolloffMode)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string-audiorolloffmode), [MakeSoundQueue(params string[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesoundqueue-params-string), [MakeSoundLoop(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesoundloop-string), [OnViewDestroy()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onviewdestroy), [ParamInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#paraminit), [HasUniqueMaxObservationFinish()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquemaxobservationfinish), [UniqueMaxObservationFinish(Desc)](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquemaxobservationfinish-desc), [OnChildSuppressed(ChildCreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onchildsuppressed-childcreaturemodel), [OnKillWorker(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onkillworker-workermodel), [GenPursueCommandAlter(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#genpursuecommandalter-workermodel), [OnAfterSuppressed()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onaftersuppressed), [hasUniqueDeadScene()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquedeadscene), [SetHpSlider(Slider)](/api/Global/Abnormalities/CreatureBase/CreatureBase#sethpslider-slider), [SetCastingSlider(Slider)](/api/Global/Abnormalities/CreatureBase/CreatureBase#setcastingslider-slider), [HasUniqueAttackDealy()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueattackdealy), [CanTakeDamage(UnitModel, DamageInfo)](/api/Global/Abnormalities/CreatureBase/CreatureBase#cantakedamage-unitmodel-damageinfo), [OnTakePhysicalDamage(UnitModel, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontakephysicaldamage-unitmodel-float), [HasUniqueFaction()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquefaction), [OnWorkerPanic(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkerpanic-workermodel), [OnSelectMaxObservation(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onselectmaxobservation-int), [OnLoadCreatureName(ref string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onloadcreaturename-ref-string), [OnWorkWindowSkillClicked(long)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkwindowskillclicked-long), [UseDefaultDamageIgnoreMessage(DamageTextEffect)](/api/Global/Abnormalities/CreatureBase/CreatureBase#usedefaultdamageignoremessage-damagetexteffect), [OnWorkAllocated(SkillTypeInfo, AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkallocated-skilltypeinfo-agentmodel), [GetPhysicalDamage(out float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getphysicaldamage-out-float), [GetMentalDamage(out float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getmentaldamage-out-float), [OnSuperArmorBreak()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onsuperarmorbreak), [UniqueStunEffect()](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquestuneffect), [HasEscapeUI()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasescapeui), [RoomCounterInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomcounterinit), [ResetQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#resetqliphothcounter), [GetMaxWorkCountView()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getmaxworkcountview), [GetQliphothCounterMax()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getqliphothcountermax), [ReducedQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#reducedqliphothcounter), [AddedQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#addedqliphothcounter), [OnTakeDamage(UnitModel, DamageInfo, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontakedamage-unitmodel-damageinfo-float), [GetRadius()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getradius), [OnElevatorStuck()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onelevatorstuck), [OnWorkClosed(UseSkill, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkclosed-useskill-int), [IsActivatedWorkDesc()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isactivatedworkdesc), [IsIndirectSuppressable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isindirectsuppressable), [GetRiskLevel()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getrisklevel), [GetName()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getname), [UniqueMoveControl()](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquemovecontrol), [HasUniqueName()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquename), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdamagefactor-unitmodel-damageinfo), [OnInitialBuild()](/api/Global/Abnormalities/CreatureBase/CreatureBase#oninitialbuild), [HasUniqueCollectionCost(string, out string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquecollectioncost-string-out-string), [HasUniqueWorkSelect(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueworkselect-int), [ForcelySuccess(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#forcelysuccess-useskill), [ForcelyFail(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#forcelyfail-useskill), [TryRabbitTeleport(MapNode)](/api/Global/Abnormalities/CreatureBase/CreatureBase#tryrabbitteleport-mapnode), [CanEnterRoom()](/api/Global/Abnormalities/CreatureBase/CreatureBase#canenterroom), [AllocatedAgent](/api/Global/Abnormalities/CreatureBase/CreatureBase#allocatedagent), [skillTriggerCheck](/api/Global/Abnormalities/CreatureBase/CreatureBase#skilltriggercheck), [Unit](/api/Global/Abnormalities/CreatureBase/CreatureBase#unit), [GetSaveSrc](/api/Global/Abnormalities/CreatureBase/CreatureBase#getsavesrc), [movable](/api/Global/Abnormalities/CreatureBase/CreatureBase#movable), [currentPassage](/api/Global/Abnormalities/CreatureBase/CreatureBase#currentpassage), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)








