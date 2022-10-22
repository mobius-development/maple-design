```lua
local Maple = require(path.to.module)
local App, Text = Maple.App, Maple.TextLabel

local Model = App({
    Text("Hello, Maple!")
})

Model:mount(game.Players.LocalPlayer.PlayerGui);
```
