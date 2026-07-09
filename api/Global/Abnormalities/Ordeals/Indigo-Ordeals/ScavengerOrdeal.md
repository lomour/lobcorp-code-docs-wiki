---
uid: Global.ScavengerOrdeal
canonical_path: /api/Global/Misc/ScavengerOrdeal
---
# Class ScavengerOrdeal
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ScavengerOrdeal : OrdealBase
```
> This section may have incomplete or incorrect information.
{.is-warning}


Parent class for Indigo Ordeals. There is just one: [Indigo Noon](/api/Global/Abnormalities/Ordeals/Indigo-Ordeals/Indigo-Noon/ScavengerNoonOrdeal).


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [OrdealBase](/api/Global/Abnormalities/Ordeals/OrdealBase) → ScavengerOrdeal

## Derived
[ScavengerNoonOrdeal](/api/Global/Abnormalities/Ordeals/Indigo-Ordeals/Indigo-Noon/ScavengerNoonOrdeal)

## Constructors
### ScavengerOrdeal()
```csharp
public ScavengerOrdeal()
```


## Fields
### _color
```csharp
protected Color _color
```


#### Field Value
**Type:** UnityEngine.Color

### _curOrdealCreatureList
```csharp
protected List<OrdealCreatureModel> _curOrdealCreatureList
```


#### Field Value
**Type:** System.Collections.Generic.List{OrdealCreatureModel}

### _ordealName
```csharp
protected string _ordealName
```


#### Field Value
**Type:** System.String

### ids
```csharp
private static int[] ids
```


#### Field Value
**Type:** System.Int32[]

## Methods
### CheckCloseCondition()
```csharp
protected virtual bool CheckCloseCondition()
```


#### Returns
**Type:** System.Boolean

### FixedUpdate()
```csharp
public override void FixedUpdate()
```


### MakeOrdealCreature(OrdealLevel, MapNode, params UnitDirection[])
```csharp
public ScavengerOrdealCreature MakeOrdealCreature(OrdealLevel level, MapNode node, params UnitDirection[] direction)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `level` | `Global.OrdealLevel` |  |
| `node` | `Global.MapNode` |  |
| `direction` | `Global.UnitDirection[]` |  |

#### Returns
**Type:** Global.ScavengerOrdealCreature

### OnDie(OrdealCreatureModel)
```csharp
public virtual void OnDie(OrdealCreatureModel model)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `model` | `Global.OrdealCreatureModel` |  |

### OnOrdealStart()
```csharp
public override void OnOrdealStart()
```


### OrdealEnd()
```csharp
public override void OrdealEnd()
```


### SetColor()
```csharp
protected void SetColor()
```


## Inherited Members
[level](/api/Global/Abnormalities/Ordeals/OrdealBase#level), [riskLevel](/api/Global/Abnormalities/Ordeals/OrdealBase#risklevel), [ordealRewards](/api/Global/Abnormalities/Ordeals/OrdealBase#ordealrewards), [startTime](/api/Global/Abnormalities/Ordeals/OrdealBase#starttime), [isStarted](/api/Global/Abnormalities/Ordeals/OrdealBase#isstarted), [_ordeal_name](/api/Global/Abnormalities/Ordeals/OrdealBase#ordeal-name), [OrdealColor](/api/Global/Abnormalities/Ordeals/OrdealBase#ordealcolor), [_canTakeRewards](/api/Global/Abnormalities/Ordeals/OrdealBase#cantakerewards), [OrdealNameText(OrdealCreatureModel)](/api/Global/Abnormalities/Ordeals/OrdealBase#ordealnametext-ordealcreaturemodel), [OnGameInit()](/api/Global/Abnormalities/Ordeals/OrdealBase#ongameinit), [OnDestroy()](/api/Global/Abnormalities/Ordeals/OrdealBase#ondestroy), [OrdealTypo(string, Color, bool, int)](/api/Global/Abnormalities/Ordeals/OrdealBase#ordealtypo-string-color-bool-int), [IsStartable()](/api/Global/Abnormalities/Ordeals/OrdealBase#isstartable), [GetRiskLevel(OrdealCreatureModel)](/api/Global/Abnormalities/Ordeals/OrdealBase#getrisklevel-ordealcreaturemodel), [SetRiskLevel(RiskLevel)](/api/Global/Abnormalities/Ordeals/OrdealBase#setrisklevel-risklevel), [canTakeRewards](/api/Global/Abnormalities/Ordeals/OrdealBase#cantakerewards), [OrdealTypeText](/api/Global/Abnormalities/Ordeals/OrdealBase#ordealtypetext), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)






