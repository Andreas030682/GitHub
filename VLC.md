You can connect ScriptPlayer to [VLC](https://www.videolan.org/) via the menu (Playback - VLC). VLC will handle playback of the video and Scriptplayer automatically loads corresponding scripts to the video. Unfortunately the timestamps provided via the webinterface are not very precice, so you might need to adjust the script delay for proper synchronization. 

## Settings in VLC

To be able to connect ScriptPlayer to VLC, you need to enable the web interface and set a password. Open the preferences dialog (Tools - Preferences or Ctrl+P) and select Show settings - All in the bottom left corner.

![VLC Setting 1](https://raw.githubusercontent.com/FredTungsten/ScriptPlayer/master/Assets/VlcWebInterface1.png)

Under Interfaces - Main Interfaces activate ``Web``.

![VLC Setting 2](https://raw.githubusercontent.com/FredTungsten/ScriptPlayer/master/Assets/VlcWebInterface2.png)

Under Interfaces - Main Interfaces - Lua set a password for ``Lua HTTP``.

> You need to restart VLC for these changes to take effect!

## Settings in ScriptPlayer

When you try to connect to VLC for the first time (via Playback - VLC) you will see a promt that asks you for connection settings like the IP, port and password for the VLC web interface. (default ``127.0.0.1:8080``)

![VLC Connection Settings 1](https://raw.githubusercontent.com/FredTungsten/ScriptPlayer/master/Assets/VlcConnectionSettings1.png)

You can change these settings later in the settings dialog.

![VLC Connection Settings 2](https://raw.githubusercontent.com/FredTungsten/ScriptPlayer/master/Assets/VlcConnectionSettings2.png)
