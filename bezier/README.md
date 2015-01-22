###bezier
Converts input from a Bézier surface representation to a polygonal representation and then display it with OpenGL. 

make
./as3 [BEZFILE] [SUBDIVISION_PARAMETER] [ADAPTIVE_FLAG]

The adaptive flag is optional, '-a' to use adaptive tesselation and nothing will use uniform. Subdivision parameter is between 0 and 1, higher value is more fine and computationally intensive. The bezfiles are in this directory.

For example:

./as3 teapot.bez 0.1

./as3 teapot.bez 0.05 -a


From the spec of James O'Brien's Fall 2014 CS 184/284a: Foundations of Computer Graphics