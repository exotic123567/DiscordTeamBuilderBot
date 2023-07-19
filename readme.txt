You'll need to install discord.py on your environment along with python for this to work.

Then you'll need to create a discord bot in discord developers page. There you'll need to setup the bot accordingly and get the bot token.
Use that Bot token wherever it's needed in the python code.

Input your command in the following format : !create_teams {Threshold} "{list of players you want to make 2 balanced teams with}

The Threshold value will be an integer which indicates how much of imbalance you can make do with. 
A low threshold like 1 or 2 means you want your teams to almost perfectly balanced. A higher threshold like 6 or 7 means you can expect
your teams to be a little bit more disbalanced.

An example command might be : !create_teams 2 "Bunty Chotai Monty Didin Yaan RounakDa".
