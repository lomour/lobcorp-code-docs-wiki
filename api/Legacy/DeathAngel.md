---
title: DeathAngel
description: 
published: true
date: 2026-02-26T23:58:16.612Z
tags: 
editor: markdown
dateCreated: 2026-01-15T05:27:46.685Z
---

# Class DeathAngel
**Namespace:** [Legacy](/api/Legacy)
**Assembly:** Assembly-CSharp.dll

```csharp
public class DeathAngel : CreatureBase
```
> This section may have incomplete or incorrect information.
{.is-warning}

Legacy WhiteNight...

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase](/api/Global/Abnormalities/CreatureBase/CreatureBase) → DeathAngel

## Constructors
### DeathAngel()
```csharp
public DeathAngel()
```

## Fields
### _isEscaped
```csharp
private bool _isEscaped
```

#### Field Value
**Type:** System.Boolean

### _left
```csharp
private MapNode _left
```

#### Field Value
**Type:** Global.MapNode

### _right
```csharp
private MapNode _right
```

#### Field Value
**Type:** Global.MapNode

### _sefiraPassage
```csharp
private PassageObject _sefiraPassage
```

#### Field Value
**Type:** Global.PassageObject

### _skillInterval
```csharp
private int _skillInterval
```

#### Field Value
**Type:** System.Int32

### agentEffect
```csharp
public const string agentEffect = "Effect/Creature/DeathAngel/AgentExplode"
```

#### Field Value
**Type:** System.String

### apostleCount
```csharp
private const int apostleCount = 12
```


#### Field Value
**Type:** System.Int32

### apostleEffect
```csharp
public const string apostleEffect = "Effect/Creature/DeathAngel/ApostleExplode"
```

#### Field Value
**Type:** System.String

### apostleList
```csharp
public List<DeathAngelApostle> apostleList
```

#### Field Value
**Type:** System.Collections.Generic.List{Legacy.DeathAngelApostle}

### apostles
```csharp
private DeathAngel.Apostle[] apostles
```

#### Field Value
**Type:** Legacy.DeathAngel.Apostle[]

### badState
```csharp
private Sprite badState
```


#### Field Value
**Type:** UnityEngine.Sprite

### badworkSound
```csharp
private const string badworkSound = "creature/deathangel/Choir1"
```

#### Field Value
**Type:** System.String

### betrayDead
```csharp
private const string betrayDead = "creature/deathangel/revive0"
```

#### Field Value
**Type:** System.String

### confessEffect
```csharp
public const string confessEffect = "Effect/Creature/DeathAngel/AngelFall"
```

#### Field Value
**Type:** System.String

### confessTimer
```csharp
private Timer confessTimer
```

#### Field Value
**Type:** Global.Timer

### currentEffect
```csharp
private GameObject currentEffect
```

#### Field Value
**Type:** UnityEngine.GameObject

### currentExtinct
```csharp
private bool currentExtinct
```

#### Field Value
**Type:** System.Boolean

### currentSkill
```csharp
private UseSkill currentSkill
```

#### Field Value
**Type:** Global.UseSkill

### deadOrAliveProb
```csharp
private const int deadOrAliveProb = 50
```

#### Field Value
**Type:** System.Int32

### deathangelEffect
```csharp
public const string deathangelEffect = "Effect/Creature/DeathAngel/LuciferExplode"
```

#### Field Value
**Type:** System.String

### docAdventCall
```csharp
private bool docAdventCall
```

#### Field Value
**Type:** System.Boolean

### doctor
```csharp
private PlagueDoctor doctor
```

#### Field Value
**Type:** Legacy.PlagueDoctor

### explodeSounds
```csharp
private static string[] explodeSounds
```

#### Field Value
**Type:** System.String[]

### extinctEffect
```csharp
public const string extinctEffect = "Effect/Creature/DeathAngel/AdventLight"
```

#### Field Value
**Type:** System.String

### factionId
```csharp
public const string factionId = "11"
```

#### Field Value
**Type:** System.String

### goodState
```csharp
private Sprite goodState
```


#### Field Value
**Type:** UnityEngine.Sprite

### goodworkSound
```csharp
private const string goodworkSound = "creature/onebad_good/oneBad_special_sry"
```

#### Field Value
**Type:** System.String

### isAdvented
```csharp
private bool isAdvented
```

#### Field Value
**Type:** System.Boolean

### isConfess
```csharp
private bool isConfess
```

#### Field Value
**Type:** System.Boolean

### iudasDelay
```csharp
private const float iudasDelay = 5
```

#### Field Value
**Type:** System.Single

### normalState
```csharp
private Sprite normalState
```


#### Field Value
**Type:** UnityEngine.Sprite

### observedId
```csharp
private List<int> observedId
```

#### Field Value
**Type:** System.Collections.Generic.List{System.Int32}

### recoverEffect
```csharp
public const string recoverEffect = "Effect/Creature/DeathAngel/Ray"
```

#### Field Value
**Type:** System.String

### resurrectSound
```csharp
private const string resurrectSound = "creature/deathangel/Lucifer_Advent"
```

#### Field Value
**Type:** System.String

### resurrectTime
```csharp
private const float resurrectTime = 90
```

#### Field Value
**Type:** System.Single

### resurrectTimer
```csharp
private Timer resurrectTimer
```

#### Field Value
**Type:** Global.Timer

### skillIntervalTime
```csharp
private const float skillIntervalTime = 30
```

#### Field Value
**Type:** System.Single

### skillIntervalTimer
```csharp
private Timer skillIntervalTimer
```

#### Field Value
**Type:** Global.Timer

### soundSrc
```csharp
private const string soundSrc = "Sounds/creature/deathangel/Lucifer_Advent1"
```

#### Field Value
**Type:** System.String

### specialSkillId
```csharp
private const long specialSkillId = 100015
```

#### Field Value
**Type:** System.Int64

### teleportTarget
```csharp
private MapNode teleportTarget
```

#### Field Value
**Type:** Global.MapNode

## Properties
### animScript
```csharp
public DeathAngelAnim animScript { get; }
```

#### Property Value
**Type:** Legacy.DeathAngelAnim

### isEscaped
```csharp
private bool isEscaped { get; set; }
```

#### Property Value
**Type:** System.Boolean

### Left
```csharp
public MapNode Left { get; set; }
```

#### Property Value
**Type:** Global.MapNode

### Right
```csharp
public MapNode Right { get; set; }
```

#### Property Value
**Type:** Global.MapNode

### sefiraPassage
```csharp
private PassageObject sefiraPassage { get; }
```

#### Property Value
**Type:** Global.PassageObject

### skillInterval
```csharp
private int skillInterval { get; set; }
```

#### Property Value
**Type:** System.Int32

## Methods
### AddDeletedPermanetly(AgentModel)
```csharp
public static void AddDeletedPermanetly(AgentModel agent)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |

### Advent(bool)
```csharp
public void Advent(bool isBet)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `isBet` | `System.Boolean` |  |

### AfterTeleport()
```csharp
public void AfterTeleport()
```

### AgentAnimCalled(int, WorkerModel)
```csharp
public override void AgentAnimCalled(int i, WorkerModel actor)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |
| `actor` | `Global.WorkerModel` |  |

### BlockUI(int)
```csharp
public void BlockUI(int index)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

### DeletePermanetly(AgentModel)
```csharp
public static void DeletePermanetly(AgentModel agent)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `agent` | `Global.AgentModel` |  |

### DoctorAdvent()
```csharp
public void DoctorAdvent()
```

### Escape()
```csharp
public override void Escape()
```


### Extinction(AgentModel)
```csharp
private void Extinction(AgentModel worker)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.AgentModel` |  |

### GetApostle(int)
```csharp
public DeathAngelApostle GetApostle(int index)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

#### Returns
**Type:** Legacy.DeathAngelApostle

### GetApostleData(int)
```csharp
public CreatureStaticData.ParameterData GetApostleData(int targetindex)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `targetindex` | `System.Int32` |  |

#### Returns
**Type:** Global.CreatureStaticData.ParameterData

### GetApostleDataRefined(int)
```csharp
public string GetApostleDataRefined(int index)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

#### Returns
**Type:** System.String

### GetApostleObject(int)
```csharp
public DeathAngel.Apostle GetApostleObject(int index)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

#### Returns
**Type:** Legacy.DeathAngel.Apostle

### GetBlockData(int)
```csharp
public CreatureStaticData.ParameterData GetBlockData(int index)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `index` | `System.Int32` |  |

#### Returns
**Type:** Global.CreatureStaticData.ParameterData

### GetCurrentNode()
```csharp
public MapNode GetCurrentNode()
```

#### Returns
**Type:** Global.MapNode

### GetCurrentPassage()
```csharp
public PassageObjectModel GetCurrentPassage()
```

#### Returns
**Type:** Global.PassageObjectModel

### GetIudas()
```csharp
public DeathAngel.Apostle GetIudas()
```

#### Returns
**Type:** Legacy.DeathAngel.Apostle

### GetRealTargets()
```csharp
public override UnitModel[] GetRealTargets()
```

#### Returns
**Type:** Global.UnitModel[]

### GetSaveData()
```csharp
public override Dictionary<string, object> GetSaveData()
```

#### Returns
**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### GetSpecialSkill()
```csharp
public override SkillTypeInfo GetSpecialSkill()
```

#### Returns
**Type:** Global.SkillTypeInfo

### HasScriptSaveData()
```csharp
public override bool HasScriptSaveData()
```

#### Returns
**Type:** System.Boolean

### HasUniqueFaction()
```csharp
public override bool HasUniqueFaction()
```

#### Returns
**Type:** System.Boolean

### HasUniqueMaxObservationFinish()
```csharp
public override bool HasUniqueMaxObservationFinish()
```

#### Returns
**Type:** System.Boolean

### LoadData(Dictionary<string, object>)
```csharp
public override void LoadData(Dictionary<string, object> dic)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |

### OnAdventEventEnd()
```csharp
public void OnAdventEventEnd()
```

### OnConfess()
```csharp
public void OnConfess()
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

### OnHaltEffect()
```csharp
public void OnHaltEffect()
```

### OnHaltKill()
```csharp
public void OnHaltKill()
```

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

### Recover(AgentModel)
```csharp
private void Recover(AgentModel worker)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.AgentModel` |  |

### ResurrectApostles()
```csharp
public void ResurrectApostles()
```

### RoomSpriteInit()
```csharp
public override void RoomSpriteInit()
```


### SetApostleList(List<DeathAngelApostle>)
```csharp
public void SetApostleList(List<DeathAngelApostle> apostle)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `apostle` | `System.Collections.Generic.List{Legacy.DeathAngelApostle}` |  |

### SetPlagueDoctorScript(PlagueDoctor)
```csharp
public void SetPlagueDoctorScript(PlagueDoctor doc)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `doc` | `Legacy.PlagueDoctor` |  |

### SkillEffect(AgentModel, bool)
```csharp
public void SkillEffect(AgentModel target, bool extinct)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.AgentModel` |  |
| `extinct` | `System.Boolean` |  |

### SkillExecute(AgentModel)
```csharp
public void SkillExecute(AgentModel target)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.AgentModel` |  |

### SpecialWorkProcess(UseSkill)
```csharp
private void SpecialWorkProcess(UseSkill skill)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `skill` | `Global.UseSkill` |  |

### Teleport()
```csharp
private void Teleport()
```

### UniqueEscape()
```csharp
public override void UniqueEscape()
```


### UniqueMaxObservationFinish(Desc)
```csharp
public override bool UniqueMaxObservationFinish(CreatureMaxObserve.Desc desc)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `desc` | `Global.CreatureMaxObserve.Desc` |  |

#### Returns
**Type:** System.Boolean

## Inherited Members
[isolateSpriteSrc](/api/Global/Abnormalities/CreatureBase/CreatureBase#isolatespritesrc), [model](/api/Global/Abnormalities/CreatureBase/CreatureBase#model), [skill](/api/Global/Abnormalities/CreatureBase/CreatureBase#skill), [kitEvent](/api/Global/Abnormalities/CreatureBase/CreatureBase#kitevent), [hasUniqueEscapeLogic](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueescapelogic), [isWorkAllocated](/api/Global/Abnormalities/CreatureBase/CreatureBase#isworkallocated), [_allocatedAgent](/api/Global/Abnormalities/CreatureBase/CreatureBase#allocatedagent), [damage](/api/Global/Abnormalities/CreatureBase/CreatureBase#damage), [OnReleaseSpecialTip](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleasespecialtip), [specialSkillTipParamList](/api/Global/Abnormalities/CreatureBase/CreatureBase#specialskilltipparamlist), [_check](/api/Global/Abnormalities/CreatureBase/CreatureBase#check), [SetModel(CreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#setmodel-creaturemodel), [OnViewInitPrev(CreatureUnit)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onviewinitprev-creatureunit), [OnFixedUpdateInSkill(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfixedupdateinskill-useskill), [OnSkillFailWorkTick(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillfailworktick-useskill), [OnSkillSuccessWorkTick(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillsuccessworktick-useskill), [OnSkillTickUpdate(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskilltickupdate-useskill), [OnSkillGoalComplete(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillgoalcomplete-useskill), [PermitCancelCurrentWork()](/api/Global/Abnormalities/CreatureBase/CreatureBase#permitcancelcurrentwork), [GetKitCreatureProcessTime()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getkitcreatureprocesstime), [OnBonusWorkProb()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onbonusworkprob), [GetDamageMultiplierInWork(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdamagemultiplierinwork-useskill), [TranformWorkProb(float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#tranformworkprob-float), [OnFinishWork(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfinishwork-useskill), [OnWorkCoolTimeEnd(CreatureFeelingState)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkcooltimeend-creaturefeelingstate), [GetDebugText()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdebugtext), [OnTimerEnd()](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontimerend), [MakeEffect(IsolateRoom, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffect-isolateroom-int), [MakeEffectAlter(IsolateRoom, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectalter-isolateroom-int), [Prob(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#prob-int), [isAttackInWorkProcess()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isattackinworkprocess), [OnAttackInWorkProcess(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onattackinworkprocess-useskill), [AttackProcess(UnitModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#attackprocess-unitmodel), [AutoFeelingDown()](/api/Global/Abnormalities/CreatureBase/CreatureBase#autofeelingdown), [MakingEffect(string, float, string, Transform, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float-string-transform-int), [MakingEffect(string, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float), [MakeEffectAttachedToHead(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectattachedtohead-string), [MakingEffect(string, float, string, Vector3, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float-string-vector3-int), [OnAgentWorkEndAnimationPlayed(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentworkendanimationplayed-useskill), [OnAgentAllocateWork(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentallocatework-agentmodel), [OnAllocatedWork(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onallocatedwork-agentmodel), [OnReleaseWorkAllocated()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleaseworkallocated), [ObserveLevelChangeForSpecialSkillTip()](/api/Global/Abnormalities/CreatureBase/CreatureBase#observelevelchangeforspecialskilltip), [OnObserveLevelChanged()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onobservelevelchanged), [HasUniqueProcessWorkNarration()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueprocessworknarration), [UniqueProcessWorkNarration(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniqueprocessworknarration-useskill), [RoomEscapeSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomescapespriteon), [RoomEscapeSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomescapespriteoff), [RoomSkillSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomskillspriteon), [RoomSkillSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomskillspriteoff), [RoomStateSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomstatespriteon), [RoomStateSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomstatespriteoff), [OnForceSpecialSkillTipReveal(string, params object[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onforcespecialskilltipreveal-string-params-object), [OnWorkReleaseSpeicalSkillTipReveal(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkreleasespeicalskilltipreveal-string), [OnWorkReleaseTipUpdate(params object[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkreleasetipupdate-params-object), [OnAgentAnimatorReseted()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentanimatorreseted), [SpecialEnergyTick()](/api/Global/Abnormalities/CreatureBase/CreatureBase#specialenergytick), [OnStageEnd()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onstageend), [OnFeverTimeOver()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfevertimeover), [OnOverlayIsolateWork()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onoverlayisolatework), [OnOverlayIsolateObserve()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onoverlayisolateobserve), [OnOpenObserveWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopenobservewindow), [OnOpenWorkWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopenworkwindow), [OnOpenCollectionWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopencollectionwindow), [DelayAttackMotion(float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#delayattackmotion-float), [IsAttackTargetable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isattacktargetable), [LoadScriptData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#loadscriptdata), [SaveScriptData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#savescriptdata), [ExistSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#existsavedata), [RemoveSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#removesavedata), [ReplaceCommand(CreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#replacecommand-creaturemodel), [OnGamemanagerInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#ongamemanagerinit), [MakeEffectGlobalPos(string, Vector3)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectglobalpos-string-vector3), [MakeEffectGlobalPosNonTrans(string, Vector3)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectglobalposnontrans-string-vector3), [CanObservedByAgent(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#canobservedbyagent-agentmodel), [MakeSound(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string), [MakeSound(string, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string-float), [MakeSound(string, AudioRolloffMode)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string-audiorolloffmode), [MakeSoundQueue(params string[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesoundqueue-params-string), [MakeSoundLoop(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesoundloop-string), [OnViewDestroy()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onviewdestroy), [IsWorkable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isworkable), [OnChildSuppressed(ChildCreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onchildsuppressed-childcreaturemodel), [MakeChildCreature(UnitModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makechildcreature-unitmodel), [OnKillWorker(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onkillworker-workermodel), [GenPursueCommandAlter(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#genpursuecommandalter-workermodel), [OnAfterSuppressed()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onaftersuppressed), [hasUniqueDeadScene()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquedeadscene), [SetHpSlider(Slider)](/api/Global/Abnormalities/CreatureBase/CreatureBase#sethpslider-slider), [SetCastingSlider(Slider)](/api/Global/Abnormalities/CreatureBase/CreatureBase#setcastingslider-slider), [HasUniqueAttackDealy()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueattackdealy), [CanTakeDamage(UnitModel, DamageInfo)](/api/Global/Abnormalities/CreatureBase/CreatureBase#cantakedamage-unitmodel-damageinfo), [OnTakePhysicalDamage(UnitModel, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontakephysicaldamage-unitmodel-float), [OnWorkerPanic(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkerpanic-workermodel), [OnSelectMaxObservation(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onselectmaxobservation-int), [OnLoadCreatureName(ref string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onloadcreaturename-ref-string), [IsSuppressable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#issuppressable), [IsSuppressableByRoom()](/api/Global/Abnormalities/CreatureBase/CreatureBase#issuppressablebyroom), [IsAutoSuppressable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isautosuppressable), [OnWorkWindowSkillClicked(long)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkwindowskillclicked-long), [UseDefaultDamageIgnoreMessage(DamageTextEffect)](/api/Global/Abnormalities/CreatureBase/CreatureBase#usedefaultdamageignoremessage-damagetexteffect), [OnWorkAllocated(SkillTypeInfo, AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkallocated-skilltypeinfo-agentmodel), [GetPhysicalDamage(out float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getphysicaldamage-out-float), [GetMentalDamage(out float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getmentaldamage-out-float), [OnSuperArmorBreak()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onsuperarmorbreak), [UniqueStunEffect()](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquestuneffect), [HasEscapeUI()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasescapeui), [HasRoomCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasroomcounter), [RoomCounterInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomcounterinit), [ResetQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#resetqliphothcounter), [GetMaxWorkCountView()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getmaxworkcountview), [GetQliphothCounterMax()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getqliphothcountermax), [ActivateQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#activateqliphothcounter), [ReducedQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#reducedqliphothcounter), [AddedQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#addedqliphothcounter), [OnTakeDamage(UnitModel, DamageInfo, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontakedamage-unitmodel-damageinfo-float), [GetRadius()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getradius), [OnElevatorStuck()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onelevatorstuck), [OnWorkClosed(UseSkill, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkclosed-useskill-int), [IsActivatedWorkDesc()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isactivatedworkdesc), [IsSensoredInPassage()](/api/Global/Abnormalities/CreatureBase/CreatureBase#issensoredinpassage), [IsIndirectSuppressable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isindirectsuppressable), [GetRiskLevel()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getrisklevel), [GetName()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getname), [UniqueMoveControl()](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquemovecontrol), [HasUniqueName()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquename), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdamagefactor-unitmodel-damageinfo), [OnInitialBuild()](/api/Global/Abnormalities/CreatureBase/CreatureBase#oninitialbuild), [HasUniqueCollectionCost(string, out string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquecollectioncost-string-out-string), [OnOpenCommandWindow(Button[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopencommandwindow-button), [HasUniqueCommandAction(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquecommandaction-int), [HasUniqueWorkSelect(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueworkselect-int), [ForcelySuccess(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#forcelysuccess-useskill), [ForcelyFail(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#forcelyfail-useskill), [TryRabbitTeleport(MapNode)](/api/Global/Abnormalities/CreatureBase/CreatureBase#tryrabbitteleport-mapnode), [CanEnterRoom()](/api/Global/Abnormalities/CreatureBase/CreatureBase#canenterroom), [AllocatedAgent](/api/Global/Abnormalities/CreatureBase/CreatureBase#allocatedagent), [skillTriggerCheck](/api/Global/Abnormalities/CreatureBase/CreatureBase#skilltriggercheck), [Unit](/api/Global/Abnormalities/CreatureBase/CreatureBase#unit), [GetSaveSrc](/api/Global/Abnormalities/CreatureBase/CreatureBase#getsavesrc), [movable](/api/Global/Abnormalities/CreatureBase/CreatureBase#movable), [currentPassage](/api/Global/Abnormalities/CreatureBase/CreatureBase#currentpassage), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)










