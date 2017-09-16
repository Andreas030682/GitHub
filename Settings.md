The settings menu is hidden on the right side of the main window. Hovering your mouse over it will make it visible. All settings described here are based on the commands for the Fleshlight Launch. They might or might not apply to other connected devices depending on their command-set.

## Settings

``Script delay`` When the script playback is a bit too late or too early, you can fine tune it to your specific setup by adjusting the slider right or left. Positive values will cause the actions to be executed later, negative values earlier.  

``Range`` Limits the up/down position for the Fleshlight Launch to the specified values. 0 is completely down, 99 completely up. Subsequent settings can restrict the range further.

* ``F`` Full Range - Movement will only be restricted to ``Range``
* ``T`` Top - Movement will be restricted to the top of the range.
* ``M`` Middle - Movement will be restricted to the middle of the range.
* ``B`` Bottom - Movement will be restricted to the bottom of the range.
* ``S`` Sine Wave - Movement will be restricted to a part of the range that moves in a sinve wave pattern over time.
* ``TB`` Top / Bottom - Movement restriction will alternate between top and bottom in a pre-defined intervall.
* ``Speed Multiplier`` Speeds up every command by the set amount.  
* ``Min Command Delay`` Specifies the minimal timespan between two commands that are sent to the Launch. 

The slider below the range settings determines how much of the full range will be used.

``Auto-Skip Gaps`` When the script doesn't contain an action to be executed within the next 10 seconds, the player will automatically jump close to the next action.

``Beat Converrsion Mode`` When the loaded script is a beat-file (*.txt, *.beats) the movements during playback can be sped up by selecting a different mode.
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

## Debug

``Show Heat Map`` The progress bar at the bottom of the window will be overlayed with colors indicating the movement speed at the position in the video. Black = no movement, Blue/Green slow movement, Yellow/Red fast movement.  

``Test patterns`` Allows you to execute pre-defined patterns.  

``Log Markers`` Will add the current timestamp to a <filename>.log text file when right-clicking on the video.
