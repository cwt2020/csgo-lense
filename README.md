# csgo-lense
Overlay-Screen for Counter Strike: Global Offensive that displays a fish-eye lens as your cross-hair.

Installation Note: This is built to run on the latest version of Windows 10. If you receive vcruntime140.dll missing error you will need to download [Visual C++ Redistributable for Visual Studio 2015](https://www.microsoft.com/en-us/download/details.aspx?id=48145).

Pre-Requisite:
  CSGO must be running in Fullscreen Windowed Display Mode on primary monitor.
  Check setting go to "HELP & OPTIONS -> VIDEO SETTINGS -> Display Mode

If you have the ability to enable DSR (Dynamic Super Resolution) you will see a much better effect, otherwise because there is no texture sampling there will be some aliasing.

The default settings are to my preference, but I have added some controls. Make sure the app has focus (clicking on the taskbar or alt-tab) then use the following keys:

     -q : increase size - Caution: this will cause performance issues at higher levels.
     -a : decrease size
     -w : increase zoom 
     -s : decrease zoom
     -e : increase inner circle size
     -d : decrease inner circle size
     -r : increase outer circle distortion
     -f : decrease outer circle distortion

Turn off your standard crosshair
    
    open console (~) type: crosshair 0
   
How it works:

  Using WINAPI to create a window that is inactive and your mouse passes through.
  The program then screen captures the csgo window and creates barrel effect. There is no dll injection and little chance that VAC or Overwatch chould detect this as any kind of hack. Remember use at your own risk. 
  

Please update me with your experiences. I would like to develope this further, add options, suggestions welcome!
