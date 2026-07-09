---
uid: Global.ScavengerNoonOrdeal
canonical_path: /api/Global/Misc/ScavengerNoonOrdeal
---
# Class ScavengerNoonOrdeal
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
internal class ScavengerNoonOrdeal : ScavengerOrdeal
```
> This section may have incomplete or incorrect information.
{.is-warning}


Noon of Indigo, The Sweepers. Spawns four groups of three [Sweepers](/api/Global/Abnormalities/Ordeals/Indigo-Ordeals/Indigo-Noon/ScavengerNoon).




## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [OrdealBase](/api/Global/Abnormalities/Ordeals/Indigo-Ordeals/ScavengerOrdeal) → ScavengerNoonOrdeal

## Constructors
### ScavengerNoonOrdeal()
```csharp
public ScavengerNoonOrdeal()
```


## Fields
### _centerDist
```csharp
private const float _centerDist = 0
```


#### Field Value
**Type:** System.Single

### _leftDist
```csharp
private const float _leftDist = -3
```


#### Field Value
**Type:** System.Single

### _maxNumOfSefira
```csharp
private const int _maxNumOfSefira = 4
```


#### Field Value
**Type:** System.Int32

### _rightDist
```csharp
private const float _rightDist = 3
```


#### Field Value
**Type:** System.Single

### _spawnPerSefira
```csharp
private const int _spawnPerSefira = 3
```


#### Field Value
**Type:** System.Int32

## Methods
### GetNode(PassageObjectModel)
```csharp
private MapNode GetNode(PassageObjectModel passage)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `passage` | `Global.PassageObjectModel` |  |

#### Returns
**Type:** Global.MapNode

### GetPassages(Sefira)
```csharp
private List<PassageObjectModel> GetPassages(Sefira sefira)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `sefira` | `Global.Sefira` |  |

#### Returns
**Type:** System.Collections.Generic.List{PassageObjectModel}

### GetSefira(ref List<Sefira>)
```csharp
private Sefira GetSefira(ref List<Sefira> remain)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `remain` | `System.Collections.Generic.List{Sefira}` |  |

#### Returns
**Type:** Global.Sefira

### MakeNoon()
```csharp
private void MakeNoon()
```


### MakeScavengers(MapNode)
```csharp
private void MakeScavengers(MapNode node)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `node` | `Global.MapNode` |  |

### OnOrdealStart()
```csharp
public override void OnOrdealStart()
```


## Inherited Members
[_curOrdealCreatureList](/api/Global/Abnormalities/Ordeals/OrdealBase#level), [riskLevel](/api/Global/Abnormalities/Ordeals/OrdealBase#risklevel), [ordealRewards](/api/Global/Abnormalities/Ordeals/OrdealBase#ordealrewards), [startTime](/api/Global/Abnormalities/Ordeals/OrdealBase#starttime), [isStarted](/api/Global/Abnormalities/Ordeals/OrdealBase#isstarted), [_ordeal_name](/api/Global/Abnormalities/Ordeals/OrdealBase#ordeal-name), [OrdealColor](/api/Global/Abnormalities/Ordeals/OrdealBase#ordealcolor), [_canTakeRewards](/api/Global/Abnormalities/Ordeals/OrdealBase#cantakerewards), [OrdealNameText(OrdealCreatureModel)](/api/Global/Abnormalities/Ordeals/OrdealBase#ordealnametext-ordealcreaturemodel), [OnGameInit()](/api/Global/Abnormalities/Ordeals/OrdealBase#ongameinit), [OnDestroy()](/api/Global/Abnormalities/Ordeals/OrdealBase#ondestroy), [OrdealTypo(string, Color, bool, int)](/api/Global/Abnormalities/Ordeals/OrdealBase#ordealtypo-string-color-bool-int), [IsStartable()](/api/Global/Abnormalities/Ordeals/OrdealBase#isstartable), [GetRiskLevel(OrdealCreatureModel)](/api/Global/Abnormalities/Ordeals/OrdealBase#getrisklevel-ordealcreaturemodel), [SetRiskLevel(RiskLevel)](/api/Global/Abnormalities/Ordeals/OrdealBase#setrisklevel-risklevel), [canTakeRewards](/api/Global/Abnormalities/Ordeals/OrdealBase#cantakerewards), [OrdealTypeText](/api/Global/Abnormalities/Ordeals/OrdealBase#ordealtypetext), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)






