---
uid: Global.CreatureSpecialDamageTable
canonical_path: /api/Global/Misc/CreatureSpecialDamageTable
---
# Class CreatureSpecialDamageTable
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureSpecialDamageTable
```
> This section may have incomplete or incorrect information.
{.is-warning}

Holds the damage values of abnormality damage outside of work damage (e.g., breaching attack damages). Only used by some abnormalities:
- [Big and Will be Bad Wolf](/api/Global/Abnormalities/Big-and-Will-be-Bad-Wolf/BigBadWolf)
- [Fragment of the Universe](/api/Global/Abnormalities/Fragment-of-the-Universe/Cosmos)
- [Laetitia's friend](/api/Global/Abnormalities/Laetitia/LittleWitchMonster)
- [Green Dawn](/api/Global/Abnormalities/Ordeals/Green-Ordeals/Green-Dawn/MachineDawn)
- [Little Red Riding Hooded Mercenary](/api/Global/Abnormalities/Little-Red-Riding-Hooded-Mercenary/RedHood)
- [The Silent Orchestra](/api/Global/Abnormalities/The-Silent-Orchestra/SilentOrchestra)
- [Forsaken Murderer](/api/Global/Abnormalities/Forsaken-Murderer/StraitJacket)



## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → CreatureSpecialDamageTable

## Constructors
### CreatureSpecialDamageTable()
```csharp
public CreatureSpecialDamageTable()
```

## Fields
### _specialWeaponInfos
```csharp
private Dictionary<string, EquipmentTypeInfo> _specialWeaponInfos
```


#### Field Value
**Type:** System.Collections.Generic.Dictionary{System.String,EquipmentTypeInfo}

## Methods
### GetList()
```csharp
public List<DamageInfo> GetList()
```


#### Returns
**Type:** System.Collections.Generic.List{DamageInfo}

### GetSpecialDamage(string)
```csharp
public DamageInfo GetSpecialDamage(string id)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.String` |  |

#### Returns
**Type:** Global.DamageInfo

### GetSpecialWeapon(string)
```csharp
public EquipmentTypeInfo GetSpecialWeapon(string id)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.String` |  |

#### Returns
**Type:** Global.EquipmentTypeInfo

### Init(Dictionary<string, EquipmentTypeInfo>)
```csharp
public void Init(Dictionary<string, EquipmentTypeInfo> infos)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `infos` | `System.Collections.Generic.Dictionary{System.String,EquipmentTypeInfo}` |  |

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)









