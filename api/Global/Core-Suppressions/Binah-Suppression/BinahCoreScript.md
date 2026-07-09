---
uid: Global.BinahCoreScript
canonical_path: /api/Global/Script/BinahCoreScript
---
# Class BinahCoreScript
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BinahCoreScript : CreatureBase
```
> This section may have incomplete or incorrect information.
{.is-warning}


extends [CreatureBase](/api/Global/Abnormalities/CreatureBase/CreatureBase)

An Arbiter, from [Binah's core suppression](/api/Global/Core-Suppressions/Binah-Suppression/BinahBossBase).


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase](/api/Global/Abnormalities/CreatureBase/CreatureBase) → BinahCoreScript

## Constructors
### BinahCoreScript()
```csharp
public BinahCoreScript()
```

## Fields
### _actionQueue
```csharp
private Queue<BinahAction> _actionQueue
```


#### Field Value
**Type:** System.Collections.Generic.Queue{BinahBoss.BinahAction}

### _currentAction
```csharp
private BinahAction _currentAction
```


#### Field Value
**Type:** BinahBoss.BinahAction

### _currentPhase
```csharp
private BinahPhase _currentPhase
```


#### Field Value
**Type:** BinahBoss.BinahPhase

### _defenseTimer
```csharp
private Timer _defenseTimer
```


#### Field Value
**Type:** Global.Timer

### _isHalted
```csharp
private bool _isHalted
```


#### Field Value
**Type:** System.Boolean

### _isInvincible
```csharp
private bool _isInvincible
```


#### Field Value
**Type:** System.Boolean

### _phaseExecution
```csharp
private BinahPhaseExecution _phaseExecution
```


#### Field Value
**Type:** BinahBoss.BinahPhaseExecution

### _recoverTimer
```csharp
private Timer _recoverTimer
```


#### Field Value
**Type:** Global.Timer

### _waves
```csharp
private List<ProjectileModel> _waves
```


#### Field Value
**Type:** System.Collections.Generic.List{ProjectileModel}

### AnimIntegerEvent
```csharp
private BinahIntegerAction AnimIntegerEvent
```


#### Field Value
**Type:** BinahBoss.BinahIntegerAction

### ArriveStopTime
```csharp
public static MinMax ArriveStopTime
```


#### Field Value
**Type:** Global.MinMax

### AttackEndEvent
```csharp
private BinahVoidAction AttackEndEvent
```


#### Field Value
**Type:** BinahBoss.BinahVoidAction

### binahDefenseType
```csharp
private BinahDefenseType binahDefenseType
```


#### Field Value
**Type:** BinahBoss.BinahDefenseType

### bossBase
```csharp
private BinahBossBase bossBase
```


#### Field Value
**Type:** Global.BinahBossBase

### currentOverload
```csharp
private BinahOverload currentOverload
```


#### Field Value
**Type:** BinahBoss.BinahOverload

### DamageEvent
```csharp
private BinahVoidAction DamageEvent
```


#### Field Value
**Type:** BinahBoss.BinahVoidAction

### defaultSpeed
```csharp
public const float defaultSpeed = 2.5
```


#### Field Value
**Type:** System.Single

### movementModule
```csharp
private BinahMovementModule movementModule
```


#### Field Value
**Type:** BinahBoss.BinahMovementModule

### overloads
```csharp
private Dictionary<OverloadType, BinahOverload> overloads
```


#### Field Value
**Type:** System.Collections.Generic.Dictionary{OverloadType,BinahBoss.BinahOverload}

### PrefabFolder
```csharp
public const string PrefabFolder = "Effect/SefiraBoss/BinahBoss/"
```


#### Field Value
**Type:** System.String

### workerSenseRange
```csharp
public const float workerSenseRange = 4
```


#### Field Value
**Type:** System.Single

## Properties
### AnimScript
```csharp
public BinahCoreAnim AnimScript { get; }
```

#### Property Value
**Type:** Global.BinahCoreAnim

### BossBase
```csharp
public BinahBossBase BossBase { get; }
```

#### Property Value
**Type:** Global.BinahBossBase

### IsInvincible
```csharp
public bool IsInvincible { get; set; }
```

#### Property Value
**Type:** System.Boolean

### MovementModule
```csharp
public BinahMovementModule MovementModule { get; }
```

#### Property Value
**Type:** BinahBoss.BinahMovementModule

### Phase
```csharp
public BinahPhase Phase { get; }
```

#### Property Value
**Type:** BinahBoss.BinahPhase

## Methods
### AddOverload(BinahOverload)
```csharp
public void AddOverload(BinahOverload overload)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `overload` | `BinahBoss.BinahOverload` |  |

### AddWave(ProjectileModel)
```csharp
public void AddWave(ProjectileModel wave)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `wave` | `Global.ProjectileModel` |  |

### AttachProjectile(BinahProjectile, string)
```csharp
private bool AttachProjectile(BinahProjectile projectile, string restSrc)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `projectile` | `BinahBoss.BinahProjectile` |  |
| `restSrc` | `System.String` |  |

#### Returns
**Type:** System.Boolean

### BinahGiveDamage(UnitModel, DamageInfo, bool)
```csharp
public void BinahGiveDamage(UnitModel target, DamageInfo damage, bool makeGut = false)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `damage` | `Global.DamageInfo` |  |
| `makeGut` | `System.Boolean` |  |

### BinahWaveGiveDamage(UnitModel, DamageInfo)
```csharp
public void BinahWaveGiveDamage(UnitModel target, DamageInfo damage)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `damage` | `Global.DamageInfo` |  |

### CancelDefenseTimer()
```csharp
public void CancelDefenseTimer()
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

### ClearActionQueue()
```csharp
public void ClearActionQueue()
```

### ClearEvents()
```csharp
public void ClearEvents()
```

### ClearOverload(OverloadType)
```csharp
public void ClearOverload(OverloadType type)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.OverloadType` |  |

### ClearWave()
```csharp
public void ClearWave()
```

### EnqueueAction(BinahAction)
```csharp
public void EnqueueAction(BinahAction action)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `action` | `BinahBoss.BinahAction` |  |

### GenProjectile(Vector3, float, BinahProjectileType, out BinahProjectile)
```csharp
public bool GenProjectile(Vector3 position, float scale, BinahProjectileType type, out BinahProjectile binahProjectile)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `position` | `UnityEngine.Vector3` |  |
| `scale` | `System.Single` |  |
| `type` | `BinahBoss.BinahProjectileType` |  |
| `binahProjectile` | `BinahBoss.BinahProjectile` |  |

#### Returns
**Type:** System.Boolean

### GetCurrentPhaseOverload()
```csharp
public OverloadType GetCurrentPhaseOverload()
```

#### Returns
**Type:** Global.OverloadType

### GetDirectionWithTarget(UnitModel)
```csharp
public UnitDirection GetDirectionWithTarget(UnitModel target)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

#### Returns
**Type:** Global.UnitDirection

### GetName()
```csharp
public override string GetName()
```

#### Returns
**Type:** System.String

### GetNear<T>(bool, float)
```csharp
public List<T> GetNear<T>(bool careDirection = false, float range = -1) where T : UnitModel
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `careDirection` | `System.Boolean` |  |
| `range` | `System.Single` |  |

#### Returns
**Type:** System.Collections.Generic.List{{T}}

### GetOverload(OverloadType)
```csharp
public BinahOverload GetOverload(OverloadType type)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.OverloadType` |  |

#### Returns
**Type:** BinahBoss.BinahOverload

### GetProjectileSrc(BinahProjectileType)
```csharp
private string GetProjectileSrc(BinahProjectileType type)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `type` | `BinahBoss.BinahProjectileType` |  |

#### Returns
**Type:** System.String

### HaltExecution()
```csharp
public void HaltExecution()
```

### HasOverload()
```csharp
public bool HasOverload()
```

#### Returns
**Type:** System.Boolean

### InterruptClear()
```csharp
public void InterruptClear()
```

### InterruptCurrentAction()
```csharp
public void InterruptCurrentAction()
```

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

### IsIndirectSuppressable()
```csharp
public override bool IsIndirectSuppressable()
```

#### Returns
**Type:** System.Boolean

### IsInRange(UnitModel, float, bool)
```csharp
public bool IsInRange(UnitModel target, float range, bool careDirection = false)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `range` | `System.Single` |  |
| `careDirection` | `System.Boolean` |  |

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

### Log(string, bool)
```csharp
public static void Log(string log, bool isError = false)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `log` | `System.String` |  |
| `isError` | `System.Boolean` |  |

### LookTarget(UnitModel)
```csharp
public void LookTarget(UnitModel target)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### MakeBattleDesc(int)
```csharp
public void MakeBattleDesc(int index)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### MakeBattleDesc(int[])
```csharp
public void MakeBattleDesc(int[] id)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32[]` |  |

### MakeNearSlowDown()
```csharp
private void MakeNearSlowDown()
```

### MakeOverload(CreatureModel, OverloadType)
```csharp
public void MakeOverload(CreatureModel target, OverloadType type = OverloadType.DEFAULT)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.CreatureModel` |  |
| `type` | `Global.OverloadType` |  |

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

### MakeSoundLoop(string)
```csharp
public override SoundEffectPlayer MakeSoundLoop(string src)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

#### Returns
**Type:** Global.SoundEffectPlayer

### MoveToNextPhase()
```csharp
public void MoveToNextPhase()
```

### OnAnimEventCalled(int)
```csharp
public void OnAnimEventCalled(int index)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### OnAttackEnd()
```csharp
public void OnAttackEnd()
```

### OnCollision(BinahCollision)
```csharp
public void OnCollision(BinahCollision collision)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `collision` | `BinahBoss.BinahCollision` |  |

### OnCollision(BinahCollision, BinahProjectile)
```csharp
public void OnCollision(BinahCollision collider, BinahProjectile projectile)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `collider` | `BinahBoss.BinahCollision` |  |
| `projectile` | `BinahBoss.BinahProjectile` |  |

### OnFixedUpdate(CreatureModel)
```csharp
public override void OnFixedUpdate(CreatureModel creature)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |

### OnGiveDamage()
```csharp
public void OnGiveDamage()
```

### OnMakeGut(WorkerModel, UnitDirection)
```csharp
public void OnMakeGut(WorkerModel target, UnitDirection dir)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |
| `dir` | `Global.UnitDirection` |  |

### OnOverloadSuccessParticle(OverloadType)
```csharp
public void OnOverloadSuccessParticle(OverloadType type)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.OverloadType` |  |

### OnParticleArrived(BinahOverloadClearParticle)
```csharp
public void OnParticleArrived(BinahOverloadClearParticle ps)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `ps` | `BinahBoss.BinahOverloadClearParticle` |  |

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

### SetAnimCalledEvent(BinahIntegerAction)
```csharp
public void SetAnimCalledEvent(BinahIntegerAction action)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `action` | `BinahBoss.BinahIntegerAction` |  |

### SetAttackEndEvent(BinahVoidAction)
```csharp
public void SetAttackEndEvent(BinahVoidAction action)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `action` | `BinahBoss.BinahVoidAction` |  |

### SetBossBase(BinahBossBase)
```csharp
public void SetBossBase(BinahBossBase bossBase)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `bossBase` | `Global.BinahBossBase` |  |

### SetDamageEvent(BinahVoidAction)
```csharp
public void SetDamageEvent(BinahVoidAction action)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `action` | `BinahBoss.BinahVoidAction` |  |

### SetDefenseReturnTimer(float)
```csharp
public void SetDefenseReturnTimer(float time)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `time` | `System.Single` |  |

### SetDefenseType(BinahDefenseType)
```csharp
public void SetDefenseType(BinahDefenseType type)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `type` | `BinahBoss.BinahDefenseType` |  |

### SetHpSlider(Slider)
```csharp
public override bool SetHpSlider(Slider slider)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `slider` | `UnityEngine.UI.Slider` |  |

#### Returns
**Type:** System.Boolean

### SetPhase(BinahPhase)
```csharp
public void SetPhase(BinahPhase phase)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `phase` | `BinahBoss.BinahPhase` |  |

### SetSpeed(float)
```csharp
public void SetSpeed(float speed = 2.5)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `speed` | `System.Single` |  |

### UniqueMoveControl()
```csharp
public override bool UniqueMoveControl()
```

#### Returns
**Type:** System.Boolean

### Update()
```csharp
public void Update()
```

## Inherited Members
[isolateSpriteSrc](/api/Global/Abnormalities/CreatureBase/CreatureBase#isolatespritesrc), [model](/api/Global/Abnormalities/CreatureBase/CreatureBase#model), [skill](/api/Global/Abnormalities/CreatureBase/CreatureBase#skill), [kitEvent](/api/Global/Abnormalities/CreatureBase/CreatureBase#kitevent), [hasUniqueEscapeLogic](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueescapelogic), [isWorkAllocated](/api/Global/Abnormalities/CreatureBase/CreatureBase#isworkallocated), [_allocatedAgent](/api/Global/Abnormalities/CreatureBase/CreatureBase#allocatedagent), [damage](/api/Global/Abnormalities/CreatureBase/CreatureBase#damage), [OnReleaseSpecialTip](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleasespecialtip), [specialSkillTipParamList](/api/Global/Abnormalities/CreatureBase/CreatureBase#specialskilltipparamlist), [_check](/api/Global/Abnormalities/CreatureBase/CreatureBase#check), [SetModel(CreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#setmodel-creaturemodel), [OnInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#oninit), [OnViewInitPrev(CreatureUnit)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onviewinitprev-creatureunit), [OnFixedUpdateInSkill(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfixedupdateinskill-useskill), [OnSkillFailWorkTick(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillfailworktick-useskill), [OnSkillSuccessWorkTick(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillsuccessworktick-useskill), [OnSkillTickUpdate(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskilltickupdate-useskill), [OnSkillGoalComplete(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillgoalcomplete-useskill), [PermitCancelCurrentWork()](/api/Global/Abnormalities/CreatureBase/CreatureBase#permitcancelcurrentwork), [GetKitCreatureProcessTime()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getkitcreatureprocesstime), [OnBonusWorkProb()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onbonusworkprob), [GetDamageMultiplierInWork(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdamagemultiplierinwork-useskill), [TranformWorkProb(float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#tranformworkprob-float), [OnEnterRoom(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onenterroom-useskill), [OnReleaseWork(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleasework-useskill), [OnFinishWork(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfinishwork-useskill), [OnWorkCoolTimeEnd(CreatureFeelingState)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkcooltimeend-creaturefeelingstate), [OnReturn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreturn), [UniqueEscape()](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniqueescape), [Escape()](/api/Global/Abnormalities/CreatureBase/CreatureBase#escape), [GetSpecialSkill()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getspecialskill), [GetDebugText()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdebugtext), [OnTimerEnd()](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontimerend), [MakeEffect(IsolateRoom, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffect-isolateroom-int), [MakeEffectAlter(IsolateRoom, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectalter-isolateroom-int), [Prob(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#prob-int), [isAttackInWorkProcess()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isattackinworkprocess), [OnAttackInWorkProcess(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onattackinworkprocess-useskill), [AttackProcess(UnitModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#attackprocess-unitmodel), [AutoFeelingDown()](/api/Global/Abnormalities/CreatureBase/CreatureBase#autofeelingdown), [AgentAnimCalled(int, WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#agentanimcalled-int-workermodel), [MakingEffect(string, float, string, Transform, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float-string-transform-int), [MakingEffect(string, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float), [MakeEffectAttachedToHead(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectattachedtohead-string), [MakingEffect(string, float, string, Vector3, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float-string-vector3-int), [OnAgentWorkEndAnimationPlayed(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentworkendanimationplayed-useskill), [OnAgentAllocateWork(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentallocatework-agentmodel), [OnStageRelease()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onstagerelease), [OnAllocatedWork(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onallocatedwork-agentmodel), [OnReleaseWorkAllocated()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleaseworkallocated), [ObserveLevelChangeForSpecialSkillTip()](/api/Global/Abnormalities/CreatureBase/CreatureBase#observelevelchangeforspecialskilltip), [OnObserveLevelChanged()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onobservelevelchanged), [HasUniqueProcessWorkNarration()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueprocessworknarration), [UniqueProcessWorkNarration(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniqueprocessworknarration-useskill), [RoomSpriteInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomspriteinit), [RoomEscapeSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomescapespriteon), [RoomEscapeSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomescapespriteoff), [RoomSkillSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomskillspriteon), [RoomSkillSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomskillspriteoff), [RoomStateSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomstatespriteon), [RoomStateSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomstatespriteoff), [OnForceSpecialSkillTipReveal(string, params object[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onforcespecialskilltipreveal-string-params-object), [OnWorkReleaseSpeicalSkillTipReveal(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkreleasespeicalskilltipreveal-string), [OnWorkReleaseTipUpdate(params object[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkreleasetipupdate-params-object), [OnAgentAnimatorReseted()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentanimatorreseted), [SpecialEnergyTick()](/api/Global/Abnormalities/CreatureBase/CreatureBase#specialenergytick), [OnStageEnd()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onstageend), [OnFeverTimeOver()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfevertimeover), [OnOverlayIsolateWork()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onoverlayisolatework), [OnOverlayIsolateObserve()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onoverlayisolateobserve), [OnOpenObserveWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopenobservewindow), [OnOpenWorkWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopenworkwindow), [OnOpenCollectionWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopencollectionwindow), [DelayAttackMotion(float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#delayattackmotion-float), [GetRealTargets()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getrealtargets), [HasScriptSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasscriptsavedata), [GetSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getsavedata), [LoadData(Dictionary<string, object>)](/api/Global/Abnormalities/CreatureBase/CreatureBase#loaddata-dictionary-string-object), [LoadScriptData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#loadscriptdata), [SaveScriptData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#savescriptdata), [ExistSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#existsavedata), [RemoveSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#removesavedata), [ReplaceCommand(CreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#replacecommand-creaturemodel), [OnGamemanagerInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#ongamemanagerinit), [MakeEffectGlobalPos(string, Vector3)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectglobalpos-string-vector3), [MakeEffectGlobalPosNonTrans(string, Vector3)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectglobalposnontrans-string-vector3), [CanObservedByAgent(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#canobservedbyagent-agentmodel), [MakeSound(string, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string-float), [MakeSound(string, AudioRolloffMode)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string-audiorolloffmode), [MakeSoundQueue(params string[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesoundqueue-params-string), [OnViewDestroy()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onviewdestroy), [IsWorkable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isworkable), [ParamInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#paraminit), [HasUniqueMaxObservationFinish()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquemaxobservationfinish), [UniqueMaxObservationFinish(Desc)](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquemaxobservationfinish-desc), [OnChildSuppressed(ChildCreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onchildsuppressed-childcreaturemodel), [MakeChildCreature(UnitModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makechildcreature-unitmodel), [OnKillWorker(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onkillworker-workermodel), [GenPursueCommandAlter(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#genpursuecommandalter-workermodel), [OnAfterSuppressed()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onaftersuppressed), [hasUniqueDeadScene()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquedeadscene), [SetCastingSlider(Slider)](/api/Global/Abnormalities/CreatureBase/CreatureBase#setcastingslider-slider), [HasUniqueAttackDealy()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueattackdealy), [OnTakePhysicalDamage(UnitModel, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontakephysicaldamage-unitmodel-float), [HasUniqueFaction()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquefaction), [OnWorkerPanic(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkerpanic-workermodel), [OnSelectMaxObservation(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onselectmaxobservation-int), [OnLoadCreatureName(ref string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onloadcreaturename-ref-string), [IsSuppressableByRoom()](/api/Global/Abnormalities/CreatureBase/CreatureBase#issuppressablebyroom), [OnWorkWindowSkillClicked(long)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkwindowskillclicked-long), [UseDefaultDamageIgnoreMessage(DamageTextEffect)](/api/Global/Abnormalities/CreatureBase/CreatureBase#usedefaultdamageignoremessage-damagetexteffect), [OnWorkAllocated(SkillTypeInfo, AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkallocated-skilltypeinfo-agentmodel), [GetPhysicalDamage(out float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getphysicaldamage-out-float), [GetMentalDamage(out float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getmentaldamage-out-float), [OnSuperArmorBreak()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onsuperarmorbreak), [UniqueStunEffect()](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquestuneffect), [HasEscapeUI()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasescapeui), [HasRoomCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasroomcounter), [RoomCounterInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomcounterinit), [ResetQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#resetqliphothcounter), [GetMaxWorkCountView()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getmaxworkcountview), [GetQliphothCounterMax()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getqliphothcountermax), [ActivateQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#activateqliphothcounter), [ReducedQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#reducedqliphothcounter), [AddedQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#addedqliphothcounter), [GetRadius()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getradius), [OnElevatorStuck()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onelevatorstuck), [OnWorkClosed(UseSkill, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkclosed-useskill-int), [IsActivatedWorkDesc()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isactivatedworkdesc), [GetRiskLevel()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getrisklevel), [HasUniqueName()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquename), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdamagefactor-unitmodel-damageinfo), [OnInitialBuild()](/api/Global/Abnormalities/CreatureBase/CreatureBase#oninitialbuild), [HasUniqueCollectionCost(string, out string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquecollectioncost-string-out-string), [OnOpenCommandWindow(Button[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopencommandwindow-button), [HasUniqueCommandAction(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquecommandaction-int), [HasUniqueWorkSelect(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueworkselect-int), [ForcelySuccess(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#forcelysuccess-useskill), [ForcelyFail(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#forcelyfail-useskill), [TryRabbitTeleport(MapNode)](/api/Global/Abnormalities/CreatureBase/CreatureBase#tryrabbitteleport-mapnode), [CanEnterRoom()](/api/Global/Abnormalities/CreatureBase/CreatureBase#canenterroom), [AllocatedAgent](/api/Global/Abnormalities/CreatureBase/CreatureBase#allocatedagent), [skillTriggerCheck](/api/Global/Abnormalities/CreatureBase/CreatureBase#skilltriggercheck), [Unit](/api/Global/Abnormalities/CreatureBase/CreatureBase#unit), [GetSaveSrc](/api/Global/Abnormalities/CreatureBase/CreatureBase#getsavesrc), [movable](/api/Global/Abnormalities/CreatureBase/CreatureBase#movable), [currentPassage](/api/Global/Abnormalities/CreatureBase/CreatureBase#currentpassage), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)







