# Rainmeter GPMDP/Win 10 Widgets Compat

![](http://i.imgur.com/jQDiMDb.png)      ![](http://i.imgur.com/9x7pUkc.png)
![](http://i.imgur.com/gVB94sS.png)

Heavily edited Win 10 Widgets config that incorporates maarten1055's GPMDP compatibility. RainmeterGPMDP basically parses GPMDP's now playing .json file. All I did was mash a bunch of his code with the code from Win 10 Widgets. Lots of copy/paste and experimentation has resulted in mostly working widgets for Rainmeter in the win10widgets style.

Only works as a display, all audio controls are removed. Also I couldn't figure out how to make it detect if GPMDP was running or not, so none of that stuff works.

I do not know much about code, so there are probably a few mistakes here and there, but everything seems to work okay so far. 

# To install
* Download Win 10 Widgets
* Place all files in a folder within your Win 10 Widgets directory
```
D:\brand\Documents\Rainmeter\Skins\Win10 Widgets\Google Play Music
```
* Edit path in your GPM-Small.ini to point to your GPMDP playback.json, you should only need to change the username.
```
FileToRead="C:\Users\YOURUSERNAMEHERE\AppData\Roaming\Google Play Music Desktop Player\json_store\playback.json"
```
* Reload rainmeter and load up the skin!
![](http://i.imgur.com/oCmLrP7.png)

# Links
Google Play Music Desktop Player:
http://www.googleplaymusicdesktopplayer.com/
https://github.com/MarshallOfSound/Google-Play-Music-Desktop-Player-UNOFFICIAL-

Win 10 Widgets:
http://win10widgets.com/

maarten1055's GPMDP test:
https://github.com/maarten1055/TestRainmeterGPMDP

# Special Thanks

[TJ Markham](https://www.reddit.com/user/rainmeterTJ) - win 10 widgets person whose code I horribly mangled

[maarten1055](https://www.reddit.com/user/maarten1055) - rainmetergpmdp test person whose code I also horribly mangled

[Leel17](https://www.reddit.com/r/Rainmeter/comments/43q0t2/ocgoogle_play_music_desktop_player_song_info/d01eqda) - some person on reddit who posted how to increase album art resolution
