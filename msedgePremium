local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "[🎃HALLOWEEN🎃] msedge premium script - Slap Battles👏", HidePremium = false, IntroText = "[🎃HALLOWEEN🎃] msedge premium script - Slap Battles👏", SaveConfig = true, ConfigFolder = "msedge farm"})


-- values/main running scripts
_G.AutoSlapAll = true

function bobMorph()
	local char = game.Players.LocalPlayer.Character
	
	for _, part in pairs(char:GetDescendants()) do
		if part:IsA("Part") then
			part.Color = Color3.fromRGB(0, 0, 0)
			part.Material = "Neon"
		end
	end
	
	for _, accessory in pairs(char:GetDescendants()) do
		if accessory:IsA("Accessory") then
			accessory:Destroy()
		end
	end
	
	char.Head.Mesh.MeshType = "Head"
	char.Head.Mesh.Scale = Vector3.new(1.25, 1.25, 1.25)
	char.Head.face.Texture = "rbxassetid://4114747358"
	char.Head.Nametag.TextLabel.Text = "b̷̺͔̘̈́ō̸͚̙͛͌̀̈̇b̴͍͈̲̱̌̿̊̐͜͠͝"
	
	end


-- tabs
local LimitedTab = Window:MakeTab({
	Name = "🔴 - LIMITED!",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})


local HalloweenTab = Window:MakeTab({
	Name = "🎃 - Halloween",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local SlapTab = Window:MakeTab({
	Name = "👏 - Slap Farm",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local GuiTab = Window:MakeTab({
	Name = "⚫ - GUI",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

-- buttons
HalloweenTab:AddButton({
	Name = "Candy Farm",
	Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/coolperson-sudo/SlapBattles/refs/heads/main/CandyFarm"))()
  	end    
})

GuiTab:AddButton({
	Name = "Destroy GUI",
	Callback = function()
        OrionLib:Destroy()
  	end    
})

GuiTab:AddButton({
	Name = "Rejoin",
	Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Jelly-plays/Rejoin-script/main/obf_L744By559M18BbuseSG6en8r1zL31daK9060LV7WyvmS4bQp92aONWfwRE36FdcZ.lua.txt"))();
  	end    
})

LimitedTab:AddButton({
	Name = "Become Bob",
	Callback = function()
    bobMorph()
end
})

-- labels
HalloweenTab:AddLabel("|------------------- Poltergeist -------------------|")
LimitedTab:AddLabel("THIS ONLY STAYS UNTIL THE NEW MONTH! (some things are visual)")

-- toggles
HalloweenTab:AddToggle({
	Name = "Auto Slap Boss/Zombies",
	Default = false,
	Callback = function(Value)
		_G.AutoSlapAll = Value
while _G.AutoSlapAll do
for i,v in pairs(workspace.Enemies:GetChildren()) do
if v:FindFirstChild("HumanoidRootPart") then
game:GetService("ReplicatedStorage").Remotes.GeneralHit:FireServer(v:FindFirstChild("HumanoidRootPart"))
end
end
task.wait(0.15)
end
	end    
})

-- poltergeist buttons
HalloweenTab:AddButton({
	Name = "Join Poltergeist Place",
	Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/coolperson-sudo/SlapBattles/refs/heads/main/PoltergeistPlace"))()
  	end    
})
