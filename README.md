# Flash-Background-by-wxPython

As we all know about wxPython, it's a simple lab for python GUI. But in recent years, clients (of course including bosses) order more and more beautiful GUI for their applications. I got a same situations like just mentioned, so I represented some individual solutions on beautify my application by wxPython.

  This solution was enlightened by another idea for showing a picture on the background of a wxPython Frame. I would like to have a automatic flashing background with several pictures. I used the priciple of flash or movies to show up a flashing background. That means I will flash my background in a short time so that the client will think that is moving. 
  
  That is a simple way to improve the feeling of your application while some performance losses are caused. This solution on my computer (i7-6560U) will generate 5% CPU utilization which only be flashed every 0.083 seconds (12 photoes every second). Because of the performance losses, I have to transform the flashing background to a frozen background while the other threadings startuped.
  
 Here is the enviroument of my computer
 1. Python 2.X
 2. wxPython 3.0
