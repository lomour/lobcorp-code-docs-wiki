 
 
---
uid: CreatureCameraUtil.CreatureCameraUtil
canonical_path: /api/CreatureCameraUtil/CreatureCameraUtil
---

# Class CreatureCameraUtil
**Namespace:** [CreatureCameraUtil](/api/CreatureCameraUtil)
**Assembly:** Assembly-CSharp.dll

```csharp
public class CreatureCameraUtil
```
> This section may have incomplete or incorrect information.
{.is-warning}

Contains a target (unused) and an [inspector](/api/CreatureCameraUtil/CreatureCameraUtil_Inspector), which apparently can tell if something is being rendered. It also has a check for being enabled, and modes for ignoring the orthogonal view mode.

[LookAtMe](/api/Global/Misc/LookAtMe) uses it, but I can't find where the inspectors are actually assigned values...


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → CreatureCameraUtil

## Constructors

### CreatureCameraUtil(UnitModel, CreatureCameraUtil_Inspector)
```csharp
public CreatureCameraUtil(UnitModel target, CreatureCameraUtil_Inspector inspector)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.UnitModel` |  |
| `inspector` | `CreatureCameraUtil.CreatureCameraUtil_Inspector` |  |

## Fields

### _isEnabled
```csharp
private bool _isEnabled
```


#### Field Value
**Type:** System.Boolean

### inspector
```csharp
public CreatureCameraUtil_Inspector inspector
```


#### Field Value
**Type:** CreatureCameraUtil.CreatureCameraUtil_Inspector

### target
```csharp
public UnitModel target
```


#### Field Value
**Type:** Global.UnitModel

## Properties

### IsEnabled
```csharp
public bool IsEnabled { get; }
```

#### Property Value
**Type:** System.Boolean

## Methods

### CheckCamera()
```csharp
public bool CheckCamera()
```


#### Returns
**Type:** System.Boolean

### CheckIgnoreOrtho()
```csharp
public bool CheckIgnoreOrtho()
```


#### Returns
**Type:** System.Boolean

### GetCamera()
```csharp
public static Camera GetCamera()
```


#### Returns
**Type:** UnityEngine.Camera

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)


