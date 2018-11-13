## Instructions.

There are 9 svg files with the shape of the 26 ribs that compose the frame. Use a CAM software to get the gcode files to cut the shapes (I used Easel). 

The shapes have 3 colors. The blue shapes are for "profiles cuts", the red shapes are "follow path cuts" and the green shapes are for "pocket cuts". Profile and follow paths must cut through all the weed (I used 5 tabs on each shape to keep them fixed).

Special care must be taken in files **slices_set_7_(1_2_19).svg** and **slices_set_9_(25_26).svg**, because they keep ribs number 1 and 26 (the left and right most ribs). In those ribs the **red shapes and green shapes (pockets) must not be cut through** (I cut about 1.2cm).
