if not game:IsLoaded() then game.Loaded:wait() end

local FinalStandTable = {536102540, 569994010, 2050207304, 882399924, 2046990924, 478132461, 3552157537, 2651456105, 3565304751, 535527772, 882375367, 3552158750}
if not table.find(FinalStandTable, game.PlaceId) then return end






game.StarterGui:SetCore("SendNotification", {
    Title = "1tsJustCmds";
    Text = "Credits 1tsJustgp";
    Duration = "15";
    })

	game.StarterGui:SetCore("SendNotification", {
		Title = "1tsJustCmds";
		Text = "send in chat _cmds and press f9 and scroll down";
		Duration = "15";
		})

wait(0.3)

local args = {
    [1] = "~1tsJustCmds V2~",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))

wait(0.3)


local args = {
    [1] = "~Credits 1tsJustgp~",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))


function dc()
	local plr = game:GetService("Players").LocalPlayer
	local mouse = plr:GetMouse()
	local place = game.PlaceId
	Character = game.Players.LocalPlayer
	Players = game.Players.LocalPlayer.Character
	MouseFunction = game:GetService("Players").LocalPlayer:GetMouse()


	mouse.KeyDown:connect(function(key)

		if key == "k" then
			Players.Humanoid:EquipTool(Character.Backpack["Dragon Crush"])
			Players["Dragon Crush"]:Activate()
			game.Workspace.Live[Character.Name]["Dragon Crush"].Activator["Flip"]:Destroy()
			wait()

		end
	end)
end 


function dc2()
game:GetService("StarterGui"):SetCore("SendNotification", {
Title = "1tsJustCmds";
Text = "DragonCrush Glich Press K";
})
end
local Player = game.Players.LocalPlayer
Player.Chatted:connect(function(cht)
if cht:match("_dc") or cht:match("_dragoncrush") then
dc2()
dc()
end
end)


function de()
	game:GetService("StarterGui"):SetCore("SendNotification", {
        Title = "1tsJustgp";
        Text = "DragonCrush Glich Press K For Glich down earth";
        })
        
        
            local plr = game:GetService("Players").LocalPlayer
            local mouse = plr:GetMouse()
            local place = game.PlaceId
            Character = game.Players.LocalPlayer
            Players = game.Players.LocalPlayer.Character
            MouseFunction = game:GetService("Players").LocalPlayer:GetMouse()
        
        
            mouse.KeyDown:connect(function(key)
        
                if key == "k" then
                    Players.Humanoid:EquipTool(Character.Backpack["Dragon Crush"])
                    Players["Dragon Crush"]:Activate()
                    game.Workspace.Live[Character.Name]["Dragon Crush"].Activator["Flip"]:Destroy()
                    wait()
                    
                    wait(1)
                    
                        game:GetService("TweenService"):Create(
                game.Players.LocalPlayer.Character.HumanoidRootPart,
                TweenInfo.new(1.2, Enum.EasingStyle.Linear, Enum.EasingDirection.Out),
                {CFrame = CFrame.new(-456, -100, -6412)}
                ):Play()
                
                wait(0.5)
                
                wait(1)
                    
                        game:GetService("TweenService"):Create(
                game.Players.LocalPlayer.Character.HumanoidRootPart,
                TweenInfo.new(1.2, Enum.EasingStyle.Linear, Enum.EasingDirection.Out),
                {CFrame = CFrame.new(-456, -100, -6412)}
                ):Play()
                
                wait(0.5)
                
                wait(1)
                    
                        game:GetService("TweenService"):Create(
                game.Players.LocalPlayer.Character.HumanoidRootPart,
                TweenInfo.new(1.2, Enum.EasingStyle.Linear, Enum.EasingDirection.Out),
                {CFrame = CFrame.new(-456, -100, -6412)}
                ):Play()
                
                wait(0.5)
                
                
                
                
                
                
                
                
                game.Players.LocalPlayer.Character.HumanoidRootPart.Anchored = true 
                
                
                wait(1.4)
                
                
                    local place = game.PlaceId
                    wait(0.1)
                    game:GetService("TeleportService"):Teleport(place)
                
                    
        
                end
            end)       
end 

local Player = game.Players.LocalPlayer
Player.Chatted:connect(function(cht)
if cht:match("_de") or cht:match("_downearth") then
de()
end
end)


function dt()
	local plr = game:GetService("Players").LocalPlayer
	local mouse = plr:GetMouse()
	local place = game.PlaceId
	Character = game.Players.LocalPlayer
	Players = game.Players.LocalPlayer.Character
	MouseFunction = game:GetService("Players").LocalPlayer:GetMouse()


	mouse.KeyDown:connect(function(key)

		if key == "k" then
			Players.Humanoid:EquipTool(Character.Backpack["Dragon Throw"])
			Players["Dragon Throw"]:Activate()
			game.Workspace.Live[Character.Name]["Dragon Throw"].Activator["Flip"]:Destroy()
			wait()

		end
	end)
end 
function dt2()
game:GetService("StarterGui"):SetCore("SendNotification", {
Title = "1tsJustCmds";
Text = "DragonThrow Glich Press K";
})
end
local Player = game.Players.LocalPlayer
Player.Chatted:connect(function(cht)
if cht:match("_dt") or cht:match("_dragonthrow") then
dt2()
dt()
end
end)




function noslow()
    (getgenv()).noslow = true;

    repeat
        wait();
    until game:IsLoaded();
    game.Players.LocalPlayer.PlayerGui:WaitForChild("HUD");
    (game:GetService("RunService")).RenderStepped:Connect(function()
        for _, v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
            if (getgenv()).noslow then
                if v.Name == "Action" or (v.Name == "Attacking") or 
                        (v.Name == "Using") or (v.Name == "hyper") or 
                        (v.Name == "Hyper") or (v.Name == "heavy") or 
                        (v.Name == "KiBlasted") or (v.Name == "Tele") or 
                        (v.Name == "tele") or (v.Name == "Killed") or 
                        (v.Name == "Slow") then
                    v:Destroy();
                end;
                if game.Players.LocalPlayer.Character.Block.Value then
                    game.Players.LocalPlayer.Character.Block.Value = false;
                end;
            end;
        end;
    end);
end 
function noslow2()
	game:GetService("StarterGui"):SetCore("SendNotification", {
		Title = "1tsJustCmds";
		Text = "Noslow";
	})
end

local Player = game.Players.LocalPlayer
Player.Chatted:connect(function(cht)
	if cht:match("_ns") or cht:match("_noslow") then
		noslow()
		noslow2()
	end
end)

function ms()
_G.on = true

	while _G.on == true do
	
		game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack["Meteor Crash"])
		game.Players.LocalPlayer.Character["Meteor Crash"]:Activate()
			wait (0.5)
		game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack["Anger Rush"])
		game.Players.LocalPlayer.Character["Anger Rush"]:Activate()
			wait(0.5)
		game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack["Neo Wolf Fang Fist"])
		game.Players.LocalPlayer.Character["Neo Wolf Fang Fist"]:Activate()
			wait(0.5)
		game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack["Wolf Fang Fist"])
		game.Players.LocalPlayer.Character["Wolf Fang Fist"]:Activate()
			wait(0.5)
		game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack["Mach Kick"])
		game.Players.LocalPlayer.Character["Mach Kick"]:Activate()
			wait(0.5)
		game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack["TS Molotov"])
		game.Players.LocalPlayer.Character["TS Molotov"]:Activate()
			wait(0.5)
		game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack["Vital Strike"])
		game.Players.LocalPlayer.Character["Vital Strike"]:Activate()
			wait(0.5)
		game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack["Strong Kick"])
		game.Players.LocalPlayer.Character["Strong Kick"]:Activate()
			wait(0.5)
		game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack["Kick Barrage"])
		game.Players.LocalPlayer.Character["Kick Barrage"]:Activate()
			wait(0.5)
		game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack["Deadly Dance"])
		game.Players.LocalPlayer.Character["Deadly Dance"]:Activate()
			wait(0.6)
		game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack["God Slicer"])
		game.Players.LocalPlayer.Character["God Slicer"]:Activate()
	wait()
	end
end 
function ms1()
	game:GetService("StarterGui"):SetCore("SendNotification", {
		Title = "1tsJustCmds";
		Text = "melee spam on but you have to have all the moves written in the cmds to make spam work";
	})
end

local Player = game.Players.LocalPlayer
Player.Chatted:connect(function(cht)
	if cht:match("_ms") or cht:match("_meleespam") then
		ms()
		ms1()
	end
end)

function mss()
    _G.on = false
end 
function mss1()
	game:GetService("StarterGui"):SetCore("SendNotification", {
		Title = "1tsJustCmds";
		Text = "melee spam off but you have to have all the moves written in the cmds to make spam work";
	})
end

local Player = game.Players.LocalPlayer
Player.Chatted:connect(function(cht)
	if cht:match("_sms") or cht:match("_stopmeleespam") then
		mss()
		mss1()
	end
end)

function freeze()
	local plr = game:GetService("Players").LocalPlayer
	local mouse = plr:GetMouse()
	local place = game.PlaceId
	Character = game.Players.LocalPlayer
	Players = game.Players.LocalPlayer.Character
	MouseFunction = game:GetService("Players").LocalPlayer:GetMouse()


	mouse.KeyDown:connect(function(key)

		if key == "k" then
			Players.Humanoid:EquipTool(Character.Backpack["Dragon Crush"])
			Players["Dragon Crush"]:Activate()
			game.Workspace.Live[Character.Name]["Dragon Crush"].Activator["Flip"]:Destroy()
			wait()

		end
	end)
	mouse.KeyDown:connect(function(key)

		if key == "k" then
			local place = game.PlaceId
			wait(0.5)
			game:GetService("TeleportService"):Teleport(place)
		end
	end)

end
function freeze2()
	game:GetService("StarterGui"):SetCore("SendNotification", {
		Title = "1tsJustCmds";
		Text = "Press K To Use";
	})
end
local Player = game.Players.LocalPlayer
Player.Chatted:connect(function(cht)
	if cht:match("_freeze") then
		freeze2()
		freeze()
	end
end)

function god()
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "decrease"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "decrease"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "decrease"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "decrease"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "decrease"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "decrease"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "decrease"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "decrease"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "decrease"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "decrease"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "decrease"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "decrease"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "decrease"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "decrease"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "decrease"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "decrease"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "decrease"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "decrease"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "decrease"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "decrease"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "decrease"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "decrease"},[2] = true}))
    game:GetService("ReplicatedStorage").ResetChar:FireServer()
    wait(0.4)
    local args = {
        [1] = "h"
    }
    
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Transform:FireServer(unpack(args))
    wait(0.4)
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "increase"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "increase"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "increase"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "increase"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "increase"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "increase"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "increase"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "increase"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "increase"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "increase"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "increase"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "increase"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "increase"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "increase"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "increase"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "increase"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "increase"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "increase"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "increase"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "increase"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "increase"},[2] = true}))
    game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack( {[1] = {[1] = "increase"},[2] = true}))
    
    getgenv().showstats = true
    getgenv().Zenni = true
    getgenv().resettop = true 
    getgenv().RespawnLowKi = true
    getgenv().movespam = true;
    getgenv().noslow = true;
    getgenv().Spambans = true;
    local plr = game.Players.LocalPlayer 
end

function god2()
	game:GetService("StarterGui"):SetCore("SendNotification", {
		Title = "1tsJustCmds";
		Text = "Become A GOD";
	})
end
local Player = game.Players.LocalPlayer
Player.Chatted:connect(function(cht)
	if cht:match("_god") then
		god2()
		god()
	end
end)

function respawn()
	-- Script generated by SimpleSpy - credits to exx#9394

	local args = {
		[1] = workspace.FriendlyNPCs:FindFirstChild("Hair Stylist")
	}

	game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatStart:FireServer(unpack(args))
	-- Script generated by SimpleSpy - credits to exx#9394
	wait(.3)
	local args = {
		[1] = {
			[1] = "Yes"
		}
	}

	game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance:FireServer(unpack(args))
	wait(.3)
	-- Script generated by SimpleSpy - credits to exx#9394

	local args = {
		[1] = "woah"
	}

	game:GetService("Players").LocalPlayer.Backpack.HairScript.RemoteEvent:FireServer(unpack(args))
end
function respawn2()
	game:GetService("StarterGui"):SetCore("SendNotification", {
		Title = "1tsJustCmds";
		Text = "Fast Reseting";
	})
end

local Player = game.Players.LocalPlayer
Player.Chatted:connect(function(cht)
	if cht:match("_respawn") or cht:match("_re") then
		respawn2()
		respawn()
	end
end)

function rejoin()
    local place = game.PlaceId
    wait(0.1)
    game:GetService("TeleportService"):Teleport(place)
end

local Player = game.Players.LocalPlayer
Player.Chatted:connect(function(cht)
	if cht:match("_rejoin") or cht:match("_rj") then
		rejoin()
	end
end)


function Tower1()
    game:GetService("TweenService"):Create(
           game.Players.LocalPlayer.Character.HumanoidRootPart,
           TweenInfo.new(1.2, Enum.EasingStyle.Linear, Enum.EasingDirection.Out),
           {CFrame = CFrame.new(2071, 1495, -2279)}
           ):Play()
end

local Player = game.Players.LocalPlayer
Player.Chatted:connect(function(cht)
	if cht:match("_tower") then
		Tower1()
	end
end)



function bonecrush()
	local plr = game:GetService("Players").LocalPlayer
	game.Workspace:WaitForChild("Live")
	game.Workspace.Live:WaitForChild(plr.Name)
	local Char = plr.Character
	local portal = game.workspace["Wormhole"]
	local Mouse = plr:GetMouse()
	
	
	game:GetService("RunService").RenderStepped:connect(
		function()
			
		
		end)
	
	
	
			function bc11()
				   local lplr = game.Players.LocalPlayer
					local plr = game:GetService("Players").LocalPlayer
						local mouse = plr:GetMouse()
						local place = game.PlaceId
						Character = game.Players.LocalPlayer
						Players = game.Players.LocalPlayer.Character
						MouseFunction = game:GetService("Players").LocalPlayer:GetMouse()
				   
				   
				   Players.Humanoid:EquipTool(Character.Backpack["Bone Crush"])
					Players["Bone Crush"]:Activate()
					lplr.Character["Bone Crush"].Activator.Crash:Destroy() 
				end
				
			   
	Mouse.KeyDown:connect(function(Key)
					Key = Key:lower()
				if Key == "k" then
				bc11()
				end
	end)
end

function bonecrush2()
	game:GetService("StarterGui"):SetCore("SendNotification", {
		Title = "1tsJustCmds";
		Text = "Pressing K to glich";
	})
end
local Player = game.Players.LocalPlayer
Player.Chatted:connect(function(cht)
	if cht:match("_bonecrush") or cht:match("_bc") then
		bonecrush2()
		bonecrush()
	end
end)

function antiq()
    game.Workspace["Wormhole"].TouchInterest:Destroy()
end

function antiq2()
    		game:GetService("StarterGui"):SetCore("SendNotification", {
			Title = "1tsJustCmds";
			Text = "Anti-Queue";
		})
end

Player.Chatted:connect(function(cht)
	if cht:match("_antiq") then
		antiq2()
		antiq()
	end
end)

function invis()
    local lplr = game.Players.LocalPlayer  
    Players = game.Players.LocalPlayer.Character
      Character = game.Players.LocalPlayer
      
      Players.Humanoid:EquipTool(Character.Backpack["Flash Strike"])
         Players["Flash Strike"]:Activate()
     lplr.Character["Flash Strike"].Activator.Animation:Destroy()
end

function invis1()
game:GetService("StarterGui"):SetCore("SendNotification", {
          Title = "1tsJustCmds";
          Text = "U are Invisible";
      })
end

Player.Chatted:connect(function(cht)
  if cht:match("_invis") then
invis1()
invis()
end
end)

function hidelvl()
    game.Players.LocalPlayer.Character:FindFirstChildOfClass("Model"):Destroy()
end

function hidelvl1()
     game:GetService("StarterGui"):SetCore("SendNotification", {
			Title = "1tsJustCmds";
			Text = "LvL hider";
		})
end

Player.Chatted:connect(function(cht)
	if cht:match("_hidelvl") then
hidelvl1()
hidelvl()
end
end)

function wings()
    while wait() do
	        pcall(function()
	            game.Players.LocalPlayer.Character:FindFirstChild('RebirthWings').Handle:Destroy()
	        end)
    end
end
function hidewingsx()
game:GetService("StarterGui"):SetCore("SendNotification", {
			Title = "1tsJustCmds";
			Text = "Wings Removed";
		})
end
Player.Chatted:connect(function(cht)
	if cht:match("_rwings") then
hidewingsx()
wings()
end
end)

function halo()
    while wait() do
	        pcall(function()
	            game.Players.LocalPlayer.Character:FindFirstChild('RealHalo').Handle:Destroy()
	        end)
    end
 end
function halox()
game:GetService("StarterGui"):SetCore("SendNotification", {
			Title = "1tsJustCmds";
			Text = "Halo Removed";
		})
end
Player.Chatted:connect(function(cht)
	if cht:match("_rhalo") then
halox()
halo()
end
end)

function godmode()
    game:GetService("RunService").Stepped:Connect(function()
firetouchinterest(game.Players.LocalPlayer.Character.HumanoidRootPart, game.Workspace.Touchy.Part, 0)
firetouchinterest(game.Players.LocalPlayer.Character.HumanoidRootPart, game.Workspace.Touchy.Part, 1)
if game.Players.LocalPlayer.PlayerGui:FindFirstChild("Popup") then
game.Players.LocalPlayer.PlayerGui.Popup:Remove()
end end)
end

function godmode2()
    		game:GetService("StarterGui"):SetCore("SendNotification", {
			Title = "1tsJustCmds";
			Text = "Godmode Only Earth";
		})
end
Player.Chatted:connect(function(cht)
	if cht:match("_godmode") or cht:match("_gm") then
		godmode2()
		godmode()
	end
end)

function commands()
	print ("-----------------------------------------Version 2.0-----------------------------------------")
    print ("_freeze Press K")
    print ("_dc for dragoncrush glich (Press K)")
	print ("_dt for dragonthrow glich (Press K)")
    print ("_rj for rejoin")
    print ("_gm (only earth)")
    print ("_rhalo for remove halo")
    print ("_rwings for remove wings")
    print ("_hidelvl hide level")
    print ("_invis become invisible")
    print ("_antiq antiqueue")
    print ("_bonecrush / =bc for bc glich")
    print ("_re fast reset (only earth)")
    print ("_god for GOD form and UI and MUI")
    print ("_iy for infinite Yield")
    print ("_anch for anchor")
    print ("_unanch for unanchor")
    print ("_earth")
	print ("_namek")
	print ("_space")
	print ("_future")
	print ("_secret") 
	print ("_zaros")
	print ("_queue")
	print ("_heaven")
	print ("_south for tp south city")
	print ("_west tp west city")
	print ("_central tp central city")
	print ("_tower for tp in tower")
	print ("_hr for hard reset")
	print ("_1tsjusthub for use my hub")
	print ("_qk for queue kick")
	print ("_slot and select u the slot after")
	print ("_afk for anti afk")
	print ("_akick for anti kick")
	print ("_beerus / _ber for beerus animation")
	print ("_aglich for anti glich")
    print ("_de for glich player down earth")
	print ("_ms for melee spam and _sms for stop")
	print ("melee spam on but you have to have all the moves written in the cmds to make spam work")
	print ("moves for works it Meteor Crash, Anger Rush, Neo Wolf Fang Fist, Wolf Fang Fist,")
	print ("Mach Kick, Strong Kick, Kick Barrage, God Slicer, Deadly Dance")


end

Player.Chatted:connect(function(cht)
	if cht:match("_cmds") then
		commands()
	end
end)

function IY()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()

end

Player.Chatted:connect(function(cht)
	if cht:match("_iy") then
		IY()
	end
end)

function anch1()
    game.Players.LocalPlayer.Character.HumanoidRootPart.Anchored = true 

end

function anch()
     game:GetService("StarterGui"):SetCore("SendNotification", {
			Title = "1tsJustCmds";
			Text = "Anchored Player";
		})
end

Player.Chatted:connect(function(cht)
	if cht:match("_anch") or cht:match("_anchor") then
        anch1()
        anch()
    end
end)

function unanch1()
    game.Players.LocalPlayer.Character.HumanoidRootPart.Anchored = false 

end

function unanch()
     game:GetService("StarterGui"):SetCore("SendNotification", {
			Title = "1tsJustCmds";
			Text = "Unanchored Player";
		})
end

Player.Chatted:connect(function(cht)
	if cht:match("_unanch") or cht:match("_unanchor") then
        unanch1()
        unanch()
    end
end)

function earth()
    game:GetService("TeleportService"):Teleport(536102540)
end



Player.Chatted:connect(function(cht)
	if cht:match("_earth") then
		earth()
	end
end)

function namek()
    game:GetService("TeleportService"):Teleport(882399924)
end



Player.Chatted:connect(function(cht)
	if cht:match("_namek") then
		namek()
	end
end)

function space()
    game:GetService("TeleportService"):Teleport(478132461)
end



Player.Chatted:connect(function(cht)
	if cht:match("_space") then
		space()
	end
end)

function future()
    game:GetService("TeleportService"):Teleport(569994010)
end



Player.Chatted:connect(function(cht)
	if cht:match("_future") then
		future()
	end
end)

function secret()
    game:GetService("TeleportService"):Teleport(2046990924)
end



Player.Chatted:connect(function(cht)
	if cht:match("_secret") then
		secret()
	end
end)

function zaros()
    game:GetService("TeleportService"):Teleport(2651456105)
end



Player.Chatted:connect(function(cht)
	if cht:match("_zaros") then
		zaros()
	end
end)

function queue()
    game:GetService("TeleportService"):Teleport(3565304751)
end



Player.Chatted:connect(function(cht)
	if cht:match("_queue") then
		queue()
	end
end)

function heaven()
    game:GetService("TeleportService"):Teleport(3552157537)
end



Player.Chatted:connect(function(cht)
	if cht:match("_heaven") then
		heaven()
	end
end)

function hardreset()
	local Player = game:GetService("Players").LocalPlayer
	local Mouse = Player:GetMouse()
	
		   Player.Character.Humanoid.Health = 0
	
end

local Player = game.Players.LocalPlayer
Player.Chatted:connect(function(cht)
	if cht:match("_hr") then
		hardreset()
	end
end)

function myhub()
loadstring(game:HttpGet(("https://raw.githubusercontent.com/gp1tsJust/1tsJustHub-V2-DBZ/main/README.md"), true))()
	
end

local Player = game.Players.LocalPlayer
Player.Chatted:connect(function(cht)
	if cht:match("_1tsjusthub") then
		myhub()
	end
end)

function queue1()
    local plr = game:GetService("Players").LocalPlayer
	local mouse = plr:GetMouse()
	local place = game.PlaceId
	Character = game.Players.LocalPlayer
	Players = game.Players.LocalPlayer.Character
	MouseFunction = game:GetService("Players").LocalPlayer:GetMouse()


	mouse.KeyDown:connect(function(key)

		if key == "k" then
			Players.Humanoid:EquipTool(Character.Backpack["Dragon Crush"])
			Players["Dragon Crush"]:Activate()
			game.Workspace.Live[Character.Name]["Dragon Crush"].Activator["Flip"]:Destroy()
			
			wait (0.2)
			
			game.Workspace["Wormhole"].TouchInterest:Destroy()
			
			wait(2)
			
			game:GetService("TweenService"):Create(
           game.Players.LocalPlayer.Character.HumanoidRootPart,
           TweenInfo.new(1.2, Enum.EasingStyle.Linear, Enum.EasingDirection.Out),
           {CFrame = CFrame.new(2656.7854, 3946.00439, -2515.78467, 0.969526529, 0, -0.244986445, -0, 1, -0, 0.244986445, 0, 0.969526529)}
           ):Play()
       
            wait(2.3)
			
			game:GetService("TweenService"):Create(
           game.Players.LocalPlayer.Character.HumanoidRootPart,
           TweenInfo.new(1.2, Enum.EasingStyle.Linear, Enum.EasingDirection.Out),
           {CFrame = CFrame.new(2656.7854, 3946.00439, -2515.78467, 0.969526529, 0, -0.244986445, -0, 1, -0, 0.244986445, 0, 0.969526529)}
           ):Play()
       
            wait(2.3)
			
			game:GetService("TweenService"):Create(
           game.Players.LocalPlayer.Character.HumanoidRootPart,
           TweenInfo.new(1.2, Enum.EasingStyle.Linear, Enum.EasingDirection.Out),
           {CFrame = CFrame.new(2656.7854, 3946.00439, -2515.78467, 0.969526529, 0, -0.244986445, -0, 1, -0, 0.244986445, 0, 0.969526529)}
           ):Play()
            
            
            

		end
	end)
end 
function queue2()
game:GetService("StarterGui"):SetCore("SendNotification", {
Title = "1tsJustCmds";
Text = "Queue Kick Press K";
})
end
local Player = game.Players.LocalPlayer
Player.Chatted:connect(function(cht)
if cht:match("_qk") then
queue2()
queue1()
end
end)

function south()
	game:GetService("TweenService"):Create(
		game.Players.LocalPlayer.Character.HumanoidRootPart,
		TweenInfo.new(1.2, Enum.EasingStyle.Linear, Enum.EasingDirection.Out),
		{CFrame = CFrame.new(-456, 28, -6412)}
		):Play()
		
	end
	
	local Player = game.Players.LocalPlayer
	Player.Chatted:connect(function(cht)
		if cht:match("_south") then
			south()
		end
	end)

	function west()
		game:GetService("TweenService"):Create(
			game.Players.LocalPlayer.Character.HumanoidRootPart,
			TweenInfo.new(1.2, Enum.EasingStyle.Linear, Enum.EasingDirection.Out),
			{CFrame = CFrame.new(-570, 23, -2884)}
			):Play()
			
		end
		
		local Player = game.Players.LocalPlayer
		Player.Chatted:connect(function(cht)
			if cht:match("_west") then
				west()
			end
		end)

		function centrals()
			game:GetService("TweenService"):Create(
				game.Players.LocalPlayer.Character.HumanoidRootPart,
				TweenInfo.new(1.2, Enum.EasingStyle.Linear, Enum.EasingDirection.Out),
				{CFrame = CFrame.new(-3834, 23, -1428)}
				):Play()
				
			end
			
			local Player = game.Players.LocalPlayer
			Player.Chatted:connect(function(cht)
				if cht:match("_central") then
					centrals()
				end
			end)


			function slot()
				-- Script generated by SimpleSpy - credits to exx#9394

local args = {
    [1] = workspace.FriendlyNPCs:FindFirstChild("Character Slot Changer")
}

game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatStart:FireServer(unpack(args))

wait(0.6)

-- Script generated by SimpleSpy - credits to exx#9394

local args = {
    [1] = {
        [1] = "Yes"
    }
}

game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance:FireServer(unpack(args))

wait(0.5)

-- Script generated by SimpleSpy - credits to exx#9394

local args = {
    [1] = {
        [1] = "k"
    }
}

game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance:FireServer(unpack(args))


					
				end
				
				local Player = game.Players.LocalPlayer
				Player.Chatted:connect(function(cht)
					if cht:match("_slot") then
						slot()
					end
				end)



				function afk()
					wait(0.5)local ba=Instance.new("ScreenGui")
local ca=Instance.new("TextLabel")local da=Instance.new("Frame")
local _b=Instance.new("TextLabel")local ab=Instance.new("TextLabel")ba.Parent=game.CoreGui
ba.ZIndexBehavior=Enum.ZIndexBehavior.Sibling;ca.Parent=ba;ca.Active=true
ca.BackgroundColor3=Color3.new(0.176471,0.176471,0.176471)ca.Draggable=true
ca.Position=UDim2.new(0.698610067,0,0.098096624,0)ca.Size=UDim2.new(0,370,0,52)
ca.Font=Enum.Font.SourceSansSemibold;ca.Text="Anti AFK Script"ca.TextColor3=Color3.new(0,1,1)
ca.TextSize=22;da.Parent=ca
da.BackgroundColor3=Color3.new(0.196078,0.196078,0.196078)da.Position=UDim2.new(0,0,1.0192306,0)
da.Size=UDim2.new(0,370,0,107)_b.Parent=da
_b.BackgroundColor3=Color3.new(0.176471,0.176471,0.176471)_b.Position=UDim2.new(0,0,0.800455689,0)
_b.Size=UDim2.new(0,370,0,21)_b.Font=Enum.Font.Arial;_b.Text="Made by Dynamic. (please subscribe)"
_b.TextColor3=Color3.new(0,1,1)_b.TextSize=20;ab.Parent=da
ab.BackgroundColor3=Color3.new(0.176471,0.176471,0.176471)ab.Position=UDim2.new(0,0,0.158377,0)
ab.Size=UDim2.new(0,370,0,44)ab.Font=Enum.Font.ArialBold;ab.Text="Status: Active"
ab.TextColor3=Color3.new(0,1,1)ab.TextSize=20;local bb=game:service'VirtualUser'
game:service'Players'.LocalPlayer.Idled:connect(function()
bb:CaptureController()bb:ClickButton2(Vector2.new())
ab.Text="Roblox Tried to kick you but we didnt let them kick you :D"wait(2)ab.Text="Status : Active"end)
						
					end
					
					local Player = game.Players.LocalPlayer
					Player.Chatted:connect(function(cht)
						if cht:match("_afk") then
							afk()
						end
					end)


					function akick()
						_, Protected_by_MoonSecV2, Discord = 'discord.gg/gQEH2uZxUk'


,nil,nil;(function() _msec=(function(e,d,l)local R=d["قنجټڝسڪنسقآڪحكحكڝجز"];local H=l[e[(641+-0x19)]][e["دكؠككؠنن؃نؠ"]];local i=(0x74-112)/(42+(-35-(0x49+(-0x5b+23))))local x=(37-(0xc1-(19750/0x7d)))-(32-0x1f)local p=l[e[(30736/0xe2)]][e["قڝڝڪنئجؠ"]];local g=(-69+(0x438a/(0x438a/70)))+(-49+0x33)local _=l[e[(0x45e-585)]][e["ؠ؃نكضآئ؃نټآڝآزسزئسج"]]local n=(0x78/60)-(112/(144+(-43+0xb)))local m=(0x21-(((-0x13+1)+0x687)/57))local B=((64240/(144+(-0x34+18)))/0x92)local v=((-0x64+(482-((62866/0x56)-0x1ad)))+-76)local u=(0x1c+(((0x1c88-3692)/84)+-67))local y=((168-(-0x59+(-0x36+255)))-52)local S=(49-((21172-(0x5334-10703))/0xeb))local t=((-63+(-0x29+(986-0x21a)))/0xac)local f=(0x1d4/((-82+(0x1c57-3663))/15))local U=(((-0x18+(-0x1c+2))+114)/32)local b=(492/(-0x55+((5676650/0x62)/0xaf)))local c=(0x29+(0x1a+(((-0x1fc16ffa/233)/246)/143)))local k=((((-9817500/0xaf)+28016)/0xee)+120)local h=((((-122+0x33b)-0x174)-201)-129)local C=(47-(((-184+0x44)+234)-74))local O=(0xc6/(((0x261+-106)-0x112)-0xa3))local D=(282/(0x2a98/(0xbd+(-9782/0x86))))local N=(51+((12+(-0x23be/183))-10))local w=((0x1c6-(0x1728/(95-0x47)))/69)local K=e[(-123+0x5d6)];local Q=l[e[(-0x4d+213)]][e["آنجآؠح؃حجټآزڪسدق؃ق"]];local G=l[(function(e)return type(e):sub(1,1)..'\101\116'end)('ؠڪڪض؃آجق')..'\109\101'..('\116\97'or'ڝحسئدؠسئ')..e[(74620/0x8c)]];local A=l[e[(-0x38+589)]][e["نئڝئسسدجدزحدحض"]];local j=(62-0x3c)-(((0x780/12)+-0x66)+-0x38)local s=((((145684/0x56)/14)-70)-0x31)-(-122+0x7c)local Y=l[e[(31144/0xe5)]][e["ئنؠټ؃ټقڝآ"]];local d=function(d,e)return d..e end local L=(32-0x1c)*(0x1ec/(0xc6+(-126+0x33)))local V=l[e["ټ؃سآؠجحئكجققؠككض"]];local r=(0x5a-88)*(((0x25+-58)+324)-175)local J=((0x199a000/113)/232)*(56/(3472/(0x4354/139)))local W=(175-((35042-0x44a8)/142))local M=((0xa4+(-4114/0x22))-41)*(31-0x1d)local P=l[e["سزآدټقنآقضؠضكڪدحجضئ"]]or l[e[(0x262+-77)]][e["سزآدټقنآقضؠضكڪدحجضئ"]];local a=(0x155+(-88-(70+-0x49)))local e=l[e["؃كضسټكټؠ"]];local A=(function(a)local r,l=2,0x10 local d={j={},v={}}local o=-n local e=l+x while true do d[a:sub(e,(function()e=r+e return e-x end)())]=(function()o=o+n return o end)()if o==(L-n)then o=""l=j break end end local o=#a while e<o+x do d.v[l]=a:sub(e,(function()e=r+e return e-x end)())l=l+n if l%i==j then l=s A(d.j,(Y((d[d.v[s]]*L)+d[d.v[n]])))end end return _(d.j)end)("..:::MoonSec::..؃دحجئضسزقكنؠآټڪڝڪدن؃قزسڪؠآئجحج؃نڝدحؠحئدنټ؃ڪجآټنزنكدنڝزټڪآضڝجڝقڪڪؠئنټندقآسسئزج؃دكنجق؃سزئڪندقؠسئئڪئئحآددڪڝټؠؠؠڪټحج؃كڝ؃ټزدڝقككسزجضنئدقزسڪسئجڪجدد؃ڝضټنآآؠجكضدټڝآڪجآن؃كڪزڪئټقكئنكسجسنؠئټآؠزكڪقضآڝنسن؃كقزټجكض؃دضدټڪحڪزؠجټكجڪ؃ڪڝضټآ؃ئدق؃ضڪدقآكدكسززسس؃حجآدج؃كڪزټضآ؃ضجقسز؃ئكججدؠ؃دڪؠزكضحجكح؃سڝضټئئحزد؃ڪڝڪضؠكنآقؠقدضآئنحسزدكدزئسڪئضحآدجئټئسجسدجڪئڪآټقؠئكققحسجئقئحدڪ؃ؠڝدكڪضدجقدڝ؃سڪټټئآجڪحجآؠڪضآجڪحض؃آسزجؠحجدئڝئټټسحئئحؠدحئټئكجؠدنڝندضسسئنجددقسجضؠجنڪكؠ؃قحسكض؃كؠقززقئڝئححآ؃ضؠسټسؠټسآقؠضآجزحدڝحدآڪقڪټؠدنڪآجدزڝقټڝآسدس؃حڪڪآزؠؠنئئآ؃قڪضآآؠجڝكڪ؃ټؠؠئكككحزسض؃جزحنڪڪكقسڪضضجآز؃سؠضضجكجد؃زڪحټزآجنؠكدزددن؃ڝڝټټڪآآزټسكئقحڝدسئدضكجټدج؃ټڪكټسؠآ؃؃ح؃؃جڪنټددن؃؃ڝكڪ؃جقجڝحح؃كڝ؃حؠحجدټ؃؃قڝضؠئدحق؃ڝضضټڝآئنؠكحزكس؃ئزئحضضآزڪټآنؠدكقټحټننڪنسقڝسزضؠدزحآ؃زقحقجضججنحدزنضدئڪدڪدزڝڪټزآټنكقؠئقحئ؃ؠڝكټآآئؠ؃كئزكسئئسحڝدحنټآدكززڪسضكڝكقققسضجسجڪحن؃سڪنټئؠضكنكئز؃ضټئجحڝنسقڪزدضقجڝقټسڪسدئ؃زئنڝك؃ززضڪؠقن؃قضسجئڝحڝزنكنزټسئئؠكئكحزئئآسزؠسكآقجسنآدټدحج؃سڪټټئدڪ؃نڪنڪحنضئئحض؃آڝججټج؃دسڝحټزټدئزجحدحڝكڪ؃حڪدج؃كڪحآقؠقنزجئ؃سڪسآټؠئ؃حڪزټټؠزكآقآزؠؠزڪكؠنندققؠڝآقنآكقز؃ضضئټحض؃ؠنڪڪآآضؠزكحجدئضئڪجضدؠڪزڪ؃آضآكجضدزڝڪڪضجآدسڝؠڪټټئ؃دجټدټ؃ئڪؠحححض؃د؃؃ټجآزنڝحس؃ڪڝدټقؠڝڪڝڝ؃ڪجآكؠدحكد؃ڝزڪ؃ټسنآكجزنسسئقحڝدس؃ڝ؃ضآؠؠحكككجسزئڪجضدآ؃جڪنټدؠقكڝقسسټضئجؠحح؃كڝدټزؠڪنضقآزجسآئدحقد؃ڝسڪئآئنؠكحقؠس؃ئزحڝدضدئڪجآنؠدؠڪزڝسسئڪجئحئ؃حڪنټ؃آقكڪقكنجضججنحدددڪڝټزؠټنئكئزحضكئ؃حق؃ڪڝضټآآضؠؠكدزكضڝئنحټدئڝؠڝئحجؠ؃كقزڪسؠئآججدن؃دڪؠآڝؠزكټقئسؠضحجكجحضنڪڪټزؠآآققنزدضقئدجز؃ټڝزټؠآضنكك؃ززضڪزئحآدزڝنڪحآقنڝكسزټسئئؠجزدك؃جڪزآڪؠضنڪقجسنضزجقحح؃سڪټټئؠؠنحقكزضضزئ؃حض؃ڪڝجڪ؃آدنقكجزسندئئحآدحڝڪڪ؃آؠڪضكضزآسجقڪجددكڝڝڪسڪنؠئن؃قحسآض؃جزدڪدز؃حټجآ؃ندكسسڝضسجټئئسئڝحټڝآ؃نټقڪكزضآئجزئددڝټټڝآقنټكسزؠسقسآج؃دؠڝڪحكآآؠئكنقسسقضجسټدټ؃ئڪؠدسؠكندقزسڪزحجآحق؃نڝئټقؠڝنسكڝقنضؠئقحكدڪڝزټڪآضآآڪآزنسزئقجضدس؃ڝڪئآؠڝآككقضسزض؃جضدڪ؃جڝ؃ڝئؠقنجقسؠدضئجآحح؃ڪڝ؃ټؠڝضنضقآزجكڪئدحك؃ڝڝسڝنآئؠ؃كحزآس؃ئزحڪدز؃ټڪجټ؃ؠدكقزڝسسئټجئسض؃حڪڪټ؃ؠككڪقزسآضكضنحد؃ټڪڝدكؠټنضقؠزحضكئئضڪ؃ڪڝضټآ؃سننكحزقضڝسجحټدكڝؠڪضآكؠ؃كزك؃كؠئآجكدندڝڪقآڝؠسنڝقئسؠضكجكج؃؃زڪڪټضآڪنجقنزكضقضڝحس؃ټڝئټؠآحنككزززسضئضجئدج؃؃ڪدآقؠسكسننسئئآجحدك؃؃ڪؠ؃ضؠضكآقجكزضدجكدڝ؃نحئټئؠؠنحؠزز؃ضقجڪجزضڝڝجڪدآدؠڪقڝزسضټئئقسدحڝڝڪ؃آټنڪكآزآسكسنجددڪڝڝدقآټؠضكؠقحسكضئسڪدڪ؃ضڪآ؃ضؠننحققزجقټجټحئ؃ؠحضټكآدنزن؃قؠضآئكحنجئڝقټڝآسنټټڪزؠسزئكجحدز؃؃ڪضټحټسكنقضسقكججسدڪ؃ئڝ؃ټحؠټټزقزسڪضضق؃حج؃ؠڝدټقټآنسكحزئضڪئححكد؃؃كڝئآضؠحكجكقسدئقحڝجسضسڪئټدؠحكڝق؃ققئڪجضسس؃جڪڝټدؠنكڝققسټضنضڪحح؃ټڝ؃دؠؠڪنسقآزقضنئضضڝ؃ڝڝسټټ؃قنؠكجزكس؃سئحڪدنڝآڪسآنؠدكقكدكقئټجندؠح؃ڪكټ؃ؠزؠڪقضسآضكجنحز؃ق؃ڪټسؠټنئقؠززضكئححزد؃ڝضټآآجننكضزقسئئسحټدئڝڝڪحآكؠ؃كزآحسضئټججدند؃ڪقټجؠسكټقئسؠضحجكحج؃زڝحټضؠټنجقنزدضڪضڝحسددڝئحكآحننك؃ززضڪئكسجدجڝنڪددسنڝكززټكئز؃جحدڪ؃؃ڝجآڪآحكآكضآئضدجټدڝ؃نڪټټئؠؠنحكحز؃ضزجڪحس؃آڝجټنټجؠڪقڝزؠضټسنحؠدحڝكڪسدكنڪكؠزآسضئنجحدق؃؃ڪسآټڪدكؠقحسكضحجزدڪ؃ضڪآحجؠننسققزدضسجڪحئ؃ڝحكټكآ؃نزټززضضټئججآحزڝقڪئآسآنكئزؠسحسكجئدز؃جڪضټدؠجكآقدزنئڝجسحئ؃ئدحټحؠكن؃قزسڪضضئدحجددڝدټنؠڝنسقټزئسدئححڝد؃ڝزټڪټزنآكجقدسدسآحڝدسڝټڪئآؠؠحن؃ق؃سقئڪجزدآججڪنټدؠڝكڝنحسټضڪجؠجئ؃كڝ؃ټڪؠڪنڪقآزجضنضجحق؃ڝڝڪټټڪدنؠكحزكزحئزحڪدڪڝآڪقآنؠدكققضؠقئټجڪدؠ؃جڪكټدؠزكڝقضسآق؃جنحد؃قڝضټسؠټنئقؠقڪضكئزحزدقڝضټڪآجننكدزقسضئسجئدئڝؠڪحټؠؠ؃كزقضسضز؃ججدن؃دڪقآڝؠسنئقئسآضحجؠح؃حزڪڪټضآجنجكدزدزئجڝئآ؃ټڝئڪحآحدزك؃زقضڪئڝحآدزجدڪدآقنڝ؃ئزټسضئؠئئحڝ؃؃ڪڪآڪټحكآقجسنزدزندڝ؃ټڪټټؠؠؠنئقكقحضزجڪحڪ؃آ؃ټټنآدنققڝزسضټئؠحؠدؠڝكڪحآزآڪكضزآسنئنجقدق؃؃ڪسټڝؠئكؠقؠسكضؠجزدڪ؃ضڪآټجؠننؠققسڝضسئدحئجؠڝحټكآننزكټزضز؃ئجضنددڝقڪكآسآئكئقجسحزكج؃دز؃قڪضڝئؠجؠضقدكقئڝجسحز؃ئ؃؃ټحټحن؃قزسڪضضئجحجدئڝدټكؠڝنسكسزئضؠئححند؃ڝزټڪآؠنآكجزنسدئقحڝدسڝڪڪئآؠؠحككقكسزئڪجضدټ؃جڪنټدؠقكڝقسسټضئض؃حح؃كڝ؃جڪآڝنضقآزجنټنسكسزجئئئآجقدئڝقڪحآجنقنحزڪسؠضدجټسجنحزڝسسئټزؠق؃زسجآجضحكدئڪڪآڝؠقدڪحض؃قڪڝټس؃س؃زڝنڪ؃حئئئحز؃ڪڝضئزحآ؃ټڝآڝقزسئسحټدئسټئئئددد؃نڝدآنآ؃كآزڪجؠدزڝڪڪآآڝؠزنجقزسټض؃جنحض؃قڝدننقنزدضقكحقؠقدجزئنجئ؃ڪكجنضضڪئضحآسآسكضسڪقد؃؃حڪنټجؠڪنسجكسزضسئحټض؃زڪآآټؠآكټقجحز؃ټحزج؃؃ضڪآټضآنؠدقؠقدضڝئسجنآقڝڝڪقآحؠنك؃ق؃سټئضحؠټآئزقسسجئنجدسؠزجئزجڝحق؃؃ڝئؠ؃آضن؃ڪق؃ضڪآټجؠنندققززكسنئحك؃ؠڝحټكحآدس؃ضټنآڪضڝجؠددڝقټڝحټدح؃قڪكآجؠسكضزنضڝضدجقح؃ڝڝڝضټ؃ؠڪكنح؃دئڪؠټحؠكڝجڪآټآؠكقنكحزڪضنجڪحق؃كڪڪڪقآئؠدكزڝئڝؠټڪآضنآڝنټؠآڪنټسئحسڝټڪئآؠڝزددڝضټضآزنقجآئزئڝئزدټ؃ؠڝضټټؠكنټقكددڝ؃ټزؠڪدكڝؠڪسآڪؠجكدزټضټزسآكنؠكحزكؠئؠ؃نحقدسدكضټ؃ؠدكقزڝټكآدنسقئز؃ض؃دڪؠڝكڪقضسآكزنڝكجسكسججڝحآدحجټزسضكئ؃حزسحضنضئجزنټكقزقضڝئسكئزكسڝئكحڪدڪ؃ټڝؠسسسڝججدن؃دڝنڝجؠسكڝقئزسضحجكح؃؃زڪڪټضؠڪنجقؠزدضنجڝجق؃ټڝئټڪآحؠقك؃ززضڪضزحآدجڝڪڪدټكنڝكسزټقئئؠجحدټ؃؃ڪؠآڪؠڝكآقجسنضدجټدڝ؃قڪټټئؠؠنحقكز؃ضؠجڪحن؃آڝجټنآدنققڝزكضټئئحؠدئڝك؃سآزنڪكقزآق؃ئنجحدق؃جڪسټدڪؠكؠقحسكسټجزدڝ؃ضڝڪڪكؠننئقققجضسجټحئ؃ؠئ؃ټكآجنزقڝزضضڪئجئنسنڝقڪحآسؠ؃كئزآسحسڝضڪدز؃دڪضڪزؠجكؠقدزټئڝجنضئ؃ئڪؠټحټئن؃ققسڪسزضححج؃ټڝدڪضؠڝنسقټكئكټئححآد؃ڝنټڪآزنآنضزنسدئټحڝدڪڝټڪئآؠؠحككق؃سنئڪجندآ؃ضڪنڝدؠقكڝقكسټضزجؠحق؃ك؃حټزؠڪننقآزڝضنئدحق؃ڝڝسټټآننؠكحزكسئئزضڪدضڝآڪكآنآدكققټسسزټجئدؠ؃قڪكڪجؠزنضقضكآضججنحز؃قڝحټسآحنئؠؠزحضكئسحزح؃ڝضڪضآجننكدزقسحئسججدئڝآڪحآكڪ؃كزقدسضئڝججدن؃دڪق؃ڪؠسن؃قئسټضحجكح؃؃زدضټضؠڝنجقنزدضقجڝحسحئڝئټڝآحنكك؃ززضڪئضحآدجڝڝڪدآقنڝكسزټسئئؠجحدآ؃؃ڪزآڪؠضكآقجسنضدجؠدڝ؃سڪټټئؠؠنحقكز؃ضزجڪحس؃آڝجټنآدنققڝزسضڪئضحؠدحڝكټټآآنڪكضزآټجؠآكنقسزجڪنآټؠئكؠكئزڝض؃جزدڪ؃سڪآټجؠنندنڝسڝضزجټحئ؃ؠڝحټكآ؃ڝزقڪزضضآئضحندحڝقټڝآڝنټكئزؠسجئكج؃دزڝڪڪضآآؠجكنقحسقئڝجسكټ؃كڪؠټحؠكد؃ڪنآڝآدنقحؠ؃نڝدټقؠڝنكقټزضضؠئححكد؃ڝزڝ؃ټؠنآكضزنسحئقحڝدس؃ججسآؠؠضككق؃سزئڝجضدڪ؃جڪنڝڪؠقكڝقسسڪضئجؠحح؃كدټټزؠڪنضقآزجضنئدحقضڝڝسټڝآئنټكحزنس؃ئزسټدضڝټڪجآآؠدكقزڝسسضسجئدؠ؃حڪنټ؃ؠزكڪقسسآضججنحض؃قڪڝټسسڝنكقؠزحضكنئقآز؃سنئجآسؠئكدزقضڝنڝن؃ق؃ضڪئڪجقحج؃آڝ؃آنؠججڝدن؃دڪقجقحكڝآڝ؃آنؠضنضقڝزنسجئزحدضضكسزدضقجڝقټزحسقجڪجددز؃جڪؠؠڝؠجن؃قس؃نڪدآقنڝنقكجسئئؠجحدؠ؃؃ڪزآڪؠؠنكقجسنضدئئدڝ؃زڪټټضؠؠنسآ؃ز؃ضزجڪجد؃آڝئټنټجؠڪقڝزسضټئزحؠدحڝكڪسټئنڪكضزآسڝئنجحدق؃؃ڪسټدڪؠكؠقحسكضآجزدڝ؃ضڝڪڪكؠنندققزجضسجټحئدددحټكآ؃نزكقزضضټئجحنددڝآدسآسنټكئقضسحئنج؃دؠجضڪضآآؠجنسقدسكئڝئقجج؃ئڪؠټحؠنن؃قزسڪزضكضحج؃نڝدټقؠڝننقټزئقحئححند؃ڝقټڪآضنآكجآئسدئقحڝدقڝټڪسآؠؠحڪسق؃سزئڪجضدآ؃جڪنټدآدكڝقسسټضضجؠحح؃كڝ؃ټزؠڪنضقآزئسحئدحق؃ڝئئڪدآئنؠكحټؠټكؠؠكجسجڝڝڪجآنؠد؃ؠڝئآققحجئدؠ؃حڪكؠئآجكڪقضسآؠسقټقززڝسئح؃جزڝآ؃ئآكآڪكنټكدئڝضټآآجدټ؃ضڪنآقؠئكئد؃ڝؠڪحآكؠ؃كززڪضضقؠسزدن؃دڪقآڝؠسكټڝئنؠجسجټح؃؃زڪڪجقحئ؃ئڝآكحضقجڝحسدڝ؃نټؠآضنككئززضڪئضحآسڪڝنڪئآقؠحكسزڪسئضدضحدك؃جڪزټضؠضكټقجسنضدجآضس؃سڪټټئآحنحقنز؃سكضئحض؃ڝڝجټڪآدنققڝزسؠقئئحڪدحڝآڪ؃آقنڪكضؠؠسجئټجددنڝڝڪسآټآسڪڪقحسآض؃جټدڪ؃ضڪآڪضټآندقآسڝضكجټحئ؃ؠ؃ئټكآ؃نآقڪزؠضآئجحنددڝقټڝآآنټكئزؠسحئكئحدزڝڪڪآآآؠككنقدسقضججسدټ؃كڪؠڪڝؠكندقزسڪزحجآحآ؃نڝضټقؠڝنسكڝكجضؠئآحكدضڝزټڪآضآآكجزنسؠئقجكدس؃ضڪئڪؠؠحككقؠسزئڪجضدڪ؃جڪنټدؠقنآقسزضضئجؠحح؃كڝ؃ټزآآنضكئزجضنئدحق؃ڝڝسڪقآئؠككحزؠس؃سزحڪدض؃زڪجټضؠدككزڝسسئټجئحس؃حڪؠټ؃ؠككڪقضسآضجئضحددجڪڝټكؠټآئقؠزحسئئ؃جح؃ڪڝآټآآجننكدقحضڝئقحټدسڝؠڪحآكؠ؃كؠزڪسڪئآجټدن؃دڪقآڝؠڝكټقزسؠضئجكئ؃؃زڪڪټقؠآنآقنزقضقئجقض؃ټڝكټؠآڝنككدززز؃ضؠحآدقڝنڪضآقنڝكسزټؠقئؠجزدك؃دڪزټحؠضكآآحسنضضجقحد؃سڪټټئؠؠنؠقكز؃ضزجڝحض؃آڝجټنآدنققڝزكضڝئئحؠدحئسڪ؃آزنڪكضزآسجئنجددض؃ئڪسآټؠئ؃ؠڪضآنؠآنججك؃ضڪآټجآآڝئققزدضسجڪحئ؃ؠڝحڪؠدجنزكدزضضټئجحندد؃نڝضآسؠدكئزټسحئكج؃دټض؃ڪضټدؠجكنقدسكئڝجندټ؃ئدقټحؠكن؃قكسڪضضجآحججزڝدټقؠڝنسقټزئضؠئحضسد؃ڝزټڪآقنآكجزنسدزضحڝدسڝټڪضآؠؠحككق؃ؠزئڪجكدآ؃ضڪنټحؠقنضكنسټضئجؠجك؃كڝدټزؠڝنضك؃ننضنئدحقحسڝسټڪآئؠدنسزكس؃ئزئضدضڝټڪجآؠؠدكآؠسسسئټجئجح؃حڪنټ؃ؠټؠحقضسټضجضدحد؃كڪڝټسؠټنقآحزحضكئ؃جڪ؃ڪڝسټآآج؃سكدزآضڝئقحټدزڝؠڪححضؠ؃كآزڪسقئآجضدن؃زڝآآڝؠنكټكؠسؠضججكحض؃زڝح؃آؠآنجقنققضقئ؃حس؃ټض؃ټؠآسنككحززسدئضحآسڝڝنڪسآقؠحكسزڝسئضدجڪدك؃ئڪزڪسؠضكټقجسڝضدجآضس؃سڪټټئټجنحقنز؃ضزئټحضد؃ڝجټنآدنققڝزسس؃ئئحڝدحڝنڪ؃آزنڪكضؠؠسجئڪجددنڝڝڪسآټؠئنئقحسكض؃جقدڪ؃ضڪآټئؠنندققسڝضسجټحئدحڝحټكآ؃نزؠئزضضآئجحؠددڝقټڝآسنټكئزؠسحئكج؃دزڝڪڪضآآؠجكنقدسقئڝجسدټ؃ئڪؠټحؠكن؃قنسڪضضجآحج؃نڝدټقؠڝنسقټزئضؠئححكد؃ڝزټڪآزنآكجزنسدئقحڝدسڝټڪضآؠؠحككق؃سزئڪجضدآ؃ضڪن");local _=(176-(23556/0x9c))local o=71 local l=n;local e={}e={[(0x4a-(253-0xb4))]=function()local e,d,n,x=p(A,l,l+g);l=l+M;o=(o+(_*M))%a;return(((x+o-(_)+r*(M*i))%r)*((i*J)^i))+(((n+o-(_*i)+r*(i^g))%a)*(r*a))+(((d+o-(_*g)+J)%a)*r)+((e+o-(_*M)+J)%a);end,[(102/0x33)]=function(e,e,e)local e=p(A,l,l);l=l+x;o=(o+(_))%a;return((e+o-(_)+J)%r);end,[((149+-0x61)-0x31)]=function()local d,e=p(A,l,l+i);o=(o+(_*i))%a;l=l+i;return(((e+o-(_)+r*(i*M))%r)*a)+((d+o-(_*i)+a*(i^g))%r);end,[(0x7e-122)]=function(d,e,l)if l then local e=(d/i^(e-n))%i^((l-x)-(e-n)+x);return e-e%n;else local e=i^(e-x);return(d%(e+e)>=e)and n or s;end;end,[(0x4f-74)]=function()local d=e[(238/0xee)]();local l=e[(246/0xf6)]();local c=n;local o=(e[(840/(532-0x142))](l,x,L+M)*(i^(L*i)))+d;local d=e[(852/0xd5)](l,21,31);local e=((-n)^e[(0x80-(5084/0x29))](l,32));if(d==s)then if(o==j)then return e*s;else d=x;c=j;end;elseif(d==(r*(i^g))-x)then return(o==s)and(e*(x/j))or(e*(s/j));end;return H(e,d-((a*(M))-n))*(c+(o/(i^W)));end,[((159+-0x59)-64)]=function(d,i,i)local i;if(not d)then d=e[(0x76+-117)]();if(d==s)then return'';end;end;i=Q(A,l,l+d-n);l=l+d;local e=''for d=x,#i do e=K(e,Y((p(Q(i,d,d))+o)%a))o=(o+_)%r end return e;end}local function A(...)return{...},V('#',...)end local function Q()local k={};local O={};local d={};local U={k,O,nil,d};local l={}local t=(0x6c+-89)local o={[(0/0x74)]=(function(d)return not(#d==e[(117-0x73)]())end),[(123-0x79)]=(function(d)return e[(-113+(0xf0+-122))]()end),[(-0x5f+98)]=(function(d)return e[(-0x35+59)]()end),[(0x21-32)]=(function(d)local l=e[(27+-0x15)]()local d=''local e=1 for o=1,#l do e=(e+t)%a d=K(d,Y((p(l:sub(o,o))+e)%r))end return d end)};local d=e[(-69+0x46)]()for d=1,d do local e=e[(127+-0x7d)]();local n;local e=o[e%(124-0x63)];l[d]=e and e({});end;for r=1,e[(0xc1/193)]()do local d=e[(48/0x18)]();if(e[(46-0x2a)](d,n,x)==j)then local O=e[((517-0x131)/0x35)](d,i,g);local o=e[(768/0xc0)](d,M,i+M);local d={e[(0x1a+-23)](),e[(357/0x77)](),nil,nil};local a={[(0x0/45)]=function()d[N]=e[(0x24+-33)]();d[B]=e[(74-0x47)]();end,[(133/0x85)]=function()d[C]=e[(0x57/87)]();end,[(-118+0x78)]=function()d[D]=e[(20/0x14)]()-(i^L)end,[((0x9171/197)/63)]=function()d[w]=e[(0x66+-101)]()-(i^L)d[u]=e[(-88+(-0x33+142))]();end};a[O]();if(e[(86+-0x52)](o,x,n)==x)then d[b]=l[d[c]]end if(e[(944/0xec)](o,i,i)==n)then d[h]=l[d[N]]end if(e[(0x1dc/119)](o,g,g)==x)then d[S]=l[d[S]]end k[r]=d;end end;for e=x,e[(-98+0x63)]()do O[e-x]=Q();end;U[3]=e[(-0x11+19)]();return U;end;local function j(e,s,_)local o=e[i];local l=e[g];local e=e[n];return(function(...)local r=e;local a=l;local e=n e*=-1 local M=e;local l={};local L={};local p=o;local A=A local o=n;local Y={...};local g={};local J=V('#',...)-x;for e=0,J do if(e>=a)then g[e-a]=Y[e+x];else l[e]=Y[e+n];end;end;local J=J-a+n local e;local a;while true do e=r[o];a=e[(-61+0x3e)];d=(9257775)while(150-0x65)>=a do d-= d d=(1865077)while(0x558/57)>=a do d-= d d=(902580)while(77/0x7)>=a do d-= d d=(13177338)while(0x352/170)>=a do d-= d d=(707795)while(20-0x12)>=a do d-= d d=(6884948)while(-44+0x2c)>=a do d-= d local e=e[c]local o,d=A(l[e](l[e+x]))M=d+e-n local d=0;for e=e,M do d=d+n;l[e]=o[d];end;break;end while 1946==(d)/((7117-0xdfb))do d=(198806)while a>((24948/0xfc)-98)do d-= d local d=e[k]l[d](P(l,d+x,e[C]))break end while(d)/(((388885/0xcd)-0x3c8))==214 do do return end;break end;break;end break;end while(d)/((0x7a2-1019))==757 do d=(5849904)while a<=(125+-0x7a)do d-= d l[e[b]]=(e[C]~=0);break;end while(d)/((19296/0x6))==1819 do d=(1633398)while(0x18-20)<a do d-= d local e=e[c]l[e](l[e+x])break end while(d)/((0x292+-99))==2922 do local a;local d;d=e[k];a=l[e[h]];l[d+1]=a;l[d]=a[e[u]];o=o+n;e=r[o];l[e[c]]=e[N];o=o+n;e=r[o];d=e[c]l[d]=l[d](P(l,d+n,e[D]))o=o+n;e=r[o];for e=e[k],e[O]do l[e]=nil;end;o=o+n;e=r[o];l[e[U]]=_[e[h]];o=o+n;e=r[o];d=e[b]l[d]=l[d]()o=o+n;e=r[o];l[e[c]][e[N]]=e[S];o=o+n;e=r[o];l[e[c]]=_[e[D]];o=o+n;e=r[o];l[e[b]]=_[e[D]];o=o+n;e=r[o];l[e[f]]=e[w];break end;break;end break;end break;end while 3574==(d)/((0xb3211/199))do d=(7071120)while(0x62-90)>=a do d-= d d=(2045745)while(44-0x26)>=a do d-= d local e=e[f];do return l[e](P(l,e+1,M))end;break;end while 845==(d)/((0x9ec+-119))do d=(1361241)while(-0x22+41)<a do d-= d l[e[c]][e[h]]=e[m];break end while 2583==(d)/(((0x2e81e/171)-0x24b))do local o=e[D];local d=l[o]for e=o+1,e[v]do d=d..l[e];end;l[e[c]]=d;break end;break;end break;end while(d)/(((0xe5903/121)-3928))==1840 do d=(3062158)while(1287/0x8f)>=a do d-= d do return end;break;end while(d)/((4032-0x7f9))==1538 do d=(10030104)while a>(0x41-55)do d-= d if(l[e[k]]==e[B])then o=o+x;else o=e[C];end;break end while(d)/(((0x1c69+-125)-3620))==2843 do for e=e[c],e[h]do l[e]=nil;end;break end;break;end break;end break;end break;end while 2940==(d)/((0x2c2-399))do d=(6666637)while(57-0x28)>=a do d-= d d=(725253)while(2590/0xb9)>=a do d-= d d=(2245315)while a<=((59940/0x2d)/0x6f)do d-= d if(l[e[b]]~=l[e[B]])then o=o+x;else o=e[w];end;break;end while 2689==(d)/((1718-0x373))do d=(1271034)while a>(767/0x3b)do d-= d o=e[D];break end while 1758==(d)/((1470-0x2eb))do if not l[e[c]]then o=o+x;else o=e[O];end;break end;break;end break;end while 1601==(d)/((941-0x1e8))do d=(4845888)while(0x6ea/118)>=a do d-= d l[e[b]]=(e[D]~=0);o=o+x;break;end while 2148==(d)/((0x1206-2358))do d=(8247456)while(3760/0xeb)<a do d-= d l[e[b]]=j(p[e[C]],nil,_);break end while(d)/((392736/0x60))==2016 do l[e[U]]=l[e[w]][e[S]];break end;break;end break;end break;end while 1783==(d)/((7522-0xec7))do d=(1627692)while a<=(3180/0x9f)do d-= d d=(224688)while a<=(2178/0x79)do d-= d local e=e[f];M=e+J-1;for d=e,M do local e=g[d-e];l[d]=e;end;break;end while 62==(d)/((3650+-0x1a))do d=(3352096)while a>(0x92+-127)do d-= d if(l[e[k]]==l[e[u]])then o=o+x;else o=e[O];end;break end while(d)/((-98+0xfae))==856 do local e=e[b]l[e]=l[e]()break end;break;end break;end while(d)/((0x353d/7))==836 do d=(833476)while((2541/0x15)+-99)>=a do d-= d d=(1355274)while a>(1134/0x36)do d-= d l[e[U]]=_[e[h]];break end while(d)/((0xe26-1871))==774 do if(l[e[c]]~=l[e[S]])then o=o+x;else o=e[h];end;break end;break;end while(d)/((0xff7+-41))==206 do d=(1573560)while a>(4669/(46284/0xe4))do d-= d l[e[f]]=e[O];break end while(d)/((2213+(-9702/0x63)))==744 do local a;local d;l[e[t]]=l[e[O]];o=o+n;e=r[o];d=e[b];M=d+J-1;for e=d,M do a=g[e-d];l[e]=a;end;o=o+n;e=r[o];d=e[U];do return l[d](P(l,d+1,M))end;o=o+n;e=r[o];d=e[c];do return P(l,d,M)end;o=o+n;e=r[o];do return end;break end;break;end break;end break;end break;end break;end while(d)/((0x2acd7/(491-0x124)))==2117 do d=(6956712)while(196-0xa0)>=a do d-= d d=(7286784)while((13254-0x1a1c)/0xdb)>=a do d-= d d=(591600)while a<=((815616/0xec)/0x80)do d-= d d=(15370290)while(-113+0x8a)>=a do d-= d local e=e[c]l[e]=l[e](l[e+x])break;end while 3915==(d)/((-0x5b+4017))do d=(12182760)while(2860/0x6e)<a do d-= d local e=e[k]l[e]=l[e](P(l,e+n,M))break end while(d)/((0x1ea0-3970))==3148 do if l[e[f]]then o=o+n;else o=e[O];end;break end;break;end break;end while 986==(d)/((0x13c68/135))do d=(3641880)while(7084/0xfd)>=a do d-= d local d;d=e[c]l[d]=l[d](P(l,d+n,e[C]))o=o+n;e=r[o];l[e[c]]=l[e[N]];o=o+n;e=r[o];l[e[b]]=_[e[O]];o=o+n;e=r[o];d=e[b]l[d]=l[d]()o=o+n;e=r[o];l[e[k]]=l[e[w]][e[u]];o=o+n;e=r[o];if(l[e[f]]==e[v])then o=o+x;else o=e[N];end;break;end while(d)/((306280/0xf7))==2937 do d=(1832916)while(0x95-120)<a do d-= d local d=e[b]l[d](P(l,d+x,e[D]))break end while 458==(d)/((0xc55d4/202))do l[e[b]]=l[e[h]];break end;break;end break;end break;end while 2048==(d)/((0x1c28-3650))do d=(10991784)while(0x906/70)>=a do d-= d d=(1110200)while(0x7b-92)>=a do d-= d local D;local a;local M;local d;l[e[f]]=_[e[O]];o=o+n;e=r[o];l[e[k]]=l[e[N]][e[u]];o=o+n;e=r[o];d=e[b];M=l[e[N]];l[d+1]=M;l[d]=M[e[B]];o=o+n;e=r[o];l[e[b]]=l[e[O]];o=o+n;e=r[o];l[e[k]]=l[e[h]];o=o+n;e=r[o];d=e[c]l[d]=l[d](P(l,d+n,e[h]))o=o+n;e=r[o];d=e[U];M=l[e[O]];l[d+1]=M;l[d]=M[e[u]];o=o+n;e=r[o];d=e[k]l[d]=l[d](l[d+x])o=o+n;e=r[o];a={l,e};a[x][a[i][f]]=a[n][a[i][y]]+a[x][a[i][w]];o=o+n;e=r[o];l[e[t]]=l[e[O]]%e[S];o=o+n;e=r[o];d=e[t]l[d]=l[d](l[d+x])o=o+n;e=r[o];M=e[h];D=l[M]for e=M+1,e[m]do D=D..l[e];end;l[e[f]]=D;o=o+n;e=r[o];a={l,e};a[x][a[i][c]]=a[n][a[i][u]]+a[x][a[i][N]];o=o+n;e=r[o];l[e[c]]=l[e[N]]%e[B];break;end while(d)/((0x50de8/(0x1b5f/77)))==305 do d=(11258324)while(-43+0x4b)<a do d-= d _[e[D]]=l[e[c]];o=o+n;e=r[o];l[e[t]]={};o=o+n;e=r[o];l[e[k]]={};o=o+n;e=r[o];_[e[O]]=l[e[b]];o=o+n;e=r[o];l[e[t]]=_[e[N]];o=o+n;e=r[o];if(l[e[f]]~=e[B])then o=o+x;else o=e[h];end;break end while(d)/(((0x1ada-3446)+-105))==3388 do if l[e[c]]then o=o+n;else o=e[w];end;break end;break;end break;end while 3343==(d)/((-107+0xd43))do d=(9199328)while(111+-0x4d)>=a do d-= d local x;local a;local d;l[e[U]]=e[D];o=o+n;e=r[o];l[e[k]]=e[D];o=o+n;e=r[o];l[e[c]]=#l[e[w]];o=o+n;e=r[o];l[e[U]]=e[w];o=o+n;e=r[o];d=e[t];a=l[d]x=l[d+2];if(x>0)then if(a>l[d+1])then o=e[h];else l[d+3]=a;end elseif(a<l[d+1])then o=e[D];else l[d+3]=a;end break;end while(d)/((4579-0x903))==4049 do d=(13234704)while a>(-127+0xa2)do d-= d local a;local i,h;local d;l[e[c]]=_[e[O]];o=o+n;e=r[o];d=e[U]l[d]=l[d]()o=o+n;e=r[o];l[e[k]]=_[e[O]];o=o+n;e=r[o];l[e[k]]=_[e[C]];o=o+n;e=r[o];l[e[b]]=l[e[D]][e[S]];o=o+n;e=r[o];l[e[t]]=l[e[D]];o=o+n;e=r[o];d=e[f]i,h=A(l[d](l[d+x]))M=h+d-n a=0;for e=d,M do a=a+n;l[e]=i[a];end;o=o+n;e=r[o];d=e[b]l[d]=l[d](P(l,d+n,M))o=o+n;e=r[o];if(l[e[f]]==e[v])then o=o+x;else o=e[w];end;break end while 3972==(d)/((0x1a27-3363))do local d=l[e[m]];if not d then o=o+x;else l[e[U]]=d;o=e[D];end;break end;break;end break;end break;end break;end while(d)/((116844/0x34))==3096 do d=(4263600)while a<=(-0x18+66)do d-= d d=(887448)while a<=(0x99-114)do d-= d d=(5820012)while a<=(165-0x80)do d-= d local e={l,e};e[n][e[i][c]]=e[i][m]+e[i][w];break;end while 3564==(d)/((0x13230/48))do d=(5535111)while a>(1596/0x2a)do d-= d l[e[f]]=s[e[O]];break end while 2231==(d)/((0xa15+-100))do l[e[U]]=s[e[C]];o=o+n;e=r[o];l[e[U]]=#l[e[h]];o=o+n;e=r[o];s[e[h]]=l[e[f]];o=o+n;e=r[o];l[e[c]]=s[e[h]];o=o+n;e=r[o];l[e[b]]=#l[e[w]];o=o+n;e=r[o];s[e[O]]=l[e[b]];o=o+n;e=r[o];do return end;break end;break;end break;end while 412==(d)/((504036/0xea))do d=(4998486)while(0x1748/149)>=a do d-= d l[e[k]]=_[e[h]];break;end while 1523==(d)/((-0x4a+3356))do d=(661320)while(-32+0x49)<a do d-= d l[e[t]]=#l[e[D]];break end while 3960==(d)/((-0x38+223))do local a=p[e[C]];local n;local d={};n=G({},{__index=function(l,e)local e=d[e];return e[1][e[2]];end,__newindex=function(o,e,l)local e=d[e]e[1][e[2]]=l;end;});for n=1,e[v]do o=o+x;local e=r[o];if e[(-51+0x34)]==45 then d[n-1]={l,e[N]};else d[n-1]={s,e[O]};end;L[#L+1]=d;end;l[e[f]]=j(a,n,_);break end;break;end break;end break;end while(d)/((3347-0x6c4))==2640 do d=(3378480)while a<=(0xbe-145)do d-= d d=(726660)while a<=(-113+0x9c)do d-= d l[e[f]][e[C]]=e[v];break;end while 495==(d)/((139460/0x5f))do d=(12060930)while a>(215-0xab)do d-= d l[e[U]]=l[e[h]];break end while 3635==(d)/((6744-0xd62))do local o=e[w];local d=l[o]for e=o+1,e[u]do d=d..l[e];end;l[e[c]]=d;break end;break;end break;end while(d)/((126000/0x4b))==2011 do d=(6547266)while(9635/0xcd)>=a do d-= d d=(30080)while a>(9108/0xc6)do d-= d local a;local d;l[e[k]]=(e[h]~=0);o=o+n;e=r[o];l[e[U]]=l[e[O]];o=o+n;e=r[o];l[e[t]]=_[e[D]];o=o+n;e=r[o];d=e[c]l[d]=l[d](l[d+x])o=o+n;e=r[o];a=l[e[S]];if not a then o=o+x;else l[e[k]]=a;o=e[h];end;break end while 640==(d)/((195-0x94))do if(l[e[b]]==e[S])then o=o+x;else o=e[N];end;break end;break;end while 2307==(d)/((0x4efcc/114))do d=(3270294)while a>(12096/0xfc)do d-= d l[e[b]]=(e[w]~=0);o=o+x;break end while 2243==(d)/((0x417f0/184))do for e=e[t],e[w]do l[e]=nil;end;break end;break;end break;end break;end break;end break;end break;end while 3425==(d)/((0x158a-2811))do d=(2290088)while(2664/0x24)>=a do d-= d d=(4438290)while(0x9f-98)>=a do d-= d d=(7878988)while(4675/0x55)>=a do d-= d d=(2968764)while(5096/(0xd1+-111))>=a do d-= d d=(1740167)while(0x9a-104)>=a do d-= d local d;l[e[c]]=_[e[N]];o=o+n;e=r[o];l[e[U]]=l[e[O]][e[y]];o=o+n;e=r[o];d=e[c]l[d]=l[d](l[d+x])o=o+n;e=r[o];l[e[c]]=l[e[C]];o=o+n;e=r[o];o=e[O];break;end while(d)/((1042-0x239))==3679 do d=(609900)while((0x153d-2734)/53)<a do d-= d if(l[e[t]]==l[e[B]])then o=o+x;else o=e[O];end;break end while 2850==(d)/((486-0x110))do local e={l,e};e[x][e[i][U]]=e[n][e[i][m]]+e[x][e[i][N]];break end;break;end break;end while 876==(d)/(((46483524/0x7f)/108))do d=(10378522)while a<=(0x1553/103)do d-= d local e=e[U]local o,d=A(l[e](l[e+x]))M=d+e-n local d=0;for e=e,M do d=d+n;l[e]=o[d];end;break;end while(d)/((-0x2b+2969))==3547 do d=(3233858)while(0x27a8/188)<a do d-= d o=e[w];break end while(d)/((0x50b58/248))==2426 do local d;local a;l[e[c]]=_[e[N]];o=o+n;e=r[o];l[e[k]]=e[w];o=o+n;e=r[o];l[e[b]]=e[C];o=o+n;e=r[o];a=e[w];d=l[a]for e=a+1,e[y]do d=d..l[e];end;l[e[k]]=d;o=o+n;e=r[o];if l[e[c]]then o=o+n;else o=e[C];end;break end;break;end break;end break;end while 2188==(d)/((0xe67+-86))do d=(3349985)while(0x98-94)>=a do d-= d d=(498168)while(0xe9-177)>=a do d-= d if not l[e[U]]then o=o+x;else o=e[D];end;break;end while 2442==(d)/((516-0x138))do d=(7468524)while(0xa05/45)<a do d-= d l[e[b]]={};break end while 3293==(d)/((0x4ac04/135))do local o=e[b];local d=l[e[O]];l[o+1]=d;l[o]=d[e[u]];break end;break;end break;end while 3743==(d)/(((0x184ae53/179)/0x9f))do d=(9017890)while(0x30a1/211)>=a do d-= d if(l[e[c]]~=e[B])then o=o+x;else o=e[C];end;break;end while 2741==(d)/(((-19+0x3aa3d)/73))do d=(3750229)while(0xb2+-118)<a do d-= d local e=e[t]l[e]=l[e](P(l,e+n,M))break end while(d)/((-0x58+1341))==2993 do local e=e[U];do return P(l,e,M)end;break end;break;end break;end break;end break;end while 1685==(d)/((0x423c6/103))do d=(5191362)while(0xdd-154)>=a do d-= d d=(9426596)while a<=(0xc4-132)do d-= d d=(7379330)while a<=(-49+0x6f)do d-= d local o=e[c];local d=l[e[h]];l[o+1]=d;l[o]=d[e[v]];break;end while(d)/((0x7ad+-68))==3890 do d=(12758064)while(159-0x60)<a do d-= d local d=e[U];local a=l[d+2];local n=l[d]+a;l[d]=n;if(a>0)then if(n<=l[d+1])then o=e[h];l[d+3]=n;end elseif(n>=l[d+1])then o=e[O];l[d+3]=n;end break end while 3504==(d)/((0x6aab8/120))do do return l[e[f]]end break end;break;end break;end while 3634==(d)/((44098/0x11))do d=(3013520)while a<=(12350/0xbe)do d-= d l[e[f]]=#l[e[w]];break;end while 2168==(d)/((1516+-0x7e))do d=(9482816)while a>(0x67+-37)do d-= d local d=e[b];local n=l[d]local a=l[d+2];if(a>0)then if(n>l[d+1])then o=e[O];else l[d+3]=n;end elseif(n<l[d+1])then o=e[w];else l[d+3]=n;end break end while(d)/((6912-0xda8))==2776 do local a;local d;d=e[t];a=l[e[w]];l[d+1]=a;l[d]=a[e[S]];o=o+n;e=r[o];l[e[c]]=e[w];o=o+n;e=r[o];d=e[b]l[d]=l[d](P(l,d+n,e[w]))o=o+n;e=r[o];d=e[f];a=l[e[h]];l[d+1]=a;l[d]=a[e[S]];o=o+n;e=r[o];l[e[f]]=e[N];o=o+n;e=r[o];l[e[k]]={};o=o+n;e=r[o];l[e[k]][e[h]]=e[S];o=o+n;e=r[o];l[e[f]][e[w]]=e[u];o=o+n;e=r[o];l[e[f]][e[N]]=e[B];o=o+n;e=r[o];l[e[t]][e[h]]=e[v];o=o+n;e=r[o];d=e[U]l[d](P(l,d+x,e[h]))break end;break;end break;end break;end while(d)/((1536+-0x7b))==3674 do d=(2748320)while(144+-0x4a)>=a do d-= d d=(5221024)while(0x1298/70)>=a do d-= d _[e[w]]=l[e[b]];break;end while(d)/((455008/0x76))==1354 do d=(7161165)while(197-0x80)<a do d-= d local e=e[k];M=e+J-1;for d=e,M do local e=g[d-e];l[d]=e;end;break end while 2805==(d)/((0x21a86/54))do l[e[k]][l[e[h]]]=l[e[y]];break end;break;end break;end while(d)/((0x681-893))==3560 do d=(9019655)while a<=((0x16b+-109)-0xb6)do d-= d d=(13623732)while a>((0x23+-79)+115)do d-= d if(l[e[U]]~=e[B])then o=o+x;else o=e[h];end;break end while(d)/((0x9e6d6/183))==3842 do do return l[e[U]]end break end;break;end while(d)/((0x130c-2493))==3785 do d=(300099)while(165+-0x5c)<a do d-= d local e=e[t]l[e]=l[e](l[e+x])break end while(d)/((250+-0x53))==1797 do local e={l,e};e[x][e[i][k]]=e[n][e[i][B]]+e[x][e[i][w]];break end;break;end break;end break;end break;end break;end while(d)/((69148/0x76))==3908 do d=(51240)while(9309/0x6b)>=a do d-= d d=(347886)while(20160/0xfc)>=a do d-= d d=(1505004)while a<=(0x1d7a/98)do d-= d d=(1495041)while(0xe4-153)>=a do d-= d l[e[b]]=j(p[e[O]],nil,_);break;end while 607==(d)/((0x9df+-64))do d=(923120)while a>(-125+0xc9)do d-= d s[e[D]]=l[e[t]];break end while 880==(d)/((0xe578/56))do local d=e[t];local n=l[d]local a=l[d+2];if(a>0)then if(n>l[d+1])then o=e[h];else l[d+3]=n;end elseif(n<l[d+1])then o=e[w];else l[d+3]=n;end break end;break;end break;end while(d)/((4597-0x928))==668 do d=(648748)while(0x8d6/29)>=a do d-= d local e=e[t]l[e]=l[e]()break;end while(d)/(((-0x14+143730)/70))==316 do d=(163804)while a>(-0x37+134)do d-= d local e=e[t]l[e](l[e+x])break end while(d)/((0xa97-1390))==124 do l[e[f]]=l[e[h]][l[e[m]]];break end;break;end break;end break;end while 1386==(d)/((548-0x129))do d=(4061982)while((0x211-277)-169)>=a do d-= d d=(7045200)while a<=(0x654/20)do d-= d local e=e[t];do return l[e](P(l,e+1,M))end;break;end while(d)/((255852/0x8a))==3800 do d=(7152579)while a>(0x113-193)do d-= d l[e[t]]=e[h];break end while 2317==(d)/((95697/0x1f))do local i=p[e[O]];local a;local d={};a=G({},{__index=function(l,e)local e=d[e];return e[1][e[2]];end,__newindex=function(o,e,l)local e=d[e]e[1][e[2]]=l;end;});for n=1,e[B]do o=o+x;local e=r[o];if e[(-0x36+55)]==45 then d[n-1]={l,e[w]};else d[n-1]={s,e[N]};end;L[#L+1]=d;end;l[e[U]]=j(i,a,_);break end;break;end break;end while(d)/((49968/0x18))==1951 do d=(4358628)while a<=(0xc9-116)do d-= d d=(4673634)while(0x1a94/81)<a do d-= d l[e[c]]=s[e[O]];break end while(d)/((3167+-0x2d))==1497 do l[e[k]][l[e[D]]]=l[e[B]];break end;break;end while 1476==(d)/((0x1781-3064))do d=(4395600)while(0x4c98/228)<a do d-= d l[e[b]]=l[e[h]]%e[S];break end while(d)/(((-0x6c+53568)/45))==3700 do local d=e[t]l[d]=l[d](P(l,d+n,e[C]))break end;break;end break;end break;end break;end while 420==(d)/((0x119-159))do d=(1095030)while(-38+0x83)>=a do d-= d d=(7752500)while(0x125-203)>=a do d-= d d=(5042976)while(0x5540/248)>=a do d-= d local e=e[U];do return P(l,e,M)end;break;end while(d)/((0x1235a/31))==2096 do d=(4822912)while a>((44447-0x570e)/0xf9)do d-= d _[e[h]]=l[e[b]];break end while 3676==(d)/((0xa80-1376))do l[e[c]]=l[e[w]][e[u]];break end;break;end break;end while 2215==(d)/((-45+0xdd9))do d=(1609920)while(-42+0x85)>=a do d-= d l[e[t]]=l[e[N]][l[e[y]]];break;end while 3440==(d)/((-0x1a+494))do d=(5822218)while a>(22540/0xf5)do d-= d l[e[c]]=l[e[C]]-l[e[B]];break end while 1471==(d)/((0xd58de/221))do l[e[k]]=l[e[N]]-l[e[v]];break end;break;end break;end break;end while 2645==(d)/((505+-0x5b))do d=(234094)while(0x109-169)>=a do d-= d d=(408133)while(0xa3+-69)>=a do d-= d local d=e[k]l[d]=l[d](P(l,d+n,e[D]))break;end while 121==(d)/((-90+0xd87))do d=(1006480)while a>(9025/0x5f)do d-= d l[e[c]]={};break end while 1840==(d)/((0xd166/98))do local d=e[U];local a=l[d+2];local n=l[d]+a;l[d]=n;if(a>0)then if(n<=l[d+1])then o=e[w];l[d+3]=n;end elseif(n>=l[d+1])then o=e[O];l[d+3]=n;end break end;break;end break;end while(d)/((0x19b-250))==1454 do d=(1629844)while(-0x58+186)>=a do d-= d d=(6899852)while(0x130-207)<a do d-= d local d=l[e[S]];if not d then o=o+x;else l[e[b]]=d;o=e[C];end;break end while(d)/((0x5206f/179))==3676 do s[e[C]]=l[e[t]];break end;break;end while(d)/((-123+0x5a7))==1231 do d=(8527725)while(135+-0x24)<a do d-= d local e={l,e};e[n][e[i][U]]=e[i][v]+e[i][h];break end while 2259==(d)/((3818+-0x2b))do l[e[U]]=l[e[O]]%e[S];break end;break;end break;end break;end break;end break;end break;end o+= x end;end);end;return j(Q(),{},R())()end)_msec({[(0x130-168)]='\115\116'..(function(e)return(e and'سڪڪئنؠسس')or'\114\105'or'\120\58'end)((108-0x67)==(123-0x75))..'\110g',["دكؠككؠنن؃نؠ"]='\108\100'..(function(e)return(e and'ئزڪئحنحټجسدئزقآض')or'\101\120'or'\119\111'end)((79-0x4a)==(0x306/129))..'\112',["قڝڝڪنئجؠ"]=(function(e)return(e and'ضضنآزئجڪ')and'\98\121'or'\100\120'end)((0x23-30)==(53-0x30))..'\116\101',["ئنؠټ؃ټقڝآ"]='\99'..(function(e)return(e and'قڝڪئڪڝدټ')and'\90\19\157'or'\104\97'end)((0x6d+-104)==(0xf3/81))..'\114',[(-109+0x282)]='\116\97'..(function(e)return(e and'جزز؃ڪح؃سسسڪقجضضڪ')and'\64\113'or'\98\108'end)((0xd2/35)==((956+-0x65)/171))..'\101',["آنجآؠح؃حجټآزڪسدق؃ق"]=(function(e)return(e and'حنؠزؠكدزضسئ')or'\115\117'or'\78\107'end)((387/0x81)==(0xb8-153))..'\98',["ؠ؃نكضآئ؃نټآڝآزسزئسج"]='\99\111'..(function(e)return(e and'سحټضآضنقدحؠح')and'\110\99'or'\110\105\103\97'end)((68+-0x25)==(0x79-(0xd3+-121)))..'\97\116',[(0x29f+-55)]=(function(e,d)return(e and'دؠڪحؠجضجڪكڪجڝڝ')and'\48\159\158\188\10'or'\109\97'end)((132+-0x7f)==(702/0x75))..'\116\104',[(-0x63+1470)]=(function(d,e)return((94-0x59)==(37+-0x22)and'\48'..'\195'or d..((not'\20\95\69'and'\90'..'\180'or e)))or'\199\203\95'end),["نئڝئسسدجدزحدحض"]='\105\110'..(function(e,d)return(e and'ټڝ؃ضڝز؃آآ؃زآنس')and'\90\115\138\115\15'or'\115\101'end)((-33+0x26)==(0xd90/112))..'\114\116',["سزآدټقنآقضؠضكڪدحجضئ"]='\117\110'..(function(e,d)return(e and'ئقدسضټڪ؃ټدسڪد')or'\112\97'or'\20\38\154'end)((0x4e7/251)==(0xac7/89))..'\99\107',["ټ؃سآؠجحئكجققؠككض"]='\115\101'..(function(e)return(e and'آسټندككؠجآجننحڝآضن؃')and'\110\112\99\104'or'\108\101'end)((0x154/(-53+0x79))==(4216/0x88))..'\99\116',["؃كضسټكټؠ"]='\116\111\110'..(function(e,d)return(e and'آزآحټضؠئڪ؃زنز')and'\117\109\98'or'\100\97\120\122'end)((0x131/61)==(110-0x69))..'\101\114'},{["قنجټڝسڪنسقآڪحكحكڝجز"]=((getfenv))},((getfenv))()) end)()



							
						end
						
						local Player = game.Players.LocalPlayer
						Player.Chatted:connect(function(cht)
							if cht:match("_akick") then
								akick()
							end
						end)


						function glic()
							if not game:IsLoaded() then
								game.Loaded:Wait()
								end
								
								local plr = game.Players.LocalPlayer
								
								while wait() do
									pcall(function()
										game:GetService("Workspace").Live[plr.Name].LowerTorso.BodyVelocity:Destroy()
									end)
								end

						end
						
						function glic2()
							game:GetService("StarterGui"):SetCore("SendNotification", {
								Title = "1tsJustCmds";
								Text = "anti glich loaded";
							})
						end
						local Player = game.Players.LocalPlayer
						Player.Chatted:connect(function(cht)
							if cht:match("_aglich") then
								glic()
								glic2()
							end
						end)


						function beeru()
							if not game:IsLoaded() then
								game.Loaded:Wait()
								end wait()
								
								player = game.Players.LocalPlayer while wait() do
								if game.Workspace.Live[player.Name].Animate.idle:FindFirstChild("Animation1") then
								game.Workspace.Live[player.Name].Animate.idle:FindFirstChild("Animation1").AnimationId = "rbxassetid://1171558651"
								if game.Workspace.Live[player.Name].Animate.walk:FindFirstChild("RunAnim") then
								game.Workspace.Live[player.Name].Animate.walk:FindFirstChild("RunAnim").AnimationId = "rbxassetid://1171558651"
								end end end
						end
						
						function beeru1()
							game:GetService("StarterGui"):SetCore("SendNotification", {
								Title = "1tsJustCmds";
								Text = "Beerus Animation Loaded";
							})
						end
						local Player = game.Players.LocalPlayer
						Player.Chatted:connect(function(cht)
							if cht:match("_beerus") or cht:match("_ber") then
								beeru()
								beeru1()
							end
						end)




