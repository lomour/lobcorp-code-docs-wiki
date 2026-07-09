---
uid: Global.Nothing
canonical_path: /api/Global/Misc/Nothing
---
# Class Nothing
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Nothing : CreatureBase
```
> This section may have incomplete or incorrect information.
{.is-warning}


Nothing There.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase](/api/Global/Abnormalities/CreatureBase/CreatureBase) → Nothing

## Constructors
### Nothing()
```csharp
public Nothing()
```

## Fields
### _animScript
```csharp
private NothingAnim _animScript
```


#### Field Value
**Type:** Global.NothingAnim

### _currentMovementTargetAgent
```csharp
private AgentModel _currentMovementTargetAgent
```


#### Field Value
**Type:** Global.AgentModel

### _healEffectSrc
```csharp
private const string _healEffectSrc = "Effect/RecoverHP"
```


#### Field Value
**Type:** System.String

### _healValueMax_1st
```csharp
private const float _healValueMax_1st = 17
```


#### Field Value
**Type:** System.Single

### _healValueMax_2nd
```csharp
private const float _healValueMax_2nd = 33
```


#### Field Value
**Type:** System.Single

### _healValueMin_1st
```csharp
private const float _healValueMin_1st = 17
```


#### Field Value
**Type:** System.Single

### _healValueMin_2nd
```csharp
private const float _healValueMin_2nd = 33
```


#### Field Value
**Type:** System.Single

### attackDelay
```csharp
private const float attackDelay = 2.5
```


#### Field Value
**Type:** System.Single

### attackRange_lv1
```csharp
public const float attackRange_lv1 = 2
```


#### Field Value
**Type:** System.Single

### attackRange_lv2
```csharp
public const float attackRange_lv2 = 2
```


#### Field Value
**Type:** System.Single

### attackTarget
```csharp
private UnitModel attackTarget
```


#### Field Value
**Type:** Global.UnitModel

### changeWorkerEscapeTime
```csharp
private const float changeWorkerEscapeTime = 3
```


#### Field Value
**Type:** System.Single

### changeWorkerEscapeTimer
```csharp
private Timer changeWorkerEscapeTimer
```


#### Field Value
**Type:** Global.Timer

### changeWorkerRoomTime
```csharp
private const float changeWorkerRoomTime = 2
```


#### Field Value
**Type:** System.Single

### changeWorkerRoomTimer
```csharp
private Timer changeWorkerRoomTimer
```


#### Field Value
**Type:** Global.Timer

### copiedWorker
```csharp
public WorkerModel copiedWorker
```


#### Field Value
**Type:** Global.WorkerModel

### currentAgent
```csharp
private AgentModel currentAgent
```


#### Field Value
**Type:** Global.AgentModel

### currentDefSoundFrq
```csharp
private float currentDefSoundFrq
```


#### Field Value
**Type:** System.Single

### currentDefSoundKey
```csharp
private string currentDefSoundKey
```


#### Field Value
**Type:** System.String

### currentForm
```csharp
public Nothing.NothingForm currentForm
```

#### Field Value
**Type:** Global.Nothing.NothingForm

### defaultSkillProb
```csharp
private const float defaultSkillProb = 0.4
```


#### Field Value
**Type:** System.Single

### defSound
```csharp
public Timer defSound
```


#### Field Value
**Type:** Global.Timer

### evolveTime
```csharp
private const float evolveTime = 30
```


#### Field Value
**Type:** System.Single

### evolveTimer
```csharp
private Timer evolveTimer
```


#### Field Value
**Type:** Global.Timer

### gonnaEscape
```csharp
private bool gonnaEscape
```


#### Field Value
**Type:** System.Boolean

### hatchTime
```csharp
private const float hatchTime = 30
```


#### Field Value
**Type:** System.Single

### hatchTimer
```csharp
private Timer hatchTimer
```


#### Field Value
**Type:** Global.Timer

### heartBeatElap
```csharp
private float heartBeatElap
```


#### Field Value
**Type:** System.Single

### heartBeatFreq
```csharp
private float heartBeatFreq
```


#### Field Value
**Type:** System.Single

### heartBeatMax
```csharp
private const float heartBeatMax = 2.5
```


#### Field Value
**Type:** System.Single

### humanDefFrq
```csharp
private const float humanDefFrq = 5
```


#### Field Value
**Type:** System.Single

### level1DefFrq
```csharp
private const float level1DefFrq = 12
```


#### Field Value
**Type:** System.Single

### level2DefFrq
```csharp
private const float level2DefFrq = 25
```


#### Field Value
**Type:** System.Single

### maxHp_egg
```csharp
private const int maxHp_egg = 2000
```


#### Field Value
**Type:** System.Int32

### maxHp_lv1
```csharp
private const int maxHp_lv1 = 2000
```


#### Field Value
**Type:** System.Int32

### maxHp_lv2
```csharp
private const int maxHp_lv2 = 2000
```


#### Field Value
**Type:** System.Int32

### movement_lv1
```csharp
private const float movement_lv1 = 2
```


#### Field Value
**Type:** System.Single

### movement_lv2
```csharp
private const float movement_lv2 = 1.2
```


#### Field Value
**Type:** System.Single

### moveWaitTimer
```csharp
public Timer moveWaitTimer
```


#### Field Value
**Type:** Global.Timer

### normalAttackStack
```csharp
private int normalAttackStack
```


#### Field Value
**Type:** System.Int32

### normalDamageMax_Lv2
```csharp
private const int normalDamageMax_Lv2 = 35
```


#### Field Value
**Type:** System.Int32

### normalDamageMin_Lv2
```csharp
private const int normalDamageMin_Lv2 = 25
```


#### Field Value
**Type:** System.Int32

### nothingWorker
```csharp
private NothingWorker nothingWorker
```


#### Field Value
**Type:** Global.NothingWorker

### passiveCancelDmg
```csharp
private const float passiveCancelDmg = 1
```


#### Field Value
**Type:** System.Single

### passiveCoolTime
```csharp
private const float passiveCoolTime = 10
```


#### Field Value
**Type:** System.Single

### passiveCoolTimer
```csharp
private Timer passiveCoolTimer
```


#### Field Value
**Type:** Global.Timer

### passivePhaseOver
```csharp
private const float passivePhaseOver = 0.3
```


#### Field Value
**Type:** System.Single

### remainAttackDelay
```csharp
private float remainAttackDelay
```


#### Field Value
**Type:** System.Single

### skillProbPerNormalAttackStack
```csharp
private const float skillProbPerNormalAttackStack = 0.15
```


#### Field Value
**Type:** System.Single

### snipe
```csharp
private NothingSnipingUI snipe
```


#### Field Value
**Type:** Global.NothingSnipingUI

### snipingTime
```csharp
private const float snipingTime = 1
```


#### Field Value
**Type:** System.Single

### snipingTimer
```csharp
private Timer snipingTimer
```


#### Field Value
**Type:** Global.Timer

### spearAttack
```csharp
private bool spearAttack
```


#### Field Value
**Type:** System.Boolean

### spearBindTargets
```csharp
private List<UnitModel> spearBindTargets
```


#### Field Value
**Type:** System.Collections.Generic.List{UnitModel}

### spearCastingTime
```csharp
private const float spearCastingTime = 2
```


#### Field Value
**Type:** System.Single

### spearCastingTimer
```csharp
private Timer spearCastingTimer
```


#### Field Value
**Type:** Global.Timer

### spearDamageMax
```csharp
private const int spearDamageMax = 60
```


#### Field Value
**Type:** System.Int32

### spearDamageMin
```csharp
private const int spearDamageMin = 50
```


#### Field Value
**Type:** System.Int32

### strikeDamageMax
```csharp
private const int strikeDamageMax = 300
```


#### Field Value
**Type:** System.Int32

### strikeDamageMin
```csharp
private const int strikeDamageMin = 300
```


#### Field Value
**Type:** System.Int32

### strikeProb
```csharp
private const float strikeProb = 0.3
```


#### Field Value
**Type:** System.Single

### targetChangeWorker
```csharp
private WorkerModel targetChangeWorker
```


#### Field Value
**Type:** Global.WorkerModel

### waitTime
```csharp
private float waitTime
```


#### Field Value
**Type:** System.Single

## Properties
### animScript
```csharp
public NothingAnim animScript { get; }
```

#### Property Value
**Type:** Global.NothingAnim

### HealValue_1st
```csharp
private static float HealValue_1st { get; }
```

#### Property Value
**Type:** System.Single

### HealValue_2nd
```csharp
private static float HealValue_2nd { get; }
```

#### Property Value
**Type:** System.Single

### normalDamage_Lv2
```csharp
private static int normalDamage_Lv2 { get; }
```

#### Property Value
**Type:** System.Int32

### spearDamage
```csharp
private static int spearDamage { get; }
```

#### Property Value
**Type:** System.Int32

### strikeDamage
```csharp
private static int strikeDamage { get; }
```

#### Property Value
**Type:** System.Int32

## Methods
### ActivateQliphothCounter()
```csharp
public override void ActivateQliphothCounter()
```


### CancelPassive()
```csharp
private void CancelPassive()
```


### CastSpearAttack()
```csharp
private void CastSpearAttack()
```


### EndSpearAttack()
```csharp
public void EndSpearAttack()
```


### Escape()
```csharp
public override void Escape()
```


### EscapeLv1()
```csharp
private void EscapeLv1()
```


### EscapeWorkerForm()
```csharp
private void EscapeWorkerForm()
```


### FinishSniping()
```csharp
public void FinishSniping()
```


### GetAttackTargets(List<UnitModel>, List<UnitModel>, List<UnitModel>)
```csharp
private void GetAttackTargets(List<UnitModel> outTargetsInPassage, List<UnitModel> outAttackTargets, List<UnitModel> outSpearTargets)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `outTargetsInPassage` | `System.Collections.Generic.List{UnitModel}` |  |
| `outAttackTargets` | `System.Collections.Generic.List{UnitModel}` |  |
| `outSpearTargets` | `System.Collections.Generic.List{UnitModel}` |  |

### GetPassive()
```csharp
private void GetPassive()
```


### GiveDamageLv2NormalAttack()
```csharp
public void GiveDamageLv2NormalAttack()
```


### GiveDamageLv2SpearAttack()
```csharp
public void GiveDamageLv2SpearAttack()
```


### GiveDamageLv2StrikeAttack()
```csharp
public void GiveDamageLv2StrikeAttack()
```


### Heal()
```csharp
public void Heal()
```


### IsAttacking()
```csharp
public bool IsAttacking()
```


#### Returns
**Type:** System.Boolean

### MakeEffect(string)
```csharp
private GameObject MakeEffect(string src)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

#### Returns
**Type:** UnityEngine.GameObject

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

### OnEnterRoom(UseSkill)
```csharp
public override void OnEnterRoom(UseSkill skill)
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

### OnInit()
```csharp
public override void OnInit()
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

### ParamInit()
```csharp
public override void ParamInit()
```


### ProcessLv1()
```csharp
private void ProcessLv1()
```


### ProcessLv2()
```csharp
private void ProcessLv2()
```


### SetDefenseType()
```csharp
private void SetDefenseType()
```


### SetLv2SpearBindTargets()
```csharp
public void SetLv2SpearBindTargets()
```


### StartEvolve()
```csharp
private void StartEvolve()
```


### StartSpearAttack()
```csharp
private void StartSpearAttack()
```


### TranformWorkProb(float)
```csharp
public override float TranformWorkProb(float originWorkProb)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `originWorkProb` | `System.Single` |  |

#### Returns
**Type:** System.Single

### Transform(NothingForm)
```csharp
private void Transform(Nothing.NothingForm form)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `form` | `Global.Nothing.NothingForm` |  |

### TransformToLv1Escape()
```csharp
private void TransformToLv1Escape()
```


### TransformToWorker(WorkerModel)
```csharp
private void TransformToWorker(WorkerModel worker)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

### TransformToWorkerEscape(WorkerModel)
```csharp
private void TransformToWorkerEscape(WorkerModel worker)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

### TransformToWorkerRoom(WorkerModel)
```csharp
private void TransformToWorkerRoom(WorkerModel worker)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

### UniqueEscape()
```csharp
public override void UniqueEscape()
```


## Inherited Members
[isolateSpriteSrc](/api/Global/Abnormalities/CreatureBase/CreatureBase#isolatespritesrc), [model](/api/Global/Abnormalities/CreatureBase/CreatureBase#model), [skill](/api/Global/Abnormalities/CreatureBase/CreatureBase#skill), [kitEvent](/api/Global/Abnormalities/CreatureBase/CreatureBase#kitevent), [hasUniqueEscapeLogic](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueescapelogic), [isWorkAllocated](/api/Global/Abnormalities/CreatureBase/CreatureBase#isworkallocated), [_allocatedAgent](/api/Global/Abnormalities/CreatureBase/CreatureBase#allocatedagent), [damage](/api/Global/Abnormalities/CreatureBase/CreatureBase#damage), [OnReleaseSpecialTip](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleasespecialtip), [specialSkillTipParamList](/api/Global/Abnormalities/CreatureBase/CreatureBase#specialskilltipparamlist), [_check](/api/Global/Abnormalities/CreatureBase/CreatureBase#check), [SetModel(CreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#setmodel-creaturemodel), [OnViewInitPrev(CreatureUnit)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onviewinitprev-creatureunit), [OnFixedUpdateInSkill(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfixedupdateinskill-useskill), [OnSkillFailWorkTick(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillfailworktick-useskill), [OnSkillSuccessWorkTick(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillsuccessworktick-useskill), [OnSkillTickUpdate(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskilltickupdate-useskill), [OnSkillGoalComplete(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillgoalcomplete-useskill), [PermitCancelCurrentWork()](/api/Global/Abnormalities/CreatureBase/CreatureBase#permitcancelcurrentwork), [GetKitCreatureProcessTime()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getkitcreatureprocesstime), [OnBonusWorkProb()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onbonusworkprob), [GetDamageMultiplierInWork(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdamagemultiplierinwork-useskill), [OnFinishWork(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfinishwork-useskill), [OnWorkCoolTimeEnd(CreatureFeelingState)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkcooltimeend-creaturefeelingstate), [GetSpecialSkill()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getspecialskill), [GetDebugText()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdebugtext), [OnTimerEnd()](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontimerend), [MakeEffect(IsolateRoom, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffect-isolateroom-int), [MakeEffectAlter(IsolateRoom, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectalter-isolateroom-int), [Prob(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#prob-int), [isAttackInWorkProcess()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isattackinworkprocess), [OnAttackInWorkProcess(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onattackinworkprocess-useskill), [AttackProcess(UnitModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#attackprocess-unitmodel), [AutoFeelingDown()](/api/Global/Abnormalities/CreatureBase/CreatureBase#autofeelingdown), [AgentAnimCalled(int, WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#agentanimcalled-int-workermodel), [MakingEffect(string, float, string, Transform, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float-string-transform-int), [MakingEffect(string, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float), [MakeEffectAttachedToHead(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectattachedtohead-string), [MakingEffect(string, float, string, Vector3, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float-string-vector3-int), [OnAgentWorkEndAnimationPlayed(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentworkendanimationplayed-useskill), [OnAgentAllocateWork(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentallocatework-agentmodel), [OnAllocatedWork(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onallocatedwork-agentmodel), [OnReleaseWorkAllocated()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleaseworkallocated), [ObserveLevelChangeForSpecialSkillTip()](/api/Global/Abnormalities/CreatureBase/CreatureBase#observelevelchangeforspecialskilltip), [OnObserveLevelChanged()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onobservelevelchanged), [HasUniqueProcessWorkNarration()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueprocessworknarration), [UniqueProcessWorkNarration(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniqueprocessworknarration-useskill), [RoomSpriteInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomspriteinit), [RoomEscapeSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomescapespriteon), [RoomEscapeSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomescapespriteoff), [RoomSkillSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomskillspriteon), [RoomSkillSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomskillspriteoff), [RoomStateSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomstatespriteon), [RoomStateSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomstatespriteoff), [OnForceSpecialSkillTipReveal(string, params object[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onforcespecialskilltipreveal-string-params-object), [OnWorkReleaseSpeicalSkillTipReveal(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkreleasespeicalskilltipreveal-string), [OnWorkReleaseTipUpdate(params object[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkreleasetipupdate-params-object), [OnAgentAnimatorReseted()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentanimatorreseted), [SpecialEnergyTick()](/api/Global/Abnormalities/CreatureBase/CreatureBase#specialenergytick), [OnStageEnd()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onstageend), [OnFeverTimeOver()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfevertimeover), [OnOverlayIsolateWork()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onoverlayisolatework), [OnOverlayIsolateObserve()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onoverlayisolateobserve), [OnOpenObserveWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopenobservewindow), [OnOpenWorkWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopenworkwindow), [OnOpenCollectionWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopencollectionwindow), [DelayAttackMotion(float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#delayattackmotion-float), [IsAttackTargetable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isattacktargetable), [GetRealTargets()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getrealtargets), [HasScriptSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasscriptsavedata), [GetSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getsavedata), [LoadData(Dictionary<string, object>)](/api/Global/Abnormalities/CreatureBase/CreatureBase#loaddata-dictionary-string-object), [LoadScriptData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#loadscriptdata), [SaveScriptData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#savescriptdata), [ExistSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#existsavedata), [RemoveSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#removesavedata), [ReplaceCommand(CreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#replacecommand-creaturemodel), [OnGamemanagerInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#ongamemanagerinit), [MakeEffectGlobalPos(string, Vector3)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectglobalpos-string-vector3), [MakeEffectGlobalPosNonTrans(string, Vector3)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectglobalposnontrans-string-vector3), [CanObservedByAgent(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#canobservedbyagent-agentmodel), [MakeSound(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string), [MakeSound(string, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string-float), [MakeSound(string, AudioRolloffMode)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string-audiorolloffmode), [MakeSoundQueue(params string[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesoundqueue-params-string), [MakeSoundLoop(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesoundloop-string), [OnViewDestroy()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onviewdestroy), [IsWorkable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isworkable), [HasUniqueMaxObservationFinish()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquemaxobservationfinish), [UniqueMaxObservationFinish(Desc)](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquemaxobservationfinish-desc), [OnChildSuppressed(ChildCreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onchildsuppressed-childcreaturemodel), [MakeChildCreature(UnitModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makechildcreature-unitmodel), [OnKillWorker(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onkillworker-workermodel), [GenPursueCommandAlter(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#genpursuecommandalter-workermodel), [OnAfterSuppressed()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onaftersuppressed), [hasUniqueDeadScene()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquedeadscene), [SetHpSlider(Slider)](/api/Global/Abnormalities/CreatureBase/CreatureBase#sethpslider-slider), [SetCastingSlider(Slider)](/api/Global/Abnormalities/CreatureBase/CreatureBase#setcastingslider-slider), [HasUniqueAttackDealy()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueattackdealy), [CanTakeDamage(UnitModel, DamageInfo)](/api/Global/Abnormalities/CreatureBase/CreatureBase#cantakedamage-unitmodel-damageinfo), [OnTakePhysicalDamage(UnitModel, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontakephysicaldamage-unitmodel-float), [HasUniqueFaction()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquefaction), [OnWorkerPanic(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkerpanic-workermodel), [OnSelectMaxObservation(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onselectmaxobservation-int), [OnLoadCreatureName(ref string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onloadcreaturename-ref-string), [IsSuppressable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#issuppressable), [IsSuppressableByRoom()](/api/Global/Abnormalities/CreatureBase/CreatureBase#issuppressablebyroom), [IsAutoSuppressable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isautosuppressable), [OnWorkWindowSkillClicked(long)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkwindowskillclicked-long), [UseDefaultDamageIgnoreMessage(DamageTextEffect)](/api/Global/Abnormalities/CreatureBase/CreatureBase#usedefaultdamageignoremessage-damagetexteffect), [OnWorkAllocated(SkillTypeInfo, AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkallocated-skilltypeinfo-agentmodel), [GetPhysicalDamage(out float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getphysicaldamage-out-float), [GetMentalDamage(out float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getmentaldamage-out-float), [OnSuperArmorBreak()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onsuperarmorbreak), [UniqueStunEffect()](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquestuneffect), [HasEscapeUI()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasescapeui), [HasRoomCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasroomcounter), [RoomCounterInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomcounterinit), [ResetQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#resetqliphothcounter), [GetMaxWorkCountView()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getmaxworkcountview), [GetQliphothCounterMax()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getqliphothcountermax), [ReducedQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#reducedqliphothcounter), [AddedQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#addedqliphothcounter), [GetRadius()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getradius), [OnElevatorStuck()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onelevatorstuck), [OnWorkClosed(UseSkill, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkclosed-useskill-int), [IsActivatedWorkDesc()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isactivatedworkdesc), [IsSensoredInPassage()](/api/Global/Abnormalities/CreatureBase/CreatureBase#issensoredinpassage), [IsIndirectSuppressable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isindirectsuppressable), [GetRiskLevel()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getrisklevel), [GetName()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getname), [UniqueMoveControl()](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquemovecontrol), [HasUniqueName()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquename), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdamagefactor-unitmodel-damageinfo), [OnInitialBuild()](/api/Global/Abnormalities/CreatureBase/CreatureBase#oninitialbuild), [HasUniqueCollectionCost(string, out string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquecollectioncost-string-out-string), [OnOpenCommandWindow(Button[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopencommandwindow-button), [HasUniqueCommandAction(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquecommandaction-int), [HasUniqueWorkSelect(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueworkselect-int), [ForcelySuccess(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#forcelysuccess-useskill), [ForcelyFail(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#forcelyfail-useskill), [TryRabbitTeleport(MapNode)](/api/Global/Abnormalities/CreatureBase/CreatureBase#tryrabbitteleport-mapnode), [CanEnterRoom()](/api/Global/Abnormalities/CreatureBase/CreatureBase#canenterroom), [AllocatedAgent](/api/Global/Abnormalities/CreatureBase/CreatureBase#allocatedagent), [skillTriggerCheck](/api/Global/Abnormalities/CreatureBase/CreatureBase#skilltriggercheck), [Unit](/api/Global/Abnormalities/CreatureBase/CreatureBase#unit), [GetSaveSrc](/api/Global/Abnormalities/CreatureBase/CreatureBase#getsavesrc), [movable](/api/Global/Abnormalities/CreatureBase/CreatureBase#movable), [currentPassage](/api/Global/Abnormalities/CreatureBase/CreatureBase#currentpassage), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)







