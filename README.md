# csgo-lense
Overlay-Screen for Counter Strike: Global Offensive that displays a fish-eye lens as your cross-hair.

If you have the ability to enable DSR (Dynamic Super Resolution) you will see a much better effect, otherwise because there is no texture sampling there will be some aliasing.

The default settings are to my preference, but I have added some controls. Make sure the app has focus (clicking on the taskbar or atl-tab) then use the following keys:
 -q : increase size - Caution: this will cause performance issues.
 -a : decrease size
 -w : increase zoom
 -s : decrease zoom
 The following change the level of defromation. Think of them as control points on a Bezier curve 
 -e : increase c1
 -d : decrease c1
 -r : increase c2
 -f : decrease c2
 
Pre-Requisite:
  CSGO must be running in Fullscreen Windowed Display Mode on primary monitor.
  Check setting go to "HELP & OPTIONS -> VIDEO SETTINGS -> Display Mode
  
Turn off your standard crosshair
    
    open console (~) type: crosshair 0
   
How it works:

  Using WINAPI to create a window that is inactive and your mouse passes through.
  The program then screen captures the csgo window and creates barrel effect. There is no dll injection and little chance that VAC or Overwatch chould detect this as any kind of hack. Remember use at your own risk. 
  

Please update me with your experiences. I would like to develope this further, add options, suggestions welcome!
