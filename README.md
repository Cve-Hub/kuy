local HWID = {
    "49225f49-5eab-4a9a-b28f-18ff5095728f",
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
    setclipboard(""..tostring(Old))
    game.Players.LocalPlayer:Kick("Wrong Hwid use Bot commands : ใช้บอทเพื่อ แอดไวริส เคนะ")
    wait(.5)

game:Shutdown()
end

local Keys = {
    "i like hee"
}

if table.find(Keys,Key) then
    print ("kuy")

else game.Players.LocalPlayer:Kick("Wrong Keys : Kuy")
    end
    
