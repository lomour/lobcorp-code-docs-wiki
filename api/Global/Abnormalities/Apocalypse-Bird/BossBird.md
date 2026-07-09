---
uid: Global.BossBird
canonical_path: /api/Global/Misc/BossBird
---
# Class BossBird
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BossBird : BirdCreatureBase
```
> This section may have incomplete or incorrect information.
{.is-warning}


Apocalypse Bird. 




## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [CreatureBase](/api/Global/Abnormalities/Apocalypse-Bird/BirdCreatureBase) → BossBird

## Constructors
### BossBird()
```csharp
public BossBird()
```

## Fields
### _attackDmgMax
```csharp
private const int _attackDmgMax = 43
```


#### Field Value
**Type:** System.Int32

### _attackDmgMin
```csharp
private const int _attackDmgMin = 23
```


#### Field Value
**Type:** System.Int32

### _attractMax
```csharp
private const int _attractMax = 5
```


#### Field Value
**Type:** System.Int32

### _attractMin
```csharp
private const int _attractMin = 3
```


#### Field Value
**Type:** System.Int32

### _biteDmgMax
```csharp
private const int _biteDmgMax = 115
```


#### Field Value
**Type:** System.Int32

### _biteDmgMin
```csharp
private const int _biteDmgMin = 50
```


#### Field Value
**Type:** System.Int32

### _boss_armor_id
```csharp
private const int _boss_armor_id = 300038
```


#### Field Value
**Type:** System.Int32

### _boss_gift_id
```csharp
public const int _boss_gift_id = 400038
```


#### Field Value
**Type:** System.Int32

### _boss_weapon_id
```csharp
private const int _boss_weapon_id = 200038
```


#### Field Value
**Type:** System.Int32

### _currentPhase
```csharp
private BossBird.Phase _currentPhase
```

#### Field Value
**Type:** Global.BossBird.Phase

### _laserDmgMax
```csharp
private const int _laserDmgMax = 14
```


#### Field Value
**Type:** System.Int32

### _laserDmgMin
```csharp
private const int _laserDmgMin = 8
```


#### Field Value
**Type:** System.Int32

### _scaleDmgMax
```csharp
private const int _scaleDmgMax = 15
```


#### Field Value
**Type:** System.Int32

### _scaleDmgMin
```csharp
private const int _scaleDmgMin = 10
```


#### Field Value
**Type:** System.Int32

### _unit
```csharp
private ChildCreatureUnit _unit
```


#### Field Value
**Type:** Global.ChildCreatureUnit

### activateState
```csharp
private bool activateState
```


#### Field Value
**Type:** System.Boolean

### aliveEggs
```csharp
private List<BossEggBase> aliveEggs
```


#### Field Value
**Type:** System.Collections.Generic.List{BossEggBase}

### attackDelayMax
```csharp
private const float attackDelayMax = 6
```


#### Field Value
**Type:** System.Single

### attackDelayMin
```csharp
private const float attackDelayMin = 4
```


#### Field Value
**Type:** System.Single

### attackType
```csharp
private RwbpType attackType
```


#### Field Value
**Type:** Global.RwbpType

### attracted
```csharp
private List<WorkerModel> attracted
```


#### Field Value
**Type:** System.Collections.Generic.List{WorkerModel}

### attractEffect
```csharp
public const string attractEffect = "Effect/Creature/BossBird/Particle/BossBirdAttractEffect"
```


#### Field Value
**Type:** System.String

### attractPatternProb
```csharp
private const int attractPatternProb = 30
```


#### Field Value
**Type:** System.Int32

### bigBird
```csharp
private BigBird bigBird
```


#### Field Value
**Type:** Global.BigBird

### bigEgg
```csharp
private BossEggBase bigEgg
```


#### Field Value
**Type:** Global.BossEggBase

### birdControl
```csharp
private List<IBirdControl> birdControl
```


#### Field Value
**Type:** System.Collections.Generic.List{IBirdControl}

### bitePatternProb
```csharp
private const int bitePatternProb = 10
```


#### Field Value
**Type:** System.Int32

### biteType
```csharp
private RwbpType biteType
```


#### Field Value
**Type:** Global.RwbpType

### currentAttackType
```csharp
private BossBird.AttackType currentAttackType
```

#### Field Value
**Type:** Global.BossBird.AttackType

### currentForcelyTeleportTarget
```csharp
private BossEggBase currentForcelyTeleportTarget
```


#### Field Value
**Type:** Global.BossEggBase

### currentTeleportDest
```csharp
private MapNode currentTeleportDest
```


#### Field Value
**Type:** Global.MapNode

### defaultAmbience
```csharp
private SoundEffectPlayer defaultAmbience
```


#### Field Value
**Type:** Global.SoundEffectPlayer

### escapedCreatures
```csharp
private List<CreatureBase> escapedCreatures
```


#### Field Value
**Type:** System.Collections.Generic.List{CreatureBase}

### eventScript
```csharp
private BossBirdEvent eventScript
```


#### Field Value
**Type:** Global.BossBirdEvent

### forcelyTeleport
```csharp
private bool forcelyTeleport
```


#### Field Value
**Type:** System.Boolean

### forcelyTeleportDelayMin
```csharp
private const float forcelyTeleportDelayMin = 10
```


#### Field Value
**Type:** System.Single

### forcelyTeleportReady
```csharp
private bool forcelyTeleportReady
```


#### Field Value
**Type:** System.Boolean

### forcelyTeleportTimer
```csharp
private Timer forcelyTeleportTimer
```


#### Field Value
**Type:** Global.Timer

### forcelyTteleportDelayMax
```csharp
private const float forcelyTteleportDelayMax = 15
```


#### Field Value
**Type:** System.Single

### gateWay
```csharp
private BossGateWay gateWay
```


#### Field Value
**Type:** Global.BossGateWay

### gatewayNode
```csharp
private MapNode gatewayNode
```


#### Field Value
**Type:** Global.MapNode

### isEscaped
```csharp
private bool isEscaped
```


#### Field Value
**Type:** System.Boolean

### isNarration
```csharp
private bool isNarration
```


#### Field Value
**Type:** System.Boolean

### isTeleporting
```csharp
private bool isTeleporting
```


#### Field Value
**Type:** System.Boolean

### laserArriveSoundPlayed
```csharp
private bool laserArriveSoundPlayed
```


#### Field Value
**Type:** System.Boolean

### LaserCount
```csharp
public const int LaserCount = 26
```


#### Field Value
**Type:** System.Int32

### laserExplode
```csharp
public const string laserExplode = "Effect/Creature/BossBird/Particle/ExplodeEffect"
```


#### Field Value
**Type:** System.String

### laserPatternProb
```csharp
private const int laserPatternProb = 35
```


#### Field Value
**Type:** System.Int32

### laserType
```csharp
private RwbpType laserType
```


#### Field Value
**Type:** Global.RwbpType

### laserUnitExplodeRad
```csharp
private const float laserUnitExplodeRad = 2
```


#### Field Value
**Type:** System.Single

### longBird
```csharp
private LongBird longBird
```


#### Field Value
**Type:** Global.LongBird

### longEgg
```csharp
private BossEggBase longEgg
```


#### Field Value
**Type:** Global.BossEggBase

### meleeHit_1_EffectSrc
```csharp
public const string meleeHit_1_EffectSrc = "Effect/Creature/BossBird/Particle/BossBirdMeleeHit"
```


#### Field Value
**Type:** System.String

### meleeHit_2_Claw_LeftEffectSrc
```csharp
public const string meleeHit_2_Claw_LeftEffectSrc = "Effect/Creature/BossBird/Particle/SlashEffectLeft"
```


#### Field Value
**Type:** System.String

### meleeHit_2_Claw_RightEffectSrc
```csharp
public const string meleeHit_2_Claw_RightEffectSrc = "Effect/Creature/BossBird/Particle/SlashEffectRight"
```


#### Field Value
**Type:** System.String

### meleeHit_2_Grep_LeftEffectSrc
```csharp
public const string meleeHit_2_Grep_LeftEffectSrc = "Effect/Creature/BossBird/Particle/GrepEffectLeft"
```


#### Field Value
**Type:** System.String

### meleeHit_2_Grep_RightEffectSrc
```csharp
public const string meleeHit_2_Grep_RightEffectSrc = "Effect/Creature/BossBird/Particle/GrepEffectRight"
```


#### Field Value
**Type:** System.String

### normalAttackReady
```csharp
private bool normalAttackReady
```


#### Field Value
**Type:** System.Boolean

### normalAttackTimer
```csharp
private Timer normalAttackTimer
```


#### Field Value
**Type:** Global.Timer

### notArrived
```csharp
private List<IBirdControl> notArrived
```


#### Field Value
**Type:** System.Collections.Generic.List{IBirdControl}

### patternDelay
```csharp
private const float patternDelay = 15
```


#### Field Value
**Type:** System.Single

### patternReady
```csharp
private bool patternReady
```


#### Field Value
**Type:** System.Boolean

### scaleEffect
```csharp
public const string scaleEffect = "Effect/Creature/BossBird/Particle/ScaleEffect"
```


#### Field Value
**Type:** System.String

### scalePatternProb
```csharp
private const int scalePatternProb = 25
```


#### Field Value
**Type:** System.Int32

### scaleType
```csharp
private RwbpType scaleType
```


#### Field Value
**Type:** Global.RwbpType

### smallBird
```csharp
private SmallBird smallBird
```


#### Field Value
**Type:** Global.SmallBird

### smallEgg
```csharp
private BossEggBase smallEgg
```


#### Field Value
**Type:** Global.BossEggBase

### specialPatternTimer
```csharp
private Timer specialPatternTimer
```


#### Field Value
**Type:** Global.Timer

### teleportDelayMax
```csharp
private const float teleportDelayMax = 25
```


#### Field Value
**Type:** System.Single

### teleportDelayMin
```csharp
private const float teleportDelayMin = 15
```


#### Field Value
**Type:** System.Single

### teleportReady
```csharp
private bool teleportReady
```


#### Field Value
**Type:** System.Boolean

### teleportTimer
```csharp
private Timer teleportTimer
```


#### Field Value
**Type:** Global.Timer

### traitId
```csharp
private const long traitId = 100038
```


#### Field Value
**Type:** System.Int64

### ultDeadEffecSrc
```csharp
public const string ultDeadEffecSrc = "Effect/Creature/BossBird/Particle/BossBirdAgentDead"
```


#### Field Value
**Type:** System.String

### ultHandLeftSrc
```csharp
public const string ultHandLeftSrc = "Effect/Creature/BossBird/Particle/UltShock_Left"
```


#### Field Value
**Type:** System.String

### ultHandRightSrc
```csharp
public const string ultHandRightSrc = "Effect/Creature/BossBird/Particle/UltShcok_Right"
```


#### Field Value
**Type:** System.String

### ultShooted
```csharp
private bool ultShooted
```


#### Field Value
**Type:** System.Boolean

### ultShootEffectLeftSrc
```csharp
public const string ultShootEffectLeftSrc = "Effect/Creature/BossBird/Particle/GutShootEffectLeft"
```


#### Field Value
**Type:** System.String

### ultShootEffectRightSrc
```csharp
public const string ultShootEffectRightSrc = "Effect/Creature/BossBird/Particle/GutShootEffectRight"
```


#### Field Value
**Type:** System.String

### uniquePattern
```csharp
private Timer uniquePattern
```


#### Field Value
**Type:** Global.Timer

### uniquePatternCheckTime
```csharp
private const float uniquePatternCheckTime = 5
```


#### Field Value
**Type:** System.Single

### waitQueue
```csharp
private Queue<IBirdControl> waitQueue
```


#### Field Value
**Type:** System.Collections.Generic.Queue{IBirdControl}

## Properties
### animScript
```csharp
private BossBirdAnim animScript { get; }
```

#### Property Value
**Type:** Global.BossBirdAnim

### attackDelay
```csharp
private float attackDelay { get; }
```

#### Property Value
**Type:** System.Single

### attackDmg
```csharp
private static int attackDmg { get; }
```

#### Property Value
**Type:** System.Int32

### attractCnt
```csharp
private static int attractCnt { get; }
```

#### Property Value
**Type:** System.Int32

### BigEggModel
```csharp
public EventCreatureModel BigEggModel { get; }
```

#### Property Value
**Type:** Global.EventCreatureModel

### biteDmg
```csharp
private static int biteDmg { get; }
```

#### Property Value
**Type:** System.Int32

### currentPhase
```csharp
public BossBird.Phase currentPhase { get; set; }
```

#### Property Value
**Type:** Global.BossBird.Phase

### forcelyTeleportDelay
```csharp
private float forcelyTeleportDelay { get; }
```

#### Property Value
**Type:** System.Single

### GateWayModel
```csharp
public EventCreatureModel GateWayModel { get; }
```

#### Property Value
**Type:** Global.EventCreatureModel

### laserDmg
```csharp
private static int laserDmg { get; }
```

#### Property Value
**Type:** System.Int32

### LongEggModel
```csharp
public EventCreatureModel LongEggModel { get; }
```

#### Property Value
**Type:** Global.EventCreatureModel

### Model
```csharp
private ChildCreatureModel Model { get; }
```

#### Property Value
**Type:** Global.ChildCreatureModel

### scaleDmg
```csharp
private static int scaleDmg { get; }
```

#### Property Value
**Type:** System.Int32

### SmallEggModel
```csharp
public EventCreatureModel SmallEggModel { get; }
```

#### Property Value
**Type:** Global.EventCreatureModel

### teleportDelay
```csharp
private float teleportDelay { get; }
```

#### Property Value
**Type:** System.Single

## Methods
### AddAgentsTrait()
```csharp
private void AddAgentsTrait()
```
Gives all living and controllable agents the Twilight EGO Gift asynchronously ^\[verify\]^, then tries to make the new Twilight EGO Weapon and Suit. 

### AfterAppearNarration()
```csharp
private void AfterAppearNarration()
```
Spawns Apocalypse Bird at Entrance's last location with EscapeInit.


### AfterEggBreakNarration()
```csharp
private void AfterEggBreakNarration()
```


### AttractCastingSuccess()
```csharp
private void AttractCastingSuccess()
```


### AttractPattern()
```csharp
public void AttractPattern()
```


### BiteCastingSuccess()
```csharp
private void BiteCastingSuccess()
```


### BitePattern()
```csharp
public void BitePattern()
```


### CancelNormalAttack()
```csharp
public void CancelNormalAttack()
```
Stops its normal attack and teleports.


### CancelPatternAttack()
```csharp
public void CancelPatternAttack()
```
Stops its special attack and teleports.


### CheckCreatureUnitState()
```csharp
private void CheckCreatureUnitState()
```
Checks to make sure the game object is active (or inactive) to match Apocalypse Bird's active state.


### CheckTwilight()
```csharp
private bool CheckTwilight()
```
Returns false if there is an agent wielding the Twilight EGO Weapon or Suit, and true otherwise. 

#### Returns
**Type:** System.Boolean

### DeleteSound(SoundEffectPlayer)
```csharp
public void DeleteSound(SoundEffectPlayer sound)
```
Stops playing the sound and destroys it.


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `sound` | `Global.SoundEffectPlayer` |  |

### EndNormalAttack()
```csharp
public void EndNormalAttack()
```
Ends the normal attack and starts a cooldown.


### EndPatternAttack()
```csharp
public void EndPatternAttack()
```
Ends the special attack and starts a 15 second cooldown.


### EndTeleport()
```csharp
public void EndTeleport()
```
Resets teleporting flag and phase.


### EndUltShoot()
```csharp
public void EndUltShoot()
```


### EscapeInit()
```csharp
private void EscapeInit()
```
Spawns Apocalypse Bird and its eggs once all birds have arrived at the [Entrance to the Black Forest](/api/Global/Abnormalities/Apocalypse-Bird/Entrance-to-the-Black-Forest/BossGateWay).


### FadeOutSound()
```csharp
public void FadeOutSound()
```
Plays a sound called 'appear' which ends in 4.5 seconds ^\[verify\]^.


### GetAttackTarget()
```csharp
public List<UnitModel> GetAttackTarget()
```


#### Returns
**Type:** System.Collections.Generic.List{UnitModel}

### GetAttackType()
```csharp
private BossBird.AttackType GetAttackType()
```

#### Returns
**Type:** Global.BossBird.AttackType

### GetCurrentAttackType()
```csharp
public BossBird.AttackType GetCurrentAttackType()
```

#### Returns
**Type:** Global.BossBird.AttackType

### GetDirectionTarget()
```csharp
public List<UnitModel> GetDirectionTarget()
```


#### Returns
**Type:** System.Collections.Generic.List{UnitModel}

### GetDirectionTarget(List<UnitModel>, float, float)
```csharp
public List<UnitModel> GetDirectionTarget(List<UnitModel> targets, float max_dist, float min_dist)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `targets` | `System.Collections.Generic.List{UnitModel}` |  |
| `max_dist` | `System.Single` |  |
| `min_dist` | `System.Single` |  |

#### Returns
**Type:** System.Collections.Generic.List{UnitModel}

### GetName()
```csharp
public override string GetName()
```
Returns Apocalypse Bird's name. (Overrides because technically Apocalypse Bird is a ChildCreatureModel with no parent... ^\[verify\]^)


#### Returns
**Type:** System.String

### GetNarrationKeyByEnum(NarrationState)
```csharp
public static string GetNarrationKeyByEnum(BossBird.NarrationState nar)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `nar` | `Global.BossBird.NarrationState` |  |

#### Returns
**Type:** System.String

### GetNarrationState(string)
```csharp
public static BossBird.NarrationState GetNarrationState(string state)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.String` |  |

#### Returns
**Type:** Global.BossBird.NarrationState

### GetParam(string)
```csharp
public CreatureStaticData.ParameterData GetParam(string key)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |

#### Returns
**Type:** Global.CreatureStaticData.ParameterData

### GetParamData(string)
```csharp
public string GetParamData(string key)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |

#### Returns
**Type:** System.String

### GetRangeTarget(Vector3, float)
```csharp
public List<UnitModel> GetRangeTarget(Vector3 pos, float half_Range)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `pos` | `UnityEngine.Vector3` |  |
| `half_Range` | `System.Single` |  |

#### Returns
**Type:** System.Collections.Generic.List{UnitModel}

### GiveMeleeDamage()
```csharp
public void GiveMeleeDamage()
```
Does melee damage to all units in range in the direction of the attack ^\[verify\]^.


### InvokeForceTeleport()
```csharp
private void InvokeForceTeleport()
```
Teleports Apocalypse Bird to whichever egg called it, and starts a cooldown.


### InvokeNormalAttack()
```csharp
private void InvokeNormalAttack()
```
Starts its melee attack.


### InvokePatternAttack()
```csharp
private void InvokePatternAttack()
```
Does a special attack depending on the current attack type. Can be normal, Big Bird's attract, Judgment Birds.... , Punishing Bird's mouth attack, or a ranged attack ?


### InvokeTeleport()
```csharp
private void InvokeTeleport()
```
Randomly teleports Apocalypse Bird to a main room, and starts a cooldown.


### MakeBirdConcentrationGate()
```csharp
public void MakeBirdConcentrationGate()
```
Activates the Apocalypse Bird event and makes the [Entrance to the Black Forest](/api/Global/Abnormalities/Apocalypse-Bird/Entrance-to-the-Black-Forest/BossGateWay). Also, registers the birds with Entrance and tells the birds to navigate to it.


### MakeBirdObjects()
```csharp
private void MakeBirdObjects()
```
Makes the eggs for the battle. 

### MakeMovementRandom()
```csharp
public void MakeMovementRandom()
```
Moves to a random main room ^\[verify\]^.


### MakeMovementToEgg(BossEggBase)
```csharp
public void MakeMovementToEgg(BossEggBase script)
```
Moves to the center of the room of the given egg, then plays the teleport animation ^\[verify\]^.


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `script` | `Global.BossEggBase` |  |

### MakeSound(string)
```csharp
public override SoundEffectPlayer MakeSound(string src)
```
Plays the sound at the given source (to play once). Attaches itself to the camera .


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
Plays the sound at the given source (to loop). Attaches itself to the camera .


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

#### Returns
**Type:** Global.SoundEffectPlayer

### MoveToNode(MapNode)
```csharp
public void MoveToNode(MapNode node)
```
Moves the model to the given node.


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |

### OnAfterSuppressed()
```csharp
public override bool OnAfterSuppressed()
```
Stops playing its sounds and tells the animator to play the death animation.


#### Returns
**Type:** System.Boolean

### OnAllBirdArrived()
```csharp
private void OnAllBirdArrived()
```
Informs each bird that the boss has started and calls AfterAppearNarration...


### OnBirdArrived(IBirdControl)
```csharp
public void OnBirdArrived(IBirdControl bird)
```
Plays narration when a bird arrives at the [Entrance to the Black Forest](/api/Global/Abnormalities/Apocalypse-Bird/Entrance-to-the-Black-Forest/BossGateWay), including when all birds have arrived. If all birds have arrived, calls OnAllBirdArrived (which will start the event) and makes the eggs for the event.


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `bird` | `Global.IBirdControl` |  |

### OnBirdArrivedEndNarration()
```csharp
private void OnBirdArrivedEndNarration()
```
Sets a flag indicating narration is not happening.


### OnBirdArrivedStartNarration()
```csharp
private void OnBirdArrivedStartNarration()
```
Sets a flag indicating narration is happening.


### OnBirdEscape(LongBird, SmallBird, BigBird)
```csharp
public void OnBirdEscape(LongBird longBird, SmallBird small, BigBird big)
```
Listens for birds escaping, and if needed, starts the event.
###### More details
If the event is already happening, does nothing. Otherwise, removes any birds which aren't escaping, and adds the newly escaped birds to the list of escaped birds.

If there are at least two birds breaching, and the Twilight EGO is not in the facility, starts the event. This displays starting narration and marks all birds as not yet arrived. When the narration ends, calls MakeBirdConcentrationGate, which spawns the [Entrance to the Black Forest](/api/Global/Abnormalities/Apocalypse-Bird/Entrance-to-the-Black-Forest/BossGateWay).


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `longBird` | `Global.LongBird` |  |
| `small` | `Global.SmallBird` |  |
| `big` | `Global.BigBird` |  |

### OnCannotUsePlaySpeedSetting(int)
```csharp
public void OnCannotUsePlaySpeedSetting(int id)
```
Logs a debug message.


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

### OnCastingEnd()
```csharp
public void OnCastingEnd()
```


### OnEggBreakDown(BossEggBase)
```csharp
public void OnEggBreakDown(BossEggBase eggScript)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `eggScript` | `Global.BossEggBase` |  |

### OnEggHalfDamage(BossEggBase)
```csharp
public void OnEggHalfDamage(BossEggBase eggScript)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `eggScript` | `Global.BossEggBase` |  |

### OnFixedUpdate(CreatureModel)
```csharp
public override void OnFixedUpdate(CreatureModel creature)
```
Makes sure the unit corresponds to whether Apocalypse Bird is active, then if not active, stops checking anything.

If active, checks to see if any agents need to take encounter fear damage..

If the force-teleport timer is done, there is an active egg that wants to be teleported to, and Apocalypse Bird is idle, activates the force-teleport.
Otherwise, if the normal teleport is ready and Apocalypse Bird is idle, teleports normally.

If not teleporting, checks to see which attack or pattern should happen. If doing a bite attack and the attack has fired, applies damage.
If the cooldown for the normal attack is done, does a normal attack; otherwise, if the cooldown for the 'special pattern' is done, does the special pattern.


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.CreatureModel` |  |

### OnGateWaySuppressed()
```csharp
public void OnGateWaySuppressed()
```
Ends the event early and informs all birds that the event is over.


### OnLaserParticleArrived(LaserAttackTargetData)
```csharp
public void OnLaserParticleArrived(BossBird.LaserAttackTargetData data)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `data` | `Global.BossBird.LaserAttackTargetData` |  |

### OnSetPhase(Phase, bool)
```csharp
private void OnSetPhase(BossBird.Phase p, bool isDifferentWithPrevious)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `p` | `Global.BossBird.Phase` |  |
| `isDifferentWithPrevious` | `System.Boolean` |  |

### OnStageEnd()
```csharp
public override void OnStageEnd()
```
Calls base's OnStageRelease ^\[weird\]^^\[verify\]^ and sets the instances of the birds to null.


### OnStageStart()
```csharp
public override void OnStageStart()
```
Calls base and resets its parameters.


### OnSuppressed()
```csharp
public override void OnSuppressed()
```
Wakes up any workers controlled by Big Bird's effect, tells each bird Apocalypse Bird has been suppressed, sets some animation thing , and gives every living and controllable agent the EGO Gift Twilight.


### OnViewInit(CreatureUnit)
```csharp
public override void OnViewInit(CreatureUnit unit)
```
Registers the [CreatureUnit](/api/Global/Abnormalities/CreatureUnit) belonging to Apocalypse Bird ^\[verify\]^, sets the animator and a method to call at half health #inc, and unlocks all of its observation data.


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.CreatureUnit` |  |

### OnWorkerWakeUp(WorkerModel)
```csharp
public void OnWorkerWakeUp(WorkerModel worker)
```
Removes the given worker from the list of workers attracted by Big Bird's ability.


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `worker` | `Global.WorkerModel` |  |

### OpenBossBirdCollection()
```csharp
public void OpenBossBirdCollection()
```


### ParamInit()
```csharp
public override void ParamInit()
```
Resets most state.

Resets:
- The list of escaped birds
- The current attack
- The current teleport destination
- The list of living eggs
- Readiness for force-teleport, normal teleport, normal attack, patternReady - Other current state (activateState , teleporting, using a special attack , force-teleport destination)


### PrevTeleport(MapNode)
```csharp
public void PrevTeleport(MapNode targetNode)
```
Tells the animation script Apocalypse Bird is teleporting, and sets some internal flags. Also, plays a noise called 'move'.


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `targetNode` | `Global.MapNode` |  |

### ScaleCastingSuccess()
```csharp
private void ScaleCastingSuccess()
```


### ScalePattern()
```csharp
public void ScalePattern()
```


### SetBirds(LongBird, SmallBird, BigBird)
```csharp
public void SetBirds(LongBird longBird, SmallBird smallBird, BigBird bigBird)
```
Registers all of the birds with Apocalypse Bird, and Apocalypse Bird with all of the birds.


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `longBird` | `Global.LongBird` |  |
| `smallBird` | `Global.SmallBird` |  |
| `bigBird` | `Global.BigBird` |  |

### SetCastingSlider(Slider)
```csharp
public override bool SetCastingSlider(Slider castingSlider)
```
Does some stuff that shouldn't matter. ^\[verify\]^

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `castingSlider` | `UnityEngine.UI.Slider` |  |

#### Returns
**Type:** System.Boolean

### SetCreatureActivateState(bool)
```csharp
public void SetCreatureActivateState(bool state)
```
Sets Apocalypse Bird's activeness to the provided state.
###### More details
Sets the active state of the game object and its movable node to the provided state. Also, sets Apocalypse Bird's active state and the model's active state to match. Also, sets the current phase to IDLE or NOTACTIVATED when state is true or false, respectively.


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `state` | `System.Boolean` |  |

### SetModel(CreatureModel)
```csharp
public override void SetModel(CreatureModel model)
```
Sets the model to the given model.


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.CreatureModel` |  |

### SetPassageAlpha(bool)
```csharp
private void SetPassageAlpha(bool isDark)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `isDark` | `System.Boolean` |  |

### StartBirdMoveToNode(MapNode)
```csharp
private void StartBirdMoveToNode(MapNode dest)
```
Tells all birds to navigate to the [Entrance to the Black Forest](/api/Global/Abnormalities/Apocalypse-Bird/Entrance-to-the-Black-Forest/BossGateWay).


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `dest` | `Global.MapNode` |  |

### StartMeleeAttack()
```csharp
public void StartMeleeAttack()
```
Chooses a random target in range, faces towards them, and attacks.


### StartRangeAttack()
```csharp
public void StartRangeAttack()
```


### StartUltShoot(MapNode)
```csharp
private void StartUltShoot(MapNode destNode)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `destNode` | `Global.MapNode` |  |

### StopMovement()
```csharp
public void StopMovement()
```
Stops moving.


### TakeUltDamage()
```csharp
public void TakeUltDamage()
```


### Teleport()
```csharp
public void Teleport()
```
Teleports to the current destination and clears it. Randomly faces left or right.


### TryMakeEquip(int)
```csharp
private void TryMakeEquip(int id)
```
If the given EGO doesn't already exist, makes it.


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int32` |  |

### TryMakeEquipments()
```csharp
private void TryMakeEquipments()
```
Attempts to make the Twilight EGO Weapon and Suit, and unlocks all of Apocalypse Bird's information. 

### WakeUpWorker(WorkerModel)
```csharp
public void WakeUpWorker(WorkerModel target)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |

## Inherited Members
[isolateSpriteSrc](/api/Global/Abnormalities/CreatureBase/CreatureBase#isolatespritesrc), [model](/api/Global/Abnormalities/CreatureBase/CreatureBase#model), [skill](/api/Global/Abnormalities/CreatureBase/CreatureBase#skill), [kitEvent](/api/Global/Abnormalities/CreatureBase/CreatureBase#kitevent), [hasUniqueEscapeLogic](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueescapelogic), [isWorkAllocated](/api/Global/Abnormalities/CreatureBase/CreatureBase#isworkallocated), [_allocatedAgent](/api/Global/Abnormalities/CreatureBase/CreatureBase#allocatedagent), [damage](/api/Global/Abnormalities/CreatureBase/CreatureBase#damage), [OnReleaseSpecialTip](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleasespecialtip), [specialSkillTipParamList](/api/Global/Abnormalities/CreatureBase/CreatureBase#specialskilltipparamlist), [_check](/api/Global/Abnormalities/CreatureBase/CreatureBase#check), [OnInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#oninit), [OnViewInitPrev(CreatureUnit)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onviewinitprev-creatureunit), [OnFixedUpdateInSkill(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfixedupdateinskill-useskill), [OnSkillFailWorkTick(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillfailworktick-useskill), [OnSkillSuccessWorkTick(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillsuccessworktick-useskill), [OnSkillTickUpdate(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskilltickupdate-useskill), [OnSkillGoalComplete(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onskillgoalcomplete-useskill), [PermitCancelCurrentWork()](/api/Global/Abnormalities/CreatureBase/CreatureBase#permitcancelcurrentwork), [GetKitCreatureProcessTime()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getkitcreatureprocesstime), [OnBonusWorkProb()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onbonusworkprob), [GetDamageMultiplierInWork(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdamagemultiplierinwork-useskill), [TranformWorkProb(float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#tranformworkprob-float), [OnEnterRoom(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onenterroom-useskill), [OnReleaseWork(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleasework-useskill), [OnFinishWork(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfinishwork-useskill), [OnWorkCoolTimeEnd(CreatureFeelingState)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkcooltimeend-creaturefeelingstate), [OnReturn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreturn), [UniqueEscape()](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniqueescape), [Escape()](/api/Global/Abnormalities/CreatureBase/CreatureBase#escape), [GetSpecialSkill()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getspecialskill), [GetDebugText()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdebugtext), [OnTimerEnd()](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontimerend), [MakeEffect(IsolateRoom, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffect-isolateroom-int), [MakeEffectAlter(IsolateRoom, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectalter-isolateroom-int), [Prob(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#prob-int), [isAttackInWorkProcess()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isattackinworkprocess), [OnAttackInWorkProcess(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onattackinworkprocess-useskill), [AttackProcess(UnitModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#attackprocess-unitmodel), [AutoFeelingDown()](/api/Global/Abnormalities/CreatureBase/CreatureBase#autofeelingdown), [AgentAnimCalled(int, WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#agentanimcalled-int-workermodel), [MakingEffect(string, float, string, Transform, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float-string-transform-int), [MakingEffect(string, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float), [MakeEffectAttachedToHead(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectattachedtohead-string), [MakingEffect(string, float, string, Vector3, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makingeffect-string-float-string-vector3-int), [OnAgentWorkEndAnimationPlayed(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentworkendanimationplayed-useskill), [OnAgentAllocateWork(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentallocatework-agentmodel), [OnStageRelease()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onstagerelease), [OnAllocatedWork(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onallocatedwork-agentmodel), [OnReleaseWorkAllocated()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onreleaseworkallocated), [ObserveLevelChangeForSpecialSkillTip()](/api/Global/Abnormalities/CreatureBase/CreatureBase#observelevelchangeforspecialskilltip), [OnObserveLevelChanged()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onobservelevelchanged), [HasUniqueProcessWorkNarration()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueprocessworknarration), [UniqueProcessWorkNarration(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniqueprocessworknarration-useskill), [RoomSpriteInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomspriteinit), [RoomEscapeSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomescapespriteon), [RoomEscapeSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomescapespriteoff), [RoomSkillSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomskillspriteon), [RoomSkillSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomskillspriteoff), [RoomStateSpriteOn()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomstatespriteon), [RoomStateSpriteOff()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomstatespriteoff), [OnForceSpecialSkillTipReveal(string, params object[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onforcespecialskilltipreveal-string-params-object), [OnWorkReleaseSpeicalSkillTipReveal(string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkreleasespeicalskilltipreveal-string), [OnWorkReleaseTipUpdate(params object[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkreleasetipupdate-params-object), [OnAgentAnimatorReseted()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onagentanimatorreseted), [SpecialEnergyTick()](/api/Global/Abnormalities/CreatureBase/CreatureBase#specialenergytick), [OnFeverTimeOver()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onfevertimeover), [OnOverlayIsolateWork()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onoverlayisolatework), [OnOverlayIsolateObserve()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onoverlayisolateobserve), [OnOpenObserveWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopenobservewindow), [OnOpenWorkWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopenworkwindow), [OnOpenCollectionWindow()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopencollectionwindow), [DelayAttackMotion(float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#delayattackmotion-float), [IsAttackTargetable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isattacktargetable), [GetRealTargets()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getrealtargets), [HasScriptSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasscriptsavedata), [GetSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getsavedata), [LoadData(Dictionary<string, object>)](/api/Global/Abnormalities/CreatureBase/CreatureBase#loaddata-dictionary-string-object), [LoadScriptData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#loadscriptdata), [SaveScriptData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#savescriptdata), [ExistSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#existsavedata), [RemoveSaveData()](/api/Global/Abnormalities/CreatureBase/CreatureBase#removesavedata), [ReplaceCommand(CreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#replacecommand-creaturemodel), [OnGamemanagerInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#ongamemanagerinit), [MakeEffectGlobalPos(string, Vector3)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectglobalpos-string-vector3), [MakeEffectGlobalPosNonTrans(string, Vector3)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makeeffectglobalposnontrans-string-vector3), [CanObservedByAgent(AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#canobservedbyagent-agentmodel), [MakeSound(string, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string-float), [MakeSound(string, AudioRolloffMode)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesound-string-audiorolloffmode), [MakeSoundQueue(params string[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#makesoundqueue-params-string), [OnViewDestroy()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onviewdestroy), [IsWorkable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isworkable), [HasUniqueMaxObservationFinish()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquemaxobservationfinish), [UniqueMaxObservationFinish(Desc)](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquemaxobservationfinish-desc), [OnChildSuppressed(ChildCreatureModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onchildsuppressed-childcreaturemodel), [MakeChildCreature(UnitModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#makechildcreature-unitmodel), [OnKillWorker(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onkillworker-workermodel), [GenPursueCommandAlter(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#genpursuecommandalter-workermodel), [hasUniqueDeadScene()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquedeadscene), [SetHpSlider(Slider)](/api/Global/Abnormalities/CreatureBase/CreatureBase#sethpslider-slider), [HasUniqueAttackDealy()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueattackdealy), [CanTakeDamage(UnitModel, DamageInfo)](/api/Global/Abnormalities/CreatureBase/CreatureBase#cantakedamage-unitmodel-damageinfo), [OnTakePhysicalDamage(UnitModel, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontakephysicaldamage-unitmodel-float), [HasUniqueFaction()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquefaction), [OnWorkerPanic(WorkerModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkerpanic-workermodel), [OnSelectMaxObservation(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onselectmaxobservation-int), [OnLoadCreatureName(ref string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onloadcreaturename-ref-string), [IsSuppressable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#issuppressable), [IsSuppressableByRoom()](/api/Global/Abnormalities/CreatureBase/CreatureBase#issuppressablebyroom), [IsAutoSuppressable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isautosuppressable), [OnWorkWindowSkillClicked(long)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkwindowskillclicked-long), [UseDefaultDamageIgnoreMessage(DamageTextEffect)](/api/Global/Abnormalities/CreatureBase/CreatureBase#usedefaultdamageignoremessage-damagetexteffect), [OnWorkAllocated(SkillTypeInfo, AgentModel)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkallocated-skilltypeinfo-agentmodel), [GetPhysicalDamage(out float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getphysicaldamage-out-float), [GetMentalDamage(out float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getmentaldamage-out-float), [OnSuperArmorBreak()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onsuperarmorbreak), [UniqueStunEffect()](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquestuneffect), [HasEscapeUI()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasescapeui), [HasRoomCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasroomcounter), [RoomCounterInit()](/api/Global/Abnormalities/CreatureBase/CreatureBase#roomcounterinit), [ResetQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#resetqliphothcounter), [GetMaxWorkCountView()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getmaxworkcountview), [GetQliphothCounterMax()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getqliphothcountermax), [ActivateQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#activateqliphothcounter), [ReducedQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#reducedqliphothcounter), [AddedQliphothCounter()](/api/Global/Abnormalities/CreatureBase/CreatureBase#addedqliphothcounter), [OnTakeDamage(UnitModel, DamageInfo, float)](/api/Global/Abnormalities/CreatureBase/CreatureBase#ontakedamage-unitmodel-damageinfo-float), [GetRadius()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getradius), [OnElevatorStuck()](/api/Global/Abnormalities/CreatureBase/CreatureBase#onelevatorstuck), [OnWorkClosed(UseSkill, int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#onworkclosed-useskill-int), [IsActivatedWorkDesc()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isactivatedworkdesc), [IsSensoredInPassage()](/api/Global/Abnormalities/CreatureBase/CreatureBase#issensoredinpassage), [IsIndirectSuppressable()](/api/Global/Abnormalities/CreatureBase/CreatureBase#isindirectsuppressable), [GetRiskLevel()](/api/Global/Abnormalities/CreatureBase/CreatureBase#getrisklevel), [UniqueMoveControl()](/api/Global/Abnormalities/CreatureBase/CreatureBase#uniquemovecontrol), [HasUniqueName()](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquename), [GetDamageFactor(UnitModel, DamageInfo)](/api/Global/Abnormalities/CreatureBase/CreatureBase#getdamagefactor-unitmodel-damageinfo), [OnInitialBuild()](/api/Global/Abnormalities/CreatureBase/CreatureBase#oninitialbuild), [HasUniqueCollectionCost(string, out string)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquecollectioncost-string-out-string), [OnOpenCommandWindow(Button[])](/api/Global/Abnormalities/CreatureBase/CreatureBase#onopencommandwindow-button), [HasUniqueCommandAction(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniquecommandaction-int), [HasUniqueWorkSelect(int)](/api/Global/Abnormalities/CreatureBase/CreatureBase#hasuniqueworkselect-int), [ForcelySuccess(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#forcelysuccess-useskill), [ForcelyFail(UseSkill)](/api/Global/Abnormalities/CreatureBase/CreatureBase#forcelyfail-useskill), [TryRabbitTeleport(MapNode)](/api/Global/Abnormalities/CreatureBase/CreatureBase#tryrabbitteleport-mapnode), [CanEnterRoom()](/api/Global/Abnormalities/CreatureBase/CreatureBase#canenterroom), [AllocatedAgent](/api/Global/Abnormalities/CreatureBase/CreatureBase#allocatedagent), [skillTriggerCheck](/api/Global/Abnormalities/CreatureBase/CreatureBase#skilltriggercheck), [Unit](/api/Global/Abnormalities/CreatureBase/CreatureBase#unit), [GetSaveSrc](/api/Global/Abnormalities/CreatureBase/CreatureBase#getsavesrc), [movable](/api/Global/Abnormalities/CreatureBase/CreatureBase#movable), [currentPassage](/api/Global/Abnormalities/CreatureBase/CreatureBase#currentpassage), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)








