---
uid: WhiteNightSpace.PlagueDoctor
canonical_path: /api/WhiteNightSpace/PlagueDoctor
---
# Class PlagueDoctor
**Namespace:** [WhiteNightSpace](/api/WhiteNightSpace)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PlagueDoctor : CreatureBase, IObserver
```
> This section may have incomplete or incorrect information.
{.is-warning}


Plague Doctor!!!!!!!!!!


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase](/api/Global/Abnormalities/CreatureBase/CreatureBase) → PlagueDoctor

## Implements
[IObserver](/api/Global/Notices/IObserver)

## Constructors
### PlagueDoctor()
```csharp
public PlagueDoctor()
```

## Fields
### _angel
```csharp
private DeathAngel _angel
```


#### Field Value
**Type:** WhiteNightSpace.DeathAngel

### _animScript
```csharp
private PlagueDoctorAnim _animScript
```


#### Field Value
**Type:** WhiteNightSpace.PlagueDoctorAnim

### _apostleCount
```csharp
private const int _apostleCount = 12
```


#### Field Value
**Type:** System.Int32

### _attractFreq
```csharp
private static MinMax _attractFreq
```


#### Field Value
**Type:** Global.MinMax

### _currentKissAnim
```csharp
private Animator _currentKissAnim
```


#### Field Value
**Type:** UnityEngine.Animator

### _currentKissTarget
```csharp
private AgentModel _currentKissTarget
```


#### Field Value
**Type:** Global.AgentModel

### _currentWork
```csharp
private UseSkill _currentWork
```


#### Field Value
**Type:** Global.UseSkill

### _genData
```csharp
private List<ApostleGenData> _genData
```


#### Field Value
**Type:** System.Collections.Generic.List{WhiteNightSpace.ApostleGenData}

### _genDay
```csharp
private int _genDay
```


#### Field Value
**Type:** System.Int32

### _isKiss
```csharp
private bool _isKiss
```


#### Field Value
**Type:** System.Boolean

### _kissDurationTimer
```csharp
private Timer _kissDurationTimer
```


#### Field Value
**Type:** Global.Timer

### _kissEnd_1
```csharp
private static float _kissEnd_1
```


#### Field Value
**Type:** System.Single

### _kissEndTimer
```csharp
private Timer _kissEndTimer
```


#### Field Value
**Type:** Global.Timer

### _kissMovementTimer
```csharp
private Timer _kissMovementTimer
```


#### Field Value
**Type:** Global.Timer

### _kissSound
```csharp
private SoundEffectPlayer _kissSound
```


#### Field Value
**Type:** Global.SoundEffectPlayer

### _kissTargetInitialScale
```csharp
private Vector3 _kissTargetInitialScale
```


#### Field Value
**Type:** UnityEngine.Vector3

### _kissTime
```csharp
private static MinMax _kissTime
```


#### Field Value
**Type:** Global.MinMax

### _save
```csharp
private static string[] _save
```


#### Field Value
**Type:** System.String[]

### _workerAnimatorScale
```csharp
private static float _workerAnimatorScale
```


#### Field Value
**Type:** System.Single

### AdventLevel
```csharp
private const int AdventLevel = 12
```


#### Field Value
**Type:** System.Int32

### apostleData
```csharp
private List<ApostleData> apostleData
```


#### Field Value
**Type:** System.Collections.Generic.List{WhiteNightSpace.ApostleData}

### Bell
```csharp
public const string Bell = "creature/deathangel/Lucifer_Bell0"
```


#### Field Value
**Type:** System.String

### giftId
```csharp
public static int giftId
```


#### Field Value
**Type:** System.Int32

### ID
```csharp
public static long ID
```


#### Field Value
**Type:** System.Int64

### KissSoundSrc
```csharp
public static string KissSoundSrc
```


#### Field Value
**Type:** System.String

### QliphothCounterMax
```csharp
private const int QliphothCounterMax = 1
```


#### Field Value
**Type:** System.Int32

### TickSound
```csharp
public const string TickSound = "creature/deathangel/Lucifer_Tick1"
```


#### Field Value
**Type:** System.String

### WhiteNightID
```csharp
public static long WhiteNightID
```


#### Field Value
**Type:** System.Int64

## Properties
### AnimScript
```csharp
public PlagueDoctorAnim AnimScript { get; }
```

#### Property Value
**Type:** WhiteNightSpace.PlagueDoctorAnim

### ApostleLevel
```csharp
public int ApostleLevel { get; }
```

#### Property Value
**Type:** System.Int32

### AttractFreq
```csharp
private static float AttractFreq { get; }
```

#### Property Value
**Type:** System.Single

## Methods
### ActivateQliphothCounter()
```csharp
public override void ActivateQliphothCounter()
```


### AddApostle(AgentModel)
```csharp
public void AddApostle(AgentModel target)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.AgentModel` |  |

### AdventWhiteNight()
```csharp
public void AdventWhiteNight()
```


### BlessedAgentWorkCheck()
```csharp
public bool BlessedAgentWorkCheck()
```


#### Returns
**Type:** System.Boolean

### CancelAttract()
```csharp
public void CancelAttract()
```


### ChangeIsolateRoom()
```csharp
public void ChangeIsolateRoom()
```


### CheckAdvent()
```csharp
public static bool CheckAdvent()
```


#### Returns
**Type:** System.Boolean

### CheckApostle(AgentModel)
```csharp
public bool CheckApostle(AgentModel target)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.AgentModel` |  |

#### Returns
**Type:** System.Boolean

### ClearKiss()
```csharp
public void ClearKiss()
```


### ClearKissSound()
```csharp
private void ClearKissSound()
```


### GenDeathAngel()
```csharp
public CreatureModel GenDeathAngel()
```


#### Returns
**Type:** Global.CreatureModel

### GetApostleDesc(int)
```csharp
public CreatureStaticData.ParameterData GetApostleDesc(int targetindex)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `targetindex` | `System.Int32` |  |

#### Returns
**Type:** Global.CreatureStaticData.ParameterData

### GetApostleDescRefined(int)
```csharp
public string GetApostleDescRefined(int index)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

#### Returns
**Type:** System.String

### GetApostleDescRefined(int, List<ApostleGenData>)
```csharp
public static string GetApostleDescRefined(int index, List<ApostleGenData> data)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |
| `data` | `System.Collections.Generic.List{WhiteNightSpace.ApostleGenData}` |  |

#### Returns
**Type:** System.String

### GetApostleNames()
```csharp
public List<string> GetApostleNames()
```


#### Returns
**Type:** System.Collections.Generic.List{System.String}

### GetApostleSaveData()
```csharp
private Dictionary<int, Dictionary<string, object>> GetApostleSaveData()
```


#### Returns
**Type:** System.Collections.Generic.Dictionary{System.Int32,System.Collections.Generic.Dictionary{System.String,System.Object}}

### GetSaveData()
```csharp
public override Dictionary<string, object> GetSaveData()
```


#### Returns
**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### HasRoomCounter()
```csharp
public override bool HasRoomCounter()
```


#### Returns
**Type:** System.Boolean

### HasScriptSaveData()
```csharp
public override bool HasScriptSaveData()
```


#### Returns
**Type:** System.Boolean

### HasUniqueCollectionCost(string, out string)
```csharp
public override bool HasUniqueCollectionCost(string areaName, out string text)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `areaName` | `System.String` |  |
| `text` | `System.String` |  |

#### Returns
**Type:** System.Boolean

### IsKissing()
```csharp
public bool IsKissing()
```


#### Returns
**Type:** System.Boolean

### IsWorkable()
```csharp
public override bool IsWorkable()
```


#### Returns
**Type:** System.Boolean

### LoadApostleSaveData(int, Dictionary<int, Dictionary<string, object>>)
```csharp
private void LoadApostleSaveData(int max, Dictionary<int, Dictionary<string, object>> data)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `max` | `System.Int32` |  |
| `data` | `System.Collections.Generic.Dictionary{System.Int32,System.Collections.Generic.Dictionary{System.String,System.Object}}` |  |

### LoadData(Dictionary<string, object>)
```csharp
public override void LoadData(Dictionary<string, object> dic)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

### Log(string, bool)
```csharp
public static void Log(string log, bool isError = false)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `log` | `System.String` |  |
| `isError` | `System.Boolean` |  |

### MoveWorkerToCustomNode(WorkerModel)
```csharp
private void MoveWorkerToCustomNode(WorkerModel target)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |

### OnAdventEnd()
```csharp
public void OnAdventEnd()
```


### OnClockUIEnd()
```csharp
public void OnClockUIEnd()
```


### OnEndKiss()
```csharp
public void OnEndKiss()
```


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


### OnInit()
```csharp
public override void OnInit()
```


### OnInitialBuild()
```csharp
public override void OnInitialBuild()
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

### OnOpenWorkWindow()
```csharp
public override bool OnOpenWorkWindow()
```


#### Returns
**Type:** System.Boolean

### OnPlagueDoctorAdventEnd()
```csharp
public void OnPlagueDoctorAdventEnd()
```


### OnSkillGoalComplete(UseSkill)
```csharp
public override void OnSkillGoalComplete(UseSkill skill)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

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

### ParamInit()
```csharp
public override void ParamInit()
```


### StartKiss(AgentModel)
```csharp
public void StartKiss(AgentModel target)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.AgentModel` |  |

## Inherited Members
[isolateSpriteSrc](/api/Global/Abnormalities/CreatureBase/CreatureBase#isolatespritesrc), [model](/api/Global/Abnormalities/CreatureBase/CreatureBase#model), [skill](/api/Global/Abnormalities/CreatureBase/CreatureBase#skill), [kitEvent](/api/Global/Abnormalities/CreatureBase/CreatureBase#kitevent), [hasUniqueEscapeLogic](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueescapelogic), [isWorkAllocated](/api/Global/Abnormalities/CreatureBase/CreatureBase#isworkallocated), [_allocatedAgent](/api/Global/Abnormalities/CreatureBase/CreatureBase#allocatedagent), [damage](/api/Global/Abnormalities/CreatureBase/CreatureBase#damage), [OnReleaseSpecialTip](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleasespecialtip), [specialSkillTipParamList](/api/Global/Abnormalities/CreatureBase/CreatureBase#specialskilltipparamlist), [_check](/api/Global/Abnormalities/CreatureBase/CreatureBase#check), [SetModel(CreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#setmodel-creaturemodel), [OnViewInitPrev(CreatureUnit)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onviewinitprev-creatureunit), [OnFixedUpdateInSkill(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfixedupdateinskill-useskill), [OnSkillFailWorkTick(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillfailworktick-useskill), [OnSkillSuccessWorkTick(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillsuccessworktick-useskill), [OnSkillTickUpdate(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskilltickupdate-useskill), [PermitCancelCurrentWork()](/api/Global/Abnormalities/CreatureBase/CreatureBase#permitcancelcurrentwork), [GetKitCreatureProcessTime()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getkitcreatureprocesstime), [OnBonusWorkProb()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onbonusworkprob), [GetDamageMultiplierInWork(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdamagemultiplierinwork-useskill), [TranformWorkProb(float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#tranformworkprob-float), [OnEnterRoom(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onenterroom-useskill), [OnReleaseWork(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleasework-useskill), [OnFinishWork(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfinishwork-useskill), [OnReturn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreturn), [UniqueEscape()](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniqueescape), [Escape()](/api/Global/Abnormalities/CreatureBase/CreatureBase#escape), [GetSpecialSkill()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getspecialskill), [GetDebugText()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdebugtext), [OnTimerEnd()](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontimerend), [MakeEffect(IsolateRoom, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffect-isolateroom-int), [MakeEffectAlter(IsolateRoom, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectalter-isolateroom-int), [Prob(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#prob-int), [isAttackInWorkProcess()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isattackinworkprocess), [OnAttackInWorkProcess(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onattackinworkprocess-useskill), [AttackProcess(UnitModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#attackprocess-unitmodel), [AutoFeelingDown()](/api/Global/Abnormalities/CreatureBase/CreatureBase#autofeelingdown), [AgentAnimCalled(int, WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#agentanimcalled-int-workermodel), [MakingEffect(string, float, string, Transform, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float-string-transform-int), [MakingEffect(string, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float), [MakeEffectAttachedToHead(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectattachedtohead-string), [MakingEffect(string, float, string, Vector3, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float-string-vector3-int), [OnAgentWorkEndAnimationPlayed(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentworkendanimationplayed-useskill), [OnAgentAllocateWork(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentallocatework-agentmodel), [OnSuppressed()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onsuppressed), [OnStageRelease()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onstagerelease), [OnAllocatedWork(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onallocatedwork-agentmodel), [OnReleaseWorkAllocated()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleaseworkallocated), [ObserveLevelChangeForSpecialSkillTip()](/api/Global/Abnormalities/CreatureBase/CreatureBase#observelevelchangeforspecialskilltip), [OnObserveLevelChanged()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onobservelevelchanged), [HasUniqueProcessWorkNarration()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueprocessworknarration), [UniqueProcessWorkNarration(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniqueprocessworknarration-useskill), [RoomSpriteInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomspriteinit), [RoomEscapeSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomescapespriteon), [RoomEscapeSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomescapespriteoff), [RoomSkillSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomskillspriteon), [RoomSkillSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomskillspriteoff), [RoomStateSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomstatespriteon), [RoomStateSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomstatespriteoff), [OnForceSpecialSkillTipReveal(string, params object[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onforcespecialskilltipreveal-string-params-object), [OnWorkReleaseSpeicalSkillTipReveal(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkreleasespeicalskilltipreveal-string), [OnWorkReleaseTipUpdate(params object[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkreleasetipupdate-params-object), [OnAgentAnimatorReseted()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentanimatorreseted), [SpecialEnergyTick()](/api/Global/Abnormalities/CreatureBase/CreatureBase#specialenergytick), [OnStageEnd()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onstageend), [OnFeverTimeOver()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfevertimeover), [OnOverlayIsolateWork()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onoverlayisolatework), [OnOverlayIsolateObserve()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onoverlayisolateobserve), [OnOpenObserveWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopenobservewindow), [OnOpenCollectionWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopencollectionwindow), [DelayAttackMotion(float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#delayattackmotion-float), [IsAttackTargetable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isattacktargetable), [GetRealTargets()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getrealtargets), [LoadScriptData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#loadscriptdata), [SaveScriptData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#savescriptdata), [ExistSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#existsavedata), [RemoveSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#removesavedata), [ReplaceCommand(CreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#replacecommand-creaturemodel), [MakeEffectGlobalPos(string, Vector3)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectglobalpos-string-vector3), [MakeEffectGlobalPosNonTrans(string, Vector3)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectglobalposnontrans-string-vector3), [CanObservedByAgent(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#canobservedbyagent-agentmodel), [MakeSound(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string), [MakeSound(string, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string-float), [MakeSound(string, AudioRolloffMode)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string-audiorolloffmode), [MakeSoundQueue(params string[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesoundqueue-params-string), [MakeSoundLoop(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesoundloop-string), [OnViewDestroy()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onviewdestroy), [HasUniqueMaxObservationFinish()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquemaxobservationfinish), [UniqueMaxObservationFinish(Desc)](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquemaxobservationfinish-desc), [OnChildSuppressed(ChildCreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onchildsuppressed-childcreaturemodel), [MakeChildCreature(UnitModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makechildcreature-unitmodel), [OnKillWorker(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onkillworker-workermodel), [GenPursueCommandAlter(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#genpursuecommandalter-workermodel), [OnAfterSuppressed()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onaftersuppressed), [hasUniqueDeadScene()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquedeadscene), [SetHpSlider(Slider)](/api/Global/Abnormalities/CreatureBase/CreatureBase#sethpslider-slider), [SetCastingSlider(Slider)](/api/Global/Abnormalities/CreatureBase/CreatureBase#setcastingslider-slider), [HasUniqueAttackDealy()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueattackdealy), [CanTakeDamage(UnitModel, DamageInfo)](/api/Global/Abnormalities/CreatureBase/CreatureBase#cantakedamage-unitmodel-damageinfo), [OnTakePhysicalDamage(UnitModel, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontakephysicaldamage-unitmodel-float), [HasUniqueFaction()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquefaction), [OnWorkerPanic(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkerpanic-workermodel), [OnSelectMaxObservation(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onselectmaxobservation-int), [OnLoadCreatureName(ref string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onloadcreaturename-ref-string), [IsSuppressable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#issuppressable), [IsSuppressableByRoom()](/api/Global/Abnormalities/CreatureBase/CreatureBase#issuppressablebyroom), [IsAutoSuppressable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isautosuppressable), [OnWorkWindowSkillClicked(long)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkwindowskillclicked-long), [UseDefaultDamageIgnoreMessage(DamageTextEffect)](/api/Global/Abnormalities/CreatureBase/CreatureBase#usedefaultdamageignoremessage-damagetexteffect), [OnWorkAllocated(SkillTypeInfo, AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkallocated-skilltypeinfo-agentmodel), [GetPhysicalDamage(out float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getphysicaldamage-out-float), [GetMentalDamage(out float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getmentaldamage-out-float), [OnSuperArmorBreak()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onsuperarmorbreak), [UniqueStunEffect()](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquestuneffect), [HasEscapeUI()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasescapeui), [RoomCounterInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomcounterinit), [ResetQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#resetqliphothcounter), [GetMaxWorkCountView()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getmaxworkcountview), [GetQliphothCounterMax()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getqliphothcountermax), [ReducedQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#reducedqliphothcounter), [AddedQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#addedqliphothcounter), [OnTakeDamage(UnitModel, DamageInfo, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontakedamage-unitmodel-damageinfo-float), [GetRadius()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getradius), [OnElevatorStuck()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onelevatorstuck), [OnWorkClosed(UseSkill, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkclosed-useskill-int), [IsActivatedWorkDesc()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isactivatedworkdesc), [IsSensoredInPassage()](/api/Global/Abnormalities/CreatureBase/CreatureBase#issensoredinpassage), [IsIndirectSuppressable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isindirectsuppressable), [GetRiskLevel()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getrisklevel), [GetName()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getname), [UniqueMoveControl()](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquemovecontrol), [HasUniqueName()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquename), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdamagefactor-unitmodel-damageinfo), [OnOpenCommandWindow(Button[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopencommandwindow-button), [HasUniqueCommandAction(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquecommandaction-int), [HasUniqueWorkSelect(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueworkselect-int), [ForcelySuccess(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#forcelysuccess-useskill), [ForcelyFail(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#forcelyfail-useskill), [TryRabbitTeleport(MapNode)](/api/Global/Abnormalities/CreatureBase/CreatureBase#tryrabbitteleport-mapnode), [CanEnterRoom()](/api/Global/Abnormalities/CreatureBase/CreatureBase#canenterroom), [AllocatedAgent](/api/Global/Abnormalities/CreatureBase/CreatureBase#allocatedagent), [skillTriggerCheck](/api/Global/Abnormalities/CreatureBase/CreatureBase#skilltriggercheck), [Unit](/api/Global/Abnormalities/CreatureBase/CreatureBase#unit), [GetSaveSrc](/api/Global/Abnormalities/CreatureBase/CreatureBase#getsavesrc), [movable](/api/Global/Abnormalities/CreatureBase/CreatureBase#movable), [currentPassage](/api/Global/Abnormalities/CreatureBase/CreatureBase#currentpassage), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)








