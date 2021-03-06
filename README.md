# Turbulent Dynamics
## Vector Viz SDL:  A utility by Turbulent Dynamics to view a grid of vectors

This utility is built to display vectors from a large grid, (eg 27 billion).  The simulation to create the grid is decomposed across a number of nodes, each with an x, y and z coordinate.  The resulting files are dumped into a directory "dirname/node.x.y.z.vvf"  It would be difficult and pointless to display all the vectors so the output is normally a plane, or slice through the vector space, or a number of each.  The input file example shows the various ways to input the data.

3d picture here. 






## Usage Instructions
* To move around, use the mouse, mouse buttons and cursor keys. Use the cursor keys to center the screen on the point of interest, and then zoom in with left mouse button. Rotate the camera around the point of interest to make the 3D effect more easily perceptible.

* The numpad keys 5,8,4,6 can be used to move camera more steadily. Use the Numpad 4/6 keys to rotate around the point of interest, and Numpad 5/8 to zoom in/out slowly.

* Numpad 0 will move the point of interest back to the center of the grid.

* PrintScreen key will capture the screenshot in a .bmp file.

* w / s  to chance brightness

* a / d to change line length

* 'm' to toggle auto adjust (auto adjust will adjust line length and brightness based on camera distance)

* keys 'o' and 'p' change dot density (the changes are logarithmic). Dot density functions approximately as a quality parameter. However, a low dot density can also provide an interesting look on the input data (even more when line length is increased). Lower dot density requires much lower GPU processing power. Higher dot densities may cause FPS to fall. Also, at some point, there will not be enough GPU memory for additional dots.

* space key will pause the visualization

* ESC key to exit



## Install SDL 2 Instructions
MacOS
Ubuntu Linux

