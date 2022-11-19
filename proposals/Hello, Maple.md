```lua
local Maple = require(path.to.module)
local App, Text = Maple.App, Maple.Text

local Model = App({
    HelloWorld = Text("Hello, world")
})

Model.mount(game.Players.LocalPlayer.PlayerGui)
```
