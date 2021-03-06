### [UnrealEngine.Framework](./UnrealEngine-Framework.md 'UnrealEngine.Framework').[World](./World.md 'UnrealEngine.Framework.World')
## World.SetOnActorBeginOverlapCallback(UnrealEngine.Framework.ActorOverlapDelegate) Method
Sets the static callback function that is called when actors start overlapping  
```csharp
public static void SetOnActorBeginOverlapCallback(UnrealEngine.Framework.ActorOverlapDelegate callback);
```
#### Parameters
<a name='UnrealEngine-Framework-World-SetOnActorBeginOverlapCallback(UnrealEngine-Framework-ActorOverlapDelegate)-callback'></a>
`callback` [ActorOverlapDelegate(UnrealEngine.Framework.ObjectReference, UnrealEngine.Framework.ObjectReference)](./ActorOverlapDelegate(ObjectReference_ObjectReference).md 'UnrealEngine.Framework.ActorOverlapDelegate(UnrealEngine.Framework.ObjectReference, UnrealEngine.Framework.ObjectReference)')  
The static function to call when an actor start overlapping with another one  
  
#### Exceptions
[System.ArgumentException](https://docs.microsoft.com/en-us/dotnet/api/System.ArgumentException 'System.ArgumentException')  
Thrown if [callback](#UnrealEngine-Framework-World-SetOnActorBeginOverlapCallback(UnrealEngine-Framework-ActorOverlapDelegate)-callback 'UnrealEngine.Framework.World.SetOnActorBeginOverlapCallback(UnrealEngine.Framework.ActorOverlapDelegate).callback') is not static  
