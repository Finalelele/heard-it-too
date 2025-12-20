local Rayfield = loadstring(game:HttpGet('https://sirius.menu/rayfield'))()

local Window = Rayfield:CreateWindow({
   Name = "Heard it too",
   LoadingTitle = "br br patapim",
   LoadingSubtitle = "by Finalelele",
   ConfigurationSaving = {
      Enabled = false,
      FolderName = nil, -- Create a custom folder for your hub/game
      FileName = "Big Hub"
   },
   Discord = {
      Enabled = false,
      Invite = "noinvitelink", -- The Discord invite code, do not include discord.gg/. E.g. discord.gg/ABCD would be ABCD
      RememberJoins = true -- Set this to false to make them join the discord every time they load it up
   },
   KeySystem = false, -- Set this to true to use our key system
   KeySettings = {
      Title = "Untitled",
      Subtitle = "Key System",
      Note = "No method of obtaining the key is provided",
      FileName = "Key", -- It is recommended to use something unique as other scripts using Rayfield may overwrite your key file
      SaveKey = true, -- The user's key will be saved, but if you change the key, they will be unable to use your script
      GrabKeyFromSite = false, -- If this is true, set Key below to the RAW site you would like Rayfield to get the key from
      Key = {"Hello"} -- List of keys that will be accepted by the system, can be RAW file links (pastebin, github etc) or simple strings ("hello","key22")
   }
})

local Tab = Window:CreateTab("Esp generators", 4483362458) -- Title, Image
local Section = Tab:CreateSection("Esp generators")
local Toggle = Tab:CreateToggle({
   Name = "old roblox map",
   CurrentValue = false,
   Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
   Callback = function(Value)
	if Value then
		local old = workspace["OLD ROBLOX MAP"]
		for _,v in pairs(old:GetDescendants()) do
            if v.Name == "generators1" or v.Name == "generators2" or v.Name == "generators3" then
                for _,child in pairs(v:GetDescendants()) do
                    if child.Name == "Highlight" then
                        child.DepthMode = "AlwaysOnTop"
                    end
                end
            end
        end
	else
		local old = workspace["OLD ROBLOX MAP"]
		for _,v in pairs(school:GetDescendants()) do
            if v.Name == "generators1" or v.Name == "generators2" or v.Name == "generators3" then
                for _,child in pairs(v:GetDescendants()) do
                    if child.Name == "Highlight" then
                        child.DepthMode = "Occluded"
                    end
                end
            end
        end
   	end
end
})

local Toggle = Tab:CreateToggle({
   Name = "school map",
   CurrentValue = false,
   Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
   Callback = function(Value)
	if Value then
		local school = workspace["SCHOOL MAP"]
		for _,v in pairs(school:GetDescendants()) do
            if v.Name == "generators1" or v.Name == "generators2" or v.Name == "generators3" then
                for _,child in pairs(v:GetDescendants()) do
                    if child.Name == "Highlight" then
                        child.DepthMode = "AlwaysOnTop"
                    end
                end
            end
        end
	else 
		local school = workspace["SCHOOL MAP"]
		for _,v in pairs(school:GetDescendants()) do
            if v.Name == "generators1" or v.Name == "generators2" or v.Name == "generators3" then
                for _,child in pairs(v:GetDescendants()) do
                    if child.Name == "Highlight" then
                        child.DepthMode = "Occluded"
                    end
                end
            end
        end
	end
end
})

local Toggle = Tab:CreateToggle({
   Name = "grass maze map",
   CurrentValue = false,
   Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
   Callback = function(Value)
	if Value then
		local maze = workspace["GRASS MAZE MAP"]
		for _,v in pairs(maze:GetDescendants()) do
            if v.Name == "generators1" or v.Name == "generators2" or v.Name == "generators3" then
                for _,child in pairs(v:GetDescendants()) do
                    if child.Name == "Highlight" then
                        child.DepthMode = "AlwaysOnTop"
                    end
    	        end
            end
        end
	else 
		local maze = workspace["GRASS MAZE MAP"]
		for _,v in pairs(maze:GetDescendants()) do
            if v.Name == "generators1" or v.Name == "generators2" or v.Name == "generators3" then
                for _,child in pairs(v:GetDescendants()) do
                    if child.Name == "Highlight" then
                        child.DepthMode = "Occluded"
                    end
                end
            end
        end
   	end
end
})

local Toggle = Tab:CreateToggle({
   Name = "city map",
   CurrentValue = false,
   Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
   Callback = function(Value)
	if Value then
		local city = workspace["CITY MAP"]
		for _,v in pairs(city:GetDescendants()) do
            if v.Name == "generators1" or v.Name == "generators2" or v.Name == "generators3" then
                for _,child in pairs(v:GetDescendants()) do
                    if child.Name == "Highlight" then
                        child.DepthMode = "AlwaysOnTop"
                    end
                end
            end
        end
	else 
		local city = workspace["CITY MAP"]
		for _,v in pairs(city:GetDescendants()) do
            if v.Name == "generators1" or v.Name == "generators2" or v.Name == "generators3" then
                for _,child in pairs(v:GetDescendants()) do
                    if child.Name == "Highlight" then
                        child.DepthMode = "Occluded"
                    end
                end
            end
        end
   	end
end
})

local Toggle = Tab:CreateToggle({
   Name = "mall map",
   CurrentValue = false,
   Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
   Callback = function(Value)
	if Value then
		local mall = workspace["MALL MAP"]
		for _,v in pairs(city:GetDescendants()) do
            if v.Name == "generators1" or v.Name == "generators2" or v.Name == "generators3" then
                for _,child in pairs(v:GetDescendants()) do
                    if child.Name == "Highlight" then
                        child.DepthMode = "AlwaysOnTop"
                    end
                end
            end
        end
	else 
		local mall = workspace["MALL MAP"]
		for _,v in pairs(mall:GetDescendants()) do
            if v.Name == "generators1" or v.Name == "generators2" or v.Name == "generators3" then
                for _,child in pairs(v:GetDescendants()) do
                    if child.Name == "Highlight" then
                        child.DepthMode = "Occluded"
                    end
                end
            end
        end
   	end
end
})

local Toggle = Tab:CreateToggle({
   Name = "haunted mansion map",
   CurrentValue = false,
   Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
   Callback = function(Value)
	if Value then
		local mansion = workspace["HAUNTED MANSION MAP"]
		for _,v in pairs(mansion:GetDescendants()) do
            if v.Name == "generators1" or v.Name == "generators2" or v.Name == "generators3" then
                for _,child in pairs(v:GetDescendants()) do
                    if child.Name == "Highlight" then
                        child.DepthMode = "AlwaysOnTop"
                    end
                end
            end
        end	
	else 
		local mansion = workspace["HAUNTED MANSION MAP"]
		for _,v in pairs(mansion:GetDescendants()) do
            if v.Name == "generators1" or v.Name == "generators2" or v.Name == "generators3" then
                for _,child in pairs(v:GetDescendants()) do
                    if child.Name == "Highlight" then
                        child.DepthMode = "Occluded"
                    end
                end
            end
        end
   	end
end
})

local Toggle = Tab:CreateToggle({
   Name = "construction map",
   CurrentValue = false,
   Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
   Callback = function(Value)
	if Value then
		local cons = workspace["CONSTRUCTION MAP"]
		for _,v in pairs(cons:GetDescendants()) do
            if v.Name == "generators1" or v.Name == "generators2" or v.Name == "generators3" then
                for _,child in pairs(v:GetDescendants()) do
                    if child.Name == "Highlight" then
                        child.DepthMode = "AlwaysOnTop"
                    end
                 end
    	    end
        end
	else 
		local cons = workspace["CONSTRUCTION MAP"]
		for _,v in pairs(cons:GetDescendants()) do
        	if v.Name == "generators1" or v.Name == "generators2" or v.Name == "generators3" then
            	for _,child in pairs(v:GetDescendants()) do
                	if child.Name == "Highlight" then
                	    child.DepthMode = "Occluded"
            		end
            	end
        	end
    	end
	end
end
})

local Toggle = Tab:CreateToggle({
   Name = "sewer map",
   CurrentValue = false,
   Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
   Callback = function(Value)
	if Value then
		local sewer = workspace["SEWER MAP"]
		for _,v in pairs(sewer:GetDescendants()) do
            if v.Name == "generators1" or v.Name == "generators2" or v.Name == "generators3" then
                for _,child in pairs(v:GetDescendants()) do
                    if child.Name == "Highlight" then
                        child.DepthMode = "AlwaysOnTop"
                    end
                end
            end
        end
		local sewer = workspace["SEWER MAP"]
		for _,v in pairs(sewer:GetDescendants()) do
            if v.Name == "generators1" or v.Name == "generators2" or v.Name == "generators3" then
                for _,child in pairs(v:GetDescendants()) do
                    if child.Name == "Highlight" then
                        child.DepthMode = "Occluded"
                    end
                end
            end
        end
   	end
end
})

local Toggle = Tab:CreateToggle({
   Name = "classic ihit map",
   CurrentValue = false,
   Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
   Callback = function(Value)
	if Value then
		local ihit = workspace["CLASSIC IHIT MAP"]
		for _,v in pairs(ihit:GetDescendants()) do
            if v.Name == "generators1" or v.Name == "generators2" or v.Name == "generators3" then
                for _,child in pairs(v:GetDescendants()) do
                    if child.Name == "Highlight" then
                        child.DepthMode = "AlwaysOnTop"
                    end
                end
            end
        end
	else
		local ihit = workspace["CLASSIC IHIT MAP"]
		for _,v in pairs(ihit:GetDescendants()) do
            if v.Name == "generators1" or v.Name == "generators2" or v.Name == "generators3" then
                for _,child in pairs(v:GetDescendants()) do
                    if child.Name == "Highlight" then
                        child.DepthMode = "Occluded"
                    end
                end
            end
        end
   	end
end
})

local Tab = Window:CreateTab("Player", 4483362458) -- Title, Image
local Section = Tab:CreateSection("players mode")
local Toggle = Tab:CreateToggle({
   Name = "Player Speed",
   CurrentValue = false,
   Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
   Callback = function(Value)
   if Value then
		local SpeedBox = workspace
		SpBox = Instance.new("BoxHandleAdornment")
		SpBox.Parent = SpeedBox
		SpBox.Name = "SpedBox"
		while wait(0.1) do
			local spb = workspace.SpedBox
			if spb.Parent == workspace then
				game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 50
			else
				break
			end
		end
	else
		local SpdBox = workspace.SpedBox
		SpdBox.Parent = nil
		game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 12
	end
end
})

local Tab = Window:CreateTab("Esp Mother", 4483362458) -- Title, Image
local Section = Tab:CreateSection("my mom is kind of homeless")
local Toggle = Tab:CreateToggle({
   Name = "Mother Esp",
   CurrentValue = false,
   Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
   Callback = function(Value)
   if Value then
		local MomEsp = workspace.Mother.Highlight
		MomEsp.Enabled = true
	else
		local MomEsp = workspace.Mother.Highlight
		MomEsp.Enabled = false
	end
end
})

local Toggle = Tab:CreateToggle({
   Name = "RageEnternal Esp",
   CurrentValue = false,
   Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
   Callback = function(Value)
   if Value then
		local EternalEsp = workspace.RageEnternal.Highlight
		EternalEsp.Enabled = true
	else
		local EternalEsp = workspace.RageEnternal.Highlight
		EternalEsp.Enabled = false
	end
end
})

local Tab = Window:CreateTab("Get spirits", 4483362458) -- Title, Image
local Section = Tab:CreateSection("one time collect")
local Button = Tab:CreateButton({
   Name = "Spirits autocollect (lag)",
   Callback = function()
	for _,v in pairs (workspace:GetDescendants()) do
		if v.Name == "SpiritsOLDROBLOX" or v.Name == "SpiritsSCHOOL" or v.Name == "SpiritsCITY" then
			for _,child in pairs(v:GetDescendants()) do
                if child.Name == "Spirit" then
					wait()
                    child.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
                end
            end
		end
	end
	for _,v in pairs (workspace:GetDescendants()) do
		if v.Name == "SpiritsGRASSMAZE" or v.Name == "SpiritsHAUNTEDMANSION" or v.Name == "SpiritsCLASSICIHIT"then
			for _,child in pairs(v:GetDescendants()) do
                if child.Name == "Spirit" then
					wait()
                    child.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
                end
            end
		end
	end
	for _,v in pairs (workspace:GetDescendants()) do
		if v.Name == "SpiritsMALL" or v.Name == "SpiritsSEWER" or v.Name == "SpiritsCONSTRUCTION"then
			for _,child in pairs(v:GetDescendants()) do
                if child.Name == "Spirit" then
					wait()
                    child.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
                end
            end
		end
	end
end,
})  
