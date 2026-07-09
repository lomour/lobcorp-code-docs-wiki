---
uid: Global.LumberjackAnim
canonical_path: /api/Global/Creature/LumberjackAnim
---
# Class LumberjackAnim
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class LumberjackAnim : CreatureAnimEventCalled, IAnimatorEventCalled
```
> This section may have incomplete or incorrect information.
{.is-warning}


Animation handler for [Warm-Hearted Woodsman](/api/Global/Abnormalities/Warm-Hearted-Woodsman/Lumberjack).




## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [Object](#) → [Component](#) → [Behaviour](#) → [MonoBehaviour](#) → [AnimScript](/api/Global/Abnormalities/CreatureAnimEventCalled) → LumberjackAnim

## Implements
[IAnimatorEventCalled](/api/Global/Animation/IAnimatorEventCalled)

## Constructors
### LumberjackAnim()
```csharp
public LumberjackAnim()
```

## Fields
### _effect_Heal
```csharp
private const string _effect_Heal = "Lumberjack_Heal"
```


#### Field Value
**Type:** System.String

### _effect_HeartAttack
```csharp
private const string _effect_HeartAttack = "Lumberjack_HeartAttack"
```


#### Field Value
**Type:** System.String

### _effect_HeartBreak
```csharp
private const string _effect_HeartBreak = "Lumberjack_HeartBreak"
```


#### Field Value
**Type:** System.String

### _effect_Smash
```csharp
private const string _effect_Smash = "Lumberjack_Smash"
```


#### Field Value
**Type:** System.String

### _effectSrc
```csharp
private const string _effectSrc = "Effect/Creature/Lumberjack/"
```


#### Field Value
**Type:** System.String

### _healFixedPosition
```csharp
private readonly Vector3 _healFixedPosition
```


#### Field Value
**Type:** UnityEngine.Vector3

### _heartAttackFixedPosition
```csharp
private readonly Vector3 _heartAttackFixedPosition
```


#### Field Value
**Type:** UnityEngine.Vector3

### _heartBreakFixedPosition
```csharp
private readonly Vector3 _heartBreakFixedPosition
```


#### Field Value
**Type:** UnityEngine.Vector3

### _module
```csharp
private SpineOptimizerModule _module
```


#### Field Value
**Type:** Global.SpineOptimizerModule

### _smashFixedPosition
```csharp
private readonly Vector3 _smashFixedPosition
```


#### Field Value
**Type:** UnityEngine.Vector3

### filterAnim
```csharp
public Animator filterAnim
```


#### Field Value
**Type:** UnityEngine.Animator

### script
```csharp
private Lumberjack script
```


#### Field Value
**Type:** Global.Lumberjack

## Methods
### AttackDamageTimeCalled()
```csharp
public override void AttackDamageTimeCalled()
```


### AttackEnd()
```csharp
private void AttackEnd()
```


### EscapeReady(bool)
```csharp
public void EscapeReady(bool start)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `start` | `System.Boolean` |  |

### HasDeadMotion()
```csharp
public override bool HasDeadMotion()
```


#### Returns
**Type:** System.Boolean

### Heal()
```csharp
private void Heal()
```


### HeartBreak()
```csharp
private void HeartBreak()
```


### Init()
```csharp
public void Init()
```


### IsAttacking()
```csharp
public bool IsAttacking()
```


#### Returns
**Type:** System.Boolean

### IsLooting()
```csharp
public bool IsLooting()
```


#### Returns
**Type:** System.Boolean

### KillAgentInRoom()
```csharp
private void KillAgentInRoom()
```


### Loot()
```csharp
private void Loot()
```


### LootingEnd()
```csharp
private void LootingEnd()
```


### MakeEffect(string, Vector3)
```csharp
private GameObject MakeEffect(string src, Vector3 fixedPosition)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |
| `fixedPosition` | `UnityEngine.Vector3` |  |

#### Returns
**Type:** UnityEngine.GameObject

### OnAttackStart(int)
```csharp
public void OnAttackStart(int pattern)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `pattern` | `System.Int32` |  |

### OnCalled(int)
```csharp
public override void OnCalled(int i)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### OnLootStart()
```csharp
public void OnLootStart()
```


### OnMove()
```csharp
public void OnMove()
```


### OnStop()
```csharp
public void OnStop()
```


### PlayDeadMotion()
```csharp
public override void PlayDeadMotion()
```


### SetFilter(bool)
```csharp
public void SetFilter(bool active)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `active` | `System.Boolean` |  |

### SetScript(Lumberjack)
```csharp
public void SetScript(Lumberjack script)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `script` | `Global.Lumberjack` |  |

### SpecialDamageTimeCalled()
```csharp
private void SpecialDamageTimeCalled()
```


### SpecialSmashTimeCalled()
```csharp
private void SpecialSmashTimeCalled()
```


### Update()
```csharp
private void Update()
```


## Inherited Members
[Move()](/api/Global/Animation/AnimScript#animator), [motionDelay](/api/Global/Animation/AnimScript#motiondelay), [defaultSpeed](/api/Global/Animation/AnimScript#defaultspeed), [FixedUpdate()](/api/Global/Animation/AnimScript#fixedupdate), [SetSpeed(float)](/api/Global/Animation/AnimScript#setspeed-float), [Internal_CancelInvokeAll()](#), [Internal_IsInvokingAll()](#), [Invoke(string, float)](https://learn.microsoft.com/dotnet/api/system.string), [InvokeRepeating(string, float, float)](https://learn.microsoft.com/dotnet/api/system.string), [CancelInvoke()](#), [CancelInvoke(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking(string)](https://learn.microsoft.com/dotnet/api/system.string), [IsInvoking()](#), [StartCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine_Auto_Internal(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StartCoroutine(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [StartCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(string)](https://learn.microsoft.com/dotnet/api/system.string), [StopCoroutine(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine(Coroutine)](#), [StopCoroutineViaEnumerator_Auto(IEnumerator)](https://learn.microsoft.com/dotnet/api/system.collections.ienumerator), [StopCoroutine_Auto(Coroutine)](#), [StopAllCoroutines()](#), [print(object)](https://learn.microsoft.com/dotnet/api/system.object), [GetScriptClassName()](#), [useGUILayout](#), [enabled](#), [isActiveAndEnabled](#), [GetComponent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentFastPath(Type, IntPtr)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponent<T>()](#), [GetComponent(string)](https://learn.microsoft.com/dotnet/api/system.string), [GetComponentInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInChildren<T>()](#), [GetComponentInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInChildren<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInChildren<T>()](#), [GetComponentsInChildren<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponentInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentInParent<T>()](#), [GetComponentsInParent(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent(Type, bool)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsInParent<T>(bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>(bool, List<T>)](https://learn.microsoft.com/dotnet/api/system.boolean), [GetComponentsInParent<T>()](#), [GetComponents(Type)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponentsForListInternal(Type, object)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents(Type, List<Component>)](https://learn.microsoft.com/dotnet/api/system.type), [GetComponents<T>(List<T>)](https://learn.microsoft.com/dotnet/api/system.collections.generic.list-1), [GetComponents<T>()](#), [CompareTag(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessageUpwards(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [SendMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, object)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string)](https://learn.microsoft.com/dotnet/api/system.string), [BroadcastMessage(string, SendMessageOptions)](https://learn.microsoft.com/dotnet/api/system.string), [transform](#), [gameObject](#), [tag](#), [m_CachedPtr](#), [OffsetOfInstanceIDInCPlusPlusObject](#), [Internal_CloneSingle(Object)](#), [Internal_CloneSingleWithParent(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Internal_InstantiateSingle(Object, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingle(Object, ref Vector3, ref Quaternion)](#), [Internal_InstantiateSingleWithParent(Object, Transform, Vector3, Quaternion)](#), [INTERNAL_CALL_Internal_InstantiateSingleWithParent(Object, Transform, ref Vector3, ref Quaternion)](#), [GetOffsetOfInstanceIDInCPlusPlusObject()](#), [EnsureRunningOnMainThread()](#), [Destroy(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [Destroy(Object)](#), [DestroyImmediate(Object, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [DestroyImmediate(Object)](#), [FindObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [DontDestroyOnLoad(Object)](#), [DestroyObject(Object, float)](https://learn.microsoft.com/dotnet/api/system.single), [DestroyObject(Object)](#), [FindSceneObjectsOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeIncludingAssets(Type)](https://learn.microsoft.com/dotnet/api/system.type), [FindObjectsOfTypeAll(Type)](https://learn.microsoft.com/dotnet/api/system.type), [ToString()](#), [DoesObjectWithInstanceIDExist(int)](https://learn.microsoft.com/dotnet/api/system.int32), [GetInstanceID()](#), [GetHashCode()](#), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object), [CompareBaseObjects(Object, Object)](#), [IsNativeObjectAlive(Object)](#), [GetCachedPtr()](#), [Instantiate(Object, Vector3, Quaternion)](#), [Instantiate(Object, Vector3, Quaternion, Transform)](#), [Instantiate(Object)](#), [Instantiate(Object, Transform)](#), [Instantiate(Object, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [Instantiate<T>(T)](#), [Instantiate<T>(T, Vector3, Quaternion)](#), [Instantiate<T>(T, Vector3, Quaternion, Transform)](#), [Instantiate<T>(T, Transform)](#), [Instantiate<T>(T, Transform, bool)](https://learn.microsoft.com/dotnet/api/system.boolean), [FindObjectsOfType<T>()](#), [FindObjectOfType<T>()](#), [CheckNullArgument(object, string)](https://learn.microsoft.com/dotnet/api/system.object), [FindObjectOfType(Type)](https://learn.microsoft.com/dotnet/api/system.type), [name](#), [hideFlags](#), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)







