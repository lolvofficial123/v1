-- Gui to Lua
-- Version: 3.2

-- Instances:		

local Util = Instance.new("ScreenGui")
local Main = Instance.new("Frame")
local Home_Page = Instance.new("Frame")
local WELCOME = Instance.new("TextLabel")
local VERSION = Instance.new("TextLabel")
local UICorner = Instance.new("UICorner")
local FE_Page = Instance.new("Frame")
local ToolFE = Instance.new("TextButton")
local UICorner_2 = Instance.new("UICorner")
local Page_Holder = Instance.new("Frame")
local FE_Scripts = Instance.new("TextButton")
local UICorner_3 = Instance.new("UICorner")
local Home_Page_2 = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local Settings_Page = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local ImageLabel = Instance.new("ImageLabel")
local TITLE = Instance.new("TextLabel")
local Close = Instance.new("Frame")
local UICorner_6 = Instance.new("UICorner")
local TextButton = Instance.new("TextButton")
local Settings_Page_2 = Instance.new("Frame")
local LightMode = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
local Darkmode = Instance.new("TextButton")
local UICorner_8 = Instance.new("UICorner")

--Properties:

Util.Name = "Util"
Util.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
Util.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
Util.ResetOnSpawn = false

Main.Name = "Main"
Main.Parent = Util
Main.BackgroundColor3 = Color3.fromRGB(33, 33, 33)
Main.BorderColor3 = Color3.fromRGB(33, 33, 33)
Main.Position = UDim2.new(0.369752765, 0, 0.345209777, 0)
Main.Size = UDim2.new(0, 414, 0, 259)

Home_Page.Name = "Home_Page"
Home_Page.Parent = Main
Home_Page.BackgroundColor3 = Color3.fromRGB(33, 33, 33)
Home_Page.BorderColor3 = Color3.fromRGB(33, 33, 33)
Home_Page.Position = UDim2.new(0.248791978, 0, 0.160529301, 0)
Home_Page.Size = UDim2.new(0, 304, 0, 217)

WELCOME.Name = "WELCOME"
WELCOME.Parent = Home_Page
WELCOME.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
WELCOME.BackgroundTransparency = 1.000
WELCOME.Position = UDim2.new(0.333333343, 0, -9.43654159e-05, 0)
WELCOME.Size = UDim2.new(0, 106, 0, 20)
WELCOME.Font = Enum.Font.SourceSans
WELCOME.Text = "Welcome to Util"
WELCOME.TextColor3 = Color3.fromRGB(188, 188, 188)
WELCOME.TextSize = 14.000

VERSION.Name = "VERSION"
VERSION.Parent = Home_Page
VERSION.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
VERSION.BackgroundTransparency = 1.000
VERSION.Position = UDim2.new(0.333333343, 0, 0.15658766, 0)
VERSION.Size = UDim2.new(0, 106, 0, 20)
VERSION.Font = Enum.Font.SourceSans
VERSION.Text = "Version is currently V1.0"
VERSION.TextColor3 = Color3.fromRGB(116, 188, 68)
VERSION.TextSize = 14.000

UICorner.CornerRadius = UDim.new(0, 10)
UICorner.Parent = Main

FE_Page.Name = "FE_Page"
FE_Page.Parent = Main
FE_Page.BackgroundColor3 = Color3.fromRGB(33, 33, 33)
FE_Page.BorderColor3 = Color3.fromRGB(33, 33, 33)
FE_Page.Position = UDim2.new(0.248791978, 0, 0.160529301, 0)
FE_Page.Size = UDim2.new(0, 304, 0, 217)
FE_Page.Visible = false

ToolFE.Name = "Tool FE"
ToolFE.Parent = FE_Page
ToolFE.BackgroundColor3 = Color3.fromRGB(186, 186, 186)
ToolFE.BorderColor3 = Color3.fromRGB(50, 50, 50)
ToolFE.Position = UDim2.new(0.0091508422, 0, 0.0414746553, 0)
ToolFE.Size = UDim2.new(0, 304, 0, 24)
ToolFE.Font = Enum.Font.SourceSans
ToolFE.Text = "Tool FE"
ToolFE.TextColor3 = Color3.fromRGB(0, 0, 0)
ToolFE.TextSize = 24.000
ToolFE.TextWrapped = true

UICorner_2.CornerRadius = UDim.new(0, 3)
UICorner_2.Parent = ToolFE

Page_Holder.Name = "Page_Holder"
Page_Holder.Parent = Main
Page_Holder.BackgroundColor3 = Color3.fromRGB(33, 33, 33)
Page_Holder.BorderColor3 = Color3.fromRGB(50, 50, 50)
Page_Holder.Position = UDim2.new(0.0150987683, 0, 0.16045025, 0)
Page_Holder.Size = UDim2.new(0, 89, 0, 201)

FE_Scripts.Name = "FE_Scripts"
FE_Scripts.Parent = Page_Holder
FE_Scripts.BackgroundColor3 = Color3.fromRGB(45, 45, 45)
FE_Scripts.BorderColor3 = Color3.fromRGB(72, 72, 72)
FE_Scripts.Position = UDim2.new(0.0564660914, 0, 0.233830988, 0)
FE_Scripts.Size = UDim2.new(0, 77, 0, 26)
FE_Scripts.Font = Enum.Font.SourceSans
FE_Scripts.Text = "FE"
FE_Scripts.TextColor3 = Color3.fromRGB(255, 255, 255)
FE_Scripts.TextSize = 24.000
FE_Scripts.TextWrapped = true

UICorner_3.CornerRadius = UDim.new(0, 3)
UICorner_3.Parent = FE_Scripts

Home_Page_2.Name = "Home_Page"
Home_Page_2.Parent = Page_Holder
Home_Page_2.BackgroundColor3 = Color3.fromRGB(45, 45, 45)
Home_Page_2.BorderColor3 = Color3.fromRGB(72, 72, 72)
Home_Page_2.Position = UDim2.new(0.0564660914, 0, 0.0696519017, 0)
Home_Page_2.Size = UDim2.new(0, 77, 0, 26)
Home_Page_2.Font = Enum.Font.SourceSans
Home_Page_2.Text = "Home"
Home_Page_2.TextColor3 = Color3.fromRGB(255, 255, 255)
Home_Page_2.TextSize = 24.000
Home_Page_2.TextWrapped = true

UICorner_4.CornerRadius = UDim.new(0, 3)
UICorner_4.Parent = Home_Page_2

Settings_Page.Name = "Settings_Page"
Settings_Page.Parent = Page_Holder
Settings_Page.BackgroundColor3 = Color3.fromRGB(45, 45, 45)
Settings_Page.BorderColor3 = Color3.fromRGB(72, 72, 72)
Settings_Page.Position = UDim2.new(0.0564660877, 0, 0.79104495, 0)
Settings_Page.Size = UDim2.new(0, 77, 0, 26)
Settings_Page.Font = Enum.Font.SourceSans
Settings_Page.Text = "Settings"
Settings_Page.TextColor3 = Color3.fromRGB(255, 255, 255)
Settings_Page.TextSize = 24.000
Settings_Page.TextWrapped = true

UICorner_5.CornerRadius = UDim.new(0, 3)
UICorner_5.Parent = Settings_Page

ImageLabel.Parent = Main
ImageLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel.BackgroundTransparency = 1.000
ImageLabel.Position = UDim2.new(0.0144927539, 0, 0.0330371037, 0)
ImageLabel.Size = UDim2.new(0, 24, 0, 27)
ImageLabel.Image = "rbxassetid://9366955376"
ImageLabel.ImageColor3 = Color3.fromRGB(162, 56, 255)

TITLE.Name = "TITLE"
TITLE.Parent = Main
TITLE.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TITLE.BackgroundTransparency = 1.000
TITLE.Position = UDim2.new(0.0893719792, 0, 0.0175930895, 0)
TITLE.Size = UDim2.new(0, 58, 0, 35)
TITLE.Font = Enum.Font.SourceSans
TITLE.Text = "UTIL"
TITLE.TextColor3 = Color3.fromRGB(188, 188, 188)
TITLE.TextScaled = true
TITLE.TextSize = 14.000
TITLE.TextWrapped = true

Close.Name = "Close"
Close.Parent = Main
Close.BackgroundColor3 = Color3.fromRGB(255, 0, 4)
Close.BorderColor3 = Color3.fromRGB(255, 0, 4)
Close.Position = UDim2.new(0.932367265, 0, 0.0330371037, 0)
Close.Size = UDim2.new(0, 20, 0, 21)

UICorner_6.Parent = Close

TextButton.Parent = Close
TextButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton.BackgroundTransparency = 0.980
TextButton.Position = UDim2.new(-0.349999994, 0, -0.409523845, 0)
TextButton.Size = UDim2.new(0, 20, 0, 19)
TextButton.Font = Enum.Font.SourceSans
TextButton.Text = ""
TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton.TextScaled = true
TextButton.TextSize = 14.000
TextButton.TextWrapped = true

Settings_Page_2.Name = "Settings_Page"
Settings_Page_2.Parent = Main
Settings_Page_2.BackgroundColor3 = Color3.fromRGB(33, 33, 33)
Settings_Page_2.BorderColor3 = Color3.fromRGB(33, 33, 33)
Settings_Page_2.Position = UDim2.new(0.248791978, 0, 0.160529301, 0)
Settings_Page_2.Size = UDim2.new(0, 304, 0, 217)
Settings_Page_2.Visible = false

LightMode.Name = "LightMode"
LightMode.Parent = Settings_Page_2
LightMode.BackgroundColor3 = Color3.fromRGB(172, 41, 172)
LightMode.BackgroundTransparency = 0.700
LightMode.BorderColor3 = Color3.fromRGB(0, 0, 0)
LightMode.Position = UDim2.new(0.171052635, 0, 0.156682029, 0)
LightMode.Size = UDim2.new(0, 200, 0, 50)
LightMode.Font = Enum.Font.SourceSans
LightMode.Text = "Lightmode"
LightMode.TextColor3 = Color3.fromRGB(222, 222, 222)
LightMode.TextSize = 20.000
LightMode.TextWrapped = true

UICorner_7.Parent = LightMode

Darkmode.Name = "Darkmode"
Darkmode.Parent = Settings_Page_2
Darkmode.BackgroundColor3 = Color3.fromRGB(172, 41, 172)
Darkmode.BackgroundTransparency = 0.700
Darkmode.BorderColor3 = Color3.fromRGB(0, 0, 0)
Darkmode.Position = UDim2.new(0.171052635, 0, 0.419354856, 0)
Darkmode.Size = UDim2.new(0, 200, 0, 50)
Darkmode.Font = Enum.Font.SourceSans
Darkmode.Text = "Darkmode"
Darkmode.TextColor3 = Color3.fromRGB(222, 222, 222)
Darkmode.TextSize = 20.000
Darkmode.TextWrapped = true

UICorner_8.Parent = Darkmode

-- Scripts:

local function CJNYL_fake_script() -- Main.Smooth GUI Dragging 
	local script = Instance.new('LocalScript', Main)

	local UserInputService = game:GetService("UserInputService")
	local runService = (game:GetService("RunService"));
	
	local gui = script.Parent
	
	local dragging
	local dragInput
	local dragStart
	local startPos
	
	function Lerp(a, b, m)
		return a + (b - a) * m
	end;
	
	local lastMousePos
	local lastGoalPos
	local DRAG_SPEED = (8); -- // The speed of the UI darg.
	function Update(dt)
		if not (startPos) then return end;
		if not (dragging) and (lastGoalPos) then
			gui.Position = UDim2.new(startPos.X.Scale, Lerp(gui.Position.X.Offset, lastGoalPos.X.Offset, dt * DRAG_SPEED), startPos.Y.Scale, Lerp(gui.Position.Y.Offset, lastGoalPos.Y.Offset, dt * DRAG_SPEED))
			return 
		end;
	
		local delta = (lastMousePos - UserInputService:GetMouseLocation())
		local xGoal = (startPos.X.Offset - delta.X);
		local yGoal = (startPos.Y.Offset - delta.Y);
		lastGoalPos = UDim2.new(startPos.X.Scale, xGoal, startPos.Y.Scale, yGoal)
		gui.Position = UDim2.new(startPos.X.Scale, Lerp(gui.Position.X.Offset, xGoal, dt * DRAG_SPEED), startPos.Y.Scale, Lerp(gui.Position.Y.Offset, yGoal, dt * DRAG_SPEED))
	end;
	
	gui.InputBegan:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
			dragging = true
			dragStart = input.Position
			startPos = gui.Position
			lastMousePos = UserInputService:GetMouseLocation()
	
			input.Changed:Connect(function()
				if input.UserInputState == Enum.UserInputState.End then
					dragging = false
				end
			end)
		end
	end)
	
	gui.InputChanged:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
			dragInput = input
		end
	end)
	
	runService.Heartbeat:Connect(Update)
end
coroutine.wrap(CJNYL_fake_script)()
local function TAITXGR_fake_script() -- ToolFE.LocalScript 
	local script = Instance.new('LocalScript', ToolFE)

	script.Parent.MouseButton1Click:Connect(function()
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
	end)
end
coroutine.wrap(TAITXGR_fake_script)()
local function VFET_fake_script() -- TextButton.LocalScript 
	local script = Instance.new('LocalScript', TextButton)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Parent.Parent.Main.Visible = false
	end)
	
end
coroutine.wrap(VFET_fake_script)()
local function LFRCN_fake_script() -- LightMode.LocalScript 
	local script = Instance.new('LocalScript', LightMode)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Parent.Parent.Main.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	end)
	
end
coroutine.wrap(LFRCN_fake_script)()
local function TZAA_fake_script() -- Darkmode.LocalScript 
	local script = Instance.new('LocalScript', Darkmode)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Parent.Parent.Main.BackgroundColor3 = Color3.fromRGB(33, 33, 33)
	end)
	
end
coroutine.wrap(TZAA_fake_script)()
local function BKHWZAE_fake_script() -- Util.Pages 
	local script = Instance.new('LocalScript', Util)

	script.Parent.Main.Page_Holder.Home_Page.MouseButton1Click:Connect(function()
		script.Parent.Main.FE_Page.Visible = false
		script.Parent.Main.Home_Page.Visible = true
		script.Parent.Main.Settings_Page.Visible = false
	end)
	
	script.Parent.Main.Page_Holder.FE_Scripts.MouseButton1Click:Connect(function()
		script.Parent.Main.Home_Page.Visible = false
		script.Parent.Main.FE_Page.Visible = true
		script.Parent.Main.Settings_Page.Visible = false
	end)
	
	script.Parent.Main.Page_Holder.Settings_Page.MouseButton1Click:Connect(function()
		script.Parent.Main.Home_Page.Visible = false
		script.Parent.Main.FE_Page.Visible = false
		script.Parent.Main.Settings_Page.Visible = true
	end)
end
coroutine.wrap(BKHWZAE_fake_script)()
