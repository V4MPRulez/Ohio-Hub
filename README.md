local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/bloodball/-back-ups-for-libs/main/kav"))()

local Window = Library.CreateLib("Ohio Hub", "DarkTheme")

local Tab1 = Window:NewTab("Games")

local Tab1Section = Tab:NewSection("Arsenal")

Tab1Section:NewButton("PWNER HUB", "best arsenal script", function()

    loadstring(game:HttpGet("https://raw.githubusercontent.com/Maikderninja/Maikderninja/main/PWNERHUB.lua"))();

end)

local Tab1Section = Tab:NewSection("Sword Fighting")

Tab1Section:NewButton("Best Sword fighting", "Pro", function()

    local library = loadstring(game:HttpGet(('https://raw.githubusercontent.com/bloodball/-back-ups-for-libs/main/wall%20v3')))()

local w = library:CreateWindow("Sword X") -- Creates the window

local b = w:CreateFolder("useful") -- Creates the folder(U will put here your buttons,etc)

b:Label("Useful Stuff",{

    TextSize = 25; -- Self Explaining

    TextColor = Color3.fromRGB(255,255,255); -- Self Explaining

    BgColor = Color3.fromRGB(69,69,69); -- Self Explaining

    

}) 

b:Button("Circle Reach",function()

    local ScreenGui = Instance.new("ScreenGui")

local Frame = Instance.new("Frame")

local Reach = Instance.new("TextButton")

ScreenGui.Parent = game.CoreGui

ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = ScreenGui

Frame.BorderSizePixel = 0

Frame.Position = UDim2.new(0.0809101239, 0, 0.203790441, 0)

Frame.Size = UDim2.new(0, 150, 0, 90)

Frame.Active = true

Frame.Draggable = true

Reach.Name = "cum gui by raz"

Reach.Parent = Frame

Reach.BorderSizePixel = 0

Reach.Position = UDim2.new(0, 0, 0.039088048, 0)

Reach.Size = UDim2.new(0, 143, 0, 38)

Reach.Font = Enum.Font.GothamBlack

Reach.Text = "raz's reach (click me)"

Reach.TextSize = 14.000

Reach.MouseButton1Down:connect(function()

	local sound = Instance.new("Sound")

	sound.SoundId = "rbxassetid://4771152040"

	sound.Parent = game:GetService("SoundService")

	sound:Play()

	wait()

	game.StarterGui:SetCore("SendNotification", {

		Title = "how to use this amazing reach?"; -- the title (ofc)

		Text = "equip your item first then press the button tell me if u want bigger reach or smaller imposter#4878"; -- what the text says (ofc)

		Duration = 10; -- how long the notification should in secounds

	})

	for i,v in pairs(game:GetService'Players'.LocalPlayer.Character:GetChildren()) do

		if v:isA("Tool") then

			local a = Instance.new("SelectionSphere",v.Handle)

			v.Handle.Massless = true

			v.Handle.Transparency = 0

			a.Adornee = v.Handle

			v.Handle.Size = Vector3.new(7, 7 , 7)

			local selectionBox = Instance.new("SelectionSphere",v.Handle)

			selectionBox.Adornee = v.Handle

			SurfaceSelection = 0

		end

	end

 end)

end)

b:Toggle("blizzy",function(state)

    shared.toggle = state

    loadstring(game:HttpGet("https://gist.githubusercontent.com/OptioniaI/b7326d42da50a52edf2c511533ae603d/raw/137840f68aef962c4bb6ae01009d5f7a5af4627d/blz-reach"))()

end)

b:Slider("Speed",{

    min = 10; -- min value of the slider

    max = 50; -- max value of the slider

    precise = true; -- max 2 decimals

},function(value)

    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = value

end)

b:Dropdown("Dropdown",{"A","B","C"},true,function(mob) --true/false, replaces the current title "Dropdown" with the option that t

    print(mob)

end)

b:Bind("Bind",Enum.KeyCode.C,function() --Default bind

    print("Yes")

end)

b:ColorPicker("ColorPicker",Color3.fromRGB(255,0,0),function(color) --Default color

    print(color)

end)

b:Box("Jumpower","value",function(value) -- "number" or "string"

game.Players.LocalPlayer.Character.Humanoid.JumpPower = value

end)

b:DestroyGui()

--[[

How to refresh a dropdown:

1)Create the dropdown and save it in a variable

local yourvariable = b:Dropdown("Hi",yourtable,function(a)

    print(a)

end)

2)Refresh it using the function

yourvariable:Refresh(yourtable)

How to refresh a label:

1)Create your label and save it in a variable

local yourvariable = b:Label("Pretty Useless NGL",{

    TextSize = 25; -- Self Explaining

    TextColor = Color3.fromRGB(255,255,255);

    BgColor = Color3.fromRGB(69,69,69);

})

2)Refresh it using the function

yourvariable:Refresh("Hello") It will only change the text ofc

]]

local b = w:CreateFolder("by owo uwu#4878 🥵") -- Creates the folder(U will put here your buttons,etc)

end)

local Tab1Section = Tab:NewSection("Kat script")

Tab1Section:NewButton("Kat", "Op", function()

    --Sub to Squidfan420

loadstring(game:HttpGet("https://raw.githubusercontent.com/ColdStep2/Breaking-Point-Funny-Squid-Hax/main/Breaking%20Point%20Funny%20Squid%20Hax",true))();

end)

local Tab1Section = Tab:NewSection("Starving Artists")

Tab1Section:NewButton("Starving Artist Script", "ButtonInfo", function()

    loadstring(game:HttpGet("https://raw.githubusercontent.com/Jeux45/Starving-Artist-script/main/Script", true))()

end)

local Tab1Section = Tab:NewSection("Keyboard Script")

Tab1Section:NewButton("Keyboard Script", "ButtonInfo", function()

    loadstring(game:HttpGet("https://raw.githubusercontent.com/advxzivhsjjdhxhsidifvsh/mobkeyboard/main/main.txt", true))()

 

end)

local Tab1Section = Tab:NewSection("Animation Hub")

Tab1Section:NewButton("Animations", "ButtonInfo", function()

    loadstring(game:HttpGet("https://gitlab.com/Tsuniox/lua-stuff/-/raw/master/R15GUI.lua"))()

end)

local Tab1Section = Tab:NewSection("Fps Booster")

Tab1Section:NewButton("Fps Boot", "ButtonInfo", function()

    getgenv().Settings = {

	Disabled = false,

	Scans = {

		["Amount"] = 3, -- scans entire game, laggy on some games with alot of instances

		["Cooldown"] = 30, -- cooldown between scans

		["SlowerChecks"] = true, -- less laggy scans (reccomended)

	},

	Main = {

		["RedirectRenderSteppedToHeartbeat"] = true, -- depends on game, but can give you 20-30+ fps (needs hookmetamethod)

		["Low Rendering"] = true, -- helps with performance

		["Extreme Low Rendering"] = true, -- more performance enhancing stuff

		["No Particles"] = true, -- disables particles like fire, trails, forcefields, etc.

		["No Explosions"] = true, -- disables explosions

		["Low Quality Parts"] = true, -- makes parts plastic looking, this boosts fps

		["Low Water Graphics"] = true, -- makes water ugly but helps with fps

		["Low Graphics"] = true, -- makes graphics a little worse

		["No Shadows"] = true, -- disables shadows, helps with performance

		["FPS Unlocker"] = false, -- unlocks fps, heavily reccomended

		["No Camera Effects"] = true, -- no lighting effects like sun rays and bloom

		["Fullbright"] = true, -- makes in-game world fully bright (no dark spots / shadows)

		["Limit FPS When Unfocused"] = false, -- doesnt render when you are tabbed out

		["StreamingEnabled"] = true, -- loads parts with minimal lag and network issues

	},

	Characters = {

		["No Clothes"] = false, -- clothes (shirts,pants) wont appear on characters

	},

	Images = {

		["Destroy"] = false, -- will destroy decals, makes checks slower

		["Invisible"] = false, -- will make images invisible

		["Low Detail"] = true, -- not sure if low detail works

	},

	Decals = {

		["Invisible"] = false, -- make decals invis, put this on iyw

		["Destroy"] = false, -- same as invis but it destroys it instead, slower

	},

	Meshes = {

		["Destroy"] = false, -- destroy meshes, dont reccomend having it on bc it makes checks slower

		["Remove Texture"] = true, -- makes meshes have a gray look

	},

	Textures = {

		["Destroy"] = true, -- destroy textures in game, can make some parts look bad

		["Invisible"] = false, -- makes checks faster and basically same as destroy

	},

	Players = {

		["Ignore LocalPlayer"] = false, -- ignore your character

		["Ignore Everyone"] = true, -- ignore all characters

	},

	Other = {

		["Print"] = false, -- has printconsole() support so games wont detect this

		["Notification"] = false, -- reccomend keeping this disabled, can get annoying

	}

}

loadstring(game:HttpGet("https://raw.githubusercontent.com/notxkid/fpsbooster/main/main.lua"))()

end)

local Tab1Section = Tab:NewSection("Brookhaven")

Tab1Section:NewButton("Brookhaven Ice", "ButtonInfo", function()

    loadstring(game:HttpGet("https://raw.githubusercontent.com/IceMael7/NewIceHub/main/Brookhaven"))()

end)

local Tab1Section = Tab:NewSection("Bedwars")

Tab1Section:NewButton("Vape", "ButtonInfo", function()

    loadstring(game:HttpGet("https://raw.githubusercontent.com/7GrandDadPGN/VapeV4ForRoblox/main/NewMainScript.lua", true))()

end)

Tab1Section:NewButton("Sape", "ButtonInfo", function()

    loadstring(game:HttpGet("https://raw.githubusercontent.com/vodxn/sape/main/Initiate.lua"))()

end)

local Tab1Section = Tab:NewSection("Combat Warriors")

Tab1Section:NewButton("Project hook", "ButtonInfo", function()

    loadstring(game:HttpGet("https://projecthook.xyz/scripts/free.lua"))()

end)

local Tab1Section = Tab:NewSection("Pop it tradimg")

Tab1Section:NewButton("Pop it trading", "ButtonInfo", function()

    loadstring(game:HttpGet("https://raw.githubusercontent.com/Vcsk/AstralHub/main/Main.lua", true))()

end)

Tab1Section:NewButton("Pop it", "ButtonInfo", function()

    loadstring(game:HttpGet("https://raw.githubusercontent.com/Balligusapos/Balligusapos/main/robloxresult-obfuscated"))()

end)

local Tab1Section = Tab:NewSection("Survive the killers")

Tab1Section:NewButton("Survive the killers script", "ButtonInfo", function()

    loadstring(game:HttpGet('https://pastebin.com/raw/TtdvYAKU'))()

end)

local Tab1Section = Tab:NewSection("Sypase x script")

Tab1Section:NewButton("Synpase", "ButtonInfo", function()

    loadstring(game:HttpGet("https://pastebin.com/raw/tWGxhNq0"))()

end)

local Tab1Section = Tab:NewSection("Ragdoll")

Tab1Section:NewButton("Ragdoll Engine script", "ButtonInfo", function()

    loadstring(game:HttpGet('https://raw.githubusercontent.com/martinelcrac/cryptonichub/main/Ragdollengine.lua'))()

end)

local Tab2 = Window:NewTab("Universal Scripts")

local Tab2Section = Tab:NewSection("HitBox")

Section:NewButton("Hitbox Script", "ButtonInfo", function()

    _G.HeadSize = 20

_G.Disabled = true

game:GetService('RunService').RenderStepped:connect(function()

if _G.Disabled then

for i,v in next, game:GetService('Players'):GetPlayers() do

if v.Name ~= game:GetService('Players').LocalPlayer.Name then

pcall(function()

v.Character.HumanoidRootPart.Size = Vector3.new(_G.HeadSize,_G.HeadSize,_G.HeadSize)

v.Character.HumanoidRootPart.Transparency = 0.7

v.Character.HumanoidRootPart.BrickColor = BrickColor.new("Really blue")

v.Character.HumanoidRootPart.Material = "Neon"

v.Character.HumanoidRootPart.CanCollide = false

end)

end

end

end

end)

end)

local Tab2Section = Tab:NewSection("Aimlock")

Tab2Section:NewButton("Aimlock Universal", "ButtonInfo", function()

    local Camera = game:GetService("Workspace").CurrentCamera local Players = game:GetService("Players") local LocalPlayer = game:GetService("Players").LocalPlayer local function GetClosestPlayer() local ClosestPlayer = nil local FarthestDistance = math.huge for i, v in pairs(Players.GetPlayers(Players)) do if v ~= LocalPlayer and v.Character and v.Character.FindFirstChild(v.Character, "HumanoidRootPart") then local DistanceFromPlayer = (LocalPlayer.Character.HumanoidRootPart.Position - v.Character.HumanoidRootPart.Position).Magnitude if DistanceFromPlayer < FarthestDistance then FarthestDistance = DistanceFromPlayer ClosestPlayer = v end end end if ClosestPlayer then return ClosestPlayer end end local GameMetaTable = getrawmetatable(game) local OldGameMetaTableNamecall = GameMetaTable.__namecall setreadonly(GameMetaTable, false) GameMetaTable.__namecall = newcclosure(function(object, ...) local NamecallMethod = getnamecallmethod() local Arguments = {...} if tostring(NamecallMethod) == "FindPartOnRayWithIgnoreList" then local ClosestPlayer = GetClosestPlayer() if ClosestPlayer and ClosestPlayer.Character then Arguments[1] = Ray.new(Camera.CFrame.Position, (ClosestPlayer.Character.Head.Position - Camera.CFrame.Position).Unit * (Camera.CFrame.Position - ClosestPlayer.Character.Head.Position).Magnitude) end end return OldGameMetaTableNamecall(object, unpack(Arguments)) end) setreadonly(GameMetaTable, true)

end)

local Tab2Section = Tab:NewSection("Inf Jumps")

Tab2Section:NewButton("Inf jumps", "ButtonInfo", function()

    local InfiniteJumpEnabled = true

game:GetService("UserInputService").JumpRequest:connect(function()

	if InfiniteJumpEnabled then

		game:GetService"Players".LocalPlayer.Character:FindFirstChildOfClass'Humanoid':ChangeState("Jumping")

	end

end)

end)

local Tab2Section = Tab:NewSection("Inf yield")

Tab2Section:NewButton("inf yield", "ButtonInfo", function()

    loadstring(game:HttpGet(('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'),true))()

end)

local Tab3 = Window:NewTab("Credits")

local Tab3Section = Tab:NewSection("Just Me Eternal")

local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/bloodball/-back-ups-for-libs/main/kav"))()

local Window = Library.CreateLib("Ohio Hub", "DarkTheme")

local Tab1 = Window:NewTab("Games")

local Tab1Section = Tab:NewSection("Arsenal")

Tab1Section:NewButton("PWNER HUB", "best arsenal script", function()

    loadstring(game:HttpGet("https://raw.githubusercontent.com/Maikderninja/Maikderninja/main/PWNERHUB.lua"))();

end)

local Tab1Section = Tab:NewSection("Sword Fighting")

Tab1Section:NewButton("Best Sword fighting", "Pro", function()

    local library = loadstring(game:HttpGet(('https://raw.githubusercontent.com/bloodball/-back-ups-for-libs/main/wall%20v3')))()

local w = library:CreateWindow("Sword X") -- Creates the window

local b = w:CreateFolder("useful") -- Creates the folder(U will put here your buttons,etc)

b:Label("Useful Stuff",{

    TextSize = 25; -- Self Explaining

    TextColor = Color3.fromRGB(255,255,255); -- Self Explaining

    BgColor = Color3.fromRGB(69,69,69); -- Self Explaining

    

}) 

b:Button("Circle Reach",function()

    local ScreenGui = Instance.new("ScreenGui")

local Frame = Instance.new("Frame")

local Reach = Instance.new("TextButton")

ScreenGui.Parent = game.CoreGui

ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = ScreenGui

Frame.BorderSizePixel = 0

Frame.Position = UDim2.new(0.0809101239, 0, 0.203790441, 0)

Frame.Size = UDim2.new(0, 150, 0, 90)

Frame.Active = true

Frame.Draggable = true

Reach.Name = "cum gui by raz"

Reach.Parent = Frame

Reach.BorderSizePixel = 0

Reach.Position = UDim2.new(0, 0, 0.039088048, 0)

Reach.Size = UDim2.new(0, 143, 0, 38)

Reach.Font = Enum.Font.GothamBlack

Reach.Text = "raz's reach (click me)"

Reach.TextSize = 14.000

Reach.MouseButton1Down:connect(function()

	local sound = Instance.new("Sound")

	sound.SoundId = "rbxassetid://4771152040"

	sound.Parent = game:GetService("SoundService")

	sound:Play()

	wait()

	game.StarterGui:SetCore("SendNotification", {

		Title = "how to use this amazing reach?"; -- the title (ofc)

		Text = "equip your item first then press the button tell me if u want bigger reach or smaller imposter#4878"; -- what the text says (ofc)

		Duration = 10; -- how long the notification should in secounds

	})

	for i,v in pairs(game:GetService'Players'.LocalPlayer.Character:GetChildren()) do

		if v:isA("Tool") then

			local a = Instance.new("SelectionSphere",v.Handle)

			v.Handle.Massless = true

			v.Handle.Transparency = 0

			a.Adornee = v.Handle

			v.Handle.Size = Vector3.new(7, 7 , 7)

			local selectionBox = Instance.new("SelectionSphere",v.Handle)

			selectionBox.Adornee = v.Handle

			SurfaceSelection = 0

		end

	end

 end)

end)

b:Toggle("blizzy",function(state)

    shared.toggle = state

    loadstring(game:HttpGet("https://gist.githubusercontent.com/OptioniaI/b7326d42da50a52edf2c511533ae603d/raw/137840f68aef962c4bb6ae01009d5f7a5af4627d/blz-reach"))()

end)

b:Slider("Speed",{

    min = 10; -- min value of the slider

    max = 50; -- max value of the slider

    precise = true; -- max 2 decimals

},function(value)

    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = value

end)

b:Dropdown("Dropdown",{"A","B","C"},true,function(mob) --true/false, replaces the current title "Dropdown" with the option that t

    print(mob)

end)

b:Bind("Bind",Enum.KeyCode.C,function() --Default bind

    print("Yes")

end)

b:ColorPicker("ColorPicker",Color3.fromRGB(255,0,0),function(color) --Default color

    print(color)

end)

b:Box("Jumpower","value",function(value) -- "number" or "string"

game.Players.LocalPlayer.Character.Humanoid.JumpPower = value

end)

b:DestroyGui()

--[[

How to refresh a dropdown:

1)Create the dropdown and save it in a variable

local yourvariable = b:Dropdown("Hi",yourtable,function(a)

    print(a)

end)

2)Refresh it using the function

yourvariable:Refresh(yourtable)

How to refresh a label:

1)Create your label and save it in a variable

local yourvariable = b:Label("Pretty Useless NGL",{

    TextSize = 25; -- Self Explaining

    TextColor = Color3.fromRGB(255,255,255);

    BgColor = Color3.fromRGB(69,69,69);

})

2)Refresh it using the function

yourvariable:Refresh("Hello") It will only change the text ofc

]]

local b = w:CreateFolder("by owo uwu#4878 🥵") -- Creates the folder(U will put here your buttons,etc)

end)

local Tab1Section = Tab:NewSection("Kat script")

Tab1Section:NewButton("Kat", "Op", function()

    --Sub to Squidfan420

loadstring(game:HttpGet("https://raw.githubusercontent.com/ColdStep2/Breaking-Point-Funny-Squid-Hax/main/Breaking%20Point%20Funny%20Squid%20Hax",true))();

end)

local Tab1Section = Tab:NewSection("Starving Artists")

Tab1Section:NewButton("Starving Artist Script", "ButtonInfo", function()

    loadstring(game:HttpGet("https://raw.githubusercontent.com/Jeux45/Starving-Artist-script/main/Script", true))()

end)

local Tab1Section = Tab:NewSection("Keyboard Script")

Tab1Section:NewButton("Keyboard Script", "ButtonInfo", function()

    loadstring(game:HttpGet("https://raw.githubusercontent.com/advxzivhsjjdhxhsidifvsh/mobkeyboard/main/main.txt", true))()

 

end)

local Tab1Section = Tab:NewSection("Animation Hub")

Tab1Section:NewButton("Animations", "ButtonInfo", function()

    loadstring(game:HttpGet("https://gitlab.com/Tsuniox/lua-stuff/-/raw/master/R15GUI.lua"))()

end)

local Tab1Section = Tab:NewSection("Fps Booster")

Tab1Section:NewButton("Fps Boot", "ButtonInfo", function()

    getgenv().Settings = {

	Disabled = false,

	Scans = {

		["Amount"] = 3, -- scans entire game, laggy on some games with alot of instances

		["Cooldown"] = 30, -- cooldown between scans

		["SlowerChecks"] = true, -- less laggy scans (reccomended)

	},

	Main = {

		["RedirectRenderSteppedToHeartbeat"] = true, -- depends on game, but can give you 20-30+ fps (needs hookmetamethod)

		["Low Rendering"] = true, -- helps with performance

		["Extreme Low Rendering"] = true, -- more performance enhancing stuff

		["No Particles"] = true, -- disables particles like fire, trails, forcefields, etc.

		["No Explosions"] = true, -- disables explosions

		["Low Quality Parts"] = true, -- makes parts plastic looking, this boosts fps

		["Low Water Graphics"] = true, -- makes water ugly but helps with fps

		["Low Graphics"] = true, -- makes graphics a little worse

		["No Shadows"] = true, -- disables shadows, helps with performance

		["FPS Unlocker"] = false, -- unlocks fps, heavily reccomended

		["No Camera Effects"] = true, -- no lighting effects like sun rays and bloom

		["Fullbright"] = true, -- makes in-game world fully bright (no dark spots / shadows)

		["Limit FPS When Unfocused"] = false, -- doesnt render when you are tabbed out

		["StreamingEnabled"] = true, -- loads parts with minimal lag and network issues

	},

	Characters = {

		["No Clothes"] = false, -- clothes (shirts,pants) wont appear on characters

	},

	Images = {

		["Destroy"] = false, -- will destroy decals, makes checks slower

		["Invisible"] = false, -- will make images invisible

		["Low Detail"] = true, -- not sure if low detail works

	},

	Decals = {

		["Invisible"] = false, -- make decals invis, put this on iyw

		["Destroy"] = false, -- same as invis but it destroys it instead, slower

	},

	Meshes = {

		["Destroy"] = false, -- destroy meshes, dont reccomend having it on bc it makes checks slower

		["Remove Texture"] = true, -- makes meshes have a gray look

	},

	Textures = {

		["Destroy"] = true, -- destroy textures in game, can make some parts look bad

		["Invisible"] = false, -- makes checks faster and basically same as destroy

	},

	Players = {

		["Ignore LocalPlayer"] = false, -- ignore your character

		["Ignore Everyone"] = true, -- ignore all characters

	},

	Other = {

		["Print"] = false, -- has printconsole() support so games wont detect this

		["Notification"] = false, -- reccomend keeping this disabled, can get annoying

	}

}

loadstring(game:HttpGet("https://raw.githubusercontent.com/notxkid/fpsbooster/main/main.lua"))()

end)

local Tab1Section = Tab:NewSection("Brookhaven")

Tab1Section:NewButton("Brookhaven Ice", "ButtonInfo", function()

    loadstring(game:HttpGet("https://raw.githubusercontent.com/IceMael7/NewIceHub/main/Brookhaven"))()

end)

local Tab1Section = Tab:NewSection("Bedwars")

Tab1Section:NewButton("Vape", "ButtonInfo", function()

    loadstring(game:HttpGet("https://raw.githubusercontent.com/7GrandDadPGN/VapeV4ForRoblox/main/NewMainScript.lua", true))()

end)

Tab1Section:NewButton("Sape", "ButtonInfo", function()

    loadstring(game:HttpGet("https://raw.githubusercontent.com/vodxn/sape/main/Initiate.lua"))()

end)

local Tab1Section = Tab:NewSection("Combat Warriors")

Tab1Section:NewButton("Project hook", "ButtonInfo", function()

    loadstring(game:HttpGet("https://projecthook.xyz/scripts/free.lua"))()

end)

local Tab1Section = Tab:NewSection("Pop it tradimg")

Tab1Section:NewButton("Pop it trading", "ButtonInfo", function()

    loadstring(game:HttpGet("https://raw.githubusercontent.com/Vcsk/AstralHub/main/Main.lua", true))()

end)

Tab1Section:NewButton("Pop it", "ButtonInfo", function()

    loadstring(game:HttpGet("https://raw.githubusercontent.com/Balligusapos/Balligusapos/main/robloxresult-obfuscated"))()

end)

local Tab1Section = Tab:NewSection("Survive the killers")

Tab1Section:NewButton("Survive the killers script", "ButtonInfo", function()

    loadstring(game:HttpGet('https://pastebin.com/raw/TtdvYAKU'))()

end)

local Tab1Section = Tab:NewSection("Sypase x script")

Tab1Section:NewButton("Synpase", "ButtonInfo", function()

    loadstring(game:HttpGet("https://pastebin.com/raw/tWGxhNq0"))()

end)

local Tab1Section = Tab:NewSection("Ragdoll")

Tab1Section:NewButton("Ragdoll Engine script", "ButtonInfo", function()

    loadstring(game:HttpGet('https://raw.githubusercontent.com/martinelcrac/cryptonichub/main/Ragdollengine.lua'))()

end)

local Tab2 = Window:NewTab("Universal Scripts")

local Tab2Section = Tab:NewSection("HitBox")

Section:NewButton("Hitbox Script", "ButtonInfo", function()

    _G.HeadSize = 20

_G.Disabled = true

game:GetService('RunService').RenderStepped:connect(function()

if _G.Disabled then

for i,v in next, game:GetService('Players'):GetPlayers() do

if v.Name ~= game:GetService('Players').LocalPlayer.Name then

pcall(function()

v.Character.HumanoidRootPart.Size = Vector3.new(_G.HeadSize,_G.HeadSize,_G.HeadSize)

v.Character.HumanoidRootPart.Transparency = 0.7

v.Character.HumanoidRootPart.BrickColor = BrickColor.new("Really blue")

v.Character.HumanoidRootPart.Material = "Neon"

v.Character.HumanoidRootPart.CanCollide = false

end)

end

end

end

end)

end)

local Tab2Section = Tab:NewSection("Aimlock")

Tab2Section:NewButton("Aimlock Universal", "ButtonInfo", function()

    local Camera = game:GetService("Workspace").CurrentCamera local Players = game:GetService("Players") local LocalPlayer = game:GetService("Players").LocalPlayer local function GetClosestPlayer() local ClosestPlayer = nil local FarthestDistance = math.huge for i, v in pairs(Players.GetPlayers(Players)) do if v ~= LocalPlayer and v.Character and v.Character.FindFirstChild(v.Character, "HumanoidRootPart") then local DistanceFromPlayer = (LocalPlayer.Character.HumanoidRootPart.Position - v.Character.HumanoidRootPart.Position).Magnitude if DistanceFromPlayer < FarthestDistance then FarthestDistance = DistanceFromPlayer ClosestPlayer = v end end end if ClosestPlayer then return ClosestPlayer end end local GameMetaTable = getrawmetatable(game) local OldGameMetaTableNamecall = GameMetaTable.__namecall setreadonly(GameMetaTable, false) GameMetaTable.__namecall = newcclosure(function(object, ...) local NamecallMethod = getnamecallmethod() local Arguments = {...} if tostring(NamecallMethod) == "FindPartOnRayWithIgnoreList" then local ClosestPlayer = GetClosestPlayer() if ClosestPlayer and ClosestPlayer.Character then Arguments[1] = Ray.new(Camera.CFrame.Position, (ClosestPlayer.Character.Head.Position - Camera.CFrame.Position).Unit * (Camera.CFrame.Position - ClosestPlayer.Character.Head.Position).Magnitude) end end return OldGameMetaTableNamecall(object, unpack(Arguments)) end) setreadonly(GameMetaTable, true)

end)

local Tab2Section = Tab:NewSection("Inf Jumps")

Tab2Section:NewButton("Inf jumps", "ButtonInfo", function()

    local InfiniteJumpEnabled = true

game:GetService("UserInputService").JumpRequest:connect(function()

	if InfiniteJumpEnabled then

		game:GetService"Players".LocalPlayer.Character:FindFirstChildOfClass'Humanoid':ChangeState("Jumping")

	end

end)

end)

local Tab2Section = Tab:NewSection("Inf yield")

Tab2Section:NewButton("inf yield", "ButtonInfo", function()

    loadstring(game:HttpGet(('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'),true))()

end)

local Tab3 = Window:NewTab("Credits")

local Tab3Section = Tab:NewSection("Just Me Eternal")

local Tab4 = Window:NewTab("Updates")

local Tab4Section = Tab:NewSection("New Hub")

