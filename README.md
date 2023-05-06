Download Link: https://assignmentchef.com/product/solved-eece5639-computer-vision-i-homework-1
<br>
<span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;">1.   Consider an ideal pinhole camera with its center of projection located at the origin of the worldcoordinate system, its optical axis along the Z world coordinate axis, and focal length f. A point P = (X,Y,Z)0 on a line in space passing through points P0 = (Xo,Yo,Zo)0 and P1 = (X1,Y1,Z1)0 must satisfy the following equations:</span>

X=Xo + λ(X1 − Xo)Y=Yo + λ(Y1 − Yo)Z=Zo + λ(Z1 − Zo)where λ is a scalar −∞ ≤ λ ≤ ∞, and all coordinates are given in the camera coordinate system. (Note, the larger |λ| the farther the point P is from Po.)

(a)   Find the equations of the image of the given line.

(b)   Show that when the 3D line is not parallel to the image plane, the image of P does not go to infinity as |λ| → ∞.

(c)   Show that when the 3D line is not parallel to the the image plane, the image of the midpointof the segment PoP1 is not the midpoint of the image segment pop1.

Figure 1: Room with tiles.

2.   Consider a room (10m.×4m.×4m.) with a world coordinate system (X,Y,Z) such that the Z axis is vertical along a corner and the X and Y axes are along the walls as shown in Figure 1. An imaging system contains a camera located at the center of the left wall of the room as shown in Figure 1. The optical axis is perpendicular to the wall and the lens is in front of the wall. The focal length of the camera is 50mm. The (x,z) plane of the camera is parallel to the (X,Y ) world plane. The floor of the room is made out of tiles with their sides parallel to the walls of the room. Each tile is 50cm. × 50cm..

1

Prove that the images of the sides of the floor tiles parallel to the camera optical axis intersect at a single point. What are the image coordinates of this point?

Hints:

(a)   The intersection point is the image of the point on the lines at infinity.

(b)   The equation of a line in 3D can be written as P = Po + λv where P = (x,y,z) are the coordinates of the points on the line as the scalar parameter λ is varied, Po = (xo,yo,zo) are the coordinates of a fixed point on the line, and v = (v1,v2,v3) is a vector parallel to the line.

3.   A camera with focal length f has taken a picture of a cube on the floor of a room as shown in Figure 2. Three of the sides of the image of the cube lie on lines that intersect at the point on the image plane with camera coordinates (10,0,f) . Find the orientation of the corresponding sides of the cube in 3D, with respect to the camera coordinate system.

Figure 2: Image of a cube

4.   Use the perspective projection equations to explain why, in a picture of a face taken frontally andfrom a very small distance, the nose appears much larger than the rest of the face. Can this effect be reduced by acting in the focal length?

5.   One form of color blindness in humans comes from a deficiency of “blue” color receptors. Which oneof the following pairs of colors appear almost the same to a person with a blue receptor deficiency?

(a)   Blue and cyan (cyan is blue-green).

(b)   Red and magenta (magenta is blue-red).

(c)   Red and green

6.   Suppose that a color camera encodes a given pixel in RGB as (200,50,100) where 255 is the highestvalue.

(a)   What should be the equivalent triple in the CMY system?

(b)   What should be the equivalent triple in the YIQ system?

(c)   What should be the equivalent triple in the HSI system?

2