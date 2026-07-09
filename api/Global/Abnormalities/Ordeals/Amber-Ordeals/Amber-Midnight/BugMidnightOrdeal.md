---
uid: Global.BugMidnightOrdeal
canonical_path: /api/Global/Misc/BugMidnightOrdeal
---
# Class BugMidnightOrdeal
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BugMidnightOrdeal : BugOrdeal
```
> This section may have incomplete or incorrect information.
{.is-warning}


Midnight of Amber ordeal; The Eternal Meal. Spawns a few [BugMidnights](/api/Global/Abnormalities/Ordeals/Amber-Ordeals/Amber-Midnight/BugMidnight).


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [OrdealBase](/api/Global/Abnormalities/Ordeals/Amber-Ordeals/BugOrdeal) → BugMidnightOrdeal

## Constructors
### BugMidnightOrdeal()
```csharp
public BugMidnightOrdeal()
```


## Fields
### _spawnNum
```csharp
private const int _spawnNum = 2
```


#### Field Value
**Type:** System.Int32

### managers
```csharp
private List<BugMidnightOrdeal.BugMidnightManager> managers
```

#### Field Value
**Type:** System.Collections.Generic.List{BugMidnightOrdeal.BugMidnightManager}

## Methods
### GetTargetNode()
```csharp
public MapNode GetTargetNode()
```


#### Returns
**Type:** Global.MapNode

### MakeBug()
```csharp
private void MakeBug()
```


### MakeOrdealCreature(OrdealLevel, MapNode, BugMidnight, params UnitDirection[])
```csharp
public override BugOrdealCreature MakeOrdealCreature(OrdealLevel level, MapNode node, BugMidnight midnight, params UnitDirection[] direction)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `level` | `Global.OrdealLevel` |  |
| `node` | `Global.MapNode` |  |
| `midnight` | `Global.BugMidnight` |  |
| `direction` | `Global.UnitDirection[]` |  |

#### Returns
**Type:** Global.BugOrdealCreature

### OnDie(OrdealCreatureModel)
```csharp
public override void OnDie(OrdealCreatureModel model)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.OrdealCreatureModel` |  |

### OnOrdealStart()
```csharp
public override void OnOrdealStart()
```


### OnTeleport(MapNode, BugMidnight)
```csharp
public void OnTeleport(MapNode node, BugMidnight midnight)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |
| `midnight` | `Global.BugMidnight` |  |

## Inherited Members
[_curOrdealCreatureList](/api/Global/Abnormalities/Ordeals/OrdealBase#level), [riskLevel](/api/Global/Abnormalities/Ordeals/OrdealBase#risklevel), [ordealRewards](/api/Global/Abnormalities/Ordeals/OrdealBase#ordealrewards), [startTime](/api/Global/Abnormalities/Ordeals/OrdealBase#starttime), [isStarted](/api/Global/Abnormalities/Ordeals/OrdealBase#isstarted), [_ordeal_name](/api/Global/Abnormalities/Ordeals/OrdealBase#ordeal-name), [OrdealColor](/api/Global/Abnormalities/Ordeals/OrdealBase#ordealcolor), [_canTakeRewards](/api/Global/Abnormalities/Ordeals/OrdealBase#cantakerewards), [OnGameInit()](/api/Global/Abnormalities/Ordeals/OrdealBase#ongameinit), [OnDestroy()](/api/Global/Abnormalities/Ordeals/OrdealBase#ondestroy), [OrdealTypo(string, Color, bool, int)](/api/Global/Abnormalities/Ordeals/OrdealBase#ordealtypo-string-color-bool-int), [IsStartable()](/api/Global/Abnormalities/Ordeals/OrdealBase#isstartable), [SetRiskLevel(RiskLevel)](/api/Global/Abnormalities/Ordeals/OrdealBase#setrisklevel-risklevel), [canTakeRewards](/api/Global/Abnormalities/Ordeals/OrdealBase#cantakerewards), [OrdealTypeText](/api/Global/Abnormalities/Ordeals/OrdealBase#ordealtypetext), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)






