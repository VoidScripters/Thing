--link is https://www.roblox.com/games/8491627378/1-20-Monkey-Sans-an-the-Door


-- ENJOY The Auto Farm



queue_on_teleport([[if game.PlaceId == 9611586905 then loadstring(game:HttpGet("https://raw.githubusercontent.com/LDUCKXD/quacks/main/monkee"))() end]])

if quacky  then
	error("DUcky no 2 !",0)
	return
end

pcall(function() getgenv().quacky = true end)


wait(1)
local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local upgrade = Instance.new("TextButton")
local erro = Instance.new("TextButton")
local grr = Instance.new("Frame")
local hehe = Instance.new("TextButton")
local credits = Instance.new("TextLabel")









ScreenGui.Name = "Quackys"
ScreenGui.Parent = game.CoreGui



Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.new(0.1,0.5,1)
Frame.BackgroundTransparency = 0.4
Frame.BorderSizePixel = 3
Frame.Active = true
Frame.Draggable = true
Frame.Position = UDim2.new(0.295620441, 0, 0.234082401, 0)
Frame.Size = UDim2.new(0, 313, 0, 250)
Frame.Rotation = 7

hehe.Name = "hehe"
hehe.Parent = Frame
hehe.BackgroundColor3 = Color3.new(0, 0, 0)
hehe.BackgroundTransparency = 0.3
hehe.BorderSizePixel = 5
hehe.Position = UDim2.new(0, 290, 0, 3)
hehe.Size = UDim2.new(0, 20, 0, 20)
hehe.Font = Enum.Font.Cartoon
hehe.FontSize = Enum.FontSize.Size14
hehe.Text = "X"
hehe.TextSize = 30
hehe.TextColor3 = Color3.new(2,2,2)
upgrade.Name = "upgrade"
upgrade.Parent = Frame
upgrade.BackgroundColor3 = Color3.new(0, 1, 1)
upgrade.BackgroundTransparency = 0.5
upgrade.BorderSizePixel = 5
upgrade.Position = UDim2.new(0.0543131009, 0, 0.161538467, 0)
upgrade.Size = UDim2.new(0, 130, 0, 49)
upgrade.Font = Enum.Font.Cartoon
upgrade.FontSize = Enum.FontSize.Size14
upgrade.Text = "End Auto farm"
upgrade.TextSize = 14


erro.Name = "erro"
erro.Parent = Frame
erro.BackgroundColor3 = Color3.new(0, 1, 1)
erro.BackgroundTransparency = 0.5
erro.BorderSizePixel = 5
erro.Position = UDim2.new(0.527156591, 0, 0.161538467, 0)
erro.Size = UDim2.new(0, 130, 0, 49)
erro.Font = Enum.Font.Cartoon
erro.FontSize = Enum.FontSize.Size14
erro.Text = "Auto Farm "
erro.TextSize = 14




credits.Name = "credits"
credits.Parent = Frame
credits.BackgroundColor3 = Color3.new(1, 1, 1)
credits.BackgroundTransparency = 1
credits.Position = UDim2.new(0.255969, 0, 0.451538422, 0)
credits.Size = UDim2.new(0, 117, 0, 39)
credits.Font = Enum.Font.Cartoon
credits.FontSize = Enum.FontSize.Size14
credits.Text = "+Added Anti Afk and \n-Removed Auto IY openning"
credits.TextSize = 17
credits.Rotation = 10
local antikickyBoii = game:GetService("VirtualUser")
game:GetService("Players").LocalPlayer.Idled:connect(function()
   antikickyBoii:Button2Down(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
   wait(1)
   antikickyBoii:Button2Up(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
end)

upgrade.MouseButton1Click:connect(function()

_G.loops = true


end)
hehe.MouseButton1Click:connect(function()
ScreenGui:Destroy()
_G.loops = true
pcall(function() getgenv().quacky  = false end)

end)
function QUACKER()

game:GetService("Workspace").Part4.Stinky.Union.Position = Vector3.new(-96, 550, 299)
end


function ducky()
	firetouchinterest(game.Players.LocalPlayer.Character.Head, workspace.MainArea.Boss1, 0)
end
function attack()
game.Players.LocalPlayer.Character["Troy😳"]:Activate()
end

function equip()

for i,v in pairs(game.Players.LocalPlayer.Backpack:GetDescendants()) do 
	if v:IsA("Tool") then
		game.Players.LocalPlayer.Character.Humanoid:EquipTool(v)
	end
end
end

function check()
game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Troy😳") 
if game.Players.LocalPlayer.Backpack:FindFirstChild("Troy😳") or game.Players.LocalPlayer.Character:FindFirstChild("Troy😳") ~= nil then else pcall(back) end
end
function DucksPower()
 wait(0.01)   
 

 repeat
 pcall(equip)
 pcall(check)
 pcall(ducky)
 pcall(QUACKER)
 pcall(attack)	
 wait(0.01) 	
 until game:GetService("Workspace").Part4.AmongUs1	
 repeat
 back()

 until game:GetService("Workspace").MainArea.Boss1
end

function back()
firetouchinterest(game.Players.LocalPlayer.Character.Head, workspace.Part4.Back, 0)
end

erro.MouseButton1Click:connect(function()
_G.loops = false

repeat

 pcall(DucksPower)

until _G.loops
end)

while wait() do
	
local meow = game:GetService("Players").LocalPlayer.WINS.Value
wait("600")
local meow2 = game:GetService("Players").LocalPlayer.WINS.Value

print("10 Min passed wins u got",meow2 - meow)
wait(600)
local meow3 = game:GetService("Players").LocalPlayer.WINS.Value

print("20 Min passed.. Wins u got is",meow3 - meow)

wait(600)
local meow4 = game:GetService("Players").LocalPlayer.WINS.Value
print("30 Min passed..wins u got", meow4 - meow)

wait(1800)
local meow5 = game:GetService("Players").LocalPlayer.WINS.Value
print("1 HOUR PASSED wins  u got",meow5 - meow)

end
