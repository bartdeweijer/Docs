# Player Hooks

## OnPlayerConnected

``` csharp
void OnPlayerConnected(ClientInfo info)
{
    Puts("OnPlayerConnected works!");
}
```

``` lua
function PLUGIN:OnPlayerConnected(player)
    print("OnPlayerConnected works!")
end
```

``` coffeescript
OnPlayerConnected: (player) =>
    print "OnPlayerConnected works!"
```

``` javascript
OnPlayerConnected: function(player) {
    print("OnPlayerConnected works!");
}
```

``` python
def OnPlayerConnected(self, player):
    print "OnPlayerConnected works!"
```

 * Called when the player has connected to the server
 * No return behavior

## OnPlayerDisconnected

``` csharp
void OnPlayerDisconnected(ClientInfo info)
{
    Puts("OnPlayerDisconnected works!");
}
```

``` lua
function PLUGIN:OnPlayerDisconnected(player)
    print("OnPlayerDisconnected works!")
end
```

``` coffeescript
OnPlayerDisconnected: (player) =>
    print "OnPlayerDisconnected works!"
```

``` javascript
OnPlayerDisconnected: function(player) {
    print("OnPlayerDisconnected works!");
}
```

``` python
def OnPlayerDisconnected(self, player):
    print "OnPlayerDisconnected works!"
```

 * Called when the player has disconnected from the server
 * No return behavior

## OnPlayerChat

``` csharp
void OnPlayerChat(string message, string name)
{
    Puts("OnPlayerChat works!");
}
```

``` lua
function PLUGIN:OnPlayerChat(message, name)
    print("OnPlayerChat works!")
end
```

``` coffeescript
OnPlayerChat: (message, name) =>
    print "OnPlayerConnected works!"
```

``` javascript
OnPlayerChat: function(message, name) {
    print("OnPlayerChat works!");
}
```

``` python
def OnPlayerChat(self, message, name):
    print "OnPlayerChat works!"
```

 * Called when the player sends chat to the server
 * No return behavior

## OnPlayerRespawned

``` csharp
void OnPlayerRespawned(ClientInfo info, string reason)
{
    Puts("OnPlayerRespawned works!");
}
```

``` lua
function PLUGIN:OnPlayerRespawned(client, reason)
    print("OnPlayerRespawned works!")
end
```

``` coffeescript
OnPlayerRespawned: (client, reason) =>
    print "OnPlayerRespawned works!"
```

``` javascript
OnPlayerRespawned: function(client, reason) {
    print("OnPlayerRespawned works!");
}
```

``` python
def OnPlayerRespawned(self, client, reason):
    print "OnPlayerRespawned works!"
```

 * Called when the player has respawned
 * No return behavior

## OnExperienceGained

``` csharp
void OnExperienceGained(ClientInfo info, uint exp)
{
    Puts("OnExperienceGained works!");
}
```

``` lua
function PLUGIN:OnExperienceGained(client, exp)
    print("OnExperienceGained works!")
end
```

``` coffeescript
OnExperienceGained: (client, exp) =>
    print "OnExperienceGained works!"
```

``` javascript
OnExperienceGained: function(client, exp) {
    print("OnExperienceGained works!");
}
```

``` python
def OnExperienceGained(self, client, exp):
    print "OnExperienceGained works!"
```

 * Called when the player has gained experience
 * No return behavior
