---
uid: Global.Helper
canonical_path: /api/Global/Misc/Helper
---
# Class Helper
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class Helper : CreatureBase
```
> This section may have incomplete or incorrect information.
{.is-warning}


All-Around Helper.




## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase](/api/Global/Abnormalities/CreatureBase/CreatureBase) → Helper

## Constructors
### Helper()
```csharp
public Helper()
```

## Fields
### _animScript
```csharp
private HelperAnim _animScript
```
[All-Around Helper's animator](/api/Global/Abnormalities/All-Around-Helper/HelperAnim). If null, sets to the creature unit's animation target.


#### Field Value
**Type:** Global.HelperAnim

### _isRight
```csharp
private bool _isRight
```


#### Field Value
**Type:** System.Boolean

### _spinAttack
```csharp
private bool _spinAttack
```


#### Field Value
**Type:** System.Boolean

### attackCoolTime
```csharp
private Timer attackCoolTime
```
Timer which counts down to the end of Helper's shutdown after attacking.


#### Field Value
**Type:** Global.Timer

### attackCoolTimeVal
```csharp
private const float attackCoolTimeVal = 4
```


#### Field Value
**Type:** System.Single

### attackedUnits
```csharp
private List<UnitModel> attackedUnits
```


#### Field Value
**Type:** System.Collections.Generic.List{UnitModel}

### attackSpace
```csharp
private const float attackSpace = 1.5
```


#### Field Value
**Type:** System.Single

### currentAttackEnd
```csharp
private MapNode currentAttackEnd
```
Location of the node to end up at during the spin attack.


#### Field Value
**Type:** Global.MapNode

### currentMoveTarget
```csharp
private MapNode currentMoveTarget
```
Current movement target. Assigned, but not really used.


#### Field Value
**Type:** Global.MapNode

### dmgMax
```csharp
private const int dmgMax = 30
```


#### Field Value
**Type:** System.Int32

### dmgMin
```csharp
private const int dmgMin = 20
```


#### Field Value
**Type:** System.Int32

### dmgType
```csharp
private RwbpType dmgType
```
The damage type Helper deals.


#### Field Value
**Type:** Global.RwbpType

### formerMovementTarget
```csharp
private int formerMovementTarget
```
Stores the index of the last targeted room in the current department.


#### Field Value
**Type:** System.Int32

### initialSpeed
```csharp
private float initialSpeed
```
Stores Helper's current speed.


#### Field Value
**Type:** System.Single

### interrupt
```csharp
private bool interrupt
```
Stores whether Helper is 'interrupted', which happens when the spin attack ends until woken up. ^\[verify\]^

#### Field Value
**Type:** System.Boolean

### isAttacking
```csharp
private bool isAttacking
```
Stores whether Helper is doing a spin attack.


#### Field Value
**Type:** System.Boolean

### prepareAttack
```csharp
private bool prepareAttack
```
Stores whether Helper is charging up its attack. ^\[verify\]^

#### Field Value
**Type:** System.Boolean

### speedMult
```csharp
private const float speedMult = 6
```


#### Field Value
**Type:** System.Single

### spinMaxSound
```csharp
private SoundEffectPlayer spinMaxSound
```
Plays the sound effect for ending the spin attack or being suppressed. ^\[verify\]^

#### Field Value
**Type:** Global.SoundEffectPlayer

### spinMaxTime
```csharp
private const float spinMaxTime = 3
```


#### Field Value
**Type:** System.Single

### spinSound
```csharp
private SoundEffectPlayer spinSound
```
Plays the sound during the spin attack.


#### Field Value
**Type:** Global.SoundEffectPlayer

### spinTimer
```csharp
private Timer spinTimer
```
Timer which counts down to the end of Helper's charging-up at the start of its attack.


#### Field Value
**Type:** Global.Timer

### throwItemSrc
```csharp
private const string throwItemSrc = "Effect/ThrowedItem"
```




#### Field Value
**Type:** System.String

### waking
```csharp
private bool waking
```
Stores whether Helper is waking up from shutdown.


#### Field Value
**Type:** System.Boolean

## Properties
### animScript
```csharp
public HelperAnim animScript { get; }
```

#### Property Value
**Type:** Global.HelperAnim

### currentSefira
```csharp
private Sefira currentSefira { get; set; }
```

#### Property Value
**Type:** Global.Sefira

### GetDmg
```csharp
private static int GetDmg { get; }
```

#### Property Value
**Type:** System.Int32

### isRight
```csharp
private bool isRight { get; set; }
```

#### Property Value
**Type:** System.Boolean

### spinAttack
```csharp
private bool spinAttack { get; set; }
```

#### Property Value
**Type:** System.Boolean

## Methods
### ActivateQliphothCounter()
```csharp
public override void ActivateQliphothCounter()
```
Calls base and breaches.


### AfterDown()
```csharp
public void AfterDown()
```
Stops being interrupted and starts a 4 second cooldown before the next attack.


### CheckPassageTarget()
```csharp
private bool CheckPassageTarget()
```
Returns true if there is another movable thing in the same room, and false otherwise.


#### Returns
**Type:** System.Boolean

### CheckTargetExist()
```csharp
private bool CheckTargetExist()
```
Return true if there are valid attack targets, and false otherwise.


#### Returns
**Type:** System.Boolean

### EndAttack()
```csharp
private void EndAttack()
```
Stops playing attack sounds, resets speed, plays a shutdown sound effect, and runs the shutdown animation. Sets flags for interrupted and recharging.


### Escape()
```csharp
public override void Escape()
```
Plays an escape animation, breaches the abnormality, and sets its current direction to right.


### GetTargetList(MovableObjectNode[])
```csharp
public MovableObjectNode[] GetTargetList(MovableObjectNode[] passageTarget)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `passageTarget` | `Global.MovableObjectNode[]` |  |

#### Returns
**Type:** Global.MovableObjectNode[]

### MakeExplodeEffect(UnitDirection, WorkerModel, float)
```csharp
public void MakeExplodeEffect(UnitDirection dir, WorkerModel target, float size)
```
Makes a gut explosion effect on a killed worker, and makes the worker vanish.


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `dir` | `Global.UnitDirection` |  |
| `target` | `Global.WorkerModel` |  |
| `size` | `System.Single` |  |

### MakeMovement()
```csharp
private void MakeMovement()
```
Moves All-Around Helper while breaching.
###### more details
If there are no living workers in the current department, chooses a random department to target; otherwise, uses the current department.

Then, makes 5 attempts to choose a room different than the previous movement target; on failure, chooses the main rooms in the department instead. Then, chooses a random node within the selected room(s) and begins moving to it.

Note: I'm pretty sure this has a bug which prevents the last room in the list from ever being chosen. 

### MakeSparkSound()
```csharp
public void MakeSparkSound()
```
Plays a spark sound.


### OnReturn()
```csharp
public override void OnReturn()
```
Calls base and resets the Qliphoth counter.


### OnStageRelease()
```csharp
public override void OnStageRelease()
```
Calls ParamInit to reset variables.


### OnStageStart()
```csharp
public override void OnStageStart()
```
Sets the animation script (to this), resets Helper's speed, and calls ParamInit to reset variables.


### OnSuppressed()
```csharp
public override void OnSuppressed()
```
When suppressed, immediately ends attack, stops any sound playing, calls ParamInit to reset variables, and removes the current behaviour.


### OnWakeUpEnded()
```csharp
public void OnWakeUpEnded()
```
Sets flags to indicate it is no longer recharging or attacking.


### OnWorkCoolTimeEnd(CreatureFeelingState)
```csharp
public override void OnWorkCoolTimeEnd(CreatureFeelingState oldState)
```
When the work cooldown ends, randomly decreases the Qliphoth counter based on work result. Reduces by 1 at a 70% chance for bad results, and 50% for normal results.

If the Qliphoth counter is above 0, also sets the form back to normal if needed.


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `oldState` | `Global.CreatureFeelingState` |  |

### ParamInit()
```csharp
public override void ParamInit()
```
Resetter for attacks, animations, and sound variables.


### PrevEscape()
```csharp
private void PrevEscape()
```
Changes the form of the abnormality to its breaching form when breaching.


### SetAttackNode(MovableObjectNode)
```csharp
private void SetAttackNode(MovableObjectNode target)
```
Finds the left-most and right-most points in the room, then sets the target node to the direction of the provided attack target. (i.e., if the target is left, spin left, and vice versa.) If at the right-most point, always attacks left.


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.MovableObjectNode` |  |

### SetCastingSlider(Slider)
```csharp
public override bool SetCastingSlider(Slider castingSlider)
```
Updates a slider during the spin attack, called when that slider exists... which I don't think it ever does. ^\[verify\]^

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `castingSlider` | `UnityEngine.UI.Slider` |  |

#### Returns
**Type:** System.Boolean

### SetSpinMultiplier(float)
```csharp
private void SetSpinMultiplier(float elapsed)
```
Sets the spinning animation speed to 0.3 times the time elapsed, for charging up the spin attack.


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `elapsed` | `System.Single` |  |

### Shoot()
```csharp
private void Shoot()
```
Plays a sound and moves at 6x speed to one side of the room, for when the spin attack is done charging up.


### SpinAttack()
```csharp
private void SpinAttack()
```
All-Around Helper's spinning attack.

For each living unit in the same room within 1.5 units of Helper which hasn't already been hit, deals damage. The first time something takes damage, also plays a hit sound.


### StartAttack()
```csharp
private void StartAttack()
```
Sets some flags to start attacking, and tells the animator to do the warm-up for the spin attack.


### StopMovement()
```csharp
private void StopMovement()
```
Clears the current command, tells the movable node to stop moving, and tells the animator Helper has stopped moving.


### TakeSpinDamage(UnitModel)
```csharp
private void TakeSpinDamage(UnitModel unit)
```
Deals damage to a unit for the spin attack and marks them as already hit.
###### more details
Skips dead units (redundantly), as well as invincible workers. Living workers take damage and display a damage particle effect, and explode if killed. If the target is a [creature](/api/Global/Abnormalities/CreatureModel), and isn't suppressed or returning, takes damage and displays a damage particle effect.


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.UnitModel` |  |

### TransformState(int)
```csharp
private void TransformState(int val)
```
Changes form.


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `val` | `System.Int32` |  |

### UniqueEscape()
```csharp
public override void UniqueEscape()
```
Handles attacking and moving during breach.
###### more details
Does nothing during the transformation or during elevator transitions. If the spin attack is active, calls SpinAttack; otherwise, skips if interrupted.

If not attacking, chooses a random target in the room and attacks them. If there are no targets, Helper isn't doing anything, and Helper is not recharging, then starts moving.

When attacking, if an attack hasn't started, prepares to attack and plays a sound.

Then, either waits while on cool-down, spins around, or if not doing anything else, ends the current attack. Also, checks for agents to give encounter damage.[^1]

[^1]: Shouldn't this be an event, though? When an agent enters a room, check if they need to take fear damage? Why check this every frame?


## Inherited Members
[isolateSpriteSrc](/api/Global/Abnormalities/CreatureBase/CreatureBase#isolatespritesrc), [model](/api/Global/Abnormalities/CreatureBase/CreatureBase#model), [skill](/api/Global/Abnormalities/CreatureBase/CreatureBase#skill), [kitEvent](/api/Global/Abnormalities/CreatureBase/CreatureBase#kitevent), [hasUniqueEscapeLogic](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueescapelogic), [isWorkAllocated](/api/Global/Abnormalities/CreatureBase/CreatureBase#isworkallocated), [_allocatedAgent](/api/Global/Abnormalities/CreatureBase/CreatureBase#allocatedagent), [damage](/api/Global/Abnormalities/CreatureBase/CreatureBase#damage), [OnReleaseSpecialTip](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleasespecialtip), [specialSkillTipParamList](/api/Global/Abnormalities/CreatureBase/CreatureBase#specialskilltipparamlist), [_check](/api/Global/Abnormalities/CreatureBase/CreatureBase#check), [SetModel(CreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#setmodel-creaturemodel), [OnInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#oninit), [OnViewInitPrev(CreatureUnit)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onviewinitprev-creatureunit), [OnViewInit(CreatureUnit)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onviewinit-creatureunit), [OnFixedUpdate(CreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfixedupdate-creaturemodel), [OnFixedUpdateInSkill(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfixedupdateinskill-useskill), [OnSkillFailWorkTick(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillfailworktick-useskill), [OnSkillSuccessWorkTick(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillsuccessworktick-useskill), [OnSkillTickUpdate(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskilltickupdate-useskill), [OnSkillGoalComplete(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillgoalcomplete-useskill), [PermitCancelCurrentWork()](/api/Global/Abnormalities/CreatureBase/CreatureBase#permitcancelcurrentwork), [GetKitCreatureProcessTime()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getkitcreatureprocesstime), [OnBonusWorkProb()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onbonusworkprob), [GetDamageMultiplierInWork(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdamagemultiplierinwork-useskill), [TranformWorkProb(float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#tranformworkprob-float), [OnEnterRoom(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onenterroom-useskill), [OnReleaseWork(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleasework-useskill), [OnFinishWork(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfinishwork-useskill), [GetSpecialSkill()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getspecialskill), [GetDebugText()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdebugtext), [OnTimerEnd()](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontimerend), [MakeEffect(IsolateRoom, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffect-isolateroom-int), [MakeEffectAlter(IsolateRoom, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectalter-isolateroom-int), [Prob(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#prob-int), [isAttackInWorkProcess()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isattackinworkprocess), [OnAttackInWorkProcess(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onattackinworkprocess-useskill), [AttackProcess(UnitModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#attackprocess-unitmodel), [AutoFeelingDown()](/api/Global/Abnormalities/CreatureBase/CreatureBase#autofeelingdown), [AgentAnimCalled(int, WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#agentanimcalled-int-workermodel), [MakingEffect(string, float, string, Transform, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float-string-transform-int), [MakingEffect(string, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float), [MakeEffectAttachedToHead(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectattachedtohead-string), [MakingEffect(string, float, string, Vector3, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float-string-vector3-int), [OnAgentWorkEndAnimationPlayed(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentworkendanimationplayed-useskill), [OnAgentAllocateWork(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentallocatework-agentmodel), [OnAllocatedWork(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onallocatedwork-agentmodel), [OnReleaseWorkAllocated()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleaseworkallocated), [ObserveLevelChangeForSpecialSkillTip()](/api/Global/Abnormalities/CreatureBase/CreatureBase#observelevelchangeforspecialskilltip), [OnObserveLevelChanged()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onobservelevelchanged), [HasUniqueProcessWorkNarration()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueprocessworknarration), [UniqueProcessWorkNarration(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniqueprocessworknarration-useskill), [RoomSpriteInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomspriteinit), [RoomEscapeSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomescapespriteon), [RoomEscapeSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomescapespriteoff), [RoomSkillSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomskillspriteon), [RoomSkillSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomskillspriteoff), [RoomStateSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomstatespriteon), [RoomStateSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomstatespriteoff), [OnForceSpecialSkillTipReveal(string, params object[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onforcespecialskilltipreveal-string-params-object), [OnWorkReleaseSpeicalSkillTipReveal(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkreleasespeicalskilltipreveal-string), [OnWorkReleaseTipUpdate(params object[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkreleasetipupdate-params-object), [OnAgentAnimatorReseted()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentanimatorreseted), [SpecialEnergyTick()](/api/Global/Abnormalities/CreatureBase/CreatureBase#specialenergytick), [OnStageEnd()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onstageend), [OnFeverTimeOver()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfevertimeover), [OnOverlayIsolateWork()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onoverlayisolatework), [OnOverlayIsolateObserve()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onoverlayisolateobserve), [OnOpenObserveWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopenobservewindow), [OnOpenWorkWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopenworkwindow), [OnOpenCollectionWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopencollectionwindow), [DelayAttackMotion(float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#delayattackmotion-float), [IsAttackTargetable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isattacktargetable), [GetRealTargets()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getrealtargets), [HasScriptSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasscriptsavedata), [GetSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getsavedata), [LoadData(Dictionary<string, object>)](/api/Global/Abnormalities/CreatureBase/CreatureBase#loaddata-dictionary-string-object), [LoadScriptData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#loadscriptdata), [SaveScriptData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#savescriptdata), [ExistSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#existsavedata), [RemoveSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#removesavedata), [ReplaceCommand(CreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#replacecommand-creaturemodel), [OnGamemanagerInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#ongamemanagerinit), [MakeEffectGlobalPos(string, Vector3)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectglobalpos-string-vector3), [MakeEffectGlobalPosNonTrans(string, Vector3)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectglobalposnontrans-string-vector3), [CanObservedByAgent(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#canobservedbyagent-agentmodel), [MakeSound(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string), [MakeSound(string, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string-float), [MakeSound(string, AudioRolloffMode)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string-audiorolloffmode), [MakeSoundQueue(params string[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesoundqueue-params-string), [MakeSoundLoop(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesoundloop-string), [OnViewDestroy()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onviewdestroy), [IsWorkable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isworkable), [HasUniqueMaxObservationFinish()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquemaxobservationfinish), [UniqueMaxObservationFinish(Desc)](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquemaxobservationfinish-desc), [OnChildSuppressed(ChildCreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onchildsuppressed-childcreaturemodel), [MakeChildCreature(UnitModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makechildcreature-unitmodel), [OnKillWorker(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onkillworker-workermodel), [GenPursueCommandAlter(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#genpursuecommandalter-workermodel), [OnAfterSuppressed()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onaftersuppressed), [hasUniqueDeadScene()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquedeadscene), [SetHpSlider(Slider)](/api/Global/Abnormalities/CreatureBase/CreatureBase#sethpslider-slider), [HasUniqueAttackDealy()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueattackdealy), [CanTakeDamage(UnitModel, DamageInfo)](/api/Global/Abnormalities/CreatureBase/CreatureBase#cantakedamage-unitmodel-damageinfo), [OnTakePhysicalDamage(UnitModel, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontakephysicaldamage-unitmodel-float), [HasUniqueFaction()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquefaction), [OnWorkerPanic(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkerpanic-workermodel), [OnSelectMaxObservation(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onselectmaxobservation-int), [OnLoadCreatureName(ref string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onloadcreaturename-ref-string), [IsSuppressable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#issuppressable), [IsSuppressableByRoom()](/api/Global/Abnormalities/CreatureBase/CreatureBase#issuppressablebyroom), [IsAutoSuppressable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isautosuppressable), [OnWorkWindowSkillClicked(long)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkwindowskillclicked-long), [UseDefaultDamageIgnoreMessage(DamageTextEffect)](/api/Global/Abnormalities/CreatureBase/CreatureBase#usedefaultdamageignoremessage-damagetexteffect), [OnWorkAllocated(SkillTypeInfo, AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkallocated-skilltypeinfo-agentmodel), [GetPhysicalDamage(out float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getphysicaldamage-out-float), [GetMentalDamage(out float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getmentaldamage-out-float), [OnSuperArmorBreak()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onsuperarmorbreak), [UniqueStunEffect()](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquestuneffect), [HasEscapeUI()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasescapeui), [HasRoomCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasroomcounter), [RoomCounterInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomcounterinit), [ResetQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#resetqliphothcounter), [GetMaxWorkCountView()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getmaxworkcountview), [GetQliphothCounterMax()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getqliphothcountermax), [ReducedQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#reducedqliphothcounter), [AddedQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#addedqliphothcounter), [OnTakeDamage(UnitModel, DamageInfo, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontakedamage-unitmodel-damageinfo-float), [GetRadius()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getradius), [OnElevatorStuck()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onelevatorstuck), [OnWorkClosed(UseSkill, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkclosed-useskill-int), [IsActivatedWorkDesc()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isactivatedworkdesc), [IsSensoredInPassage()](/api/Global/Abnormalities/CreatureBase/CreatureBase#issensoredinpassage), [IsIndirectSuppressable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isindirectsuppressable), [GetRiskLevel()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getrisklevel), [GetName()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getname), [UniqueMoveControl()](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquemovecontrol), [HasUniqueName()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquename), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdamagefactor-unitmodel-damageinfo), [OnInitialBuild()](/api/Global/Abnormalities/CreatureBase/CreatureBase#oninitialbuild), [HasUniqueCollectionCost(string, out string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquecollectioncost-string-out-string), [OnOpenCommandWindow(Button[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopencommandwindow-button), [HasUniqueCommandAction(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquecommandaction-int), [HasUniqueWorkSelect(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueworkselect-int), [ForcelySuccess(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#forcelysuccess-useskill), [ForcelyFail(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#forcelyfail-useskill), [TryRabbitTeleport(MapNode)](/api/Global/Abnormalities/CreatureBase/CreatureBase#tryrabbitteleport-mapnode), [CanEnterRoom()](/api/Global/Abnormalities/CreatureBase/CreatureBase#canenterroom), [AllocatedAgent](/api/Global/Abnormalities/CreatureBase/CreatureBase#allocatedagent), [skillTriggerCheck](/api/Global/Abnormalities/CreatureBase/CreatureBase#skilltriggercheck), [Unit](/api/Global/Abnormalities/CreatureBase/CreatureBase#unit), [GetSaveSrc](/api/Global/Abnormalities/CreatureBase/CreatureBase#getsavesrc), [movable](/api/Global/Abnormalities/CreatureBase/CreatureBase#movable), [currentPassage](/api/Global/Abnormalities/CreatureBase/CreatureBase#currentpassage), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)








