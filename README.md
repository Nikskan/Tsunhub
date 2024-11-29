-- Auto Farm Script for Blox Fruits
local Player = game.Players.LocalPlayer
local Character = Player.Character or Player.CharacterAdded:Wait()
local Humanoid = Character:WaitForChild("Humanoid")
local AutoFarm = true

-- Start the Auto Farm loop
while AutoFarm do
    for _,enemy in pairs(workspace.Enemies:GetChildren()) do
        -- Attack logic goes here
        -- You can target specific enemies, or automate your attacks
    end
    wait(1)  -- Delay between actions
end
