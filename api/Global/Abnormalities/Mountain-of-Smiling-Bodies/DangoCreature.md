---
uid: Global.DangoCreature
canonical_path: /api/Global/IOBserver/DangoCreature
---
# Class DangoCreature
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DangoCreature : CreatureBase, IObserver
```
> This section may have incomplete or incorrect information.
{.is-warning}


Mountain of Smiling Bodies.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase](/api/Global/Abnormalities/CreatureBase/CreatureBase) → DangoCreature

## Implements
[IObserver](/api/Global/Notices/IObserver)

## Constructors
### DangoCreature()
```csharp
public DangoCreature()
```

## Fields
### _animScript
```csharp
private DangoCreatureAnim _animScript
```


#### Field Value
**Type:** Global.DangoCreatureAnim

### _attackDelay
```csharp
private Timer _attackDelay
```


#### Field Value
**Type:** Global.Timer

### _attackDelayMax
```csharp
private const float _attackDelayMax = 1
```


#### Field Value
**Type:** System.Single

### _attackDelayMin
```csharp
private const float _attackDelayMin = 0.5
```


#### Field Value
**Type:** System.Single

### _currentAgentDead
```csharp
private int _currentAgentDead
```


#### Field Value
**Type:** System.Int32

### _dangoLevel
```csharp
private DangoCreature.Level _dangoLevel
```

#### Field Value
**Type:** Global.DangoCreature.Level

### _eatenCount
```csharp
private int _eatenCount
```


#### Field Value
**Type:** System.Int32

### _eatenUnit
```csharp
private List<UnitModel> _eatenUnit
```


#### Field Value
**Type:** System.Collections.Generic.List{UnitModel}

### _escapedSound
```csharp
private SoundEffectPlayer _escapedSound
```


#### Field Value
**Type:** Global.SoundEffectPlayer

### _escapedSoundFreqTimer
```csharp
private Timer _escapedSoundFreqTimer
```


#### Field Value
**Type:** Global.Timer

### _escapeSoundFreqMax
```csharp
private const float _escapeSoundFreqMax = 30
```


#### Field Value
**Type:** System.Single

### _escapeSoundFreqMin
```csharp
private const float _escapeSoundFreqMin = 20
```


#### Field Value
**Type:** System.Single

### _hpMax
```csharp
private readonly int[] _hpMax
```


#### Field Value
**Type:** System.Int32[]

### _lv3_SkillProb
```csharp
private const int _lv3_SkillProb = 30
```


#### Field Value
**Type:** System.Int32

### _movementScale
```csharp
private readonly float[] _movementScale
```


#### Field Value
**Type:** System.Single[]

### _workerDeadQliphothCount
```csharp
private const int _workerDeadQliphothCount = 10
```


#### Field Value
**Type:** System.Int32

### CollapseEatCount
```csharp
public const int CollapseEatCount = 3
```


#### Field Value
**Type:** System.Int32

### deadList
```csharp
private List<WorkerModel> deadList
```


#### Field Value
**Type:** System.Collections.Generic.List{WorkerModel}

### DebugPrefix
```csharp
public const string DebugPrefix = "<color=#FFFF33>[DangoCreature]</color> "
```


#### Field Value
**Type:** System.String

### destDead
```csharp
private UnitModel destDead
```


#### Field Value
**Type:** Global.UnitModel

### destNode
```csharp
private MapNode destNode
```


#### Field Value
**Type:** Global.MapNode

### QCountMax
```csharp
public const int QCountMax = 2
```


#### Field Value
**Type:** System.Int32

## Properties
### AnimScript
```csharp
public DangoCreatureAnim AnimScript { get; private set; }
```

#### Property Value
**Type:** Global.DangoCreatureAnim

### AttackDelay
```csharp
private float AttackDelay { get; }
```

#### Property Value
**Type:** System.Single

### CheckRange
```csharp
private float CheckRange { get; }
```

#### Property Value
**Type:** System.Single

### DangoLevel
```csharp
public DangoCreature.Level DangoLevel { get; private set; }
```

#### Property Value
**Type:** Global.DangoCreature.Level

### EscapedSoundFreq
```csharp
private float EscapedSoundFreq { get; }
```

#### Property Value
**Type:** System.Single

## Methods
### ActivateQliphothCounter()
```csharp
public override void ActivateQliphothCounter()
```


### AddedQliphothCounter()
```csharp
public override void AddedQliphothCounter()
```


### AttackDamageInvoke(int)
```csharp
public void AttackDamageInvoke(int attackType)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `attackType` | `System.Int32` |  |

### CheckAttackTarget()
```csharp
private void CheckAttackTarget()
```


### CheckCollapseTrample(List<UnitModel>)
```csharp
private void CheckCollapseTrample(List<UnitModel> near)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `near` | `System.Collections.Generic.List{UnitModel}` |  |

### CheckDeadAvailable()
```csharp
private void CheckDeadAvailable()
```


### CheckEnterState(UseSkill)
```csharp
private bool CheckEnterState(UseSkill skill)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

#### Returns
**Type:** System.Boolean

### CheckExitState(UseSkill)
```csharp
private bool CheckExitState(UseSkill skill)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

#### Returns
**Type:** System.Boolean

### CheckNearestDead()
```csharp
private void CheckNearestDead()
```


### CheckQliphothCounter()
```csharp
private void CheckQliphothCounter()
```


### EatenCollapse(UnitModel)
```csharp
public void EatenCollapse(UnitModel unit)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.UnitModel` |  |

### EndAttack()
```csharp
public void EndAttack()
```


### Escape()
```csharp
public override void Escape()
```


### FirstDamage()
```csharp
private void FirstDamage()
```


### GetAllCollapse()
```csharp
private List<UnitModel> GetAllCollapse()
```


#### Returns
**Type:** System.Collections.Generic.List{UnitModel}

### GetAttackTarget()
```csharp
private List<UnitModel> GetAttackTarget()
```


#### Returns
**Type:** System.Collections.Generic.List{UnitModel}

### GetCollapse(PassageObjectModel)
```csharp
private List<UnitModel> GetCollapse(PassageObjectModel passage)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `passage` | `Global.PassageObjectModel` |  |

#### Returns
**Type:** System.Collections.Generic.List{UnitModel}

### GetCurrentDirection()
```csharp
private UnitDirection GetCurrentDirection()
```


#### Returns
**Type:** Global.UnitDirection

### GetDirection(UnitModel)
```csharp
private UnitDirection GetDirection(UnitModel target)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

#### Returns
**Type:** Global.UnitDirection

### GetMaxHp(int)
```csharp
private int GetMaxHp(int level)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `level` | `System.Int32` |  |

#### Returns
**Type:** System.Int32

### GetMaxHp(Level)
```csharp
private int GetMaxHp(DangoCreature.Level level)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `level` | `Global.DangoCreature.Level` |  |

#### Returns
**Type:** System.Int32

### GetNearestCollapse()
```csharp
private UnitModel GetNearestCollapse()
```


#### Returns
**Type:** Global.UnitModel

### GetNearUnits()
```csharp
private List<UnitModel> GetNearUnits()
```


#### Returns
**Type:** System.Collections.Generic.List{UnitModel}

### GetRadius()
```csharp
public override float GetRadius()
```


#### Returns
**Type:** System.Single

### GetRandomMoveNode()
```csharp
public MapNode GetRandomMoveNode()
```


#### Returns
**Type:** Global.MapNode

### GetSefiraCollapse(Sefira)
```csharp
private List<UnitModel> GetSefiraCollapse(Sefira sefira)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.Sefira` |  |

#### Returns
**Type:** System.Collections.Generic.List{UnitModel}

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

### GetViewDist(UnitModel)
```csharp
private float GetViewDist(UnitModel unit)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.UnitModel` |  |

#### Returns
**Type:** System.Single

### IsAttacking()
```csharp
private bool IsAttacking()
```


#### Returns
**Type:** System.Boolean

### MakeEscapeDefaultSound()
```csharp
private void MakeEscapeDefaultSound()
```


### MakeRandomMovement()
```csharp
private void MakeRandomMovement()
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

### OnChangeDangoLevel(bool, Level)
```csharp
private void OnChangeDangoLevel(bool isAscend, DangoCreature.Level level)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `isAscend` | `System.Boolean` |  |
| `level` | `Global.DangoCreature.Level` |  |

### OnElevatorStuck()
```csharp
public override void OnElevatorStuck()
```


### OnEnterRoom(UseSkill)
```csharp
public override void OnEnterRoom(UseSkill skill)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

### OnNotice(string, params object[])
```csharp
public void OnNotice(string notice, params object[] param)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `notice` | `System.String` |  |
| `param` | `System.Object[]` |  |

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


### OnStageStart()
```csharp
public override void OnStageStart()
```


### OnSuppressed()
```csharp
public override void OnSuppressed()
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


### ReduceAliveAgent()
```csharp
private void ReduceAliveAgent()
```


### ReducedQliphothCounter()
```csharp
public override void ReducedQliphothCounter()
```


### SecondDamage()
```csharp
private void SecondDamage()
```


### SplashDamage(float, float, DamageInfo)
```csharp
private List<WorkerModel> SplashDamage(float range, float space, DamageInfo damage)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `range` | `System.Single` |  |
| `space` | `System.Single` |  |
| `damage` | `Global.DamageInfo` |  |

#### Returns
**Type:** System.Collections.Generic.List{WorkerModel}

### StartAttack(List<UnitModel>)
```csharp
private void StartAttack(List<UnitModel> targetAbleList)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `targetAbleList` | `System.Collections.Generic.List{UnitModel}` |  |

### StopMovement()
```csharp
private void StopMovement()
```


### ThirdDamage(int)
```csharp
private void ThirdDamage(int type)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `type` | `System.Int32` |  |

### UniqueEscape()
```csharp
public override void UniqueEscape()
```


## Inherited Members
[isolateSpriteSrc](/api/Global/Abnormalities/CreatureBase/CreatureBase#isolatespritesrc), [model](/api/Global/Abnormalities/CreatureBase/CreatureBase#model), [skill](/api/Global/Abnormalities/CreatureBase/CreatureBase#skill), [kitEvent](/api/Global/Abnormalities/CreatureBase/CreatureBase#kitevent), [hasUniqueEscapeLogic](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueescapelogic), [isWorkAllocated](/api/Global/Abnormalities/CreatureBase/CreatureBase#isworkallocated), [_allocatedAgent](/api/Global/Abnormalities/CreatureBase/CreatureBase#allocatedagent), [damage](/api/Global/Abnormalities/CreatureBase/CreatureBase#damage), [OnReleaseSpecialTip](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleasespecialtip), [specialSkillTipParamList](/api/Global/Abnormalities/CreatureBase/CreatureBase#specialskilltipparamlist), [_check](/api/Global/Abnormalities/CreatureBase/CreatureBase#check), [SetModel(CreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#setmodel-creaturemodel), [OnInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#oninit), [OnViewInitPrev(CreatureUnit)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onviewinitprev-creatureunit), [OnFixedUpdate(CreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfixedupdate-creaturemodel), [OnFixedUpdateInSkill(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfixedupdateinskill-useskill), [OnSkillFailWorkTick(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillfailworktick-useskill), [OnSkillSuccessWorkTick(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillsuccessworktick-useskill), [OnSkillTickUpdate(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskilltickupdate-useskill), [OnSkillGoalComplete(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillgoalcomplete-useskill), [PermitCancelCurrentWork()](/api/Global/Abnormalities/CreatureBase/CreatureBase#permitcancelcurrentwork), [GetKitCreatureProcessTime()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getkitcreatureprocesstime), [OnBonusWorkProb()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onbonusworkprob), [GetDamageMultiplierInWork(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdamagemultiplierinwork-useskill), [TranformWorkProb(float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#tranformworkprob-float), [OnFinishWork(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfinishwork-useskill), [GetSpecialSkill()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getspecialskill), [GetDebugText()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdebugtext), [OnTimerEnd()](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontimerend), [MakeEffect(IsolateRoom, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffect-isolateroom-int), [MakeEffectAlter(IsolateRoom, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectalter-isolateroom-int), [Prob(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#prob-int), [isAttackInWorkProcess()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isattackinworkprocess), [OnAttackInWorkProcess(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onattackinworkprocess-useskill), [AttackProcess(UnitModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#attackprocess-unitmodel), [AutoFeelingDown()](/api/Global/Abnormalities/CreatureBase/CreatureBase#autofeelingdown), [AgentAnimCalled(int, WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#agentanimcalled-int-workermodel), [MakingEffect(string, float, string, Transform, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float-string-transform-int), [MakingEffect(string, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float), [MakeEffectAttachedToHead(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectattachedtohead-string), [MakingEffect(string, float, string, Vector3, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float-string-vector3-int), [OnAgentWorkEndAnimationPlayed(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentworkendanimationplayed-useskill), [OnAgentAllocateWork(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentallocatework-agentmodel), [OnStageRelease()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onstagerelease), [OnAllocatedWork(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onallocatedwork-agentmodel), [OnReleaseWorkAllocated()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleaseworkallocated), [ObserveLevelChangeForSpecialSkillTip()](/api/Global/Abnormalities/CreatureBase/CreatureBase#observelevelchangeforspecialskilltip), [OnObserveLevelChanged()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onobservelevelchanged), [HasUniqueProcessWorkNarration()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueprocessworknarration), [UniqueProcessWorkNarration(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniqueprocessworknarration-useskill), [RoomSpriteInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomspriteinit), [RoomEscapeSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomescapespriteon), [RoomEscapeSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomescapespriteoff), [RoomSkillSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomskillspriteon), [RoomSkillSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomskillspriteoff), [RoomStateSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomstatespriteon), [RoomStateSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomstatespriteoff), [OnForceSpecialSkillTipReveal(string, params object[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onforcespecialskilltipreveal-string-params-object), [OnWorkReleaseSpeicalSkillTipReveal(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkreleasespeicalskilltipreveal-string), [OnWorkReleaseTipUpdate(params object[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkreleasetipupdate-params-object), [OnAgentAnimatorReseted()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentanimatorreseted), [SpecialEnergyTick()](/api/Global/Abnormalities/CreatureBase/CreatureBase#specialenergytick), [OnFeverTimeOver()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfevertimeover), [OnOverlayIsolateWork()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onoverlayisolatework), [OnOverlayIsolateObserve()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onoverlayisolateobserve), [OnOpenObserveWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopenobservewindow), [OnOpenWorkWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopenworkwindow), [OnOpenCollectionWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopencollectionwindow), [DelayAttackMotion(float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#delayattackmotion-float), [IsAttackTargetable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isattacktargetable), [GetRealTargets()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getrealtargets), [HasScriptSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasscriptsavedata), [GetSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getsavedata), [LoadData(Dictionary<string, object>)](/api/Global/Abnormalities/CreatureBase/CreatureBase#loaddata-dictionary-string-object), [LoadScriptData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#loadscriptdata), [SaveScriptData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#savescriptdata), [ExistSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#existsavedata), [RemoveSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#removesavedata), [ReplaceCommand(CreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#replacecommand-creaturemodel), [OnGamemanagerInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#ongamemanagerinit), [MakeEffectGlobalPos(string, Vector3)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectglobalpos-string-vector3), [MakeEffectGlobalPosNonTrans(string, Vector3)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectglobalposnontrans-string-vector3), [CanObservedByAgent(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#canobservedbyagent-agentmodel), [MakeSound(string, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string-float), [MakeSound(string, AudioRolloffMode)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string-audiorolloffmode), [MakeSoundQueue(params string[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesoundqueue-params-string), [MakeSoundLoop(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesoundloop-string), [OnViewDestroy()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onviewdestroy), [IsWorkable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isworkable), [HasUniqueMaxObservationFinish()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquemaxobservationfinish), [UniqueMaxObservationFinish(Desc)](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquemaxobservationfinish-desc), [OnChildSuppressed(ChildCreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onchildsuppressed-childcreaturemodel), [MakeChildCreature(UnitModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makechildcreature-unitmodel), [OnKillWorker(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onkillworker-workermodel), [GenPursueCommandAlter(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#genpursuecommandalter-workermodel), [OnAfterSuppressed()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onaftersuppressed), [hasUniqueDeadScene()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquedeadscene), [SetHpSlider(Slider)](/api/Global/Abnormalities/CreatureBase/CreatureBase#sethpslider-slider), [SetCastingSlider(Slider)](/api/Global/Abnormalities/CreatureBase/CreatureBase#setcastingslider-slider), [HasUniqueAttackDealy()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueattackdealy), [CanTakeDamage(UnitModel, DamageInfo)](/api/Global/Abnormalities/CreatureBase/CreatureBase#cantakedamage-unitmodel-damageinfo), [OnTakePhysicalDamage(UnitModel, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontakephysicaldamage-unitmodel-float), [HasUniqueFaction()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquefaction), [OnWorkerPanic(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkerpanic-workermodel), [OnSelectMaxObservation(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onselectmaxobservation-int), [OnLoadCreatureName(ref string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onloadcreaturename-ref-string), [IsSuppressable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#issuppressable), [IsSuppressableByRoom()](/api/Global/Abnormalities/CreatureBase/CreatureBase#issuppressablebyroom), [IsAutoSuppressable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isautosuppressable), [OnWorkWindowSkillClicked(long)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkwindowskillclicked-long), [UseDefaultDamageIgnoreMessage(DamageTextEffect)](/api/Global/Abnormalities/CreatureBase/CreatureBase#usedefaultdamageignoremessage-damagetexteffect), [OnWorkAllocated(SkillTypeInfo, AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkallocated-skilltypeinfo-agentmodel), [GetPhysicalDamage(out float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getphysicaldamage-out-float), [GetMentalDamage(out float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getmentaldamage-out-float), [OnSuperArmorBreak()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onsuperarmorbreak), [UniqueStunEffect()](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquestuneffect), [HasEscapeUI()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasescapeui), [HasRoomCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasroomcounter), [RoomCounterInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomcounterinit), [ResetQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#resetqliphothcounter), [GetMaxWorkCountView()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getmaxworkcountview), [GetQliphothCounterMax()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getqliphothcountermax), [OnWorkClosed(UseSkill, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkclosed-useskill-int), [IsActivatedWorkDesc()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isactivatedworkdesc), [IsSensoredInPassage()](/api/Global/Abnormalities/CreatureBase/CreatureBase#issensoredinpassage), [IsIndirectSuppressable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isindirectsuppressable), [GetRiskLevel()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getrisklevel), [GetName()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getname), [UniqueMoveControl()](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquemovecontrol), [HasUniqueName()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquename), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdamagefactor-unitmodel-damageinfo), [OnInitialBuild()](/api/Global/Abnormalities/CreatureBase/CreatureBase#oninitialbuild), [HasUniqueCollectionCost(string, out string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquecollectioncost-string-out-string), [OnOpenCommandWindow(Button[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopencommandwindow-button), [HasUniqueCommandAction(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquecommandaction-int), [HasUniqueWorkSelect(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueworkselect-int), [ForcelySuccess(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#forcelysuccess-useskill), [ForcelyFail(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#forcelyfail-useskill), [TryRabbitTeleport(MapNode)](/api/Global/Abnormalities/CreatureBase/CreatureBase#tryrabbitteleport-mapnode), [CanEnterRoom()](/api/Global/Abnormalities/CreatureBase/CreatureBase#canenterroom), [AllocatedAgent](/api/Global/Abnormalities/CreatureBase/CreatureBase#allocatedagent), [skillTriggerCheck](/api/Global/Abnormalities/CreatureBase/CreatureBase#skilltriggercheck), [Unit](/api/Global/Abnormalities/CreatureBase/CreatureBase#unit), [GetSaveSrc](/api/Global/Abnormalities/CreatureBase/CreatureBase#getsavesrc), [movable](/api/Global/Abnormalities/CreatureBase/CreatureBase#movable), [currentPassage](/api/Global/Abnormalities/CreatureBase/CreatureBase#currentpassage), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)







