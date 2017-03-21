# csgo-lense
Overlay-Screen for Counter Strike: Global Offensive that displays a fish-eye lens as your cross-hair.

Pre-Requisite:
  CSGO must be running in Fullscreen Windowed Display Mode on primary monitor.
  Check setting go to "HELP & OPTIONS -> VIDEO SETTINGS -> Display Mode
  
Turn off your standard crosshair
    
    open console type: crosshair 0
   
How it works:

  Using WINAPI to create a window that is inactive and your mouse passes through.
  The program then screen captures the csgo window does the barrel effect and displays.

Please update me with your experiences. I would like to develope this further, add options, suggestions welcome!
