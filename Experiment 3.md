EXPERIMENT – 3
Title: 3D Modelling, Transformations (Scaling, Rotation, Translation) using AutoCAD

1. Objective
To create 3D models of basic objects and perform transformations such as scaling, rotation, and translation using AutoCAD.

2. Software Required
AutoCAD (3D workspace)
3. Theory (Short)

3D modeling is the process of creating a mathematical representation of a 3D object.
Transformations include:

Translation → Moving object
Rotation → Rotating object
Scaling → Changing size
4. Initial Setup in AutoCAD
Step 1: Open 3D Workspace
Open AutoCAD
Switch workspace:
Click Workspace → Select 3D Modeling
Step 2: Set Units
Command: UNITS
Set:
Type: Decimal
Scale: Millimeters
Step 3: Set View
Use VIEWCUBE or:
Command: V → Select SW Isometric
5. Basic 3D Commands
Command	Function
BOX	Create rectangular solid
CYLINDER	Create cylinder
CONE	Create cone
SPHERE	Create sphere
EXTRUDE	Convert 2D → 3D
UNION	Join objects
SUBTRACT	Remove material
INTERSECT	Common portion
6. PROCEDURE
6.1 Creating Basic 3D Models
A. Create a Box
Steps:
Type BOX → Enter
Specify base corner → 0,0,0
Specify length → 80
Specify width → 50
Specify height → 40
B. Create a Cylinder
Steps:
Type CYLINDER → Enter
Specify center → 100,0,0
Radius → 20
Height → 60
C. Create a Cone
Steps:
Type CONE → Enter
Specify base center
Radius → 20
Height → 60
6.2 3D Transformations
A. Translation (Move Object)
Command: MOVE
Steps:
Select object
Press Enter
Specify base point
Specify new location

👉 Example: Move object from (0,0,0) to (50,50,0)

B. Rotation
Command: ROTATE
Steps:
Select object
Specify base point
Enter angle (e.g., 45°)

👉 Object rotates about axis

C. Scaling
Command: SCALE
Steps:
Select object
Specify base point
Enter scale factor

1 → Increase size

<1 → Decrease size

👉 Example: Scale = 2 (double size)

6.3 Advanced 3D Operations
A. Extrude
Steps:
Draw 2D shape (circle/rectangle)
Type EXTRUDE
Select object
Enter height
B. Boolean Operations
UNION
Combines objects into one
SUBTRACT
Removes one object from another
INTERSECT
Keeps common volume
7. Visualization
Step:
Command: SHADEMODE or VISUALSTYLES
Select:
Conceptual
Realistic
8. UCS (User Coordinate System)
Command: UCS

Use to:

Change drawing plane
Align objects in 3D
9. View Control
Command	Use
ORBIT	Rotate view
PAN	Move view
ZOOM	Zoom in/out
10. Precautions
Always work in correct UCS
Use proper coordinates
Check object orientation
Avoid overlapping solids
11. Result

3D models were successfully created and transformed using AutoCAD tools like MOVE, ROTATE, and SCALE.

12. Viva Questions
What is 3D modeling?
Difference between 2D and 3D drawing
What is extrusion?
Define scaling, rotation, translation
What is UCS?
What is Boolean operation?
