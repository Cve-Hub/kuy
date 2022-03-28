local HWID = {
    "211929af-1c97-4891-8e46-d77a65398653",
    "bb38624d-927f-45bc-a64a-081e1d82cbf1",
    "1a2a1be4-c714-4d65-8091-510458d331ea"
}
local Old = game:GetService("RbxAnalyticsService"):GetClientId()
if game:GetService("RbxAnalyticsService"):GetClientId() ~= Old then 
    while true do end
end
if HWID[table.find(HWID, Old)] == Old then
    loadstring(game:HttpGet"https://raw.githubusercontent.com/Cve-Hub/LnHub/main/README.md")()
else
    setclipboard("HWID : "..tostring(Old))
    game.Players.LocalPlayer:Kick("Wrong Hwid Dm Admin!")
    wait(.5)

game:Shutdown()
end
