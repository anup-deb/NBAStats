# NBA Stats
A website containing all relevant NBA stats for quick viewing. Uses the nba_py library, Flask, Python, and HTML/CSS.

## Features
* Records important NBA stats since as early as the 1960's
* Links to relevant NBA reddit threads and YouTube videos
* Shows live scores with player, and team stats, quarter-by-quarter analysis of both teams, coaches, etc.
* Has search feature to find players or teams easily
* Shows player-specific information for any past or present NBA players in all their regular season or playoff appearances
* Displays NBA standings in both conferences at any date.
* Includes team logos, player images, game-unrelated facts such as College attended, Age, Hometown, Draft pick, Years in league, etc.
* Box scores include information such as FG, FG%, MINS, REB, PTS, OREB, DREB, 3PT, 3PT%, FT, FT%, STL, BLK, TOV, PF, +/-
* Allows for tables to be sorted by any statistical category
* Stores stats for individual games

## How to Use
Use pip to install:
1. ```Flask```
2. ```requests```
3. ```nba_py```
4. ```pytz```
5. ```praw```
6. ```beautifulsoup4```
7. ```google-api-python-client```
8. ```Install python-dateutil```

Next, create a YouTube Data v3 API Credentials Key at: https://console.developers.google.com/apis/dashboard
Create a Reddit Client ID and Client Secret Key at: https://www.reddit.com/prefs/apps
Put the YouTube and Reddit API keys inside __init__.py.

Create YouTube Data v3 API Credentials Key at:
[https://console.developers.google.com/apis/dashboard](https://console.developers.google.com/apis/dashboard)

Create Reddit Client ID and Client Secret Key at:
[https://www.reddit.com/prefs/apps](https://www.reddit.com/prefs/apps)

Put the YouTube and Reddit API keys inside `__init__.py`

```
# YouTube Developer Key
DEVELOPER_KEY = ""
YOUTUBE_API_SERVICE_NAME = "youtube"
YOUTUBE_API_VERSION = "v3"

# Reddit API Key
reddit = praw.Reddit(client_id="",
                     client_secret="",
                     user_agent="anything")
```

To run the server locally on port 8080, type ```python __init__.py``` in the command line.

## Screenshots
![Screenshot](https://github.com/anup-deb/NBAStats/blob/master/images/sc1.PNG)
![Screenshot](https://github.com/anup-deb/NBAStats/blob/master/images/sc2.PNG)
![Screenshot](https://github.com/anup-deb/NBAStats/blob/master/images/sc3.PNG)
![Screenshot](https://github.com/anup-deb/NBAStats/blob/master/images/sc4.PNG)
