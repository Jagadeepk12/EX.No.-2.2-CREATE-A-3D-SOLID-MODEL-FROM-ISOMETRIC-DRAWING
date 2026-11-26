# EX.No.-2.2 CREATE A 3D SOLID MODEL FROM ISOMETRIC DRAWING
## Date :15-10-2026

## AIM: 

To design and construct a 3D CAD solid model of the given
mechanical bracket component using parametric 3D modeling
software, adhering precisely to all dimensional parameters given
in the isometric drawing.

## REQUIREMENTS:
1. Autodesk fusion 360
2. Windows 10
3. 16 GB of RAM (integrated graphics recommend 1 GB or more)
4. 2.5 Mbps or faster download; 500 Kbps or faster upload 

Key Dimensions Summary
* **Base Plate:** * Length between arc centers: 56𝑚𝑚
* End radius: 𝑅18𝑚𝑚
* Thickness: 8𝑚𝑚 (Width = 36𝑚𝑚 )
* Two holes: $\varnothing16\text{ mm}$ each
  
* **Vertical / Rib Block:**
* Height from base: 32mm
* Width: 40𝑚𝑚
* Thickness of base block/wall offset: 10𝑚𝑚
* Triangular Web/Rib thickness: 12𝑚𝑚
  
* **Upper Arm:**
* Horizontal extension length: 32𝑚𝑚
* Height/Thickness: 10mm
  
* **Upper Cylindrical Boss:**
* Outer Diameter: $\varnothing30\text{ mm}$
* Inner Hole Diameter: $\varnothing20\text{ mm}$
* Total Boss Height: 10𝑚𝑚 protruding above the arm

## Step-by-Step Procedure

Step 1: Environment Setup

1. Open the CAD software and create a **New Part File** (`.prt` or
`.sldprt`).
2. Set the unit system to **MMGS** (Millimeter, Gram, Second).

Step 2: Modeling the Base Plate

1. Select the **Top Plane** and create a new sketch.
2. Draw two circles of diameter 16mm spaced 56mm apart
horizontally along the center axis.
3. Draw concentric arcs of radius 𝑅18𝑚𝑚 around each circle
center
4. Connect the outer arcs with tangent lines to complete the
slot-like base boundary.
5. Extrude the sketch upwards using **Extrude Boss/Base** with
a height/depth of ** 8𝑚𝑚 **


<img width="1226" height="560" alt="image" src="https://github.com/user-attachments/assets/c8fbfe5d-1923-4a20-986f-edff015e5f04" />

Step 3: Modeling the Vertical Block

1. Select the top surface of the base plate (or the **Front/Right
Plane**) to create the central vertical support profile.
2. Sketch a rectangle with a width of ** 40𝑚𝑚 **, thickness of
**10𝑚𝑚 ** and height of **32𝑚𝑚 ** rising above the top surface of
the base.
3. Apply **Extrude Boss/Base** to create the solid vertical block.


<img width="1121" height="743" alt="image" src="https://github.com/user-attachments/assets/2bd79cc6-3851-4d2b-9ca3-1f2ca039a581" />

Step 4: Creating the Triangular Support Rib (Stiffener)

1. Select the symmetry plane (e.g., **Right Plane** or mid-plane
passing through the center of the part).
2. Draw a right-angled triangle sketch connecting the top rear
edge of the vertical block to the top face of the base plate.
3. Use the **Rib Feature** (or **Extrude Mid-Plane**) with a
specified thickness of **12𝑚𝑚 **.


<img width="1032" height="572" alt="image" src="https://github.com/user-attachments/assets/c77cf8dc-b281-432b-96e6-fcb9a1c159d8" />

Step 5: Modeling the Upper Cantilever Arm

1. Select the front face of the vertical block.
2. Create a sketch extending forward horizontally:
* Extension length = ** 32𝑚𝑚 **
* Height/Thickness = ** 10𝑚𝑚 **
* Width = ** 40𝑚𝑚 ** (matching the vertical block width)
3. Extrude the sketch to create the horizontal cantilever portion.

Step 6: Modeling the Upper Cylindrical Boss & Center Hole

1. Select the top surface of the upper cantilever arm or a parallel
plane.
2. Draw a circle of diameter **$\varnothing30\text{ mm}$**
centered at the front end of the arm.
3. Extrude this sketch upwards by ** 10𝑚𝑚 **.
4. Select the top face of the new cylinder, sketch a concentric
circle of diameter **$\varnothing20\text{ mm}$**.
5. Apply **Extruded Cut** with the condition **Through All** to
create the central hole.


<img width="1207" height="610" alt="image" src="https://github.com/user-attachments/assets/e7804151-fdb7-4faf-98f1-a3996d0364af" />

Step 7: Final Inspection & File Saving

1. Inspect the feature tree to ensure proper parent-child relations
and fully constrained sketches.
2. Check all dimensions against the drawing.
3. Apply appearance/material (e.g., Magenta/Purple color as seen
in the source image) if required.
4. Save the file as `Mechanical_Bracket.SLDPRT` (or
corresponding extension).

## Output:


<img width="1142" height="765" alt="image" src="https://github.com/user-attachments/assets/8b7fd329-8571-4c38-a35b-ee9b06bc6f88" />


<img width="1192" height="817" alt="image" src="https://github.com/user-attachments/assets/ee3fc420-608a-4fc3-a670-b7778404ef24" />

## RESULT: 
Thus the given sketch is drawn and drafted using fusion 360
tool.
