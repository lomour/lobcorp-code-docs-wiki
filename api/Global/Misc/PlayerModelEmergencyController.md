---
title: PlayerModelEmergencyController
description: 
published: true
date: 2026-02-25T03:38:11.640Z
tags: 
editor: markdown
dateCreated: 2026-01-15T04:23:07.933Z
---

# Class PlayerModel.EmergencyController
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class PlayerModel.EmergencyController
```
Controls the trumpet level in the facility. A nested class of [PlayerModel](/api/Global/Model/PlayerModel), which has otherwise unrelated functions.

Oddly, [BgmManager](/api/Global/IOBserver/BgmManager) seems to handle the score reducing over time.
## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → PlayerModel.EmergencyController

## Constructors
### EmergencyController()
```csharp
public EmergencyController()
```

## Fields
### _currentLevel
```csharp
private EmergencyLevel _currentLevel
```

#### Field Value
**Type:** Global.EmergencyLevel

### _currentScore
```csharp
private float _currentScore
```

#### Field Value
**Type:** System.Single

### ALEPH
```csharp
public static float ALEPH
```

#### Field Value
**Type:** System.Single

### emergecyID
```csharp
private List<long> emergecyID
```

#### Field Value
**Type:** System.Collections.Generic.List{System.Int64}

### HE
```csharp
public static float HE
```

#### Field Value
**Type:** System.Single

### Range
```csharp
public static int[] Range
```

#### Field Value
**Type:** System.Int32[]

### TETH
```csharp
public static float TETH
```

#### Field Value
**Type:** System.Single

### WAW
```csharp
public static float WAW
```

#### Field Value
**Type:** System.Single

### ZAYIN
```csharp
public static float ZAYIN
```

#### Field Value
**Type:** System.Single

## Properties
### currentLevel
```csharp
public EmergencyLevel currentLevel { get; set; }
```

#### Property Value
**Type:** Global.EmergencyLevel

### currentScore
```csharp
private float currentScore { get; set; }
```

#### Property Value
**Type:** System.Single

## Methods
### AddScore(CreatureModel)
```csharp
public void AddScore(CreatureModel model)
```
Adds the appropriate score for the provided breaching abnormality.
#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.CreatureModel` |  |

### AddScore(float)
```csharp
public void AddScore(float val)
```
Adds the value to the emergency score, then sets the appropriate emergency level. Also instructs the [BgmManager](/api/Global/IOBserver/BgmManager) to start a timer which prevents reducing the score.
#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `val` | `System.Single` |  |

### AddScore(RiskLevel)
```csharp
public void AddScore(RiskLevel level)
```
Adds the appropriate score for the provided risk level.
#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `level` | `Global.RiskLevel` |  |

### Apply(long)
```csharp
public void Apply(long id)
```
Unused.
#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

### Exit(long)
```csharp
public void Exit(long id)
```
Unused.
#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.Int64` |  |

### GetCurrentScore()
```csharp
public float GetCurrentScore()
```

#### Returns
**Type:** System.Single

### GetLevelScore(RiskLevel)
```csharp
public float GetLevelScore(RiskLevel level)
```
Returns the amount the emergency score should go up for a breaching abnormality of the given risk level.

| **Risk Level** | **Score** |
| -------------- | --------- |
| ZAYIN          | 5         |
| TETH           | 20        |
| HE             | 40        |
| WAW            | 60        |
| ALEPH          | 75        |

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `level` | `Global.RiskLevel` |  |

#### Returns
**Type:** System.Single

### GetScore(CreatureModel)
```csharp
public float GetScore(CreatureModel model)
```
Gets the score for the provided abnormality's risk level.
#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.CreatureModel` |  |

#### Returns
**Type:** System.Single

### GetScore(RiskLevel)
```csharp
public float GetScore(RiskLevel level)
```
Gets the score for the provided risk level.
#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `level` | `Global.RiskLevel` |  |

#### Returns
**Type:** System.Single

### Init()
```csharp
public void Init()
```
Initializes the emergency score to `0`.
### OnStageEnd()
```csharp
public void OnStageEnd()
```
Sets the emergency level to `NORMAL`.
### OnStageRelease()
```csharp
public void OnStageRelease()
```
Resets the score to `0`, clears all trumpets, and sets the emergency level to `NORMAL`.
### Print()
```csharp
public void Print()
```
Prints the current score to Unity's debug log.
### ReduceSore(float)
```csharp
public void ReduceSore(float val)
```
Lowers the emergency score by the value, then prints this the new value to the debug log.
#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `val` | `System.Single` |  |

### SetCurrentScore(float)
```csharp
public void SetCurrentScore(float val)
```

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `val` | `System.Single` |  |

### SetLevel()
```csharp
private void SetLevel()
```
Sets the level as follows:
| Value | Level |
| --- | --- |
|$\leq$ 10 | Normal |
|$\leq$ 50 | First Trumpet |
| $\leq$ 80 | Second Trumpet |
| $>$ 80 | Third Trumpet |

If the emergency level changes, it also notifies listeners of OnEmergencyLevelChanged (and logs a debug string).
## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)



