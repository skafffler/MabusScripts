local b='ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789+/'
function tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB(data) m=string.sub(data, 0, 55) data=data:gsub(m,'')

data = string.gsub(data, '[^'..b..'=]', '') return (data:gsub('.', function(x) if (x == '=') then return '' end local r,f='',(b:find(x)-1) for i=6,1,-1 do r=r..(f%2^i-f%2^(i-1)>0 and '1' or '0') end return r; end):gsub('%d%d%d?%d?%d?%d?%d?%d?', function(x) if (#x ~= 8) then return '' end local c=0 for i=1,8 do c=c+(x:sub(i,i)=='1' and 2^(8-i) or 0) end return string.char(c) end)) end


 


  --// Locals
  local Camera = game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('PuNReMBZvrkaZDdzhkaeTenhIYIDTCdVjKyljCWTWZbjEUXEQiUSsTRV29ya3NwYWNl')).Camera
  local Camera = game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('ypPSEugCoucMMjDLdREeVKVVmTYcaxRpBAnSHUsQFcAMIHNhKqJYMehV29ya3NwYWNl')).CurrentCamera
  local Cam = game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('RUfXPouIoGaUwgLpExNiWWIrtDNkOLinBXsQWpeaDoulZqUOzeRlnpCV29ya3NwYWNl')).Camera
  local CharcaterMiddle = game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('YfCCRJAfUNdZepZEaiiwyGeVlKzEFKIafXsydIPGXJcImmZWtACbgDnV29ya3NwYWNl')).Ignore.LocalCharacter.Middle
  local Mouse = game.Players.LocalPlayer:GetMouse()
  local lighting = game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('DztZgRRBqsydegBccbemgFvbLdcMGFLPApKgNdWFiTseKRbaUsSqWeGTGlnaHRpbmc='))
  local UserInputService = game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('SzASThqCSRzhZxKpdkejGbYjVxQZHXcXvUnSbmeOLyLvkAIeNTrNJMlVXNlcklucHV0U2VydmljZQ=='))
  local SoundService = game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('GHNIgoaMMaTscnRrOBNGzRbPzlnLFgNdPLpeZQBePqyfjuoHDCSUbpvU291bmRTZXJ2aWNl'))
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
local repo = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('PyTamrZnCzQKtahHWlJSfPPaRykRePIOVriiJZmCKcKJqVAhgrlTnMKaHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL3Zpb2xpbi1zdXp1dHN1a2kvTGlub3JpYUxpYi9tYWluLw==')

local Library = loadstring(game:HttpGet(repo .. tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('NTYTZePDFjeHcFIIYOCHgnQqMVcKXUlBjLXbTRJWbKpizNmhVRbLukETGlicmFyeS5sdWE=')))()
local ThemeManager = loadstring(game:HttpGet(repo .. tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('TQoaTzHhDDBcGxAKFHewSdUdhsTterIISTVqfOHNIetwSxYmTjzMAUBYWRkb25zL1RoZW1lTWFuYWdlci5sdWE=')))()
local SaveManager = loadstring(game:HttpGet(repo .. tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('mFlaSOWYftNvpISAhvVSsWwCDUVUyXnKrqjDBSXbFXxupQlaqrAaBylYWRkb25zL1NhdmVNYW5hZ2VyLmx1YQ==')))()

local Window = Library:CreateWindow({Title = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('jVlvhfKmVyLZYbQuZVsRCTBosGwgIrclhrlwTWUVFIGwEUCDBTswQebc2thZmZmLnNraWQgREVWIFZFUlNJT04='),Center = true,AutoShow = true,TabPadding = 8,MenuFadeTime = 0.2})
local Tabs = {Combat = Window:AddTab(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('XbvadsjdbPXsZpEEwRdAPafDaqQdqtJZBHNFHEAfvMggkiAXZMWYWNKQ29tYmF0')),Visual = Window:AddTab(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('iOaZFmlUTBDNtVVfFqUugNuulgQXGeJnuOEYPrmBgSCMxfyQIPTlucuVmlzdWFs')),Misc = Window:AddTab(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('rpLKzhfsNmTrfGxYGcLszLYdrqgdGOJHgJUYGhPHrdDJuXartOLAsppRXhwbG9pdHM=')),[tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('RZvCNFhUhKAUvIrjSDIIsJSnCLeHQHPSexQahupOZzfLifUNtQHqcPkVUkgU2V0dGluZ3M=')] = Window:AddTab(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('aPVWiJlEEbLmSVhYHMCheQQMhprRahDTIHxPuPezxvWOrqeJCOksLIaVUkgU2V0dGluZ3M=')),}
	
	
--Tables
local Functions = {}
local Esp = {Settings={
  Boxes=false,BoxesOutline=false,BoxesFilled=false,BoxesFilledColor=Color3.fromRGB(255,255,255),BoxesFilledTransparency=0.25,BoxesColor=Color3.fromRGB(255,255,255),OtherBoxesColor=Color3.fromRGB(255,255,255),OtherBoxesColorTeam=Color3.fromRGB(0, 255, 0),BoxesOutlineColor=Color3.fromRGB(0,0,0),CornerEspThickness=1,CornerBoxes=false,
  Sleeping=false,SleepingColor=Color3.fromRGB(255,255,255),OtherSleepingColor=Color3.fromRGB(255,255,255),OtherSleepingColorTeam=Color3.fromRGB(0, 255, 0),
  Distances=false,DistanceColor=Color3.fromRGB(255,255,255),OtherDistanceColor=Color3.fromRGB(255,255,255),OtherDistanceColorTeam=Color3.fromRGB(0, 255, 0),
  Armour=false,ArmourColor=Color3.fromRGB(255,255,255),OtherArmourColor=Color3.fromRGB(255,255,255),OtherArmourColorTeam=Color3.fromRGB(0, 255, 0),
  Tools=false,ToolColor=Color3.fromRGB(255,255,255),OtherToolColor=Color3.fromRGB(255,255,255),OtherToolColorTeam=Color3.fromRGB(0, 255, 0),
  Tracer=false,TracerColor=Color3.fromRGB(255,255,255),OtherTracerColor=Color3.fromRGB(255,255,255),OtherTracerColorTeam=Color3.fromRGB(0, 255, 0),TracerThickness=1,TracerTransparrency=1,TracerFrom=tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('cUPiXgWLfaZVUImlwfUFiNuyrimqBfOJHKTBDQBcnBRFSuBrgmDVdIgQm90dG9t'),
  ViewAngle=false,ViewAngleColor=Color3.fromRGB(255,255,255),OtherViewAngleColor=Color3.fromRGB(255,255,255),OtherViewAngleColorTeam=Color3.fromRGB(0, 255, 0),ViewAngleThickness=1,ViewAngleTransparrency=1,
  HeadCircles=false,HeadCirclesColor=Color3.fromRGB(255,255,255),OtherHeadCirclesColor=Color3.fromRGB(255,255,255),OtherHeadCirclesTeam=Color3.fromRGB(0, 255, 0),HeadCirclesThickness=1,HeadCirclesTransparrency=1,HeadCirclesRadius=3,HeadCirclesFilled=false,
  HighlightTarget = false,HighlightTargetColor = Color3.fromRGB(255,0,0),
  TextFont=2,TextOutline=true,TextSize=12,RenderDistance=1000,TeamCheck=false,TargetSleepers=true,MinTextSize=11
},Drawings={},Connections={},Players={},Ores={},StorageThings={}}local Fonts = {[tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('OjqHHpYvqTcPocZuvSsnVNcaBoZOAFYFRutEsUFfHdFoWTxoGjwSPiLVUk=')]=0,[tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('uiSQZEoLySapAcxqaaKbHZtycLGMOzhnBcWJAAKVciYDkWVNFORgFUAU3lzdGVt')]=1,[tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('nYDEaqNGoYhtjMaZQUGsxdOGHgpnghmTFlShekJjdooxlZHfHyFhfgKUGxleA==')]=2,[tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('ViSjjxjMIlSygooQRlhUwAnjymTaBwENDnGBatepTWpbutMoevGPIUETW9ub3NwYWNl')]=3}
local Fonts = {[tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('HOSrzwqiDtzqEunzegJyIDveVFixObiRJgAhQebqplKmSqCLXNMsZEgVUk=')]=0,[tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('yykYwvvUImeKSOzAkFdhKuBTSsHPIDTExSNujqopbGcMtYOPgyiuUeWU3lzdGVt')]=1,[tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('LTFkHKxCwLrYhEwzuYMSmoshepgIaPLZeVFQmcNspLSKvNJeqydcrtfUGxleA==')]=2,[tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('MHwrYbBSKwBVqlcKUBZhSIvQMfaaLRmyRyUOURfpOIhjAEirAYlaoUrTW9ub3NwYWNl')]=3}
local cache = {}

--Locals
local Camera = game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('dHlEAPoJUVAakxmYNLjuriRALcMgJBGeZKwoEjNmgBhhSHDoFmKqYBeV29ya3NwYWNl')).CurrentCamera
local CharcaterMiddle = game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('FeXyikKEIaguKStOmlGbheHjJrlTaNOVEdgPlyzCqSRXjOQCLYkjIoeV29ya3NwYWNl')).Ignore.LocalCharacter.Middle

--Functions
function Functions:IsSleeping(Model)
    if Model and Model:FindFirstChild(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('OrTCnTsfoCXjceHoCdpyzcqevkDZxqwnPYZUYQZZihrLeMufgEBycSvQW5pbWF0aW9uQ29udHJvbGxlcg==')) and Model.AnimationController:FindFirstChild(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('WbHhUDAEqTvzWBkWQlQCWittnJuLABKGQLIeCTbOCdMNsieZnzaPRjPQW5pbWF0b3I=')) then
		for i,v in pairs(Model.AnimationController.Animator:GetPlayingAnimationTracks()) do
            if v.Animation.AnimationId == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('YyRToYcRNJuTZadsmEDzyYVcVFXAzBVdxyGvfaMkwmlJmJcCMKhHZvEcmJ4YXNzZXRpZDovLzEzMjgwODg3NzY0') then
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
    drawings.BoxOutline = Functions:Draw(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('oyndzxPGMpAeBEbvproKTAyrqGXeGIMnAaGRGufsZelsVNtotcahbQmU3F1YXJl'),{Thickness=2,Filled=false,Transparency=1,Color=Esp.Settings.BoxesOutlineColor,Visible=false,ZIndex = -1,Visible=false});
    drawings.Box = Functions:Draw(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('VsirpIfLkWzGVumrtZQuYNzYaGxmnVCudoQHiTUYDHcisxyDAplSHEiU3F1YXJl'),{Thickness=1,Filled=false,Transparency=1,Color=Esp.Settings.BoxesColor,Visible=false,ZIndex = 2,Visible=false});
    drawings.Sleeping = Functions:Draw(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('vcKJBJFslojiiLXnHflRkLtNdAkuyHtBTyvxUAoEDiDrbfcxqphqvBlVGV4dA=='),{Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('ietkMhUrXOMAIgbxUzjoyRXBwynhdUWWjQUWjKklvWXnrFcakmfBaaeTmls'),Font=Esp.Settings.TextFont,Size=Esp.Settings.TextSize,Center=true,Outline=Esp.Settings.TextOutline,Color = Esp.Settings.SleepingColor,ZIndex = 2,Visible=false})
    drawings.Distance = Functions:Draw(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('MhLSVxdoORoqSQTbBMAAEfhxVOATbObWQlaZIMvLRkvXhUJOBpsArzAVGV4dA=='),{Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('AUQvvhNihCKIKtNWBXrgIPCLVFLkwpPdAomSDpTiHRYsVzjGdlXhAEMTmls'),Font=Esp.Settings.TextFont,Size=Esp.Settings.TextSize,Center=true,Outline=Esp.Settings.TextOutline,Color = Esp.Settings.SleepingColor,ZIndex = 2,Visible=false})
    drawings.Armour = Functions:Draw(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('OjKMcYmcsFaKCpVlkegQUFweoUGhVlLtvmFSuqpauqzPTQLrOdxGuZOVGV4dA=='),{Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('drOjekTcwfdAjutYOEYiIoFRgGwSGQaoOBGOhMZdTatqGBMeaBkhiRmTmFrZWQ='),Font=Esp.Settings.TextFont,Size=Esp.Settings.TextSize,Center=false,Outline=Esp.Settings.TextOutline,Color = Esp.Settings.ArmourColor,ZIndex = 2,Visible=false})
    drawings.ViewAngle = Functions:Draw(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('IZHNLgimHIqwyjYJaCMepuQvLovbQPnnSDgMuRKlWSdkzcnswJAfXiaTGluZQ=='),{Thickness=Esp.Settings.ViewAngleThickness,Transparency=Esp.Settings.ViewAngleTransparrency,Color=Esp.Settings.ViewAngleColor,ZIndex=2,Visible=false})
    drawings.PlayerTable = PlayerTable
    Esp.Players[PlayerTable.model] = drawings
end
function Esp:RemoveEsp(PlayerTable)
    if not PlayerTable and PlayerTable.model ~= nil then return end
    esp = Esp.Players[PlayerTable.model];
    if not esp then return end
    for i, v in pairs(esp) do
        if not type(v) == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('TULlUyykATbvlETpoavnbzrVQYQtEuNiVUttpKwTCaWGPbqnwqSiXCodGFibGU=') then
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
        if Character and Character:FindFirstChild(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('ShOKxVmgVXUOMAOYitktmlTbCVcpsnLkxoAlAOKCTDQAwTaTuZsRgnxSHVtYW5vaWRSb290UGFydA==')) and Character:FindFirstChild(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('ExXMXjXMLUdtTMIRwQqaswEvEzasFRWkqfwXQIsnYMoaYWDLGZtuFftSGVhZA==')) then
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
                if sleeping == true then v.Sleeping.Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('XkrbSzbOWnarGDViBvXoEfcBderqlJDGPZRIbQuwIjGCSIKNgFOfUYiU2xlZXBpbmc=') else v.Sleeping.Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('cxrDyomvZMkSlOXIZjxOGlvYAWHhlDfgVmSUmOoVTNjuavEJMoBqRyKQXdha2U=') end
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
                    v.Distance.Text = math.floor(Distance)..tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('mrcRwyxBwDufCIBQEjIlEtsqtJeJyLRfonQDcETNalZlahCRkhUaoyBcw==')
                else
                    v.Distance.Text = math.floor(Distance)..tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('uDliDmCvDiIDeQPevdtNWJbQcPCIXyGoKEnWWBFpSDniXDhCrBilftScw==')
                end
                v.Distance.Outline=Esp.Settings.TextOutline;v.Distance.Color=Esp.Settings.SleepingColor;v.Distance.Size=math.max(math.min(math.abs(Esp.Settings.TextSize*scale),Esp.Settings.TextSize),Esp.Settings.MinTextSize);v.Distance.Color = Esp.Settings.DistanceColor;v.Distance.Font=Esp.Settings.TextFont;v.Distance.Position = Vector2.new(x,math.floor(y+h*.5))
            else
                v.Distance.Visible = false
            end
            if OnScreen == true and Esp.Settings.Armour == true and Distance <= Esp.Settings.RenderDistance then
                if Character.Armor:FindFirstChildOfClass(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('bActPbRkxgeAlWrBsYidxMbxCLrQymeVlxLXPlMlXsaIbGClxyitrPwRm9sZGVy')) then v.Armour.Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('OEOFNXeMSCdxuedEpShUYfYGfeVrRvroiejAjLrpaIFOpBnLwLWRQpqQXJtb3VyZWQ=') else v.Armour.Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('zLoRxKzfJrhCxXaSqylzHuxEoutHgIZjSMoArCTPMrdcdCnRPBCEiAOTmFrZWQ=') end
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
local PlayerUpdater = game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('kmAmuiPBnSgmqVtWVCFFwwlgglPwaPBpHQYoBrCnkupkLTOMqJxJazhUnVuU2VydmljZQ==')).RenderStepped
local PlayerConnection = PlayerUpdater:Connect(function()
    Esp:UpdateEsp()
end)

--Init Functions
for i,v in pairs(workspace:GetChildren()) do
	if v:FindFirstChild(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('GieDxXvmFLjfNCLJqELMwIbGIECrrYsKtEgrbbNBiINiRaQCRvAHEvoSHVtYW5vaWRSb290UGFydA==')) then
        table.insert(cache,v)
        Esp:CreateEsp({model=v})
	end
end

function Functions:GetToolNames()
tbl = {}
for i,v in pairs(game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('DIVoycUmabKGhekWZRyaUSWxhTLYZyhlzmJEQHgUaOzkiQCWxtvYtvPUmVwbGljYXRlZFN0b3JhZ2U=')).HandModels:GetChildren()) do
	if not table.find(tbl,v.Name) then table.insert(tbl,v.Name) end
end
return tbl
end
function Esp:CheckTools(PlayerTable)
if not PlayerTable then return end
if PlayerTable.equippedItem and table.find(Functions:GetToolNames(),PlayerTable[tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('qvHwWeWSPjQtlfwNsJEAXaLZsNsvhvBWZjBBJKzTATCZoFzvdLKbhQRZXF1aXBwZWRJdGVt')].id) then
	return tostring(PlayerTable[tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('gmhdEwGqGsszsweTiOsYvdYqSkbHYLjVlagRupFjRgmhelAucWwrMnsZXF1aXBwZWRJdGVt')].id)
elseif PlayerTable.handModel and PlayerTable.handModel.Name and string.find(PlayerTable.handModel.Name,tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('dfLhhFSlPufFXSuVSsSWMXTZYKwhESTxObaFieBaflYnEUMNrqvmzCvSGFtbWVy')) then
	return PlayerTable[tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('WugrXFruInIECHJybBSKAPQVMUlGuqOdmGXYWePPHRSAkCGJGvocySKaGFuZE1vZGVs')].Name
else
	return tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('FowdtDkITunkUhDLfASJvMHgFTcIfCeJNGvGOBJIMdHVWtiyjFZyFDhRW1wdHk=')
end
end

game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('zdMBKgOKFfvyXRRGQAsEMwDPJcERFTTQbCLtaetPtaEBSmMUBXZfXyAV29ya3NwYWNl')).ChildAdded:Connect(function(child)
    if child:FindFirstChild(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('UgyhfxqPfqruoLKkUxwRmDNHuMcxghAcRAHXTdpEkHFAHJPDBivbDXpSHVtYW5vaWRSb290UGFydA==')) and not table.find(cache,child) then
        table.insert(cache,child)
        Esp:CreateEsp({model=child})
    end
end)

local PlayerVisualTabbox = Tabs.Visual:AddLeftTabbox()
local PlayerVisualTab = PlayerVisualTabbox:AddTab(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('WqgXOKNxWTdlsxBBInkuJLmEGzsHNzBhwCmgQkImOWaRaKyyACUFiJkUGxheWVycw=='))
local PlayerSettingsVisualTab = PlayerVisualTabbox:AddTab(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('mgVHWTXPfxSaYIvAsvfvsaYWecPdClpNXAvtLjRdiQOOvhYOaVJiZntU2V0dGluZ3M='))

PlayerVisualTab:AddToggle(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('IJYuwqscSLKBujDrnFDcJoADywnMCLrynlznmBiHAJWpxOGEOfZEeMZQm94ZXM='),{Text=tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('QGPyFLauLhMAaZaUJMfUlAkejQcwPXflxQvSLdgtWSzfxzCDVEFGHwVQm94ZXM='),Default=false}):AddColorPicker(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('kFQrhXlDUuPHzCUbhlOefPtrzFmiUCOGcmhdLiZpfttaIAHgqiGaHuNQm94ZXNDb2xvcg=='),{Default=Color3.fromRGB(0,255,239),Title=tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('CNUNMSSylsyvEwrUSIBXLhpfHaMoxVbgcPqmCloxdrgCMtDUtbwCFfKQ29sb3I=')}):AddColorPicker(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('ulmuCxakkhjNTOsCeoEIQkCPqFLAwDDbHckRKbJptvFrPWkOeialStMQm94ZXNPdXRsaW5lQ29sb3I='),{Default=Color3.fromRGB(0,0,0),Title=tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('GyGjcbdeOIOgDpGejRqnnMbaIIyoWhwCLPEVhNgDTTuDNwvdzzzufKQQ29sb3I=')})
PlayerVisualTab:AddToggle(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('DGnamkVgdPAmuZjbloVaeaBeTKUPRjZnWOWaoHihOXsBFIbJFvbbmeVRGlzdGFuY2Vz'),{Text=tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('GsvgQLxEjBUujBHHfJAmZLECohmnJaPbFOZaUZylSZokNTQphqrjNroRGlzdGFuY2U='),Default=false}):AddColorPicker(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('rAMBrmtiVUAsSLCdYESnxaMFSRsUfhYSglTiEcXGbyUsLEQVDZkKIRXRGlzdGFuY2VzQ29sb3I='),{Default=Color3.fromRGB(0,255,239),Title=tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('MIIOSiQFLuYftpnOESCFldEYtpLiSpDgDEgGyXIUSerGhiqEfQskwjsQ29sb3I=')})
PlayerVisualTab:AddToggle(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('dcTdJXcsGFvJZxexyhfUtCNFFSUymsHhXgvPrEKZmdsYrIOTnIUzGIAU2xlZXBpbmc='),{Text=tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('NcomtrjtqDzAAsirAhcAJDFDcBWscZkzShuApGvtlebcXRevliokzYqU2xlZXBpbmc='),Default=false}):AddColorPicker(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('SXzZZLUbPCpiNWreHyiyYElXIacpHtDgYLcXnaOBCTGxuTyoPfjAxDRU2xlZXBpbmdDb2xvcg=='),{Default=Color3.fromRGB(0,255,239),Title=tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('vhScQCeLMQXNyxHLuiIDigptpSITLgUoQWfyADHTGTdpLlogNpTISTnQ29sb3I=')})
PlayerVisualTab:AddToggle(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('zcrldLoDcWLGjAwlUFWxDDDNApOWxpnEENJLgfGBXMQfWiNbRfcKkJMQXJtb3Vy'),{Text=tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('QsEmRfDqxijFQRambcCoJBUoqUcmxhwcqJCQVrlmOLMTdxbYfcJEKubQXJtb3Vy'),Default=false}):AddColorPicker(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('rGkOkBVGOYdXmAwOugkhECikODXruojeFjlQkkxuBcvvwNGbsMqDGGSQXJtb3VyQ29sb3I='),{Default=Color3.fromRGB(0,255,239),Title=tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('OxhJaCZxQhmmsPnznspCSAxBRdqEgneUCaohlsLxtnWfSkZSPFxQeTuQ29sb3I=')})
PlayerVisualTab:AddToggle(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('KPwtQdJAuDndpiGJpxvuRiCsGtXBqsyKZwuMveIZhNwXBxfGDnuhoRAVmlld0FuZ2xl'),{Text=tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('gbTqUSDzqmNJgBwHjEmTFhVUsBdFoposJvHkpFggBiaFZffwqYQOvaiVmlldyBBbmdsZQ=='),Default=false}):AddColorPicker(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('pSCPlnTHFjzGinngnwehMOGJdXPcwPBlakjmHFwLkbRZOLLokLnAKvGVmlld0FuZ2xlQ29sb3I='),{Default=Color3.fromRGB(0,255,239),Title=tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('LcqSPeCwjBoClxOaddyXhEZDPNDJfwOtKboxWoFcnfSGYHtZbTMVoXJQ29sb3I=')})

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
PlayerSettingsVisualTab:AddSlider(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('HSjGltJkNvFjkUioYCCwzlXqjQsSRZsGBmFDxFeqVKMMQolOKFDGYllUmVuZGVyRGlzdGFuY2U='), {Text=tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('ojwHIyrnKgEIZJumnNyWTUCEhuADpQralRDFqlGCrnxOFgVDISIdbxbUmVuZGVyIERpc3RhbmNl'),Default=1500,Min=1,Max=1500,Rounding=0,Compact=false,Suffix=tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('WmFJGnaYwfVRLRfAmNkVtSztyFUaYbdaNvuBlzJKvztdfJWZiqJTCLCcw==')}):OnChanged(function(Value)
    Esp.Settings.RenderDistance = Value
end)
PlayerSettingsVisualTab:AddToggle(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('SCvXeWamQlNUceELSBDEwdhhIoALBqUKeJrjMtvkBbWfXhqsijOIcpxVGFyZ2V0U2xlZXBlcnM='),{Text=tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('vOOEgjTOzaUtXgcnpYxXphyALtFuiKiKngleMVMosDBejtwtQNDigqRRG9udCBTaG93IFNsZWVwZXJz'),Default=true}):OnChanged(function(Value)
    Esp.Settings.TargetSleepers = Value
end)
PlayerSettingsVisualTab:AddToggle(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('aDwqBBcBENwGCfMSpJYIicamhAjrdzUcfpgFDYTAYfIdFHEPrjJYluyQm94ZXNPdXRsaW5lcw=='),{Text=tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('mlfrrzZSHuxdtdQMtFuZWDvVvFimZoHpZNUxKNkqaoOzDXuYJpYYXNRQm94IE91dGxpbmVz'),Default=true}):OnChanged(function(Value)
    Esp.Settings.BoxesOutline = Value
end)
PlayerSettingsVisualTab:AddToggle(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('UIqffvYNxfSCEpLhIQxtFmqlhWlRLWSsLjGKDBduAQdsxAkUVrKifeqVGVhbUNoZWNr'),{Text=tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('FgbCTtJNAnXRlnErWWkGTsrUNhIWTdvftPjtqgaloZpmqZshNHtNLfmVGVhbSBDaGVjaw=='),Default=true}):OnChanged(function(Value)
    Esp.Settings.TeamCheck = Value
end)
PlayerSettingsVisualTab:AddToggle(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('kTMpvKhgoCQICJnAApGagEYlHOERUUbfYcwPapXRnVIZGXhNsQFhKZNVGV4dE91dGxpbmU='),{Text=tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('AHEviEHGhalOxoSlGofrHlSPsyPfqNNcoVysUYnjsudQJoogwpoKccVVGV4dCBPdXRsaW5lcw=='),Default=true}):OnChanged(function(Value)
    Esp.Settings.TextOutline = Value
end)
PlayerSettingsVisualTab:AddToggle(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('jobpNmbuMUmMqUGXPxlaKllsSFFfDqmIvvweYqRIavQDskTVMtsCLhpQ2hlY2tUb29scw=='),{Text=tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('SEGDzRnucVtyNgcpLBpcKCPulDVOfqwrorwwLoooZpExMtcaYsNAMPvVG9vbHM='),Default=true}):OnChanged(function(Value)
    Esp.Settings.CheckTools = Value
end)

local HeadHitboxTabBox = Tabs.Combat:AddLeftTabbox(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('DQYWCdGtoRjZTqbwWOOAandvufHTtXCFMpsBqpMwrhfieMMtbFevCoCaGVhZCBoaXRib3g='))
local HeadHitboxTab = HeadHitboxTabBox:AddTab(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('tLKnYjShzgKHsuEAxstsXrfJVbtBNVoEFCaGDWmYyryFoKeALpsOpdeaGVhZCBoaXRib3g='))

local antihitbox
antihitbox = hookmetamethod(game, tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('lWpSLpxNiImrECqEzoYqzjpKXfiAskyDhzYGAhSkfIVFhAtdRoFYapwX19pbmRleA=='), newcclosure(function(...)
local self, k = ...
if not checkcaller() and k == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('jpLVlyAUTiTOuxdULbpiXqKjBSvABaXSFgZNgJYqYPwqcImXyzrIACNU2l6ZQ==') and self.Name == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('yscnAgCskwLqBzzWiyLOPQzzrfPtmsErlJYLzJAGoCydQdjvpQdMOwmSGVhZA==') then
  return Vector3.new(1.672248125076294, 0.835624098777771, 0.835624098777771)
end
return antihitbox(...)
end))

--* Head Hitbox Expander *--

local HedsOn = Instance.new(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('knltVMwbebAHQubOecsNtbkpsGtGNlslMNskUctemdhphXSTIWWefcWUGFydA=='))
HedsOn.Name = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('lEvywmcElqahNVjipfgxDgOiOzlUreRzjaqsAkxUDhAFrFPfeHRnagaSGVkc09u')
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

HeadHitboxTab:AddToggle(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('jjKwfjFIVhrQLyBogZgaOvQnJQUDklFuPvAFxPDZrzmeKoOxnXSMBjESEJP'),{Text=tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('nKKhiaETPxjvwDpQeZFHKTTrQbcPaVHsQlttFEAmjbVDZpnaQTTOgPmZW5hYmxlZA=='),Default=false}):OnChanged(function(Value)
HeadExtends = Value
end)

HeadHitboxTab:AddSlider(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('cqVFklTeCqPcuIwaNlaFlTXjghGlKwsJcizbHSZCSRvWXqjQknBPDboSGl0Ym94WFNpemVfU2xpZGVy'), {Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('EJUwgmUmngdhACGHdLbFiLBzZdyLXOPUohKgNiUHeczbCWOangdYCogaGl0Ym94IHdpZHRoOg=='), Default = 5, Min = 0, Max = 10, Rounding = 2, Suffix = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('qxaZFXBrqfnPhDutQbCcjegXBSBBAPtAgXevuftqWlsGVnUDwQrQSPkJQ=='), Compact = false}):OnChanged(function(HitboxXSize)
XSize = HitboxXSize
end)

HeadHitboxTab:AddSlider(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('nkauwnbLBowByXkJgYIhWUCzwgezLkltcYEAJNIosVwkamqvrymRHfHSGl0Ym94WVNpemVfU2xpZGVy'), {Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('SkltKxfRFvMShpGEwuEbXizKrOZBTBcMvUvKAjNLYfOmAlyKLYyQPtmaGl0Ym94IGhlaWdodDo='), Default = 5, Min = 0, Max = 10, Rounding = 2, Suffix = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('XpEQvwlScWkQizPocLugShlCbWUkTvbnRyzbDjPPaNLUzUnYqcqLRmbJQ=='), Compact = false}):OnChanged(function(HitboxYSize)
YSize = HitboxYSize
end)

HeadHitboxTab:AddSlider(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('UdzzZzgRHZqUAajudFiQZexnuVDagdjDSKOeNkelfKJdpQJcLwdOdJXSGl0Ym94WFNpemVfU2xpZGVy'), {Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('ybFqmQagzmAJjMWyGbOMQmEsIQdrSjcJdOcLumhRTVHEgyizhmAxnpWdHJhbnNwYXJlbmN5Og=='), Default = 50, Min = 0, Max = 100, Rounding = 0, Suffix = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('qGFnlJNgXvFFeyxJJAagXbvQwTgpamWTJWGVwIPFmcRHJyoveNPVFihJQ=='), Compact = false}):OnChanged(function(TransparencyValue)
HitboxTransparency = TransparencyValue / 100
end)

task.spawn(function()
while task.wait() do
  if HeadExtends then
    for _, i in ipairs(game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('AWgAmrjTNnfQYwPQWcLGKUyinxPNMGIjbjFOtSAtJQzFEVfQkcPaaTDV29ya3NwYWNl')):GetChildren()) do
      if i:FindFirstChild(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('WhJyeGudZUxIFzkwkabhjhjNdHoylvxfWvAvqdGnHPREPnTEgiApYNUSHVtYW5vaWRSb290UGFydA==')) and not i:FindFirstChild(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('aqyPrwBNabLxDhIxiwpIblSghfPstOQeacmXhFFJbTOWnCBVuqQEWzRSGVkc09u')) then
        local BigHeadsPart = Instance.new(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('mAltDekoGclsXSvdqcGUsVkWuLtVEUWxFmTcjDxIimMiptovRnkEgubUGFydA=='))
        BigHeadsPart.Name = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('xrhpYsWiOrfABpAgRkPdUoBfPFODRUXPBsoROVOezPtewRsSzdTJWXLSGVhZA==')
        BigHeadsPart.Anchored = false
        BigHeadsPart.CanCollide = false
        BigHeadsPart.Transparency = HitboxTransparency
        BigHeadsPart.Size = Vector3.new(XSize, YSize, ZSize)
        local DeletePart = Instance.new(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('iIBOiqilUsrvEjAxvrJaXUrZPtsfRpzBHZvGkOVcSkrUcmHDFniyHSdV2VsZA=='))
        DeletePart.Parent = BigHeadsPart
        DeletePart.Name = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('RIrPaIwFSgPTQdmfoDaRVPbMuVKlhMqaHxiBOLMyIzzSczgIdQrWyJURkFLRUhFQUQ=')
        local HeadsParts = BigHeadsPart:Clone()
        HeadsParts.Parent = i
        HeadsParts.Orientation = i.HumanoidRootPart.Orientation
        local clonedHedsOn = HedsOn:Clone()
        clonedHedsOn.Parent = i
        local Headswelding = Instance.new(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('mUieqbCGHhcyhlXVmnbcNaAtGsXlhJhpZbdXXzSKGtSEPJNvOoBsUcjV2VsZA=='))
        Headswelding.Parent = HeadsParts
        Headswelding.Part0 = i.HumanoidRootPart
        Headswelding.Part1 = HeadsParts
        HeadsParts.Position = Vector3.new(i.HumanoidRootPart.Position.X, i.HumanoidRootPart.Position.Y - 0.6, i.HumanoidRootPart.Position.Z)
      end
    end
  else
    for _, i in ipairs(game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('EPJuqEgTnUsIRjrgZaAIrmeaOSxnyZvPvqbzRXyquvrmwUlykWrJnQkV29ya3NwYWNl')):GetChildren()) do
      if i:FindFirstChild(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('JPHRqoqbobrgurGlBHRtsNxZYUBZdBBCUzuzUOnkxatqkyvUqZKdLTLSHVtYW5vaWRSb290UGFydA==')) and i:FindFirstChild(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('lTSdSfEvKjKhdcOoWJXfTCWNRyZaDCfLlpqXPSpggdteJrGNbvsHJVISGVkc09u')) then
        i.HedsOn:Remove()
        for _, a in ipairs(i:GetChildren()) do
          if a.Name == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('pgVXiNLrioAgxTuoXYDNNlKJGHkHBFmmBJfYipbEQPYSOENKLTReERhSGVhZA==') and a:FindFirstChild(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('GejroelWFWYJgJTfxjuQFApcSATefKENRhaCFUrsuBuhZByiWTbKBxwRkFLRUhFQUQ=')) and (not a:FindFirstChild(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('cYTjAkfGWRgOuYNNcvsAPkRJWUuwpbzFmOZvIuBeuTgDuFKiJkRuaRWTmFtZXRhZw==')) or not a:FindFirstChild(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('nsFsjBwQRkHbNFCqDErIoBGXIxlLhzJCwSUcfBYRaQCchrWfVWQwDnrRmFjZQ=='))) then
            a:Remove()
          end
        end
      end
    end
  end
end
end)

--/EXPLOITS\--


local ExploitsTabBox = Tabs.Misc:AddLeftTabbox(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('JRgcOyCtBJOWchaaTlLwzoBHYpJtvvtWYpKAlMvdUifUTyDPAkJJbSjRXhwbG9pdHM='))
local ExploitsTab = ExploitsTabBox:AddTab(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('XcaNDeKGgfGovGoJqHIDHwkYXzNODKSQuOfVJyEONYhlsWOpTDUPlauRXhwbG9pdHM='))

local LongNeckEnabled = false
local UpperLimitDefault = 3
local LowerLimitDefault = 1.75
local CurrentSliderValue = 1.75

ExploitsTab:AddToggle(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('UGQiWDXWFuCdBkTvvmHIYdZDsOyqcXnQiKGVkOScGYJDFrpuaxEeFRcTG9uZ05lY2s='), {Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('GTHgTrXHgjurDWDnxyfePCoDZCKRDUFeTactpTjQYhFuKZSjpypTPuwbG9uZyBuZWNr'), Default = false, Tooltip}):AddKeyPicker(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('RIGTvwzEqqrKmtAmWdQYlegZkEZpjCBqpqbvOzDRnSFfBuGpOQgjXACTG9uZ05lY2tLZXk='), {Default = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('ipYzkUHXKtajCqZBzmHtChtRalawdboViMzdRWWMVDsfIszDCyGpHpsTm9u'), SyncToggleState = true, Mode = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('hrQHcFwwkbCimfKitXoVdrIoXlztjCKQcVWEwalSSxghKCSTmWijBvVVG9nZ2xl'), Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('KtSytkGcfJtIvkXktcmAZEHdtZWJVqszbFIGGukiecHBIfVvchrJcrITG9uZyBOZWNr'), NoUI = false}):OnChanged(function(value)
LongNeckEnabled = value
if not LongNeckEnabled then
game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('ojWIYumfSEBZMnUrExliNiURyObytNCyEocnrEVYodQEYigZwhfizIXV29ya3NwYWNl')).Ignore.LocalCharacter.Bottom.PrismaticConstraint.UpperLimit = UpperLimitDefault
game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('sFuvtpoicfXNpqLpjoVYsEoMJnyBEnfXbvEopQMYdWvOCncQcFUDcZVV29ya3NwYWNl')).Ignore.LocalCharacter.Bottom.PrismaticConstraint.LowerLimit = LowerLimitDefault
else
game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('UzWkRtVDLeHJenPbffyPoPCegIQGpwDzETNPAIwOpKLnVnRtrXyklaCV29ya3NwYWNl')).Ignore.LocalCharacter.Bottom.PrismaticConstraint.UpperLimit = CurrentSliderValue
game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('WCZhRTjrFxRjaooHptjjoLhylIkUPTqCqnHgiEYSyAVgHwvpwNsOeeNV29ya3NwYWNl')).Ignore.LocalCharacter.Bottom.PrismaticConstraint.LowerLimit = CurrentSliderValue
end
end)

ExploitsTab:AddSlider(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('pyVTCCbwdekTOvzEEZSoLXxxUtAmNXtdSUvUYKlTplpOQsltdKiRseUSGVpZ2h0Q2hhbmdlclNsaWRlcg=='), {Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('axWaMpreRYqUjOVkQDvvaUNXmtiXNbLruHjJwSQcmyICZsMKOOIfmnvaGVpZ2h0Og=='), Suffix = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('wIDiDHkAoLnlURFFcdDNNopWjLdTKXkHavaNQNWARYDpfaNDTPmEndXbQ=='), Default = 4.25, Min = 0, Max = 8.5, Rounding = 2, Compact = false}):OnChanged(function(Value)
CurrentSliderValue = Value
if LongNeckEnabled then
game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('mYsKinySsVJKpqkgiciMttNkLOZfaAyavnSGwDIMgBBiJsvLyqjYBgKV29ya3NwYWNl')).Ignore.LocalCharacter.Bottom.PrismaticConstraint.LowerLimit = Value
game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('yGURqVXhhGlozTjofHzpfqetpinbGwrTSDLsxFbAWQijlmJmgcXVLmaV29ya3NwYWNl')).Ignore.LocalCharacter.Bottom.PrismaticConstraint.UpperLimit = Value
end
end)

ExploitsTab:AddToggle(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('iJnEzxnaPFmKNmsrPTlrGwaQfFPVgYVRxnaUOSSNmZkmQAmzGxOlTHj'), {Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('ITFLVSrTqgcWRxKwPGIlVMuSjXdvvjjJGLUPLSplGFkfBGvXBYFkQWwanVtcCBjcm91Y2g='),Default = false,}):AddKeyPicker(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('svEVUlxqvIbZdcsyheFCrOYhUHknhQbsBBBYUrlWJIRwNjJNUFNjCKlSnVtcENyb3VjaEtleQ=='), {Default=tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('LOOdjDjmNOIPLIKPyDaZaxaMBiMAOhbGWbehgFgUqOQFfwGDyeiHfuiUQ=='),SyncToggleState=true,Mode=tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('fTdYihLPzWBxFttagmbLNiqcCKKJmZMKQzpoSjnwyXuamGxPRuqVoxAVG9nZ2xl'),Text=tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('hgPTdRoTTHjjJIJbmLWNBXgubaPjCBzZRFOxRRhggkoqXiRoFlpexAhSnVtcCBDcm91Y2g='),NoUI=false})
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
antixray = hookmetamethod(game, tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('YvVnmYazbBdINZSFulXwNuUYjRigzhQbGzzgxuigJXZLbJZKbHxUphuX19pbmRleA=='), newcclosure(function(...)
local self, k = ...
if not checkcaller() and k == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('OdExhwGDJIlhcUAYQPIOOfQKxlGOfJXhCdagSrqHmAnPwWigWciWrgeSGl0Ym94') and self.Name == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('HPlWJyDYcybLNSroTYsYutGbIaxjTErTVwbsTKFxWepMRWgYrNMspnkVHJhbnNwYXJlbmN5') then
return 0
end
return antixray(...)
end))

local XRayEnabled = false
local CurrentSliderValue = 50
ExploitsTab:AddToggle(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('fwwqqYMTnxPeRIlpCySmLLAGCUbPrWBuQSLTeksWdblqJyCtanaQSKWWHJheQ=='), {Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('JFZulKtbMWmPppfuhxHOthbXNrCVETGPcJUhZvnmTuTZzgQufRckHysWHJheQ=='), Default = false, Tooltip}):AddKeyPicker(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('GshVQTYclynNpNWNvgITSYaZcrWgqPrsCbnJousZDPijsFqXmhgEwwlWFJheUtleQ=='), {Default = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('emYXveiZSVoMJOUKfxSSKhGuJXYLYssxTSvyrjzzkejmAEXDPVbARpzTm9u'), SyncToggleState = true, Mode = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('GOOzoLNhFitUrqQXyLqhTgZIbGfsmArZrOdKyEdOshAJmuoYLpSmbwUVG9nZ2xl'), Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('ipbHrvJeEHZyJLUGFShyVSSZShvrtYJnooryAqPNLiGFHpJHkjpSuQmWC1SYXk='), NoUI = true}):OnChanged(function(value)
XRayEnabled = value
if XRayEnabled then
for i,v in pairs(game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('KqPWkeSAmijBJCQjDGIIwzQqxIgGIBotdPifBjecXdhuHpVgLkhDAfzV29ya3NwYWNl')):GetChildren()) do
  if v:FindFirstChild(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('NinUrumGXhMvKfweUBkaqHAigjjZYXQiXUoBTImPjdjDiJKsXbApeUoSGl0Ym94')) then
    v.Hitbox.Transparency = CurrentSliderValue
  end
end
else
for i,v in pairs(game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('nELaqTGUtapsldRrbpZldurSQrxqxqnCqgxeAQroAadzbiOgbUTzOrtV29ya3NwYWNl')):GetChildren()) do
  if v:FindFirstChild(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('nePNuWzMhDuweMFidGmgZotLgiioZXJuEvGAxjpAhQybFzjLZgfoVTFSGl0Ym94')) then
    v.Hitbox.Transparency = 0
  end
end
end
end)

ExploitsTab:AddSlider(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('mDpAKtnfrSahsxwvZehoRBOlOyDJlWhNPBVUcIDhKAYqUGpTyOjbWoZWHJheUNoYW5nZXJTbGlkZXI='), {Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('RrPcpRqShrLEUwOXAWexxRNwvPLXMjfrPMMqIcogCwDrHBrxDMvPHGcdHJhbnNwYXJlbmN5Og=='), Suffix = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('FTZrITLbfkQiECnGZegfqYejWFqQEBNhSenrKENUMIxFqzgYjRXyqIIJQ=='), Default = 50, Min = 0, Max = 100, Rounding = 0, Compact = false}):OnChanged(function(Value)
CurrentSliderValue = Value / 100
if XRayEnabled then
CurrentSliderValue = Value / 100
end
end)

local ComExtraTabBox = Tabs.Misc:AddRightTabbox(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('JnVMHqUFKPxjbPPPIvVAnklOFYDHPtJvynSrNMvUJBfTpABFnygsrvlZXh0cmE='))
local ComExtraTab = ComExtraTabBox:AddTab(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('SHEvdOSLCRxZulExVsFBrjORrccdlglentjMWrMtkWDHjvdvDRjmwSMZXh0cmE='))

--* Extra *--

ComExtraTab:AddToggle(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('QVMUGTHXrykYjIlCshvcFeFMPmRmBWviHIMDqiszEfjbPtyyRXVDfBZQmxvb2RTcGxhdHRlcg=='), {Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('nXcGpGgNEeLHzFKDqQLWiGatsVmHjWQQKpwTtDSvgBKsQpHBvMacpDBcmVtb3ZlIGJsb29k'), Default = false}):OnChanged(function(BloodSplatter_Toggle)
if BloodSplatter_Toggle == false then
game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('vlBlsVAKtwNMSDjHeekBELWMuIYPojrOlCDQGVuLhvWdLpEGOmzcxBQUGxheWVycw==')).LocalPlayer.PlayerGui.GameUI.BloodSplatter.Visible = true
elseif BloodSplatter_Toggle == true then
game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('gweIcjbTqaRUWrlIzxyfJWrhGtrACRUPUmVmFSzsvFWxvHeFzmmFVODUGxheWVycw==')).LocalPlayer.PlayerGui.GameUI.BloodSplatter.Visible = false
end
end)

ComExtraTab:AddLabel(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('QNadEDkYyVYtTIUIccSZXTTpqatHHEWmllFzlblhfJhZeMAvCmVpHGYbG9vdCBhbGw=')):AddKeyPicker(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('CHtfHrREVMRMgIKmWeFNPgnCRJxDWPidWnxRgzBelBensKXnuEPkxVUZ2FrYg=='), { Default = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('PcOxMytpmQAZshYpVXpdlQpleEkvtnhPIFcqpqIyYIBwAGjOChtxThGRg=='), SyncToggleState = false, Mode = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('JtuwFjjvFUtPIJCKvcfajGubJRHfBpoAMOlQPRDohqJdMgUARTuRiIDVG9nZ2xl'), Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('zWhkeQBMJYkuzxOLywSjlGCwUuCUoHwAXfMtpIYordjApxHTVBLKWPqbG9vdCBhbGw='), NoUI = true })
Options.gakb:OnClick(function()
for i = 1, 20 do
wait(0.03)
local ohNumber1 = 12
local ohNumber2 = i
local ohBoolean3 = true
game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('hxzdsryqqvCJQMAeitXBkgnRaKQIrrXNkSqXsSWmxParzyaTlLcFsuAUGxheWVycw==')).LocalPlayer.RemoteEvent:FireServer(ohNumber1, ohNumber2, ohBoolean3)
end
end)

ComExtraTab:AddLabel(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('qMnlPYQmHFfGxFMGUxNfiOcTUZTGvkyncweSlNnCNagNHzwjOXckhHTZGVwb3NpdCBhbGw=')):AddKeyPicker(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('quuNeJDmsMnkmonhRFZeZyVUFPJIuWyTSkrRyWqgUmEtEpbLyHgndwEZ2F6a2I='), { Default = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('BegNUBEkSmTxNpTYEIvTcmQuTTKkvZyypRAedynxAnbbYCvdvYFFBrDTm9u'), SyncToggleState = false, Mode = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('EXMFliMUshmxUDZUUlaLAThHXJazEVbSQMMpmuOfDeguULhRrRJaGvuVG9nZ2xl'), Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('nslGoPCYNsPZnRvAuiHXtRFBELTjrWiDRrRcTeYNTStpGGyhjqJcnTEZGVwb3NpdCBhbGw='), NoUI = true })
Options.gazkb:OnClick(function()
for i = 1, 20 do
wait(0.03)
local ohNumber1 = 12
local ohNumber2 = i
local ohBoolean3 = false
game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('KRzdbnNQuiHgqBoSaLVpjMvcTJNdSiwufZuiwzeJktSuNLJzSgkfaLQUGxheWVycw==')).LocalPlayer.RemoteEvent:FireServer(ohNumber1, ohNumber2, ohBoolean3)
end
end)

--
local HitboxOverrideTabBox = Tabs.Combat:AddLeftTabbox(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('GvNJpFdvXFNfjBXhNNhvpkRSXlfkBesWuEZWawnawgpESDfiguPIwlVaGl0Ym94IG92ZXJyaWRlcg=='))
local HitboxOverrideTab = HitboxOverrideTabBox:AddTab(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('skAQhOJERcNBNSSWjrrxMJTBEQpEkBqOUxZQMtzwMXiFrdinPOdbkBxaGl0Ym94IG92ZXJyaWRlcg=='))

--* Hitbox Overrider *--

local HBO2 = false
local HBO2H = 100
local HBO2P = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('LAVPXTIXbaBGeAQLkXKAaiDUxoXFEWSFBlOpXjaykTSeJqwJuVqudfCSGVhZA==')
HitboxOverrideTab:AddToggle(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('PycAaCBvNTLLMqFWxdYTezLqSStYATFrKsIUuERoyOLuEldrradzCut'),{Text=tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('wIqGZUrXLlCudbXVyQqcpIJlruoyLhtbzZanGFsHPrGPtRxDAHDPfAbZW5hYmxlZA=='),Default=false}):OnChanged(function(Value)
HBO2 = Value;
end)

HitboxOverrideTab:AddSlider(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('lVlkRbOOsQYdnWIFMKAjJfIaXnqaIXyxJiRrtjnbOlvcxTsdEFfXamc'), {Text=tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('NrpwpCIPkdFQvPqlzBZaoPUbGYHJPWGRIircrMqPIpZMlGUVrSDHZjQaGl0Y2hhbmNlOg=='),Default=100,Min=0,Max=100,Rounding=0,Compact=false,Suffix=tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('pMRpPZvYPoOsMRvgvFZzgYBcCpemAPsblolkfELYYzNZLCUtJIPwrdKJQ==')}):OnChanged(function(Value)
HBO2H = Value;
end)

HitboxOverrideTab:AddDropdown(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('DxggHcMcNAJnBglPuXAoXjDuWhneKnTJLqiywsaajcahZvllPCjTcDn'), {Values = {tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('QuRsTblUfapMtSJCqPyRlkiUHJuVUHshqiOSWXvBqLAJhvPHOglNHmpSGVhZA=='), tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('MUcMzMHLldxBAOfQyRTTXDxcYTaHNnJfxeRTLKUmZhUqRJRXEltnjxHSHVtYW5vaWRSb290UGFydA=='), tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('bdCJchXkvinKcTRBeQbAdHuShuWOZAoPkADOwLybQTCiIqVOhvCLSouVG9yc28='), tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('WrzcbSspYFXuAbGunaLoMlsTVWkqldIKqePTDCrQxUuXZXwdqCGTYwKUmFuZG9t')},Default = 1,Multi = false,Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('WPeYIRPBwOZtHtERDWmMGelMThxZxwEFxoDAhdCkDnwJfWOvIfGklooaGl0cGFydDo=')}):OnChanged(function(Value)
HBO2P = Value
end)

LPH_NO_VIRTUALIZE(function()
local Bypass22; Bypass22 = hookfunction(game.Players.LocalPlayer:FindFirstChild(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('JknVTZjnlxDTgqeuhBOZjpoYJoLqAmlKdzSJJpjdotlJmvLpattyouNUmVtb3RlRXZlbnQ=')).FireServer,function(self, ...)
local args = {...}
if args[1] == 10 and args[2] == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('bMYQUxeNsUQlwCHNZenYCnnKUOvVawcilvMRQxRHyhZnBCvUfsIDoghSGl0') and (args[6] == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('YZbWNsXxwIZFjULLNWLxoDblexUCmRsOHvzeOaKPmpGCxmwCDVrCCziSGVhZA==') or args[6] == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('tEekbYLurJfaZKpLgIPpeQaxhUMtGKJzsoEBDfZZbLWCbQpdzhfuyVjVG9yc28=') or args[6] == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('PklsxEDepGPDzwXnCYZXZaaswxIAvdeVizMKphlumKCMVjITRGcfiwYSHVtYW5vaWRSb290UGFydA==') or args[6] == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('OoPAOTBaAjcpDfOffLjlXWUtWYTxUtsGqHwkRpzcQlunwmMAWeaSrsnUmlnaHRVcHBlckFybQ==') or args[6] == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('cLSoKMXTEylpkUojtaZelPQqTuOyhuUCVbbriIAFPqKoMIgeYABamJJUmlnaHRMb3dlckFybQ==') or args[6] == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('ldrtAUWVOWKePJlQuDjwqsOechhRrsgfbgJjdklZNtJqhgznCzpxJEUTGVmdFVwcGVyQXJt') or args[6] == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('LRFNdjckgHOPynLsRMUAuqPWiDuOUJvrSKzUUdjjrKwzpCmJSMSlwwmTGVmdExvd2VyQXJt') or args[6] == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('RPDsdDXHCFTsEknTupprDxpkugakoeqiJJpKgbXLkPqnEHJXJsiVkhKUmlnaHRVcHBlckxlZw==') or args[6] == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('jFAAaOdHkGvHNuqndYgvhFIjdDWbNtVBPdxeBTZwnjAdeTEYZgJkBrOUmlnaHRMb3dlckxlZw==') or args[6] == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('IjpknlNuYdyVJJwAoYoUqbRZrixUtCHQEOQugfwsXbAosrbUibxBWlSTGVmdFVwcGVyTGVn') or args[6] == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('bsBZVWuyiAEIbfOLFZpvrelGiNMwHuzoGYVNDwBwmjYrQMDalrCsxVmTGVmdExvd2VyTGVn') or args[6] == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('MUYnouHrjyZPcSVXQWCeCjycTWgriQYLDPVEYjEQGwcVcdmbDVHeBfKTGVmdEZvb3Q=') or args[6] == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('lAnxLHmrsQvZuBFtALLxKpWHmivUpRjXLJCgvjdUdDcOpZoLSptfaOIUmlnaHRGb290')) and HBO2 then
local bodyParts = { {part = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('aaEaLLhnueDnqxIkjArZIZcNGNTnzLDeTTshZSFsBeCnwlgjfGWjszXSGVhZA=='), probability = 10}, {part = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('wsfTxJVxoAnNpHwzDuJzwVFwMnzYluyGELQtepyxmcilfhJxfeuAupXVG9yc28='), probability = 20}, {part = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('fPXVdslVKzWPScHnNkvVRXEtzeuTCkPTIKhjIyCGkijHRPhRIGMlzqeSHVtYW5vaWRSb290UGFydA=='), probability = 5}, {part = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('LBJTGYAjycRIalSvBSUwzPvotBwEnHZTiheeDghhUeLqfekzDpScxflUmlnaHRVcHBlckFybQ=='), probability = 15}, {part = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('HfnVOlJwmPCrpDxrOWxsZZnLveRnbsCfkzrMFtyOgBpgMNeaGwZIGSXUmlnaHRMb3dlckFybQ=='), probability = 10}, {part = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('cjJfviXWvpcfAxtgSYLljSBdUJOvIXiCYbOImbnOsseQykgJexwlrsuTGVmdFVwcGVyQXJt'), probability = 15}, {part = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('xeSRzTWtLEQrgrEYkYLUSmvuxNtKHhPctCMliynBsELkpoOjFVadtoYTGVmdExvd2VyQXJt'), probability = 10}, {part = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('XpoIYMQlowtWCpvaRozGQXfGoFEjOFaLJsfMmtioEzmBDUgxdtYXdPpUmlnaHRVcHBlckxlZw=='), probability = 5}, {part = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('GlmqJCtlBMNifNiUvKKWggpucrxffNqcrhgKRRLEGYvzdxXNanmnfcrUmlnaHRMb3dlckxlZw=='), probability = 5}, {part = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('dWWaiNfBOfrTeTkoQgbouvDGiTuCdelRIcwgJjzUTYgAEHAtGyqDLAlTGVmdFVwcGVyTGVn'), probability = 5}, {part = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('WLrdlpuJGDZwxpGzgHumzAPeGeeRmRpDpaHAizTFViFaLIPlJDVDJkzTGVmdExvd2VyTGVn'), probability = 5}, {part = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('UwnXEPWhHqtjbhnaIfDQOVlIIUyUqIGlVyuDURwPwtXNnchTIggZgYdTGVmdEZvb3Q='), probability = 5}, {part = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('FhFEaVrwfvXZNTJYVyEtkIBatUJISsTgDCQchgtiMVmVipKifKTCzXRUmlnaHRGb290'), probability = 5} }
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
	if HBO2P == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('MpYhvwbVmwjgwziisfdGOqwzRtMGCSVXIPQxgOjFbwRwfnfbHbmPlQqSGVhZA==') then
		args[6] = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('AegKzexuaSrpLhLbnbOagfdyUPoVGMtmIofIBjtRYJrzElbpRrwIZQuSGVhZA==')
	elseif HBO2P == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('BfgXOAktJokDDJbVNrcNZxSrhWWsMJkgEBUrJPrhsMSsHPknsqweUTtSHVtYW5vaWRSb290UGFydA==') then
		args[6] = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('XQkgXRTnLNZskahROZSLiwnGoMyUGTSnGDDJqDIgbgzvjLzxnkUNTynSHVtYW5vaWRSb290UGFydA==')
	elseif HBO2P == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('ZKiMJViyriroAaiAIsmzBoAAUQoZhEnBoWHmnbmihqpLbWZJAKWTLhmVG9yc28=') then
		args[6] = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('fTRKgFkbrcPRSZFhVkScrYJRjXzymkDmCxZLGNqDTrIztwAYyMMobWJVG9yc28=')
	elseif HBO2P == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('vppFZKdEEYberuOGcNvjlRuPHTZguqaNkNNaYfSDyKRZWbEgMvCTGqaUmFuZG9t') then
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
if args[1] == 10 and args[2] == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('RqocgHuLFsElXRODYwBKsKDFuOcQzSEqLKYgVpksnTJJGPyNHfphEsJSGl0') and (args[6] == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('nEkdUNOhdkppCmlACYINiGtpoVtcZyqcfAezGKSPPIegtqCzBHHcfMJSGVhZA==') or args[6] == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('IPtSEnMNNMGsjdNWuJyiIQTBmRkPCYmmXeCuHWByIRsDLgXfNfWWbrUVG9yc28=') or args[6] == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('QbBuZrRkCCYbGZRQdiGQnxOKCBsvhRVjsyWjFtDKpNkRorJGyOIZpDFSHVtYW5vaWRSb290UGFydA==') or args[6] == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('MDuxIvByNZfHBWghbMTToyFrAtDVbjfSLbbnoBVKbLpxJwDNjlQNLmlUmlnaHRVcHBlckFybQ==') or args[6] == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('QOAJhnJIxAZFuVpvNjdgLLGcmErzomwkywGPMcdBluNvELnWlYlhtneUmlnaHRMb3dlckFybQ==') or args[6] == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('cKhOVMEMjBhrzyrqoNqspZoYTvXyQQdDFlHSJLkLwVcEzMgwIfzPLvGTGVmdFVwcGVyQXJt') or args[6] == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('IdBqXxhcRSVkBdsNsTvxVBxucNPzVbJiXZGSXWnCnZqAqClIscKDZbNTGVmdExvd2VyQXJt') or args[6] == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('OUjPCSoPfSSTUqyGZIyupBAUBGAyNjhenulqhqLxoBWcHUzEjnvfvaYUmlnaHRVcHBlckxlZw==') or args[6] == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('ALxlPWaInIjZCYbwWcMUABSkZprMCUIGMhdtrcKfXxIvTnltDnWmeVVUmlnaHRMb3dlckxlZw==') or args[6] == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('tVOssasFGfUqXVhhLwdKqNMJxuKMdlDDcgjQWIqAlhyxTwSraVcbiNvTGVmdFVwcGVyTGVn') or args[6] == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('NmydGhdKRFWztqsMVWxdoaXkPzpPgqcPvzeLrtNBGvNyPbxdCKtAGArTGVmdExvd2VyTGVn') or args[6] == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('GwYtGBYANUJlbgvueQMTHiIWKVWjOglqVowdzasuYeXcVJaTsCshxWrTGVmdEZvb3Q=') or args[6] == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('kkmynhLYgFfQmrdOxfvpMNISXEBVmXzmDWoOCjtwXewILqBpaKiQjuhUmlnaHRGb290')) and HBO2 then
local bodyParts = { {part = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('qYPWdCAFNjzVvwjBDEroiKaHdXgaFFWVbkspFGNwHrpNATCMsYybzBqSGVhZA=='), probability = 10}, {part = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('NjguSloOdiMKsJdOWHAvAGnZyBwjpDMIwoPGCwwmhUHrWbKyDWyDXUvVG9yc28='), probability = 20}, {part = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('QZbpAHtXfOdJJGJtijhwUUEmVsanEhRfoZXwaMbTxzXRddmpjKpQsbPSHVtYW5vaWRSb290UGFydA=='), probability = 5}, {part = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('tfcvLwoouWrwemzwiUctLEtrvYzjDvkQWZJzYIrCEMHGqWLQjVHZZIzUmlnaHRVcHBlckFybQ=='), probability = 15}, {part = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('FuSZbHTkluulmXwSVjrAEhtGeQtxgeRYLmxJUzkRuCyWXUsGrGIbyaSUmlnaHRMb3dlckFybQ=='), probability = 10}, {part = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('FaFLKMAZIJHEtnHFyIQMelpPADtwmVLojFuuFxdOnfCSrapMStIgwWKTGVmdFVwcGVyQXJt'), probability = 15}, {part = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('mvMgprSrngylJEkKOSuHwPZetJNVQaMvzNtOnCWhZeitDMSclXLedNkTGVmdExvd2VyQXJt'), probability = 10}, {part = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('fzyCQIDuveCSTXPxSkgnIMaMsWZwVugOBuDSihORoDldqhAHtqUmONZUmlnaHRVcHBlckxlZw=='), probability = 5}, {part = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('CFQagGpMtNOevNcdiQeGwnXyzYuixYohVwTEiBSsYNRJaJvfqbZxMbwUmlnaHRMb3dlckxlZw=='), probability = 5}, {part = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('vXItlwvxHjFEnOzJXviNGNTcTWPoBlTkNBomwqNZbttTWGJEJaafIwLTGVmdFVwcGVyTGVn'), probability = 5}, {part = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('cKJvmetmIZyusIEhzeCEmhBsQTrOjEiIJRMAzWaabdGyROnWDzZEFkLTGVmdExvd2VyTGVn'), probability = 5}, {part = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('GvxOCrVpKKPGCxxjrMXuJwoZemwvUVLgfDOqrHkCHZQBNGIJoXuROYUTGVmdEZvb3Q='), probability = 5}, {part = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('vxpuYvjkjzUBlOqpSxJXzKPdWGCghXGxtAltrvvMaTLkvkUnLqkayzHUmlnaHRGb290'), probability = 5} }
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
	if HBO2P == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('QOkBcIckgygugLygEdmzyBkgSaWvxwbAYQnoXsJqaoNqrzobhkQOnoWSGVhZA==') then
		args[6] = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('rfoQVxfbzeCbQvUeKKNdLiYZDSCYMKGCmSUElhvGvHViPUAiSHrAGgeSGVhZA==')
	elseif HBO2P == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('nZcolqghfQqwWPdSMvhoxRKaAbaPxvQeHbzBmMZKnvWHNyZQvtHTMhQSHVtYW5vaWRSb290UGFydA==') then
		args[6] = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('ckrdMmcsmbKZDoxlHQwRjdFQZwVHzgcYbeMivYeKFEsfaUWCSNRKbbnSHVtYW5vaWRSb290UGFydA==')
	elseif HBO2P == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('CSrFHHvbmxMJchzNikINEpQfbStpFvjWdaLPlZSEqicGTKaOjiZfwJhVG9yc28=') then
		args[6] = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('ZmCpxiDjDnHuBciGdIDiGtrkopTUSSUSRDSeAWvmjoydBlwkIdsgdqjVG9yc28=')
	elseif HBO2P == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('pDmaCehlVornAEKgOlMEGXRxRcjgcuvMyZmwxdrCDbaxyMnKbWJIadiUmFuZG9t') then
		args[6] = selectedPart
	end
end
end
return old(unpack(args))
end
end)()

local TrashTalkTabBox = Tabs.Misc:AddLeftTabbox(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('LezXOQRNDZfoRXSXqjibiztzHtWWoOciVoLlFgfdKayOeKFXhvcABejdHJhc2ggdGFsaw=='))
local TrashTalkTab = TrashTalkTabBox:AddTab(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('IZjbkMfIGxJsnWlduiyBUkWPYZQnzHyblwnPdrbRNJNbNLhWIguBxARdHJhc2ggdGFsaw=='))

--* Trash Talk *--

local Trashtalk = false
local Chats = {
[tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('HclbhkjxRiXAHoqRLFGzWaOzhdKbnHgBjHIGhvzGlLgTWXouYuUQMfkc2thZmZm')] = {tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('eFJBKbjFazEuhHaQTwKimUfKhZvCmjIRTioJWgzStBoDInmuPiJeusec29ycnkgYnJ1aCBza2FmZmYgb3ducyB1IGZy')};
}

local _Network = getrenv()._G.modules.Network
local _SendCodes = getrenv()._G.modules.Network.SendCodes
game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('unCWbUdhrxXbwiIqDPVegXsqOsJxpUjFJfaCDNKdJEBKzqQphkORGbjTG9nU2VydmljZQ==')).MessageOut:Connect(function(message)
local extractedName = message:match(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('lwRadTcgyqMxMpFPXAkMLgnPUSRUAlNoEMHUufjULyImvLETvDyBVuLLT4oWyV3X10rKQ=='))
local initialHealth, finalHealth = message:match(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('jnTsRUHLMNDJBGCmQnBSKucVIDlyMFLGBRLaPYrWATYLgiNECsrOHWWKCUtPyVkKyUuPyVkKiklRCotPiglLT8lZCslLj8lZCopaHA='))
local studsValue = message:match(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('nutCsErIhurqygEFpvBoetjKKrZvgEgswHMvrCTDqMeLRBdJQNbsntgKCVkKyUuPyVkKilz'))
if Trashtalk and extractedName and initialHealth and finalHealth and studsValue and extractedName ~= game.Players.LocalPlayer.Name then
if Trashtalk and tonumber(finalHealth) <= 0 then
  _Network.Send(_SendCodes.SEND_CHAT_MESSAGE, extractedName .. tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('DIHFMOgOOXWWSiZATFOcVLSIQCiBJjXhSTKCgxenGGIvMPfEEoVCGTyIGtpbGxlZCBmcm9tIA==') .. studsValue .. tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('FlLwtKvDMOODdpRKbeXdbLnRFhHWTINeksfgKsTqlUhnujzPTEklZzlbSwg') .. Chats[tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('BrcVrOdBPrbknbmMjawWYOWjwqAsXnzZSimHGuevFQMcBwZwgqqVVLHc2thZmZm')][math.random(1, #Chats[tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('cSUFBlCIxlSTfAZwEqLArLOIDoHDiDxyRzkPiaPyJfjXiuSWPgHNUrLc2thZmZm')])] .. tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('iPxLDpxRxwoOHJlvfWbDnAglWtbhtleLolLmZUGNoGeZCYcrVkGAAsSIHwgc2thZmZmIG9uIHRvcA=='), tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('VCVlsmExUlgjCVJsJzAoSelAIDPQnpGqobkOsyWeRLwgAWyRVVmHkwER2xvYmFs'))
end
end
end)

local enabledspamchat = false
local chatSpammerText = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('LIzHoLPHHIQGARIZmbvlrFDbAbcYuqhqSuMeLwfsfkNZRtHETELzDWx')
local WaitTime = 3
local function spamChat()
local args = {[1] = 27, [2] = chatSpammerText, [3] = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('psFhbFPGEdUkkLmTIVajeiEnIvbVYvOpPdnwEXeSSEHzzjFOPrEIdHuR2xvYmFs')}
while enabledspamchat do
  game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('WVOuKqdXILSWgwNzLOAdfhfTGQjrcGmWtoRgClZPjkwSmKvfTqQypIKUGxheWVycw==')).LocalPlayer.RemoteEvent:FireServer(unpack(args))
  wait(WaitTime)
end
end

TrashTalkTab:AddToggle(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('TNZgWyqAtOuLQnbYWTecdPoMmtsMUYsXubQmBryaBhHImsLyXezEuuSRW5hYmxlZF9Ub2dnbGUx'), {Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('ybYYOencrceGfDTEKCFlWnzKeickRGzWpGhSqFlRMbJeaZEEQcBJokqZW5hYmxlZA=='), Default = false}):OnChanged(function(value)
Trashtalk = value
enabledspamchat = value
end)

TrashTalkTab:AddDropdown(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('jcKUXQyvmCcRTzXBdELGBXuzZxicpFFRTevZFeQPIeMmeUMWbwAEokA'), {Values = { tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('eSOkhvhGjQAkOwwtFwXWBzltenozGkCeNrGmMZFlBzoLsgpuYYpRtpETm9uZQ=='),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('yuATfPxHREEeXktpIqgFLnTawZnihQWjHmqLGeoaXcsWdpJFNRZvpSpVHJhc2ggVGFsaw=='), tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('MNRcscVLivHuGTmgZMLnwERXSntMuLkKMHPWiQYWhVszBRhNQWUUWfyQ2hhdCBTcGFtbWVy') }, Default = 1, Multi = false, Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('fOlMMaVRbqnNELaxMXZeDRHZgCVmQSJYTiTXYSxpWXpRbiGJWFwTyUxdHlwZTo=')}):OnChanged(function(bool2)
if bool2 == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('AYoTwrItGrVpcCxVjDjGuNCPFMPJMfyIUMOjioBzmYIfSJgoeMLXuNBTm9uZQ==') then
Trashtalk = false
enabledspamchat = false
elseif bool2 == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('bbFHSxcXzrJSyabJzEDjWFynGvxGctnDNGstPZaSkenrZVeDFbXOnYcVHJhc2ggVGFsaw==') then
Trashtalk = true
elseif bool2 == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('hgekdYLbkSccXGwdbomyOYdCNLBKgNaGtaXebXURsmnhxjvGIHYoBxKQ2hhdCBTcGFtbWVy') then
spamChat()
end
end)

TrashTalkTab:AddSlider(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('GpFBhTKCGALmlhPJDODsGuSdpIlYBOITanKmINMkLlEZzfKLvfknIgIU3BhbUNoYXRTcGVlZA=='), {Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('gGSxiAQMWVTzPIwecrqStjqYElhrBUzMbnChLlMWQAiYGwQrasltucKc3BlZWQ6'),Suffix = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('mEIaJiISRxenWDFdeDLGaEHjtkIIyaMNPwPMiEnzkVXWQYmIqcfOYJJcw=='), Default = 3, Min = 1, Max = 10, Rounding = 0, Compact = false,}):OnChanged(function(SpamChatSpeedValue)
WaitTime = SpamChatSpeedValue
end)

TrashTalkTab:AddInput(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('mmCxiCMRiLADlnJTJxiHUOMEYhCbMYytiEpLxGYpqWyTISFOBQuUavtQ2hhdFNwYW1tZXI='), {Default = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('riioRDjipgPpZwCNfskSsCDzTDccgEgLiQhEoisqCEFxOkctWlSkxsGSSBPV04gVEhJUyBTRVJWRVIu'), Numeric = false, Finished = true, Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('vyVikkoQbXmioSSKoHsbBuPaGLOTgmDXGKhfVaiFOVSPxPTeKhptuurY2hhdCBzcGFtbWVyOg=='), Placeholder = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('pGlsxFLKlfmziOKhVYXnSzCDQDtwvTnhzxyOpLwCOVgymyqklMKiohgQ2hhdCBTcGFtIEN1c3RvbSBUZXh0IFtIRVJFXQ==')}):OnChanged(function(value)
chatSpammerText = value
end)

local KillAuraTabBox = Tabs.Combat:AddRightTabbox(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('NuudHbwFzLnaXmRqfatxKngyoFqgiuDrWgQbAHQHoqYDEKzzqveHkKia2lsbCBhdXJh'))
local KillAuraTab = KillAuraTabBox:AddTab(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('GrMVWVXGKSyUmIRIpwdEaQDDXTPZDzDtKKQrKILvRKfkauYLWCAiwyRa2lsbCBhdXJh'))

--* Kill Aura *--

function Functions:GetLocalToolName()
  if getrenv()._G.modules.FPS.GetEquippedItem() == nil then return 0,0 end
  local mod = require(game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('xtBVpjOZAdBMlionqPuzPSCzloRCieFEJoUPdtJUwZVSpZMYWReuGPJUmVwbGljYXRlZFN0b3JhZ2U=')).ItemConfigs[getrenv()._G.modules.FPS.GetEquippedItem().id])
  for i,v in pairs(mod) do
    if i == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('WxdkQQpePDbxfBNnMTWfNXvwdamaOeiKWsUEdOMlZLvrrjwaghXVzveSGFuZE1vZGVs') then
      return mod.HandModel
    end
  end
  return 0,0
end
local killauradistance = 8
local function GetPlayer()
  local closest,PlayerDistance,playerTable = nil,math.huge,nil
  for i,v in pairs(getupvalues(getrenv()._G.modules.Player.GetPlayerModel)[1]) do
    if v.model:FindFirstChild(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('HScUzzbdCsWdhlmqeTdQhhpiQGzZBLdteqANexgVsiKigPPNENeJGZmSHVtYW5vaWRSb290UGFydA==')) then
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

local KAHitPartSelected = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('yShhspQzlFcradiKPqTYJogCPEhCPxvYZKEXAfCrxpDktVSvglXJNozSGVhZA==')
local Wait = 0.95
local AuraGoodToUse = false
KillAuraTab:AddToggle(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('BglZUFVnBdxXsVmzguMvsmPPEhdriuvRtWZfLOpMENGThIeHjMBaVMmS2lsbEF1cmE='),{Text=tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('VdWYUlrvxtvbNlLDyYtJfPebJuPNOzHmrvRUcKNEUWATFCvWRjSyjtza2lsbCBhdXJh'),Default=false}):AddKeyPicker(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('RjtGRMVCECJGyKHxSfSMYuifWjAwGkZQNFUrZNWStHKdNbOZbLDrphtS2lsbEF1cmFLZXk='), {Default=tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('ohLBMuHlrCmkHjvpxGtJUQzoqdiyJRQwUUDdTmpsEohqPGfqmkZrdEYTm9u'),SyncToggleState=true,Mode=tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('vmLgkYdDKNDMRIsRAEILEoeYrzxjTeUsaJMLBZHXEozcBMrpKUbyppNVG9nZ2xl'),Text=tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('ICnyQPGhQmKHZhGviaqExsLLrNyssvVcAdBaZyZKfSpCwQkGvpMXCGUS2lsbCBBdXJh'),NoUI=false})
local PlayerID = nil
local Bypass; Bypass = hookfunction(game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('EcjaGjpGtvnAhZRSQaKKeFLayHTWtgOohyHPGxqpWqgqWCnPIjFSXpbUGxheWVycw==')).LocalPlayer:FindFirstChild(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('SUKlZzUiAhPOgvhqnYbvyKRNYfxVRIRnfWuubClfLajUjvkLmZUNxGvUmVtb3RlRXZlbnQ=')).FireServer,function(self, ...)
local args = {...}
if args[1] == 10 and args[2] == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('DBntXmpQBIHJJHzPSDTzApRlflpGsIInMYhaapouuloVoyemFELMTvBSGl0') then
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
      game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('gzPUchYOnJhPHWaIdLakaKKfmQmVzhIAghfRamldMEzZcsylCXUJCVLUGxheWVycw==')).LocalPlayer.RemoteEvent:FireServer(10, tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('egARINemNZTLRCdnlcMZPShfQyrVRtICwiMoyiQjfGtrItfVbyntueuU3dpbmc='))
      game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('IszqJYuUPfhMCPagPEgYMLdKcxVOWDAZjprWbfupPbrJXyIXdoPXgmzUGxheWVycw==')).LocalPlayer.RemoteEvent:FireServer(10, tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('CeDZyNwjWhsDDtlpzVISzMihnaRwrgderwlKNxwpNYjvTwhXMmURFzrSGl0'), fr.id, PlayerHumanoid.HumanoidRootPart.Position, KAHitPartSelected, Vector3.new(-0.1275634765625, 0.5433349609375, -0.237548828125))
      wait(Wait)
    end
  end
end
end)
task.spawn(function()
while task.wait() do
  local Weapon = Functions:GetLocalToolName()
  if Weapon == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('nNwqXaRMtCJJXlDdMcPukSIhgFygUvrfsvMvBzbdWASakEDSiMbahQKTWluaW5nRHJpbGw=') then
    Wait = 0.12
  else
    Wait = 0.95
  end
  if Weapon == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('fsrYypbzvGVjSJQQZHhtnJUkjAVrIAsmobTQIoCPuQqcMDhZZzvxBhPSGFtbWVy') or tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('hnYOKzZwXSTbNywGQVLoaWbQWjuByeMptVRuSuobDyGfRektJvEUGJTQ3Jvd2Jhcg==') or tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('yALhFeNaPhmIaauasggylhCNNFtUAAaJXHMUFMIQmfGmKVChuKowhWQU3RvbmVIYW1tZXI=') or tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('bPraEQLhkjrFEJvOekNOAvoSQKKCAlLwnUcjvZlURXJTFACAxmTlJwfU3RlZWxIYW1tZXI=') or tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('zZpEoSvYjSKiDILzdllblfODZJlFZjnsJKShLJrxNzCCuepUqbgJOpjTWluaW5nRHJpbGw=') or tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('FytzlmxTPakcTjvfMuYnhRpgZmKSuYaykGNHQsgXjhUlhFLCKMFAkjaSXJvbkhhbW1lcg==') then
    AuraGoodToUse = true
  else
    AuraGoodToUse = false
  end
end
end)

KillAuraTab:AddSlider(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('kcsZJfjChciHGAFnPDFrEiCovHbveJDGTlJKHKkxjRxynebGvzXpSSe'), {Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('RAgBzTcDUVIXobxteobrIbUzsrPHIcAtVGrxQtichvZJWtKfjzTklqDZGlzdGFuY2U6'), Default = 8, Min = 5, Max = 10, Rounding = 0, Suffix = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('dvqrNThQhQhMcFqKUNWuVyjaYTlXVFParGwGXzlqPZHgusLKenDRTIjIHN0dWRz'), Compact = false}):OnChanged(function(Value)
killauradistance = Value
end)

KillAuraTab:AddDropdown(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('sNRnqXTFuqvFKIdCBMKwTcFrHWMkPMYjeQvHFSHSzKHpoIkhqSsOWXt'), {Values = {tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('dZoeaKhTBiSJosgNzYYpclqFYdvMBizTuBvRyachJofHYDVIkTyIfSISGVhZA=='), tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('KVGUuvVFnZJnivCdAGlciHtgeNURMbWfipisWkdQBOXbKcAmhVDpxMUSHVtYW5vaWRSb290UGFydA=='), tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('PyzpnemahjKjsTMpguoYJAgTsqmWqBVeHKAyhebBoDVwrQPIlhkWXKXVG9yc28='), tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('TSHwlZjqXPQcLYSdOYAlLxCglgYWHYpqbTtHBgoHhsfURdSuZhloawRTG93ZXJUb3Jzbw=='), tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('njXhbbMlgEmfhNnyMPGNVPyCjwptKDjYxOTYApIXBxijtosiWcKrkpWUmlnaHRIYW5k'), tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('dexxduijkJoHRJWmbFKtpROqqiAhTankeHYxssNYEndPFVXzGZUWUmxTGVmdEhhbmQ='), tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('aFeGHIfwLpUPhROiYReraGjzmTrVHALzDoCbioNVEhArqvSSooYROXjUmlnaHRGb290'), tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('mUNokCHtfulThXAIYyopIRlxEJGwKruniwoejMdnfTMiIEdSXvsUifLTGVmdEZvb3Q=')}, Default = 1, Multi = false, Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('vtHpaIajCDdJYptjACAjzLYNgnjcuTUGjYcbMiMXLZrzKpREwfTGcpSaGl0cGFydDo=')}):OnChanged(function(Value)
KAHitPartSelected = Value
end)


--* Crosshair *--

local CrossHairX = Drawing.new(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('yayOnVEruUAQiywRvDfcOYdPdqFzkgzzxuTvktiboIyyfjiBKMPBKwsQ2lyY2xl')), Drawing.new(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('QkElKcXxdaORxVOZVLrUPAaWeYEjcKOUOjrhcOZvJRmBZZimhUFhcLOQ2lyY2xl'))
--
CrossHairX.Position = Vector2.new(Camera.ViewportSize.X / 2, Camera.ViewportSize.Y / 2)
CrossHairX.Thickness = 1
CrossHairX.ZIndex = 3

do
  ComExtraTab:AddToggle(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('MbcOSOuSRGdvrsuVBLYbiGoTuFkHnlYQxJqmIeURIxnBaFRIkbcgxghekNyb3NzaGFpclhfVG9nZ2xl'), {Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('ZHKJAipKvSkEVmDVipHFKfFfokxxktYTjLubgzemLCzogiSrewcBVbFZW5hYmxlZA=='), Default = false}):AddColorPicker(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('FHIpnNObsdyIABiFfPoFhLsGLgKSGyXDINxpbOCjKHBENuUiKHcUKbuZUNyb3NzaGFpclhfQ29sb3I='), {Default = Color3.fromRGB(208, 123, 255)}):OnChanged(function()
  CrossHairX.Visible = Toggles.zCrosshairX_Toggle.Value
  end)

  Options.eCrosshairX_Color:OnChanged(function()
  CrossHairX.Color = Options.eCrosshairX_Color.Value
  end)

  ComExtraTab:AddToggle(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('tJalfSFbeUBzODgVPtWFFIeYaVYQQnReKwFhnhUanBSfnDLscUJShmuQ3Jvc3NoYWlyX0ZpbGxlZDE='), {Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('SRwfgDcPtgKdEhppybrpyVKJyzAuZABJGuYUcDJhnLVwLQqCrWnNZnsZmlsbGVk'), Default = false}):OnChanged(function()
  CrossHairX.Filled = Toggles.Crosshair_Filled1.Value
  end)

  ComExtraTab:AddSlider(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('eEstrTAisCotEEGYmUoMeLBdbOkttvCovEebjYcrwJWIcJJYYLBlDsmQ3Jvc3NoYWlyX1JhZGl1cw=='), {Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('elsEVarULwESjsHIRjpnxkGfWEANfPrSBDmtiedkVMgWOwposBUXiRAc2l6ZQ=='), Suffix = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('KTEqCOIkoYOSsCnUZDtkZaWxuZeXjuQwrbGystpuXxYmNmCDhEbBhtAwrA='), Default = 2, Min = 0, Max = 100, Rounding = 0, Compact = true}):OnChanged(function(CrosshairXRadius)
  CrossHairX.Radius = CrosshairXRadius
  end)
end

local CustomHitsoundsTabBox = Tabs.Misc:AddRightTabbox(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('ZzSYfdkkmNZNwwoXKQGZpijJLeWvFAvVakWPmtjoCSzLSuyIDNVeGlXY3VzdG9tIGhpdHNvdW5kcw=='))
local PlayerHitsoundsTab = CustomHitsoundsTabBox:AddTab(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('XFSQMzxsogxuXNsjkkRcSCyeMGkQhZTVgtiYlzNEbZHQoQmNEWlfeZxY3VzdG9tIGhpdHNvdW5kcw=='))

--* Player Hitsounds *--

SoundService.PlayerHitHeadshot.Volume = 5
SoundService.PlayerHitHeadshot.Pitch = 1
SoundService.PlayerHitHeadshot.EqualizerSoundEffect.HighGain = -1.5
local sounds = {[tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('KugiYIKafQzXUfvQIiFtzpjiSGCSHwJXoVIksmhxCjWQhaAEBCcNPLVRGVmdWFsdCBIZWFkc2hvdA==')] = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('eEISjAORnrtOipdDdWJJrtgLJRTsuTuAJFgUbQyxTFSMaeYwLCzWvkdcmJ4YXNzZXRpZDovLzkxMTk1NjEwNDY='),[tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('zTXlYVIwshJcaYEaOrikBrZceRrKytzEUSsTYZugjqsUaoHqlOvIGDRRGVmdWFsdCBCb2R5')] = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('cobaRAtXcwYAWQbjAVZBqGBxFpVoUClvJZTQavaPtzQNGyenGMLuCVFcmJ4YXNzZXRpZDovLzkxMTQ0ODczNjk='),Neverlose = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('RadwgAfqPnnUlovitBqPgZaEOYWYDExBJMPmUhSCEigPDwzlRfhdqVRcmJ4YXNzZXRpZDovLzg3MjY4ODExMTY='),Gamesense = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('bZwusZdCJMiBKHorTakrCxeqIPatqYhFbhCtKqMWlMrAaztyWdSeckecmJ4YXNzZXRpZDovLzQ4MTc4MDkxODg='),One = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('IPluqkhcDTEnYxBLJqRiueLtOvUQgPrtsFpAYQSVTDQJPCPCJnZXvolcmJ4YXNzZXRpZDovLzczODA1MDIzNDU='),Bell = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('HmPIdaWBXBNNTAYolrwOqKVBAkICrCdDEcZDxzDrRDZVUeDyjzRiACXcmJ4YXNzZXRpZDovLzY1MzQ5NDcyNDA='),Rust = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('XLbcXqoTIDsCqNaIYjtqsKvpZOsphupiSqmYrOuKGbSactiIqSvdENUcmJ4YXNzZXRpZDovLzEyNTUwNDA0NjI='),TF2 = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('xUgDbqxitbwOwfDCgMjQHTSxGmsYuLZBAfliXDHhpJXFmFZdFfQhwPucmJ4YXNzZXRpZDovLzI4NjgzMzE2ODQ='),Slime = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('ZDBHICPAPgVZYqbZrLDLghghCJCPrnfRXhjkepyQRUhwnDXGRlmJwWccmJ4YXNzZXRpZDovLzY5MTYzNzE4MDM='),[tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('FJUHtCRZiGRDfjhiMaNXYquecDeKYTyPAddJlRLvyncOxFndjbGufmuQW1vbmcgVXM=')] = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('xJwkRJUgSXswFzsOJtPTHGxXCwHQUxoZUmbSsAqWncBqKBBMuctwbjDcmJ4YXNzZXRpZDovLzU3MDAxODM2MjY='),Minecraft = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('KgjHUWOBEUInEcFhCiJVaJxseABkOjnpTmqnCiLdNcUvOkvDgTqOTefcmJ4YXNzZXRpZDovLzQwMTg2MTY4NTA='),[tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('UNxWASnPndDLMYouvsjGZHfinTtTgptkIwoYWnDfKNaaQMOrqYGjopuQ1M6R08=')] = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('GGIyYXiSDHYkQxThUmnMjWWwfNIczsulCaLLodTjdvWsoORKOuGZxClcmJ4YXNzZXRpZDovLzY5MzczNTM2OTE='),Saber = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('YyAPtItaiZREvbRosqMxjmasMIVpthAABBsjIXJRcdocxQfZixyEwEGcmJ4YXNzZXRpZDovLzg0MTU2Nzg4MTM='),Baimware = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('NuVRULOckmIUVXipjAaafjXvOFHnGpjORPbRrZDIufUVuggczbZHbpucmJ4YXNzZXRpZDovLzMxMjQzMzE4MjA='),Osu = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('IWeSIzNDxALXfHwfzsVxhopeIbqMzYMbEAOkCzZkVCrDyYLdmTzUSvEcmJ4YXNzZXRpZDovLzcxNDkyNTU1NTE='),[tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('VXWPNBDuCmMqHQTqTIHxyraiEJRQxGXfqCZvtLkgIcAJMPCLoFPXYbLVEYyIENyaXRpY2Fs')] = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('xmtNpqvMytsmryntNbJtVGIduuErgqqSTjuhanuyZmWZYKhKLPVZlNccmJ4YXNzZXRpZDovLzI5NjEwMjczNA=='),Bat = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('wUoVFWYLUgffuyvuFDypIsieJXefFvoGNIanwPDwZgCZkhgYJsISRYUcmJ4YXNzZXRpZDovLzMzMzM5MDczNDc='),[tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('imSWgiuCtQzRgOPlShdgsGrrrHNQkIzBfpqnVZjkiJpxBpQCyUapTisQ2FsbCBvZiBEdXR5')] = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('ZkQnbtKArZARORsyaFJBbqRCKZTnuUyLLgZqRaiYNJPXsPzcmooyxCxcmJ4YXNzZXRpZDovLzU5NTIxMjAzMDE='),Bubble = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('DMjaliqbRxCXZEMHzqWqPdiVWXFCAbuGHQSrglNILNqqKcnXoxKtRbccmJ4YXNzZXRpZDovLzY1MzQ5NDc1ODg='),Pick = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('RupiLmBeJVGzUcbuPwydrTZZFouGfblfXlWYmfcseWTXaUXwJZXKvkhcmJ4YXNzZXRpZDovLzEzNDcxNDAwMjc='),Pop = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('uZnUMcHvaXgXRruHfINsBXgjorqQQXnjzwjJBNIKACtPiTrlToomdJdcmJ4YXNzZXRpZDovLzE5ODU5ODc5Mw=='),Bruh = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('YNirPxRGDLWGcfPkykOkwGsPcPNgxaAyJsiMhzPpjFFhhoQEcDgHYUEcmJ4YXNzZXRpZDovLzQyNzU4NDI1NzQ='),Bamboo = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('mNbNtPBftRYHMfjYCWIQVaFroJSniLvWGvDDchlFgWinYNWDKhDsFNmcmJ4YXNzZXRpZDovLzM3Njk0MzQ1MTk='),Crowbar = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('EPFXPAlNdSRHewIuNFpchtTJCxYEQvNdjbXHByImzRIxMtTbtxUWIoscmJ4YXNzZXRpZDovLzU0NjQxMDQ4MQ=='),Weeb = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('UpuTPlhELlnHkxHsexAcBbYnpFRpuZHkmazpgUFifBoKbMQFEeoRqwtcmJ4YXNzZXRpZDovLzY0NDI5NjUwMTY='),Beep = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('ZatlbyyQthNwcbCdNSpFbqXzbVbbmdgaDLUddOklNaYVLThjkBBDdZMcmJ4YXNzZXRpZDovLzgxNzcyNTYwMTU='),Bambi = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('stYNmlSORCqSkFVajwobCUxpguxfZnRWfuTNGhWjpBXqePSlklETFsEcmJ4YXNzZXRpZDovLzg0MzcyMDM4MjE='),Stone = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('KhSbFHjcQOyQaAPhOQqvErfCrUKDPKMzBUyALeKWaEAYmNugikplFnYcmJ4YXNzZXRpZDovLzM1ODEzODM0MDg='),[tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('KceqIlaTMYRYQAnTRyJlOWOTAADFqZQeZhBTUUsRDbRpomIwcsCEBgdT2xkIEZhdGFsaXR5')] = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('vEEcjhuKgXTSNQtkeuAtRgsHhBXXgMXKkxZpNosYERFbvnWzrGCSikRcmJ4YXNzZXRpZDovLzY2MDcxNDIwMzY='),Click = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('KshmvVpnKTUDnBmYGYUGzdXZnRjwuXoAFLWnhtCCFCjOBAAimGqhFOdcmJ4YXNzZXRpZDovLzgwNTM3MDQ0Mzc='),Ding = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('fVcAauLNpQgyxojGZqHdJJbspXludFjNWJzRuKDJVDFQfENxXRyrZVKcmJ4YXNzZXRpZDovLzcxNDk1MTY5OTQ='),Snow = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('oAPqSREAOtzEYvQLfFUxukuwqSZQFjTpHmdcVVRgQVFYAbksAFIkAmpcmJ4YXNzZXRpZDovLzY0NTU1Mjc2MzI='),Laser = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('nwrqXvFgTdblDLrWFaissGtCrtRypWjWnkwxzzPaqqpXAZDRxcbGYSQcmJ4YXNzZXRpZDovLzc4Mzc0NjEzMzE='),Mario = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('dCbDsKfdMZumybsWWlbESftTPwufRjVYNLucgmEIspfUXcbaTlVvUiucmJ4YXNzZXRpZDovLzI4MTUyMDc5ODE='),Steve = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('plZmWVKfXedtdJRLzrGibIDDqPCnjouCLzTHEafQnGBInmdphXdXklfcmJ4YXNzZXRpZDovLzQ5NjUwODM5OTc=')}

PlayerHitsoundsTab:AddToggle(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('xfaMsRiXJvXkpmaCSDxsrSUsVsePIAPpdfnPxPxmgaJrXUxbyBgUNNYRW5hYmxlZF9Ub2dnbGUx'), {Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('fXDfRNcPlRsGZoFzjTZjJiBvkrMzGWWuWBkmkuxJOsVQFGpmiEoqKnUZW5hYmxlZA=='), Default = false})

PlayerHitsoundsTab:AddDropdown(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('NgvHJdRvvViwPkxZjrwRsEmbwZtqxnnxfCKJIWPSvwhBvabFKaVjOddSGVhZHNob3RIaXQ='), {Values = { tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('WRYGWeqHkvfaePwFmePLkIeIkWiojsMzKxzpMjwHAknkakqApsuJNlYRGVmdWFsdCBIZWFkc2hvdA=='),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('KyBkNcpHabYvGDeHwEobzbtmNqtCqtfhHltSOGLaEvjxVuemzRrZDTkTmV2ZXJsb3Nl'),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('GQNvTAXPSsmELqIZtRkNAJmKAhdVsHuYjrlaZUaMHNgNlZfqGUXicCOR2FtZXNlbnNl'),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('LorpnPqHCMQyfMuSBgZnFIuFVLfNztdVuPCzUsQQqQvCrAXisnkfRacT25l'),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('IlzfRsffXYkRAWXcwSKGAGyheefOssfXFkvNtBKMnDEcERYkxQmfoDxQmVsbA=='),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('GOSuUNDvdayyYUqHcbKbTlARmSlkjpZJgYpPlMrVTMDsullwHZTKPxiUnVzdA=='),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('QIyhvranTbqznMussCnpWacPgePKmsrJkFqkmgsNJLDroMQoYLKbXGCVEYy'),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('cgERBTqahzOzVEmERywlrUHMAeYqJqTxBjOMzfTSRCkYXrejbuElBxTU2xpbWU='),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('brwTyKgnYwZgjDIFoDCPWnNkFpXFhXnJDtgLXkJnGnSuAGSnCRkkuqgQW1vbmcgVXM='),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('RyKobLmWrGXGLuJYKHHXJWJDplYjmUpTchXvgYTlXYKGMWYpvoAvKWsTWluZWNyYWZ0'),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('rlwAqhkNKvNsPdHpIcdJhmFnIVrrMXvTlZbhMMTvzJLoaWtswofTfHLQ1M6R08='),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('fZziboaPQNjVUepEovWBAyOTUNsVrqCuBTThWwDMLnroKHTqmvFTZWaU2FiZXI='),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('IoQtPmShQHKSsjUJcLomZisLpMnGjoZwvutnZZxcoSJsiOmbOcHTCZNQmFpbXdhcmU='),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('bbbgjbxXFyBifriRctTTmFixYIkoTHjgmzKMsAjFVUuTZwslumMdWKyT3N1'),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('VToFyHcrCGGysfTzeFtiZvnwYHDkGvWArlCXhMnrcgoptXXcUjOKwIBVEYyIENyaXRpY2Fs'),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('yDvrqSZiWLOFZqGLarNfdgHNsuDmAAZhTbrwJjbCuOiXkMRziVWVhqVQmF0'),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('VQpGibIakbafJEqDjGcYdnsNPWbZreeRXWOaFcsoYtTdbJXIaEntwKgQ2FsbCBvZiBEdXR5'),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('muipcAUGIRzAyFUxERNVAopLTAyQQQFbIafftXUgOhzsjbNXuyJVPWpQnViYmxl'),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('NPbbPBIyZISWbaAwDHYbXOLJDKpNKgIjnDIsmyoHTAXCsRrfZJlGkpvUGljaw=='),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('OpIpUTdMUNrxhIRBdtGdAnMcPXmmaOAYrmoaCizhRtItNKyaCDMbUUNUG9w'),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('wkwHSOLKSrTjlZbDgRHcCWuYKltzbeeEMDgWizoPCjipZUWXyJUlLZvQnJ1aA=='),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('BXIBOGrhsVOnWZDPRsQbjSkqIWTsopayXlAxvSGmrvPdBDtKugiUwtjQmFtYm9v'),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('acmxIqJxirWVszDlcFjPkqeimJiLXXgtlmOqUnEGDORBPaRuTQXMeqnQ3Jvd2Jhcg=='),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('xzqpkjygAMFHOyGhcbrAEdpkFgAsHRIxUAMTZLEayROodoATHGttchyV2VlYg=='),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('dSaphuwpucrrlRyBwCXBDsUTaiHpyWFwfPAnWAnkSfMmFeehfBQYbgRQmVlcA=='),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('DSEjJFhIScgoUieQPlESuHtgAJYUGIGNrtpVksauWBBCHtQrzADkDHbQmFtYmk='),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('KcFULpySeyUzaJbgLjgNjPzwoXrIqtQfPtiNkdROxIKyLrEgzNDJVasU3RvbmU='),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('wGQtyVrhCKReXOpskQQTmNXwlelUIsMCPdIhcnnMtudeymTrFXXKVXBT2xkIEZhdGFsaXR5'),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('efQdUdaChXPPtAuUthVOMOQlmSdByeduuozpUBBhbfKQKkxjtEzhBSfQ2xpY2s='),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('hrIwhncbTJafPcQeRGBSfisAzqvOjnSKoPrQbsElDyfTfzYaMPNzVoMRGluZw=='),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('FsXFAyJfsuTkVKpotRaXEFHITztGNzLgzAmmwNqJDTByaZGeWnPIBXKU25vdw=='),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('jRBvOaZZljBNLehuxCaegqabThVHzfGAYTrWeZraSxsCpTjyLKLYLHRTGFzZXI='),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('gAzGIhqbPUtvgMwHuzyZBvefNayUfxGObJplKwskVuiZMwmxjTQpODZTWFyaW8='),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('zyajVsFKFOWeATRZPRPvXJwKMtZhaQdDyiknSWKIQEzIiFXeYmrFOqSU3RldmU='),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('trwSNPOmrHwHtSnBzhpFiPIdVKDSgKuVbNjBZyUGJsbnkUzTejAdsGCU25vd2RyYWtl') },Default = 1, Multi = false, Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('CyIwZVgVMRbRlCyzpWgFnoTtwvkqomrOXVgIzGqwdyUUVhiIfQFwuoySGVhZCBIaXRzb3VuZDo=')})
Options.HeadshotHit:OnChanged(function()
local soundId = sounds[Options.HeadshotHit.Value]
game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('WcDPXTpLEIKOLvgaKsOlyOiAVdBtYIuvnCYQZZvWMhNPuGDRrfaINfnU291bmRTZXJ2aWNl')).PlayerHitHeadshot.SoundId = soundId
game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('IlTXuvphGDYSSkplGskCMrORREngcQjSyfZJGpUWfJJTBTpqVyWSCbwU291bmRTZXJ2aWNl')).PlayerHitHeadshot.Playing = true
end)

PlayerHitsoundsTab:AddSlider(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('mUpuwocmkylMhUHDqpNGMjTEtHLhJWkdrCXvTmbckizwHaIcppbpzyGVm9sdW1lX1NsaWRlcg=='), {Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('deiFBqtjkJbUEqDBKYQAWDRvaFLwcSAqoBJjtLSdblhAXMJhWuUuJuydm9sdW1l'), Default = 5, Min = 0, Max = 10, Rounding = 0, Compact = true,}):OnChanged(function(vol)
SoundService.PlayerHitHeadshot.Volume = vol
end)

PlayerHitsoundsTab:AddSlider(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('uFNHjdhPMpFJmjMOlNvchTfJtnQWohscbQRaibquurbRDSSxQXCRQkeUGl0Y2hfU2xpZGVy'), {Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('kBBINziyDeMwTQfUzRBSPWEQvxFrKgZiAmMseKwjqSyXMstMnrHYBgbcGl0Y2g='), Default = 1, Min = 0, Max = 2, Rounding = 2, Compact = true,}):OnChanged(function(pich)
SoundService.PlayerHitHeadshot.Pitch = pich
end)

PlayerHitsoundsTab:AddInput(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('cbXdnDxVaXrEvTKtIZtgYDHhrzMGQgcpYxzGpSwcUYyKHbFryuBuwwvSGVhZFNob3RIaXRBc3NldElE'), {Default = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('XoUJUPpTJBAfDnTIgJziCSRluxYXgpbIoIbsSKLPcXVfMLjuMctmcRkcmJ4YXNzZXRpZDovLzkxMTk1NjEwNDY='),Numeric = false,Finished = true,Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('evJZqNVVoYchjOBlenCOUgZmmVlMfnkpBMxIFZthCiWUoYuurzQjBWGY3VzdG9tIHNvdW5kOg=='),Placeholder = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('gSQnLmaUPCKwPUHbzEreObLteBwOxhLsQxmdUyKRuNcFGYPJfRvhaorcmJ4YXNzZXRpZDovLzkxMTk1NjEwNDY='),}):OnChanged(function(CustomSoundID)
SoundService.PlayerHitHeadshot.SoundId = CustomSoundID
end)
--
PlayerHitsoundsTab:AddToggle(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('vZqUNlJKqHrRcUQRjQpkkHPRwWvhUdAFWouJVQGolUsrXPsdogLCkDSRW5hYmxlZF9Ub2dnbGUy'), {Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('SIfRiGhMOnpipGlNrHAXCVuUhgMHwnSAYgEmQPrdTgZlVIpvQKlceFEZW5hYmxlZA=='), Default = false})

PlayerHitsoundsTab:AddDropdown(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('JsdvhslQkGhqBZpDFWOpuwZuiUPBUscSgCqXFXatEuTeQRAYygSdwbBSGl0'), {Values = { tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('RKyfcFXIHsWiKeVAiQQuVyXiNKPTqHqvmPQDQOKHIkYmKHULkmyHngMRGVmdWFsdCBCb2R5'),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('NYzKJYtAyBsXjTMBrWGOlawemwqnLBhfqqjGdwqStSAarBYBdUohDyoTmV2ZXJsb3Nl'),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('fEJrgvfpGjyOtxUXMXtmgeCpCRxDYvUamtrAFOteRlkEciswsUFBEiYR2FtZXNlbnNl'),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('yrKixhtikxwOaGKDbDDmrOHSCCyfunzTySiUOAgoMOmPQOCYdagLplPT25l'),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('SvttWyhpVnvLwvkGtNiNlnSyGRLtwYQidNOKKAYJrYynCprvxJwHJGgQmVsbA=='),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('IzCGzaMZMfnbkHMnUCiefqLAHTGHRVoZqQydojsAdrUdjSLuwbYMAkuUnVzdA=='),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('SqmvYhrlzBCwrJMebENhLrFefdLCLepfKxgcgpItLVUmssGqeLyFXbbVEYy'),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('OlhvIqPqmbeIMamPTWkDOCOufHDTasEuUosMbpcCWADQJagaeeYaDcfU2xpbWU='),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('dSaFGfkNHJsQZMSkhiYagCcmpRYbCJbuRmVavMNoaXEvoWslKsSPDnMQW1vbmcgVXM='),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('yZzQfeBJTlyYCPrVfSjMHLZtTMHDQejmLBbiALUAJUzKxoPwmCukEdQTWluZWNyYWZ0'),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('AxsDEmyyfBjKUCVMFxtIgUMeyrMLkxEseoQmFRwnhohFyTppcDcXYoLQ1M6R08='),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('SlCTvTHFevQvfSNMGqAGcJuXYhnvBQpnWlxRsgFyNAfaCmNpFDoBLhrU2FiZXI='),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('hmJmeVpsnNYVMGKXRwVaQOLFMAGIYyRpopndpYfUppBCJwJdrGZmfZkQmFpbXdhcmU='),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('HCCuVmrPSHsXzcWGnluqUWVOqzpfItIfMatxXEtqiXOPMRSJrkJBNsOT3N1'),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('rbJaFADNwjwLYlMmetspOveRfcXiVliCyxYHcAHtauBaIzHBYKKxZlQVEYyIENyaXRpY2Fs'),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('OvYLuzbkqBSsPNjoYGZcmsBwwmZVaBXampbpgbQEcLoVSkzrIANfeHZQmF0'),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('wpXZYakIatBEUrORHzdldWbMkkXvZwNYBPscfcmhqILCwmiBgfrbcuAQ2FsbCBvZiBEdXR5'),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('daiWqDMUattJTwaTMPKFaHbVuKgiTIbYdnKbzFJxyzjtalAInpGAtbnQnViYmxl'),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('pHhdTgPUmZNxOLVaIMefToEOAETmXIFHlwzlfPSIfdEfqzhQxgyvAJmUGljaw=='),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('EkmWeIYKDriQRtRkwqpWpxOhwHEiqmqyJhiaiUZkjYCJNMVoVtcIEleUG9w'),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('AecRAoqejNdmAetsYXsRVxxkdadnTkYpkaTTAnaEoOrcGlQFLMqIWcWQnJ1aA=='),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('lPVScvIAtnmjgoJsoBSdhXMVhshSUgNSHbtxUFCLsxBFvZlrGaJWXQvQmFtYm9v'),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('EBRWOhOIBeUxLQhINuHCAVcxvOSxBAsFxChbExFWLwEIJXUsVivvLerQ3Jvd2Jhcg=='),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('ulPercqZOqlxSceiHqDemRjbqIUHFevNwWKuRAxXHdSWeGvMiaovgKeV2VlYg=='),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('aUAbbkrIKjVrxdJJfXyQkUgVeNuuOjpreszVUPmvDdSWzVUgRdFHbwjQmVlcA=='),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('eaSLTQaAMEWrFhhXXdBRhnSKiwyNMrLgroYIiFMmKSjMJYCkQWdEoSwQmFtYmk='),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('AsttzanrwVeSeLANNMDqiMRQrRjvvOkdLIhBErPdCiqwizatOVbUvPwU3RvbmU='),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('bQOiWUhzPRmntnzpIVFzFpiSKtpwyEldykJRPoIGbAleQeciSkbLVeOT2xkIEZhdGFsaXR5'),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('DQEoDtgaGmODozZWwenzTThzrIXBqkomQZcYcxHXXQtMpyOmtdQiWLJQ2xpY2s='),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('JnDSWJDnxKJiEFBngsGwiNPpPRKoBgBYsCzymjoTsakCRKdUIOMoePkRGluZw=='),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('JesFWFbUQmJiBVlsNMwCCzIfkITGDcTAIkWRFhZAYKvqbXZSSvNmSdMU25vdw=='),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('iowAHFhCaClNWKOlWJPGmLxazBXenyjzSZmrWnbkxzckpKhRCJgzOzkTGFzZXI='),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('fzWeVEvRIduHItlofTgvitORskQMZaftXkvAInTKhgubRHkvmkMKFMJTWFyaW8='),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('TaIwURRNUvvUuLleTlBEFhNkYeuMuhIXdPkRhiFKwGuDnLvPjxwpiokU3RldmU='),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('SDAZUhqhPjHOOLopmUdggMqQwFGLlBpAhDbJtYuhiHpgJpibBFYvEBkU25vd2RyYWtl') },Default = 1, Multi = false, Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('HIpsNOwHveeFuqyCDqarKCbjPVMOojEDyILJxZBTbqMGIjubWwdqMlRQm9keSBIaXRzb3VuZDo=')})
Options.Hit:OnChanged(function()
local soundId = sounds[Options.Hit.Value]
game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('uyUwmbiiKztFWJySJfKmmKLPUPfhcXTNBYhJveHsVRESEyvLbFiYkLAU291bmRTZXJ2aWNl')).PlayerHit2.SoundId = soundId
game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('utiwXYyqZzePesJIBLeSwEJWRdczwlsLecuKIlQcnYQJKRGwcuZvghGU291bmRTZXJ2aWNl')).PlayerHit2.Playing = true
end)

PlayerHitsoundsTab:AddSlider(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('dXqHogJtKNKdBhEErJsSfZWWChyXPjTlARunayYArWVDgrpVpInutCjVm9sdW1lX1NsaWRlcg=='), {Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('QlsopDXwhWFxZdOyoOixlZefcEoBTmXhgrQkmVYsiSBarFuNXVFDugmdm9sdW1l'), Default = 5, Min = 0, Max = 10, Rounding = 0, Compact = true,}):OnChanged(function(vole)
SoundService.PlayerHit2.Volume = vole
end)

PlayerHitsoundsTab:AddSlider(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('cikFdaoHMwSLHynSyoPtwPkribTPSPPCmfjwhETBRyrBvEPBJOALMJRUGl0Y2hfU2xpZGVy'), {Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('jMdymtbowxVptDCzOINQNqIwUtmmGKIGJZfalylZjpeUYbkhfpbghyZcGl0Y2g='), Default = 1, Min = 0, Max = 2, Rounding = 2, Compact = true,}):OnChanged(function(piche)
SoundService.PlayerHit2.Pitch = piche
end)

PlayerHitsoundsTab:AddInput(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('jqSEKMvhMWVzAwllJBeNgbMTMOmiEWNRJXGScjKSOzQFydPOlZMLvHCUGxheWVySGl0QXNzZXRJRA=='), {Default = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('ZyngkOYxALkTiBsenUXrQeNQyKGjEtOdQKySQlASIZywxdvzzhjCUfwcmJ4YXNzZXRpZDovLzkxMTQ0ODczNjk='),Numeric = false,Finished = true,Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('haPHyvqyBPYnvRnIcHXVuCPWsfvUxzAjsWhEppphTVDFDkONHbLkGgCY3VzdG9tIHNvdW5kOg=='),Placeholder = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('mGEmafTRPlzSOmFjpEfIZFJZYgQlTsOTsDyhaWKwOCOpwaMMKTxNWqYcmJ4YXNzZXRpZDovLzkxMTQ0ODczNjk='),}):OnChanged(function(CustomSoundID)
SoundService.PlayerHit2.SoundId = CustomSoundID
end)

local GravityTabBox = Tabs.Misc:AddRightTabbox(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('fECgCcxWemrBgptpJCAFUmXoSXPvMnvAVSBBnGenqvYZoltQyXvNkrsZ3Jhdml0eQ=='))
local GravityTab = GravityTabBox:AddTab(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('xsBapImeoDSDfSnLWNNlIRuinfuzmhJnaILrWyyGJvdvqMRRxFWtBRAZ3Jhdml0eQ=='))

--* Gravity *--

local GravityEnabled = false
local defaultGravity = 75
local CurrentSliderValue2 = 75

GravityTab:AddToggle(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('ANYytadgfsgYRorhIpiZONspoQuKChxWASsVymvGLiNbpxIAQUFjSKyR3Jhdml0eQ=='), {Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('ZaiQWsnDnbRVwbZIrLpQRKxGzyKndoQDPvFpEMIgOPnZFyocmLxLkEnZW5hYmxlZA=='), Default = false, Tooltip}):AddKeyPicker(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('FquJKGpinBTCradWPFRMUJgxWUrEeQTkLiLyFyZKJPnJqFpMeqNKZqOR3Jhdml0eUtleQ=='), {Default = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('SAbxBxRrLMQMIRjawMmWOkiFhMjnudUlTcgtUPTJCEiyjVaJhrgMnSoTm9u'), SyncToggleState = true, Mode = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('TpoFslkmRbMBFGUFPyFgAxgVPfsXnFbCovZhOKXjaEMwjsGoSfSygQVVG9nZ2xl'), Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('OKlHBcoFDCuvpTJQnptWugeSUftotbLYuTYPPGqJehNcUmFYQpaMYYIR3Jhdml0eQ=='), NoUI = true}):OnChanged(function(value)
GravityEnabled = value
if not GravityEnabled then
sethiddenproperty(game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('ebdQypHXMfMkPCQtIPnZoqLXtpDcpbztUjjQyUExCfaHUfWjTKZZKwzV29ya3NwYWNl')), tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('jhFBFlzYrtThcPksocZRYRWNJaESNJfDqOJVSBhnCIEnGscKUlFAeFJR3Jhdml0eQ=='), defaultGravity)
else
sethiddenproperty(game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('FDPdWoiBNYteXQgaNGpClvYolDOaeERYpqkkDXVQEYGzFSzJxTQTcpoV29ya3NwYWNl')), tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('tjwgOtryaJCbqPviuAHcnXenqWWxZZZmPRTKvTjxHWOaWOcSxigsQVKR3Jhdml0eQ=='), CurrentSliderValue2)
end
end)

GravityTab:AddSlider(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('fFUxLpdWVLYSweWulHiFNeUnEeZfvfzIBykNcBugDOGCHlLhrHvsUcOR3Jhdml0eUNoYW5nZXJTbGlkZXI='), {Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('cmXZoxvhzHLBdnfSvjBDFZqQTRNjewAISoonBrbdJrLYZufZMOzBYTPZ3Jhdml0eTo='), Suffix = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('oUQgETNziCUaOzXmRtcbjmqWIJtLIvApsduWDlVTdogWHGrirqNWZjpeA=='), Default = defaultGravity, Min = 60, Max = 100, Rounding = 0, Compact = false}):OnChanged(function(Value)
CurrentSliderValue2 = Value
if GravityEnabled then
sethiddenproperty(game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('xiyszcYdgrKQvywcNEBUyYixqYQCgfzDMhtGWjDxZUZrlWYrEwNombiV29ya3NwYWNl')), tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('PIxLLzXyKlkGCUPWiuXRTQAKyNLqsbGbmpPMjbVkUfIAERibvYAHWvBR3Jhdml0eQ=='), Value)
end
end)


local qf = {
Settings = {
  SpeedHackEnabled = false,
  SpeedHackSpeed = 30,
}
}

ExploitsTab:AddToggle(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('TpTNjJvSkessJrYeZqMXJFfXYaQZSbrKaGoWqMRDAcvCjvdXiJmHyHJU3BlZWRIYWNr'), { Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('ukJbllHpEdLryxdEHQhXcLtyjoauNUBmYziTJjDIQPAZHcfOmBJVbFZc3BlZWRoYWNr'), Default = false }):AddKeyPicker(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('jvtVMrfUrUhUueoBiOivjfdpSeSflDtqzuRlsooBxpxnBxTuMGVDHGHU3BlZWRIYWNrS2V5'),{ Default = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('cYJnYhbHbMaQtPLlMlwZeOCDemyDVazwivwMichgTPBXSLOsGvmfwthSA=='), SyncToggleState = false, Mode = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('sWqRbJzfVzPXHqgBcRsyNqytflzfYgcDwHtDDKIoCVPFYxXTyGUDMkLVG9nZ2xl'), Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('SzAcdgNsYunMAgAOWKCjAUWpksWhnTaxdobhzqaaePoVtvQNpLBtcHdU3BlZWQgQm9vc3Q='), NoUI = false })
ExploitsTab:AddSlider(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('bBiAIcaoVyDdhSewTlhEbUljpCRxPtpxzehTtiaiywbTsPFNBSWKdXXU3BlZWRIYWNrU3BlZWQ='), { Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('kioNITxzYVvmEyeCjrmyLorTIwbyVEavXAFaIHFAAhohRSesRirOSgxc3BlZWQ6'), Suffix = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('IjEwnSlqbrdeWpfugqQkaNXRSJKORIWiPsHYroiKaRIWxGIfHQQSmTFJQ=='),Default = 17, Min = 1, Max = 34, Rounding = 0,Compact = false}):OnChanged(function(G) qf.Settings.SpeedHackSpeed = G; end)
Toggles.SpeedHack:OnChanged(function(G)
qf.Settings.SpeedHackEnabled = G
end)
local nT, OT, JT = true, false, false;
game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('JOGkZBiKWNnENwljhlfeUnXWlDwOygEsKinjFfHgtNlMKdoXZCDbYRTUnVuU2VydmljZQ==')).RenderStepped:Connect(function(G)
if qf.Settings.SpeedHackEnabled == true and OT == true then
for w, m in pairs(game.Workspace.Ignore.LocalCharacter:GetChildren()) do
  m.CFrame = m.CFrame + game.Workspace.CurrentCamera.CFrame.LookVector * qf.Settings.SpeedHackSpeed * G
end
end
end)
game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('qaUCCWIaecaJGSyucKZqBEHSwrzFwHVRJucEDSeWXUEKUlTZftKMYOsVXNlcklucHV0U2VydmljZQ==')).InputBegan:Connect(function(G)
if Options.SpeedHackKey:GetState() == true then
if nT == true then
  nT, JT = false, true
elseif nT == false then
  nT, JT = true, false
end
end
end)
game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('mFNjLoJuEYVqhXkoCEEZouOOZyHIEqJeAgCbPmifzGqVeegNHQPKFxdVXNlcklucHV0U2VydmljZQ==')).InputBegan:Connect(function(G)
if G.KeyCode == Enum.KeyCode.C and JT then
OT = true
end
end)
game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('lMQwxbVDojubgDbdyexcdcvIXGxgMPVCxXyjnjJRmgAIHyCsFCmuGuNVXNlcklucHV0U2VydmljZQ==')).InputEnded:Connect(function(G)
if G.KeyCode == Enum.KeyCode.C then
OT = false
end
end)

local CustomViewmodelTabBox = Tabs.Visual:AddLeftTabbox(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('MsQRzXHLJebsMglodpDQJrvDkfikBgArhfyNadfVJCVqYKunhdMDCzZY3VzdG9tIHZpZXdtb2RlbA=='))
local CustomViewmodelTab = CustomViewmodelTabBox:AddTab(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('agkaemRRtJMGViscEACisTYgsVFpZeiabyNsLXAFCZHqEMRvjJPTEtGY3VzdG9tIHZpZXdtb2RlbA=='))

--* Custom Viewmodel *--

local ViewmodelEnabled = false
local ViewmodelPos = Vector3.new(0, 0, 0)
LPH_NO_VIRTUALIZE(function()
local newindex
newindex = hookmetamethod(game, tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('ytnTJJyZqgroEKnkzruWDWCizdvZccDVIwTANLIFFFIPPNDDBaJCAmXX19uZXdpbmRleA=='), function(obj, idx, val)
if obj == workspace.CurrentCamera and idx == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('JeoQFWzXKHvEjKyQiAcMjCXZJFrSxAVPoxIpVuutybVmIEgKtLrmawkQ0ZyYW1l') and ViewmodelEnabled then
val = val + (val.LookVector * ViewmodelPos.Z) + (val.RightVector * ViewmodelPos.X) + (val.UpVector * ViewmodelPos.Y)
end
return newindex(obj, idx, val)
end)
end)()

CustomViewmodelTab:AddToggle(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('qJHzMVuHCkYoguVBoRuICzCzwnXfOlJyaNRkwwYGYqIYcvRbbhaJZzCVmlld21vZGVsRW5hYmxlZA=='), {Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('vKokLytBFrnXxFFsCfXhGHUcswmxcRTHRtZboQoXcEKFJwxsvLhxkwkZW5hYmxlZA=='), Default = ViewmodelEnabled}):OnChanged(function(Toggle)
ViewmodelEnabled = Toggle
end)

CustomViewmodelTab:AddSlider(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('jDlZTakgvVtaaDOpzpmAcmIwuWxsMTqroELgdqzjvelLsQtWoNWhTKrVmlld21vZGVsWA=='), {Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('gBGxAxkPzTyfcjnxisOIsjJvRjvhykRsKGdiSLhLgrsgNbZWkWCdxuLeC1vZmZzZXQ6'), Default = 0, Min = -5, Max = 5, Rounding = 2, Compact = false}):OnChanged(function(Slider)
ViewmodelPos = Vector3.new(Slider, ViewmodelPos.Y, ViewmodelPos.Z)
end)

CustomViewmodelTab:AddSlider(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('wuUBqNsOcGjMqdveghQgBvYvsqyBNbPhvTDbuDVYbtIIRhLKObZWKjLVmlld21vZGVsWQ=='), {Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('pMtJCGXCbzojHxOMRqpdwnOzpokPpEDNMfDytDJKqeurzjzDHnqYnEAeS1vZmZzZXQ6'), Default = 0, Min = -5, Max = 5, Rounding = 2, Compact = false}):OnChanged(function(Slider)
ViewmodelPos = Vector3.new(ViewmodelPos.X, Slider, ViewmodelPos.Z)
end)

CustomViewmodelTab:AddSlider(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('ktOgFTvCizyJNkKjHPxuUkJVCkjbOMkmzcbmjbNpTjZYQxwuCWqAbIdVmlld21vZGVsWg=='), {Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('mYlxQvsxykIKZYQmAmUerRZGnxLlhjdRrKoAakwKZYeLSLPgocMEFhyei1vZmZzZXQ6'), Default = 0, Min = -5, Max = 5, Rounding = 2, Compact = false}):OnChanged(function(Slider)
ViewmodelPos = Vector3.new(ViewmodelPos.X, ViewmodelPos.Y, Slider)
end)

--
local CustomCharTabBox = Tabs.Visual:AddLeftTabbox(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('cHajVngQbRTHQzXYBKdpUZzPirYDLCQkygaVTGazNetljjLefdQfjIVY3VzdG9tIGNoYXJhY3Rlcg=='))
local CustomCharTab = CustomCharTabBox:AddTab(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('kseXQvDrHhERclSwWVHNbHQtRrtzhDOBxgpnIaBvaaXyhyfcAWEQoWjY3VzdG9tIGNoYXJhY3Rlcg=='))

--* custom character *--

local function CreateCustomCharacter(Mesh, Texture, Size)
local part = Instance.new(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('AOJUGpOdXwiEsikLmsFNpzjsmCjtygNnlctgDyoKNZLQNSdwFLwEcJcUGFydA=='), workspace)
part.CFrame = workspace.Ignore.FPSArms.HumanoidRootPart.CFrame
part.CanCollide = false
part.Name = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('QfdCYAWqIEoRdoHPfTYULtWDYcsNyLPbCgtquWFthesNNkPGCXxSItoRGVsZXRlTWVGb3JOb25l')
local mesh = Instance.new(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('yefkWsFycTaepRvwxfLLkQvHoGLdbXzfGgDSNYpchzhKPMpaUQmDGWJU3BlY2lhbE1lc2g='), part)
mesh.MeshType = Enum.MeshType.FileMesh
mesh.Scale = Size
mesh.TextureId = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('TclqGuhKiSsNOPGFftMlqbPKFVGbgPqhxgJtYlTexwRLqULHBdioQzdaHR0cDovL3d3dy5yb2Jsb3guY29tL2Fzc2V0Lz9pZD0=') .. Texture
mesh.MeshId = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('LObYchWTwbPvcYFTHPjTkAhzdGDfWZDUFZLbXmhgGwYzRPERrPDpGxGaHR0cDovL3d3dy5yb2Jsb3guY29tL2Fzc2V0Lz9pZD0=') .. Mesh
local weld = Instance.new(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('qyVCPJQVpJZUaILuWncTIebXcrUiFZbzrosjJVllBleDWxJcHscyGIKV2VsZA=='), mesh)
weld.Part0 = workspace.Ignore.FPSArms.HumanoidRootPart
weld.Part1 = part
end

local CharacterType = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('ikDLhBNikxkOytCSneaMbYTyqXThCJYRJrUXzFzTXskOPAgLMDBOLgHQW1vbmdVcw==')
local CustomCharacter = false
local function UpdateCharacter()
for _, child in pairs(workspace:GetChildren()) do
if child.Name == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('KrOJurYjZxIAJXWpfjzzgWOFUqVQQCnrEjlcVQprXhCUBxoDDQPshxuRGVsZXRlTWVGb3JOb25l') then
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

CustomCharTab:AddToggle(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('qhtyPZuwZiioSpvuimcCKEMWtbNvPWbBuBwlClAmuMgfoxPBvrloGujQ3VzdG9tQ2hhcmFjdGVy'), { Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('GKQuSMPKMeCndnUIXTmBYDWtbOIFaalIHNrCgsMeiYFTbowICBkukZYZW5hYmxlZA=='), Default = false }):OnChanged(ToggleCustomCharacter)
CustomCharTab:AddDropdown(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('sORGuwEZEVBwQQxXJKjjYeNasNpTtuzYnXdRDOWtlGIzaPjIomhwoHUQ2hhcmFjdGVy'), { Values = { tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('yWrTfObSLAYAlGDxzElsZINHajyjrCmLKtMEThQAOHOzGuMPnqdNqGqQW1vbmdVcw=='), tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('cSbBTQfQTQwMGdvhmgZVjTaKIQrYAYBChYHuFbGRxTKeipgvNukcpkCQnVpbGRlck1hbg=='), tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('QfsexYchmVedhvHpBgmIgxGLXtxVLlTiCZISMigebJyZbMITPfbFlzgTWluaW9u'), tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('PfyvFKtkSXCRQjKXDinyjliLVVnSABdHeNEsJBMzoJogOukFRnMgGDDTGVnb0Nsb25lVHJvb3Blcg=='), tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('uiRuHAPCmolrJlqNXrJkZxqLHgfSMqMtcBrdIkwfUXzsoPcdOvSQjOSQW5pbWVHaXJs') }, Default = 1, Multi = false, Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('qKIyEbgIvLXSxRvlAMdZLweKWBINhtkaoYgPedBFwMZnGjDqTKepcoBdHlwZTo=') }):OnChanged(ChangeCharacterType)

local ArmVisTabBox = Tabs.Misc:AddLeftTabbox(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('DMwHnkVImSaCCtoKhVkUDZwHdQPUObKkjaLPSxglwVyTpLuhovwlwfYYXJtIHZpc3VhbHM='))
local ArmVisTab = ArmVisTabBox:AddTab(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('tQReJomzspCJAvVLgkVDtpsNhFCSTNLsWqVAEYfOQHxmMMNGpVoYgthbG9jYWwgY2hhbXM='))

--* Local Chams *--

local Misc2 = {Settings = {LocalChams = false,LocalChamsColor = Color3.fromRGB(80, 77, 56),LocalChamsMaterial = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('YFSkhuyTFycZWxjEcaMynITezBOexlYlDAewMPeiEdltWXcDlwuRZpmU21vb3RoUGxhc3RpYw==')}}
local DeafultArm = {}
for i,v in pairs(game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('kMEigIhyCAGKmBzTCsraVxMUhxluPJRrYetAMPtbzWAxHtBUfbjUjzXV29ya3NwYWNl')).Ignore.FPSArms:GetChildren()) do
if v:IsA(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('bCSuZenSQktuKEYIrLMZtKnufacvWGKLufVMROrwswTCuhZBWrOUepvTWVzaFBhcnQ=')) then
  DeafultArm[v] = {Color=v.Color,Material=v.Material}
end
end
function Functions:ArmChams()
if Misc2.Settings.LocalChams == true then
  for i,v in pairs(game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('uUAVhsmSYLYnHExAsfssEzyPblaekVwBJtIxodLwsfhnjxeSLAOzLlaV29ya3NwYWNl')).Ignore.FPSArms:GetChildren()) do
    if v.ClassName == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('fAxDBgMaHwcJjpvNoeTYLKxlFlQdGvEqUsIiVoYSHYaUIMfFqtXZldPTWVzaFBhcnQ=') then
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
for i,v in pairs(game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('cAZwWWrjajfHbGmiwCGtOohlvFrkaCnwvYzAWKrFWShOrLaeJgPJzyHV29ya3NwYWNl')).Ignore.FPSArms:GetChildren()) do
v.Changed:Connect(function(Change)
if Change ~= tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('JYFyuqxxRoaogHPfnWyBtCAUtsRBxtKLsoGwaMGcVWsfeiKGouVpavlQ0ZyYW1l') then
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
game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('OaSaHCPuHatGpzBfosNkNjwylkRFGBtEqRvzHFGDPeAIJXlPuoLGTvUV29ya3NwYWNl')).Ignore.FPSArms.Changed:Connect(function()
Functions:ArmChams()
end)

ArmVisTab:AddToggle(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('EIySUxuRPijvkvQZUqUdrnNHwLnKuzJKkDzSaYjcsQMHvmpFmRNheAlQXJtQ2hhbXM='),{Text=tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('XqWQHzBBOlrtVJQkVoKYCKWdQOhQUySpRjBItvKVKfFraXkCCzYphWTZW5hYmxlZA=='),Default=false}):AddColorPicker(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('taZCmAkASHKmjoJnEjGMQwrKDLQRSkJXygvBqaMSnCSmiNbNnfHXwWqQXJtQ2hhbXNDb2xvcg=='),{Default=Color3.fromRGB(208,123,255),Title=tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('hXlSYMMevtdiAdQtNeQFoDTmDMXsEtJsYCAGBAAoJuUPYCuMorryXMaQ29sb3I=')})
Toggles.ArmChams:OnChanged(function(Value)
Misc2.Settings.LocalChams = Value
Functions:ArmChams()
end)
Options.ArmChamsColor:OnChanged(function(Value)
Misc2.Settings.LocalChamsColor = Value
end)

ArmVisTab:AddDropdown(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('BjGbiJeSyRCmtBBPLfrNQHkLXdLesjYyeVslMgliKqJwhrvxZvuuSqeQXJtQ2hhbXNNYXRlcmlhbA=='),{Values={tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('UDACsFZBcYGTuWHyrPUXUpRCGtehLyyvomwLIjzFbxlrjDJlJOTdrUERm9yY2VGaWVsZA=='),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('aGzGVFikXgUzxmKOTlVNIXamoRWUuUqZwfNSatwsklKuPChUQECndUATmVvbg=='),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('PyQfeVnKTQMjzhcIAVELvWAuuXDlPtWhCZOtaFZjrZQIyCHquuUyknLSWNl'),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('ACERAqjxpVWrrihvLamMFhOnjhdVfGHAihRkXQAdNrYDqjpzghQsyjdR2xhc3M=')},Default=1,Multi=false,Text=tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('cqzOVkfbJuOYBZPtkdCkwjOxJdEdJntNXZjozjHcWoTWNQkVEiaFnaPYXJtIG1hdGVyaWFsOg==')})
Options.ArmChamsMaterial:OnChanged(function(Value)
Misc2.Settings.LocalChamsMaterial = Value
end)

ArmVisTab:AddInput(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('GdvHhczxEAjAufyvzMRguniWOGCNQmAUXvcVYcDoysMYWbqOfgtNKqm'), {Default = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('aOozHzfejCEMGwbaCJxHuneSqjzAJWlaQyPFTcGOoaCjmVgoHAFnETEcmJ4YXNzZXRpZDovLzExNDE0NjMzODU1'), Numeric = false, Finished = true, Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('VIfFLBWyZGMeuekWPptugBwPRtlXyYGiQoOfgXcAbfQEXIGWYqJwhokVGV4dHVyZSBJRDo='), Placeholder = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('aSeLSFMQVQbCwouaxLlgcoXTFiLqLnHYzNNXgEclzIOgkDrRwDMlEYJcmJ4YXNzZXRpZDovLy4uLg==')}):OnChanged(function(TextureID)
game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('ioDwJFgSwvKyjIITDLZpmpLmHcLBBPVUAebliADLTYxaomPAedyASzcV29ya3NwYWNl')).Ignore.FPSArms.LeftUpperArm.TextureID = TextureID
game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('HSGipXKeboKoMZxoyKMaNMurfyfategbWFaqCWJPlDfXYjFpnTghWrpV29ya3NwYWNl')).Ignore.FPSArms.LeftLowerArm.TextureID = TextureID
game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('xwHDEHbEwldMKLfsBMeBXPiVysPHEkQCSyMekxiEMvlHXzoBBqThqlRV29ya3NwYWNl')).Ignore.FPSArms.LeftHand.TextureID = TextureID
game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('CalYmTzwerbZXNLIkOYnIKBVqjoMuJKPidinHocHsdMSjQFQVWCVWOZV29ya3NwYWNl')).Ignore.FPSArms.RightUpperArm.TextureID = TextureID
game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('PvGiOyZrrplcEFzLSsTjUVfEFOlkIDBjqAoELxvBzknlokaTfjpfxqdV29ya3NwYWNl')).Ignore.FPSArms.RightLowerArm.TextureID = TextureID
game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('dWfbSAltAQCZLKQRxNKGLuAEVjPPSiTHptKCiOsOthCPrSwkgXwUKZTV29ya3NwYWNl')).Ignore.FPSArms.RightHand.TextureID = TextureID
end)

ExploitsTab:AddToggle(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('bsslVPcOZobRLGcIxYzMqnJDzWKoCVUVtyLCraSxejvkPpUmzdAsaTITk9TTE9XRE9XTg=='),{Text=tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('baOrjqBWDyfUQtqXwBOVSXRYuAGaAGQOwkwZpTtmTsPszUmXCDFMRchbm8gc2xvd2Rvd24='),Default=false}):OnChanged(function(Value)
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

local WorldEspTabBox = Tabs.Visual:AddRightTabbox(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('xoLlDLkAIyiLfzpsdsMrMASYjzYTRQdOaWXOXBIoTbrGxswwmeMHMAcd29ybGQgZXNw'))
local WorldEspTab = WorldEspTabBox:AddTab(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('FUAawLAPZUzPFAmUKhEjmurTbOCvzmggwnQyauCKttiqxDVtsHZmqRld29ybGQgZXNw'))

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

WorldEspTab:AddToggle(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('NKUagXtzeaaMBfRDUiLWoBeCGSOYpQnglzolUsfhhjEaOlnlvkAnSrIaXJvbl9Ub2dnbGU='),{Text=tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('aQCFXjNEOKELlVGJmVpQGFyKhlpMdrzOwwgGQQeCpfWPsqYXErWGuajZW5hYmxlZA=='),Default=false})

WorldEspTab:AddSlider(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('KDOdKbxAzyaymhiEDudwnATmzJIlYmaZHIPtlQNttpzyuLRlTLGeREWT3JlUmVuZGVyRGlzdGFuY2U='), {Text=tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('xJTNjPnDzAEDNhvStzkKkhKrwltegqinbTbAvJbthYQOrypWAYbttlnZGlzdGFuY2U6'),Default=1000,Min=1,Max=2500,Rounding=0,Compact=false,Suffix=tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('IfxHJtydhXWOIGIFIYGisqSkuySvCrfyiLblEeLAEXHUkEGyYyRqrUIIHN0dWRz')}):OnChanged(function(Value)
settings1.oreDistance = Value
end)

WorldEspTab:AddToggle(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('iMrkDptVgqZyzqvmitWSBQtUZzyPSNrCCEThlSgSritgVkiQaGYbQKWaXJvbl9Ub2dnbGU='),{Text=tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('efjTFHHTOZYnNsYksSJrXIfghQtxWNefjFscQEYZBDLaMUWeCKUAqFmaXJvbiBvcmU='),Default=false}):AddColorPicker(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('szfDyCYZUCYLRnqRlAoazWSIwxXqeBtuKBZSJtdhwPHhPwGnjsqAZRYSXJvbkNvbG9y'), { Default = Color3.fromRGB(199, 172, 120), Title = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('ADcPDawtXcwRlmpKjYbjhXCRJwNGAVWHJwsXSzMmwpsYgdAFGSDfZMIQ29sb3I='), }):OnChanged(function(Value)
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

WorldEspTab:AddToggle(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('NfNUkIlvanabDjLEEsQURyHzjqurlejVqIJAjKjGrSWGgQVNIuwiGPIbml0cmF0ZV9Ub2dnbGU='),{Text=tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('vtgSQfwAmuouezMJSDOhqgxSTlyXvAQeVpFvuquyAgvBSWzrjLZTAYgbml0cmF0ZSBvcmU='),Default=false}):AddColorPicker(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('OpqpdPgGdCeKcWEUMOULaGfYYsRUXyOKNAXykQMpvOOhAFUPNFbnusgTml0cmF0ZUNvbG9y'), { Default = Color3.fromRGB(248, 248, 248), Title = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('XzPmAEtvDlUmTpcQwDlGNSjwSSNjzgtHnhETRhhHJIcJRXrBLqmQYgXQ29sb3I='), }):OnChanged(function(Value)
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

WorldEspTab:AddToggle(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('rKLxOuHzVukhikhqcownCPaRcrPKBtFgDJnpcBpgGKjlndAYbrXKDyvc3RvbmVfVG9nZ2xl'),{Text=tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('lKnLolmywMrkyxYGXojLYJBbNzBcbGVDLxdkmLNpAcqqYlRzwyzoYtgc3RvbmUgb3Jl'),Default=false}):AddColorPicker(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('uWKQtnDZmWfOXfNtYsBTattCJeWIGrDRLypJlXQhkcwQbKYcKXfwUGhU3RvbmVDb2xvcg=='), { Default = Color3.fromRGB(205, 205, 205), Title = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('ljgGiEwszwhPkAtNCcTpgsKKKlATnhQzXqrugnXRYjZMZxQfewDlaDDQ29sb3I='), }):OnChanged(function(Value)
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
local final_text = tostring(text) .. tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('MAtzyiEIgljeWMFTWNIjaxPvBCvseHOjwpRfHENxMcqquoNSGytwJMyXG5b') .. tostring(distance) .. tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('yjSTgmlvpfVPPvdXVhBxBKuXjedUUsRdykpnJsPQaUPivmgPHglLIjcXSBzdHVkcw==')
return tostring(final_text)
end
local function worldtoviewport(position)
local a, b = workspace.CurrentCamera:WorldToViewportPoint(position)
return Vector2.new(a.X, a.Y), b
end
local function add_esp(part, text, colour, toggle)
local drawing_text = Drawing.new(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('uLueGooNjCWWBirjhhFGgDaFIeUTkmJojQLelruaTGFYXWEZfDZULsCVGV4dA=='))
drawing_text.Outline = textoutlines
drawing_text.Center = true
drawing_text.Visible = false
drawing_text.Font = Text1Font
drawing_text.Size = testsize
drawing_text.Color = colour
local rendersteploop = game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('MDsxhSUZWtyPaINLmufbgXDqDwTkaOjGZMaHqvVvcPtYiqchEKpAMwlUnVuU2VydmljZQ==')).RenderStepped:connect(function()pcall(function()
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
local oreDis = (game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('JRuKWYmUdoTtEIyeoGtMzZrjAqHKukXQNXbFdnxzvOCIjdTInnbJxzKV29ya3NwYWNl')).Ignore.LocalCharacter:WaitForChild(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('AgaaHaoESeNPIhIOpIlehOvcXrVqQstigJWNpEEmRrFwQMSZeXcsnbgVG9w')):GetPivot().Position-part_pos).Magnitude
if oreDis >= settings1.oreDistance then
  drawing_text.Visible = false
  drawing_text.Size = testsize
  drawing_text.Outline = textoutlines
  drawing_text.Font = Text1Font
  rendersteploop:Disconnect()
end
if text == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('HrSaYCBAGeZceNqxCgcAPpcuupnchWGusMQMazaRpPFpEBmCwWCueAWSXJvbg==') and not settings1.iron.enabled then
  drawing_text.Visible = false
  drawing_text.Color = settings1.iron.colour
  rendersteploop:Disconnect()
else if text == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('VQOBuvTEqGKhyfTRdzslSbuYLgKuasrqWfxDDEaudEbDUHzOCCxYQdUTml0cmF0ZQ==') and not settings1.nitrate.enabled then
  drawing_text.Visible = false
  drawing_text.Color = settings1.nitrate.colour
  rendersteploop:Disconnect()
else if text == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('XQcuaLbgncYmCoOoqqXNrhPPxXoPMWoxaHrnBEgVwNvlvFdLkdgXKIjU3RvbmU=') and not settings1.stone.enabled then
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
if (not v:IsA(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('zzGPsHvUEbXDuUNBDRHqgkmyyEJETXeZPHPuwHpVwaETyskNFMZBLHSTW9kZWw='))) then
return
end
local is_part = v:FindFirstChild(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('kScCEEIGXeKARaPuQTdZYxzPdtMLUeMQhqRDDNipKbRClYRWtFIVdQTUGFydA=='))
local children = v:GetChildren()
local child_amount = #children
if is_part then
if child_amount == 1 then
add_esp(is_part, tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('BJjMgaXkDttBTybMgfZmXNSjFufROKaPgITyznvZKyZIssdReLWCFnDU3RvbmU='), settings1.stone.colour, settings1.stone.enabled)
elseif child_amount == 2 then
for _, v in pairs(children) do
  local brickcolor = v.BrickColor
  local is_ore = v.ClassName == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('vTAiFwbkRfsvkMCMIvgsiwAVUmsoRxCdaNcsDQhHPDyXUOgbPAJqzcHTWVzaFBhcnQ=') and v.Name == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('RLQioDJnzgOBmRjqYQEcxQXBQMXNriLftYsMbOzPuMgNRIpMuQiGSckUGFydA==')
  if is_ore then
    if brickcolor == BrickColor.new(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('JNKpMGXRoVcPrENcPjkHdzTjoKiWTmWYHDfNJaIsprmyqAsSUIjLZDaSW5zdGl0dXRpb25hbCB3aGl0ZQ==')) then
      add_esp(v, tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('LbkIvlmsDsqAzbPAmifmFBMuMIBAJfRIMHTTlfQsjAcCBZhTqpwdmPhTml0cmF0ZQ=='), settings1.nitrate.colour, settings1.nitrate.enabled)
    elseif brickcolor == BrickColor.new(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('JPOwHZFRvyspBwvFQGDBcQvCDjWNVcgnPptbFvknWyFmhwSidAJxWLgQnVybGFw')) then
      add_esp(v, tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('JJXDyhDQxcphiCJeBwPAURvNSircfCOPEtrCFXAGsbVMdvSjnPjiJIISXJvbg=='), settings1.iron.colour, settings1.iron.enabled)
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

WorldEspTab:AddDivider(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('vuBaupAwtZcTySfgvfHUlZzOCrWhyIKjoCFSNMCnKiQDjULcedvMKcr'))

WorldEspTab:AddToggle(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('WwWcpNqIBgbCjFHsvGIYtzerpnRlFamsKfwoWPbwPbHYJbPstGmWMHQVGV4dE91dGxpbmUy'),{Text=tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('lUZnhiCpMISDClYHDaytGvyGRXRVrLsxNKKzgLjNCzGVdrevqaZFlcQdGV4dCBvdXRsaW5lcw=='),Default=true}):OnChanged(function(Value)
textoutlines = Value
end)

WorldEspTab:AddSlider(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('olISlkazlXbesAWnMgQRqesfwwtDvQawTwmQNPPnZFdHbQcruYnbCNPVGV4dFNpemVTbGlkZXIy'), {Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('hlDeLtWsSVSAQqKgRbkhmAsKPtwcZvevhoOmbRAnTJFwjUjunNILbbjdGV4dCBzaXplOg=='), Default = 12, Min = 1, Max = 25, Rounding = 0, Suffix = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('qgKPtxIGyTNOhkDcXxnGWMXtooKzCdqTWfwJErgujsneqQqngPfFXAxcHg='), Compact = false}):OnChanged(function(TextSizeValue2)
testsize = TextSizeValue2
end)

WorldEspTab:AddDropdown(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('EHPWKQZGgldozhGckPVEUEZhfNFFVflPNVPrLrxJtHzXzFrwYrakcZrRXNwRm9udDI='),{Values={tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('ITsAFBDgAWGZwilUuAHPcQCxRxiBQEaLekuwrKMKnYudzrKGEAvjqANMA=='),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('zAwuAvbXRYNXSwtSqACwBOmEwtHTyoUtykfEEXxnkdPMAGXvQZSDOjjMQ=='),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('GDsJTGJpSwtllfJFhpfZgAzlXbVIvhqNQZVVBReFgQVTRTlEHbuWlYyMg=='),tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('KERRgQKJwcinzgDrXNyIjKYoHZZeDyEGwvNZYcTSCVKktEKCFaHlIlpMw==')},Default=3,Multi=false,Text=tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('jYjYdvmiSGyaCweiRqLuZRedVhAzCMWfnOoaMHdYnmjmFstBglYNiHGZm9udDo=')}):OnChanged(function(Value)
Text1Font = Value
end)


local SpinbotTabBox = Tabs.Combat:AddRightTabbox(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('VYQeNvMegkNpbMEoTDDUUohkwvmQDIBVWAHZnfbIdRuJwABivDcHxifc3BpbmJvdA=='))
local SpinbotTab = SpinbotTabBox:AddTab(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('xRufKUnVYxrptACaOrZjyvFwmDZODJOuQxbBeuSYbzPcxoPeDTXXcJjc3BpbmJvdA=='))

--* Spinbot *--

local fakeduck = false
local Spinbot = false
local SpinbotSpeed = 3
local SpinbotType = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('vMwrBveQgxjoWYUcokyLmFCTmqsNfsEUYdOapWjGSfvDBTQchHDUlCOTm9ybWFs')
local value = 1
local SpinBotLM = false
local SpinBotV = false
SpinbotTab:AddToggle(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('VSjEYzGPMoAmmThHxyMMaNvvIIITrwCRINGwjquFWeghpdxSSllxMadU3BpbmJvdA=='),{Text=tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('juFYSfGEOvdzsJBSqswUdnkCnpeAHaLfjqvzkNhQlmNSRprCyyanMwtZW5hYmxlZA=='),Default=false}):OnChanged(function(Value)
Spinbot = Value
end)

SpinbotTab:AddSlider(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('oyIENdAuxAUMzixZUycyMYSjiuuFdGSpZHfVGaMtFVwrdAnzpzQeramU3BpbmJvdFNwZWVk'), {Text=tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('FsMeMXoViNAiSJuZDyOGiXCffCZhipfVBaYpvvLJXXaKfmIjtKiFYhvc3BlZWQ6'),Default=3,Min=1,Max=3,Rounding=0,Compact=false,Thickness = 3}):OnChanged(function(Value)
SpinbotSpeed = Value
end)

SpinbotTab:AddDropdown(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('SVEfgsvFrHESlCebhsouSWvRKpVzgjASUYZmhZLkLPhuDrjEjtiSUovU3BpbmJvdFR5cGU='), {Values = {tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('AKlpKOWpohCfesurgCrRAYIdzcfYIyCRHpJWiLTenUejFOskIlJpBxzTm9ybWFs'), tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('irhoklkXrsfJpCGFlcoitxPmOfBkUWILZXwDzkHBncOkuuHNhrDFmdFRGVzeW5j'), tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('MRQxzdgOUoLRiXymrZFJdXEdFTkzQZweeKjPJqNPLVCLXgFQrpvdsuAUmFuZG9t')},Default = 1,Multi = false,Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('xcAhHmCTjjkSKeYVslhpOSgpQkBwcqLXANzeuzJbQLmEtoUyfRmFrmEdHlwZTo=')}):OnChanged(function(Value)
SpinbotType = Value
end)

local OldSpinHook
OldSpinHook = hookfunction(game.Players.LocalPlayer:FindFirstChild(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('AFsHByXYIfNpPUReaqYPfoTapZmzEPmFgwfGPFCOCLWljAMqZVptizKUmVtb3RlRXZlbnQ=')).FireServer, function(self, ...)
local args = {...}
if args[1] and args[2] and args[1] == 1 and typeof(args[2]) == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('TzBFoqNuXyCEtAqnYDuqtWFAEwjmYSDprvGeyPZIzYLyMbsGuSbFDENVmVjdG9yMw==') and args[4] and Spinbot == true then
  if SpinBotLM == true and SpinbotType == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('NzfuqDaPszLPCqXSbLtwJDYZLhGyMaFmIrAccTSHQHXAVAtEcTPfcTKRGVzeW5j') then
    args[4] = value
    value = value + SpinbotSpeed
  elseif SpinbotType == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('DhNurtYqekkrSEwDJmgrETEHSNosBOpfwAylVdOUfgTlPWxeWPhjdBUTm9ybWFs') or SpinBotLM == false then
    args[4] = value
    value = value - SpinbotSpeed
  end
end
if args[1] and args[2] and args[1] == 1 and typeof(args[2]) == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('gPDgrXdNCFvIsCYNZOrcNLgseHzQBySZcgJGFvLIMoHoQlBPbPTKzfMVmVjdG9yMw==') and args[4] and Spinbot == true then
  if SpinBotV == true and SpinbotType == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('pTvfVFykpSlHVortquEqZfeNNbuxGNSTAQofLTowyaacnWCuHznDmgfRGVzeW5j') then
    args[3] = 1.5000001192092896
  elseif SpinbotType == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('IDdCxuoddGWSnRWMQRuCkMKSOsSzXDgUXPPaUNHQUMKMFbGDWoGMpLHTm9ybWFs') or SpinBotV == false then
    args[3] = -1.5000001192092896
  elseif SpinbotType == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('rAvsFFlyZCwvjqMxKKFPtZaKKZresJFtljoXlnzyijGLwjKoWaORwYoUmFuZG9t') or SpinBotV == false then
    args[3] = -1.5000001192092896
  end
end
return OldSpinHook(self, unpack(args))
end)
task.spawn(function()
while task.wait() do
  if SpinbotType == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('uFLcUPVnSLnqKuYFyUcPCzSQBZgmBZFoqgUZMnvLMKAEgJrXEXHIuTSRGVzeW5j') then
    SpinBotV = not SpinBotV
  end
end
end)
task.spawn(function()
while task.wait(0.1) do
  if SpinbotType == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('zPvIQuzOChMSurutRJPeFVzIqhnoJzFwOXYgzPzKPbaNJrhhPWFMZKcRGVzeW5j') or SpinbotType == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('RaoVXebbpvMLJAiJjvfEAyvEabtSqrMmjFWHdVoEvZGHMxGhYEyBeqUUmFuZG9t') then
    SpinBotLM = not SpinBotLM
  end
end
end)

SpinbotTab:AddToggle(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('BsAGkvOuhIlNPTFMuUXChUELXsDDooeptCAjuTFFNPSkprsrRZRRUfBRmFrZUNyb3VjaA=='), {Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('JLhhlaLZAhwcRIpLpkcFAQqoNbimCUSKkwTaqtMMdocOXBhTpRUBavVZmFrZSBkdWNr'),Default = false,Tooltip = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('vOWmLmFNOlvYcKjoszBZjFAbXskyvaRHiMZLCTqrBjfVlvARgpizxFLTWFrZXMgdSBjcm91Y2ggZm9yIG90aGVyIHBlb3BsZSBhbHNvIHRoZXkgY2FudCBoZWFyIHlvdXIgZm9vdHN0ZXBz')})
local OldCrouchHook; OldCrouchHook = hookfunction(game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('MHOoOKKGqlvRIXjyEFmGpggsnnxGYzReiqhDgZqDsuXqAJFbcwTSsTwUGxheWVycw==')).LocalPlayer:FindFirstChild(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('XDWvettcYmffoEiDrAybGwLQpRxYvXgRRAikdOLrMPPlixZsBHcNHsTUmVtb3RlRXZlbnQ=')).FireServer, function(self, ...)
local args = {...}
if args[1] == 2 and fakeduck == true then
  args[2] = true
end
return OldCrouchHook(self, unpack(args))
end)
Toggles.FakeCrouch:OnChanged(function() fakeduck = Toggles.FakeCrouch.Value end)
local function onFakeLagToggled(value)
  local networkClient = game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('PLbDRFQwEcdPjJwnPlTmuRPuzoObYkEBQysyuhCNEUAFgsyoIlMqERoTmV0d29ya0NsaWVudA=='))
  networkClient:SetOutgoingKBPSLimit(value and 1 or 100)
end
SpinbotTab:AddToggle(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('OcILQRhRfwGgchcuxbUtDHPypmJxJEycwEOzTTECSNdXsZMSpFepaYzRmFrZUxhZw=='), {Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('sgdvFxWQwJFlAbbEOOrrdmSRtfQmglJGMSejjWgaQwfreLbIlZQOdOsZmFrZSBsYWc='), Default = false}):OnChanged(onFakeLagToggled)

local WeaponModsTabBox = Tabs.Combat:AddRightTabbox(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('mCHAoepyRVnZfWiFdqdpGRGtdKYBxfxTNgHEzyyYNKGGBbVFaeWnsfYd2VhcG9uIG1vZGlmaWNhdGlvbnM='))
local WeaponModsTab = WeaponModsTabBox:AddTab(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('mWroMqfONpbIlMAwzzJQlnEadglOtpFzztQvKgFpVoqZJVckCsNvjoSd2VhcG9uIG1vZGlmaWNhdGlvbnM='))

local gunMods = {
  norecoilTog = false,
  noSpreadTog = false,
  firerateMultiTog = false,
  firerateMulti = 1,
  noReloadanimTog = false,
}

local GunModsEnabled = false
WeaponModsTab:AddToggle(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('CyOVEFMZxCzEHcOqunWiNGSdpiuzkQQuRGCarQZilybSybebferASQoRmlyZVR5cGVFbmFibGVk'), {Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('eNYcHFnvnXluBHZKOutdmiOkWhEdIamtCCPJgkeovDRISRmEkNFdOTFZW5hYmxlZA=='), Default = false}):OnChanged(function(EnabledFireType)
GunModsEnabled = EnabledFireType
end)

WeaponModsTab:AddToggle(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('kHXcrTaKfhUFnhXRrPrmJDtBBigsWFOTxlaVAyaZnkSetUcjfbyNFuaTm9SZWNvaWw='),{Text=tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('gFWhgVOYPbbfqoLICWxrDwbUSqWAwtEweOjJaekatWJIYNxajigKzMFbm8gcmVjb2ls'),Default=false}):OnChanged(function(Value)
gunMods.norecoilTog = Value
end)
local oldNoRecoil;oldNoRecoil = hookfunction(getrenv()._G.modules.Camera.Recoil,function(...)
if GunModsEnabled and gunMods.norecoilTog == true then
  return false
else
  return oldNoRecoil(...)
end
end)

WeaponModsTab:AddToggle(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('vrqEBNhdhIWtFjMEeWCMNIMtUYZTwqTqDIApOATccFfmamKwJhQcBKWTm9TcHJlYWQ='),{Text=tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('kaLzgFdvGnrDQZScVfntekkSDXmacXKlJZRewwcrYeNWaQmEnYIuBaebm8gc3ByZWFk'),Default=false}):OnChanged(function(Value)
gunMods.noSpreadTog = Value
end)
local oldNoSpread;oldNoSpread = hookfunction(getupvalues(getrenv()._G.modules.FPS.ToolControllers.RangedWeapon.PlayerFire)[1],function(...)
local arg = {...}
if GunModsEnabled and gunMods.noSpreadTog == true then
  arg[2][tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('EHkORodjLTgXbfANoOTwxmgcHpovXWoXjWENxnwuwDVHWiehLYzhrxAQWNjdXJhY3k=')] = math.huge
  return oldNoSpread(unpack(arg))
end
return oldNoSpread(...)
end)

WeaponModsTab:AddToggle(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('iACpNEqXhsTPINDSUIpNNxFOvOvZbMHOfGihKqyWSNZxLaaDJIOZENURmlyZXJhdGU='),{Text=tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('owLjTYsGNYMDQvazkfwJLUvKUFeidgfkmRSnGJBWSNJhPCkBhImoyohZmlyZXJhdGU='),Default=false}):OnChanged(function(Value)
gunMods.firerateMultiTog = Value
end)

WeaponModsTab:AddSlider(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('sCsgFqpIPXkddgogByFrGabevrOZgKBbqUjqedwpMHEVGrGbDfGnTkPZmlyZXJhdGVNdWx0aVM='), {Text=tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('EQllZmHlLKUHvZMuPWKFVKCWazQkPFLfKqDdOkCveYWMeWibQfUftFObXVsdGk6'),Default=0.5,Min=0,Max=1,Rounding=2,Compact=false}):OnChanged(function(Value)
gunMods.firerateMulti = Value
end)
local oldAttackCooldown;oldAttackCooldown = hookfunction(getupvalues(getrenv()._G.modules.FPS.ToolControllers.RangedWeapon.PlayerFire)[1],function(...)
local arg = {...}
if GunModsEnabled and gunMods.firerateMultiTog == true then
  arg[2][tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('QWHEJwJhSlWGTgFEczPMQkrPxbCkcBMSwcTkCNXxNaEChBzrFJIFGUJQXR0YWNrQ29vbGRvd24=')] = gunMods.firerateMulti
  return oldAttackCooldown(unpack(arg))
end
return oldAttackCooldown(...)
end)

local ItemConfigs = game.ReplicatedStorage.ItemConfigs
local weapons = {PipePistol = require(ItemConfigs.PipePistol),Blunderbuss = require(ItemConfigs.Blunderbuss),Crossbow = require(ItemConfigs.Crossbow),Bow = require(ItemConfigs.Bow),USP9 = require(ItemConfigs.USP9),LeverActionRifle = require(ItemConfigs.LeverActionRifle),GaussRifle = require(ItemConfigs.GaussRifle)}
local FireActions = {Semi = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('DLlDPSQiJCLxAlCSYFnQgSOrZRItqzgOZCtxXuywedghdyPRTOmuvoEc2VtaQ=='),Auto = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('AwDyhGmiJUXmKJdWTtyCDumJcnGsZrpznQJgEgpMPmniqUyngaYVauRYXV0bw==')}
WeaponModsTab:AddDropdown(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('xWsofjuivgdNxyodguaVHmRZItiigIbHojeaMBjcOVxlZlnrrdHtTDBRmlyZVR5cGVEcm9wZG93bg=='), {Values = {tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('ZBMzRuHtHHxaQfsmpZySBimRySWWMnqQTKOQhfohoWNAqwpMOCnKNlIU2VtaQ=='), tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('cElwEFJUWRpkrYxxSynXjwkKkMOUEZPfzrlTtFlrcOcjPPDWqfHNFoWQXV0bw==')},Default = 1,Multi = false,Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('wemKszRTHBdWRnduvOmIbdZUXkRBwTOKQhwgXUspjFsIZYwXlLsAqSxZmlyZSB0eXBlOg==')}):OnChanged(function(Value)
if GunModsEnabled then
  local fireAction = FireActions[Value]
  for _, weapon in pairs(weapons) do
    weapon.FireAction = fireAction
  end
end
end)

local FieldOfViewTabBox = Tabs.Combat:AddLeftTabbox(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('AJfvwofUVzvTwWeSPDyVTAGTRwayQoiSdjCQlulzHwKHtqVeLMQmmdSZmllbGQgb2Ygdmlldw=='))
local FieldOfViewTab = FieldOfViewTabBox:AddTab(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('HDUIYSjjcFFchCDSqzEANxflcDVZmbNaRQIInWzTdmmHvdWaNUcfxxiZmllbGQgb2Ygdmlldw=='))

--* Field Of View *--

local FieldOfViewEnabled = false
local FieldOfViewValue = 70
local CurrentSliderValue3 = 70
game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('eLtKDbsiILEgSEewVyxUfIFNMzQNsqRSZzMXIukzoZnNEcDvxdZpqmnUnVuU2VydmljZQ==')).RenderStepped:Connect(function()
local fovFunc = nil
for i,v in pairs(getreg()) do
if type(v) == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('spGMxWJiJifTHqyJjdXNSoaemofnjmuZyDBLgGOuvNlDPWSEnKZcGNiZnVuY3Rpb24=') and getfenv(v).script.Name == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('IlSgLitJKDJMzvcWiavZMezNGKICuNKtTncoHRdOWeOJSlIyDIzROMAQ2FtZXJh') and #getupvalues(v) >= 18 then
  fovFunc = v
end
end
setupvalue(fovFunc,18,FieldOfViewValue)
end)

FieldOfViewTab:AddToggle(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('iVOAwrUfEpVpWbNzYYzADTayHhskGdrzLjSBBKLhYyYqhVgUUIxiilJRmllbGRPZlZpZXc='), { Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('OPbOEvIbOgDwjHHQZblwWacrjsuWCLDBXNSAqmoDomnObssLTXxjuYPZW5hYmxlZA=='), Default = false }):AddKeyPicker(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('AfqVwtOKparYUqKVInqXUfCIsTHfwQEKWoJdIikoOseDYDwZetfXMVoZmllbGRvZnZpZXdrZXk='), { Default = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('ylGsSrPLAOEEKlpmyYTjGAOVydUKKEthAmucoUegpTwcgKffbIlDaNFTm9u'), SyncToggleState = true, Mode = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('WzxBnFTLDwjMIZgwStpKTIyKzsMVITIOOCUxwXQkvVpAIAFxXMXCWxJVG9nZ2xl'), Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('ZzUusyrBCsMByDaDWZXRawqTyyqgdkPHbPFabPevPZOiuGPkpiYgrwyZmllbGQgb2Ygdmlldw=='), NoUI = true }):OnChanged(function(value)
FieldOfViewEnabled = value
if not FieldOfViewEnabled then
FieldOfViewValue = 70
else
FieldOfViewValue = CurrentSliderValue3
end
end)

FieldOfViewTab:AddSlider(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('RoBDIKLmdVRbZwZFwHsXyLxqzHOxggraloucRwbYJGayidgHTshJzXLRmllbGRPZlZpZXdTbGlkZXI='), { Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('AurSVGLTYMXvYEKgCsMLXaLlvgFMQpCIZnDYxRvfOIMWojpHNqBrVLCZmllbGQgb2Ygdmlldzo='), Suffix = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('OJprGpvIOGpjywdktLqHeXUPcWivIUnliISXzLumHRXXXxhPXbjdRYCeA=='), Default = 70, Min = 0, Max = 120, Rounding = 0, Compact = false }):OnChanged(function(sliderValue)
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

ExploitsTab:AddToggle(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('zyploPzrQNgaVSyPQTZniJFbulXaOiiKAdHEpDzWvWZePWDeiNiKTJxSnVtcFNob290'),{Text=tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('YzFuheqhKtQdHlQskWHypGVypAIKiDZRWrTqJkrFGatJSBHqYCWkHJRanVtcCBzaG9vdA=='),Default=false}):OnChanged(function(Value)
Misc.Settings.JumpShoot = Value
end)
local oldIsGrounded;oldIsGrounded = hookfunction(getrenv()._G.modules.Character.IsGrounded,function(...)
if Misc.Settings.JumpShoot == true then
return true
else
return oldIsGrounded(...)
end
end)

ExploitsTab:AddToggle(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('CpWZuSvbEpPuSOGFWQnNOxDiRvzIxPZnSziVVbijOmibJHAuchlqdctTm9BRFM='),{Text=tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('aKdaRCLDJBNqvYjdZWYqZKmxrpVDwHkWMQrnBNXReccHpNVkIFLzsPybm8gYWRz'),Default=false}):OnChanged(function(Value)
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
ExploitsTab:AddToggle(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('eggdWGgAsJaFKbLvUywfPfXAKdXPLBjJkcATFcPuUUOdaoVmaphhnpVTm9Td2F5'),{Text=tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('QXajKepGzzGFVdpetqZwFNlesZPpnmQaWqJRLdcArtehQvjxBobmATfbm8gc3dheQ=='),Default=false}):OnChanged(function(Value)
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
local WatermarkConnection = game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('iqFuEmRvoynVTBizKAVrmUFzUiBAjZNVbRGoujlNHPmihqKgMgJpXxpUnVuU2VydmljZQ==')).RenderStepped:Connect(function()
    FrameCounter += 1;

    if (tick() - FrameTimer) >= 1 then
        FPS = FrameCounter;
        FrameTimer = tick();
        FrameCounter = 0;
    end;

    Library:SetWatermark((tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('yxlzYISooYqipQgeGErwrmzDKnXInvIlewvysLMNsAWrjmLKdfVwHgZc2thZmZmLnNraWQgfCAlcyBmcHMgfCAlcyBtcw==')):format(
        math.floor(FPS),
        math.floor(game:GetService(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('VbZherICMDMrAljpNvunufflDIeLTfiIyXRtUXSDitHKkwpYCktpxTWU3RhdHM=')).Network.ServerStatsItem[tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('pxzalaHUJhJMqJKPbmWNuhmkeSKbWPqxpOOGsnCbpOTHPLtcBMKpblTRGF0YSBQaW5n')]:GetValue())
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

local MenuGroup = Tabs[tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('jbitEtACORtogVFTxHwheJPYxZovRxIXWSiyzWwGjokUhvIMqnZqxrCVUkgU2V0dGluZ3M=')]:AddLeftGroupbox(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('rOWiFkOgAIQtSFhZrOjZIEmFdBagMszpqEXkojQHUWLLxmLzadDcAkVTWVudQ=='))
MenuGroup:AddButton(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('nvceDPSRQFKmKPoOpDtmyddyoaqUvcZYIZQVoNCZsVLhtuakiWVEzoAVW5sb2Fk'), function() Library:Unload() end)
MenuGroup:AddLabel(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('zgKKatBINOYoyJMrTFmreggfiwavkwXtnMzsxADWnRqQlNRAafIOjoUTWVudSBiaW5k')):AddKeyPicker(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('YURCFedgsHpMCGXmGLzILgfZCGpOhRUPqnujNvgjMuNPqYTNZCAekaKTWVudUtleWJpbmQ='), { Default = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('BVMYXgybWNziJYOoRBpvYSZPkBoQGDWMnCiGTclrKQvqXRAHLgSwMTvRW5k'), NoUI = true, Text = tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('pDKZlFcBzsHwEIEQHniSpXgpGIdOhoDBvtBacDiWpjKthFgqnXfoJNZTWVudSBrZXliaW5k') })
Library.ToggleKeybind = Options.MenuKeybind
ThemeManager:SetLibrary(Library)
SaveManager:SetLibrary(Library)
SaveManager:IgnoreThemeSettings()
SaveManager:SetIgnoreIndexes({ tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('sEsjDMzPFsrmxcireOGhbmWAsvMEsOFvEvWXVKWBXCFxoWHfDJCUmczTWVudUtleWJpbmQ=') })
ThemeManager:SetFolder(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('UWvboEJArqXejbrmOXybARjfabRPvvHcDfOZqAdgZHHtVCuAfhgrKcac2thZmZmc2tpZA=='))
SaveManager:SetFolder(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('YOAcOoEhIyAiScEIzOMUbyKDMcNNxogAvWcGioEFjAHCQJqJZbaisLic2thZmZmL1RyaWRlbnRTdXJ2aXZhbE5vQWN0b3I='))
SaveManager:BuildConfigSection(Tabs[tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('SVIPBrjXOhlmxOYtQBwCHJAlTlwitenFxQCYrJITeHumZkGyWaPfcbbVUkgU2V0dGluZ3M=')])
ThemeManager:ApplyToTab(Tabs[tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('QpBwPsHojJWMKLqIhhmqpcoiEZHlZRXbQZZNrVxUUsOvinhSGmaEqQbVUkgU2V0dGluZ3M=')])
SaveManager:LoadAutoloadConfig()

Library:Notify(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('MuWlBePmSAFSHeyGuSiLnNkHsSLusBgwWxXldZJnwprNcPigUQtwKDAd3NnIA==')..game.Players.LocalPlayer.Name..tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('AjCdzaxEhDhfVJiIylFSDspgXYezhOPTVYmGmsrTdlMBknovGZpggngIHRoeCBmb3IgdXNpbmcgc2thZmZmLnNraWQ='),8)
Library:Notify(tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('IvEHketFQFUFiXNqLLAIrCcyvEtAYKXLTqkgbBOBHjpjvBqXhWWAikSU3RhdHVzOiBVbmRldGVjdGVkIPCfn6k='),8)
  local notifyPlayerChange = function(player, message, color)
  local prefix = player:IsFriendsWith(game.Players.LocalPlayer.UserId) and tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('kyqBOwmphwVMeSZLqiSmjeVLXhkoAKfBtdLlAwfLNxiUEYLYpaHGHWmbm90aWZpY2F0aW9uIC0gZnJpZW5k') or tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('tCYhNgySlekuVvMaXgPtnOjZtrhxzwhGdXKNtSMAPMtrrssjAVmEzEWbm90aWZpY2F0aW9uIC0gcGxheWVy')
  Library:Notify((tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('vWKXbNaxpymDxJtgMKuXHoUsOahwgNdcgivMfENcrbaPxixHysgNkJnJXMgfCB1c2VyOiAlcyB8ICVz')):format(prefix, player.DisplayName, message), prefix == tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('eLsphJPYcPtgetSVtzdbsogZMfBIZpkXMhgdURsmrKloGBGeQjnjuFDbm90aWZpY2F0aW9uIC0gZnJpZW5k') and 6 or 3, color)
end
game.Players.PlayerAdded:Connect(function(player)
notifyPlayerChange(player, tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('fqamNybFxkXlshwlAKddOEVtfPYkkwAYaKxbBmUvlHnCTlTJAdaUrLiam9pbmVk'), Color3.fromRGB(0, 255, 0))
end)
game.Players.PlayerRemoving:Connect(function(player)
notifyPlayerChange(player, tpOunkUyfGqmvEyszjlqNDViOcfwGFjjjSyHVJOhKgJCWSftNHGpHHPoneTXDjUKYvPmROTeVywUArWnvfeBYuwScB('jzlYiAUMhwcTBpJgemFsgFXpbCtvNonRwRuXTbOLRdSYLQQTWboKPBAbGVmdA=='), Color3.fromRGB(255, 0, 0))
end)    
