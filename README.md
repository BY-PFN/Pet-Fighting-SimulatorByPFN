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

tgls:Button("TP word8 ", function()

  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-3205.944580078125, 8.10053539276123, 11018.2880859375)    

end)

tgls:Button("TP word9 ", function()

  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-3160.49365234375, 8.100536346435547, 12381.62109375)    

end)

tgls:Button("TP word10 ", function()

  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-3203.89990234375, 8.10055160522461, 13676.7392578125)    

end)

 _G.word6C55 = false
    tgls:Toggle("Auto โกโลฮาร์ด",false, function(bool)
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
    
    
                wait(5)
            end)
          end
        end
    end)
 


 _G.weapon1 = false
    tgls:Toggle("Auto กุปโลร่า",false, function(bool)
        _G.weapon1 = bool
    end)
    
    spawn(function()
        while wait(1) do
          if _G.weapon1 then
            pcall(function() 
                
    
    local args = {
        [1] = workspace.ForScript.Battle.C57
    }
    
    game:GetService("ReplicatedStorage").Remotes.BattleClickEvent:FireServer(unpack(args))
    
    
                wait(5)
            end)
          end
        end
    end)
 
 _G.weapon2 = false
    tgls:Toggle("Auto เอลบิท",false, function(bool)
        _G.weapon2 = bool
    end)
    
    spawn(function()
        while wait(1) do
          if _G.weapon2 then
            pcall(function() 
                
    
    local args = {
        [1] = workspace.ForScript.Battle.C64
    }
    
    game:GetService("ReplicatedStorage").Remotes.BattleClickEvent:FireServer(unpack(args))
    
    
                wait(5)
            end)
          end
        end
    end)
    

 _G.weapon3 = false
    tgls:Toggle("Auto อีเลฟ",false, function(bool)
        _G.weapon3 = bool
    end)
    
    spawn(function()
        while wait(1) do
          if _G.weapon3 then
            pcall(function() 
                
    
    local args = {
        [1] = workspace.ForScript.Battle.C65
    }
    
    game:GetService("ReplicatedStorage").Remotes.BattleClickEvent:FireServer(unpack(args))
    
    
                wait(5)
            end)
          end
        end
    end)
    
  _G.weapon4 = false
    tgls:Toggle("Auto อีเลฟ",false, function(bool)
        _G.weapon4 = bool
    end)
    
    spawn(function()
        while wait(1) do
          if _G.weapon4 then
            pcall(function() 
                
    
    local args = {
        [1] = workspace.ForScript.Battle.C72
    }
    
    game:GetService("ReplicatedStorage").Remotes.BattleClickEvent:FireServer(unpack(args))
    
    
                wait(5)
            end)
          end
        end
    end)
    
       

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
            VirtualUser:SetKeyDown("w",key)
            wait()
            VirtualUser:CaptureController()
            VirtualUser:SetKeyUp("w",key)
            wait(1900)
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
