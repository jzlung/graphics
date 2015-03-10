###phong
Implements the Phong Illumination Model (by hand, minimal OpenGL) to light a sphere. The scene is set with point and directional lights, and the object can have coefficients for ambient, diffuse, and specular reflection. 

• -ka r g b
This is the ambient color coefficients of the sphere material. The parameters r g b are numbers
between 0 and 1 inclusive.

• -kd r g b
This is the diffuse color coefficients of the sphere material. The parameters r g b are numbers
between 0 and 1 inclusive.

• -ks r g b
This is the specular color coefficients of the sphere material. The parameters r g b are numbers
between 0 and 1 inclusive.

• -sp v
This is the power coefficient on the specular term. It is a number between 0 and max_float.

• -pl x y z r g b
This adds a point light to the scene. The x y z values are the location of the light. The r g b
values are it's color. Note that the x y z values are relative to the sphere. That is, the center of
the sphere is at the origin and the radius of the sphere defines one unit of length. The Y direction
is UP, the X direction is to the right on the screen, and the Z direction is "in your face." The
r g b value are between 0 and max_float, NOT between 0 and 1 (that is, the r g b values encode
the brightness of the light).

• -dl x y z r g b
This adds a directional light to the scene. The x y z values are the direction that the light
points in. The r g b values are it's color. See -pl for coordinate system notes. 


From the spec of James O'Brien's Fall 2014 CS 184/284a: Foundations of Computer Graphics