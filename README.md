Owner = game:GetService("Players").LocalPlayer
game:GetService("StarterGui"):SetCore("SendNotification", {
Title = "Loading...";
Text  = "Joining Server Please Wait!";})
local ts = game:GetService("TeleportService")
local p = game:GetService("Players").LocalPlayer
ts:Teleport(1456080999, p)
