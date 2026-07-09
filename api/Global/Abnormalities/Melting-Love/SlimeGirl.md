---
uid: Global.SlimeGirl
canonical_path: /api/Global/Misc/SlimeGirl
---
# Class SlimeGirl
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class SlimeGirl : SlimeCreature
```
> This section may have incomplete or incorrect information.
{.is-warning}


Melting Love.




## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase](/api/Global/Abnormalities/Melting-Love/SlimeCreature) → SlimeGirl

## Constructors
### SlimeGirl()
```csharp
public SlimeGirl()
```

## Fields
### _animScript
```csharp
private SlimeGirlAnim _animScript
```


#### Field Value
**Type:** Global.SlimeGirlAnim

### _atkDmgMax
```csharp
private const int _atkDmgMax = 25
```


#### Field Value
**Type:** System.Int32

### _atkDmgMin
```csharp
private const int _atkDmgMin = 15
```


#### Field Value
**Type:** System.Int32

### _atkDmgType
```csharp
private const RwbpType _atkDmgType = B
```


#### Field Value
**Type:** Global.RwbpType

### _atkEnrageDmgMax
```csharp
private const int _atkEnrageDmgMax = 32
```


#### Field Value
**Type:** System.Int32

### _atkEnrageDmgMin
```csharp
private const int _atkEnrageDmgMin = 20
```


#### Field Value
**Type:** System.Int32

### _atkEnrageDmgType
```csharp
private const RwbpType _atkEnrageDmgType = B
```


#### Field Value
**Type:** Global.RwbpType

### _healCoolInitTimeMax
```csharp
private const float _healCoolInitTimeMax = 20
```


#### Field Value
**Type:** System.Single

### _healCoolInitTimeMin
```csharp
private const float _healCoolInitTimeMin = 15
```


#### Field Value
**Type:** System.Single

### _healCoolTimeMax
```csharp
private const float _healCoolTimeMax = 18
```


#### Field Value
**Type:** System.Single

### _healCoolTimeMin
```csharp
private const float _healCoolTimeMin = 12
```


#### Field Value
**Type:** System.Single

### _healTimeMax
```csharp
private const float _healTimeMax = 8
```


#### Field Value
**Type:** System.Single

### _healTimeMin
```csharp
private const float _healTimeMin = 7
```


#### Field Value
**Type:** System.Single

### _healValueMax
```csharp
private const float _healValueMax = 200
```


#### Field Value
**Type:** System.Single

### _healValueMin
```csharp
private const float _healValueMin = 200
```


#### Field Value
**Type:** System.Single

### _mentalHealMax
```csharp
private const float _mentalHealMax = 35
```


#### Field Value
**Type:** System.Single

### _mentalHealMin
```csharp
private const float _mentalHealMin = 25
```


#### Field Value
**Type:** System.Single

### _phase
```csharp
private SlimeGirl.Phase _phase
```

#### Field Value
**Type:** Global.SlimeGirl.Phase

### _sacrifce
```csharp
private SlimePawn _sacrifce
```


#### Field Value
**Type:** Global.SlimePawn

### _skillCoolInitTimeMax
```csharp
private const float _skillCoolInitTimeMax = 15
```


#### Field Value
**Type:** System.Single

### _skillCoolInitTimeMin
```csharp
private const float _skillCoolInitTimeMin = 10
```


#### Field Value
**Type:** System.Single

### _skillCoolTimeMax
```csharp
private const float _skillCoolTimeMax = 15
```


#### Field Value
**Type:** System.Single

### _skillCoolTimeMin
```csharp
private const float _skillCoolTimeMin = 10
```


#### Field Value
**Type:** System.Single

### _skillDmgMax
```csharp
private const int _skillDmgMax = 45
```


#### Field Value
**Type:** System.Int32

### _skillDmgMin
```csharp
private const int _skillDmgMin = 25
```


#### Field Value
**Type:** System.Int32

### _skillDmgType
```csharp
private const RwbpType _skillDmgType = B
```


#### Field Value
**Type:** Global.RwbpType

### _skillEnrageDmgMax
```csharp
private const int _skillEnrageDmgMax = 60
```


#### Field Value
**Type:** System.Int32

### _skillEnrageDmgMin
```csharp
private const int _skillEnrageDmgMin = 30
```


#### Field Value
**Type:** System.Int32

### _skillEnrageDmgType
```csharp
private const RwbpType _skillEnrageDmgType = B
```


#### Field Value
**Type:** Global.RwbpType

### _state
```csharp
private SlimeGirl.State _state
```

#### Field Value
**Type:** Global.SlimeGirl.State

### ATK_DMG_RANGE
```csharp
private const float ATK_DMG_RANGE = 2
```


#### Field Value
**Type:** System.Single

### ATTACK_RANGE
```csharp
private const float ATTACK_RANGE = 1.5
```


#### Field Value
**Type:** System.Single

### enrageEffect
```csharp
private GameObject enrageEffect
```


#### Field Value
**Type:** UnityEngine.GameObject

### ESCAPE_CONDITION_PAWN_RATIO
```csharp
private const float ESCAPE_CONDITION_PAWN_RATIO = 0.5
```


#### Field Value
**Type:** System.Single

### HEAL_DIST
```csharp
private const float HEAL_DIST = 3.1
```


#### Field Value
**Type:** System.Single

### HEAL_EFFECT_SRC
```csharp
private const string HEAL_EFFECT_SRC = "Effect/RecoverHP"
```


#### Field Value
**Type:** System.String

### HEAL_HP_CONDITION
```csharp
private const float HEAL_HP_CONDITION = 0.6
```


#### Field Value
**Type:** System.Single

### HEAL_RECOGNIZE_RANGE
```csharp
private const float HEAL_RECOGNIZE_RANGE = 15
```


#### Field Value
**Type:** System.Single

### healCoolTimer
```csharp
private Timer healCoolTimer
```


#### Field Value
**Type:** Global.Timer

### healTimer
```csharp
private Timer healTimer
```


#### Field Value
**Type:** Global.Timer

### lover
```csharp
private WorkerModel lover
```


#### Field Value
**Type:** Global.WorkerModel

### LOVER_BONUS_WORK_PROB
```csharp
private const int LOVER_BONUS_WORK_PROB = 10
```


#### Field Value
**Type:** System.Int32

### loverCreature
```csharp
private SlimeLover loverCreature
```


#### Field Value
**Type:** Global.SlimeLover

### MENTAL_HEAL_PROB
```csharp
private const float MENTAL_HEAL_PROB = 1
```


#### Field Value
**Type:** System.Single

### PAUSE_SKILL_ID
```csharp
private const int PAUSE_SKILL_ID = 2
```


#### Field Value
**Type:** System.Int32

### PAUSE_SUCCESS_CONDITION
```csharp
private const int PAUSE_SUCCESS_CONDITION = 24
```


#### Field Value
**Type:** System.Int32

### pawns
```csharp
private List<SlimePawn> pawns
```


#### Field Value
**Type:** System.Collections.Generic.List{SlimePawn}

### RECOGNIZE_RANGE
```csharp
private const float RECOGNIZE_RANGE = 15
```


#### Field Value
**Type:** System.Single

### SKILL_RANGE
```csharp
private const float SKILL_RANGE = 10
```


#### Field Value
**Type:** System.Single

### skillCoolTimer
```csharp
private Timer skillCoolTimer
```


#### Field Value
**Type:** Global.Timer

### UNTARGETABLE_ID
```csharp
private const int UNTARGETABLE_ID = 4
```


#### Field Value
**Type:** System.Int32

## Properties
### animScript
```csharp
public SlimeGirlAnim animScript { get; }
```

#### Property Value
**Type:** Global.SlimeGirlAnim

### AttackDmg
```csharp
private static DamageInfo AttackDmg { get; }
```

#### Property Value
**Type:** Global.DamageInfo

### AttackEnrageDmg
```csharp
private static DamageInfo AttackEnrageDmg { get; }
```

#### Property Value
**Type:** Global.DamageInfo

### HealCoolInitTime
```csharp
private static float HealCoolInitTime { get; }
```

#### Property Value
**Type:** System.Single

### HealCoolTime
```csharp
private static float HealCoolTime { get; }
```

#### Property Value
**Type:** System.Single

### HealTime
```csharp
private static float HealTime { get; }
```

#### Property Value
**Type:** System.Single

### HealValue
```csharp
private static float HealValue { get; }
```

#### Property Value
**Type:** System.Single

### LoverCreature
```csharp
public SlimeLover LoverCreature { get; }
```

#### Property Value
**Type:** Global.SlimeLover

### MentalHealValue
```csharp
private static float MentalHealValue { get; }
```

#### Property Value
**Type:** System.Single

### PawnBufCnt
```csharp
public int PawnBufCnt { get; }
```

#### Property Value
**Type:** System.Int32

### phase
```csharp
public SlimeGirl.Phase phase { get; }
```

#### Property Value
**Type:** Global.SlimeGirl.Phase

### sacrifce
```csharp
public SlimePawn sacrifce { get; private set; }
```

#### Property Value
**Type:** Global.SlimePawn

### SkillCoolInitTime
```csharp
private static float SkillCoolInitTime { get; }
```

#### Property Value
**Type:** System.Single

### SkillCoolTime
```csharp
private static float SkillCoolTime { get; }
```

#### Property Value
**Type:** System.Single

### SkillDmg
```csharp
private static DamageInfo SkillDmg { get; }
```

#### Property Value
**Type:** Global.DamageInfo

### SkillEnrageDmg
```csharp
private static DamageInfo SkillEnrageDmg { get; }
```

#### Property Value
**Type:** Global.DamageInfo

### state
```csharp
public SlimeGirl.State state { get; }
```

#### Property Value
**Type:** Global.SlimeGirl.State

## Methods
### ActivateQliphothCounter()
```csharp
public override void ActivateQliphothCounter()
```


### AttackStart()
```csharp
private void AttackStart()
```


### CheckIfBeingLover(UseSkill)
```csharp
private bool CheckIfBeingLover(UseSkill skill)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

#### Returns
**Type:** System.Boolean

### CheckIfProjectileHit(UnitModel)
```csharp
public bool CheckIfProjectileHit(UnitModel target)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

#### Returns
**Type:** System.Boolean

### ClearPawns()
```csharp
private void ClearPawns()
```


### Enrage()
```csharp
private void Enrage()
```


### Escape()
```csharp
public override void Escape()
```


### FinishHeal()
```csharp
private void FinishHeal()
```


### GetAttackDamageTarget()
```csharp
private UnitModel GetAttackDamageTarget()
```


#### Returns
**Type:** Global.UnitModel

### GetAttackTarget()
```csharp
private UnitModel GetAttackTarget()
```


#### Returns
**Type:** Global.UnitModel

### GetNearestPawn()
```csharp
private SlimePawn GetNearestPawn()
```


#### Returns
**Type:** Global.SlimePawn

### GetPawnBufWorkers()
```csharp
private WorkerModel[] GetPawnBufWorkers()
```


#### Returns
**Type:** Global.WorkerModel[]

### Heal()
```csharp
private void Heal()
```


### IsAttacking()
```csharp
private bool IsAttacking()
```


#### Returns
**Type:** System.Boolean

### IsHealing()
```csharp
private bool IsHealing()
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

### MakeChildCreature(UnitModel, bool)
```csharp
public ChildCreatureModel MakeChildCreature(UnitModel origin, bool isLover)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `origin` | `Global.UnitModel` |  |
| `isLover` | `System.Boolean` |  |

#### Returns
**Type:** Global.ChildCreatureModel

### MakeEffect(GameObject, string, bool)
```csharp
private GameObject MakeEffect(GameObject position, string src, bool setParent = true)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `position` | `UnityEngine.GameObject` |  |
| `src` | `System.String` |  |
| `setParent` | `System.Boolean` |  |

#### Returns
**Type:** UnityEngine.GameObject

### MakeHealEffect()
```csharp
private GameObject MakeHealEffect()
```


#### Returns
**Type:** UnityEngine.GameObject

### MakeLover(WorkerModel)
```csharp
private void MakeLover(WorkerModel worker)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

### MakeMovement()
```csharp
private void MakeMovement()
```


### MakeMovement(MovableObjectNode)
```csharp
private void MakeMovement(MovableObjectNode movable)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `movable` | `Global.MovableObjectNode` |  |

### MakeMovement(SlimePawn)
```csharp
private void MakeMovement(SlimePawn nearestPawn)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `nearestPawn` | `Global.SlimePawn` |  |

### MentalHeal(WorkerModel)
```csharp
private void MentalHeal(WorkerModel worker)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

### OnAttackDamageTimeCalled()
```csharp
public override void OnAttackDamageTimeCalled()
```


### OnAttackEnd()
```csharp
public override void OnAttackEnd()
```


### OnBonusWorkProb()
```csharp
public override int OnBonusWorkProb()
```


#### Returns
**Type:** System.Int32

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

### OnHealEnd()
```csharp
public void OnHealEnd()
```


### OnJoin()
```csharp
public void OnJoin()
```


### OnLoverCreatureDie()
```csharp
public void OnLoverCreatureDie()
```


### OnLoverDie()
```csharp
public void OnLoverDie()
```


### OnLoverGen()
```csharp
public void OnLoverGen()
```


### OnProjectileHit(UnitModel)
```csharp
public void OnProjectileHit(UnitModel target)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

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


### OnSkillEnd()
```csharp
public void OnSkillEnd()
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


### RemoveEnrageEffect()
```csharp
private void RemoveEnrageEffect()
```


### RemoveLover()
```csharp
public void RemoveLover()
```


### SkillStart()
```csharp
private void SkillStart()
```


### StartHeal(SlimePawn)
```csharp
private void StartHeal(SlimePawn nearestPawn)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `nearestPawn` | `Global.SlimePawn` |  |

### StopMovement()
```csharp
protected override void StopMovement()
```


### SubQliphothCounter()
```csharp
private void SubQliphothCounter()
```


### SubQliphothCounterAll()
```csharp
private void SubQliphothCounterAll()
```


### TryHeal(SlimePawn)
```csharp
private bool TryHeal(SlimePawn nearestPawn)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `nearestPawn` | `Global.SlimePawn` |  |

#### Returns
**Type:** System.Boolean

### UniqueEscape()
```csharp
public override void UniqueEscape()
```


## Inherited Members
[motionDelayTimer](/api/Global/Abnormalities/CreatureBase/CreatureBase#isolatespritesrc), [model](/api/Global/Abnormalities/CreatureBase/CreatureBase#model), [skill](/api/Global/Abnormalities/CreatureBase/CreatureBase#skill), [kitEvent](/api/Global/Abnormalities/CreatureBase/CreatureBase#kitevent), [hasUniqueEscapeLogic](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueescapelogic), [isWorkAllocated](/api/Global/Abnormalities/CreatureBase/CreatureBase#isworkallocated), [_allocatedAgent](/api/Global/Abnormalities/CreatureBase/CreatureBase#allocatedagent), [damage](/api/Global/Abnormalities/CreatureBase/CreatureBase#damage), [OnReleaseSpecialTip](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleasespecialtip), [specialSkillTipParamList](/api/Global/Abnormalities/CreatureBase/CreatureBase#specialskilltipparamlist), [_check](/api/Global/Abnormalities/CreatureBase/CreatureBase#check), [SetModel(CreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#setmodel-creaturemodel), [OnInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#oninit), [OnViewInitPrev(CreatureUnit)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onviewinitprev-creatureunit), [OnFixedUpdateInSkill(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfixedupdateinskill-useskill), [OnSkillFailWorkTick(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillfailworktick-useskill), [OnSkillSuccessWorkTick(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillsuccessworktick-useskill), [OnSkillTickUpdate(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskilltickupdate-useskill), [PermitCancelCurrentWork()](/api/Global/Abnormalities/CreatureBase/CreatureBase#permitcancelcurrentwork), [GetKitCreatureProcessTime()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getkitcreatureprocesstime), [GetDamageMultiplierInWork(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdamagemultiplierinwork-useskill), [TranformWorkProb(float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#tranformworkprob-float), [OnEnterRoom(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onenterroom-useskill), [OnWorkCoolTimeEnd(CreatureFeelingState)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkcooltimeend-creaturefeelingstate), [GetSpecialSkill()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getspecialskill), [GetDebugText()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdebugtext), [OnTimerEnd()](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontimerend), [MakeEffect(IsolateRoom, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffect-isolateroom-int), [MakeEffectAlter(IsolateRoom, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectalter-isolateroom-int), [Prob(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#prob-int), [isAttackInWorkProcess()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isattackinworkprocess), [OnAttackInWorkProcess(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onattackinworkprocess-useskill), [AttackProcess(UnitModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#attackprocess-unitmodel), [AutoFeelingDown()](/api/Global/Abnormalities/CreatureBase/CreatureBase#autofeelingdown), [AgentAnimCalled(int, WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#agentanimcalled-int-workermodel), [MakingEffect(string, float, string, Transform, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float-string-transform-int), [MakingEffect(string, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float), [MakeEffectAttachedToHead(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectattachedtohead-string), [MakingEffect(string, float, string, Vector3, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float-string-vector3-int), [OnAgentWorkEndAnimationPlayed(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentworkendanimationplayed-useskill), [OnAgentAllocateWork(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentallocatework-agentmodel), [OnAllocatedWork(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onallocatedwork-agentmodel), [OnReleaseWorkAllocated()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleaseworkallocated), [ObserveLevelChangeForSpecialSkillTip()](/api/Global/Abnormalities/CreatureBase/CreatureBase#observelevelchangeforspecialskilltip), [OnObserveLevelChanged()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onobservelevelchanged), [HasUniqueProcessWorkNarration()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueprocessworknarration), [UniqueProcessWorkNarration(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniqueprocessworknarration-useskill), [RoomSpriteInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomspriteinit), [RoomEscapeSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomescapespriteon), [RoomEscapeSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomescapespriteoff), [RoomSkillSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomskillspriteon), [RoomSkillSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomskillspriteoff), [RoomStateSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomstatespriteon), [RoomStateSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomstatespriteoff), [OnForceSpecialSkillTipReveal(string, params object[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onforcespecialskilltipreveal-string-params-object), [OnWorkReleaseSpeicalSkillTipReveal(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkreleasespeicalskilltipreveal-string), [OnWorkReleaseTipUpdate(params object[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkreleasetipupdate-params-object), [OnAgentAnimatorReseted()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentanimatorreseted), [SpecialEnergyTick()](/api/Global/Abnormalities/CreatureBase/CreatureBase#specialenergytick), [OnFeverTimeOver()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfevertimeover), [OnOverlayIsolateWork()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onoverlayisolatework), [OnOverlayIsolateObserve()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onoverlayisolateobserve), [OnOpenObserveWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopenobservewindow), [OnOpenWorkWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopenworkwindow), [OnOpenCollectionWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopencollectionwindow), [DelayAttackMotion(float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#delayattackmotion-float), [IsAttackTargetable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isattacktargetable), [GetRealTargets()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getrealtargets), [HasScriptSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasscriptsavedata), [GetSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getsavedata), [LoadData(Dictionary<string, object>)](/api/Global/Abnormalities/CreatureBase/CreatureBase#loaddata-dictionary-string-object), [LoadScriptData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#loadscriptdata), [SaveScriptData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#savescriptdata), [ExistSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#existsavedata), [RemoveSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#removesavedata), [ReplaceCommand(CreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#replacecommand-creaturemodel), [OnGamemanagerInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#ongamemanagerinit), [MakeEffectGlobalPos(string, Vector3)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectglobalpos-string-vector3), [MakeEffectGlobalPosNonTrans(string, Vector3)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectglobalposnontrans-string-vector3), [CanObservedByAgent(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#canobservedbyagent-agentmodel), [MakeSound(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string), [MakeSound(string, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string-float), [MakeSound(string, AudioRolloffMode)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string-audiorolloffmode), [MakeSoundQueue(params string[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesoundqueue-params-string), [MakeSoundLoop(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesoundloop-string), [OnViewDestroy()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onviewdestroy), [IsWorkable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isworkable), [HasUniqueMaxObservationFinish()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquemaxobservationfinish), [UniqueMaxObservationFinish(Desc)](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquemaxobservationfinish-desc), [OnChildSuppressed(ChildCreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onchildsuppressed-childcreaturemodel), [MakeChildCreature(UnitModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makechildcreature-unitmodel), [OnKillWorker(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onkillworker-workermodel), [GenPursueCommandAlter(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#genpursuecommandalter-workermodel), [OnAfterSuppressed()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onaftersuppressed), [hasUniqueDeadScene()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquedeadscene), [SetHpSlider(Slider)](/api/Global/Abnormalities/CreatureBase/CreatureBase#sethpslider-slider), [SetCastingSlider(Slider)](/api/Global/Abnormalities/CreatureBase/CreatureBase#setcastingslider-slider), [HasUniqueAttackDealy()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueattackdealy), [CanTakeDamage(UnitModel, DamageInfo)](/api/Global/Abnormalities/CreatureBase/CreatureBase#cantakedamage-unitmodel-damageinfo), [OnTakePhysicalDamage(UnitModel, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontakephysicaldamage-unitmodel-float), [HasUniqueFaction()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquefaction), [OnWorkerPanic(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkerpanic-workermodel), [OnSelectMaxObservation(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onselectmaxobservation-int), [OnLoadCreatureName(ref string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onloadcreaturename-ref-string), [IsSuppressable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#issuppressable), [IsSuppressableByRoom()](/api/Global/Abnormalities/CreatureBase/CreatureBase#issuppressablebyroom), [IsAutoSuppressable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isautosuppressable), [OnWorkWindowSkillClicked(long)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkwindowskillclicked-long), [UseDefaultDamageIgnoreMessage(DamageTextEffect)](/api/Global/Abnormalities/CreatureBase/CreatureBase#usedefaultdamageignoremessage-damagetexteffect), [OnWorkAllocated(SkillTypeInfo, AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkallocated-skilltypeinfo-agentmodel), [GetPhysicalDamage(out float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getphysicaldamage-out-float), [GetMentalDamage(out float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getmentaldamage-out-float), [OnSuperArmorBreak()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onsuperarmorbreak), [UniqueStunEffect()](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquestuneffect), [HasEscapeUI()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasescapeui), [HasRoomCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasroomcounter), [RoomCounterInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomcounterinit), [ResetQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#resetqliphothcounter), [GetMaxWorkCountView()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getmaxworkcountview), [GetQliphothCounterMax()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getqliphothcountermax), [ReducedQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#reducedqliphothcounter), [AddedQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#addedqliphothcounter), [OnTakeDamage(UnitModel, DamageInfo, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontakedamage-unitmodel-damageinfo-float), [GetRadius()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getradius), [OnElevatorStuck()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onelevatorstuck), [OnWorkClosed(UseSkill, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkclosed-useskill-int), [IsActivatedWorkDesc()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isactivatedworkdesc), [IsSensoredInPassage()](/api/Global/Abnormalities/CreatureBase/CreatureBase#issensoredinpassage), [IsIndirectSuppressable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isindirectsuppressable), [GetRiskLevel()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getrisklevel), [UniqueMoveControl()](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquemovecontrol), [HasUniqueName()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquename), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdamagefactor-unitmodel-damageinfo), [OnInitialBuild()](/api/Global/Abnormalities/CreatureBase/CreatureBase#oninitialbuild), [HasUniqueCollectionCost(string, out string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquecollectioncost-string-out-string), [OnOpenCommandWindow(Button[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopencommandwindow-button), [HasUniqueCommandAction(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquecommandaction-int), [HasUniqueWorkSelect(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueworkselect-int), [ForcelySuccess(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#forcelysuccess-useskill), [ForcelyFail(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#forcelyfail-useskill), [TryRabbitTeleport(MapNode)](/api/Global/Abnormalities/CreatureBase/CreatureBase#tryrabbitteleport-mapnode), [CanEnterRoom()](/api/Global/Abnormalities/CreatureBase/CreatureBase#canenterroom), [AllocatedAgent](/api/Global/Abnormalities/CreatureBase/CreatureBase#allocatedagent), [skillTriggerCheck](/api/Global/Abnormalities/CreatureBase/CreatureBase#skilltriggercheck), [Unit](/api/Global/Abnormalities/CreatureBase/CreatureBase#unit), [GetSaveSrc](/api/Global/Abnormalities/CreatureBase/CreatureBase#getsavesrc), [movable](/api/Global/Abnormalities/CreatureBase/CreatureBase#movable), [currentPassage](/api/Global/Abnormalities/CreatureBase/CreatureBase#currentpassage), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)







