local HWID = {
    "211929af-1c97-4891-8e46-d77a65398653",
    "21c552fb-8f0a-479a-8a62-9166af19fdc6",
    "1a2a1be4-c714-4d65-8091-510458d331ea"
}
local Old = game:GetService("RbxAnalyticsService"):GetClientId()
if game:GetService("RbxAnalyticsService"):GetClientId() ~= Old then 
    while true do end
end
if HWID[table.find(HWID, Old)] == Old then
    loadstring(game:HttpGet('https://raw.githubusercontent.com/acsu123/HOHO_H/main/Loading_UI'))()
else
    setclipboard("HWID : "..tostring(Old))
    game.Players.LocalPlayer:Kick("Wrong Hwid Dm Admin!")
    wait(.5)

game:Shutdown()
end
