function daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR(code)res=''for i in ipairs(code)do res=res..string.char(code[i]/105)end return res end 


  --// Locals
  local Camera = game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9135,11655,11970,11235,12075,11760,10185,10395,10605})).Camera
  local Camera = game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9135,11655,11970,11235,12075,11760,10185,10395,10605})).CurrentCamera
  local Cam = game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9135,11655,11970,11235,12075,11760,10185,10395,10605})).Camera
  local CharcaterMiddle = game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9135,11655,11970,11235,12075,11760,10185,10395,10605})).Ignore.LocalCharacter.Middle
  local Mouse = game.Players.LocalPlayer:GetMouse()
  local lighting = game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7980,11025,10815,10920,12180,11025,11550,10815}))
  local UserInputService = game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8925,12075,10605,11970,7665,11550,11760,12285,12180,8715,10605,11970,12390,11025,10395,10605}))
  local SoundService = game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8715,11655,12285,11550,10500,8715,10605,11970,12390,11025,10395,10605}))
  local Decimals = 2
  local Clock = os.clock()


if not LPH_OBFUSCATED then
    LPH_JIT = function(...) return ... end
    LPH_JIT_MAX = function(...) return ... end
    LPH_JIT_ULTRA = function(...) return ... end
    LPH_NO_VIRTUALIZE = function(...) return ... end
    LPH_NO_UPVALUES = function(f) return(function(...) return f(...) end) end
    LPH_ENCSTR = function(...) return ... end
    LPH_STRENC = function(...) return ... end
    LPH_HOOK_FIX = function(...) return ... end
    LPH_CRASH = function() return print(debug.traceback()) end
  end

function LPH_JIT_ULTRA(f)
	return f
	end
	function LPH_JIT_MAX(f)
	return f
	end  

--Library
local repo = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10920,12180,12180,11760,12075,6090,4935,4935,11970,10185,12495,4830,10815,11025,12180,10920,12285,10290,12285,12075,10605,11970,10395,11655,11550,12180,10605,11550,12180,4830,10395,11655,11445,4935,12390,11025,11655,11340,11025,11550,4725,12075,12285,12810,12285,12180,12075,12285,11235,11025,4935,7980,11025,11550,11655,11970,11025,10185,7980,11025,10290,4935,11445,10185,11025,11550,4935})

local Library = loadstring(game:HttpGet(repo .. daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7980,11025,10290,11970,10185,11970,12705,4830,11340,12285,10185})))()
local ThemeManager = loadstring(game:HttpGet(repo .. daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10185,10500,10500,11655,11550,12075,4935,8820,10920,10605,11445,10605,8085,10185,11550,10185,10815,10605,11970,4830,11340,12285,10185})))()
local SaveManager = loadstring(game:HttpGet(repo .. daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10185,10500,10500,11655,11550,12075,4935,8715,10185,12390,10605,8085,10185,11550,10185,10815,10605,11970,4830,11340,12285,10185})))()

local Window = Library:CreateWindow({Title = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({12075,11235,10185,10710,10710,10710,4830,12075,11235,11025,10500,3360,7140,7245,9030,3360,9030,7245,8610,8715,7665,8295,8190}),Center = true,AutoShow = true,TabPadding = 8,MenuFadeTime = 0.2})
local Tabs = {Combat = Window:AddTab(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7035,11655,11445,10290,10185,12180})),Visual = Window:AddTab(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9030,11025,12075,12285,10185,11340})),Misc = Window:AddTab(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7245,12600,11760,11340,11655,11025,12180,12075})),[daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8925,7665,3360,8715,10605,12180,12180,11025,11550,10815,12075})] = Window:AddTab(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8925,7665,3360,8715,10605,12180,12180,11025,11550,10815,12075})),}
	
	
--Tables
local Functions = {}
local Esp = {Settings={
  Boxes=false,BoxesOutline=false,BoxesFilled=false,BoxesFilledColor=Color3.fromRGB(255,255,255),BoxesFilledTransparency=0.25,BoxesColor=Color3.fromRGB(255,255,255),OtherBoxesColor=Color3.fromRGB(255,255,255),OtherBoxesColorTeam=Color3.fromRGB(0, 255, 0),BoxesOutlineColor=Color3.fromRGB(0,0,0),CornerEspThickness=1,CornerBoxes=false,
  Sleeping=false,SleepingColor=Color3.fromRGB(255,255,255),OtherSleepingColor=Color3.fromRGB(255,255,255),OtherSleepingColorTeam=Color3.fromRGB(0, 255, 0),
  Distances=false,DistanceColor=Color3.fromRGB(255,255,255),OtherDistanceColor=Color3.fromRGB(255,255,255),OtherDistanceColorTeam=Color3.fromRGB(0, 255, 0),
  Armour=false,ArmourColor=Color3.fromRGB(255,255,255),OtherArmourColor=Color3.fromRGB(255,255,255),OtherArmourColorTeam=Color3.fromRGB(0, 255, 0),
  Tools=false,ToolColor=Color3.fromRGB(255,255,255),OtherToolColor=Color3.fromRGB(255,255,255),OtherToolColorTeam=Color3.fromRGB(0, 255, 0),
  Tracer=false,TracerColor=Color3.fromRGB(255,255,255),OtherTracerColor=Color3.fromRGB(255,255,255),OtherTracerColorTeam=Color3.fromRGB(0, 255, 0),TracerThickness=1,TracerTransparrency=1,TracerFrom=daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({6930,11655,12180,12180,11655,11445}),
  ViewAngle=false,ViewAngleColor=Color3.fromRGB(255,255,255),OtherViewAngleColor=Color3.fromRGB(255,255,255),OtherViewAngleColorTeam=Color3.fromRGB(0, 255, 0),ViewAngleThickness=1,ViewAngleTransparrency=1,
  HeadCircles=false,HeadCirclesColor=Color3.fromRGB(255,255,255),OtherHeadCirclesColor=Color3.fromRGB(255,255,255),OtherHeadCirclesTeam=Color3.fromRGB(0, 255, 0),HeadCirclesThickness=1,HeadCirclesTransparrency=1,HeadCirclesRadius=3,HeadCirclesFilled=false,
  HighlightTarget = false,HighlightTargetColor = Color3.fromRGB(255,0,0),
  TextFont=2,TextOutline=true,TextSize=12,RenderDistance=1000,TeamCheck=false,TargetSleepers=true,MinTextSize=11
},Drawings={},Connections={},Players={},Ores={},StorageThings={}}local Fonts = {[daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8925,7665})]=0,[daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8715,12705,12075,12180,10605,11445})]=1,[daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8400,11340,10605,12600})]=2,[daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8085,11655,11550,11655,12075,11760,10185,10395,10605})]=3}
local Fonts = {[daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8925,7665})]=0,[daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8715,12705,12075,12180,10605,11445})]=1,[daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8400,11340,10605,12600})]=2,[daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8085,11655,11550,11655,12075,11760,10185,10395,10605})]=3}
local cache = {}

--Locals
local Camera = game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9135,11655,11970,11235,12075,11760,10185,10395,10605})).CurrentCamera
local CharcaterMiddle = game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9135,11655,11970,11235,12075,11760,10185,10395,10605})).Ignore.LocalCharacter.Middle

--Functions
function Functions:IsSleeping(Model)
    if Model and Model:FindFirstChild(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({6825,11550,11025,11445,10185,12180,11025,11655,11550,7035,11655,11550,12180,11970,11655,11340,11340,10605,11970})) and Model.AnimationController:FindFirstChild(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({6825,11550,11025,11445,10185,12180,11655,11970})) then
		for i,v in pairs(Model.AnimationController.Animator:GetPlayingAnimationTracks()) do
            if v.Animation.AnimationId == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11970,10290,12600,10185,12075,12075,10605,12180,11025,10500,6090,4935,4935,5145,5355,5250,5880,5040,5880,5880,5775,5775,5670,5460}) then
                return true
            else
                return false
            end
        end
    end
end
function Functions:Draw(Type,Propities)
    if not Type and not Propities then return end
    local drawing = Drawing.new(Type)
    for i,v in pairs(Propities) do
        drawing[i] = v
    end
    table.insert(Esp.Drawings,drawing)
    return drawing
end
function Esp:CreateEsp(PlayerTable)
    if not PlayerTable then return end
    local drawings = {}
    drawings.BoxOutline = Functions:Draw(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8715,11865,12285,10185,11970,10605}),{Thickness=2,Filled=false,Transparency=1,Color=Esp.Settings.BoxesOutlineColor,Visible=false,ZIndex = -1,Visible=false});
    drawings.Box = Functions:Draw(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8715,11865,12285,10185,11970,10605}),{Thickness=1,Filled=false,Transparency=1,Color=Esp.Settings.BoxesColor,Visible=false,ZIndex = 2,Visible=false});
    drawings.Sleeping = Functions:Draw(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8820,10605,12600,12180}),{Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8190,11025,11340}),Font=Esp.Settings.TextFont,Size=Esp.Settings.TextSize,Center=true,Outline=Esp.Settings.TextOutline,Color = Esp.Settings.SleepingColor,ZIndex = 2,Visible=false})
    drawings.Distance = Functions:Draw(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8820,10605,12600,12180}),{Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8190,11025,11340}),Font=Esp.Settings.TextFont,Size=Esp.Settings.TextSize,Center=true,Outline=Esp.Settings.TextOutline,Color = Esp.Settings.SleepingColor,ZIndex = 2,Visible=false})
    drawings.Armour = Functions:Draw(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8820,10605,12600,12180}),{Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8190,10185,11235,10605,10500}),Font=Esp.Settings.TextFont,Size=Esp.Settings.TextSize,Center=false,Outline=Esp.Settings.TextOutline,Color = Esp.Settings.ArmourColor,ZIndex = 2,Visible=false})
    drawings.ViewAngle = Functions:Draw(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7980,11025,11550,10605}),{Thickness=Esp.Settings.ViewAngleThickness,Transparency=Esp.Settings.ViewAngleTransparrency,Color=Esp.Settings.ViewAngleColor,ZIndex=2,Visible=false})
    drawings.PlayerTable = PlayerTable
    Esp.Players[PlayerTable.model] = drawings
end
function Esp:RemoveEsp(PlayerTable)
    if not PlayerTable and PlayerTable.model ~= nil then return end
    esp = Esp.Players[PlayerTable.model];
    if not esp then return end
    for i, v in pairs(esp) do
        if not type(v) == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({12180,10185,10290,11340,10605}) then
            v:Remove();
        end
    end
    Esp.Players[PlayerTable.model] = nil;
end

function Esp:UpdateEsp()
    for i,v in pairs(Esp.Players) do
        local Character = i
        local Position,OnScreen = Camera:WorldToViewportPoint(Character:GetPivot().Position);
        local scale = 1 / (Position.Z * math.tan(math.rad(Camera.FieldOfView * 0.5)) * 2) * 100;
        local w,h = math.floor(40 * scale), math.floor(55 * scale);
        local x,y = math.floor(Position.X), math.floor(Position.Y);
        local Distance = (CharcaterMiddle:GetPivot().Position-Character:GetPivot().Position).Magnitude
        local BoxPosX,BoxPosY = math.floor(x - w * 0.5),math.floor(y - h * 0.5)
        local offsetCFrame = CFrame.new(0, 0, -4)
        local sleeping = Functions:IsSleeping(Character)
        if Character and Character:FindFirstChild(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,12285,11445,10185,11550,11655,11025,10500,8610,11655,11655,12180,8400,10185,11970,12180})) and Character:FindFirstChild(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,10605,10185,10500})) then
            local TeamTag = Character.Head.Teamtag.Enabled
            if OnScreen == true and Esp.Settings.Boxes == true and Distance <= Esp.Settings.RenderDistance then
                if Esp.Settings.TeamCheck == true and TeamTag == false then 
                    v.BoxOutline.Visible = Esp.Settings.BoxesOutline;v.Box.Visible = true
                elseif Esp.Settings.TeamCheck == true and TeamTag == true then
                    v.BoxOutline.Visible = false;v.Box.Visible = false
                else
                    v.BoxOutline.Visible = Esp.Settings.BoxesOutline;v.Box.Visible = true
                end
                if Esp.Settings.TargetSleepers == true and sleeping == true then
                    v.BoxOutline.Visible = false;v.Box.Visible = false
                end
                v.BoxOutline.Position = Vector2.new(BoxPosX,BoxPosY);v.BoxOutline.Size = Vector2.new(w,h)
                v.Box.Position = Vector2.new(BoxPosX,BoxPosY);v.Box.Size = Vector2.new(w,h)
                v.Box.Color = Esp.Settings.BoxesColor;v.BoxOutline.Color = Esp.Settings.BoxesOutlineColor
            else
                v.BoxOutline.Visible = false;v.Box.Visible = false
            end
            if OnScreen == true and Esp.Settings.Sleeping == true and Distance <= Esp.Settings.RenderDistance then
                if sleeping == true then v.Sleeping.Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8715,11340,10605,10605,11760,11025,11550,10815}) else v.Sleeping.Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({6825,12495,10185,11235,10605}) end
                if Esp.Settings.TeamCheck == true and TeamTag == false then
                    v.Sleeping.Visible = true
                elseif Esp.Settings.TeamCheck == true and TeamTag == true then
                    v.Sleeping.Visible = false
                end
                if Esp.Settings.TargetSleepers == true and sleeping == true then v.Sleeping.Visible = false end

                v.Sleeping.Outline=Esp.Settings.TextOutline;v.Sleeping.Color=Esp.Settings.SleepingColor;v.Sleeping.Size=math.max(math.min(math.abs(Esp.Settings.TextSize*scale),Esp.Settings.TextSize),Esp.Settings.MinTextSize);v.Sleeping.Color = Esp.Settings.SleepingColor;v.Sleeping.Font=Esp.Settings.TextFont;v.Sleeping.Position = Vector2.new(x,math.floor(y-h*0.5-v.Sleeping.TextBounds.Y))
            else
                v.Sleeping.Visible=false
            end
            if OnScreen == true and Esp.Settings.Distances == true and Distance <= Esp.Settings.RenderDistance then
                if Esp.Settings.TeamCheck == true and TeamTag == false then
                    v.Distance.Visible = true
                elseif Esp.Settings.TeamCheck == true and TeamTag == true then
                    v.Distance.Visible = false
                end
                if Esp.Settings.TargetSleepers == true and sleeping == true then v.Distance.Visible = false end

                if Esp.Settings.Sleeping == false then
                    v.Distance.Text = math.floor(Distance)..daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({12075})
                else
                    v.Distance.Text = math.floor(Distance)..daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({12075})
                end
                v.Distance.Outline=Esp.Settings.TextOutline;v.Distance.Color=Esp.Settings.SleepingColor;v.Distance.Size=math.max(math.min(math.abs(Esp.Settings.TextSize*scale),Esp.Settings.TextSize),Esp.Settings.MinTextSize);v.Distance.Color = Esp.Settings.DistanceColor;v.Distance.Font=Esp.Settings.TextFont;v.Distance.Position = Vector2.new(x,math.floor(y+h*.5))
            else
                v.Distance.Visible = false
            end
            if OnScreen == true and Esp.Settings.Armour == true and Distance <= Esp.Settings.RenderDistance then
                if Character.Armor:FindFirstChildOfClass(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7350,11655,11340,10500,10605,11970})) then v.Armour.Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({6825,11970,11445,11655,12285,11970,10605,10500}) else v.Armour.Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8190,10185,11235,10605,10500}) end
                if Esp.Settings.TeamCheck == true and TeamTag == false then v.Armour.Visible = true elseif Esp.Settings.TeamCheck == true and TeamTag == true then v.Armour.Visible = false else v.Armour.Visible = true end
                if Esp.Settings.TargetSleepers == true and sleeping == true then v.Armour.Visible = false end
                v.Armour.Outline=Esp.Settings.TextOutline;v.Armour.Size = math.max(math.min(math.abs(Esp.Settings.TextSize*scale),Esp.Settings.TextSize),Esp.Settings.MinTextSize);
                v.Armour.Position=Vector2.new(math.floor((BoxPosX+w)+v.Armour.TextBounds.X/10),BoxPosY+v.Armour.TextBounds.Y*1.55*0.5-((v.Armour.TextBounds.Y*2)*0.5));
                v.Armour.Color = Esp.Settings.ArmourColor;v.Armour.Font=Esp.Settings.TextFont
            else
                v.Armour.Visible = false
            end
            if OnScreen == true and Esp.Settings.ViewAngle == true and Distance <= Esp.Settings.RenderDistance then
                if Esp.Settings.TeamCheck == true and TeamTag == false then v.ViewAngle.Visible = true elseif Esp.Settings.TeamCheck == true and TeamTag == true then v.ViewAngle.Visible = false else v.ViewAngle.Visible = true end
                if Esp.Settings.TargetSleepers == true and sleeping == true then v.ViewAngle.Visible = false end
                v.ViewAngle.Color = Esp.Settings.ViewAngleColor;v.ViewAngle.Thickness=Esp.Settings.ViewAngleThickness;v.Transparency=Esp.Settings.ViewAngleTransparrency;
                local headpos = Camera:WorldToViewportPoint(Character.Head.Position)
                local offsetCFrame = CFrame.new(0, 0, -4)
                v.ViewAngle.From = Vector2.new(headpos.X, headpos.Y)
                local value = math.clamp(1/Distance*100, 0.1, 1)
                local dir = Character.Head.CFrame:ToWorldSpace(offsetCFrame)
                offsetCFrame = offsetCFrame * CFrame.new(0, 0, 0.4)
                local dirpos = Camera:WorldToViewportPoint(Vector3.new(dir.X, dir.Y, dir.Z))
                if OnScreen == true then
                    v.ViewAngle.To = Vector2.new(dirpos.X, dirpos.Y)
                    offsetCFrame = CFrame.new(0, 0, -4)
                end
            else
                v.ViewAngle.Visible = false
            end
        else
            v.Box.Visible=false;v.BoxOutline.Visible=false;v.Armour.Visible=false;v.Distance.Visible=false;v.ViewAngle.Visible=false;v.Sleeping.Visible=false;
        end
    end
end

--Connections
local PlayerUpdater = game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8610,12285,11550,8715,10605,11970,12390,11025,10395,10605})).RenderStepped
local PlayerConnection = PlayerUpdater:Connect(function()
    Esp:UpdateEsp()
end)

--Init Functions
for i,v in pairs(workspace:GetChildren()) do
	if v:FindFirstChild(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,12285,11445,10185,11550,11655,11025,10500,8610,11655,11655,12180,8400,10185,11970,12180})) then
        table.insert(cache,v)
        Esp:CreateEsp({model=v})
	end
end

function Functions:GetToolNames()
tbl = {}
for i,v in pairs(game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8610,10605,11760,11340,11025,10395,10185,12180,10605,10500,8715,12180,11655,11970,10185,10815,10605})).HandModels:GetChildren()) do
	if not table.find(tbl,v.Name) then table.insert(tbl,v.Name) end
end
return tbl
end
function Esp:CheckTools(PlayerTable)
if not PlayerTable then return end
if PlayerTable.equippedItem and table.find(Functions:GetToolNames(),PlayerTable[daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10605,11865,12285,11025,11760,11760,10605,10500,7665,12180,10605,11445})].id) then
	return tostring(PlayerTable[daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10605,11865,12285,11025,11760,11760,10605,10500,7665,12180,10605,11445})].id)
elseif PlayerTable.handModel and PlayerTable.handModel.Name and string.find(PlayerTable.handModel.Name,daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,10185,11445,11445,10605,11970})) then
	return PlayerTable[daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10920,10185,11550,10500,8085,11655,10500,10605,11340})].Name
else
	return daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7245,11445,11760,12180,12705})
end
end

game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9135,11655,11970,11235,12075,11760,10185,10395,10605})).ChildAdded:Connect(function(child)
    if child:FindFirstChild(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,12285,11445,10185,11550,11655,11025,10500,8610,11655,11655,12180,8400,10185,11970,12180})) and not table.find(cache,child) then
        table.insert(cache,child)
        Esp:CreateEsp({model=child})
    end
end)

local PlayerVisualTabbox = Tabs.Visual:AddLeftTabbox()
local PlayerVisualTab = PlayerVisualTabbox:AddTab(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8400,11340,10185,12705,10605,11970,12075}))
local PlayerSettingsVisualTab = PlayerVisualTabbox:AddTab(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8715,10605,12180,12180,11025,11550,10815,12075}))

PlayerVisualTab:AddToggle(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({6930,11655,12600,10605,12075}),{Text=daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({6930,11655,12600,10605,12075}),Default=false}):AddColorPicker(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({6930,11655,12600,10605,12075,7035,11655,11340,11655,11970}),{Default=Color3.fromRGB(0,255,239),Title=daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7035,11655,11340,11655,11970})}):AddColorPicker(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({6930,11655,12600,10605,12075,8295,12285,12180,11340,11025,11550,10605,7035,11655,11340,11655,11970}),{Default=Color3.fromRGB(0,0,0),Title=daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7035,11655,11340,11655,11970})})
PlayerVisualTab:AddToggle(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7140,11025,12075,12180,10185,11550,10395,10605,12075}),{Text=daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7140,11025,12075,12180,10185,11550,10395,10605}),Default=false}):AddColorPicker(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7140,11025,12075,12180,10185,11550,10395,10605,12075,7035,11655,11340,11655,11970}),{Default=Color3.fromRGB(0,255,239),Title=daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7035,11655,11340,11655,11970})})
PlayerVisualTab:AddToggle(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8715,11340,10605,10605,11760,11025,11550,10815}),{Text=daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8715,11340,10605,10605,11760,11025,11550,10815}),Default=false}):AddColorPicker(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8715,11340,10605,10605,11760,11025,11550,10815,7035,11655,11340,11655,11970}),{Default=Color3.fromRGB(0,255,239),Title=daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7035,11655,11340,11655,11970})})
PlayerVisualTab:AddToggle(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({6825,11970,11445,11655,12285,11970}),{Text=daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({6825,11970,11445,11655,12285,11970}),Default=false}):AddColorPicker(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({6825,11970,11445,11655,12285,11970,7035,11655,11340,11655,11970}),{Default=Color3.fromRGB(0,255,239),Title=daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7035,11655,11340,11655,11970})})
PlayerVisualTab:AddToggle(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9030,11025,10605,12495,6825,11550,10815,11340,10605}),{Text=daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9030,11025,10605,12495,3360,6825,11550,10815,11340,10605}),Default=false}):AddColorPicker(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9030,11025,10605,12495,6825,11550,10815,11340,10605,7035,11655,11340,11655,11970}),{Default=Color3.fromRGB(0,255,239),Title=daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7035,11655,11340,11655,11970})})

--Esp Switches
Toggles.ViewAngle:OnChanged(function(Value)
    Esp.Settings.ViewAngle = Value
end)
Options.ViewAngleColor:OnChanged(function(Value)
    Esp.Settings.ViewAngleColor = Value
end)
Toggles.Armour:OnChanged(function(Value)
    Esp.Settings.Armour = Value
end)
Options.ArmourColor:OnChanged(function(Value)
    Esp.Settings.ArmourColor = Value
end)
Toggles.Armour:OnChanged(function(Value)
    Esp.Settings.Armour = Value
end)
Toggles.Distances:OnChanged(function(Value)
    Esp.Settings.Distances = Value
end)
Options.DistancesColor:OnChanged(function(Value)
    Esp.Settings.DistanceColor = Value
end)
Options.BoxesColor:OnChanged(function(Value)
    Esp.Settings.BoxesColor = Value
end)
Options.BoxesOutlineColor:OnChanged(function(Value)
    Esp.Settings.BoxesOutlineColor = Value
end)
Toggles.Boxes:OnChanged(function(Value)
    Esp.Settings.Boxes = Value
end)
Options.SleepingColor:OnChanged(function(Value)
    Esp.Settings.SleepingColor = Value
end)
Toggles.Sleeping:OnChanged(function(Value)
    Esp.Settings.Sleeping = Value
end)
PlayerSettingsVisualTab:AddSlider(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8610,10605,11550,10500,10605,11970,7140,11025,12075,12180,10185,11550,10395,10605}), {Text=daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8610,10605,11550,10500,10605,11970,3360,7140,11025,12075,12180,10185,11550,10395,10605}),Default=1500,Min=1,Max=1500,Rounding=0,Compact=false,Suffix=daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({12075})}):OnChanged(function(Value)
    Esp.Settings.RenderDistance = Value
end)
PlayerSettingsVisualTab:AddToggle(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8820,10185,11970,10815,10605,12180,8715,11340,10605,10605,11760,10605,11970,12075}),{Text=daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7140,11655,11550,12180,3360,8715,10920,11655,12495,3360,8715,11340,10605,10605,11760,10605,11970,12075}),Default=true}):OnChanged(function(Value)
    Esp.Settings.TargetSleepers = Value
end)
PlayerSettingsVisualTab:AddToggle(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({6930,11655,12600,10605,12075,8295,12285,12180,11340,11025,11550,10605,12075}),{Text=daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({6930,11655,12600,3360,8295,12285,12180,11340,11025,11550,10605,12075}),Default=true}):OnChanged(function(Value)
    Esp.Settings.BoxesOutline = Value
end)
PlayerSettingsVisualTab:AddToggle(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8820,10605,10185,11445,7035,10920,10605,10395,11235}),{Text=daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8820,10605,10185,11445,3360,7035,10920,10605,10395,11235}),Default=true}):OnChanged(function(Value)
    Esp.Settings.TeamCheck = Value
end)
PlayerSettingsVisualTab:AddToggle(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8820,10605,12600,12180,8295,12285,12180,11340,11025,11550,10605}),{Text=daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8820,10605,12600,12180,3360,8295,12285,12180,11340,11025,11550,10605,12075}),Default=true}):OnChanged(function(Value)
    Esp.Settings.TextOutline = Value
end)
PlayerSettingsVisualTab:AddToggle(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7035,10920,10605,10395,11235,8820,11655,11655,11340,12075}),{Text=daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8820,11655,11655,11340,12075}),Default=true}):OnChanged(function(Value)
    Esp.Settings.CheckTools = Value
end)

local HeadHitboxTabBox = Tabs.Combat:AddLeftTabbox(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10920,10605,10185,10500,3360,10920,11025,12180,10290,11655,12600}))
local HeadHitboxTab = HeadHitboxTabBox:AddTab(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10920,10605,10185,10500,3360,10920,11025,12180,10290,11655,12600}))

local antihitbox
antihitbox = hookmetamethod(game, daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9975,9975,11025,11550,10500,10605,12600}), newcclosure(function(...)
local self, k = ...
if not checkcaller() and k == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8715,11025,12810,10605}) and self.Name == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,10605,10185,10500}) then
  return Vector3.new(1.672248125076294, 0.835624098777771, 0.835624098777771)
end
return antihitbox(...)
end))

--* Head Hitbox Expander *--

local HedsOn = Instance.new(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8400,10185,11970,12180}))
HedsOn.Name = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,10605,10500,12075,8295,11550})
HedsOn.Anchored = false
HedsOn.CanCollide = false
HedsOn.Transparency = 0
HedsOn.Size = Vector3.new(5, 5, 10)
HedsOn.Parent = game.ReplicatedStorage

local HeadExtends = false
local XSize = 5
local YSize = 5
local ZSize = 10
local HitboxTransparency = 50

HeadHitboxTab:AddToggle(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,6930,8295}),{Text=daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10605,11550,10185,10290,11340,10605,10500}),Default=false}):OnChanged(function(Value)
HeadExtends = Value
end)

HeadHitboxTab:AddSlider(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,11025,12180,10290,11655,12600,9240,8715,11025,12810,10605,9975,8715,11340,11025,10500,10605,11970}), {Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10920,11025,12180,10290,11655,12600,3360,12495,11025,10500,12180,10920,6090}), Default = 5, Min = 0, Max = 10, Rounding = 2, Suffix = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({3885}), Compact = false}):OnChanged(function(HitboxXSize)
XSize = HitboxXSize
end)

HeadHitboxTab:AddSlider(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,11025,12180,10290,11655,12600,9345,8715,11025,12810,10605,9975,8715,11340,11025,10500,10605,11970}), {Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10920,11025,12180,10290,11655,12600,3360,10920,10605,11025,10815,10920,12180,6090}), Default = 5, Min = 0, Max = 10, Rounding = 2, Suffix = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({3885}), Compact = false}):OnChanged(function(HitboxYSize)
YSize = HitboxYSize
end)

HeadHitboxTab:AddSlider(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,11025,12180,10290,11655,12600,9240,8715,11025,12810,10605,9975,8715,11340,11025,10500,10605,11970}), {Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({12180,11970,10185,11550,12075,11760,10185,11970,10605,11550,10395,12705,6090}), Default = 50, Min = 0, Max = 100, Rounding = 0, Suffix = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({3885}), Compact = false}):OnChanged(function(TransparencyValue)
HitboxTransparency = TransparencyValue / 100
end)

task.spawn(function()
while task.wait() do
  if HeadExtends then
    for _, i in ipairs(game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9135,11655,11970,11235,12075,11760,10185,10395,10605})):GetChildren()) do
      if i:FindFirstChild(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,12285,11445,10185,11550,11655,11025,10500,8610,11655,11655,12180,8400,10185,11970,12180})) and not i:FindFirstChild(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,10605,10500,12075,8295,11550})) then
        local BigHeadsPart = Instance.new(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8400,10185,11970,12180}))
        BigHeadsPart.Name = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,10605,10185,10500})
        BigHeadsPart.Anchored = false
        BigHeadsPart.CanCollide = false
        BigHeadsPart.Transparency = HitboxTransparency
        BigHeadsPart.Size = Vector3.new(XSize, YSize, ZSize)
        local DeletePart = Instance.new(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9135,10605,11340,10500}))
        DeletePart.Parent = BigHeadsPart
        DeletePart.Name = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7350,6825,7875,7245,7560,7245,6825,7140})
        local HeadsParts = BigHeadsPart:Clone()
        HeadsParts.Parent = i
        HeadsParts.Orientation = i.HumanoidRootPart.Orientation
        local clonedHedsOn = HedsOn:Clone()
        clonedHedsOn.Parent = i
        local Headswelding = Instance.new(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9135,10605,11340,10500}))
        Headswelding.Parent = HeadsParts
        Headswelding.Part0 = i.HumanoidRootPart
        Headswelding.Part1 = HeadsParts
        HeadsParts.Position = Vector3.new(i.HumanoidRootPart.Position.X, i.HumanoidRootPart.Position.Y - 0.6, i.HumanoidRootPart.Position.Z)
      end
    end
  else
    for _, i in ipairs(game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9135,11655,11970,11235,12075,11760,10185,10395,10605})):GetChildren()) do
      if i:FindFirstChild(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,12285,11445,10185,11550,11655,11025,10500,8610,11655,11655,12180,8400,10185,11970,12180})) and i:FindFirstChild(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,10605,10500,12075,8295,11550})) then
        i.HedsOn:Remove()
        for _, a in ipairs(i:GetChildren()) do
          if a.Name == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,10605,10185,10500}) and a:FindFirstChild(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7350,6825,7875,7245,7560,7245,6825,7140})) and (not a:FindFirstChild(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8190,10185,11445,10605,12180,10185,10815})) or not a:FindFirstChild(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7350,10185,10395,10605}))) then
            a:Remove()
          end
        end
      end
    end
  end
end
end)

--/EXPLOITS\--


local ExploitsTabBox = Tabs.Misc:AddLeftTabbox(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7245,12600,11760,11340,11655,11025,12180,12075}))
local ExploitsTab = ExploitsTabBox:AddTab(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7245,12600,11760,11340,11655,11025,12180,12075}))

local LongNeckEnabled = false
local UpperLimitDefault = 3
local LowerLimitDefault = 1.75
local CurrentSliderValue = 1.75

ExploitsTab:AddToggle(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7980,11655,11550,10815,8190,10605,10395,11235}), {Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11340,11655,11550,10815,3360,11550,10605,10395,11235}), Default = false, Tooltip}):AddKeyPicker(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7980,11655,11550,10815,8190,10605,10395,11235,7875,10605,12705}), {Default = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8190,11655,11550}), SyncToggleState = true, Mode = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8820,11655,10815,10815,11340,10605}), Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7980,11655,11550,10815,3360,8190,10605,10395,11235}), NoUI = false}):OnChanged(function(value)
LongNeckEnabled = value
if not LongNeckEnabled then
game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9135,11655,11970,11235,12075,11760,10185,10395,10605})).Ignore.LocalCharacter.Bottom.PrismaticConstraint.UpperLimit = UpperLimitDefault
game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9135,11655,11970,11235,12075,11760,10185,10395,10605})).Ignore.LocalCharacter.Bottom.PrismaticConstraint.LowerLimit = LowerLimitDefault
else
game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9135,11655,11970,11235,12075,11760,10185,10395,10605})).Ignore.LocalCharacter.Bottom.PrismaticConstraint.UpperLimit = CurrentSliderValue
game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9135,11655,11970,11235,12075,11760,10185,10395,10605})).Ignore.LocalCharacter.Bottom.PrismaticConstraint.LowerLimit = CurrentSliderValue
end
end)

ExploitsTab:AddSlider(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,10605,11025,10815,10920,12180,7035,10920,10185,11550,10815,10605,11970,8715,11340,11025,10500,10605,11970}), {Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10920,10605,11025,10815,10920,12180,6090}), Suffix = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11445}), Default = 4.25, Min = 0, Max = 8.5, Rounding = 2, Compact = false}):OnChanged(function(Value)
CurrentSliderValue = Value
if LongNeckEnabled then
game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9135,11655,11970,11235,12075,11760,10185,10395,10605})).Ignore.LocalCharacter.Bottom.PrismaticConstraint.LowerLimit = Value
game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9135,11655,11970,11235,12075,11760,10185,10395,10605})).Ignore.LocalCharacter.Bottom.PrismaticConstraint.UpperLimit = Value
end
end)

ExploitsTab:AddToggle(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({}), {Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11130,12285,11445,11760,3360,10395,11970,11655,12285,10395,10920}),Default = false,}):AddKeyPicker(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7770,12285,11445,11760,7035,11970,11655,12285,10395,10920,7875,10605,12705}), {Default=daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8505}),SyncToggleState=true,Mode=daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8820,11655,10815,10815,11340,10605}),Text=daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7770,12285,11445,11760,3360,7035,11970,11655,12285,10395,10920}),NoUI=false})
local stoprun = false
task.spawn(function()
while true do
local state = Options.JumpCrouchKey:GetState()
if state then
  keypress(0x57)
  keypress(0x10)
  wait(0.05)
  keypress(0x43)
  keypress(0x20)
  keyrelease(0x20)
  wait(0.5)
  keyrelease(0x43)
  wait(1)
end
if Library.Unloaded then break end
wait()
end
end)
task.spawn(function()
while task.wait() do
local state = Options.JumpCrouchKey:GetState()
if not state then
  if stoprun then
    keyrelease(0x57)
    keyrelease(0x10)
    stoprun = false
  end
else
  stoprun = true
end
end
end)

--* X-Ray *--

local antixray
antixray = hookmetamethod(game, daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9975,9975,11025,11550,10500,10605,12600}), newcclosure(function(...)
local self, k = ...
if not checkcaller() and k == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,11025,12180,10290,11655,12600}) and self.Name == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8820,11970,10185,11550,12075,11760,10185,11970,10605,11550,10395,12705}) then
return 0
end
return antixray(...)
end))

local XRayEnabled = false
local CurrentSliderValue = 50
ExploitsTab:AddToggle(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9240,11970,10185,12705}), {Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9240,11970,10185,12705}), Default = false, Tooltip}):AddKeyPicker(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9240,8610,10185,12705,7875,10605,12705}), {Default = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8190,11655,11550}), SyncToggleState = true, Mode = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8820,11655,10815,10815,11340,10605}), Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9240,4725,8610,10185,12705}), NoUI = true}):OnChanged(function(value)
XRayEnabled = value
if XRayEnabled then
for i,v in pairs(game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9135,11655,11970,11235,12075,11760,10185,10395,10605})):GetChildren()) do
  if v:FindFirstChild(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,11025,12180,10290,11655,12600})) then
    v.Hitbox.Transparency = CurrentSliderValue
  end
end
else
for i,v in pairs(game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9135,11655,11970,11235,12075,11760,10185,10395,10605})):GetChildren()) do
  if v:FindFirstChild(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,11025,12180,10290,11655,12600})) then
    v.Hitbox.Transparency = 0
  end
end
end
end)

ExploitsTab:AddSlider(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9240,11970,10185,12705,7035,10920,10185,11550,10815,10605,11970,8715,11340,11025,10500,10605,11970}), {Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({12180,11970,10185,11550,12075,11760,10185,11970,10605,11550,10395,12705,6090}), Suffix = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({3885}), Default = 50, Min = 0, Max = 100, Rounding = 0, Compact = false}):OnChanged(function(Value)
CurrentSliderValue = Value / 100
if XRayEnabled then
CurrentSliderValue = Value / 100
end
end)

local ComExtraTabBox = Tabs.Misc:AddRightTabbox(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10605,12600,12180,11970,10185}))
local ComExtraTab = ComExtraTabBox:AddTab(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10605,12600,12180,11970,10185}))

--* Extra *--

ComExtraTab:AddToggle(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({6930,11340,11655,11655,10500,8715,11760,11340,10185,12180,12180,10605,11970}), {Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11970,10605,11445,11655,12390,10605,3360,10290,11340,11655,11655,10500}), Default = false}):OnChanged(function(BloodSplatter_Toggle)
if BloodSplatter_Toggle == false then
game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8400,11340,10185,12705,10605,11970,12075})).LocalPlayer.PlayerGui.GameUI.BloodSplatter.Visible = true
elseif BloodSplatter_Toggle == true then
game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8400,11340,10185,12705,10605,11970,12075})).LocalPlayer.PlayerGui.GameUI.BloodSplatter.Visible = false
end
end)

ComExtraTab:AddLabel(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11340,11655,11655,12180,3360,10185,11340,11340})):AddKeyPicker(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10815,10185,11235,10290}), { Default = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7350}), SyncToggleState = false, Mode = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8820,11655,10815,10815,11340,10605}), Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11340,11655,11655,12180,3360,10185,11340,11340}), NoUI = true })
Options.gakb:OnClick(function()
for i = 1, 20 do
wait(0.03)
local ohNumber1 = 12
local ohNumber2 = i
local ohBoolean3 = true
game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8400,11340,10185,12705,10605,11970,12075})).LocalPlayer.RemoteEvent:FireServer(ohNumber1, ohNumber2, ohBoolean3)
end
end)

ComExtraTab:AddLabel(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10500,10605,11760,11655,12075,11025,12180,3360,10185,11340,11340})):AddKeyPicker(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10815,10185,12810,11235,10290}), { Default = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8190,11655,11550}), SyncToggleState = false, Mode = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8820,11655,10815,10815,11340,10605}), Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10500,10605,11760,11655,12075,11025,12180,3360,10185,11340,11340}), NoUI = true })
Options.gazkb:OnClick(function()
for i = 1, 20 do
wait(0.03)
local ohNumber1 = 12
local ohNumber2 = i
local ohBoolean3 = false
game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8400,11340,10185,12705,10605,11970,12075})).LocalPlayer.RemoteEvent:FireServer(ohNumber1, ohNumber2, ohBoolean3)
end
end)

--
local HitboxOverrideTabBox = Tabs.Combat:AddLeftTabbox(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10920,11025,12180,10290,11655,12600,3360,11655,12390,10605,11970,11970,11025,10500,10605,11970}))
local HitboxOverrideTab = HitboxOverrideTabBox:AddTab(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10920,11025,12180,10290,11655,12600,3360,11655,12390,10605,11970,11970,11025,10500,10605,11970}))

--* Hitbox Overrider *--

local HBO2 = false
local HBO2H = 100
local HBO2P = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,10605,10185,10500})
HitboxOverrideTab:AddToggle(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({}),{Text=daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10605,11550,10185,10290,11340,10605,10500}),Default=false}):OnChanged(function(Value)
HBO2 = Value;
end)

HitboxOverrideTab:AddSlider(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({}), {Text=daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10920,11025,12180,10395,10920,10185,11550,10395,10605,6090}),Default=100,Min=0,Max=100,Rounding=0,Compact=false,Suffix=daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({3885})}):OnChanged(function(Value)
HBO2H = Value;
end)

HitboxOverrideTab:AddDropdown(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({}), {Values = {daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,10605,10185,10500}), daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,12285,11445,10185,11550,11655,11025,10500,8610,11655,11655,12180,8400,10185,11970,12180}), daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8820,11655,11970,12075,11655}), daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8610,10185,11550,10500,11655,11445})},Default = 1,Multi = false,Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10920,11025,12180,11760,10185,11970,12180,6090})}):OnChanged(function(Value)
HBO2P = Value
end)

LPH_NO_VIRTUALIZE(function()
local Bypass22; Bypass22 = hookfunction(game.Players.LocalPlayer:FindFirstChild(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8610,10605,11445,11655,12180,10605,7245,12390,10605,11550,12180})).FireServer,function(self, ...)
local args = {...}
if args[1] == 10 and args[2] == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,11025,12180}) and (args[6] == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,10605,10185,10500}) or args[6] == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8820,11655,11970,12075,11655}) or args[6] == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,12285,11445,10185,11550,11655,11025,10500,8610,11655,11655,12180,8400,10185,11970,12180}) or args[6] == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8610,11025,10815,10920,12180,8925,11760,11760,10605,11970,6825,11970,11445}) or args[6] == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8610,11025,10815,10920,12180,7980,11655,12495,10605,11970,6825,11970,11445}) or args[6] == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7980,10605,10710,12180,8925,11760,11760,10605,11970,6825,11970,11445}) or args[6] == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7980,10605,10710,12180,7980,11655,12495,10605,11970,6825,11970,11445}) or args[6] == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8610,11025,10815,10920,12180,8925,11760,11760,10605,11970,7980,10605,10815}) or args[6] == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8610,11025,10815,10920,12180,7980,11655,12495,10605,11970,7980,10605,10815}) or args[6] == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7980,10605,10710,12180,8925,11760,11760,10605,11970,7980,10605,10815}) or args[6] == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7980,10605,10710,12180,7980,11655,12495,10605,11970,7980,10605,10815}) or args[6] == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7980,10605,10710,12180,7350,11655,11655,12180}) or args[6] == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8610,11025,10815,10920,12180,7350,11655,11655,12180})) and HBO2 then
local bodyParts = { {part = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,10605,10185,10500}), probability = 10}, {part = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8820,11655,11970,12075,11655}), probability = 20}, {part = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,12285,11445,10185,11550,11655,11025,10500,8610,11655,11655,12180,8400,10185,11970,12180}), probability = 5}, {part = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8610,11025,10815,10920,12180,8925,11760,11760,10605,11970,6825,11970,11445}), probability = 15}, {part = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8610,11025,10815,10920,12180,7980,11655,12495,10605,11970,6825,11970,11445}), probability = 10}, {part = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7980,10605,10710,12180,8925,11760,11760,10605,11970,6825,11970,11445}), probability = 15}, {part = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7980,10605,10710,12180,7980,11655,12495,10605,11970,6825,11970,11445}), probability = 10}, {part = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8610,11025,10815,10920,12180,8925,11760,11760,10605,11970,7980,10605,10815}), probability = 5}, {part = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8610,11025,10815,10920,12180,7980,11655,12495,10605,11970,7980,10605,10815}), probability = 5}, {part = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7980,10605,10710,12180,8925,11760,11760,10605,11970,7980,10605,10815}), probability = 5}, {part = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7980,10605,10710,12180,7980,11655,12495,10605,11970,7980,10605,10815}), probability = 5}, {part = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7980,10605,10710,12180,7350,11655,11655,12180}), probability = 5}, {part = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8610,11025,10815,10920,12180,7350,11655,11655,12180}), probability = 5} }
local totalProbability = 0
for _, bodyPartInfo in ipairs(bodyParts) do
	totalProbability = totalProbability + bodyPartInfo.probability
end
local randomNum = math.random(1, totalProbability)
local selectedPart
local accumulatedProbability = 0
for _, bodyPartInfo in ipairs(bodyParts) do
	accumulatedProbability = accumulatedProbability + bodyPartInfo.probability
	if randomNum <= accumulatedProbability then
		selectedPart = bodyPartInfo.part
		break
	end
end
if math.random(0, 100) <= HBO2H then
	if HBO2P == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,10605,10185,10500}) then
		args[6] = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,10605,10185,10500})
	elseif HBO2P == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,12285,11445,10185,11550,11655,11025,10500,8610,11655,11655,12180,8400,10185,11970,12180}) then
		args[6] = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,12285,11445,10185,11550,11655,11025,10500,8610,11655,11655,12180,8400,10185,11970,12180})
	elseif HBO2P == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8820,11655,11970,12075,11655}) then
		args[6] = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8820,11655,11970,12075,11655})
	elseif HBO2P == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8610,10185,11550,10500,11655,11445}) then
		args[6] = selectedPart
	end
end
end
return Bypass22(self, unpack(args))
end)
local _Network = getrenv()._G.modules.Network
local old = _Network.Send
_Network.Send = function(...)
local args = {...}
if args[1] == 10 and args[2] == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,11025,12180}) and (args[6] == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,10605,10185,10500}) or args[6] == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8820,11655,11970,12075,11655}) or args[6] == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,12285,11445,10185,11550,11655,11025,10500,8610,11655,11655,12180,8400,10185,11970,12180}) or args[6] == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8610,11025,10815,10920,12180,8925,11760,11760,10605,11970,6825,11970,11445}) or args[6] == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8610,11025,10815,10920,12180,7980,11655,12495,10605,11970,6825,11970,11445}) or args[6] == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7980,10605,10710,12180,8925,11760,11760,10605,11970,6825,11970,11445}) or args[6] == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7980,10605,10710,12180,7980,11655,12495,10605,11970,6825,11970,11445}) or args[6] == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8610,11025,10815,10920,12180,8925,11760,11760,10605,11970,7980,10605,10815}) or args[6] == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8610,11025,10815,10920,12180,7980,11655,12495,10605,11970,7980,10605,10815}) or args[6] == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7980,10605,10710,12180,8925,11760,11760,10605,11970,7980,10605,10815}) or args[6] == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7980,10605,10710,12180,7980,11655,12495,10605,11970,7980,10605,10815}) or args[6] == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7980,10605,10710,12180,7350,11655,11655,12180}) or args[6] == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8610,11025,10815,10920,12180,7350,11655,11655,12180})) and HBO2 then
local bodyParts = { {part = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,10605,10185,10500}), probability = 10}, {part = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8820,11655,11970,12075,11655}), probability = 20}, {part = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,12285,11445,10185,11550,11655,11025,10500,8610,11655,11655,12180,8400,10185,11970,12180}), probability = 5}, {part = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8610,11025,10815,10920,12180,8925,11760,11760,10605,11970,6825,11970,11445}), probability = 15}, {part = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8610,11025,10815,10920,12180,7980,11655,12495,10605,11970,6825,11970,11445}), probability = 10}, {part = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7980,10605,10710,12180,8925,11760,11760,10605,11970,6825,11970,11445}), probability = 15}, {part = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7980,10605,10710,12180,7980,11655,12495,10605,11970,6825,11970,11445}), probability = 10}, {part = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8610,11025,10815,10920,12180,8925,11760,11760,10605,11970,7980,10605,10815}), probability = 5}, {part = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8610,11025,10815,10920,12180,7980,11655,12495,10605,11970,7980,10605,10815}), probability = 5}, {part = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7980,10605,10710,12180,8925,11760,11760,10605,11970,7980,10605,10815}), probability = 5}, {part = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7980,10605,10710,12180,7980,11655,12495,10605,11970,7980,10605,10815}), probability = 5}, {part = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7980,10605,10710,12180,7350,11655,11655,12180}), probability = 5}, {part = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8610,11025,10815,10920,12180,7350,11655,11655,12180}), probability = 5} }
local totalProbability = 0
for _, bodyPartInfo in ipairs(bodyParts) do
	totalProbability = totalProbability + bodyPartInfo.probability
end
local randomNum = math.random(1, totalProbability)
local selectedPart
local accumulatedProbability = 0
for _, bodyPartInfo in ipairs(bodyParts) do
	accumulatedProbability = accumulatedProbability + bodyPartInfo.probability
	if randomNum <= accumulatedProbability then
		selectedPart = bodyPartInfo.part
		break
	end
end
if math.random(0, 100) <= HBO2H then
	if HBO2P == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,10605,10185,10500}) then
		args[6] = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,10605,10185,10500})
	elseif HBO2P == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,12285,11445,10185,11550,11655,11025,10500,8610,11655,11655,12180,8400,10185,11970,12180}) then
		args[6] = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,12285,11445,10185,11550,11655,11025,10500,8610,11655,11655,12180,8400,10185,11970,12180})
	elseif HBO2P == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8820,11655,11970,12075,11655}) then
		args[6] = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8820,11655,11970,12075,11655})
	elseif HBO2P == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8610,10185,11550,10500,11655,11445}) then
		args[6] = selectedPart
	end
end
end
return old(unpack(args))
end
end)()

local TrashTalkTabBox = Tabs.Misc:AddLeftTabbox(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({12180,11970,10185,12075,10920,3360,12180,10185,11340,11235}))
local TrashTalkTab = TrashTalkTabBox:AddTab(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({12180,11970,10185,12075,10920,3360,12180,10185,11340,11235}))

--* Trash Talk *--

local Trashtalk = false
local Chats = {
[daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({12075,11235,10185,10710,10710,10710})] = {daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({12075,11655,11970,11970,12705,3360,10290,11970,12285,10920,3360,12075,11235,10185,10710,10710,10710,3360,11655,12495,11550,12075,3360,12285,3360,10710,11970})};
}

local _Network = getrenv()._G.modules.Network
local _SendCodes = getrenv()._G.modules.Network.SendCodes
game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7980,11655,10815,8715,10605,11970,12390,11025,10395,10605})).MessageOut:Connect(function(message)
local extractedName = message:match(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({4725,6510,4200,9555,3885,12495,9975,9765,4515,4305}))
local initialHealth, finalHealth = message:match(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({4200,3885,4725,6615,3885,10500,4515,3885,4830,6615,3885,10500,4410,4305,3885,7140,4410,4725,6510,4200,3885,4725,6615,3885,10500,4515,3885,4830,6615,3885,10500,4410,4305,10920,11760}))
local studsValue = message:match(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({4200,3885,10500,4515,3885,4830,6615,3885,10500,4410,4305,12075}))
if Trashtalk and extractedName and initialHealth and finalHealth and studsValue and extractedName ~= game.Players.LocalPlayer.Name then
if Trashtalk and tonumber(finalHealth) <= 0 then
  _Network.Send(_SendCodes.SEND_CHAT_MESSAGE, extractedName .. daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({3360,11235,11025,11340,11340,10605,10500,3360,10710,11970,11655,11445,3360}) .. studsValue .. daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11445,4620,3360}) .. Chats[daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({12075,11235,10185,10710,10710,10710})][math.random(1, #Chats[daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({12075,11235,10185,10710,10710,10710})])] .. daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({3360,13020,3360,12075,11235,10185,10710,10710,10710,3360,11655,11550,3360,12180,11655,11760}), daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7455,11340,11655,10290,10185,11340}))
end
end
end)

local enabledspamchat = false
local chatSpammerText = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({})
local WaitTime = 3
local function spamChat()
local args = {[1] = 27, [2] = chatSpammerText, [3] = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7455,11340,11655,10290,10185,11340})}
while enabledspamchat do
  game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8400,11340,10185,12705,10605,11970,12075})).LocalPlayer.RemoteEvent:FireServer(unpack(args))
  wait(WaitTime)
end
end

TrashTalkTab:AddToggle(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7245,11550,10185,10290,11340,10605,10500,9975,8820,11655,10815,10815,11340,10605,5145}), {Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10605,11550,10185,10290,11340,10605,10500}), Default = false}):OnChanged(function(value)
Trashtalk = value
enabledspamchat = value
end)

TrashTalkTab:AddDropdown(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({}), {Values = { daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8190,11655,11550,10605}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8820,11970,10185,12075,10920,3360,8820,10185,11340,11235}), daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7035,10920,10185,12180,3360,8715,11760,10185,11445,11445,10605,11970}) }, Default = 1, Multi = false, Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({12180,12705,11760,10605,6090})}):OnChanged(function(bool2)
if bool2 == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8190,11655,11550,10605}) then
Trashtalk = false
enabledspamchat = false
elseif bool2 == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8820,11970,10185,12075,10920,3360,8820,10185,11340,11235}) then
Trashtalk = true
elseif bool2 == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7035,10920,10185,12180,3360,8715,11760,10185,11445,11445,10605,11970}) then
spamChat()
end
end)

TrashTalkTab:AddSlider(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8715,11760,10185,11445,7035,10920,10185,12180,8715,11760,10605,10605,10500}), {Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({12075,11760,10605,10605,10500,6090}),Suffix = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({12075}), Default = 3, Min = 1, Max = 10, Rounding = 0, Compact = false,}):OnChanged(function(SpamChatSpeedValue)
WaitTime = SpamChatSpeedValue
end)

TrashTalkTab:AddInput(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7035,10920,10185,12180,8715,11760,10185,11445,11445,10605,11970}), {Default = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7665,3360,8295,9135,8190,3360,8820,7560,7665,8715,3360,8715,7245,8610,9030,7245,8610,4830}), Numeric = false, Finished = true, Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10395,10920,10185,12180,3360,12075,11760,10185,11445,11445,10605,11970,6090}), Placeholder = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7035,10920,10185,12180,3360,8715,11760,10185,11445,3360,7035,12285,12075,12180,11655,11445,3360,8820,10605,12600,12180,3360,9555,7560,7245,8610,7245,9765})}):OnChanged(function(value)
chatSpammerText = value
end)

local KillAuraTabBox = Tabs.Combat:AddRightTabbox(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11235,11025,11340,11340,3360,10185,12285,11970,10185}))
local KillAuraTab = KillAuraTabBox:AddTab(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11235,11025,11340,11340,3360,10185,12285,11970,10185}))

--* Kill Aura *--

function Functions:GetLocalToolName()
  if getrenv()._G.modules.FPS.GetEquippedItem() == nil then return 0,0 end
  local mod = require(game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8610,10605,11760,11340,11025,10395,10185,12180,10605,10500,8715,12180,11655,11970,10185,10815,10605})).ItemConfigs[getrenv()._G.modules.FPS.GetEquippedItem().id])
  for i,v in pairs(mod) do
    if i == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,10185,11550,10500,8085,11655,10500,10605,11340}) then
      return mod.HandModel
    end
  end
  return 0,0
end
local killauradistance = 8
local function GetPlayer()
  local closest,PlayerDistance,playerTable = nil,math.huge,nil
  for i,v in pairs(getupvalues(getrenv()._G.modules.Player.GetPlayerModel)[1]) do
    if v.model:FindFirstChild(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,12285,11445,10185,11550,11655,11025,10500,8610,11655,11655,12180,8400,10185,11970,12180})) then
      local Mouse = game.Players.LocalPlayer:GetMouse()
      local pos,OnScreen = Camera.WorldToViewportPoint(Camera, v.model:GetPivot().Position)
      local PlayerDistance = (CharcaterMiddle:GetPivot().Position-v.model:GetPivot().Position).Magnitude
      Distance = (game.Workspace.Ignore.LocalCharacter.Middle.Position - v.model:GetPivot().Position).Magnitude
      if PlayerDistance <= killauradistance and OnScreen == true then
        closest = v.model;PlayerDistance = PlayerDistance;playerTable=v
      end
    end
  end
  return closest,playerTable
end

local KAHitPartSelected = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,10605,10185,10500})
local Wait = 0.95
local AuraGoodToUse = false
KillAuraTab:AddToggle(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7875,11025,11340,11340,6825,12285,11970,10185}),{Text=daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11235,11025,11340,11340,3360,10185,12285,11970,10185}),Default=false}):AddKeyPicker(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7875,11025,11340,11340,6825,12285,11970,10185,7875,10605,12705}), {Default=daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8190,11655,11550}),SyncToggleState=true,Mode=daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8820,11655,10815,10815,11340,10605}),Text=daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7875,11025,11340,11340,3360,6825,12285,11970,10185}),NoUI=false})
local PlayerID = nil
local Bypass; Bypass = hookfunction(game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8400,11340,10185,12705,10605,11970,12075})).LocalPlayer:FindFirstChild(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8610,10605,11445,11655,12180,10605,7245,12390,10605,11550,12180})).FireServer,function(self, ...)
local args = {...}
if args[1] == 10 and args[2] == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,11025,12180}) then
  PlayerID = args[3]
end
return Bypass(self, unpack(args))
end)
task.spawn(function()
while task.wait() do
  local state = Options.KillAuraKey:GetState()
  if state then
    local PlayerHumanoid,fr = GetPlayer()
    if PlayerHumanoid and AuraGoodToUse and PlayerHumanoid ~= nil and fr ~= nil then
      game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8400,11340,10185,12705,10605,11970,12075})).LocalPlayer.RemoteEvent:FireServer(10, daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8715,12495,11025,11550,10815}))
      game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8400,11340,10185,12705,10605,11970,12075})).LocalPlayer.RemoteEvent:FireServer(10, daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,11025,12180}), fr.id, PlayerHumanoid.HumanoidRootPart.Position, KAHitPartSelected, Vector3.new(-0.1275634765625, 0.5433349609375, -0.237548828125))
      wait(Wait)
    end
  end
end
end)
task.spawn(function()
while task.wait() do
  local Weapon = Functions:GetLocalToolName()
  if Weapon == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8085,11025,11550,11025,11550,10815,7140,11970,11025,11340,11340}) then
    Wait = 0.12
  else
    Wait = 0.95
  end
  if Weapon == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,10185,11445,11445,10605,11970}) or daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7035,11970,11655,12495,10290,10185,11970}) or daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8715,12180,11655,11550,10605,7560,10185,11445,11445,10605,11970}) or daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8715,12180,10605,10605,11340,7560,10185,11445,11445,10605,11970}) or daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8085,11025,11550,11025,11550,10815,7140,11970,11025,11340,11340}) or daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7665,11970,11655,11550,7560,10185,11445,11445,10605,11970}) then
    AuraGoodToUse = true
  else
    AuraGoodToUse = false
  end
end
end)

KillAuraTab:AddSlider(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({}), {Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10500,11025,12075,12180,10185,11550,10395,10605,6090}), Default = 8, Min = 5, Max = 10, Rounding = 0, Suffix = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({3360,12075,12180,12285,10500,12075}), Compact = false}):OnChanged(function(Value)
killauradistance = Value
end)

KillAuraTab:AddDropdown(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({}), {Values = {daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,10605,10185,10500}), daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,12285,11445,10185,11550,11655,11025,10500,8610,11655,11655,12180,8400,10185,11970,12180}), daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8820,11655,11970,12075,11655}), daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7980,11655,12495,10605,11970,8820,11655,11970,12075,11655}), daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8610,11025,10815,10920,12180,7560,10185,11550,10500}), daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7980,10605,10710,12180,7560,10185,11550,10500}), daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8610,11025,10815,10920,12180,7350,11655,11655,12180}), daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7980,10605,10710,12180,7350,11655,11655,12180})}, Default = 1, Multi = false, Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10920,11025,12180,11760,10185,11970,12180,6090})}):OnChanged(function(Value)
KAHitPartSelected = Value
end)


--* Crosshair *--

local CrossHairX = Drawing.new(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7035,11025,11970,10395,11340,10605})), Drawing.new(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7035,11025,11970,10395,11340,10605}))
--
CrossHairX.Position = Vector2.new(Camera.ViewportSize.X / 2, Camera.ViewportSize.Y / 2)
CrossHairX.Thickness = 1
CrossHairX.ZIndex = 3

do
  ComExtraTab:AddToggle(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({12810,7035,11970,11655,12075,12075,10920,10185,11025,11970,9240,9975,8820,11655,10815,10815,11340,10605}), {Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10605,11550,10185,10290,11340,10605,10500}), Default = false}):AddColorPicker(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10605,7035,11970,11655,12075,12075,10920,10185,11025,11970,9240,9975,7035,11655,11340,11655,11970}), {Default = Color3.fromRGB(208, 123, 255)}):OnChanged(function()
  CrossHairX.Visible = Toggles.zCrosshairX_Toggle.Value
  end)

  Options.eCrosshairX_Color:OnChanged(function()
  CrossHairX.Color = Options.eCrosshairX_Color.Value
  end)

  ComExtraTab:AddToggle(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7035,11970,11655,12075,12075,10920,10185,11025,11970,9975,7350,11025,11340,11340,10605,10500,5145}), {Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10710,11025,11340,11340,10605,10500}), Default = false}):OnChanged(function()
  CrossHairX.Filled = Toggles.Crosshair_Filled1.Value
  end)

  ComExtraTab:AddSlider(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7035,11970,11655,12075,12075,10920,10185,11025,11970,9975,8610,10185,10500,11025,12285,12075}), {Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({12075,11025,12810,10605}), Suffix = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({20370,18480}), Default = 2, Min = 0, Max = 100, Rounding = 0, Compact = true}):OnChanged(function(CrosshairXRadius)
  CrossHairX.Radius = CrosshairXRadius
  end)
end

local CustomHitsoundsTabBox = Tabs.Misc:AddRightTabbox(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10395,12285,12075,12180,11655,11445,3360,10920,11025,12180,12075,11655,12285,11550,10500,12075}))
local PlayerHitsoundsTab = CustomHitsoundsTabBox:AddTab(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10395,12285,12075,12180,11655,11445,3360,10920,11025,12180,12075,11655,12285,11550,10500,12075}))

--* Player Hitsounds *--

SoundService.PlayerHitHeadshot.Volume = 5
SoundService.PlayerHitHeadshot.Pitch = 1
SoundService.PlayerHitHeadshot.EqualizerSoundEffect.HighGain = -1.5
local sounds = {[daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7140,10605,10710,12285,10185,11340,12180,3360,7560,10605,10185,10500,12075,10920,11655,12180})] = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11970,10290,12600,10185,12075,12075,10605,12180,11025,10500,6090,4935,4935,5985,5145,5145,5985,5565,5670,5145,5040,5460,5670}),[daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7140,10605,10710,12285,10185,11340,12180,3360,6930,11655,10500,12705})] = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11970,10290,12600,10185,12075,12075,10605,12180,11025,10500,6090,4935,4935,5985,5145,5145,5460,5460,5880,5775,5355,5670,5985}),Neverlose = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11970,10290,12600,10185,12075,12075,10605,12180,11025,10500,6090,4935,4935,5880,5775,5250,5670,5880,5880,5145,5145,5145,5670}),Gamesense = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11970,10290,12600,10185,12075,12075,10605,12180,11025,10500,6090,4935,4935,5460,5880,5145,5775,5880,5040,5985,5145,5880,5880}),One = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11970,10290,12600,10185,12075,12075,10605,12180,11025,10500,6090,4935,4935,5775,5355,5880,5040,5565,5040,5250,5355,5460,5565}),Bell = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11970,10290,12600,10185,12075,12075,10605,12180,11025,10500,6090,4935,4935,5670,5565,5355,5460,5985,5460,5775,5250,5460,5040}),Rust = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11970,10290,12600,10185,12075,12075,10605,12180,11025,10500,6090,4935,4935,5145,5250,5565,5565,5040,5460,5040,5460,5670,5250}),TF2 = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11970,10290,12600,10185,12075,12075,10605,12180,11025,10500,6090,4935,4935,5250,5880,5670,5880,5355,5355,5145,5670,5880,5460}),Slime = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11970,10290,12600,10185,12075,12075,10605,12180,11025,10500,6090,4935,4935,5670,5985,5145,5670,5355,5775,5145,5880,5040,5355}),[daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({6825,11445,11655,11550,10815,3360,8925,12075})] = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11970,10290,12600,10185,12075,12075,10605,12180,11025,10500,6090,4935,4935,5565,5775,5040,5040,5145,5880,5355,5670,5250,5670}),Minecraft = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11970,10290,12600,10185,12075,12075,10605,12180,11025,10500,6090,4935,4935,5460,5040,5145,5880,5670,5145,5670,5880,5565,5040}),[daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7035,8715,6090,7455,8295})] = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11970,10290,12600,10185,12075,12075,10605,12180,11025,10500,6090,4935,4935,5670,5985,5355,5775,5355,5565,5355,5670,5985,5145}),Saber = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11970,10290,12600,10185,12075,12075,10605,12180,11025,10500,6090,4935,4935,5880,5460,5145,5565,5670,5775,5880,5880,5145,5355}),Baimware = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11970,10290,12600,10185,12075,12075,10605,12180,11025,10500,6090,4935,4935,5355,5145,5250,5460,5355,5355,5145,5880,5250,5040}),Osu = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11970,10290,12600,10185,12075,12075,10605,12180,11025,10500,6090,4935,4935,5775,5145,5460,5985,5250,5565,5565,5565,5565,5145}),[daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8820,7350,5250,3360,7035,11970,11025,12180,11025,10395,10185,11340})] = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11970,10290,12600,10185,12075,12075,10605,12180,11025,10500,6090,4935,4935,5250,5985,5670,5145,5040,5250,5775,5355,5460}),Bat = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11970,10290,12600,10185,12075,12075,10605,12180,11025,10500,6090,4935,4935,5355,5355,5355,5355,5985,5040,5775,5355,5460,5775}),[daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7035,10185,11340,11340,3360,11655,10710,3360,7140,12285,12180,12705})] = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11970,10290,12600,10185,12075,12075,10605,12180,11025,10500,6090,4935,4935,5565,5985,5565,5250,5145,5250,5040,5355,5040,5145}),Bubble = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11970,10290,12600,10185,12075,12075,10605,12180,11025,10500,6090,4935,4935,5670,5565,5355,5460,5985,5460,5775,5565,5880,5880}),Pick = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11970,10290,12600,10185,12075,12075,10605,12180,11025,10500,6090,4935,4935,5145,5355,5460,5775,5145,5460,5040,5040,5250,5775}),Pop = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11970,10290,12600,10185,12075,12075,10605,12180,11025,10500,6090,4935,4935,5145,5985,5880,5565,5985,5880,5775,5985,5355}),Bruh = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11970,10290,12600,10185,12075,12075,10605,12180,11025,10500,6090,4935,4935,5460,5250,5775,5565,5880,5460,5250,5565,5775,5460}),Bamboo = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11970,10290,12600,10185,12075,12075,10605,12180,11025,10500,6090,4935,4935,5355,5775,5670,5985,5460,5355,5460,5565,5145,5985}),Crowbar = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11970,10290,12600,10185,12075,12075,10605,12180,11025,10500,6090,4935,4935,5565,5460,5670,5460,5145,5040,5460,5880,5145}),Weeb = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11970,10290,12600,10185,12075,12075,10605,12180,11025,10500,6090,4935,4935,5670,5460,5460,5250,5985,5670,5565,5040,5145,5670}),Beep = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11970,10290,12600,10185,12075,12075,10605,12180,11025,10500,6090,4935,4935,5880,5145,5775,5775,5250,5565,5670,5040,5145,5565}),Bambi = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11970,10290,12600,10185,12075,12075,10605,12180,11025,10500,6090,4935,4935,5880,5460,5355,5775,5250,5040,5355,5880,5250,5145}),Stone = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11970,10290,12600,10185,12075,12075,10605,12180,11025,10500,6090,4935,4935,5355,5565,5880,5145,5355,5880,5355,5460,5040,5880}),[daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8295,11340,10500,3360,7350,10185,12180,10185,11340,11025,12180,12705})] = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11970,10290,12600,10185,12075,12075,10605,12180,11025,10500,6090,4935,4935,5670,5670,5040,5775,5145,5460,5250,5040,5355,5670}),Click = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11970,10290,12600,10185,12075,12075,10605,12180,11025,10500,6090,4935,4935,5880,5040,5565,5355,5775,5040,5460,5460,5355,5775}),Ding = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11970,10290,12600,10185,12075,12075,10605,12180,11025,10500,6090,4935,4935,5775,5145,5460,5985,5565,5145,5670,5985,5985,5460}),Snow = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11970,10290,12600,10185,12075,12075,10605,12180,11025,10500,6090,4935,4935,5670,5460,5565,5565,5565,5250,5775,5670,5355,5250}),Laser = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11970,10290,12600,10185,12075,12075,10605,12180,11025,10500,6090,4935,4935,5775,5880,5355,5775,5460,5670,5145,5355,5355,5145}),Mario = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11970,10290,12600,10185,12075,12075,10605,12180,11025,10500,6090,4935,4935,5250,5880,5145,5565,5250,5040,5775,5985,5880,5145}),Steve = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11970,10290,12600,10185,12075,12075,10605,12180,11025,10500,6090,4935,4935,5460,5985,5670,5565,5040,5880,5355,5985,5985,5775})}

PlayerHitsoundsTab:AddToggle(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7245,11550,10185,10290,11340,10605,10500,9975,8820,11655,10815,10815,11340,10605,5145}), {Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10605,11550,10185,10290,11340,10605,10500}), Default = false})

PlayerHitsoundsTab:AddDropdown(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,10605,10185,10500,12075,10920,11655,12180,7560,11025,12180}), {Values = { daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7140,10605,10710,12285,10185,11340,12180,3360,7560,10605,10185,10500,12075,10920,11655,12180}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8190,10605,12390,10605,11970,11340,11655,12075,10605}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7455,10185,11445,10605,12075,10605,11550,12075,10605}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8295,11550,10605}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({6930,10605,11340,11340}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8610,12285,12075,12180}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8820,7350,5250}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8715,11340,11025,11445,10605}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({6825,11445,11655,11550,10815,3360,8925,12075}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8085,11025,11550,10605,10395,11970,10185,10710,12180}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7035,8715,6090,7455,8295}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8715,10185,10290,10605,11970}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({6930,10185,11025,11445,12495,10185,11970,10605}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8295,12075,12285}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8820,7350,5250,3360,7035,11970,11025,12180,11025,10395,10185,11340}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({6930,10185,12180}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7035,10185,11340,11340,3360,11655,10710,3360,7140,12285,12180,12705}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({6930,12285,10290,10290,11340,10605}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8400,11025,10395,11235}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8400,11655,11760}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({6930,11970,12285,10920}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({6930,10185,11445,10290,11655,11655}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7035,11970,11655,12495,10290,10185,11970}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9135,10605,10605,10290}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({6930,10605,10605,11760}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({6930,10185,11445,10290,11025}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8715,12180,11655,11550,10605}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8295,11340,10500,3360,7350,10185,12180,10185,11340,11025,12180,12705}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7035,11340,11025,10395,11235}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7140,11025,11550,10815}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8715,11550,11655,12495}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7980,10185,12075,10605,11970}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8085,10185,11970,11025,11655}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8715,12180,10605,12390,10605}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8715,11550,11655,12495,10500,11970,10185,11235,10605}) },Default = 1, Multi = false, Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,10605,10185,10500,3360,7560,11025,12180,12075,11655,12285,11550,10500,6090})})
Options.HeadshotHit:OnChanged(function()
local soundId = sounds[Options.HeadshotHit.Value]
game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8715,11655,12285,11550,10500,8715,10605,11970,12390,11025,10395,10605})).PlayerHitHeadshot.SoundId = soundId
game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8715,11655,12285,11550,10500,8715,10605,11970,12390,11025,10395,10605})).PlayerHitHeadshot.Playing = true
end)

PlayerHitsoundsTab:AddSlider(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9030,11655,11340,12285,11445,10605,9975,8715,11340,11025,10500,10605,11970}), {Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({12390,11655,11340,12285,11445,10605}), Default = 5, Min = 0, Max = 10, Rounding = 0, Compact = true,}):OnChanged(function(vol)
SoundService.PlayerHitHeadshot.Volume = vol
end)

PlayerHitsoundsTab:AddSlider(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8400,11025,12180,10395,10920,9975,8715,11340,11025,10500,10605,11970}), {Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11760,11025,12180,10395,10920}), Default = 1, Min = 0, Max = 2, Rounding = 2, Compact = true,}):OnChanged(function(pich)
SoundService.PlayerHitHeadshot.Pitch = pich
end)

PlayerHitsoundsTab:AddInput(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,10605,10185,10500,8715,10920,11655,12180,7560,11025,12180,6825,12075,12075,10605,12180,7665,7140}), {Default = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11970,10290,12600,10185,12075,12075,10605,12180,11025,10500,6090,4935,4935,5985,5145,5145,5985,5565,5670,5145,5040,5460,5670}),Numeric = false,Finished = true,Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10395,12285,12075,12180,11655,11445,3360,12075,11655,12285,11550,10500,6090}),Placeholder = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11970,10290,12600,10185,12075,12075,10605,12180,11025,10500,6090,4935,4935,5985,5145,5145,5985,5565,5670,5145,5040,5460,5670}),}):OnChanged(function(CustomSoundID)
SoundService.PlayerHitHeadshot.SoundId = CustomSoundID
end)
--
PlayerHitsoundsTab:AddToggle(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7245,11550,10185,10290,11340,10605,10500,9975,8820,11655,10815,10815,11340,10605,5250}), {Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10605,11550,10185,10290,11340,10605,10500}), Default = false})

PlayerHitsoundsTab:AddDropdown(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560,11025,12180}), {Values = { daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7140,10605,10710,12285,10185,11340,12180,3360,6930,11655,10500,12705}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8190,10605,12390,10605,11970,11340,11655,12075,10605}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7455,10185,11445,10605,12075,10605,11550,12075,10605}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8295,11550,10605}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({6930,10605,11340,11340}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8610,12285,12075,12180}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8820,7350,5250}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8715,11340,11025,11445,10605}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({6825,11445,11655,11550,10815,3360,8925,12075}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8085,11025,11550,10605,10395,11970,10185,10710,12180}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7035,8715,6090,7455,8295}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8715,10185,10290,10605,11970}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({6930,10185,11025,11445,12495,10185,11970,10605}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8295,12075,12285}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8820,7350,5250,3360,7035,11970,11025,12180,11025,10395,10185,11340}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({6930,10185,12180}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7035,10185,11340,11340,3360,11655,10710,3360,7140,12285,12180,12705}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({6930,12285,10290,10290,11340,10605}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8400,11025,10395,11235}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8400,11655,11760}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({6930,11970,12285,10920}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({6930,10185,11445,10290,11655,11655}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7035,11970,11655,12495,10290,10185,11970}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9135,10605,10605,10290}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({6930,10605,10605,11760}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({6930,10185,11445,10290,11025}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8715,12180,11655,11550,10605}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8295,11340,10500,3360,7350,10185,12180,10185,11340,11025,12180,12705}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7035,11340,11025,10395,11235}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7140,11025,11550,10815}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8715,11550,11655,12495}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7980,10185,12075,10605,11970}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8085,10185,11970,11025,11655}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8715,12180,10605,12390,10605}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8715,11550,11655,12495,10500,11970,10185,11235,10605}) },Default = 1, Multi = false, Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({6930,11655,10500,12705,3360,7560,11025,12180,12075,11655,12285,11550,10500,6090})})
Options.Hit:OnChanged(function()
local soundId = sounds[Options.Hit.Value]
game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8715,11655,12285,11550,10500,8715,10605,11970,12390,11025,10395,10605})).PlayerHit2.SoundId = soundId
game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8715,11655,12285,11550,10500,8715,10605,11970,12390,11025,10395,10605})).PlayerHit2.Playing = true
end)

PlayerHitsoundsTab:AddSlider(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9030,11655,11340,12285,11445,10605,9975,8715,11340,11025,10500,10605,11970}), {Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({12390,11655,11340,12285,11445,10605}), Default = 5, Min = 0, Max = 10, Rounding = 0, Compact = true,}):OnChanged(function(vole)
SoundService.PlayerHit2.Volume = vole
end)

PlayerHitsoundsTab:AddSlider(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8400,11025,12180,10395,10920,9975,8715,11340,11025,10500,10605,11970}), {Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11760,11025,12180,10395,10920}), Default = 1, Min = 0, Max = 2, Rounding = 2, Compact = true,}):OnChanged(function(piche)
SoundService.PlayerHit2.Pitch = piche
end)

PlayerHitsoundsTab:AddInput(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8400,11340,10185,12705,10605,11970,7560,11025,12180,6825,12075,12075,10605,12180,7665,7140}), {Default = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11970,10290,12600,10185,12075,12075,10605,12180,11025,10500,6090,4935,4935,5985,5145,5145,5460,5460,5880,5775,5355,5670,5985}),Numeric = false,Finished = true,Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10395,12285,12075,12180,11655,11445,3360,12075,11655,12285,11550,10500,6090}),Placeholder = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11970,10290,12600,10185,12075,12075,10605,12180,11025,10500,6090,4935,4935,5985,5145,5145,5460,5460,5880,5775,5355,5670,5985}),}):OnChanged(function(CustomSoundID)
SoundService.PlayerHit2.SoundId = CustomSoundID
end)

local GravityTabBox = Tabs.Misc:AddRightTabbox(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10815,11970,10185,12390,11025,12180,12705}))
local GravityTab = GravityTabBox:AddTab(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10815,11970,10185,12390,11025,12180,12705}))

--* Gravity *--

local GravityEnabled = false
local defaultGravity = 75
local CurrentSliderValue2 = 75

GravityTab:AddToggle(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7455,11970,10185,12390,11025,12180,12705}), {Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10605,11550,10185,10290,11340,10605,10500}), Default = false, Tooltip}):AddKeyPicker(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7455,11970,10185,12390,11025,12180,12705,7875,10605,12705}), {Default = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8190,11655,11550}), SyncToggleState = true, Mode = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8820,11655,10815,10815,11340,10605}), Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7455,11970,10185,12390,11025,12180,12705}), NoUI = true}):OnChanged(function(value)
GravityEnabled = value
if not GravityEnabled then
sethiddenproperty(game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9135,11655,11970,11235,12075,11760,10185,10395,10605})), daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7455,11970,10185,12390,11025,12180,12705}), defaultGravity)
else
sethiddenproperty(game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9135,11655,11970,11235,12075,11760,10185,10395,10605})), daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7455,11970,10185,12390,11025,12180,12705}), CurrentSliderValue2)
end
end)

GravityTab:AddSlider(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7455,11970,10185,12390,11025,12180,12705,7035,10920,10185,11550,10815,10605,11970,8715,11340,11025,10500,10605,11970}), {Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10815,11970,10185,12390,11025,12180,12705,6090}), Suffix = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({12600}), Default = defaultGravity, Min = 60, Max = 100, Rounding = 0, Compact = false}):OnChanged(function(Value)
CurrentSliderValue2 = Value
if GravityEnabled then
sethiddenproperty(game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9135,11655,11970,11235,12075,11760,10185,10395,10605})), daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7455,11970,10185,12390,11025,12180,12705}), Value)
end
end)


local qf = {
Settings = {
  SpeedHackEnabled = false,
  SpeedHackSpeed = 30,
}
}

ExploitsTab:AddToggle(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8715,11760,10605,10605,10500,7560,10185,10395,11235}), { Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({12075,11760,10605,10605,10500,10920,10185,10395,11235}), Default = false }):AddKeyPicker(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8715,11760,10605,10605,10500,7560,10185,10395,11235,7875,10605,12705}),{ Default = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7560}), SyncToggleState = false, Mode = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8820,11655,10815,10815,11340,10605}), Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8715,11760,10605,10605,10500,3360,6930,11655,11655,12075,12180}), NoUI = false })
ExploitsTab:AddSlider(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8715,11760,10605,10605,10500,7560,10185,10395,11235,8715,11760,10605,10605,10500}), { Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({12075,11760,10605,10605,10500,6090}), Suffix = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({3885}),Default = 17, Min = 1, Max = 34, Rounding = 0,Compact = false}):OnChanged(function(G) qf.Settings.SpeedHackSpeed = G; end)
Toggles.SpeedHack:OnChanged(function(G)
qf.Settings.SpeedHackEnabled = G
end)
local nT, OT, JT = true, false, false;
game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8610,12285,11550,8715,10605,11970,12390,11025,10395,10605})).RenderStepped:Connect(function(G)
if qf.Settings.SpeedHackEnabled == true and OT == true then
for w, m in pairs(game.Workspace.Ignore.LocalCharacter:GetChildren()) do
  m.CFrame = m.CFrame + game.Workspace.CurrentCamera.CFrame.LookVector * qf.Settings.SpeedHackSpeed * G
end
end
end)
game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8925,12075,10605,11970,7665,11550,11760,12285,12180,8715,10605,11970,12390,11025,10395,10605})).InputBegan:Connect(function(G)
if Options.SpeedHackKey:GetState() == true then
if nT == true then
  nT, JT = false, true
elseif nT == false then
  nT, JT = true, false
end
end
end)
game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8925,12075,10605,11970,7665,11550,11760,12285,12180,8715,10605,11970,12390,11025,10395,10605})).InputBegan:Connect(function(G)
if G.KeyCode == Enum.KeyCode.C and JT then
OT = true
end
end)
game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8925,12075,10605,11970,7665,11550,11760,12285,12180,8715,10605,11970,12390,11025,10395,10605})).InputEnded:Connect(function(G)
if G.KeyCode == Enum.KeyCode.C then
OT = false
end
end)

local CustomViewmodelTabBox = Tabs.Visual:AddLeftTabbox(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10395,12285,12075,12180,11655,11445,3360,12390,11025,10605,12495,11445,11655,10500,10605,11340}))
local CustomViewmodelTab = CustomViewmodelTabBox:AddTab(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10395,12285,12075,12180,11655,11445,3360,12390,11025,10605,12495,11445,11655,10500,10605,11340}))

--* Custom Viewmodel *--

local ViewmodelEnabled = false
local ViewmodelPos = Vector3.new(0, 0, 0)
LPH_NO_VIRTUALIZE(function()
local newindex
newindex = hookmetamethod(game, daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9975,9975,11550,10605,12495,11025,11550,10500,10605,12600}), function(obj, idx, val)
if obj == workspace.CurrentCamera and idx == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7035,7350,11970,10185,11445,10605}) and ViewmodelEnabled then
val = val + (val.LookVector * ViewmodelPos.Z) + (val.RightVector * ViewmodelPos.X) + (val.UpVector * ViewmodelPos.Y)
end
return newindex(obj, idx, val)
end)
end)()

CustomViewmodelTab:AddToggle(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9030,11025,10605,12495,11445,11655,10500,10605,11340,7245,11550,10185,10290,11340,10605,10500}), {Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10605,11550,10185,10290,11340,10605,10500}), Default = ViewmodelEnabled}):OnChanged(function(Toggle)
ViewmodelEnabled = Toggle
end)

CustomViewmodelTab:AddSlider(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9030,11025,10605,12495,11445,11655,10500,10605,11340,9240}), {Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({12600,4725,11655,10710,10710,12075,10605,12180,6090}), Default = 0, Min = -5, Max = 5, Rounding = 2, Compact = false}):OnChanged(function(Slider)
ViewmodelPos = Vector3.new(Slider, ViewmodelPos.Y, ViewmodelPos.Z)
end)

CustomViewmodelTab:AddSlider(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9030,11025,10605,12495,11445,11655,10500,10605,11340,9345}), {Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({12705,4725,11655,10710,10710,12075,10605,12180,6090}), Default = 0, Min = -5, Max = 5, Rounding = 2, Compact = false}):OnChanged(function(Slider)
ViewmodelPos = Vector3.new(ViewmodelPos.X, Slider, ViewmodelPos.Z)
end)

CustomViewmodelTab:AddSlider(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9030,11025,10605,12495,11445,11655,10500,10605,11340,9450}), {Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({12810,4725,11655,10710,10710,12075,10605,12180,6090}), Default = 0, Min = -5, Max = 5, Rounding = 2, Compact = false}):OnChanged(function(Slider)
ViewmodelPos = Vector3.new(ViewmodelPos.X, ViewmodelPos.Y, Slider)
end)

--
local CustomCharTabBox = Tabs.Visual:AddLeftTabbox(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10395,12285,12075,12180,11655,11445,3360,10395,10920,10185,11970,10185,10395,12180,10605,11970}))
local CustomCharTab = CustomCharTabBox:AddTab(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10395,12285,12075,12180,11655,11445,3360,10395,10920,10185,11970,10185,10395,12180,10605,11970}))

--* custom character *--

local function CreateCustomCharacter(Mesh, Texture, Size)
local part = Instance.new(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8400,10185,11970,12180}), workspace)
part.CFrame = workspace.Ignore.FPSArms.HumanoidRootPart.CFrame
part.CanCollide = false
part.Name = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7140,10605,11340,10605,12180,10605,8085,10605,7350,11655,11970,8190,11655,11550,10605})
local mesh = Instance.new(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8715,11760,10605,10395,11025,10185,11340,8085,10605,12075,10920}), part)
mesh.MeshType = Enum.MeshType.FileMesh
mesh.Scale = Size
mesh.TextureId = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10920,12180,12180,11760,6090,4935,4935,12495,12495,12495,4830,11970,11655,10290,11340,11655,12600,4830,10395,11655,11445,4935,10185,12075,12075,10605,12180,4935,6615,11025,10500,6405}) .. Texture
mesh.MeshId = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10920,12180,12180,11760,6090,4935,4935,12495,12495,12495,4830,11970,11655,10290,11340,11655,12600,4830,10395,11655,11445,4935,10185,12075,12075,10605,12180,4935,6615,11025,10500,6405}) .. Mesh
local weld = Instance.new(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9135,10605,11340,10500}), mesh)
weld.Part0 = workspace.Ignore.FPSArms.HumanoidRootPart
weld.Part1 = part
end

local CharacterType = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({6825,11445,11655,11550,10815,8925,12075})
local CustomCharacter = false
local function UpdateCharacter()
for _, child in pairs(workspace:GetChildren()) do
if child.Name == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7140,10605,11340,10605,12180,10605,8085,10605,7350,11655,11970,8190,11655,11550,10605}) then
child:Destroy()
end
end
if not CustomCharacter then
return
end

local characterData = {AmongUs = { Mesh = 6686375902, Texture = 6686375937, Size = Vector3.new(0.16, 0.16, 0.16) },BuilderMan = { Mesh = 2711196756, Texture = 2711196829, Size = Vector3.new(1.2, 1.2, 1.2) },Minion = { Mesh = 12009037504, Texture = 12009037612, Size = Vector3.new(5, 4, 5) },LegoCloneTrooper = { Mesh = 9903790031, Texture = 9903790118, Size = Vector3.new(0.16, 0.16, 0.16) },AnimeGirl = { Mesh = 752599066, Texture = 752599541, Size = Vector3.new(0.7, 0.7, 0.7) }}
local character = characterData[CharacterType]
if character then
CreateCustomCharacter(character.Mesh, character.Texture, character.Size)
end
end
local function ToggleCustomCharacter(value)
CustomCharacter = value
UpdateCharacter()
end
local function ChangeCharacterType(value)
CharacterType = value
UpdateCharacter()
end

CustomCharTab:AddToggle(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7035,12285,12075,12180,11655,11445,7035,10920,10185,11970,10185,10395,12180,10605,11970}), { Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10605,11550,10185,10290,11340,10605,10500}), Default = false }):OnChanged(ToggleCustomCharacter)
CustomCharTab:AddDropdown(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7035,10920,10185,11970,10185,10395,12180,10605,11970}), { Values = { daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({6825,11445,11655,11550,10815,8925,12075}), daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({6930,12285,11025,11340,10500,10605,11970,8085,10185,11550}), daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8085,11025,11550,11025,11655,11550}), daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7980,10605,10815,11655,7035,11340,11655,11550,10605,8820,11970,11655,11655,11760,10605,11970}), daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({6825,11550,11025,11445,10605,7455,11025,11970,11340}) }, Default = 1, Multi = false, Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({12180,12705,11760,10605,6090}) }):OnChanged(ChangeCharacterType)

local ArmVisTabBox = Tabs.Misc:AddLeftTabbox(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10185,11970,11445,3360,12390,11025,12075,12285,10185,11340,12075}))
local ArmVisTab = ArmVisTabBox:AddTab(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11340,11655,10395,10185,11340,3360,10395,10920,10185,11445,12075}))

--* Local Chams *--

local Misc2 = {Settings = {LocalChams = false,LocalChamsColor = Color3.fromRGB(80, 77, 56),LocalChamsMaterial = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8715,11445,11655,11655,12180,10920,8400,11340,10185,12075,12180,11025,10395})}}
local DeafultArm = {}
for i,v in pairs(game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9135,11655,11970,11235,12075,11760,10185,10395,10605})).Ignore.FPSArms:GetChildren()) do
if v:IsA(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8085,10605,12075,10920,8400,10185,11970,12180})) then
  DeafultArm[v] = {Color=v.Color,Material=v.Material}
end
end
function Functions:ArmChams()
if Misc2.Settings.LocalChams == true then
  for i,v in pairs(game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9135,11655,11970,11235,12075,11760,10185,10395,10605})).Ignore.FPSArms:GetChildren()) do
    if v.ClassName == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8085,10605,12075,10920,8400,10185,11970,12180}) then
      v.Color=Misc2.Settings.LocalChamsColor
      v.Material=Enum.Material[Misc2.Settings.LocalChamsMaterial]
    end
  end
else
  for i,v in pairs(DeafultArm) do
    i.Color=v.Color;i.Material=v.Material
  end
end
end
for i,v in pairs(game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9135,11655,11970,11235,12075,11760,10185,10395,10605})).Ignore.FPSArms:GetChildren()) do
v.Changed:Connect(function(Change)
if Change ~= daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7035,7350,11970,10185,11445,10605}) then
  if Misc2.Settings.LocalChams == true then
    v.Color=Misc2.Settings.LocalChamsColor
    v.Material=Enum.Material[Misc2.Settings.LocalChamsMaterial]
  else
    for i,v in pairs(DeafultArm) do
      i.Color=v.Color;i.Material=v.Material
    end
  end
end
end)
end
game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9135,11655,11970,11235,12075,11760,10185,10395,10605})).Ignore.FPSArms.Changed:Connect(function()
Functions:ArmChams()
end)

ArmVisTab:AddToggle(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({6825,11970,11445,7035,10920,10185,11445,12075}),{Text=daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10605,11550,10185,10290,11340,10605,10500}),Default=false}):AddColorPicker(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({6825,11970,11445,7035,10920,10185,11445,12075,7035,11655,11340,11655,11970}),{Default=Color3.fromRGB(208,123,255),Title=daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7035,11655,11340,11655,11970})})
Toggles.ArmChams:OnChanged(function(Value)
Misc2.Settings.LocalChams = Value
Functions:ArmChams()
end)
Options.ArmChamsColor:OnChanged(function(Value)
Misc2.Settings.LocalChamsColor = Value
end)

ArmVisTab:AddDropdown(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({6825,11970,11445,7035,10920,10185,11445,12075,8085,10185,12180,10605,11970,11025,10185,11340}),{Values={daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7350,11655,11970,10395,10605,7350,11025,10605,11340,10500}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8190,10605,11655,11550}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7665,10395,10605}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7455,11340,10185,12075,12075})},Default=1,Multi=false,Text=daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10185,11970,11445,3360,11445,10185,12180,10605,11970,11025,10185,11340,6090})})
Options.ArmChamsMaterial:OnChanged(function(Value)
Misc2.Settings.LocalChamsMaterial = Value
end)

ArmVisTab:AddInput(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({}), {Default = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11970,10290,12600,10185,12075,12075,10605,12180,11025,10500,6090,4935,4935,5145,5145,5460,5145,5460,5670,5355,5355,5880,5565,5565}), Numeric = false, Finished = true, Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8820,10605,12600,12180,12285,11970,10605,3360,7665,7140,6090}), Placeholder = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11970,10290,12600,10185,12075,12075,10605,12180,11025,10500,6090,4935,4935,4830,4830,4830})}):OnChanged(function(TextureID)
game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9135,11655,11970,11235,12075,11760,10185,10395,10605})).Ignore.FPSArms.LeftUpperArm.TextureID = TextureID
game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9135,11655,11970,11235,12075,11760,10185,10395,10605})).Ignore.FPSArms.LeftLowerArm.TextureID = TextureID
game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9135,11655,11970,11235,12075,11760,10185,10395,10605})).Ignore.FPSArms.LeftHand.TextureID = TextureID
game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9135,11655,11970,11235,12075,11760,10185,10395,10605})).Ignore.FPSArms.RightUpperArm.TextureID = TextureID
game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9135,11655,11970,11235,12075,11760,10185,10395,10605})).Ignore.FPSArms.RightLowerArm.TextureID = TextureID
game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9135,11655,11970,11235,12075,11760,10185,10395,10605})).Ignore.FPSArms.RightHand.TextureID = TextureID
end)

ExploitsTab:AddToggle(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8190,8295,8715,7980,8295,9135,7140,8295,9135,8190}),{Text=daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11550,11655,3360,12075,11340,11655,12495,10500,11655,12495,11550}),Default=false}):OnChanged(function(Value)
local NoSlowDown = false
local old = getrenv()._G.modules.Character.SetSprintBlocked
NoSlowDown = Value
getrenv()._G.modules.Character.SetSprintBlocked = function(...)
local args = {...}
if NoSlowDown then
  args[1] = false
  return old(unpack(args))
end
return old(...)
end
end)

local WorldEspTabBox = Tabs.Visual:AddRightTabbox(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({12495,11655,11970,11340,10500,3360,10605,12075,11760}))
local WorldEspTab = WorldEspTabBox:AddTab(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({12495,11655,11970,11340,10500,3360,10605,12075,11760}))

--* Player Settings *--

_G.SettingsOre = {
iron = {
  enabled = true,
  colour = Color3.fromRGB(199, 172, 120),
},
nitrate = {
  enabled = true,
  colour = Color3.fromRGB(248, 248, 248),
},
stone = {
  enabled = true,
  colour = Color3.fromRGB(205, 205, 205),
},
oreDistance = 1000,
}
local settings1 = _G.SettingsOre
if settings1 == nil then
return
end

WorldEspTab:AddToggle(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11025,11970,11655,11550,9975,8820,11655,10815,10815,11340,10605}),{Text=daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10605,11550,10185,10290,11340,10605,10500}),Default=false})

WorldEspTab:AddSlider(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8295,11970,10605,8610,10605,11550,10500,10605,11970,7140,11025,12075,12180,10185,11550,10395,10605}), {Text=daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10500,11025,12075,12180,10185,11550,10395,10605,6090}),Default=1000,Min=1,Max=2500,Rounding=0,Compact=false,Suffix=daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({3360,12075,12180,12285,10500,12075})}):OnChanged(function(Value)
settings1.oreDistance = Value
end)

WorldEspTab:AddToggle(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11025,11970,11655,11550,9975,8820,11655,10815,10815,11340,10605}),{Text=daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11025,11970,11655,11550,3360,11655,11970,10605}),Default=false}):AddColorPicker(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7665,11970,11655,11550,7035,11655,11340,11655,11970}), { Default = Color3.fromRGB(199, 172, 120), Title = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7035,11655,11340,11655,11970}), }):OnChanged(function(Value)
settings1.iron.enabled = Value
end)
Options.IronColor:OnChanged(function(Value)
settings1.iron.colour = Value
if settings1.iron.enabled then
settings1.iron.enabled = false
task.wait(0.01)
settings1.iron.enabled = true
end
end)

WorldEspTab:AddToggle(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11550,11025,12180,11970,10185,12180,10605,9975,8820,11655,10815,10815,11340,10605}),{Text=daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11550,11025,12180,11970,10185,12180,10605,3360,11655,11970,10605}),Default=false}):AddColorPicker(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8190,11025,12180,11970,10185,12180,10605,7035,11655,11340,11655,11970}), { Default = Color3.fromRGB(248, 248, 248), Title = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7035,11655,11340,11655,11970}), }):OnChanged(function(Value)
settings1.nitrate.enabled = Value
end)
Options.NitrateColor:OnChanged(function(Value)
settings1.nitrate.colour = Value
if settings1.nitrate.enabled then
settings1.nitrate.enabled = false
task.wait(0.01)
settings1.nitrate.enabled = true
end
end)

WorldEspTab:AddToggle(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({12075,12180,11655,11550,10605,9975,8820,11655,10815,10815,11340,10605}),{Text=daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({12075,12180,11655,11550,10605,3360,11655,11970,10605}),Default=false}):AddColorPicker(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8715,12180,11655,11550,10605,7035,11655,11340,11655,11970}), { Default = Color3.fromRGB(205, 205, 205), Title = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7035,11655,11340,11655,11970}), }):OnChanged(function(Value)
settings1.stone.enabled = Value
end)
Options.StoneColor:OnChanged(function(Value)
settings1.stone.colour = Value
if settings1.stone.enabled then
settings1.stone.enabled = false
task.wait(0.01)
settings1.stone.enabled = true
end
end)

local Text1Font = 2
local textoutlines = true
local testsize = 11
local function get_text(text, position)
local distance = math.floor((position - workspace.Ignore.LocalCharacter.Middle.Position).Magnitude)
local final_text = tostring(text) .. daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9660,11550,9555}) .. tostring(distance) .. daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9765,3360,12075,12180,12285,10500,12075})
return tostring(final_text)
end
local function worldtoviewport(position)
local a, b = workspace.CurrentCamera:WorldToViewportPoint(position)
return Vector2.new(a.X, a.Y), b
end
local function add_esp(part, text, colour, toggle)
local drawing_text = Drawing.new(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8820,10605,12600,12180}))
drawing_text.Outline = textoutlines
drawing_text.Center = true
drawing_text.Visible = false
drawing_text.Font = Text1Font
drawing_text.Size = testsize
drawing_text.Color = colour
local rendersteploop = game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8610,12285,11550,8715,10605,11970,12390,11025,10395,10605})).RenderStepped:connect(function()pcall(function()
if not part:IsDescendantOf(workspace) or not settings1 then
  table.remove(oresDebris,part)
  drawing_text:Remove()
  rendersteploop:Disconnect()
end
local part_pos = part.Position
local screen_pos, on_screen = worldtoviewport(part_pos)
if not on_screen then
  drawing_text.Visible = false
  drawing_text.Size = testsize
  drawing_text.Outline = textoutlines
  drawing_text.Font = Text1Font
  rendersteploop:Disconnect()
end
local oreDis = (game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9135,11655,11970,11235,12075,11760,10185,10395,10605})).Ignore.LocalCharacter:WaitForChild(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8820,11655,11760})):GetPivot().Position-part_pos).Magnitude
if oreDis >= settings1.oreDistance then
  drawing_text.Visible = false
  drawing_text.Size = testsize
  drawing_text.Outline = textoutlines
  drawing_text.Font = Text1Font
  rendersteploop:Disconnect()
end
if text == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7665,11970,11655,11550}) and not settings1.iron.enabled then
  drawing_text.Visible = false
  drawing_text.Color = settings1.iron.colour
  rendersteploop:Disconnect()
else if text == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8190,11025,12180,11970,10185,12180,10605}) and not settings1.nitrate.enabled then
  drawing_text.Visible = false
  drawing_text.Color = settings1.nitrate.colour
  rendersteploop:Disconnect()
else if text == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8715,12180,11655,11550,10605}) and not settings1.stone.enabled then
  drawing_text.Visible = false
  drawing_text.Color = settings1.stone.colour
  rendersteploop:Disconnect()
end
end
end
drawing_text.Visible = true
drawing_text.Text = get_text(text, part_pos)
drawing_text.Position = screen_pos
drawing_text.Size = testsize
drawing_text.Outline = textoutlines
drawing_text.Font = Text1Font
rendersteploop:Disconnect()
end)
end)
end
local function filter_models(v)
if (not v:IsA(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8085,11655,10500,10605,11340}))) then
return
end
local is_part = v:FindFirstChild(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8400,10185,11970,12180}))
local children = v:GetChildren()
local child_amount = #children
if is_part then
if child_amount == 1 then
add_esp(is_part, daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8715,12180,11655,11550,10605}), settings1.stone.colour, settings1.stone.enabled)
elseif child_amount == 2 then
for _, v in pairs(children) do
  local brickcolor = v.BrickColor
  local is_ore = v.ClassName == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8085,10605,12075,10920,8400,10185,11970,12180}) and v.Name == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8400,10185,11970,12180})
  if is_ore then
    if brickcolor == BrickColor.new(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7665,11550,12075,12180,11025,12180,12285,12180,11025,11655,11550,10185,11340,3360,12495,10920,11025,12180,10605})) then
      add_esp(v, daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8190,11025,12180,11970,10185,12180,10605}), settings1.nitrate.colour, settings1.nitrate.enabled)
    elseif brickcolor == BrickColor.new(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({6930,12285,11970,11340,10185,11760})) then
      add_esp(v, daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7665,11970,11655,11550}), settings1.iron.colour, settings1.iron.enabled)
    end
  end
end
end
end
end
for index, model in pairs(workspace:GetChildren()) do
filter_models(model)
end
workspace.ChildAdded:Connect(function(model)
filter_models(model)
end)

WorldEspTab:AddDivider(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({}))

WorldEspTab:AddToggle(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8820,10605,12600,12180,8295,12285,12180,11340,11025,11550,10605,5250}),{Text=daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({12180,10605,12600,12180,3360,11655,12285,12180,11340,11025,11550,10605,12075}),Default=true}):OnChanged(function(Value)
textoutlines = Value
end)

WorldEspTab:AddSlider(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8820,10605,12600,12180,8715,11025,12810,10605,8715,11340,11025,10500,10605,11970,5250}), {Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({12180,10605,12600,12180,3360,12075,11025,12810,10605,6090}), Default = 12, Min = 1, Max = 25, Rounding = 0, Suffix = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11760,12600}), Compact = false}):OnChanged(function(TextSizeValue2)
testsize = TextSizeValue2
end)

WorldEspTab:AddDropdown(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7245,12075,11760,7350,11655,11550,12180,5250}),{Values={daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({5040}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({5145}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({5250}),daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({5355})},Default=3,Multi=false,Text=daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10710,11655,11550,12180,6090})}):OnChanged(function(Value)
Text1Font = Value
end)


local SpinbotTabBox = Tabs.Combat:AddRightTabbox(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({12075,11760,11025,11550,10290,11655,12180}))
local SpinbotTab = SpinbotTabBox:AddTab(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({12075,11760,11025,11550,10290,11655,12180}))

--* Spinbot *--

local fakeduck = false
local Spinbot = false
local SpinbotSpeed = 3
local SpinbotType = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8190,11655,11970,11445,10185,11340})
local value = 1
local SpinBotLM = false
local SpinBotV = false
SpinbotTab:AddToggle(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8715,11760,11025,11550,10290,11655,12180}),{Text=daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10605,11550,10185,10290,11340,10605,10500}),Default=false}):OnChanged(function(Value)
Spinbot = Value
end)

SpinbotTab:AddSlider(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8715,11760,11025,11550,10290,11655,12180,8715,11760,10605,10605,10500}), {Text=daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({12075,11760,10605,10605,10500,6090}),Default=3,Min=1,Max=3,Rounding=0,Compact=false,Thickness = 3}):OnChanged(function(Value)
SpinbotSpeed = Value
end)

SpinbotTab:AddDropdown(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8715,11760,11025,11550,10290,11655,12180,8820,12705,11760,10605}), {Values = {daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8190,11655,11970,11445,10185,11340}), daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7140,10605,12075,12705,11550,10395}), daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8610,10185,11550,10500,11655,11445})},Default = 1,Multi = false,Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({12180,12705,11760,10605,6090})}):OnChanged(function(Value)
SpinbotType = Value
end)

local OldSpinHook
OldSpinHook = hookfunction(game.Players.LocalPlayer:FindFirstChild(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8610,10605,11445,11655,12180,10605,7245,12390,10605,11550,12180})).FireServer, function(self, ...)
local args = {...}
if args[1] and args[2] and args[1] == 1 and typeof(args[2]) == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9030,10605,10395,12180,11655,11970,5355}) and args[4] and Spinbot == true then
  if SpinBotLM == true and SpinbotType == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7140,10605,12075,12705,11550,10395}) then
    args[4] = value
    value = value + SpinbotSpeed
  elseif SpinbotType == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8190,11655,11970,11445,10185,11340}) or SpinBotLM == false then
    args[4] = value
    value = value - SpinbotSpeed
  end
end
if args[1] and args[2] and args[1] == 1 and typeof(args[2]) == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({9030,10605,10395,12180,11655,11970,5355}) and args[4] and Spinbot == true then
  if SpinBotV == true and SpinbotType == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7140,10605,12075,12705,11550,10395}) then
    args[3] = 1.5000001192092896
  elseif SpinbotType == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8190,11655,11970,11445,10185,11340}) or SpinBotV == false then
    args[3] = -1.5000001192092896
  elseif SpinbotType == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8610,10185,11550,10500,11655,11445}) or SpinBotV == false then
    args[3] = -1.5000001192092896
  end
end
return OldSpinHook(self, unpack(args))
end)
task.spawn(function()
while task.wait() do
  if SpinbotType == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7140,10605,12075,12705,11550,10395}) then
    SpinBotV = not SpinBotV
  end
end
end)
task.spawn(function()
while task.wait(0.1) do
  if SpinbotType == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7140,10605,12075,12705,11550,10395}) or SpinbotType == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8610,10185,11550,10500,11655,11445}) then
    SpinBotLM = not SpinBotLM
  end
end
end)

SpinbotTab:AddToggle(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7350,10185,11235,10605,7035,11970,11655,12285,10395,10920}), {Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10710,10185,11235,10605,3360,10500,12285,10395,11235}),Default = false,Tooltip = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8085,10185,11235,10605,12075,3360,12285,3360,10395,11970,11655,12285,10395,10920,3360,10710,11655,11970,3360,11655,12180,10920,10605,11970,3360,11760,10605,11655,11760,11340,10605,3360,10185,11340,12075,11655,3360,12180,10920,10605,12705,3360,10395,10185,11550,12180,3360,10920,10605,10185,11970,3360,12705,11655,12285,11970,3360,10710,11655,11655,12180,12075,12180,10605,11760,12075})})
local OldCrouchHook; OldCrouchHook = hookfunction(game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8400,11340,10185,12705,10605,11970,12075})).LocalPlayer:FindFirstChild(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8610,10605,11445,11655,12180,10605,7245,12390,10605,11550,12180})).FireServer, function(self, ...)
local args = {...}
if args[1] == 2 and fakeduck == true then
  args[2] = true
end
return OldCrouchHook(self, unpack(args))
end)
Toggles.FakeCrouch:OnChanged(function() fakeduck = Toggles.FakeCrouch.Value end)
local function onFakeLagToggled(value)
  local networkClient = game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8190,10605,12180,12495,11655,11970,11235,7035,11340,11025,10605,11550,12180}))
  networkClient:SetOutgoingKBPSLimit(value and 1 or 100)
end
SpinbotTab:AddToggle(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7350,10185,11235,10605,7980,10185,10815}), {Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10710,10185,11235,10605,3360,11340,10185,10815}), Default = false}):OnChanged(onFakeLagToggled)

local WeaponModsTabBox = Tabs.Combat:AddRightTabbox(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({12495,10605,10185,11760,11655,11550,3360,11445,11655,10500,11025,10710,11025,10395,10185,12180,11025,11655,11550,12075}))
local WeaponModsTab = WeaponModsTabBox:AddTab(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({12495,10605,10185,11760,11655,11550,3360,11445,11655,10500,11025,10710,11025,10395,10185,12180,11025,11655,11550,12075}))

local gunMods = {
  norecoilTog = false,
  noSpreadTog = false,
  firerateMultiTog = false,
  firerateMulti = 1,
  noReloadanimTog = false,
}

local GunModsEnabled = false
WeaponModsTab:AddToggle(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7350,11025,11970,10605,8820,12705,11760,10605,7245,11550,10185,10290,11340,10605,10500}), {Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10605,11550,10185,10290,11340,10605,10500}), Default = false}):OnChanged(function(EnabledFireType)
GunModsEnabled = EnabledFireType
end)

WeaponModsTab:AddToggle(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8190,11655,8610,10605,10395,11655,11025,11340}),{Text=daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11550,11655,3360,11970,10605,10395,11655,11025,11340}),Default=false}):OnChanged(function(Value)
gunMods.norecoilTog = Value
end)
local oldNoRecoil;oldNoRecoil = hookfunction(getrenv()._G.modules.Camera.Recoil,function(...)
if GunModsEnabled and gunMods.norecoilTog == true then
  return false
else
  return oldNoRecoil(...)
end
end)

WeaponModsTab:AddToggle(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8190,11655,8715,11760,11970,10605,10185,10500}),{Text=daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11550,11655,3360,12075,11760,11970,10605,10185,10500}),Default=false}):OnChanged(function(Value)
gunMods.noSpreadTog = Value
end)
local oldNoSpread;oldNoSpread = hookfunction(getupvalues(getrenv()._G.modules.FPS.ToolControllers.RangedWeapon.PlayerFire)[1],function(...)
local arg = {...}
if GunModsEnabled and gunMods.noSpreadTog == true then
  arg[2][daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({6825,10395,10395,12285,11970,10185,10395,12705})] = math.huge
  return oldNoSpread(unpack(arg))
end
return oldNoSpread(...)
end)

WeaponModsTab:AddToggle(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7350,11025,11970,10605,11970,10185,12180,10605}),{Text=daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10710,11025,11970,10605,11970,10185,12180,10605}),Default=false}):OnChanged(function(Value)
gunMods.firerateMultiTog = Value
end)

WeaponModsTab:AddSlider(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10710,11025,11970,10605,11970,10185,12180,10605,8085,12285,11340,12180,11025,8715}), {Text=daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11445,12285,11340,12180,11025,6090}),Default=0.5,Min=0,Max=1,Rounding=2,Compact=false}):OnChanged(function(Value)
gunMods.firerateMulti = Value
end)
local oldAttackCooldown;oldAttackCooldown = hookfunction(getupvalues(getrenv()._G.modules.FPS.ToolControllers.RangedWeapon.PlayerFire)[1],function(...)
local arg = {...}
if GunModsEnabled and gunMods.firerateMultiTog == true then
  arg[2][daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({6825,12180,12180,10185,10395,11235,7035,11655,11655,11340,10500,11655,12495,11550})] = gunMods.firerateMulti
  return oldAttackCooldown(unpack(arg))
end
return oldAttackCooldown(...)
end)

local ItemConfigs = game.ReplicatedStorage.ItemConfigs
local weapons = {PipePistol = require(ItemConfigs.PipePistol),Blunderbuss = require(ItemConfigs.Blunderbuss),Crossbow = require(ItemConfigs.Crossbow),Bow = require(ItemConfigs.Bow),USP9 = require(ItemConfigs.USP9),LeverActionRifle = require(ItemConfigs.LeverActionRifle),GaussRifle = require(ItemConfigs.GaussRifle)}
local FireActions = {Semi = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({12075,10605,11445,11025}),Auto = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10185,12285,12180,11655})}
WeaponModsTab:AddDropdown(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7350,11025,11970,10605,8820,12705,11760,10605,7140,11970,11655,11760,10500,11655,12495,11550}), {Values = {daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8715,10605,11445,11025}), daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({6825,12285,12180,11655})},Default = 1,Multi = false,Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10710,11025,11970,10605,3360,12180,12705,11760,10605,6090})}):OnChanged(function(Value)
if GunModsEnabled then
  local fireAction = FireActions[Value]
  for _, weapon in pairs(weapons) do
    weapon.FireAction = fireAction
  end
end
end)

local FieldOfViewTabBox = Tabs.Combat:AddLeftTabbox(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10710,11025,10605,11340,10500,3360,11655,10710,3360,12390,11025,10605,12495}))
local FieldOfViewTab = FieldOfViewTabBox:AddTab(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10710,11025,10605,11340,10500,3360,11655,10710,3360,12390,11025,10605,12495}))

--* Field Of View *--

local FieldOfViewEnabled = false
local FieldOfViewValue = 70
local CurrentSliderValue3 = 70
game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8610,12285,11550,8715,10605,11970,12390,11025,10395,10605})).RenderStepped:Connect(function()
local fovFunc = nil
for i,v in pairs(getreg()) do
if type(v) == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10710,12285,11550,10395,12180,11025,11655,11550}) and getfenv(v).script.Name == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7035,10185,11445,10605,11970,10185}) and #getupvalues(v) >= 18 then
  fovFunc = v
end
end
setupvalue(fovFunc,18,FieldOfViewValue)
end)

FieldOfViewTab:AddToggle(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7350,11025,10605,11340,10500,8295,10710,9030,11025,10605,12495}), { Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10605,11550,10185,10290,11340,10605,10500}), Default = false }):AddKeyPicker(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10710,11025,10605,11340,10500,11655,10710,12390,11025,10605,12495,11235,10605,12705}), { Default = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8190,11655,11550}), SyncToggleState = true, Mode = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8820,11655,10815,10815,11340,10605}), Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10710,11025,10605,11340,10500,3360,11655,10710,3360,12390,11025,10605,12495}), NoUI = true }):OnChanged(function(value)
FieldOfViewEnabled = value
if not FieldOfViewEnabled then
FieldOfViewValue = 70
else
FieldOfViewValue = CurrentSliderValue3
end
end)

FieldOfViewTab:AddSlider(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7350,11025,10605,11340,10500,8295,10710,9030,11025,10605,12495,8715,11340,11025,10500,10605,11970}), { Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({10710,11025,10605,11340,10500,3360,11655,10710,3360,12390,11025,10605,12495,6090}), Suffix = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({12600}), Default = 70, Min = 0, Max = 120, Rounding = 0, Compact = false }):OnChanged(function(sliderValue)
CurrentSliderValue3 = sliderValue
if FieldOfViewEnabled then
FieldOfViewValue = sliderValue
end
end)

local Misc = {
Settings = {
  JumpShoot = false,
  NoADS = false,
}
}

ExploitsTab:AddToggle(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7770,12285,11445,11760,8715,10920,11655,11655,12180}),{Text=daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11130,12285,11445,11760,3360,12075,10920,11655,11655,12180}),Default=false}):OnChanged(function(Value)
Misc.Settings.JumpShoot = Value
end)
local oldIsGrounded;oldIsGrounded = hookfunction(getrenv()._G.modules.Character.IsGrounded,function(...)
if Misc.Settings.JumpShoot == true then
return true
else
return oldIsGrounded(...)
end
end)

ExploitsTab:AddToggle(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8190,11655,6825,7140,8715}),{Text=daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11550,11655,3360,10185,10500,12075}),Default=false}):OnChanged(function(Value)
Misc.Settings.NoADS = Value
end)
local oldNoADS;oldNoADS = hookfunction(getrenv()._G.modules.Camera.SetVMAimingOffset,function(...)
if Misc.Settings.NoADS == true then
return true
else
return oldNoADS(...)
end
end)

local NoSway = false
ExploitsTab:AddToggle(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8190,11655,8715,12495,10185,12705}),{Text=daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11550,11655,3360,12075,12495,10185,12705}),Default=false}):OnChanged(function(Value)
NoSway = Value
end)
local NoSwayHook;NoSwayHook = hookfunction(getrenv()._G.modules.Camera.SetSwaySpeed,function(...)
local args = {...}
if NoSway == true then
args[1] = 0
return NoSwayHook(unpack(args))
end
return NoSwayHook(...)
end)

Library:SetWatermarkVisibility(true)
local FrameTimer = tick()
local FrameCounter = 0;
local FPS = 60;
local WatermarkConnection = game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8610,12285,11550,8715,10605,11970,12390,11025,10395,10605})).RenderStepped:Connect(function()
    FrameCounter += 1;

    if (tick() - FrameTimer) >= 1 then
        FPS = FrameCounter;
        FrameTimer = tick();
        FrameCounter = 0;
    end;

    Library:SetWatermark((daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({12075,11235,10185,10710,10710,10710,4830,12075,11235,11025,10500,3360,13020,3360,3885,12075,3360,10710,11760,12075,3360,13020,3360,3885,12075,3360,11445,12075})):format(
        math.floor(FPS),
        math.floor(game:GetService(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8715,12180,10185,12180,12075})).Network.ServerStatsItem[daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7140,10185,12180,10185,3360,8400,11025,11550,10815})]:GetValue())
    ));
end);

Library.KeybindFrame.Visible = true;

Library:OnUnload(function()
    WatermarkConnection:Disconnect()
    for i,v in pairs(Toggles) do
        v:SetValue(false)
    end
    PlayerConnection:Disconnect()
    Library.Unloaded = true
end)

local MenuGroup = Tabs[daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8925,7665,3360,8715,10605,12180,12180,11025,11550,10815,12075})]:AddLeftGroupbox(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8085,10605,11550,12285}))
MenuGroup:AddButton(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8925,11550,11340,11655,10185,10500}), function() Library:Unload() end)
MenuGroup:AddLabel(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8085,10605,11550,12285,3360,10290,11025,11550,10500})):AddKeyPicker(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8085,10605,11550,12285,7875,10605,12705,10290,11025,11550,10500}), { Default = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({7245,11550,10500}), NoUI = true, Text = daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8085,10605,11550,12285,3360,11235,10605,12705,10290,11025,11550,10500}) })
Library.ToggleKeybind = Options.MenuKeybind
ThemeManager:SetLibrary(Library)
SaveManager:SetLibrary(Library)
SaveManager:IgnoreThemeSettings()
SaveManager:SetIgnoreIndexes({ daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8085,10605,11550,12285,7875,10605,12705,10290,11025,11550,10500}) })
ThemeManager:SetFolder(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({12075,11235,10185,10710,10710,10710,12075,11235,11025,10500}))
SaveManager:SetFolder(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({12075,11235,10185,10710,10710,10710}))
SaveManager:BuildConfigSection(Tabs[daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8925,7665,3360,8715,10605,12180,12180,11025,11550,10815,12075})])
ThemeManager:ApplyToTab(Tabs[daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8925,7665,3360,8715,10605,12180,12180,11025,11550,10815,12075})])
SaveManager:LoadAutoloadConfig()

Library:Notify(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({12495,12075,10815,3360})..game.Players.LocalPlayer.Name..daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({3360,12180,10920,12600,3360,10710,11655,11970,3360,12285,12075,11025,11550,10815,3360,12075,11235,10185,10710,10710,10710,4830,12075,11235,11025,10500}),8)
Library:Notify(daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({8715,12180,10185,12180,12285,12075,6090,3360,8925,11550,10500,10605,12180,10605,10395,12180,10605,10500,3360,25200,16695,16695,17745}),8)
  local notifyPlayerChange = function(player, message, color)
  local prefix = player:IsFriendsWith(game.Players.LocalPlayer.UserId) and daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11550,11655,12180,11025,10710,11025,10395,10185,12180,11025,11655,11550,3360,4725,3360,10710,11970,11025,10605,11550,10500}) or daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11550,11655,12180,11025,10710,11025,10395,10185,12180,11025,11655,11550,3360,4725,3360,11760,11340,10185,12705,10605,11970})
  Library:Notify((daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({3885,12075,3360,13020,3360,12285,12075,10605,11970,6090,3360,3885,12075,3360,13020,3360,3885,12075})):format(prefix, player.DisplayName, message), prefix == daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11550,11655,12180,11025,10710,11025,10395,10185,12180,11025,11655,11550,3360,4725,3360,10710,11970,11025,10605,11550,10500}) and 6 or 3, color)
end
game.Players.PlayerAdded:Connect(function(player)
notifyPlayerChange(player, daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11130,11655,11025,11550,10605,10500}), Color3.fromRGB(0, 255, 0))
end)
game.Players.PlayerRemoving:Connect(function(player)
notifyPlayerChange(player, daaDAqxazeGFQzJDkRyOkkxvmZXckCBEimwXuKWwhCqwSGgYNVcgWnzeYLEpmxOySMBuR({11340,10605,10710,12180}), Color3.fromRGB(255, 0, 0))
end)    
