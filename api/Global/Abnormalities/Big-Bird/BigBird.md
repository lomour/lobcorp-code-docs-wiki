---
uid: Global.BigBird
canonical_path: /api/Global/Misc/BigBird
---
# Class BigBird
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BigBird : BirdCreatureBase, IBirdControl, IObserver
```
> This section may have incomplete or incorrect information.
{.is-warning}


Big Bird. 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase](/api/Global/Abnormalities/Apocalypse-Bird/BirdCreatureBase) → BigBird

## Implements
[IBirdControl](/api/Global/Notices/IObserver)

## Constructors
### BigBird()
```csharp
public BigBird()
```

## Fields
### _agentDeadSceneHpConditionRatio
```csharp
private const float _agentDeadSceneHpConditionRatio = 0.3
```


#### Field Value
**Type:** System.Single

### _animScript
```csharp
private BigBirdAnim _animScript
```


#### Field Value
**Type:** Global.BigBirdAnim

### _attractCoolTimeMax
```csharp
private const float _attractCoolTimeMax = 12
```


#### Field Value
**Type:** System.Single

### _attractCoolTimeMin
```csharp
private const float _attractCoolTimeMin = 10
```


#### Field Value
**Type:** System.Single

### _attractInitTimeMax
```csharp
private const float _attractInitTimeMax = 7
```


#### Field Value
**Type:** System.Single

### _attractInitTimeMin
```csharp
private const float _attractInitTimeMin = 5
```


#### Field Value
**Type:** System.Single

### _attractOfficerProb
```csharp
private const int _attractOfficerProb = 40
```


#### Field Value
**Type:** System.Int32

### _attractTimeMax
```csharp
private const float _attractTimeMax = 5
```


#### Field Value
**Type:** System.Single

### _attractTimeMin
```csharp
private const float _attractTimeMin = 3
```


#### Field Value
**Type:** System.Single

### _cameraSensingScale
```csharp
private const float _cameraSensingScale = 2
```


#### Field Value
**Type:** System.Single

### _deadSceneRangeMax
```csharp
private const float _deadSceneRangeMax = 2.75
```


#### Field Value
**Type:** System.Single

### _deadSceneRangeMin
```csharp
private const float _deadSceneRangeMin = 0
```


#### Field Value
**Type:** System.Single

### _defaultSpeed
```csharp
private const float _defaultSpeed = 1.5
```


#### Field Value
**Type:** System.Single

### _effect_boom
```csharp
private const string _effect_boom = "BigBirdAgentDeadEffect"
```


#### Field Value
**Type:** System.String

### _effect_src
```csharp
private const string _effect_src = "Effect/Creature/BigBird/"
```


#### Field Value
**Type:** System.String

### _escapeCoolTimeMax
```csharp
private const float _escapeCoolTimeMax = 40
```


#### Field Value
**Type:** System.Single

### _escapeCoolTimeMin
```csharp
private const float _escapeCoolTimeMin = 30
```


#### Field Value
**Type:** System.Single

### _motionDelayMax
```csharp
private const float _motionDelayMax = 1.2
```


#### Field Value
**Type:** System.Single

### _motionDelayMin
```csharp
private const float _motionDelayMin = 0.8
```


#### Field Value
**Type:** System.Single

### _officeDeadSceneProb
```csharp
private const int _officeDeadSceneProb = 30
```


#### Field Value
**Type:** System.Int32

### _otherBirdState
```csharp
private BossBird.OtherBirdState _otherBirdState
```


#### Field Value
**Type:** Global.BossBird.OtherBirdState

### _qliphothMax
```csharp
private const int _qliphothMax = 5
```


#### Field Value
**Type:** System.Int32

### _sound_attract
```csharp
private const string _sound_attract = "attract"
```


#### Field Value
**Type:** System.String

### _sound_dead1
```csharp
private const string _sound_dead1 = "dead1"
```


#### Field Value
**Type:** System.String

### _sound_dead2
```csharp
private const string _sound_dead2 = "dead2"
```


#### Field Value
**Type:** System.String

### _sound_walk
```csharp
private const string _sound_walk = "walk"
```


#### Field Value
**Type:** System.String

### _specialSpeed
```csharp
private const float _specialSpeed = 2.5
```


#### Field Value
**Type:** System.Single

### _subQliphothCondition
```csharp
private const int _subQliphothCondition = 5
```


#### Field Value
**Type:** System.Int32

### alive
```csharp
private List<OfficerModel> alive
```


#### Field Value
**Type:** System.Collections.Generic.List{OfficerModel}

### attractCoolTimer
```csharp
private Timer attractCoolTimer
```


#### Field Value
**Type:** Global.Timer

### attracted
```csharp
private List<WorkerModel> attracted
```


#### Field Value
**Type:** System.Collections.Generic.List{WorkerModel}

### attractTimer
```csharp
private Timer attractTimer
```


#### Field Value
**Type:** Global.Timer

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

### cameraSensored
```csharp
private bool cameraSensored
```


#### Field Value
**Type:** System.Boolean

### dead
```csharp
private List<WorkerModel> dead
```


#### Field Value
**Type:** System.Collections.Generic.List{WorkerModel}

### deadCnt
```csharp
private int deadCnt
```


#### Field Value
**Type:** System.Int32

### deadScene
```csharp
private Queue<WorkerModel> deadScene
```


#### Field Value
**Type:** System.Collections.Generic.Queue{WorkerModel}

### escapeCoolTimer
```csharp
private Timer escapeCoolTimer
```


#### Field Value
**Type:** Global.Timer

### motionDelayTimer
```csharp
private Timer motionDelayTimer
```


#### Field Value
**Type:** Global.Timer

### moveTarget
```csharp
private WorkerModel moveTarget
```


#### Field Value
**Type:** Global.WorkerModel

### observingDanger
```csharp
private bool observingDanger
```


#### Field Value
**Type:** System.Boolean

### oldPassage
```csharp
private PassageObjectModel oldPassage
```


#### Field Value
**Type:** Global.PassageObjectModel

### prevSefira
```csharp
private Sefira prevSefira
```


#### Field Value
**Type:** Global.Sefira

### sensing
```csharp
private CreatureBase.SensingModule sensing
```

#### Field Value
**Type:** Global.CreatureBase.SensingModule

## Properties
### animScript
```csharp
public BigBirdAnim animScript { get; }
```

#### Property Value
**Type:** Global.BigBirdAnim

### attractCoolTime
```csharp
private static float attractCoolTime { get; }
```

#### Property Value
**Type:** System.Single

### attractInitTime
```csharp
private static float attractInitTime { get; }
```

#### Property Value
**Type:** System.Single

### attractTime
```csharp
private static float attractTime { get; }
```

#### Property Value
**Type:** System.Single

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

### escapeCoolTime
```csharp
private static float escapeCoolTime { get; }
```

#### Property Value
**Type:** System.Single

### InstanceID
```csharp
public Guid InstanceID { get; private set; }
```


#### Property Value
**Type:** System.Guid

### motionDelay
```csharp
private static float motionDelay { get; }
```

#### Property Value
**Type:** System.Single

### OtherBirdState
```csharp
public BossBird.OtherBirdState OtherBirdState { get; }
```

#### Property Value
**Type:** Global.BossBird.OtherBirdState

### rect
```csharp
private RectTransform rect { get; }
```

#### Property Value
**Type:** UnityEngine.RectTransform

### sensor
```csharp
private Camera sensor { get; }
```

#### Property Value
**Type:** UnityEngine.Camera

## Methods
### ActivateQliphothCounter()
```csharp
public override void ActivateQliphothCounter()
```


### AgentDeadScene()
```csharp
private void AgentDeadScene()
```


### Attract(WorkerModel)
```csharp
private void Attract(WorkerModel target)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |

### CancelAttract()
```csharp
public void CancelAttract()
```


### CancelAttract(WorkerModel)
```csharp
public void CancelAttract(WorkerModel worker)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

### CancelCast()
```csharp
private void CancelCast()
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

### CheckAttractCondition(WorkerModel)
```csharp
private bool CheckAttractCondition(WorkerModel worker)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

#### Returns
**Type:** System.Boolean

### CheckDeadScene()
```csharp
private void CheckDeadScene()
```


### Escape()
```csharp
public override void Escape()
```


### GetDistance(WorkerModel)
```csharp
private float GetDistance(WorkerModel target)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |

#### Returns
**Type:** System.Single

### GetMoveTarget()
```csharp
private WorkerModel GetMoveTarget()
```


#### Returns
**Type:** Global.WorkerModel

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

### GetWorkersInRange(float, float, bool)
```csharp
private List<WorkerModel> GetWorkersInRange(float rangeMax, float rangeMin = 0, bool hasDir = true)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `rangeMax` | `System.Single` |  |
| `rangeMin` | `System.Single` |  |
| `hasDir` | `System.Boolean` |  |

#### Returns
**Type:** System.Collections.Generic.List{WorkerModel}

### GetWorkersInSefira(Sefira, ref List<AgentModel>, ref List<OfficerModel>)
```csharp
private bool GetWorkersInSefira(Sefira sefira, ref List<AgentModel> agents, ref List<OfficerModel> officers)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.Sefira` |  |
| `agents` | `System.Collections.Generic.List{AgentModel}` |  |
| `officers` | `System.Collections.Generic.List{OfficerModel}` |  |

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

### IsCasting()
```csharp
private bool IsCasting()
```


#### Returns
**Type:** System.Boolean

### IsHostile(WorkerModel)
```csharp
private bool IsHostile(WorkerModel worker)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

#### Returns
**Type:** System.Boolean

### IsInDeadScene()
```csharp
private bool IsInDeadScene()
```


#### Returns
**Type:** System.Boolean

### IsInRange(WorkerModel, float, float, bool)
```csharp
private bool IsInRange(WorkerModel target, float rangeMax, float rangeMin = 0, bool hasDir = true)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |
| `rangeMax` | `System.Single` |  |
| `rangeMin` | `System.Single` |  |
| `hasDir` | `System.Boolean` |  |

#### Returns
**Type:** System.Boolean

### IsSuppressable()
```csharp
public override bool IsSuppressable()
```


#### Returns
**Type:** System.Boolean

### MakeAgentDeadEffect(WorkerModel, string)
```csharp
private GameObject MakeAgentDeadEffect(WorkerModel worker, string src)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |
| `src` | `System.String` |  |

#### Returns
**Type:** UnityEngine.GameObject

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

### MakeSefiraBrightly(Sefira)
```csharp
private void MakeSefiraBrightly(Sefira targetSefira)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `targetSefira` | `Global.Sefira` |  |

### MakeSefiraDarkly(Sefira)
```csharp
public void MakeSefiraDarkly(Sefira targetSefira)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `targetSefira` | `Global.Sefira` |  |

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

### MakeSound(string, float)
```csharp
public override SoundEffectPlayer MakeSound(string src, float vol)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |
| `vol` | `System.Single` |  |

#### Returns
**Type:** Global.SoundEffectPlayer

### MoveTargetable(WorkerModel)
```csharp
private bool MoveTargetable(WorkerModel worker)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

#### Returns
**Type:** System.Boolean

### OnAfterSuppressed()
```csharp
public override bool OnAfterSuppressed()
```


#### Returns
**Type:** System.Boolean

### OnAgentAnimCalled(int)
```csharp
public void OnAgentAnimCalled(int i)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### OnArrivedAndHide()
```csharp
public void OnArrivedAndHide()
```


### OnAttractSound()
```csharp
public void OnAttractSound()
```


### OnBossActivate()
```csharp
public void OnBossActivate()
```


### OnBossSuppressed()
```csharp
public void OnBossSuppressed()
```


### OnDeadSceneSound_1()
```csharp
public void OnDeadSceneSound_1()
```


### OnDeadSceneSound_2()
```csharp
public void OnDeadSceneSound_2()
```


### OnEndCast()
```csharp
public void OnEndCast()
```


### OnEndDeadScene()
```csharp
public void OnEndDeadScene()
```


### OnFixedUpdate(CreatureModel)
```csharp
public override void OnFixedUpdate(CreatureModel creature)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |

### OnGateSuppressed()
```csharp
public void OnGateSuppressed()
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


### OnStep()
```csharp
public void OnStep()
```


### OnViewInit(CreatureUnit)
```csharp
public override void OnViewInit(CreatureUnit unit)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.CreatureUnit` |  |

### ParamInit()
```csharp
public override void ParamInit()
```


### SetBoss(BossBird)
```csharp
public void SetBoss(BossBird boss)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `boss` | `Global.BossBird` |  |

### SetObserver(bool)
```csharp
private void SetObserver(bool active)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `active` | `System.Boolean` |  |

### StartCast()
```csharp
private void StartCast()
```


### StartDeadScene(WorkerModel)
```csharp
private void StartDeadScene(WorkerModel target)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |

### StopMovement()
```csharp
private void StopMovement()
```


### SuccessCast()
```csharp
private void SuccessCast()
```


### TryAttract(out WorkerModel)
```csharp
private bool TryAttract(out WorkerModel target)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |

#### Returns
**Type:** System.Boolean

### UniqueEscape()
```csharp
public override void UniqueEscape()
```


## Inherited Members
[isolateSpriteSrc](/api/Global/Abnormalities/CreatureBase/CreatureBase#isolatespritesrc), [model](/api/Global/Abnormalities/CreatureBase/CreatureBase#model), [skill](/api/Global/Abnormalities/CreatureBase/CreatureBase#skill), [kitEvent](/api/Global/Abnormalities/CreatureBase/CreatureBase#kitevent), [hasUniqueEscapeLogic](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueescapelogic), [isWorkAllocated](/api/Global/Abnormalities/CreatureBase/CreatureBase#isworkallocated), [_allocatedAgent](/api/Global/Abnormalities/CreatureBase/CreatureBase#allocatedagent), [damage](/api/Global/Abnormalities/CreatureBase/CreatureBase#damage), [OnReleaseSpecialTip](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleasespecialtip), [specialSkillTipParamList](/api/Global/Abnormalities/CreatureBase/CreatureBase#specialskilltipparamlist), [_check](/api/Global/Abnormalities/CreatureBase/CreatureBase#check), [SetModel(CreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#setmodel-creaturemodel), [OnInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#oninit), [OnViewInitPrev(CreatureUnit)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onviewinitprev-creatureunit), [OnFixedUpdateInSkill(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfixedupdateinskill-useskill), [OnSkillFailWorkTick(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillfailworktick-useskill), [OnSkillSuccessWorkTick(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillsuccessworktick-useskill), [OnSkillTickUpdate(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskilltickupdate-useskill), [OnSkillGoalComplete(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillgoalcomplete-useskill), [PermitCancelCurrentWork()](/api/Global/Abnormalities/CreatureBase/CreatureBase#permitcancelcurrentwork), [GetKitCreatureProcessTime()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getkitcreatureprocesstime), [OnBonusWorkProb()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onbonusworkprob), [GetDamageMultiplierInWork(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdamagemultiplierinwork-useskill), [TranformWorkProb(float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#tranformworkprob-float), [OnEnterRoom(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onenterroom-useskill), [OnFinishWork(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfinishwork-useskill), [OnWorkCoolTimeEnd(CreatureFeelingState)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkcooltimeend-creaturefeelingstate), [GetSpecialSkill()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getspecialskill), [GetDebugText()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdebugtext), [OnTimerEnd()](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontimerend), [MakeEffect(IsolateRoom, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffect-isolateroom-int), [MakeEffectAlter(IsolateRoom, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectalter-isolateroom-int), [Prob(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#prob-int), [isAttackInWorkProcess()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isattackinworkprocess), [OnAttackInWorkProcess(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onattackinworkprocess-useskill), [AttackProcess(UnitModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#attackprocess-unitmodel), [AutoFeelingDown()](/api/Global/Abnormalities/CreatureBase/CreatureBase#autofeelingdown), [AgentAnimCalled(int, WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#agentanimcalled-int-workermodel), [MakingEffect(string, float, string, Transform, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float-string-transform-int), [MakingEffect(string, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float), [MakeEffectAttachedToHead(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectattachedtohead-string), [MakingEffect(string, float, string, Vector3, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float-string-vector3-int), [OnAgentWorkEndAnimationPlayed(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentworkendanimationplayed-useskill), [OnAgentAllocateWork(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentallocatework-agentmodel), [OnSuppressed()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onsuppressed), [OnAllocatedWork(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onallocatedwork-agentmodel), [OnReleaseWorkAllocated()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleaseworkallocated), [ObserveLevelChangeForSpecialSkillTip()](/api/Global/Abnormalities/CreatureBase/CreatureBase#observelevelchangeforspecialskilltip), [OnObserveLevelChanged()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onobservelevelchanged), [HasUniqueProcessWorkNarration()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueprocessworknarration), [UniqueProcessWorkNarration(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniqueprocessworknarration-useskill), [RoomSpriteInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomspriteinit), [RoomEscapeSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomescapespriteon), [RoomEscapeSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomescapespriteoff), [RoomSkillSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomskillspriteon), [RoomSkillSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomskillspriteoff), [RoomStateSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomstatespriteon), [RoomStateSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomstatespriteoff), [OnForceSpecialSkillTipReveal(string, params object[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onforcespecialskilltipreveal-string-params-object), [OnWorkReleaseSpeicalSkillTipReveal(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkreleasespeicalskilltipreveal-string), [OnWorkReleaseTipUpdate(params object[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkreleasetipupdate-params-object), [OnAgentAnimatorReseted()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentanimatorreseted), [SpecialEnergyTick()](/api/Global/Abnormalities/CreatureBase/CreatureBase#specialenergytick), [OnFeverTimeOver()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfevertimeover), [OnOverlayIsolateWork()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onoverlayisolatework), [OnOverlayIsolateObserve()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onoverlayisolateobserve), [OnOpenObserveWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopenobservewindow), [OnOpenWorkWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopenworkwindow), [DelayAttackMotion(float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#delayattackmotion-float), [GetRealTargets()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getrealtargets), [HasScriptSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasscriptsavedata), [GetSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getsavedata), [LoadData(Dictionary<string, object>)](/api/Global/Abnormalities/CreatureBase/CreatureBase#loaddata-dictionary-string-object), [LoadScriptData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#loadscriptdata), [SaveScriptData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#savescriptdata), [ExistSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#existsavedata), [RemoveSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#removesavedata), [ReplaceCommand(CreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#replacecommand-creaturemodel), [OnGamemanagerInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#ongamemanagerinit), [MakeEffectGlobalPos(string, Vector3)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectglobalpos-string-vector3), [MakeEffectGlobalPosNonTrans(string, Vector3)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectglobalposnontrans-string-vector3), [CanObservedByAgent(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#canobservedbyagent-agentmodel), [MakeSound(string, AudioRolloffMode)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string-audiorolloffmode), [MakeSoundQueue(params string[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesoundqueue-params-string), [MakeSoundLoop(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesoundloop-string), [OnViewDestroy()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onviewdestroy), [IsWorkable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isworkable), [HasUniqueMaxObservationFinish()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquemaxobservationfinish), [UniqueMaxObservationFinish(Desc)](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquemaxobservationfinish-desc), [OnChildSuppressed(ChildCreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onchildsuppressed-childcreaturemodel), [MakeChildCreature(UnitModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makechildcreature-unitmodel), [OnKillWorker(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onkillworker-workermodel), [GenPursueCommandAlter(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#genpursuecommandalter-workermodel), [hasUniqueDeadScene()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquedeadscene), [SetHpSlider(Slider)](/api/Global/Abnormalities/CreatureBase/CreatureBase#sethpslider-slider), [SetCastingSlider(Slider)](/api/Global/Abnormalities/CreatureBase/CreatureBase#setcastingslider-slider), [HasUniqueAttackDealy()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueattackdealy), [OnTakePhysicalDamage(UnitModel, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontakephysicaldamage-unitmodel-float), [HasUniqueFaction()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquefaction), [OnWorkerPanic(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkerpanic-workermodel), [OnSelectMaxObservation(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onselectmaxobservation-int), [OnLoadCreatureName(ref string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onloadcreaturename-ref-string), [IsSuppressableByRoom()](/api/Global/Abnormalities/CreatureBase/CreatureBase#issuppressablebyroom), [OnWorkWindowSkillClicked(long)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkwindowskillclicked-long), [UseDefaultDamageIgnoreMessage(DamageTextEffect)](/api/Global/Abnormalities/CreatureBase/CreatureBase#usedefaultdamageignoremessage-damagetexteffect), [OnWorkAllocated(SkillTypeInfo, AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkallocated-skilltypeinfo-agentmodel), [GetPhysicalDamage(out float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getphysicaldamage-out-float), [GetMentalDamage(out float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getmentaldamage-out-float), [OnSuperArmorBreak()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onsuperarmorbreak), [UniqueStunEffect()](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquestuneffect), [HasEscapeUI()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasescapeui), [HasRoomCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasroomcounter), [RoomCounterInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomcounterinit), [ResetQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#resetqliphothcounter), [GetMaxWorkCountView()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getmaxworkcountview), [GetQliphothCounterMax()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getqliphothcountermax), [ReducedQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#reducedqliphothcounter), [AddedQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#addedqliphothcounter), [OnTakeDamage(UnitModel, DamageInfo, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontakedamage-unitmodel-damageinfo-float), [GetRadius()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getradius), [OnElevatorStuck()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onelevatorstuck), [OnWorkClosed(UseSkill, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkclosed-useskill-int), [IsActivatedWorkDesc()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isactivatedworkdesc), [IsSensoredInPassage()](/api/Global/Abnormalities/CreatureBase/CreatureBase#issensoredinpassage), [IsIndirectSuppressable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isindirectsuppressable), [GetRiskLevel()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getrisklevel), [GetName()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getname), [UniqueMoveControl()](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquemovecontrol), [HasUniqueName()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquename), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdamagefactor-unitmodel-damageinfo), [OnInitialBuild()](/api/Global/Abnormalities/CreatureBase/CreatureBase#oninitialbuild), [HasUniqueCollectionCost(string, out string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquecollectioncost-string-out-string), [OnOpenCommandWindow(Button[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopencommandwindow-button), [HasUniqueCommandAction(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquecommandaction-int), [HasUniqueWorkSelect(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueworkselect-int), [ForcelySuccess(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#forcelysuccess-useskill), [ForcelyFail(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#forcelyfail-useskill), [TryRabbitTeleport(MapNode)](/api/Global/Abnormalities/CreatureBase/CreatureBase#tryrabbitteleport-mapnode), [CanEnterRoom()](/api/Global/Abnormalities/CreatureBase/CreatureBase#canenterroom), [AllocatedAgent](/api/Global/Abnormalities/CreatureBase/CreatureBase#allocatedagent), [skillTriggerCheck](/api/Global/Abnormalities/CreatureBase/CreatureBase#skilltriggercheck), [Unit](/api/Global/Abnormalities/CreatureBase/CreatureBase#unit), [GetSaveSrc](/api/Global/Abnormalities/CreatureBase/CreatureBase#getsavesrc), [movable](/api/Global/Abnormalities/CreatureBase/CreatureBase#movable), [currentPassage](/api/Global/Abnormalities/CreatureBase/CreatureBase#currentpassage), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)








