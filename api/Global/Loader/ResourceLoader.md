---
uid: Global.ResourceLoader
canonical_path: /api/Global/Loader/ResourceLoader
---
# Class ResourceLoader
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class ResourceLoader
```
> This section may have incomplete or incorrect information.
{.is-warning}

> This class is not used.
{.is-info}

Unused helper for loading some sprites and prefabs.


## Methods
#### private static string GetLowQualityPath(string src)
Replaces 'filename' in the path with 'SD/filename' to get a lower quality version of the file.
#### public static Sprite LoadSprite(string src)
Returns the sprite (or a lower quality version of the sprite if the quality settings are low). Uses the Unity Resources class.
#### public static GameObject LoadPrefab(string src)
Returns the prefab (or a lower quality version of the prefab if the quality settings are low). Uses [Prefab](/api/Global/Misc/Prefab).


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → ResourceLoader

## Constructors
### ResourceLoader()
```csharp
public ResourceLoader()
```

## Methods
### GetLowQualityPath(string)
```csharp
private static string GetLowQualityPath(string src)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

#### Returns
**Type:** System.String

### LoadPrefab(string)
```csharp
public static GameObject LoadPrefab(string src)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

#### Returns
**Type:** UnityEngine.GameObject

### LoadSprite(string)
```csharp
public static Sprite LoadSprite(string src)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |

#### Returns
**Type:** UnityEngine.Sprite

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)



