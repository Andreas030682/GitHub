Setting are available via the menu or the hidden panel (less settings but instantly effective) on the right side of the main window. Hovering your mouse over it will make it visible. All settings described here are based on the commands for the Fleshlight Launch. They might or might not apply to other connected devices depending on their command-set. The list below contains all settings, some of which may only be accessible via the settings dialog or the hidden panel.

## Buttplug

``Web Socket URL`` The websocket url that will be used to connect to Buttplug.  

``Use Default`` Resets the Web Socket URL to the default value ``ws://localhost:12345/buttplug``.  
WSS (SSL/TLS) connections are not supported.

## Debug

``Show Heat Map`` The progress bar at the bottom of the window will be overlayed with colors indicating the movement speed at the position in the video. Black = no movement, Blue/Green slow movement, Yellow/Red fast movement. 

``Show Script Positions`` Displays the position timeline of the script at the bottom of the video. The time-scale can be adjusted by scrolling up/down with the mouse wheel. 

``Log Markers`` Will add the current timestamp to a <filename>.log text file when right-clicking on the video.

``Test patterns`` Allows you to execute pre-defined patterns.  

## Gaps

``Auto-Skip Gaps`` When the script doesn't contain an action to be executed within the next 10 seconds, the player will automatically jump close to the next action.

``Show Skip Button`` When a section can be skipped (because it contains no actions or only fillers) a skip button will appear on screen.  

``Soft seek`` When gaps are skipped, the video will slowly fade-out instead of instantly skipping (Local playback only).

``Freeze frame`` During soft seek, the last visible video frame will be faded in and out during transistion.

``Fade to black`` Soft seek will simply fade to black and back.

``Fill gaps with movement`` Will fill all gaps in the scripts with movement (details below)  

``Show filled gaps in heat map`` When generating the heat map, filler actions will be displayed like regular ones.  

``Fill gap before first action`` The gap from the start of the video until the first action will also be filled.  

``Fill gap after last action`` The gap from the last action until the end of the video will also be filled.  

``Spacing before/after gap`` Includes a small space at the beginning and end of the gap.

``Filler Intervall`` The intervall at which gap fillers will be inserted into the script (approximately, the generator takes the actual duration, start- and end- position into account).  

## General

``Check for new version on startup`` Will check Github for new releases when ScriptPlayer is started (no popup).

## Input

``Toggle playback when clicking video`` Clicking the video will toggle playback.

``Toggle fullscreen when double-clicking video`` Double-clicking the video will toggle fullscreen.

``Filter double-clicks`` Single click actions will be slightly delayed to check if they will turn into double-clicks. This avoids pause stuttering when double-clicking.

## Notifications

Enables or disables various notifications.

## Paths

When a script or a video is opened, ScriptPlayer is looking for a corresponding file with the same name that will also be loaded. When such a file can not be found in the same directory, the paths that are set here will also be checked (e.g. in case you want to keep all your scripts in a separate folder).

## Playlist

``Remember`` The current playlist will be saved when closing ScriptPlayer and automatically loaded when it is opened again.

``Shuffle`` When pressing the ``Next`` button or finishing a video, a random playlist entry will be loaded instead of the next one.

``Repeat`` Playback will continue with the first playlist item after the last one.

## Range

``Range`` Limits the up/down position for the Fleshlight Launch to the specified values. 0 is completely down, 99 completely up. Subsequent settings can restrict the range further.

``Range Filter``  
* ``F`` Full Range - Movement will only be restricted to ``Range``
* ``T`` Top - Movement will be restricted to the top of the range.
* ``M`` Middle - Movement will be restricted to the middle of the range.
* ``B`` Bottom - Movement will be restricted to the bottom of the range.
* ``S`` Sine Wave - Movement will be restricted to a part of the range that moves in a sinve wave pattern over time.
* ``TB`` Top / Bottom - Movement restriction will alternate between top and bottom in a pre-defined intervall.

``Filter Range`` Determines how much of the full range will be used.

``Beat Conversion Mode`` When the loaded script is a beat-file (*.txt, *.beats) the movements during playback can be sped up by selecting a different mode.
* ``Up/Down`` One beat up, second beat up
* ``Down (fast)`` Fast down/up movement on every beat
* ``Down (centered)`` Down on every beat, up centered between each two beats
* ``Up (fast)`` like Down (fast) but inverted
* ``Up (centered)`` like Down (centered) but inverted

## Source

``Video`` Movements are determined by the script loaded with the video and will pause/skip in sync with the video.  
``None`` No movement  
``Slow`` Slow up/down movement  
``Fast`` Fast up/down movement  
``Random`` Random up/down movement  
``Zig-Zag`` Zig-zag up/down movement 

## Speed

``Speed`` Restricts the speed.  

``Speed Multiplier`` Speeds up every command by the set amount.  

## Timings

``Script delay`` When the script playback is a bit too late or too early, you can fine tune it to your specific setup by adjusting the slider right or left. Positive values will cause the actions to be executed later, negative values earlier.  

``Min Command Delay`` Specifies the minimal timespan between two commands that are sent to devices. 

## VLC

``IP : Port`` IP and port of the VLC web interface.

``Password`` Password for the VLC web interface.

``Use Default`` Resets the endpoint to the default value ``127.0.0.1:8080``.  

 [[Details|VLC]]

## Whirligig

``IP : Port`` IP and port of the Whirligig timecode server.

``Use Default`` Resets the endpoint to the default value ``127.0.0.1:2000``.  

 [[Details|Whirligig]]