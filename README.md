# suggestmusic
A simple python script that scrapes music-map.com recommendations for an artist and creates a spotify playlist out of them.


## Requirements
BeautifulSoup4, python-dotenv, Spotipy


## Setup
Clone the repository, install requirements, create a .env file in the same directory with the following content:
```
SPOTIPY_CLIENT_ID=***********
SPOTIPY_CLIENT_SECRET=**********
```
You need to get these API keys from https://developer.spotify.com in order to be able to use Spotipy.


## End result
![Sample result](https://github.com/hur/suggestmusic/blob/master/sample.png)
