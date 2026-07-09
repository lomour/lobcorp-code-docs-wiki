---
uid: Global.Yggdrasil
canonical_path: /api/Global/IOBserver/Yggdrasil
---
# Class Yggdrasil
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Yggdrasil : CreatureBase, IObserver
```
> This section may have incomplete or incorrect information.
{.is-warning}


Parasite Tree.




## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase](/api/Global/Abnormalities/CreatureBase/CreatureBase) → Yggdrasil

## Implements
[IObserver](/api/Global/Notices/IObserver)

## Constructors
### Yggdrasil()
```csharp
public Yggdrasil()
```

## Fields
### _animScript
```csharp
private YggdrasilAnim _animScript
```


#### Field Value
**Type:** Global.YggdrasilAnim

### _defaultSoundFreqMax
```csharp
private const float _defaultSoundFreqMax = 10
```


#### Field Value
**Type:** System.Single

### _defaultSoundFreqMin
```csharp
private const float _defaultSoundFreqMin = 5
```


#### Field Value
**Type:** System.Single

### _FILTER_NAME
```csharp
private const string _FILTER_NAME = "YggdrasilSporeFilter"
```


#### Field Value
**Type:** System.String

### _FILTER_SRC
```csharp
private const string _FILTER_SRC = "Sprites/CreatureSprite/Yggdrasil/filter_hall"
```


#### Field Value
**Type:** System.String

### _PASSAGE_DMG_MAX
```csharp
private const int _PASSAGE_DMG_MAX = 12
```


#### Field Value
**Type:** System.Int32

### _PASSAGE_DMG_MIN
```csharp
private const int _PASSAGE_DMG_MIN = 9
```


#### Field Value
**Type:** System.Int32

### _PASSAGE_DMG_TYPE
```csharp
private const RwbpType _PASSAGE_DMG_TYPE = W
```


#### Field Value
**Type:** Global.RwbpType

### BLESS_OVERLOAD_CNT
```csharp
private int BLESS_OVERLOAD_CNT
```


#### Field Value
**Type:** System.Int32

### blessedList
```csharp
private List<WorkerModel> blessedList
```


#### Field Value
**Type:** System.Collections.Generic.List{WorkerModel}

### blessTarget
```csharp
private WorkerModel blessTarget
```


#### Field Value
**Type:** Global.WorkerModel

### defaultSoundTimer
```csharp
private Timer defaultSoundTimer
```


#### Field Value
**Type:** Global.Timer

### FILTER_DECREASE_TIME
```csharp
private const float FILTER_DECREASE_TIME = 1
```


#### Field Value
**Type:** System.Single

### FILTER_INCREASE_TIME
```csharp
private const float FILTER_INCREASE_TIME = 1
```


#### Field Value
**Type:** System.Single

### filterDecreaseTimer
```csharp
private Timer filterDecreaseTimer
```


#### Field Value
**Type:** Global.Timer

### filterIncreaseTimer
```csharp
private Timer filterIncreaseTimer
```


#### Field Value
**Type:** Global.Timer

### gonnaSubQliphoth
```csharp
private bool gonnaSubQliphoth
```


#### Field Value
**Type:** System.Boolean

### infestedPassages
```csharp
private Dictionary<PassageObjectModel, Yggdrasil.InfestedPassage> infestedPassages
```

#### Field Value
**Type:** System.Collections.Generic.Dictionary{PassageObjectModel,Yggdrasil.InfestedPassage}

### isInSkill
```csharp
private bool isInSkill
```


#### Field Value
**Type:** System.Boolean

### loopSound
```csharp
private SoundEffectPlayer loopSound
```


#### Field Value
**Type:** Global.SoundEffectPlayer

### SUB_QLIPHOTH_ESCAPE_PROB
```csharp
private float SUB_QLIPHOTH_ESCAPE_PROB
```


#### Field Value
**Type:** System.Single

### SUB_QLIPHOTH_WORK_OHTER_CNT
```csharp
private int SUB_QLIPHOTH_WORK_OHTER_CNT
```


#### Field Value
**Type:** System.Int32

### TARGET_SKILL_ID
```csharp
private int TARGET_SKILL_ID
```


#### Field Value
**Type:** System.Int32

### workOtherCnt
```csharp
private int workOtherCnt
```


#### Field Value
**Type:** System.Int32

## Properties
### animScript
```csharp
public YggdrasilAnim animScript { get; }
```

#### Property Value
**Type:** Global.YggdrasilAnim

### BlessedCnt
```csharp
private int BlessedCnt { get; }
```

#### Property Value
**Type:** System.Int32

### ChildAlive
```csharp
private bool ChildAlive { get; }
```

#### Property Value
**Type:** System.Boolean

### DEFAULT_SOUND_FREQ
```csharp
private static float DEFAULT_SOUND_FREQ { get; }
```

#### Property Value
**Type:** System.Single

### PassageDmg
```csharp
public static DamageInfo PassageDmg { get; }
```

#### Property Value
**Type:** Global.DamageInfo

## Methods
### ActivateQliphothCounter()
```csharp
public override void ActivateQliphothCounter()
```


### ActivateSkill()
```csharp
private void ActivateSkill()
```


### AddBlessedList(WorkerModel)
```csharp
public void AddBlessedList(WorkerModel target)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |

### AddFilters(float)
```csharp
private void AddFilters(float alpha)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `alpha` | `System.Single` |  |

### AddFlower()
```csharp
private void AddFlower()
```


### AddWorkCount()
```csharp
private void AddWorkCount()
```


### Attract(WorkerModel)
```csharp
private void Attract(WorkerModel worker)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

### Bless(WorkerModel)
```csharp
private void Bless(WorkerModel worker)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

### BlessOverload()
```csharp
private void BlessOverload()
```


### BlessOverloadEnd()
```csharp
private void BlessOverloadEnd()
```


### BlessStart()
```csharp
private void BlessStart()
```


### CancelAttract(WorkerModel)
```csharp
public void CancelAttract(WorkerModel worker)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

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

### CheckBlessCondition(WorkerModel)
```csharp
private bool CheckBlessCondition(WorkerModel worker)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

#### Returns
**Type:** System.Boolean

### GetAttractTargets()
```csharp
private WorkerModel[] GetAttractTargets()
```


#### Returns
**Type:** Global.WorkerModel[]

### GetAttractTargets(Sefira)
```csharp
private WorkerModel[] GetAttractTargets(Sefira sefira)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.Sefira` |  |

#### Returns
**Type:** Global.WorkerModel[]

### GetSoundSrc(string)
```csharp
private string GetSoundSrc(string key)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |

#### Returns
**Type:** System.String

### GetTargets(PassageObjectModel)
```csharp
public UnitModel[] GetTargets(PassageObjectModel passage)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `passage` | `Global.PassageObjectModel` |  |

#### Returns
**Type:** Global.UnitModel[]

### HasRoomCounter()
```csharp
public override bool HasRoomCounter()
```


#### Returns
**Type:** System.Boolean

### InitFlower()
```csharp
private void InitFlower()
```


### IsHostile(MovableObjectNode)
```csharp
private bool IsHostile(MovableObjectNode mov)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `mov` | `Global.MovableObjectNode` |  |

#### Returns
**Type:** System.Boolean

### IsTransformed()
```csharp
private bool IsTransformed()
```


#### Returns
**Type:** System.Boolean

### IsWorkable()
```csharp
public override bool IsWorkable()
```


#### Returns
**Type:** System.Boolean

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

### MakeSound(string, Vector3, float)
```csharp
public SoundEffectPlayer MakeSound(string src, Vector3 pos, float vol = 1)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |
| `pos` | `UnityEngine.Vector3` |  |
| `vol` | `System.Single` |  |

#### Returns
**Type:** Global.SoundEffectPlayer

### MakeSoundLoop(string, Transform, float)
```csharp
public SoundEffectPlayer MakeSoundLoop(string src, Transform trans, float vol = 1)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |
| `trans` | `UnityEngine.Transform` |  |
| `vol` | `System.Single` |  |

#### Returns
**Type:** Global.SoundEffectPlayer

### OnArrive(WorkerModel)
```csharp
public void OnArrive(WorkerModel arrived)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `arrived` | `Global.WorkerModel` |  |

### OnChildSuppressed(ChildCreatureModel)
```csharp
public override void OnChildSuppressed(ChildCreatureModel child)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `child` | `Global.ChildCreatureModel` |  |

### OnEnterRoom(UseSkill)
```csharp
public override void OnEnterRoom(UseSkill skill)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

### OnFinishWork(UseSkill)
```csharp
public override void OnFinishWork(UseSkill skill)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

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

### OnOpenWorkWindow()
```csharp
public override bool OnOpenWorkWindow()
```


#### Returns
**Type:** System.Boolean

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


### ReduceFilters(float)
```csharp
private void ReduceFilters(float alpha)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `alpha` | `System.Single` |  |

### ReduceFlower()
```csharp
private void ReduceFlower()
```


### RemoveBlessedWorker(WorkerModel)
```csharp
public void RemoveBlessedWorker(WorkerModel worker)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

### RemoveLoopSound()
```csharp
private void RemoveLoopSound()
```


### Reset()
```csharp
private void Reset()
```


### ResetWorkCount()
```csharp
private void ResetWorkCount()
```


### SetFilters(float)
```csharp
private void SetFilters(float alpha)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `alpha` | `System.Single` |  |

### SetTransform(bool)
```csharp
private void SetTransform(bool isTransform)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `isTransform` | `System.Boolean` |  |

### SubQliphothCounter()
```csharp
private void SubQliphothCounter()
```


## Inherited Members
[isolateSpriteSrc](/api/Global/Abnormalities/CreatureBase/CreatureBase#isolatespritesrc), [model](/api/Global/Abnormalities/CreatureBase/CreatureBase#model), [skill](/api/Global/Abnormalities/CreatureBase/CreatureBase#skill), [kitEvent](/api/Global/Abnormalities/CreatureBase/CreatureBase#kitevent), [hasUniqueEscapeLogic](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueescapelogic), [isWorkAllocated](/api/Global/Abnormalities/CreatureBase/CreatureBase#isworkallocated), [_allocatedAgent](/api/Global/Abnormalities/CreatureBase/CreatureBase#allocatedagent), [damage](/api/Global/Abnormalities/CreatureBase/CreatureBase#damage), [OnReleaseSpecialTip](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleasespecialtip), [specialSkillTipParamList](/api/Global/Abnormalities/CreatureBase/CreatureBase#specialskilltipparamlist), [_check](/api/Global/Abnormalities/CreatureBase/CreatureBase#check), [SetModel(CreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#setmodel-creaturemodel), [OnInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#oninit), [OnViewInitPrev(CreatureUnit)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onviewinitprev-creatureunit), [OnFixedUpdateInSkill(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfixedupdateinskill-useskill), [OnSkillFailWorkTick(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillfailworktick-useskill), [OnSkillSuccessWorkTick(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillsuccessworktick-useskill), [OnSkillTickUpdate(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskilltickupdate-useskill), [PermitCancelCurrentWork()](/api/Global/Abnormalities/CreatureBase/CreatureBase#permitcancelcurrentwork), [GetKitCreatureProcessTime()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getkitcreatureprocesstime), [OnBonusWorkProb()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onbonusworkprob), [GetDamageMultiplierInWork(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdamagemultiplierinwork-useskill), [TranformWorkProb(float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#tranformworkprob-float), [OnReleaseWork(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleasework-useskill), [OnReturn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreturn), [UniqueEscape()](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniqueescape), [Escape()](/api/Global/Abnormalities/CreatureBase/CreatureBase#escape), [GetSpecialSkill()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getspecialskill), [GetDebugText()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdebugtext), [OnTimerEnd()](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontimerend), [MakeEffect(IsolateRoom, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffect-isolateroom-int), [MakeEffectAlter(IsolateRoom, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectalter-isolateroom-int), [Prob(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#prob-int), [isAttackInWorkProcess()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isattackinworkprocess), [OnAttackInWorkProcess(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onattackinworkprocess-useskill), [AttackProcess(UnitModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#attackprocess-unitmodel), [AutoFeelingDown()](/api/Global/Abnormalities/CreatureBase/CreatureBase#autofeelingdown), [AgentAnimCalled(int, WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#agentanimcalled-int-workermodel), [MakingEffect(string, float, string, Transform, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float-string-transform-int), [MakingEffect(string, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float), [MakeEffectAttachedToHead(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectattachedtohead-string), [MakingEffect(string, float, string, Vector3, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float-string-vector3-int), [OnAgentWorkEndAnimationPlayed(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentworkendanimationplayed-useskill), [OnAgentAllocateWork(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentallocatework-agentmodel), [OnSuppressed()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onsuppressed), [OnAllocatedWork(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onallocatedwork-agentmodel), [OnReleaseWorkAllocated()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleaseworkallocated), [ObserveLevelChangeForSpecialSkillTip()](/api/Global/Abnormalities/CreatureBase/CreatureBase#observelevelchangeforspecialskilltip), [OnObserveLevelChanged()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onobservelevelchanged), [HasUniqueProcessWorkNarration()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueprocessworknarration), [UniqueProcessWorkNarration(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniqueprocessworknarration-useskill), [RoomSpriteInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomspriteinit), [RoomEscapeSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomescapespriteon), [RoomEscapeSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomescapespriteoff), [RoomSkillSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomskillspriteon), [RoomSkillSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomskillspriteoff), [RoomStateSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomstatespriteon), [RoomStateSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomstatespriteoff), [OnForceSpecialSkillTipReveal(string, params object[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onforcespecialskilltipreveal-string-params-object), [OnWorkReleaseSpeicalSkillTipReveal(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkreleasespeicalskilltipreveal-string), [OnWorkReleaseTipUpdate(params object[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkreleasetipupdate-params-object), [OnAgentAnimatorReseted()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentanimatorreseted), [SpecialEnergyTick()](/api/Global/Abnormalities/CreatureBase/CreatureBase#specialenergytick), [OnStageEnd()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onstageend), [OnFeverTimeOver()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfevertimeover), [OnOverlayIsolateWork()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onoverlayisolatework), [OnOverlayIsolateObserve()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onoverlayisolateobserve), [OnOpenObserveWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopenobservewindow), [OnOpenCollectionWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopencollectionwindow), [DelayAttackMotion(float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#delayattackmotion-float), [IsAttackTargetable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isattacktargetable), [GetRealTargets()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getrealtargets), [HasScriptSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasscriptsavedata), [GetSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getsavedata), [LoadData(Dictionary<string, object>)](/api/Global/Abnormalities/CreatureBase/CreatureBase#loaddata-dictionary-string-object), [LoadScriptData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#loadscriptdata), [SaveScriptData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#savescriptdata), [ExistSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#existsavedata), [RemoveSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#removesavedata), [ReplaceCommand(CreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#replacecommand-creaturemodel), [OnGamemanagerInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#ongamemanagerinit), [MakeEffectGlobalPos(string, Vector3)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectglobalpos-string-vector3), [MakeEffectGlobalPosNonTrans(string, Vector3)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectglobalposnontrans-string-vector3), [CanObservedByAgent(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#canobservedbyagent-agentmodel), [MakeSound(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string), [MakeSound(string, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string-float), [MakeSound(string, AudioRolloffMode)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string-audiorolloffmode), [MakeSoundQueue(params string[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesoundqueue-params-string), [MakeSoundLoop(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesoundloop-string), [OnViewDestroy()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onviewdestroy), [HasUniqueMaxObservationFinish()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquemaxobservationfinish), [UniqueMaxObservationFinish(Desc)](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquemaxobservationfinish-desc), [OnKillWorker(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onkillworker-workermodel), [GenPursueCommandAlter(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#genpursuecommandalter-workermodel), [OnAfterSuppressed()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onaftersuppressed), [hasUniqueDeadScene()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquedeadscene), [SetHpSlider(Slider)](/api/Global/Abnormalities/CreatureBase/CreatureBase#sethpslider-slider), [SetCastingSlider(Slider)](/api/Global/Abnormalities/CreatureBase/CreatureBase#setcastingslider-slider), [HasUniqueAttackDealy()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueattackdealy), [CanTakeDamage(UnitModel, DamageInfo)](/api/Global/Abnormalities/CreatureBase/CreatureBase#cantakedamage-unitmodel-damageinfo), [OnTakePhysicalDamage(UnitModel, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontakephysicaldamage-unitmodel-float), [HasUniqueFaction()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquefaction), [OnWorkerPanic(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkerpanic-workermodel), [OnSelectMaxObservation(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onselectmaxobservation-int), [OnLoadCreatureName(ref string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onloadcreaturename-ref-string), [IsSuppressable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#issuppressable), [IsSuppressableByRoom()](/api/Global/Abnormalities/CreatureBase/CreatureBase#issuppressablebyroom), [IsAutoSuppressable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isautosuppressable), [OnWorkWindowSkillClicked(long)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkwindowskillclicked-long), [UseDefaultDamageIgnoreMessage(DamageTextEffect)](/api/Global/Abnormalities/CreatureBase/CreatureBase#usedefaultdamageignoremessage-damagetexteffect), [OnWorkAllocated(SkillTypeInfo, AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkallocated-skilltypeinfo-agentmodel), [GetPhysicalDamage(out float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getphysicaldamage-out-float), [GetMentalDamage(out float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getmentaldamage-out-float), [OnSuperArmorBreak()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onsuperarmorbreak), [UniqueStunEffect()](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquestuneffect), [HasEscapeUI()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasescapeui), [RoomCounterInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomcounterinit), [ResetQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#resetqliphothcounter), [GetMaxWorkCountView()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getmaxworkcountview), [GetQliphothCounterMax()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getqliphothcountermax), [ReducedQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#reducedqliphothcounter), [AddedQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#addedqliphothcounter), [OnTakeDamage(UnitModel, DamageInfo, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontakedamage-unitmodel-damageinfo-float), [GetRadius()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getradius), [OnElevatorStuck()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onelevatorstuck), [OnWorkClosed(UseSkill, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkclosed-useskill-int), [IsActivatedWorkDesc()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isactivatedworkdesc), [IsSensoredInPassage()](/api/Global/Abnormalities/CreatureBase/CreatureBase#issensoredinpassage), [IsIndirectSuppressable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isindirectsuppressable), [GetRiskLevel()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getrisklevel), [GetName()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getname), [UniqueMoveControl()](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquemovecontrol), [HasUniqueName()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquename), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdamagefactor-unitmodel-damageinfo), [OnInitialBuild()](/api/Global/Abnormalities/CreatureBase/CreatureBase#oninitialbuild), [HasUniqueCollectionCost(string, out string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquecollectioncost-string-out-string), [OnOpenCommandWindow(Button[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopencommandwindow-button), [HasUniqueCommandAction(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquecommandaction-int), [HasUniqueWorkSelect(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueworkselect-int), [ForcelySuccess(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#forcelysuccess-useskill), [ForcelyFail(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#forcelyfail-useskill), [TryRabbitTeleport(MapNode)](/api/Global/Abnormalities/CreatureBase/CreatureBase#tryrabbitteleport-mapnode), [CanEnterRoom()](/api/Global/Abnormalities/CreatureBase/CreatureBase#canenterroom), [AllocatedAgent](/api/Global/Abnormalities/CreatureBase/CreatureBase#allocatedagent), [skillTriggerCheck](/api/Global/Abnormalities/CreatureBase/CreatureBase#skilltriggercheck), [Unit](/api/Global/Abnormalities/CreatureBase/CreatureBase#unit), [GetSaveSrc](/api/Global/Abnormalities/CreatureBase/CreatureBase#getsavesrc), [movable](/api/Global/Abnormalities/CreatureBase/CreatureBase#movable), [currentPassage](/api/Global/Abnormalities/CreatureBase/CreatureBase#currentpassage), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)







