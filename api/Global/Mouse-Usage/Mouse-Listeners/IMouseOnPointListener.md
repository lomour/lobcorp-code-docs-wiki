---
uid: Global.IMouseOnPointListener
canonical_path: /api/Global/Misc/IMouseOnPointListener
---
# Interface IMouseOnPointListener
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public interface IMouseOnPointListener
```
> This section may have incomplete or incorrect information.
{.is-warning}

Interface for things which react to being hovered over by the cursor.

Implemented by [AgentUnit](/api/Global/Map/Rooms-and-Hallways/PassageObject).

Used by [UnitMouseEventManager](/api/Global/Mouse-Usage/Mouse-Events/UnitMouseEventManager).


#### Methods
	bool HasPointListener()
	void OnPointEnter()
	void OnPointExit()


## Methods
### HasPointListener()
```csharp
bool HasPointListener()
```


#### Returns
**Type:** System.Boolean

### OnPointEnter()
```csharp
void OnPointEnter()
```


### OnPointExit()
```csharp
void OnPointExit()
```








