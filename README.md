## EXPERIMENT: No.3.2
## CREATE 3D MODEL FROM ORTHOGRAPHIC PROJECTION
## AIM:

To create a 3D model from given orthographic projection.

## REQUIREMENTS:

• Software: Autodesk Fusion 360 (Educational License)

• Hardware: Workstation/PC equipped with a 64-bit processor, minimum 8 GB RAM, a dedicated graphics card, and a 3-button scroll wheel mouse.

## PROCEDURE:

Step 1:Create Central Arch

• Setup Units: Open Autodesk Fusion 360, create a new design file, and verify under Document Settings that units are set to Millimeters (mm).

• Select Sketch Plane: Click Create Sketch and select the Front Plane (XY plane).

• Draw Arch Profile: Sketch the central arch profile with an outer radius of R110mm along with the bottom internal rectangular undercut slot measuring 120mm wide and 60mm high

<img width="650" height="416" alt="image" src="https://github.com/user-attachments/assets/70ab4172-46f0-4861-af3a-9fd085435586" />

• Extrude Profile: Finish the sketch, select Extrude (E), pick the profile, set it to extrude symmetrically to a total width of 150mm, and set Operation = New body

<img width="372" height="462" alt="image" src="https://github.com/user-attachments/assets/c311bac7-0c02-4668-8096-4214c13c2dcb" />

<img width="707" height="547" alt="image" src="https://github.com/user-attachments/assets/519e1c82-b8d7-4617-8271-66daf9afa937" />

Step 2:Create Base-Flange Using Offset Plane

• Create Offset Plane: Go to Construct > Offset Plane, select the Top Plane (XZ plane) or the bottom reference plane of the arch, and input the required offset distance to position it at the bottom base level. Click 0K.

<img width="390" height="332" alt="image" src="https://github.com/user-attachments/assets/4b080dd4-f4b6-4c6f-a96d-a6e33db38fe4" />

• Sketch on Offset Plane: Select the newly created offset construction plane and dick Create Sketch

• Draw Base Profile: Draw the outer footprint of the base plate: an overall length of 420mm with rounded ends of radius R60mm and a total width of 150mm

• Extrude Base: Finish the sketch, select Extrude (E), pick the base profile, extrude it upward to a thickness of 30mm, and set Operation = Join.

<img width="371" height="462" alt="image" src="https://github.com/user-attachments/assets/ab579c1e-cb20-46af-a5d1-a6ed0d1effb5" />

Step 3:Create End Holes in the Base Flange

• Select Sketch Plane: Select the top flat surface of the left or right base flange extension and click Create Sketch.

• Draw Circles: Draw circles of diameter $\emptyset 40\text{ mm}$ concentrically aligned with the R60 rounded arc centers on both ends of the flange.

<img width="725" height="382" alt="image" src="https://github.com/user-attachments/assets/42b8c2b4-572c-4928-a07d-3d2f2b09ae86" />

• Cut Extrusion: Finish the sketch, launch Extrude (E), select both circle profiles, set Operation = Cut, and set Extent = All to bore clean through the 30mm base flange.

<img width="372" height="515" alt="image" src="https://github.com/user-attachments/assets/eef8ec08-cb67-4777-9785-2865b51a762d" />

<img width="718" height="507" alt="image" src="https://github.com/user-attachments/assets/e4144dbe-b2a3-4c47-af8a-40e4ce5317c2" />

Step 4:Create Central Hole

• Select Sketch Plane: Select the top curved apex face of the central arch dome as your sketch plane and click Create Sketch

• Draw Circle: Draw a circle with a diameter of 20 mm centered precisely at the midpoint of the arch.

<img width="677" height="342" alt="image" src="https://github.com/user-attachments/assets/9d293d83-9026-407b-a7d0-3ff44fde6634" />

• Cut Extrusion: Finish the sketch, select Extrude (E), pick the circle profile, set Operation = Cut, and set Extent = All (or through the arch wall down into the internal cavity).

<img width="345" height="475" alt="image" src="https://github.com/user-attachments/assets/3d420e46-75bf-4a58-ad07-12db22853a81" />

<img width="672" height="530" alt="image" src="https://github.com/user-attachments/assets/ec19c551-0fc1-4807-854c-99ab3f827f11" />

## OUTPUT:

<img width="1016" height="718" alt="image" src="https://github.com/user-attachments/assets/70aef5cb-c978-4e9a-a3d7-ce983dca6b62" />

## RESULT:
Thus, 3D model is created from orthographic projection.



