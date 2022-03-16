local player = game.Players.LocalPlayer local mouse = player:GetMouse() bind = "keybind" mouse.KeyDown:connect(function(key) if key == bind then player.Character.Head:Destroy() end end)
