---
uid: Global.KnightOfDespair
canonical_path: /api/Global/Misc/KnightOfDespair
---
# Class KnightOfDespair
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class KnightOfDespair : CreatureBase
```
> This section may have incomplete or incorrect information.
{.is-warning}


Knight of Despair. 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase](/api/Global/Abnormalities/CreatureBase/CreatureBase) → KnightOfDespair

## Constructors
### KnightOfDespair()
```csharp
public KnightOfDespair()
```

## Fields
### _attackDelayMax
```csharp
private const float _attackDelayMax = 3
```


#### Field Value
**Type:** System.Single

### _attackDelayMin
```csharp
private const float _attackDelayMin = 2
```


#### Field Value
**Type:** System.Single

### _attackDelayTimer
```csharp
private Timer _attackDelayTimer
```


#### Field Value
**Type:** Global.Timer

### _blessedWorker
```csharp
private WorkerModel _blessedWorker
```


#### Field Value
**Type:** Global.WorkerModel

### _currentAttackAnimIndex
```csharp
private Queue<int> _currentAttackAnimIndex
```


#### Field Value
**Type:** System.Collections.Generic.Queue{System.Int32}

### _currentDestNode
```csharp
private MapNode _currentDestNode
```


#### Field Value
**Type:** Global.MapNode

### _currentTarget
```csharp
private UnitModel _currentTarget
```


#### Field Value
**Type:** Global.UnitModel

### _currentTeleportNode
```csharp
private MapNode _currentTeleportNode
```


#### Field Value
**Type:** Global.MapNode

### _escapeDefaultSound
```csharp
private SoundEffectPlayer _escapeDefaultSound
```


#### Field Value
**Type:** Global.SoundEffectPlayer

### _escapeSoundFreqMax
```csharp
private const float _escapeSoundFreqMax = 40
```


#### Field Value
**Type:** System.Single

### _escapeSoundFreqMin
```csharp
private const float _escapeSoundFreqMin = 30
```


#### Field Value
**Type:** System.Single

### _escapeSoundTimer
```csharp
private Timer _escapeSoundTimer
```


#### Field Value
**Type:** Global.Timer

### _isAtttackig
```csharp
private bool _isAtttackig
```


#### Field Value
**Type:** System.Boolean

### _isBlessing
```csharp
private bool _isBlessing
```


#### Field Value
**Type:** System.Boolean

### _isMoving
```csharp
private bool _isMoving
```


#### Field Value
**Type:** System.Boolean

### _isTeleporting
```csharp
private bool _isTeleporting
```


#### Field Value
**Type:** System.Boolean

### _readyForTeleport
```csharp
private bool _readyForTeleport
```


#### Field Value
**Type:** System.Boolean

### _teleportAfterDelay
```csharp
private Timer _teleportAfterDelay
```


#### Field Value
**Type:** Global.Timer

### _teleportDelayMax
```csharp
private const float _teleportDelayMax = 30
```


#### Field Value
**Type:** System.Single

### _teleportDelayMin
```csharp
private const float _teleportDelayMin = 15
```


#### Field Value
**Type:** System.Single

### _teleportTimer
```csharp
private Timer _teleportTimer
```


#### Field Value
**Type:** Global.Timer

### blessEffect
```csharp
private GameObject blessEffect
```


#### Field Value
**Type:** UnityEngine.GameObject

### blessEffectSrc
```csharp
public const string blessEffectSrc = "Effect/Creature/KnightOfDespair/KnightBufAurora"
```


#### Field Value
**Type:** System.String

### damageEffectSrc
```csharp
public const string damageEffectSrc = "Effect/Creature/KnightOfDespair/Spade"
```


#### Field Value
**Type:** System.String

### Damageinfo
```csharp
private static DamageInfo Damageinfo
```


#### Field Value
**Type:** Global.DamageInfo

### DefaultAttackIndex
```csharp
private static int[] DefaultAttackIndex
```


#### Field Value
**Type:** System.Int32[]

### LogPrefix
```csharp
private static string LogPrefix
```


#### Field Value
**Type:** System.String

### renableList
```csharp
private List<KnightOfDespair.SwordRenable> renableList
```

#### Field Value
**Type:** System.Collections.Generic.List{KnightOfDespair.SwordRenable}

### SoundKey_Attack
```csharp
public const string SoundKey_Attack = "Attack"
```


#### Field Value
**Type:** System.String

### SoundKey_Aura
```csharp
public const string SoundKey_Aura = "Aura"
```


#### Field Value
**Type:** System.String

### SoundKey_Bless
```csharp
public const string SoundKey_Bless = "Bless"
```


#### Field Value
**Type:** System.String

### SoundKey_Blink_1
```csharp
public const string SoundKey_Blink_1 = "Blink_1"
```


#### Field Value
**Type:** System.String

### SoundKey_Blink_2
```csharp
public const string SoundKey_Blink_2 = "Blink_2"
```


#### Field Value
**Type:** System.String

### SoundKey_Change_1
```csharp
public const string SoundKey_Change_1 = "Change_1"
```


#### Field Value
**Type:** System.String

### SoundKey_Change_2
```csharp
public const string SoundKey_Change_2 = "Change_2"
```


#### Field Value
**Type:** System.String

### SoundKey_Dead
```csharp
public const string SoundKey_Dead = "Dead"
```


#### Field Value
**Type:** System.String

### SoundKey_Default
```csharp
public const string SoundKey_Default = "Default"
```


#### Field Value
**Type:** System.String

### TeleportAppearEffect
```csharp
public const string TeleportAppearEffect = "Effect/Creature/MagicalGirl/Appear"
```


#### Field Value
**Type:** System.String

### TeleportDisappearEffect
```csharp
public const string TeleportDisappearEffect = "Effect/Creature/MagicalGirl/Disappear"
```


#### Field Value
**Type:** System.String

## Properties
### AnimScript
```csharp
public KnightOfDespairAnim AnimScript { get; }
```

#### Property Value
**Type:** Global.KnightOfDespairAnim

### AttackDelay
```csharp
private float AttackDelay { get; }
```

#### Property Value
**Type:** System.Single

### BlessedWorker
```csharp
public WorkerModel BlessedWorker { get; }
```

#### Property Value
**Type:** Global.WorkerModel

### CurrentTarget
```csharp
public UnitModel CurrentTarget { get; }
```

#### Property Value
**Type:** Global.UnitModel

### TeleportDelay
```csharp
private float TeleportDelay { get; }
```

#### Property Value
**Type:** System.Single

## Methods
### ActivateBless(WorkerModel)
```csharp
private void ActivateBless(WorkerModel target)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |

### AttackEnd()
```csharp
public void AttackEnd()
```


### CheckBless(UseSkill)
```csharp
private bool CheckBless(UseSkill skill)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

#### Returns
**Type:** System.Boolean

### CheckSword()
```csharp
private void CheckSword()
```


### ClearBlessed()
```csharp
public void ClearBlessed()
```


### Escape()
```csharp
public override void Escape()
```


### GetAttackIndex()
```csharp
private List<int> GetAttackIndex()
```


#### Returns
**Type:** System.Collections.Generic.List{System.Int32}

### GetNearTargets()
```csharp
private List<UnitModel> GetNearTargets()
```


#### Returns
**Type:** System.Collections.Generic.List{UnitModel}

### GetRandomDestination()
```csharp
private MapNode GetRandomDestination()
```


#### Returns
**Type:** Global.MapNode

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

### IsActivatedWorkDesc()
```csharp
public override bool IsActivatedWorkDesc()
```


#### Returns
**Type:** System.Boolean

### IsTeleportable()
```csharp
private bool IsTeleportable()
```


#### Returns
**Type:** System.Boolean

### Log(string)
```csharp
public static void Log(string log)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `log` | `System.String` |  |

### MakeBlessSound()
```csharp
public void MakeBlessSound()
```


### MakeDeadSound()
```csharp
public void MakeDeadSound()
```


### MakeDefaultSound()
```csharp
private void MakeDefaultSound()
```


### MakeRandomMovement()
```csharp
private void MakeRandomMovement()
```


### MakeSound(string, Vector3)
```csharp
public SoundEffectPlayer MakeSound(string key, Vector3 pos)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |
| `pos` | `UnityEngine.Vector3` |  |

#### Returns
**Type:** Global.SoundEffectPlayer

### OnAfterSuppressed()
```csharp
public override bool OnAfterSuppressed()
```


#### Returns
**Type:** System.Boolean

### OnBlessAnimEnded()
```csharp
public void OnBlessAnimEnded()
```


### OnBlessedWorkerEndangered()
```csharp
public void OnBlessedWorkerEndangered()
```


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


### OnSwordArrived(ProjectileModel)
```csharp
public void OnSwordArrived(ProjectileModel proj)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `proj` | `Global.ProjectileModel` |  |

### OnTeleport()
```csharp
public void OnTeleport()
```


### OnThrowSword(KnightOfDespairSword)
```csharp
public void OnThrowSword(KnightOfDespairSword sword)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `sword` | `Global.KnightOfDespairSword` |  |

### OnTransformEnded()
```csharp
public void OnTransformEnded()
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


### ResetState()
```csharp
private void ResetState()
```


### StartAttack(UnitModel)
```csharp
public void StartAttack(UnitModel mainTarget)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `mainTarget` | `Global.UnitModel` |  |

### StartTeleport()
```csharp
private void StartTeleport()
```


### StopAttack()
```csharp
private void StopAttack()
```


### StopMovement(bool)
```csharp
private void StopMovement(bool clearDest = false)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `clearDest` | `System.Boolean` |  |

### UniqueEscape()
```csharp
public override void UniqueEscape()
```


## Inherited Members
[isolateSpriteSrc](/api/Global/Abnormalities/CreatureBase/CreatureBase#isolatespritesrc), [model](/api/Global/Abnormalities/CreatureBase/CreatureBase#model), [skill](/api/Global/Abnormalities/CreatureBase/CreatureBase#skill), [kitEvent](/api/Global/Abnormalities/CreatureBase/CreatureBase#kitevent), [hasUniqueEscapeLogic](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueescapelogic), [isWorkAllocated](/api/Global/Abnormalities/CreatureBase/CreatureBase#isworkallocated), [_allocatedAgent](/api/Global/Abnormalities/CreatureBase/CreatureBase#allocatedagent), [damage](/api/Global/Abnormalities/CreatureBase/CreatureBase#damage), [OnReleaseSpecialTip](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleasespecialtip), [specialSkillTipParamList](/api/Global/Abnormalities/CreatureBase/CreatureBase#specialskilltipparamlist), [_check](/api/Global/Abnormalities/CreatureBase/CreatureBase#check), [SetModel(CreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#setmodel-creaturemodel), [OnInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#oninit), [OnViewInitPrev(CreatureUnit)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onviewinitprev-creatureunit), [OnFixedUpdate(CreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfixedupdate-creaturemodel), [OnFixedUpdateInSkill(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfixedupdateinskill-useskill), [OnSkillFailWorkTick(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillfailworktick-useskill), [OnSkillSuccessWorkTick(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillsuccessworktick-useskill), [OnSkillTickUpdate(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskilltickupdate-useskill), [PermitCancelCurrentWork()](/api/Global/Abnormalities/CreatureBase/CreatureBase#permitcancelcurrentwork), [GetKitCreatureProcessTime()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getkitcreatureprocesstime), [OnBonusWorkProb()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onbonusworkprob), [GetDamageMultiplierInWork(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdamagemultiplierinwork-useskill), [TranformWorkProb(float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#tranformworkprob-float), [OnEnterRoom(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onenterroom-useskill), [OnReleaseWork(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleasework-useskill), [OnFinishWork(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfinishwork-useskill), [OnWorkCoolTimeEnd(CreatureFeelingState)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkcooltimeend-creaturefeelingstate), [GetSpecialSkill()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getspecialskill), [GetDebugText()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdebugtext), [OnTimerEnd()](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontimerend), [MakeEffect(IsolateRoom, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffect-isolateroom-int), [MakeEffectAlter(IsolateRoom, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectalter-isolateroom-int), [Prob(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#prob-int), [isAttackInWorkProcess()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isattackinworkprocess), [OnAttackInWorkProcess(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onattackinworkprocess-useskill), [AttackProcess(UnitModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#attackprocess-unitmodel), [AutoFeelingDown()](/api/Global/Abnormalities/CreatureBase/CreatureBase#autofeelingdown), [AgentAnimCalled(int, WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#agentanimcalled-int-workermodel), [MakingEffect(string, float, string, Transform, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float-string-transform-int), [MakingEffect(string, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float), [MakeEffectAttachedToHead(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectattachedtohead-string), [MakingEffect(string, float, string, Vector3, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float-string-vector3-int), [OnAgentWorkEndAnimationPlayed(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentworkendanimationplayed-useskill), [OnAgentAllocateWork(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentallocatework-agentmodel), [OnAllocatedWork(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onallocatedwork-agentmodel), [OnReleaseWorkAllocated()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleaseworkallocated), [ObserveLevelChangeForSpecialSkillTip()](/api/Global/Abnormalities/CreatureBase/CreatureBase#observelevelchangeforspecialskilltip), [OnObserveLevelChanged()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onobservelevelchanged), [HasUniqueProcessWorkNarration()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueprocessworknarration), [UniqueProcessWorkNarration(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniqueprocessworknarration-useskill), [RoomSpriteInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomspriteinit), [RoomEscapeSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomescapespriteon), [RoomEscapeSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomescapespriteoff), [RoomSkillSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomskillspriteon), [RoomSkillSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomskillspriteoff), [RoomStateSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomstatespriteon), [RoomStateSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomstatespriteoff), [OnForceSpecialSkillTipReveal(string, params object[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onforcespecialskilltipreveal-string-params-object), [OnWorkReleaseSpeicalSkillTipReveal(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkreleasespeicalskilltipreveal-string), [OnWorkReleaseTipUpdate(params object[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkreleasetipupdate-params-object), [OnAgentAnimatorReseted()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentanimatorreseted), [SpecialEnergyTick()](/api/Global/Abnormalities/CreatureBase/CreatureBase#specialenergytick), [OnStageEnd()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onstageend), [OnFeverTimeOver()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfevertimeover), [OnOverlayIsolateWork()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onoverlayisolatework), [OnOverlayIsolateObserve()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onoverlayisolateobserve), [OnOpenObserveWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopenobservewindow), [OnOpenWorkWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopenworkwindow), [OnOpenCollectionWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopencollectionwindow), [DelayAttackMotion(float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#delayattackmotion-float), [IsAttackTargetable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isattacktargetable), [GetRealTargets()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getrealtargets), [HasScriptSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasscriptsavedata), [GetSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getsavedata), [LoadData(Dictionary<string, object>)](/api/Global/Abnormalities/CreatureBase/CreatureBase#loaddata-dictionary-string-object), [LoadScriptData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#loadscriptdata), [SaveScriptData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#savescriptdata), [ExistSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#existsavedata), [RemoveSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#removesavedata), [ReplaceCommand(CreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#replacecommand-creaturemodel), [OnGamemanagerInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#ongamemanagerinit), [MakeEffectGlobalPos(string, Vector3)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectglobalpos-string-vector3), [MakeEffectGlobalPosNonTrans(string, Vector3)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectglobalposnontrans-string-vector3), [CanObservedByAgent(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#canobservedbyagent-agentmodel), [MakeSound(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string), [MakeSound(string, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string-float), [MakeSound(string, AudioRolloffMode)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string-audiorolloffmode), [MakeSoundQueue(params string[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesoundqueue-params-string), [MakeSoundLoop(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesoundloop-string), [OnViewDestroy()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onviewdestroy), [IsWorkable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isworkable), [HasUniqueMaxObservationFinish()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquemaxobservationfinish), [UniqueMaxObservationFinish(Desc)](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquemaxobservationfinish-desc), [OnChildSuppressed(ChildCreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onchildsuppressed-childcreaturemodel), [MakeChildCreature(UnitModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makechildcreature-unitmodel), [OnKillWorker(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onkillworker-workermodel), [GenPursueCommandAlter(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#genpursuecommandalter-workermodel), [hasUniqueDeadScene()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquedeadscene), [SetHpSlider(Slider)](/api/Global/Abnormalities/CreatureBase/CreatureBase#sethpslider-slider), [SetCastingSlider(Slider)](/api/Global/Abnormalities/CreatureBase/CreatureBase#setcastingslider-slider), [HasUniqueAttackDealy()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueattackdealy), [CanTakeDamage(UnitModel, DamageInfo)](/api/Global/Abnormalities/CreatureBase/CreatureBase#cantakedamage-unitmodel-damageinfo), [OnTakePhysicalDamage(UnitModel, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontakephysicaldamage-unitmodel-float), [HasUniqueFaction()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquefaction), [OnWorkerPanic(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkerpanic-workermodel), [OnSelectMaxObservation(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onselectmaxobservation-int), [OnLoadCreatureName(ref string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onloadcreaturename-ref-string), [IsSuppressable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#issuppressable), [IsSuppressableByRoom()](/api/Global/Abnormalities/CreatureBase/CreatureBase#issuppressablebyroom), [IsAutoSuppressable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isautosuppressable), [OnWorkWindowSkillClicked(long)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkwindowskillclicked-long), [UseDefaultDamageIgnoreMessage(DamageTextEffect)](/api/Global/Abnormalities/CreatureBase/CreatureBase#usedefaultdamageignoremessage-damagetexteffect), [OnWorkAllocated(SkillTypeInfo, AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkallocated-skilltypeinfo-agentmodel), [GetPhysicalDamage(out float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getphysicaldamage-out-float), [GetMentalDamage(out float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getmentaldamage-out-float), [OnSuperArmorBreak()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onsuperarmorbreak), [UniqueStunEffect()](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquestuneffect), [HasEscapeUI()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasescapeui), [RoomCounterInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomcounterinit), [ResetQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#resetqliphothcounter), [GetMaxWorkCountView()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getmaxworkcountview), [GetQliphothCounterMax()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getqliphothcountermax), [ActivateQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#activateqliphothcounter), [ReducedQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#reducedqliphothcounter), [AddedQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#addedqliphothcounter), [OnTakeDamage(UnitModel, DamageInfo, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontakedamage-unitmodel-damageinfo-float), [GetRadius()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getradius), [OnElevatorStuck()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onelevatorstuck), [OnWorkClosed(UseSkill, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkclosed-useskill-int), [IsSensoredInPassage()](/api/Global/Abnormalities/CreatureBase/CreatureBase#issensoredinpassage), [IsIndirectSuppressable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isindirectsuppressable), [GetRiskLevel()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getrisklevel), [GetName()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getname), [UniqueMoveControl()](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquemovecontrol), [HasUniqueName()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquename), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdamagefactor-unitmodel-damageinfo), [OnInitialBuild()](/api/Global/Abnormalities/CreatureBase/CreatureBase#oninitialbuild), [HasUniqueCollectionCost(string, out string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquecollectioncost-string-out-string), [OnOpenCommandWindow(Button[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopencommandwindow-button), [HasUniqueCommandAction(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquecommandaction-int), [HasUniqueWorkSelect(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueworkselect-int), [ForcelySuccess(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#forcelysuccess-useskill), [ForcelyFail(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#forcelyfail-useskill), [TryRabbitTeleport(MapNode)](/api/Global/Abnormalities/CreatureBase/CreatureBase#tryrabbitteleport-mapnode), [CanEnterRoom()](/api/Global/Abnormalities/CreatureBase/CreatureBase#canenterroom), [AllocatedAgent](/api/Global/Abnormalities/CreatureBase/CreatureBase#allocatedagent), [skillTriggerCheck](/api/Global/Abnormalities/CreatureBase/CreatureBase#skilltriggercheck), [Unit](/api/Global/Abnormalities/CreatureBase/CreatureBase#unit), [GetSaveSrc](/api/Global/Abnormalities/CreatureBase/CreatureBase#getsavesrc), [movable](/api/Global/Abnormalities/CreatureBase/CreatureBase#movable), [currentPassage](/api/Global/Abnormalities/CreatureBase/CreatureBase#currentpassage), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)







