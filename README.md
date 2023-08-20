local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "ผีหลอกวิญญาณหลอน😱😱", HidePremium = false, lntroText = "Goldenhub", SaveConfig = true, ConfigFolder = "OrionTest"})

local Tab = Window:MakeTab({
	Name = "OP script",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})


OrionLib:MakeNotification({
	Name = "",
	Content = "ขอให้สนุก🥰",
	Image = "rbxassetid://4483345998",
	Time = 5
})


Tab:AddButton({
	Name = "กดแล้วใช้ไอเทมดู🥱🥱",
	Callback = function()
      		g = hookfunction(wait, function(seconds)
return g(0)
end)
  	end    
})

OrionLib:Init()
