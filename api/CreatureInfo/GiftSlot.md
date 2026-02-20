 
 
---
uid: CreatureInfo.GiftSlot
canonical_path: /api/CreatureInfo/GiftSlot
---

# Class GiftSlot
**Namespace:** [CreatureInfo](/api/CreatureInfo)
**Assembly:** Assembly-CSharp.dll

```csharp
public class GiftSlot : EquipSlot
```
> This section may have incomplete or incorrect information.
{.is-warning}


Class for displaying the EGO gift slot in the abnormality information screen.

**Fields:**
Image ItemImage: EGO gift image
Text ItemTrait: presumably the gift description? 
**Methods:**
void SetModel([EquipmentModel](/api/Global/Model/EquipmentModel) Model): populates class from an EquipmentModel 
void SetProb(float prob): Creates the drop chance string.

void SetEmpty(): Makes the drop chance string... none? 
void SetModel([EquipmentTypeInfo](/api/Global/Info/EquipmentTypeInfo) info): populates class from an EquipmentTypeInfo object 

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [EquipSlot](/api/CreatureInfo/EquipSlot) → GiftSlot

## Constructors

### GiftSlot()
```csharp
public GiftSlot()
```

## Fields

### ItemImage
```csharp
public Image ItemImage
```


#### Field Value
**Type:** UnityEngine.UI.Image

### ItemTrait
```csharp
public Text ItemTrait
```


#### Field Value
**Type:** UnityEngine.UI.Text

## Properties

### GiftModel
```csharp
private EGOgiftModel GiftModel { get; }
```

#### Property Value
**Type:** Global.EGOgiftModel

## Methods

### SetEmpty()
```csharp
public void SetEmpty()
```


### SetModel(EquipmentModel)
```csharp
public override void SetModel(EquipmentModel Model)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `Model` | `Global.EquipmentModel` |  |

### SetModel(EquipmentTypeInfo)
```csharp
public override void SetModel(EquipmentTypeInfo info)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `info` | `Global.EquipmentTypeInfo` |  |

### SetProb(float)
```csharp
public void SetProb(float prob)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `prob` | `System.Single` |  |

## Inherited Members
[ActiveControl](/api/CreatureInfo/EquipSlot#activecontrol), [BlockControl](/api/CreatureInfo/EquipSlot#blockcontrol), [BlockText](/api/CreatureInfo/EquipSlot#blocktext), [Title](/api/CreatureInfo/EquipSlot#title), [Outlook](/api/CreatureInfo/EquipSlot#outlook), [ItemName](/api/CreatureInfo/EquipSlot#itemname), [_info](/api/CreatureInfo/EquipSlot#info), [_model](/api/CreatureInfo/EquipSlot#model), [makeInfo](/api/CreatureInfo/EquipSlot#makeinfo), [CheckBlocked(bool, int)](/api/CreatureInfo/EquipSlot#checkblocked-bool-int), [NoData(string)](/api/CreatureInfo/EquipSlot#nodata-string), [CheckOpened(out int)](/api/CreatureInfo/EquipSlot#checkopened-out-int), [SetEquipInfo(CreatureEquipmentMakeInfo)](/api/CreatureInfo/EquipSlot#setequipinfo-creatureequipmentmakeinfo), [Info](/api/CreatureInfo/EquipSlot#info), [Model](/api/CreatureInfo/EquipSlot#model), [MakeInfo](/api/CreatureInfo/EquipSlot#makeinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)


