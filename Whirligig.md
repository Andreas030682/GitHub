You can connect ScriptPlayer to Whirligig via the menu (Playback - Whirligig). Whirligig will handle playback of the video and Scriptplayer automatically loads corresponding scripts to the video, as long as the video was loaded after the connection has been established. The timestamps provided via the timestamp sever are fairly precice but you can further need to adjust the script delay for even better synchronization. 

## Settings in Whirligig

To be able to connect ScriptPlayer to Whirligig, you need to enable the timecode server in the settings tab ``General 1``

![Whirligig Settings](https://raw.githubusercontent.com/FredTungsten/ScriptPlayer/master/Assets/WhirligigSettings.png)

## Settings in ScriptPlayer

When you try to connect to Whirligig for the first time (via Playback - Whirligig) you will see a promt that asks you for connection settings like the IP and port for the Whirligig timecode server. (default is ``127.0.0.1:2000``)

You can change these settings later in the settings dialog.

![Whirligig Settings](https://raw.githubusercontent.com/FredTungsten/ScriptPlayer/master/Assets/WhirligigConnectionSettings.png)