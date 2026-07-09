---
uid: Global.MachineDuskOrdeal
canonical_path: /api/Global/Machine/MachineDuskOrdeal
---
# Class MachineDuskOrdeal
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class MachineDuskOrdeal : MachineOrdeal
```
> This section may have incomplete or incorrect information.
{.is-warning}


Dusk of Green, Where We Must Reach. Spawns four [MachineDusks](/api/Global/Abnormalities/Ordeals/Green-Ordeals/Green-Dusk/MachineDusk).




## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [OrdealBase](/api/Global/Abnormalities/Ordeals/Green-Ordeals/MachineOrdeal) → MachineDuskOrdeal

## Constructors
### MachineDuskOrdeal()
```csharp
public MachineDuskOrdeal()
```


## Fields
### _duskMax
```csharp
private const int _duskMax = 4
```


#### Field Value
**Type:** System.Int32

### _spawnMax
```csharp
private const int _spawnMax = 15
```


#### Field Value
**Type:** System.Int32

### dusks
```csharp
private List<MachineDusk> dusks
```


#### Field Value
**Type:** System.Collections.Generic.List{MachineDusk}

### spawning
```csharp
private int spawning
```


#### Field Value
**Type:** System.Int32

### spawns
```csharp
private List<MachineOrdealCreature> spawns
```


#### Field Value
**Type:** System.Collections.Generic.List{MachineOrdealCreature}

## Properties
### count
```csharp
private int count { get; }
```

#### Property Value
**Type:** System.Int32

### spawnCount
```csharp
private int spawnCount { get; }
```

#### Property Value
**Type:** System.Int32

## Methods
### FixedUpdate()
```csharp
public override void FixedUpdate()
```


### GetNode(Sefira)
```csharp
private MapNode GetNode(Sefira sefira)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.Sefira` |  |

#### Returns
**Type:** Global.MapNode

### GetPassage(Sefira)
```csharp
private PassageObjectModel GetPassage(Sefira sefira)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.Sefira` |  |

#### Returns
**Type:** Global.PassageObjectModel

### MakeDusks()
```csharp
private void MakeDusks()
```


### MakeOrdealCreature(OrdealLevel, MapNode)
```csharp
public override MachineOrdealCreature MakeOrdealCreature(OrdealLevel level, MapNode node)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `level` | `Global.OrdealLevel` |  |
| `node` | `Global.MapNode` |  |

#### Returns
**Type:** Global.MachineOrdealCreature

### OnOrdealStart()
```csharp
public override void OnOrdealStart()
```


## Inherited Members
[_curOrdealCreatureList](/api/Global/Abnormalities/Ordeals/OrdealBase#level), [riskLevel](/api/Global/Abnormalities/Ordeals/OrdealBase#risklevel), [ordealRewards](/api/Global/Abnormalities/Ordeals/OrdealBase#ordealrewards), [startTime](/api/Global/Abnormalities/Ordeals/OrdealBase#starttime), [isStarted](/api/Global/Abnormalities/Ordeals/OrdealBase#isstarted), [_ordeal_name](/api/Global/Abnormalities/Ordeals/OrdealBase#ordeal-name), [OrdealColor](/api/Global/Abnormalities/Ordeals/OrdealBase#ordealcolor), [_canTakeRewards](/api/Global/Abnormalities/Ordeals/OrdealBase#cantakerewards), [OnGameInit()](/api/Global/Abnormalities/Ordeals/OrdealBase#ongameinit), [OnDestroy()](/api/Global/Abnormalities/Ordeals/OrdealBase#ondestroy), [OrdealTypo(string, Color, bool, int)](/api/Global/Abnormalities/Ordeals/OrdealBase#ordealtypo-string-color-bool-int), [IsStartable()](/api/Global/Abnormalities/Ordeals/OrdealBase#isstartable), [SetRiskLevel(RiskLevel)](/api/Global/Abnormalities/Ordeals/OrdealBase#setrisklevel-risklevel), [canTakeRewards](/api/Global/Abnormalities/Ordeals/OrdealBase#cantakerewards), [OrdealTypeText](/api/Global/Abnormalities/Ordeals/OrdealBase#ordealtypetext), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)






