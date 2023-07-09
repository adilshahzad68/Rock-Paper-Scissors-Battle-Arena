# Rock-Paper-Scissors-Battle-Arena
Last Man Standing mode

		The game server is run with the following parameter
    			NUM_PLAYERS ( INTEGER > 0 )
    			INITIAL_HP  ( INTEGER >0, DEFAULT 5 )
		Server awaits connections. When NUM_PLAYERS are connected the game starts.
		Players see the list of all players with their statistics.
		Player statistics is
    			PLAYER_HP ( if 0 player is considered dead )
		Players challenge other players. When a player challanges another player, none of them can be challanged by a third player.
		Challange is made with specific choice R|P|S which is unknown to the chalanged player until they reply to the challange with their choice R|P|S.
		Chalange won increments the winner's PLAYTER_HP and decrement's the loser's PLAYER_HP.
		If challange is not answered in 3 seconds it is considered lost.

	A global chat is featured.
