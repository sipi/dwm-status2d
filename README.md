dwm-status2d
============

patch for DWM that allows colors and draw rectangle in the DWM status bar

usage
=====

draw rectangle
--------------
Add ^rx,y,w,h^ in the status text.

change color
------------
Add ^c#FF0000^ in the status text.

forward the x position for drawing
----------------------------------
Add ^f11^ in the status text.

Example
=======

xsetroot -name "dwmstatus ^c#FF0000^ in red with red rectangle ^r0,0,10,10^^f10^^c#FFFFFF^ and white text"

See my [dwmstatus](https://github.com/sipi/dwmstatus) repository for a compatible statusbar program (written in C).
