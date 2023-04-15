wait(1)

local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Konkan pro HUB", "BloodTheme")

--TP

local Tab = Window:NewTab("Teleport")
local Section = Tab:NewSection("Teleport Island")

Section:NewButton("Lobby", "ButtonInfo", function()
wait(0.2)
local targetPosition = Vector3.new(1097.3790283203125, 16.299402236938477, 1426.59326171875) -- ที่อยู่ของมึง
local distance = (targetPosition - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
local speed = 350 -- หน่วยคือ studs/s
local duration = distance / speed
local tweenInfo = TweenInfo.new(duration, Enum.EasingStyle.Linear)
local tween = game:GetService("TweenService"):Create(game.Players.LocalPlayer.Character.HumanoidRootPart, tweenInfo, {CFrame = CFrame.new(targetPosition)})
tween:Play()
end)

Section:NewButton("Small Marine", "ButtonInfo", function()
wait(0.2)
local targetPosition = Vector3.new(-2539.1494140625, 32.99635696411133, 2042.819580078125) -- ที่อยู่ของมึง
local distance = (targetPosition - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
local speed = 350 -- หน่วยคือ studs/s
local duration = distance / speed
local tweenInfo = TweenInfo.new(duration, Enum.EasingStyle.Linear)
local tween = game:GetService("TweenService"):Create(game.Players.LocalPlayer.Character.HumanoidRootPart, tweenInfo, {CFrame = CFrame.new(targetPosition)})
tween:Play()
end)

Section:NewButton("Monkey", "ButtonInfo", function()
wait(0.2)
local targetPosition = Vector3.new(-1610.2681884765625, 36.87788009643555, 150.04042053222656) -- ที่อยู่ของมึง
local distance = (targetPosition - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
local speed = 350 -- หน่วยคือ studs/s
local duration = distance / speed
local tweenInfo = TweenInfo.new(duration, Enum.EasingStyle.Linear)
local tween = game:GetService("TweenService"):Create(game.Players.LocalPlayer.Character.HumanoidRootPart, tweenInfo, {CFrame = CFrame.new(targetPosition)})
tween:Play()
end)

Section:NewButton("Monkey2", "ButtonInfo", function()
wait(0.2)
local targetPosition = Vector3.new(-1269.5697021484375, 6.305151462554932, -495.5296936035156) -- ที่อยู่ของมึง
local distance = (targetPosition - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
local speed = 350 -- หน่วยคือ studs/s
local duration = distance / speed
local tweenInfo = TweenInfo.new(duration, Enum.EasingStyle.Linear)
local tween = game:GetService("TweenService"):Create(game.Players.LocalPlayer.Character.HumanoidRootPart, tweenInfo, {CFrame = CFrame.new(targetPosition)})
tween:Play()
end)

Section:NewButton("Colosseum", "ButtonInfo", function()
wait(0.2)
local targetPosition = Vector3.new(-1484.496826171875, 7.415125846862793, -2940.155029296875) -- ที่อยู่ของมึง
local distance = (targetPosition - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
local speed = 350 -- หน่วยคือ studs/s
local duration = distance / speed
local tweenInfo = TweenInfo.new(duration, Enum.EasingStyle.Linear)
local tween = game:GetService("TweenService"):Create(game.Players.LocalPlayer.Character.HumanoidRootPart, tweenInfo, {CFrame = CFrame.new(targetPosition)})
tween:Play()
end)

Section:NewButton("MainIsland", "ButtonInfo", function()
wait(0.2)
local targetPosition = Vector3.new(-666.2522583007812, 7.878032207489014, 1576.946044921875) -- ที่อยู่ของมึง
local distance = (targetPosition - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
local speed = 350 -- หน่วยคือ studs/s
local duration = distance / speed
local tweenInfo = TweenInfo.new(duration, Enum.EasingStyle.Linear)
local tween = game:GetService("TweenService"):Create(game.Players.LocalPlayer.Character.HumanoidRootPart, tweenInfo, {CFrame = CFrame.new(targetPosition)})
tween:Play()
end)

Section:NewButton("Desert", "ButtonInfo", function()

wait(0.2)
local targetPosition = Vector3.new(909.7342529296875, 6.594980716705322, 4139.55078125) -- ที่อยู่ของมึง
local distance = (targetPosition - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
local speed = 350 -- หน่วยคือ studs/s
local duration = distance / speed
local tweenInfo = TweenInfo.new(duration, Enum.EasingStyle.Linear)
local tween = game:GetService("TweenService"):Create(game.Players.LocalPlayer.Character.HumanoidRootPart, tweenInfo, {CFrame = CFrame.new(targetPosition)})
tween:Play()
end)

Section:NewButton("Desert2", "ButtonInfo", function()
wait(0.2)
local targetPosition = Vector3.new(1585.553955078125, 3.995598316192627, 4355.7744140625) -- ที่อยู่ของมึง
local distance = (targetPosition - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
local speed = 350 -- หน่วยคือ studs/s
local duration = distance / speed
local tweenInfo = TweenInfo.new(duration, Enum.EasingStyle.Linear)
local tween = game:GetService("TweenService"):Create(game.Players.LocalPlayer.Character.HumanoidRootPart, tweenInfo, {CFrame = CFrame.new(targetPosition)})
tween:Play()
end)

Section:NewButton("SkyArea1", "ButtonInfo", function()
wait(0.2)
local targetPosition = Vector3.new(-4850.55908203125, 717.7164306640625, -2629.68701171875) -- ที่อยู่ของมึง
local distance = (targetPosition - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
local speed = 350 -- หน่วยคือ studs/s
local duration = distance / speed
local tweenInfo = TweenInfo.new(duration, Enum.EasingStyle.Linear)
local tween = game:GetService("TweenService"):Create(game.Players.LocalPlayer.Character.HumanoidRootPart, tweenInfo, {CFrame = CFrame.new(targetPosition)})
tween:Play()
end)

Section:NewButton("SkyFloor1", "ButtonInfo", function()
wait(0.2)
local targetPosition = Vector3.new(-4955.1875, 295.74420166015625, -2906.380615234375) -- ที่อยู่ของมึง
local distance = (targetPosition - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
local speed = 350 -- หน่วยคือ studs/s
local duration = distance / speed
local tweenInfo = TweenInfo.new(duration, Enum.EasingStyle.Linear)
local tween = game:GetService("TweenService"):Create(game.Players.LocalPlayer.Character.HumanoidRootPart, tweenInfo, {CFrame = CFrame.new(targetPosition)})
tween:Play()
end)

Section:NewButton("SkyFloor2", "ButtonInfo", function()
wait(0.2)
local targetPosition = Vector3.new(-5267.94580078125, 393.07440185546875, -2204.260498046875) -- ที่อยู่ของมึง
local distance = (targetPosition - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
local speed = 350 -- หน่วยคือ studs/s
local duration = distance / speed
local tweenInfo = TweenInfo.new(duration, Enum.EasingStyle.Linear)
local tween = game:GetService("TweenService"):Create(game.Players.LocalPlayer.Character.HumanoidRootPart, tweenInfo, {CFrame = CFrame.new(targetPosition)})
tween:Play()
end)

Section:NewButton("SkyFloor3", "ButtonInfo", function()
wait(0.2)
local targetPosition = Vector3.new(-4720.01123046875, 854.1559448242188, -1941.0614013671875) -- ที่อยู่ของมึง
local distance = (targetPosition - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
local speed = 350 -- หน่วยคือ studs/s
local duration = distance / speed
local tweenInfo = TweenInfo.new(duration, Enum.EasingStyle.Linear)
local tween = game:GetService("TweenService"):Create(game.Players.LocalPlayer.Character.HumanoidRootPart, tweenInfo, {CFrame = CFrame.new(targetPosition)})
tween:Play()
end)

Section:NewButton("SkyArea2", "ButtonInfo", function()
wait(0.2)
local targetPosition = Vector3.new(-4624.740234375, 845.2070922851562, -1722.6168212890625) -- ที่อยู่ของมึง
local distance = (targetPosition - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
local speed = 350 -- หน่วยคือ studs/s
local duration = distance / speed
local tweenInfo = TweenInfo.new(duration, Enum.EasingStyle.Linear)
local tween = game:GetService("TweenService"):Create(game.Players.LocalPlayer.Character.HumanoidRootPart, tweenInfo, {CFrame = CFrame.new(targetPosition)})
tween:Play()
end)

Section:NewButton("Fishmen", "ButtonInfo", function()
wait(0.2)
local targetPosition = Vector3.new(4030.595703125, 23.5452880859375, -1830.1649169921875) -- ที่อยู่ของมึง
local distance = (targetPosition - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
local speed = 350 -- หน่วยคือ studs/s
local duration = distance / speed
local tweenInfo = TweenInfo.new(duration, Enum.EasingStyle.Linear)
local tween = game:GetService("TweenService"):Create(game.Players.LocalPlayer.Character.HumanoidRootPart, tweenInfo, {CFrame = CFrame.new(targetPosition)})
tween:Play()
end)

Section:NewButton("Ice", "ButtonInfo", function()

wait(0.2)
local targetPosition = Vector3.new(1398.2279052734375, 89.89217376708984, -1345.538330078125) -- ที่อยู่ของมึง
local distance = (targetPosition - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
local speed = 350 -- หน่วยคือ studs/s
local duration = distance / speed
local tweenInfo = TweenInfo.new(duration, Enum.EasingStyle.Linear)
local tween = game:GetService("TweenService"):Create(game.Players.LocalPlayer.Character.HumanoidRootPart, tweenInfo, {CFrame = CFrame.new(targetPosition)})
tween:Play()
end)

Section:NewButton("Bagy", "ButtonInfo", function()

wait(0.2)
local targetPosition = Vector3.new(-1085.5443115234375, 44.77781677246094, 3861.403564453125) -- ที่อยู่ของมึง
local distance = (targetPosition - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
local speed = 350 -- หน่วยคือ studs/s
local duration = distance / speed
local tweenInfo = TweenInfo.new(duration, Enum.EasingStyle.Linear)
local tween = game:GetService("TweenService"):Create(game.Players.LocalPlayer.Character.HumanoidRootPart, tweenInfo, {CFrame = CFrame.new(targetPosition)})
tween:Play()
end)

--Setting




local Tab = Window:NewTab("Mic")
local Section = Tab:NewSection("Team")

Section:NewButton("Join Pirates(15s)", "joinPirates(15s Cooldown)", function()
local args = {
    [1] = "SetTeam",
    [2] = "Pirates"
}
game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("CommF_"):InvokeServer(unpack(args))
end)

Section:NewButton("Join Marines(15s)", "joinMarines(15s Cooldown)", function()
local args = {
    [1] = "SetTeam",
    [2] = "Marines"
}
game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("CommF_"):InvokeServer(unpack(args))
end)


local Section = Tab:NewSection("MoreFunction")
Section:NewButton("infiniteyield", "AdminCommand", function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
end)
Section:NewButton("Rejoin", "RejoinSever", function()
local ts = game:GetService("TeleportService")
local p = game:GetService("Players").LocalPlayer
ts:Teleport(game.PlaceId, p)
end)



local Section = Tab:NewSection("ToggleUI")
Section:NewKeybind("ToggleUIEIEI", "ToggleUI", Enum.KeyCode.RightControl, function()
	Library:ToggleUI()
end)
