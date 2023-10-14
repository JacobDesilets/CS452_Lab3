Lab 3
Jacob DeRosa and Jacob Desilets

To compose the three different transformations, we first apply the scaling, then rotation, then lastly the translation. 
We chose to do these transformations in small increments so the polyhedron doesn't change too fast. Rotations are done in 0.01 rad 
in all 3 axis directions. Translations are done in increments of 0.05 in both the x and y directions. Finally, scaling increases in 
increments of 0.05 in both the x and y directions. 

We create 4x4 matrices for each axis on each of the 3 transformations. On each keystroke, the appropriate transformation parameter
is modified, a new overall transformation matrix is contructed via multiplication, and then that is applied to the points on the 
polyhedron. To rotate the shape in the X, Y, and Z directions, use the X, Y, and Z keys. To translate the shape along the x axis, 
use the A key. To translate the shape along the y axis, use the S key. And for scaling, Q scales it about the X axis, and W scales
it about the Y axis. The direction of the translations reverse at the GUI's boundaries so the polyhedron stays in frame. Also, to 
keep it a reasonable size, the scale factor is limited to a max of 5, and then it will begin to shrink back down to the original size.
