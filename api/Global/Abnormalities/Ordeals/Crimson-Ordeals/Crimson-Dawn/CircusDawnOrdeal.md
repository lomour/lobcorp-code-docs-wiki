---
uid: Global.CircusDawnOrdeal
canonical_path: /api/Global/Misc/CircusDawnOrdeal
---
# Class CircusDawnOrdeal
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CircusDawnOrdeal : CircusOrdeal
```
> This section may have incomplete or incorrect information.
{.is-warning}


Dawn of Crimson ordeal, The Cheers for the Beginning. Spawns several [CircusDawns](/api/Global/Abnormalities/Ordeals/Crimson-Ordeals/Crimson-Dawn/CircusDawn).


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [OrdealBase](/api/Global/Abnormalities/Ordeals/Crimson-Ordeals/CircusOrdeal) → CircusDawnOrdeal

## Constructors
### CircusDawnOrdeal()
```csharp
public CircusDawnOrdeal()
```


## Fields
### _currentWaitingCreature
```csharp
private CreatureModel _currentWaitingCreature
```


#### Field Value
**Type:** Global.CreatureModel

## Methods
### GetTarget(out bool)
```csharp
public CreatureModel GetTarget(out bool hasError)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `hasError` | `System.Boolean` |  |

#### Returns
**Type:** Global.CreatureModel

### GetTeleportNode()
```csharp
public MapNode GetTeleportNode()
```


#### Returns
**Type:** Global.MapNode

### IsStartable()
```csharp
public override bool IsStartable()
```


#### Returns
**Type:** System.Boolean

### OnOrdealStart()
```csharp
public override void OnOrdealStart()
```


### ReadyForTeleport()
```csharp
public bool ReadyForTeleport()
```


#### Returns
**Type:** System.Boolean

## Inherited Members
[_curOrdealCreatureList](/api/Global/Abnormalities/Ordeals/OrdealBase#level), [riskLevel](/api/Global/Abnormalities/Ordeals/OrdealBase#risklevel), [ordealRewards](/api/Global/Abnormalities/Ordeals/OrdealBase#ordealrewards), [startTime](/api/Global/Abnormalities/Ordeals/OrdealBase#starttime), [isStarted](/api/Global/Abnormalities/Ordeals/OrdealBase#isstarted), [_ordeal_name](/api/Global/Abnormalities/Ordeals/OrdealBase#ordeal-name), [OrdealColor](/api/Global/Abnormalities/Ordeals/OrdealBase#ordealcolor), [_canTakeRewards](/api/Global/Abnormalities/Ordeals/OrdealBase#cantakerewards), [OnGameInit()](/api/Global/Abnormalities/Ordeals/OrdealBase#ongameinit), [OnDestroy()](/api/Global/Abnormalities/Ordeals/OrdealBase#ondestroy), [OrdealTypo(string, Color, bool, int)](/api/Global/Abnormalities/Ordeals/OrdealBase#ordealtypo-string-color-bool-int), [SetRiskLevel(RiskLevel)](/api/Global/Abnormalities/Ordeals/OrdealBase#setrisklevel-risklevel), [canTakeRewards](/api/Global/Abnormalities/Ordeals/OrdealBase#cantakerewards), [OrdealTypeText](/api/Global/Abnormalities/Ordeals/OrdealBase#ordealtypetext), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)






