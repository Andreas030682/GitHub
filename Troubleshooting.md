Make sure to read the [[installation manual|Installation#Prerequisites]] first, it covers the most basic prerequisites that are absolutely mandatory. For every entry here, make sure to check the previous ones first to make sure you didn't miss anything.

## The video doesn't load / Screen stays back
This is usually a codec issue and can be fixed quite easily. ScriptPlayer uses DirectShow filters to render videos, so to test if this really is the issue try opening the file with Windows Media Player. If the result is the same, you have found the problem and simply have to install the right codec(s). One of the following should work in most cases:
* [Windows Media Player Feature Pack](https://www.microsoft.com/en-us/software-download/mediafeaturepack)
* [LAV-Filters](https://github.com/Nevcairiel/LAVFilters/releases)
* [K-Lite Codec Pack](https://www.codecguide.com/download_kl.htm) (includes LAV and madVR)
* [CCCP](http://www.cccp-project.net/) (includes LAV and custom MPC)

If that still doesn't solve the issue, maybe [this support page from VRP](https://support.virtualrealporn.com/hc/en-us/articles/203037781-The-screen-stays-black-and-I-can-t-see-the-video) can help you.

## I can't connect to my toy
Make sure you have at least the Windows version recommented in [[the installation manual|Installation#Prerequisites]], check if your bluetooth dongle supports BT 4.0 Low Energy (BLE) and is [[not listed|Devices#ble-dongle-chipsets]] under the chipsets known to cause issues.

## I can connect my toy but it doesn't move
Make sure you have the latest version of ScriptPlayer, Buttplug (for devices other than the Fleshlight Launch) and your device's firmware (Launch can be updated with the FeelConnect app). Select "Source" - "Slow" in the settings menu to make sure it's not just a faulty script.

## Manual movement works, but I can't playback scripts
Make sure the script loaded successfully by enabling "Show Heatmap" in the [[settings panel|Settings]]. If the progressbar at the bottom stays black, the script was not loaded correctly.

## It works for a while and suddenly stops
Make sure your BLE dongle is not overheating and plugged into the correct type of port (e.g. if it's USB 2.0 don't use a 3.0 even though common sense says it should work).

## Movement is too fast or erratic
Try adjusting the settings for ``Speed``, ``Range`` and ``Min Command Delay`` in the [[settings panel|Settings]]. By default they are pushing the limit and result in faster movement that other applications. The defaults of other applications are approximately:   
``Speed``: 20 - 80  
``Range``: 5 - 95