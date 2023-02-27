# PythonRealWorld

This is a program which selects appropriate landing sites on Mars for spacecrafts.
Landing spacecrafts on mars is challenging and costly, you would not want to destroy billions invested into a spacecraft probe upon landing.
This program uses satellite images of Mars to initially select the preffered location of landing, and uses appropriate code and algorithms to 
process and refine this images to further on select or show which parts of the images are potential landing sites according to the requirements
given.
Note that Mars is quite dry and rocky with numerous craters so this is already a challenge, but using the right parameters and constants the code 
draws rectangular shapes on the satellite image to extract statistics and on elevation and surface roughness.
A grayscale image of a MOLA map is used my the Marsproject.py to select landing site rectangles and shaded color map to post them, and elevation is much easier to represent in grayscale image than RGB image(color image).
The colored image is then use to show the processed results.
A simulation for selecting Martian landing sites for NASA.
