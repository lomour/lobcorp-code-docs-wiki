---
title: ArmorSlot
description: 
published: true
date: 2026-02-23T23:22:51.141Z
tags: 
editor: markdown
dateCreated: 2026-01-15T02:52:43.854Z
---

# Class ArmorSlot
**Namespace:** [CreatureInfo](/api/CreatureInfo)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ArmorSlot : EquipSlot
```
> This section may have incomplete or incorrect information.
{.is-warning}


Class for displaying the EGO Suit slot in the abnormality information screen.

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [EquipSlot](/api/CreatureInfo/EquipSlot) → ArmorSlot

## Constructors
### ArmorSlot()
```csharp
public ArmorSlot()
```

## Fields
### BuildButton
```csharp
public Button BuildButton
```
Button that buys the EGO.

#### Field Value
**Type:** UnityEngine.UI.Button

### Cost
```csharp
public int Cost
```
PE box cost of making the EGO.

#### Field Value
**Type:** System.Int32

### cost
```csharp
private string cost
```


#### Field Value
**Type:** System.String

### currentCreature
```csharp
public CreatureModel currentCreature
```
The abnormality whose information is being displayed.

#### Field Value
**Type:** Global.CreatureModel

### GradeText
```csharp
public Text GradeText
```
Grade of the EGO.

#### Field Value
**Type:** UnityEngine.UI.Text

### MakeArmorTooltip
```csharp
public TooltipMouseOver MakeArmorTooltip
```
Tooltip for hovering over the build button.

#### Field Value
**Type:** Global.TooltipMouseOver

### MakeCount
```csharp
public Text MakeCount
```
Maximum amount of EGO allowed to be bought.

#### Field Value
**Type:** UnityEngine.UI.Text

### portrait
```csharp
public WorkerPortraitSetter portrait
```
Display window for showing the EGO suit.

#### Field Value
**Type:** Global.WorkerPortraitSetter

### RWBP_Defense
```csharp
public Text[] RWBP_Defense
```
List of defenses of the EGO suit.

#### Field Value
**Type:** UnityEngine.UI.Text[]

### TypeText
```csharp
public Text[] TypeText
```


#### Field Value
**Type:** UnityEngine.UI.Text[]

## Properties
### ArmorModel
```csharp
private ArmorModel ArmorModel { get; }
```

#### Property Value
**Type:** Global.ArmorModel

## Methods
### CheckMakeCount()
```csharp
public void CheckMakeCount()
```
Grabs and updates current count and max count from [InventoryModel](/api/Global/Model/InventoryModel).

### OnEnter()
```csharp
public void OnEnter()
```
Changes the text to display buy message.

### OnExit()
```csharp
public void OnExit()
```
Changes the text to display the cost.

### SetModel(EquipmentModel)
```csharp
public override void SetModel(EquipmentModel Model)
```
Pseudo-constructor based on a more generic 'EquipmentModel'? 

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `Model` | `Global.EquipmentModel` |  |

### SetModel(EquipmentTypeInfo)
```csharp
public override void SetModel(EquipmentTypeInfo info)
```
Pseudo-constructor from EquipmentTypeInfo?

#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `info` | `Global.EquipmentTypeInfo` |  |

## Inherited Members
[ActiveControl](/api/CreatureInfo/EquipSlot#activecontrol), [BlockControl](/api/CreatureInfo/EquipSlot#blockcontrol), [BlockText](/api/CreatureInfo/EquipSlot#blocktext), [Title](/api/CreatureInfo/EquipSlot#title), [Outlook](/api/CreatureInfo/EquipSlot#outlook), [ItemName](/api/CreatureInfo/EquipSlot#itemname), [_info](/api/CreatureInfo/EquipSlot#info), [_model](/api/CreatureInfo/EquipSlot#model), [makeInfo](/api/CreatureInfo/EquipSlot#makeinfo), [CheckBlocked(bool, int)](/api/CreatureInfo/EquipSlot#checkblocked-bool-int), [NoData(string)](/api/CreatureInfo/EquipSlot#nodata-string), [CheckOpened(out int)](/api/CreatureInfo/EquipSlot#checkopened-out-int), [SetEquipInfo(CreatureEquipmentMakeInfo)](/api/CreatureInfo/EquipSlot#setequipinfo-creatureequipmentmakeinfo), [Info](/api/CreatureInfo/EquipSlot#info), [Model](/api/CreatureInfo/EquipSlot#model), [MakeInfo](/api/CreatureInfo/EquipSlot#makeinfo), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)



