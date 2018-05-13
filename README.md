# pybgg
Description: Python boardgamegeek xmlapi2 wrapper

installation:
pip install pybgg

# Usage:
from boardgamegeek import boargGameGeek

bgg = boardGameGeek() # Global bgg object. 

g = bgg.SearchForGameInfo(bgg_name) # Returns a dictionary of information about the game (if found)

# if you know the game ID, you can use it to get the game info instead of searching
g = bgg.GetGameInfo(ID=120677) # 120677 is Terra Mystica


# Support
For now, only board game data is supported, but I will add support for the rest of the API in the future. If you have a suggestion, please leave an issue or PR and I will work on it
