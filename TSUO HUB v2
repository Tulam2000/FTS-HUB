repeat wait(1) until game:IsLoaded()if string.lower(game:GetService("RbxAnalyticsService"):GetClientId()) == game:GetService("RbxAnalyticsService"):GetClientId() then
    local ScreenGui = Instance.new("ScreenGui")
    local ImageButton = Instance.new("ImageButton")

    ScreenGui.Parent = game:GetService("Players").LocalPlayer:WaitForChild("PlayerGui")

    ImageButton.Parent = ScreenGui
    ImageButton.BackgroundColor3 = Color3.fromRGB(15, 15, 15)
    ImageButton.Position = UDim2.new(0.120833337, 0, 0.0952890813, 0)
    ImageButton.Size = UDim2.new(0, 50, 0, 50)
    ImageButton.Image = "rbxassetid://13192570418"
    ImageButton.MouseButton1Down:connect(function()
        game:GetService("VirtualInputManager"):SendKeyEvent(true,305,false,game)
        game:GetService("VirtualInputManager"):SendKeyEvent(false,305,false,game)
    end)
end

local ScreenGui = Instance.new("ScreenGui")
local ImageButton = Instance.new("ImageButton")

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

ImageButton.Parent = ScreenGui
ImageButton.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
ImageButton.BorderSizePixel = 0
ImageButton.Position = UDim2.new(0.1208337, 0, 0.0952890813, 0)
ImageButton.Size = UDim2.new(0, 50, 0, 50)
ImageButton.Image = "rbxassetid://13192570418"
ImageButton.MouseButton1Down:connect(function()
    game:GetService("VirtualInputManager"):SendKeyEvent(true,305,false,game)
    game:GetService("VirtualInputManager"):SendKeyEvent(false,305,false,game)
end)







		repeat wait() until game.Players
		repeat wait() until game.Players.LocalPlayer
		repeat wait() until game.ReplicatedStorage
		repeat wait() until game.ReplicatedStorage:FindFirstChild("Remotes");
		repeat wait() until game.Players.LocalPlayer:FindFirstChild("PlayerGui");
		repeat wait() until game.Players.LocalPlayer.PlayerGui:FindFirstChild("Main");
		repeat wait() until game:GetService("Players")
		repeat wait() until game:GetService("Players").LocalPlayer.Character:FindFirstChild("Energy")
		
		wait(1)
		
		if not game:IsLoaded() then repeat game.Loaded:Wait() until game:IsLoaded() end
		--Team
		if game:GetService("Players").LocalPlayer.PlayerGui.Main:FindFirstChild("ChooseTeam") then
			repeat wait()
				if game:GetService("Players").LocalPlayer.PlayerGui:WaitForChild("Main").ChooseTeam.Visible == true then
					if _G.Team == "Pirate" then
						for i, v in pairs(getconnections(game:GetService("Players").LocalPlayer.PlayerGui.Main.ChooseTeam.Container.Pirates.Frame.ViewportFrame.TextButton.Activated)) do                                                                                                
							v.Function()
						end
					elseif _G.Team == "Marine" then
						for i, v in pairs(getconnections(game:GetService("Players").LocalPlayer.PlayerGui.Main.ChooseTeam.Container.Marines.Frame.ViewportFrame.TextButton.Activated)) do                                                                                                
							v.Function()
						end
					else
						for i, v in pairs(getconnections(game:GetService("Players").LocalPlayer.PlayerGui.Main.ChooseTeam.Container.Pirates.Frame.ViewportFrame.TextButton.Activated)) do                                                                                                
							v.Function()
						end
					end
				end
			until game.Players.LocalPlayer.Team ~= nil and game:IsLoaded()
		end
		local MyLevel = game.Players.LocalPlayer.Data.Level.Value
		task.spawn(function() 
			while true do task.wait(0.3);
			coroutine.wrap(function() 
			pcall(function() 
			game:GetService("ReplicatedStorage").RigControllerEvent:FireServer("weaponChange",tostring("Combat"));
			game:GetService("ReplicatedStorage").RigControllerEvent:FireServer("unequipWeapon",tostring("Combat"));
			end);
			end)();
			end;
			end);
		if game.PlaceId == 2753915549 then
			World1 = true
		elseif game.PlaceId == 4442272183 then
			World2 = true
		elseif game.PlaceId == 7449423635 then
			World3 = true
		else
			game.Players.LocalPlayer:Kick("????????????")
		end
		local placeId = game.PlaceId;
							 if placeId == 2753915549 then
								OldWorld = true;
							 elseif placeId == 4442272183 then
								NewWorld = true;
							 elseif placeId == 7449423635 then
								Three = true;
								do
								   local count = 0;
								   for i,v in pairs(game:GetService("Workspace").Map.Turtle:GetChildren()) do
									  if v.Name == "Model" and #v:GetChildren() >= 40 and v:FindFirstChild("Meshes/Plank7") and i > 20 then
										 v:Destroy()
										 count = count + 1
										 if count > 2 then
											break
										 end
									  end
								   end
								end
							 end
							 function CheckQuest()
								local MyLevel = game.Players.LocalPlayer.Data.Level.Value
								if OldWorld then
								   if MyLevel == 1 or MyLevel <= 9 then -- Bandit
									Ms = "Bandit [Lv. 5]"
									NaemQuest = "BanditQuest1"
									LevelQuest = 1
									NameMon = "Bandit"
									CFrameQuest = CFrame.new(1061.66699, 16.5166187, 1544.52905, -0.942978859, -3.33851502e-09, 0.332852632, 7.04340497e-09, 1, 2.99841325e-08, -0.332852632, 3.06188177e-08, -0.942978859)
									CFrameMon = CFrame.new(1199.31287, 52.2717781, 1536.91516, -0.929782331, 6.60215846e-08, -0.368109822, 3.9077392e-08, 1, 8.06501603e-08, 0.368109822, 6.06023249e-08, -0.929782331)
	
								elseif MyLevel == 10 or MyLevel <= 14 then -- Monkey
									magbring = 400
									Ms = "Monkey [Lv. 14]"
									NaemQuest = "JungleQuest"
									LevelQuest = 1
									NameMon = "Monkey"
									CFrameQuest = CFrame.new(-1604.12012, 36.8521118, 154.23732, 0.0648873374, -4.70858913e-06, -0.997892559, 1.41431883e-07, 1, -4.70933674e-06, 0.997892559, 1.64442184e-07, 0.0648873374)
									CFrameMon = CFrame.new(-1502.74609, 98.5633316, 90.6417007, 0.836947978, 0, 0.547282517, -0, 1, -0, -0.547282517, 0, 0.836947978)
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 1000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(1.5)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
								elseif MyLevel == 15 or MyLevel <= 29 then -- Gorilla
									magbring = 240
									Ms = "Gorilla [Lv. 20]"
									NaemQuest = "JungleQuest"
									LevelQuest = 2
									NameMon = "Gorilla"
									CFrameQuest = CFrame.new(-1604.12012, 36.8521118, 154.23732, 0.0648873374, -4.70858913e-06, -0.997892559, 1.41431883e-07, 1, -4.70933674e-06, 0.997892559, 1.64442184e-07, 0.0648873374)
									CFrameMon = CFrame.new(-1223.52808, 6.27936459, -502.292664, 0.310949147, -5.66602516e-08, 0.950426519, -3.37275488e-08, 1, 7.06501808e-08, -0.950426519, -5.40241736e-08, 0.310949147)
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 1000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(4)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
								elseif MyLevel == 30 or MyLevel <= 39 then -- Pirate
									Dis = 150
									Ms = "Pirate [Lv. 35]"
									NaemQuest = "BuggyQuest1"
									LevelQuest = 1
									NameMon = "Pirate"
									CFrameQuest = CFrame.new(-1139.59717, 4.75205183, 3825.16211, -0.959730506, -7.5857054e-09, 0.280922383, -4.06310328e-08, 1, -1.11807175e-07, -0.280922383, -1.18718916e-07, -0.959730506)
									CFrameMon = CFrame.new(-1219.32324, 4.75205183, 3915.63452, -0.966492832, -6.91238853e-08, 0.25669381, -5.21195496e-08, 1, 7.3047012e-08, -0.25669381, 5.72206496e-08, -0.966492832)
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 3000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(4)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
								elseif MyLevel == 40 or MyLevel <= 59 then -- Brute
									Dis = 150
									Ms = "Brute [Lv. 45]"
									NaemQuest = "BuggyQuest1"
									LevelQuest = 2
									NameMon = "Brute"
									CFrameQuest = CFrame.new(-1139.59717, 4.75205183, 3825.16211, -0.959730506, -7.5857054e-09, 0.280922383, -4.06310328e-08, 1, -1.11807175e-07, -0.280922383, -1.18718916e-07, -0.959730506)
									CFrameMon = CFrame.new(-1146.49646, 96.0936813, 4312.1333, -0.978175163, -1.53222057e-08, 0.207781896, -3.33316912e-08, 1, -8.31738873e-08, -0.207781896, -8.82843523e-08, -0.978175163)
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 3000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(4)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
								elseif MyLevel == 60 or MyLevel <= 74 then -- Desert Bandit
									Ms = "Desert Bandit [Lv. 60]"
									NaemQuest = "DesertQuest"
									LevelQuest = 1
									NameMon = "Desert Bandit"
									CFrameQuest = CFrame.new(897.031128, 6.43846416, 4388.97168, -0.804044724, 3.68233266e-08, 0.594568789, 6.97835176e-08, 1, 3.24365246e-08, -0.594568789, 6.75715199e-08, -0.804044724)
									CFrameMon = CFrame.new(932.788818, 6.4503746, 4488.24609, -0.998625934, 3.08948351e-08, 0.0524050146, 2.79967303e-08, 1, -5.60361286e-08, -0.0524050146, -5.44919629e-08, -0.998625934)
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 3000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(4)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
								elseif MyLevel == 75 or MyLevel <= 89 then -- Desert Officre
									Ms = "Desert Officer [Lv. 70]"
									NaemQuest = "DesertQuest"
									LevelQuest = 2
									NameMon = "Desert Officer"
									CFrameQuest = CFrame.new(897.031128, 6.43846416, 4388.97168, -0.804044724, 3.68233266e-08, 0.594568789, 6.97835176e-08, 1, 3.24365246e-08, -0.594568789, 6.75715199e-08, -0.804044724)
									CFrameMon = CFrame.new(1580.03198, 4.61375761, 4366.86426, 0.135744005, -6.44280718e-08, -0.990743816, 4.35738308e-08, 1, -5.90598574e-08, 0.990743816, -3.51534837e-08, 0.135744005)
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 3000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(4)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
								elseif MyLevel == 90 or MyLevel <= 99 then -- Snow Bandits
									Ms = "Snow Bandit [Lv. 90]"
									NaemQuest = "SnowQuest"
									LevelQuest = 1
									NameMon = "Snow Bandits"
									CFrameQuest = CFrame.new(1384.14001, 87.272789, -1297.06482, 0.348555952, -2.53947841e-09, -0.937287986, 1.49860568e-08, 1, 2.86358204e-09, 0.937287986, -1.50443711e-08, 0.348555952)
									CFrameMon = CFrame.new(1370.24316, 102.403511, -1411.52905, 0.980274439, -1.12995728e-08, 0.197641045, -9.57343449e-09, 1, 1.04655214e-07, -0.197641045, -1.04482936e-07, 0.980274439)
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 3000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(4)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
								elseif MyLevel == 100 or MyLevel <= 119 then -- Snowman
									Ms = "Snowman [Lv. 100]"
									NaemQuest = "SnowQuest"
									LevelQuest = 2
									NameMon = "Snowman"
									CFrameQuest = CFrame.new(1384.14001, 87.272789, -1297.06482, 0.348555952, -2.53947841e-09, -0.937287986, 1.49860568e-08, 1, 2.86358204e-09, 0.937287986, -1.50443711e-08, 0.348555952)
									CFrameMon = CFrame.new(1370.24316, 102.403511, -1411.52905, 0.980274439, -1.12995728e-08, 0.197641045, -9.57343449e-09, 1, 1.04655214e-07, -0.197641045, -1.04482936e-07, 0.980274439)
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 3000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(4)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
								elseif MyLevel == 120 or MyLevel <= 149 then -- Chief Petty Officer
									Ms = "Chief Petty Officer [Lv. 120]"
									NaemQuest = "MarineQuest2"
									LevelQuest = 1
									NameMon = "Chief Petty Officer"
									CFrameQuest = CFrame.new(-5035.0835, 28.6520386, 4325.29443, 0.0243340395, -7.08064647e-08, 0.999703884, -6.36926814e-08, 1, 7.23777944e-08, -0.999703884, -6.54350671e-08, 0.0243340395)
									CFrameMon = CFrame.new(-4882.8623, 22.6520386, 4255.53516, 0.273695946, -5.40380647e-08, -0.96181643, 4.37720793e-08, 1, -4.37274998e-08, 0.96181643, -3.01326679e-08, 0.273695946)
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 3000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(4)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
								elseif MyLevel == 150 or MyLevel <= 174 then -- Sky Bandit
									Ms = "Sky Bandit [Lv. 150]"
									NaemQuest = "SkyQuest"
									LevelQuest = 1
									NameMon = "Sky Bandit"
									CFrameQuest = CFrame.new(-4841.83447, 717.669617, -2623.96436, -0.875942111, 5.59710216e-08, -0.482416272, 3.04023082e-08, 1, 6.08195947e-08, 0.482416272, 3.86078725e-08, -0.875942111)
									CFrameMon = CFrame.new(-4970.74219, 294.544342, -2890.11353, -0.994874597, -8.61311236e-08, -0.101116329, -9.10836206e-08, 1, 4.43614923e-08, 0.101116329, 5.33441664e-08, -0.994874597)
									if _G.AutoFarm and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 1000 then
										game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(-4607.82275, 872.54248, -1667.55688))
									end
								elseif MyLevel == 175 or MyLevel <= 189 then -- Dark Master
									Ms = "Dark Master [Lv. 175]"
									NaemQuest = "SkyQuest"
									LevelQuest = 2
									NameMon = "Dark Master"
									CFrameQuest = CFrame.new(-4841.83447, 717.669617, -2623.96436, -0.875942111, 5.59710216e-08, -0.482416272, 3.04023082e-08, 1, 6.08195947e-08, 0.482416272, 3.86078725e-08, -0.875942111)
									CFrameMon = CFrame.new(-5220.58594, 430.693298, -2278.17456, -0.925375521, 1.12086873e-08, 0.379051805, -1.05115507e-08, 1, -5.52320891e-08, -0.379051805, -5.50948407e-08, -0.925375521)
									if _G.AutoFarm and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 1000 then
										game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(-4607.82275, 872.54248, -1667.55688))
									end
								elseif MyLevel == 190 or MyLevel <= 209 then -- Dark Master
									Ms = "Prisoner [Lv. 190]"
									NaemQuest = "PrisonerQuest"
									LevelQuest = 1
									NameMon = "Prisoner"
									CFrameQuest = CFrame.new(5310.61, 0.350015, 474.947)
									CFrameMon = CFrame.new(4977.88525390625, 72.67780303955078, 498.108642578125)
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 3000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(4)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
								elseif MyLevel == 210 or MyLevel <= 249 then -- Dark Master
									Ms = "Dangerous Prisoner [Lv. 210]"
									NaemQuest = "PrisonerQuest"
									LevelQuest = 2
									NameMon = "Dangerous Prisoner"
									CFrameQuest = CFrame.new(5310.61, 0.350015, 474.947)
									CFrameMon = CFrame.new(5656.42333984375, 72.67793273925781, 866.1055908203125)
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 3000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(4)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
								elseif MyLevel == 250 or MyLevel <= 299 then -- Toga Warrior
									Ms = "Toga Warrior [Lv. 250]"
									NaemQuest = "ColosseumQuest"
									LevelQuest = 1
									NameMon = "Toga Warrior"
									CFrameQuest = CFrame.new(-1576.11743, 7.38933945, -2983.30762, 0.576966345, 1.22114863e-09, 0.816767931, -3.58496594e-10, 1, -1.24185606e-09, -0.816767931, 4.2370063e-10, 0.576966345)
									CFrameMon = CFrame.new(-1779.97583, 44.6077499, -2736.35474, 0.984437346, 4.10396339e-08, 0.175734788, -3.62286876e-08, 1, -3.05844168e-08, -0.175734788, 2.3741821e-08, 0.984437346)
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 3000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(1.5)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
								elseif MyLevel == 300 or MyLevel <= 325 then -- Military Soldier
									Ms = "Military Soldier [Lv. 300]"
									NaemQuest = "MagmaQuest"
									LevelQuest = 1
									NameMon = "Military Soldier"
									CFrameQuest = CFrame.new(-5316.55859, 12.2370615, 8517.2998, 0.588437557, -1.37880001e-08, -0.808542669, -2.10116209e-08, 1, -3.23446478e-08, 0.808542669, 3.60215964e-08, 0.588437557)
									CFrameMon = CFrame.new(-5376.13867, 60.2465515, 8313.62305, -0.693342566, -1.01933502e-07, 0.720608115, -9.95837439e-08, 1, 4.56390268e-08, -0.720608115, -4.01173743e-08, -0.693342566)
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 3000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(1.5)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
								elseif MyLevel == 325 or MyLevel <= 374 then -- Military Spy
									FM = false
									Ms = "Military Spy [Lv. 325]"
									NaemQuest = "MagmaQuest"
									LevelQuest = 2
									NameMon = "Military Spy"
									CFrameQuest = CFrame.new(-5316.55859, 12.2370615, 8517.2998, 0.588437557, -1.37880001e-08, -0.808542669, -2.10116209e-08, 1, -3.23446478e-08, 0.808542669, 3.60215964e-08, 0.588437557)
									CFrameMon = CFrame.new(-5960.86182, 82.3629303, 8893.15625, 0.942766786, 8.98857095e-08, 0.333452851, -5.81543986e-08, 1, -1.05141325e-07, -0.333452851, 7.9731997e-08, 0.942766786)
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 3000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(1.5)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
								elseif MyLevel == 375 or MyLevel <= 399 then -- Fishman Warrior
									FM = true
									Ms = "Fishman Warrior [Lv. 375]"
									NaemQuest = "FishmanQuest"
									LevelQuest = 1
									NameMon = "Fishman Warrior"
									CFrameQuest = CFrame.new(61122.5625, 18.4716396, 1568.16504, 0.893533468, 3.95251609e-09, 0.448996574, -2.34327455e-08, 1, 3.78297464e-08, -0.448996574, -4.43233645e-08, 0.893533468)
									CFrameMon = CFrame.new(60946.6094, 48.6735229, 1525.91687, -0.0817126185, 8.90751153e-08, 0.996655822, 2.00889794e-08, 1, -8.77269599e-08, -0.996655822, 1.28533992e-08, -0.0817126185)
									if _G.AutoFarm and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 then
										game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(61163.8515625, 11.6796875, 1819.7841796875))
									end
								elseif MyLevel == 400 or MyLevel <= 449 then -- Fishman Commando
									FM = true
									Ms = "Fishman Commando [Lv. 400]"
									NaemQuest = "FishmanQuest"
									LevelQuest = 2
									NameMon = "Fishman Commando"
									CFrameQuest = CFrame.new(61122.5625, 18.4716396, 1568.16504, 0.893533468, 3.95251609e-09, 0.448996574, -2.34327455e-08, 1, 3.78297464e-08, -0.448996574, -4.43233645e-08, 0.893533468)
									CFrameMon = CFrame.new(61885.5039, 18.4828243, 1504.17896, 0.577502489, 0, -0.816389024, -0, 1.00000012, -0, 0.816389024, 0, 0.577502489)
									if _G.AutoFarm and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 then
										game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(61163.8515625, 11.6796875, 1819.7841796875))
									end
								elseif MyLevel == 450 or MyLevel <= 474 then -- God's Guards
									FM = false
									Ms = "God's Guard [Lv. 450]"
									NaemQuest = "SkyExp1Quest"
									LevelQuest = 1
									NameMon = "God's Guards"
									CFrameQuest = CFrame.new(-4721.71436, 845.277161, -1954.20105, -0.999277651, -5.56969759e-09, 0.0380011722, -4.14751478e-09, 1, 3.75035256e-08, -0.0380011722, 3.73188307e-08, -0.999277651)
									CFrameMon = CFrame.new(-4716.95703, 853.089722, -1933.92542, -0.93441087, -6.77488776e-09, -0.356197298, 1.12145182e-08, 1, -4.84390199e-08, 0.356197298, -4.92565206e-08, -0.93441087)
									if _G.AutoFarm and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 then
										game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(-4607.82275, 872.54248, -1667.55688))
									end
								elseif MyLevel == 475 or MyLevel <= 524 then -- Shandas
									sky = false
									Ms = "Shanda [Lv. 475]"
									NaemQuest = "SkyExp1Quest"
									LevelQuest = 2
									NameMon = "Shandas"
									CFrameQuest = CFrame.new(-7863.63672, 5545.49316, -379.826324, 0.362120807, -1.98046344e-08, -0.93213129, 4.05822291e-08, 1, -5.48095125e-09, 0.93213129, -3.58431969e-08, 0.362120807)
									CFrameMon = CFrame.new(-7685.12354, 5601.05127, -443.171509, 0.150056243, 1.79768236e-08, -0.988677442, 6.67798661e-09, 1, 1.91962481e-08, 0.988677442, -9.48289181e-09, 0.150056243)
									if _G.AutoFarm and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 then
										game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(-7894.6176757813, 5547.1416015625, -380.29119873047))
									end
								elseif MyLevel == 525 or MyLevel <= 549 then -- Royal Squad
									sky = true
									Ms = "Royal Squad [Lv. 525]"
									NaemQuest = "SkyExp2Quest"
									LevelQuest = 1
									NameMon = "Royal Squad"
									CFrameQuest = CFrame.new(-7902.66895, 5635.96387, -1411.71802, 0.0504222959, 2.5710392e-08, 0.998727977, 1.12541557e-07, 1, -3.14249675e-08, -0.998727977, 1.13982921e-07, 0.0504222959)
									CFrameMon = CFrame.new(-7685.02051, 5606.87842, -1442.729, 0.561947823, 7.69527464e-09, -0.827172697, -4.24974544e-09, 1, 6.41599973e-09, 0.827172697, -9.01838604e-11, 0.561947823)
								elseif MyLevel == 550 or MyLevel <= 624 then -- Royal Soldier
									Dis = 240
									sky = true
									Ms = "Royal Soldier [Lv. 550]"
									NaemQuest = "SkyExp2Quest"
									LevelQuest = 2
									NameMon = "Royal Soldier"
									CFrameQuest = CFrame.new(-7902.66895, 5635.96387, -1411.71802, 0.0504222959, 2.5710392e-08, 0.998727977, 1.12541557e-07, 1, -3.14249675e-08, -0.998727977, 1.13982921e-07, 0.0504222959)
									CFrameMon = CFrame.new(-7864.44775, 5661.94092, -1708.22351, 0.998389959, 2.28686137e-09, -0.0567218624, 1.99431383e-09, 1, 7.54200258e-08, 0.0567218624, -7.54117195e-08, 0.998389959)
								elseif MyLevel == 625 or MyLevel <= 649 then -- Galley Pirate
									Dis = 240
									sky = false
									Ms = "Galley Pirate [Lv. 625]"
									NaemQuest = "FountainQuest"
									LevelQuest = 1
									NameMon = "Galley Pirate"
									CFrameQuest = CFrame.new(5254.60156, 38.5011406, 4049.69678, -0.0504891425, -3.62066501e-08, -0.998724639, -9.87921389e-09, 1, -3.57534553e-08, 0.998724639, 8.06145284e-09, -0.0504891425)
									CFrameMon = CFrame.new(5595.06982, 41.5013695, 3961.47095, -0.992138803, -2.11610267e-08, -0.125142589, -1.34249509e-08, 1, -6.26613996e-08, 0.125142589, -6.04887518e-08, -0.992138803)
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 3000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(1.5)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
								elseif MyLevel >= 650 then -- Galley Captain
									Dis = 240
									Ms = "Galley Captain [Lv. 650]"
									NaemQuest = "FountainQuest"
									LevelQuest = 2
									NameMon = "Galley Captain"
									CFrameQuest = CFrame.new(5254.60156, 38.5011406, 4049.69678, -0.0504891425, -3.62066501e-08, -0.998724639, -9.87921389e-09, 1, -3.57534553e-08, 0.998724639, 8.06145284e-09, -0.0504891425)
									CFrameMon = CFrame.new(5658.5752, 38.5361786, 4928.93506, -0.996873081, 2.12391046e-06, -0.0790185928, 2.16989656e-06, 1, -4.96097414e-07, 0.0790185928, -6.66008248e-07, -0.996873081)
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 3000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(1.5)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
						   end
							elseif NewWorld then
								local MyLevel = game.Players.LocalPlayer.Data.Level.Value
								Dis = 240
								if MyLevel == 700 or MyLevel <= 724 then -- Raider [Lv. 700]
									Ms = "Raider [Lv. 700]"
									NaemQuest = "Area1Quest"
									LevelQuest = 1
									NameMon = "Raider"
									CFrameQuest = CFrame.new(337.276031, 39.1396255, 2320.86694, 0.999621809, -4.15421413e-20, -0.0275000762, 4.18174761e-20, 1, 9.43714367e-21, 0.0275000762, -1.05835578e-20, 0.999621809)
									CFrameMon = CFrame.new(310.3685302734375, 39.13898849487305, 2306.282958984375)
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 3000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(1.5)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
								elseif MyLevel == 725 or MyLevel <= 774 then -- Mercenary [Lv. 725]
									Ms = "Mercenary [Lv. 725]"
									NaemQuest = "Area1Quest"
									LevelQuest = 2
									NameMon = "Mercenary"
									CFrameQuest = CFrame.new(-424.080078, 73.0055847, 1836.91589, 0.253544956, -1.42165932e-08, 0.967323601, -6.00147771e-08, 1, 3.04272909e-08, -0.967323601, -6.5768397e-08, 0.253544956)
									CFrameMon = CFrame.new(-973.731995, 95.8733215, 1836.46936, 0.999135971, 2.02326991e-08, -0.0415605344, -1.90767793e-08, 1, 2.82094952e-08, 0.0415605344, -2.73922804e-08, 0.999135971)
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 3000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(1.5)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
								elseif MyLevel == 775 or MyLevel <= 799 then -- Swan Pirate [Lv. 775]
									Ms = "Swan Pirate [Lv. 775]"
									NaemQuest = "Area2Quest"
									LevelQuest = 1
									NameMon = "Swan Pirate"
									CFrameQuest = CFrame.new(632.698608, 73.1055908, 918.666321, -0.0319722369, 8.96074881e-10, -0.999488771, 1.36326533e-10, 1, 8.92172336e-10, 0.999488771, -1.07732087e-10, -0.0319722369)
									CFrameMon = CFrame.new(970.369446, 142.653198, 1217.3667, 0.162079468, -4.85452638e-08, -0.986777723, 1.03357589e-08, 1, -4.74980872e-08, 0.986777723, -2.50063148e-09, 0.162079468)
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 3000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(1.5)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
								elseif MyLevel == 800 or MyLevel <= 874 then -- Factory Staff [Lv. 800]
									Ms = "Factory Staff [Lv. 800]"
									NaemQuest = "Area2Quest"
									LevelQuest = 2
									NameMon = "Factory Staff"
									CFrameQuest = CFrame.new(632.698608, 73.1055908, 918.666321, -0.0319722369, 8.96074881e-10, -0.999488771, 1.36326533e-10, 1, 8.92172336e-10, 0.999488771, -1.07732087e-10, -0.0319722369)
									CFrameMon = CFrame.new(296.786499, 72.9948196, -57.1298141, -0.876037002, -5.32364979e-08, 0.482243896, -3.87658332e-08, 1, 3.99718729e-08, -0.482243896, 1.63222538e-08, -0.876037002)                            
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 5000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(1.5)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
								elseif MyLevel == 875 or MyLevel <= 899 then -- Marine Lieutenant [Lv. 875]
									Ms = "Marine Lieutenant [Lv. 875]"
									NaemQuest = "MarineQuest3"
									LevelQuest = 1
									NameMon = "Marine Lieutenant"
									CFrameQuest = CFrame.new(-2442.65015, 73.0511475, -3219.11523, -0.873540044, 4.2329841e-08, -0.486752301, 5.64383384e-08, 1, -1.43220786e-08, 0.486752301, -3.99823996e-08, -0.873540044)
									CFrameMon = CFrame.new(-2913.26367, 73.0011826, -2971.64282, 0.910507619, 0, 0.413492233, 0, 1.00000012, 0, -0.413492233, 0, 0.910507619)
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 5000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(1.5)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
								elseif MyLevel == 900 or MyLevel <= 949 then -- Marine Captain [Lv. 900]
									Ms = "Marine Captain [Lv. 900]"
									NaemQuest = "MarineQuest3"
									LevelQuest = 2
									NameMon = "Marine Captain"
									CFrameQuest = CFrame.new(-2442.65015, 73.0511475, -3219.11523, -0.873540044, 4.2329841e-08, -0.486752301, 5.64383384e-08, 1, -1.43220786e-08, 0.486752301, -3.99823996e-08, -0.873540044)
									CFrameMon = CFrame.new(-1868.67688, 73.0011826, -3321.66333, -0.971402287, 1.06502087e-08, 0.237439692, 3.68856199e-08, 1, 1.06050372e-07, -0.237439692, 1.11775684e-07, -0.971402287)
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 5000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(1.5)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
								elseif MyLevel == 950 or MyLevel <= 974 then -- Zombie [Lv. 950]
									Ms = "Zombie [Lv. 950]"
									NaemQuest = "ZombieQuest"
									LevelQuest = 1
									NameMon = "Zombie"
									CFrameQuest = CFrame.new(-5492.79395, 48.5151672, -793.710571, 0.321800292, -6.24695815e-08, 0.946807742, 4.05616092e-08, 1, 5.21931227e-08, -0.946807742, 2.16082796e-08, 0.321800292)
									CFrameMon = CFrame.new(-5634.83838, 126.067039, -697.665039, -0.992770672, 6.77618939e-09, 0.120025545, 1.65461245e-08, 1, 8.04023372e-08, -0.120025545, 8.18070234e-08, -0.992770672)
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 5000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(1.5)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
								elseif MyLevel == 975 or MyLevel <= 999 then -- Vampire [Lv. 975]
									Ms = "Vampire [Lv. 975]"
									NaemQuest = "ZombieQuest"
									LevelQuest = 2
									NameMon = "Vampire"
									CFrameQuest = CFrame.new(-5492.79395, 48.5151672, -793.710571, 0.321800292, -6.24695815e-08, 0.946807742, 4.05616092e-08, 1, 5.21931227e-08, -0.946807742, 2.16082796e-08, 0.321800292)
									CFrameMon = CFrame.new(-6030.32031, 6.4377408, -1313.5564, -0.856965423, 3.9138893e-08, -0.515373945, -1.12178942e-08, 1, 9.45958547e-08, 0.515373945, 8.68467822e-08, -0.856965423)
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 5000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(1.5)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
								elseif MyLevel == 1000 or MyLevel <= 1049 then -- Snow Trooper [Lv. 1000] **
									Ms = "Snow Trooper [Lv. 1000]"
									NaemQuest = "SnowMountainQuest"
									LevelQuest = 1
									NameMon = "Snow Trooper"
									CFrameQuest = CFrame.new(604.964966, 401.457062, -5371.69287, 0.353063971, 1.89520435e-08, -0.935599446, -5.81846002e-08, 1, -1.70033754e-09, 0.935599446, 5.50377841e-08, 0.353063971)
									CFrameMon = CFrame.new(535.893433, 401.457062, -5329.6958, -0.999524176, 0, 0.0308452044, 0, 1, -0, -0.0308452044, 0, -0.999524176)
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 5000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(1.5)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
								elseif MyLevel == 1050 or MyLevel <= 1099 then -- Winter Warrior [Lv. 1050]
									Ms = "Winter Warrior [Lv. 1050]"
									NaemQuest = "SnowMountainQuest"
									LevelQuest = 2
									NameMon = "Winter Warrior"
									CFrameQuest = CFrame.new(604.964966, 401.457062, -5371.69287, 0.353063971, 1.89520435e-08, -0.935599446, -5.81846002e-08, 1, -1.70033754e-09, 0.935599446, 5.50377841e-08, 0.353063971)
									CFrameMon = CFrame.new(1223.7417, 454.575226, -5170.02148, 0.473996818, 2.56845354e-08, 0.880526543, -5.62456428e-08, 1, 1.10811016e-09, -0.880526543, -5.00510211e-08, 0.473996818)
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 5000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(1.5)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
								elseif MyLevel == 1100 or MyLevel <= 1124 then -- Lab Subordinate [Lv. 1100]
									Ms = "Lab Subordinate [Lv. 1100]"
									NaemQuest = "IceSideQuest"
									LevelQuest = 1
									NameMon = "Lab Subordinate"
									CFrameQuest = CFrame.new(-6060.10693, 15.9868021, -4904.7876, -0.411000341, -5.06538868e-07, 0.91163528, 1.26306062e-07, 1, 6.12581289e-07, -0.91163528, 3.66916197e-07, -0.411000341)
									CFrameMon = CFrame.new(-5769.2041, 37.9288292, -4468.38721, -0.569419742, -2.49055017e-08, 0.822046936, -6.96206541e-08, 1, -1.79282633e-08, -0.822046936, -6.74401548e-08, -0.569419742)
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 5000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(1.5)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
								elseif MyLevel == 1125 or MyLevel <= 1174 then -- Horned Warrior [Lv. 1125]
									Ms = "Horned Warrior [Lv. 1125]"
									NaemQuest = "IceSideQuest"
									LevelQuest = 2
									NameMon = "Horned Warrior"
									CFrameQuest = CFrame.new(-6060.10693, 15.9868021, -4904.7876, -0.411000341, -5.06538868e-07, 0.91163528, 1.26306062e-07, 1, 6.12581289e-07, -0.91163528, 3.66916197e-07, -0.411000341)
									CFrameMon = CFrame.new(-6400.85889, 24.7645149, -5818.63574, -0.964845479, 8.65926566e-08, -0.262817472, 3.98261392e-07, 1, -1.13260398e-06, 0.262817472, -1.19745812e-06, -0.964845479)
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 5000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(1.5)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
								elseif MyLevel == 1175 or MyLevel <= 1199 then -- Magma Ninja [Lv. 1175]
									Ms = "Magma Ninja [Lv. 1175]"
									NaemQuest = "FireSideQuest"
									LevelQuest = 1
									NameMon = "Magma Ninja"
									CFrameQuest = CFrame.new(-5431.09473, 15.9868021, -5296.53223, 0.831796765, 1.15322464e-07, -0.555080295, -1.10814341e-07, 1, 4.17010995e-08, 0.555080295, 2.68240168e-08, 0.831796765)
									CFrameMon = CFrame.new(-5496.65576, 58.6890411, -5929.76855, -0.885073781, 0, -0.465450764, 0, 1.00000012, -0, 0.465450764, 0, -0.885073781)
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 5000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(1.5)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
								elseif MyLevel == 1200 or MyLevel <= 1249 then -- Lava Pirate [Lv. 1200]
									Ms = "Lava Pirate [Lv. 1200]"
									NaemQuest = "FireSideQuest"
									LevelQuest = 2
									NameMon = "Lava Pirate"
									CFrameQuest = CFrame.new(-5431.09473, 15.9868021, -5296.53223, 0.831796765, 1.15322464e-07, -0.555080295, -1.10814341e-07, 1, 4.17010995e-08, 0.555080295, 2.68240168e-08, 0.831796765)
									CFrameMon = CFrame.new(-5169.71729, 34.1234779, -4669.73633, -0.196780294, 0, 0.98044765, 0, 1.00000012, -0, -0.98044765, 0, -0.196780294)
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 5000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(1.5)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
								elseif MyLevel == 1250 or MyLevel <= 1274 then -- Ship Deckhand [Lv. 1250]
									Ms = "Ship Deckhand [Lv. 1250]"
									NaemQuest = "ShipQuest1"
									LevelQuest = 1
									NameMon = "Ship Deckhand"
									CFrameQuest = CFrame.new(1037.80127, 125.092171, 32911.6016, -0.244533166, -0, -0.969640911, -0, 1.00000012, -0, 0.96964103, 0, -0.244533136)
									CFrameMon = CFrame.new(1163.80872, 138.288452, 33058.4258, -0.998580813, 5.49076979e-08, -0.0532564968, 5.57436763e-08, 1, -1.42118655e-08, 0.0532564968, -1.71604082e-08, -0.998580813)
									if _G.AutoFarm and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 then
										game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(923.21252441406, 126.9760055542, 32852.83203125))
									end
								elseif MyLevel == 1275 or MyLevel <= 1299 then -- Ship Engineer [Lv. 1275]
									Ms = "Ship Engineer [Lv. 1275]"
									NaemQuest = "ShipQuest1"
									LevelQuest = 2
									NameMon = "Ship Engineer"
									CFrameQuest = CFrame.new(1037.80127, 125.092171, 32911.6016, -0.244533166, -0, -0.969640911, -0, 1.00000012, -0, 0.96964103, 0, -0.244533136)
									CFrameMon = CFrame.new(916.666504, 44.0920448, 32917.207, -0.99746871, -4.85034697e-08, -0.0711069331, -4.8925461e-08, 1, 4.19294288e-09, 0.0711069331, 7.66126895e-09, -0.99746871)
									if _G.AutoFarm and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 then
										game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(923.21252441406, 126.9760055542, 32852.83203125))
									end
								elseif MyLevel == 1300 or MyLevel <= 1324 then -- Ship Steward [Lv. 1300]
									Ms = "Ship Steward [Lv. 1300]"
									NaemQuest = "ShipQuest2"
									LevelQuest = 1
									NameMon = "Ship Steward"
									CFrameQuest = CFrame.new(968.80957, 125.092171, 33244.125, -0.869560242, 1.51905191e-08, -0.493826836, 1.44108379e-08, 1, 5.38534195e-09, 0.493826836, -2.43357912e-09, -0.869560242)
									CFrameMon = CFrame.new(918.743286, 129.591064, 33443.4609, -0.999792814, -1.7070947e-07, -0.020350717, -1.72559169e-07, 1, 8.91351277e-08, 0.020350717, 9.2628369e-08, -0.999792814)
									if _G.AutoFarm and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 then
										game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(923.21252441406, 126.9760055542, 32852.83203125))
									end
								elseif MyLevel == 1325 or MyLevel <= 1349 then -- Ship Officer [Lv. 1325]
									Ms = "Ship Officer [Lv. 1325]"
									NaemQuest = "ShipQuest2"
									LevelQuest = 2
									NameMon = "Ship Officer"
									CFrameQuest = CFrame.new(968.80957, 125.092171, 33244.125, -0.869560242, 1.51905191e-08, -0.493826836, 1.44108379e-08, 1, 5.38534195e-09, 0.493826836, -2.43357912e-09, -0.869560242)
									CFrameMon = CFrame.new(786.051941, 181.474106, 33303.2969, 0.999285698, -5.32193063e-08, 0.0377905183, 5.68968588e-08, 1, -9.62386864e-08, -0.0377905183, 9.83201005e-08, 0.999285698)
									if _G.AutoFarm and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 then
										game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(923.21252441406, 126.9760055542, 32852.83203125))
									end
								elseif MyLevel == 1350 or MyLevel <= 1374 then -- Arctic Warrior [Lv. 1350]
									Ms = "Arctic Warrior [Lv. 1350]"
									NaemQuest = "FrostQuest"
									LevelQuest = 1
									NameMon = "Arctic Warrior"
									CFrameQuest = CFrame.new(5669.43506, 28.2117786, -6482.60107, 0.888092756, 1.02705066e-07, 0.459664226, -6.20391774e-08, 1, -1.03572376e-07, -0.459664226, 6.34646895e-08, 0.888092756)
									CFrameMon = CFrame.new(5995.07471, 57.3188477, -6183.47314, 0.702747107, -1.53454167e-07, -0.711440146, -1.08168464e-07, 1, -3.22542007e-07, 0.711440146, 3.03620908e-07, 0.702747107)
									if _G.AutoFarm and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 then
										game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(-6508.5581054688, 5000.034996032715, -132.83953857422))
									end
								elseif MyLevel == 1375 or MyLevel <= 1424 then -- Snow Lurker [Lv. 1375]
									Ms = "Snow Lurker [Lv. 1375]"
									NaemQuest = "FrostQuest"
									LevelQuest = 2
									NameMon = "Snow Lurker"
									CFrameQuest = CFrame.new(5669.43506, 28.2117786, -6482.60107, 0.888092756, 1.02705066e-07, 0.459664226, -6.20391774e-08, 1, -1.03572376e-07, -0.459664226, 6.34646895e-08, 0.888092756)
									CFrameMon = CFrame.new(5518.00684, 60.5559731, -6828.80518, -0.650781393, -3.64292951e-08, 0.759265184, -4.07668654e-09, 1, 4.44854642e-08, -0.759265184, 2.58550248e-08, -0.650781393)
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 5000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(1.5)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
								elseif MyLevel == 1425 or MyLevel <= 1449 then -- Sea Soldier [Lv. 1425]
									Ms = "Sea Soldier [Lv. 1425]"
									NaemQuest = "ForgottenQuest"
									LevelQuest = 1
									NameMon = "Sea Soldier"
									CFrameQuest = CFrame.new(-3052.99097, 236.881363, -10148.1943, -0.997911751, 4.42321983e-08, 0.064591676, 4.90968759e-08, 1, 7.37270085e-08, -0.064591676, 7.67442998e-08, -0.997911751)
									CFrameMon = CFrame.new(-3029.78467, 66.944252, -9777.38184, -0.998552859, 1.09555076e-08, 0.0537791774, 7.79564235e-09, 1, -5.89660658e-08, -0.0537791774, -5.84614881e-08, -0.998552859)
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 5000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(1.5)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
								elseif MyLevel >= 1450 then -- Water Fighter [Lv. 1450]
									Ms = "Water Fighter [Lv. 1450]"
									NaemQuest = "ForgottenQuest"
									LevelQuest = 2
									NameMon = "Water Fighter"
									CFrameQuest = CFrame.new(-3052.99097, 236.881363, -10148.1943, -0.997911751, 4.42321983e-08, 0.064591676, 4.90968759e-08, 1, 7.37270085e-08, -0.064591676, 7.67442998e-08, -0.997911751)
									CFrameMon = CFrame.new(-3436.11401, 289.52652, -10504.2559, -0.999507904, 2.13766516e-08, 0.031368468, 2.18623413e-08, 1, 1.51404205e-08, -0.031368468, 1.58187579e-08, -0.999507904)
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 5000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(1.5)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
								end
							else
								local MyLevel =  game.Players.LocalPlayer.Data.Level.Value
								Dis = 240
								if MyLevel == 1500 or MyLevel <= 1524 then
									Ms = "Pirate Millionaire [Lv. 1500]"
									NaemQuest = "PiratePortQuest"
									LevelQuest = 1
									NameMon = "Pirate Millionaire"
									CFrameQuest = CFrame.new(-290.074677, 42.9034653, 5581.58984, 0.965929627, -0, -0.258804798, 0, 1, -0, 0.258804798, 0, 0.965929627)
									CFrameMon = CFrame.new(81.164993286133, 43.755737304688, 5724.7021484375)
								elseif MyLevel == 1525 or MyLevel <= 1574 then
									Ms = "Pistol Billionaire [Lv. 1525]"
									NaemQuest = "PiratePortQuest"
									LevelQuest = 2
									NameMon = "Pistol Billionaire"
									CFrameQuest = CFrame.new(-290.074677, 42.9034653, 5581.58984, 0.965929627, -0, -0.258804798, 0, 1, -0, 0.258804798, 0, 0.965929627)
									CFrameMon = CFrame.new(81.164993286133, 43.755737304688, 5724.7021484375)
								elseif MyLevel == 1575 or MyLevel <= 1599 then
									Ms = "Dragon Crew Warrior [Lv. 1575]"
									NaemQuest = "AmazonQuest"
									LevelQuest = 1
									NameMon = "Dragon Crew Warrior"
									CFrameQuest = CFrame.new(5832.83594, 51.6806107, -1101.51563, 0.898790359, -0, -0.438378751, 0, 1, -0, 0.438378751, 0, 0.898790359)
									CFrameMon = CFrame.new(6241.9951171875, 51.522083282471, -1243.9771728516)
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 5000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(1.5)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
								elseif MyLevel == 1600 or MyLevel <= 1624 then
									Ms = "Dragon Crew Archer [Lv. 1600]"
									NaemQuest = "AmazonQuest"
									LevelQuest = 2
									NameMon = "Dragon Crew Archer"
									CFrameQuest = CFrame.new(5832.83594, 51.6806107, -1101.51563, 0.898790359, -0, -0.438378751, 0, 1, -0, 0.438378751, 0, 0.898790359)
									CFrameMon = CFrame.new(6488.9155273438, 383.38375854492, -110.66246032715)
								elseif MyLevel == 1625 or MyLevel <= 1649 then
									Ms = "Female Islander [Lv. 1625]"
									NaemQuest = "AmazonQuest2"
									LevelQuest = 1
									NameMon = "Female Islander"
									CFrameQuest = CFrame.new(5448.86133, 601.516174, 751.130676, 0, 0, 1, 0, 1, -0, -1, 0, 0)
									CFrameMon = CFrame.new(4770.4990234375, 758.95520019531, 1069.8680419922)
								elseif MyLevel == 1650 or MyLevel <= 1699 then
									Ms = "Giant Islander [Lv. 1650]"
									NaemQuest = "AmazonQuest2"
									LevelQuest = 2
									NameMon = "Giant Islander"
									CFrameQuest = CFrame.new(5448.86133, 601.516174, 751.130676, 0, 0, 1, 0, 1, -0, -1, 0, 0)
									CFrameMon = CFrame.new(4530.3540039063, 656.75695800781, -131.60952758789)
								elseif MyLevel == 1700 or MyLevel <= 1724 then
									Ms = "Marine Commodore [Lv. 1700]"
									NaemQuest = "MarineTreeIsland"
									LevelQuest = 1
									NameMon = "Marine Commodore"
									CFrameQuest = CFrame.new(2180.54126, 27.8156815, -6741.5498, -0.965929747, 0, 0.258804798, 0, 1, 0, -0.258804798, 0, -0.965929747)
									CFrameMon = CFrame.new(2490.0844726563, 190.4232635498, -7160.0502929688)
								elseif MyLevel == 1725 or MyLevel <= 1774 then
									Ms = "Marine Rear Admiral [Lv. 1725]"
									NaemQuest = "MarineTreeIsland"
									LevelQuest = 2
									NameMon = "Marine Rear Admiral"
									CFrameQuest = CFrame.new(2180.54126, 27.8156815, -6741.5498, -0.965929747, 0, 0.258804798, 0, 1, 0, -0.258804798, 0, -0.965929747)
									CFrameMon = CFrame.new(3951.3903808594, 229.11549377441, -6912.81640625)
								elseif MyLevel == 1775 or MyLevel <= 1799 then
									Ms = "Fishman Raider [Lv. 1775]"
									NaemQuest = "DeepForestIsland3"
									LevelQuest = 1
									NameMon = "Fishman Raider"
									CFrameQuest = CFrame.new(-10581.6563, 330.872955, -8761.18652, -0.882952213, 0, 0.469463557, 0, 1, 0, -0.469463557, 0, -0.882952213)
									CFrameMon = CFrame.new(-10322.400390625, 390.94473266602, -8580.0908203125)
								elseif MyLevel == 1800 or MyLevel <= 1824 then
									Ms = "Fishman Captain [Lv. 1800]"
									NaemQuest = "DeepForestIsland3"
									LevelQuest = 2
									NameMon = "Fishman Captain"
									CFrameQuest = CFrame.new(-10581.6563, 330.872955, -8761.18652, -0.882952213, 0, 0.469463557, 0, 1, 0, -0.469463557, 0, -0.882952213)
									CFrameMon = CFrame.new(-11194.541992188, 442.02795410156, -8608.806640625)
								elseif MyLevel == 1825 or MyLevel <= 1849 then
									Ms = "Forest Pirate [Lv. 1825]"
									NaemQuest = "DeepForestIsland"
									LevelQuest = 1
									NameMon = "Forest Pirate"
									CFrameQuest = CFrame.new(-13234.04, 331.488495, -7625.40137, 0.707134247, -0, -0.707079291, 0, 1, -0, 0.707079291, 0, 0.707134247)
									CFrameMon = CFrame.new(-13225.809570313, 428.19387817383, -7753.1245117188)
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 5000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(1.5)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
								elseif MyLevel == 1850 or MyLevel <= 1899 then
									Ms = "Mythological Pirate [Lv. 1850]"
									NaemQuest = "DeepForestIsland"
									LevelQuest = 2
									NameMon = "Mythological Pirate"
									CFrameQuest = CFrame.new(-13234.04, 331.488495, -7625.40137, 0.707134247, -0, -0.707079291, 0, 1, -0, 0.707079291, 0, 0.707134247)
									CFrameMon = CFrame.new(-13869.172851563, 564.95251464844, -7084.4135742188)
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 5000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(1.5)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
								elseif MyLevel == 1900 or MyLevel <= 1924 then
									Ms = "Jungle Pirate [Lv. 1900]"
									NaemQuest = "DeepForestIsland2"
									LevelQuest = 1
									NameMon = "Jungle Pirate"
									CFrameQuest = CFrame.new(-12680.3818, 389.971039, -9902.01953, -0.0871315002, 0, 0.996196866, 0, 1, 0, -0.996196866, 0, -0.0871315002)
									CFrameMon = CFrame.new(-11982.221679688, 376.32522583008, -10451.415039063)
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 5000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(1.5)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
								elseif MyLevel == 1925 or MyLevel <= 1974 then
									Ms = "Musketeer Pirate [Lv. 1925]"
									NaemQuest = "DeepForestIsland2"
									LevelQuest = 2
									NameMon = "Musketeer Pirate"
									CFrameQuest = CFrame.new(-12680.3818, 389.971039, -9902.01953, -0.0871315002, 0, 0.996196866, 0, 1, 0, -0.996196866, 0, -0.0871315002)
									CFrameMon = CFrame.new(-13282.3046875, 496.23684692383, -9565.150390625)
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 5000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(1.5)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
								elseif MyLevel == 1975 or MyLevel <= 1999 then
									Ms = "Reborn Skeleton [Lv. 1975]"
									NaemQuest = "HauntedQuest1"
									LevelQuest = 1
									NameMon = "Reborn Skeleton"
									CFrameQuest = CFrame.new(-9479.2168, 141.215088, 5566.09277, 0, 0, 1, 0, 1, -0, -1, 0, 0)
									CFrameMon = CFrame.new(-8761.3154296875, 164.85829162598, 6161.1567382813)
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 5000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(1.5)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
								elseif MyLevel == 2000 or MyLevel <= 2024 then
									Ms = "Living Zombie [Lv. 2000]"
									NaemQuest = "HauntedQuest1"
									LevelQuest = 2
									NameMon = "Living Zombie"
									CFrameQuest = CFrame.new(-9479.2168, 141.215088, 5566.09277, 0, 0, 1, 0, 1, -0, -1, 0, 0)
									CFrameMon = CFrame.new(-10093.930664063, 237.38233947754, 6180.5654296875)
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 5000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(1.5)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
								elseif MyLevel == 2025 or MyLevel <= 2049 then
									Ms = "Demonic Soul [Lv. 2025]"
									NaemQuest = "HauntedQuest2"
									LevelQuest = 1
									NameMon = "Demonic Soul"
									CFrameQuest = CFrame.new(-9514.78027, 171.162918, 6078.82373, 0.301918149, 7.4535027e-09, 0.953333855, -3.22802141e-09, 1, -6.79604995e-09, -0.953333855, -1.02553133e-09, 0.301918149)
									CFrameMon = CFrame.new(-9503.9921875, 272.1305847167969, 6250.5703125)
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 5000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(1.5)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
								elseif MyLevel == 2050 or MyLevel <= 2074 then
									Ms = "Posessed Mummy [Lv. 2050]" 
									NaemQuest = "HauntedQuest2"
									LevelQuest = 2
									NameMon = "Posessed Mummy"
									CFrameQuest = CFrame.new(-9514.78027, 171.162918, 6078.82373, 0.301918149, 7.4535027e-09, 0.953333855, -3.22802141e-09, 1, -6.79604995e-09, -0.953333855, -1.02553133e-09, 0.301918149)
									CFrameMon = CFrame.new(-9589.93848, 4.85058546, 6190.27197)
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 5000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(1.5)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
								elseif MyLevel == 2075 or MyLevel <= 2099 then
									Ms = "Peanut Scout [Lv. 2075]"
									NaemQuest = "NutsIslandQuest"
									LevelQuest = 1
									NameMon = "Peanut Scout"
									CFrameQuest = CFrame.new(-2075.9643554688, 38.129207611084, -10172.815429688)
									CFrameMon = CFrame.new(-2150.587890625, 122.49767303467, -10358.994140625)
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 5000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(1.5)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
								elseif MyLevel == 2100 or MyLevel <= 2124 then
									Ms = "Peanut President [Lv. 2100]"
									NaemQuest = "NutsIslandQuest"
									LevelQuest = 2
									NameMon = "Peanut President"
									CFrameQuest = CFrame.new(-2075.9643554688, 38.129207611084, -10172.815429688)
									CFrameMon = CFrame.new(-2150.587890625, 122.49767303467, -10358.994140625)
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 5000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(1.5)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
								elseif MyLevel == 2125 or MyLevel <= 2149 then
									Ms = "Ice Cream Chef [Lv. 2125]"
									NaemQuest = "IceCreamIslandQuest"
									LevelQuest = 1
									NameMon = "Ice Cream Chef"
									CFrameQuest = CFrame.new(-819.84533691406, 65.845329284668, -10965.487304688)
									CFrameMon = CFrame.new(-890.55895996094, 186.34135437012, -11127.306640625)
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 5000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(1.5)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
								elseif MyLevel == 2150 or MyLevel <= 2199 then
									Ms = "Ice Cream Commander [Lv. 2150]"
									NaemQuest = "IceCreamIslandQuest"
									LevelQuest = 2
									NameMon = "Ice Cream Commander"
									CFrameQuest = CFrame.new(-819.84533691406, 65.845329284668, -10965.487304688)
									CFrameMon = CFrame.new(-890.55895996094, 186.34135437012, -11127.306640625)
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 5000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(1.5)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
								elseif MyLevel == 2200 or MyLevel <= 2224 then
									Ms = "Cookie Crafter [Lv. 2200]"
									NaemQuest = "CakeQuest1"
									LevelQuest = 1
									NameMon = "Cookie Crafter"
									CFrameQuest = CFrame.new(-2022.3, 36.9276, -12031)
									CFrameMon = CFrame.new(-2280.569091796875, 89.83930206298828, -12041.4326171875)
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 5000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(1.5)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
								elseif MyLevel == 2225 or MyLevel <= 2249 then
									Ms = "Cake Guard [Lv. 2225]"
									NaemQuest = "CakeQuest1"
									LevelQuest = 2
									NameMon = "Cake Guard"
									CFrameQuest = CFrame.new(-2022.3, 36.9276, -12031)
									CFrameMon = CFrame.new(-1621.9512939453125, 195.68287658691406, -12281.0908203125)
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 5000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(1.5)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
								elseif MyLevel == 2250 or MyLevel <= 2274 then
									Ms = "Baking Staff [Lv. 2250]"
									NaemQuest = "CakeQuest2"
									LevelQuest = 1
									NameMon = "Baking Staff"
									CFrameQuest = CFrame.new(-1928.32, 37.7297, -12840.6)
									CFrameMon = CFrame.new(-1912.928955078125, 113.134033203125, -12990.53515625)
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 5000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(1.5)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
								elseif MyLevel == 2275 or MyLevel <= 2299 then
									Ms = "Head Baker [Lv. 2275]"
									NaemQuest = "CakeQuest2"
									LevelQuest = 2
									NameMon = "Head Baker"
									CFrameQuest = CFrame.new(-1927.9107666015625, 37.79813003540039, -12843.78515625)
									CFrameMon = CFrame.new(-2203.302490234375, 109.90937042236328, -12788.7333984375)                            
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 5000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(4)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
								elseif MyLevel == 2300 or MyLevel <= 2324 then
									Ms = "Cocoa Warrior [Lv. 2300]"
									NaemQuest = "ChocQuest1"
									LevelQuest = 1
									NameMon = "Cocoa Warriors"
									CFrameQuest = CFrame.new(231.75, 23.9003, -12200.3)
									CFrameMon = CFrame.new(89.75547790527344, 73.66654968261719, -12315.4609375)
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 5000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(4)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
								elseif MyLevel == 2325 or MyLevel <= 2349 then
									Ms = "Chocolate Bar Battler [Lv. 2325]"
									NaemQuest = "ChocQuest1"
									LevelQuest = 2
									NameMon = "Chocolate Bar Battler"
									CFrameQuest = CFrame.new(231.75, 23.9003, -12200.3)
									CFrameMon = CFrame.new(614.6710205078125, 81.79888153076172, -12578.4521484375)
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 5000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(4)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
								elseif MyLevel == 2350 or MyLevel <= 2374 then
									Ms = "Sweet Thief [Lv. 2350]"
									NaemQuest = "ChocQuest2"
									LevelQuest = 1
									NameMon = "Sweet Thiefs"
									CFrameQuest = CFrame.new(147.222900390625, 24.819623947143555, -12775.2890625)
									CFrameMon = CFrame.new(-92.28578186035156, 132.29556274414062, -12655.9111328125)
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 5000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(4)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
								elseif MyLevel >= 2375 then
									Ms = "Candy Rebel [Lv. 2375]"
									NaemQuest = "ChocQuest2"
									LevelQuest = 2
									NameMon = "Candy Rebel"
									CFrameQuest = CFrame.new(147.222900390625, 24.819623947143555, -12775.2890625)
									CFrameMon = CFrame.new(174.739349, 59.6885834, -12851.1729, 0.769098222, 6.77065071e-10, 0.639130652, -1.27687849e-09, 1, 4.77179296e-10, -0.639130652, -1.18308996e-09, 0.769098222)
									if _G.Bypass and (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 5000 then
										game.Players.LocalPlayer.Character.Head:Destroy()
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(3)
										_G.AutoFarm = false
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										wait(4)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
										_G.AutoFarm = true
										repeat wait() until game:GetService("Players").LocalPlayer.Character:WaitForChild("Humanoid").Health > 0
												wait(.1)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
											
									end
								end
						end
					end

					task.spawn(function()
						while true do wait()
							if setscriptable then
								setscriptable(game.Players.LocalPlayer, "SimulationRadius", true)
							end
							if sethiddenproperty then
								sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius", math.huge)
							end
						end
					end)
					function InMyNetWork(object)
						if isnetworkowner then
							return isnetworkowner(object)
						else
							if (object.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 200 then 
								return true
							end
							return false
						end
					end
					

						task.spawn(function()
							while task.wait() do
								pcall(function()
									if _G.AutoFarm or MagnetActive then
										for i,v in pairs(game.Workspace.Enemies:GetChildren()) do
											if not string.find(v.Name,"Boss") and (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 500 then
												if InMyNetWork(v.HumanoidRootPart) then
													v.HumanoidRootPart.CFrame = PosMon
													v.Humanoid.JumpPower = 0
													v.Humanoid.WalkSpeed = 0
													v.HumanoidRootPart.Size = Vector3.new(90,90,90)
													v.HumanoidRootPart.Transparency = 1
													v.HumanoidRootPart.CanCollide = false
													v.Head.CanCollide = false
													if v.Humanoid:FindFirstChild("Animator") then
														v.Humanoid.Animator:Destroy()
													end
													v.Humanoid:ChangeState(11)
													v.Humanoid:ChangeState(14)
												end
											end
										end
									end
								end)
							end
						end)
		
		
					
		
		spawn(function()
			game:GetService('RunService').Stepped:Connect(function()
				if guy then
					for i, v in pairs(game.Workspace["_WorldOrigin"]:GetChildren()) do
						if v.Name == "CurvedRing" or v.Name == "SwordSlash" or v.Name == "Sounds" or v.Name == "SlashHit" or v.Name == "DamageCounter" then--or v.Name == "SlashHit"
							v:Destroy() 
						end
					end
				end
			end)
		end)
		local Client = game.Players.LocalPlayer
		local STOP = require(Client.PlayerScripts.CombatFramework.Particle)
		local STOPRL = require(game:GetService("ReplicatedStorage").CombatFramework.RigLib)
		spawn(function()
			while task.wait() do
				if _G.VeryFast then
					pcall(function()
						if not shared.orl then shared.orl = STOPRL.wrapAttackAnimationAsync end
						if not shared.cpc then shared.cpc = STOP.play end
							STOPRL.wrapAttackAnimationAsync = function(a,b,c,d,func)
							local Hits = STOPRL.getBladeHits(b,c,d)
							if Hits then
								STOP.play = function() end
								a:Play(0.01,0.01,0.01)
								func(Hits)
								STOP.play = shared.cpc
								wait(a.length * 0.5)
								a:Stop()
							end
						end
					end)
				end
			end
		end)
		
		function Hop()
		local PlaceID = game.PlaceId
		local AllIDs = {}
		local foundAnything = ""
		local actualHour = os.date("!*t").hour
		local Deleted = false
		function TPReturner()
		local Site;
		if foundAnything == "" then
		Site = game.HttpService:JSONDecode(game:HttpGet('https://games.roblox.com/v1/games/' .. PlaceID .. '/servers/Public?sortOrder=Asc&limit=100'))
		else
		Site = game.HttpService:JSONDecode(game:HttpGet('https://games.roblox.com/v1/games/' .. PlaceID .. '/servers/Public?sortOrder=Asc&limit=100&cursor=' .. foundAnything))
		end
		local ID = ""
		if Site.nextPageCursor and Site.nextPageCursor ~= "null" and Site.nextPageCursor ~= nil then
		foundAnything = Site.nextPageCursor
		end
		local num = 0;
		for i,v in pairs(Site.data) do
		local Possible = true
		ID = tostring(v.id)
		if tonumber(v.maxPlayers) > tonumber(v.playing) then
		for _,Existing in pairs(AllIDs) do
			if num ~= 0 then
				if ID == tostring(Existing) then
					Possible = false
				end
			else
				if tonumber(actualHour) ~= tonumber(Existing) then
					local delFile = pcall(function()
						AllIDs = {}
						table.insert(AllIDs, actualHour)
					end)
				end
			end
			num = num + 1
		end
		if Possible == true then
			table.insert(AllIDs, ID)
			wait()
			pcall(function()
				wait()
				game:GetService("TeleportService"):TeleportToPlaceInstance(PlaceID, ID, game.Players.LocalPlayer)
			end)
			wait(4)
		end
		end
		end
		end
		function Teleport() 
		while wait() do
		pcall(function()
		TPReturner()
		if foundAnything ~= "" then
			TPReturner()
		end
		end)
		end
		end
		Teleport()
		end                   
		function Attack()
			pcall(function()
				game:GetService'VirtualUser':CaptureController()
				game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
			end)
		end
		local Attack = 0.2
		for i,v in pairs(getreg()) do
			if typeof(v) == "function" and getfenv(v).script == game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework then
				for x,w in pairs(debug.getupvalues(v)) do
					 if typeof(w) == "table" then
						spawn(function()
							game:GetService("RunService").Heartbeat:Connect(function()
								if _G.AutoEliteHunter or _G.AutoEliteHunter_Hop or _G.Mobaura or _G.FastFarm or _G.AutoBone or _G.KillBoss or _G.Tushitahop or _G.AutoAdvanceDungeon or _G.AutoDoughtBoss or _G.Auto_DungeonMobAura or _G.AutoFarmChest or _G.AutoFarmBossHallow or _G.AutoFarmSwanGlasses or _G.AutoLongSword or _G.AutoBlackSpikeycoat or _G.AutoElectricClaw or _G.AutoFarmGunMastery or _G.AutoHolyTorch or _G.AutoLawRaid or _G.AutoFarmBoss or Auto_Twin_Hooks or _G.AutoOpenSwanDoor or Auto_Dragon_Trident or _G.AutoSaber or _G.AutoFarmFruitMastery or _G.AutoFarmGunMastery or _G.TeleportIsland or _G.Auto_EvoRace or _G.AutoFarmAllMsBypassType or _G.AutoObservationv2 or _G.AutoMusketeerHat or _G.AutoEctoplasm or _G.AutoRengoku or _G.Auto_Rainbow_Haki or _G.AutoObservation or _G.AutoDarkDagger or _G.Safe_Mode or _G.MasteryFruit or _G.AutoBudySword or _G.AutoOderSword or _G.AutoBounty or _G.AutoAllBoss or _G.Auto_Bounty or _G.AutoSharkman or _G.Auto_Mastery_Fruit or _G.Auto_Mastery_Gun or _G.Auto_Dungeon or _G.Auto_Cavender or _G.Auto_Pole or _G.Auto_Kill_Ply or _G.Auto_Factory or _G.AutoSecondSea or _G.TeleportPly or _G.AutoBartilo or _G.Auto_DarkBoss or _G.GrabChest or _G.AutoFarmBounty or _G.Holy_Torch or _G.Clip or FarmBoss or _G.AutoElitehunter or _G.AutoThirdSea or _G.Auto_Bone or _G.AutoFarmCandy or _G.AutoFactory or Pole_Farm or Auto_Serpent_Bow or Auto_Canvander or _G.YamaHop or _G.AutoSaber2 or _G.AutoFarmAllBoss or _G.SOLSecond or _G.Auto_Next_Island or _G.AutoNextIsland or _G.Auto_Farm_Ectoplasm or _G.Auto_Pole or _G.Auto_Open_Dough_Dungeon or _G.Auto_Farm_Chest or _G.Auto_Soul_Reaper or _G.Auto_Cake_Prince or _G.Auto_Saber or _G.FastFarmPlayer or Auto_Cursed_Dual_Katana or AutoFarmMaterial or Auto_Quest_Yama_1 or Auto_Quest_Yama_2 or Auto_Quest_Yama_3 or Auto_Quest_Tushita_1 or Auto_Quest_Tushita_2 or Auto_Quest_Tushita_3 or _G.Auto_kill_Captains or _G.Auto_kill_Captain then
									pcall(function()
										if game.Players.LocalPlayer.Character:FindFirstChild("Combat") or game.Players.LocalPlayer.Character:FindFirstChild("Black Leg") or game.Players.LocalPlayer.Character:FindFirstChild("Electro") or game.Players.LocalPlayer.Character:FindFirstChild("Fishman Karate") or game.Players.LocalPlayer.Character:FindFirstChild("Dragon Claw") or game.Players.LocalPlayer.Character:FindFirstChild("Superhuman") or game.Players.LocalPlayer.Character:FindFirstChild("Sharkman Karate") then
											w.activeController.increment = 3
										else
											w.activeController.increment = 4
										end             
										if game.Players.LocalPlayer.Character:FindFirstChild("Black Leg") then
											w.activeController.timeToNextAttack = 3
										elseif game.Players.LocalPlayer.Character:FindFirstChild("Electro") then
											w.activeController.timeToNextAttack = 4
										else
											w.activeController.timeToNextAttack = 0
										end
										CameraShaker:Stop()
										w.activeController.attacking = false
										w.activeController.timeToNextBlock = 0
										w.activeController.blocking = false                            
										w.activeController.hitboxMagnitude = 100
										w.activeController.humanoid.AutoRotate = true
										  w.activeController.focusStart = 0
									end)
								end
							end)
						end)
					end
				end
			end
		end
		function isnil(thing)
		return (thing == nil)
		end
		local function round(n)
		return math.floor(tonumber(n) + 0.5)
		end
		Number = math.random(1, 1000000)
		function UpdateEspPlayer()
		for i,v in pairs(game:GetService'Players':GetChildren()) do
		pcall(function()
		if not isnil(v.Character) then
		if ESPPlayer then
			if not isnil(v.Character.Head) and not v.Character.Head:FindFirstChild('NameEsp'..Number) then
				local bill = Instance.new('BillboardGui',v.Character.Head)
				bill.Name = 'NameEsp'..Number
				bill.ExtentsOffset = Vector3.new(0, 1, 0)
				bill.Size = UDim2.new(1,200,1,30)
				bill.Adornee = v.Character.Head
				bill.AlwaysOnTop = true
				local name = Instance.new('TextLabel',bill)
				name.Font = "GothamBold"
				name.FontSize = "Size14"
				name.TextWrapped = true
				name.Text = (v.Name ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Character.Head.Position).Magnitude/3) ..' M')
				name.Size = UDim2.new(1,0,1,0)
				name.TextYAlignment = 'Top'
				name.BackgroundTransparency = 1
				name.TextStrokeTransparency = 0.5
				if v.Team == game.Players.LocalPlayer.Team then
					name.TextColor3 = Color3.new(0,255,0)
				else
					name.TextColor3 = Color3.new(255,0,0)
				end
			else
				v.Character.Head['NameEsp'..Number].TextLabel.Text = (v.Name ..' | '.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Character.Head.Position).Magnitude/3) ..' M\nHealth : ' .. round(v.Character.Humanoid.Health*100/v.Character.Humanoid.MaxHealth) .. '%')
			end
		else
			if v.Character.Head:FindFirstChild('NameEsp'..Number) then
				v.Character.Head:FindFirstChild('NameEsp'..Number):Destroy()
			end
		end
		end
		end)
		end
		end
		
		function UpdateIslandESP() 
		for i,v in pairs(game:GetService("Workspace")["_WorldOrigin"].Locations:GetChildren()) do
		pcall(function()
		if IslandESP then 
		if v.Name ~= "Sea" then
			if not v:FindFirstChild('NameEsp') then
				local bill = Instance.new('BillboardGui',v)
				bill.Name = 'NameEsp'
				bill.ExtentsOffset = Vector3.new(0, 1, 0)
				bill.Size = UDim2.new(1,200,1,30)
				bill.Adornee = v
				bill.AlwaysOnTop = true
				local name = Instance.new('TextLabel',bill)
				name.Font = "GothamBold"
				name.FontSize = "Size14"
				name.TextWrapped = true
				name.Size = UDim2.new(1,0,1,0)
				name.TextYAlignment = 'Top'
				name.BackgroundTransparency = 1
				name.TextStrokeTransparency = 0.5
				name.TextColor3 = Color3.fromRGB(80, 245, 245)
			else
				v['NameEsp'].TextLabel.Text = (v.Name ..'   \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' M')
			end
		end
		else
		if v:FindFirstChild('NameEsp') then
			v:FindFirstChild('NameEsp'):Destroy()
		end
		end
		end)
		end
		end
		
		function UpdateChestEsp() 
		for i,v in pairs(game:GetService("Workspace"):GetChildren()) do
		pcall(function()
		if string.find(v.Name,"Chest") then
		if ChestESP then
			if string.find(v.Name,"Chest") then
				if not v:FindFirstChild('NameEsp'..Number) then
					local bill = Instance.new('BillboardGui',v)
					bill.Name = 'NameEsp'..Number
					bill.ExtentsOffset = Vector3.new(0, 1, 0)
					bill.Size = UDim2.new(1,200,1,30)
					bill.Adornee = v
					bill.AlwaysOnTop = true
					local name = Instance.new('TextLabel',bill)
					name.Font = "GothamBold"
					name.FontSize = "Size14"
					name.TextWrapped = true
					name.Size = UDim2.new(1,0,1,0)
					name.TextYAlignment = 'Top'
					name.BackgroundTransparency = 1
					name.TextStrokeTransparency = 0.5
					name.TextColor3 = Color3.fromRGB(0, 255, 250)
				if v.Name == "Chest1" then
					name.Text = ("Chest 1" ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' M')
				end
				if v.Name == "Chest2" then
					name.Text = ("Chest 2" ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' M')
				end
			if v.Name == "Chest3" then
				name.Text = ("Chest 3" ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' M')
			end
			else
				v['NameEsp'..Number].TextLabel.Text = (v.Name ..'   \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' M')
			end
		end
		else
		if v:FindFirstChild('NameEsp'..Number) then
		v:FindFirstChild('NameEsp'..Number):Destroy()
		end
		end
		end
		end)
		end
		end
		
		function UpdateBfEsp() 
		for i,v in pairs(game:GetService("Workspace"):GetChildren()) do
		pcall(function()
		if DevilFruitESP then
		if string.find(v.Name, "Fruit") then   
			if not v.Handle:FindFirstChild('NameEsp'..Number) then
				local bill = Instance.new('BillboardGui',v.Handle)
				bill.Name = 'NameEsp'..Number
				bill.ExtentsOffset = Vector3.new(0, 1, 0)
				bill.Size = UDim2.new(1,200,1,30)
				bill.Adornee = v.Handle
				bill.AlwaysOnTop = true
				local name = Instance.new('TextLabel',bill)
				name.Font = "GothamBold"
				name.FontSize = "Size14"
				name.TextWrapped = true
				name.Size = UDim2.new(1,0,1,0)
				name.TextYAlignment = 'Top'
				name.BackgroundTransparency = 1
				name.TextStrokeTransparency = 0.5
				name.TextColor3 = Color3.fromRGB(255, 0, 0)
				name.Text = (v.Name ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Handle.Position).Magnitude/3) ..' M')
			else
				v.Handle['NameEsp'..Number].TextLabel.Text = (v.Name ..'   \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Handle.Position).Magnitude/3) ..' M')
			end
		end
		else
		if v.Handle:FindFirstChild('NameEsp'..Number) then
			v.Handle:FindFirstChild('NameEsp'..Number):Destroy()
			end
		end
		end)
		end
		end
		
		function UpdateFlowerEsp() 
		for i,v in pairs(game:GetService("Workspace"):GetChildren()) do
		pcall(function()
		if v.Name == "Flower2" or v.Name == "Flower1" then
		if FlowerESP then 
			if not v:FindFirstChild('NameEsp'..Number) then
				local bill = Instance.new('BillboardGui',v)
				bill.Name = 'NameEsp'..Number
				bill.ExtentsOffset = Vector3.new(0, 1, 0)
				bill.Size = UDim2.new(1,200,1,30)
				bill.Adornee = v
				bill.AlwaysOnTop = true
				local name = Instance.new('TextLabel',bill)
				name.Font = "GothamBold"
				name.FontSize = "Size14"
				name.TextWrapped = true
				name.Size = UDim2.new(1,0,1,0)
				name.TextYAlignment = 'Top'
				name.BackgroundTransparency = 1
				name.TextStrokeTransparency = 0.5
				name.TextColor3 = Color3.fromRGB(255, 0, 0)
			if v.Name == "Flower1" then 
				name.Text = ("Blue Flower" ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' M')
				name.TextColor3 = Color3.fromRGB(255, 0, 0)
			end
			if v.Name == "Flower2" then
				name.Text = ("Red Flower" ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' M')
				name.TextColor3 = Color3.fromRGB(255, 0, 0)
			end
		else
			v['NameEsp'..Number].TextLabel.Text = (v.Name ..'   \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Position).Magnitude/3) ..' M')
		end
		else
			if v:FindFirstChild('NameEsp'..Number) then
				v:FindFirstChild('NameEsp'..Number):Destroy()
			end
		end
		end   
		end)
		end
		end
		function TP(P1)
		Distance = (P1.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
		if Distance < 250 then
		Speed = 500
		elseif Distance < 500 then
		Speed = 400
		elseif Distance < 1000 then
		Speed = 350
		elseif Distance >= 1000 then
		Speed = 300
		end
		game:GetService("TweenService"):Create(
		game.Players.LocalPlayer.Character.HumanoidRootPart,
		TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear),
		{CFrame = P1}
		):Play()
		end
		function InfAb()
		if InfAbility then
		if not game:GetService("Players").LocalPlayer.Character.HumanoidRootPart:FindFirstChild("Agility") then
		local inf = Instance.new("ParticleEmitter")
		inf.Acceleration = Vector3.new(0,0,0)
		inf.Archivable = true
		inf.Drag = 20
		inf.EmissionDirection = Enum.NormalId.Top
		inf.Enabled = true
		inf.Lifetime = NumberRange.new(0,0)
		inf.LightInfluence = 0
		inf.LockedToPart = true
		inf.Name = "Agility"
		inf.Rate = 500
		local numberKeypoints2 = {
		NumberSequenceKeypoint.new(0, 0);
		NumberSequenceKeypoint.new(1, 4); 
		}
		inf.Size = NumberSequence.new(numberKeypoints2)
		inf.RotSpeed = NumberRange.new(9999, 99999)
		inf.Rotation = NumberRange.new(0, 0)
		inf.Speed = NumberRange.new(30, 30)
		inf.SpreadAngle = Vector2.new(0,0,0,0)
		inf.Texture = ""
		inf.VelocityInheritance = 0
		inf.ZOffset = 2
		inf.Transparency = NumberSequence.new(0)
		inf.Color = ColorSequence.new(Color3.fromRGB(0,0,0),Color3.fromRGB(0,0,0))
		inf.Parent = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart
		end
		else
		if game:GetService("Players").LocalPlayer.Character.HumanoidRootPart:FindFirstChild("Agility") then
		game:GetService("Players").LocalPlayer.Character.HumanoidRootPart:FindFirstChild("Agility"):Destroy()
		end
		end
		end
		
		local LocalPlayer = game:GetService'Players'.LocalPlayer
		local originalstam = LocalPlayer.Character.Energy.Value
		function infinitestam()
		LocalPlayer.Character.Energy.Changed:connect(function()
		if InfiniteEnergy then
		LocalPlayer.Character.Energy.Value = originalstam
		end 
		end)
		end
		
		spawn(function()
		pcall(function()
		while wait(.1) do
		if InfiniteEnergy then
		wait(0.1)
		originalstam = LocalPlayer.Character.Energy.Value
		infinitestam()
		end
		end
		end)
		end)
		
task.spawn(function()
	if game.Players.LocalPlayer.Character:FindFirstChild("Stun") then
		game.Players.LocalPlayer.Character.Stun.Changed:connect(function()
			pcall(function()
				if game.Players.LocalPlayer.Character:FindFirstChild("Stun") then
					game.Players.LocalPlayer.Character.Stun.Value = 0
				end
			end)
		end)
	end
end)
		function NoDodgeCool()
		if nododgecool then
		for i,v in next, getgc() do
		if game:GetService("Players").LocalPlayer.Character.Dodge then
		if typeof(v) == "function" and getfenv(v).script == game:GetService("Players").LocalPlayer.Character.Dodge then
			for i2,v2 in next, getupvalues(v) do
				if tostring(v2) == "0.1" then
				repeat wait(.1)
					setupvalue(v,i2,0)
				until not nododgecool
				end
			end
		end
		end
		end
		end
		end
		
		function fly()
		local mouse=game:GetService("Players").LocalPlayer:GetMouse''
		localplayer=game:GetService("Players").LocalPlayer
		game:GetService("Players").LocalPlayer.Character:WaitForChild("HumanoidRootPart")
		local torso = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart
		local speedSET=25
		local keys={a=false,d=false,w=false,s=false}
		local e1
		local e2
		local function start()
		local pos = Instance.new("BodyPosition",torso)
		local gyro = Instance.new("BodyGyro",torso)
		pos.Name="EPIXPOS"
		pos.maxForce = Vector3.new(math.huge, math.huge, math.huge)
		pos.position = torso.Position
		gyro.maxTorque = Vector3.new(9e9, 9e9, 9e9)
		gyro.CFrame = torso.CFrame
		repeat
		wait()
		localplayer.Character.Humanoid.PlatformStand=true
		local new=gyro.CFrame - gyro.CFrame.p + pos.position
		if not keys.w and not keys.s and not keys.a and not keys.d then
		speed=1
		end
		if keys.w then
		new = new + workspace.CurrentCamera.CoordinateFrame.lookVector * speed
		speed=speed+speedSET
		end
		if keys.s then
		new = new - workspace.CurrentCamera.CoordinateFrame.lookVector * speed
		speed=speed+speedSET
		end
		if keys.d then
		new = new * CFrame.new(speed,0,0)
		speed=speed+speedSET
		end
		if keys.a then
		new = new * CFrame.new(-speed,0,0)
		speed=speed+speedSET
		end
		if speed>speedSET then
		speed=speedSET
		end
		pos.position=new.p
		if keys.w then
		gyro.CFrame = workspace.CurrentCamera.CoordinateFrame*CFrame.Angles(-math.rad(speed*15),0,0)
		elseif keys.s then
		gyro.CFrame = workspace.CurrentCamera.CoordinateFrame*CFrame.Angles(math.rad(speed*15),0,0)
		else
		gyro.CFrame = workspace.CurrentCamera.CoordinateFrame
		end
		until not Fly
		if gyro then 
		gyro:Destroy() 
		end
		if pos then 
		pos:Destroy() 
		end
		flying=false
		localplayer.Character.Humanoid.PlatformStand=false
		speed=0
		end
		e1=mouse.KeyDown:connect(function(key)
		if not torso or not torso.Parent then 
		flying=false e1:disconnect() e2:disconnect() return 
		end
		if key=="w" then
		keys.w=true
		elseif key=="s" then
		keys.s=true
		elseif key=="a" then
		keys.a=true
		elseif key=="d" then
		keys.d=true
		end
		end)
		e2=mouse.KeyUp:connect(function(key)
		if key=="w" then
		keys.w=false
		elseif key=="s" then
		keys.s=false
		elseif key=="a" then
		keys.a=false
		elseif key=="d" then
		keys.d=false
		end
		end)
		start()
		end
		
		function Click()
		game:GetService'VirtualUser':CaptureController()
		game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
		end
		
		function AutoHaki()
		if not game:GetService("Players").LocalPlayer.Character:FindFirstChild("HasBuso") then
		game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Buso")
		end
		end
		
		function UnEquipWeapon(Weapon)
		if game.Players.LocalPlayer.Character:FindFirstChild(Weapon) then
		_G.NotAutoEquip = true
		wait(.5)
		game.Players.LocalPlayer.Character:FindFirstChild(Weapon).Parent = game.Players.LocalPlayer.Backpack
		wait(.1)
		_G.NotAutoEquip = false
		end
		end
		
		function EquipWeapon(ToolSe)
		if not _G.NotAutoEquip then
		if game.Players.LocalPlayer.Backpack:FindFirstChild(ToolSe) then
		Tool = game.Players.LocalPlayer.Backpack:FindFirstChild(ToolSe)
		wait(.1)
		game.Players.LocalPlayer.Character.Humanoid:EquipTool(Tool)
		end
		end
		end
		
	
		
		function GetDistance(target)
		return math.floor((target.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude)
		end
		
		function TP1(Pos)
		Distance = (Pos.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
		if Distance < 360 then
		Speed = 1200
		elseif Distance < 1000 then
		Speed = 360
		elseif Distance < 360 then
		Speed = 1200
		elseif Distance >= 1000 then
		Speed = 360
		end
		game:GetService("TweenService"):Create(
		game.Players.LocalPlayer.Character.HumanoidRootPart,
		TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear),
		{CFrame = Pos}
		):Play()
		end
		
		function TP(Pos)
		Distance = (Pos.Position - game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
		if Distance < 250 then
		Speed = 500
		elseif Distance >= 1000 then
		Speed = 325
		end
		game:GetService("TweenService"):Create(
		game:GetService("Players").LocalPlayer.Character.HumanoidRootPart,
		TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear),
		{CFrame = Pos}
		):Play()
		_G.Clip = true
		wait(Distance/Speed)
		_G.Clip = false
		end
		
		spawn(function()
		pcall(function()
		while wait() do
		if _G.AutoAdvanceDungeon or _G.AutoDoughtBoss or _G.Auto_DungeonMobAura or _G.AutoFarmChest or _G.AutoFarmBossHallow or _G.AutoFarmSwanGlasses or _G.AutoLongSword or _G.AutoBlackSpikeycoat or _G.AutoElectricClaw or _G.AutoFarmGunMastery or _G.AutoHolyTorch or _G.AutoLawRaid or _G.AutoFarmBoss or _G.AutoTwinHooks or _G.AutoOpenSwanDoor or _G.AutoDragon_Trident or _G.AutoSaber or _G.AutoFarmFruitMastery or _G.AutoFarmGunMastery or _G.TeleportIsland or _G.Auto_EvoRace or _G.AutoFarmAllMsBypassType or _G.AutoObservationv2 or _G.AutoMusketeerHat or _G.AutoEctoplasm or _G.AutoRengoku or _G.Auto_Rainbow_Haki or _G.AutoObservation or _G.AutoDarkDagger or _G.Safe_Mode or _G.MasteryFruit or _G.AutoBudySword or _G.AutoOderSword or _G.AutoBounty or _G.AutoAllBoss or _G.Auto_Bounty or _G.AutoSharkman or _G.Auto_Mastery_Fruit or _G.Auto_Mastery_Gun or _G.Auto_Dungeon or _G.Auto_Cavender or _G.Auto_Pole or _G.Auto_Kill_Ply or _G.Auto_Factory or _G.AutoSecondSea or _G.TeleportPly or _G.AutoBartilo or _G.Auto_DarkBoss or _G.GrabChest or _G.AutoFarmBounty or _G.Holy_Torch or _G.AutoFarm or _G.Clip or FarmBoss or _G.AutoElitehunter or _G.AutoThirdSea or _G.Auto_Bone or _G.AutoFarmCandy == true then
		if not game:GetService("Players").LocalPlayer.Character.HumanoidRootPart:FindFirstChild("BodyClip") then
			local Noclip = Instance.new("BodyVelocity")
			Noclip.Name = "BodyClip"
			Noclip.Parent = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart
			Noclip.MaxForce = Vector3.new(100000,100000,100000)
			Noclip.Velocity = Vector3.new(0,0,0)
		end
		end
		end
		end)
		end)
		
		local CameraShaker = require(game.ReplicatedStorage.Util.CameraShaker)
		CombatFrameworkR = require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework)
		y = debug.getupvalues(CombatFrameworkR)[2]
		spawn(function()
			game:GetService("RunService").RenderStepped:Connect(function()
				if _G.Auto_Cake_Princen or _G.AutoElitehunter or _G.FastFarmx or _G.FastFarmPlayer1 then
					if typeof(y) == "table" then
						pcall(function()
							CameraShaker:Stop()
							y.activeController.timeToNextAttack = (math.huge^math.huge^math.huge)
							y.activeController.timeToNextAttack = 0
							y.activeController.hitboxMagnitude = 150
							y.activeController.active = false
							y.activeController.timeToNextBlock = 0
							y.activeController.focusStart = 0
							y.activeController.increment = 4
							y.activeController.blocking = false
							y.activeController.attacking = false
							y.activeController.humanoid.AutoRotate = true
						end)
					end
				end
			end)
		end)
		if game.PlaceId == 2753915549 then  OldWolrd=true elseif game.PlaceId == 4442272183 then SecondSea=true elseif game.PlaceId == 7449423635 then ThirdSea=true else game.Players.LocalPlayer:Kick("You Have Banned") end

		function topos(Pos)
			Distance = (Pos.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
				if game.Players.LocalPlayer.Character.Humanoid.Sit == true then game.Players.LocalPlayer.Character.Humanoid.Sit = false end
				pcall(function() tween = game:GetService("TweenService"):Create(game.Players.LocalPlayer.Character.HumanoidRootPart,TweenInfo.new(Distance/240, Enum.EasingStyle.Linear),{CFrame = Pos}) end)
				tween:Play()
				if Distance <= 250 then
					tween:Cancel()
					game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Pos
				end
				if _G.Bypassse and Distance >= 3000 then
					if not  _G.AutoNextIsland then end
					  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Pos
					  game.Players.LocalPlayer.Character.Head:Destroy()
					  game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
					  game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
					  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Pos
					  wait(1)
					  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Pos
					  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Pos
					  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Pos
					  game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
					  game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
					  end
				if _G.StopTween == true then
					tween:Cancel()
					_G.Clip = false
				end
			 end
			 function ToTarget(Pos)
				Distance = (Pos.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
					if game.Players.LocalPlayer.Character.Humanoid.Sit == true then game.Players.LocalPlayer.Character.Humanoid.Sit = false end
					pcall(function() tween = game:GetService("TweenService"):Create(game.Players.LocalPlayer.Character.HumanoidRootPart,TweenInfo.new(Distance/240, Enum.EasingStyle.Linear),{CFrame = Pos}) end)
					tween:Play()
					if Distance <= 250 then
						tween:Cancel()
						game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Pos
					end
					if _G.Bypassse and Distance >= 3000 then
						if not  _G.AutoNextIsland then end
						  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Pos
						  game.Players.LocalPlayer.Character.Head:Destroy()
						  game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
						  game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
						  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Pos
						  wait(1)
						  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Pos
						  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Pos
						  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Pos
						  game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
						  game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
						  end
					if _G.StopTween == true then
						tween:Cancel()
						_G.Clip = false
					end
				 end
				
		
			function InstantTP(Pos)
				if not  _G.AutoNextIsland then end
				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Pos
				game.Players.LocalPlayer.Character.Humanoid.Health =- math.huge
				game:GetService("ReplicatedStorage").Remotes.CommF_:invokeServer("SetSpawnPoint")
			end
		
		spawn(function()
			while wait() do
				pcall(function()
					if _G.FastFarmPlayer1 then
						local MyLevel = game:GetService("Players").LocalPlayer.Data.Level.Value
				local quest = game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text
				local Player = string.split(quest," ")[2]
				 getgenv().SelectPly = string.split(quest," ")[2]
				 if string.find(quest,"Defeat") then
					repeat task.wait()
						if not game.Players.LocalPlayer.Character:FindFirstChild("HasBuso") then
							game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Buso")
						end
						game.Players:FindFirstChild(Player).Character.HumanoidRootPart.Size = Vector3.new(160,160,160)
						game:GetService("VirtualUser"):CaptureController()
						game:GetService("VirtualUser"):Button1Down(Vector2.new(1280,672))
						topos(game:GetService("Players")[getgenv().SelectPly].Character.HumanoidRootPart.CFrame*CFrame.new(-2,3,0))
						if game:GetService("Players")["LocalPlayer"].PlayerGui.Main.PvpDisabled.Visible == true then
							local args = {
								[1] = "EnablePvp"
							}
					
							game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
						end
						if game.Players.LocalPlayer.Character:FindFirstChild("Black Leg") and game.Players.LocalPlayer.Character:FindFirstChild("Black Leg").Level.Value >= 150 then
							game:service('VirtualInputManager'):SendKeyEvent(true, "V", false, game)
							game:service('VirtualInputManager'):SendKeyEvent(false, "V", false, game)
						end
						game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyHaki","Buso")
						if not game.Players.LocalPlayer.Character:FindFirstChild("HasBuso") then
							local args = {
								[1] = "Buso"
							}
							game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
						end
						EquipWeapon(_G.SelectWeapon)
						Attack()
						game:service('VirtualInputManager'):SendKeyEvent(true, "X", false, game)
						game:service('VirtualInputManager'):SendKeyEvent(true, "Z", false, game)
						game:service('VirtualInputManager'):SendKeyEvent(false, "X", false, game)
						game:service('VirtualInputManager'):SendKeyEvent(false, "Z", false, game)
						_G.FastAttackF2 = true
					until game.Players:FindFirstChild(Player).Character.Humanoid.Health <= 0 or not game.Players:FindFirstChild(Player) or not FastFarm()
						if not game.Players:FindFirstChild(Player) then
							game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("PlayerHunter")
							_G.FastAttackF2 = false
						end   
					else
						game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("PlayerHunter")
					end
				end
				end)
			end
		end)
		
		local CameraShaker = require(game.ReplicatedStorage.Util.CameraShaker)
		CombatFrameworkR = require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework)
		y = debug.getupvalues(CombatFrameworkR)[2]
		spawn(function()
			game:GetService("RunService").RenderStepped:Connect(function()
				if _G.FastFarmPlayer1s then
					if typeof(y) == "table" then
						pcall(function()
							CameraShaker:Stop()
							y.activeController.timeToNextAttack = (math.huge^math.huge^math.huge)
							y.activeController.timeToNextAttack = 0
							y.activeController.hitboxMagnitude = 200
							y.activeController.active = false
							y.activeController.timeToNextBlock = 0
							y.activeController.focusStart = 0
							y.activeController.increment = 4
							y.activeController.blocking = false
							y.activeController.attacking = false
							y.activeController.humanoid.AutoRotate = true
						end)
					end
				end
			end)
		end)
			  spawn(function()
				while wait() do
				pcall(function()
					if _G.FastFarmPlayer1 then
					if game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == false then
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("PlayerHunter")
				end
			end
				end)
				end
				end) 
		
	
	

		spawn(function()
		pcall(function()
		game:GetService("RunService").Stepped:Connect(function()
		if _G.AutoAdvanceDungeon or _G.AutoDoughtBoss or _G.Auto_DungeonMobAura or _G.AutoFarmChest or _G.AutoFarmBossHallow or _G.AutoFarmSwanGlasses or _G.AutoLongSword or _G.AutoBlackSpikeycoat or _G.AutoElectricClaw or _G.AutoFarmGunMastery or _G.AutoHolyTorch or _G.AutoLawRaid or _G.AutoFarmBoss or _G.AutoTwinHooks or _G.AutoOpenSwanDoor or _G.AutoDragon_Trident or _G.AutoSaber or _G.NOCLIP or _G.AutoFarmFruitMastery or _G.AutoFarmGunMastery or _G.TeleportIsland or _G.Auto_EvoRace or _G.AutoFarmAllMsBypassType or _G.AutoObservationv2 or _G.AutoMusketeerHat or _G.AutoEctoplasm or _G.AutoRengoku or _G.Auto_Rainbow_Haki or _G.AutoObservation or _G.AutoDarkDagger or _G.Safe_Mode or _G.MasteryFruit or _G.AutoBudySword or _G.AutoOderSword or _G.AutoBounty or _G.AutoAllBoss or _G.Auto_Bounty or _G.AutoSharkman or _G.Auto_Mastery_Fruit or _G.Auto_Mastery_Gun or _G.Auto_Dungeon or _G.Auto_Cavender or _G.Auto_Pole or _G.Auto_Kill_Ply or _G.Auto_Factory or _G.AutoSecondSea or _G.TeleportPly or _G.AutoBartilo or _G.Auto_DarkBoss or _G.GrabChest or _G.AutoFarmBounty or _G.Holy_Torch or _G.AutoFarm or _G.Clip or _G.AutoElitehunter or _G.AutoThirdSea or _G.Auto_Bone or _G.AutoFarmCandy == true then
		for _, v in pairs(game:GetService("Players").LocalPlayer.Character:GetDescendants()) do
			if v:IsA("BasePart") then
				v.CanCollide = false    
			end
		end
		end
		end)
		end)
		end)
		local r=game:GetService("Players").LocalPlayer
		getgenv().ToTarget=function(p)
		task.spawn(function()
		pcall(function()
		if r:DistanceFromCharacter(p.Position)<=300 then 
		r.Character.HumanoidRootPart.CFrame=p
		else if not game.Players.LocalPlayer.Character:FindFirstChild("Root")then 
		local K=Instance.new("Part",game.Players.LocalPlayer.Character)
		K.Size=Vector3.new(1,0.5,1)
		K.Name="Root"
		K.Anchored=true
		K.Transparency=1
		K.CanCollide=false
		K.CFrame=game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame*CFrame.new(0,20,0)
		end
		
		local U=(game.Players.LocalPlayer.Character.HumanoidRootPart.Position-p.Position).Magnitude
		local z=game:service("TweenService")
		local B=TweenInfo.new((p.Position-game.Players.LocalPlayer.Character.Root.Position).Magnitude/300,Enum.EasingStyle.Linear)
		local S,g=pcall(function()
		local q=z:Create(game.Players.LocalPlayer.Character.Root,B,{CFrame=p})
		q:Play()
		end)
		if not S then 
		return g
		end
		game.Players.LocalPlayer.Character.Root.CFrame=game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
		if S and game.Players.LocalPlayer.Character:FindFirstChild("Root")then 
		pcall(function()
		if(game.Players.LocalPlayer.Character.HumanoidRootPart.Position-p.Position).Magnitude>=20 then 
		spawn(function()
		pcall(function()if(game.Players.LocalPlayer.Character.Root.Position-game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude>150 then game.Players.LocalPlayer.Character.Root.CFrame=game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
		else game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame=game.Players.LocalPlayer.Character.Root.CFrame
		end
		end)
		end)
		elseif(game.Players.LocalPlayer.Character.HumanoidRootPart.Position-p.Position).Magnitude>=10 and(game.Players.LocalPlayer.Character.HumanoidRootPart.Position-p.Position).Magnitude<20 then 
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame=p
		elseif(game.Players.LocalPlayer.Character.HumanoidRootPart.Position-p.Position).Magnitude<10 then 
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame=p
		end
		end)
		end
		end
		end)
		end)
		end    
		spawn(function()
		while wait() do
		if _G.AutoDoughtBoss or _G.FastFarm or _G.AutoFarm or _G.AutoFarmBossHallow or _G.AutoFarmSwanGlasses or _G.AutoLongSword or _G.AutoBlackSpikeycoat or _G.AutoElectricClaw or _G.AutoFarmGunMastery or _G.AutoHolyTorch or _G.AutoLawRaid or _G.AutoFarmBoss or _G.AutoTwinHooks or _G.AutoOpenSwanDoor or _G.AutoDragon_Trident or _G.AutoSaber or _G.NOCLIP or _G.AutoFarmFruitMastery or _G.AutoFarmGunMastery or _G.TeleportIsland or _G.Auto_EvoRace or _G.AutoFarmAllMsBypassType or _G.AutoObservationv2 or _G.AutoMusketeerHat or _G.AutoEctoplasm or _G.AutoRengoku or _G.Auto_Rainbow_Haki or _G.AutoObservation or _G.AutoDarkDagger or _G.Safe_Mode or _G.MasteryFruit or _G.AutoBudySword or _G.AutoOderSword or _G.AutoAllBoss or _G.Auto_Bounty or _G.AutoSharkman or _G.Auto_Mastery_Fruit or _G.Auto_Mastery_Gun or _G.Auto_Dungeon or _G.Auto_Cavender or _G.Auto_Pole or _G.Auto_Kill_Ply or _G.Auto_Factory or _G.AutoSecondSea or _G.TeleportPly or _G.AutoBartilo or _G.Auto_DarkBoss or _G.AutoFarm or _G.Clip or _G.AutoElitehunter or _G.AutoThirdSea or _G.Auto_Bone or _G.AutoFarmCandy or _G.Auto_kill_Empress or _G.Auto_kill_Captain == true then
		pcall(function()
		game:GetService("ReplicatedStorage").Remotes.CommE:FireServer("Ken",true)
		end)
		end    
		end
		end)
		
		function StopTween(target)
		if not target then
		_G.StopTween = true
		wait()
		topos(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame)
		wait()
		if game:GetService("Players").LocalPlayer.Character.HumanoidRootPart:FindFirstChild("BodyClip") then
		game:GetService("Players").LocalPlayer.Character.HumanoidRootPart:FindFirstChild("BodyClip"):Destroy()
		end
		_G.StopTween = false
		_G.Clip = false
		end
		end
		
		spawn(function()
		pcall(function()
		while wait() do
		for i,v in pairs(game:GetService("Players").LocalPlayer.Backpack:GetChildren()) do  
		if v:IsA("Tool") then
			if v:FindFirstChild("RemoteFunctionShoot") then 
				SelectWeaponGun = v.Name
			end
		end
		end
		end
		end)
		end)
		
		game:GetService("Players").LocalPlayer.Idled:connect(function()
		game:GetService("VirtualUser"):Button2Down(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
		wait(1)
		game:GetService("VirtualUser"):Button2Up(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
		end)
		function CheckBossQuest()
			if _G.Select_Boss == "Saber Expert [Lv. 200] [Boss]" then
				MsBoss = "Saber Expert [Lv. 200] [Boss]"
				NameBoss = "Saber Expert"
				CFrameBoss = CFrame.new(-1458.89502, 29.8870335, -50.633564, 0.858821094, 1.13848939e-08, 0.512275636, -4.85649254e-09, 1, -1.40823326e-08, -0.512275636, 9.6063415e-09, 0.858821094)
			elseif _G.Select_Boss == "The Saw [Lv. 100] [Boss]" then
				MsBoss = "The Saw [Lv. 100] [Boss]"
				NameBoss = "The Saw"
				CFrameBoss = CFrame.new(-683.519897, 13.8534927, 1610.87854, -0.290192783, 6.88365773e-08, 0.956968188, 6.98413629e-08, 1, -5.07531119e-08, -0.956968188, 5.21077759e-08, -0.290192783)
			elseif _G.Select_Boss == "Greybeard [Lv. 750] [Raid Boss]" then
				MsBoss = "Greybeard [Lv. 750] [Raid Boss]"
				NameBoss = "Greybeard"
				CFrameBoss = CFrame.new(-4955.72949, 80.8163834, 4305.82666, -0.433646321, -1.03394289e-08, 0.901083171, -3.0443168e-08, 1, -3.17633075e-09, -0.901083171, -2.88092288e-08, -0.433646321)
			elseif _G.Select_Boss == "The Gorilla King [Lv. 25] [Boss]" then
				MsBoss = "The Gorilla King [Lv. 25] [Boss]"
				NameBoss = "The Gorilla King"
				NameQuestBoss = "JungleQuest"
				LevelQuestBoss = 3
				CFrameQuestBoss = CFrame.new(-1604.12012, 36.8521118, 154.23732, 0.0648873374, -4.70858913e-06, -0.997892559, 1.41431883e-07, 1, -4.70933674e-06, 0.997892559, 1.64442184e-07, 0.0648873374)
				CFrameBoss = CFrame.new(-1223.52808, 6.27936459, -502.292664, 0.310949147, -5.66602516e-08, 0.950426519, -3.37275488e-08, 1, 7.06501808e-08, -0.950426519, -5.40241736e-08, 0.310949147)
			elseif _G.Select_Boss == "Bobby [Lv. 55] [Boss]" then
				MsBoss = "Bobby [Lv. 55] [Boss]"
				NameBoss = "Bobby"
				NameQuestBoss = "BuggyQuest1"
				LevelQuestBoss = 3
				CFrameQuestBoss = CFrame.new(-1139.59717, 4.75205183, 3825.16211, -0.959730506, -7.5857054e-09, 0.280922383, -4.06310328e-08, 1, -1.11807175e-07, -0.280922383, -1.18718916e-07, -0.959730506)
				CFrameBoss = CFrame.new(-1147.65173, 32.5966301, 4156.02588, 0.956680477, -1.77109952e-10, -0.29113996, 5.16530874e-10, 1, 1.08897802e-09, 0.29113996, -1.19218679e-09, 0.956680477)
			elseif _G.Select_Boss == "Yeti [Lv. 110] [Boss]" then
				MsBoss = "Yeti [Lv. 110] [Boss]"
				NameBoss = "Yeti"
				NameQuestBoss = "SnowQuest"
				LevelQuestBoss = 3
				CFrameQuestBoss = CFrame.new(1384.90247, 87.3078308, -1296.6825, 0.280209213, 2.72035177e-08, -0.959938943, -6.75690828e-08, 1, 8.6151708e-09, 0.959938943, 6.24481444e-08, 0.280209213)
				CFrameBoss = CFrame.new(1221.7356, 138.046906, -1488.84082, 0.349343032, -9.49245944e-08, 0.936994851, 6.29478194e-08, 1, 7.7838429e-08, -0.936994851, 3.17894653e-08, 0.349343032)
			elseif _G.Select_Boss == "Mob Leader [Lv. 120] [Boss]" then
				MsBoss = "Mob Leader [Lv. 120] [Boss]"
				NameBoss = "Mob Leader"
				CFrameBoss = CFrame.new(-2848.59399, 7.4272871, 5342.44043, -0.928248107, -8.7248246e-08, 0.371961564, -7.61816636e-08, 1, 4.44474857e-08, -0.371961564, 1.29216433e-08, -0.92824)
			elseif _G.Select_Boss == "Vice Admiral [Lv. 130] [Boss]" then
				MsBoss = "Vice Admiral [Lv. 130] [Boss]"
				NameBoss = "Vice Admiral"
				NameQuestBoss = "MarineQuest2"
				LevelQuestBoss = 2
				CFrameQuestBoss = CFrame.new(-5035.42285, 28.6520386, 4324.50293, -0.0611100644, -8.08395768e-08, 0.998130739, -1.57416586e-08, 1, 8.00271849e-08, -0.998130739, -1.08217701e-08, -0.0611100644)
				CFrameBoss = CFrame.new(-5078.45898, 99.6520691, 4402.1665, -0.555574954, -9.88630566e-11, 0.831466436, -6.35508286e-08, 1, -4.23449258e-08, -0.831466436, -7.63661632e-08, -0.555574954)
			elseif _G.Select_Boss == "Warden [Lv. 175] [Boss]" then
				MsBoss = "Warden [Lv. 175] [Boss]"
				NameBoss = "Warden"
				NameQuestBoss = "ImpelQuest"
				LevelQuestBoss = 1
				CFrameQuestBoss = CFrame.new(4851.35059, 5.68744135, 743.251282, -0.538484037, -6.68303741e-08, -0.842635691, 1.38001752e-08, 1, -8.81300792e-08, 0.842635691, -5.90851599e-08, -0.538484037)
				CFrameBoss = CFrame.new(5232.5625, 5.26856995, 747.506897, 0.943829298, -4.5439414e-08, 0.330433697, 3.47818627e-08, 1, 3.81658154e-08, -0.330433697, -2.45289105e-08, 0.943829298)
			elseif _G.Select_Boss == "Chief Warden [Lv. 200] [Boss]" then
				MsBoss = "Chief Warden [Lv. 200] [Boss]"
				NameBoss = "Chief Warden"
				NameQuestBoss = "ImpelQuest"
				LevelQuestBoss = 2
				CFrameQuestBoss = CFrame.new(4851.35059, 5.68744135, 743.251282, -0.538484037, -6.68303741e-08, -0.842635691, 1.38001752e-08, 1, -8.81300792e-08, 0.842635691, -5.90851599e-08, -0.538484037)
				CFrameBoss = CFrame.new(5232.5625, 5.26856995, 747.506897, 0.943829298, -4.5439414e-08, 0.330433697, 3.47818627e-08, 1, 3.81658154e-08, -0.330433697, -2.45289105e-08, 0.943829298)
			elseif _G.Select_Boss == "Swan [Lv. 225] [Boss]" then
				MsBoss = "Swan [Lv. 225] [Boss]"
				NameBoss = "Swan"
				NameQuestBoss = "ImpelQuest"
				LevelQuestBoss = 3
				CFrameQuestBoss = CFrame.new(4851.35059, 5.68744135, 743.251282, -0.538484037, -6.68303741e-08, -0.842635691, 1.38001752e-08, 1, -8.81300792e-08, 0.842635691, -5.90851599e-08, -0.538484037)
				CFrameBoss = CFrame.new(5232.5625, 5.26856995, 747.506897, 0.943829298, -4.5439414e-08, 0.330433697, 3.47818627e-08, 1, 3.81658154e-08, -0.330433697, -2.45289105e-08, 0.943829298)
			elseif _G.Select_Boss == "Magma Admiral [Lv. 350] [Boss]" then
				MsBoss = "Magma Admiral [Lv. 350] [Boss]"
				NameBoss = "Magma Admiral"
				NameQuestBoss = "MagmaQuest"
				LevelQuestBoss = 3
				CFrameQuestBoss = CFrame.new(-5317.07666, 12.2721891, 8517.41699, 0.51175487, -2.65508806e-08, -0.859131515, -3.91131572e-08, 1, -5.42026761e-08, 0.859131515, 6.13418294e-08, 0.51175487)
				CFrameBoss = CFrame.new(-5530.12646, 22.8769703, 8859.91309, 0.857838571, 2.23414389e-08, 0.513919294, 1.53689133e-08, 1, -6.91265853e-08, -0.513919294, 6.71978384e-08, 0.857838571)
			elseif _G.Select_Boss == "Fishman Lord [Lv. 425] [Boss]" then
				MsBoss = "Fishman Lord [Lv. 425] [Boss]"
				NameBoss = "Fishman Lord"
				NameQuestBoss = "FishmanQuest"
				LevelQuestBoss = 3
				CFrameQuestBoss = CFrame.new(61123.0859, 18.5066795, 1570.18018, 0.927145958, 1.0624845e-07, 0.374700129, -6.98219367e-08, 1, -1.10790765e-07, -0.374700129, 7.65569368e-08, 0.927145958)
				CFrameBoss = CFrame.new(61351.7773, 31.0306778, 1113.31409, 0.999974668, 0, -0.00714713801, 0, 1.00000012, 0, 0.00714714266, 0, 0.999974549)
			elseif _G.Select_Boss == "Wysper [Lv. 500] [Boss]" then
				MsBoss = "Wysper [Lv. 500] [Boss]"
				NameBoss = "Wysper"
				NameQuestBoss = "SkyExp1Quest"
				LevelQuestBoss = 3
				CFrameQuestBoss = CFrame.new(-7862.94629, 5545.52832, -379.833954, 0.462944925, 1.45838088e-08, -0.886386991, 1.0534996e-08, 1, 2.19553424e-08, 0.886386991, -1.95022007e-08, 0.462944925)
				CFrameBoss = CFrame.new(-7925.48389, 5550.76074, -636.178345, 0.716468513, -1.22915289e-09, 0.697619379, 3.37381434e-09, 1, -1.70304748e-09, -0.697619379, 3.57381835e-09, 0.716468513)
			elseif _G.Select_Boss == "Thunder God [Lv. 575] [Boss]" then
				MsBoss = "Thunder God [Lv. 575] [Boss]"
				NameBoss = "Thunder God"
				NameQuestBoss = "SkyExp2Quest"
				LevelQuestBoss = 3
				CFrameQuestBoss = CFrame.new(-7902.78613, 5635.99902, -1411.98706, -0.0361216255, -1.16895912e-07, 0.999347389, 1.44533963e-09, 1, 1.17024491e-07, -0.999347389, 5.6715117e-09, -0.0361216255)
				CFrameBoss = CFrame.new(-7917.53613, 5616.61377, -2277.78564, 0.965189934, 4.80563429e-08, -0.261550069, -6.73089886e-08, 1, -6.46515304e-08, 0.261550069, 8.00056768e-08, 0.965189934)
			elseif _G.Select_Boss == "Cyborg [Lv. 675] [Boss]" then
				MsBoss = "Cyborg [Lv. 675] [Boss]"
				NameBoss = "Cyborg"
				NameQuestBoss = "FountainQuest"
				LevelQuestBoss = 3
				CFrameQuestBoss = CFrame.new(5253.54834, 38.5361786, 4050.45166, -0.0112687312, -9.93677887e-08, -0.999936521, 2.55291371e-10, 1, -9.93769547e-08, 0.999936521, -1.37512213e-09, -0.0112687312)
				CFrameBoss = CFrame.new(6041.82813, 52.7112198, 3907.45142, -0.563162148, 1.73805248e-09, -0.826346457, -5.94632716e-08, 1, 4.26280238e-08, 0.826346457, 7.31437524e-08, -0.563162148)
			-- New World
			elseif _G.Select_Boss == "Diamond [Lv. 750] [Boss]" then
				MsBoss = "Diamond [Lv. 750] [Boss]"
				NameBoss = "Diamond"
				NameQuestBoss = "Area1Quest"
				LevelQuestBoss = 3
				CFrameQuestBoss = CFrame.new(-424.080078, 73.0055847, 1836.91589, 0.253544956, -1.42165932e-08, 0.967323601, -6.00147771e-08, 1, 3.04272909e-08, -0.967323601, -6.5768397e-08, 0.253544956)
				CFrameBoss = CFrame.new(-1736.26587, 198.627731, -236.412857, -0.997808516, 0, -0.0661673471, 0, 1, 0, 0.0661673471, 0, -0.997808516)
			elseif _G.Select_Boss == "Jeremy [Lv. 850] [Boss]" then
				MsBoss = "Jeremy [Lv. 850] [Boss]"
				NameBoss = "Jeremy"
				NameQuestBoss = "Area2Quest"
				LevelQuestBoss = 3
				CFrameQuestBoss = CFrame.new(632.698608, 73.1055908, 918.666321, -0.0319722369, 8.96074881e-10, -0.999488771, 1.36326533e-10, 1, 8.92172336e-10, 0.999488771, -1.07732087e-10, -0.0319722369)
				CFrameBoss = CFrame.new(2203.76953, 448.966034, 752.731079, -0.0217453763, 0, -0.999763548, 0, 1, 0, 0.999763548, 0, -0.0217453763)
			elseif _G.Select_Boss == "Fajita [Lv. 925] [Boss]" then
				MsBoss = "Fajita [Lv. 925] [Boss]"
				NameBoss = "Fajita"
				NameQuestBoss = "MarineQuest3"
				LevelQuestBoss = 3
				CFrameQuestBoss = CFrame.new(-2442.65015, 73.0511475, -3219.11523, -0.873540044, 4.2329841e-08, -0.486752301, 5.64383384e-08, 1, -1.43220786e-08, 0.486752301, -3.99823996e-08, -0.873540044)
				CFrameBoss = CFrame.new(-2297.40332, 115.449463, -3946.53833, 0.961227536, -1.46645796e-09, -0.275756449, -2.3212845e-09, 1, -1.34094433e-08, 0.275756449, 1.35296352e-08, 0.961227536)
			elseif _G.Select_Boss == "Don Swan [Lv. 1000] [Boss]" then
				MsBoss = "Don Swan [Lv. 1000] [Boss]"
				NameBoss = "Don Swan"
				CFrameBoss = CFrame.new(2288.802, 15.1870775, 863.034607, 0.99974072, -8.41247214e-08, -0.0227668174, 8.4774733e-08, 1, 2.75850098e-08, 0.0227668174, -2.95079072e-08, 0.99974072)
			elseif _G.Select_Boss == "Smoke Admiral [Lv. 1150] [Boss]" then
				MsBoss = "Smoke Admiral [Lv. 1150] [Boss]"
				NameBoss = "Smoke Admiral"
				NameQuestBoss = "IceSideQuest"
				LevelQuestBoss = 3
				CFrameQuestBoss = CFrame.new(-6059.96191, 15.9868021, -4904.7373, -0.444992423, -3.0874483e-09, 0.895534337, -3.64098796e-08, 1, -1.4644522e-08, -0.895534337, -3.91229982e-08, -0.444992423)
				CFrameBoss = CFrame.new(-5115.72754, 23.7664986, -5338.2207, 0.251453817, 1.48345061e-08, -0.967869282, 4.02796978e-08, 1, 2.57916977e-08, 0.967869282, -4.54708946e-08, 0.251453817)
			elseif _G.Select_Boss == "Cursed Captain [Lv. 1325] [Raid Boss]" then
				MsBoss = "Cursed Captain [Lv. 1325] [Raid Boss]"
				NameBoss = "Cursed Captain"
				CFrameBoss = CFrame.new(916.928589, 181.092773, 33422, -0.999505103, 9.26310495e-09, 0.0314563364, 8.42916226e-09, 1, -2.6643713e-08, -0.0314563364, -2.63653774e-08, -0.999505103)
			elseif _G.Select_Boss == "Darkbeard [Lv. 1000] [Raid Boss]" then
				MsBoss = "Darkbeard [Lv. 1000] [Raid Boss]"
				NameBoss = "Darkbeard"
				CFrameBoss = CFrame.new(3876.00366, 24.6882591, -3820.21777, -0.976951957, 4.97356325e-08, 0.213458836, 4.57335361e-08, 1, -2.36868622e-08, -0.213458836, -1.33787044e-08, -0.976951957)
			elseif _G.Select_Boss == "Order [Lv. 1250] [Raid Boss]" then
				MsBoss = "Order [Lv. 1250] [Raid Boss]"
				NameBoss = "Order"
				CFrameBoss = CFrame.new(-6221.15039, 16.2351036, -5045.23584, -0.380726993, 7.41463495e-08, 0.924687505, 5.85604774e-08, 1, -5.60738549e-08, -0.924687505, 3.28013137e-08, -0.380726993)
			elseif _G.Select_Boss == "Awakened Ice Admiral [Lv. 1400] [Boss]" then
				MsBoss = "Awakened Ice Admiral [Lv. 1400] [Boss]"
				NameBoss = "Awakened Ice Admiral"
				NameQuestBoss = "FrostQuest"
				LevelQuestBoss = 3
				CFrameQuestBoss = CFrame.new(5669.33203, 28.2118053, -6481.55908, 0.921275556, -1.25320829e-08, 0.388910472, 4.72230788e-08, 1, -7.96414241e-08, -0.388910472, 9.17372489e-08, 0.921275556)
				CFrameBoss = CFrame.new(6407.33936, 340.223785, -6892.521, 0.49051559, -5.25310213e-08, -0.871432424, -2.76146022e-08, 1, -7.58250565e-08, 0.871432424, 6.12576301e-08, 0.49051559)
			elseif _G.Select_Boss == "Tide Keeper [Lv. 1475] [Boss]" then
				MsBoss = "Tide Keeper [Lv. 1475] [Boss]"
				 NameBoss = "Tide Keeper"
				NameQuestBoss = "ForgottenQuest"             
				LevelQuestBoss = 3
				CFrameQuestBoss = CFrame.new(-3053.89648, 236.881363, -10148.2324, -0.985987961, -3.58504737e-09, 0.16681771, -3.07832915e-09, 1, 3.29612559e-09, -0.16681771, 2.73641976e-09, -0.985987961)
				CFrameBoss = CFrame.new(-3570.18652, 123.328949, -11555.9072, 0.465199202, -1.3857326e-08, 0.885206044, 4.0332897e-09, 1, 1.35347511e-08, -0.885206044, -2.72606271e-09, 0.465199202)
			-- Thire World
			elseif _G.Select_Boss == "Stone [Lv. 1550] [Boss]" then
				MsBoss = "Stone [Lv. 1550] [Boss]"
				NameBoss = "Stone"
				NameQuestBoss = "PiratePortQuest"             
				LevelQuestBoss = 3
				CFrameQuestBoss = CFrame.new(-290, 44, 5577)
				CFrameBoss = CFrame.new(-1085, 40, 6779)
			elseif _G.Select_Boss == "Island Empress [Lv. 1675] [Boss]" then
				MsBoss = "Island Empress [Lv. 1675] [Boss]"
				 NameBoss = "Island Empress"
				NameQuestBoss = "AmazonQuest2"             
				LevelQuestBoss = 3
				CFrameQuestBoss = CFrame.new(5443, 602, 752)
				CFrameBoss = CFrame.new(5659, 602, 244)
			elseif _G.Select_Boss == "Kilo Admiral [Lv. 1750] [Boss]" then
				MsBoss = "Kilo Admiral [Lv. 1750] [Boss]"
				NameBoss = "Kilo Admiral"
				NameQuestBoss = "MarineTreeIsland"             
				LevelQuestBoss = 3
				CFrameQuestBoss = CFrame.new(2178, 29, -6737)
				CFrameBoss =CFrame.new(2846, 433, -7100)
			elseif _G.Select_Boss == "Captain Elephant [Lv. 1875] [Boss]" then
				MsBoss = "Captain Elephant [Lv. 1875] [Boss]"
				NameBoss = "Captain Elephant"
				NameQuestBoss = "DeepForestIsland"             
				LevelQuestBoss = 3
				CFrameQuestBoss = CFrame.new(-13232, 333, -7631)
				CFrameBoss = CFrame.new(-13221, 325, -8405)
			elseif _G.Select_Boss == "Beautiful Pirate [Lv. 1950] [Boss]" then
				MsBoss = "Beautiful Pirate [Lv. 1950] [Boss]"
				NameBoss = "Beautiful Pirate"
				NameQuestBoss = "DeepForestIsland2"             
				LevelQuestBoss = 3
				CFrameQuestBoss = CFrame.new(-12686, 391, -9902)
				CFrameBoss = CFrame.new(5182, 23, -20)
			elseif _G.Select_Boss == "Cake Queen [Lv. 2175] [Boss]" then
				MsBoss = "Cake Queen [Lv. 2175] [Boss]"
				NameQuestBoss = "IceCreamIslandQuest"             
				LevelQuestBoss = 3
				CFrameQuestBoss = CFrame.new(-716, 382, -11010)
				CFrameBoss = CFrame.new(-821, 66, -10965)
			elseif _G.Select_Boss == "rip_indra True Form [Lv. 5000] [Raid Boss]" then
				MsBoss = "rip_indra True Form [Lv. 5000] [Raid Boss]"
				NameBoss = "rip_indra True Form"
				CFrameBoss = CFrame.new(-5359, 424, -2735)
			elseif _G.Select_Boss == "Longma [Lv. 2000] [Boss]" then
				MsBoss = "Longma [Lv. 2000] [Boss]"
				NameBoss = "Longma"
				CFrameBoss = CFrame.new(-10248.3936, 353.79129, -9306.34473)
			elseif _G.Select_Boss == "Soul Reaper [Lv. 2100] [Raid Boss]" then
				MsBoss = "Soul Reaper [Lv. 2100] [Raid Boss]"
				NameBoss = "Soul Reaper"
				CFrameBoss = CFrame.new(-9515.62109, 315.925537, 6691.12012)
			end
		end
	
	
	
		setfflag("HumanoidParallelRemoveNoPhysics", "False");
		setfflag("HumanoidParallelRemoveNoPhysicsNoSimulate2", "False");
		setfflag("CrashPadUploadToBacktraceToBacktraceBaseUrl", "");
		setfflag("CrashUploadToBacktracePercentage", "0");
		setfflag("CrashUploadToBacktraceBlackholeToken", "");
		setfflag("CrashUploadToBacktraceWindowsPlayerToken", "");
		
		local r=game:GetService("Players").LocalPlayer
		getgenv().ToTarget=function(p)
			task.spawn(function()
				pcall(function()
					if r:DistanceFromCharacter(p.Position)<=300 then 
						r.Character.HumanoidRootPart.CFrame=p
					else if not game.Players.LocalPlayer.Character:FindFirstChild("Root")then 
						local K=Instance.new("Part",game.Players.LocalPlayer.Character)
						K.Size=Vector3.new(1,0.5,1)
						K.Name="Root"
						K.Anchored=true
						K.Transparency=1
						K.CanCollide=false
						K.CFrame=game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame*CFrame.new(0,20,0)
					end
		
					local U=(game.Players.LocalPlayer.Character.HumanoidRootPart.Position-p.Position).Magnitude
					local z=game:service("TweenService")
					local B=TweenInfo.new((p.Position-game.Players.LocalPlayer.Character.Root.Position).Magnitude/300,Enum.EasingStyle.Linear)
					local S,g=pcall(function()
						local q=z:Create(game.Players.LocalPlayer.Character.Root,B,{CFrame=p})
		q:Play()
		end)
		if not S then 
			return g
		end
		game.Players.LocalPlayer.Character.Root.CFrame=game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
		if S and game.Players.LocalPlayer.Character:FindFirstChild("Root")then 
			pcall(function()
				if(game.Players.LocalPlayer.Character.HumanoidRootPart.Position-p.Position).Magnitude>=20 then 
					spawn(function()
						pcall(function()if(game.Players.LocalPlayer.Character.Root.Position-game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude>150 then game.Players.LocalPlayer.Character.Root.CFrame=game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
		else game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame=game.Players.LocalPlayer.Character.Root.CFrame
		end
		end)
		end)
		elseif(game.Players.LocalPlayer.Character.HumanoidRootPart.Position-p.Position).Magnitude>=10 and(game.Players.LocalPlayer.Character.HumanoidRootPart.Position-p.Position).Magnitude<20 then 
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame=p
		elseif(game.Players.LocalPlayer.Character.HumanoidRootPart.Position-p.Position).Magnitude<10 then 
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame=p
		end
		end)
		end
		end
		end)
		end)
		end
		
		
		task.spawn(function()
			while wait() do
				if _G.SelectWeapon == nil or _G.SelectWeapon == "" or _G.SelectWeapon == "Melee" then
					for i ,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
						if v.ToolTip == "Melee" then
							_G.SelectWeapon = v.Name
						end
					end
				end
			end
		end)
		task.spawn(function()
			while wait() do
				if _G.SelectWeapon == "Sword" then
					for i ,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
						if v.ToolTip == "Sword" then
							_G.SelectWeapon = v.Name
						end
					end
				end
			end
		end)
		spawn(function()
			while wait() do
				pcall(function()
					if _G.Auto_Pole and game.ReplicatedStorage:FindFirstChild("Thunder God [Lv. 575] [Boss]") or game.Workspace.Enemies:FindFirstChild("Thunder God [Lv. 575] [Boss]") then
						if game.Workspace.Enemies:FindFirstChild("Thunder God [Lv. 575] [Boss]") then
							for i,v in pairs(game.Workspace.Enemies:GetChildren()) do
								if _G.Auto_Pole and v.Name == "Thunder God [Lv. 575] [Boss]" and v:FindFirstChild("HumanoidRootPart") and v:FindFirstChild("Humanoid") and v.Humanoid.Health > 0 then
									repeat wait()  
										AutoHaki()
										EquipWeapon(_G.SelectWeapon)
										getgenv().ToTarget(v.HumanoidRootPart.CFrame * CFrame.new(0,17,0))
										v.HumanoidRootPart.Size = Vector3.new(120,160,120)
										_G.FastAttackF2 = true  
									until not _G.Auto_Pole or v.Humanoid.Health <= 0 or not v.Parent
								end
							end
						else
							getgenv().ToTarget(CFrame.new(-7900.66406, 5606.90918, -2267.46436))
						end
					else
						if _G.Auto_Pole_Hop then
							Hop()
						end
					end
				end)
			end
		end)
	   -- Anti Kick
	
	
		spawn(function()
			game:GetService("RunService").Heartbeat:Connect(function()
				if _G.AutoFarm or _G.AutoEliteHunter or _G.AutoEliteHunter_Hop or _G.Mobaura or _G.FastFarm or _G.AutoBone or _G.KillBoss or _G.Tushitahop or _G.AutoAdvanceDungeon or _G.AutoDoughtBoss or _G.Auto_DungeonMobAura or _G.AutoFarmChest or _G.AutoFarmBossHallow or _G.AutoFarmSwanGlasses or _G.AutoLongSword or _G.AutoBlackSpikeycoat or _G.AutoElectricClaw or _G.AutoFarmGunMastery or _G.AutoHolyTorch or _G.AutoLawRaid or _G.AutoFarmBoss or Auto_Twin_Hooks or _G.AutoOpenSwanDoor or Auto_Dragon_Trident or _G.AutoSaber or _G.AutoFarmFruitMastery or _G.AutoFarmGunMastery or _G.TeleportIsland or _G.Auto_EvoRace or _G.Auto_kill_Canvander or _G.AutoObservationv2 or _G.AutoMusketeerHat or _G.AutoEctoplasm or _G.AutoRengoku or _G.Auto_Rainbow_Haki or _G.AutoObservation or _G.AutoDarkDagger or _G.Safe_Mode or _G.MasteryFruit or _G.AutoBudySword or _G.AutoOderSword or _G.AutoBounty or _G.AutoAllBoss or _G.Auto_Bounty or _G.AutoSharkman or _G.Auto_Mastery_Fruit or _G.Auto_Mastery_Gun or _G.Auto_Dungeon or _G.Auto_Cavender or _G.Auto_Pole or _G.Auto_Kill_Ply or _G.Auto_Factory or _G.AutoSecondSea or _G.TeleportPly or _G.AutoBartilo or _G.Auto_DarkBoss or _G.GrabChest or _G.AutoFarmBounty or _G.Holy_Torch or _G.Clip or FarmBoss or _G.AutoElitehunter or _G.AutoThirdSea or _G.Auto_Bone or _G.AutoFarmCandy or _G.AutoFactory or Pole_Farm or Auto_Serpent_Bow or Auto_Canvander or _G.YamaHop or _G.AutoSaber2 or _G.AutoFarmAllBoss or _G.SOLSecond or _G.Auto_Next_Island or _G.AutoNextIsland or _G.Auto_Farm_Ectoplasm or _G.Auto_Pole or _G.Auto_Open_Dough_Dungeon or _G.Auto_Farm_Chest or _G.Auto_Soul_Reaper or _G.Auto_Cake_Prince or _G.Auto_Saber or _G.FastFarmPlayer or Auto_Cursed_Dual_Katana or AutoFarmMaterial or Auto_Quest_Yama_1 or Auto_Quest_Yama_2 or Auto_Quest_Yama_3 or Auto_Quest_Tushita_1 or Auto_Quest_Tushita_2 or Auto_Quest_Tushita_3 or getgenv().AutoThirdSea or _G.FastFarmPlayer1 or _G.Auto_Mystic_Island or _G.Auto_kill_Empress or _G.Auto_kill_Captain or _G.Auto_kill_Captains or _G.Auto_Next_Island2 or _G.BringFruit2 or _G.AutoTideKeeper or _G.AutoSwordSword or _G.FastFarmx or getgenv().AutoBone or getgenv().cakefarm or getgenv().Ectoplasm or getgenv().FarmBoss or getgenv().FarmAllBoss or getgenv().Elitehunter  then
					setfflag("HumanoidParallelRemoveNoPhysics", "False")
					setfflag("HumanoidParallelRemoveNoPhysicsNoSimulate2", "False")
					game:GetService("Players").LocalPlayer.Character.Humanoid:ChangeState(11)
				end
			end)
		end)
		if game:GetService("ReplicatedStorage").Effect.Container:FindFirstChild("Death") then
			game:GetService("ReplicatedStorage").Effect.Container.Death:Destroy()
		end
		if game:GetService("ReplicatedStorage").Effect.Container:FindFirstChild("Respawn") then
			game:GetService("ReplicatedStorage").Effect.Container.Respawn:Destroy()
		end
		task.spawn(function() 
		_G.Type=math.random(1,5);
		while task.wait(.5) do
		_G.Type=math.random(1,5);
		end;
		end);
		local Client = game.Players.LocalPlayer
		local STOP = require(Client.PlayerScripts.CombatFramework.Particle)
		local STOPRL = require(game:GetService("ReplicatedStorage").CombatFramework.RigLib)
		spawn(function()
			while task.wait() do
				pcall(function()
					if not shared.orl then shared.orl = STOPRL.wrapAttackAnimationAsync end
					if not shared.cpc then shared.cpc = STOP.play end
						STOPRL.wrapAttackAnimationAsync = function(a,b,c,d,func)
						local Hits = STOPRL.getBladeHits(b,c,d)
						if Hits then
							if _G.AutoFarm or _G.AutoEliteHunter or _G.AutoEliteHunter_Hop or _G.Mobaura or _G.FastFarm or _G.AutoBone or _G.KillBoss or _G.Tushitahop or _G.AutoAdvanceDungeon or _G.AutoDoughtBoss or _G.Auto_DungeonMobAura or _G.AutoFarmChest or _G.AutoFarmBossHallow or _G.AutoFarmSwanGlasses or _G.AutoLongSword or _G.AutoBlackSpikeycoat or _G.AutoElectricClaw or _G.AutoFarmGunMastery or _G.AutoHolyTorch or _G.AutoLawRaid or _G.AutoFarmBoss or Auto_Twin_Hooks or _G.AutoOpenSwanDoor or Auto_Dragon_Trident or _G.AutoSaber or _G.AutoFarmFruitMastery or _G.AutoFarmGunMastery or _G.TeleportIsland or _G.Auto_EvoRace or _G.AutoFarmAllMsBypassType or _G.AutoObservationv2 or _G.AutoMusketeerHat or _G.AutoEctoplasm or _G.AutoRengoku or _G.Auto_Rainbow_Haki or _G.AutoObservation or _G.AutoDarkDagger or _G.Safe_Mode or _G.MasteryFruit or _G.AutoBudySword or _G.AutoOderSword or _G.AutoBounty or _G.AutoAllBoss or _G.Auto_Bounty or _G.AutoSharkman or _G.Auto_Mastery_Fruit or _G.Auto_Mastery_Gun or _G.Auto_Dungeon or _G.Auto_Cavender or _G.Auto_Pole or _G.Auto_Kill_Ply or _G.Auto_Factory or _G.AutoSecondSea or _G.TeleportPly or _G.AutoBartilo or _G.Auto_DarkBoss or _G.GrabChest or _G.AutoFarmBounty or _G.Holy_Torch or _G.Clip or FarmBoss or _G.AutoElitehunter or _G.AutoThirdSea or _G.Auto_Bone or _G.AutoFarmCandy or _G.AutoFactory or Pole_Farm or Auto_Serpent_Bow or Auto_Canvander or _G.YamaHop or _G.AutoSaber2 or _G.AutoFarmAllBoss or _G.SOLSecond or _G.Auto_Next_Island or _G.AutoNextIsland or _G.Auto_Farm_Ectoplasm or _G.Auto_Pole or _G.Auto_Open_Dough_Dungeon or _G.Auto_Farm_Chest or _G.Auto_Soul_Reaper or _G.Auto_Cake_Prince or _G.Auto_Saber or _G.FastFarmPlayer or getgenv().AutoThirdSea then
								STOP.play = function() end
								a:Play(0.01,0.01,0.01)
								func(Hits)
								STOP.play = shared.cpc
								wait(a.length * 0.5)
								a:Stop()
							else
								a:Play()
							end
						end
					end
				end)
			end
		end)
		----------------------------------------------------------------------------------------------------------------------------------------
		local Client = game.Players.LocalPlayer
		local STOP = require(Client.PlayerScripts.CombatFramework.Particle)
		local STOPRL = require(game:GetService("ReplicatedStorage").CombatFramework.RigLib)
		if not shared.orl then
		shared.orl = STOPRL.wrapAttackAnimationAsync
		end
		if not shared.cpc then
		shared.cpc = STOP.play 
		end
		spawn(function()
		game:GetService("RunService").Stepped:Connect(function()
			STOPRL.wrapAttackAnimationAsync = function(a,b,c,d,func)
				local Hits = STOPRL.getBladeHits(b,c,d)
				if Hits then
					if _G.RemoveAnimation and _G.VeryFast and _G.AutoFarm then
						STOP.play = function() end
						a:Play(0.01,0.01,0.01)
						func(Hits)
						STOP.play = shared.cpc
						wait(a.length * 0.5)
						a:Stop()
					else
						func(Hits)
						STOP.play = shared.cpc
						wait(a.length * 0.5)
						a:Stop()
					end
				end
			end
		end)
		end)
		local Client = game.Players.LocalPlayer
		local STOP = require(Client.PlayerScripts.CombatFramework.Particle)
		local STOPRL = require(game:GetService("ReplicatedStorage").CombatFramework.RigLib)
		if not shared.orl then
		shared.orl = STOPRL.wrapAttackAnimationAsync
		end
		if not shared.cpc then
		shared.cpc = STOP.play 
		end
		spawn(function()
		game:GetService("RunService").Stepped:Connect(function()
			STOPRL.wrapAttackAnimationAsync = function(a,b,c,d,func)
				local Hits = STOPRL.getBladeHits(b,c,d)
				if Hits then
					if _G.AutoFarm or _G.AutoEliteHunter or _G.AutoEliteHunter_Hop or _G.Mobaura or _G.FastFarm or _G.AutoBone or _G.KillBoss or _G.Tushitahop or _G.AutoAdvanceDungeon or _G.AutoDoughtBoss or _G.Auto_DungeonMobAura or _G.AutoFarmChest or _G.AutoFarmBossHallow or _G.AutoFarmSwanGlasses or _G.AutoLongSword or _G.AutoBlackSpikeycoat or _G.AutoElectricClaw or _G.AutoFarmGunMastery or _G.AutoHolyTorch or _G.AutoLawRaid or _G.AutoFarmBoss or Auto_Twin_Hooks or _G.AutoOpenSwanDoor or Auto_Dragon_Trident or _G.AutoSaber or _G.AutoFarmFruitMastery or _G.AutoFarmGunMastery or _G.TeleportIsland or _G.Auto_EvoRace or _G.AutoFarmAllMsBypassType or _G.AutoObservationv2 or _G.AutoMusketeerHat or _G.AutoEctoplasm or _G.AutoRengoku or _G.Auto_Rainbow_Haki or _G.AutoObservation or _G.AutoDarkDagger or _G.Safe_Mode or _G.MasteryFruit or _G.AutoBudySword or _G.AutoOderSword or _G.AutoBounty or _G.AutoAllBoss or _G.Auto_Bounty or _G.AutoSharkman or _G.Auto_Mastery_Fruit or _G.Auto_Mastery_Gun or _G.Auto_Dungeon or _G.Auto_Cavender or _G.Auto_Pole or _G.Auto_Kill_Ply or _G.Auto_Factory or _G.AutoSecondSea or _G.TeleportPly or _G.AutoBartilo or _G.Auto_DarkBoss or _G.GrabChest or _G.AutoFarmBounty or _G.Holy_Torch or _G.Clip or FarmBoss or _G.AutoElitehunter or _G.AutoThirdSea or _G.Auto_Bone or _G.AutoFarmCandy or _G.AutoFactory or Pole_Farm or Auto_Serpent_Bow or Auto_Canvander or _G.YamaHop or _G.AutoSaber2 or _G.AutoFarmAllBoss or _G.SOLSecond or _G.Auto_Next_Island or _G.AutoNextIsland or _G.Auto_Farm_Ectoplasm or _G.Auto_Pole or _G.Auto_Open_Dough_Dungeon or _G.Auto_Farm_Chest or _G.Auto_Soul_Reaper or _G.Auto_Cake_Prince or _G.Auto_Saber or _G.FastFarmPlayer or Auto_Quest_Yama_1 or Auto_Quest_Yama_2 or Auto_Quest_Yama_3 or Auto_Quest_Tushita_1 or Auto_Quest_Tushita_2 or Auto_Quest_Tushita_3 then
						STOP.play = function() end
						a:Play(0.01,0.01,0.01)
						func(Hits)
						STOP.play = shared.cpc
						wait(a.length * 0.5)
						a:Stop()
					else
						func(Hits)
						STOP.play = shared.cpc
						wait(a.length * 0.5)
						a:Stop()
					end
				end
			end
		end)
		end)
		
		
		spawn(function()
			while wait() do
				pcall(function()
					if _G.SOLSecond then
						EquipWeapon("Key")
					end
				end)
			end
		end)
		

		
		
		spawn(function()
			pcall(function()
				while wait() do
					if getgenv().RandomBone then    
						game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Bones","Buy",1,1)
					end
				end
			end)
		end)
		
		
		spawn(function()
			while task.wait() do
				pcall(function()
					if _G.AutoFarm then
	
					end
				end)
			end
		end)
		spawn(function()
			while task.wait() do
				pcall(function()
					if getgenv().AutoThirdSea then
						EquipWeapon(_G.SelectWeapon)
					end
				end)
			end
		end)
		spawn(function()
			while wait(.2) do
				if _G.SOLSecond then
					if Mix_Farm == nil or Auto_New_Farm then
						local Lv = game:GetService("Players").LocalPlayer.Data.Level.Value
						local Beli = game:GetService("Players").LocalPlayer.Data.Beli.Value
						local FG = game:GetService("Players").LocalPlayer.Data.Fragments.Value
						if Lv >= 700 then
							Aura_SOL = true
							Auto_FPS = true
							if game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("DressrosaQuestProgress","Detective") == 1 then
							else
								game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("DressrosaQuestProgress","Detective")
								wait(1)
								EquipWeapon("Key")
							end 
							repeat wait()
								getgenv().ToTarget(CFrame.new(1347.32947, 37.349369, -1325.44922, 0.538348913, 8.57539106e-08, 0.842722058, 8.61935634e-10, 1, -1.0230886e-07, -0.842722058, 5.58042359e-08, 0.538348913))
							until (Vector3.new(1347.32947, 37.349369, -1325.44922)-game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude < 1 or _G.SOLSecond == false
							wait(2)
							for i,v in pairs(game.workspace.Enemies:GetChildren()) do
								if v.Name == "Ice Admiral [Lv. 700] [Boss]" then
									game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
										EquipWeapon(_G.SelectWeapon)    
										v.Humanoid.JumpPower = 0
										v.Humanoid.WalkSpeed = 0
										v.HumanoidRootPart.Size = Vector3.new(50,50,50)
										getgenv().ToTarget(v.HumanoidRootPart.CFrame*CFrame.new(0,30,30))
										_G.FastAttackF2 = true    
									wait(13)
									game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("TravelDressrosa")
									_G.FastAttackF2 = false
									wait(25)
									game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("TravelDressrosa")
								end
							end
						end
					end
				end
			end
		end)
		getgenv().AutoThirdSea = false
                
		spawn(function()
			pcall(function()
				while wait() do
					if getgenv().AutoThirdSea then
						if game:GetService("Players").LocalPlayer.Data.Level.Value >= 1500 and World2 then
							_G.AutoFarm = false
							if game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("ZQuestProgress").KilledIndraBoss == false then
								if game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BartiloQuestProgress","Bartilo") == 3 then
									if game:GetService("Players").LocalPlayer.Data.SpawnPoint.Value == "Bar" then
										if game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("TalkTrevor","1") == 0 then
											if game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("ZQuestProgress","Check") == 0 then
												if (CFrame.new(-1926.3221435547, 12.819851875305, 1738.3092041016).Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 10 then
													wait(1.1)
													Click()
													game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("ZQuestProgress","Begin")
												else
													topos(CFrame.new(-1926.3221435547, 12.819851875305, 1738.3092041016))
												end
												if game:GetService("Workspace").Enemies:FindFirstChild("rip_indra [Lv. 1500] [Boss]") then
													for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
														if v.Name == "rip_indra [Lv. 1500] [Boss]" then
															repeat game:GetService("RunService").Heartbeat:wait()
																Click()
																pcall(function()
																	Click()
																	topos(v.HumanoidRootPart.CFrame * CFrame.new(0,25,0))
																	require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework).activeController.hitboxMagnitude = 1000
																	game:GetService'VirtualUser':CaptureController()
																	game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
																	game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("TravelZou")
																	sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius", math.huge)
																end)
															until getgenv().AutoThirdSea == false or v.Humanoid.Health <= 0 or not v.Parent
														end
													end
												elseif not game:GetService("Workspace").Enemies:FindFirstChild("rip_indra [Lv. 1500] [Boss]") and (CFrame.new(-26880.93359375, 22.848554611206, 473.18951416016).Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 1000 then
													topos(CFrame.new(-26880.93359375, 22.848554611206, 473.18951416016))
												end
											elseif game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("ZQuestProgress","Check") ~= 0 then
												if game:GetService("Workspace").Enemies:FindFirstChild("Don Swan [Lv. 1000] [Boss]") or game:GetService("ReplicatedStorage"):FindFirstChild("Don Swan [Lv. 1000] [Boss]") then
													if game:GetService("Workspace").Enemies:FindFirstChild("Don Swan [Lv. 1000] [Boss]") then
														for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
															if v.Name == "Don Swan [Lv. 1000] [Boss]" then
																repeat game:GetService("RunService").Heartbeat:wait()
																	pcall(function()
																		 Click()
																		topos(v.HumanoidRootPart.CFrame * CFrame.new(0,25,0))
																		require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework).activeController.hitboxMagnitude = 1000
																		game:GetService'VirtualUser':CaptureController()
																		game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
																		sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius", math.huge)
																	end)
																until getgenv().AutoThirdSea == false or v.Humanoid.Health <= 0 or not v.Parent
															end
														end
													else
														if (CFrame.new(2284.912109375, 15.537666320801, 905.48291015625).Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 1000 then
															game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(2284.912109375, 15.537666320801, 905.48291015625))
															wait()
														end
														topos(CFrame.new(2284.912109375, 15.537666320801, 905.48291015625))
													end
												elseif getgenv().AutoThirdSea and not game:GetService("Workspace").Enemies:FindFirstChild("Don Swan [Lv. 1000] [Boss]") and not game:GetService("ReplicatedStorage"):FindFirstChild("Don Swan [Lv. 1000] [Boss]") then
													Hop()
												elseif not getgenv().AutoThirdSea and not game:GetService("Workspace").Enemies:FindFirstChild("Don Swan [Lv. 1000] [Boss]") and not game:GetService("ReplicatedStorage"):FindFirstChild("Don Swan [Lv. 1000] [Boss]") then
													if (CFrame.new(2284.912109375, 15.537666320801, 905.48291015625).Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 1000 then
														game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(2284.912109375, 15.537666320801, 905.48291015625))
														wait()
													end
													topos(CFrame.new(2284.912109375, 15.537666320801, 905.48291015625))
												end
											end
										elseif game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("TalkTrevor","1") ~= 0 then
											for i,v in pairs(game:GetService("Workspace"):GetChildren()) do
												if string.find(v.Name, "Fruit") then
													if v:IsA("Tool") then
														if (v.Handle.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 20000 then
															v.Handle.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
														end
													end
												end
											end
											if game.Players.LocalPlayer.Backpack:FindFirstChild("Quake Fruit") or game.Players.LocalPlayer.Backpack:FindFirstChild("Human: Buddha Fruit") or game.Players.LocalPlayer.Backpack:FindFirstChild("String Fruit") or game.Players.LocalPlayer.Backpack:FindFirstChild("Bird: Phoenix Fruit") or game.Players.LocalPlayer.Backpack:FindFirstChild("Rumble Fruit") or game.Players.LocalPlayer.Backpack:FindFirstChild("Paw Fruit") or game.Players.LocalPlayer.Backpack:FindFirstChild("Gravity Fruit") or game.Players.LocalPlayer.Backpack:FindFirstChild("Dough Fruit") or game.Players.LocalPlayer.Backpack:FindFirstChild("Shadow Fruit") or game.Players.LocalPlayer.Backpack:FindFirstChild("Venom Fruit") or game.Players.LocalPlayer.Backpack:FindFirstChild("Control Fruit") or game.Players.LocalPlayer.Backpack:FindFirstChild("Dragon Fruit") or game.Players.LocalPlayer.Character:FindFirstChild("Quake Fruit") or game.Players.LocalPlayer.Character:FindFirstChild("Human: Buddha Fruit") or game.Players.LocalPlayer.Character:FindFirstChild("String Fruit") or game.Players.LocalPlayer.Character:FindFirstChild("Bird: Phoenix Fruit") or game.Players.LocalPlayer.Character:FindFirstChild("Rumble Fruit") or game.Players.LocalPlayer.Character:FindFirstChild("Paw Fruit") or game.Players.LocalPlayer.Character:FindFirstChild("Gravity Fruit") or game.Players.LocalPlayer.Character:FindFirstChild("Dough Fruit") or game.Players.LocalPlayer.Character:FindFirstChild("Shadow Fruit") or game.Players.LocalPlayer.Character:FindFirstChild("Venom Fruit") or game.Players.LocalPlayer.Character:FindFirstChild("Control Fruit") or game.Players.LocalPlayer.Character:FindFirstChild("Dragon Fruit") then
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("TalkTrevor","1")
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("TalkTrevor","2")
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("TalkTrevor","3")
											end
										end
									else
										topos(CFrame.new(-379.70889282227, 73.0458984375, 304.84692382813))
										game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
									end
								else
									if game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BartiloQuestProgress","Bartilo") == 0 then
										if string.find(game.Players.LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text, "Swan Pirates") and string.find(game.Players.LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text, "50") and game.Players.LocalPlayer.PlayerGui.Main.Quest.Visible == true then
											if game.Workspace.Enemies:FindFirstChild("Swan Pirate [Lv. 775]") then
												for i,v in pairs(game.Workspace.Enemies:GetChildren()) do
													if v.Name == "Swan Pirate [Lv. 775]" then
														PosMonBarto =  v.HumanoidRootPart.CFrame
														pcall(function()
															repeat wait()
																for k,x in pairs(game.Workspace.Enemies:GetChildren()) do
																	if x.Name ==  "Swan Pirate [Lv. 775]"  then
																		x.HumanoidRootPart.Size = Vector3.new(5,5,5)
																		x.HumanoidRootPart.Transparency = 1
																		x.HumanoidRootPart.CanCollide = false
																		x.HumanoidRootPart.CFrame = PosMonBarto
																		sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius", math.huge)
																	end
																end
								Click()
																v.HumanoidRootPart.CanCollide = false
																v.HumanoidRootPart.Size = Vector3.new(5, 5, 5)
																topos( v.HumanoidRootPart.CFrame * CFrame.new(0,25,0))
																game:GetService'VirtualUser':CaptureController()
																game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))                           
															until not v.Parent or v.Humanoid.Health <= 0 or game.Players.LocalPlayer.PlayerGui.Main.Quest.Visible == false
														end)
													end
												end
											else
												topos(CFrame.new(1057.92761, 137.614319, 1242.08069))
											end
										else
											topos(CFrame.new(-456.28952, 73.0200958, 299.895966))
											wait(1.1)
											game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StartQuest","BartiloQuest",1)
										end
									elseif game.Players.LocalPlayer.Data.Level.Value >= 800 and game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BartiloQuestProgress","Bartilo") == 1 then
										if game.Workspace.Enemies:FindFirstChild("Jeremy [Lv. 850] [Boss]") then
											Ms = "Jeremy [Lv. 850] [Boss]"
											for i,v in pairs(game.Workspace.Enemies:GetChildren()) do
												if v.Name == Ms then
													repeat wait()
														Click()
														v.HumanoidRootPart.CanCollide = false
														v.HumanoidRootPart.Size = Vector3.new(35, 35, 35)
														topos(v.HumanoidRootPart.CFrame * CFrame.new(0,25,0))
														game:GetService'VirtualUser':CaptureController()
														game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
													until not v.Parent or v.Humanoid.Health <= 0
												end
											end
										elseif game.ReplicatedStorage:FindFirstChild("Jeremy [Lv. 850] [Boss]") then
											topos(CFrame.new(-456.28952, 73.0200958, 299.895966))
											wait(1.1)
											game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BartiloQuestProgress","Bartilo")
											wait(1)
											topos(CFrame.new(2099.88159, 448.931, 648.997375))
											wait(2)
										else
											topos(CFrame.new(2099.88159, 448.931, 648.997375))
										end
										wait(15)
										if not game.Workspace.Enemies:FindFirstChild("Jeremy [Lv. 850] [Boss]") then
											Hop()
										end
									elseif game.Players.LocalPlayer.Data.Level.Value >= 800 and game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BartiloQuestProgress","Bartilo") == 2 then
										topos(CFrame.new(-1850.49329, 13.1789551, 1750.89685))
										wait(1.5)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1858.87305, 19.3777466, 1712.01807)
										wait(1.5)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1803.94324, 16.5789185, 1750.89685)
										wait(1.5)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1858.55835, 16.8604317, 1724.79541)
										wait(1.5)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1869.54224, 15.987854, 1681.00659)
										wait(1.5)                                                                  
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1800.0979, 16.4978027, 1684.52368) 
										wait(1.5)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1819.26343, 15.795166, 1717.90625)
										wait(1.5)
										game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1813.51843, 15.8604736, 1724.79541)
										wait(1.5)
									end
								end
							else
								game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("TravelZou")
							end
						end
					end
				end
			end)
		end)
		spawn(function()
			pcall(function()
				while wait(.1) do wait(5)
					if getgenv().AutoThirdSea and World2 and game:GetService("Players").LocalPlayer.Data.Level.Value >= 1500 then
						if game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BartiloQuestProgress","Bartilo") == 3 then
							if game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("TalkTrevor","1") ~= 0 then
								if not game.Players.LocalPlayer.Backpack:FindFirstChild("Quake Fruit") and not game.Players.LocalPlayer.Backpack:FindFirstChild("Human: Buddha Fruit") and not game.Players.LocalPlayer.Backpack:FindFirstChild("String Fruit") and not game.Players.LocalPlayer.Backpack:FindFirstChild("Bird: Phoenix Fruit") and not game.Players.LocalPlayer.Backpack:FindFirstChild("Rumble Fruit") and not game.Players.LocalPlayer.Backpack:FindFirstChild("Paw Fruit") and not game.Players.LocalPlayer.Backpack:FindFirstChild("Gravity Fruit") and not game.Players.LocalPlayer.Backpack:FindFirstChild("Dough Fruit") and not game.Players.LocalPlayer.Backpack:FindFirstChild("Shadow Fruit") and not game.Players.LocalPlayer.Backpack:FindFirstChild("Venom Fruit") and not game.Players.LocalPlayer.Backpack:FindFirstChild("Control Fruit") and not game.Players.LocalPlayer.Backpack:FindFirstChild("Dragon Fruit") and not game.Players.LocalPlayer.Character:FindFirstChild("Quake Fruit") and not game.Players.LocalPlayer.Character:FindFirstChild("Human: Buddha Fruit") and not game.Players.LocalPlayer.Character:FindFirstChild("String Fruit") and not game.Players.LocalPlayer.Character:FindFirstChild("Bird: Phoenix Fruit") and not game.Players.LocalPlayer.Character:FindFirstChild("Rumble Fruit") and not game.Players.LocalPlayer.Character:FindFirstChild("Paw Fruit") and not game.Players.LocalPlayer.Character:FindFirstChild("Gravity Fruit") and not game.Players.LocalPlayer.Character:FindFirstChild("Dough Fruit") and not game.Players.LocalPlayer.Character:FindFirstChild("Shadow Fruit") and not game.Players.LocalPlayer.Character:FindFirstChild("Venom Fruit") and not game.Players.LocalPlayer.Character:FindFirstChild("Control Fruit") and not game.Players.LocalPlayer.Character:FindFirstChild("Dragon Fruit") then
									Hop()
								end
							end
						end
					end
				end
			end)
		end)
		require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework.Particle.SlashHit).playAt = function() return nil end;
    getgenv().A = require(game:GetService("ReplicatedStorage").CombatFramework.RigLib).wrapAttackAnimationAsync 
    getgenv().B = require(game.Players.LocalPlayer.PlayerScripts.CombatFramework.Particle).play
    spawn(function()
        while wait() do
            if _G.AutoFarm or _G.AutoEliteHunter or _G.AutoEliteHunter_Hop or _G.Mobaura or _G.FastFarm or _G.AutoBone or _G.KillBoss or _G.Tushitahop or _G.AutoAdvanceDungeon or _G.AutoDoughtBoss or _G.Auto_DungeonMobAura or _G.AutoFarmChest or _G.AutoFarmBossHallow or _G.AutoFarmSwanGlasses or _G.AutoLongSword or _G.AutoBlackSpikeycoat or _G.AutoElectricClaw or _G.AutoFarmGunMastery or _G.AutoHolyTorch or _G.AutoLawRaid or _G.AutoFarmBoss or Auto_Twin_Hooks or _G.AutoOpenSwanDoor or Auto_Dragon_Trident or _G.AutoSaber or _G.AutoFarmFruitMastery or _G.AutoFarmGunMastery or _G.TeleportIsland or _G.Auto_EvoRace or _G.AutoFarmAllMsBypassType or _G.AutoObservationv2 or _G.AutoMusketeerHat or _G.AutoEctoplasm or _G.AutoRengoku or _G.Auto_Rainbow_Haki or _G.AutoObservation or _G.AutoDarkDagger or _G.Safe_Mode or _G.MasteryFruit or _G.AutoBudySword or _G.AutoOderSword or _G.AutoBounty or _G.AutoAllBoss or _G.Auto_Bounty or _G.AutoSharkman or _G.Auto_Mastery_Fruit or _G.Auto_Mastery_Gun or _G.Auto_Dungeon or _G.Auto_Cavender or _G.Auto_Pole or _G.Auto_Kill_Ply or _G.Auto_Factory or _G.AutoSecondSea or _G.TeleportPly or _G.AutoBartilo or _G.Auto_DarkBoss or _G.GrabChest or _G.AutoFarmBounty or _G.Holy_Torch or _G.Clip or FarmBoss or _G.AutoElitehunter or _G.AutoThirdSea or _G.Auto_Bone or _G.AutoFarmCandy or _G.AutoFactory or Pole_Farm or Auto_Serpent_Bow or Auto_Canvander or _G.YamaHop or _G.AutoSaber2 or _G.AutoFarmAllBoss or _G.SOLSecond or _G.Auto_Next_Island or _G.AutoNextIsland or _G.Auto_Farm_Ectoplasm or _G.Auto_Pole or _G.Auto_Open_Dough_Dungeon or _G.Auto_Farm_Chest or _G.Auto_Soul_Reaper or _G.Auto_Cake_Prince or _G.Auto_Saber or _G.FastFarmPlayer then
                pcall(function()
                    require(game:GetService("ReplicatedStorage").CombatFramework.RigLib).wrapAttackAnimationAsync =function(a1,a2,a3,a4,a5)
                        local GetBladeHits = require(game:GetService("ReplicatedStorage").CombatFramework.RigLib).getBladeHits(a2,a3,a4)
                        if GetBladeHits then
                            require(game:GetService("ReplicatedStorage").CombatFramework.RigLib).play = function() end;
                            a1:Play(0.1, 0.1, 0.1);
                            a5(GetBladeHits);
                            require(game:GetService("ReplicatedStorage").CombatFramework.RigLib).play = getgenv().B 
                            wait(.5);
                            a1:Stop();
                        end;
                    end;
                end);
            end
        end;
    end);
    require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework.Particle.SlashHit).playAt = function() return nil end;
    getgenv().A = require(game:GetService("ReplicatedStorage").CombatFramework.RigLib).wrapAttackAnimationAsync 
    getgenv().B = require(game.Players.LocalPlayer.PlayerScripts.CombatFramework.Particle).play
    spawn(function()
        while wait() do
            if _G.AutoFarm or _G.Fast_Attack_Normal3 or _G.Auto_Cake_Prince or _G.AutoElitehunter or Auto_Canvander or Auto_Dragon_Trident or Auto_Serpent_Bow or Auto_Twin_Hooks or _G.Auto_Saber or _G.Auto_Soul_Reaper then
                pcall(function()
                    require(game:GetService("ReplicatedStorage").CombatFramework.RigLib).wrapAttackAnimationAsync =function(a1,a2,a3,a4,a5)
                        local GetBladeHits = require(game:GetService("ReplicatedStorage").CombatFramework.RigLib).getBladeHits(a2,a3,a4)
                        if GetBladeHits then
                            require(game:GetService("ReplicatedStorage").CombatFramework.RigLib).play = function() end;
                            a1:Play(0.1, 0.1, 0.1);
                            a5(GetBladeHits);
                            require(game:GetService("ReplicatedStorage").CombatFramework.RigLib).play = getgenv().B 
                            wait(.5);
                            a1:Stop();
                        end;
                    end;
                end);
            end
        end;
    end);
    AttackRandomType = 1
	spawn(function()
		while task.wait(0.25) do
			if _G.Fast_Attack then
				pcall(function()
					local AC = CbFw2.activeController
					for i = 1,1 do 
						local bladehit = require(game.ReplicatedStorage.CombatFramework.RigLib).getBladeHits(
							plr.Character,
							{plr.Character.HumanoidRootPart},
							45
						)
						local cac = {}
						local hash = {}
						for k, v in pairs(bladehit) do
							if v.Parent:FindFirstChild("HumanoidRootPart") and not hash[v.Parent] then
								table.insert(cac, v.Parent.HumanoidRootPart)
								hash[v.Parent] = true
							end
						end
						bladehit = cac
						if #bladehit > 0 then
							local u8 = debug.getupvalue(AC.attack, 5)
							local u9 = debug.getupvalue(AC.attack, 6)
							local u7 = debug.getupvalue(AC.attack, 4)
							local u10 = debug.getupvalue(AC.attack, 7)
							local u12 = (u8 * 798405 + u7 * 727595) % u9
							local u13 = u7 * 798405
							(function()
								u12 = (u12 * u9 + u13) % 1099511627776
								u8 = math.floor(u12 / u9)
								u7 = u12 - u8 * u9
							end)()
							u10 = u10 + 1
							debug.setupvalue(AC.attack, 5, u8)
							debug.setupvalue(AC.attack, 6, u9)
							debug.setupvalue(AC.attack, 4, u7)
							debug.setupvalue(AC.attack, 7, u10)
							if plr.Character:FindFirstChildOfClass("Tool") and AC.blades and AC.blades[1] then 
								game:GetService("ReplicatedStorage").RigControllerEvent:FireServer("weaponChange",tostring(GetCurrentBlade()))
								game.ReplicatedStorage.Remotes.Validator:FireServer(math.floor(u12 / 1099511627776 * 16777215), u10)
								game:GetService("ReplicatedStorage").RigControllerEvent:FireServer("hit", bladehit, i, "") 
							end
						end
					end
				end)
			end
		end
	end)
task.spawn(function()
	while wait() do 
		AttackRandomType = math.random(1,5)
		wait(0.3)
	end
end)

    spawn(function()
        while task.wait() do
            if _G.AutoFarm then
                pcall(function()
                    local MyLevel = game:GetService("Players").LocalPlayer.Data.Level.Value
                if game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == false then
                    MagnetActive = false;
                        CheckQuest();
                        topos(CFrameQuest);
                        if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - CFrameQuest.Position).Magnitude <= 20 then
                            CheckQuest();
                            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuest
                            task.wait();
                            game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StartQuest", NaemQuest, LevelQuest);
                            game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint");
                    end;
                elseif game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == true then
                    pcall(function()
                        CheckQuest();
                        if game:GetService("Workspace").Enemies:FindFirstChild(Ms) then
                            for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                                if v.Name == Ms and v:FindFirstChild("Humanoid") then
                                    if v.Humanoid.Health > 0 then
                                        repeat task.wait()
                                            if game:GetService("Workspace").Enemies:FindFirstChild(Ms) then
                                                if string.find(game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text, NameMon) then
                                                    if not game.Players.LocalPlayer.Character:FindFirstChild("HasBuso") then
                                                    local args = {
                                                        [1] = "Buso"
                                                    }
                                                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args));
                                                    end;
                                                    EquipWeapon(_G.SelectWeapon)
                                                    topos(v.HumanoidRootPart.CFrame*CFrame.new(0,40,0))
                                                    if game.Players.LocalPlayer.Character:FindFirstChild("Black Leg") and game.Players.LocalPlayer.Character:FindFirstChild("Black Leg").Level.Value >= 150 then
                                                        game:service('VirtualInputManager'):SendKeyEvent(true, "V", false, game)
                                                        game:service('VirtualInputManager'):SendKeyEvent(false, "V", false, game)
                                                    end
                                                    v.HumanoidRootPart.CanCollide = false;
                                                    PosMon = v.HumanoidRootPart.CFrame
                                                    v.Humanoid:ChangeState(14);
                                                    MagnetActive = true;
                                                   _G.Fast_Attack = true;                                 
                                                else
                                                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AbandonQuest");
                                                end;
                                            else
                                                MagnetActive = false;
                                                CheckQuest();
                                                topos(CFrameMon);
                                            end
                                        until not v.Parent or v.Humanoid.Health <= 0 or _G.AutoFarm == false or game.Players.LocalPlayer.PlayerGui.Main.Quest.Visible == false or not game:GetService("Workspace").Enemies:FindFirstChild(v.Name)
										MagnetActive = false;
										_G.Fast_Attack = false
                                    end;
                                end;
                            end;
                        else
    MagnetActive = false;
    _G.Fast_Attack = false;
                            CheckQuest();
                            topos(CFrameMon);
                        end;
                    end);
                end;
                end);
            end;
        end;
    end);

    function Click()
        game:GetService'VirtualUser':CaptureController()
        game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
    end
	
  
    CFrameFast = CFrame.new(-4718.82373, 854.679321, -1942.53796, 0.892800689, -1.42452192e-08, 0.45045197, 6.08748163e-09, 1, 1.95588257e-08, -0.45045197, -1.47200145e-08, 0.892800689)

    spawn(function()
        while task.wait() do
            if _G.FastFarm then
                if MyLevel >= 15 and MyLevel <= 70 and _G.FastFarm then
                    pcall(function()
                    _G.AutoFarm = false
                    local MyLevel = game:GetService("Players").LocalPlayer.Data.Level.Value
                    if game:GetService("Workspace").Enemies:FindFirstChild("God's Guard [Lv. 450]") then
                        for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                            if v.Name == "God's Guard [Lv. 450]" then
                                if v.Humanoid.Health > 0 then
                                    repeat task.wait()
                                        if not game.Players.LocalPlayer.Character:FindFirstChild("HasBuso") then
                                        local args = {
                                            [1] = "Buso"
                                        }
                                        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
                                        end
                                        EquipWeapon(_G.SelectWeapon)
                                        if AttackRandomType == 1 then
                                            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0, 20, 0)
                                        elseif AttackRandomType == 2 then
                                            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0, 20, 10)
                                        elseif AttackRandomType == 3 then
                                            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0, 20, -10)
                                        elseif AttackRandomType == 4 then
                                            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(10, 20, 0)
                                        elseif AttackRandomType == 5 then
                                            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(-10, 20, 0)
                                        else
                                            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0, 20, 0)
                                        end

                                            v.HumanoidRootPart.CanCollide = false;
                                            v.HumanoidRootPart.Size = Vector3.new(160, 160, 160);
                                            a = v.HumanoidRootPart.CFrame
                                            v.Humanoid.JumpPower = 0;
                                            v.Humanoid.WalkSpeed = 0;
                                            v.HumanoidRootPart.CanCollide = false
                                            if v.Humanoid:FindFirstChild("Animator") then
                                                v.Humanoid.Animator:Destroy();
                                            end;
    _G.Fast_Attack_Normal = true
                                            v.Humanoid:ChangeState(14);
                                    until _G.FastFarm == false or not v.Parent or v.Humanoid.Health <= 0
                                else
                                    topos(CFrameFast)
                                end
                            end
                        end
                    else
                        if (CFrameFast.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 3000 then
                            game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(-4607.8227539063, 872.54248046875, -1667.5568847656))
                        end
                        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
                        topos(CFrameFast)
                    end
                    end)
                end
            end
        end
    end)

		spawn(function()
			while task.wait() do
				pcall(function()
					if _G.Auto_Cake_Prince then
						EquipWeapon(_G.SelectWeapon)
					end
				end)
			end
		end)
    task.spawn(function()
        while task.wait() do
            pcall(function()
                if _G.FastFarmx then
                    for i, v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                        if v.Name == "God's Guard [Lv. 450]" and (v.HumanoidRootPart.Position - a.Position).Magnitude <= 300 then
                                v.HumanoidRootPart.CFrame = a
                                v.HumanoidRootPart.Size = Vector3.new(50,50,50)
                                v.HumanoidRootPart.CanCollide = false
                                v.Humanoid.WalkSpeed = 0
                                v.Humanoid.JumpPower = 0
                                v.Humanoid:ChangeState(14)
                                if v.Humanoid:FindFirstChild("Animator") then
                                   v.Humanoid.Animator:Destroy()
                                end
                                sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius", math.huge)
                        end
                    end
                end
            end)
        end
    end)
	
-- [CheckMastery]

function CheckMasteryWeapon(NameWe,MasNum)
	if game.Players.LocalPlayer.Backpack:FindFirstChild(NameWe) then
		if tonumber(game.Players.LocalPlayer.Backpack:FindFirstChild(NameWe).Level.Value) < tonumber(MasNum) then
			return "true DownTo"
		elseif tonumber(game.Players.LocalPlayer.Backpack:FindFirstChild(NameWe).Level.Value) >= tonumber(MasNum) then
			return "true UpTo"
		end
	end
	if game.Players.LocalPlayer.Character:FindFirstChild(NameWe) then
		if tonumber(game.Players.LocalPlayer.Character:FindFirstChild(NameWe).Level.Value) < tonumber(MasNum) then
			return "true DownTo"
		elseif tonumber(game.Players.LocalPlayer.Character:FindFirstChild(NameWe).Level.Value) >= tonumber(MasNum) then
			return "true UpTo"
		end
	end
	return "else"
end

--[GetWeaponInventory]

function GetWeaponInventory(Weaponname)
	for i,v in pairs(game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("getInventory")) do
		if type(v) == "table" then
			if v.Type == "Sword" then
				if v.Name == Weaponname then
					return true
				end
			end
		end
	end
	return false
end
task.spawn(function()
	while true do wait()
		if setscriptable then
			setscriptable(game.Players.LocalPlayer, "SimulationRadius", true)
		end
		if sethiddenproperty then
			sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius", math.huge)
		end
	end
end)

	local plr = game.Players.LocalPlayer
    local CbFw = getupvalues(require(plr.PlayerScripts.CombatFramework))
    local CbFw2 = CbFw[2]

    function GetCurrentBlade() 
        local p13 = CbFw2.activeController
        local ret = p13.blades[1]
        if not ret then return end
        while ret.Parent~=game.Players.LocalPlayer.Character do ret=ret.Parent end
        return ret
    end 

    
    function AttackFarm()
        if not fuck then
            if not Auto_Raid then
                local AC = CbFw2.activeController
                for i = 1, 1 do 
                    local bladehit = require(game.ReplicatedStorage.CombatFramework.RigLib).getBladeHits(
                        plr.Character,
                        {plr.Character.HumanoidRootPart},
                        0
                    )
                    local cac = {}
                    local hash = {}
                    for k, v in pairs(bladehit) do
                        if v.Parent:FindFirstChild("HumanoidRootPart") and not hash[v.Parent] then
                            table.insert(cac, v.Parent.HumanoidRootPart)
                            hash[v.Parent] = true
                        end
                    end
                    bladehit = cac
                    if #bladehit > 0 then
                        local u8 = debug.getupvalue(AC.attack, 5)
                        local u9 = debug.getupvalue(AC.attack, 6)
                        local u7 = debug.getupvalue(AC.attack, 4)
                        local u10 = debug.getupvalue(AC.attack, 7)
                        local u12 = (u8 * 798405 + u7 * 727595) % u9
                        local u13 = u7 * 798405
                        (function()
                            u12 = (u12 * u9 + u13) % 1099511627776
                            u8 = math.floor(u12 / u9)
                            u7 = u12 - u8 * u9
                        end)()
                        u10 = u10 + 1
                        debug.setupvalue(AC.attack, 5, u8)
                        debug.setupvalue(AC.attack, 6, u9)
                        debug.setupvalue(AC.attack, 4, u7)
                        debug.setupvalue(AC.attack, 7, u10)
                        pcall(function()
                            if plr.Character:FindFirstChildOfClass("Tool") and AC.blades and AC.blades[1] then
                                AC.animator.anims.basic[1]:Play(0.01,0.01,0.01)
                                game:GetService("ReplicatedStorage").RigControllerEvent:FireServer("weaponChange",tostring(GetCurrentBlade()))
                                game.ReplicatedStorage.Remotes.Validator:FireServer(math.floor(u12 / 1099511627776 * 16777215), u10)
                                game:GetService("ReplicatedStorage").RigControllerEvent:FireServer("hit", bladehit, i, "")
                            end
                        end)
                    end
                end
            end
        end
        if _G.FastFarmPlayer15 then
            local Fast = getupvalues(require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework))
            local Lop = Fast[2]
            Lop.activeController.timeToNextAttack = (-math.huge^math.huge*math.huge)
            Lop.activeController.attacking = false
            Lop.activeController.timeToNextBlock = 0
            Lop.activeController.humanoid.AutoRotate = 80
            Lop.activeController.increment = 3
            Lop.activeController.blocking = false
            Lop.activeController.hitboxMagnitude = 150
        end
    end
	_G.ColorMethod = Color3.fromRGB(191, 121, 195)

	local UiLib =  game:GetService("CoreGui").RobloxGui.Modules:FindFirstChild("By _BEAMxHACK_.#4444") 
	if UiLib then 
		UiLib:Destroy()
		print("Ui Destroy.")
	end
	
		local UserInputService = game:GetService("UserInputService")
		local TweenService = game:GetService("TweenService")
		local RunService = game:GetService("RunService")
		local LocalPlayer = game:GetService("Players").LocalPlayer
		local Mouse = LocalPlayer:GetMouse()
		local tween = game:GetService("TweenService")
		local Red = {RainbowColorValue = 0, HueSelectionPosition = 0}
		local PresetColor = Color3.fromRGB(0, 190, 255)
	
	
		coroutine.wrap(
			function()
				while wait() do
					Red.RainbowColorValue = Red.RainbowColorValue + 1 / 255
					Red.HueSelectionPosition = Red.HueSelectionPosition + 1
	
					if Red.RainbowColorValue >= 1 then
						Red.RainbowColorValue = 0
					end
	
					if Red.HueSelectionPosition == 160 then
						Red.HueSelectionPosition = 0
					end
				end
			end
		)()
	
		local Reduisceen = Instance.new("ScreenGui")
		Reduisceen.Parent = game:GetService("CoreGui").RobloxGui.Modules
		Reduisceen.Name = "By _BEAMxHACK_ #4444"
		Reduisceen.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
	
		local function MakeDraggable(topbarobject, object)
			local Dragging = nil
			local DragInput = nil
			local DragStart = nil
			local StartPosition = nil
	
			local function Update(input)
				local Delta = input.Position - DragStart
				local pos =
					UDim2.new(
					StartPosition.X.Scale,
					StartPosition.X.Offset + Delta.X,
					StartPosition.Y.Scale,
					StartPosition.Y.Offset + Delta.Y
				)
				local Tween = TweenService:Create(object, TweenInfo.new(0.2), {Position = pos})
				Tween:Play()
			end
	
			topbarobject.InputBegan:Connect(
				function(input)
					if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
						Dragging = true
						DragStart = input.Position
						StartPosition = object.Position
	
						input.Changed:Connect(
							function()
								if input.UserInputState == Enum.UserInputState.End then
									Dragging = false
								end
							end
						)
					end
				end
			)
	
			topbarobject.InputChanged:Connect(
				function(input)
					if
						input.UserInputType == Enum.UserInputType.MouseMovement or
							input.UserInputType == Enum.UserInputType.Touch
					then
						DragInput = input
					end
				end
			)
	
			UserInputService.InputChanged:Connect(
				function(input)
					if input == DragInput and Dragging then
						Update(input)
					end
				end
			)
		end
	
		local function Tween(instance, properties,style,wa)
			if style == nil or "" then
				return Back
			end
			tween:Create(instance,TweenInfo.new(wa,Enum.EasingStyle[style]),{properties}):Play()
		end
	
		local create = {}
		function create.win()
			if logoid == nil or logoid == "" then
				logoid = "13192570418"
			end
			local fs = false
	
			local MainSceen = Instance.new("Frame")
			MainSceen.Name = "MainSceen"
			MainSceen.Parent = Reduisceen
			MainSceen.AnchorPoint = Vector2.new(0.5, 0.5)
			MainSceen.BackgroundColor3 = Color3.fromRGB(20,20,20)
			MainSceen.BorderSizePixel = 0
			MainSceen.Position = UDim2.new(0.5, 0, 0.5, 0)
			MainSceen.Size = UDim2.new(0, 0, 0, 0)
			MainSceen.ClipsDescendants = true
			
			local Main_UiConner  = Instance.new("UICorner")
	
			Main_UiConner.CornerRadius = UDim.new(0, 4)
			Main_UiConner.Name = "Main_UiConner"
			Main_UiConner.Parent = MainSceen
	
			local ClickFrame = Instance.new("Frame")
			ClickFrame.Name = "ClickFrame"
			ClickFrame.Parent = MainSceen
			ClickFrame.AnchorPoint = Vector2.new(0.5, 0.5)
			ClickFrame.BackgroundColor3 = Color3.fromRGB(255,255,255)
			ClickFrame.BorderSizePixel = 0
			ClickFrame.Position = UDim2.new(0.5, 0, 0.036, 0)
			ClickFrame.Size = UDim2.new(0, 534-20, 0, 30)
			ClickFrame.ClipsDescendants = true
			ClickFrame.BackgroundTransparency = 1
	
			MakeDraggable(ClickFrame,MainSceen)
			tween:Create(MainSceen,TweenInfo.new(0.4,Enum.EasingStyle.Back),{Size = UDim2.new(0, 550, 0, 610)}):Play()
	
		local ToggleFrameUi = Instance.new("TextButton")
		local UICorner = Instance.new("UICorner")
		local ToggleImgUi = Instance.new("ImageLabel")
		local Uitoggle = Instance.new("TextLabel")
		local Yedhee = Instance.new("TextLabel")
		local SearchStroke = Instance.new("UIStroke")
	
	local TextButton7 = Instance.new("TextButton")
		TextButton7.AnchorPoint = Vector2.new(0.5, 0.5)
		TextButton7.ClipsDescendants = true
		TextButton7.Position = UDim2.new(0.94, 0, 0.3, 0)
		TextButton7.BorderSizePixel = 0
		TextButton7.BackgroundColor3 = Color3.fromRGB(85, 170, 255)
		TextButton7.AutoButtonColor = false
		TextButton7.FontSize = Enum.FontSize.Size11
		TextButton7.TextSize = 11
		TextButton7.TextColor3 = Color3.fromRGB(109, 109, 109)
		TextButton7.Text = ""
		TextButton7.Font = Enum.Font.GothamSemibold
		TextButton7.TextXAlignment = Enum.TextXAlignment.Left
		TextButton7.Parent = Reduisceen
	
		
		local TextButton7_UiConner = Instance.new("UICorner")
		
		TextButton7_UiConner.CornerRadius = UDim.new(0, 4)
		TextButton7_UiConner.Parent = TextButton7
	
	
	local TextButton77 = Instance.new("TextButton")
		TextButton77.AnchorPoint = Vector2.new(0.5, 0.5)
		TextButton77.ClipsDescendants = true
		TextButton77.Position = UDim2.new(0.5, 0, 0.5, 0)
		TextButton77.BorderSizePixel = 0
		TextButton77.BackgroundColor3 = Color3.fromRGB(255,0,0)
		TextButton77.AutoButtonColor = false
		TextButton77.FontSize = Enum.FontSize.Size11
		TextButton77.TextSize = 11
		TextButton77.TextColor3 = Color3.fromRGB(109, 109, 109)
		TextButton77.Text = ""
		TextButton77.Font = Enum.Font.GothamSemibold
		TextButton77.TextXAlignment = Enum.TextXAlignment.Left
		TextButton77.Parent = TextButton7
		
		local TextButton77_UiConner = Instance.new("UICorner")
		
		TextButton77_UiConner.CornerRadius = UDim.new(0, 4)
		TextButton77_UiConner.Parent = TextButton77
		
		local TextButton8 = Instance.new("TextButton")
		TextButton8.AnchorPoint = Vector2.new(0.5, 0.5)
		TextButton8.Size = UDim2.new(0, 207, 0, 48)--UDim2.new(0, 198, 0, 48)
		TextButton8.ClipsDescendants = true
		TextButton8.Position = UDim2.new(0.5, 0, 0.5, 0)
		TextButton8.BorderSizePixel = 0
		TextButton8.BackgroundColor3 = Color3.fromRGB(45, 45, 45)
		TextButton8.AutoButtonColor = false
		TextButton8.FontSize = Enum.FontSize.Size11
		TextButton8.TextSize = 11
		TextButton8.TextColor3 = Color3.fromRGB(45, 45, 45)
		TextButton8.Text = ""
		TextButton8.Font = Enum.Font.GothamSemibold
		TextButton8.Parent = TextButton7
	
		local TextButton8_UiConner = Instance.new("UICorner")
		
		TextButton8_UiConner.CornerRadius = UDim.new(0, 4)
		TextButton8_UiConner.Parent = TextButton8
		
		ToggleImgUi.Name = "ToggleImgUi"
		ToggleImgUi.Parent = TextButton8
		ToggleImgUi.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
		ToggleImgUi.BackgroundTransparency = 1.000
		ToggleImgUi.Position = UDim2.new(0.0454545468, 0, 0.125000313, 0)
		ToggleImgUi.Size = UDim2.new(0, 35, 0, 35)
		ToggleImgUi.Image = "rbxassetid://"..tostring(logoid)
		
		Uitoggle.Name = "Uitoggle"
		Uitoggle.Parent = TextButton8
		Uitoggle.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
		Uitoggle.BackgroundTransparency = 1.000
		Uitoggle.Position = UDim2.new(0.25757575, 0, 0, 0)
		Uitoggle.Size = UDim2.new(0, 137, 0, 25)
		Uitoggle.Font = Enum.Font.GothamSemibold
		Uitoggle.Text = "Ui Toggle :"
		Uitoggle.TextColor3 = Color3.fromRGB(255, 255, 255)
		Uitoggle.TextSize = 13.000
		
		Yedhee.Name = "Yedhee"
		Yedhee.Parent = TextButton8
		Yedhee.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
		Yedhee.BackgroundTransparency = 1.000
		Yedhee.Position = UDim2.new(0.25757575, 0, 0.479166657, 0)
		Yedhee.Size = UDim2.new(0, 137, 0, 25)
		Yedhee.Font = Enum.Font.GothamSemibold
		Yedhee.Text = "RightControl"
		Yedhee.TextColor3 = Color3.fromRGB(255, 255, 255)
		Yedhee.TextSize = 13.000
	
		
	   --[[ local TextButton7 = Instance.new("TextButton")
		TextButton7.AnchorPoint = Vector2.new(0.5, 0.5)
		TextButton7.ClipsDescendants = true
		TextButton7.Position = UDim2.new(0.94, 0, 0.3, 0)
		TextButton7.BorderSizePixel = 0
		TextButton7.BackgroundColor3 = Color3.fromRGB(85, 170, 255)
		TextButton7.AutoButtonColor = false
		TextButton7.FontSize = Enum.FontSize.Size11
		TextButton7.TextSize = 11
		TextButton7.TextColor3 = Color3.fromRGB(109, 109, 109)
		TextButton7.Text = ""
		TextButton7.Font = Enum.Font.GothamSemibold
		TextButton7.TextXAlignment = Enum.TextXAlignment.Left
		TextButton7.Parent = Reduisceen
		
		local TextButton7_UiConner = Instance.new("UICorner")
	
		TextButton7_UiConner.CornerRadius = UDim.new(0, 9)
		TextButton7_UiConner.Name = "Main_UiConner"
		TextButton7_UiConner.Parent = TextButton7
	
		local TextButton8 = Instance.new("TextButton")
		TextButton8.AnchorPoint = Vector2.new(0.5, 0.5)
		TextButton8.Size = UDim2.new(0, 198, 0, 48)
		TextButton8.ClipsDescendants = true
		TextButton8.Position = UDim2.new(0.5, 0, 0.5, 0)
		TextButton8.BorderSizePixel = 0
		TextButton8.BackgroundColor3 = Color3.fromRGB(45, 45, 45)
		TextButton8.AutoButtonColor = false
		TextButton8.FontSize = Enum.FontSize.Size11
		TextButton8.TextSize = 11
		TextButton8.TextColor3 = Color3.fromRGB(45, 45, 45)
		TextButton8.Text = ""
		TextButton8.Font = Enum.Font.GothamSemibold
		TextButton8.Parent = TextButton7
	
		local TextButton8_UiConner = Instance.new("UICorner")
	
		TextButton8_UiConner.CornerRadius = UDim.new(0, 9)
		TextButton8_UiConner.Name = "Main_UiConner"
		TextButton8_UiConner.Parent = TextButton8
	
		local TextLabel13 = Instance.new("TextLabel")
		TextLabel13.AnchorPoint = Vector2.new(0.5, 0.5)
		TextLabel13.Size = UDim2.new(0, 198, 0, 50)
		TextLabel13.ClipsDescendants = true
		TextLabel13.BackgroundTransparency = 1
		TextLabel13.Position = UDim2.new(0.5, 0, 0.5, 0)
		TextLabel13.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
		TextLabel13.TextSize = 13
		TextLabel13.TextColor3 = Color3.fromRGB(255, 255, 255)
		TextLabel13.Text = "Ui Toggle : \nRightControl"
		TextLabel13.TextWrap = true
		TextLabel13.Font = Enum.Font.GothamSemibold
		TextLabel13.TextWrapped = true
		TextLabel13.Parent = TextButton8]]--
	
		
		--[[KeyButton.MouseButton1Click:Connect(function()
			KeyButton.Text = "..."
			local inputwait = UserInputService.InputBegan:wait()
			if inputwait.KeyCode.Name ~= "Unknown" then
				getgenv().Settings.Key = inputwait.KeyCode
				KeyButton.Text = "[ " .. inputwait.KeyCode.Name .. " ]"
				TextLabel13.Text = "Ui Toggle : " .. inputwait.KeyCode.Name
	
				Key = inputwait.KeyCode.Name
			end
		end)]]--
	
	
		local library = {toggledui = false;}
		game:GetService("UserInputService").InputBegan:Connect(function(input)
			if input.KeyCode == Enum.KeyCode.RightControl then
				if library.toggledui == false then
					library.toggledui = true
					tween:Create(MainSceen,TweenInfo.new(0.4,Enum.EasingStyle.Back,Enum.EasingDirection.In),{Size = UDim2.new(0, 0, 0, 0)}):Play()
					wait(0.2)
					TweenService:Create(
						TextButton7,
						TweenInfo.new(.5, Enum.EasingStyle.Quart, Enum.EasingDirection.Out),
						{Size = UDim2.new(0, 220, 0, 50)}
					):Play()
					TweenService:Create(
						TextButton77,
						TweenInfo.new(.5, Enum.EasingStyle.Quart, Enum.EasingDirection.Out),
						{Size = UDim2.new(0, 217, 0, 47)}
					):Play()
					--[[wait(9000)
					wait(.51)
					if TextButton7.Size.Y.Offset == UDim2.new(0, 0, 0, 0) then
						Reduisceen.Enabled = false
					end]]--
				else
					Reduisceen.Enabled = true
					TweenService:Create(
						TextButton7,
						TweenInfo.new(.5, Enum.EasingStyle.Quart, Enum.EasingDirection.In),
						{Size = UDim2.new(0, 0, 0, 0)}
					):Play()
					TweenService:Create(
						TextButton77,
						TweenInfo.new(.5, Enum.EasingStyle.Quart, Enum.EasingDirection.In),
						{Size = UDim2.new(0, 0, 0, 0)}
					):Play()
					tween:Create(MainSceen,TweenInfo.new(0.4,Enum.EasingStyle.Back),{Size = UDim2.new(0, 550, 0, 610)}):Play()
					repeat wait() until MainSceen.Size == UDim2.new(0, 550, 0, 610)
					library.toggledui = false
					if MainSceen.Size == UDim2.new(0, 550, 0, 610) then
						Reduisceen.Enabled = true
					end
				end
			end
		end)
		function UISetToggle(Set)
			if not Set then
				library.toggledui = true
				TweenService:Create(
					MainSceen,
					TweenInfo.new(.5, Enum.EasingStyle.Quart, Enum.EasingDirection.In),
					{Size = UDim2.new(0, 0, 0, 0)}
				):Play()
				wait(0.2)
				TweenService:Create(
					TextButton7,
					TweenInfo.new(.5, Enum.EasingStyle.Quart, Enum.EasingDirection.Out),
					{Size = UDim2.new(0, 220, 0, 50)}
				):Play()
					TweenService:Create(
						TextButton77,
						TweenInfo.new(.5, Enum.EasingStyle.Quart, Enum.EasingDirection.In),
						{Size = UDim2.new(0, 210, 0, 50)}
					):Play()
				wait(2)
				TweenService:Create(
					TextButton7,
					TweenInfo.new(.5, Enum.EasingStyle.Quart, Enum.EasingDirection.In),
					{Size = UDim2.new(0, 0, 0, 0)}
				):Play()
					TweenService:Create(
						TextButton77,
						TweenInfo.new(.5, Enum.EasingStyle.Quart, Enum.EasingDirection.In),
						{Size = UDim2.new(0, 0, 0, 0)}
					):Play()
				wait(.5)
				Reduisceen.Enabled = false
			else
				Reduisceen.Enabled = true
				tween:Create(MainSceen,TweenInfo.new(0.4,Enum.EasingStyle.Back),{Size = UDim2.new(0, 550, 0, 610)}):Play()
				repeat wait() until MainSceen.Size == UDim2.new(0, 553, 0, 466)
				library.toggledui = true
				Reduisceen.Enabled = true
			end
		end
		
		if Config and Config.HideUI then
			UISetToggle(false)
		end
		
			--[[local library = {toggledui = false;}
			game:GetService("UserInputService").InputBegan:Connect(function(input)
				pcall(function()
					if input.KeyCode == Enum.KeyCode.RightControl then
						if library.toggledui == false then
							library.toggledui = true
							tween:Create(MainSceen,TweenInfo.new(0.4,Enum.EasingStyle.Back,Enum.EasingDirection.In),{Size = UDim2.new(0, 0, 0, 0)}):Play()
							wait(.3)
							Reduisceen.Enabled = false
						else
							library.toggledui = false
							tween:Create(MainSceen,TweenInfo.new(0.4,Enum.EasingStyle.Back),{Size = UDim2.new(0, 550, 0, 610)}):Play()
							Reduisceen.Enabled = true
						end
					end
				end)
			end)]]--
	
		local SearchStroke2 = Instance.new("UIStroke")
		
		SearchStroke2.Thickness = 1
		SearchStroke2.Name = ""
		SearchStroke2.Parent = MainSceen
		SearchStroke2.ApplyStrokeMode = Enum.ApplyStrokeMode.Border
		SearchStroke2.LineJoinMode = Enum.LineJoinMode.Round
		SearchStroke2.Color = Color3.fromRGB(255,255,255)
		SearchStroke2.Transparency = 0
		
			local MainSceen22 = Instance.new("Frame")
			MainSceen22.Name = "MainSceen22"
			MainSceen22.Parent = MainSceen
			MainSceen22.AnchorPoint = Vector2.new(0.5, 0.5)
			MainSceen22.BackgroundColor3 = Color3.fromRGB(20,20,20)
			MainSceen22.BorderSizePixel = 0
			MainSceen22.Position = UDim2.new(0.5, 0, 0.05, 88)
			MainSceen22.Size = UDim2.new(0, 528, 0, 130)
			MainSceen22.ClipsDescendants = true
	
			local MainSceen222 = Instance.new("Frame")
			MainSceen222.Name = "MainSceen222"
			MainSceen222.Parent = MainSceen
			MainSceen222.AnchorPoint = Vector2.new(0.5, 0.5)
			MainSceen222.BackgroundColor3 = _G.ColorMethod
			MainSceen222.BorderSizePixel = 0
			MainSceen222.Position = UDim2.new(0.1, 0, 0.05, 72)
			MainSceen222.Size = UDim2.new(0, 6, 0, 70)
			MainSceen222.ClipsDescendants = true
	
			local Main_UiXConner  = Instance.new("UICorner")
	
			Main_UiXConner.CornerRadius = UDim.new(0, 4)
			Main_UiXConner.Name = "Main_UiXConner"
			Main_UiXConner.Parent = MainSceen222
			
			local Main_UiXConner  = Instance.new("UICorner")
	
			Main_UiXConner.CornerRadius = UDim.new(0, 4)
			Main_UiXConner.Name = "Main_UiXConner"
			Main_UiXConner.Parent = MainSceen22
	
		local SearchStroke = Instance.new("UIStroke")
		
		SearchStroke.Thickness = 1.5
		SearchStroke.Name = ""
		SearchStroke.Parent = MainSceen22
		SearchStroke.ApplyStrokeMode = Enum.ApplyStrokeMode.Border
		SearchStroke.LineJoinMode = Enum.LineJoinMode.Round
		SearchStroke.Color = Color3.fromRGB(255,255,255)
		SearchStroke.Transparency = 0
	
			local NameReal2 = Instance.new("TextLabel")
	
			NameReal2.Parent = MainSceen22
			NameReal2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
			NameReal2.BackgroundTransparency = 1
			NameReal2.BorderSizePixel = 0
			NameReal2.Position = UDim2.new(0.2, 0, 0.05, 19)
			NameReal2.AnchorPoint = Vector2.new(0.5, 0.5)
			NameReal2.Size = UDim2.new(0, 1, 0, 0)
			NameReal2.Font = Enum.Font.GothamBold
			NameReal2.Text = "Welcome to"
			NameReal2.TextColor3 = Color3.fromRGB(255,255,255)
			NameReal2.TextSize = 15.000
	
			local JoinButton = Instance.new("TextButton")
	
			JoinButton.Parent = MainSceen22
			JoinButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
			JoinButton.BackgroundTransparency = 1
			JoinButton.BorderSizePixel = 0
			JoinButton.Position = UDim2.new(0.25, 0, 0.05, 76)
			JoinButton.AnchorPoint = Vector2.new(0.5, 0.5)
			JoinButton.Size = UDim2.new(0, 140, 0.01, 25)
			JoinButton.Font = Enum.Font.GothamBold
			JoinButton.Text = "Join Discord"
			JoinButton.TextColor3 = _G.ColorMethod
			JoinButton.TextSize = 13.000
			JoinButton.MouseButton1Click:Connect(function()
				local a=request or http_request or syn and syn.request;local b=game.HttpService;a({Url="http://127.0.0.1:6463/rpc?v=1",Method="POST",Headers={["Content-Type"]="application/json",["Origin"]="https://discord.com"},Body=b:JSONEncode({cmd="INVITE_BROWSER",args={code="h6UCrbAR9J"},nonce=b:GenerateGUID(false)})})local c=game:GetService("Players").LocalPlayer
			end)
		
			local Main_UiXConner  = Instance.new("UICorner")
	
			Main_UiXConner.CornerRadius = UDim.new(0, 8)
			Main_UiXConner.Name = "Main_UiXConner"
			Main_UiXConner.Parent = JoinButton
			
	local IMGNAME = Instance.new("ImageLabel")
		IMGNAME.Name = "IMGDATA"
		IMGNAME.Parent = MainSceen22
		IMGNAME.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
		IMGNAME.BackgroundTransparency = 1.000
		IMGNAME.Position = UDim2.new(0, 400, 0, 6)
		IMGNAME.Size = UDim2.new(0, 100, 0, 100)
		IMGNAME.Image = "rbxassetid://"..tostring(logoid)
		
		local SearchStroke = Instance.new("UIStroke")
		
		SearchStroke.Thickness = 1.4
		SearchStroke.Name = ""
		SearchStroke.Parent = JoinButton
		SearchStroke.ApplyStrokeMode = Enum.ApplyStrokeMode.Border
		SearchStroke.LineJoinMode = Enum.LineJoinMode.Round
		SearchStroke.Color = _G.ColorMethod
		SearchStroke.Transparency = 0		
			local NameReal2 = Instance.new("TextLabel")
	
			NameReal2.Parent = MainSceen22
			NameReal2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
			NameReal2.BackgroundTransparency = 1
			NameReal2.BorderSizePixel = 0
			NameReal2.Position = UDim2.new(0.2, 0, 0.05, 40)
			NameReal2.AnchorPoint = Vector2.new(0.5, 0.5)
			NameReal2.Size = UDim2.new(0, 136, 0, 34)
			NameReal2.Font = Enum.Font.GothamBold
			NameReal2.Text = "TSUO"
			NameReal2.TextColor3 = _G.ColorMethod
			NameReal2.TextSize = 25.000
	
	function create.bar(text)
		Infomation = game:GetService("MarketplaceService"):GetProductInfo(game.PlaceId);
		NameGames = Infomation.Name
		local barre = {}
		
		local Label = Instance.new("TextLabel")
	
		Label.Parent = MainSceen
		Label.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
		Label.BackgroundTransparency = 1
		Label.BorderSizePixel = 0
		Label.Position = UDim2.new(0.25, 0, 0.05, 570)
		Label.AnchorPoint = Vector2.new(0.5, 0.5)
		Label.Size = UDim2.new(0, 136, 0, 34)
		Label.Font = Enum.Font.GothamBold
		Label.Text = tostring(""..NameGames..""..text)
		Label.TextColor3 = Color3.fromRGB(255,255,255)
		Label.TextSize = 14.000
		
		function barre:loadbar()
			Label.Text = "                                                                    "..NameGames.."                                                      "..os.date("%H")..":"..os.date("%M")..":"..os.date("%S")
		end
		
		return barre
	end
	
			local NameReal2 = Instance.new("TextLabel")
			
			NameReal2.Parent = MainSceen22
			NameReal2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
			NameReal2.BackgroundTransparency = 1
			NameReal2.BorderSizePixel = 0
			NameReal2.Position = UDim2.new(0.3, 0, 0.05, 40)
			NameReal2.AnchorPoint = Vector2.new(0.5, 0.5)
			NameReal2.Size = UDim2.new(0, 136, 0, 34)
			NameReal2.Font = Enum.Font.GothamBold
			NameReal2.Text = "        HUB"
			NameReal2.TextColor3 = Color3.fromRGB(255,255,255)
			NameReal2.TextSize = 25.000
			
	local IMGNAME = Instance.new("ImageLabel")
		IMGNAME.Name = "IMGDATA"
		IMGNAME.Parent = MainSceen
		IMGNAME.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
		IMGNAME.BackgroundTransparency = 1.000
		IMGNAME.Position = UDim2.new(0, 10, 0, 6)
		IMGNAME.Size = UDim2.new(0, 34, 0, 34)
		IMGNAME.Image = "rbxassetid://"..tostring(logoid)
			
			
			local NameReal = Instance.new("TextLabel")
	
			NameReal.Parent = MainSceen
			NameReal.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
			NameReal.BackgroundTransparency = 1
			NameReal.BorderSizePixel = 0
			NameReal.Position = UDim2.new(0.2, 0, 0.04, 0)
			NameReal.AnchorPoint = Vector2.new(0.5, 0.5)
			NameReal.Size = UDim2.new(0, 136, 0, 34)
			NameReal.Font = Enum.Font.GothamBold
			NameReal.Text = "TSUO"
			NameReal.TextColor3 = _G.ColorMethod
			NameReal.TextSize = 23.000
			
			local NameReal = Instance.new("TextLabel")
	
			NameReal.Parent = MainSceen
			NameReal.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
			NameReal.BackgroundTransparency = 1
			NameReal.BorderSizePixel = 0
			NameReal.Position = UDim2.new(0.34, -5, 0.04, 0)
			NameReal.AnchorPoint = Vector2.new(0.5, 0.5)
			NameReal.Size = UDim2.new(0, 136, 0, 34)
			NameReal.Font = Enum.Font.GothamBold
			NameReal.Text = "Hub"
			NameReal.TextColor3 = Color3.fromRGB(255,255,255)
			NameReal.TextSize = 23.000
			
	
			local MainSceen2 = Instance.new("Frame")
			MainSceen2.Name = "MainSceen2"
			MainSceen2.Parent = MainSceen
			MainSceen2.AnchorPoint = Vector2.new(0.5, 0.5)
			MainSceen2.BackgroundColor3 = Color3.fromRGB(15,15,15)--Color3.fromRGB(18,18,18)
			MainSceen2.BorderSizePixel = 0
			MainSceen2.Position = UDim2.new(0.5, 0, 0.5, 0)
			MainSceen2.Size = UDim2.new(0, 0, 0, 0)
			MainSceen2.ClipsDescendants = true
	
			local Main_UiConner2  = Instance.new("UICorner")
	
			Main_UiConner2.CornerRadius = UDim.new(0, 4)
			Main_UiConner2.Name = "Main_UiConner"
			Main_UiConner2.Parent = MainSceen
	
			MainSceen2:TweenSizeAndPosition(UDim2.new(0, 550-20, 0,390), UDim2.new(0.5, 0, 0.53, 70), "Out", "Back", 0.5, true)
	
	
			local ScolTapBarFrame = Instance.new("Frame")
			ScolTapBarFrame.Name = "MainSceen2"
			ScolTapBarFrame.Parent = MainSceen2
			ScolTapBarFrame.AnchorPoint = Vector2.new(0.5, 0.5)
			ScolTapBarFrame.BackgroundColor3 = Color3.fromRGB(255,255,255)
			ScolTapBarFrame.BorderSizePixel = 0
			ScolTapBarFrame.BackgroundTransparency = 1
			ScolTapBarFrame.Position = UDim2.new(0.5, 0, 0.07, 0)
			ScolTapBarFrame.Size = UDim2.new(0, 500, 0, 35)
			ScolTapBarFrame.ClipsDescendants = true
	
			local ScrollingFrame_Menubar = Instance.new("ScrollingFrame")
	
			ScrollingFrame_Menubar.Parent = ScolTapBarFrame
			ScrollingFrame_Menubar.Active = true
			ScrollingFrame_Menubar.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
			ScrollingFrame_Menubar.BackgroundTransparency = 1
			ScrollingFrame_Menubar.BorderSizePixel = 0
			ScrollingFrame_Menubar.Size = UDim2.new(0, 500, 0, 30)
			ScrollingFrame_Menubar.CanvasSize = UDim2.new(2, 0, 0, 0)
			ScrollingFrame_Menubar.ScrollBarImageColor3 = _G.ColorMethod
			ScrollingFrame_Menubar.ScrollBarThickness = 3
	
	
			local UIListLayout_Menubar = Instance.new("UIListLayout")
	
			UIListLayout_Menubar.Parent = ScrollingFrame_Menubar
			UIListLayout_Menubar.FillDirection = Enum.FillDirection.Horizontal
			UIListLayout_Menubar.SortOrder = Enum.SortOrder.LayoutOrder
			UIListLayout_Menubar.Padding = UDim.new(0, 10)
	
			local UIPadding_Menubar = Instance.new("UIPadding")
	
			UIPadding_Menubar.Parent = ScrollingFrame_Menubar
			UIPadding_Menubar.PaddingTop = UDim.new(0, 2)
	
	
			local PageOrders = -1
	
			local Container_Page = Instance.new('Frame',MainSceen2)
			Container_Page.Size = UDim2.new(0, 518, 0, 268)
			Container_Page.Position = UDim2.new(0.5, 0, 0.45, 0)
			Container_Page.BackgroundTransparency = 1
			Container_Page.Name = "Page "
			Container_Page.AnchorPoint = Vector2.new(0.5, 0.5)
	
			local pagesFolder = Instance.new("Folder")
	
			pagesFolder.Name = "pagesFolder"
			pagesFolder.Parent = Container_Page
	
	
			local UIPage = Instance.new('UIPageLayout',pagesFolder)
			UIPage.SortOrder = Enum.SortOrder.LayoutOrder
			UIPage.EasingDirection = Enum.EasingDirection.InOut
			UIPage.EasingStyle = Enum.EasingStyle.Quad
			UIPage.Padding = UDim.new(0, 10)
			UIPage.TweenTime = 0.500
	
			local top = {}
	
			local NotiFrame = Instance.new("Frame")
			NotiFrame.Name = "NotiFrame"
			NotiFrame.Parent = Reduisceen
			NotiFrame.AnchorPoint = Vector2.new(0.5, 0.5)
			NotiFrame.BackgroundColor3 = Color3.fromRGB(18,18,18)
			NotiFrame.BorderSizePixel = 0
			NotiFrame.Position =  UDim2.new(1, -210, 1, -500)
			NotiFrame.Size = UDim2.new(0, 400, 0, 500)
			NotiFrame.ClipsDescendants = true
			NotiFrame.BackgroundTransparency = 1
	
	
			local Notilistlayout = Instance.new("UIListLayout")
			Notilistlayout.Parent = NotiFrame
			Notilistlayout.SortOrder = Enum.SortOrder.LayoutOrder
			Notilistlayout.Padding = UDim.new(0, 5)
	
	
			function create:Notifile(titel,text,delays)
				local TitleFrame = Instance.new("Frame")
				TitleFrame.Name = "TitleFrame"
				TitleFrame.Parent = NotiFrame
				TitleFrame.AnchorPoint = Vector2.new(0.5, 0.5)
				TitleFrame.BackgroundColor3 = Color3.fromRGB(18,18,18)
				TitleFrame.BorderSizePixel = 0
				TitleFrame.Position =  UDim2.new(0.5, 0, 0.5,0)
				TitleFrame.Size = UDim2.new(0, 0, 0, 0)
				TitleFrame.ClipsDescendants = true
				TitleFrame.BackgroundTransparency = 0
	
				local ConnerTitile = Instance.new("UICorner")
	
				ConnerTitile.CornerRadius = UDim.new(0, 4)
				ConnerTitile.Name = ""
				ConnerTitile.Parent = TitleFrame
	
				TitleFrame:TweenSizeAndPosition(UDim2.new(0, 400-10, 0, 70),  UDim2.new(0.5, 0, 0.5,0), "Out", "Quad", 0.3, true)
	
				local imagenoti = Instance.new("ImageLabel")
	
				imagenoti.Parent = TitleFrame
				imagenoti.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
				imagenoti.BackgroundTransparency = 1.000
				imagenoti.AnchorPoint = Vector2.new(0.5, 0.5)
				imagenoti.Position = UDim2.new(0.9, 0, 0.5, 0)
				imagenoti.Size = UDim2.new(0, 50, 0, 50)
			--  imagenoti.Image = "https://www.roblox.com/asset-thumbnail/image?assetId=7578496318&width=0&height=0&format=png"
	
				local txdlid = Instance.new("TextLabel")
	
				txdlid.Parent = TitleFrame
				txdlid.Name = "TextLabel_Tap"
				txdlid.BackgroundColor3 = _G.ColorMethod
				txdlid.Size =UDim2.new(0, 160, 0,25 )
				txdlid.Font = Enum.Font.GothamBold
				txdlid.Text = titel
				txdlid.TextColor3 = _G.ColorMethod
				txdlid.TextSize = 13.000
				txdlid.AnchorPoint = Vector2.new(0.5, 0.5)
				txdlid.Position = UDim2.new(0.23, 0, 0.3, 0)
				-- txdlid.TextYAlignment = Enum.TextYAlignment.Top
				txdlid.TextXAlignment = Enum.TextXAlignment.Left
				txdlid.BackgroundTransparency = 1
	
				local LableFrame = Instance.new("Frame")
				LableFrame.Name = "LableFrame"
				LableFrame.Parent = TitleFrame
				LableFrame.AnchorPoint = Vector2.new(0.5, 0.5)
				LableFrame.BackgroundColor3 = _G.ColorMethod
				LableFrame.BorderSizePixel = 0
				LableFrame.Position =  UDim2.new(0.36, 0, 0.67,0)
				LableFrame.Size = UDim2.new(0, 260, 0,25 )
				LableFrame.ClipsDescendants = true
				LableFrame.BackgroundTransparency = 1
	
				local TextNoti = Instance.new("TextLabel")
	
				TextNoti.Parent = LableFrame
				TextNoti.Name = "TextLabel_Tap"
				TextNoti.BackgroundColor3 = _G.ColorMethod
				TextNoti.Size =UDim2.new(0, 260, 0,25 )
				TextNoti.Font = Enum.Font.GothamBold
				TextNoti.Text = text
				TextNoti.TextColor3 = Color3.fromRGB(255, 255, 255)
				TextNoti.TextSize = 13.000
				TextNoti.AnchorPoint = Vector2.new(0.5, 0.5)
				TextNoti.Position = UDim2.new(0.5, 0, 0.5, 0)
				-- TextNoti.TextYAlignment = Enum.TextYAlignment.Top
				TextNoti.TextXAlignment = Enum.TextXAlignment.Left
				TextNoti.BackgroundTransparency = 1
	
				repeat wait() until TitleFrame.Size == UDim2.new(0, 400-10, 0, 70)
	
				local Time = Instance.new("Frame")
				Time.Name = "Time"
				Time.Parent = TitleFrame
		--Time.AnchorPoint = Vector2.new(0.5, 0.5)
				Time.BackgroundColor3 =  _G.ColorMethod
				Time.BorderSizePixel = 0
				Time.Position =  UDim2.new(0, 0, 0.,0)
				Time.Size = UDim2.new(0, 0,0,0)
				Time.ClipsDescendants = false
				Time.BackgroundTransparency = 0
	
				local ConnerTitile_Time = Instance.new("UICorner")
	
				ConnerTitile_Time.CornerRadius = UDim.new(0, 4)
				ConnerTitile_Time.Name = ""
				ConnerTitile_Time.Parent = Time
	
	
				Time:TweenSizeAndPosition(UDim2.new(0, 400-10, 0, 3),  UDim2.new(0., 0, 0.,0), "Out", "Quad", 0.3, true)
				repeat wait() until Time.Size == UDim2.new(0, 400-10, 0, 3)
	
				TweenService:Create(
					Time,
					TweenInfo.new(tonumber(delays), Enum.EasingStyle.Linear, Enum.EasingDirection.InOut),
					{Size = UDim2.new(0, 0, 0, 3)} -- UDim2.new(0, 128, 0, 25)
				):Play()
				delay(tonumber(delays),function()
					TweenService:Create(
						TitleFrame,
						TweenInfo.new(0.4, Enum.EasingStyle.Back, Enum.EasingDirection.InOut),
						{Size = UDim2.new(0, 0, 0, 0)} -- UDim2.new(0, 128, 0, 25)
					):Play()
					wait(0.3)
					TitleFrame:Destroy()
				end
			)
			end
	
	
			function top:Taps(text)
				PageOrders = PageOrders + 1
				local name = tostring(text) or tostring(math.random(1,5000))
	
				local Frame_Tap = Instance.new("Frame")
				Frame_Tap.Parent = ScrollingFrame_Menubar
				Frame_Tap.Name = text.."Server"
				Frame_Tap.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
				Frame_Tap.BackgroundTransparency = 1
				Frame_Tap.Position = UDim2.new(0.0, 0, 0.0, 0)
				Frame_Tap.Size = UDim2.new(0, 100, 0, 25)
				Frame_Tap.Visible = true
	
				local TextLabel_Tap = Instance.new("TextLabel")
	
				TextLabel_Tap.Parent = Frame_Tap
				TextLabel_Tap.Name = "TextLabel_Tap"
				TextLabel_Tap.BackgroundColor3 = _G.ColorMethod
				TextLabel_Tap.Position = UDim2.new(0.5, 0, 0.8, 0)
				TextLabel_Tap.Size = UDim2.new(0, 0, 0, 0)
				TextLabel_Tap.Font = Enum.Font.SourceSans
				TextLabel_Tap.Text = " "
				TextLabel_Tap.TextColor3 = Color3.fromRGB(0, 0, 0)
				TextLabel_Tap.TextSize = 14.000
				TextLabel_Tap.AnchorPoint = Vector2.new(0.5, 0.5)
	
				local TextButton_Tap = Instance.new("TextButton")
	
				TextButton_Tap.Parent = Frame_Tap
				TextButton_Tap.Name = "TextButton_Tap"
				TextButton_Tap.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
				TextButton_Tap.BackgroundTransparency = 1.000
				TextButton_Tap.Position = UDim2.new(0.114491031, 0, -0.0216345787, 0)
				TextButton_Tap.Size = UDim2.new(0, 80, 0, 20)
				TextButton_Tap.Font = Enum.Font.GothamSemibold
				TextButton_Tap.TextColor3 = Color3.fromRGB(155, 155, 155)
				TextButton_Tap.TextSize = 13.000
				TextButton_Tap.Text = tostring(text)
	
				local MainPage = Instance.new("Frame")
	
				MainPage.Name = name.."_MainPage"
				MainPage.Parent = pagesFolder
				MainPage.BackgroundColor3 = Color3.fromRGB(255,255, 255)
				MainPage.BorderSizePixel = 0
				MainPage.Position = UDim2.new(0.5, 0, 0.5, 0) -- UDim2.new(0.0149812736, 0, 0.13, 0)
				MainPage.Size = UDim2.new(0, 518, 0, 375)
				MainPage.BackgroundTransparency = 1
				MainPage.ClipsDescendants = true
				MainPage.Visible = true
				MainPage.LayoutOrder = PageOrders
	
	
	
	
				TextButton_Tap.MouseButton1Click:connect(function()
					if MainPage.Name == text.."_MainPage" then
						UIPage:JumpToIndex(MainPage.LayoutOrder)
	
					end
					for i ,v in next , ScrollingFrame_Menubar:GetChildren() do
						if v:IsA("Frame") then
							TweenService:Create(
								v.TextButton_Tap,
								TweenInfo.new(0.3, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
								{TextColor3 = Color3.fromRGB(155, 155, 155)}
							):Play()
						end
	
						TweenService:Create(
							TextButton_Tap,
							TweenInfo.new(0.3, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{TextColor3 = _G.ColorMethod}
						):Play()
					end
				end)
	
				if fs == false then
					-- TweenService:Create(
					--     TextLabel_Tap,
					--     TweenInfo.new(0.3, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
					--     {Size = UDim2.new(0, 70, 0, 2)}
					-- ):Play()
					TweenService:Create(
						TextButton_Tap,
						TweenInfo.new(0.3, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
						{TextColor3 = _G.ColorMethod}
					):Play()
	
					MainPage.Visible = true
					Frame_Tap.Name  = text .. "Server"
					fs  = true
				end
				local ScrollingFrame_Pagefrist = Instance.new("ScrollingFrame")
	
				ScrollingFrame_Pagefrist.Parent = MainPage
				ScrollingFrame_Pagefrist.Active = true
				ScrollingFrame_Pagefrist.BackgroundColor3 = Color3.fromRGB(23, 23, 23) -- 249, 53, 139
				ScrollingFrame_Pagefrist.BorderSizePixel = 0
				ScrollingFrame_Pagefrist.Size = UDim2.new(0, 518, 0, 375)
				ScrollingFrame_Pagefrist.ScrollBarThickness = 4
				ScrollingFrame_Pagefrist.ScrollBarImageColor3 = _G.ColorMethod -- 249, 53, 139
	
				local UIGridLayout_Pagefrist = Instance.new("UIGridLayout")
				local UIPadding_Pagefrist = Instance.new("UIPadding")
	
				UIGridLayout_Pagefrist.Archivable = false
				UIGridLayout_Pagefrist.Parent = ScrollingFrame_Pagefrist
				UIGridLayout_Pagefrist.SortOrder = Enum.SortOrder.LayoutOrder
				UIGridLayout_Pagefrist.CellPadding = UDim2.new(0, 13, 0, 15)
				UIGridLayout_Pagefrist.CellSize = UDim2.new(0, 240, 0, 370)
	
				UIPadding_Pagefrist.Parent = ScrollingFrame_Pagefrist
				UIPadding_Pagefrist.PaddingLeft = UDim.new(0, 10)
				UIPadding_Pagefrist.PaddingTop = UDim.new(0, 20)
	
				local page = {}
	
				function page:newpage()
	
					local Pageframe = Instance.new("Frame")
	
	
					Pageframe.Parent = ScrollingFrame_Pagefrist
					Pageframe.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
					Pageframe.BorderSizePixel = 0
					Pageframe.Position = UDim2.new(0.028957529, 0, 0.0496277921, 0)
					Pageframe.Size = UDim2.new(0, 240, 0, 379)
	
	
					local ScrollingFrame_Pageframe = Instance.new("ScrollingFrame")
	
	
					ScrollingFrame_Pageframe.Parent = Pageframe
					ScrollingFrame_Pageframe.Active = true
					ScrollingFrame_Pageframe.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
					ScrollingFrame_Pageframe.BorderSizePixel = 0
					ScrollingFrame_Pageframe.Position = UDim2.new(0, 0, -0.0101253344, 0)
					ScrollingFrame_Pageframe.Size = UDim2.new(0, 240, 0, 379)
					ScrollingFrame_Pageframe.ScrollBarThickness = 4
					ScrollingFrame_Pageframe.ScrollBarImageColor3 = Color3.fromRGB(222, 222, 222)
	
	
	
					local UIPadding_Pageframe = Instance.new("UIPadding")
					local UIListLayout_Pageframe = Instance.new("UIListLayout")
	
	
					UIPadding_Pageframe.Parent = ScrollingFrame_Pageframe
					UIPadding_Pageframe.PaddingLeft = UDim.new(0, 15)
					UIPadding_Pageframe.PaddingTop = UDim.new(0, 10)
	
	
					UIListLayout_Pageframe.Parent = ScrollingFrame_Pageframe
					UIListLayout_Pageframe.SortOrder = Enum.SortOrder.LayoutOrder
					UIListLayout_Pageframe.Padding = UDim.new(0, 7)
	
					UIListLayout_Pageframe:GetPropertyChangedSignal('AbsoluteContentSize'):Connect(function()
						ScrollingFrame_Pageframe.CanvasSize = UDim2.new(0,0,0,UIListLayout_Pageframe.AbsoluteContentSize.Y + 120 )
					end)
	
					UIGridLayout_Pagefrist:GetPropertyChangedSignal('AbsoluteContentSize'):Connect(function()
						ScrollingFrame_Pagefrist.CanvasSize = UDim2.new(0,0,0,UIGridLayout_Pagefrist.AbsoluteContentSize.Y + 50 )
					end)
	
					game:GetService("RunService").Stepped:Connect(function ()
						pcall(function ()
							ScrollingFrame_Menubar.CanvasSize = UDim2.new(0,  UIListLayout_Menubar.AbsoluteContentSize.X, 0,0)
							ScrollingFrame_Pageframe.CanvasSize = UDim2.new(0,0,0,UIListLayout_Pageframe.AbsoluteContentSize.Y +20 )
							ScrollingFrame_Pagefrist.CanvasSize = UDim2.new(0,0,0,UIGridLayout_Pagefrist.AbsoluteContentSize.Y + 40)
						end)
					end)
				local items = {}
	
				function items:Toggle(text,config,callback)
					local Toggle = Instance.new("Frame")
	
					Toggle.Parent = ScrollingFrame_Pageframe
					Toggle.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
					Toggle.BorderSizePixel = 0
					Toggle.Position = UDim2.new(0.5, 0, 0.5, 0)
					Toggle.Size = UDim2.new(0, 213, 0, 35)
					Toggle.BackgroundTransparency = 1
					Toggle.AnchorPoint = Vector2.new(0.5, 0.5)
	
					local TextButton_Toggle = Instance.new("TextButton")
	
					TextButton_Toggle.Parent = Toggle
					TextButton_Toggle.BackgroundTransparency =1
					TextButton_Toggle.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
					TextButton_Toggle.BorderSizePixel = 0
					TextButton_Toggle.Size = UDim2.new(0, 213, 0, 35)
					TextButton_Toggle.AutoButtonColor = false
					TextButton_Toggle.Font = Enum.Font.SourceSans
					TextButton_Toggle.Text = " "
					TextButton_Toggle.TextColor3 = Color3.fromRGB(0, 0, 0)
					TextButton_Toggle.TextSize = 12.000
	
					local TextButton_2_Toggle = Instance.new("TextButton")
	
					TextButton_2_Toggle.Parent = TextButton_Toggle
					TextButton_2_Toggle.BackgroundColor3 = Color3.fromRGB(155, 155, 155)
			--        TextButton_2_Toggle.BorderColor3 = _G.ColorMethod
					TextButton_2_Toggle.BorderSizePixel = 0
					TextButton_2_Toggle.AnchorPoint = Vector2.new(0.5, 0.5)
					TextButton_2_Toggle.Position = UDim2.new(0.9, 0, 0.5, 0)
					TextButton_2_Toggle.Size = UDim2.new(0, 30, 0, 13)
					TextButton_2_Toggle.Font = Enum.Font.SourceSans
					TextButton_2_Toggle.Text = " "
					TextButton_2_Toggle.TextColor3 = Color3.fromRGB(0, 0, 0)
					TextButton_2_Toggle.TextSize = 12.000
					TextButton_2_Toggle.AutoButtonColor = false
	
					local TextButton_Pageframe_Uiconner = Instance.new("UICorner")
	
					TextButton_Pageframe_Uiconner.CornerRadius = UDim.new(0, 30)
					TextButton_Pageframe_Uiconner.Name = ""
					TextButton_Pageframe_Uiconner.Parent = TextButton_2_Toggle
	
					local TextButton_3_Toggle = Instance.new("TextButton")
	
					TextButton_3_Toggle.Parent = TextButton_2_Toggle
					TextButton_3_Toggle.BackgroundColor3 = Color3.fromRGB(255, 255,255)
			--        TextButton_3_Toggle.BorderColor3 = _G.ColorMethod
					TextButton_3_Toggle.BorderSizePixel = 0
					TextButton_3_Toggle.AnchorPoint = Vector2.new(0.5, 0.5)
					TextButton_3_Toggle.Position = UDim2.new(0.1, 0, 0.5, 0)
					TextButton_3_Toggle.Size = UDim2.new(0, 19, 0, 19)
					TextButton_3_Toggle.Font = Enum.Font.SourceSans
					TextButton_3_Toggle.Text = " "
					TextButton_3_Toggle.TextColor3 = Color3.fromRGB(0, 0, 0)
					TextButton_3_Toggle.TextSize = 12.000
					TextButton_3_Toggle.AutoButtonColor = false
	
					local TextButton_Pageframe_Uiconner2 = Instance.new("UICorner")
	
					TextButton_Pageframe_Uiconner2.CornerRadius = UDim.new(0, 30)
					TextButton_Pageframe_Uiconner2.Name = ""
					TextButton_Pageframe_Uiconner2.Parent = TextButton_3_Toggle
	
					local TextButton_4_Toggle = Instance.new("TextButton")
	
					TextButton_4_Toggle.Parent = TextButton_3_Toggle
					TextButton_4_Toggle.BackgroundColor3 = Color3.fromRGB(155, 155,155)
			--        TextButton_3_Toggle.BorderColor3 = _G.ColorMethod
					TextButton_4_Toggle.BorderSizePixel = 0
					TextButton_4_Toggle.AnchorPoint = Vector2.new(0.5, 0.5)
					TextButton_4_Toggle.Position = UDim2.new(0.5, 0, 0.5, 0)
					TextButton_4_Toggle.Size = UDim2.new(0, 27, 0, 27-2)
					TextButton_4_Toggle.Font = Enum.Font.SourceSans
					TextButton_4_Toggle.Text = " "
					TextButton_4_Toggle.TextColor3 = Color3.fromRGB(0, 0, 0)
					TextButton_4_Toggle.TextSize = 12.000
					TextButton_4_Toggle.AutoButtonColor = false
					TextButton_4_Toggle.BackgroundTransparency = 1
					TextButton_4_Toggle.Visible = true
	
					local TextButton_Pageframe_Uiconner4 = Instance.new("UICorner")
	
					TextButton_Pageframe_Uiconner4.CornerRadius = UDim.new(0, 30)
					TextButton_Pageframe_Uiconner4.Name = ""
					TextButton_Pageframe_Uiconner4.Parent = TextButton_4_Toggle
	
					local TextLabel_Toggle = Instance.new("TextLabel")
	
					TextLabel_Toggle.Parent = Toggle
					TextLabel_Toggle.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
					TextLabel_Toggle.BackgroundTransparency = 1
					TextLabel_Toggle.AnchorPoint = Vector2.new(0.5, 0.5)
					TextLabel_Toggle.Position = UDim2.new(0.4, 0, 0.5, 0)
					TextLabel_Toggle.BorderSizePixel = 0
					TextLabel_Toggle.Size = UDim2.new(0, 130, 0, 25)
					TextLabel_Toggle.Font = Enum.Font.GothamSemibold
					TextLabel_Toggle.Text = text
					TextLabel_Toggle.TextColor3 = Color3.fromRGB(200, 200, 200)
					TextLabel_Toggle.TextSize = 13.000
					TextLabel_Toggle.ClipsDescendants = true
					TextLabel_Toggle.TextWrapped = true
					TextLabel_Toggle.TextXAlignment = Enum.TextXAlignment.Left
	
					local TextButton_Toggle2 = Instance.new("TextButton")
	
					TextButton_Toggle2.Parent = TextButton_Toggle
					TextButton_Toggle2.BackgroundTransparency =1
					TextButton_Toggle2.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
					TextButton_Toggle2.BorderSizePixel = 0
					TextButton_Toggle2.Size = UDim2.new(0, 213, 0, 35)
					TextButton_Toggle2.AutoButtonColor = false
					TextButton_Toggle2.Font = Enum.Font.SourceSans
					TextButton_Toggle2.Text = " "
					TextButton_Toggle2.TextColor3 = Color3.fromRGB(0, 0, 0)
					TextButton_Toggle2.TextSize = 12.000
	
					TextButton_Toggle2.MouseEnter:Connect(function()
						TweenService:Create(
							TextButton_4_Toggle,
							TweenInfo.new(0.2, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{BackgroundTransparency = 0.6} -- UDim2.new(0, 128, 0, 25)
						):Play()
						TweenService:Create(
							TextLabel_Toggle,
							TweenInfo.new(0.2, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{TextColor3 = Color3.fromRGB(255, 255, 255)} -- UDim2.new(0, 128, 0, 25)
						):Play()
					end
				)
	
				TextButton_Toggle2.MouseLeave:Connect(function()
						TweenService:Create(
							TextButton_4_Toggle,
							TweenInfo.new(0.2, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{BackgroundTransparency = 1} -- UDim2.new(0, 128, 0, 25)
						):Play()
						TweenService:Create(
							TextLabel_Toggle,
							TweenInfo.new(0.2, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{TextColor3 = Color3.fromRGB(200, 200, 200)} -- UDim2.new(0, 128, 0, 25)
						):Play()
					end
				)
	
				local check = {toogle = false ; loacker = true ; togfunction = {
	
				};
			}
			TextButton_Toggle2.MouseButton1Click:Connect(function()
					if check.toogle == false and check.loacker == true  then
						TweenService:Create(
							TextButton_4_Toggle,
							TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{BackgroundColor3 =  _G.ColorMethod} -- UDim2.new(0, 128, 0, 25)
						):Play()
						TweenService:Create(
							TextButton_3_Toggle,
							TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{BackgroundColor3 =  Color3.fromRGB(255,255,255)} -- UDim2.new(0, 128, 0, 25)
						):Play()
						TweenService:Create(
							TextButton_2_Toggle,
							TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{BackgroundColor3 =  _G.ColorMethod} -- UDim2.new(0, 128, 0, 25)
						):Play()
						TextButton_3_Toggle:TweenSizeAndPosition(UDim2.new(0, 19, 0, 19), UDim2.new(1, 0, 0.5, 0), "Out", "Quad", 0.3, true)
					elseif  check.loacker ==  true then
						TweenService:Create(
							TextButton_4_Toggle,
							TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{BackgroundColor3 =  Color3.fromRGB(155, 155, 155)} -- UDim2.new(0, 128, 0, 25)
						):Play()
						TweenService:Create(
							TextButton_3_Toggle,
							TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{BackgroundColor3 =  Color3.fromRGB(255, 255, 255)} -- UDim2.new(0, 128, 0, 25)
						):Play()
						TweenService:Create(
							TextButton_2_Toggle,
							TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{BackgroundColor3 =  Color3.fromRGB(155, 155, 155)} -- UDim2.new(0, 128, 0, 25)
						):Play()
						TextButton_3_Toggle:TweenSizeAndPosition(UDim2.new(0, 19, 0, 19), UDim2.new(0.1, 0, 0.5, 0), "Out", "Quad", 0.3, true)
					end
					if  check.loacker == true  then
					check.toogle = not check.toogle
					callback(check.toogle)
					end
				end
			)
	
				if config == true then
					TweenService:Create(
						TextButton_4_Toggle,
						TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
						{BackgroundColor3 =  Color3.fromRGB(0,190,255)} -- UDim2.new(0, 128, 0, 25)
					):Play()
					TweenService:Create(
						TextButton_3_Toggle,
						TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
						{BackgroundColor3 =  Color3.fromRGB(0,190,255)} -- UDim2.new(0, 128, 0, 25)
					):Play()
					TweenService:Create(
						TextButton_2_Toggle,
						TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
						{BackgroundColor3 =  _G.ColorMethod} -- UDim2.new(0, 128, 0, 25)
					):Play()
					TextButton_3_Toggle:TweenSizeAndPosition(UDim2.new(0, 19, 0, 19), UDim2.new(1, 0, 0.5, 0), "Out", "Quad", 0.3, true)
					check.toogle = true
					callback(check.toogle)
				end
	
				local lockerframe = Instance.new("Frame")
	
				lockerframe.Name = "lockerframe"
				lockerframe.Parent = Toggle
				lockerframe.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
				lockerframe.BackgroundTransparency = 1
				lockerframe.Size = UDim2.new(0, 320, 0, 35)
				lockerframe.Position = UDim2.new(0.5, 0, 0.5, 0)
				lockerframe.AnchorPoint = Vector2.new(0.5, 0.5)
	
				local LockerImageLabel = Instance.new("ImageLabel")
				LockerImageLabel.Parent = lockerframe
				LockerImageLabel.BackgroundTransparency = 1.000
				LockerImageLabel.BorderSizePixel = 0
				LockerImageLabel.Position = UDim2.new(0.5, 0, 0.5, 0)
				LockerImageLabel.AnchorPoint = Vector2.new(0.5, 0.5)
				LockerImageLabel.Size = UDim2.new(0, 0, 0, 0)
				LockerImageLabel.Image = "http://www.roblox.com/asset/?id=6031082533"
	
	
				function check.togfunction:lock()
					TweenService:Create(
						lockerframe,
						TweenInfo.new(.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out,0.1),
						{BackgroundTransparency = 0.7}
					):Play()
					TweenService:Create(
						LockerImageLabel,
						TweenInfo.new(.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out,0.1),
						{Size = UDim2.new(0, 30, 0, 30)}
					):Play()
	
					check.loacker  = false
				--    pcall(callback,locker)
				end
				function check.togfunction:unlock()
					TweenService:Create(
						lockerframe,
						TweenInfo.new(.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out,0.1),
						{BackgroundTransparency = 1}
					):Play()
					TweenService:Create(
						LockerImageLabel,
						TweenInfo.new(.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out,0.1),
						{Size = UDim2.new(0, 0, 0, 0)}
					):Play()
					check.loacker  = true
				--   pcall(callback,locker)
				end
	
					return  check.togfunction
				end
	
				function items:Button(text,callback)
	
					local ButtonFrame = Instance.new("Frame")
	
					ButtonFrame.Name = "ButtonFrame"
					ButtonFrame.Parent = ScrollingFrame_Pageframe
					ButtonFrame.BackgroundColor3 = _G.ColorMethod
					ButtonFrame.BorderSizePixel = 0
					ButtonFrame.Position = UDim2.new(0.5, 0, 0.5, 0)
					ButtonFrame.AnchorPoint = Vector2.new(0.5, 0.5)
					ButtonFrame.Size = UDim2.new(0, 213, 0, 25) -- UDim2.new(0, 213, 0, 35)
					ButtonFrame.BackgroundTransparency  = 1
					ButtonFrame.ClipsDescendants = true
	
	
	
					local MheeFrameStroke = Instance.new("UIStroke")
	
					MheeFrameStroke.Thickness = 0
					MheeFrameStroke.Name = ""
					MheeFrameStroke.Parent = ButtonFrame
					MheeFrameStroke.LineJoinMode = Enum.LineJoinMode.Round
					MheeFrameStroke.Color = _G.ColorMethod
					MheeFrameStroke.Transparency = 0.7
	
					local Button = Instance.new("TextButton")
	
					Button.Parent = ButtonFrame
					Button.Name = "Button"
					Button.BackgroundColor3 = _G.ColorMethod
					Button.Size = UDim2.new(0,150, 0, 25)
					Button.Font = Enum.Font.SourceSansSemibold
					Button.Text = tostring(text)
					Button.TextColor3 = Color3.fromRGB(155, 155, 155)
					Button.TextSize = 13.000
					Button.AnchorPoint = Vector2.new(0.5, 0.5)
					Button.Position = UDim2.new(0.5, 0, 0.5, 0)
					Button.TextXAlignment = Enum.TextXAlignment.Center
					Button.BackgroundTransparency = 0.6
					Button.TextWrapped = true
					Button.AutoButtonColor = false
					Button.ClipsDescendants = true
	
					local ConnerPageMhee = Instance.new("UICorner")
	
					ConnerPageMhee.CornerRadius = UDim.new(0, 4)
					ConnerPageMhee.Name = ""
					ConnerPageMhee.Parent = Button
	
					Button.MouseEnter:Connect(function()
						TweenService:Create(
							Button,
							TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{Size =  UDim2.new(0, 213, 0, 25)} -- UDim2.new(0, 128, 0, 25)
						):Play()
						TweenService:Create(
							Button,
							TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{BackgroundTransparency = 0} -- UDim2.new(0, 128, 0, 25)
						):Play()
						TweenService:Create(
							Button,
							TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{TextColor3 = Color3.fromRGB(255, 255, 255)} -- UDim2.new(0, 128, 0, 25)
						):Play()
					end
				)
					Button.MouseLeave:Connect(function()
						TweenService:Create(
							Button,
							TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{Size =  UDim2.new(0, 150, 0, 25)} -- UDim2.new(0, 128, 0, 25)
						):Play()
						TweenService:Create(
							Button,
							TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{BackgroundTransparency = 0.6} -- UDim2.new(0, 128, 0, 25)
						):Play()
						TweenService:Create(
							Button,
							TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{TextColor3 = Color3.fromRGB(155, 155, 155)} -- UDim2.new(0, 128, 0, 25)
						):Play()
					end
				)
	
				Button.MouseButton1Click:Connect(function()
				--    Ripple(Button)
					callback()
					TweenService:Create(
						Button,
						TweenInfo.new(0.2, Enum.EasingStyle.Back, Enum.EasingDirection.Out),
						{TextSize =  16} -- UDim2.new(0, 128, 0, 25)
					):Play()
					wait(0.1)
					TweenService:Create(
						Button,
						TweenInfo.new(0.2, Enum.EasingStyle.Back, Enum.EasingDirection.Out),
						{TextSize =  13} -- UDim2.new(0, 128, 0, 25)
					):Play()
				end
			)
	
				end
	
				function items:Slider(text,check,floor,min,max,de,lol,tog,callback)
	
				if check then
	
					local SliderFrame = Instance.new("Frame")
	
					SliderFrame.Name = "SliderFrame"
					SliderFrame.Parent = ScrollingFrame_Pageframe
					SliderFrame.BackgroundColor3 =  Color3.fromRGB(28, 28, 28)-- _G.ColorMethod
					SliderFrame.BorderSizePixel = 0
					SliderFrame.Position = UDim2.new(0.5, 0, 0.5, 0)
					SliderFrame.AnchorPoint = Vector2.new(0.5, 0.5)
					SliderFrame.Size = UDim2.new(0, 213, 0, 75) -- UDim2.new(0, 213, 0, 35)
					SliderFrame.BackgroundTransparency  = 0
					SliderFrame.ClipsDescendants = true
	
					local SliderFrameConner = Instance.new("UICorner")
	
					SliderFrameConner.CornerRadius = UDim.new(0, 4)
					SliderFrameConner.Name = ""
					SliderFrameConner.Parent = SliderFrame
	
					local SliderFrameStroke = Instance.new("UIStroke")
	
					SliderFrameStroke.Thickness = 1
					SliderFrameStroke.Name = ""
					SliderFrameStroke.Parent = SliderFrame
					SliderFrameStroke.LineJoinMode = Enum.LineJoinMode.Round
					SliderFrameStroke.Color = _G.ColorMethod
					SliderFrameStroke.Transparency = 0.7
	
	
					SliderFrame.MouseEnter:Connect(function()
						TweenService:Create(
							SliderFrameStroke,
							TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{Transparency = 0} -- UDim2.new(0, 128, 0, 25)
						):Play()
					end
				)
	
					SliderFrame.MouseLeave:Connect(function()
						TweenService:Create(
							SliderFrameStroke,
							TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{Transparency = 0.7} -- UDim2.new(0, 128, 0, 25)
						):Play()
					end
				)
	
	
					local LabelNameSliderxd = Instance.new("TextLabel")
	
					LabelNameSliderxd.Parent = SliderFrame
					LabelNameSliderxd.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
					LabelNameSliderxd.BackgroundTransparency = 1
					LabelNameSliderxd.BorderSizePixel = 0
					LabelNameSliderxd.Position = UDim2.new(0.35, 0, 0.2, 0)
					LabelNameSliderxd.AnchorPoint = Vector2.new(0.5, 0.5)
					LabelNameSliderxd.Size = UDim2.new(0, 120, 0, 20)
					LabelNameSliderxd.Font = Enum.Font.GothamBold
					LabelNameSliderxd.Text = tostring(text)
					LabelNameSliderxd.TextColor3 = Color3.fromRGB(255, 255, 255)
					LabelNameSliderxd.TextSize = 11.000
					LabelNameSliderxd.TextXAlignment = Enum.TextXAlignment.Left
	
	
					local ShowValueFarm = Instance.new("Frame")
	
					ShowValueFarm.Name = "ShowValueFarm"
					ShowValueFarm.Parent = SliderFrame
					ShowValueFarm.BackgroundColor3 = Color3.fromRGB(45, 45, 45)
					ShowValueFarm.Position = UDim2.new(0.0833333358, 0, 0.235135213, 0)
					ShowValueFarm.Size = UDim2.new(0, 75, 0, 15)
					ShowValueFarm.BackgroundTransparency = 0
					ShowValueFarm.BorderSizePixel = 0
					ShowValueFarm.AnchorPoint = Vector2.new(0.5, 0.5)
					ShowValueFarm.Position = UDim2.new(0.8, 0, 0.2, 0)
					ShowValueFarm.ClipsDescendants = false
	
					local CustomValue = Instance.new("TextBox")
	
					CustomValue.Parent = ShowValueFarm
					CustomValue.BackgroundColor3 = Color3.fromRGB(45,45, 45)
					CustomValue.BorderSizePixel = 0
					CustomValue.ClipsDescendants = true
					CustomValue.AnchorPoint = Vector2.new(0.5, 0.5)
					CustomValue.Position = UDim2.new(0.5, 0, 0.5, 0)
					CustomValue.Size = UDim2.new(0, 158, 0, 26)
					CustomValue.Font = Enum.Font.GothamSemibold
					CustomValue.PlaceholderColor3 = Color3.fromRGB(222, 222, 222)
					CustomValue.PlaceholderText =  ""
					if floor == true then
						CustomValue.Text =  tostring(de and string.format("%.1f",(de / max) * (max - min) + min) or 0)
					else
						CustomValue.Text =  tostring(de and math.floor( (de / max) * (max - min) + min) or 0)
					end
					CustomValue.TextColor3 = Color3.fromRGB(255, 255, 255)
					CustomValue.TextSize = 8.000
					CustomValue.BackgroundTransparency = 1
	
					local ValueFrame = Instance.new("Frame")
	
					ValueFrame.Name = "ValueFrame"
					ValueFrame.Parent = SliderFrame
					ValueFrame.BackgroundColor3 = Color3.fromRGB(45, 45, 45)
					ValueFrame.Position = UDim2.new(0.0833333358, 0, 0.235135213, 0)
					ValueFrame.Size = UDim2.new(0, 140, 0, 5)
					ValueFrame.BackgroundTransparency = 0
					ValueFrame.BorderSizePixel = 0
					ValueFrame.AnchorPoint = Vector2.new(0.5, 0.5)
					ValueFrame.Position = UDim2.new(0.4, 0, 0.8, 0)
					ValueFrame.ClipsDescendants = false
	
	
					local PartValue = Instance.new("Frame")
	
					PartValue.Name = "PartValue"
					PartValue.Parent = ValueFrame
					PartValue.BackgroundColor3 = Color3.fromRGB(222, 222, 222)
					PartValue.Position = UDim2.new(0.0833333358, 0, 0.235135213, 0)
					PartValue.Size = UDim2.new(0, 140, 0, 5)
					PartValue.BackgroundTransparency = 1
					PartValue.BorderSizePixel = 0
					PartValue.AnchorPoint = Vector2.new(0.5, 0.5)
					PartValue.Position = UDim2.new(0.5, 0, 0.5, 0)
					PartValue.ClipsDescendants = false
	
					local MainValue = Instance.new("Frame")
	
					MainValue.Name = "MainValue"
					MainValue.Parent = PartValue
					MainValue.BackgroundColor3 = _G.ColorMethod
					MainValue.Size = UDim2.new((de or 0) / max, 0, 0, 5)
					MainValue.BackgroundTransparency = 0
					MainValue.BorderSizePixel = 0
					-- MainValue.AnchorPoint = Vector2.new(0.5, 0.5)
					MainValue.Position = UDim2.new(0., 0, 0.0, 0)
					MainValue.ClipsDescendants = false
	
					local Conner_S1 = Instance.new("UICorner")
	
					Conner_S1.CornerRadius = UDim.new(0, 8)
					Conner_S1.Name = ""
					Conner_S1.Parent = MainValue
	
					local Conner_S2 = Instance.new("UICorner")
	
					Conner_S2.CornerRadius = UDim.new(0, 8)
					Conner_S2.Name = ""
					Conner_S2.Parent = ValueFrame
	
					local ConneValue = Instance.new("Frame")
	
					ConneValue.Name = "ConneValue"
					ConneValue.Parent = PartValue
					ConneValue.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
					ConneValue.Size = UDim2.new(0, 13, 0,13)
					ConneValue.BackgroundTransparency = 0
					ConneValue.BorderSizePixel = 0
					ConneValue.AnchorPoint = Vector2.new(0.5, 0.5)
					ConneValue.Position = UDim2.new((de or 0)/max, 0.5, 0.3,0.5, 0)
					ConneValue.ClipsDescendants = false
	
	
					local Conner_Conne = Instance.new("UICorner")
	
					Conner_Conne.CornerRadius = UDim.new(0, 300)
					Conner_Conne.Name = ""
					Conner_Conne.Parent = ConneValue
	
					local Addvalue = Instance.new("ImageButton")
	
					Addvalue.Name = "Imatog"
					Addvalue.Parent = SliderFrame
					Addvalue.BackgroundTransparency = 1.000
					Addvalue.BorderSizePixel = 0
					Addvalue.Position = UDim2.new(0.85, 0, 0.35, 0)
					Addvalue.Size = UDim2.new(0, 15, 0, 15)
					Addvalue.Image = "http://www.roblox.com/asset/?id=6035067836"
					Addvalue.ImageColor3 =  _G.ColorMethod
	
					local Deletevalue = Instance.new("ImageButton")
	
					Deletevalue.Name = "Imatog"
					Deletevalue.Parent = SliderFrame
					Deletevalue.BackgroundTransparency = 1.000
					Deletevalue.BorderSizePixel = 0
					Deletevalue.Position = UDim2.new(0.7, 0, 0.35, 0)
					Deletevalue.Size = UDim2.new(0, 15, 0, 15)
					Deletevalue.Image = "http://www.roblox.com/asset/?id=6035047377"
					Deletevalue.ImageColor3 =  _G.ColorMethod
	
	
					local TextButton_2_Toggle = Instance.new("TextButton")
	
					TextButton_2_Toggle.Parent = ValueFrame
					TextButton_2_Toggle.BackgroundColor3 = Color3.fromRGB(155, 155, 155)
			--        TextButton_2_Toggle.BorderColor3 = _G.ColorMethod
					TextButton_2_Toggle.BorderSizePixel = 0
					TextButton_2_Toggle.AnchorPoint = Vector2.new(0.5, 0.5)
					TextButton_2_Toggle.Position = UDim2.new(1.25, 0, 0.4, 0)
					TextButton_2_Toggle.Size = UDim2.new(0, 30, 0, 13)
					TextButton_2_Toggle.Font = Enum.Font.SourceSans
					TextButton_2_Toggle.Text = " "
					TextButton_2_Toggle.TextColor3 = Color3.fromRGB(0, 0, 0)
					TextButton_2_Toggle.TextSize = 12.000
					TextButton_2_Toggle.AutoButtonColor = false
	
					local TextButton_Pageframe_Uiconner = Instance.new("UICorner")
	
					TextButton_Pageframe_Uiconner.CornerRadius = UDim.new(0, 30)
					TextButton_Pageframe_Uiconner.Name = ""
					TextButton_Pageframe_Uiconner.Parent = TextButton_2_Toggle
	
					local TextButton_3_Toggle = Instance.new("TextButton")
	
					TextButton_3_Toggle.Parent = TextButton_2_Toggle
					TextButton_3_Toggle.BackgroundColor3 = Color3.fromRGB(255, 255,255)
			--        TextButton_3_Toggle.BorderColor3 = _G.ColorMethod
					TextButton_3_Toggle.BorderSizePixel = 0
					TextButton_3_Toggle.AnchorPoint = Vector2.new(0.5, 0.5)
					TextButton_3_Toggle.Position = UDim2.new(0.1, 0, 0.5, 0)
					TextButton_3_Toggle.Size = UDim2.new(0, 19, 0, 19)
					TextButton_3_Toggle.Font = Enum.Font.SourceSans
					TextButton_3_Toggle.Text = " "
					TextButton_3_Toggle.TextColor3 = Color3.fromRGB(0, 0, 0)
					TextButton_3_Toggle.TextSize = 12.000
					TextButton_3_Toggle.AutoButtonColor = false
	
					local TextButton_Pageframe_Uiconner2 = Instance.new("UICorner")
	
					TextButton_Pageframe_Uiconner2.CornerRadius = UDim.new(0, 30)
					TextButton_Pageframe_Uiconner2.Name = ""
					TextButton_Pageframe_Uiconner2.Parent = TextButton_3_Toggle
	
					local TextButton_4_Toggle = Instance.new("TextButton")
	
					TextButton_4_Toggle.Parent = TextButton_3_Toggle
					TextButton_4_Toggle.BackgroundColor3 = Color3.fromRGB(155, 155,155)
			--        TextButton_3_Toggle.BorderColor3 = _G.ColorMethod
					TextButton_4_Toggle.BorderSizePixel = 0
					TextButton_4_Toggle.AnchorPoint = Vector2.new(0.5, 0.5)
					TextButton_4_Toggle.Position = UDim2.new(0.5, 0, 0.5, 0)
					TextButton_4_Toggle.Size = UDim2.new(0, 27, 0, 27-2)
					TextButton_4_Toggle.Font = Enum.Font.SourceSans
					TextButton_4_Toggle.Text = " "
					TextButton_4_Toggle.TextColor3 = Color3.fromRGB(0, 0, 0)
					TextButton_4_Toggle.TextSize = 12.000
					TextButton_4_Toggle.AutoButtonColor = false
					TextButton_4_Toggle.BackgroundTransparency = 1
					TextButton_4_Toggle.Visible = true
	
					local TextButton_Pageframe_Uiconner4 = Instance.new("UICorner")
	
					TextButton_Pageframe_Uiconner4.CornerRadius = UDim.new(0, 30)
					TextButton_Pageframe_Uiconner4.Name = ""
					TextButton_Pageframe_Uiconner4.Parent = TextButton_4_Toggle
	
	
					local TextButton_Toggle = Instance.new("TextButton")
	
					TextButton_Toggle.Parent = ValueFrame
					TextButton_Toggle.BackgroundTransparency =1
					TextButton_Toggle.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
					TextButton_Toggle.BorderSizePixel = 0
					TextButton_Toggle.Size = UDim2.new(0, 50, 0, 20)
					TextButton_Toggle.AutoButtonColor = false
					TextButton_Toggle.Font = Enum.Font.SourceSans
					TextButton_Toggle.Text = " "
					TextButton_Toggle.TextColor3 = Color3.fromRGB(0, 0, 0)
					TextButton_Toggle.TextSize = 12.000
					TextButton_Toggle.AnchorPoint = Vector2.new(0.5, 0.5)
					TextButton_Toggle.Position = UDim2.new(1.25, 0, 0.4, 0)
	
	
	
				-- local value = de
				local check2 = {toogle2 = false;}
					local function move(input)
						local pos =
							UDim2.new(
								math.clamp((input.Position.X - ValueFrame.AbsolutePosition.X) / ValueFrame.AbsoluteSize.X, 0, 1),
								0,
								0.3,
								0
							)
						local pos1 =
							UDim2.new(
								math.clamp((input.Position.X - ValueFrame.AbsolutePosition.X) / ValueFrame.AbsoluteSize.X, 0, 1),
								0,
								0,
								5
							)
	
							MainValue:TweenSize(pos1, "Out", "Sine", 0.2, true)
	
							ConneValue:TweenPosition(pos, "Out", "Sine", 0.2, true)
							if floor == true then
								local value = string.format("%.1f",((pos.X.Scale * max) / max) * (max - min) + min)
								CustomValue.Text = tostring(value)
							--   callback[2] = value
							callback({
								["s"] = value;
								["t"] = check2.toogle2
							})
							--callback({value,check2.toogle2})
								--callback(value)
							else
								local value = math.floor(((pos.X.Scale * max) / max) * (max - min) + min)
								CustomValue.Text = tostring(value)
								callback({
									["s"] = value;
									["t"] = check2.toogle2
								})
						--       callback({value,check2.toogle2})
	
							end
	
	
	
						end
	
						local dragging = false
						ConneValue.InputBegan:Connect(
							function(input)
								if input.UserInputType == Enum.UserInputType.MouseButton1 then
									dragging = true
	
								end
							end
						)
						ConneValue.InputEnded:Connect(
							function(input)
								if input.UserInputType == Enum.UserInputType.MouseButton1 then
									dragging = false
	
								end
							end
						)
						SliderFrame.InputBegan:Connect(
							function(input)
								if input.UserInputType == Enum.UserInputType.MouseButton1 then
									dragging = true
	
								end
							end
						)
						SliderFrame.InputEnded:Connect(
							function(input)
								if input.UserInputType == Enum.UserInputType.MouseButton1 then
									dragging = false
	
								end
							end
						)
	
	
						ValueFrame.InputBegan:Connect(
							function(input)
								if input.UserInputType == Enum.UserInputType.MouseButton1 then
									dragging = true
	
								end
							end
						)
						ValueFrame.InputEnded:Connect(
							function(input)
								if input.UserInputType == Enum.UserInputType.MouseButton1 then
									dragging = false
	
								end
							end
						)
	
						game:GetService("UserInputService").InputChanged:Connect(
							function(input)
								if dragging and input.UserInputType == Enum.UserInputType.MouseMovement then
									move(input)
								end
							end
							)
	
							CustomValue.FocusLost:Connect(function()
								if CustomValue.Text == "" then
									CustomValue.Text  = de
								end
								if  tonumber(CustomValue.Text) > max then
									CustomValue.Text  = max
								end
								if  tonumber(CustomValue.Text) <= min then
									CustomValue.Text  = min
								end
								MainValue:TweenSize(UDim2.new((CustomValue.Text or 0) / max, 0, 0, 5), "Out", "Sine", 0.2, true)
								ConneValue:TweenPosition(UDim2.new((CustomValue.Text or 0)/max, 0,0, 0) , "Out", "Sine", 0.2, true)
								if floor == true then
									CustomValue.Text = tostring(CustomValue.Text and string.format("%.1f",(CustomValue.Text / max) * (max - min) + min) )
								else
									CustomValue.Text = tostring(CustomValue.Text and math.floor( (CustomValue.Text / max) * (max - min) + min) )
								end
								callback({
									["s"] =  CustomValue.Text;
									["t"] = check2.toogle2;
								})
						--       callback({ tonumber(CustomValue.Text),check2.toogle2})
						--  pcall(callback, CustomValue.Text)
							end)
	
	
							Addvalue.MouseButton1Click:Connect(function ()
								if CustomValue.Text == "" then
									CustomValue.Text  = de
								end
								pcall(function()
									CustomValue.Text  = CustomValue.Text  - tonumber(lol)
								end)
								if  tonumber(CustomValue.Text) > max then
									CustomValue.Text  = max
								end
								if  tonumber(CustomValue.Text) < min then
									CustomValue.Text  = min
								end
								MainValue:TweenSize(UDim2.new((CustomValue.Text  or 0  ) / max, 0, 0, 5), "Out", "Sine", 0.2, true)
								ConneValue:TweenPosition(UDim2.new((CustomValue.Text or 0)/max, 0,0.5, 0) , "Out", "Sine", 0.2, true)
								if floor == true then
									CustomValue.Text = tostring(CustomValue.Text and string.format("%.1f",(CustomValue.Text / max) * (max - min) + min) )
								else
									CustomValue.Text = tostring(CustomValue.Text and math.floor( (CustomValue.Text / max) * (max - min) + min) )
								end
								callback({
									["s"] =  CustomValue.Text;
									["t"] = check2.toogle2
								})
							--   callback({ tonumber(CustomValue.Text),check2.toogle2})
							--  pcall(callback, CustomValue.Text)
							end)
	
							Deletevalue.MouseButton1Click:Connect(function ()
								if CustomValue.Text == "" then
									CustomValue.Text  = de
								end
								pcall(function()
									CustomValue.Text  = CustomValue.Text  + tonumber(lol)
								end)
								if  tonumber(CustomValue.Text) > max then
									CustomValue.Text  = max
								end
								if  tonumber(CustomValue.Text) < min then
									CustomValue.Text  = min
								end
								MainValue:TweenSize(UDim2.new((CustomValue.Text  or 0  ) / max, 0, 0, 5), "Out", "Sine", 0.2, true)
								ConneValue:TweenPosition(UDim2.new((CustomValue.Text or 0)/max, 0,0.5, 0) , "Out", "Sine", 0.2, true)
								if floor == true then
									CustomValue.Text = tostring(CustomValue.Text and string.format("%.1f",(CustomValue.Text / max) * (max - min) + min) )
								else
									CustomValue.Text = tostring(CustomValue.Text and math.floor( (CustomValue.Text / max) * (max - min) + min) )
								end
								callback({
									["s"] =  CustomValue.Text;
									["t"] = check2.toogle2;
								})
					--callback({ tonumber(CustomValue.Text),check2.toogle2})
							--  pcall(callback, CustomValue.Text)
							end)
	
	
	
	
					---
							TextButton_Toggle.MouseEnter:Connect(function()
								TweenService:Create(
									TextButton_4_Toggle,
									TweenInfo.new(0.2, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
									{BackgroundTransparency = 0.6} -- UDim2.new(0, 128, 0, 25)
								):Play()
							end
						)
	
						TextButton_Toggle.MouseLeave:Connect(function()
								TweenService:Create(
									TextButton_4_Toggle,
									TweenInfo.new(0.2, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
									{BackgroundTransparency = 1} -- UDim2.new(0, 128, 0, 25)
								):Play()
							end
						)
	
	
	
					TextButton_Toggle.MouseButton1Click:Connect(function()
						if check2.toogle2 == false   then
							TweenService:Create(
								TextButton_4_Toggle,
								TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
								{BackgroundColor3 =  _G.ColorMethod} -- UDim2.new(0, 128, 0, 25)
							):Play()
							TweenService:Create(
								TextButton_3_Toggle,
								TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
								{BackgroundColor3 =  _G.ColorMethod} -- UDim2.new(0, 128, 0, 25)
							):Play()
							TweenService:Create(
								TextButton_2_Toggle,
								TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
								{BackgroundColor3 =  Color3.fromRGB(153, 0, 102)} -- UDim2.new(0, 128, 0, 25)
							):Play()
							TextButton_3_Toggle:TweenSizeAndPosition(UDim2.new(0, 19, 0, 19), UDim2.new(1, 0, 0.5, 0), "Out", "Quad", 0.3, true)
						else
							TweenService:Create(
								TextButton_4_Toggle,
								TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
								{BackgroundColor3 =  Color3.fromRGB(155, 155, 155)} -- UDim2.new(0, 128, 0, 25)
							):Play()
							TweenService:Create(
								TextButton_3_Toggle,
								TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
								{BackgroundColor3 =  Color3.fromRGB(255, 255, 255)} -- UDim2.new(0, 128, 0, 25)
							):Play()
							TweenService:Create(
								TextButton_2_Toggle,
								TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
								{BackgroundColor3 =  Color3.fromRGB(155, 155, 155)} -- UDim2.new(0, 128, 0, 25)
							):Play()
							TextButton_3_Toggle:TweenSizeAndPosition(UDim2.new(0, 19, 0, 19), UDim2.new(0.1, 0, 0.5, 0), "Out", "Quad", 0.3, true)
						end
							check2.toogle2 = not check2.toogle2
							callback({
								["t"] = check2.toogle2;
	
							})
						--   callback({value,check2.toogle2})
							--callback(check2.toogle2)
					end
				)
	
					if tog == true then
						TweenService:Create(
							TextButton_4_Toggle,
							TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{BackgroundColor3 =  _G.ColorMethod} -- UDim2.new(0, 128, 0, 25)
						):Play()
						TweenService:Create(
							TextButton_3_Toggle,
							TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{BackgroundColor3 =  _G.ColorMethod} -- UDim2.new(0, 128, 0, 25)
						):Play()
						TweenService:Create(
							TextButton_2_Toggle,
							TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{BackgroundColor3 =  Color3.fromRGB(153, 0, 102)} -- UDim2.new(0, 128, 0, 25)
						):Play()
						TextButton_3_Toggle:TweenSizeAndPosition(UDim2.new(0, 19, 0, 19), UDim2.new(1, 0, 0.5, 0), "Out", "Quad", 0.3, true)
						check2.toogle2 = true
						callback({
							["t"] = check2.toogle2;
						})
				--        callback({value,check2.toogle2})
					--  callback(check2.toogle2)
					end
	
	
				else
					tog = nil
					local SliderFrame = Instance.new("Frame")
	
					SliderFrame.Name = "SliderFrame"
					SliderFrame.Parent = ScrollingFrame_Pageframe
					SliderFrame.BackgroundColor3 =  Color3.fromRGB(28, 28, 28)-- _G.ColorMethod
					SliderFrame.BorderSizePixel = 0
					SliderFrame.Position = UDim2.new(0.5, 0, 0.5, 0)
					SliderFrame.AnchorPoint = Vector2.new(0.5, 0.5)
					SliderFrame.Size = UDim2.new(0, 213, 0, 75) -- UDim2.new(0, 213, 0, 35)
					SliderFrame.BackgroundTransparency  = 0
					SliderFrame.ClipsDescendants = true
	
					local SliderFrameConner = Instance.new("UICorner")
	
					SliderFrameConner.CornerRadius = UDim.new(0, 4)
					SliderFrameConner.Name = ""
					SliderFrameConner.Parent = SliderFrame
	
					local SliderFrameStroke = Instance.new("UIStroke")
	
					SliderFrameStroke.Thickness = 1
					SliderFrameStroke.Name = ""
					SliderFrameStroke.Parent = SliderFrame
					SliderFrameStroke.LineJoinMode = Enum.LineJoinMode.Round
					SliderFrameStroke.Color = _G.ColorMethod
					SliderFrameStroke.Transparency = 0.7
	
	
	
					SliderFrame.MouseEnter:Connect(function()
						TweenService:Create(
							SliderFrameStroke,
							TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{Transparency = 0} -- UDim2.new(0, 128, 0, 25)
						):Play()
					end
				)
	
					SliderFrame.MouseLeave:Connect(function()
						TweenService:Create(
							SliderFrameStroke,
							TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{Transparency = 0.7} -- UDim2.new(0, 128, 0, 25)
						):Play()
					end
				)
	
					local LabelNameSliderxd = Instance.new("TextLabel")
	
					LabelNameSliderxd.Parent = SliderFrame
					LabelNameSliderxd.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
					LabelNameSliderxd.BackgroundTransparency = 1
					LabelNameSliderxd.BorderSizePixel = 0
					LabelNameSliderxd.Position = UDim2.new(0.35, 0, 0.2, 0)
					LabelNameSliderxd.AnchorPoint = Vector2.new(0.5, 0.5)
					LabelNameSliderxd.Size = UDim2.new(0, 120, 0, 20)
					LabelNameSliderxd.Font = Enum.Font.GothamBold
					LabelNameSliderxd.Text = tostring(text)
					LabelNameSliderxd.TextColor3 = Color3.fromRGB(255, 255, 255)
					LabelNameSliderxd.TextSize = 11.000
					LabelNameSliderxd.TextXAlignment = Enum.TextXAlignment.Left
	
	
					local ShowValueFarm = Instance.new("Frame")
	
					ShowValueFarm.Name = "ShowValueFarm"
					ShowValueFarm.Parent = SliderFrame
					ShowValueFarm.BackgroundColor3 = Color3.fromRGB(45, 45, 45)
					ShowValueFarm.Position = UDim2.new(0.0833333358, 0, 0.235135213, 0)
					ShowValueFarm.Size = UDim2.new(0, 75, 0, 15)
					ShowValueFarm.BackgroundTransparency = 0
					ShowValueFarm.BorderSizePixel = 0
					ShowValueFarm.AnchorPoint = Vector2.new(0.5, 0.5)
					ShowValueFarm.Position = UDim2.new(0.8, 0, 0.2, 0)
					ShowValueFarm.ClipsDescendants = false
	
					local CustomValue = Instance.new("TextBox")
	
					CustomValue.Parent = ShowValueFarm
					CustomValue.BackgroundColor3 = Color3.fromRGB(45,45, 45)
					CustomValue.BorderSizePixel = 0
					CustomValue.ClipsDescendants = true
					CustomValue.AnchorPoint = Vector2.new(0.5, 0.5)
					CustomValue.Position = UDim2.new(0.5, 0, 0.5, 0)
					CustomValue.Size = UDim2.new(0, 158, 0, 26)
					CustomValue.Font = Enum.Font.GothamSemibold
					CustomValue.PlaceholderColor3 = Color3.fromRGB(222, 222, 222)
					CustomValue.PlaceholderText =  ""
					if floor == true then
						CustomValue.Text =  tostring(de and string.format("%.1f",(de / max) * (max - min) + min) or 0)
					else
						CustomValue.Text =  tostring(de and math.floor( (de / max) * (max - min) + min) or 0)
					end
					CustomValue.TextColor3 = Color3.fromRGB(255, 255, 255)
					CustomValue.TextSize = 8.000
					CustomValue.BackgroundTransparency = 1
	
					local ValueFrame = Instance.new("Frame")
	
					ValueFrame.Name = "ValueFrame"
					ValueFrame.Parent = SliderFrame
					ValueFrame.BackgroundColor3 = Color3.fromRGB(45, 45, 45)
					ValueFrame.Position = UDim2.new(0.0833333358, 0, 0.235135213, 0)
					ValueFrame.Size = UDim2.new(0, 190, 0, 5)
					ValueFrame.BackgroundTransparency = 0
					ValueFrame.BorderSizePixel = 0
					ValueFrame.AnchorPoint = Vector2.new(0.5, 0.5)
					ValueFrame.Position = UDim2.new(0.5, 0, 0.8, 0)
					ValueFrame.ClipsDescendants = false
	
	
					local PartValue = Instance.new("Frame")
	
					PartValue.Name = "PartValue"
					PartValue.Parent = ValueFrame
					PartValue.BackgroundColor3 = Color3.fromRGB(222, 222, 222)
					PartValue.Position = UDim2.new(0.0833333358, 0, 0.235135213, 0)
					PartValue.Size = UDim2.new(0, 190, 0, 5)
					PartValue.BackgroundTransparency = 1
					PartValue.BorderSizePixel = 0
					PartValue.AnchorPoint = Vector2.new(0.5, 0.5)
					PartValue.Position = UDim2.new(0.5, 0, 0.5, 0)
					PartValue.ClipsDescendants = false
	
					local MainValue = Instance.new("Frame")
	
					MainValue.Name = "MainValue"
					MainValue.Parent = PartValue
					MainValue.BackgroundColor3 = _G.ColorMethod
					MainValue.Size = UDim2.new((de or 0) / max, 0, 0, 5)
					MainValue.BackgroundTransparency = 0
					MainValue.BorderSizePixel = 0
					-- MainValue.AnchorPoint = Vector2.new(0.5, 0.5)
					MainValue.Position = UDim2.new(0., 0, 0.0, 0)
					MainValue.ClipsDescendants = false
	
					local Conner_S1 = Instance.new("UICorner")
	
					Conner_S1.CornerRadius = UDim.new(0, 8)
					Conner_S1.Name = ""
					Conner_S1.Parent = MainValue
	
					local Conner_S2 = Instance.new("UICorner")
	
					Conner_S2.CornerRadius = UDim.new(0, 8)
					Conner_S2.Name = ""
					Conner_S2.Parent = ValueFrame
	
					local ConneValue = Instance.new("Frame")
	
					ConneValue.Name = "ConneValue"
					ConneValue.Parent = PartValue
					ConneValue.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
					ConneValue.Size = UDim2.new(0, 13, 0,13)
					ConneValue.BackgroundTransparency = 0
					ConneValue.BorderSizePixel = 0
					ConneValue.AnchorPoint = Vector2.new(0.5, 0.5)
					ConneValue.Position = UDim2.new((de or 0)/max, 0.5, 0.3,0.5, 0)
					ConneValue.ClipsDescendants = false
	
	
					local Conner_Conne = Instance.new("UICorner")
	
					Conner_Conne.CornerRadius = UDim.new(0, 300)
					Conner_Conne.Name = ""
					Conner_Conne.Parent = ConneValue
	
					local Addvalue = Instance.new("ImageButton")
	
					Addvalue.Name = "Imatog"
					Addvalue.Parent = SliderFrame
					Addvalue.BackgroundTransparency = 1.000
					Addvalue.BorderSizePixel = 0
					Addvalue.Position = UDim2.new(0.85, 0, 0.35, 0)
					Addvalue.Size = UDim2.new(0, 15, 0, 15)
					Addvalue.Image = "http://www.roblox.com/asset/?id=6035067836"
					Addvalue.ImageColor3 =  _G.ColorMethod
	
					local Deletevalue = Instance.new("ImageButton")
	
					Deletevalue.Name = "Imatog"
					Deletevalue.Parent = SliderFrame
					Deletevalue.BackgroundTransparency = 1.000
					Deletevalue.BorderSizePixel = 0
					Deletevalue.Position = UDim2.new(0.7, 0, 0.35, 0)
					Deletevalue.Size = UDim2.new(0, 15, 0, 15)
					Deletevalue.Image = "http://www.roblox.com/asset/?id=6035047377"
					Deletevalue.ImageColor3 =  _G.ColorMethod
	
					local function move(input)
						local pos =
							UDim2.new(
								math.clamp((input.Position.X - ValueFrame.AbsolutePosition.X) / ValueFrame.AbsoluteSize.X, 0, 1),
								0,
								0.3,
								0
							)
						local pos1 =
							UDim2.new(
								math.clamp((input.Position.X - ValueFrame.AbsolutePosition.X) / ValueFrame.AbsoluteSize.X, 0, 1),
								0,
								0,
								5
							)
	
							MainValue:TweenSize(pos1, "Out", "Sine", 0.2, true)
	
							ConneValue:TweenPosition(pos, "Out", "Sine", 0.2, true)
							if floor == true then
								local value = string.format("%.1f",((pos.X.Scale * max) / max) * (max - min) + min)
								CustomValue.Text = tostring(value)
								callback(value)
							else
								local value = math.floor(((pos.X.Scale * max) / max) * (max - min) + min)
								CustomValue.Text = tostring(value)
								callback(value)
							end
	
	
	
						end
	
						local dragging = false
						ConneValue.InputBegan:Connect(
							function(input)
								if input.UserInputType == Enum.UserInputType.MouseButton1 then
									dragging = true
	
								end
							end
						)
						ConneValue.InputEnded:Connect(
							function(input)
								if input.UserInputType == Enum.UserInputType.MouseButton1 then
									dragging = false
	
								end
							end
						)
						SliderFrame.InputBegan:Connect(
							function(input)
								if input.UserInputType == Enum.UserInputType.MouseButton1 then
									dragging = true
	
								end
							end
						)
						SliderFrame.InputEnded:Connect(
							function(input)
								if input.UserInputType == Enum.UserInputType.MouseButton1 then
									dragging = false
	
								end
							end
						)
	
	
						ValueFrame.InputBegan:Connect(
							function(input)
								if input.UserInputType == Enum.UserInputType.MouseButton1 then
									dragging = true
	
								end
							end
						)
						ValueFrame.InputEnded:Connect(
							function(input)
								if input.UserInputType == Enum.UserInputType.MouseButton1 then
									dragging = false
	
								end
							end
						)
	
						game:GetService("UserInputService").InputChanged:Connect(
							function(input)
								if dragging and input.UserInputType == Enum.UserInputType.MouseMovement then
									move(input)
								end
							end
							)
	
							CustomValue.FocusLost:Connect(function()
								if CustomValue.Text == "" then
									CustomValue.Text  = de
								end
								if  tonumber(CustomValue.Text) > max then
									CustomValue.Text  = max
								end
								MainValue:TweenSize(UDim2.new((CustomValue.Text or 0) / max, 0, 0, 5), "Out", "Sine", 0.2, true)
								ConneValue:TweenPosition(UDim2.new((CustomValue.Text or 0)/max, 0,0, 0) , "Out", "Sine", 0.2, true)
								if floor == true then
									CustomValue.Text = tostring(CustomValue.Text and string.format("%.1f",(CustomValue.Text / max) * (max - min) + min) )
								else
									CustomValue.Text = tostring(CustomValue.Text and math.floor( (CustomValue.Text / max) * (max - min) + min) )
								end
								pcall(callback, CustomValue.Text)
							end)
	
	
					Addvalue.MouseButton1Click:Connect(function ()
						if CustomValue.Text == "" then
							CustomValue.Text  = de
						end
						CustomValue.Text  = CustomValue.Text  - tonumber(lol)
						if  tonumber(CustomValue.Text) > max then
							CustomValue.Text  = max
						end
						if  tonumber(CustomValue.Text) < min then
							CustomValue.Text  = min
						end
						MainValue:TweenSize(UDim2.new((CustomValue.Text  or 0  ) / max, 0, 0, 5), "Out", "Sine", 0.2, true)
						ConneValue:TweenPosition(UDim2.new((CustomValue.Text or 0)/max, 0,0.5, 0) , "Out", "Sine", 0.2, true)
						if floor == true then
							CustomValue.Text = tostring(CustomValue.Text and string.format("%.1f",(CustomValue.Text / max) * (max - min) + min) )
						else
							CustomValue.Text = tostring(CustomValue.Text and math.floor( (CustomValue.Text / max) * (max - min) + min) )
						end
						pcall(callback, CustomValue.Text)
					end)
	
					Deletevalue.MouseButton1Click:Connect(function ()
						if CustomValue.Text == "" then
							CustomValue.Text  = de
						end
						CustomValue.Text  = CustomValue.Text  + tonumber(lol)
						if  tonumber(CustomValue.Text) > max then
							CustomValue.Text  = max
						end
						if  tonumber(CustomValue.Text) < min then
							CustomValue.Text  = min
						end
						MainValue:TweenSize(UDim2.new((CustomValue.Text  or 0  ) / max, 0, 0, 5), "Out", "Sine", 0.2, true)
						ConneValue:TweenPosition(UDim2.new((CustomValue.Text or 0)/max, 0,0.5, 0) , "Out", "Sine", 0.2, true)
						if floor == true then
							CustomValue.Text = tostring(CustomValue.Text and string.format("%.1f",(CustomValue.Text / max) * (max - min) + min) )
						else
							CustomValue.Text = tostring(CustomValue.Text and math.floor( (CustomValue.Text / max) * (max - min) + min) )
						end
						pcall(callback, CustomValue.Text)
					end)
	
				end
	
				end
	
				function items:Drop(text,use,option,callback)
	
				if use == false then
					local DropFrame = Instance.new("Frame")
	
					DropFrame.Name = "DropFrame"
					DropFrame.Parent = ScrollingFrame_Pageframe
					DropFrame.BackgroundColor3 =  Color3.fromRGB(23, 23, 23)-- _G.ColorMethod
					DropFrame.BorderSizePixel = 0
					DropFrame.Position = UDim2.new(0.5, 0, 0.5, 0)
					DropFrame.AnchorPoint = Vector2.new(0.5, 0.5)
					DropFrame.Size = UDim2.new(0, 213, 0, 30) -- UDim2.new(0, 213, 0, 35)
					DropFrame.BackgroundTransparency  = 0
					DropFrame.ClipsDescendants = true
	
					local ConnerDropFrame = Instance.new("UICorner")
	
					ConnerDropFrame.CornerRadius = UDim.new(0, 4)
					ConnerDropFrame.Name = ""
					ConnerDropFrame.Parent = DropFrame
	
					local DropFrameStroke = Instance.new("UIStroke")
	
					DropFrameStroke.Thickness = 1
					DropFrameStroke.Name = ""
					DropFrameStroke.Parent = DropFrame
					DropFrameStroke.LineJoinMode = Enum.LineJoinMode.Round
					DropFrameStroke.Color = _G.ColorMethod
					DropFrameStroke.Transparency = 0.7
	
	
	
	
	
					local LabelFrameDrop = Instance.new("TextLabel")
	
					LabelFrameDrop.Parent = DropFrame
					LabelFrameDrop.Name = "LabelFrameDrop"
					LabelFrameDrop.BackgroundColor3 = _G.ColorMethod
					LabelFrameDrop.Position = UDim2.new(0., 0, 0., 0)
					LabelFrameDrop.Size =    UDim2.new(0, 213, 0, 30)
					LabelFrameDrop.Font = Enum.Font.SourceSansSemibold
					LabelFrameDrop.Text = ""
					LabelFrameDrop.TextColor3 = Color3.fromRGB(155, 155, 155)
					LabelFrameDrop.TextSize = 14.000
				--   LabelFrameDrop.AnchorPoint = Vector2.new(0.5, 0.5)
					LabelFrameDrop.BackgroundTransparency = 1
					LabelFrameDrop.TextXAlignment = Enum.TextXAlignment.Left
	
	
					local TextLabel_TapDrop = Instance.new("TextLabel")
	
					TextLabel_TapDrop.Parent = LabelFrameDrop
					TextLabel_TapDrop.Name = "TextLabel_TapDrop"
					TextLabel_TapDrop.BackgroundColor3 = _G.ColorMethod
					TextLabel_TapDrop.Position = UDim2.new(0.04, 0, 0.14, 0)
					TextLabel_TapDrop.Size =    UDim2.new(0, 140, 0, 20)
					TextLabel_TapDrop.Font = Enum.Font.SourceSansSemibold
					TextLabel_TapDrop.Text = tostring(text).." :"
					TextLabel_TapDrop.TextColor3 = Color3.fromRGB(155, 155, 155)
					TextLabel_TapDrop.TextSize = 14.000
			--     TextLabel_TapDrop.AnchorPoint = Vector2.new(0.5, 0.5)
					TextLabel_TapDrop.BackgroundTransparency = 1
					TextLabel_TapDrop.TextXAlignment = Enum.TextXAlignment.Left
	
	
					local DropArbt_listimage = Instance.new("ImageButton")
	
					DropArbt_listimage.Parent = LabelFrameDrop
					DropArbt_listimage.BackgroundTransparency = 1.000
					DropArbt_listimage.AnchorPoint = Vector2.new(0.5, 0.5)
					DropArbt_listimage.Position = UDim2.new(0.9, 0, 0.5, 0)
					DropArbt_listimage.BorderSizePixel = 0
					DropArbt_listimage.Size = UDim2.new(0, 25, 0, 25)
					DropArbt_listimage.Image = "http://www.roblox.com/asset/?id=6031091004"
					DropArbt_listimage.ImageColor3 = Color3.fromRGB(155, 155, 155)
	
					local ScolDown = Instance.new("ScrollingFrame")
	
					ScolDown.Name = "ScolDown"
					ScolDown.Position = UDim2.new(0.02, 0, 1., 0)
					ScolDown.Parent = LabelFrameDrop
					ScolDown.Active = true
					ScolDown.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
					ScolDown.BorderSizePixel = 0
					ScolDown.Size = UDim2.new(0, 205, 0, 115)
					ScolDown.ScrollBarThickness = 3
					ScolDown.ClipsDescendants = true
					ScolDown.BackgroundTransparency = 1
					ScolDown.CanvasSize = UDim2.new(0, 0, 0, 2)
	
					local UIListLayoutlist = Instance.new("UIListLayout")
					local UIPaddinglist = Instance.new("UIPadding")
	
					UIListLayoutlist.Name = "UIListLayoutlist"
					UIListLayoutlist.Parent = ScolDown
					UIListLayoutlist.SortOrder = Enum.SortOrder.LayoutOrder
					UIListLayoutlist.Padding = UDim.new(0, 5)
	
					UIPaddinglist.Name = "UIPaddinglist"
					UIPaddinglist.Parent = ScolDown
					UIPaddinglist.PaddingTop = UDim.new(0, 5)
					UIPaddinglist.PaddingLeft = UDim.new(0, 12)
	
					local ButtonDrop = Instance.new("TextButton")
	
					ButtonDrop.Parent = DropFrame
					ButtonDrop.Name = "ButtonDrop"
					ButtonDrop.BackgroundColor3 = _G.ColorMethod
					ButtonDrop.Size = UDim2.new(0, 213, 0, 30)
					ButtonDrop.Font = Enum.Font.SourceSansSemibold
					ButtonDrop.Text = ""
					ButtonDrop.TextColor3 = Color3.fromRGB(155, 155, 155)
					ButtonDrop.TextSize = 13.000
				--   ButtonDrop.AnchorPoint = Vector2.new(0.5, 0.5)
					ButtonDrop.Position = UDim2.new(0., 0, 0., 0)
					ButtonDrop.TextXAlignment = Enum.TextXAlignment.Center
					ButtonDrop.BackgroundTransparency = 1
					ButtonDrop.TextWrapped = true
					ButtonDrop.AutoButtonColor = false
					ButtonDrop.ClipsDescendants = true
	
					local dog = false
	
					local FrameSize = 75
					local cout = 0
					for i , v in pairs(option) do
						cout =cout + 1
						if cout == 1 then
							FrameSize = 75
						elseif cout == 2 then
							FrameSize = 110
						elseif cout >= 3 then
							FrameSize = 150
						end
	
						local ListFrame = Instance.new("Frame")
	
						ListFrame.Name = "ListFrame"
						ListFrame.Parent = ScolDown
						ListFrame.BackgroundColor3 =  Color3.fromRGB(22553, 23, 23)-- _G.ColorMethod
						ListFrame.BorderSizePixel = 0
						ListFrame.Position = UDim2.new(0.5, 0, 0.5, 0)
						ListFrame.AnchorPoint = Vector2.new(0.5, 0.5)
						ListFrame.Size = UDim2.new(0, 180, 0, 30) -- UDim2.new(0, 213, 0, 35)
						ListFrame.BackgroundTransparency  = 1
						ListFrame.ClipsDescendants = true
	
						local TextLabel_TapDro2p = Instance.new("TextLabel")
	
						TextLabel_TapDro2p.Parent = ListFrame
						TextLabel_TapDro2p.Name =  tostring(v).."Dropdown"
						TextLabel_TapDro2p.BackgroundColor3 = _G.ColorMethod
						TextLabel_TapDro2p.Position = UDim2.new(0.5, 0, 0.5, 0)
						TextLabel_TapDro2p.Size =  UDim2.new(0, 180, 0, 30)
						TextLabel_TapDro2p.Font = Enum.Font.SourceSansSemibold
						TextLabel_TapDro2p.Text = tostring(v)
						TextLabel_TapDro2p.TextColor3 = Color3.fromRGB(155, 155, 155)
						TextLabel_TapDro2p.TextSize = 14.000
						TextLabel_TapDro2p.AnchorPoint = Vector2.new(0.5, 0.5)
						TextLabel_TapDro2p.BackgroundTransparency = 1
						TextLabel_TapDro2p.TextXAlignment = Enum.TextXAlignment.Center
	
						local ButtonDrop2 = Instance.new("TextButton")
	
						ButtonDrop2.Parent = ListFrame
						ButtonDrop2.Name = "ButtonDrop2"
						ButtonDrop2.BackgroundColor3 = _G.ColorMethod
						ButtonDrop2.Size = UDim2.new(0, 213, 0, 30)
						ButtonDrop2.Font = Enum.Font.SourceSansSemibold
						ButtonDrop2.Text = ""
						ButtonDrop2.TextColor3 = Color3.fromRGB(155, 155, 155)
						ButtonDrop2.TextSize = 13.000
					--   ButtonDrop2.AnchorPoint = Vector2.new(0.5, 0.5)
						ButtonDrop2.Position = UDim2.new(0., 0, 0., 0)
						ButtonDrop2.TextXAlignment = Enum.TextXAlignment.Center
						ButtonDrop2.BackgroundTransparency = 1
						ButtonDrop2.TextWrapped = true
						ButtonDrop2.AutoButtonColor = false
						ButtonDrop2.ClipsDescendants = true
	
						ButtonDrop2.MouseEnter:Connect(function ()
							TweenService:Create(
								TextLabel_TapDro2p,
								TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
								{TextColor3 = Color3.fromRGB(255, 255, 255)} -- UDim2.new(0, 128, 0, 25)
							):Play()
						end)
	
						ButtonDrop2.MouseLeave:Connect(function ()
							TweenService:Create(
								TextLabel_TapDro2p,
								TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
								{TextColor3 = Color3.fromRGB(155, 155, 155)} -- UDim2.new(0, 128, 0, 25)
							):Play()
						end)
	
						ButtonDrop2.MouseButton1Click:Connect(function()
							TweenService:Create(
								DropFrame,
								TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
								{Size = UDim2.new(0, 213, 0, 30)} -- UDim2.new(0, 128, 0, 25)
							):Play()
							TweenService:Create(
								DropArbt_listimage,
								TweenInfo.new(0.3, Enum.EasingStyle.Linear, Enum.EasingDirection.Out),
								{Rotation = 0}
							):Play()
							TextLabel_TapDrop.Text =  text.." : "..tostring(v)
							callback(v)
							dog = not dog
						end
					)
	
	
						ScolDown.CanvasSize = UDim2.new(0,0,0,UIListLayoutlist.AbsoluteContentSize.Y + 10  )
					end
	
	
					DropFrame.MouseEnter:Connect(function()
						TweenService:Create(
							DropFrameStroke,
							TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{Transparency = 0} -- UDim2.new(0, 128, 0, 25)
						):Play()
						TweenService:Create(
							TextLabel_TapDrop,
							TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{TextColor3 = Color3.fromRGB(255, 255, 255)} -- UDim2.new(0, 128, 0, 25)
						):Play()
						TweenService:Create(
							DropArbt_listimage,
							TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{ImageColor3 = Color3.fromRGB(255, 255, 255)} -- UDim2.new(0, 128, 0, 25)
						):Play()
					end
				)
	
				DropFrame.MouseLeave:Connect(function()
						TweenService:Create(
							DropFrameStroke,
							TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{Transparency = 0.7} -- UDim2.new(0, 128, 0, 25)
						):Play()
						TweenService:Create(
							TextLabel_TapDrop,
							TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{TextColor3 = Color3.fromRGB(155, 155, 155)} -- UDim2.new(0, 128, 0, 25)
						):Play()
						TweenService:Create(
							DropArbt_listimage,
							TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{ImageColor3 = Color3.fromRGB(155, 155, 155)} -- UDim2.new(0, 128, 0, 25)
						):Play()
					end
				)
	
	
				ButtonDrop.MouseButton1Click:Connect(function()
					if dog == false then
						TweenService:Create(
							DropFrame,
							TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{Size = UDim2.new(0, 213, 0, FrameSize)} -- UDim2.new(0, 128, 0, 25)
						):Play()
						TweenService:Create(
							DropArbt_listimage,
							TweenInfo.new(0.3, Enum.EasingStyle.Linear, Enum.EasingDirection.Out),
							{Rotation = -180}
						):Play()
						ScolDown.CanvasSize = UDim2.new(0,0,0,UIListLayoutlist.AbsoluteContentSize.Y + 10  )
					else
						TweenService:Create(
							DropFrame,
							TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{Size = UDim2.new(0, 213, 0, 30)} -- UDim2.new(0, 128, 0, 25)
						):Play()
						TweenService:Create(
							DropArbt_listimage,
							TweenInfo.new(0.3, Enum.EasingStyle.Linear, Enum.EasingDirection.Out),
							{Rotation = 0}
						):Play()
						ScolDown.CanvasSize = UDim2.new(0,0,0,UIListLayoutlist.AbsoluteContentSize.Y + 10  )
					end
					dog = not dog
				end
			)
			ScolDown.CanvasSize = UDim2.new(0,0,0,UIListLayoutlist.AbsoluteContentSize.Y + 10  )
	
				local dropfunc = {}
	
				function dropfunc:Clear()
					TextLabel_TapDrop.Text = tostring(text).." :"
					for i, v in next, ScolDown:GetChildren() do
						if v:IsA("Frame") then
							v:Destroy()
						end
					end
					ScolDown.CanvasSize = UDim2.new(0,0,0,UIListLayoutlist.AbsoluteContentSize.Y + 10  )
				end
	
				function dropfunc:Add(t)
					local ListFrame = Instance.new("Frame")
	
					ListFrame.Name = "ListFrame"
					ListFrame.Parent = ScolDown
					ListFrame.BackgroundColor3 =  Color3.fromRGB(22553, 23, 23)-- _G.ColorMethod
					ListFrame.BorderSizePixel = 0
					ListFrame.Position = UDim2.new(0.5, 0, 0.5, 0)
					ListFrame.AnchorPoint = Vector2.new(0.5, 0.5)
					ListFrame.Size = UDim2.new(0, 180, 0, 30) -- UDim2.new(0, 213, 0, 35)
					ListFrame.BackgroundTransparency  = 1
					ListFrame.ClipsDescendants = true
	
					local TextLabel_TapDro2p = Instance.new("TextLabel")
	
					TextLabel_TapDro2p.Parent = ListFrame
					TextLabel_TapDro2p.Name =  tostring(t).."Dropdown"
					TextLabel_TapDro2p.BackgroundColor3 = _G.ColorMethod
					TextLabel_TapDro2p.Position = UDim2.new(0.5, 0, 0.5, 0)
					TextLabel_TapDro2p.Size =  UDim2.new(0, 180, 0, 30)
					TextLabel_TapDro2p.Font = Enum.Font.SourceSansSemibold
					TextLabel_TapDro2p.Text = tostring(t)
					TextLabel_TapDro2p.TextColor3 = Color3.fromRGB(155, 155, 155)
					TextLabel_TapDro2p.TextSize = 14.000
					TextLabel_TapDro2p.AnchorPoint = Vector2.new(0.5, 0.5)
					TextLabel_TapDro2p.BackgroundTransparency = 1
					TextLabel_TapDro2p.TextXAlignment = Enum.TextXAlignment.Center
	
					local ButtonDrop2 = Instance.new("TextButton")
	
					ButtonDrop2.Parent = ListFrame
					ButtonDrop2.Name = "ButtonDrop2"
					ButtonDrop2.BackgroundColor3 = _G.ColorMethod
					ButtonDrop2.Size = UDim2.new(0, 213, 0, 30)
					ButtonDrop2.Font = Enum.Font.SourceSansSemibold
					ButtonDrop2.Text = ""
					ButtonDrop2.TextColor3 = Color3.fromRGB(155, 155, 155)
					ButtonDrop2.TextSize = 13.000
				--   ButtonDrop2.AnchorPoint = Vector2.new(0.5, 0.5)
					ButtonDrop2.Position = UDim2.new(0., 0, 0., 0)
					ButtonDrop2.TextXAlignment = Enum.TextXAlignment.Center
					ButtonDrop2.BackgroundTransparency = 1
					ButtonDrop2.TextWrapped = true
					ButtonDrop2.AutoButtonColor = false
					ButtonDrop2.ClipsDescendants = true
	
					ButtonDrop2.MouseEnter:Connect(function ()
						TweenService:Create(
							TextLabel_TapDro2p,
							TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{TextColor3 = Color3.fromRGB(255, 255, 255)} -- UDim2.new(0, 128, 0, 25)
						):Play()
					end)
	
					ButtonDrop2.MouseLeave:Connect(function ()
						TweenService:Create(
							TextLabel_TapDro2p,
							TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{TextColor3 = Color3.fromRGB(155, 155, 155)} -- UDim2.new(0, 128, 0, 25)
						):Play()
					end)
	
					ButtonDrop2.MouseButton1Click:Connect(function()
						TweenService:Create(
							DropFrame,
							TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{Size = UDim2.new(0, 213, 0, 30)} -- UDim2.new(0, 128, 0, 25)
						):Play()
						TweenService:Create(
							DropArbt_listimage,
							TweenInfo.new(0.3, Enum.EasingStyle.Linear, Enum.EasingDirection.Out),
							{Rotation = 0}
						):Play()
						TextLabel_TapDrop.Text =  text.." : "..tostring(t)
						callback(t)
						dog = not dog
					end
				)
	
					ScolDown.CanvasSize = UDim2.new(0,0,0,UIListLayoutlist.AbsoluteContentSize.Y + 10  )
				end
				return dropfunc
	
			else
	
				local location = option.location or self.flags
				local flag = not use and option.flag or ""
				local callback = callback or function() end
				local list = option.list or {}
				local default = list.default or list[1].Name
	
				if not use then
					location[flag] = default
				end
	
	
				local DropFrame = Instance.new("Frame")
	
				DropFrame.Name = "DropFrame"
				DropFrame.Parent = ScrollingFrame_Pageframe
				DropFrame.BackgroundColor3 =  Color3.fromRGB(23, 23, 23)-- _G.ColorMethod
				DropFrame.BorderSizePixel = 0
				DropFrame.Position = UDim2.new(0.5, 0, 0.5, 0)
				DropFrame.AnchorPoint = Vector2.new(0.5, 0.5)
				DropFrame.Size = UDim2.new(0, 213, 0, 30) -- UDim2.new(0, 213, 0, 35)
				DropFrame.BackgroundTransparency  = 0
				DropFrame.ClipsDescendants = true
	
				local ConnerDropFrame = Instance.new("UICorner")
	
				ConnerDropFrame.CornerRadius = UDim.new(0, 4)
				ConnerDropFrame.Name = ""
				ConnerDropFrame.Parent = DropFrame
	
				local DropFrameStroke = Instance.new("UIStroke")
	
				DropFrameStroke.Thickness = 1
				DropFrameStroke.Name = ""
				DropFrameStroke.Parent = DropFrame
				DropFrameStroke.LineJoinMode = Enum.LineJoinMode.Round
				DropFrameStroke.Color = _G.ColorMethod
				DropFrameStroke.Transparency = 0.7
	
	
	
	
	
				local LabelFrameDrop = Instance.new("TextLabel")
	
				LabelFrameDrop.Parent = DropFrame
				LabelFrameDrop.Name = "LabelFrameDrop"
				LabelFrameDrop.BackgroundColor3 = _G.ColorMethod
				LabelFrameDrop.Position = UDim2.new(0., 0, 0., 0)
				LabelFrameDrop.Size =    UDim2.new(0, 213, 0, 30)
				LabelFrameDrop.Font = Enum.Font.SourceSansSemibold
				LabelFrameDrop.Text = ""
				LabelFrameDrop.TextColor3 = Color3.fromRGB(155, 155, 155)
				LabelFrameDrop.TextSize = 14.000
			--   LabelFrameDrop.AnchorPoint = Vector2.new(0.5, 0.5)
				LabelFrameDrop.BackgroundTransparency = 1
				LabelFrameDrop.TextXAlignment = Enum.TextXAlignment.Left
	
	
				local TextLabel_TapDrop = Instance.new("TextLabel")
	
				TextLabel_TapDrop.Parent = LabelFrameDrop
				TextLabel_TapDrop.Name = "TextLabel_TapDrop"
				TextLabel_TapDrop.BackgroundColor3 = _G.ColorMethod
				TextLabel_TapDrop.Position = UDim2.new(0.04, 0, 0.14, 0)
				TextLabel_TapDrop.Size =    UDim2.new(0, 140, 0, 20)
				TextLabel_TapDrop.Font = Enum.Font.SourceSansSemibold
				TextLabel_TapDrop.Text = tostring(text).." :"
				TextLabel_TapDrop.TextColor3 = Color3.fromRGB(155, 155, 155)
				TextLabel_TapDrop.TextSize = 14.000
		--     TextLabel_TapDrop.AnchorPoint = Vector2.new(0.5, 0.5)
				TextLabel_TapDrop.BackgroundTransparency = 1
				TextLabel_TapDrop.TextXAlignment = Enum.TextXAlignment.Left
	
	
				local DropArbt_listimage = Instance.new("ImageButton")
	
				DropArbt_listimage.Parent = LabelFrameDrop
				DropArbt_listimage.BackgroundTransparency = 1.000
				DropArbt_listimage.AnchorPoint = Vector2.new(0.5, 0.5)
				DropArbt_listimage.Position = UDim2.new(0.9, 0, 0.5, 0)
				DropArbt_listimage.BorderSizePixel = 0
				DropArbt_listimage.Size = UDim2.new(0, 25, 0, 25)
				DropArbt_listimage.Image = "http://www.roblox.com/asset/?id=6031091004"
				DropArbt_listimage.ImageColor3 = Color3.fromRGB(155, 155, 155)
	
				local ScolDown = Instance.new("ScrollingFrame")
	
				ScolDown.Name = "ScolDown"
				ScolDown.Position = UDim2.new(0.02, 0, 1., 0)
				ScolDown.Parent = LabelFrameDrop
				ScolDown.Active = true
				ScolDown.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
				ScolDown.BorderSizePixel = 0
				ScolDown.Size = UDim2.new(0, 205, 0, 115)
				ScolDown.ScrollBarThickness = 3
				ScolDown.ClipsDescendants = true
				ScolDown.BackgroundTransparency = 1
				ScolDown.CanvasSize = UDim2.new(0, 0, 0, 2)
	
				local UIListLayoutlist = Instance.new("UIListLayout")
				local UIPaddinglist = Instance.new("UIPadding")
	
				UIListLayoutlist.Name = "UIListLayoutlist"
				UIListLayoutlist.Parent = ScolDown
				UIListLayoutlist.SortOrder = Enum.SortOrder.LayoutOrder
				UIListLayoutlist.Padding = UDim.new(0, 5)
	
				UIPaddinglist.Name = "UIPaddinglist"
				UIPaddinglist.Parent = ScolDown
				UIPaddinglist.PaddingTop = UDim.new(0, 5)
				UIPaddinglist.PaddingLeft = UDim.new(0, 12)
	
				local ButtonDrop = Instance.new("TextButton")
	
				ButtonDrop.Parent = DropFrame
				ButtonDrop.Name = "ButtonDrop"
				ButtonDrop.BackgroundColor3 = _G.ColorMethod
				ButtonDrop.Size = UDim2.new(0, 213, 0, 30)
				ButtonDrop.Font = Enum.Font.SourceSansSemibold
				ButtonDrop.Text = ""
				ButtonDrop.TextColor3 = Color3.fromRGB(155, 155, 155)
				ButtonDrop.TextSize = 13.000
			--   ButtonDrop.AnchorPoint = Vector2.new(0.5, 0.5)
				ButtonDrop.Position = UDim2.new(0., 0, 0., 0)
				ButtonDrop.TextXAlignment = Enum.TextXAlignment.Center
				ButtonDrop.BackgroundTransparency = 1
				ButtonDrop.TextWrapped = true
				ButtonDrop.AutoButtonColor = false
				ButtonDrop.ClipsDescendants = true
	
				local dog = false
	
				local FrameSize = 75
				local cout = 0
				for i , v in pairs(list) do
					cout =cout + 1
					if cout == 1 then
						FrameSize = 75
					elseif cout == 2 then
						FrameSize = 110
					elseif cout >= 3 then
						FrameSize = 150
					end
	
					local listtog = Instance.new("Frame")
	
					listtog.Name = "listtog"
					listtog.Parent = ScolDown
					listtog.BackgroundColor3 = Color3.fromRGB(23, 23, 23)
					listtog.BackgroundTransparency =1
					listtog.BorderSizePixel = 0
					listtog.ClipsDescendants = true
					listtog.AnchorPoint = Vector2.new(0.5, 0.5)
					listtog.Position = UDim2.new(0.5, 0, 0.5, 0)
					listtog.Size = UDim2.new(0, 210, 0, 33)
	
	
					local listtextbutton = Instance.new("TextButton")
	
					listtextbutton.Parent = listtog
					listtextbutton.BackgroundTransparency =1
					listtextbutton.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
					listtextbutton.BorderSizePixel = 0
					listtextbutton.Size =  UDim2.new(0, 210, 0, 33)
					listtextbutton.AutoButtonColor = false
					listtextbutton.Font = Enum.Font.SourceSans
					listtextbutton.Text = " "
					listtextbutton.TextColor3 = Color3.fromRGB(0, 0, 0)
					listtextbutton.TextSize = 14.000
	
					local farmtoglist = Instance.new("TextButton")
	
					farmtoglist.Parent = listtextbutton
					farmtoglist.BackgroundColor3 = _G.ColorMethod
					farmtoglist.BorderColor3 = _G.ColorMethod
					farmtoglist.BorderSizePixel = 0
					farmtoglist.AnchorPoint = Vector2.new(0.5, 0.5)
					farmtoglist.Position = UDim2.new(0.1, 0, 0.5, 0)
					farmtoglist.Size = UDim2.new(0, 23, 0, 23)
					farmtoglist.Font = Enum.Font.SourceSans
					farmtoglist.Text = " "
					farmtoglist.TextColor3 = Color3.fromRGB(0, 0, 0)
					farmtoglist.TextSize = 14.000
					farmtoglist.AutoButtonColor = false
	
	
					local farmtoglist2 = Instance.new("TextButton")
	
					farmtoglist2.Parent = farmtoglist
					farmtoglist2.BackgroundColor3 = Color3.fromRGB(32, 32,32)
					farmtoglist2.BorderColor3 = _G.ColorMethod
					farmtoglist2.BorderSizePixel = 0
					farmtoglist2.AnchorPoint = Vector2.new(0.5, 0.5)
					farmtoglist2.Position = UDim2.new(0.5, 0, 0.5, 0)
					farmtoglist2.Size = UDim2.new(0, 21, 0, 21)
					farmtoglist2.Font = Enum.Font.SourceSans
					farmtoglist2.Text = " "
					farmtoglist2.TextColor3 = Color3.fromRGB(0, 0, 0)
					farmtoglist2.TextSize = 14.000
					farmtoglist2.AutoButtonColor = false
	
	
					local listimage = Instance.new("ImageButton")
	
					listimage.Parent = farmtoglist2
					listimage.BackgroundTransparency = 1.000
					listimage.AnchorPoint = Vector2.new(0.5, 0.5)
					listimage.Position = UDim2.new(0.5, 0, 0.5, 0)
					listimage.BorderSizePixel = 0
					listimage.Size = UDim2.new(0, 0, 0, 0)
					listimage.Image = "http://www.roblox.com/asset/?id=5880482965"
	
	
					local textlist = Instance.new("TextLabel")
	
	
					textlist.Parent = listtextbutton
					textlist.Name = "textlist"
					textlist.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
					textlist.BackgroundTransparency = 1.000
					textlist.AnchorPoint = Vector2.new(0.5, 0.5)
					textlist.Position = UDim2.new(0.5, 0, 0.5, 0)
					textlist.BorderSizePixel = 0
					textlist.Size = UDim2.new(0, 91, 0, 25)
					textlist.Font = Enum.Font.GothamSemibold
					textlist.Text = tostring(v.Name)
					textlist.TextColor3 = Color3.fromRGB(255, 255, 255)
					textlist.TextSize = 13.000
	
	
	
					local TextButton_Pageframe_Uiconner2 = Instance.new("UICorner")
	
					TextButton_Pageframe_Uiconner2.CornerRadius = UDim.new(0, 5)
					TextButton_Pageframe_Uiconner2.Name = ""
					TextButton_Pageframe_Uiconner2.Parent = farmtoglist
	
					local TextButton_Pageframe_Uiconner22 = Instance.new("UICorner")
	
					TextButton_Pageframe_Uiconner22.CornerRadius = UDim.new(0, 5)
					TextButton_Pageframe_Uiconner22.Name = ""
					TextButton_Pageframe_Uiconner22.Parent = farmtoglist2
	
	
	
					listtextbutton.MouseButton1Click:Connect(function()
						if not  location[v.flag] then
							listimage:TweenSizeAndPosition(UDim2.new(0, 30, 0, 30), UDim2.new(0.5, 0, 0.5, 0), "In", "Bounce", 0.1, true)
							wait(0.1)
							listimage:TweenSizeAndPosition(UDim2.new(0, 23, 0, 23), UDim2.new(0.5, 0, 0.5, 0), "In", "Bounce", 0.1, true)
						else
							listimage:TweenSizeAndPosition(UDim2.new(0, 30, 0, 30), UDim2.new(0.5, 0, 0.5, 0), "In", "Bounce", 0.1, true)
							wait(0.1)
							listimage:TweenSizeAndPosition(UDim2.new(0, 0, 0, 0), UDim2.new(0.5, 0, 0.5, 0), "In", "Bounce", 0.1, true)
						end
						location[v.flag] = not location[v.flag]
						callback(location[v.flag])
					end
				)
	
				if  location[v.flag] then
					listimage:TweenSizeAndPosition(UDim2.new(0, 30, 0, 30), UDim2.new(0.5, 0, 0.5, 0), "In", "Bounce", 0.1, true)
					wait(0.1)
					listimage:TweenSizeAndPosition(UDim2.new(0, 23, 0, 23), UDim2.new(0.5, 0, 0.5, 0), "In", "Bounce", 0.1, true)
	
					callback(location[v.flag])
				end
	
					ScolDown.CanvasSize = UDim2.new(0,0,0,UIListLayoutlist.AbsoluteContentSize.Y + 10  )
				end
	
	
				DropFrame.MouseEnter:Connect(function()
					TweenService:Create(
						DropFrameStroke,
						TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
						{Transparency = 0} -- UDim2.new(0, 128, 0, 25)
					):Play()
					TweenService:Create(
						TextLabel_TapDrop,
						TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
						{TextColor3 = Color3.fromRGB(255, 255, 255)} -- UDim2.new(0, 128, 0, 25)
					):Play()
					TweenService:Create(
						DropArbt_listimage,
						TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
						{ImageColor3 = Color3.fromRGB(255, 255, 255)} -- UDim2.new(0, 128, 0, 25)
					):Play()
				end
			)
	
			DropFrame.MouseLeave:Connect(function()
					TweenService:Create(
						DropFrameStroke,
						TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
						{Transparency = 0.7} -- UDim2.new(0, 128, 0, 25)
					):Play()
					TweenService:Create(
						TextLabel_TapDrop,
						TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
						{TextColor3 = Color3.fromRGB(155, 155, 155)} -- UDim2.new(0, 128, 0, 25)
					):Play()
					TweenService:Create(
						DropArbt_listimage,
						TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
						{ImageColor3 = Color3.fromRGB(155, 155, 155)} -- UDim2.new(0, 128, 0, 25)
					):Play()
				end
			)
	
	
			ButtonDrop.MouseButton1Click:Connect(function()
				if dog == false then
					TweenService:Create(
						DropFrame,
						TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
						{Size = UDim2.new(0, 213, 0, FrameSize)} -- UDim2.new(0, 128, 0, 25)
					):Play()
					TweenService:Create(
						DropArbt_listimage,
						TweenInfo.new(0.3, Enum.EasingStyle.Linear, Enum.EasingDirection.Out),
						{Rotation = -180}
					):Play()
					ScolDown.CanvasSize = UDim2.new(0,0,0,UIListLayoutlist.AbsoluteContentSize.Y + 10  )
				else
					TweenService:Create(
						DropFrame,
						TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
						{Size = UDim2.new(0, 213, 0, 30)} -- UDim2.new(0, 128, 0, 25)
					):Play()
					TweenService:Create(
						DropArbt_listimage,
						TweenInfo.new(0.3, Enum.EasingStyle.Linear, Enum.EasingDirection.Out),
						{Rotation = 0}
					):Play()
					ScolDown.CanvasSize = UDim2.new(0,0,0,UIListLayoutlist.AbsoluteContentSize.Y + 10  )
				end
				dog = not dog
			end
		)
		ScolDown.CanvasSize = UDim2.new(0,0,0,UIListLayoutlist.AbsoluteContentSize.Y + 10  )
	
	
	
				end
	
	
	
				end
	
				function items:TextBox(text,text2,callback)
					local TextFrame = Instance.new("Frame")
	
					TextFrame.Name = "TextFrame"
					TextFrame.Parent = ScrollingFrame_Pageframe
					TextFrame.BackgroundColor3 =  Color3.fromRGB(23, 23, 23)
					TextFrame.BorderSizePixel = 0
					TextFrame.Position = UDim2.new(0.5, 0, 0.5, 0)
					TextFrame.AnchorPoint = Vector2.new(0.5, 0.5)
					TextFrame.Size = UDim2.new(0, 213, 0, 70)
					TextFrame.BackgroundTransparency  = 1
					TextFrame.ClipsDescendants = true
	
					local LabelNameSliderxd = Instance.new("TextLabel")
	
					LabelNameSliderxd.Parent = TextFrame
					LabelNameSliderxd.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
					LabelNameSliderxd.BackgroundTransparency = 1
					LabelNameSliderxd.BorderSizePixel = 0
					LabelNameSliderxd.Position = UDim2.new(0.5, 0, 0.2, 0)
					LabelNameSliderxd.AnchorPoint = Vector2.new(0.5, 0.5)
					LabelNameSliderxd.Size = UDim2.new(0, 160, 0, 20)
					LabelNameSliderxd.Font = Enum.Font.GothamBold
					LabelNameSliderxd.Text = tostring(text)
					LabelNameSliderxd.TextColor3 = Color3.fromRGB(155, 155, 155)
					LabelNameSliderxd.TextSize = 11.000
					LabelNameSliderxd.TextXAlignment = Enum.TextXAlignment.Center
	
					local ConerTextBox = Instance.new("UICorner")
	
					ConerTextBox.CornerRadius = UDim.new(0, 4)
					ConerTextBox.Name = ""
					ConerTextBox.Parent = TextFrame
	
					local FrameBox = Instance.new("Frame")
	
					FrameBox.Name = "TextFrame"
					FrameBox.Parent = TextFrame
					FrameBox.BackgroundColor3 =  Color3.fromRGB(23, 23, 23)
					FrameBox.BorderSizePixel = 0
					FrameBox.Position = UDim2.new(0.5, 0, 0.65, 0)
					FrameBox.AnchorPoint = Vector2.new(0.5, 0.5)
					FrameBox.Size = UDim2.new(0, 158, 0, 30)
					FrameBox.BackgroundTransparency  = 0.2
					FrameBox.ClipsDescendants = true
					FrameBox.AnchorPoint = Vector2.new(0.5, 0.5)
	
					local TextFrame2 = Instance.new("TextBox")
	
					TextFrame2.Parent = FrameBox
					TextFrame2.BackgroundColor3 = _G.ColorMethod
					TextFrame2.BorderSizePixel = 0
					TextFrame2.ClipsDescendants = true
					TextFrame2.Position = UDim2.new(0.5, 0, 0.5, 0)
					TextFrame2.AnchorPoint = Vector2.new(0.5, 0.5)
					TextFrame2.Size = UDim2.new(0, 158, 0, 35)
					TextFrame2.Font = Enum.Font.GothamSemibold
					TextFrame2.PlaceholderColor3 = Color3.fromRGB(155, 155, 155)
					TextFrame2.PlaceholderText = text2
					TextFrame2.Text = ""
					TextFrame2.TextColor3 = Color3.fromRGB(155, 155, 155)
					TextFrame2.TextSize = 12.000
					TextFrame2.BackgroundTransparency = 1
	
					local ConerTextBox2 = Instance.new("UICorner")
	
					ConerTextBox2.CornerRadius = UDim.new(0, 4)
					ConerTextBox2.Name = ""
					ConerTextBox2.Parent = FrameBox
	
					local TextBoxStroke = Instance.new("UIStroke")
	
					TextBoxStroke.Thickness = 1
					TextBoxStroke.Name = ""
					TextBoxStroke.Parent = FrameBox
					TextBoxStroke.LineJoinMode = Enum.LineJoinMode.Round
					TextBoxStroke.Color = _G.ColorMethod
					TextBoxStroke.Transparency = 0.7
	
	
					TextFrame.MouseEnter:Connect(function()
						TweenService:Create(
							FrameBox,
							TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{Size = UDim2.new(0, 213, 0, 30)} -- UDim2.new(0, 128, 0, 25)
						):Play()
						TweenService:Create(
							FrameBox,
							TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{BackgroundColor3 = _G.ColorMethod} -- UDim2.new(0, 128, 0, 25)
						):Play()
						TweenService:Create(
							TextFrame2,
							TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{PlaceholderColor3 = Color3.fromRGB(255, 255, 255)} -- UDim2.new(0, 128, 0, 25)
						):Play()
						TweenService:Create(
							TextFrame2,
							TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{TextColor3 = Color3.fromRGB(255, 255, 255)} -- UDim2.new(0, 128, 0, 25)
						):Play()
						TweenService:Create(
							LabelNameSliderxd,
							TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{TextColor3 = Color3.fromRGB(255, 255, 255)} -- UDim2.new(0, 128, 0, 25)
						):Play()
						TweenService:Create(
							TextBoxStroke,
							TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{Thickness = 0} -- UDim2.new(0, 128, 0, 25)
						):Play()
					end
				)
	
				TextFrame.MouseLeave:Connect(function()
					TweenService:Create(
						FrameBox,
						TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
						{Size = UDim2.new(0, 158, 0, 30)} -- UDim2.new(0, 128, 0, 25)
					):Play()
					TweenService:Create(
						FrameBox,
						TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
						{BackgroundColor3 = Color3.fromRGB(23, 23, 23)} -- UDim2.new(0, 128, 0, 25)
					):Play()
					TweenService:Create(
						TextFrame2,
						TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
						{PlaceholderColor3 = Color3.fromRGB(155, 155, 155)} -- UDim2.new(0, 128, 0, 25)
					):Play()
					TweenService:Create(
						TextBoxStroke,
						TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
						{Thickness = 1} -- UDim2.new(0, 128, 0, 25)
					):Play()
					TweenService:Create(
						LabelNameSliderxd,
						TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
						{TextColor3 = Color3.fromRGB(155, 155, 155)} -- UDim2.new(0, 128, 0, 25)
					):Play()
					TweenService:Create(
						TextFrame2,
						TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
						{TextColor3 = Color3.fromRGB(155, 155, 155)} -- UDim2.new(0, 128, 0, 25)
					):Play()
				end
				)
					TextFrame2.FocusLost:Connect(function ()
						if #TextFrame2.Text > 0 then
							pcall(callback,TextFrame2.Text)
						end
					end)
				end
	
				function items:Bind(text,bi,callback)
					local BindFrame = Instance.new("Frame")
	
					BindFrame.Name = "BindFrame"
					BindFrame.Parent = ScrollingFrame_Pageframe
					BindFrame.BackgroundColor3 =  Color3.fromRGB(23, 23, 23)
					BindFrame.BorderSizePixel = 0
					BindFrame.Position = UDim2.new(0.5, 0, 0.5, 0)
					BindFrame.AnchorPoint = Vector2.new(0.5, 0.5)
					BindFrame.Size = UDim2.new(0, 213, 0, 35)
					BindFrame.BackgroundTransparency  = 0
					BindFrame.ClipsDescendants = true
	
					local BindConner = Instance.new("UICorner")
	
					BindConner.CornerRadius = UDim.new(0, 4)
					BindConner.Name = ""
					BindConner.Parent = BindFrame
	
					local BindStroke = Instance.new("UIStroke")
	
					BindStroke.Thickness = 1
					BindStroke.Name = ""
					BindStroke.Parent = BindFrame
					BindStroke.LineJoinMode = Enum.LineJoinMode.Round
					BindStroke.Color = _G.ColorMethod
					BindStroke.Transparency = 0.7
	
					local LabelBind = Instance.new("TextLabel")
	
					LabelBind.Parent = BindFrame
					LabelBind.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
					LabelBind.BackgroundTransparency = 1
					LabelBind.BorderSizePixel = 0
					LabelBind.Position = UDim2.new(0.4, 0, 0.5, 0)
					LabelBind.AnchorPoint = Vector2.new(0.5, 0.5)
					LabelBind.Size = UDim2.new(0, 140, 0, 35)
					LabelBind.Font = Enum.Font.GothamBold
					LabelBind.Text = tostring(text)
					LabelBind.TextColor3 = Color3.fromRGB(155, 155, 155)
					LabelBind.TextSize = 11.000
					LabelBind.TextXAlignment = Enum.TextXAlignment.Left
	
					local key = bi.Name
					local LabelBind2 = Instance.new("TextButton")
	
					LabelBind2.Parent = BindFrame
					LabelBind2.Name = "LabelBind2"
					LabelBind2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
					LabelBind2.Size = UDim2.new(0, 100, 0, 19)
					LabelBind2.Font = Enum.Font.GothamBold
					LabelBind2.Text =  "KEY : "..key
					LabelBind2.TextColor3 = Color3.fromRGB(155, 155, 155)
					LabelBind2.TextSize = 11.000
					LabelBind2.AnchorPoint = Vector2.new(0.5, 0.5)
					LabelBind2.Position = UDim2.new(0.75, 0, 0.5, 0)
					LabelBind2.TextXAlignment = Enum.TextXAlignment.Center
					LabelBind2.BackgroundTransparency = 1
					LabelBind2.TextWrapped = true
	
					local LabelBind22 = Instance.new("TextButton")
	
					LabelBind22.Parent = BindFrame
					LabelBind22.Name = "LabelBind22"
					LabelBind22.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
					LabelBind22.Size = UDim2.new(0, 213, 0, 35)
					LabelBind22.Font = Enum.Font.GothamBold
					LabelBind22.Text =  ""
					LabelBind22.TextColor3 = Color3.fromRGB(155, 155, 155)
					LabelBind22.TextSize = 11.000
					LabelBind22.AnchorPoint = Vector2.new(0.5, 0.5)
					LabelBind22.Position = UDim2.new(0.5, 0, 0.5, 0)
					LabelBind22.TextXAlignment = Enum.TextXAlignment.Center
					LabelBind22.BackgroundTransparency = 1
					LabelBind22.TextWrapped = true
	
					BindFrame.MouseEnter:Connect(function()
						TweenService:Create(
							BindStroke,
							TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{Transparency = 0} -- UDim2.new(0, 128, 0, 25)
						):Play()
						TweenService:Create(
							LabelBind22,
							TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{TextColor3 = Color3.fromRGB(255, 255, 255)} -- UDim2.new(0, 128, 0, 25)
						):Play()
						TweenService:Create(
							LabelBind2,
							TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{TextColor3 = Color3.fromRGB(255, 255, 255)} -- UDim2.new(0, 128, 0, 25)
						):Play()
						TweenService:Create(
							LabelBind,
							TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{TextColor3 = Color3.fromRGB(255, 255, 255)} -- UDim2.new(0, 128, 0, 25)
						):Play()
					end
				)
					BindFrame.MouseLeave:Connect(function()
						TweenService:Create(
							BindStroke,
							TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{Transparency = 0.7} -- UDim2.new(0, 128, 0, 25)
						):Play()
						TweenService:Create(
							LabelBind22,
							TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{TextColor3 = Color3.fromRGB(155, 155, 155)} -- UDim2.new(0, 128, 0, 25)
						):Play()
						TweenService:Create(
							LabelBind2,
							TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{TextColor3 = Color3.fromRGB(155, 155, 155)} -- UDim2.new(0, 128, 0, 25)
						):Play()
						TweenService:Create(
							LabelBind,
							TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{TextColor3 = Color3.fromRGB(155, 155, 155)} -- UDim2.new(0, 128, 0, 25)
						):Play()
					end
				)
	
					LabelBind22.MouseButton1Click:Connect(function ()
	
	
						LabelBind2.Text = "KEY : ".."..."
						local inputwait = game:GetService("UserInputService").InputBegan:wait()
						local fuckulop = inputwait.KeyCode == Enum.KeyCode.Unknown and inputwait.UserInputType or inputwait.KeyCode
	
						if
						fuckulop.Name ~= "Focus" and fuckulop.Name ~= "MouseMovement" and fuckulop.Name ~= "Focus"
						then
							LabelBind2.Text =  "KEY : "..fuckulop.Name
							key = fuckulop.Name
						end
						-- if fuckulop.Name ~= "Unknown" then
						--     LabelBind2.Text = fuckulop.Name
						--     key = fuckulop.Name
						-- end
	
					end)
	
	
					game:GetService("UserInputService").InputBegan:connect(
						function(current)
							local fuckulop2 = current.KeyCode == Enum.KeyCode.Unknown and current.UserInputType or current.KeyCode
	
								if fuckulop2.Name ==  key then
									pcall(callback)
	
							end
						end
						)
	
				end
	
				function items:Line()
					local LineFrame = Instance.new("Frame")
	
					LineFrame.Name = "LineFrame"
					LineFrame.Parent = ScrollingFrame_Pageframe
					LineFrame.BackgroundColor3 =  _G.ColorMethod
					LineFrame.BorderSizePixel = 0
					LineFrame.Position = UDim2.new(0.5, 0, 0.5, 0)
					LineFrame.AnchorPoint = Vector2.new(0.5, 0.5)
					LineFrame.Size = UDim2.new(0, 213, 0, 1)
					LineFrame.BackgroundTransparency  = 0
					LineFrame.ClipsDescendants = true
	
					local LineFrame_BindConner = Instance.new("UICorner")
	
					LineFrame_BindConner.CornerRadius = UDim.new(0, 30)
					LineFrame_BindConner.Name = ""
					LineFrame_BindConner.Parent = LineFrame
	
				end
	
				function items:Color(text,preset,callback)
					local Pixker = Instance.new("Frame")
	
					Pixker.Name = "Pixker"
					Pixker.Parent = ScrollingFrame_Pageframe
					Pixker.BackgroundColor3 = Color3.fromRGB(23, 23, 23)
					Pixker.Position = UDim2.new(0.0833333358, 0, 0.235135213, 0)
					Pixker.Size = UDim2.new(0, 213, 0, 33)
					Pixker.BackgroundTransparency = 0
					Pixker.BorderSizePixel = 0
					Pixker.AnchorPoint = Vector2.new(0.5, 0.5)
					Pixker.Position = UDim2.new(0.5, 0, 0.5, 0)
					Pixker.ClipsDescendants = true
	
	
					local BoxColorCorner2 = Instance.new("UICorner")
	
					BoxColorCorner2.CornerRadius = UDim.new(0, 4)
					BoxColorCorner2.Name = "BoxColorCorner"
					BoxColorCorner2.Parent = Pixker
	
					local MheeFrameStroke = Instance.new("UIStroke")
	
					MheeFrameStroke.Thickness = 1
					MheeFrameStroke.Name = ""
					MheeFrameStroke.Parent = Pixker
					MheeFrameStroke.LineJoinMode = Enum.LineJoinMode.Round
					MheeFrameStroke.Color = _G.ColorMethod
					MheeFrameStroke.Transparency = 0.7
	
	
					local TextFrameColor = Instance.new("TextLabel")
	
					TextFrameColor.Parent = Pixker
					TextFrameColor.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
					TextFrameColor.BorderSizePixel = 0
					TextFrameColor.Size = UDim2.new(0, 200, 0, 34)
					TextFrameColor.Font = Enum.Font.SourceSans
					TextFrameColor.Text = "  "
					TextFrameColor.TextColor3 = Color3.fromRGB(0, 0, 0)
					TextFrameColor.TextSize = 14.000
					TextFrameColor.BackgroundTransparency = 1
					TextFrameColor.Position = UDim2.new(0., 0, 0., 0)
	
					local TextReal = Instance.new("TextLabel")
	
					TextReal.Parent = TextFrameColor
					TextReal.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
					TextReal.BorderSizePixel = 0
					TextReal.Size = UDim2.new(0, 140, 0, 34)
					TextReal.Font = Enum.Font.GothamSemibold
					TextReal.Text = text
					TextReal.TextColor3 = Color3.fromRGB(155,155, 155)
					TextReal.TextSize = 12.000
					TextReal.BackgroundTransparency = 1
					TextReal.Position = UDim2.new(0.05, 0, 0., 0)
					TextReal.TextXAlignment = Enum.TextXAlignment.Left
	
					local BoxColor = Instance.new("Frame")
	
					BoxColor.Name = "BoxColor"
					BoxColor.Parent = TextFrameColor
					BoxColor.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
					BoxColor.Position = UDim2.new(0.85, 0, 0.5, 0)
					BoxColor.Size = UDim2.new(0, 35, 0, 19)
					BoxColor.AnchorPoint = Vector2.new(0.5, 0.5)
	
					local BoxColorCorner = Instance.new("UICorner")
	
					BoxColorCorner.CornerRadius = UDim.new(0, 4)
					BoxColorCorner.Name = "BoxColorCorner"
					BoxColorCorner.Parent = BoxColor
	
					local TextButton_Dropdown = Instance.new("TextButton")
	
	
					TextButton_Dropdown.Parent = TextFrameColor
					TextButton_Dropdown.BackgroundColor3 = Color3.fromRGB(45, 45, 45)
					TextButton_Dropdown.BorderSizePixel = 0
					TextButton_Dropdown.Position = UDim2.new(0., 0, 0.14705883, 0)
					TextButton_Dropdown.Size = UDim2.new(0, 200, 0, 33)
					TextButton_Dropdown.Font = Enum.Font.SourceSans
					TextButton_Dropdown.Text = "  "
					TextButton_Dropdown.TextColor3 = Color3.fromRGB(0, 0, 0)
					TextButton_Dropdown.TextSize = 14.000
					TextButton_Dropdown.AutoButtonColor = false
					--TextButton_Dropdown.AnchorPoint = Vector2.new(0.5, 0.5)
					TextButton_Dropdown.Position = UDim2.new(0, 0, 0, 0)
					TextButton_Dropdown.BackgroundTransparency = 1
	
	
	
					Pixker.MouseEnter:Connect(function()
						TweenService:Create(
							MheeFrameStroke,
							TweenInfo.new(0.3, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{Transparency = 0.}
						):Play()
						TweenService:Create(
							TextReal,
							TweenInfo.new(0.3, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{TextColor3 = Color3.fromRGB(255,255, 255)}
						):Play()
	
					end)
					Pixker.MouseLeave:Connect(function()
						TweenService:Create(
							MheeFrameStroke,
							TweenInfo.new(0.3, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{Transparency = 0.7}
						):Play()
						TweenService:Create(
							TextReal,
							TweenInfo.new(0.3, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{TextColor3 = Color3.fromRGB(155,155, 155)}
						):Play()
					end)
				-- Rainbow Toggle
	
	
				local TextButton_2_Toggle = Instance.new("TextButton")
	
				TextButton_2_Toggle.Parent = TextFrameColor
				TextButton_2_Toggle.BackgroundColor3 = Color3.fromRGB(155, 155, 155)
		--        TextButton_2_Toggle.BorderColor3 = _G.ColorMethod
				TextButton_2_Toggle.BorderSizePixel = 0
				TextButton_2_Toggle.AnchorPoint = Vector2.new(0.5, 0.5)
				TextButton_2_Toggle.Position = UDim2.new(0.2, 0, 1.87, 0)
				TextButton_2_Toggle.Size = UDim2.new(0, 30, 0, 13)
				TextButton_2_Toggle.Font = Enum.Font.SourceSans
				TextButton_2_Toggle.Text = " "
				TextButton_2_Toggle.TextColor3 = Color3.fromRGB(0, 0, 0)
				TextButton_2_Toggle.TextSize = 12.000
				TextButton_2_Toggle.AutoButtonColor = false
	
				local TextButton_Pageframe_Uiconner = Instance.new("UICorner")
	
				TextButton_Pageframe_Uiconner.CornerRadius = UDim.new(0, 30)
				TextButton_Pageframe_Uiconner.Name = ""
				TextButton_Pageframe_Uiconner.Parent = TextButton_2_Toggle
	
				local TextButton_3_Toggle = Instance.new("TextButton")
	
				TextButton_3_Toggle.Parent = TextButton_2_Toggle
				TextButton_3_Toggle.BackgroundColor3 = Color3.fromRGB(255, 255,255)
		--        TextButton_3_Toggle.BorderColor3 = _G.ColorMethod
				TextButton_3_Toggle.BorderSizePixel = 0
				TextButton_3_Toggle.AnchorPoint = Vector2.new(0.5, 0.5)
				TextButton_3_Toggle.Position = UDim2.new(0.1, 0, 0.5, 0)
				TextButton_3_Toggle.Size = UDim2.new(0, 19, 0, 19)
				TextButton_3_Toggle.Font = Enum.Font.SourceSans
				TextButton_3_Toggle.Text = " "
				TextButton_3_Toggle.TextColor3 = Color3.fromRGB(0, 0, 0)
				TextButton_3_Toggle.TextSize = 12.000
				TextButton_3_Toggle.AutoButtonColor = false
	
				local TextButton_Pageframe_Uiconner2 = Instance.new("UICorner")
	
				TextButton_Pageframe_Uiconner2.CornerRadius = UDim.new(0, 30)
				TextButton_Pageframe_Uiconner2.Name = ""
				TextButton_Pageframe_Uiconner2.Parent = TextButton_3_Toggle
	
				local TextButton_4_Toggle = Instance.new("TextButton")
	
				TextButton_4_Toggle.Parent = TextButton_3_Toggle
				TextButton_4_Toggle.BackgroundColor3 = Color3.fromRGB(155, 155,155)
		--        TextButton_3_Toggle.BorderColor3 = _G.ColorMethod
				TextButton_4_Toggle.BorderSizePixel = 0
				TextButton_4_Toggle.AnchorPoint = Vector2.new(0.5, 0.5)
				TextButton_4_Toggle.Position = UDim2.new(0.5, 0, 0.5, 0)
				TextButton_4_Toggle.Size = UDim2.new(0, 27, 0, 27-2)
				TextButton_4_Toggle.Font = Enum.Font.SourceSans
				TextButton_4_Toggle.Text = " "
				TextButton_4_Toggle.TextColor3 = Color3.fromRGB(0, 0, 0)
				TextButton_4_Toggle.TextSize = 12.000
				TextButton_4_Toggle.AutoButtonColor = false
				TextButton_4_Toggle.BackgroundTransparency = 1
				TextButton_4_Toggle.Visible = true
	
				local TextButton_Pageframe_Uiconner4 = Instance.new("UICorner")
	
				TextButton_Pageframe_Uiconner4.CornerRadius = UDim.new(0, 30)
				TextButton_Pageframe_Uiconner4.Name = ""
				TextButton_Pageframe_Uiconner4.Parent = TextButton_4_Toggle
	
	
				local TextButton_Toggle = Instance.new("TextButton")
	
				TextButton_Toggle.Parent = ValueFrame
				TextButton_Toggle.BackgroundTransparency =1
				TextButton_Toggle.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
				TextButton_Toggle.BorderSizePixel = 0
				TextButton_Toggle.Size = UDim2.new(0, 50, 0, 20)
				TextButton_Toggle.AutoButtonColor = false
				TextButton_Toggle.Font = Enum.Font.SourceSans
				TextButton_Toggle.Text = " "
				TextButton_Toggle.TextColor3 = Color3.fromRGB(0, 0, 0)
				TextButton_Toggle.TextSize = 12.000
				TextButton_Toggle.AnchorPoint = Vector2.new(0.5, 0.5)
				TextButton_Toggle.Position = UDim2.new(1.25, 0, 0.4, 0)
	
				local TextButton_3_Toggle2 = Instance.new("TextLabel")
	
				TextButton_3_Toggle2.Parent = TextButton_2_Toggle
				TextButton_3_Toggle2.BackgroundColor3 = Color3.fromRGB(32, 32,32)
				TextButton_3_Toggle2.BorderColor3 = _G.ColorMethod
				TextButton_3_Toggle2.BorderSizePixel = 0
				TextButton_3_Toggle2.AnchorPoint = Vector2.new(0.5, 0.5)
				TextButton_3_Toggle2.Position = UDim2.new(1.9, 0, 0.5, 0)
				TextButton_3_Toggle2.Size = UDim2.new(0, 500, 0, 21)
				TextButton_3_Toggle2.Font = Enum.Font.SourceSansBold
				TextButton_3_Toggle2.Text = "Rainbow"
				TextButton_3_Toggle2.TextColor3 = Color3.fromRGB(255, 255, 255)
				TextButton_3_Toggle2.TextSize = 13.000
				TextButton_3_Toggle2.BackgroundTransparency = 1
	
				local OMF = Instance.new("TextButton")
	
				OMF.Parent = TextButton_2_Toggle
				OMF.BackgroundTransparency =1
				OMF.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
				OMF.BorderSizePixel = 0
				OMF.Size = UDim2.new(0, 100, 0, 20)
				OMF.AutoButtonColor = false
				OMF.Font = Enum.Font.SourceSans
				OMF.Text = " "
				OMF.TextColor3 = Color3.fromRGB(0, 0, 0)
				OMF.TextSize = 12.000
				OMF.AnchorPoint = Vector2.new(0.5, 0.5)
				OMF.Position = UDim2.new(1.3, 0, 0.5, 0)
	
				local Color =  Instance.new("ImageLabel")
	
				Color.Name = "Color"
				Color.Parent = TextFrameColor
				Color.BackgroundColor3 = Color3.fromRGB(255, 0, 4)
				Color.Position = UDim2.new(0.05,0,4,0)
				Color.Size = UDim2.new(0, 195, 0, 40)
				Color.ZIndex = 0
				Color.BorderSizePixel = 0
				Color.Image = "rbxassetid://4155801252"
	
				local ColorFucj = Instance.new("UICorner")
	
				ColorFucj.CornerRadius = UDim.new(0, 4)
				ColorFucj.Name = ""
				ColorFucj.Parent = Color
	
				local ColorSelection =  Instance.new("ImageLabel")
	
				ColorSelection.Name = "ColorSelection"
				ColorSelection.Parent = Color
				ColorSelection.AnchorPoint = Vector2.new(0.5, 0.5)
				ColorSelection.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
				ColorSelection.BackgroundTransparency = 1.000
				ColorSelection.Position = UDim2.new(preset and select(3, Color3.toHSV(preset)))
				ColorSelection.Size = UDim2.new(0, 18, 0, 18)
				ColorSelection.Image = "http://www.roblox.com/asset/?id=4805639000"
				ColorSelection.ScaleType = Enum.ScaleType.Fit
				ColorSelection.Visible = true
	
				local Hue =  Instance.new("ImageLabel")
	
				Hue.Name = "Hue2"
				Hue.Parent = TextFrameColor
				Hue.Position = UDim2.new(0.14,0,3,0)
				Hue.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
				Hue.Size = UDim2.new(0, 160, 0, 25)
				Hue.ZIndex = 0
				Hue.BorderSizePixel = 0
	
				local ColorFucj2 = Instance.new("UICorner")
	
				ColorFucj2.CornerRadius = UDim.new(0, 4)
				ColorFucj2.Name = ""
				ColorFucj2.Parent = Hue
	
				local HueGradient = Instance.new("UIGradient")
	
				HueGradient.Color = ColorSequence.new {
					ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 0, 4)),
					ColorSequenceKeypoint.new(0.20, Color3.fromRGB(234, 255, 0)),
					ColorSequenceKeypoint.new(0.40, Color3.fromRGB(21, 255, 0)),
					ColorSequenceKeypoint.new(0.60, Color3.fromRGB(0, 255, 255)),
					ColorSequenceKeypoint.new(0.80, Color3.fromRGB(0, 17, 255)),
					ColorSequenceKeypoint.new(0.90, Color3.fromRGB(255, 0, 251)),
					ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 0, 4))
				}
				HueGradient.Rotation = 0
				HueGradient.Name = "HueGradient"
				HueGradient.Parent = Hue
	
				local HueSelection =  Instance.new("ImageLabel")
	
				HueSelection.Name = "HueSelection"
				HueSelection.Parent = Hue
				HueSelection.AnchorPoint = Vector2.new(0.5, 0.5)
				HueSelection.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
				HueSelection.BackgroundTransparency = 1.000
				HueSelection.Position = UDim2.new(preset and select(3, Color3.toHSV(preset)))
				HueSelection.Size = UDim2.new(0, 18, 0, 18)
				HueSelection.Image = "http://www.roblox.com/asset/?id=4805639000"
				HueSelection.ScaleType = Enum.ScaleType.Fit
				HueSelection.Visible = true
	
	
				local BTN_XD = Instance.new("TextButton")
	
				BTN_XD.Parent = TextFrameColor
				BTN_XD.BackgroundColor3 = _G.ColorMethod
				BTN_XD.BorderColor3 = _G.ColorMethod
				BTN_XD.BorderSizePixel = 0
				BTN_XD.AnchorPoint = Vector2.new(0.5, 0.5)
				BTN_XD.Position = UDim2.new(0.8, 0, 1.9, 0)
				BTN_XD.Size = UDim2.new(0, 50, 0, 25)
				BTN_XD.Font = Enum.Font.GothamSemibold
				BTN_XD.Text = "Confirm"
				BTN_XD.TextColor3 = Color3.fromRGB(255, 255, 255)
				BTN_XD.TextSize = 11.000
				BTN_XD.AutoButtonColor = false
	
				local BTN_XD_COnner = Instance.new("UICorner")
	
				BTN_XD_COnner.CornerRadius = UDim.new(0, 4)
				BTN_XD_COnner.Name = ""
				BTN_XD_COnner.Parent = BTN_XD
	
	
	
				local MheeFrameStroke = Instance.new("UIStroke")
	
				MheeFrameStroke.Thickness = 1
				MheeFrameStroke.Name = ""
				MheeFrameStroke.Parent = BTN_XD
				MheeFrameStroke.LineJoinMode = Enum.LineJoinMode.Round
				MheeFrameStroke.Color = _G.ColorMethod
				MheeFrameStroke.Transparency = 0.7
	
	
				local UwU = false
	
	
				OMF.MouseButton1Click:Connect(function()
					if       UwU == false  then
						TweenService:Create(
							TextButton_4_Toggle,
							TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{BackgroundColor3 =  _G.ColorMethod} -- UDim2.new(0, 128, 0, 25)
						):Play()
						TweenService:Create(
							TextButton_3_Toggle,
							TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{BackgroundColor3 =  _G.ColorMethod} -- UDim2.new(0, 128, 0, 25)
						):Play()
						TweenService:Create(
							TextButton_2_Toggle,
							TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{BackgroundColor3 =  Color3.fromRGB(153, 0, 102)} -- UDim2.new(0, 128, 0, 25)
						):Play()
						TextButton_3_Toggle:TweenSizeAndPosition(UDim2.new(0, 19, 0, 19), UDim2.new(1, 0, 0.5, 0), "Out", "Quad", 0.3, true)
					else
						TweenService:Create(
							TextButton_4_Toggle,
							TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{BackgroundColor3 =  Color3.fromRGB(155, 155, 155)} -- UDim2.new(0, 128, 0, 25)
						):Play()
						TweenService:Create(
							TextButton_3_Toggle,
							TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{BackgroundColor3 =  Color3.fromRGB(255, 255, 255)} -- UDim2.new(0, 128, 0, 25)
						):Play()
						TweenService:Create(
							TextButton_2_Toggle,
							TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{BackgroundColor3 =  Color3.fromRGB(155, 155, 155)} -- UDim2.new(0, 128, 0, 25)
						):Play()
						TextButton_3_Toggle:TweenSizeAndPosition(UDim2.new(0, 19, 0, 19), UDim2.new(0.1, 0, 0.5, 0), "Out", "Quad", 0.3, true)
					end
					UwU = not UwU
				end
			)
	
	
			OMF.MouseEnter:Connect(function()
					TweenService:Create(
						TextButton_4_Toggle,
						TweenInfo.new(0.2, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
						{BackgroundTransparency = 0.6} -- UDim2.new(0, 128, 0, 25)
					):Play()
				end
			)
	
			OMF.MouseLeave:Connect(function()
					TweenService:Create(
						TextButton_4_Toggle,
						TweenInfo.new(0.2, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
						{BackgroundTransparency = 1} -- UDim2.new(0, 128, 0, 25)
					):Play()
				end
			)
	
			OMF.MouseButton1Down:Connect(
					function()
						RainbowColorPicker = not RainbowColorPicker
	
						if ColorInput then
							ColorInput:Disconnect()
						end
	
						if HueInput then
							HueInput:Disconnect()
						end
	
						if RainbowColorPicker then
	
	
							OldToggleColor = BoxColor.BackgroundColor3
							OldColor = Color.BackgroundColor3
							OldColorSelectionPosition = ColorSelection.Position
							OldHueSelectionPosition = HueSelection.Position
	
							while RainbowColorPicker do
								BoxColor.BackgroundColor3 = Color3.fromHSV(Red.RainbowColorValue, 1, 1)
								Color.BackgroundColor3 = Color3.fromHSV(Red.RainbowColorValue, 1, 1)
	
								ColorSelection.Position = UDim2.new(1, 0, 0, 0)
								HueSelection.Position = UDim2.new(0,  Red.HueSelectionPosition, 0.5,0)
	
								pcall(callback, BoxColor.BackgroundColor3)
								wait()
							end
						elseif not RainbowColorPicker then
	
							BoxColor.BackgroundColor3 = OldToggleColor
							Color.BackgroundColor3 = OldColor
	
							ColorSelection.Position = OldColorSelectionPosition
							HueSelection.Position = OldHueSelectionPosition
	
							pcall(callback, BoxColor.BackgroundColor3)
						end
					end
				)
				TextButton_3_Toggle.MouseButton1Down:Connect(
					function()
						RainbowColorPicker = not RainbowColorPicker
	
						if ColorInput then
							ColorInput:Disconnect()
						end
	
						if HueInput then
							HueInput:Disconnect()
						end
	
						if RainbowColorPicker then
	
	
							OldToggleColor = BoxColor.BackgroundColor3
							OldColor = Color.BackgroundColor3
							OldColorSelectionPosition = ColorSelection.Position
							OldHueSelectionPosition = HueSelection.Position
	
							while RainbowColorPicker do
								BoxColor.BackgroundColor3 = Color3.fromHSV(Red.RainbowColorValue, 1, 1)
								Color.BackgroundColor3 = Color3.fromHSV(Red.RainbowColorValue, 1, 1)
	
								ColorSelection.Position = UDim2.new(1, 0, 0, 0)
								HueSelection.Position = UDim2.new(0,  Red.HueSelectionPosition, 0.5,0)
	
								pcall(callback, BoxColor.BackgroundColor3)
								wait()
							end
						elseif not RainbowColorPicker then
	
							BoxColor.BackgroundColor3 = OldToggleColor
							Color.BackgroundColor3 = OldColor
	
							ColorSelection.Position = OldColorSelectionPosition
							HueSelection.Position = OldHueSelectionPosition
	
							pcall(callback, BoxColor.BackgroundColor3)
						end
					end
				)
	
	
				local function UpdateColorPicker(nope)
					BoxColor.BackgroundColor3 = Color3.fromHSV(ColorH, ColorS, ColorV)
					Color.BackgroundColor3 = Color3.fromHSV(ColorH, 1, 1)
	
					pcall(callback, BoxColor.BackgroundColor3)
				end
				ColorH =
				1 -
				(math.clamp(HueSelection.AbsolutePosition.Y - Hue.AbsolutePosition.Y, 0, Hue.AbsoluteSize.Y) /
					Hue.AbsoluteSize.Y)
				ColorS =
					(math.clamp(ColorSelection.AbsolutePosition.X - Color.AbsolutePosition.X, 0, Color.AbsoluteSize.X) /
						Color.AbsoluteSize.X)
				ColorV =
					1 -
					(math.clamp(ColorSelection.AbsolutePosition.Y - Color.AbsolutePosition.Y, 0, Color.AbsoluteSize.Y) /
						Color.AbsoluteSize.Y)
	
				BoxColor.BackgroundColor3 = preset
				Color.BackgroundColor3 = preset
				pcall(callback, BoxColor.BackgroundColor3)
	
				local RainbowColorPicker = false
	
				Color.InputBegan:Connect(
					function(input)
						if input.UserInputType == Enum.UserInputType.MouseButton1 then
							if RainbowColorPicker then
								return
							end
	
							if ColorInput then
								ColorInput:Disconnect()
							end
	
							ColorInput =
								RunService.RenderStepped:Connect(
									function()
									local ColorX =
										(math.clamp(Mouse.X - Color.AbsolutePosition.X, 0, Color.AbsoluteSize.X) /
											Color.AbsoluteSize.X)
									local ColorY =
										(math.clamp(Mouse.Y - Color.AbsolutePosition.Y, 0, Color.AbsoluteSize.Y) /
											Color.AbsoluteSize.Y)
	
									ColorSelection.Position = UDim2.new(ColorX, 0, ColorY, 0)
									ColorS = ColorX
									ColorV = 1 - ColorY
	
									UpdateColorPicker(true)
								end
								)
						end
					end
				)
	
	
					Color.InputEnded:Connect(
						function(input)
							if input.UserInputType == Enum.UserInputType.MouseButton1 then
								if ColorInput then
									ColorInput:Disconnect()
								end
							end
						end
					)
	
					Hue.InputBegan:Connect(
						function(input)
							if input.UserInputType == Enum.UserInputType.MouseButton1 then
								if RainbowColorPicker then
									return
								end
	
								if HueInput then
									HueInput:Disconnect()
								end
	
								HueInput =
									RunService.RenderStepped:Connect(
										function()
										local HueY =
											(math.clamp(Mouse.Y - Hue.AbsolutePosition.Y, 0, Hue.AbsoluteSize.Y) /
												Hue.AbsoluteSize.Y)
										local HueX =
											(math.clamp(Mouse.X- Hue.AbsolutePosition.X, 0, Hue.AbsoluteSize.X) /
												Hue.AbsoluteSize.X)
	
										HueSelection.Position = UDim2.new(HueX, 0, HueY, 0)
										ColorH = 1 - HueY
	
										UpdateColorPicker(true)
									end
									)
							end
						end
					)
	
					Hue.InputEnded:Connect(
						function(input)
							if input.UserInputType == Enum.UserInputType.MouseButton1 then
								if HueInput then
									HueInput:Disconnect()
								end
							end
						end
					)
					local sk = false
					TextButton_Dropdown.MouseButton1Click:Connect(function()
						if sk == false then
						TweenService:Create(
							Pixker,
							TweenInfo.new(0.3, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{Size = UDim2.new(0, 213, 0, 180)}
						):Play()
					else
						TweenService:Create(
							Pixker,
							TweenInfo.new(0.3, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{Size = UDim2.new(0, 213, 0, 33)}
						):Play()
					end
					sk = not sk
					end
				)
					BTN_XD.MouseButton1Click:Connect(
						function()
							TweenService:Create(
								Pixker,
								TweenInfo.new(0.3, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
								{Size = UDim2.new(0, 213, 0, 33)}
							):Play()
							sk = not sk
						end
					)
	
	
				end
				function items:Label(text,image)
					if image == nil then
						image = logoid
					end
					local labaelchange = {}
					local LabelFrame = Instance.new("Frame")
	
	
					LabelFrame.Name = "Mainframenoti"
					LabelFrame.Parent = ScrollingFrame_Pageframe
					LabelFrame.BackgroundColor3 = Color3.fromRGB(23, 23, 23)
					LabelFrame.BackgroundTransparency = 0
					LabelFrame.BorderSizePixel = 0
					LabelFrame.ClipsDescendants = false
					LabelFrame.AnchorPoint = Vector2.new(0.5, 0.5)
					LabelFrame.Position = UDim2.new(0.498, 0, 0.5, 0)
					LabelFrame.Size = UDim2.new(0, 213, 0, 28)
	
					local LabelFarm2 = Instance.new("TextLabel")
	
					LabelFarm2.Parent = LabelFrame
					LabelFarm2.Name = "TextLabel_Tap"
					LabelFarm2.BackgroundColor3 = Color3.fromRGB(45, 45, 45)
					LabelFarm2.Size =UDim2.new(0, 130, 0,24 )
					LabelFarm2.Font = Enum.Font.SourceSansSemibold
					LabelFarm2.Text = text
					LabelFarm2.TextColor3 = Color3.fromRGB(255, 255, 255)
					LabelFarm2.TextSize = 12.000
					LabelFarm2.AnchorPoint = Vector2.new(0.5, 0.5)
					LabelFarm2.Position = UDim2.new(0.5, 0, 0.5, 0)
					LabelFarm2.TextXAlignment = Enum.TextXAlignment.Center
					LabelFarm2.BackgroundTransparency = 1
					LabelFarm2.TextWrapped = true
	
					local ImageLabel_gx = Instance.new("ImageLabel")
	
					ImageLabel_gx.Parent = LabelFrame
					ImageLabel_gx.BackgroundTransparency = 1.000
					ImageLabel_gx.BorderSizePixel = 0
					ImageLabel_gx.Size = UDim2.new(0,15, 0, 15)
					ImageLabel_gx.AnchorPoint = Vector2.new(0.5, 0.5)
					ImageLabel_gx.Position = UDim2.new(0.1, 0, 0.50, 0)
					ImageLabel_gx.Image = "http://www.roblox.com/asset/?id="..tostring(7040410130)
					ImageLabel_gx.BackgroundTransparency = 1
	
					local noticore55 = Instance.new("UICorner")
	
					noticore55.CornerRadius = UDim.new(0, 4)
					noticore55.Name = ""
					noticore55.Parent = LabelFarm2
	
					local noticore2777 = Instance.new("UICorner")
	
					noticore2777.CornerRadius = UDim.new(0, 4)
					noticore2777.Name = ""
					noticore2777.Parent = LabelFrame
	
					local LabelStroke = Instance.new("UIStroke")
	
					LabelStroke.Thickness = 1
					LabelStroke.Name = ""
					LabelStroke.Parent = LabelFrame
					LabelStroke.LineJoinMode = Enum.LineJoinMode.Round
					LabelStroke.Color = _G.ColorMethod
					LabelStroke.Transparency = 0.7
	
					LabelFrame.MouseEnter:Connect(function()
						TweenService:Create(
							LabelStroke,
							TweenInfo.new(0.3, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{Transparency =0}
						):Play()
					end
				)
					LabelFrame.MouseLeave:Connect(function()
						TweenService:Create(
							LabelStroke,
							TweenInfo.new(0.3, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
							{Transparency =0.7}
						):Play()
					end
				)
					function labaelchange:Change(text2)
						LabelFarm2.Text = text2
					end
					return  labaelchange
				end
				return  items
				end
			return  page
			end
		return top
		end
local Window = create:win("Test")
local Tap = Window:Taps("Main")
 local Main = Tap:newpage()
Main:Label("🎄 Auto Farm Function 🎄")
spawn(function()
	while wait() do
		if _G.AutoRejoin then
			getgenv().rejoin = game:GetService("CoreGui").RobloxPromptGui.promptOverlay.ChildAdded:Connect(function(child)
				if child.Name == 'ErrorPrompt' and child:FindFirstChild('MessageArea') and child.MessageArea:FindFirstChild("ErrorFrame") then
					game:GetService("TeleportService"):Teleport(game.PlaceId)
				end
			end)
		end
	end
end) 




    Main:Toggle("Auto Farm",_G.AutoFarm,function(value)
                    _G.AutoFarm = value
            StopTween(_G.AutoFarm)


            if value == false then
                getgenv().ToTarget(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame)
                getgenv().ToTarget(game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame)
               topos(game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame)
                topos(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame)
    _G.Bypass = false
            end
            if _G.AutoFarm == false then
                _G.Bypass = false
            end
            

        _G.Bypass = value
    end)

	if World1 then
		Main:Toggle("Player Farm Mode",_G.FastFarmPlayer1,function(value)
			_G.FastFarmPlayer1 = value
				StopTween(_G.FastFarmPlayer1)
	
	
				if value == false then
					getgenv().ToTarget(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame)
					getgenv().ToTarget(game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame)
				   topos(game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame)
					topos(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame)
		_G.Bypass = false
				end
			  
		end)
	end
  
function TP(Point)
	local Ply = game.Players.LocalPlayer
	local Char = Ply.Character
--	repeat
	Char.Humanoid:ChangeState(15)
	Char.HumanoidRootPart.CFrame = Point
	wait()
	Char.HumanoidRootPart.CFrame = Point
--	until (Char.HumanoidRootPart.Position - Point.Position).Magnitude <= 20
end
function BTP(Pos)
	local Ply = game.Players.LocalPlayer
	local Char = Ply.Character
	Char.HumanoidRootPart.CFrame = Pos
	wait()
	Char.HumanoidRootPart.CFrame = Pos
end

spawn(function()
while task.wait() do
pcall(function()
if _G.AutoConfetti then
for i,v in pairs(game.Workspace.NPCs:GetChildren()) do
	game:GetService("ReplicatedStorage").Remotes.Celebration:InvokeServer('TalkNpc',workspace.NPCs[v.Name])
end
end
end)
end
end)

spawn(function()
while task.wait() do
pcall(function()
	if _G.AutoConfetti then
		if game.PlaceId == 4442272183 then
			TP(CFrame.new(-11.848626136779785, 19.311767578125, 2828.531005859375))
			TP(CFrame.new(-375.93408203125, 73.11296844482422, 1180.5146484375))
			TP(CFrame.new(-378.0177001953125, 73.05511474609375, 287.2165222167969))
			TP(CFrame.new(-2070.090576171875, 72.37596893310547, -2689.849853515625))
			TP(CFrame.new(-5365.74462890625, 9.003767013549805, -705.3399658203125))
			TP(CFrame.new(880.24462890625, 125.09214782714844, 32865.26171875))
			TP(CFrame.new(-5610.93798828125, 18.35700798034668, -5015.65869140625))
			TP(CFrame.new(-3014.4755859375, 29.575407028198242, -9777.16015625))
			TP(CFrame.new(113.77246856689453, 401.45697021484375, -5192.54248046875))
			TP(CFrame.new(5585.3740234375, 12.449106216430664, -5954.33349609375))
		elseif game.PlaceId == 7449423635 then
			TP(CFrame.new(-259.380126953125, 6.764979839324951, 5254.09912109375))
			TP(CFrame.new(-1932.3507080078125, 13.824933052062988, -11636.8515625))
			TP(CFrame.new(-929.170166015625, 7.802646160125732, -10826.3876953125))
			TP(CFrame.new(497.3184509277344, 24.76936149597168, -12418.55859375))
			TP(CFrame.new(-47.42597961425781, 16.97955322265625, -11992.779296875))
			TP(CFrame.new(2245.78271484375, 12.776296615600586, -6353.974609375))
			TP(CFrame.new(-9515.0009765625, 142.1398468017578, 5534.05029296875))
			TP(CFrame.new(-9512.8896484375, 21.139892578125, 4641.02978515625))
			TP(CFrame.new(4732.6533203125, 51.589698791503906, -1414.252197265625))
			TP(CFrame.new(5277.3388671875, 602.0785522460938, 363.35223388671875))
			TP(CFrame.new(3371.987060546875, 38.98302459716797, 1593.1405029296875))
			TP(CFrame.new(-2045.0103759765625, 38.138248443603516, -10041.935546875))
			TP(CFrame.new(-5116.79931640625, 314.550537109375, -2964.70068359375))
			TP(CFrame.new(-4598.1025390625, 16.455780029296875, -2705.09619140625))
			TP(CFrame.new(-6069.4306640625, 16.455780029296875, -2160.60205078125))
			TP(CFrame.new(-11385.6767578125, 331.75823974609375, -10405.916015625))
			TP(CFrame.new(-9603.1591796875, 46.55657196044922, -8365.3828125))
			TP(CFrame.new(-12545.2353515625, 337.20330810546875, -7454.07470703125))
		else
			TP(CFrame.new(-2550.043212890625, 6.890709400177002, 2047.015625))
			TP(CFrame.new(-1248.0438232421875, 2.6870851516723633, 1716.0859375))
			TP(CFrame.new(-459.51275634765625, 7.687240123748779, 1455.679443359375))
			TP(CFrame.new(-572.7285766601562, 7.687240123748779, 1797.2501220703125))
			TP(CFrame.new(781.9508666992188, 5.761781215667725, 1492.8056640625))
			TP(CFrame.new(949.3020629882812, 16.55164909362793, 1421.4573974609375))
			TP(CFrame.new(1115.21484375, 7.338680744171143, -1159.033935546875))
			TP(CFrame.new(3876.05029296875, 5.4081878662109375, -1907.011474609375))
			TP(CFrame.new(5087.5341796875, 48.43275833129883, 4126.625))
			TP(CFrame.new(-1135.5067138671875, 4.787090301513672, 3821.385498046875))
			TP(CFrame.new(881.5269775390625, 3.4771769046783447, 4100.76611328125))
			TP(CFrame.new(-4830.9208984375, 20.68707275390625, 4373.51953125))
			TP(CFrame.new(-5206.47998046875, 4.308171272277832, 8430.990234375))
			TP(CFrame.new(-1324.8131103515625, 11.88819408416748, 500.3249816894531))
			TP(CFrame.new(-1439.505615234375, 7.32259464263916, -2801.103515625))
			TP(CFrame.new(-4935.75830078125, 2.8822989463806152, -2325.49462890625))
			TP(CFrame.new(-4874.67578125, 717.705078125, -2625.676513671875))
			TP(CFrame.new(-7884.97900390625, 5545.6123046875, -361.72772216796875))
			TP(CFrame.new(4861.38330078125, 5.687756061553955, 741.5126342773438))
		end
	end
end)
end
end)

spawn(function()
local vu = game:GetService("VirtualUser")
game:GetService("Players").LocalPlayer.Idled:connect(function()
	vu:Button2Down(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
	wait(1)
	vu:Button2Up(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
end)
end)
    if World1 then
	Main:Toggle("Auto Second Sea",false,function(vu)
		_G.SOLSecond = vu
		StopTween(_G.SOLSecond)
		if value == false then
			getgenv().ToTarget(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame)
			getgenv().ToTarget(game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame)
		end
    end)
end
    if World2 then
	Main:Toggle("Auto Third Sea",false,function(value)
		getgenv().AutoThirdSea = value
		StopTween(getgenv().AutoThirdSea)
		if value == false then
			getgenv().ToTarget(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame)
			getgenv().ToTarget(game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame)
		end
    end)
end
Main:Toggle("Black Screen",false,function(value)
	StartBlackScreen = value
	local BlackScreen = game:GetService("Players").LocalPlayer.PlayerGui.Main.Blackscreen
	getgenv().DefaultSize = BlackScreen.Size
	getgenv().NewSize = UDim2.new(500, 0, 500, 500)
	getgenv().StartBlackScreen = false
	if StartBlackScreen then
		BlackScreen.Size = NewSize
	else
		BlackScreen.Size = UDim2.new(DefaultSize)
	end
	_G.WhiteScreen = value
	if _G.WhiteScreen == true then
		game:GetService("RunService"):Set3dRenderingEnabled(false)
	elseif _G.WhiteScreen == false then
		game:GetService("RunService"):Set3dRenderingEnabled(true)
	end
end)
Main:Toggle("Auto Confetti",_G.AutoConfetti,function(value)
	_G.AutoConfetti = value
StopTween(_G.AutoConfetti)


if value == false then
getgenv().ToTarget(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame)
getgenv().ToTarget(game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame)
topos(game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame)
topos(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame)
_G.Bypass = false
end

end)
Main:Toggle("Bypass TP (Working)",_G.Bypassse,function(value)
	_G.Bypassse = value
end)

if World1 then
	Main:Label("🎄 Pole 🎄")
Main:Toggle("Auto Pole",false,function(value)
	_G.Auto_Pole = value
	StopTween(_G.Auto_Pole)
end)
end
if World1 then
Main:Toggle("Auto Pole Hop",false,function(value)
	_G.Auto_Pole_Hop = value
end)
end
if World2 then
	Main:Label("🎄 Factory 🎄")
	Main:Toggle("Auto Factory",false,function(value)
		_G.AutoFactory = value
		StopTween(_G.AutoFactory)
	end)
	end
	if World2 then
		Main:Toggle("Auto Acidum Rifle",false,function(value)
			_G.AutoFactory = value
			StopTween(_G.AutoFactory)
		end)
		end
		spawn(function()
			while wait() do
				pcall(function()
					if _G.AutoFactory then
						if game:GetService("Workspace").Enemies:FindFirstChild("Core") then
							for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
								if v.Name == "Core" and v.Humanoid.Health > 0 then
									repeat task.wait()
										AutoHaki()         
										EquipWeapon(_G.SelectWeapon)           
										topos(CFrame.new(448.46756, 199.356781, -441.389252))                                  
										game:GetService("VirtualUser"):CaptureController()
										game:GetService("VirtualUser"):Button1Down(Vector2.new(1280,672))
		_G.Fast_Attack_Normal = true;
									until v.Humanoid.Health <= 0 or _G.AutoFactory == false
								end
							end
						else
							topos(CFrame.new(448.46756, 199.356781, -441.389252))
						end
					end
				end)
			end
		end)
		spawn(function()
			while wait() do
				if _G.AutoBuyLegendarySword then
					pcall(function()
						local args = {
							[1] = "LegendarySwordDealer",
							[2] = "1"
						}
						game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
						local args = {
							[1] = "LegendarySwordDealer",
							[2] = "2"
						}
						game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
						local args = {
							[1] = "LegendarySwordDealer",
							[2] = "3"
						}
						game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
						if _G.AutoBuyLegendarySword_Hop and _G.AutoBuyLegendarySword and World2 then
							wait(10)
							Hop()
						end
					end)
				end 
			end
		end)
		if World2 then
			Main:Label("🎊 LegendarySword 🎊")
			Main:Toggle("Buy Legendary",false,function(value)
				_G.AutoBuyLegendarySword = value
			end)
			end
			if World2 then
			Main:Toggle("Legendary Hop",false,function(value)
				_G.AutoBuyLegendarySword_Hop = value
			end)
			end
			if World2 then
				Main:Label("🎄 Swan Glasses 🎄")
				Main:Toggle("Auto Swan Glasses",false,function(value)
					_G.AutoFarmSwanGlasses = value
					StopTween(_G.AutoFarmSwanGlasses)
				end)
				end
				if World2 then
				Main:Toggle("Swan Glasses Hop",false,function(value)
					_G.AutoFarmSwanGlasses_Hop = value
				end)
				end
if World2 then
	Main:Label("🎊 Dragon Trident 🎊")
	Main:Toggle("Auto Dragon Trident",false,function(value)
		_G.AutoTideKeeper = value
		StopTween(_G.AutoTideKeeper)
	end)
	end
	if World2 then
	Main:Toggle("Dragon Trident Hop ",false,function(value)
		_G.AutoTideKeeperHop = value
	end)
	end
	spawn(function()
        while wait() do
            if  _G.AutoOderSword then
                pcall(function()
                    if game:GetService("Workspace").Enemies:FindFirstChild("Order [Lv. 1250] [Raid Boss]") then
                        for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                            if v.Name == "Order [Lv. 1250] [Raid Boss]" then
                                if v:FindFirstChild("Humanoid") and v:FindFirstChild("HumanoidRootPart") and v.Humanoid.Health > 0 then
                                    repeat task.wait()
                                        AutoHaki()
                                        EquipWeapon(_G.SelectWeapon)
                                        v.HumanoidRootPart.CanCollide = false
										v.Humanoid.JumpPower = 0;
										v.Humanoid.WalkSpeed = 0;
                                        v.HumanoidRootPart.Size = Vector3.new(150,150,150)
                                        topos(v.HumanoidRootPart.CFrame * CFrame.new(0,20,0))
										_G.FastAttackF2 = true
                                        game:GetService("VirtualUser"):CaptureController()
                                        game:GetService("VirtualUser"):Button1Down(Vector2.new(1280,672))
                                        sethiddenproperty(game.Players.LocalPlayer,"SimulationRadius",math.huge)
                                    until not  _G.AutoOderSword or not v.Parent or v.Humanoid.Health <= 0
                                end
                            end
                        end
                    else
                        if game:GetService("ReplicatedStorage"):FindFirstChild("Order [Lv. 1250] [Raid Boss]") then
                            topos(game:GetService("ReplicatedStorage"):FindFirstChild("Order [Lv. 1250] [Raid Boss]").HumanoidRootPart.CFrame * CFrame.new(2,20,2))
                        else
                            if  _G.AutoOderSwordHop then
                                Hop()
                            end
                        end
                    end
                end)
            end
        end
    end)
    
    spawn(function()
        while wait() do
            if _G.AutoBudySword then
                pcall(function()
                    if game:GetService("Workspace").Enemies:FindFirstChild("Cake Queen [Lv. 2175] [Boss]") then
                        for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                            if v.Name == "Cake Queen [Lv. 2175] [Boss]" then
                                if v:FindFirstChild("Humanoid") and v:FindFirstChild("HumanoidRootPart") and v.Humanoid.Health > 0 then
                                    repeat task.wait()
                                        AutoHaki()
                                        EquipWeapon(_G.SelectWeapon)
                                        v.HumanoidRootPart.CanCollide = false
										v.Humanoid.JumpPower = 0;
										v.Humanoid.WalkSpeed = 0;
                                        v.HumanoidRootPart.Size = Vector3.new(50,150,50)
                                        topos(v.HumanoidRootPart.CFrame * CFrame.new(0,20,0))
                                        game:GetService("VirtualUser"):CaptureController()
                                        game:GetService("VirtualUser"):Button1Down(Vector2.new(1280,672))
                                        sethiddenproperty(game.Players.LocalPlayer,"SimulationRadius",math.huge)
                                    until not _G.AutoBudySword or not v.Parent or v.Humanoid.Health <= 0
                                end
                            end
                        end
                    else
                        if game:GetService("ReplicatedStorage"):FindFirstChild("Cake Queen [Lv. 2175] [Boss]") then
                            topos(game:GetService("ReplicatedStorage"):FindFirstChild("Cake Queen [Lv. 2175] [Boss]").HumanoidRootPart.CFrame * CFrame.new(2,20,2))
                        else
                            if _G.AutoBudySwordHop then
                                Hop()
                            end
                        end
                    end
                end)
            end
        end
    end)
    spawn(function()
        while wait() do
            if _G.AutoFarmBossHallow then
                pcall(function()
                    if game:GetService("Workspace").Enemies:FindFirstChild("Soul Reaper [Lv. 2100] [Raid Boss]") then
                        for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                            if string.find(v.Name , "Soul Reaper") then
                                repeat task.wait()
                                    EquipWeapon(_G.SelectWeapon)
                                    AutoHaki()
                                    v.HumanoidRootPart.Size = Vector3.new(50,50,50)
                                    topos(v.HumanoidRootPart.CFrame*CFrame.new(2,20,2))
                                    game:GetService("VirtualUser"):CaptureController()
                                    game:GetService("VirtualUser"):Button1Down(Vector2.new(1280, 670))
                                    v.HumanoidRootPart.Transparency = 1
                                    sethiddenproperty(game.Players.LocalPlayer,"SimulationRadius",math.huge)
                                until v.Humanoid.Health <= 0 or _G.AutoFarmBossHallow == false
                            end
                        end
                    elseif game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Hallow Essence") or game:GetService("Players").LocalPlayer.Character:FindFirstChild("Hallow Essence") then
                        repeat topos(CFrame.new(-8932.322265625, 146.83154296875, 6062.55078125)) wait() until (CFrame.new(-8932.322265625, 146.83154296875, 6062.55078125).Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 8                        
                        EquipWeapon("Hallow Essence")
                    else
                        if game:GetService("ReplicatedStorage"):FindFirstChild("Soul Reaper [Lv. 2100] [Raid Boss]") then
                            topos(game:GetService("ReplicatedStorage"):FindFirstChild("Soul Reaper [Lv. 2100] [Raid Boss]").HumanoidRootPart.CFrame * CFrame.new(2,20,2))
                        else
                            if _G.AutoFarmBossHallowHop then
                                Hop()
                            end
                        end
                    end
                end)
            end
        end
    end)
    spawn(function()
        pcall(function()
            while wait() do
                if (_G.AutoDarkDagger_Hop and _G.AutoDarkDagger) and World3 and not game:GetService("ReplicatedStorage"):FindFirstChild("rip_indra True Form [Lv. 5000] [Raid Boss]") and not game:GetService("Workspace").Enemies:FindFirstChild("rip_indra True Form [Lv. 5000] [Raid Boss]") then
                    Hop()
                end
            end
        end)
    end)
	if World2 then
		Main:Label("😎 Long Sword 😎")

		Main:Toggle("Auto Long Sword",false,function(value)
            _G.AutoSwordSword = value
            StopTween(_G.AutoSwordSword)
		end)
		end
		if World2 then
			Main:Toggle("Long Sword Hop",false,function(value)
				_G.AutoSwordHop = value
			end)
		end
	if World2 then
		Main:Label("👻 Law Sword 👻")
		Main:Button("Buy Microchip",function()
			local args = {
				[1] = "BlackbeardReward",
				[2] = "Microchip",
				[3] = "2"
			 }
			 game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
		end)
		Main:Toggle("Auto Law Sword",false,function(value)
            _G.AutoOderSword = value
            StopTween( _G.AutoOderSword)
             if World2 then
                fireclickdetector(game:GetService("Workspace").Map.CircleIsland.RaidSummon.Button.Main.ClickDetector)
            end
		end)
		end
		if World2 then
			Main:Toggle("Law Sword Hop",false,function(value)
				_G.AutoOderSwordHop = value
			end)
		end
		spawn(function()
			pcall(function()
				while wait() do
					if _G.AutoDarkDagger then
						if game:GetService("Workspace").Enemies:FindFirstChild("rip_indra True Form [Lv. 5000] [Raid Boss]") or game:GetService("Workspace").Enemies:FindFirstChild("rip_indra [Lv. 5000] [Raid Boss]") then
							for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
								if v.Name == ("rip_indra True Form [Lv. 5000] [Raid Boss]" or v.Name == "rip_indra [Lv. 5000] [Raid Boss]") and v.Humanoid.Health > 0 and v:IsA("Model") and v:FindFirstChild("Humanoid") and v:FindFirstChild("HumanoidRootPart") then
									repeat task.wait()
										pcall(function()
											AutoHaki()
											EquipWeapon(_G.SelectWeapon)
											v.HumanoidRootPart.CanCollide = false
											v.HumanoidRootPart.Size = Vector3.new(70,70,70)
											v.Humanoid.JumpPower = 0
											v.Humanoid.WalkSpeed = 0
											topos(v.HumanoidRootPart.CFrame * CFrame.new(0,30,0))
											game:GetService("VirtualUser"):CaptureController()
											game:GetService("VirtualUser"):Button1Down(Vector2.new(1280, 670),workspace.CurrentCamera.CFrame)
										end)
									until _G.AutoDarkDagger == false or v.Humanoid.Health <= 0
								end
							end
						else
							topos(CFrame.new(-5344.822265625, 423.98541259766, -2725.0930175781))
						end
					end
				end
			end)
		end)
	if World3 then
		Main:Label("👻 Buddy Sword 👻")
		Main:Toggle("Auto Buddy Sword",false,function(value)
            _G.AutoBudySword = value
            StopTween(_G.AutoBudySword)
		end)
		end
		if World3 then
		Main:Toggle("Buddy Sword Hop",false,function(value)
			_G.AutoBudySwordHop = value
		end)
		end
		if World3 then
			Main:Label("🎩 Valkyrie Helmet 🎩")
			Main:Toggle("Valkyrie Helmet",false,function(value)
				_G.AutoDarkDagger = value
				StopTween(_G.AutoDarkDagger)
			end)
			end
			if World3 then
			Main:Toggle("Valkyrie Helmet Hop",false,function(value)
				_G.AutoDarkDagger_Hop = value
			end)
			end
			if World3 then
				Main:Label("🎃 Dark Dagger 🎃")
				Main:Toggle("Auto Dark Dagger",false,function(value)
					_G.AutoDarkDagger = value
					StopTween(_G.AutoDarkDagger)
				end)
				end
				if World3 then
				Main:Toggle("Dark Dagger Hop",false,function(value)
					_G.AutoDarkDagger_Hop = value
				end)
				end
				if World3 then
					Main:Label("✨ Serpent Bow ✨")
					Main:Toggle("Auto Serpent Bow",false,function(value)
						_G.Auto_kill_Empress = value
						StopTween(_G.Auto_kill_Empress)
					end)
					end
					if World3 then
					Main:Toggle("Serpent Bow Hop",false,function(value)
						_G.Auto_kill_EmpressHop = value
					end)
					end
					if World3 then
						Main:Label("🧵 Twin Hooks 🧵")
						Main:Toggle("Auto Twin Hooks",false,function(value)
							_G.Auto_kill_Captain  = value
							StopTween(_G.Auto_kill_Captain)
						end)
						end
						if World3 then
						Main:Toggle("Twin Hooks Hop",false,function(value)
							_G.Auto_kill_CaptainHop = value
						end)
						end
						if World3 then
							Main:Label("🎗 Canvander 🎗")
							Main:Toggle("Auto Canvander",false,function(value)
								_G.Auto_kill_Canvander = value
								StopTween(_G.Auto_kill_Canvander)
							end)
							end
							if World3 then
								Main:Toggle("Canvander Hop",false,function(value)
									_G.Auto_kill_CaptainHops = value
								end)
								end
					

								
								spawn(function()
									while wait() do
										pcall(function()
											if _G.AutoTideKeeper and game.ReplicatedStorage:FindFirstChild("Tide Keeper [Lv. 1475] [Boss]") or game.Workspace.Enemies:FindFirstChild("Tide Keeper [Lv. 1475] [Boss]") then
												if game.Workspace.Enemies:FindFirstChild("Tide Keeper [Lv. 1475] [Boss]") then
													for i,v in pairs(game.Workspace.Enemies:GetChildren()) do
														if _G.AutoTideKeeper and v.Name == "Tide Keeper [Lv. 1475] [Boss]" and v:FindFirstChild("HumanoidRootPart") and v:FindFirstChild("Humanoid") and v.Humanoid.Health > 0 then
															repeat wait()  
																AutoHaki()
																EquipWeapon(_G.SelectWeapon)
																topos(v.HumanoidRootPart.CFrame * CFrame.new(0,30,0))
																v.Humanoid.JumpPower = 0;
																v.Humanoid.WalkSpeed = 0;
																v.HumanoidRootPart.Size = Vector3.new(150, 150, 150)
																game:GetService'VirtualUser':CaptureController()
																game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
															until not _G.AutoTideKeeper or v.Humanoid.Health <= 0 or not v.Parent
														end
													end
												else
													topos(CFrame.new(-3709.56055, 77.2797546, -11452.0762, -0.924486399, 1.25095809e-08, -0.381215006, 4.84416063e-09, 1, 2.10674287e-08, 0.381215006, 1.76298851e-08, -0.924486399))
												end
											else
												if _G.AutoTideKeeperHop then
													Hop()
												end
											end
										end)
									end
								end)
	
spawn(function()
	while wait() do
		pcall(function()
			if _G.AutoSwordSword and game.ReplicatedStorage:FindFirstChild("Diamond [Lv. 750] [Boss]") or game.Workspace.Enemies:FindFirstChild("Diamond [Lv. 750] [Boss]") then
				if game.Workspace.Enemies:FindFirstChild("Diamond [Lv. 750] [Boss]") then
					for i,v in pairs(game.Workspace.Enemies:GetChildren()) do
						if _G.AutoSwordSword and v.Name == "Diamond [Lv. 750] [Boss]" and v:FindFirstChild("HumanoidRootPart") and v:FindFirstChild("Humanoid") and v.Humanoid.Health > 0 then
							repeat wait()  
								AutoHaki()
								EquipWeapon(_G.SelectWeapon)
								topos(v.HumanoidRootPart.CFrame * CFrame.new(0,30,0))
								v.Humanoid.JumpPower = 0;
								v.Humanoid.WalkSpeed = 0;
								v.HumanoidRootPart.Size = Vector3.new(150, 150, 150)
								game:GetService'VirtualUser':CaptureController()
								game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
							until not _G.AutoSwordSword or v.Humanoid.Health <= 0 or not v.Parent
						end
					end
				else
					topos(CFrame.new(-1670.40186, 411.318787, -137.068939, 0.311598331, -1.12171126e-08, -0.950213909, -5.49143238e-08, 1, -2.98125755e-08, 0.950213909, 6.14699047e-08, 0.311598331))
				end
			else
				if _G.AutoSwordHop then
					Hop()
				end
			end
		end)
	end
end)


spawn(function()
	while wait() do
		pcall(function()
			if _G.Auto_Pole and game.ReplicatedStorage:FindFirstChild("Thunder God [Lv. 575] [Boss]") or game.Workspace.Enemies:FindFirstChild("Thunder God [Lv. 575] [Boss]") then
				if game.Workspace.Enemies:FindFirstChild("Thunder God [Lv. 575] [Boss]") then
					for i,v in pairs(game.Workspace.Enemies:GetChildren()) do
						if _G.Auto_Pole and v.Name == "Thunder God [Lv. 575] [Boss]" and v:FindFirstChild("HumanoidRootPart") and v:FindFirstChild("Humanoid") and v.Humanoid.Health > 0 then
							repeat wait()  
								AutoHaki()
								EquipWeapon(_G.SelectWeapon)
								topos(v.HumanoidRootPart.CFrame * CFrame.new(0,17,0))
								v.Humanoid.JumpPower = 0;
								v.Humanoid.WalkSpeed = 0;
								v.HumanoidRootPart.Size = Vector3.new(150, 150, 150)
								game:GetService'VirtualUser':CaptureController()
								game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
							until not _G.Auto_Pole or v.Humanoid.Health <= 0 or not v.Parent
						end
					end
				else
					topos(CFrame.new(-7900.66406, 5606.90918, -2267.46436))
				end
			else
				if _G.Auto_Pole_Hop then
					Hop()
				end
			end
		end)
	end
end)
spawn(function()
	while wait() do
		pcall(function()
			if _G.Auto_kill_Empress and game.ReplicatedStorage:FindFirstChild("Island Empress [Lv. 1675] [Boss]") or game.Workspace.Enemies:FindFirstChild("Island Empress [Lv. 1675] [Boss]") then
				if game.Workspace.Enemies:FindFirstChild("Island Empress [Lv. 1675] [Boss]") then
					for i,v in pairs(game.Workspace.Enemies:GetChildren()) do
						if _G.Auto_kill_Empress and v.Name == "Island Empress [Lv. 1675] [Boss]" and v:FindFirstChild("HumanoidRootPart") and v:FindFirstChild("Humanoid") and v.Humanoid.Health > 0 then
							repeat wait()  
								AutoHaki()
								EquipWeapon(_G.SelectWeapon)
								topos(v.HumanoidRootPart.CFrame * CFrame.new(0,30,0))
								v.HumanoidRootPart.Size = Vector3.new(150, 150, 150)
								v.Humanoid.JumpPower = 0
								v.Humanoid.WalkSpeed = 0
								_G.FastAttackF2 = true
								game:GetService'VirtualUser':CaptureController()
								game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
							until not _G.Auto_kill_Empress or v.Humanoid.Health <= 0 or not v.Parent
						end
					end
				else
					topos(CFrame.new(5571.94727, 648.725952, 198.545868, 0.0603555888, -2.16443682e-10, -0.998176932, -4.03472669e-08, 1, -2.65646949e-09, 0.998176932, 4.04340419e-08, 0.0603555888))
				end
			else
				if _G.Auto_kill_EmpressHop then
					Hop()
				end
			end
		end)
	end
end) 
spawn(function()
	while wait() do
		pcall(function()
			if _G.Auto_kill_Canvander and game.ReplicatedStorage:FindFirstChild("Beautiful Pirate [Lv. 1950] [Boss]") or game.Workspace.Enemies:FindFirstChild("Beautiful Pirate [Lv. 1950] [Boss]") then
				if game.Workspace.Enemies:FindFirstChild("Beautiful Pirate [Lv. 1950] [Boss]") then
					for i,v in pairs(game.Workspace.Enemies:GetChildren()) do
						if _G.Auto_kill_Canvander and v.Name == "Beautiful Pirate [Lv. 1950] [Boss]" and v:FindFirstChild("HumanoidRootPart") and v:FindFirstChild("Humanoid") and v.Humanoid.Health > 0 then
							repeat wait()  
								AutoHaki()
								EquipWeapon(_G.SelectWeapon)
								topos(v.HumanoidRootPart.CFrame * CFrame.new(0,20,0))
								v.HumanoidRootPart.Size = Vector3.new(150, 150, 150)
								v.Humanoid.JumpPower = 0
								v.Humanoid.WalkSpeed = 0
								_G.FastAttackF2 = true
								game:GetService'VirtualUser':CaptureController()
								game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
							until not _G.Auto_kill_Canvander or v.Humanoid.Health <= 0 or not v.Parent
						end
					end
				else
					topos(CFrame.new(5337.89746, 22.5177879, 164.948975, 0.979801893, -1.77746422e-08, 0.199970573, 1.86812272e-08, 1, -2.64669198e-09, -0.199970573, 6.32892938e-09, 0.979801893))
				end
			else
				if _G.Auto_kill_CaptainHops then
					Hop()
				end
			end
		end)
	end
end)
spawn(function()
	while wait() do
		pcall(function()
			if _G.Auto_kill_Captain and game.ReplicatedStorage:FindFirstChild("Captain Elephant [Lv. 1875] [Boss]") or game.Workspace.Enemies:FindFirstChild("Captain Elephant [Lv. 1875] [Boss]") then
				if game.Workspace.Enemies:FindFirstChild("Captain Elephant [Lv. 1875] [Boss]") then
					for i,v in pairs(game.Workspace.Enemies:GetChildren()) do
						if _G.Auto_kill_Captain and v.Name == "Captain Elephant [Lv. 1875] [Boss]" and v:FindFirstChild("HumanoidRootPart") and v:FindFirstChild("Humanoid") and v.Humanoid.Health > 0 then
							repeat wait()  
								AutoHaki()
								EquipWeapon(_G.SelectWeapon)
								topos(v.HumanoidRootPart.CFrame * CFrame.new(0,30,0))
								v.HumanoidRootPart.Size = Vector3.new(150, 150, 150)
								v.Humanoid.JumpPower = 0
								v.Humanoid.WalkSpeed = 0
								_G.FastAttackF2 = true
								game:GetService'VirtualUser':CaptureController()
								game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
							until not _G.Auto_kill_Captain or v.Humanoid.Health <= 0 or not v.Parent
						end
					end
				else
					topos(CFrame.new(-13381.6787, 367.055725, -8538.58887, -0.999389052, 9.01120123e-10, -0.0349510163, 6.98308245e-10, 1, 5.81495296e-09, 0.0349510163, 5.78699355e-09, -0.999389052))
				end
			else
				if _G.Auto_kill_CaptainHop then
					Hop()
				end
			end
		end)
	end
end)
spawn(function()
	while wait(.5) do
		if _G.AutoSuperhuman or _G.Auto_Fully_Superhuman and game.Players.LocalPlayer:FindFirstChild("WeaponAssetCache") then 
			pcall(function()
				if game:GetService("Players").LocalPlayer.Data.Beli.Value >= 500000 and (game.Players.LocalPlayer.Character:FindFirstChild("Combat") or game.Players.LocalPlayer.Backpack:FindFirstChild("Combat")) then
					_G.SelectWeapon = "Combat"
					local args = {
						[1] = "BuyElectro"
					}
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
				end   
				if game.Players.LocalPlayer.Character:FindFirstChild("Superhuman") or game.Players.LocalPlayer.Backpack:FindFirstChild("Superhuman") then
					_G.SelectWeapon = "Superhuman"
				end  
				if game.Players.LocalPlayer.Backpack:FindFirstChild("Black Leg") and game.Players.LocalPlayer.Backpack:FindFirstChild("Black Leg").Level.Value <= 299  then
					_G.SelectWeapon = "Black Leg"
				end
				if game.Players.LocalPlayer.Backpack:FindFirstChild("Electro") and game.Players.LocalPlayer.Backpack:FindFirstChild("Electro").Level.Value <= 299  then
					_G.SelectWeapon = "Electro"
				end
				if game.Players.LocalPlayer.Backpack:FindFirstChild("Fishman Karate") and game.Players.LocalPlayer.Backpack:FindFirstChild("Fishman Karate").Level.Value <= 299  then
					_G.SelectWeapon = "Fishman Karate"
				end
				if game.Players.LocalPlayer.Backpack:FindFirstChild("Dragon Claw") and game.Players.LocalPlayer.Backpack:FindFirstChild("Dragon Claw").Level.Value <= 299  then
					_G.SelectWeapon = "Dragon Claw"
				end
				if game.Players.LocalPlayer.Backpack:FindFirstChild("Black Leg") and game.Players.LocalPlayer.Backpack:FindFirstChild("Black Leg").Level.Value >= 300  then
					local args = {
						[1] = "BuyFishmanKarate"
					}
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
				end
				if game.Players.LocalPlayer.Character:FindFirstChild("Black Leg") and game.Players.LocalPlayer.Character:FindFirstChild("Black Leg").Level.Value >= 300  then
					local args = {
						[1] = "BuyFishmanKarate"
					}
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
				end
				if game.Players.LocalPlayer.Character:FindFirstChild("Electro") and game.Players.LocalPlayer.Character:FindFirstChild("Electro").Level.Value >= 300  then
					local args = {
						[1] = "BuyBlackLeg"
					}
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
				end
				if game.Players.LocalPlayer.Backpack:FindFirstChild("Fishman Karate") and game.Players.LocalPlayer.Backpack:FindFirstChild("Fishman Karate").Level.Value >= 300  then
					if getgenv().FullySuperhuman and game.Players.LocalPlayer.Data.Fragments.Value < 1500 then
						if game.Players.LocalPlayer.Data.Level.Value > 1100 then
							_G.SelectChip = "Flame"
							_G.Auto_Buy_Chips_Dungeon = true
							_G.Auto_Start_Dungeon = true
							_G.Auto_Next_Island = true
							_G.Kill_Aura = true
						end
					else
						_G.Auto_Buy_Chips_Dungeon = false
						_G.Auto_Start_Dungeon = false
						_G.Auto_Next_Island = false
						_G.Kill_Aura = false
						local args = {
							[1] = "BlackbeardReward",
							[2] = "DragonClaw",
							[3] = "2"
						}
						game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
					end
				end
				if game.Players.LocalPlayer.Character:FindFirstChild("Fishman Karate") and game.Players.LocalPlayer.Character:FindFirstChild("Fishman Karate").Level.Value >= 300  then
					if getgenv().FullySuperhuman and game.Players.LocalPlayer.Data.Fragments.Value < 1500 then
						if game.Players.LocalPlayer.Data.Level.Value > 1100 then
							_G.SelectChip = "Flame"
							_G.Auto_Buy_Chips_Dungeon = true
							_G.Auto_Start_Dungeon = true
							_G.Auto_Next_Island = true
							_G.Kill_Aura = true
						end
					else
						_G.Auto_Buy_Chips_Dungeon = false
						_G.Auto_Start_Dungeon = false
						_G.Auto_Next_Island = false
						_G.Kill_Aura = false
						local args = {
							[1] = "BlackbeardReward",
							[2] = "DragonClaw",
							[3] = "2"
						}
						game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
					end
				end
				if game.Players.LocalPlayer.Backpack:FindFirstChild("Dragon Claw") and game.Players.LocalPlayer.Backpack:FindFirstChild("Dragon Claw").Level.Value >= 300  then
					local args = {
						[1] = "BuySuperhuman"
					}
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
				end
				if game.Players.LocalPlayer.Character:FindFirstChild("Dragon Claw") and game.Players.LocalPlayer.Character:FindFirstChild("Dragon Claw").Level.Value >= 300  then
					local args = {
						[1] = "BuySuperhuman"
					}
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
				end 
			end)
		end
	end
end)
spawn(function()
	game:GetService("RunService").RenderStepped:Connect(function()
	 pcall(function()
		 if _G.AutoFarm then
		 
		 if game:GetService("Workspace").Enemies[Ms].Humanoid.Health == 0 then
game:GetService("Workspace").Enemies[Ms]:Destroy()
end
end
end)
end)
					end)
spawn(function()
	while wait() do
		if _G.Auto_Buy_Chips_Dungeon then
			pcall(function()
				local args = {
					[1] = "RaidsNpc",
					[2] = "Select",
					[3] = _G.SelectChip
				}
				
				game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
			end)
		end
	end
end)
spawn(function()
	while wait() do
		if _G.Auto_Start_Dungeon then
			pcall(function()
				if World2 then
					if not game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 1") then
						if game.Players.LocalPlayer.Backpack:FindFirstChild("Special Microchip") then 
							fireclickdetector(game.Workspace.Map.CircleIsland.RaidSummon2.Button.Main.ClickDetector)
						end
					end
				elseif World3 then
					if not game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 1") then
						if game.Players.LocalPlayer.Backpack:FindFirstChild("Special Microchip") then
							fireclickdetector(game.Workspace.Map["Boat Castle"].RaidSummon2.Button.Main.ClickDetector)
						end
					end
				end
			end)
		end
	end
end)
spawn(function()
	while wait() do
		if _G.Auto_Next_Island then
			if not game.Players.LocalPlayer.PlayerGui.Main.Timer.Visible == false then
				if game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 5") then
					getgenv().ToTarget(game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 5").CFrame * CFrame.new(0,70,100))
				elseif game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 4") then
					getgenv().ToTarget(game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 4").CFrame * CFrame.new(0,70,100))
				elseif game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 3") then
					getgenv().ToTarget(game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 3").CFrame * CFrame.new(0,70,100))
				elseif game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 2") then
					getgenv().ToTarget(game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 2").CFrame * CFrame.new(0,70,100))
				elseif game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 1") then
					getgenv().ToTarget(game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 1").CFrame * CFrame.new(0,70,100))
				end
			end
		end
	end
end)
spawn(function()
	while wait() do
		if _G.Kill_Aura then
			for i,v in pairs(game.Workspace.Enemies:GetDescendants()) do
				if v:FindFirstChild("Humanoid") and v:FindFirstChild("HumanoidRootPart") and v.Humanoid.Health > 0 then
					pcall(function()
						repeat wait(.1)
							v.Humanoid.Health = 0
							v.HumanoidRootPart.CanCollide = false
							sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius", math.huge)
						until not _G.Kill_Aura  or not v.Parent or v.Humanoid.Health <= 0
					end)
				end
			end
		end
	end
end)
spawn(function()
	while wait() do
		if getgenv().DragonTalon then
			if game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Dragon Claw") or game:GetService("Players").LocalPlayer.Character:FindFirstChild("Dragon Claw") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Dragon Talon") or game:GetService("Players").LocalPlayer.Character:FindFirstChild("Dragon Talon") then
				if game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Dragon Claw") and game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Dragon Claw").Level.Value >= 400 then
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyDragonTalon")
					_G.SelectWeapon = "Dragon Talon"
				end  
				if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Dragon Claw") and game:GetService("Players").LocalPlayer.Character:FindFirstChild("Dragon Claw").Level.Value >= 400 then
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyDragonTalon")
					_G.SelectWeapon = "Dragon Talon"
				end  
				if game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Dragon Claw") and game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Dragon Claw").Level.Value <= 399 then
					_G.SelectWeapon = "Dragon Claw"
				end 
			else 
				game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BlackbeardReward","DragonClaw","2")
			end
		end
	end
end)

spawn(function()
	pcall(function()
		while wait() do 
			if getgenv().ElectricClaw then
				if game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Electro") or game:GetService("Players").LocalPlayer.Character:FindFirstChild("Electro") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Electric Claw") or game:GetService("Players").LocalPlayer.Character:FindFirstChild("Electric Claw") then
					if game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Electro") and game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Electro").Level.Value >= 400 then
						game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyElectricClaw")
						_G.SelectWeapon = "Electric Claw"
					end  
					if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Electro") and game:GetService("Players").LocalPlayer.Character:FindFirstChild("Electro").Level.Value >= 400 then
						game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyElectricClaw")
						_G.SelectWeapon = "Electric Claw"
					end  
					if game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Electro") and game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Electro").Level.Value <= 399 then
						_G.SelectWeapon = "Electro"
					end 
				else
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyElectro")
				end
			end
			if _G.AutoElectricClaw then
				if game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Electro") or game:GetService("Players").LocalPlayer.Character:FindFirstChild("Electro") then
					if game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Electro") or game:GetService("Players").LocalPlayer.Character:FindFirstChild("Electro") and game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Electro").Level.Value >= 400 or game:GetService("Players").LocalPlayer.Character:FindFirstChild("Electro").Level.Value >= 400 then
						if _G.AutoFarm == false then
							repeat task.wait()
								topos(CFrame.new(-10371.4717, 330.764496, -10131.4199))
							until not getgenv().ElectricClaw or (game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position - CFrame.new(-10371.4717, 330.764496, -10131.4199).Position).Magnitude <= 10
							game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyElectricClaw","Start")
							wait(2)
							repeat task.wait()
								topos(CFrame.new(-12550.532226563, 336.22631835938, -7510.4233398438))
							until not getgenv().ElectricClaw or (game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position - CFrame.new(-12550.532226563, 336.22631835938, -7510.4233398438).Position).Magnitude <= 10
							wait(1)
							repeat task.wait()
								topos(CFrame.new(-10371.4717, 330.764496, -10131.4199))
							until not getgenv().ElectricClaw or (game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position - CFrame.new(-10371.4717, 330.764496, -10131.4199).Position).Magnitude <= 10
							wait(1)
							game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyElectricClaw")
						elseif _G.AutoFarm == true then
							_G.AutoFarm = false
							wait(1)
							repeat task.wait()
								topos(CFrame.new(-10371.4717, 330.764496, -10131.4199))
							until not getgenv().ElectricClaw or (game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position - CFrame.new(-10371.4717, 330.764496, -10131.4199).Position).Magnitude <= 10
							game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyElectricClaw","Start")
							wait(2)
							repeat task.wait()
								topos(CFrame.new(-12550.532226563, 336.22631835938, -7510.4233398438))
							until not getgenv().ElectricClaw or (game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position - CFrame.new(-12550.532226563, 336.22631835938, -7510.4233398438).Position).Magnitude <= 10
							wait(1)
							repeat task.wait()
								topos(CFrame.new(-10371.4717, 330.764496, -10131.4199))
							until not getgenv().ElectricClaw or (game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position - CFrame.new(-10371.4717, 330.764496, -10131.4199).Position).Magnitude <= 10
							wait(1)
							game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyElectricClaw")
							_G.SelectWeapon = "Electric Claw"
							wait(.1)
							_G.AutoFarm = true
						end
					end
				end
			end
		end
	end)
end)
spawn(function()
	pcall(function()
		while wait() do
			if getgenv().Sharkman then
				game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyFishmanKarate")
				if string.find(game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySharkmanKarate"), "keys") then  
					if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Water Key") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Water Key") then
						topos(CFrame.new(-2604.6958, 239.432526, -10315.1982, 0.0425701365, 0, -0.999093413, 0, 1, 0, 0.999093413, 0, 0.0425701365))
						game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySharkmanKarate")
					elseif game:GetService("Players").LocalPlayer.Character:FindFirstChild("Fishman Karate") and game:GetService("Players").LocalPlayer.Character:FindFirstChild("Fishman Karate").Level.Value >= 400 then
					else 
						Ms = "Tide Keeper [Lv. 1475] [Boss]"
						if game:GetService("Workspace").Enemies:FindFirstChild(Ms) then   
							for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
								if v.Name == Ms then    
									OldCFrameShark = v.HumanoidRootPart.CFrame
									repeat task.wait()
										AutoHaki()
										EquipWeapon(_G.SelectWeapon)
										v.Head.CanCollide = false
										v.Humanoid.WalkSpeed = 0
										v.HumanoidRootPart.CanCollide = false
										v.HumanoidRootPart.Size = Vector3.new(50,50,50)
										v.HumanoidRootPart.CFrame = OldCFrameShark
										topos(v.HumanoidRootPart.CFrame*CFrame.new(2,20,2))
										game:GetService("VirtualUser"):CaptureController()
										game:GetService("VirtualUser"):Button1Down(Vector2.new(1280, 670))
										sethiddenproperty(game:GetService("Players").LocalPlayer,"SimulationRadius",math.huge)
									until not v.Parent or v.Humanoid.Health <= 0 or getgenv().Sharkman == false or game:GetService("Players").LocalPlayer.Character:FindFirstChild("Water Key") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Water Key")
								end
							end
						else
							topos(CFrame.new(-3570.18652, 123.328949, -11555.9072, 0.465199202, -1.3857326e-08, 0.885206044, 4.0332897e-09, 1, 1.35347511e-08, -0.885206044, -2.72606271e-09, 0.465199202))
							wait(3)
						end
					end
				else 
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySharkmanKarate")
				end
			end
		end
	end)
end)
spawn(function()
	while wait() do wait()
		if getgenv().FullyDeathStep then
			if game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Black Leg") or game:GetService("Players").LocalPlayer.Character:FindFirstChild("Black Leg") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Death Step") or game:GetService("Players").LocalPlayer.Character:FindFirstChild("Death Step") then
				if game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Black Leg") and game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Black Leg").Level.Value >= 450 then
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyDeathStep")
					_G.SelectWeapon = "Death Step"
				end  
				if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Black Leg") and game:GetService("Players").LocalPlayer.Character:FindFirstChild("Black Leg").Level.Value >= 450 then
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyDeathStep")
					_G.SelectWeapon = "Death Step"
				end  
				if game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Black Leg") and game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Black Leg").Level.Value <= 449 then
					_G.SelectWeapon = "Black Leg"
				end 
			else 
				game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyBlackLeg")
			end
		end
	end
end)
spawn(function()
	pcall(function()
		while wait() do 
			if getgenv().Superhuman then
				if game.Players.LocalPlayer.Backpack:FindFirstChild("Combat") or game.Players.LocalPlayer.Character:FindFirstChild("Combat") and game:GetService("Players")["LocalPlayer"].Data.Beli.Value >= 150000 then
					UnEquipWeapon("Combat")
					wait(.1)
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyBlackLeg")
				end   
				if game.Players.LocalPlayer.Character:FindFirstChild("Superhuman") or game.Players.LocalPlayer.Backpack:FindFirstChild("Superhuman") then
					_G.SelectWeapon = "Superhuman"
				end  
				if game.Players.LocalPlayer.Backpack:FindFirstChild("Black Leg") or game.Players.LocalPlayer.Character:FindFirstChild("Black Leg") or game.Players.LocalPlayer.Backpack:FindFirstChild("Electro") or game.Players.LocalPlayer.Character:FindFirstChild("Electro") or game.Players.LocalPlayer.Backpack:FindFirstChild("Fishman Karate") or game.Players.LocalPlayer.Character:FindFirstChild("Fishman Karate") or game.Players.LocalPlayer.Backpack:FindFirstChild("Dragon Claw") or game.Players.LocalPlayer.Character:FindFirstChild("Dragon Claw") then
					if game.Players.LocalPlayer.Backpack:FindFirstChild("Black Leg") and game.Players.LocalPlayer.Backpack:FindFirstChild("Black Leg").Level.Value <= 299 then
						_G.SelectWeapon = "Black Leg"
					end
					if game.Players.LocalPlayer.Backpack:FindFirstChild("Electro") and game.Players.LocalPlayer.Backpack:FindFirstChild("Electro").Level.Value <= 299 then
						_G.SelectWeapon = "Electro"
					end
					if game.Players.LocalPlayer.Backpack:FindFirstChild("Fishman Karate") and game.Players.LocalPlayer.Backpack:FindFirstChild("Fishman Karate").Level.Value <= 299 then
						_G.SelectWeapon = "Fishman Karate"
					end
					if game.Players.LocalPlayer.Backpack:FindFirstChild("Dragon Claw") and game.Players.LocalPlayer.Backpack:FindFirstChild("Dragon Claw").Level.Value <= 299 then
						_G.SelectWeapon = "Dragon Claw"
					end
					if game.Players.LocalPlayer.Backpack:FindFirstChild("Black Leg") and game.Players.LocalPlayer.Backpack:FindFirstChild("Black Leg").Level.Value >= 300 and game:GetService("Players")["LocalPlayer"].Data.Beli.Value >= 300000 then
						UnEquipWeapon("Black Leg")
						wait(.1)
						game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyElectro")
					end
					if game.Players.LocalPlayer.Character:FindFirstChild("Black Leg") and game.Players.LocalPlayer.Character:FindFirstChild("Black Leg").Level.Value >= 300 and game:GetService("Players")["LocalPlayer"].Data.Beli.Value >= 300000 then
						UnEquipWeapon("Black Leg")
						wait(.1)
						game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyElectro")
					end
					if game.Players.LocalPlayer.Backpack:FindFirstChild("Electro") and game.Players.LocalPlayer.Backpack:FindFirstChild("Electro").Level.Value >= 300 and game:GetService("Players")["LocalPlayer"].Data.Beli.Value >= 750000 then
						UnEquipWeapon("Electro")
						wait(.1)
						game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyFishmanKarate")
					end
					if game.Players.LocalPlayer.Character:FindFirstChild("Electro") and game.Players.LocalPlayer.Character:FindFirstChild("Electro").Level.Value >= 300 and game:GetService("Players")["LocalPlayer"].Data.Beli.Value >= 750000 then
						UnEquipWeapon("Electro")
						wait(.1)
						game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyFishmanKarate")
					end
					if game.Players.LocalPlayer.Backpack:FindFirstChild("Fishman Karate") and game.Players.LocalPlayer.Backpack:FindFirstChild("Fishman Karate").Level.Value >= 300 and game:GetService("Players")["Localplayer"].Data.Fragments.Value >= 1500 then
						UnEquipWeapon("Fishman Karate")
						wait(.1)
						game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BlackbeardReward","DragonClaw","1")
						game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BlackbeardReward","DragonClaw","2") 
					end
					if game.Players.LocalPlayer.Character:FindFirstChild("Fishman Karate") and game.Players.LocalPlayer.Character:FindFirstChild("Fishman Karate").Level.Value >= 300 and game:GetService("Players")["Localplayer"].Data.Fragments.Value >= 1500 then
						UnEquipWeapon("Fishman Karate")
						wait(.1)
						game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BlackbeardReward","DragonClaw","1")
						game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BlackbeardReward","DragonClaw","2") 
					end
					if game.Players.LocalPlayer.Backpack:FindFirstChild("Dragon Claw") and game.Players.LocalPlayer.Backpack:FindFirstChild("Dragon Claw").Level.Value >= 300 and game:GetService("Players")["LocalPlayer"].Data.Beli.Value >= 3000000 then
						UnEquipWeapon("Dragon Claw")
						wait(.1)
						game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySuperhuman")
					end
					if game.Players.LocalPlayer.Character:FindFirstChild("Dragon Claw") and game.Players.LocalPlayer.Character:FindFirstChild("Dragon Claw").Level.Value >= 300 and game:GetService("Players")["LocalPlayer"].Data.Beli.Value >= 3000000 then
						UnEquipWeapon("Dragon Claw")
						wait(.1)
						game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySuperhuman")
					end 
				end
			end
		end
	end)
end)
function InMyNetWork(object)
	if isnetworkowner then
		return isnetworkowner(object)
	else
		if (object.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 200 then 
			return true
		end
		return false
	end
end
spawn(function()
	while wait() do
		if getgenv().FullyDeathStep then
			pcall(function()
				if not game.Players.LocalPlayer.Backpack:FindFirstChild("Black Leg") or not game.Players.LocalPlayer.Character:FindFirstChild("Black Leg") or not game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Death Step") or not game:GetService("Players").LocalPlayer.Character:FindFirstChild("Death Step") then
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyBlackLeg")
				end				
				if game:GetService("Workspace").Map.IceCastle.Hall.LibraryDoor.PhoeyuDoor.Transparency == 0 then  
					if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Library Key") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Library Key") then
						EquipWeapon("Library Key")
						repeat wait() getgenv().ToTarget(CFrame.new(6371.2001953125, 296.63433837890625, -6841.18115234375)) until (CFrame.new(6371.2001953125, 296.63433837890625, -6841.18115234375).Position - game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 3 or not getgenv().FullyDeathStep
						if (CFrame.new(6371.2001953125, 296.63433837890625, -6841.18115234375).Position - game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 3 then
							wait(1.2)
							game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyDeathStep",true)
							game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyDeathStep")
							wait(0.5)
						end
					elseif game.Players.LocalPlayer.Backpack:FindFirstChild("Black Leg") and game.Players.LocalPlayer.Backpack:FindFirstChild("Black Leg").Level.Value >= 450 or game.Players.LocalPlayer.Character:FindFirstChild("Black Leg") and game.Players.LocalPlayer.Character:FindFirstChild("Black Leg").Level.Value >= 450 then   
						if game:GetService("ReplicatedStorage"):FindFirstChild("Awakened Ice Admiral [Lv. 1400] [Boss]") or game:GetService("Workspace").Enemies:FindFirstChild("Awakened Ice Admiral [Lv. 1400] [Boss]") then
							if game:GetService("Workspace").Enemies:FindFirstChild("Awakened Ice Admiral [Lv. 1400] [Boss]") then 	
								for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
									if v.Name == "Awakened Ice Admiral [Lv. 1400] [Boss]" then    
										repeat wait()
											AutoHaki()
											EquipWeapon(_G.SelectWeapon)
											v.Head.CanCollide = false
											v.Humanoid.WalkSpeed = 0
											v.HumanoidRootPart.CanCollide = false
											v.HumanoidRootPart.Size = Vector3.new(50,50,50)
											getgenv().ToTarget(v.HumanoidRootPart.CFrame * CFrame.new(0,30,0))
											game:GetService'VirtualUser':CaptureController()
											game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
											sethiddenproperty(game:GetService("Players").LocalPlayer,"SimulationRadius",math.huge)
										until not v.Parent or v.Humanoid.Health <= 0 or _G.getgenv().FullyDeathStep == false or game:GetService("Players").LocalPlayer.Character:FindFirstChild("Library Key") or game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Library Key")
									end
								end
							else
								repeat wait() getgenv().ToTarget(game:GetService("ReplicatedStorage"):FindFirstChild("Awakened Ice Admiral [Lv. 1400] [Boss]").HumanoidRootPart.CFrame) until game:GetService("Workspace").Enemies:FindFirstChild("Awakened Ice Admiral [Lv. 1400] [Boss]")
							end
						else 
							Hop()
						end
					end
				else 
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyDeathStep")
				end
			end)
		end
	end
end)
Main:Label("👹 Auto Combat Function 👹")

Main:Toggle("Auto Super human",getgenv().Superhuman,function(value)
	getgenv().Superhuman = value
	getgenv().FullySuperhuman = value
	local args = {
		[1] = "BuySuperhuman"
	}
	game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
end)
Main:Toggle("Auto Death Step",getgenv().FullyDeathStep,function(value)
	getgenv().FullyDeathStep = value
	wait()
	game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyDeathStep")
end)
Main:Toggle("Auto Sharkman",getgenv().Sharkman,function(value)
	getgenv().Sharkman = value
end)
Main:Toggle("Auto Electric Claw",getgenv().ElectricClaw,function(value)
	getgenv().ElectricClaw = value
	StopTween(getgenv().ElectricClaw)
end)
Main:Toggle("Auto Dragon Talon",getgenv().DragonTalon,function(value)
	getgenv().DragonTalon = value
end)
Main:Toggle("Auto God Human",getgenv().Godhuman,function(value)
	getgenv().Godhuman = value
end)
spawn(function()
	while task.wait() do
		pcall(function()
			if getgenv().Godhuman then
				if game.Players.LocalPlayer.Character:FindFirstChild("Godhuman") or game.Players.LocalPlayer.Backpack:FindFirstChild("Godhuman") then
					_G.SelectWeapon = "Godhuman"
				end  
				if game.Players.LocalPlayer.Backpack:FindFirstChild("Death Step") or game.Players.LocalPlayer.Character:FindFirstChild("Death Step") or game.Players.LocalPlayer.Backpack:FindFirstChild("Electric Claw") or game.Players.LocalPlayer.Character:FindFirstChild("Electric Claw") or game.Players.LocalPlayer.Backpack:FindFirstChild("Sharkman Karate") or game.Players.LocalPlayer.Character:FindFirstChild("Sharkman Karate") or game.Players.LocalPlayer.Backpack:FindFirstChild("Dragon Talon") or game.Players.LocalPlayer.Character:FindFirstChild("Dragon Talon") then
					if game.Players.LocalPlayer.Backpack:FindFirstChild("Death Step") and game.Players.LocalPlayer.Backpack:FindFirstChild("Death Step").Level.Value <= 399 then
						_G.SelectWeapon = "Death Step"
					end
					if game.Players.LocalPlayer.Backpack:FindFirstChild("Electric Claw") and game.Players.LocalPlayer.Backpack:FindFirstChild("Electric Claw").Level.Value <= 399 then
						_G.SelectWeapon = "Electric Claw"
					end
					if game.Players.LocalPlayer.Backpack:FindFirstChild("Sharkman Karate") and game.Players.LocalPlayer.Backpack:FindFirstChild("Sharkman Karate").Level.Value <= 399 then
						_G.SelectWeapon = "Sharkman Karate"
					end
					if game.Players.LocalPlayer.Backpack:FindFirstChild("Dragon Talon") and game.Players.LocalPlayer.Backpack:FindFirstChild("Dragon Talon").Level.Value <= 399 then
						_G.SelectWeapon = "Dragon Claw"
					end
					if game.Players.LocalPlayer.Backpack:FindFirstChild("Death Step") and game.Players.LocalPlayer.Backpack:FindFirstChild("Death Step").Level.Value >= 400 or game.Players.LocalPlayer.Character:FindFirstChild("Death Step") and game.Players.LocalPlayer.Character:FindFirstChild("Death Step").Level.Value >= 400 then
						game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyElectricClaw")
					end
					if game.Players.LocalPlayer.Backpack:FindFirstChild("Electric Claw") and game.Players.LocalPlayer.Backpack:FindFirstChild("Electric Claw").Level.Value >= 400 or game.Players.LocalPlayer.Character:FindFirstChild("Electric Claw") and game.Players.LocalPlayer.Character:FindFirstChild("Electric Claw").Level.Value >= 400 then
						game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySharkmanKarate")
					end
					if game.Players.LocalPlayer.Backpack:FindFirstChild("Sharkman Karate") and game.Players.LocalPlayer.Backpack:FindFirstChild("Sharkman Karate").Level.Value >= 400 or game.Players.LocalPlayer.Character:FindFirstChild("Sharkman Karate") and game.Players.LocalPlayer.Character:FindFirstChild("Sharkman Karate").Level.Value >= 400 then
						game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyDragonTalon")
					end 
					if game.Players.LocalPlayer.Backpack:FindFirstChild("Dragon Talon") and game.Players.LocalPlayer.Backpack:FindFirstChild("Dragon Talon").Level.Value >= 400 or game.Players.LocalPlayer.Backpack:Character("Dragon Talon") and game.Players.LocalPlayer.Character:FindFirstChild("Dragon Talon").Level.Value >= 400 then
						game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyGodhuman")
					end
				end
			end
		end)
	end
end)
spawn(function()
	while task.wait() do
		pcall(function()
			if _G.AutoStats then
				if _G.SelectStats == "Melee" then
local args = {
	[1] = "AddPoint",
	[2] = "Melee",
	[3] = _G.Point
}

game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
				elseif _G.SelectStats == "Defense" then
local args = {
	[1] = "AddPoint",
	[2] = "Defense",
	[3] = _G.Point
}

game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
				elseif _G.SelectStats == "Sword" then
local args = {
	[1] = "AddPoint",
	[2] = "Sword",
	[3] = _G.Point
}

game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
				elseif _G.SelectStats == "Gun" then
local args = {
	[1] = "AddPoint",
	[2] = "Gun",
	[3] = _G.Point
}

game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
				elseif _G.SelectStats == "DevilFruit" then
local args = {
	[1] = "AddPoint",
	[2] = "Devil Fruit",
	[3] = _G.Point
}

game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
				end
			end
		end)
	end
end)
	local Main2 = Tap:newpage()
Main2:Label("Settings Auto Farm")
	WeaponList = {}
        
    for i,v in pairs(game:GetService("Players").LocalPlayer.Backpack:GetChildren()) do  
        if v:IsA("Tool") then
            table.insert(WeaponList ,v.Name)
        end
    end
	local SelectWeapon = Main2:Drop("Select Weapon",false,WeaponList,function(value)
		_G.SelectWeapon = value
    end)
Main2:Button("Refresh Weapon",function()
	SelectWeapon:Clear()
	for i,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do  
		if v:IsA("Tool") then
			SelectWeapon:Add(v.Name)
		end
	end
	for i,v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do  
		if v:IsA("Tool") then
			SelectWeapon:Add(v.Name)
		end
	end
end)
function Click()
    game:GetService'VirtualUser':CaptureController()
    game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
    end
    
    function AutoHaki()
    if not game:GetService("Players").LocalPlayer.Character:FindFirstChild("HasBuso") then
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Buso")
    end
    end

	Main2:Toggle("Fast Attack",true,function(value)
		_G.FastAttack95 = value
        _G.Fast_Attack_Normal3 = value
    end)

	
	Main2:Toggle("Auto Haki",true,function(value)
		_G.Haki = value
    end)
	Main2:Toggle("Auto Set Spawn",false,function(value)
		_G.SetSpawnPoint = value
    end)
	Main2:Toggle("Auto Rejoin",true,function(value)
		_G.AutoRejoin = value
    end)
	Main2:Button("Fps Boost",function(t)
		_G.BoostFPS = t
		local decalsyeeted = true
		local g = game
		local w = g.Workspace
		local l = g.Lighting
		local t = w.Terrain
		t.WaterWaveSize = 0
		t.WaterWaveSpeed = 0
		t.WaterReflectance = 0
		t.WaterTransparency = 0
		l.GlobalShadows = false
		l.FogEnd = 9e9
		l.Brightness = 0
		settings().Rendering.QualityLevel = "Level01"
		for i, v in pairs(g:GetDescendants()) do
			if v:IsA("Part") or v:IsA("Union") or v:IsA("CornerWedgePart") or v:IsA("TrussPart") then 
				v.Material = "Plastic"
				v.Reflectance = 0
			elseif v:IsA("Decal") or v:IsA("Texture") and decalsyeeted then
				v.Transparency = 1
			elseif v:IsA("ParticleEmitter") or v:IsA("Trail") then
				v.Lifetime = NumberRange.new(0)
			elseif v:IsA("Explosion") then
				v.BlastPressure = 1
				v.BlastRadius = 1
			elseif v:IsA("Fire") or v:IsA("SpotLight") or v:IsA("Smoke") or v:IsA("Sparkles") then
				v.Enabled = false
			elseif v:IsA("MeshPart") then
				v.Material = "Plastic"
				v.Reflectance = 0
				v.TextureID = 10385902758728957
			end
		end
		for i, e in pairs(l:GetChildren()) do
			if e:IsA("BlurEffect") or e:IsA("SunRaysEffect") or e:IsA("ColorCorrectionEffect") or e:IsA("BloomEffect") or e:IsA("DepthOfFieldEffect") then
				e.Enabled = false
			end
		end
	end)
	if _G.BoostFPS then
		local decalsyeeted = true
		local g = game
		local w = g.Workspace
		local l = g.Lighting
		local t = w.Terrain
		t.WaterWaveSize = 0
		t.WaterWaveSpeed = 0
		t.WaterReflectance = 0
		t.WaterTransparency = 0
		l.GlobalShadows = false
		l.FogEnd = 9e9
		l.Brightness = 0
		settings().Rendering.QualityLevel = "Level01"
		for i, v in pairs(g:GetDescendants()) do
			if v:IsA("Part") or v:IsA("Union") or v:IsA("CornerWedgePart") or v:IsA("TrussPart") then 
				v.Material = "Plastic"
				v.Reflectance = 0
			elseif v:IsA("Decal") or v:IsA("Texture") and decalsyeeted then
				v.Transparency = 1
			elseif v:IsA("ParticleEmitter") or v:IsA("Trail") then
				v.Lifetime = NumberRange.new(0)
			elseif v:IsA("Explosion") then
				v.BlastPressure = 1
				v.BlastRadius = 1
			elseif v:IsA("Fire") or v:IsA("SpotLight") or v:IsA("Smoke") or v:IsA("Sparkles") then
				v.Enabled = false
			elseif v:IsA("MeshPart") then
				v.Material = "Plastic"
				v.Reflectance = 0
				v.TextureID = 10385902758728957
			end
		end
		for i, e in pairs(l:GetChildren()) do
			if e:IsA("BlurEffect") or e:IsA("SunRaysEffect") or e:IsA("ColorCorrectionEffect") or e:IsA("BloomEffect") or e:IsA("DepthOfFieldEffect") then
				e.Enabled = false
			end
		end
	end
	spawn(function()
        while wait(.1) do
            if _G.SetSpawnPoint then
                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint");
            end
        end
    end)
	spawn(function()
        while wait(1) do
            if _G.Haki then
                AutoHaki()
            end
        end
    end)
	local WebHookLog = {}

local AllRequest = http_request or request or HttpPost or syn.request
function WebHookLog:WebHookKaiTanSend(WebHookUrl)

	function GetFightingStyle(Style)
		ReturnText = ""
		for i ,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
			if v:IsA("Tool") then
				if v.ToolTip == Style then
					ReturnText = v.Name
				end
			end
		end
		for i ,v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
			if v:IsA("Tool") then
				if v.ToolTip == Style then
					ReturnText = v.Name
				end
			end
		end
		if ReturnText ~= "" then
			return ReturnText
		else
			return "Not Have"
		end
	end

	function GetAwaken()
		ReturnText = ""
		Awakened_Z = ":x:"
		Awakened_X = ":x:"
		Awakened_C = ":x:"
		Awakened_V = ":x:"
		Awakened_F = ":x:"
		for i ,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
			if v:IsA("Tool") then
				if v.ToolTip == "Blox Fruit" then
					if v:FindFirstChild("AwakenedMoves") then
						if v.AwakenedMoves:FindFirstChild("Z") then
							Awakened_Z = ":white_check_mark:"
						end
						if v.AwakenedMoves:FindFirstChild("X") then
							Awakened_X = ":white_check_mark:"
						end
						if v.AwakenedMoves:FindFirstChild("C") then
							Awakened_C = ":white_check_mark:"
						end
						if v.AwakenedMoves:FindFirstChild("V") then
							Awakened_V = ":white_check_mark:"
						end
						if v.AwakenedMoves:FindFirstChild("F") then
							Awakened_F = ":white_check_mark:"
						end
						ReturnText = ":regional_indicator_z:"..Awakened_Z..
							"\n"..":regional_indicator_x:"..Awakened_X..
							"\n"..":regional_indicator_c:"..Awakened_C..
							"\n"..":regional_indicator_v:"..Awakened_V..
							"\n"..":regional_indicator_f:"..Awakened_F
					else
						ReturnText = "This Fruit Can't Awakened"
					end
				end
			end
		end
		for i ,v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
			if v:IsA("Tool") then
				if v.ToolTip == "Blox Fruit" then
					if v:FindFirstChild("AwakenedMoves") then
						if v.AwakenedMoves:FindFirstChild("Z") then
							Awakened_Z = ":white_check_mark:"
						end
						if v.AwakenedMoves:FindFirstChild("X") then
							Awakened_X = ":white_check_mark:"
						end
						if v.AwakenedMoves:FindFirstChild("C") then
							Awakened_C = ":white_check_mark:"
						end
						if v.AwakenedMoves:FindFirstChild("V") then
							Awakened_V = ":white_check_mark:"
						end
						if v.AwakenedMoves:FindFirstChild("F") then
							Awakened_F = ":white_check_mark:"
						end
						ReturnText = ":regional_indicator_z:"..Awakened_Z..
							"\n"..":regional_indicator_x:"..Awakened_X..
							"\n"..":regional_indicator_c:"..Awakened_C..
							"\n"..":regional_indicator_v:"..Awakened_V..
							"\n"..":regional_indicator_f:"..Awakened_F
					else
						ReturnText = "This Fruit Can't Awakened"
					end
				end
			end
		end
		if ReturnText ~= "" then
			return ReturnText
		else
			return "Not Have"
		end
	end

	function GetWeapon(Rare)
		if Rare == "Common" then
			RareNumber = 0
		elseif Rare == "Uncommon" then
			RareNumber = 1
		elseif Rare == "Rare" then
			RareNumber = 2
		elseif Rare == "Legendary" then
			RareNumber = 3
		elseif Rare == "Mythical" then
			RareNumber = 4
		else
			return "Worng InPut"
		end
		local ReturnText = ""
		for i,v in pairs(game:GetService("ReplicatedStorage").Remotes["CommF_"]:InvokeServer("getInventoryWeapons")) do
			if type(v) == "table" then
				if v.Rarity then
					if tonumber(v.Rarity) == RareNumber then
						ReturnText = ReturnText .. v.Name .. "\n"
					end
				end
			end
		end
		if ReturnText ~= "" then
			return ReturnText
		else
			return "Not Have"
		end
	end

	function GetFruitInU()
		local ReturnText = ""
		for i,v in pairs(game:GetService("ReplicatedStorage").Remotes["CommF_"]:InvokeServer("getInventoryFruits")) do
			if type(v) == "table" then
				if v ~= nil then
					ReturnText = ReturnText .. v.Name .. " : " .. v.Price .. "\n"
				end
			end
		end

		if ReturnText ~= "" then
			return ReturnText
		else
			return "Not Have"
		end
	end

	function GetAllMelee()
		BuyDragonTalon = tonumber(game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyDragonTalon",true))
		if BuyDragonTalon then
			if BuyDragonTalon == 1 then
				TalComplete = true
			end
		end
		BuySuperhuman = tonumber(game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySuperhuman",true))
		if BuySuperhuman then
			if BuySuperhuman == 1 then
				SupComplete = true
			end
		end
		BuySharkmanKarate = tonumber(game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySharkmanKarate",true))
		if BuySharkmanKarate then
			if BuySharkmanKarate == 1 then
				SharkComplete = true
			end
		end
		BuyDeathStep = tonumber(game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyDeathStep",true))
		if BuyDeathStep then
			if BuyDeathStep == 1 then
				DeathComplete = true
			end
		end
		BuyElectricClaw = tonumber(game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyElectricClaw",true))
		if BuyElectricClaw then
			if BuyElectricClaw == 1 then
				EClawComplete = true
			end
		end
		BuyGod = tonumber(game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyGodhuman",true))
		if BuyGod then
			if BuyGod == 1 then
				GodComplete = true
			end
		end
		ReturnText = {}
		if SupComplete == true then
			table.insert(ReturnText,"SuperHuman")
		end
		if EClawComplete == true then
			table.insert(ReturnText,"Electric Claw")
		end
		if TalComplete == true then
			table.insert(ReturnText,"Dragon Talon")
		end
		if SharkComplete == true then
			table.insert(ReturnText,"Sharkman Karate")
		end
		if DeathComplete == true then
			table.insert(ReturnText,"Death Step")
		end
		if GodComplete == true then
			table.insert(ReturnText,"God Human")
		end

		if #ReturnText ~= 0 then
			return table.concat(ReturnText,",")
		else
			return "Not Have"
		end
	end

	local Embeds = {{
		["title"] = "**Lua Hub Webhooks Status**",
		["color"] = tonumber(0xD936FF),
		["fields"] = {
			{
				["name"] = "User Name",
				["value"] = "||"..tostring(game.Players.LocalPlayer.Name).."||",
				["inline"] = true
			},
			{
				["name"] = "Level",
				["value"] = tostring(game:GetService("Players").LocalPlayer.Data:FindFirstChild("Level").Value),
				["inline"] = true
			},
			{
				["name"] = "Fragments",
				["value"] = tostring(game:GetService("Players").LocalPlayer.Data:FindFirstChild("Fragments").Value),
				["inline"] = true
			},
			{
				["name"] = "Bounty/Honor",
				["value"] = tostring(game:GetService("Players").LocalPlayer.leaderstats["Bounty/Honor"].Value),
				["inline"] = true
			},
			{
				["name"] = "Beli",
				["value"] = tostring(game:GetService("Players").LocalPlayer.Data:FindFirstChild("Beli").Value),
				["inline"] = true
			},
			{
				["name"] = "Fighting Style",
				["value"] = GetFightingStyle("Melee"),
				["inline"] = true
			},
			{
				["name"] = "Sword",
				["value"] = GetFightingStyle("Sword"),
				["inline"] = true
			},
			{
				["name"] = "Devil Fruit",
				["value"] = GetFightingStyle("Blox Fruit"),
				["inline"] = true
			},
			{
				["name"] = "Gun",
				["value"] = GetFightingStyle("Gun"),
				["inline"] = true
			},
			{
				["name"] = "Accessory",
				["value"] = GetFightingStyle("Wear"),
				["inline"] = true
			},
			{
				["name"] = "Race",
				["value"] = tostring(game:GetService("Players").LocalPlayer.Data:FindFirstChild("Race").Value),
				["inline"] = true
			},
			{
				["name"] = "Awakened",
				["value"] = tostring(GetAwaken()),
				["inline"] = true
			},
			{
				["name"] = "Status",
				["value"] = "```sml\n"..tostring("Melee : "..game:GetService("Players").LocalPlayer.Data.Stats.Melee:WaitForChild("Level").Value .. 
					"\nDefense : "..game:GetService("Players").LocalPlayer.Data.Stats.Defense:WaitForChild("Level").Value .. 
					"\nSword : "..game:GetService("Players").LocalPlayer.Data.Stats.Sword:WaitForChild("Level").Value.. 
					"\nGun : "..game:GetService("Players").LocalPlayer.Data.Stats.Gun:WaitForChild("Level").Value .. 
					"\nDevil Fruit : "..game:GetService("Players").LocalPlayer.Data.Stats["Demon Fruit"]:WaitForChild("Level").Value).."```",
				["inline"] = true
			},
			{
				["name"] = "Common :blue_circle:",
				["value"] = "```sml\n"..tostring(GetWeapon("Common")).."```",
				["inline"] = true
			},
			{
				["name"] = "Uncommon :green_circle:",
				["value"] = "```sml\n"..tostring(GetWeapon("Uncommon")).."```",
				["inline"] = true
			},
			{
				["name"] = "Rare :yellow_circle:",
				["value"] = "```sml\n"..tostring(GetWeapon("Rare")).."```",
				["inline"] = true
			},
			{
				["name"] = "Legendary :purple_circle:",
				["value"] = "```sml\n"..tostring(GetWeapon("Legendary")).."```",
				["inline"] = true
			},
			{
				["name"] = "Mythical :red_circle:",
				["value"] = "```sml\n"..tostring(GetWeapon("Mythical")).."```",
				["inline"] = true
			},
			{
				["name"] = "Fruit In Inventory",
				["value"] = "```sml\n"..tostring(GetFruitInU()).."```",
				["inline"] = true
			},
			{
				["name"] = "All Melee",
				["value"] = "```sml\n"..tostring(GetAllMelee()).."```",
				["inline"] = true
			},



			{
				["name"] = "ㅤ",
				["value"] = tostring("ㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤ"),
				["inline"] = false
			}},
		["footer"] = {
			["text"] = "Made by ! TSUO".."\nTime".." : "..os.date("%c").." ("..os.date("%X")..")",
			["icon_url"] = "https://cdn.discordapp.com/attachments/1044229754632544296/1048491372686094336/Book_JE2_BE2.webp"
		},
	}}

	local Message
	if _G.SendWebHookPing then
		Message = {
			['username'] = "Lua Webhook",
			["avatar_url"] = "https://cdn.discordapp.com/attachments/1044229754632544296/1048491372686094336/Book_JE2_BE2.webp",
			["content"] = "@everyone",
			["embeds"] = Embeds,
		}
	else
		Message = {
			['username'] = "Lua Webhook",
			["avatar_url"] = "https://cdn.discordapp.com/attachments/1044229754632544296/1048491372686094336/Book_JE2_BE2.webp",
			["embeds"] = Embeds,
		}
	end

	local DataCallBack = AllRequest({
		Url = WebHookUrl,
		Method = 'POST',
		Headers = {
			["Content-Type"] = "application/json"
		},
		Body = game:GetService("HttpService"):JSONEncode(Message)
	})
	return DataCallBack
end

function WebHookLog:SheetBestLogSend(SheetBestUrl)

	function GetFightingStyle(Style)
		ReturnText = ""
		for i ,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
			if v:IsA("Tool") then
				if v.ToolTip == Style then
					ReturnText = v.Name
				end
			end
		end
		for i ,v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
			if v:IsA("Tool") then
				if v.ToolTip == Style then
					ReturnText = v.Name
				end
			end
		end
		if ReturnText ~= "" then
			return ReturnText
		else
			return "Not Have"
		end
	end

	function GetAllMelee()
		BuyDragonTalon = tonumber(game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyDragonTalon",true))
		if BuyDragonTalon then
			if BuyDragonTalon == 1 then
				TalComplete = true
			end
		end
		BuySuperhuman = tonumber(game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySuperhuman",true))
		if BuySuperhuman then
			if BuySuperhuman == 1 then
				SupComplete = true
			end
		end
		BuySharkmanKarate = tonumber(game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySharkmanKarate",true))
		if BuySharkmanKarate then
			if BuySharkmanKarate == 1 then
				SharkComplete = true
			end
		end
		BuyDeathStep = tonumber(game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyDeathStep",true))
		if BuyDeathStep then
			if BuyDeathStep == 1 then
				DeathComplete = true
			end
		end
		BuyElectricClaw = tonumber(game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyElectricClaw",true))
		if BuyElectricClaw then
			if BuyElectricClaw == 1 then
				EClawComplete = true
			end
		end
		BuyGod = tonumber(game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyGodhuman",true))
		if BuyGod then
			if BuyGod == 1 then
				GodComplete = true
			end
		end
		ReturnText = {}
		if SupComplete == true then
			table.insert(ReturnText,"SuperHuman")
		end
		if EClawComplete == true then
			table.insert(ReturnText,"Electric Claw")
		end
		if TalComplete == true then
			table.insert(ReturnText,"Dragon Talon")
		end
		if SharkComplete == true then
			table.insert(ReturnText,"Sharkman Karate")
		end
		if DeathComplete == true then
			table.insert(ReturnText,"Death Step")
		end
		if GodComplete == true then
			table.insert(ReturnText,"God Human")
		end

		if #ReturnText ~= 0 then
			return table.concat(ReturnText,",")
		else
			return "Not Have"
		end
	end

	function GetAwaken()
		ReturnText = ""
		Awakened_Z = "❌"
		Awakened_X = "❌"
		Awakened_C = "❌"
		Awakened_V = "❌"
		Awakened_F = "❌"
		for i ,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
			if v:IsA("Tool") then
				if v.ToolTip == "Blox Fruit" then
					if v:FindFirstChild("AwakenedMoves") then
						if v.AwakenedMoves:FindFirstChild("Z") then
							Awakened_Z = "Z"
						end
						if v.AwakenedMoves:FindFirstChild("X") then
							Awakened_X = "X"
						end
						if v.AwakenedMoves:FindFirstChild("C") then
							Awakened_C = "C"
						end
						if v.AwakenedMoves:FindFirstChild("V") then
							Awakened_V = "V"
						end
						if v.AwakenedMoves:FindFirstChild("F") then
							Awakened_F = "F"
						end
						ReturnText = Awakened_Z..
							" : "..Awakened_X..
							" : "..Awakened_C..
							" : "..Awakened_V..
							" : "..Awakened_F
					else
						ReturnText = "This Fruit Can't Awakened"
					end
				end
			end
		end
		for i ,v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
			if v:IsA("Tool") then
				if v.ToolTip == "Blox Fruit" then
					if v:FindFirstChild("AwakenedMoves") then
						if v.AwakenedMoves:FindFirstChild("Z") then
							Awakened_Z = ":white_check_mark:"
						end
						if v.AwakenedMoves:FindFirstChild("X") then
							Awakened_X = ":white_check_mark:"
						end
						if v.AwakenedMoves:FindFirstChild("C") then
							Awakened_C = ":white_check_mark:"
						end
						if v.AwakenedMoves:FindFirstChild("V") then
							Awakened_V = ":white_check_mark:"
						end
						if v.AwakenedMoves:FindFirstChild("F") then
							Awakened_F = ":white_check_mark:"
						end
						ReturnText = ":regional_indicator_z:"..Awakened_Z..
							" : "..":regional_indicator_x:"..Awakened_X..
							" : "..":regional_indicator_c:"..Awakened_C..
							" : "..":regional_indicator_v:"..Awakened_V..
							" : "..":regional_indicator_f:"..Awakened_F
					else
						ReturnText = "This Fruit Can't Awakened"
					end
				end
			end
		end
		if ReturnText ~= "" then
			return ReturnText
		else
			return "Not Have"
		end
	end

	function GetWeapon()
		local ReturnText = ""
		for i,v in pairs(game:GetService("ReplicatedStorage").Remotes["CommF_"]:InvokeServer("getInventoryWeapons")) do
			if type(v) == "table" then
				if v.Name then
					ReturnText = ReturnText .. v.Name .. " "
				end
			end
		end
		if ReturnText ~= "" then
			return ReturnText
		else
			return "Not Have"
		end
	end

	function GetFruitInU()
		local ReturnText = ""
		for i,v in pairs(game:GetService("ReplicatedStorage").Remotes["CommF_"]:InvokeServer("getInventoryFruits")) do
			if type(v) == "table" then
				if v ~= nil then
					ReturnText = ReturnText .. v.Name .. " "
				end
			end
		end

		if ReturnText ~= "" then
			return ReturnText
		else
			return "Not Have"
		end
	end

	function GetWeaponMastery(Style)
		ReturnText = ""
		for i ,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
			if v:IsA("Tool") then
				if v.ToolTip == Style then
					ReturnText = v:FindFirstChild("Level").Value
				end
			end
		end
		for i ,v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
			if v:IsA("Tool") then
				if v.ToolTip == Style then
					ReturnText = v:FindFirstChild("Level").Value
				end
			end
		end
		if ReturnText ~= "" then
			return ReturnText
		else
			return "Not Have"
		end
	end

	function Abbreviate(x)
		local abbreviations = {
			"K", -- 4 digits
			"M", -- 7 digits
			"B", -- 10 digits
			"T", -- 13 digits
			"QD", -- 16 digits
			"QT", -- 19 digits
			"SXT", -- 22 digits
			"SEPT", -- 25 digits
			"OCT", -- 28 digits
			"NON", -- 31 digits
			"DEC", -- 34 digits
			"UDEC", -- 37 digits
			"DDEC", -- 40 digits
		}
		if x < 1000 then 
			return tostring(x)
		end

		local digits = math.floor(math.log10(x)) + 1
		local index = math.min(#abbreviations, math.floor((digits - 1) / 3))
		local front = x / math.pow(10, index * 3)

		return string.format("%i%s+", front, abbreviations[index])
	end

	local Message
	Message = {
		["UserName"] = tostring(game.Players.LocalPlayer.Name),
		["Level"] = tostring(game:GetService("Players").LocalPlayer.Data:FindFirstChild("Level").Value),
		["Weapon inventory"] = tostring(GetWeapon()),
		["Fruit inventory"] = tostring(GetFruitInU()),
		["Melee"] = tostring(GetAllMelee()),
		["Fruit"] = tostring(GetFightingStyle("Blox Fruit")),
		["Fruit Mastery"] = tostring(GetWeaponMastery("Blox Fruit")),
		["Fruit Awake"] = tostring(GetAwaken()),
		["Beli"] = tostring(Abbreviate(game:GetService("Players").LocalPlayer.Data:FindFirstChild("Beli").Value)),
		["Fragment"] = tostring(Abbreviate(game:GetService("Players").LocalPlayer.Data:FindFirstChild("Fragments").Value)),
		["Race"] = tostring(game:GetService("Players").LocalPlayer.Data:FindFirstChild("Race").Value)
	}

	local DataCallBack = AllRequest({
		Url = SheetBestUrl,
		Method = 'POST',
		Headers = {
			["Content-Type"] = "application/json"
		},
		Body = game:GetService("HttpService"):JSONEncode(Message)
	})
	return DataCallBack
end
	require(game.ReplicatedStorage.Util.CameraShaker):Stop()
	task.spawn(
		function()
			while task.wait(0.2) do
				pcall(
					function()
						if _G.Fast_Attack_Normal3 then
								AttackFarm()
							end
						end
				)
			end
		end
	)

	
		local Main5 = Tap:newpage()
		Statslist = {
			"Melee",
			"Defense",
			"Sword",
			"Gun",
			"DevilFruit"
		}
		Main5:Label("Settings Auto Farm2")
	Main5:Drop("Select Stats",false,Statslist,function(value)
			_G.SelectStats = value
		end)
		Main5:Toggle("Auto Up Stats",false,function(value)
			_G.AutoStats = value
		end)
		Main5:Slider("Slider Stats",false,false,0,100,10,1,false,10,function(value)
			_G.Point = value
		end)
	local Main3 = Tap:newpage()
	local bone20 = Main3:Label("🎃 Bone 🎃")
	spawn(function()
        while wait(4) do
            pcall(function()
                if getgenv().AutoBone then
					local NotifyLibrary = loadstring(game:HttpGet("https://raw.githubusercontent.com/Kinlei/Dynissimo/main/Scripts/AkaliNotif.lua"))()
					local Notify = NotifyLibrary.Notify      
							  
									Notify({
										Title = "Lua Notify",
										Description = "Your Bone : "..(game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Bones","Check")),
										Duration = 5
									})
                end
            end)
        end
    end)
	
	Main3:Toggle("Auto Farm Bone",getgenv().AutoBone,function(value)
		getgenv().AutoBone = value
		StopTween(_G.AutoBone)
		if value == false then
			getgenv().ToTarget(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame)
			getgenv().ToTarget(game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame)
		   topos(game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame)
			topos(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame)
			getgenv().AutoBone = false
		end
    end)
	Main3:Toggle("Auto Random Bone",getgenv().RandomBone,function(value)
		getgenv().RandomBone = value
    end)
	local bone20zx = Main3:Label("🍦 Cake Prince 🍦")
	Main3:Toggle("Auto Cake Prince",getgenv().cakefarm,function(value)
		topos(CFrame.new(-1771.66064, 79.6693497, -12203.0693, -0.800069749, -1.06273355e-08, -0.599906981, -4.78388635e-08, 1, 4.60856278e-08, 0.599906981, 6.55705819e-08, -0.800069749))
		getgenv().cakefarm = value
		StopTween(getgenv().cakefarm)
	end)
	Main3:Toggle("Auto Spawn Dought Boss",getgenv().Spawn_Cake_Prince,function(value)
		getgenv().Spawn_Cake_Prince = value
		StopTween(getgenv().Spawn_Cake_Prince)
	end)
	local bone20vx = Main3:Label("🎆 Ectoplasm 🎆")
	Main3:Toggle("Auto Ectoplasm",getgenv().Ectoplasm,function(value)
		getgenv().Ectoplasm = value
		StopTween(getgenv().Ectoplasm)
	end)
	local bone20v = Main3:Label("👻 Elite Hunter 👻")
	Main3:Toggle("Auto Elite Hunter",getgenv().Elitehunter,function(value)
		getgenv().Elitehunter = value
            wait(1.1)
            game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("EliteHunter")
            StopTween(getgenv().Elitehunter)
	end)
	Main3:Toggle("Elite Hunter Hop",getgenv().ElitehunterHop,function(value)
		getgenv().ElitehunterHop = value
	end)
	task.spawn(function()
		while task.wait() do
			pcall(function()
				if StartMagnet then
					for i,v in pairs(game.Workspace.Enemies:GetChildren()) do
						if not string.find(v.Name,"Boss") and (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 500 then
							if InMyNetWork(v.HumanoidRootPart) then
								v.HumanoidRootPart.CFrame = PosMon
								v.Humanoid.JumpPower = 0
								v.Humanoid.WalkSpeed = 0
								v.HumanoidRootPart.Size = Vector3.new(60,60,60)
								v.HumanoidRootPart.Transparency = 1
								v.HumanoidRootPart.CanCollide = false
								v.Head.CanCollide = false
								if v.Humanoid:FindFirstChild("Animator") then
									v.Humanoid.Animator:Destroy()
								end
								v.Humanoid:ChangeState(11)
								v.Humanoid:ChangeState(14)
							end
						end
					end
				end
			end)
		end
	end)
	function CameraShaker()
		task.spawn(function()
			local Camera = require(game.Players.LocalPlayer.PlayerScripts.CombatFramework.CameraShaker)
			while wait() do
				pcall(function()
					if _G.Fast_Attack then
						Camera.CameraShakeInstance.CameraShakeState.Inactive = 0
					else
						Camera.CameraShakeInstance.CameraShakeState.Inactive = 3
					end
				end)
			end
		end)
	end
	task.spawn(function()
		while wait() do
			pcall(function()
				if getgenv().AutoBone then
					if game:GetService("Workspace").Enemies:FindFirstChild("Reborn Skeleton [Lv. 1975]") or game:GetService("Workspace").Enemies:FindFirstChild("Living Zombie [Lv. 2000]") or game:GetService("Workspace").Enemies:FindFirstChild("Demonic Soul [Lv. 2025]") or game:GetService("Workspace").Enemies:FindFirstChild("Posessed Mummy [Lv. 2050]") then
						for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
							if v.Name == "Reborn Skeleton [Lv. 1975]" or v.Name == "Living Zombie [Lv. 2000]" or v.Name == "Demonic Soul [Lv. 2025]" or v.Name == "Posessed Mummy [Lv. 2050]" then
								if v:FindFirstChild("Humanoid") and v:FindFirstChild("HumanoidRootPart") and v.Humanoid.Health > 0 then
									repeat wait()
										StartMagnet = true
										EquipWeapon(_G.SelectWeapon)
										_G.Fast_Attack = true
										PosMon = v.HumanoidRootPart.CFrame
										v.HumanoidRootPart.Size = Vector3.new(160,160,160)
										v.Humanoid.JumpPower = 0
										v.Humanoid.WalkSpeed = 0
										v.HumanoidRootPart.CanCollide = false
										v.Humanoid:ChangeState(11)
										topos(v.HumanoidRootPart.CFrame * CFrame.new(0,30,0))
									until not getgenv().AutoBone or v.Humanoid.Health <= 0 or not v.Parent or v.Humanoid.Health <= 0
									StartMagnet = false
									_G.Fast_Attack = false
								end
							end
						end
					else
						topos(CFrame.new(-9504.8564453125, 172.14292907714844, 6057.259765625))
					end
				end
			end)
		end
	end)

	
	spawn(function()
        while task.wait(0.3) do
            if getgenv().cakefarm or _G.Auto_kill_Empress or _G.Auto_kill_Captain or _G.Auto_kill_Captains or _G.AutoTideKeeper or getgenv().Elitehunter then
                pcall(function()
                    local AC = CbFw2.activeController
                    for i = 1,1 do 
                        local bladehit = require(game.ReplicatedStorage.CombatFramework.RigLib).getBladeHits(
                            plr.Character,
                            {plr.Character.HumanoidRootPart},
                            60
                        )
                        local cac = {}
                        local hash = {}
                        for k, v in pairs(bladehit) do
                            if v.Parent:FindFirstChild("HumanoidRootPart") and not hash[v.Parent] then
                                table.insert(cac, v.Parent.HumanoidRootPart)
                                hash[v.Parent] = true
                            end
                        end
                        bladehit = cac
                        if #bladehit > 0 then
                            local u8 = debug.getupvalue(AC.attack, 5)
                            local u9 = debug.getupvalue(AC.attack, 6)
                            local u7 = debug.getupvalue(AC.attack, 4)
                            local u10 = debug.getupvalue(AC.attack, 7)
                            local u12 = (u8 * 798405 + u7 * 727595) % u9
                            local u13 = u7 * 798405
                            (function()
                                u12 = (u12 * u9 + u13) % 1099511627776
                                u8 = math.floor(u12 / u9)
                                u7 = u12 - u8 * u9
                            end)()
                            u10 = u10 + 1
                            debug.setupvalue(AC.attack, 5, u8)
                            debug.setupvalue(AC.attack, 6, u9)
                            debug.setupvalue(AC.attack, 4, u7)
                            debug.setupvalue(AC.attack, 7, u10)
                            if plr.Character:FindFirstChildOfClass("Tool") and AC.blades and AC.blades[1] then 
                                game:GetService("ReplicatedStorage").RigControllerEvent:FireServer("weaponChange",tostring(GetCurrentBlade()))
                                game.ReplicatedStorage.Remotes.Validator:FireServer(math.floor(u12 / 1099511627776 * 16777215), u10)
                                game:GetService("ReplicatedStorage").RigControllerEvent:FireServer("hit", bladehit, i, "") 
                            end
                        end
                    end
                end)
            end
        end
    end)

	spawn(function()
        while wait() do
            if getgenv().Elitehunter then
                pcall(function()
                    local QuestTitle = game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text
                    if game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == false then
                        repeat  wait()
                            topos(CFrame.new(-5418.892578125, 313.74130249023, -2826.2260742188)) 
                        until not _G.AutoElitehunter or (Vector3.new(-5418.892578125, 313.74130249023, -2826.2260742188)-game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 3
                        if (Vector3.new(-5418.892578125, 313.74130249023, -2826.2260742188)-game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 3 then
                            wait(1.1)
                            game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("EliteHunter")
                            wait(0.5)
                        end
                    elseif game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == true then
                        if string.find(QuestTitle,"Diablo") or string.find(QuestTitle,"Deandre") or string.find(QuestTitle,"Urban") then
                            if game:GetService("Workspace").Enemies:FindFirstChild("Diablo [Lv. 1750]") or game:GetService("Workspace").Enemies:FindFirstChild("Deandre [Lv. 1750]") or game:GetService("Workspace").Enemies:FindFirstChild("Urban [Lv. 1750]") then
                                for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                                    if v.Name == "Diablo [Lv. 1750]" or v.Name == "Deandre [Lv. 1750]" or v.Name == "Urban [Lv. 1750]" then
                                        if v:FindFirstChild("Humanoid") and v:FindFirstChild("HumanoidRootPart") and v.Humanoid.Health > 0 then
                                            repeat task.wait()
                                                AutoHaki()
                                                EquipWeapon(_G.SelectWeapon)
                                                v.HumanoidRootPart.CanCollide = false
                                                v.Humanoid.JumpPower = 0
                                                v.Humanoid.WalkSpeed = 0
                                                v.HumanoidRootPart.Size = Vector3.new(150,150,150)
                                                    getgenv().ToTarget(v.HumanoidRootPart.CFrame*CFrame.new(0,20,0));
                                                Attack()
                                                game:GetService("VirtualUser"):CaptureController()
                                                game:GetService("VirtualUser"):Button1Down(Vector2.new(1280,672))
                                                sethiddenproperty(game:GetService("Players").LocalPlayer,"SimulationRadius",math.huge)
                                            until getgenv().Elitehunter == false or v.Humanoid.Health <= 0 or not v.Parent
                                        end
                                    end
                                end
                            else
                                if game:GetService("ReplicatedStorage"):FindFirstChild("Diablo [Lv. 1750]") then
                                    topos(game:GetService("ReplicatedStorage"):FindFirstChild("Diablo [Lv. 1750]").HumanoidRootPart.CFrame * CFrame.new(0,30,0))
                                elseif game:GetService("ReplicatedStorage"):FindFirstChild("Deandre [Lv. 1750]") then
                                    topos(game:GetService("ReplicatedStorage"):FindFirstChild("Deandre [Lv. 1750]").HumanoidRootPart.CFrame * CFrame.new(0,30,0))
                                elseif game:GetService("ReplicatedStorage"):FindFirstChild("Urban [Lv. 1750]") then
                                    topos(game:GetService("ReplicatedStorage"):FindFirstChild("Urban [Lv. 1750]").HumanoidRootPart.CFrame * CFrame.new(0,30,0))
                                else
                                    if getgenv().ElitehunterHop and game:GetService("ReplicatedStorage").Remotes["CommF_"]:InvokeServer("EliteHunter") == "I don't have anything for you right now. Come back later." then
                                        Hop()
                                    else
                                        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("EliteHunter")
                                    end
									if getgenv().ElitehunterHop then
                                        Hop()
								end
                                end
                            end                    
                        end
                    end
                end)
            end
        end
    end)
local Tap2 = Window:Taps("Visual")
 local Mainz = Tap2:newpage()
 local Boss = {}
    
 for i, v in pairs(game:GetService("ReplicatedStorage"):GetChildren()) do
	 if string.find(v.Name, "Boss") then
		 if v.Name == "Ice Admiral [Lv. 700] [Boss]" then
			 else
			 table.insert(Boss, v.Name)
		 end
	 end
 end
 Mainz:Label("🎡 Settings Boss 🎡")
	local BossName = Mainz:Drop("Select Boss",false,Boss,function(value)
		_G.Select_Boss = value
    end)
	Mainz:Button("Refresh Boss",function()
        BossName:Clear()
            for i, v in pairs(game:GetService("ReplicatedStorage"):GetChildren()) do
            if string.find(v.Name, "Boss") then
                BossName:Add(v.Name) 
            end
        end
	end)
	Mainz:Toggle("Auto Farm Boss",getgenv().FarmBoss,function(value)
		getgenv().FarmBoss = value
            game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AbandonQuest")
            getgenv().FarmBoss = value
            StopTween(getgenv().FarmBoss)
    end)
	Mainz:Toggle("Auto Farm All Boss",false,function(value)
		getgenv().FarmAllBoss = value
    end)
	Mainz:Toggle("All Boss Hop",false,function(value)
		getgenv().AllBossHop = value
    end)
	local Camera = require(game.ReplicatedStorage.Util.CameraShaker)
    Camera:Stop()
--AutoFarmBoss
spawn(function()
        while wait() do
            if getgenv().FarmBoss then
                pcall(function()
                    if game:GetService("Workspace").Enemies:FindFirstChild(_G.Select_Boss) then
                        for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                            if v.Name == _G.Select_Boss then
                                if v:FindFirstChild("Humanoid") and v:FindFirstChild("HumanoidRootPart") and v.Humanoid.Health > 0 then
                                    repeat task.wait()
                                        AutoHaki()
                                        EquipWeapon(_G.SelectWeapon)
                                        v.HumanoidRootPart.CanCollide = false
                                        v.Humanoid.JumpPower = 0
                                        v.Humanoid.WalkSpeed = 0
                                        v.HumanoidRootPart.Size = Vector3.new(80,180,80)                             
                                        topos(v.HumanoidRootPart.CFrame*CFrame.new(0,40,0))
                                        game:GetService("VirtualUser"):CaptureController()
                                        game:GetService("VirtualUser"):Button1Down(Vector2.new(1280,672))
                                        sethiddenproperty(game:GetService("Players").LocalPlayer,"SimulationRadius",math.huge)
                                    until not getgenv().FarmBoss or not v.Parent or v.Humanoid.Health <= 0
                                end
                            end
                        end
                    else
                        if game:GetService("ReplicatedStorage"):FindFirstChild(_G.Select_Boss) then
                            topos(game:GetService("ReplicatedStorage"):FindFirstChild(_G.Select_Boss).HumanoidRootPart.CFrame * CFrame.new(0,30,0))
                        end
                    end
                end)
            end
        end
    end)
--AutoFarmAllBoss
spawn(function()
        while wait() do
            if getgenv().FarmAllBoss then
                pcall(function()
                    for i,v in pairs(game.ReplicatedStorage:GetChildren()) do
                        if string.find(v.Name,"Boss") then
                            if (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude < 17000 then
                                repeat task.wait()
                                    AutoHaki()
                                    EquipWeapon(_G.SelectWeapon)
                                    v.Humanoid.JumpPower = 0
                                    v.Humanoid.WalkSpeed = 0
                                    v.HumanoidRootPart.CanCollide = false
                                    v.Head.CanCollide = false
                                    v.HumanoidRootPart.Size = Vector3.new(80,80,80)
                                    topos(v.HumanoidRootPart.CFrame*CFrame.new(0,30,0))
                                    game:GetService'VirtualUser':CaptureController()
                                    game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
                                    sethiddenproperty(game.Players.LocalPlayer,"SimulationRadius",math.huge)
                                until v.Humanoid.Health <= 0 or getgenv().FarmAllBoss == false or not v.Parent
                            end
                        else
                            if getgenv().AllBossHop then
                                Hop()
                            end
                        end
                    end
                end)
            end
        end
    end)   
	spawn(function()
		game:GetService("RunService").Heartbeat:Connect(function()
			if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Humanoid") and getgenv().cakefarm then
				setfflag("HumanoidParallelRemoveNoPhysics", "False")
				setfflag("HumanoidParallelRemoveNoPhysicsNoSimulate2", "False")
				game:GetService("Players").LocalPlayer.Character.Humanoid:ChangeState(11)
			end
		end)
		end)


local Client = game.Players.LocalPlayer
local STOP = require(Client.PlayerScripts.CombatFramework.Particle)
local STOPRL = require(game:GetService("ReplicatedStorage").CombatFramework.RigLib)
spawn(function()
	while task.wait() do
		if getgenv().cakefarm then
			pcall(function()
				if not shared.orl then shared.orl = STOPRL.wrapAttackAnimationAsync end
				if not shared.cpc then shared.cpc = STOP.play end
					STOPRL.wrapAttackAnimationAsync = function(a,b,c,d,func)
					local Hits = STOPRL.getBladeHits(b,c,d)
					if Hits then
						STOP.play = function() end
						a:Play(0.01,0.01,0.01)
						func(Hits)
						STOP.play = shared.cpc
						wait(a.length * 0.5)
						a:Stop()
					end
				end
			end)
		end
	end
end)

spawn(function()
game:GetService("RunService").Heartbeat:Connect(function()
	pcall(function()
		for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
			if getgenv().cakefarm and StartCakeMagnet and (v.Name == "Cookie Crafter [Lv. 2200]" or v.Name == "Cake Guard [Lv. 2225]" or v.Name == "Baking Staff [Lv. 2250]" or v.Name == "Head Baker [Lv. 2275]") and (v.HumanoidRootPart.Position - POSCAKE.Position).magnitude <= 350 then
				v.HumanoidRootPart.CFrame = POSCAKE
				v.HumanoidRootPart.CanCollide = false
				v.HumanoidRootPart.Size = Vector3.new(150,150,150)
				sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius",  math.huge)
			end
		end
	end)
end)
end)


spawn(function()
	while wait() do
		if getgenv().cakefarm then
			repeat wait() until game.CoreGui:FindFirstChild('RobloxPromptGui')
			local lp,po,ts = game:GetService('Players').LocalPlayer,game.CoreGui.RobloxPromptGui.promptOverlay,game:GetService('TeleportService')							
			po.ChildAdded:connect(function(a)
				if a.Name == 'ErrorPrompt' then
					repeat
						ts:Teleport(7449423635)
						wait(2)
					until false
				end
			end)
		end
	end
end)

spawn(function()
	game:GetService("RunService").RenderStepped:Connect(function()
		pcall(function()
			if getgenv().cakefarm then
				if game:GetService("Workspace").Enemies:FindFirstChild("Cake Prince [Lv. 2300] [Raid Boss]") then
						Mon = "Cake Prince [Lv. 2300] [Raid Boss]"
						CFMN = CFrame.new(-2042.34949, 4532.99805, -14844.8076, -0.629801929, 4.94784125e-08, 0.77675575, 6.7660352e-08, 1, -8.83906104e-09, -0.77675575, 4.69887134e-08, -0.629801929)
					elseif game:GetService("Workspace").Enemies:FindFirstChild("Cookie Crafter [Lv. 2200]") then
						Mon = "Cookie Crafter [Lv. 2200]"
						CFMN = CFrame.new(-2375.37109, 37.8240471, -12132.6592, 0.371290624, 0, 0.928516686, 0, 1, 0, -0.928516686, 0, 0.371290624)
					elseif game:GetService("Workspace").Enemies:FindFirstChild("Cake Guard [Lv. 2225]") then
						Mon = "Cake Guard [Lv. 2225]"
						CFMN = CFrame.new(-1547.46704, 37.8239517, -12256.4502, -0.863587916, 1.35471945e-08, -0.504198313, -1.54829394e-08, 1, 5.33878683e-08, 0.504198313, 5.39115916e-08, -0.863587916)
					elseif game:GetService("Workspace").Enemies:FindFirstChild("Baking Staff [Lv. 2250]") then
						Mon = "Baking Staff [Lv. 2250]"
						CFMN = CFrame.new(-1838.87097, 37.8239822, -12930.1797, 0.999966979, -4.56582017e-09, 0.0081237359, 4.51649829e-09, 1, 6.08966477e-09, -0.0081237359, -6.05277295e-09, 0.999966979)
					elseif game:GetService("Workspace").Enemies:FindFirstChild("Head Baker [Lv. 2275]") then
						Mon = "Head Baker [Lv. 2275]"
						CFMN = CFrame.new(-2246.24707, 53.5282593, -12863.1514, 0.83096534, 6.33553432e-10, 0.556324184, 2.73355644e-11, 1, -1.17965093e-09, -0.556324184, 9.95456495e-10, 0.83096534)
						end
				end
			end)
		   end)
		end)

	
spawn(function()
		   game:GetService("RunService").RenderStepped:Connect(function()
			pcall(function()
				if getgenv().cakefarm then
			local Distance2 = (game:GetService("Workspace").Enemies[Mon].HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
			local tween_s = game:service"TweenService"
			local info = TweenInfo.new(Distance2/350, Enum.EasingStyle.Linear)
			local tween = tween_s:Create(game:GetService("Players").LocalPlayer.Character["HumanoidRootPart"], info, {CFrame = game:GetService("Workspace").Enemies[Mon].HumanoidRootPart.CFrame * CFrame.new(0,45,0)})
			tween:Play()
	local CombatFramework = require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework)
		local Camera = require(game.ReplicatedStorage.Util.CameraShaker)
		Camera:Stop()
		getupvalues(CombatFramework)[2].activeController.hitboxMagnitude = 150
getupvalues(CombatFramework)[2]['activeController']:attack()  
			end
			end)
		   end)
end)
	
				spawn(function()
		   game:GetService("RunService").RenderStepped:Connect(function()
			pcall(function()
				if getgenv().cakefarm then
			if not game.Players.LocalPlayer.Character:FindFirstChild("HasBuso") then
			local args = {
			[1] = "Buso"
			}
			game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
		end
		end
		end)
		end)
				end)
	
			   spawn(function()
		   game:GetService("RunService").RenderStepped:Connect(function()
			pcall(function()
				if getgenv().cakefarm then
		for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
							for i2,v2 in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
								if v.Name == Mon and v2.Name == Mon then
									v2.HumanoidRootPart.CFrame = CFMN
									v2.HumanoidRootPart.CanCollide = false
									v.Humanoid:ChangeState(11)
								v.Humanoid.JumpPower = 0
								v.Humanoid.WalkSpeed = 0
								if v.Humanoid:FindFirstChild("Animator") then
									v.Humanoid.Animator:Destroy()
								end
									sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius", math.huge)
								end
							end
		end
					
				end
			end)
			end)
			end)

				 
			   
						   spawn(function()
		   game:GetService("RunService").RenderStepped:Connect(function()
			pcall(function()
				if getgenv().cakefarm then
				
				if game:GetService("Workspace").Enemies[Mon].Humanoid.Health == 0 then
	game:GetService("Workspace").Enemies[Mon]:Destroy()
	end
	end
	end)
	end)
						   end)


						   
						   spawn(function()
							game:GetService('RunService').Stepped:Connect(function()
								if _G.Fast_Attack_Normal3 then
									for i, v in pairs(game.Workspace["_WorldOrigin"]:GetChildren()) do
										if v.Name == "CurvedRing" or v.Name == "SwordSlash" or v.Name == "Sounds" or v.Name == "SlashHit" or v.Name == "DamageCounter" then--or v.Name == "SlashHit"
											v:Destroy() 
										end
									end
								end
							end)
						end)

	
		  spawn(function()
		game:GetService('RunService').Stepped:Connect(function()
			if getgenv().cakefarm then
				for i, v in pairs(game.Workspace["_WorldOrigin"]:GetChildren()) do
					if v.Name == "CurvedRing" or v.Name == "SwordSlash" or v.Name == "Sounds" or v.Name == "SlashHit" or v.Name == "DamageCounter" then--or v.Name == "SlashHit"
						v:Destroy() 
					end
				end
			end
		end)
	end)
	local Client = game.Players.LocalPlayer
	local STOP = require(Client.PlayerScripts.CombatFramework.Particle)
	local STOPRL = require(game:GetService("ReplicatedStorage").CombatFramework.RigLib)
	spawn(function()
		while task.wait() do
			if getgenv().cakefarm then
				pcall(function()
					if not shared.orl then shared.orl = STOPRL.wrapAttackAnimationAsync end
					if not shared.cpc then shared.cpc = STOP.play end
						STOPRL.wrapAttackAnimationAsync = function(a,b,c,d,func)
						local Hits = STOPRL.getBladeHits(b,c,d)
						if Hits then
							STOP.play = function() end
							a:Play(0.01,0.01,0.01)
							func(Hits)
							STOP.play = shared.cpc
							wait(a.length * 0.5)
							a:Stop()
						end
					end
				end)
			end
		end
	end)
	
spawn(function()
while wait() do
	if getgenv().Spawn_Cake_Prince then
		local args = {
			[1] = "CakePrinceSpawner",
			[2] = true
		}

		game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))                    
		local args = {
			[1] = "CakePrinceSpawner"
		}

		game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
	end
end
end)

spawn(function()
	game:GetService("RunService").Heartbeat:Connect(function()
		pcall(function()
			for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
				if getgenv().Ectoplasm and MagnetEctoplasm and string.find(v.Name, "Ship") and (v.HumanoidRootPart.Position - PosMonEctoplasm.Position).magnitude <= 350 then
					v.HumanoidRootPart.CFrame = PosMonEctoplasm
					v.HumanoidRootPart.CanCollide = false
					v.HumanoidRootPart.Size = Vector3.new(90,90,90)
					if v.Humanoid:FindFirstChild("Animator") then
						v.Humanoid.Animator:Destroy()
					end
					sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius",  math.huge)
				end
			end
		end)
	end)
end)

spawn(function()
	while wait() do
		if getgenv().Ectoplasm then
			pcall(function()
				if game:GetService("Workspace").Enemies:FindFirstChild("Ship Deckhand [Lv. 1250]") or game:GetService("Workspace").Enemies:FindFirstChild("Ship Engineer [Lv. 1275]") or game:GetService("Workspace").Enemies:FindFirstChild("Ship Steward [Lv. 1300]") or game:GetService("Workspace").Enemies:FindFirstChild("Ship Officer [Lv. 1325]") then
					for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
						if string.find(v.Name, "Ship") then
							repeat wait()
								AutoHaki()
								EquipWeapon(_G.SelectWeapon)
								PosMonEctoplasm = v.HumanoidRootPart.CFrame
								v.HumanoidRootPart.CanCollide = false
								v.HumanoidRootPart.Size = Vector3.new(90,90,90)
								v.Humanoid.JumpPower = 0
								v.Humanoid.WalkSpeed = 0
								getgenv().ToTarget(v.HumanoidRootPart.CFrame * CFrame.new(0,30,0))
								MagnetEctoplasm = true
								game:GetService'VirtualUser':CaptureController()
								game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
							until getgenv().Ectoplasm == false or not v.Parent or v.Humanoid.Health <= 0
							MagnetEctoplasm = false
						else
							MagnetEctoplasm = false
							getgenv().ToTarget(CFrame.new(904.4072265625, 181.05767822266, 33341.38671875))
						end
					end
				else
					MagnetEctoplasm = false
					local Distance = (Vector3.new(904.4072265625, 181.05767822266, 33341.38671875) - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
					if Distance > 20000 then
						game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(923.21252441406, 126.9760055542, 32852.83203125))
					end
					getgenv().ToTarget(CFrame.new(904.4072265625, 181.05767822266, 33341.38671875))
				end
			end)
		end
	end
end)    



 
 local TP = Tap2:newpage()
 TP:Label("🎡 Settings Teleport 🎡")
 if World1 then
	TP:Drop("Select Island",false,{
		"WindMill",
		"Marine",
		"Middle Town",
		"Jungle",
		"Pirate Village",
		"Desert",
		"Snow Island",
		"MarineFord",
		"Colosseum",
		"Sky Island 1",
		"Sky Island 2",
		"Sky Island 3",
		"Prison",
		"Magma Village",
		"Under Water Island",
		"Fountain City",
		"Shank Room",
		"Mob Island",
	},function(value)
		_G.SelectIsland = value
		end)
	end
 if World2 then
	TP:Drop("Select Island",false,{
		"The Cafe",
		"Frist Spot",
		"Dark Area",
		"Flamingo Mansion",
		"Flamingo Room",
		"Green Zone",
		"Factory",
		"Colossuim",
		"Zombie Island",
		"Two Snow Mountain",
		"Punk Hazard",
		"Cursed Ship",
		"Ice Castle",
		"Forgotten Island",
		"Ussop Island",
		"Mini Sky Island",
	},function(value)
		_G.SelectIsland = value
		end)
	end
 if World3 then
TP:Drop("Select Island",false,{
		"Mansion",
		"Port Town",
		"Great Tree",
		"Castle On The Sea",
		"MiniSky", 
		"Hydra Island",
		"Floating Turtle",
		"Haunted Castle",
		"Ice Cream Island",
		"Peanut Island",
		"Cake Island",
	},function(value)
		_G.SelectIsland = value
    end)
end
	TP:Toggle("Teleport",false,function(value)
		_G.TeleportIsland = value
		if _G.TeleportIsland == true then
			repeat wait()
				if _G.SelectIsland == "WindMill" then
					topos(CFrame.new(979.79895019531, 16.516613006592, 1429.0466308594))
				elseif _G.SelectIsland == "Marine" then
					topos(CFrame.new(-2566.4296875, 6.8556680679321, 2045.2561035156))
				elseif _G.SelectIsland == "Middle Town" then
					topos(CFrame.new(-690.33081054688, 15.09425163269, 1582.2380371094))
				elseif _G.SelectIsland == "Jungle" then
					topos(CFrame.new(-1612.7957763672, 36.852081298828, 149.12843322754))
				elseif _G.SelectIsland == "Pirate Village" then
					topos(CFrame.new(-1181.3093261719, 4.7514905929565, 3803.5456542969))
				elseif _G.SelectIsland == "Desert" then
					topos(CFrame.new(944.15789794922, 20.919729232788, 4373.3002929688))
				elseif _G.SelectIsland == "Snow Island" then
					topos(CFrame.new(1347.8067626953, 104.66806030273, -1319.7370605469))
				elseif _G.SelectIsland == "MarineFord" then
					topos(CFrame.new(-4914.8212890625, 50.963626861572, 4281.0278320313))
				elseif _G.SelectIsland == "Colosseum" then
					topos( CFrame.new(-1427.6203613281, 7.2881078720093, -2792.7722167969))
				elseif _G.SelectIsland == "Sky Island 1" then
					topos(CFrame.new(-4869.1025390625, 733.46051025391, -2667.0180664063))
				elseif _G.SelectIsland == "Sky Island 2" then  
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(-4607.82275, 872.54248, -1667.55688))
				elseif _G.SelectIsland == "Sky Island 3" then
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(-7894.6176757813, 5547.1416015625, -380.29119873047))
				elseif _G.SelectIsland == "Prison" then
					topos( CFrame.new(4875.330078125, 5.6519818305969, 734.85021972656))
				elseif _G.SelectIsland == "Magma Village" then
					topos(CFrame.new(-5247.7163085938, 12.883934020996, 8504.96875))
				elseif _G.SelectIsland == "Under Water Island" then
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(61163.8515625, 11.6796875, 1819.7841796875))
				elseif _G.SelectIsland == "Fountain City" then
					topos(CFrame.new(5127.1284179688, 59.501365661621, 4105.4458007813))
				elseif _G.SelectIsland == "Shank Room" then
					topos(CFrame.new(-1442.16553, 29.8788261, -28.3547478))
				elseif _G.SelectIsland == "Mob Island" then
					topos(CFrame.new(-2850.20068, 7.39224768, 5354.99268))
				elseif _G.SelectIsland == "The Cafe" then
					topos(CFrame.new(-380.47927856445, 77.220390319824, 255.82550048828))
				elseif _G.SelectIsland == "Frist Spot" then
					topos(CFrame.new(-11.311455726624, 29.276733398438, 2771.5224609375))
				elseif _G.SelectIsland == "Dark Area" then
					topos(CFrame.new(3780.0302734375, 22.652164459229, -3498.5859375))
				elseif _G.SelectIsland == "Flamingo Mansion" then
					topos(CFrame.new(-483.73370361328, 332.0383605957, 595.32708740234))
				elseif _G.SelectIsland == "Flamingo Room" then
					topos(CFrame.new(2284.4140625, 15.152037620544, 875.72534179688))
				elseif _G.SelectIsland == "Green Zone" then
					topos( CFrame.new(-2448.5300292969, 73.016105651855, -3210.6306152344))
				elseif _G.SelectIsland == "Factory" then
					topos(CFrame.new(424.12698364258, 211.16171264648, -427.54049682617))
				elseif _G.SelectIsland == "Colossuim" then
					topos( CFrame.new(-1503.6224365234, 219.7956237793, 1369.3101806641))
				elseif _G.SelectIsland == "Zombie Island" then
					topos(CFrame.new(-5622.033203125, 492.19604492188, -781.78552246094))
				elseif _G.SelectIsland == "Two Snow Mountain" then
					topos(CFrame.new(753.14288330078, 408.23559570313, -5274.6147460938))
				elseif _G.SelectIsland == "Punk Hazard" then
					topos(CFrame.new(-6127.654296875, 15.951762199402, -5040.2861328125))
				elseif _G.SelectIsland == "Cursed Ship" then
					topos(CFrame.new(923.40197753906, 125.05712890625, 32885.875))
				elseif _G.SelectIsland == "Ice Castle" then
					topos(CFrame.new(6148.4116210938, 294.38687133789, -6741.1166992188))
				elseif _G.SelectIsland == "Forgotten Island" then
					topos(CFrame.new(-3032.7641601563, 317.89672851563, -10075.373046875))
				elseif _G.SelectIsland == "Ussop Island" then
					topos(CFrame.new(4816.8618164063, 8.4599885940552, 2863.8195800781))
				elseif _G.SelectIsland == "Mini Sky Island" then
					topos(CFrame.new(-288.74060058594, 49326.31640625, -35248.59375))
				elseif _G.SelectIsland == "Great Tree" then
					topos(CFrame.new(2681.2736816406, 1682.8092041016, -7190.9853515625))
				elseif _G.SelectIsland == "Castle On The Sea" then
					topos(CFrame.new(-5074.45556640625, 314.5155334472656, -2991.054443359375))
				elseif _G.SelectIsland == "MiniSky" then
					topos(CFrame.new(-260.65557861328, 49325.8046875, -35253.5703125))
				elseif _G.SelectIsland == "Port Town" then
					topos(CFrame.new(-290.7376708984375, 6.729952812194824, 5343.5537109375))
				elseif _G.SelectIsland == "Hydra Island" then
					topos(CFrame.new(5228.8842773438, 604.23400878906, 345.0400390625))
				elseif _G.SelectIsland == "Floating Turtle" then
					topos(CFrame.new(-13274.528320313, 531.82073974609, -7579.22265625))
				elseif _G.SelectIsland == "Mansion" then
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(-12471.169921875, 374.94024658203, -7551.677734375))
				elseif _G.SelectIsland == "Haunted Castle" then
					topos(CFrame.new(-9515.3720703125, 164.00624084473, 5786.0610351562))
				elseif _G.SelectIsland == "Ice Cream Island" then
					topos(CFrame.new(-902.56817626953, 79.93204498291, -10988.84765625))
				elseif _G.SelectIsland == "Peanut Island" then
					topos(CFrame.new(-2062.7475585938, 50.473892211914, -10232.568359375))
				elseif _G.SelectIsland == "Cake Island" then
					topos(CFrame.new(-1884.7747802734375, 19.327526092529297, -11666.8974609375))
				end
			until not _G.TeleportIsland
		end
		StopTween(_G.TeleportIsland) 
    end)
	Playerslist = {}
	TP:Label("🎆 Settings Player 🎆")
    for i,v in pairs(game:GetService("Players"):GetChildren()) do
        table.insert(Playerslist,v.Name)
    end
	TP:Drop("Select Player",false,Playerslist,function(value)
		_G.SelectPly = value
    end)

	TP:Button("Refresh Players",function()
		Playerslist = {}
		SelectedPly:Clear()
		for i,v in pairs(game:GetService("Players"):GetChildren()) do  
			SelectedPly:Add(v.Name)
		end
	end)
	TP:Toggle("Spectate Players",false,function(value)
		SpectatePlys = value
		local plr1 = game:GetService("Players").LocalPlayer.Character.Humanoid
		local plr2 = game:GetService("Players"):FindFirstChild(_G.SelectPly)
		repeat wait(.1)
			game:GetService("Workspace").Camera.CameraSubject = game:GetService("Players"):FindFirstChild(_G.SelectPly).Character.Humanoid
		until SpectatePlys == false 
		game:GetService("Workspace").Camera.CameraSubject = game:GetService("Players").LocalPlayer.Character.Humanoid
    end)
	TP:Toggle("Teleport",false,function(value)
		_G.TeleportPly = value
		pcall(function()
			if _G.TeleportPly then
				repeat topos(game:GetService("Players")[_G.SelectPly].Character.HumanoidRootPart.CFrame) wait() until _G.TeleportPly == false
			end
			StopTween(_G.TeleportPly)
		end)
    end)
	TP:Toggle("Auto Farm Player",false,function(value)
		_G.Auto_Kill_Ply = value
		StopTween(_G.Auto_Kill_Ply)
    end)
	spawn(function()
        while wait() do
            if _G.Auto_Kill_Ply then
                pcall(function()
                    if _G.SelectPly ~= nil then 
                        if game.Players:FindFirstChild(_G.SelectPly) then
                            if game.Players:FindFirstChild(_G.SelectPly).Character.Humanoid.Health > 0 then
                                repeat task.wait()
                                    EquipWeapon(_G.SelectWeapon)
                                    AutoHaki()
                                    game.Players:FindFirstChild(_G.SelectPly).Character.HumanoidRootPart.CanCollide = false
                                    topos(game.Players:FindFirstChild(_G.SelectPly).Character.HumanoidRootPart.CFrame * CFrame.new(0,2,0))
                                    spawn(function()
                                        pcall(function()
                                            if _G.SelectWeapon == SelectWeaponGun then
                                                local args = {
                                                    [1] = game.Players:FindFirstChild(_G.SelectPly).Character.HumanoidRootPart.Position,
                                                    [2] = game.Players:FindFirstChild(_G.SelectPly).Character.HumanoidRootPart
                                                }
                                                game:GetService("Players").LocalPlayer.Character[SelectWeaponGun].RemoteFunctionShoot:InvokeServer(unpack(args))
                                            else
                                                game:GetService("VirtualUser"):CaptureController()
                                                game:GetService("VirtualUser"):Button1Down(Vector2.new(1280,672))
                                            end
                                        end)
                                    end)
                                until game.Players:FindFirstChild(_G.SelectPly).Character.Humanoid.Health <= 0 or not game.Players:FindFirstChild(_G.SelectPly) or not _G.Auto_Kill_Ply
                            end
                        end
                    end
                end)
            end
        end
    end)
		TP:Label("🎆 Settings Fruit 🎆")
		TP:Toggle("Auto Store Fruit",false,function(value)
			_G.Auto_Store_Fruit = value
		end)
		spawn(function()
			while wait() do
				if _G.Auto_Store_Fruit then
					for i,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
						if string.find(v.Name,"Fruit") then
							local FruitName = RemoveSpaces(v.Name)
							if v.Name == "Bird: Falcon Fruit" then
								NameFruit = "Bird-Bird: Falcon"
							elseif v.Name == "Bird: Phoenix Fruit" then
								NameFruit = "Bird-Bird: Phoenix"
							elseif v.Name == "Human: Buddha Fruit" then
								NameFruit = "Human-Human: Buddha"
							else
								NameFruit = FruitName.."-"..FruitName
							end
		
							local string_1 = "getInventoryFruits";
							local Target = game:GetService("ReplicatedStorage").Remotes["CommF_"];
							for i1,v1 in pairs(Target:InvokeServer(string_1)) do
								if v1.Name == NameFruit then
									HaveFruitInStore = true
								end
							end
							if not Have then
								local string_1 = "StoreFruit";
								local string_2 = NameFruit;
								local Target = game:GetService("ReplicatedStorage").Remotes["CommF_"];
								Target:InvokeServer(string_1, string_2);
							end
							HaveFruitInStore = false
						end
					end
				end
			end
		end)
		spawn(function()
			pcall(function()
				while wait(.3) do
					if getgenv().BringFruit then
						for i,v in pairs(game:GetService("Workspace"):GetChildren()) do
							if string.find(v.Name, "Fruit") then
								if v:IsA("Tool") then
									v.Handle.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0, 50, 0)
									wait(.2)
									firetouchinterest(game.Players.LocalPlayer.Character.HumanoidRootPart,v.Handle,0)
								end
							end
						end
					end
				end
			end)
		end)
		spawn(function()
			pcall(function()
				while wait(.1) do
					if getgenv().BringFruit2 then
						for i,v in pairs(game:GetService("Workspace"):GetChildren()) do
							if string.find(v.Name, "Fruit") then
								if v:IsA("Tool") then
									v.Handle.CFrame = topos(v.HumanoidRootPart.CFrame* CFrame.new(0, 50, 0))
									wait(.2)
									firetouchinterest(game.Players.LocalPlayer.Character.HumanoidRootPart,v.Handle,0)
								end
							end
						end
					end
				end
			end)
		end)
		TP:Toggle("Bring Fruit TP",false,function(value)
			getgenv().BringFruit = value
		end)
		TP:Toggle("Bring Fruit Tween",false,function(value)
			getgenv().BringFruit2 = value
		end)
		TP:Toggle("Auto Random Fruit",false,function(value)
			getgenv().randomfruit = value
		end)
		spawn(function()
			pcall(function()
				while wait(.1) do
					if getgenv().randomfruit then
						game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Cousin","Buy")
					end 
				end
			end)
		end)
		local TP2 = Tap2:newpage()
		TP2:Label("🎡 Settings Raid 🎡")
		spawn(function()
			while wait() do
				if _G.Auto_Buy_Chips_Dungeon then
					pcall(function()
						local args = {
							[1] = "RaidsNpc",
							[2] = "Select",
							[3] = (_G.SelectChip)
						}
						
						game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
					end)
				end
			end
		end)
		spawn(function()
			while wait() do
				if _G.Auto_Start_Dungeon then
					pcall(function()
						if World2 then
							if not game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 1") then
								if game.Players.LocalPlayer.Backpack:FindFirstChild("Special Microchip") then 
									fireclickdetector(game.Workspace.Map.CircleIsland.RaidSummon2.Button.Main.ClickDetector)
								end
							end
						elseif World3 then
							if not game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 1") then
								if game.Players.LocalPlayer.Backpack:FindFirstChild("Special Microchip") then
									fireclickdetector(game.Workspace.Map["Boat Castle"].RaidSummon2.Button.Main.ClickDetector)
								end
							end
						end
					end)
				end
			end
		end)
		spawn(function()
			while wait() do
				if _G.Auto_Next_Island2 then
					if not game.Players.LocalPlayer.PlayerGui.Main.Timer.Visible == false then
						if game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 5") then
							getgenv().ToTarget(game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 5").CFrame * CFrame.new(0,70,0))
						elseif game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 4") then
							getgenv().ToTarget(game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 4").CFrame * CFrame.new(0,70,0))
						elseif game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 3") then
							getgenv().ToTarget(game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 3").CFrame * CFrame.new(0,70,0))
						elseif game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 2") then
							getgenv().ToTarget(game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 2").CFrame * CFrame.new(0,70,0))
						elseif game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 1") then
							getgenv().ToTarget(game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 1").CFrame * CFrame.new(0,70,0))
						end
					end
				end
			end
		end)
		spawn(function()
			while wait() do
				if _G.Kill_Aura then
					for i,v in pairs(game.Workspace.Enemies:GetDescendants()) do
						if v:FindFirstChild("Humanoid") and v:FindFirstChild("HumanoidRootPart") and v.Humanoid.Health > 0 then
							pcall(function()
								repeat wait(.1)
									v.Humanoid.Health = 0
									v.HumanoidRootPart.CanCollide = false
									sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius", math.huge)
								until not _G.Kill_Aura  or not v.Parent or v.Humanoid.Health <= 0
							end)
						end
					end
				end
			end
		end)
		TP2:Drop("Select Chip",false,{"Flame","Ice","Quake","Light","Dark","String","Rumble","Magma","Human: Buddha","Sand","Bird: Phoenix","Dough"},function(value)
			_G.SelectChip = value
		end)
		
		TP2:Toggle("Auto Buy Chip",false,function(value)
			_G.Auto_Buy_Chips_Dungeon = value
		end)
		TP2:Toggle("Auto Starts Raid",false,function(value)
			_G.Auto_Start_Dungeon = value
		end)
				TP2:Toggle("Auto Next Island",false,function(value)
					_G.Auto_Next_Island2 = value
		end)
		TP2:Toggle("Kill Aura",false,function(value)
			_G.Kill_Aura = value
		end)
		local Tove = Window:Taps("Misc")
		local  love = Tove:newpage()
		love:Button("Rejoin Server",function()
			game:GetService("TeleportService"):Teleport(game.PlaceId, game:GetService("Players").LocalPlayer)
		end)
		love:Button("Hop To Lower Player",function()
			Hop()
		end)
		love:Button("Server Hop",function()
			getgenv().AutoTeleport = true
            getgenv().DontTeleportTheSameNumber = true 
            getgenv().CopytoClipboard = false
            if not game:IsLoaded() then
                print("Game is loading waiting...")
            end
            local maxplayers = math.huge
            local serversmaxplayer;
            local goodserver;
            local gamelink = "https://games.roblox.com/v1/games/" .. game.PlaceId .. "/servers/Public?sortOrder=Asc&limit=100" 
            function serversearch()
                for _, v in pairs(game:GetService("HttpService"):JSONDecode(game:HttpGetAsync(gamelink)).data) do
                    if type(v) == "table" and v.playing ~= nil and maxplayers > v.playing then
                        serversmaxplayer = v.maxPlayers
                        maxplayers = v.playing
                        goodserver = v.id
                    end
                end       
            end
            function getservers()
                serversearch()
                for i,v in pairs(game:GetService("HttpService"):JSONDecode(game:HttpGetAsync(gamelink))) do
                    if i == "nextPageCursor" then
                        if gamelink:find("&cursor=") then
                            local a = gamelink:find("&cursor=")
                            local b = gamelink:sub(a)
                            gamelink = gamelink:gsub(b, "")
                        end
                        gamelink = gamelink .. "&cursor=" ..v
                        getservers()
                    end
                end
            end 
            getservers()
            if AutoTeleport then
                if DontTeleportTheSameNumber then 
                    if #game:GetService("Players"):GetPlayers() - 4  == maxplayers then
                        return warn("It has same number of players (except you)")
                    elseif goodserver == game.JobId then
                        return warn("Your current server is the most empty server atm") 
                    end
                end
                game:GetService("TeleportService"):TeleportToPlaceInstance(game.PlaceId, goodserver)
            end
		end)

		love:Toggle("InfAbility Ghoul",false,function(infA)
            if infA then
                local Heightened_Senses = game:GetService("ReplicatedStorage").FX["Heightened Senses"]:Clone()
                Heightened_Senses.Parent = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart
        else
            game:GetService("Players").LocalPlayer.Character.HumanoidRootPart["Heightened Senses"]:Destroy()
        end
		end)
		love:Toggle("InfAbility Human",false,function(infA)
            if infA then
                local Last_Resort = game:GetService("ReplicatedStorage").FX["Last Resort"]:Clone()
                Last_Resort.Parent = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart
        else
            game:GetService("Players").LocalPlayer.Character.HumanoidRootPart["Last Resort"]:Destroy()
        end
		end)
		love:Toggle("InfAbility Cyborg",false,function(infA)
			if infA then
                local Energy_Core = game:GetService("ReplicatedStorage").FX["Energy Core"]:Clone()
                Energy_Core.Parent = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart
        else
            game:GetService("Players").LocalPlayer.Character.HumanoidRootPart["Energy Core"]:Destroy()
        end
		end)
		love:Toggle("InfAbility Sky",false,function(infA)
			if infA then
                local Heavenly_Blood = game:GetService("ReplicatedStorage").FX["Heavenly Blood"]:Clone()
            Heavenly_Blood.Parent = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart
        else
            game:GetService("Players").LocalPlayer.Character.HumanoidRootPart["Heavenly Blood"]:Destroy()
        end
		end)
		love:Toggle("InfAbility Fish",false,function(infA)
            if infA then
                local Water_Body = game:GetService("ReplicatedStorage").FX["Water Body"]:Clone()
                Water_Body.Parent = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart
        else
            game:GetService("Players").LocalPlayer.Character.HumanoidRootPart["Water Body"]:Destroy()
        end
		end)
		love:Toggle("InfAbility Mink",false,function(infA)
			if infA then
				local Agility = game:GetService("ReplicatedStorage").FX["Agility"]:Clone()
				Agility.Parent = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart
			else
				game:GetService("Players").LocalPlayer.Character.HumanoidRootPart["Agility"]:Destroy()
			  end
		end)
		love:Toggle("InfAbility ALL",false,function(infA)
			if infA then
                local Agility = game:GetService("ReplicatedStorage").FX["Agility"]:Clone()
                local Water_Body = game:GetService("ReplicatedStorage").FX["Water Body"]:Clone()
                local Heavenly_Blood = game:GetService("ReplicatedStorage").FX["Heavenly Blood"]:Clone()
                local Energy_Core = game:GetService("ReplicatedStorage").FX["Energy Core"]:Clone()
                local Heightened_Senses = game:GetService("ReplicatedStorage").FX["Heightened Senses"]:Clone()
                local Last_Resort = game:GetService("ReplicatedStorage").FX["Last Resort"]:Clone()
                Agility.Parent = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart
                Water_Body.Parent = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart
                Heavenly_Blood.Parent = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart
                Energy_Core.Parent = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart
                Heightened_Senses.Parent = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart
                Last_Resort.Parent = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart
            else
                game:GetService("Players").LocalPlayer.Character.HumanoidRootPart["Agility"]:Destroy()
                game:GetService("Players").LocalPlayer.Character.HumanoidRootPart["Water Body"]:Destroy()
                game:GetService("Players").LocalPlayer.Character.HumanoidRootPart["Heavenly Blood"]:Destroy()
                game:GetService("Players").LocalPlayer.Character.HumanoidRootPart["Energy Core"]:Destroy()
                game:GetService("Players").LocalPlayer.Character.HumanoidRootPart["Heightened Senses"]:Destroy()
                game:GetService("Players").LocalPlayer.Character.HumanoidRootPart["Last Resort"]:Destroy()
                
            end
		end)
		local  TP3 = Tove:newpage()
		TP3:TextBox("Webhook link","link Here",function(x)
			Webhooklink = x
		end)
		TP3:Button("Send Webhook",function()
			WebHookLog:WebHookKaiTanSend(Webhooklink)
		end)
		TP3:TextBox("BaseShee link","link Here",function(x)
			Baselink = x
		end)
		TP3:Button("Send BaseShee",function()
			WebHookLog:SheetBestLogSend(Baselink)
		end)
		
   local a = create.bar("")
	
	spawn(function()
	    pcall(function()
	        while task.wait() do
	            a:loadbar()
	        end
	    end)
	end) 
	return  create
