# Discord-bot-lua
This commands, I'll help you a lot.
--------------------------------------------------

local discordia = require('discordia')
local client = discordia.Client()
local prefix = "!" ----- คำนำหน้า

client:on('messageCreate', function(message)
    if message.content == prefix.. "Cool" then
        message.channel:send ('Not cool')
    end
end)

client:run("Bot token บอท")
