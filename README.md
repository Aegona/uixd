-- Gui to Lua
-- Version: 3.2

-- Instances:

local EzenHub = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local Key = Instance.new("TextBox")
local TextButton = Instance.new("TextButton")
local UICorner_2 = Instance.new("UICorner")
local Logo = Instance.new("ImageLabel")
local tex = Instance.new("TextLabel")
local about = Instance.new("TextLabel")
local buy = Instance.new("TextButton")
local BG2 = Instance.new("Frame")
local UICorner_3 = Instance.new("UICorner")
local Frame_2 = Instance.new("Frame")
local UICorner_4 = Instance.new("UICorner")
local TextLabel = Instance.new("TextLabel")
local Toggle = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local TextLabel_2 = Instance.new("TextLabel")
local Togle2 = Instance.new("TextButton")
local UICorner_6 = Instance.new("UICorner")

--Properties:

EzenHub.Name = "EzenHub"
EzenHub.Parent = game.CoreGui
EzenHub.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = EzenHub
Frame.BackgroundColor3 = Color3.fromRGB(67, 67, 67)
Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.35891813, 0, 0.298543692, 0)
Frame.Size = UDim2.new(0, 385, 0, 332)

UICorner.Parent = Frame

Key.Name = "Key"
Key.Parent = Frame
Key.BackgroundColor3 = Color3.fromRGB(100, 100, 100)
Key.BorderColor3 = Color3.fromRGB(0, 0, 0)
Key.BorderSizePixel = 0
Key.Position = UDim2.new(0.0467532463, 0, 0.620481908, 0)
Key.Size = UDim2.new(0, 349, 0, 34)
Key.Font = Enum.Font.SourceSansBold
Key.PlaceholderText = "Key"
Key.Text = ""
Key.TextColor3 = Color3.fromRGB(0, 0, 0)
Key.TextScaled = true
Key.TextSize = 14.000
Key.TextWrapped = true

TextButton.Parent = Frame
TextButton.BackgroundColor3 = Color3.fromRGB(99, 99, 99)
TextButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton.BorderSizePixel = 0
TextButton.Position = UDim2.new(0.241558447, 0, 0.762048185, 0)
TextButton.Size = UDim2.new(0, 200, 0, 50)
TextButton.Font = Enum.Font.Unknown
TextButton.Text = "Submit"
TextButton.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton.TextScaled = true
TextButton.TextSize = 14.000
TextButton.TextWrapped = true

UICorner_2.Parent = TextButton

Logo.Name = "Logo"
Logo.Parent = Frame
Logo.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Logo.BorderColor3 = Color3.fromRGB(0, 0, 0)
Logo.BorderSizePixel = 0
Logo.Position = UDim2.new(0.368831158, 0, 0.105421685, 0)
Logo.Size = UDim2.new(0, 100, 0, 100)
Logo.Image = "rbxasset://textures/ui/GuiImagePlaceholder.png"

tex.Name = "tex"
tex.Parent = Frame
tex.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
tex.BackgroundTransparency = 1.000
tex.BorderColor3 = Color3.fromRGB(0, 0, 0)
tex.BorderSizePixel = 0
tex.Position = UDim2.new(0.241558447, 0, 0.512048185, 0)
tex.Size = UDim2.new(0, 200, 0, 22)
tex.Font = Enum.Font.SourceSansBold
tex.Text = "How to Get Key?"
tex.TextColor3 = Color3.fromRGB(255, 255, 255)
tex.TextSize = 26.000
tex.TextWrapped = true

about.Name = "about"
about.Parent = Frame
about.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
about.BackgroundTransparency = 1.000
about.BorderColor3 = Color3.fromRGB(0, 0, 0)
about.BorderSizePixel = 0
about.Position = UDim2.new(-0.207792208, 0, -0.4246988, 0)
about.Size = UDim2.new(0, 545, 0, 50)
about.Font = Enum.Font.SourceSansBold
about.Text = "Buy Key in Discord ..."
about.TextColor3 = Color3.fromRGB(255, 8, 0)
about.TextScaled = true
about.TextSize = 14.000
about.TextWrapped = true

buy.Name = "buy"
buy.Parent = Frame
buy.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
buy.BackgroundTransparency = 1.000
buy.BorderColor3 = Color3.fromRGB(0, 0, 0)
buy.BorderSizePixel = 0
buy.Position = UDim2.new(0.259740263, 0, 0.512048185, 0)
buy.Size = UDim2.new(0, 200, 0, 22)
buy.Font = Enum.Font.SourceSans
buy.Text = ""
buy.TextColor3 = Color3.fromRGB(0, 0, 0)
buy.TextSize = 14.000

BG2.Name = "BG2"
BG2.Parent = EzenHub
BG2.BackgroundColor3 = Color3.fromRGB(76, 76, 76)
BG2.BorderColor3 = Color3.fromRGB(0, 0, 0)
BG2.BorderSizePixel = 0
BG2.Position = UDim2.new(0.329678267, 0, 0.354368925, 0)
BG2.Size = UDim2.new(0, 465, 0, 326)
BG2.Visible = false

UICorner_3.Parent = BG2

Frame_2.Parent = BG2
Frame_2.BackgroundColor3 = Color3.fromRGB(54, 54, 54)
Frame_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame_2.BorderSizePixel = 0
Frame_2.Size = UDim2.new(0, 465, 0, 100)

UICorner_4.Parent = Frame_2

TextLabel.Parent = Frame_2
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(0.0215053763, 0, 0.109999999, 0)
TextLabel.Size = UDim2.new(0, 446, 0, 80)
TextLabel.Font = Enum.Font.Unknown
TextLabel.Text = "Ezen Hub"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true

Toggle.Name = "Toggle"
Toggle.Parent = BG2
Toggle.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Toggle.BorderColor3 = Color3.fromRGB(0, 0, 0)
Toggle.BorderSizePixel = 0
Toggle.Position = UDim2.new(0.0215053763, 0, 0.564417183, 0)
Toggle.Size = UDim2.new(0, 446, 0, 50)
Toggle.Font = Enum.Font.SourceSansBold
Toggle.Text = ""
Toggle.TextColor3 = Color3.fromRGB(0, 0, 0)
Toggle.TextSize = 14.000

UICorner_5.Parent = Toggle

TextLabel_2.Parent = BG2
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.BorderSizePixel = 0
TextLabel_2.Position = UDim2.new(0.0344086029, 0, 0.37730062, 0)
TextLabel_2.Size = UDim2.new(0, 440, 0, 50)
TextLabel_2.Font = Enum.Font.SourceSansBold
TextLabel_2.Text = "Kaitan Mode"
TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.TextScaled = true
TextLabel_2.TextSize = 14.000
TextLabel_2.TextWrapped = true

Togle2.Name = "Togle2"
Togle2.Parent = EzenHub
Togle2.BackgroundColor3 = Color3.fromRGB(76, 76, 76)
Togle2.BorderColor3 = Color3.fromRGB(0, 0, 0)
Togle2.BorderSizePixel = 0
Togle2.Position = UDim2.new(0.0343567245, 0, 0.503640771, 0)
Togle2.Size = UDim2.new(0, 51, 0, 50)
Togle2.Visible = false
Togle2.Font = Enum.Font.SourceSans
Togle2.Text = ""
Togle2.TextColor3 = Color3.fromRGB(0, 0, 0)
Togle2.TextSize = 14.000

UICorner_6.Parent = Togle2

-- Scripts:

local function EKCV_fake_script() -- TextButton.LocalScript 
	local script = Instance.new('LocalScript', TextButton)

	-- กำหนด Key เป็น Table
	local Key = {
		EzenKey11294 = true,
		EzenKeyASc3asdij89 = true,
		EzenKeyASdc124 = true,
		EzenKeyIcOo1042199 = true
	}
	
	-- ตั้งค่า MouseButton1Click event
	script.Parent.MouseButton1Click:Connect(function()
		-- หา TextBox ที่ชื่อ "Key" ใน Parent
		local textBox = script.Parent.Parent:FindFirstChild("Key")
	
		-- ตรวจสอบว่า textBox มีค่าหรือไม่
		if textBox then
			local inputCode = textBox.Text
	
			-- ตรวจสอบว่า inputCode ตรงกับ Key หรือไม่
			if Key[inputCode] then
				textBox.PlaceholderText = "Suscess!"
				script.Parent.Parent.Parent.Frame.Visible = false
				wait(2)
				script.Parent.Parent.Parent.BG2.Visible = true
				script.Parent.Parent.Parent.Togle2.Visible = true
			else
				textBox.PlaceholderText = "Error ไม่พบ Key!"
			end
		else
			textBox.PlaceholderText = "Error โปรดติดต่อ Support!"
		end
	end)
	
end
coroutine.wrap(EKCV_fake_script)()
local function XVCO_fake_script() -- buy.LocalScript 
	local script = Instance.new('LocalScript', buy)

	local about = script.Parent.Parent.about
	
	
	about.Visible = false
	local button = script.Parent
	
	button.MouseButton1Click:Connect(function()
		about.Visible = true
		wait(2)
		about.Visible = false
	end)
end
coroutine.wrap(XVCO_fake_script)()
local function RZBJTCX_fake_script() -- Toggle.LocalScript 
	local script = Instance.new('LocalScript', Toggle)

	local st = false
	
	script.Parent.BackgroundColor3 = Color3.fromHSV(0, 1, 1)
	
	
	script.Parent.MouseButton1Click:Connect(function()
		if st == false then
			_G.Farm = true
			game.Players.LocalPlayer.Character:WaitForChild("Humanoid").WalkSpeed = 200
			script.Parent.BackgroundColor3 = Color3.fromHSV(0.353, 0.924178, 0.827451)
			st = true
		elseif st == true then
			game.Players.LocalPlayer.Character:WaitForChild("Humanoid").WalkSpeed = 16
			_G.Farm = false
			script.Parent.BackgroundColor3 = Color3.fromHSV(0, 1, 1)
			st = false
		end
	end)
end
coroutine.wrap(RZBJTCX_fake_script)()
local function VONJGCZ_fake_script() -- Togle2.LocalScript 
	local script = Instance.new('LocalScript', Togle2)

	script.Parent.MouseButton1Click:Connect(function()
		if script.Parent.Parent.BG2.Visible == false then
			script.Parent.Parent.BG2.Visible = true
		elseif script.Parent.Parent.BG2.Visible == true then
			script.Parent.Parent.BG2.Visible = false
		end
	end)
end
coroutine.wrap(VONJGCZ_fake_script)()
