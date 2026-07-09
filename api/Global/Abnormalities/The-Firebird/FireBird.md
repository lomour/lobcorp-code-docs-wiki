---
uid: Global.FireBird
canonical_path: /api/Global/IOBserver/FireBird
---
# Class FireBird
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class FireBird : CreatureBase, IObserver
```
> This section may have incomplete or incorrect information.
{.is-warning}


The Firebird.




## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase](/api/Global/Abnormalities/CreatureBase/CreatureBase) → FireBird

## Implements
[IObserver](/api/Global/Notices/IObserver)

## Constructors
### FireBird()
```csharp
public FireBird()
```

## Fields
### _animScript
```csharp
private FireBirdAnim _animScript
```


#### Field Value
**Type:** Global.FireBirdAnim

### _ARRIVE_RANGE
```csharp
private const float _ARRIVE_RANGE = 0.5
```


#### Field Value
**Type:** System.Single

### _ATTACK_DMG_MAX
```csharp
private const int _ATTACK_DMG_MAX = 110
```


#### Field Value
**Type:** System.Int32

### _ATTACK_DMG_MIN
```csharp
private const int _ATTACK_DMG_MIN = 90
```


#### Field Value
**Type:** System.Int32

### _ATTACK_DMG_RANGE
```csharp
private const float _ATTACK_DMG_RANGE = 0.5
```


#### Field Value
**Type:** System.Single

### _ATTACK_DMG_TYPE
```csharp
private const RwbpType _ATTACK_DMG_TYPE = W
```


#### Field Value
**Type:** Global.RwbpType

### _comeBackTimeMax
```csharp
private const float _comeBackTimeMax = 90
```


#### Field Value
**Type:** System.Single

### _comeBackTimeMin
```csharp
private const float _comeBackTimeMin = 45
```


#### Field Value
**Type:** System.Single

### _EQUIPMENT_ID
```csharp
private const int _EQUIPMENT_ID = 200061
```


#### Field Value
**Type:** System.Int32

### _FILTER_ALPHA
```csharp
private readonly float[] _FILTER_ALPHA
```


#### Field Value
**Type:** System.Single[]

### _FILTER_NAME
```csharp
private const string _FILTER_NAME = "FireBirdBurningFilter"
```


#### Field Value
**Type:** System.String

### _FILTER_SRC
```csharp
private const string _FILTER_SRC = "Sprites/CreatureSprite/FireBird/PassageFilter"
```


#### Field Value
**Type:** System.String

### _HEAL_CONDITION_QLIPHOTH
```csharp
private const int _HEAL_CONDITION_QLIPHOTH = 1
```


#### Field Value
**Type:** System.Int32

### _HEAL_HP_CONDITION
```csharp
private const float _HEAL_HP_CONDITION = 0.2
```


#### Field Value
**Type:** System.Single

### _MOVEMENT_ATTACK
```csharp
private const float _MOVEMENT_ATTACK = 20
```


#### Field Value
**Type:** System.Single

### _PASSAGE_DMG_MAX
```csharp
private const int _PASSAGE_DMG_MAX = 5
```


#### Field Value
**Type:** System.Int32

### _PASSAGE_DMG_MIN
```csharp
private const int _PASSAGE_DMG_MIN = 5
```


#### Field Value
**Type:** System.Int32

### _PASSAGE_DMG_TYPE
```csharp
private const RwbpType _PASSAGE_DMG_TYPE = R
```


#### Field Value
**Type:** Global.RwbpType

### _phase
```csharp
private FireBird.Phase _phase
```

#### Field Value
**Type:** Global.FireBird.Phase

### _QLIPHOTH_MAX
```csharp
private const int _QLIPHOTH_MAX = 3
```


#### Field Value
**Type:** System.Int32

### _RECOGNIZE_RANGE
```csharp
private const float _RECOGNIZE_RANGE = 15
```


#### Field Value
**Type:** System.Single

### _skillCoolTimeMax
```csharp
private const float _skillCoolTimeMax = 10
```


#### Field Value
**Type:** System.Single

### _skillCoolTimeMin
```csharp
private const float _skillCoolTimeMin = 8
```


#### Field Value
**Type:** System.Single

### _SUB_PROB_NORM
```csharp
private const float _SUB_PROB_NORM = 0.3
```


#### Field Value
**Type:** System.Single

### _TREE_SRC
```csharp
private const string _TREE_SRC = "Unit/ETC/FireBirdTree"
```


#### Field Value
**Type:** System.String

### _WORK_DMG_RATIO
```csharp
private readonly float[] _WORK_DMG_RATIO
```


#### Field Value
**Type:** System.Single[]

### annoyed
```csharp
private bool annoyed
```


#### Field Value
**Type:** System.Boolean

### burningPassage
```csharp
private FireBird.BurningPassage burningPassage
```

#### Field Value
**Type:** Global.FireBird.BurningPassage

### comeBackTimer
```csharp
private Timer comeBackTimer
```


#### Field Value
**Type:** Global.Timer

### damaged
```csharp
private List<UnitModel> damaged
```


#### Field Value
**Type:** System.Collections.Generic.List{UnitModel}

### healTarget
```csharp
private WorkerModel healTarget
```


#### Field Value
**Type:** Global.WorkerModel

### isSuppressed
```csharp
private bool isSuppressed
```


#### Field Value
**Type:** System.Boolean

### moveTarget
```csharp
private WorkerModel moveTarget
```


#### Field Value
**Type:** Global.WorkerModel

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

### speedUp
```csharp
private bool speedUp
```


#### Field Value
**Type:** System.Boolean

### targetNode
```csharp
private MapNode targetNode
```


#### Field Value
**Type:** Global.MapNode

### tree
```csharp
private GameObject tree
```


#### Field Value
**Type:** UnityEngine.GameObject

## Properties
### animScript
```csharp
public FireBirdAnim animScript { get; }
```

#### Property Value
**Type:** Global.FireBirdAnim

### AttackDmg
```csharp
private static DamageInfo AttackDmg { get; }
```

#### Property Value
**Type:** Global.DamageInfo

### ComeBackTime
```csharp
private static float ComeBackTime { get; }
```

#### Property Value
**Type:** System.Single

### Filter
```csharp
private IsolateFilter Filter { get; }
```

#### Property Value
**Type:** Global.IsolateFilter

### PassageDmg
```csharp
public static DamageInfo PassageDmg { get; }
```

#### Property Value
**Type:** Global.DamageInfo

### SkillCoolTime
```csharp
private static float SkillCoolTime { get; }
```

#### Property Value
**Type:** System.Single

## Methods
### ActivateQliphothCounter()
```csharp
public override void ActivateQliphothCounter()
```


### AddBurningPassage(PassageObjectModel)
```csharp
private void AddBurningPassage(PassageObjectModel passage)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `passage` | `Global.PassageObjectModel` |  |

### AddedQliphothCounter()
```csharp
public override void AddedQliphothCounter()
```


### AddQliphothCounter()
```csharp
private void AddQliphothCounter()
```


### AttackDamage(UnitModel)
```csharp
private void AttackDamage(UnitModel target)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### AttackEnd()
```csharp
private void AttackEnd()
```


### AttackStart(UnitDirection)
```csharp
private void AttackStart(UnitDirection dir)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `dir` | `Global.UnitDirection` |  |

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

### CheckHeal(UseSkill)
```csharp
private bool CheckHeal(UseSkill skill)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

#### Returns
**Type:** System.Boolean

### CheckMoveCondition(WorkerModel)
```csharp
private bool CheckMoveCondition(WorkerModel worker)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

#### Returns
**Type:** System.Boolean

### CheckPassage()
```csharp
private void CheckPassage()
```


### Escape()
```csharp
public override void Escape()
```


### FixedUpdate_Attacking()
```csharp
private void FixedUpdate_Attacking()
```


### FixedUpdate_ComeBack()
```csharp
private void FixedUpdate_ComeBack()
```


### FixedUpdate_Default()
```csharp
private void FixedUpdate_Default()
```


### GetDamageMultiplierInWork(UseSkill)
```csharp
public override float GetDamageMultiplierInWork(UseSkill skill)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

#### Returns
**Type:** System.Single

### GetDistance(UnitModel)
```csharp
private float GetDistance(UnitModel target)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

#### Returns
**Type:** System.Single

### GetNearest(float, bool)
```csharp
private UnitModel GetNearest(float range, bool needDir = true)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `range` | `System.Single` |  |
| `needDir` | `System.Boolean` |  |

#### Returns
**Type:** Global.UnitModel

### GetTargetDirection(UnitModel)
```csharp
private UnitDirection GetTargetDirection(UnitModel target)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

#### Returns
**Type:** Global.UnitDirection

### GetTargetInAll()
```csharp
private WorkerModel GetTargetInAll()
```


#### Returns
**Type:** Global.WorkerModel

### GetTargetInSefira(Sefira)
```csharp
private WorkerModel GetTargetInSefira(Sefira sefira)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.Sefira` |  |

#### Returns
**Type:** Global.WorkerModel

### GetTargets(float, bool)
```csharp
public List<UnitModel> GetTargets(float range, bool needDir = true)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `range` | `System.Single` |  |
| `needDir` | `System.Boolean` |  |

#### Returns
**Type:** System.Collections.Generic.List{UnitModel}

### GetWorkersInAll()
```csharp
private List<WorkerModel> GetWorkersInAll()
```


#### Returns
**Type:** System.Collections.Generic.List{WorkerModel}

### GetWorkersInSefira(Sefira)
```csharp
private List<WorkerModel> GetWorkersInSefira(Sefira sefira)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.Sefira` |  |

#### Returns
**Type:** System.Collections.Generic.List{WorkerModel}

### HealStart(AgentModel)
```csharp
private void HealStart(AgentModel target)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.AgentModel` |  |

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

### IsInRange(UnitModel, float)
```csharp
private bool IsInRange(UnitModel target, float range)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `range` | `System.Single` |  |

#### Returns
**Type:** System.Boolean

### IsInView(UnitModel)
```csharp
private bool IsInView(UnitModel target)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

#### Returns
**Type:** System.Boolean

### IsSuppressable()
```csharp
public override bool IsSuppressable()
```


#### Returns
**Type:** System.Boolean

### MakeMovement(bool)
```csharp
private void MakeMovement(bool init = false)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `init` | `System.Boolean` |  |

### MakeMovement_Back()
```csharp
private void MakeMovement_Back()
```


### OnCastEnd()
```csharp
public void OnCastEnd()
```


### OnDelayEnd()
```csharp
public void OnDelayEnd()
```


### OnFinishWork(UseSkill)
```csharp
public override void OnFinishWork(UseSkill skill)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

### OnHeal()
```csharp
public void OnHeal()
```


### OnHealEnd()
```csharp
public void OnHealEnd()
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


### OnSkillGoalComplete(UseSkill)
```csharp
public override void OnSkillGoalComplete(UseSkill skill)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

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


### Present()
```csharp
private void Present()
```


### ReducedQliphothCounter()
```csharp
public override void ReducedQliphothCounter()
```


### RemoveBurningPassage()
```csharp
private void RemoveBurningPassage()
```


### RoomSpriteInit()
```csharp
public override void RoomSpriteInit()
```


### SetFilterAlpha()
```csharp
private void SetFilterAlpha()
```


### Shoot()
```csharp
private void Shoot()
```


### SpeedDown()
```csharp
private void SpeedDown()
```


### SpeedUp()
```csharp
private void SpeedUp()
```


### StopMovement()
```csharp
private void StopMovement()
```


### SubQliphothCounter()
```csharp
private void SubQliphothCounter()
```


### TreeOff()
```csharp
private void TreeOff()
```


### TreeOn()
```csharp
private void TreeOn()
```


### UniqueEscape()
```csharp
public override void UniqueEscape()
```


## Inherited Members
[isolateSpriteSrc](/api/Global/Abnormalities/CreatureBase/CreatureBase#isolatespritesrc), [model](/api/Global/Abnormalities/CreatureBase/CreatureBase#model), [skill](/api/Global/Abnormalities/CreatureBase/CreatureBase#skill), [kitEvent](/api/Global/Abnormalities/CreatureBase/CreatureBase#kitevent), [hasUniqueEscapeLogic](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueescapelogic), [isWorkAllocated](/api/Global/Abnormalities/CreatureBase/CreatureBase#isworkallocated), [_allocatedAgent](/api/Global/Abnormalities/CreatureBase/CreatureBase#allocatedagent), [damage](/api/Global/Abnormalities/CreatureBase/CreatureBase#damage), [OnReleaseSpecialTip](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleasespecialtip), [specialSkillTipParamList](/api/Global/Abnormalities/CreatureBase/CreatureBase#specialskilltipparamlist), [_check](/api/Global/Abnormalities/CreatureBase/CreatureBase#check), [SetModel(CreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#setmodel-creaturemodel), [OnInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#oninit), [OnViewInitPrev(CreatureUnit)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onviewinitprev-creatureunit), [OnFixedUpdate(CreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfixedupdate-creaturemodel), [OnFixedUpdateInSkill(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfixedupdateinskill-useskill), [OnSkillFailWorkTick(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillfailworktick-useskill), [OnSkillSuccessWorkTick(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillsuccessworktick-useskill), [OnSkillTickUpdate(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskilltickupdate-useskill), [PermitCancelCurrentWork()](/api/Global/Abnormalities/CreatureBase/CreatureBase#permitcancelcurrentwork), [GetKitCreatureProcessTime()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getkitcreatureprocesstime), [OnBonusWorkProb()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onbonusworkprob), [TranformWorkProb(float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#tranformworkprob-float), [OnEnterRoom(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onenterroom-useskill), [OnWorkCoolTimeEnd(CreatureFeelingState)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkcooltimeend-creaturefeelingstate), [GetSpecialSkill()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getspecialskill), [GetDebugText()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdebugtext), [OnTimerEnd()](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontimerend), [MakeEffect(IsolateRoom, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffect-isolateroom-int), [MakeEffectAlter(IsolateRoom, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectalter-isolateroom-int), [Prob(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#prob-int), [isAttackInWorkProcess()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isattackinworkprocess), [OnAttackInWorkProcess(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onattackinworkprocess-useskill), [AttackProcess(UnitModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#attackprocess-unitmodel), [AutoFeelingDown()](/api/Global/Abnormalities/CreatureBase/CreatureBase#autofeelingdown), [AgentAnimCalled(int, WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#agentanimcalled-int-workermodel), [MakingEffect(string, float, string, Transform, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float-string-transform-int), [MakingEffect(string, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float), [MakeEffectAttachedToHead(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectattachedtohead-string), [MakingEffect(string, float, string, Vector3, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float-string-vector3-int), [OnAgentWorkEndAnimationPlayed(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentworkendanimationplayed-useskill), [OnAgentAllocateWork(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentallocatework-agentmodel), [OnAllocatedWork(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onallocatedwork-agentmodel), [OnReleaseWorkAllocated()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleaseworkallocated), [ObserveLevelChangeForSpecialSkillTip()](/api/Global/Abnormalities/CreatureBase/CreatureBase#observelevelchangeforspecialskilltip), [OnObserveLevelChanged()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onobservelevelchanged), [HasUniqueProcessWorkNarration()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueprocessworknarration), [UniqueProcessWorkNarration(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniqueprocessworknarration-useskill), [RoomEscapeSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomescapespriteon), [RoomEscapeSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomescapespriteoff), [RoomSkillSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomskillspriteon), [RoomSkillSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomskillspriteoff), [RoomStateSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomstatespriteon), [RoomStateSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomstatespriteoff), [OnForceSpecialSkillTipReveal(string, params object[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onforcespecialskilltipreveal-string-params-object), [OnWorkReleaseSpeicalSkillTipReveal(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkreleasespeicalskilltipreveal-string), [OnWorkReleaseTipUpdate(params object[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkreleasetipupdate-params-object), [OnAgentAnimatorReseted()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentanimatorreseted), [SpecialEnergyTick()](/api/Global/Abnormalities/CreatureBase/CreatureBase#specialenergytick), [OnFeverTimeOver()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfevertimeover), [OnOverlayIsolateWork()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onoverlayisolatework), [OnOverlayIsolateObserve()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onoverlayisolateobserve), [OnOpenObserveWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopenobservewindow), [OnOpenWorkWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopenworkwindow), [OnOpenCollectionWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopencollectionwindow), [DelayAttackMotion(float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#delayattackmotion-float), [GetRealTargets()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getrealtargets), [HasScriptSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasscriptsavedata), [GetSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getsavedata), [LoadData(Dictionary<string, object>)](/api/Global/Abnormalities/CreatureBase/CreatureBase#loaddata-dictionary-string-object), [LoadScriptData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#loadscriptdata), [SaveScriptData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#savescriptdata), [ExistSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#existsavedata), [RemoveSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#removesavedata), [ReplaceCommand(CreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#replacecommand-creaturemodel), [OnGamemanagerInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#ongamemanagerinit), [MakeEffectGlobalPos(string, Vector3)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectglobalpos-string-vector3), [MakeEffectGlobalPosNonTrans(string, Vector3)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectglobalposnontrans-string-vector3), [CanObservedByAgent(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#canobservedbyagent-agentmodel), [MakeSound(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string), [MakeSound(string, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string-float), [MakeSound(string, AudioRolloffMode)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string-audiorolloffmode), [MakeSoundQueue(params string[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesoundqueue-params-string), [MakeSoundLoop(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesoundloop-string), [OnViewDestroy()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onviewdestroy), [IsWorkable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isworkable), [HasUniqueMaxObservationFinish()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquemaxobservationfinish), [UniqueMaxObservationFinish(Desc)](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquemaxobservationfinish-desc), [OnChildSuppressed(ChildCreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onchildsuppressed-childcreaturemodel), [MakeChildCreature(UnitModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makechildcreature-unitmodel), [OnKillWorker(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onkillworker-workermodel), [GenPursueCommandAlter(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#genpursuecommandalter-workermodel), [OnAfterSuppressed()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onaftersuppressed), [hasUniqueDeadScene()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquedeadscene), [SetHpSlider(Slider)](/api/Global/Abnormalities/CreatureBase/CreatureBase#sethpslider-slider), [SetCastingSlider(Slider)](/api/Global/Abnormalities/CreatureBase/CreatureBase#setcastingslider-slider), [HasUniqueAttackDealy()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueattackdealy), [OnTakePhysicalDamage(UnitModel, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontakephysicaldamage-unitmodel-float), [HasUniqueFaction()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquefaction), [OnWorkerPanic(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkerpanic-workermodel), [OnSelectMaxObservation(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onselectmaxobservation-int), [OnLoadCreatureName(ref string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onloadcreaturename-ref-string), [IsSuppressableByRoom()](/api/Global/Abnormalities/CreatureBase/CreatureBase#issuppressablebyroom), [OnWorkWindowSkillClicked(long)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkwindowskillclicked-long), [UseDefaultDamageIgnoreMessage(DamageTextEffect)](/api/Global/Abnormalities/CreatureBase/CreatureBase#usedefaultdamageignoremessage-damagetexteffect), [OnWorkAllocated(SkillTypeInfo, AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkallocated-skilltypeinfo-agentmodel), [GetPhysicalDamage(out float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getphysicaldamage-out-float), [GetMentalDamage(out float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getmentaldamage-out-float), [OnSuperArmorBreak()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onsuperarmorbreak), [UniqueStunEffect()](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquestuneffect), [HasEscapeUI()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasescapeui), [HasRoomCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasroomcounter), [RoomCounterInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomcounterinit), [ResetQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#resetqliphothcounter), [GetMaxWorkCountView()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getmaxworkcountview), [GetQliphothCounterMax()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getqliphothcountermax), [GetRadius()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getradius), [OnElevatorStuck()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onelevatorstuck), [OnWorkClosed(UseSkill, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkclosed-useskill-int), [IsActivatedWorkDesc()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isactivatedworkdesc), [IsSensoredInPassage()](/api/Global/Abnormalities/CreatureBase/CreatureBase#issensoredinpassage), [IsIndirectSuppressable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isindirectsuppressable), [GetRiskLevel()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getrisklevel), [GetName()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getname), [UniqueMoveControl()](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquemovecontrol), [HasUniqueName()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquename), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdamagefactor-unitmodel-damageinfo), [OnInitialBuild()](/api/Global/Abnormalities/CreatureBase/CreatureBase#oninitialbuild), [HasUniqueCollectionCost(string, out string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquecollectioncost-string-out-string), [OnOpenCommandWindow(Button[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopencommandwindow-button), [HasUniqueCommandAction(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquecommandaction-int), [HasUniqueWorkSelect(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueworkselect-int), [ForcelySuccess(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#forcelysuccess-useskill), [ForcelyFail(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#forcelyfail-useskill), [TryRabbitTeleport(MapNode)](/api/Global/Abnormalities/CreatureBase/CreatureBase#tryrabbitteleport-mapnode), [CanEnterRoom()](/api/Global/Abnormalities/CreatureBase/CreatureBase#canenterroom), [AllocatedAgent](/api/Global/Abnormalities/CreatureBase/CreatureBase#allocatedagent), [skillTriggerCheck](/api/Global/Abnormalities/CreatureBase/CreatureBase#skilltriggercheck), [Unit](/api/Global/Abnormalities/CreatureBase/CreatureBase#unit), [GetSaveSrc](/api/Global/Abnormalities/CreatureBase/CreatureBase#getsavesrc), [movable](/api/Global/Abnormalities/CreatureBase/CreatureBase#movable), [currentPassage](/api/Global/Abnormalities/CreatureBase/CreatureBase#currentpassage), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)







