---
uid: Global.RedHood
canonical_path: /api/Global/IOBserver/RedHood
---
# Class RedHood
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class RedHood : CreatureBase, IObserver
```
> This section may have incomplete or incorrect information.
{.is-warning}


Little Red Riding Hooded Mercenary.




## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase](/api/Global/Abnormalities/CreatureBase/CreatureBase) → RedHood

## Implements
[IObserver](/api/Global/Notices/IObserver)

## Constructors
### RedHood()
```csharp
public RedHood()
```

## Fields
### _axeRespawn
```csharp
public const float _axeRespawn = 10
```


#### Field Value
**Type:** System.Single

### _changeTargetAsWolf
```csharp
private bool _changeTargetAsWolf
```


#### Field Value
**Type:** System.Boolean

### _chase
```csharp
private bool _chase
```


#### Field Value
**Type:** System.Boolean

### _currentAgentPrevWorkIsWolf
```csharp
private bool _currentAgentPrevWorkIsWolf
```


#### Field Value
**Type:** System.Boolean

### _currentAttackType
```csharp
private RedHood.AttackType _currentAttackType
```

#### Field Value
**Type:** Global.RedHood.AttackType

### _currentDestMovable
```csharp
private MovableObjectNode _currentDestMovable
```


#### Field Value
**Type:** Global.MovableObjectNode

### _currentDestNode
```csharp
private MapNode _currentDestNode
```


#### Field Value
**Type:** Global.MapNode

### _currentMoveCommand
```csharp
private CreatureCommand.OnCommandEnd _currentMoveCommand
```


#### Field Value
**Type:** Global.CreatureCommand.OnCommandEnd

### _currentSpeedFactor
```csharp
private float _currentSpeedFactor
```


#### Field Value
**Type:** System.Single

### _entryPassage
```csharp
private PassageObjectModel _entryPassage
```


#### Field Value
**Type:** Global.PassageObjectModel

### _freezeReturnTimer
```csharp
private Timer _freezeReturnTimer
```


#### Field Value
**Type:** Global.Timer

### _initialSpeed
```csharp
private float _initialSpeed
```


#### Field Value
**Type:** System.Single

### _isApproaching
```csharp
private bool _isApproaching
```


#### Field Value
**Type:** System.Boolean

### _isAttacking
```csharp
private bool _isAttacking
```


#### Field Value
**Type:** System.Boolean

### _isAxeThrowed
```csharp
private bool _isAxeThrowed
```


#### Field Value
**Type:** System.Boolean

### _isWaiting
```csharp
private bool _isWaiting
```


#### Field Value
**Type:** System.Boolean

### _isWolfSuppressed
```csharp
private bool _isWolfSuppressed
```


#### Field Value
**Type:** System.Boolean

### _oldTargetNode
```csharp
private MapNode _oldTargetNode
```


#### Field Value
**Type:** Global.MapNode

### _state
```csharp
private RedHood.RedHoodState _state
```

#### Field Value
**Type:** Global.RedHood.RedHoodState

### _target
```csharp
private UnitModel _target
```


#### Field Value
**Type:** Global.UnitModel

### _text_exclam
```csharp
private const string _text_exclam = "...!"
```


#### Field Value
**Type:** System.String

### _text_norm
```csharp
private const string _text_norm = "..."
```


#### Field Value
**Type:** System.String

### _throwingRespawnTimer
```csharp
private Timer _throwingRespawnTimer
```


#### Field Value
**Type:** Global.Timer

### _wolf
```csharp
private BigBadWolf _wolf
```


#### Field Value
**Type:** Global.BigBadWolf

### bufDictionary
```csharp
private Dictionary<UnitModel, RedHoodBleedBuf> bufDictionary
```


#### Field Value
**Type:** System.Collections.Generic.Dictionary{UnitModel,RedHoodBleedBuf}

### GunFire_Left
```csharp
private const string GunFire_Left = "Effect/Creature/RedHood/GunFireLeft"
```


#### Field Value
**Type:** System.String

### GunFire_Right
```csharp
private const string GunFire_Right = "Effect/Creature/RedHood/GunFireRight"
```


#### Field Value
**Type:** System.String

### MeleeAttackRange
```csharp
private const float MeleeAttackRange = 2
```


#### Field Value
**Type:** System.Single

### QliphothMax
```csharp
public const int QliphothMax = 3
```


#### Field Value
**Type:** System.Int32

### RequestCostFactor
```csharp
private const int RequestCostFactor = 40
```


#### Field Value
**Type:** System.Int32

### SlashSrc
```csharp
private const string SlashSrc = "Effect/Creature/RedHood/RedHoodSlash{0}_{1}"
```


#### Field Value
**Type:** System.String

## Properties
### AnimScript
```csharp
private RedHoodAnim AnimScript { get; }
```

#### Property Value
**Type:** Global.RedHoodAnim

### CurrentSpeedFactor
```csharp
public float CurrentSpeedFactor { get; }
```

#### Property Value
**Type:** System.Single

### IsBigBadWolfExist
```csharp
private bool IsBigBadWolfExist { get; }
```

#### Property Value
**Type:** System.Boolean

### MeleeDamage
```csharp
public DamageInfo MeleeDamage { get; }
```

#### Property Value
**Type:** Global.DamageInfo

### RangeDamage
```csharp
public DamageInfo RangeDamage { get; }
```

#### Property Value
**Type:** Global.DamageInfo

### target
```csharp
private UnitModel target { get; set; }
```

#### Property Value
**Type:** Global.UnitModel

### ThrowingDamage
```csharp
public DamageInfo ThrowingDamage { get; }
```

#### Property Value
**Type:** Global.DamageInfo

## Methods
### ActivateQliphothCounter()
```csharp
public override void ActivateQliphothCounter()
```


### Approach()
```csharp
private void Approach()
```


### CanCastMovingShoot()
```csharp
public bool CanCastMovingShoot()
```


#### Returns
**Type:** System.Boolean

### CheckRange(UnitModel, float, bool)
```csharp
private bool CheckRange(UnitModel target, float range, bool ignoreDirection = true)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `range` | `System.Single` |  |
| `ignoreDirection` | `System.Boolean` |  |

#### Returns
**Type:** System.Boolean

### CheckTargetPassage()
```csharp
private bool CheckTargetPassage()
```


#### Returns
**Type:** System.Boolean

### CheckWolf(List<UnitModel>)
```csharp
private void CheckWolf(List<UnitModel> near)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `near` | `System.Collections.Generic.List{UnitModel}` |  |

### ClearBuf()
```csharp
public void ClearBuf()
```


### EscapeMovementArrived()
```csharp
private void EscapeMovementArrived()
```


### EscapeUpdate()
```csharp
private void EscapeUpdate()
```


### FindBadWolf()
```csharp
private void FindBadWolf()
```


### GenThrowing()
```csharp
private void GenThrowing()
```


### GetBuf(UnitModel)
```csharp
private RedHoodBleedBuf GetBuf(UnitModel target)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

#### Returns
**Type:** Global.RedHoodBleedBuf

### GetDamageFactor(UnitModel, DamageInfo)
```csharp
public override float GetDamageFactor(UnitModel target, DamageInfo damage)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `damage` | `Global.DamageInfo` |  |

#### Returns
**Type:** System.Single

### GetDamageTargets(float, bool)
```csharp
private List<UnitModel> GetDamageTargets(float dist = -1, bool ignoreDirection = true)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `dist` | `System.Single` |  |
| `ignoreDirection` | `System.Boolean` |  |

#### Returns
**Type:** System.Collections.Generic.List{UnitModel}

### GetRequestCost(UnitModel)
```csharp
public int GetRequestCost(UnitModel unit)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.UnitModel` |  |

#### Returns
**Type:** System.Int32

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

### GiveAxeThrowingDamage(UnitModel)
```csharp
public void GiveAxeThrowingDamage(UnitModel target)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### GiveDamage(DamageInfo, List<UnitModel>, AttackType)
```csharp
private void GiveDamage(DamageInfo damageInfo, List<UnitModel> targets, RedHood.AttackType attackType)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `damageInfo` | `Global.DamageInfo` |  |
| `targets` | `System.Collections.Generic.List{UnitModel}` |  |
| `attackType` | `Global.RedHood.AttackType` |  |

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

### HuntingUpdate()
```csharp
private void HuntingUpdate()
```


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

### IsWolf(UnitModel)
```csharp
public bool IsWolf(UnitModel unit)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.UnitModel` |  |

#### Returns
**Type:** System.Boolean

### IsWorkable()
```csharp
public override bool IsWorkable()
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

### MakeGunFlame(Transform)
```csharp
public void MakeGunFlame(Transform tr)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `tr` | `UnityEngine.Transform` |  |

### MakeMovement(MapNode, OnCommandEnd)
```csharp
public void MakeMovement(MapNode targetNode, CreatureCommand.OnCommandEnd end = null)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `targetNode` | `Global.MapNode` |  |
| `end` | `Global.CreatureCommand.OnCommandEnd` |  |

### MakeMovement(MovableObjectNode, OnCommandEnd)
```csharp
public void MakeMovement(MovableObjectNode targetMovable, CreatureCommand.OnCommandEnd end = null)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `targetMovable` | `Global.MovableObjectNode` |  |
| `end` | `Global.CreatureCommand.OnCommandEnd` |  |

### MakeSlashEffect()
```csharp
public void MakeSlashEffect()
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

### MakeThrowEffect(UnitModel, float)
```csharp
public void MakeThrowEffect(UnitModel target, float heightFctor = 2)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `heightFctor` | `System.Single` |  |

### OnAfterSuppressed()
```csharp
public override bool OnAfterSuppressed()
```


#### Returns
**Type:** System.Boolean

### OnApproachUpdate()
```csharp
public void OnApproachUpdate()
```


### OnArrivedRoom()
```csharp
public void OnArrivedRoom()
```


### OnAttackAnimEnd()
```csharp
public void OnAttackAnimEnd()
```


### OnAxeRespawned()
```csharp
public void OnAxeRespawned()
```


### OnDamageTime()
```csharp
public void OnDamageTime()
```


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

### OnGiveDamage(UnitModel, bool)
```csharp
public void OnGiveDamage(UnitModel target, bool isRanged)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `isRanged` | `System.Boolean` |  |

### OnHowlingAttacked()
```csharp
public void OnHowlingAttacked()
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

### OnReadyForEscape()
```csharp
public void OnReadyForEscape()
```


### OnReturn()
```csharp
public override void OnReturn()
```


### OnSetTarget(UnitModel)
```csharp
public void OnSetTarget(UnitModel target)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### OnStageRelease()
```csharp
public override void OnStageRelease()
```


### OnStageStart()
```csharp
public override void OnStageStart()
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

### OnWolfSuppressedByOther()
```csharp
public void OnWolfSuppressedByOther()
```


### OnWolfSuppressedByRedHood()
```csharp
public void OnWolfSuppressedByRedHood()
```


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


### ResetMovement()
```csharp
public void ResetMovement()
```


### SetTargetDirection(UnitModel)
```csharp
public void SetTargetDirection(UnitModel target)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### StartAttack()
```csharp
private void StartAttack()
```


### StartRequest(UnitModel)
```csharp
public void StartRequest(UnitModel target)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### StopMovement(bool)
```csharp
public void StopMovement(bool clearDest = false)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `clearDest` | `System.Boolean` |  |

### TryRequest()
```csharp
public void TryRequest()
```


### UniqueEscape()
```csharp
public override void UniqueEscape()
```


### UniqueMoveControl()
```csharp
public override bool UniqueMoveControl()
```


#### Returns
**Type:** System.Boolean

### ValidateTarget()
```csharp
private bool ValidateTarget()
```


#### Returns
**Type:** System.Boolean

## Inherited Members
[isolateSpriteSrc](/api/Global/Abnormalities/CreatureBase/CreatureBase#isolatespritesrc), [model](/api/Global/Abnormalities/CreatureBase/CreatureBase#model), [skill](/api/Global/Abnormalities/CreatureBase/CreatureBase#skill), [kitEvent](/api/Global/Abnormalities/CreatureBase/CreatureBase#kitevent), [hasUniqueEscapeLogic](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueescapelogic), [isWorkAllocated](/api/Global/Abnormalities/CreatureBase/CreatureBase#isworkallocated), [_allocatedAgent](/api/Global/Abnormalities/CreatureBase/CreatureBase#allocatedagent), [damage](/api/Global/Abnormalities/CreatureBase/CreatureBase#damage), [OnReleaseSpecialTip](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleasespecialtip), [specialSkillTipParamList](/api/Global/Abnormalities/CreatureBase/CreatureBase#specialskilltipparamlist), [_check](/api/Global/Abnormalities/CreatureBase/CreatureBase#check), [SetModel(CreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#setmodel-creaturemodel), [OnInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#oninit), [OnViewInitPrev(CreatureUnit)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onviewinitprev-creatureunit), [OnFixedUpdateInSkill(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfixedupdateinskill-useskill), [OnSkillFailWorkTick(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillfailworktick-useskill), [OnSkillSuccessWorkTick(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillsuccessworktick-useskill), [OnSkillTickUpdate(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskilltickupdate-useskill), [OnSkillGoalComplete(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillgoalcomplete-useskill), [PermitCancelCurrentWork()](/api/Global/Abnormalities/CreatureBase/CreatureBase#permitcancelcurrentwork), [GetKitCreatureProcessTime()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getkitcreatureprocesstime), [OnBonusWorkProb()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onbonusworkprob), [GetDamageMultiplierInWork(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdamagemultiplierinwork-useskill), [TranformWorkProb(float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#tranformworkprob-float), [OnReleaseWork(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleasework-useskill), [OnFinishWork(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfinishwork-useskill), [Escape()](/api/Global/Abnormalities/CreatureBase/CreatureBase#escape), [GetSpecialSkill()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getspecialskill), [GetDebugText()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdebugtext), [OnTimerEnd()](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontimerend), [MakeEffect(IsolateRoom, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffect-isolateroom-int), [MakeEffectAlter(IsolateRoom, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectalter-isolateroom-int), [Prob(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#prob-int), [isAttackInWorkProcess()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isattackinworkprocess), [OnAttackInWorkProcess(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onattackinworkprocess-useskill), [AttackProcess(UnitModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#attackprocess-unitmodel), [AutoFeelingDown()](/api/Global/Abnormalities/CreatureBase/CreatureBase#autofeelingdown), [AgentAnimCalled(int, WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#agentanimcalled-int-workermodel), [MakingEffect(string, float, string, Transform, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float-string-transform-int), [MakingEffect(string, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float), [MakeEffectAttachedToHead(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectattachedtohead-string), [MakingEffect(string, float, string, Vector3, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float-string-vector3-int), [OnAgentWorkEndAnimationPlayed(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentworkendanimationplayed-useskill), [OnAgentAllocateWork(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentallocatework-agentmodel), [OnSuppressed()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onsuppressed), [OnAllocatedWork(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onallocatedwork-agentmodel), [OnReleaseWorkAllocated()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleaseworkallocated), [ObserveLevelChangeForSpecialSkillTip()](/api/Global/Abnormalities/CreatureBase/CreatureBase#observelevelchangeforspecialskilltip), [OnObserveLevelChanged()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onobservelevelchanged), [HasUniqueProcessWorkNarration()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueprocessworknarration), [UniqueProcessWorkNarration(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniqueprocessworknarration-useskill), [RoomSpriteInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomspriteinit), [RoomEscapeSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomescapespriteon), [RoomEscapeSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomescapespriteoff), [RoomSkillSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomskillspriteon), [RoomSkillSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomskillspriteoff), [RoomStateSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomstatespriteon), [RoomStateSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomstatespriteoff), [OnForceSpecialSkillTipReveal(string, params object[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onforcespecialskilltipreveal-string-params-object), [OnWorkReleaseSpeicalSkillTipReveal(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkreleasespeicalskilltipreveal-string), [OnWorkReleaseTipUpdate(params object[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkreleasetipupdate-params-object), [OnAgentAnimatorReseted()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentanimatorreseted), [SpecialEnergyTick()](/api/Global/Abnormalities/CreatureBase/CreatureBase#specialenergytick), [OnStageEnd()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onstageend), [OnFeverTimeOver()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfevertimeover), [OnOverlayIsolateWork()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onoverlayisolatework), [OnOverlayIsolateObserve()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onoverlayisolateobserve), [OnOpenObserveWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopenobservewindow), [OnOpenCollectionWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopencollectionwindow), [DelayAttackMotion(float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#delayattackmotion-float), [IsAttackTargetable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isattacktargetable), [GetRealTargets()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getrealtargets), [HasScriptSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasscriptsavedata), [GetSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getsavedata), [LoadData(Dictionary<string, object>)](/api/Global/Abnormalities/CreatureBase/CreatureBase#loaddata-dictionary-string-object), [LoadScriptData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#loadscriptdata), [SaveScriptData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#savescriptdata), [ExistSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#existsavedata), [RemoveSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#removesavedata), [ReplaceCommand(CreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#replacecommand-creaturemodel), [OnGamemanagerInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#ongamemanagerinit), [MakeEffectGlobalPos(string, Vector3)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectglobalpos-string-vector3), [MakeEffectGlobalPosNonTrans(string, Vector3)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectglobalposnontrans-string-vector3), [CanObservedByAgent(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#canobservedbyagent-agentmodel), [MakeSound(string, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string-float), [MakeSound(string, AudioRolloffMode)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string-audiorolloffmode), [MakeSoundQueue(params string[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesoundqueue-params-string), [MakeSoundLoop(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesoundloop-string), [OnViewDestroy()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onviewdestroy), [HasUniqueMaxObservationFinish()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquemaxobservationfinish), [UniqueMaxObservationFinish(Desc)](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquemaxobservationfinish-desc), [OnChildSuppressed(ChildCreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onchildsuppressed-childcreaturemodel), [MakeChildCreature(UnitModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makechildcreature-unitmodel), [OnKillWorker(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onkillworker-workermodel), [GenPursueCommandAlter(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#genpursuecommandalter-workermodel), [hasUniqueDeadScene()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquedeadscene), [SetHpSlider(Slider)](/api/Global/Abnormalities/CreatureBase/CreatureBase#sethpslider-slider), [SetCastingSlider(Slider)](/api/Global/Abnormalities/CreatureBase/CreatureBase#setcastingslider-slider), [HasUniqueAttackDealy()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueattackdealy), [CanTakeDamage(UnitModel, DamageInfo)](/api/Global/Abnormalities/CreatureBase/CreatureBase#cantakedamage-unitmodel-damageinfo), [OnTakePhysicalDamage(UnitModel, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontakephysicaldamage-unitmodel-float), [HasUniqueFaction()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquefaction), [OnWorkerPanic(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkerpanic-workermodel), [OnSelectMaxObservation(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onselectmaxobservation-int), [OnLoadCreatureName(ref string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onloadcreaturename-ref-string), [IsSuppressableByRoom()](/api/Global/Abnormalities/CreatureBase/CreatureBase#issuppressablebyroom), [OnWorkWindowSkillClicked(long)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkwindowskillclicked-long), [UseDefaultDamageIgnoreMessage(DamageTextEffect)](/api/Global/Abnormalities/CreatureBase/CreatureBase#usedefaultdamageignoremessage-damagetexteffect), [OnWorkAllocated(SkillTypeInfo, AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkallocated-skilltypeinfo-agentmodel), [GetPhysicalDamage(out float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getphysicaldamage-out-float), [GetMentalDamage(out float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getmentaldamage-out-float), [OnSuperArmorBreak()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onsuperarmorbreak), [UniqueStunEffect()](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquestuneffect), [HasEscapeUI()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasescapeui), [RoomCounterInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomcounterinit), [ResetQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#resetqliphothcounter), [GetMaxWorkCountView()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getmaxworkcountview), [GetQliphothCounterMax()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getqliphothcountermax), [ReducedQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#reducedqliphothcounter), [AddedQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#addedqliphothcounter), [GetRadius()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getradius), [OnElevatorStuck()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onelevatorstuck), [OnWorkClosed(UseSkill, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkclosed-useskill-int), [IsActivatedWorkDesc()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isactivatedworkdesc), [IsIndirectSuppressable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isindirectsuppressable), [GetRiskLevel()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getrisklevel), [GetName()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getname), [HasUniqueName()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquename), [OnInitialBuild()](/api/Global/Abnormalities/CreatureBase/CreatureBase#oninitialbuild), [HasUniqueCollectionCost(string, out string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquecollectioncost-string-out-string), [HasUniqueWorkSelect(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueworkselect-int), [ForcelySuccess(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#forcelysuccess-useskill), [ForcelyFail(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#forcelyfail-useskill), [TryRabbitTeleport(MapNode)](/api/Global/Abnormalities/CreatureBase/CreatureBase#tryrabbitteleport-mapnode), [CanEnterRoom()](/api/Global/Abnormalities/CreatureBase/CreatureBase#canenterroom), [AllocatedAgent](/api/Global/Abnormalities/CreatureBase/CreatureBase#allocatedagent), [skillTriggerCheck](/api/Global/Abnormalities/CreatureBase/CreatureBase#skilltriggercheck), [Unit](/api/Global/Abnormalities/CreatureBase/CreatureBase#unit), [GetSaveSrc](/api/Global/Abnormalities/CreatureBase/CreatureBase#getsavesrc), [movable](/api/Global/Abnormalities/CreatureBase/CreatureBase#movable), [currentPassage](/api/Global/Abnormalities/CreatureBase/CreatureBase#currentpassage), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)







