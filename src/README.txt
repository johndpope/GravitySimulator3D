Usage:

java -jar GravitySimulator3D.jar
java -jar GravitySimulator3D.jar filename.scene

The scene files can be found in de directory: "rdj/scenes/"


The following keys can be used:

Key	Description

ENTER	Continue or pause movement on all objects with any type of translational of rotational momentum
SPACE	Show or hide displays
TAB	Restore (Motion State Changable) objects in scene (position & motion)
P	Print coordinal status to terminal (if started from terminal / command-line)

Control Object Movement

0-9	Control object (if object is cam then switch view to this cam)
CTRL0-9	Only control object (ignore view switch if object is cam)
[	Zoom Cam Out (also mouse wheel)
]	Zoom Cam In (also mouse wheel)


Move (Translate)

Q	Move forward fast (main engine)
W	Move forward
X	Move backward
A	Move left
D	Move right
E	Move up
C	Move down
S	Stop (real astronauts don't have such a break of course)

Rotate

Mouse	Left click in scene to rotate controlled object
ESC	To release mouse rotational control

J	Rotate (pan) left
L	Rotate (pan) right
<	Rotate (tilt) up
I	Rotate (tilt) down
U	Rotate (roll) left
O	Rotate (roll) right
K	Stop (real astronauts don't have such a break of course)

M	Scale down (found use for this in the past)
>	Scale up  (found use for this in the past)

================================================================

Displays (use SPACE to show or hide)

The left display is the SceneDisplay offering many scene and object related functions
The bottom display is the NodeDisplay offering coordinal info and edit functions

================================================================

Further you can create your own scenes in the scenes directory.
Use the included scenes as an example on howto create scenes.
Create your scenes in the same directory and they will appear in the scenes list of the SceneDisplay

Any questions regarding GravitySimulator3D can be send to: ronuitzaandam@gmail.com