local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "THUNDER HUB", HidePremium = false, SaveConfig = true, ConfigFolder = "THUNDER HUB SOME TOWN"})

local dbView = false

local Tab1 = Window:MakeTab({
	Name = "Teleport",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})
local Tab2 = Window:MakeTab({
	Name = "Highlight",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})
local Tab3 = Window:MakeTab({
	Name = "Car",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})
local Tab4 = Window:MakeTab({
	Name = "Player",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})
local Tab5 = Window:MakeTab({
	Name = "Character",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})
local Tab6 = Window:MakeTab({
	Name = "AutoFarm",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})
local Tab7 = Window:MakeTab({
	Name = "Fake Item",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Section = Tab1:AddSection({
	Name = "Teleport Farm"
})

Tab1:AddButton({
	Name = "Wood",
	Callback = function()
    	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1310.61572, 18.0391312, -1718.38159, -0.447192252, 8.70090346e-08, 0.89443785, -2.39332887e-09, 1, -9.84744943e-08, -0.89443785, -4.61777141e-08, -0.447192252)
        OrionLib:MakeNotification({
            Name = "Teleport",
            Content = "Teleport To Wood",
            Image = "rbxassetid://4483345998",
            Time = 5
        })
    end    
})
Tab1:AddButton({
	Name = "Pork",
	Callback = function()
    	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-538.915894, 13.9583454, 2335.96924, 0.925712407, 3.55705119e-08, -0.378228158, -7.2071856e-08, 1, -8.23505601e-08, 0.378228158, 1.03492539e-07, 0.925712407)
        OrionLib:MakeNotification({
            Name = "Teleport",
            Content = "Teleport To Part",
            Image = "rbxassetid://4483345998",
            Time = 5
        })
    end    
})
Tab1:AddButton({
	Name = "Rock",
	Callback = function()
    	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-316.492859, -67.8217468, -2028.47546, 0.966099441, 4.67094008e-09, -0.258170217, -3.51835094e-09, 1, 4.92645214e-09, 0.258170217, -3.85110921e-09, 0.966099441)
        OrionLib:MakeNotification({
            Name = "Teleport",
            Content = "Teleport To Rock",
            Image = "rbxassetid://4483345998",
            Time = 5
        })
    end    
})
Tab1:AddButton({
	Name = "Plant", 
	Callback = function()
    	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(2199.05981, 16.2435379, -3326.05444, 0.998570502, 3.79036136e-09, -0.0534502007, -3.05782555e-09, 1, 1.37867948e-08, 0.0534502007, -1.36036453e-08, 0.998570502)
        OrionLib:MakeNotification({
            Name = "Teleport",
            Content = "Teleport To Plant",
            Image = "rbxassetid://4483345998",
            Time = 5
        })
    end    
})
Tab1:AddButton({
	Name = "Corn",
	Callback = function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-171.547043, 48.5520935, 447.17688, -0.584445894, 4.76066866e-08, -0.811432719, 1.10644893e-09, 1, 5.78729775e-08, 0.811432719, 3.2925815e-08, -0.584445894)
        OrionLib:MakeNotification({
            Name = "Teleport",-- 
            Content = "Teleport To Corn",
            Image = "rbxassetid://4483345998",
            Time = 5
        })
    end    
})
Tab1:AddButton({
	Name = "Banana",
	Callback = function()
    	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(67.1075668, 18.4468536, -272.878082, -0.891458333, 3.7502299e-09, 0.453102678, 1.36071767e-08, 1, 1.84947062e-08, -0.453102678, 2.26527082e-08, -0.891458333)
        OrionLib:MakeNotification({
            Name = "Teleport",
            Content = "Teleport To Banana",
            Image = "rbxassetid://4483345998",
            Time = 5
        })
    end    
})

local Section = Tab1:AddSection({
	Name = "Teleport Farm"
})

Tab1:AddButton({
	Name = "สภา",
	Callback = function()
    	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1464.83838, 55.6054382, 828.143005, 0.123219244, 5.23793275e-08, 0.992379487, -5.56022961e-09, 1, -5.20911634e-08, -0.992379487, 9.00775787e-10, 0.123219244)
        OrionLib:MakeNotification({
            Name = "Teleport",
            Content = "Teleport To สภา",
            Image = "rbxassetid://4483345998",
            Time = 5
        })
    end    
})
Tab1:AddButton({
	Name = "ตํารวจ",
	Callback = function()
    	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(3687.34644, 14.27174, 3619.75391, 0.0894601196, -5.73128434e-09, 0.995990396, -5.78499515e-09, 1, 6.27396668e-09, -0.995990396, -6.32306962e-09, 0.0894601196)
        OrionLib:MakeNotification({
            Name = "Teleport",
            Content = "Teleport To ตํารวจ",
            Image = "rbxassetid://4483345998",
            Time = 5
        })
    end    
})
Tab1:AddButton({
	Name = "ร้านค้า",
	Callback = function()
    	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(3002.34497, 14.3816833, 1925.05872, 0.999999821, 3.88486789e-08, -0.000590398966, -3.8818456e-08, 1, 5.11995246e-08, 0.000590398966, -5.1176599e-08, 0.999999821)
        OrionLib:MakeNotification({
            Name = "Teleport",
            Content = "Teleport To ร้านค้า",
            Image = "rbxassetid://4483345998",
            Time = 5
        })
    end    
})
Tab1:AddButton({
	Name = "ปั้มนํ้ามัน 1",
	Callback = function()
    	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(3716.26562, 14.7984238, 2891.52588, 0.696943641, 1.31163098e-08, -0.717125893, 3.59137857e-08, 1, 5.31931654e-08, 0.717125893, -6.28273469e-08, 0.696943641)
        OrionLib:MakeNotification({
            Name = "Teleport",
            Content = "Teleport To ปั้มนํ้ามัน 1",
            Image = "rbxassetid://4483345998",
            Time = 5
        })
    end    
})
Tab1:AddButton({
	Name = "เรเบล",
	Callback = function()
    	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(2501.14307, 15.1122379, 555.308167, -0.519874394, -9.84422428e-08, 0.854242682, -7.94727342e-08, 1, 6.68737314e-08, -0.854242682, -3.31230616e-08, -0.519874394)
        OrionLib:MakeNotification({
            Name = "Teleport",
            Content = "Teleport To เรเบล",
            Image = "rbxassetid://4483345998",
            Time = 5
        })
    end    
})
Tab1:AddButton({
	Name = "โรงพยาบาล",
	Callback = function()
    	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(3424.07275, 14.244236, 2596.35742, 0.95701617, 3.54125831e-08, 0.290034503, -2.19252403e-08, 1, -4.97519181e-08, -0.290034503, 4.12543137e-08, 0.95701617)
        OrionLib:MakeNotification({
            Name = "Teleport",
            Content = "Teleport To โรงพยาบาล",
            Image = "rbxassetid://4483345998",
            Time = 5
        })
    end    
})
Tab1:AddButton({
	Name = "แปรรูปหิน",
	Callback = function()
    	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1896.18726, 13.1281643, 3201.65015, 0.966443598, -1.41463534e-08, 0.256879002, 3.9046629e-08, 1, -9.18331651e-08, -0.256879002, 9.87818325e-08, 0.966443598)
        OrionLib:MakeNotification({
            Name = "Teleport",
            Content = "Teleport To แปรรูปหิน",
            Image = "rbxassetid://4483345998",
            Time = 5
        })
    end    
})
Tab1:AddButton({
	Name = "ตลาดโลก",
	Callback = function()
    	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(2845.45142, 14.2436848, 2079.27222, -0.388715088, 1.28141585e-06, -0.921357989, -1.4877221e-06, 1, 2.01845091e-06, 0.921357989, 2.15532691e-06, -0.388715088)
        OrionLib:MakeNotification({
            Name = "Teleport",
            Content = "Teleport To ตลาดโลก",
            Image = "rbxassetid://4483345998",
            Time = 5
        })
    end    
})
Tab1:AddButton({
	Name = "ร้านขายรถ",
	Callback = function()
    	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(3031.60376, 14.2829304, 2884.8916, -0.647440672, -4.2225075e-08, -0.762115836, -7.45602406e-08, 1, 7.93613619e-09, 0.762115836, 6.1961714e-08, -0.647440672)
        OrionLib:MakeNotification({
            Name = "Teleport",
            Content = "Teleport To ร้านขายรถ",
            Image = "rbxassetid://4483345998",
            Time = 5
        })
    end    
})
Tab1:AddButton({
	Name = "ปั้มนํ้ามัน 4",
	Callback = function()
    	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(293.110352, 14.1683521, -554.815552, 0.261437625, 3.62182604e-08, 0.965220392, 4.86328444e-09, 1, -3.88405681e-08, -0.965220392, 1.48485269e-08, 0.261437625)
        OrionLib:MakeNotification({
            Name = "Teleport",
            Content = "Teleport To ปั้มนํ็ามัน 4",
            Image = "rbxassetid://4483345998",
            Time = 5
        })
    end    
})
Tab1:AddButton({
	Name = "ปั้มนํ้ามัน 2",
	Callback = function()
    	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-266.731415, 14.9860458, 3485.51465, -0.00118964224, -6.67604567e-08, -0.999999285, -5.34426814e-09, 1, -6.67541471e-08, 0.999999285, 5.26485078e-09, -0.00118964224)
        OrionLib:MakeNotification({
            Name = "Teleport",
            Content = "Teleport To ปั้มนํ้ามัน 2",
            Image = "rbxassetid://4483345998",
            Time = 5
        })
    end    
})
Tab1:AddButton({
	Name = "อู่ช่าง",
	Callback = function()
    	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(2879.12012, 14.4760342, 2771.61133, -0.494345367, -3.71931961e-08, 0.869265616, -1.08556595e-08, 1, 3.6613379e-08, -0.869265616, 8.6632026e-09, -0.494345367)
        OrionLib:MakeNotification({
            Name = "Teleport",
            Content = "Teleport To อู่ช่าง",
            Image = "rbxassetid://4483345998",
            Time = 5
        })
    end    
})
Tab1:AddButton({
	Name = "ปั้มนํ้ามัน 3",
	Callback = function()
    	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1025.63696, 15.8193264, 1475.87134, 0.996082783, -9.14768372e-10, 0.0884257406, 5.54683299e-10, 1, 4.09674694e-09, -0.0884257406, -4.03165057e-09, 0.996082783)
        OrionLib:MakeNotification({
            Name = "Teleport",
            Content = "Teleport To ปั้มนํ้ามัน 3",
            Image = "rbxassetid://4483345998",
            Time = 5
        })
    end    
})

local Section = Tab1:AddSection({
	Name = "Teleport Cement"
})

Tab1:AddButton({
	Name = "Cement 1",
	Callback = function()
    	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(3495.99414, 77.2299347, 2934.33594, -0.452851057, -8.97525894e-08, 0.891586185, -2.05007229e-08, 1, 9.02535504e-08, -0.891586185, 2.25932535e-08, -0.452851057)
        OrionLib:MakeNotification({
            Name = "Teleport",
            Content = "Teleport To Cement 1",
            Image = "rbxassetid://4483345998",
            Time = 5
        })
    end    
})
Tab1:AddButton({
	Name = "Cement 2",
	Callback = function()
    	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(3243.1123, 17.4799843, 2980.90454, 0.173435032, -1.82180937e-08, -0.98484534, 2.21042349e-08, 1, -1.46057904e-08, 0.98484534, -1.92360972e-08, 0.173435032)
        OrionLib:MakeNotification({
            Name = "Teleport",
            Content = "Teleport To Cement 2",
            Image = "rbxassetid://4483345998",
            Time = 5
        })
    end    
})
Tab1:AddButton({
	Name = "Cement 3",
	Callback = function()
    	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(3887.19189, 49.9490967, 3367.62817, -0.605714977, -4.62784939e-08, -0.795681655, 5.59857192e-08, 1, -1.00781364e-07, 0.795681655, -1.05591596e-07, -0.605714977)
        OrionLib:MakeNotification({
            Name = "Teleport",
            Content = "Teleport To Cement 3",
            Image = "rbxassetid://4483345998",
            Time = 5
        })
    end    
})
Tab1:AddButton({
	Name = "Cement 4",
	Callback = function()
    	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(2859.61084, 17.2979889, 2443.59106, -0.0175855868, 3.63704835e-08, -0.999845386, 7.47965423e-09, 1, 3.6244554e-08, 0.999845386, -6.84111567e-09, -0.0175855868)
        OrionLib:MakeNotification({
            Name = "Teleport",
            Content = "Teleport To Cement 4",
            Image = "rbxassetid://4483345998",
            Time = 5
        })
    end    
})

local Section = Tab1:AddSection({
	Name = "Teleport Cement"
})

Tab1:AddButton({
	Name = "Wire 1",
	Callback = function()
    	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(3734.97949, 14.3816814, 2654.95483, 0.409280628, -5.27198418e-09, -0.912408531, -2.39213732e-10, 1, -5.88540061e-09, 0.912408531, 2.62704125e-09, 0.409280628)
        OrionLib:MakeNotification({
            Name = "Teleport",
            Content = "Teleport To Wire 1",
            Image = "rbxassetid://4483345998",
            Time = 5
        })
    end    
})
Tab1:AddButton({
	Name = "Wire 2",
	Callback = function()
    	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(2620.24512, 14.3816891, 2479.66821, 0.621054471, -7.94673394e-09, 0.783767402, 1.45210608e-08, 1, -1.36728739e-09, -0.783767402, 1.22302941e-08, 0.621054471)
        OrionLib:MakeNotification({
            Name = "Teleport",
            Content = "Teleport To Wire 2",
            Image = "rbxassetid://4483345998",
            Time = 5
        })
    end    
})
Tab1:AddButton({
	Name = "Wire 3",
	Callback = function()
    	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1911.3573, 14.5676041, 2506.57104, -0.168154433, -2.94396276e-08, 0.985760689, -1.25464965e-07, 1, 8.46264125e-09, -0.985760689, -1.22255386e-07, -0.168154433)
        OrionLib:MakeNotification({
            Name = "Teleport",
            Content = "Teleport To Wire 3",
            Image = "rbxassetid://4483345998",
            Time = 5
        })
    end    
})
Tab1:AddButton({
	Name = "Wire 4",
	Callback = function()
    	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(3167.71436, 14.5636768, 2767.69946, 0.253667325, -2.73629635e-08, -0.967291534, 5.92657834e-08, 1, -1.27460753e-08, 0.967291534, -5.4094027e-08, 0.253667325)
        OrionLib:MakeNotification({
            Name = "Teleport",
            Content = "Teleport To Wire 4",
            Image = "rbxassetid://4483345998",
            Time = 5
        })
    end    
})
Tab1:AddButton({
	Name = "Wire 5",
	Callback = function()
    	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(3736.69214, 14.3816814, 3681.44556, -0.999635398, -3.41276518e-09, 0.0270002559, -3.39440498e-09, 1, 7.25832283e-10, -0.0270002559, 6.33917807e-10, -0.999635398)
        OrionLib:MakeNotification({
            Name = "Teleport",
            Content = "Teleport To Wire 5",
            Image = "rbxassetid://4483345998",
            Time = 5
        })
    end    
})

Tab2:AddButton({
	Name = "All Highlight",
	Callback = function()
    	for i,v in pairs(game.Workspace.Black_Jobs:GetDescendants()) do
            if v:IsA("Model") then  
                local A = Instance.new("Highlight")
                A.Parent = v
            end
        end
        OrionLib:MakeNotification({
            Name = "Highlight",
            Content = "All Highlight Black_Jobs",
            Image = "rbxassetid://4483345998",
            Time = 5
        })
    end    
})
Tab2:AddButton({
	Name = "Highlight Cement",
	Callback = function()
        for i,v in pairs(game.Workspace.Black_Jobs.Cement:GetDescendants()) do
            if v:IsA("Model") then  
                local A = Instance.new("Highlight")
                A.Parent = v
            end
        end
        OrionLib:MakeNotification({
            Name = "Highlight",
            Content = "Highlight Cement",
            Image = "rbxassetid://4483345998",
            Time = 5
        })
    end    
})
Tab2:AddButton({
	Name = "Highlight Electrical cabinet",
	Callback = function()
        for i,v in pairs(game.Workspace["Electrical cabinet"]:GetDescendants()) do
            if v:IsA("Model") then  
                local A = Instance.new("Highlight")
                A.Parent = v
            end
        end
        OrionLib:MakeNotification({
            Name = "Highlight",
            Content = "Highlight Electrical cabinet",
            Image = "rbxassetid://4483345998",
            Time = 5
        })
    end    
})
Tab2:AddButton({
	Name = "Highlight Wire",
	Callback = function()
        for i,v in pairs(game.Workspace.Black_Jobs.Wire:GetDescendants()) do
            if v:IsA("Model") then  
                local A = Instance.new("Highlight")
                A.Parent = v
            end
        end
        OrionLib:MakeNotification({
            Name = "Highlight",
            Content = "Highlight Wire",
            Image = "rbxassetid://4483345998",
            Time = 5
        })
    end    
})
Tab2:AddButton({
	Name = "Close Highlight",
	Callback = function()
        for i,v in pairs(game.Workspace:GetDescendants()) do
            if v:IsA("Highlight") then  
               v:Destroy()
            end
        end
        OrionLib:MakeNotification({
            Name = "Highlight",
            Content = "Close Highlight",
            Image = "rbxassetid://4483345998",
            Time = 5
        })
    end    
})

local Section = Tab3:AddSection({
	Name = "CLIENT (แค่รถเรารถเดียว)"
})

Tab3:AddTextbox({
	Name = "DrivingTorque",
	Default = nil,
	TextDisappear = true,
	Callback = function(txt)
		for i, v in pairs(game.Workspace.PlayerVehicle:GetChildren()) do
            if v:IsA("Model") then  
                if v:GetAttribute("Owner") == game.Players.LocalPlayer.Name then
                    v.Settings.DrivingTorque.Value = txt
                    OrionLib:MakeNotification({
                        Name = "Car",
                        Content = "DrivingTorque: "..txt,
                        Image = "rbxassetid://4483345998",
                        Time = 5
                    })
                end
            end
        end
	end	  
})
Tab3:AddTextbox({
	Name = "Friction",
	Default = nil,
	TextDisappear = true,
	Callback = function(txt)
		for i, v in pairs(game.Workspace.PlayerVehicle:GetChildren()) do
            if v:IsA("Model") then  
                if v:GetAttribute("Owner") == game.Players.LocalPlayer.Name then
                    v.Settings.Friction.Value = txt
                    OrionLib:MakeNotification({
                        Name = "Car",
                        Content = "Friction: "..txt,
                        Image = "rbxassetid://4483345998",
                        Time = 5
                    })
                end
            end
        end
	end	  
})
Tab3:AddTextbox({
	Name = "IdleRPM",
	Default = nil,
	TextDisappear = true,
	Callback = function(txt)
		for i, v in pairs(game.Workspace.PlayerVehicle:GetChildren()) do
            if v:IsA("Model") then  
                if v:GetAttribute("Owner") == game.Players.LocalPlayer.Name then
                    v.Settings.IdleRPM.Value = txt
                    OrionLib:MakeNotification({
                        Name = "Car",
                        Content = "IdleRPM: "..txt,
                        Image = "rbxassetid://4483345998",
                        Time = 5
                    })
                end
            end
        end
	end	  
})
Tab3:AddTextbox({
	Name = "MaxHeight",
	Default = nil,
	TextDisappear = true,
	Callback = function(txt)
		for i, v in pairs(game.Workspace.PlayerVehicle:GetChildren()) do
            if v:IsA("Model") then  
                if v:GetAttribute("Owner") == game.Players.LocalPlayer.Name then
                    v.Settings.MaxHeight.Value = txt
                    OrionLib:MakeNotification({
                        Name = "Car",
                        Content = "MaxHeight: "..txt,
                        Image = "rbxassetid://4483345998",
                        Time = 5
                    })
                end
            end
        end
	end	  
})
Tab3:AddTextbox({
	Name = "MaxRPM",
	Default = nil,
	TextDisappear = true,
	Callback = function(txt)
		for i, v in pairs(game.Workspace.PlayerVehicle:GetChildren()) do
            if v:IsA("Model") then  
                if v:GetAttribute("Owner") == game.Players.LocalPlayer.Name then
                    v.Settings.MaxRPM.Value = txt
                    OrionLib:MakeNotification({
                        Name = "Car",
                        Content = "MaxRPM: "..txt,
                        Image = "rbxassetid://4483345998",
                        Time = 5
                    })
                end
            end
        end
	end	  
})
Tab3:AddTextbox({
	Name = "Speed",
	Default = nil,
	TextDisappear = true,
	Callback = function(txt)
		for i, v in pairs(game.Workspace.PlayerVehicle:GetChildren()) do
            if v:IsA("Model") then  
                if v:GetAttribute("Owner") == game.Players.LocalPlayer.Name then
                    v.Settings.MaxSpeed.Value = txt
                    OrionLib:MakeNotification({
                        Name = "Car",
                        Content = "Speed: "..txt,
                        Image = "rbxassetid://4483345998",
                        Time = 5
                    })
                end
            end
        end
	end	  
})
Tab3:AddTextbox({
	Name = "MaxSteer",
	Default = nil,
	TextDisappear = true,
	Callback = function(txt)
		for i, v in pairs(game.Workspace.PlayerVehicle:GetChildren()) do
            if v:IsA("Model") then  
                if v:GetAttribute("Owner") == game.Players.LocalPlayer.Name then
                    v.Settings.MaxSteer.Value = txt
                    OrionLib:MakeNotification({
                        Name = "Car",
                        Content = "MaxSteer: "..txt,
                        Image = "rbxassetid://4483345998",
                        Time = 5
                    })
                end
            end
        end
	end	  
})
Tab3:AddTextbox({
	Name = "MinHeight",
	Default = nil,
	TextDisappear = true,
	Callback = function(txt)
		for i, v in pairs(game.Workspace.PlayerVehicle:GetChildren()) do
            if v:IsA("Model") then  
                if v:GetAttribute("Owner") == game.Players.LocalPlayer.Name then
                    v.Settings.MinHeight.Value = txt
                    OrionLib:MakeNotification({
                        Name = "Car",
                        Content = "MinHeight: "..txt,
                        Image = "rbxassetid://4483345998",
                        Time = 5
                    })
                end
            end
        end
	end	  
})
Tab3:AddTextbox({
	Name = "RedlineRPM",
	Default = nil,
	TextDisappear = true,
	Callback = function(txt)
		for i, v in pairs(game.Workspace.PlayerVehicle:GetChildren()) do
            if v:IsA("Model") then  
                if v:GetAttribute("Owner") == game.Players.LocalPlayer.Name then
                    v.Settings.RedlineRPM.Value = txt
                    OrionLib:MakeNotification({
                        Name = "Car",
                        Content = "RedlineRPM: "..txt,
                        Image = "rbxassetid://4483345998",
                        Time = 5
                    })
                end
            end
        end
	end	  
})
Tab3:AddTextbox({
	Name = "ReverseSpeed",
	Default = nil,
	TextDisappear = true,
	Callback = function(txt)
		for i, v in pairs(game.Workspace.PlayerVehicle:GetChildren()) do
            if v:IsA("Model") then  
                if v:GetAttribute("Owner") == game.Players.LocalPlayer.Name then
                    v.Settings.ReverseSpeed.Value = txt
                    OrionLib:MakeNotification({
                        Name = "Car",
                        Content = "ReverseSpeed: "..txt,
                        Image = "rbxassetid://4483345998",
                        Time = 5
                    })
                end
            end
        end
	end	  
})

local Section = Tab3:AddSection({
	Name = "CLIENT (รถทุกคัน)"
})

Tab3:AddTextbox({
	Name = "DrivingTorqueAll",
	Default = nil,
	TextDisappear = true,
	Callback = function(txt)
		for i, v in pairs(game.Workspace.PlayerVehicle:GetChildren()) do
            if v:IsA("Model") then  
                v.Settings.DrivingTorque.Value = txt
                OrionLib:MakeNotification({
                    Name = "Car",
                    Content = "DrivingTorque: "..txt,
                    Image = "rbxassetid://4483345998",
                    Time = 5
                })
            end
        end
	end	  
})
Tab3:AddTextbox({
	Name = "FrictionAll",
	Default = nil,
	TextDisappear = true,
	Callback = function(txt)
		for i, v in pairs(game.Workspace.PlayerVehicle:GetChildren()) do
            if v:IsA("Model") then  
                v.Settings.Friction.Value = txt
                OrionLib:MakeNotification({
                    Name = "Car",
                    Content = "Friction: "..txt,
                    Image = "rbxassetid://4483345998",
                    Time = 5
                })
            end
        end
	end	  
})
Tab3:AddTextbox({
	Name = "IdleRPMAll",
	Default = nil,
	TextDisappear = true,
	Callback = function(txt)
		for i, v in pairs(game.Workspace.PlayerVehicle:GetChildren()) do
            if v:IsA("Model") then  
                v.Settings.IdleRPM.Value = txt
                OrionLib:MakeNotification({
                    Name = "Car",
                    Content = "IdleRPM: "..txt,
                    Image = "rbxassetid://4483345998",
                    Time = 5
                })
            end
        end
	end	  
})
Tab3:AddTextbox({
	Name = "MaxHeightAll",
	Default = nil,
	TextDisappear = true,
	Callback = function(txt)
		for i, v in pairs(game.Workspace.PlayerVehicle:GetChildren()) do
            if v:IsA("Model") then  
                v.Settings.MaxHeight.Value = txt
                OrionLib:MakeNotification({
                    Name = "Car",
                    Content = "MaxHeight: "..txt,
                    Image = "rbxassetid://4483345998",
                    Time = 5
                })
            end
        end
	end	  
})
Tab3:AddTextbox({
	Name = "MaxRPMAll",
	Default = nil,
	TextDisappear = true,
	Callback = function(txt)
		for i, v in pairs(game.Workspace.PlayerVehicle:GetChildren()) do
            if v:IsA("Model") then  
                v.Settings.MaxRPM.Value = txt
                OrionLib:MakeNotification({
                    Name = "Car",
                    Content = "MaxRPM: "..txt,
                    Image = "rbxassetid://4483345998",
                    Time = 5
                })
            end
        end
	end	  
})
Tab3:AddTextbox({
	Name = "SpeedAll",
	Default = nil,
	TextDisappear = true,
	Callback = function(txt)
		for i, v in pairs(game.Workspace.PlayerVehicle:GetChildren()) do
            if v:IsA("Model") then  
                v.Settings.MaxSpeed.Value = txt
                OrionLib:MakeNotification({
                    Name = "Car",
                    Content = "Speed: "..txt,
                    Image = "rbxassetid://4483345998",
                    Time = 5
                })
            end
        end
	end	  
})
Tab3:AddTextbox({
	Name = "MaxSteerAll",
	Default = nil,
	TextDisappear = true,
	Callback = function(txt)
		for i, v in pairs(game.Workspace.PlayerVehicle:GetChildren()) do
            if v:IsA("Model") then  
                v.Settings.MaxSteer.Value = txt
                OrionLib:MakeNotification({
                    Name = "Car",
                    Content = "MaxSteer: "..txt,
                    Image = "rbxassetid://4483345998",
                    Time = 5
                })
            end
        end
	end	  
})
Tab3:AddTextbox({
	Name = "MinHeightAll",
	Default = nil,
	TextDisappear = true,
	Callback = function(txt)
		for i, v in pairs(game.Workspace.PlayerVehicle:GetChildren()) do
            if v:IsA("Model") then  
                v.Settings.MinHeight.Value = txt
                OrionLib:MakeNotification({
                    Name = "Car",
                    Content = "MinHeight: "..txt,
                    Image = "rbxassetid://4483345998",
                    Time = 5
                })
            end
        end
	end	  
})
Tab3:AddTextbox({
	Name = "RedlineRPMAll",
	Default = nil,
	TextDisappear = true,
	Callback = function(txt)
		for i, v in pairs(game.Workspace.PlayerVehicle:GetChildren()) do
            if v:IsA("Model") then  
                v.Settings.RedlineRPM.Value = txt
                OrionLib:MakeNotification({
                    Name = "Car",
                    Content = "RedlineRPM: "..txt,
                    Image = "rbxassetid://4483345998",
                    Time = 5
                })
            end
        end
	end	  
})
Tab3:AddTextbox({
	Name = "ReverseSpeedAll",
	Default = nil,
	TextDisappear = true,
	Callback = function(txt)
		for i, v in pairs(game.Workspace.PlayerVehicle:GetChildren()) do
            if v:IsA("Model") then  
                v.Settings.ReverseSpeed.Value = txt
                OrionLib:MakeNotification({
                    Name = "Car",
                    Content = "ReverseSpeed: "..txt,
                    Image = "rbxassetid://4483345998",
                    Time = 5
                })
            end
        end
	end	  
})

local Section = Tab3:AddSection({
	Name = "Check"
})

Tab3:AddButton({
	Name = "Check DrivingTorque",
	Callback = function()
        for i, v in pairs(game.Workspace.PlayerVehicle:GetChildren()) do
            if v:IsA("Model") then  
                if v:GetAttribute("Owner") == game.Players.LocalPlayer.Name then
                    OrionLib:MakeNotification({
                        Name = "Car",
                        Content = v.Settings.DrivingTorque.Value,
                        Image = "rbxassetid://4483345998",
                        Time = 5
                    })
                end
            end
        end
    end
})
Tab3:AddButton({
	Name = "Check Friction",
	Callback = function()
        for i, v in pairs(game.Workspace.PlayerVehicle:GetChildren()) do
            if v:IsA("Model") then  
                if v:GetAttribute("Owner") == game.Players.LocalPlayer.Name then
                    OrionLib:MakeNotification({
                        Name = "Car",
                        Content = v.Settings.Friction.Value,
                        Image = "rbxassetid://4483345998",
                        Time = 5
                    })
                end
            end
        end
    end    
})
Tab3:AddButton({
	Name = "Check Friction",
	Callback = function()
        for i, v in pairs(game.Workspace.PlayerVehicle:GetChildren()) do
            if v:IsA("Model") then  
                if v:GetAttribute("Owner") == game.Players.LocalPlayer.Name then
                    OrionLib:MakeNotification({
                        Name = "Car",
                        Content = v.Settings.Friction.Value,
                        Image = "rbxassetid://4483345998",
                        Time = 5
                    })
                end
            end
        end
    end    
})
Tab3:AddButton({
	Name = "Check MaxHeight",
	Callback = function()
        for i, v in pairs(game.Workspace.PlayerVehicle:GetChildren()) do
            if v:IsA("Model") then  
                if v:GetAttribute("Owner") == game.Players.LocalPlayer.Name then
                    OrionLib:MakeNotification({
                        Name = "Car",
                        Content = v.Settings.MaxHeight.Value,
                        Image = "rbxassetid://4483345998",
                        Time = 5
                    })
                end
            end
        end
    end    
})
Tab3:AddButton({
	Name = "Check MaxRPM",
	Callback = function()
        for i, v in pairs(game.Workspace.PlayerVehicle:GetChildren()) do
            if v:IsA("Model") then  
                if v:GetAttribute("Owner") == game.Players.LocalPlayer.Name then
                    OrionLib:MakeNotification({
                        Name = "Car",
                        Content = v.Settings.MaxRPM.Value,
                        Image = "rbxassetid://4483345998",
                        Time = 5
                    })
                end
            end
        end
    end    
})
Tab3:AddButton({
	Name = "Check MaxSpeed",
	Callback = function()
        for i, v in pairs(game.Workspace.PlayerVehicle:GetChildren()) do
            if v:IsA("Model") then  
                if v:GetAttribute("Owner") == game.Players.LocalPlayer.Name then
                    OrionLib:MakeNotification({
                        Name = "Car",
                        Content = v.Settings.MaxSpeed.Value,
                        Image = "rbxassetid://4483345998",
                        Time = 5
                    })
                end
            end
        end
    end    
})
Tab3:AddButton({
	Name = "Check MaxSteer",
	Callback = function()
        for i, v in pairs(game.Workspace.PlayerVehicle:GetChildren()) do
            if v:IsA("Model") then  
                if v:GetAttribute("Owner") == game.Players.LocalPlayer.Name then
                    OrionLib:MakeNotification({
                        Name = "Car",
                        Content = v.Settings.MaxSteer.Value,
                        Image = "rbxassetid://4483345998",
                        Time = 5
                    })
                end
            end
        end
    end    
})
Tab3:AddButton({
	Name = "Check MinHeight",
	Callback = function()
        for i, v in pairs(game.Workspace.PlayerVehicle:GetChildren()) do
            if v:IsA("Model") then  
                if v:GetAttribute("Owner") == game.Players.LocalPlayer.Name then
                    OrionLib:MakeNotification({
                        Name = "Car",
                        Content = v.Settings.MinHeight.Value,
                        Image = "rbxassetid://4483345998",
                        Time = 5
                    })
                end
            end
        end
    end    
})
Tab3:AddButton({
	Name = "Check RedlineRPM",
	Callback = function()
        for i, v in pairs(game.Workspace.PlayerVehicle:GetChildren()) do
            if v:IsA("Model") then  
                if v:GetAttribute("Owner") == game.Players.LocalPlayer.Name then
                    OrionLib:MakeNotification({
                        Name = "Car",
                        Content = v.Settings.RedlineRPM.Value,
                        Image = "rbxassetid://4483345998",
                        Time = 5
                    })
                end
            end
        end
    end    
})
Tab3:AddButton({
	Name = "Check ReverseSpeed",
	Callback = function()
        for i, v in pairs(game.Workspace.PlayerVehicle:GetChildren()) do
            if v:IsA("Model") then  
                if v:GetAttribute("Owner") == game.Players.LocalPlayer.Name then
                    OrionLib:MakeNotification({
                        Name = "Car",
                        Content = v.Settings.ReverseSpeed.Value,
                        Image = "rbxassetid://4483345998",
                        Time = 5
                    })
                end
            end
        end
    end    
})

Plr = {}
for i,v in pairs(game:GetService("Players"):GetChildren()) do
    table.insert(Plr,v.Name) 
end
local drop = Tab4:AddDropdown({
	Name = "Select Player!",
	Default = "Click To Select",
	Options = Plr,
	Callback = function(t)
		PlayerTP = t
        OrionLib:MakeNotification({
            Name = "Players",
            Content = t,
            Image = "rbxassetid://4483345998",
            Time = 5
        })
	end    
})
Tab4:AddButton({
	Name = "Click To TP",
	Callback = function()
        game.Workspace.Character[game.Players.LocalPlayer.Name].HumanoidRootPart.CFrame = game.Workspace.Character[PlayerTP].HumanoidRootPart.CFrame
        OrionLib:MakeNotification({
            Name = "Teleport",
            Content = "Teleport To Players: "..PlayerTP,
            Image = "rbxassetid://4483345998",
            Time = 5
        })
    end    
})
Tab4:AddToggle({
	Name = "Auto Teleport",
	Default = false,
	Callback = function(Value)
		_G.LLLLL = Value
        while _G.LLLLL do wait()
            game.Workspace.Character[game.Players.LocalPlayer.Name].HumanoidRootPart.CFrame = game.Workspace.Character[PlayerTP].HumanoidRootPart.CFrame
        end
	end    
})
Tab4:AddButton({
	Name = "Refresh Dropdown",
	Callback = function()
        drop:Refresh()
    end    
})
Tab4:AddButton({
	Name = "View",
	Callback = function()
        if dbView == false then
            game.Workspace.Camera.CameraSubject = game.Workspace.Character[PlayerTP]
            dbView = true
        elseif dbView == true then
            game.Workspace.Camera.CameraSubject = game.Workspace.Character[game.Players.LocalPlayer.Name]
            dbView = false
        end
    end    
})

Tab5:AddSlider({
	Name = "Speed Character",
	Min = 0,
	Max = 100,
	Default = game.Workspace.Character[game.Players.LocalPlayer.Name].Humanoid.WalkSpeed,
	Color = Color3.fromRGB(255,255,255),
	Increment = 1,
	ValueName = "Speed",
	Callback = function(ValueSpeed)
		 game.Workspace.Character[game.Players.LocalPlayer.Name].Humanoid.WalkSpeed = ValueSpeed
	end    
})
Tab5:AddSlider({
	Name = "Jump Character",
	Min = 0,
	Max = 100,
	Default = game.Workspace.Character[game.Players.LocalPlayer.Name].Humanoid.JumpPower,
	Color = Color3.fromRGB(255,255,255),
	Increment = 1,
	ValueName = "Jump",
	Callback = function(ValueSpeed)
		 game.Workspace.Character[game.Players.LocalPlayer.Name].Humanoid.JumpPower = ValueSpeed
	end    
})
Tab5:AddTextbox({
	Name = "Speed Character",
	Default = nil,
	TextDisappear = true,
	Callback = function(Speed)
		game.Workspace.Character[game.Players.LocalPlayer.Name].Humanoid.WalkSpeed = Speed
	end	  
})
Tab5:AddTextbox({
	Name = "Jump Character",
	Default = nil,
	TextDisappear = true,
	Callback = function(Speed)
		game.Workspace.Character[game.Players.LocalPlayer.Name].Humanoid.JumpPower = Speed
	end	  
})
Tab5:AddButton({
	Name = "review",
	Callback = function()
        game.Workspace.Character[game.Players.LocalPlayer.Name].Humanoid.Health = 0
    end    
})

local FarmName = nil

Tab6:AddDropdown({
	Name = "Dropdown",
	Default = nil,
	Options = {"Wood", "ScrapIron", "Rock", "Pork", "Plant", "Giftbox", "Flower", "Corn", "Banana"},
	Callback = function(Value)
		FarmName = tostring(Value)
	end    
})

Tab6:AddToggle({
	Name = "Auto Sell",
	Default = false,
	Callback = function(t)
		    if FarmName == "Wood" then
                                                            local JU = game:GetService("Workspace"):FindFirstChild("JU")
                                                            if JU then
                                                                JU:Destroy()
                                                            end
                                                        local Noclip = Instance.new("Part", workspace)
                                                            Noclip.Name = "JU"
                                                            Noclip.CanCollide = true
                                                            Noclip.Anchored = true
                                                            Noclip.Transparency = 0.5
                                                            Noclip.Size = Vector3.new(30, 1, 30)
                                                            game:GetService("Workspace"):FindFirstChild("JU").CFrame = CFrame.new(2846.16187, 3.34974432, 2078.43701, -0.585431039, -0.0284520276, -0.810222805, -1.68365466e-09, 0.999383986, -0.0350946672, 0.810722172, -0.0205455068, -0.585070431)

                                                    local teleport_table = {
                                                        location1 = Vector3.new(2845.45142, 14.2436848, 2079.27222, -0.388715088, 1.28141585e-06, -0.921357989, -1.4877221e-06, 1, 2.01845091e-06, 0.921357989, 2.15532691e-06, -0.388715088),
                                                        location2 = Vector3.new(1268, 14, -1705)
                                                    }

                                                    local tween_s = game:GetService('TweenService')
                                                    local tweeninfo = TweenInfo.new(0,Enum.EasingStyle.Linear)

                                                    local lp = game.Players.LocalPlayer

                                                    function bypass_teleport(v)
                                                        if lp.Character and 
                                                        lp.Character:FindFirstChild('HumanoidRootPart') then
                                                            local cf = CFrame.new(v)
                                                            local a = tween_s:Create(lp.Character.HumanoidRootPart,tweeninfo,{CFrame=cf})
                                                            a:Play()
                                                            a.Completed:Wait()
                                                            print('Teleporting Done!')
                                                        end
                                                    end

                                                    bypass_teleport(teleport_table.location2)

                                                    local Players = game:GetService("Players")

                                                    local LocalPlayer = Players.LocalPlayer

                                                    local Inventory = LocalPlayer.Inventory

                                                    _G.AutoFarm = t

                                                    while _G.AutoFarm do wait()
                                                        if Inventory:GetAttribute("Wood") >= 50 then
                                                            game.Workspace.Character[game.Players.LocalPlayer.Name].Humanoid.WalkSpeed = 0
                                                            wait(6.5)
                                                            game:GetService("Workspace"):FindFirstChild("Character"):FindFirstChild(game.Players.LocalPlayer.Name):FindFirstChild("HumanoidRootPart").CFrame = CFrame.new(2846.16187, 5.34974432, 2078.43701, -0.585431039, -0.0284520276, -0.810222805, -1.68365466e-09, 0.999383986, -0.0350946672, 0.810722172, -0.0205455068, -0.585070431)
                                                            wait(2.5)
                                                            local args = {
                                                                [1] = "fire",
                                                                [3] = "Economy",
                                                                [4] = FarmName,
                                                                [5] = Inventory:GetAttribute("Wood")
                                                            }

                                                            game:GetService("ReplicatedStorage"):WaitForChild("Modules"):WaitForChild("NetworkFramework"):WaitForChild("NetworkEvent"):FireServer(unpack(args))
                                                            wait(10)
                                                            bypass_teleport(teleport_table.location2)
                                                            game.Workspace.Character[game.Players.LocalPlayer.Name].Humanoid.WalkSpeed = 27
                                                        end
                                                    end
        elseif FarmName == "ScrapIron" then
                                                            local JU = game:GetService("Workspace"):FindFirstChild("JU")
                                                            if JU then
                                                                JU:Destroy()
                                                            end
                                                        local Noclip = Instance.new("Part", workspace)
                                                            Noclip.Name = "JU"
                                                            Noclip.CanCollide = true
                                                            Noclip.Anchored = true
                                                            Noclip.Transparency = 0.5
                                                            Noclip.Size = Vector3.new(30, 1, 30)
                                                            game:GetService("Workspace"):FindFirstChild("JU").CFrame = CFrame.new(2846.16187, 3.34974432, 2078.43701, -0.585431039, -0.0284520276, -0.810222805, -1.68365466e-09, 0.999383986, -0.0350946672, 0.810722172, -0.0205455068, -0.585070431)

                                                    local teleport_table = {
                                                        location1 = Vector3.new(2845.45142, 14.2436848, 2079.27222, -0.388715088, 1.28141585e-06, -0.921357989, -1.4877221e-06, 1, 2.01845091e-06, 0.921357989, 2.15532691e-06, -0.388715088),
                                                        location2 = Vector3.new(1087, 13, 3701)
                                                    }

                                                    local tween_s = game:GetService('TweenService')
                                                    local tweeninfo = TweenInfo.new(0,Enum.EasingStyle.Linear)

                                                    local lp = game.Players.LocalPlayer

                                                    function bypass_teleport(v)
                                                        if lp.Character and 
                                                        lp.Character:FindFirstChild('HumanoidRootPart') then
                                                            local cf = CFrame.new(v)
                                                            local a = tween_s:Create(lp.Character.HumanoidRootPart,tweeninfo,{CFrame=cf})
                                                            a:Play()
                                                            a.Completed:Wait()
                                                            print('Teleporting Done!')
                                                        end
                                                    end

                                                    bypass_teleport(teleport_table.location2)

                                                    local Players = game:GetService("Players")

                                                    local LocalPlayer = Players.LocalPlayer

                                                    local Inventory = LocalPlayer.Inventory

                                                    _G.AutoFarm = t

                                                    while _G.AutoFarm do wait()
                                                        if Inventory:GetAttribute("ScrapIron") >= 290 then
                                                            game.Workspace.Character[game.Players.LocalPlayer.Name].Humanoid.WalkSpeed = 0
                                                            wait(6.5)
                                                            game:GetService("Workspace"):FindFirstChild("Character"):FindFirstChild(game.Players.LocalPlayer.Name):FindFirstChild("HumanoidRootPart").CFrame = CFrame.new(2846.16187, 5.34974432, 2078.43701, -0.585431039, -0.0284520276, -0.810222805, -1.68365466e-09, 0.999383986, -0.0350946672, 0.810722172, -0.0205455068, -0.585070431)
                                                            wait(2.5)
                                                            local args = {
                                                                [1] = "fire",
                                                                [3] = "Economy",
                                                                [4] = FarmName,
                                                                [5] = Inventory:GetAttribute("ScrapIron")
                                                            }

                                                            game:GetService("ReplicatedStorage"):WaitForChild("Modules"):WaitForChild("NetworkFramework"):WaitForChild("NetworkEvent"):FireServer(unpack(args))
                                                            wait(10)
                                                            bypass_teleport(teleport_table.location2)
                                                            game.Workspace.Character[game.Players.LocalPlayer.Name].Humanoid.WalkSpeed = 27
                                                        end
                                                    end
        elseif FarmName == "Rock" then
                                                            local JU = game:GetService("Workspace"):FindFirstChild("JU")
                                                            if JU then
                                                                JU:Destroy()
                                                            end
                                                        local Noclip = Instance.new("Part", workspace)
                                                            Noclip.Name = "JU"
                                                            Noclip.CanCollide = true
                                                            Noclip.Anchored = true
                                                            Noclip.Transparency = 0.5
                                                            Noclip.Size = Vector3.new(30, 1, 30)
                                                            game:GetService("Workspace"):FindFirstChild("JU").CFrame = CFrame.new(2846.16187, 3.34974432, 2078.43701, -0.585431039, -0.0284520276, -0.810222805, -1.68365466e-09, 0.999383986, -0.0350946672, 0.810722172, -0.0205455068, -0.585070431)

                                                    local teleport_table = {
                                                        location1 = Vector3.new(2845.45142, 14.2436848, 2079.27222, -0.388715088, 1.28141585e-06, -0.921357989, -1.4877221e-06, 1, 2.01845091e-06, 0.921357989, 2.15532691e-06, -0.388715088),
                                                        location2 = Vector3.new(-272, -92, -2066)
                                                    }

                                                    local tween_s = game:GetService('TweenService')
                                                    local tweeninfo = TweenInfo.new(0,Enum.EasingStyle.Linear)

                                                    local lp = game.Players.LocalPlayer

                                                    function bypass_teleport(v)
                                                        if lp.Character and 
                                                        lp.Character:FindFirstChild('HumanoidRootPart') then
                                                            local cf = CFrame.new(v)
                                                            local a = tween_s:Create(lp.Character.HumanoidRootPart,tweeninfo,{CFrame=cf})
                                                            a:Play()
                                                            a.Completed:Wait()
                                                            print('Teleporting Done!')
                                                        end
                                                    end

                                                    bypass_teleport(teleport_table.location2)

                                                    local Players = game:GetService("Players")

                                                    local LocalPlayer = Players.LocalPlayer

                                                    local Inventory = LocalPlayer.Inventory

                                                    _G.AutoFarm = t

                                                    while _G.AutoFarm do wait()
                                                        if Inventory:GetAttribute("Rock") >= 90 then
                                                            game.Workspace.Character[game.Players.LocalPlayer.Name].Humanoid.WalkSpeed = 0
                                                            wait(6.5)
                                                            game:GetService("Workspace"):FindFirstChild("Character"):FindFirstChild(game.Players.LocalPlayer.Name):FindFirstChild("HumanoidRootPart").CFrame = CFrame.new(2846.16187, 5.34974432, 2078.43701, -0.585431039, -0.0284520276, -0.810222805, -1.68365466e-09, 0.999383986, -0.0350946672, 0.810722172, -0.0205455068, -0.585070431)
                                                            wait(2.5)
                                                            local args = {
                                                                [1] = "fire",
                                                                [3] = "Economy",
                                                                [4] = FarmName,
                                                                [5] = Inventory:GetAttribute("Rock")
                                                            }

                                                            game:GetService("ReplicatedStorage"):WaitForChild("Modules"):WaitForChild("NetworkFramework"):WaitForChild("NetworkEvent"):FireServer(unpack(args))
                                                            wait(10)
                                                            bypass_teleport(teleport_table.location2)
                                                            game.Workspace.Character[game.Players.LocalPlayer.Name].Humanoid.WalkSpeed = 27
                                                        end
                                                    end
        elseif FarmName == "Pork" then
                                                                        local JU = game:GetService("Workspace"):FindFirstChild("JU")
                                                            if JU then
                                                                JU:Destroy()
                                                            end
                                                        local Noclip = Instance.new("Part", workspace)
                                                            Noclip.Name = "JU"
                                                            Noclip.CanCollide = true
                                                            Noclip.Anchored = true
                                                            Noclip.Transparency = 0.5
                                                            Noclip.Size = Vector3.new(30, 1, 30)
                                                            game:GetService("Workspace"):FindFirstChild("JU").CFrame = CFrame.new(2846.16187, 3.34974432, 2078.43701, -0.585431039, -0.0284520276, -0.810222805, -1.68365466e-09, 0.999383986, -0.0350946672, 0.810722172, -0.0205455068, -0.585070431)


                                                    local teleport_table = {
                                                        location1 = Vector3.new(2845.45142, 14.2436848, 2079.27222, -0.388715088, 1.28141585e-06, -0.921357989, -1.4877221e-06, 1, 2.01845091e-06, 0.921357989, 2.15532691e-06, -0.388715088),
                                                        location2 = Vector3.new(-594, 14, 2344)
                                                    }

                                                    local tween_s = game:GetService('TweenService')
                                                    local tweeninfo = TweenInfo.new(0,Enum.EasingStyle.Linear)

                                                    local lp = game.Players.LocalPlayer

                                                    function bypass_teleport(v)
                                                        if lp.Character and 
                                                        lp.Character:FindFirstChild('HumanoidRootPart') then
                                                            local cf = CFrame.new(v)
                                                            local a = tween_s:Create(lp.Character.HumanoidRootPart,tweeninfo,{CFrame=cf})
                                                            a:Play()
                                                            a.Completed:Wait()
                                                            print('Teleporting Done!')
                                                        end
                                                    end

                                                    bypass_teleport(teleport_table.location2)

                                                    local Players = game:GetService("Players")

                                                    local LocalPlayer = Players.LocalPlayer

                                                    local Inventory = LocalPlayer.Inventory

                                                    _G.AutoFarm = t

                                                    while _G.AutoFarm do wait()
                                                        if Inventory:GetAttribute("Pork") >= 50 then
                                                            for i, v in pairs(workspace:FindFirstChild("Farm"):FindFirstChild("Pork"):GetChildren()) do
                                                                if v.Name == "pig" then
                                                                    v.Parent = game:GetService("ReplicatedStorage")
                                                                end
                                                            end
                                                            game.Workspace.Character[game.Players.LocalPlayer.Name].Humanoid.WalkSpeed = 0
                                                            wait(6.5)
                                                            game:GetService("Workspace"):FindFirstChild("Character"):FindFirstChild(game.Players.LocalPlayer.Name):FindFirstChild("HumanoidRootPart").CFrame = CFrame.new(2846.16187, 5.34974432, 2078.43701, -0.585431039, -0.0284520276, -0.810222805, -1.68365466e-09, 0.999383986, -0.0350946672, 0.810722172, -0.0205455068, -0.585070431)
                                                            for i, v in pairs(game:GetService("ReplicatedStorage"):GetChildren()) do
                                                                if v.Name == "pig" then
                                                                    v.Parent = workspace:FindFirstChild("Farm"):FindFirstChild("Pork")
                                                                end
                                                            end
                                                            wait(2.5)
                                                            local args = {
                                                                [1] = "fire",
                                                                [3] = "Economy",
                                                                [4] = FarmName,
                                                                [5] = Inventory:GetAttribute("Pork")
                                                            }

                                                            game:GetService("ReplicatedStorage"):WaitForChild("Modules"):WaitForChild("NetworkFramework"):WaitForChild("NetworkEvent"):FireServer(unpack(args))
                                                            wait(10)
                                                            bypass_teleport(teleport_table.location2)
                                                            game.Workspace.Character[game.Players.LocalPlayer.Name].Humanoid.WalkSpeed = 27
                                                        end
                                                    end
        elseif FarmName == "Plant" then        
                                                                                    local JU = game:GetService("Workspace"):FindFirstChild("JU")
                                                            if JU then
                                                                JU:Destroy()
                                                            end
                                                        local Noclip = Instance.new("Part", workspace)
                                                            Noclip.Name = "JU"
                                                            Noclip.CanCollide = true
                                                            Noclip.Anchored = true
                                                            Noclip.Transparency = 0.5
                                                            Noclip.Size = Vector3.new(30, 1, 30)
                                                            game:GetService("Workspace"):FindFirstChild("JU").CFrame = CFrame.new(2846.16187, 3.34974432, 2078.43701, -0.585431039, -0.0284520276, -0.810222805, -1.68365466e-09, 0.999383986, -0.0350946672, 0.810722172, -0.0205455068, -0.585070431)

                                                    local teleport_table = {
                                                        location1 = Vector3.new(2845.45142, 14.2436848, 2079.27222, -0.388715088, 1.28141585e-06, -0.921357989, -1.4877221e-06, 1, 2.01845091e-06, 0.921357989, 2.15532691e-06, -0.388715088),
                                                        location2 = Vector3.new(2127, 14, -3308)
                                                    }

                                                    local tween_s = game:GetService('TweenService')
                                                    local tweeninfo = TweenInfo.new(0,Enum.EasingStyle.Linear)

                                                    local lp = game.Players.LocalPlayer

                                                    function bypass_teleport(v)
                                                        if lp.Character and 
                                                        lp.Character:FindFirstChild('HumanoidRootPart') then
                                                            local cf = CFrame.new(v)
                                                            local a = tween_s:Create(lp.Character.HumanoidRootPart,tweeninfo,{CFrame=cf})
                                                            a:Play()
                                                            a.Completed:Wait()
                                                            print('Teleporting Done!')
                                                        end
                                                    end

                                                    bypass_teleport(teleport_table.location2)

                                                        local Players = game:GetService("Players")

                                                        local LocalPlayer = Players.LocalPlayer

                                                        local Inventory = LocalPlayer.Inventory

                                                    _G.AutoFarm = t

                                                    while _G.AutoFarm do wait()
                                                        if Inventory:GetAttribute("Plant") >= 50 then       
                                                            game.Workspace.Character[game.Players.LocalPlayer.Name].Humanoid.WalkSpeed = 0
                                                            wait(6.5)
                                                            game:GetService("Workspace"):FindFirstChild("Character"):FindFirstChild(game.Players.LocalPlayer.Name):FindFirstChild("HumanoidRootPart").CFrame = CFrame.new(2846.16187, 5.34974432, 2078.43701, -0.585431039, -0.0284520276, -0.810222805, -1.68365466e-09, 0.999383986, -0.0350946672, 0.810722172, -0.0205455068, -0.585070431)
                                                            wait(2.5)
                                                            local args = {
                                                                [1] = "fire",
                                                                [3] = "Economy",
                                                                [4] = FarmName,
                                                                [5] = Inventory:GetAttribute("Plant")
                                                            }

                                                            game:GetService("ReplicatedStorage"):WaitForChild("Modules"):WaitForChild("NetworkFramework"):WaitForChild("NetworkEvent"):FireServer(unpack(args))
                                                            wait(10)
                                                            bypass_teleport(teleport_table.location2)
                                                            game.Workspace.Character[game.Players.LocalPlayer.Name].Humanoid.WalkSpeed = 27
                                                        end
                                                    end
        elseif FarmName == "Flower" then        
                                                                                                local JU = game:GetService("Workspace"):FindFirstChild("JU")
                                                            if JU then
                                                                JU:Destroy()
                                                            end
                                                        local Noclip = Instance.new("Part", workspace)
                                                            Noclip.Name = "JU"
                                                            Noclip.CanCollide = true
                                                            Noclip.Anchored = true
                                                            Noclip.Transparency = 0.5
                                                            Noclip.Size = Vector3.new(30, 1, 30)
                                                            game:GetService("Workspace"):FindFirstChild("JU").CFrame = CFrame.new(2846.16187, 3.34974432, 2078.43701, -0.585431039, -0.0284520276, -0.810222805, -1.68365466e-09, 0.999383986, -0.0350946672, 0.810722172, -0.0205455068, -0.585070431)

                                                    local teleport_table = {
                                                        location1 = Vector3.new(2845.45142, 14.2436848, 2079.27222, -0.388715088, 1.28141585e-06, -0.921357989, -1.4877221e-06, 1, 2.01845091e-06, 0.921357989, 2.15532691e-06, -0.388715088),
                                                        location2 = Vector3.new(3016, 14, -876)
                                                    }

                                                    local tween_s = game:GetService('TweenService')
                                                    local tweeninfo = TweenInfo.new(0,Enum.EasingStyle.Linear)

                                                    local lp = game.Players.LocalPlayer

                                                    function bypass_teleport(v)
                                                        if lp.Character and 
                                                        lp.Character:FindFirstChild('HumanoidRootPart') then
                                                            local cf = CFrame.new(v)
                                                            local a = tween_s:Create(lp.Character.HumanoidRootPart,tweeninfo,{CFrame=cf})
                                                            a:Play()
                                                            a.Completed:Wait()
                                                            print('Teleporting Done!')
                                                        end
                                                    end

                                                    bypass_teleport(teleport_table.location2)

                                                    local Players = game:GetService("Players")

                                                    local LocalPlayer = Players.LocalPlayer

                                                    local Inventory = LocalPlayer.Inventory

                                                    _G.AutoFarm = t

                                                    while _G.AutoFarm do wait()
                                                        if Inventory:GetAttribute("Flower") >= 290 then
                                                            game.Workspace.Character[game.Players.LocalPlayer.Name].Humanoid.WalkSpeed = 0
                                                            wait(6.5)
                                                            game:GetService("Workspace"):FindFirstChild("Character"):FindFirstChild(game.Players.LocalPlayer.Name):FindFirstChild("HumanoidRootPart").CFrame = CFrame.new(2846.16187, 5.34974432, 2078.43701, -0.585431039, -0.0284520276, -0.810222805, -1.68365466e-09, 0.999383986, -0.0350946672, 0.810722172, -0.0205455068, -0.585070431)
                                                            wait(2.5)
                                                            local args = {
                                                                [1] = "fire",
                                                                [3] = "Economy",
                                                                [4] = FarmName,
                                                                [5] = Inventory:GetAttribute("Flower")
                                                            }

                                                            game:GetService("ReplicatedStorage"):WaitForChild("Modules"):WaitForChild("NetworkFramework"):WaitForChild("NetworkEvent"):FireServer(unpack(args))
                                                            wait(10)
                                                            bypass_teleport(teleport_table.location2)
                                                            game.Workspace.Character[game.Players.LocalPlayer.Name].Humanoid.WalkSpeed = 27
                                                        end
                                                    end
        elseif FarmName == "Corn" then        
                                                                                                            local JU = game:GetService("Workspace"):FindFirstChild("JU")
                                                            if JU then
                                                                JU:Destroy()
                                                            end
                                                        local Noclip = Instance.new("Part", workspace)
                                                            Noclip.Name = "JU"
                                                            Noclip.CanCollide = true
                                                            Noclip.Anchored = true
                                                            Noclip.Transparency = 0.5
                                                            Noclip.Size = Vector3.new(30, 1, 30)
                                                            game:GetService("Workspace"):FindFirstChild("JU").CFrame = CFrame.new(2846.16187, 3.34974432, 2078.43701, -0.585431039, -0.0284520276, -0.810222805, -1.68365466e-09, 0.999383986, -0.0350946672, 0.810722172, -0.0205455068, -0.585070431)

                                                    local teleport_table = {
                                                        location1 = Vector3.new(2845.45142, 14.2436848, 2079.27222, -0.388715088, 1.28141585e-06, -0.921357989, -1.4877221e-06, 1, 2.01845091e-06, 0.921357989, 2.15532691e-06, -0.388715088),
                                                        location2 = Vector3.new(-205, 49, 533)
                                                    }

                                                    local tween_s = game:GetService('TweenService')
                                                    local tweeninfo = TweenInfo.new(0,Enum.EasingStyle.Linear)

                                                    local lp = game.Players.LocalPlayer

                                                    function bypass_teleport(v)
                                                        if lp.Character and 
                                                        lp.Character:FindFirstChild('HumanoidRootPart') then
                                                            local cf = CFrame.new(v)
                                                            local a = tween_s:Create(lp.Character.HumanoidRootPart,tweeninfo,{CFrame=cf})
                                                            a:Play()
                                                            a.Completed:Wait()
                                                            print('Teleporting Done!')
                                                        end
                                                    end

                                                    bypass_teleport(teleport_table.location2)

                                                    local Players = game:GetService("Players")

                                                    local LocalPlayer = Players.LocalPlayer

                                                    local Inventory = LocalPlayer.Inventory

                                                    _G.AutoFarm = t

                                                    while _G.AutoFarm do wait()
                                                        if Inventory:GetAttribute("Corn") >= 50 then
                                                            game.Workspace.Character[game.Players.LocalPlayer.Name].Humanoid.WalkSpeed = 0
                                                            wait(6.5)
                                                            game:GetService("Workspace"):FindFirstChild("Character"):FindFirstChild(game.Players.LocalPlayer.Name):FindFirstChild("HumanoidRootPart").CFrame = CFrame.new(2846.16187, 5.34974432, 2078.43701, -0.585431039, -0.0284520276, -0.810222805, -1.68365466e-09, 0.999383986, -0.0350946672, 0.810722172, -0.0205455068, -0.585070431)
                                                            wait(2.5)
                                                            local args = {
                                                                [1] = "fire",
                                                                [3] = "Economy",
                                                                [4] = FarmName,
                                                                [5] = Inventory:GetAttribute("Corn")
                                                            }

                                                            game:GetService("ReplicatedStorage"):WaitForChild("Modules"):WaitForChild("NetworkFramework"):WaitForChild("NetworkEvent"):FireServer(unpack(args))
                                                            wait(10)
                                                            bypass_teleport(teleport_table.location2)
                                                            game.Workspace.Character[game.Players.LocalPlayer.Name].Humanoid.WalkSpeed = 27
                                                        end
                                                    end
        elseif FarmName == "Banana" then        
                                                                                                            local JU = game:GetService("Workspace"):FindFirstChild("JU")
                                                            if JU then
                                                                JU:Destroy()
                                                            end
                                                        local Noclip = Instance.new("Part", workspace)
                                                            Noclip.Name = "JU"
                                                            Noclip.CanCollide = true
                                                            Noclip.Anchored = true
                                                            Noclip.Transparency = 0.5
                                                            Noclip.Size = Vector3.new(30, 1, 30)
                                                            game:GetService("Workspace"):FindFirstChild("JU").CFrame = CFrame.new(2846.16187, 3.34974432, 2078.43701, -0.585431039, -0.0284520276, -0.810222805, -1.68365466e-09, 0.999383986, -0.0350946672, 0.810722172, -0.0205455068, -0.585070431)

                                                    local teleport_table = {
                                                        location1 = Vector3.new(2845.45142, 14.2436848, 2079.27222, -0.388715088, 1.28141585e-06, -0.921357989, -1.4877221e-06, 1, 2.01845091e-06, 0.921357989, 2.15532691e-06, -0.388715088),
                                                        location2 = Vector3.new(72, 14, -358)
                                                    }

                                                    local tween_s = game:GetService('TweenService')
                                                    local tweeninfo = TweenInfo.new(0,Enum.EasingStyle.Linear)

                                                    local lp = game.Players.LocalPlayer

                                                    function bypass_teleport(v)
                                                        if lp.Character and 
                                                        lp.Character:FindFirstChild('HumanoidRootPart') then
                                                            local cf = CFrame.new(v)
                                                            local a = tween_s:Create(lp.Character.HumanoidRootPart,tweeninfo,{CFrame=cf})
                                                            a:Play()
                                                            a.Completed:Wait()
                                                            print('Teleporting Done!')
                                                        end
                                                    end

                                                    bypass_teleport(teleport_table.location2)

                                                    local Players = game:GetService("Players")

                                                    local LocalPlayer = Players.LocalPlayer

                                                    local Inventory = LocalPlayer.Inventory

                                                    _G.AutoFarm = t

                                                    while _G.AutoFarm do wait()
                                                        if Inventory:GetAttribute("Banana") >= 50 then
                                                            game.Workspace.Character[game.Players.LocalPlayer.Name].Humanoid.WalkSpeed = 0
                                                            wait(6.5)
                                                            game:GetService("Workspace"):FindFirstChild("Character"):FindFirstChild(game.Players.LocalPlayer.Name):FindFirstChild("HumanoidRootPart").CFrame = CFrame.new(2846.16187, 5.34974432, 2078.43701, -0.585431039, -0.0284520276, -0.810222805, -1.68365466e-09, 0.999383986, -0.0350946672, 0.810722172, -0.0205455068, -0.585070431)
                                                            wait(2.5)
                                                            local args = {
                                                                [1] = "fire",
                                                                [3] = "Economy",
                                                                [4] = FarmName,
                                                                [5] = Inventory:GetAttribute("Banana")
                                                            }

                                                            game:GetService("ReplicatedStorage"):WaitForChild("Modules"):WaitForChild("NetworkFramework"):WaitForChild("NetworkEvent"):FireServer(unpack(args))
                                                            wait(10)
                                                            bypass_teleport(teleport_table.location2)
                                                            game.Workspace.Character[game.Players.LocalPlayer.Name].Humanoid.WalkSpeed = 27
                                                        end
                                                    end
            end
	end    
})

ItemTable = {}
for i,v in pairs(game.Players.LocalPlayer.Inventory:GetAttributes()) do
    table.insert(ItemTable,i) 
end

local Item = nil

Tab7:AddDropdown({
	Name = "Dropdown",
	Default = nil,
	Options = ItemTable,
	Callback = function(Value)
		Item = tostring(Value)
	end    
})

Tab7:AddTextbox({
	Name = "Fake Item",
	Default = nil,
	TextDisappear = true,
	Callback = function(txt)
		game.Players.LocalPlayer.Inventory:SetAttribute(Item, txt)
	end	  
})

Tab7:AddTextbox({
	Name = "Fake Item All",
	Default = nil,
	TextDisappear = true,
	Callback = function(txt)
        for attributeName, value in pairs(game.Players.LocalPlayer.Inventory:GetAttributes()) do
            game.Players.LocalPlayer.Inventory:SetAttribute(attributeName, txt)
        end        
	end	  
})

game:GetService("RunService").RenderStepped:Connect(function()
	for i, v in pairs(game.Workspace.PlayerVehicle:GetChildren()) do
		if v:IsA("Model") then  
			v:SetAttribute("Health", 100)
		end
	end
	for i, v in pairs(game.Workspace.PlayerVehicle:GetChildren()) do
		if v:IsA("Model") then  
			v:SetAttribute("Fuel", 100)
		end
	end
end)
