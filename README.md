# graphics
Assortment of graphics problems solved for CS184
Each folder has its own README that explains the project, files, and how to run.

'raytracer', 'inverse-kinematics', 'bezier' were done in collaboration with Logan Carter. All usage for each project can be found in each's README. 

###phong
Implements the Phong Illumination Model (by hand, minimal OpenGL) to light a sphere. The scene is set with point and directional lights, and the object can have coefficients for ambient, diffuse, and specular reflection. 
example_01.cpp is the main file

###raytracer
Ray Tracer is a multipart functional graphics generator that creates image by shooting rays through a screen into the scene. Takes a scene file which includes a sphere and lights.
raytracer.cpp
Util.h
Util.cppm

###bezier
Converts input from a Bézier surface representation to a polygonal representation and then display it with OpenGL. 
as3.cpp is the main file

###inverse-kinematics
Basic Inverse Kinematics solver, animates an arm on a path by giving it a target, which the arm should contort to reach.
as4.cpp is the main file
Util.h for defined classes

