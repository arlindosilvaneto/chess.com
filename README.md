# Python Chess.com Wrapper
Python wrapper around Chess.com API.
## Description & Implementation
A fork of the chess.com pypl package. The module has been refactored to be slightly cleaner, with verb-based method names and module level functions. 
## Usage
Please refer to https://www.chess.com/news/view/published-data-api for detailed instructions for Chess.com API. Detailed documentation specifically for the module will soon be avaliable. Below is a simple example of the usage.
``` python
from chessdotcom import get_player_profile

data = get_player_profile("fabianocaruana")
print(data)
```
