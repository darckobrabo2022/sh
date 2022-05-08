local library = loadstring(game:HttpGet("https://raw.githubusercontent.com/GreenDeno/Venyx-UI-Library/main/source.lua"))()
local venyx = library.new("Thiago UI", 5013109572)

-- themes
local themes = {
Background = Color3.fromRGB(24, 24, 24),
Glow = Color3.fromRGB(0, 0, 0),
Accent = Color3.fromRGB(10, 10, 10),
LightContrast = Color3.fromRGB(20, 20, 20),
DarkContrast = Color3.fromRGB(14, 14, 14),  
TextColor = Color3.fromRGB(255, 255, 255)
}
local page = venyx:addPage("Nfts", 5012544693)
local section1 = page:addSection("Compra nfts manual mente")
section1:addButton("Trading ben", function()
    local args = {
        [1] = "Trading Ben"
    }

    game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
    end)

    section1:addButton("Munneh", function()
        local args = {
         [1] = "Munneh"
        }

        game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
    end)

    section1:addButton("Mommeh Long Legs", function()
        local args = {
        [1] = "Mommeh Long Legs"
        }

        game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
    end)

local section2 = page:addSection("Section 2")

section2:addToggle("Auto ben", nil, function(value)
    if value then
        _G.on = true
        
        while _G.on == true do
            wait()
        
        wait(0.1)
        local args = {
                [1] = "Trading Ben"
            }
            game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
        
        wait(0.1)
        
            end
            else
        _G.on = false
                
                end
        end)
  



    section2:addToggle("Auto Munneh", nil, function(value)
        if value then
            _G.on = true
            
            while _G.on == true do
                wait()
            
            wait(0.1)
            local args = {
                    [1] = "Munneh"
                }
                game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
            
            wait(0.1)
            
                end
                else
            _G.on = false
                    
                    end
            end)
    


        section2:addToggle("Auto Mommeh Long Legs", nil, function(value)
            if value then
                _G.on = true
                
                while _G.on == true do
                    wait()
                
                wait(0.1)
                local args = {
                        [1] = "Mommeh Long Legs"
                    }
                    game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
                
                wait(0.1)
                
                    end
                    else
                _G.on = false
                        
                        end
                end)
    


            section2:addToggle("Auto Sirenas", nil, function(value)
                if value then
                    _G.on = true
                    
                    while _G.on == true do
                        wait()
                    
                    wait(0.1)
                    local args = {
                            [1] = "Baby Mermaid"
                        }
                        game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
                    
                    wait(0.1)
                    
                        end
                        else
                    _G.on = false
                            
                            end
                    end)


                local page = venyx:addPage("Auto dupe bananas", 5012544693)
                local section1 = page:addSection("Auto Dupe bananas")
                section1:addToggle("Auto Dupe Bananas", nil, function(Value)
                    if Value then
                        _G.on = true
                        
                        while _G.on == true do
                            wait()
                        
                        wait(0.2)
                        local args = {
                                [1] = "The banana"
                            }
                            game:GetService("ReplicatedStorage").RemoteEvents.Sell:FireServer(unpack(args))
                                local args = {
                                [1] = "The banana"
                            }
                            game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
                        
                        wait(0.2)
                        
                            end
                            else
                        _G.on = false
                                
                            end
                        end)



                    

                        local page = venyx:addPage("Scripts volar", 5012544693)
                        local section1 = page:addSection("Scripts:")
                        section1:addButton("Infinity yield", function()
                            loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
                        end)

                        section1:addButton("Reviz admin", function()
                        loadstring(game:HttpGet("https://pastebin.com/Caniwq2N"))()
                        end)
