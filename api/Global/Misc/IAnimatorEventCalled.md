---
uid: Global.IAnimatorEventCalled
canonical_path: /api/Global/Misc/IAnimatorEventCalled
---
# Interface IAnimatorEventCalled
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public interface IAnimatorEventCalled
```
> This section may have incomplete or incorrect information.
{.is-warning}

Interface representing something which should be animated when certain events are called.

Used *mainly* by abnormality animation handlers, but also by [agents](/api/Global/Misc/AgentAnim) and (frustratingly) some UI elements.

#### Methods
	OnCalled
	OnCalled(int i)
	AgentReset
	SimpleReset
	AnimatorEventInit
	CreatureAnimCall(int i, CreatureBase script)
	AttackCalled(int i)
	AttackDamageTimeCalled
	SoundMake(string src)

(Say what each of these do. AttackCalled is when this thing attacks. (??))


## Methods
### AgentReset()
```csharp
void AgentReset()
```


### AnimatorEventInit()
```csharp
void AnimatorEventInit()
```


### AttackCalled(int)
```csharp
void AttackCalled(int i)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### AttackDamageTimeCalled()
```csharp
void AttackDamageTimeCalled()
```


### CreatureAnimCall(int, CreatureBase)
```csharp
void CreatureAnimCall(int i, CreatureBase script)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |
| `script` | `Global.CreatureBase` |  |

### OnCalled()
```csharp
void OnCalled()
```


### OnCalled(int)
```csharp
void OnCalled(int i)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `i` | `System.Int32` |  |

### SimpleReset()
```csharp
void SimpleReset()
```


### SoundMake(string)
```csharp
void SoundMake(string src)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `src` | `System.String` |  |



