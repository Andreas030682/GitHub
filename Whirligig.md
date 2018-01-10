[Whirligig](http://www.whirligig.xyz/) is a highly customizable VR video player for Vive, Oculus and openVR headsets. You can get the [free version](http://www.whirligig.xyz/new-page-3/) from the homepage, or support the creator by buying it on [Steam](http://store.steampowered.com/app/451650/), the [Oculus Store](https://www.oculus.com/experiences/rift/1130182873666293/), or [Viveport](https://www.viveport.com/apps/4c5e1cd4-895b-4167-8581-1f7ab94a5491).

You can connect ScriptPlayer to Whirligig via the menu (Playback - Whirligig). When you open a video in Whirligig **after** connecting with ScriptPlayer, Whirligig will send the filename of the video back to ScriptPlayer which will automatically load corresponding scripts. The timestamps provided via the timestamp sever are fairly precice but you can further adjust the script delay for even better synchronization. 

## Settings in Whirligig

To be able to connect ScriptPlayer to Whirligig, you need to enable the timecode server in the settings tab ``General 1``

![Whirligig Settings](https://raw.githubusercontent.com/FredTungsten/ScriptPlayer/master/Assets/WhirligigSettings.png)

## Settings in ScriptPlayer

When you try to connect to Whirligig for the first time (via Playback - Whirligig) you will see a promt that asks you for connection settings like the IP and port for the Whirligig timecode server. (default is ``127.0.0.1:2000``)

You can change these settings later in the settings dialog.

![Whirligig Settings](https://raw.githubusercontent.com/FredTungsten/ScriptPlayer/master/Assets/WhirligigConnectionSettings.png)