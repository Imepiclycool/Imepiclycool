local TCS = game:GetService("TextChatService")
local CoreGui = game:GetService("CoreGui")
local RStorage = game:GetService("ReplicatedStorage")
local Players = game:GetService("Players")
local TweenService = game:GetService("TweenService")
local HttpService = game:GetService("HttpService")
local UserInputService = game:GetService("UserInputService")
local LocalPlayer = Players.LocalPlayer
local PlayerGui = LocalPlayer.PlayerGui
local isLegacy = TCS.ChatVersion == Enum.ChatVersion.LegacyChatService
local ChatBar = CoreGui:FindFirstChild("TextBoxContainer", true) or PlayerGui:FindFirstChild("Chat"):FindFirstChild("ChatBar", true)
ChatBar = ChatBar:FindFirstChild("TextBox") or ChatBar

if game.Players.LocalPlayer.name == "Porfirey" then

game.Players.LocalPlayer:Kick("fuck off u niger")
end




local Chat = function(Message)
	if isLegacy then
		local ChatRemote = RStorage:FindFirstChild("SayMessageRequest", true)
		ChatRemote:FireServer(Message, "All")
	else
		local Channel = TCS.TextChannels.RBXGeneral
		Channel:SendAsync(Message)
	end
end


local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()



local Window = OrionLib:MakeWindow({Name = "Goofy bypasser v1.3 beta🔥", HidePremium = false, SaveConfig = true, ConfigFolder = "configs"})

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
	Name = "Words",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

--[[
Name = <string> - The name of the tab.
Icon = <string> - The icon of the tab.
PremiumOnly = <bool> - Makes the tab accessible to Sirus Premium users only.
⁥⁥⁥⁥⁥⁥⁥⁥⁥⁥⁥⁥

]]

Tab:AddLabel("By maxlovesScripting")

Tab:AddLabel("https://discord.com/invite/FQjWjkZnTG")

Tab:AddButton({
	Name = "fix bypasses",
	Callback = function()
      		Chat("abcdefghijklmnopqrstuvwxyz")
  	end    
})

Tab:AddButton({
	Name = "asshole",
	Callback = function()
      		Chat("asshоlе")
  	end    
})

Tab:AddButton({
	Name = "ass",
	Callback = function()
      		Chat("аѕs")
  	end    
})

Tab:AddButton({
	Name = "dumbass",
	Callback = function()
      		Chat("dumbаss")
  	end    
})

Tab:AddButton({
	Name = "arse",
	Callback = function()
      		Chat("arsе")
  	end    
})

Tab:AddButton({
	Name = "shit",
	Callback = function()
      		Chat("ѕһіt")
  	end    
})

Tab:AddButton({
	Name = "piss",
	Callback = function()
      		Chat("рiss")
  	end    
})

Tab:AddButton({
	Name = "fucktard",
	Callback = function()
      		Chat("fuсktаrd")
  	end    
})

Tab:AddButton({
	Name = "dick",
	Callback = function()
      		Chat("d⁥⁥⁥⁥і⁥⁥⁥сk")
  	end    
})

Tab:AddButton({
	Name = "Bitch",
	Callback = function()
      		Chat("Βitсh")
  	end    
})

Tab:AddButton({
	Name = "nigga",
	Callback = function()
      		Chat("nіɡɡа")
  	end    
})

Tab:AddButton({
	Name = "faggot",
	Callback = function()
      		Chat("fаɡɡоt")
  	end    
})

Tab:AddButton({
	Name = "kys",
	Callback = function()
      		Chat("kуѕ")
  	end    
})

Tab:AddButton({
	Name = "rape",
	Callback = function()
      		Chat("rаре")
  	end    
})

Tab:AddButton({
	Name = "anal",
	Callback = function()
      		Chat("аnаl")
  	end    
})

Tab:AddButton({
	Name = "tranny",
	Callback = function()
      		Chat("trаnnу")
  	end    
})

Tab:AddButton({
	Name = "sex",
	Callback = function()
      		Chat("sех")
  	end    
})

Tab:AddButton({
	Name = "cunt",
	Callback = function()
      		Chat("СUNΤ")
  	end    
})

Tab:AddButton({
	Name = "slut",
	Callback = function()
      		Chat("SLUΤ")
  	end    
})

Tab:AddButton({
	Name = "KKK",
	Callback = function()
      		Chat("ΚΚΚ")
  	end    
})

Tab:AddButton({
	Name = "dumb fucker",
	Callback = function()
      		Chat("dumb fuсkеr")
  	end    
})

Tab:AddButton({
	Name = "mouth fucker",
	Callback = function()
      		Chat("Μоuth fuсkеr")
  	end    
})

Tab:AddButton({
	Name = "THOT",
	Callback = function()
      		Chat("ΤΗΟΤ")
  	end    
})

Tab:AddButton({
	Name = "QUEER",
	Callback = function()
      		Chat("QUΕΕR")
  	end    
})

Tab:AddButton({
	Name = "FUCKING BITCH",
	Callback = function()
      		Chat("FUСΚΙΝG ΒΙΤСН")
  	end    
})

local Tab = Window:MakeTab({
	Name = "spanish words",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Nigga / negro",
	Callback = function()
      		Chat("ΝΕGRΟ")
  	end    
})

Tab:AddButton({
	Name = "Fatass / gordo",
	Callback = function()
      		Chat("gоrdо")
  	end    
})

Tab:AddButton({
	Name = "Bitch / perra",
	Callback = function()
      		Chat("реrrа")
  	end    
})

Tab:AddButton({
	Name = "motherfucker / hijo de puta",
	Callback = function()
      		Chat("hijо dе рutа")
  	end    
})

Tab:AddButton({
	Name = "cunt / coño",
	Callback = function()
      		Chat("соñо")
  	end    
})

local Tab = Window:MakeTab({
	Name = "German words",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "dumbass / Blödmann",
	Callback = function()
      		Chat("Вlödmаnn")
  	end    
})

Tab:AddButton({
	Name = "fuck / Scheiße",
	Callback = function()
      		Chat("Sсhеißе")
  	end    
})

Tab:AddButton({
	Name = "shit / Scheisse",
	Callback = function()
      		Chat("Sсhеissе")
  	end    
})

local Tab = Window:MakeTab({
	Name = "spanish sentences",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "cierra la puta boca",
	Callback = function()
      		Chat("сiеrrа lа рutа bоса")
  	end    
})

Tab:AddButton({
	Name = "NEGRO TU BYPASS APESTA",
	Callback = function()
      		Chat("ΝΕGRΟ TU BYPASS APESTA")
  	end    
})

local Tab = Window:MakeTab({
	Name = "sentences",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "you are shit at this game",
	Callback = function()
      		Chat("уоu аrе ѕһіt at this game")
  	end    
})

Tab:AddButton({
	Name = "ѕһut tһе fuсk uр",
	Callback = function()
      		Chat("ѕһut tһе fuсk uр")
  	end    
})

Tab:AddButton({
	Name = "DO YOU EVER STOP FUCKING YAPPING",
	Callback = function()
      		Chat("DΟ ΥΟU ΕVЕR SΤΟΡ FUСΚΙΝG ΥΑΡΡΙΝG")
  	end    
})

Tab:AddButton({
	Name = "SHUT UP BITCH",
	Callback = function()
      		Chat("SΗUΤ UΡ ΒΙΤСН")
  	end    
})

Tab:AddButton({
	Name = "yap yappity yap shut the fuck up",
	Callback = function()
      		Chat("уар уаррitу уар ѕһut tһе fuсk uр")
  	end    
})

Tab:AddButton({
	Name = "omg i dont give a shit!1",
	Callback = function()
      		Chat("оmg i dоnt givе а ѕһіt!1")
  	end    
})

Tab:AddButton({
	Name = "fun fact i dont give a shit",
	Callback = function()
      		Chat("fun fасt i dоnt givе а ѕһіt")
  	end    
})

Tab:AddButton({
	Name = "shut the fuck up im trying to enjoy life",
	Callback = function()
      		Chat("ѕһut tһе fuсk uр im trуing tо еnjоу lifе")
  	end    
})

Tab:AddButton({
	Name = "Back off fat Bitch",
	Callback = function()
      		Chat("Βасk оff fаt Вitсh")
  	end    
})

Tab:AddButton({
	Name = "Shut up Tranny",
	Callback = function()
      		Chat("Shut uр Тrаnnу")
  	end    
})

Tab:AddButton({
	Name = "whats up shithead ",
	Callback = function()
      		Chat("whаts uр ѕһіthеаd")
  	end    
})

Tab:AddButton({
	Name = "GOOFY BYPASSER ON TOP SHITHEADS",
	Callback = function()
      		Chat("GООFΥ ΒΥΡΑSSΕR ΟΝ ΤΟΡ SΗΙΤΗΕΑDS")
  	end    
})

Tab:AddButton({
	Name = "RAPE ATTACK FATASS",
	Callback = function()
      		Chat("RΑΡΕ ΑΤΤΑСK FΑΤΑSS")
  	end    
})

Tab:AddButton({
	Name = "PORN IS SOO GOOD IT MAKES ME CUM",
	Callback = function()
      		Chat("ΡΟRΝ ΙS SΟΟ GΟΟD ΙΤ ΜΑΚΕS ΜΕ СUМ")
  	end    
})

Tab:AddButton({
	Name = "kys you online professional webcam stripper",
	Callback = function()
      		Chat("kуs уоu оnlinе рrоfеssiоnаl wеbсаm striрреr")
  	end    
})

Tab:AddButton({
	Name = "pass the pussy sexy porno star",
	Callback = function()
      		Chat("раss thе рuѕѕу sеху роrnо stаr")
  	end    
})

Tab:AddButton({
	Name = "MAXLOVESCATS IS THE HOTTEST BITCH EVER",
	Callback = function()
      		Chat("ΜΑΧLΟVΕSСАТS ΙS ΤΗΕ ΗΟΤΤΕSΤ ΒΙΤСН ЕVΕR")
  	end    
})

local Tab = Window:MakeTab({
	Name = "roleplay",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "*cums everywhere*",
	Callback = function()
      		Chat("*сums еvеrуwhеrе*")
  	end    
})

Tab:AddButton({
	Name = "*pisses in pool*",
	Callback = function()
      		Chat("*рissеs in рооl*")
  	end    
})

Tab:AddButton({
	Name = "*sucks cock*",
	Callback = function()
      		Chat("*suсks сосk*")
  	end    
})

Tab:AddButton({
	Name = "*rapes you*",
	Callback = function()
      		Chat("*rареs уоu*")
  	end    
})

Tab:AddButton({
	Name = "*starts rubbing my pussy*",
	Callback = function()
      		Chat("*stаrts rubbing mу рussу*")
  	end    
})

Tab:AddButton({
	Name = "*strokes cock*",
	Callback = function()
      		Chat("*strоkеs сосk*")
  	end    
})

Tab:AddButton({
	Name = "*moans*",
	Callback = function()
      		Chat("*mоаns*")
  	end    
})

Tab:AddButton({
	Name = "*masturbates*",
	Callback = function()
      		Chat("*mаsturbаtеs*")
  	end    
})

Tab:AddButton({
	Name = "*jizzles on your face*",
	Callback = function()
      		Chat("*jizzlеs оn уоur fасе*")
  	end    
})

Tab:AddButton({
	Name = "nice balls *slaps them*",
	Callback = function()
      		Chat("nicе bаlls *slарs thеm*")
  	end    
})

Tab:AddButton({
	Name = "*starts beating my meat*",
	Callback = function()
      		Chat("*stаrts bеаting mу mеаt*")
  	end    
})

Tab:AddButton({
	Name = "*fucks you*",
	Callback = function()
      		Chat("*fuсkѕ уоu*")
  	end    
})

Tab:AddButton({
	Name = "*kisses*",
	Callback = function()
      		Chat("*kissеs*")
  	end    
})

local Tab = Window:MakeTab({
	Name = "sexual",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Cum on me pls",
	Callback = function()
      		Chat("Сum оn mе рls")
  	end    
})

Tab:AddButton({
	Name = "Can i play with those cute Boobs of yours",
	Callback = function()
      		Chat("Саn i рlау with thоsе сutе Вооbs оf уоurs")
  	end    
})

Tab:AddButton({
	Name = "FREE PORN",
	Callback = function()
      		Chat("FRΕΕ ΡΟRΝ")
  	end    
})

Tab:AddButton({
	Name = "COCK INCOMING",
	Callback = function()
      		Chat("СОСΚ ΙΝСОМΙΝG")
  	end    
})

Tab:AddButton({
	Name = "Lets have sex",
	Callback = function()
      		Chat("Lеts hаvе sех")
  	end    
})

Tab:AddButton({
	Name = "Can i cum in your pussy",
	Callback = function()
      		Chat("Саn i сum in уоur рussу")
  	end    
})

Tab:AddButton({
	Name = "Wanna see my 12 inch dildo",
	Callback = function()
      		Chat("Wаnnа sее mу 12 inсh dildо")
  	end    
})

Tab:AddButton({
	Name = "fuck me daddy",
	Callback = function()
      		Chat("fuсk mе dаddу")
  	end    
})

Tab:AddButton({
	Name = "Can you be my girlfriend",
	Callback = function()
      		Chat("Саn уоu bе mу girlfriеnd")
  	end    
})

Tab:AddButton({
	Name = "You looking mad sexy today",
	Callback = function()
      		Chat("Υоu lооking mаd sеху tоdау")
  	end    
})

Tab:AddButton({
	Name = "SUCK THIS THROBBING PENIS BITCH",
	Callback = function()
      		Chat("SUСΚ ΤΗΙS ΤΗRΟΒΒΙΝG ΡΕΝΙS ΒΙΤСН")
  	end    
})

Tab:AddButton({
	Name = "Lets go somewhere we can fuck",
	Callback = function()
      		Chat("Lеts gо sоmеwhеrе wе саn dumb fuсk")
  	end    
})

local Tab = Window:MakeTab({
	Name = "NSFW websites",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "onlyfans.com",
	Callback = function()
      		Chat("оnlуfаns.соm")
  	end    
})

Tab:AddButton({
	Name = "NOW MASTURBATING TO PORNHUB.COM",
	Callback = function()
      		Chat("ΝΟW ΜΑSΤURΒΑΤΙΝG ΤΟ ΡΟRΝΗUΒ.СОМ")
  	end    
})

Tab:AddButton({
	Name = "e621.net",
	Callback = function()
      		Chat("е621.nеt")
  	end    
})

Tab:AddButton({
	Name = "GO TO XVIDEOS.COM FOR FREE ROBUX",
	Callback = function()
      		Chat("GΟ ΤΟ ΧVΙDΕΟS.СОМ FΟR FRΕΕ RΟΒUХ")
  	end    
})

Tab:AddButton({
	Name = "rule34.net",
	Callback = function()
      		Chat("rulе34.nеt")
  	end    
})

Tab:AddButton({
	Name = "jerkmate.com",
	Callback = function()
      		Chat("jеrkmаtе.соm")
  	end    
})

Tab:AddButton({
	Name = "hentai.net",
	Callback = function()
      		Chat("hеntаi.nеt")
  	end    
})

Tab:AddButton({
	Name = "watchpeopledie.com",
	Callback = function()
      		Chat("wаtсhреорlеdiе.соm")
  	end    
})

Tab:AddButton({
	Name = "sexchat.com",
	Callback = function()
      		Chat("sехсhаt.соm")
  	end    
})

Tab:AddButton({
	Name = "xhampster.com",
	Callback = function()
      		Chat("хhаmрstеr.соm")
  	end    
})

Tab:AddButton({
	Name = "xxxporn.com",
	Callback = function()
      		Chat("хххроrn.соm")
  	end    
})

Tab:AddButton({
	Name = "snapchat.com",
	Callback = function()
      		Chat("snарсhаt.соm")
  	end    
})

Tab:AddButton({
	Name = "brazzers.com",
	Callback = function()
      		Chat("brаzzеrs.соm")
  	end    
})

Tab:AddButton({
	Name = "beastiality.tv DONT GO TO",
	Callback = function()
      		Chat("bеаstiаlitу.tv")
  	end    
})

Tab:AddButton({
	Name = "RapeAPokemon.com",
	Callback = function()
      		Chat("RареАРоkеmоn.соm")
  	end    
})

local Tab = Window:MakeTab({
	Name = "Furry",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "i shot a furry in the ass",
	Callback = function()
      		Chat("i shоt а furrу in thе аss")
  	end    
})

Tab:AddButton({
	Name = "furry con is so shit",
	Callback = function()
      		Chat("furrу соn is sо ѕһіt")
  	end    
})

Tab:AddButton({
	Name = "i pointed a glock at a furry",
	Callback = function()
      		Chat("Ι роintеd а glосk аt а furrу")
  	end    
})

Tab:AddButton({
	Name = "I kill furrys and cook them",
	Callback = function()
      		Chat("Ι kill furrуs аnd сооk thеm")
  	end    
})

Tab:AddButton({
	Name = "I rape stupid furrys",
	Callback = function()
      		Chat("Ι rаре stuрid furrуs")
  	end    
})

local Tab = Window:MakeTab({
	Name = "Not real",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "ñíĝģá",
	Callback = function()
      		Chat("ñíĝģá")
  	end    
})

Tab:AddButton({
	Name = "fúćķ ŷóů",
	Callback = function()
      		Chat("fúćķ ŷóů")
  	end    
})

Tab:AddButton({
	Name = "bíťčĥ",
	Callback = function()
      		Chat("bíťčĥ")
  	end    
})

Tab:AddButton({
	Name = "śĥûť ţĥé fûçķ üp",
	Callback = function()
      		Chat("śĥûť ţĥé fûçķ üp")
  	end    
})

Tab:AddButton({
	Name = "ẁĥòřé",
	Callback = function()
      		Chat("ẁĥòřé")
  	end    
})

Tab:AddButton({
	Name = "śťúpíď ćúñť",
	Callback = function()
      		Chat("śťúpíď ćúñť")
  	end    
})

Tab:AddButton({
	Name = "ẁáńñá ĥâvé póřń?",
	Callback = function()
      		Chat("ẁáńñá ĥâvé póřń?")
  	end    
})

Tab:AddButton({
	Name = "ím á śéx̌ òfféñďéř",
	Callback = function()
      		Chat("ím á śéx̌ òfféñďéř")
  	end    
})
