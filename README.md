# tinyTimer
Very simple Timer app for counting down a set number of minutes/seconds.

TimerApp v1.0 by JammerB (c) 2011

Created in Microsoft Visual Studio Express 2010
Written in VB .NET

The app opens a small Windows form with two separate controls respectively for minutes and seconds input.
Once these are set, the user presses the Start button and the countdown starts. 
There is a Stop button in case there is no need to wait the full amount of time. Another press of the Stop button resets the 'Minutes' and 'Seconds' controls.

Otherwise, when the countdown ends - a dialog box pops up to inform the user about it.

While the timer is counting, users can use their PCs as normal - the app gets hidden behind other programs. When the time reaches zero: a dialog pops up on top of all other windows.

The tricky part is that while the countdown is progressing the app window behaves as normal, when it ends - the window is displayed on top of all other programs (i.e. option 'Always on top' is set to True).

The purpose was to count the time between free donwloads for share sites like rapidshare.com, uploaded.com, etc.
So in example after downloading one file for free - you have to wait 15 minutes before the next download. Dial in 15 minutes in the app and go on doing your business - the app will pop up to inform you as soon as the time has passed. 

This saved me a lot of time back then cause I'll usually get distracted and remember to start the next download like 30-60 minutes later. With this app I was able to keep the losses to a minimum :)
