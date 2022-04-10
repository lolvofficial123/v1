# v1

for i,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
    local bp = Instance.new("BodyPosition")
    v.Parent = game.Players.LocalPlayer.Character
    wait(0.5)
    bp.Parent = v.Handle
    v.Handle.Mesh:Destroy()
    bp.Position = game.Players.LocalPlayer.Character.Head.Position
    v.Handle.Parent = workspace
    
    
    
    local counter = 1
    spawn(function()
        while wait() do
            if game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.E) then
                bp.Position = game.Players.LocalPlayer:GetMouse().hit.p
                print('ok')
            else
            counter = counter + 1
            bp.Position = game.Players.LocalPlayer.Character.Head.Position + Vector3.new(0,counter,0)
            if counter == 6 then
                counter = 1
            end
            wait(0.1)
            end
        end
    end)
end
