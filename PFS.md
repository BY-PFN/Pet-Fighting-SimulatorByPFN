repeat wait() until game:IsLoaded()
wait(5)
local vu = game:GetService("VirtualUser")
game:GetService("Players").LocalPlayer.Idled:connect(function()
   vu:Button2Down(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
   wait(1)
   vu:Button2Up(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
end)


if game.PlaceId  == 10142749739 then --

    local DiscordLib = loadstring(game:HttpGet("https://pastebin.com/raw/xcdmdnw0"))()
    local win = DiscordLib:Window(" [Beta] Pet Fighting Simulator [UPDATE 1]")
    
    local serv = win:Server("P_NonShop By PFN", "")
    local tgls = serv:Channel("AutoFarm")
    local drops = serv:Channel("Player TP!")
    local MOD = serv:Channel("MOD!")
    

--Auto--

_G.weapon = false
    tgls:Toggle("Auto potion",false, function(bool)
        _G.weapon = bool
    end)
    
    spawn(function()
        while wait(1) do
          if _G.weapon then
            pcall(function() 
                
    
   local args = {
    [1] = "potion",
    [2] = "CubBag1"
}

game:GetService("ReplicatedStorage").Remotes.DataChange_Item:FireServer(unpack(args))

    
    
                wait(1)
            end)
          end
        end
    end)


tgls:Button("TP word1 ", function()

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1747.6343994140625, 8.107684135437012, 1709.166259765625)    
      
end)

_G.word1C10 = false
    tgls:Toggle("Auto Muyaa C10",false, function(bool)
        _G.word1C10 = bool
    end)
    
    spawn(function()
        while wait(1) do
          if _G.word1C10 then
            pcall(function() 
                
    
    local args = {
        [1] = workspace.ForScript.Battle.C10
    }
    
    game:GetService("ReplicatedStorage").Remotes.BattleClickEvent:FireServer(unpack(args))
    
    
                wait(2)
            end)
          end
        end
    end)
-------
_G.word1C11 = false
    tgls:Toggle("Auto Fluoyaf C11",false, function(bool)
        _G.word1C11 = bool
    end)
    
    spawn(function()
        while wait(1) do
          if _G.word1C11 then
            pcall(function() 
                
    
    local args = {
        [1] = workspace.ForScript.Battle.C11
    }
    
    game:GetService("ReplicatedStorage").Remotes.BattleClickEvent:FireServer(unpack(args))
    
    
                wait(2)
            end)
          end
        end
    end)
-------
_G.word1C13 = false
    tgls:Toggle("Auto Budodo C13",false, function(bool)
        _G.word1C13 = bool
    end)
    
    spawn(function()
        while wait(1) do
          if _G.word1C13 then
            pcall(function() 
                
    
    local args = {
        [1] = workspace.ForScript.Battle.C13
    }
    
    game:GetService("ReplicatedStorage").Remotes.BattleClickEvent:FireServer(unpack(args))
    
    
                wait(2)
            end)
          end
        end
    end)
-------    
_G.word1C14 = false
    tgls:Toggle("Auto Burolla C14",false, function(bool)
        _G.word1C14 = bool
    end)
    
    spawn(function()
        while wait(1) do
          if _G.word1C14 then
            pcall(function() 
                
    
    local args = {
        [1] = workspace.ForScript.Battle.C14
    }
    
    game:GetService("ReplicatedStorage").Remotes.BattleClickEvent:FireServer(unpack(args))
    
    
                wait(2)
            end)
          end
        end
    end)
-------    
_G.word1C16 = false
    tgls:Toggle("Auto Sheesom C16",false, function(bool)
        _G.word1C16 = bool
    end)
    
    spawn(function()
        while wait(1) do
          if _G.word1C16 then
            pcall(function() 
                
    
    local args = {
        [1] = workspace.ForScript.Battle.C16
    }
    
    game:GetService("ReplicatedStorage").Remotes.BattleClickEvent:FireServer(unpack(args))
    
    
                wait(2)
            end)
          end
        end
    end)
-------     
_G.word1C17 = false
    tgls:Toggle("Auto Sheesom C17",false, function(bool)
        _G.word1C17 = bool
    end)
    
    spawn(function()
        while wait(1) do
          if _G.word1C17 then
            pcall(function() 
                
    
    local args = {
        [1] = workspace.ForScript.Battle.C17
    }
    
    game:GetService("ReplicatedStorage").Remotes.BattleClickEvent:FireServer(unpack(args))
    
    
                wait(2)
            end)
          end
        end
    end)
-------      
tgls:Button("TP word2 ", function()

  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1622.3367919921875, 8.277461051940918, 3216.16748046875)    
        
end)

     
_G.word2C19 = false
    tgls:Toggle("Auto Crababy C19",false, function(bool)
        _G.word2C19 = bool
    end)
    
    spawn(function()
        while wait(1) do
          if _G.word2C19 then
            pcall(function() 
                
    
    local args = {
        [1] = workspace.ForScript.Battle.C19
    }
    
    game:GetService("ReplicatedStorage").Remotes.BattleClickEvent:FireServer(unpack(args))
    
    
                wait(2)
            end)
          end
        end
    end)
-------      
_G.word2C20 = false
    tgls:Toggle("Auto Hydrcrab C20",false, function(bool)
        _G.word2C20 = bool
    end)
    
    spawn(function()
        while wait(1) do
          if _G.word2C20 then
            pcall(function() 
                
    
    local args = {
        [1] = workspace.ForScript.Battle.C20
    }
    
    game:GetService("ReplicatedStorage").Remotes.BattleClickEvent:FireServer(unpack(args))
    
    
                wait(2)
            end)
          end
        end
    end)
------- 

_G.word2C22 = false
    tgls:Toggle("Auto Beshell C22",false, function(bool)
        _G.word2C22 = bool
    end)
    
    spawn(function()
        while wait(1) do
          if _G.word2C22 then
            pcall(function() 
                
    
    local args = {
        [1] = workspace.ForScript.Battle.C22
    }
    
    game:GetService("ReplicatedStorage").Remotes.BattleClickEvent:FireServer(unpack(args))
    
    
                wait(2)
            end)
          end
        end
    end)
-------      


_G.word2C23 = false
    tgls:Toggle("Auto Mermashell C23",false, function(bool)
        _G.word2C23 = bool
    end)
    
    spawn(function()
        while wait(1) do
          if _G.word2C23 then
            pcall(function() 
                
    
    local args = {
        [1] = workspace.ForScript.Battle.C23
    }
    
    game:GetService("ReplicatedStorage").Remotes.BattleClickEvent:FireServer(unpack(args))
    
    
                wait(2)
            end)
          end
        end
    end)
-------      

_G.word2C25 = false
    tgls:Toggle("Auto Nymny C25",false, function(bool)
        _G.word2C25 = bool
    end)
    
    spawn(function()
        while wait(1) do
          if _G.word2C25 then
            pcall(function() 
                
    
    local args = {
        [1] = workspace.ForScript.Battle.C25
    }
    
    game:GetService("ReplicatedStorage").Remotes.BattleClickEvent:FireServer(unpack(args))
    
    
                wait(2)
            end)
          end
        end
    end)
-------     

_G.word2C26 = false
    tgls:Toggle("Auto Wavnym C26",false, function(bool)
        _G.word2C26 = bool
    end)
    
    spawn(function()
        while wait(1) do
          if _G.word2C26 then
            pcall(function() 
                
    
    local args = {
        [1] = workspace.ForScript.Battle.C26
    }
    
    game:GetService("ReplicatedStorage").Remotes.BattleClickEvent:FireServer(unpack(args))
    
    
                wait(2)
            end)
          end
        end
    end)
-------   

tgls:Button("TP word3 ", function()

  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1816.560546875, 8.105761528015137, 4125.326171875)    
        
end)

tgls:Button("TP word4 ", function()

  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1928.29833984375, 8.100523948669434, 5632.1455078125)    
          
end)

tgls:Button("TP word5 ", function()

  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1878.93115234375, 8.100523948669434, 6716.162109375)    
            
end)

_G.word5C44 = false
    tgls:Toggle("Auto Ledilv C44",false, function(bool)
        _G.word5C44 = bool
    end)
    
    spawn(function()
        while wait(1) do
          if _G.word5C44 then
            pcall(function() 
                
    
    local args = {
        [1] = workspace.ForScript.Battle.C44
    }
    
    game:GetService("ReplicatedStorage").Remotes.BattleClickEvent:FireServer(unpack(args))
    
    
                wait(2)
            end)
          end
        end
    end)
-------  
_G.word5C45 = false
    tgls:Toggle("Auto Ledystar C45",false, function(bool)
        _G.word5C44 = bool
    end)
    
    spawn(function()
        while wait(1) do
          if _G.word5C45 then
            pcall(function() 
                
    
    local args = {
        [1] = workspace.ForScript.Battle.C45
    }
    
    game:GetService("ReplicatedStorage").Remotes.BattleClickEvent:FireServer(unpack(args))
    
    
                wait(2)
            end)
          end
        end
    end)
-------  
_G.word5C47 = false
    tgls:Toggle("Auto Guguga C47",false, function(bool)
        _G.word5C47 = bool
    end)
    
    spawn(function()
        while wait(1) do
          if _G.word5C47 then
            pcall(function() 
                
    
    local args = {
        [1] = workspace.ForScript.Battle.C47
    }
    
    game:GetService("ReplicatedStorage").Remotes.BattleClickEvent:FireServer(unpack(args))
    
    
                wait(2)
            end)
          end
        end
    end)
-------  
_G.word5C48 = false
    tgls:Toggle("Auto Guplora C48",false, function(bool)
        _G.word5C48 = bool
    end)
    
    spawn(function()
        while wait(1) do
          if _G.word5C48 then
            pcall(function() 
                
    
    local args = {
        [1] = workspace.ForScript.Battle.C48
    }
    
    game:GetService("ReplicatedStorage").Remotes.BattleClickEvent:FireServer(unpack(args))
    
    
                wait(2)
            end)
          end
        end
    end)
------- 
_G.word5C50 = false
    tgls:Toggle("Auto Ubaoo C50",false, function(bool)
        _G.word5C50 = bool
    end)
    
    spawn(function()
        while wait(1) do
          if _G.word5C50 then
            pcall(function() 
                
    
    local args = {
        [1] = workspace.ForScript.Battle.C50
    }
    
    game:GetService("ReplicatedStorage").Remotes.BattleClickEvent:FireServer(unpack(args))
    
    
                wait(2)
            end)
          end
        end
    end)
-------  
tgls:Button("TP word6 ", function()

  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-3207.1787109375, 8.100528717041016, 8328.5205078125)    

end)
_G.word6C52 = false
    tgls:Toggle("Auto Golin C52",false, function(bool)
        _G.word6C52 = bool
    end)
    
    spawn(function()
        while wait(1) do
          if _G.word6C52 then
            pcall(function() 
                
    
    local args = {
        [1] = workspace.ForScript.Battle.C52
    }
    
    game:GetService("ReplicatedStorage").Remotes.BattleClickEvent:FireServer(unpack(args))
    
    
                wait(2)
            end)
          end
        end
    end)
-------
_G.word6C53 = false
    tgls:Toggle("Auto Golihard C53",false, function(bool)
        _G.word6C53 = bool
    end)
    
    spawn(function()
        while wait(1) do
          if _G.word6C53 then
            pcall(function() 
                
    
    local args = {
        [1] = workspace.ForScript.Battle.C53
    }
    
    game:GetService("ReplicatedStorage").Remotes.BattleClickEvent:FireServer(unpack(args))
    
    
                wait(2)
            end)
          end
        end
    end)
-------
_G.word6C55 = false
    tgls:Toggle("Auto Grard C55",false, function(bool)
        _G.word6C55 = bool
    end)
    
    spawn(function()
        while wait(1) do
          if _G.word6C55 then
            pcall(function() 
                
    
    local args = {
        [1] = workspace.ForScript.Battle.C55
    }
    
    game:GetService("ReplicatedStorage").Remotes.BattleClickEvent:FireServer(unpack(args))
    
    
                wait(2)
            end)
          end
        end
    end)
-------
_G.word6C57 = false
    tgls:Toggle("Auto Reeoat C57",false, function(bool)
        _G.word6C57 = bool
    end)
    
    spawn(function()
        while wait(1) do
          if _G.word6C57 then
            pcall(function() 
                
    
    local args = {
        [1] = workspace.ForScript.Battle.C57
    }
    
    game:GetService("ReplicatedStorage").Remotes.BattleClickEvent:FireServer(unpack(args))
    
    
                wait(2)
            end)
          end
        end
    end)
-------  

tgls:Button("TP word7 ", function()

  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-3148.891845703125, 8.177334785461426, 9619.1474609375)    

end)

_G.word7C59 = false
tgls:Toggle("Auto Qiqi C59",false, function(bool)
    _G.word7C59 = bool
end)

spawn(function()
    while wait(1) do
      if _G.word7C59 then
        pcall(function() 
            

local args = {
    [1] = workspace.ForScript.Battle.C59
}

game:GetService("ReplicatedStorage").Remotes.BattleClickEvent:FireServer(unpack(args))


            wait(2)
        end)
      end
    end
end)
-------  

_G.word7C61 = false
tgls:Toggle("Auto Biliopard C61",false, function(bool)
    _G.word7C61 = bool
end)

spawn(function()
    while wait(1) do
      if _G.word7C61 then
        pcall(function() 
            

local args = {
    [1] = workspace.ForScript.Battle.C61
}

game:GetService("ReplicatedStorage").Remotes.BattleClickEvent:FireServer(unpack(args))


            wait(2)
        end)
      end
    end
end)
-------  

_G.word7C64 = false
tgls:Toggle("Auto Elbbit C64",false, function(bool)
    _G.word7C64 = bool
end)

spawn(function()
    while wait(1) do
      if _G.word7C64 then
        pcall(function() 
            

local args = {
    [1] = workspace.ForScript.Battle.C64
}

game:GetService("ReplicatedStorage").Remotes.BattleClickEvent:FireServer(unpack(args))


            wait(2)
        end)
      end
    end
end)
-------  

_G.word7C65 = false
tgls:Toggle("Auto Eleep C65",false, function(bool)
    _G.word7C65 = bool
end)

spawn(function()
    while wait(1) do
      if _G.word7C65 then
        pcall(function() 
            

local args = {
    [1] = workspace.ForScript.Battle.C65
}

game:GetService("ReplicatedStorage").Remotes.BattleClickEvent:FireServer(unpack(args))


            wait(2)
        end)
      end
    end
end)
-------  

tgls:Button("TP word8 ", function()

  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-3205.944580078125, 8.10053539276123, 11018.2880859375)    

end)

_G.word8C67 = false
tgls:Toggle("Auto Hamimon C67",false, function(bool)
    _G.word8C67 = bool
end)

spawn(function()
    while wait(1) do
      if _G.word8C67 then
        pcall(function() 
            

local args = {
    [1] = workspace.ForScript.Battle.C67
}

game:GetService("ReplicatedStorage").Remotes.BattleClickEvent:FireServer(unpack(args))


            wait(2)
        end)
      end
    end
end)
-------  

_G.word8C68 = false
tgls:Toggle("Auto Hammard C68",false, function(bool)
    _G.word8C68 = bool
end)

spawn(function()
    while wait(1) do
      if _G.word8C68 then
        pcall(function() 
            

local args = {
    [1] = workspace.ForScript.Battle.C68
}

game:GetService("ReplicatedStorage").Remotes.BattleClickEvent:FireServer(unpack(args))


            wait(2)
        end)
      end
    end
end)
-------  

_G.word8C70 = false
tgls:Toggle("Auto Ssis Q C70",false, function(bool)
    _G.word8C70 = bool
end)

spawn(function()
    while wait(1) do
      if _G.word8C70 then
        pcall(function() 
            

local args = {
    [1] = workspace.ForScript.Battle.C70
}

game:GetService("ReplicatedStorage").Remotes.BattleClickEvent:FireServer(unpack(args))


            wait(2)
        end)
      end
    end
end)
-------  

_G.word8C72 = false
tgls:Toggle("Auto Toyon C72",false, function(bool)
    _G.word8C72 = bool
end)

spawn(function()
    while wait(1) do
      if _G.word8C72 then
        pcall(function() 
            

local args = {
    [1] = workspace.ForScript.Battle.C72
}

game:GetService("ReplicatedStorage").Remotes.BattleClickEvent:FireServer(unpack(args))


            wait(2)
        end)
      end
    end
end)
-------  

_G.word8C73 = false
tgls:Toggle("Auto Toybrigon C73",false, function(bool)
    _G.word8C73 = bool
end)

spawn(function()
    while wait(1) do
      if _G.word8C73 then
        pcall(function() 
            

local args = {
    [1] = workspace.ForScript.Battle.C73
}

game:GetService("ReplicatedStorage").Remotes.BattleClickEvent:FireServer(unpack(args))


            wait(2)
        end)
      end
    end
end)
-------  
tgls:Button("TP word9 ", function()

  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-3160.49365234375, 8.100536346435547, 12381.62109375)    

end)

_G.word9C75 = false
tgls:Toggle("Auto Abai C75",false, function(bool)
    _G.word9C75 = bool
end)

spawn(function()
    while wait(1) do
      if _G.word9C75 then
        pcall(function() 
            

local args = {
    [1] = workspace.ForScript.Battle.C75
}

game:GetService("ReplicatedStorage").Remotes.BattleClickEvent:FireServer(unpack(args))


            wait(2)
        end)
      end
    end
end)
-------  

_G.word9C76 = false
tgls:Toggle("Auto Bibbai C76",false, function(bool)
    _G.word9C76 = bool
end)

spawn(function()
    while wait(1) do
      if _G.word9C76 then
        pcall(function() 
            

local args = {
    [1] = workspace.ForScript.Battle.C76
}

game:GetService("ReplicatedStorage").Remotes.BattleClickEvent:FireServer(unpack(args))


            wait(2)
        end)
      end
    end
end)
-------  

_G.word9C78 = false
tgls:Toggle("Auto Moonigher C78",false, function(bool)
    _G.word9C78 = bool
end)

spawn(function()
    while wait(1) do
      if _G.word9C78 then
        pcall(function() 
            

local args = {
    [1] = workspace.ForScript.Battle.C78
}

game:GetService("ReplicatedStorage").Remotes.BattleClickEvent:FireServer(unpack(args))


            wait(2)
        end)
      end
    end
end)
-------  

_G.word9C80 = false
tgls:Toggle("Auto Bluorner C80",false, function(bool)
    _G.word9C80 = bool
end)

spawn(function()
    while wait(1) do
      if _G.word9C80 then
        pcall(function() 
            

local args = {
    [1] = workspace.ForScript.Battle.C80
}

game:GetService("ReplicatedStorage").Remotes.BattleClickEvent:FireServer(unpack(args))


            wait(2)
        end)
      end
    end
end)
-------  


tgls:Button("TP word10 ", function()

  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-3203.89990234375, 8.10055160522461, 13676.7392578125)    

end)

-------------------------------------------------------------------------------------------------------------------
_G.word10Spray = false
tgls:Toggle("BossGo Jitsu",false, function(bool)
  _G.word10Spray = bool
end)
spawn(function()
  while wait(10) do
    if _G.word10Spray then
      pcall(function() 
          

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-3268.384521484375, 7.90869665145874, 13688.25390625)
if (CFrame.new(-3268.384521484375, 7.90869665145874, 13688.25390625).Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position) >= 5 then
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-3268.384521484375, 7.90869665145874, 13688.25390625)
end


          wait(10)
          
          
      end)
    end
  end
end)
-------------------------------------------------------------------------------------------------------------------

_G.word10C82 = false
tgls:Toggle("Auto Wichhy C82",false, function(bool)
    _G.word10C82 = bool
end)

spawn(function()
    while wait(1) do
      if _G.word10C82 then
        pcall(function() 
            

local args = {
    [1] = workspace.ForScript.Battle.C82
}

game:GetService("ReplicatedStorage").Remotes.BattleClickEvent:FireServer(unpack(args))


            wait(2)
        end)
      end
    end
end)
-------  
_G.word10C83 = false
tgls:Toggle("Auto Wichdevily C83",false, function(bool)
    _G.word10C83 = bool
end)

spawn(function()
    while wait(1) do
      if _G.word10C83 then
        pcall(function() 
            

local args = {
    [1] = workspace.ForScript.Battle.C83
}

game:GetService("ReplicatedStorage").Remotes.BattleClickEvent:FireServer(unpack(args))


            wait(2)
        end)
      end
    end
end)
-------  
             

_G.word10C85 = false
tgls:Toggle("Auto Foleye C85",false, function(bool)
    _G.word10C85 = bool
end)

spawn(function()
    while wait(1) do
      if _G.word10C85 then
        pcall(function() 
            

local args = {
    [1] = workspace.ForScript.Battle.C85
}

game:GetService("ReplicatedStorage").Remotes.BattleClickEvent:FireServer(unpack(args))


            wait(2)
        end)
      end
    end
end)
-------  
       
_G.word10C87 = false
tgls:Toggle("Auto Minson C87",false, function(bool)
    _G.word10C87 = bool
end)

spawn(function()
    while wait(1) do
      if _G.word10C87 then
        pcall(function() 
            

local args = {
    [1] = workspace.ForScript.Battle.C87
}

game:GetService("ReplicatedStorage").Remotes.BattleClickEvent:FireServer(unpack(args))


            wait(2)
        end)
      end
    end
end)
-------  

_G.word10C88 = false
tgls:Toggle("Auto Minonator C88",false, function(bool)
    _G.word10C88 = bool
end)

spawn(function()
    while wait(1) do
      if _G.word10C88 then
        pcall(function() 
            

local args = {
    [1] = workspace.ForScript.Battle.C88
}

game:GetService("ReplicatedStorage").Remotes.BattleClickEvent:FireServer(unpack(args))


            wait(2)
        end)
      end
    end
end)
-------  
----------------------------------------------------------------------

----Player TP!----
Plr = {}
for i,v in pairs(game:GetService("Players"):GetChildren()) do
    table.insert(Plr,v.Name) 
end

local drop = drops:Dropdown("Select Player!", Plr, function(t)
   PlayerTP = t

end)


drops:Button("Click To TP", function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[PlayerTP].Character.HumanoidRootPart.CFrame 
end)


  drops:Toggle("Auto Tp", false, function(t)
_G.TPPlayer = t
while _G.TPPlayer do wait()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[PlayerTP].Character.HumanoidRootPart.CFrame
end
end)

drops:Button("Refresh Dropdown", function()
  drop:Refresh(Plr)
end)  


----------------------------------------------------------------------
----AFK----

_G.AFK = true
    MOD:Toggle("AFK",true, function(bool)
        _G.AKF = bool
    end)

spawn(function()
    while wait() do
        if _G.AKF then
        pcall(function() 
            local VirtualUser = game:GetService("VirtualUser")
            VirtualUser:CaptureController()
            VirtualUser:SetKeyDown("W",key)
            wait()
            VirtualUser:CaptureController()
            VirtualUser:SetKeyUp("W",key)
            wait(1900)
        end)
    end
end
end)

----AFKSpacebar----

_G.AFK = true
    MOD:Toggle("AFK",true, function(bool)
        _G.AKF = bool
    end)


          spawn(function()
            while wait() do
                pcall(function() 
                  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,5.3,0)
                  wait(300)
                end)
            end
        end)
        end)
    end
end
end)


-----MOD-----
_G.VIP = false
    MOD:Toggle("VIP ONLY",false, function(bool)
        _G.VIP = bool
    end)
    
    spawn(function()
        while wait(1) do
          if _G.VIP then
            pcall(function() 
                
    
 game:GetService("Workspace").ForScript.Touch.VipWall:Destroy()

    
    
                wait(1)
            end)
          end
        end
    end)



----------------------------------------------------------------------
 end
