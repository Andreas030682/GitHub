Samsung VR is a 3D VR video player for Gear VR. You can download this app at the Oculus Store.
You can connect ScriptPlayer to Samsung VR via the menu (Playback – Samsung VR). When you open a video in Samsung VR after connecting with ScriptPlayer, Samsung VR will send the filename of the video back to ScriptPlayer which will automatically load corresponding script. It will search for a script with a corresponding filename within all paths, added to Scriptplayer (Settings – Paths).
The timestamps provided through the the UDP sever are fairly precice but you can further adjust the script delay for even better synchronization.
Important: Make sure your phone is connected with your home WiFi network to be able to connect with Scriptplayer.

Known issue:  If you are using a MediaServer (DLNA) in Samsung VR, Scriptplayer will be out of sync because of the loading/buffering time. Unfortunately, Samsung VR does not send the exact position while loading/buffering a video. The workaround for now is to pause the video when loading/buffering, change the position a litte and then press play when the loading/buffering is done. Important: Make sure you have enough bandwidth to prevent the video for buffering while playing.

Settings in Samsung VR
To be able to connect ScriptPlayer to Samsung VR, you need to enable Presentation mode in the settings window (tap on the three dots in the upper right and tap Settings. You will find these settings on the second page. (This requires Samsung VR version 2.0 or higher.) 
Presentation mode will let Scriptplayer receive UDP commands from Samsung VR, therefore you can use your Gear VR headset (and GearVR controller) as the controller. This will allow you to keep your Gear VR headset on all the time. Scriptplayer will automatically load the corresponding script when you load change to another video (if exists).

Settings in ScriptPlayer
When you try to connect to Samsung VR for the first time (via Playback – Samsung VR) you will see a prompt that asks you for UPD port for the connection. (default port is 5000) You can change these settings later in the settings dialog.