---
uid: Global.BugOrdeal
canonical_path: /api/Global/Misc/BugOrdeal
---
# Class BugOrdeal
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BugOrdeal : OrdealBase
```
> This section may have incomplete or incorrect information.
{.is-warning}


Amber ordeal parent class.

(Seems to think there should be a bug noon... It's wrong.)


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [OrdealBase](/api/Global/Abnormalities/Ordeals/OrdealBase) → BugOrdeal

## Derived
[BugDawnOrdeal](/api/Global/Abnormalities/Ordeals/Amber-Ordeals/Amber-Midnight/BugMidnightOrdeal)

## Constructors
### BugOrdeal()
```csharp
public BugOrdeal()
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

### names
```csharp
private static string[] names
```


#### Field Value
**Type:** System.String[]

### risks
```csharp
private static RiskLevel[] risks
```


#### Field Value
**Type:** Global.RiskLevel[]

## Methods
### AddChildBug(OrdealCreatureModel)
```csharp
public void AddChildBug(OrdealCreatureModel child)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `child` | `Global.OrdealCreatureModel` |  |

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


### GetRiskLevel(OrdealCreatureModel)
```csharp
public override RiskLevel GetRiskLevel(OrdealCreatureModel creature)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `creature` | `Global.OrdealCreatureModel` |  |

#### Returns
**Type:** Global.RiskLevel

### MakeOrdealCreature(OrdealLevel, MapNode, BugMidnight, params UnitDirection[])
```csharp
public virtual BugOrdealCreature MakeOrdealCreature(OrdealLevel level, MapNode node, BugMidnight midnight, params UnitDirection[] direction)
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


### OrdealNameText(OrdealCreatureModel)
```csharp
public override string OrdealNameText(OrdealCreatureModel ordeal)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `ordeal` | `Global.OrdealCreatureModel` |  |

#### Returns
**Type:** System.String

### SetColor()
```csharp
private void SetColor()
```


## Inherited Members
[level](/api/Global/Abnormalities/Ordeals/OrdealBase#level), [riskLevel](/api/Global/Abnormalities/Ordeals/OrdealBase#risklevel), [ordealRewards](/api/Global/Abnormalities/Ordeals/OrdealBase#ordealrewards), [startTime](/api/Global/Abnormalities/Ordeals/OrdealBase#starttime), [isStarted](/api/Global/Abnormalities/Ordeals/OrdealBase#isstarted), [_ordeal_name](/api/Global/Abnormalities/Ordeals/OrdealBase#ordeal-name), [OrdealColor](/api/Global/Abnormalities/Ordeals/OrdealBase#ordealcolor), [_canTakeRewards](/api/Global/Abnormalities/Ordeals/OrdealBase#cantakerewards), [OnGameInit()](/api/Global/Abnormalities/Ordeals/OrdealBase#ongameinit), [OnDestroy()](/api/Global/Abnormalities/Ordeals/OrdealBase#ondestroy), [OrdealTypo(string, Color, bool, int)](/api/Global/Abnormalities/Ordeals/OrdealBase#ordealtypo-string-color-bool-int), [IsStartable()](/api/Global/Abnormalities/Ordeals/OrdealBase#isstartable), [SetRiskLevel(RiskLevel)](/api/Global/Abnormalities/Ordeals/OrdealBase#setrisklevel-risklevel), [canTakeRewards](/api/Global/Abnormalities/Ordeals/OrdealBase#cantakerewards), [OrdealTypeText](/api/Global/Abnormalities/Ordeals/OrdealBase#ordealtypetext), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)






