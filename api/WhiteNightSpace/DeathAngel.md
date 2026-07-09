---
uid: WhiteNightSpace.DeathAngel
canonical_path: /api/WhiteNightSpace/DeathAngel
---
# Class DeathAngel
**Namespace:** [WhiteNightSpace](/api/WhiteNightSpace)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DeathAngel : CreatureBase
```
> This section may have incomplete or incorrect information.
{.is-warning}


WhiteNight <3


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase](/api/Global/Abnormalities/CreatureBase/CreatureBase) → DeathAngel

## Constructors
### DeathAngel()
```csharp
public DeathAngel()
```

## Fields
### _animScript
```csharp
private DeathAngelAnim _animScript
```


#### Field Value
**Type:** WhiteNightSpace.DeathAngelAnim

### _badDamageInfo
```csharp
private static DamageInfo _badDamageInfo
```


#### Field Value
**Type:** Global.DamageInfo

### _bgmFadeTime
```csharp
private Timer _bgmFadeTime
```


#### Field Value
**Type:** Global.Timer

### _blockUI
```csharp
private const string _blockUI = "Effect/Creature/DeathAngel/DeathAngelBlock"
```


#### Field Value
**Type:** System.String

### _confessDead
```csharp
private UnscaledTimer _confessDead
```


#### Field Value
**Type:** Global.UnscaledTimer

### _confessDeadDamage
```csharp
private static DamageInfo _confessDeadDamage
```


#### Field Value
**Type:** Global.DamageInfo

### _confessDeadFreq
```csharp
private const float _confessDeadFreq = 0.3
```


#### Field Value
**Type:** System.Single

### _currentSefira
```csharp
private Sefira _currentSefira
```


#### Field Value
**Type:** Global.Sefira

### _escapeFreqRange
```csharp
private static MinMax _escapeFreqRange
```


#### Field Value
**Type:** Global.MinMax

### _escapeLoop
```csharp
private SoundEffectPlayer _escapeLoop
```


#### Field Value
**Type:** Global.SoundEffectPlayer

### _escapeSense
```csharp
private CreatureCameraUtil _escapeSense
```

#### Field Value
**Type:** CreatureCameraUtil.CreatureCameraUtil

### _escapeSkillDamage
```csharp
private static DamageInfo _escapeSkillDamage
```


#### Field Value
**Type:** Global.DamageInfo

### _escapeSkillTimer
```csharp
private Timer _escapeSkillTimer
```


#### Field Value
**Type:** Global.Timer

### _goodRecoverFactor
```csharp
private const float _goodRecoverFactor = 1
```


#### Field Value
**Type:** System.Single

### _isPrevEscaped
```csharp
private bool _isPrevEscaped
```


#### Field Value
**Type:** System.Boolean

### _normalQliphothIncreaseProb
```csharp
private const float _normalQliphothIncreaseProb = 0.4
```


#### Field Value
**Type:** System.Single

### _normRecoverFactor
```csharp
private const float _normRecoverFactor = 0.5
```


#### Field Value
**Type:** System.Single

### _outPos
```csharp
private static Vector3 _outPos
```


#### Field Value
**Type:** UnityEngine.Vector3

### _outScale
```csharp
private static Vector3 _outScale
```


#### Field Value
**Type:** UnityEngine.Vector3

### _qliphothSubTime
```csharp
private const float _qliphothSubTime = 90
```


#### Field Value
**Type:** System.Single

### _qliphothSubTimer
```csharp
private Timer _qliphothSubTimer
```


#### Field Value
**Type:** Global.Timer

### _roomPos
```csharp
private static Vector3 _roomPos
```


#### Field Value
**Type:** UnityEngine.Vector3

### _roomScale
```csharp
private static Vector3 _roomScale
```


#### Field Value
**Type:** UnityEngine.Vector3

### apostleCount
```csharp
private const int apostleCount = 12
```


#### Field Value
**Type:** System.Int32

### apostleData
```csharp
private List<ApostleData> apostleData
```


#### Field Value
**Type:** System.Collections.Generic.List{WhiteNightSpace.ApostleData}

### apostles
```csharp
private List<DeathAngelApostle> apostles
```


#### Field Value
**Type:** System.Collections.Generic.List{WhiteNightSpace.DeathAngelApostle}

### badState
```csharp
private Sprite badState
```


#### Field Value
**Type:** UnityEngine.Sprite

### betrayer
```csharp
private DeathAngelBetrayerBuf betrayer
```


#### Field Value
**Type:** Global.DeathAngelBetrayerBuf

### bgm_escape
```csharp
public const string bgm_escape = "creature/deathangel/Lucifer_standbg0"
```


#### Field Value
**Type:** System.String

### bgmChanged
```csharp
private bool bgmChanged
```


#### Field Value
**Type:** System.Boolean

### blockUI
```csharp
private DeathAngelPlaySpeedBlockUI blockUI
```


#### Field Value
**Type:** WhiteNightSpace.DeathAngelPlaySpeedBlockUI

### damageSound
```csharp
public const string damageSound = "creature/WhiteNight/WhiteNight_Shout"
```


#### Field Value
**Type:** System.String

### genDataSave
```csharp
private List<ApostleGenData> genDataSave
```


#### Field Value
**Type:** System.Collections.Generic.List{WhiteNightSpace.ApostleGenData}

### goodState
```csharp
private Sprite goodState
```


#### Field Value
**Type:** UnityEngine.Sprite

### healSound
```csharp
public const string healSound = "creature/WhiteNight/WhiteNight_Heal"
```


#### Field Value
**Type:** System.String

### normalState
```csharp
private Sprite normalState
```


#### Field Value
**Type:** UnityEngine.Sprite

### oneBadManyGood
```csharp
private OneBadManyGood oneBadManyGood
```


#### Field Value
**Type:** Global.OneBadManyGood

### outSound
```csharp
public const string outSound = "creature/WhiteNight/WhiteNight_Atk"
```


#### Field Value
**Type:** System.String

### QliphothMax
```csharp
private const int QliphothMax = 3
```


#### Field Value
**Type:** System.Int32

### suppress_confess_0
```csharp
public const string suppress_confess_0 = "creature/WhiteNight/WhiteNight_Dead1"
```


#### Field Value
**Type:** System.String

### suppress_confess_1
```csharp
public const string suppress_confess_1 = "creature/WhiteNight/WhiteNight_Dead2"
```


#### Field Value
**Type:** System.String

### suppress_confess_2
```csharp
public const string suppress_confess_2 = "creature/WhiteNight/WhiteNight_Dead3"
```


#### Field Value
**Type:** System.String

### suppressByHit
```csharp
public const string suppressByHit = "creature/deathangel/Lucifer_yaduafinish_poof"
```


#### Field Value
**Type:** System.String

## Properties
### _escapeSkillFreq
```csharp
private static float _escapeSkillFreq { get; }
```

#### Property Value
**Type:** System.Single

### AnimScript
```csharp
public DeathAngelAnim AnimScript { get; }
```

#### Property Value
**Type:** WhiteNightSpace.DeathAngelAnim

### CurrentSefira
```csharp
public Sefira CurrentSefira { get; }
```

#### Property Value
**Type:** Global.Sefira

### IsPrevEscaped
```csharp
public bool IsPrevEscaped { get; }
```

#### Property Value
**Type:** System.Boolean

## Methods
### ActivateQliphothCounter()
```csharp
public override void ActivateQliphothCounter()
```


### ActivateWorkSkill(CreatureFeelingState)
```csharp
private void ActivateWorkSkill(CreatureFeelingState feelingState)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `feelingState` | `Global.CreatureFeelingState` |  |

### AddedQliphothCounter()
```csharp
public override void AddedQliphothCounter()
```


### ChangeIsolateRoom()
```csharp
public void ChangeIsolateRoom()
```


### CheckStateSprite()
```csharp
private void CheckStateSprite()
```


### ClearEscapeLoop()
```csharp
private void ClearEscapeLoop()
```


### DamageSefira()
```csharp
private void DamageSefira()
```


### Escape()
```csharp
public override void Escape()
```


### EscapeSkill()
```csharp
private void EscapeSkill()
```


### FindAgent(ApostleData, List<AgentModel>)
```csharp
public static AgentModel FindAgent(ApostleData data, List<AgentModel> searchPool)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `data` | `WhiteNightSpace.ApostleData` |  |
| `searchPool` | `System.Collections.Generic.List{AgentModel}` |  |

#### Returns
**Type:** Global.AgentModel

### GenApostle(List<ApostleGenData>)
```csharp
public void GenApostle(List<ApostleGenData> genDataList)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `genDataList` | `System.Collections.Generic.List{WhiteNightSpace.ApostleGenData}` |  |

### GetAdeventTargets(List<ApostleData>)
```csharp
public static List<ApostleGenData> GetAdeventTargets(List<ApostleData> apostles)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `apostles` | `System.Collections.Generic.List{WhiteNightSpace.ApostleData}` |  |

#### Returns
**Type:** System.Collections.Generic.List{WhiteNightSpace.ApostleGenData}

### GetApostleNames()
```csharp
public List<string> GetApostleNames()
```


#### Returns
**Type:** System.Collections.Generic.List{System.String}

### GetFunctionDesc(string)
```csharp
public string GetFunctionDesc(string key)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |

#### Returns
**Type:** System.String

### GiveGlobalDamage(UnitModel)
```csharp
public void GiveGlobalDamage(UnitModel target)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |

### HasRoomCounter()
```csharp
public override bool HasRoomCounter()
```


#### Returns
**Type:** System.Boolean

### IsKilledByConfess()
```csharp
public bool IsKilledByConfess()
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

### MakeOverload(int)
```csharp
private void MakeOverload(int overloadCount = 12)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `overloadCount` | `System.Int32` |  |

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

### OnGamemanagerInit()
```csharp
public override void OnGamemanagerInit()
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


### OnSuppressedByConfess(OneBadManyGood)
```csharp
public void OnSuppressedByConfess(OneBadManyGood oneBad)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `oneBad` | `Global.OneBadManyGood` |  |

### OnSuppressedByDamage()
```csharp
public void OnSuppressedByDamage()
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

### Prob(float)
```csharp
public static bool Prob(float value)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `value` | `System.Single` |  |

#### Returns
**Type:** System.Boolean

### RecoverAllFacility()
```csharp
private void RecoverAllFacility()
```


### RecoverList(List<AgentModel>, float)
```csharp
private void RecoverList(List<AgentModel> targets, float factor)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `targets` | `System.Collections.Generic.List{AgentModel}` |  |
| `factor` | `System.Single` |  |

### RecoverSefira()
```csharp
private void RecoverSefira()
```


### ReducedQliphothCounter()
```csharp
public override void ReducedQliphothCounter()
```


### RoomSpriteInit()
```csharp
public override void RoomSpriteInit()
```


### SecondAdvent()
```csharp
public void SecondAdvent()
```


### SetApostleData(List<ApostleData>)
```csharp
public void SetApostleData(List<ApostleData> data)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `data` | `System.Collections.Generic.List{WhiteNightSpace.ApostleData}` |  |

### SetCameraUtil(CreatureCameraUtil_Inspector)
```csharp
public void SetCameraUtil(CreatureCameraUtil_Inspector insp)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `insp` | `CreatureCameraUtil.CreatureCameraUtil_Inspector` |  |

### UniqueEscape()
```csharp
public override void UniqueEscape()
```


### Update()
```csharp
public void Update()
```


## Inherited Members
[isolateSpriteSrc](/api/Global/Abnormalities/CreatureBase/CreatureBase#isolatespritesrc), [model](/api/Global/Abnormalities/CreatureBase/CreatureBase#model), [skill](/api/Global/Abnormalities/CreatureBase/CreatureBase#skill), [kitEvent](/api/Global/Abnormalities/CreatureBase/CreatureBase#kitevent), [hasUniqueEscapeLogic](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueescapelogic), [isWorkAllocated](/api/Global/Abnormalities/CreatureBase/CreatureBase#isworkallocated), [_allocatedAgent](/api/Global/Abnormalities/CreatureBase/CreatureBase#allocatedagent), [damage](/api/Global/Abnormalities/CreatureBase/CreatureBase#damage), [OnReleaseSpecialTip](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleasespecialtip), [specialSkillTipParamList](/api/Global/Abnormalities/CreatureBase/CreatureBase#specialskilltipparamlist), [_check](/api/Global/Abnormalities/CreatureBase/CreatureBase#check), [SetModel(CreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#setmodel-creaturemodel), [OnInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#oninit), [OnViewInitPrev(CreatureUnit)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onviewinitprev-creatureunit), [OnFixedUpdateInSkill(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfixedupdateinskill-useskill), [OnSkillFailWorkTick(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillfailworktick-useskill), [OnSkillSuccessWorkTick(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillsuccessworktick-useskill), [OnSkillTickUpdate(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskilltickupdate-useskill), [PermitCancelCurrentWork()](/api/Global/Abnormalities/CreatureBase/CreatureBase#permitcancelcurrentwork), [GetKitCreatureProcessTime()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getkitcreatureprocesstime), [OnBonusWorkProb()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onbonusworkprob), [GetDamageMultiplierInWork(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdamagemultiplierinwork-useskill), [TranformWorkProb(float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#tranformworkprob-float), [OnReleaseWork(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleasework-useskill), [OnFinishWork(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfinishwork-useskill), [GetSpecialSkill()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getspecialskill), [GetDebugText()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdebugtext), [OnTimerEnd()](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontimerend), [MakeEffect(IsolateRoom, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffect-isolateroom-int), [MakeEffectAlter(IsolateRoom, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectalter-isolateroom-int), [Prob(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#prob-int), [isAttackInWorkProcess()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isattackinworkprocess), [OnAttackInWorkProcess(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onattackinworkprocess-useskill), [AttackProcess(UnitModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#attackprocess-unitmodel), [AutoFeelingDown()](/api/Global/Abnormalities/CreatureBase/CreatureBase#autofeelingdown), [AgentAnimCalled(int, WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#agentanimcalled-int-workermodel), [MakingEffect(string, float, string, Transform, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float-string-transform-int), [MakingEffect(string, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float), [MakeEffectAttachedToHead(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectattachedtohead-string), [MakingEffect(string, float, string, Vector3, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float-string-vector3-int), [OnAgentWorkEndAnimationPlayed(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentworkendanimationplayed-useskill), [OnAgentAllocateWork(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentallocatework-agentmodel), [OnAllocatedWork(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onallocatedwork-agentmodel), [OnReleaseWorkAllocated()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleaseworkallocated), [ObserveLevelChangeForSpecialSkillTip()](/api/Global/Abnormalities/CreatureBase/CreatureBase#observelevelchangeforspecialskilltip), [OnObserveLevelChanged()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onobservelevelchanged), [HasUniqueProcessWorkNarration()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueprocessworknarration), [UniqueProcessWorkNarration(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniqueprocessworknarration-useskill), [RoomEscapeSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomescapespriteon), [RoomEscapeSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomescapespriteoff), [RoomSkillSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomskillspriteon), [RoomSkillSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomskillspriteoff), [RoomStateSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomstatespriteon), [RoomStateSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomstatespriteoff), [OnForceSpecialSkillTipReveal(string, params object[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onforcespecialskilltipreveal-string-params-object), [OnWorkReleaseSpeicalSkillTipReveal(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkreleasespeicalskilltipreveal-string), [OnWorkReleaseTipUpdate(params object[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkreleasetipupdate-params-object), [OnAgentAnimatorReseted()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentanimatorreseted), [SpecialEnergyTick()](/api/Global/Abnormalities/CreatureBase/CreatureBase#specialenergytick), [OnStageEnd()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onstageend), [OnFeverTimeOver()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfevertimeover), [OnOverlayIsolateWork()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onoverlayisolatework), [OnOverlayIsolateObserve()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onoverlayisolateobserve), [OnOpenObserveWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopenobservewindow), [OnOpenWorkWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopenworkwindow), [OnOpenCollectionWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopencollectionwindow), [DelayAttackMotion(float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#delayattackmotion-float), [IsAttackTargetable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isattacktargetable), [GetRealTargets()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getrealtargets), [HasScriptSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasscriptsavedata), [GetSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getsavedata), [LoadData(Dictionary<string, object>)](/api/Global/Abnormalities/CreatureBase/CreatureBase#loaddata-dictionary-string-object), [LoadScriptData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#loadscriptdata), [SaveScriptData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#savescriptdata), [ExistSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#existsavedata), [RemoveSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#removesavedata), [ReplaceCommand(CreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#replacecommand-creaturemodel), [MakeEffectGlobalPos(string, Vector3)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectglobalpos-string-vector3), [MakeEffectGlobalPosNonTrans(string, Vector3)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectglobalposnontrans-string-vector3), [CanObservedByAgent(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#canobservedbyagent-agentmodel), [MakeSound(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string), [MakeSound(string, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string-float), [MakeSound(string, AudioRolloffMode)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string-audiorolloffmode), [MakeSoundQueue(params string[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesoundqueue-params-string), [MakeSoundLoop(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesoundloop-string), [OnViewDestroy()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onviewdestroy), [IsWorkable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isworkable), [ParamInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#paraminit), [HasUniqueMaxObservationFinish()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquemaxobservationfinish), [UniqueMaxObservationFinish(Desc)](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquemaxobservationfinish-desc), [OnChildSuppressed(ChildCreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onchildsuppressed-childcreaturemodel), [MakeChildCreature(UnitModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makechildcreature-unitmodel), [OnKillWorker(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onkillworker-workermodel), [GenPursueCommandAlter(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#genpursuecommandalter-workermodel), [OnAfterSuppressed()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onaftersuppressed), [hasUniqueDeadScene()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquedeadscene), [SetHpSlider(Slider)](/api/Global/Abnormalities/CreatureBase/CreatureBase#sethpslider-slider), [SetCastingSlider(Slider)](/api/Global/Abnormalities/CreatureBase/CreatureBase#setcastingslider-slider), [HasUniqueAttackDealy()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueattackdealy), [CanTakeDamage(UnitModel, DamageInfo)](/api/Global/Abnormalities/CreatureBase/CreatureBase#cantakedamage-unitmodel-damageinfo), [OnTakePhysicalDamage(UnitModel, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontakephysicaldamage-unitmodel-float), [HasUniqueFaction()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquefaction), [OnWorkerPanic(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkerpanic-workermodel), [OnSelectMaxObservation(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onselectmaxobservation-int), [OnLoadCreatureName(ref string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onloadcreaturename-ref-string), [IsSuppressable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#issuppressable), [IsSuppressableByRoom()](/api/Global/Abnormalities/CreatureBase/CreatureBase#issuppressablebyroom), [IsAutoSuppressable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isautosuppressable), [OnWorkWindowSkillClicked(long)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkwindowskillclicked-long), [UseDefaultDamageIgnoreMessage(DamageTextEffect)](/api/Global/Abnormalities/CreatureBase/CreatureBase#usedefaultdamageignoremessage-damagetexteffect), [OnWorkAllocated(SkillTypeInfo, AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkallocated-skilltypeinfo-agentmodel), [GetPhysicalDamage(out float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getphysicaldamage-out-float), [GetMentalDamage(out float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getmentaldamage-out-float), [OnSuperArmorBreak()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onsuperarmorbreak), [UniqueStunEffect()](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquestuneffect), [HasEscapeUI()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasescapeui), [RoomCounterInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomcounterinit), [ResetQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#resetqliphothcounter), [GetMaxWorkCountView()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getmaxworkcountview), [GetQliphothCounterMax()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getqliphothcountermax), [GetRadius()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getradius), [OnElevatorStuck()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onelevatorstuck), [OnWorkClosed(UseSkill, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkclosed-useskill-int), [IsActivatedWorkDesc()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isactivatedworkdesc), [IsSensoredInPassage()](/api/Global/Abnormalities/CreatureBase/CreatureBase#issensoredinpassage), [IsIndirectSuppressable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isindirectsuppressable), [GetRiskLevel()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getrisklevel), [GetName()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getname), [UniqueMoveControl()](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquemovecontrol), [HasUniqueName()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquename), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdamagefactor-unitmodel-damageinfo), [OnInitialBuild()](/api/Global/Abnormalities/CreatureBase/CreatureBase#oninitialbuild), [HasUniqueCollectionCost(string, out string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquecollectioncost-string-out-string), [OnOpenCommandWindow(Button[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopencommandwindow-button), [HasUniqueCommandAction(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquecommandaction-int), [HasUniqueWorkSelect(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueworkselect-int), [ForcelySuccess(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#forcelysuccess-useskill), [ForcelyFail(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#forcelyfail-useskill), [TryRabbitTeleport(MapNode)](/api/Global/Abnormalities/CreatureBase/CreatureBase#tryrabbitteleport-mapnode), [CanEnterRoom()](/api/Global/Abnormalities/CreatureBase/CreatureBase#canenterroom), [AllocatedAgent](/api/Global/Abnormalities/CreatureBase/CreatureBase#allocatedagent), [skillTriggerCheck](/api/Global/Abnormalities/CreatureBase/CreatureBase#skilltriggercheck), [Unit](/api/Global/Abnormalities/CreatureBase/CreatureBase#unit), [GetSaveSrc](/api/Global/Abnormalities/CreatureBase/CreatureBase#getsavesrc), [movable](/api/Global/Abnormalities/CreatureBase/CreatureBase#movable), [currentPassage](/api/Global/Abnormalities/CreatureBase/CreatureBase#currentpassage), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)








