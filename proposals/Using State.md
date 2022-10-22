```lua
local Maple = require(path.to.module)
local App, Text, State = Maple.App, Maple.TextLabel, Maple.State
local State = State("Hello, world")

local Model = App({
    Text(State:get())
})

Model:mount(game.Players.LocalPlayer.PlayerGui);
```
