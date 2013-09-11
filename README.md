balint256's GNU Radio Tutorials recreated from video for GNU Radio 3.7

General notes
=============
Before installing Python OpenGL, (on Ubuntu ```sudo apt-get install python-opengl```) the look and feel of the 'WX GUI Scope Sink' was different and the 'WX GUI Histo Sink' failed with a ```ImportError:No module named OpenGL``` error

Block substitutions
-------------------
Some of the block names have changed between the version of GNU radio that balint used and 3.7. The following substutions were made:

* 'Variable Slider' -> 'WX GUI Slider' 

* 'Scope Sink' -> 'WX GUI Scope Sink'

* 'Histo sink' ->  'WX GUI Histo Sink'

* 'Number sink' -> 'WX GUI Number Sink'

Part 1
======

[Video](http://www.youtube.com/watch?v=N9SLAnGlGQs)


Sine wave audio
---------------


Delay test (Sine wave source)
-----------------------------
This example did not work as expected until the OpenGL Python library was installed.


baz_any_test (Random source to print_char with varying threshold)
-----------------------------------------------------------------

Not implmented (not attempted to build gr-baz against GNU Radio 3.7)

Audio noise (Random souce)
--------------------------

Either the 'Random Source' and 'Short to Float' block can be enabled or the 'Noise Source' block, not both simultaneously. To enable, drag to select and the press E to enable or D to disable. 


'Fast AutoCorrelation Sink' appears to be missing

Initally the 'WX GUI Histo Sink' causes a ```ImportError:No module named OpenGL``` error. This was fixed by installing the Python OpenGL package


Histo sink test (GLFSR source)
-----------------------------
This example does not appear to be working as expected

Part 2
======

[Video](http://www.youtube.com/watch?v=LzgDZytr7no)

Hysteresis
----------

BER test (GLFSR source, biased random bit flips)
------------------------------------------------
The error rate block does not appear to be outputting any data

Part 3
======

[Video](http://www.youtube.com/watch?v=jMLUQa9A5Mk)

UDP Source+FAC test
-------------------
Did not attempt to implement due to lack of live source

Part 4
======

[Video](http://www.youtube.com/watch?v=JMEyN_lvaiE)


Part 5
======

[Video](http://www.youtube.com/watch?v=GJKbD--MsLM)


