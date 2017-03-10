# csgo-lense
Overlay-Screen for Counter Strike: Global Offensive that displays a fish-eye lens as your cross-hair.

Pre-Requisite:
  CSGO must be running in Fullscreen Windowed Display Mode on primary monitor.
  Check setting go to "HELP & OPTIONS -> VIDEO SETTINGS -> Display Mode"
  Best if you limit your frames under 120.
    open console type: fps_max 120
  Turn off your standard crosshair
   open console type: crosshair 0
   
How it works:
  Using WINAPI to create a window that is inactive and your mouse passes through.
  The program then screen captures the csgo window does the barrel effect and displays.
  
CAUTION:
  If you have a window open over csgo you will not see it but your mouse will activate it.
  Best to ALT+TAB to activate CSGO to confirm your in that window.
  Zoom can be closed by right clicking taskbar icon or Window+TAB.

Please update me with your experiences. I would like to develope this further, add options, suggestions welcome!
