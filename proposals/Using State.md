```lua
local Maple = require(path.to.module)
local App, Text, useState = Maple.App, Maple.TextLabel, Maple.useState
local State = useState("Hello, world")

local Model = App({
    Text(State:get())
})

Model
    :render()
    :mount(game.Players.LocalPlayer.PlayerGui);
```