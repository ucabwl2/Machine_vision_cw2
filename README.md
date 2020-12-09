# Machine_vision_cw2

o	Goal: to find the four corners of an AruCo Marker in an frame taken from a video and use homography to project a 3D cube fitting on the AruCo marker. 

o	Used a temporal model (Constant velocity model) to compensate for the motion in the video predict the location of the four corners

o	Applied a direct linear transform (DLT) algorithm to recover the best homography which represents the best relationship between the lower four corners and the upper four corners in the cube.
