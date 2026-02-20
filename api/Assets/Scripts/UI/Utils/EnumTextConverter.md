 
 
---
uid: Assets.Scripts.UI.Utils.EnumTextConverter
canonical_path: /api/Assets/Scripts/UI/Utils/EnumTextConverter
---

# Class EnumTextConverter
**Namespace:** Assets . Scripts . UI . [Utils](/api/Assets/Scripts/UI/Utils)
**Assembly:** Assembly-CSharp.dll

```csharp
public static class EnumTextConverter
```
> This section may have incomplete or incorrect information.
{.is-warning}

Convert certain enums to readable text, and vice versa.

Vulnerabilities -> text, damage types -> text, and damage type text -> damage type enum.


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → EnumTextConverter

## Methods

### GetDefenseType(Type)
```csharp
public static string GetDefenseType(DefenseInfo.Type type)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.DefenseInfo.Type` |  |

#### Returns
**Type:** System.String

### GetRwbpType(RwbpType)
```csharp
public static string GetRwbpType(RwbpType type)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `type` | `Global.RwbpType` |  |

#### Returns
**Type:** System.String

### GetRwbpType(string)
```csharp
public static RwbpType GetRwbpType(string type)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `type` | `System.String` |  |

#### Returns
**Type:** Global.RwbpType

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)


