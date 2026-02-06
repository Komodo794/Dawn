# Dawn
cool
```lua
local Dawn = script.Parent["DawnEngine"]
Dawn["CoreGui"].Parent = game["PlayerGUI"]
Dawn["Frontend"].Parent = game["PlayerGUI"]
Dawn = require(Dawn)

Dawn:Teams({
    {"Bright red", Color.New(1, 0, 0)},
    {"Bright blue", Color.New(0, 0, 1)},
    {"Bright green", Color.New(0, 1, 0)},
})
Dawn:SetSpawn("Bright red", {game["Workspace"]["Red"]})
Dawn:SetSpawn("Bright blue", {game["Workspace"]["Blue"]})
Dawn:SetSpawn("Bright green", {game["Workspace"]["Green"]})
Dawn:Init()
```
