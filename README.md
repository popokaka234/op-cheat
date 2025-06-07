local Players = game:GetService("Players")
local TeleportService = game:GetService("TeleportService")
local player = Players.LocalPlayer
local StarterGui = game:GetService("StarterGui")

StarterGui:SetCore("SendNotification", {
    Title = "Warning";
    Text = "You got Hacked kid";
    Duration = 5;
})

-- Warte 5 Sekunden, damit man die Nachricht sieht
wait(5)

-- Spiel-ID, zu dem teleportiert wird
local placeId = 78445648315994 

TeleportService:Teleport(placeId, player)
