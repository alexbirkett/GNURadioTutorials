balint256's GNU Radio Tutorials recreated from video for GNU Radio 3.7

General notes
=============
Before installing Python OpenGL, (on Ubuntu ```sudo apt-get install python-opengl```) the look and feel of the 'WX GUI Scope Sink' was different and the 'WX GUI Histo Sink' failed with a ```ImportError:No module named OpenGL``` error



Part 1
======

[Video](http://www.youtube.com/watch?v=N9SLAnGlGQs)


Sine wave audio
---------------
Used 'WX GUI Slider' block instead of 'Variable Slider' block

Delay test (Sine wave source)
-----------------------------
This example did not work as expected until the OpenGL Python library was installed.

Used 'WX GUI Slider' block instead of 'Variable Slider' block 

Used 'WX GUI Scope Sink' block instead of 'Scope Sink' block

baz_any_test (Random source to print_char with varying threshold)
-----------------------------------------------------------------

Not implmented (not attempted to build gr-baz against GNU Radio 3.7)

Audio noise (Random souce)
--------------------------

Either the 'Random Source' and 'Short to Float' block can be enabled or the 'Noise Source' block, not both simultaneously. To enable, drag to select and the press E to enable or D to disable. 


'Fast AutoCorrelation Sink' appears to be missing

Initally the 'WX GUI Histo Sink' causes a ```ImportError:No module named OpenGL``` error. This was fixed by installing the Python OpenGL package

Used 'WX GUI Histo Sink' instead of 'Histo sink'

Used 'WX GUI Scope Sink' block instead of 'Scope Sink' block

Histo sink test (GLFSR source)
-----------------------------
This example does not appear to be working as expected

Part 2
======

[Video](http://www.youtube.com/watch?v=LzgDZytr7no)

Hysteresis
----------

Used 'WX GUI Slider' block instead of 'Variable Slider' block 

Used 'WX GUI Scope Sink' block instead of 'Scope Sink' block

Used 'WX GUI Histo Sink' instead of 'Histo sink'
