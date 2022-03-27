local HWID = {
    "bb38624d-927f-45bc-a64a-081e1d82cbf1",
    "21c552fb-8f0a-479a-8a62-9166af19fdc6",
    "bb38624d-927f-45bc-a64a-081e1d82cbf1"
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
