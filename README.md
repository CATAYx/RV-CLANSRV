local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()

local Window = OrionLib:MakeWindow({Name = "RV CLANS", HidePremium = false, SaveConfig = true, ConfigFolder = "السكربت من صنع شاتاي الشعار RV"})

--[[
Name = <string> - The name of the UI.
HidePremium = <bool> - Whether or not the user details shows Premium status or not.
SaveConfig = <bool> - Toggles the config saving in the UI.
ConfigFolder = <string> - The name of the folder where the configs are saved.
IntroEnabled = <bool> - Whether or not to show the intro animation.
IntroText = <string> - Text to show in the intro animation.
IntroIcon = <string> - URL to the image you want to use in the intro animation.
Icon = <string> - URL to the image you want displayed on the window.
CloseCallback = <function> - Function to execute when the window is closed.
]]

local Tab = Window:MakeTab({
	Name = "Brookhaven RP",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

--[[
Name = <string> - The name of the tab.
Icon = <string> - The icon of the tab.
PremiumOnly = <bool> - Makes the tab accessible to Sirus Premium users only.
]]

local Section = Tab:AddSection({
	Name = "السكربت من صنع شاتاي الشعار RV"
})

--[[
Name = <string> - The name of the section.
]]

Tab:AddButton({
	Name = "Redz hub",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/REDzHUB/REDzHUB/main/REDzHUB"))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "Sender X",
	Callback = function()loadstring(game:HttpGet(('https://raw.githubusercontent.com/kigredns/sanderXNewVersion/main/sanderX')))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "راقدول!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/VR7ss/OMK/main/VR7%20RAGDOLL"))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "R4D!",
	Callback = function()loadstring(game:HttpGet('https://raw.githubusercontent.com/M1ZZ001/BrookhavenR4D/main/Brookhaven%20R4D%20Script'))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "رحمه اجنبي!",
	Callback = function()loadstring(game:HttpGet('https://raw.githubusercontent.com/n0kc/AtomicHub/main/Script.lua'))() 
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "رحمه عربي!",
	Callback = function()loadstring(game:HttpGet('https://raw.githubusercontent.com/Ndora1/Ndora1/main/Nokia%20Hub.lua'))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "منع تخريب!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/hasan08122020108181818/devronaldo/main/antithsuireboe.lua"))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "Infinite Yiled!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/Infinite-Store/Infinite-Store/main/main.lua"))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "صمله صنع شاتاي!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/2dgeneralspam1/scripts-and-stuff/master/scripts/LoadstringypVvhJBq4QNz",true))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "TP Tool!",
	Callback = function()loadstring(game:HttpGet("https://scriptblox.com/raw/Brookhaven-RP-Mikeexc-Tptool-V1-10960"))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "1x1x1x1 سكربت!",
	Callback = function()loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-1x1x1x1-blue-gui-ANOTHER-VERSION-OF-1X1X1X1-GUI-PLS-NO-HATE-14099"))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "Rips hub!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/CasperFlyModz/discord.gg-rips/main/FPSBooster.lua"))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "رقصات!",
	Callback = function()loadstring(game:HttpGet("https://scriptblox.com/raw/Brookhaven-RP-all-emotes-6849"))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "طيران!",
	Callback = function()loadstring("\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\40\39\104\116\116\112\115\58\47\47\103\105\115\116\46\103\105\116\104\117\98\117\115\101\114\99\111\110\116\101\110\116\46\99\111\109\47\109\101\111\122\111\110\101\89\84\47\98\102\48\51\55\100\102\102\57\102\48\97\55\48\48\49\55\51\48\52\100\100\100\54\55\102\100\99\100\51\55\48\47\114\97\119\47\101\49\52\101\55\52\102\52\50\53\98\48\54\48\100\102\53\50\51\51\52\51\99\102\51\48\98\55\56\55\48\55\52\101\98\51\99\53\100\50\47\97\114\99\101\117\115\37\50\53\50\48\120\37\50\53\50\48\102\108\121\37\50\53\50\48\50\37\50\53\50\48\111\98\102\108\117\99\97\116\111\114\39\41\44\116\114\117\101\41\41\40\41\10\10")()

  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "ARAB SCR!",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/ARAB-SCR/ARAB-SCR/main/AR"))()

      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

local Tab = Window:MakeTab({
	Name = "Blox fort",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

--[[
Name = <string> - The name of the tab.
Icon = <string> - The icon of the tab.
PremiumOnly = <bool> - Makes the tab accessible to Sirus Premium users only.
]]

local Section = Tab:AddSection({
	Name = "السكربت من صنع شاتاي الشعار RV"
})

Tab:AddButton({
	Name = "Redzhub!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/REDzHUB/BloxFruits/main/redz9999"))()

      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "Vector Hub!",
	Callback = function()loadstring(game:HttpGet("https://pastebin.com/raw/4QtEAA6g"))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "zia hub!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/AnDepZaiHub/AnDepZaiHubBeta/main/AnDepZaiHubBeta.lua"))()

      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "تجميع صناديق!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/ahmadsgamer2/Zekrom-Hub-X/main/Zekrom-Hub-X-exe", true))()

      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "AnSit hub!",
	Callback = function()loadstring(game:HttpGet(("https://raw.githubusercontent.com/AnSitDz/AnSitHub/main/BloxFruits"),true))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "systen blox!",
	Callback = function()loadstring(game:HttpGet("https://scriptblox.com/raw/Universal-Script-System-hub-V2-13161"))()
 
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "ايم بوت!",
	Callback = function()loadstring(game:HttpGet"https://raw.githubusercontent.com/Basicallyy/Basicallyy/main/MinGamingV4.lua")()


      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "Speed hub!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/AhmadV99/Speed-Hub-X/main/Speed%20Hub%20X.lua"))()

      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "Radon hub!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/x2-Neptune/RadonHub/main/Script.lua"))()

      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "سكربت اسطوري!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/Basicallyybeta/main/main/Mingaming.lua"))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "ray hub!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/SeaBabyBF/X-rayse/main/X-RayHub"))()
 
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "Ver hub جديد!",
	Callback = function()loadstring(game:HttpGet"https://raw.githubusercontent.com/PNguyen0199/Script/main/Fai-Fao-Ver2.lua")()

      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "طيران!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/pro1x1/Fly-scrip/main/Fly%20scrip"))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

local Tab = Window:MakeTab({
	Name = "mm2",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

--[[
Name = <string> - The name of the tab.
Icon = <string> - The icon of the tab.
PremiumOnly = <bool> - Makes the tab accessible to Sirus Premium users only.
]]

local Section = Tab:AddSection({
	Name = "السكربت من صنع شاتاي الشعار RV"
})

Tab:AddButton({
	Name = "عدم موت!",
	Callback = function()loadstring(game:HttpGet("https://pastebin.com/raw/4izZLAmH"))()

      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "ايم بوت!",
	Callback = function()loadstring(game:HttpGet('https://pastebin.com/raw/71YWvURH'))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "فيه كل شيئ!",
	Callback = function()loadstring(game:HttpGet('https://raw.githubusercontent.com/scriptemt/CE-Technologies/main/script', true))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "Ruby hub!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/Deni210/murdersvssherrifsduels/main/rubyhub", true))()

      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "VR7!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/VR7ss/VR7/main/MM2"))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "s_o_a_b!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/s-o-a-b/nexus/main/loadstring"))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "جديد!",
	Callback = function()loadstring(game:HttpGet("https://pastebin.com/raw/UTuWzEcZ"))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "اسطوري!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/Au0yX/Community/main/XhubMM2"))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "Xhub!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/Au0yX/Community/main/XhubMM2"))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "Kinh!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/LOLking123456/eggs/main/MM2"))()

      	
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "xking!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/Soxpcoxod/Tt/main/Kigogi"))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "مره اسطوري!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/Joystickplays/psychic-octo-invention/main/yarhm.lua", false))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "ثاني من صنع VR7!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/VR7ss/VR7/main/MM2"))()

      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "جديد mm2!",
	Callback = function()loadstring(game:HttpGet('https://pastebin.com/raw/PGCZSiAY'))()
 
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

local Tab = Window:MakeTab({
	Name = "Balde bal ",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

--[[
Name = <string> - The name of the tab.
Icon = <string> - The icon of the tab.
PremiumOnly = <bool> - Makes the tab accessible to Sirus Premium users only.
]]

local Section = Tab:AddSection({
	Name = "السكربت من صنع شاتاي الشعار RV"
})


Tab:AddButton({
	Name = "Baldebal1!",
	Callback = function()loadstring(game:HttpGet('https://pastebin.com/raw/71YWvURH'))()
 
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "Baldebal2!",
	Callback = function()loadstring(game:HttpGet('https://pastebin.com/raw/71YWvURH'))()
 
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "Baldebal3!",
	Callback = function()loadstring(game:HttpGet('https://raw.githubusercontent.com/scriptemt/CE-Technologies/main/script', true))()

      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "Baldebal4!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/Deni210/murdersvssherrifsduels/main/rubyhub", true))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "Baldebal5!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/VR7ss/VR7/main/MM2"))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "Baldebal6!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/s-o-a-b/nexus/main/loadstring"))()
 
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "Baldebal7!",
	Callback = function()loadstring(game:HttpGet("https://pastebin.com/raw/UTuWzEcZ"))()

      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "Baldebal8!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/Au0yX/Community/main/XhubMM2"))()

      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "Baldebal7!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/Au0yX/Community/main/XhubMM2"))()

      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "Baldebal10!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/LOLking123456/eggs/main/MM2"))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "Baldebal11!",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Soxpcoxod/Tt/main/Kigogi"))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "Baldebal12!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/Joystickplays/psychic-octo-invention/main/yarhm.lua", false))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "Baldebal13!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/VR7ss/VR7/main/MM2"))()

      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

local Tab = Window:MakeTab({
	Name = "Adopt me ",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

--[[
Name = <string> - The name of the tab.
Icon = <string> - The icon of the tab.
PremiumOnly = <bool> - Makes the tab accessible to Sirus Premium users only.
]]

local Section = Tab:AddSection({
	Name = "السكربت من صنع شاتاي الشعار RV"
})

Tab:AddButton({
	Name = "Freehub!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/FreeeScripts/FREEHub/main/Loader", true))()

      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "YTPLhub!",
	Callback = function()loadstring(game:HttpGet('https://gitfront.io/r/ReQiuYTPL/wFUydaK74uGx/hub/raw/ReQiuYTPLHub.lua'))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "ادوبت مي!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/Dan..."))();
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "مره قوي!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/Ultra-Scripts/AdoptmeScript/main/AdoptmeScript/1XED629-adopt-me.lua"))()

      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "قديم!",
	Callback = function()loadstring(game:HttpGet("https://pastebin.com/raw/wx7J90FD"))();

      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "اسطوري!",
	Callback = function()loadstring(game:HttpGet('https://raw.githubusercontent.com/Penguin285/AdoptMe/main/tradeScam'))()
 
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "Dope pet!",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/AdoptMeScript-VIP/AutoFarm/main/DupePets"))()

      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "جديد!",
	Callback = function()loadstring(game:HttpGet("https://rentry.org/wdo4kv67/raw",true))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "جديد كمان!",
	Callback = function()loadstring(game:HttpGet("https://pastebin.com/raw/ZpKCYua3"))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "نادر جدا!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/xvkzi/adopt-me/main/duper"))()

      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "Julhub!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/Ult..."))()

      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "سكربت قوي!",
	Callback = function()loadstring(game:HttpGet("https://egorikusa.space/ba5805141d57d3db8a9c30e4.lua", true))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "Bxlixhub!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/trdrock/adoptMe/main/BxlixHuB"))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "piggy 1!",
	Callback = function()loadstring(game:HttpGet(('https://raw.githubusercontent.com/lolpoppyus/Roblox-Lua/master/Piggy'),true))()

      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "piggy 2!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/ICraftPe/ICraftPe/main/UniversalScript"))()
 
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "lolpop hub !",
	Callback = function()loadstring(game:HttpGet(('https://raw.githubusercontent.com/lolpoppyus/Roblox-Lua/master/Piggy'),true))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "نادر مره !",
	Callback = function()loadstring(Game:HttpGet("https://pastebin.com/raw/xRHcjXVs", true))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "اخر اصدار !",
	Callback = function()loadstring(game:HttpGet(('https://raw.githubusercontent.com/lolpoppyus/Roblox-Lua/master/Piggy'),true))()

      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

local Tab = Window:MakeTab({
	Name = "Tower of Hell",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

--[[
Name = <string> - The name of the tab.
Icon = <string> - The icon of the tab.
PremiumOnly = <bool> - Makes the tab accessible to Sirus Premium users only.
]]

local Section = Tab:AddSection({
	Name = "السكربت من صنع شاتاي الشعار RV"
})

Tab:AddButton({
	Name = "Tower of Hell 1!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/GamingScripter/scripts/main/TOH", true))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "Tower of Hell 2!",
	Callback = function()loadstring(game:HttpGet('https://pastebin.com/raw/BbVHjH56'))()
 
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "TrixAde hub!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/TrixAde/Proxima-Hub/main/Main.lua"))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "ventore hub !",
	Callback = function()loadstring(game:HttpGet("https://venture-lol.vercel.app/Main.lua"))()

      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "قديم !",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/MinionRoblox/Tower-of-Hell/main/Scripts%20from%20Minion"))()

      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

local Tab = Window:MakeTab({
	Name = "شاليه محمد ",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

--[[
Name = <string> - The name of the tab.
Icon = <string> - The icon of the tab.
PremiumOnly = <bool> - Makes the tab accessible to Sirus Premium users only.
]]

local Section = Tab:AddSection({
	Name = "السكربت من صنع شاتاي الشعار RV"
})

Tab:AddButton({
	Name = "تخريب الشاليه 1!",
	Callback = function()loadstring(game:HttpGet('https://pastebin.com/raw/TL6mAArq'))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "ArabXhub!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/Au0yX/ArabXHub/main/ChaletMuhammad.Lua"))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "سكربت 1x1x1x1النادر !",
	Callback = function()
loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-1x1x1x1-blue-gui-ANOTHER-VERSION-OF-1X1X1X1-GUI-PLS-NO-HATE-14099"))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "رحمه شاليه !",
	Callback = function()loadstring(game:HttpGet('https://raw.githubusercontent.com/n0kc/AtomicHub/main/Script.lua'))() 

      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "ادمن الشاليه !",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/Infinite-Store/Infinite-Store/main/main.lua"))()
      		
  	end    
})

local Tab = Window:MakeTab({
	Name = "Arsenal ارسينال ",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

--[[
Name = <string> - The name of the tab.
Icon = <string> - The icon of the tab.
PremiumOnly = <bool> - Makes the tab accessible to Sirus Premium users only.
]]

local Section = Tab:AddSection({
	Name = "السكربت من صنع شاتاي الشعار RV"
})

Tab:AddButton({
	Name = "ارسينال 1!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/tbao143/thaibao/main/TbaoHubArsenal"))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "! ارسينال 2",
	Callback = function()loadstring(game:HttpGet(("https://raw.githubusercontent.com/Maikderninja/Maikderninja/main/PWNERHUB.lua"), true))()
 
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "ارسينال3!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/DomainXV3/DomainX/main/virtual.cc",true))()
 
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "OwlHub !",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/CriShoux/OwlHub/master/OwlHub.txt"))();

      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "Tect-menu hub!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/Infinity2346/Tect-Menu/main/Arsenalscript.txt"))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

local Tab = Window:MakeTab({
	Name = "Blox borg بلوكس بورج",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

--[[
Name = <string> - The name of the tab.
Icon = <string> - The icon of the tab.
PremiumOnly = <bool> - Makes the tab accessible to Sirus Premium users only.
]]

local Section = Tab:AddSection({
	Name = "السكربت من صنع شاتاي الشعار RV"
})

Tab:AddButton({
	Name = "BloxBorg 1!",
	Callback = function()loadstring(game:HttpGet('https://whimper.xyz/kitty'))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "bloxborg 2!",
	Callback = function()loadstring(game:HttpGet("https://vysorbloxburg.vercel.app/free.lua", true))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "bloxborg 3!",
	Callback = function()loadstring(game:HttpGet("https://bloxburger.eu/scripts/free/script.lua"))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "free hub!",
	Callback = function()loadstring(game:HttpGet("https://bloxburger.eu/scripts/free/script.lua"))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "قديم!",
	Callback = function()loadstring(game:HttpGet("https://bloxburger.eu/scripts/free/script.lua"))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

local Tab = Window:MakeTab({
	Name = "Meepcity",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

--[[
Name = <string> - The name of the tab.
Icon = <string> - The icon of the tab.
PremiumOnly = <bool> - Makes the tab accessible to Sirus Premium users only.
]]

local Section = Tab:AddSection({
	Name = "السكربت من صنع شاتاي الشعار RV"
})

Tab:AddButton({
	Name = "Meepcity 1!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/COP...",true))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "Meepcity 2!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/synolope/mpcity/main/loader.lua",true))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "Meepcity 3!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/synolope/mpcity/main/loader.lua",true))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "Meepcity 4!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/AnonyProArg/ScriptsRobloz/main/OneCreatorX.lua"))()

      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "Meepcity 5!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/Bannable666/Scripts/main/Meep.txt", true))()

      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

local Tab = Window:MakeTab({
	Name = "shindo ماب  ",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

--[[
Name = <string> - The name of the tab.
Icon = <string> - The icon of the tab.
PremiumOnly = <bool> - Makes the tab accessible to Sirus Premium users only.
]]

local Section = Tab:AddSection({
	Name = "السكربت من صنع شاتاي الشعار RV"
})

Tab:AddButton({
	Name = "shindo script 1!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/SxnwDev/Premier/main/Free-Premier.lua",true))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "shindo script 2!",
	Callback = function()loadstring(game:HttpGet("https://pastebin.com/raw/1SWd5EaD"))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "shindo script 3!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/IkkyyDF/ProjectNexus/main/Loader.lua"))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "shindo script 4!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/SxnwDev/Premier/main/Free-Premier.lua", true))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "shindo script 5!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/IkkyyDF/ProjectNexus/main/Loader.lua"))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

# RV-CLANSRV
