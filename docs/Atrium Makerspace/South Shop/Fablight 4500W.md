# Fablight 4500W

<img src="..\assets\fablight\fablight.png" class="image-float-right" width=30%>
The FabLight 4500 Laser Cutter is quite the machine! It cuts 1/4th inch steel, slices both sheets and tubes, and is the largest publicly available laser cutter on campus!

The machine always does rasterization first, then engraving, then cutting.

### Prerequisites for Use

* [Preparing DXFs for Water Jet and Laser Cutting](https://make.rit.edu/app/maker/training/31){target="_blank"}
* [In-Person Competency Check](#in-person-competency-check)

<p class = "clear-float"></p>

## Material Capabilities

<img src="..\assets\fablight\materials.png" class="image-float-right" width=60%>

Before using the FabLight, always refer to the Compatible Materials list! If your material is "Undocumented" or otherwise unlisted below, it means the settings for your it are not in our software list yet. Please contact [make@rit.edu](mailto:make@rit.edu) before proceeding.

<p class = "clear-float"></p>

## Preparing Your File

1. Using your favorite CAD design tool, create the design you desire for your projec. Make note of what units you used.

    * Design Constraints: Your design should consist only lines of no particular thickness or color. All cut, engrave, and raster choices are all made afterward in the software. 

    * Choosing Your CAD Software: The FabLight tool seems to prefer arcs to splines, and for this reason prefers SolidWorks to Illustrator, although for simple cuts, even  Inkscape will suffice.

2. Export your file a .dxf, with an easy to remember name

    * **In Inkscape**: File -> Save As. Then go to Save as Type, and select "Desktop Cutting Plotter (Auto CAD DXF R12) (*.dxf)"

3. Bring your .dxf file to the PC next to the FabLight, then open FabCreator 2.2, located on the desktop.

4. File -> Import, then select your .dxf file.

5. In the pop-up window, select the units that match yours.

    * For Placement, select "Move to origin before placing"

!!! warning

    <img src="..\assets\fablight\join_warning.png" class="image-float-right" width=30%>

    If you received a Join Warning you may have features that are especially small. Click OK and continue on to the editor

    If your drawing does not look right to you, you'll need to lower the line tolerances beneath the default 0.2mm. Go to Edit -> Dxf/Dxg Import -> Join Tolerance, or design your figure to have less fine details.

    <p class = "clear-float"></p>

## Using the FabCreator Software

<img src="..\assets\fablight\using_2.png" class="image-float-right" width=25%>
<img src="..\assets\fablight\using_1.png" class="image-float-right" width=25%>

This software is as simple as the Five Tabs located on the left under "Combo View". We must go through each tab in order before moving on to the machine.

1. The Part Tab organizes each of your lines into folders for Cut, Engrave, and Raster. Expand the folder to reveal all your lines, defaulting to Cut. 

    Click and drag to select the lines you'd like to change folders, then drag them over.

        * Cut: Slices through material along line.

        * Engrave: Etches material along line.

        * Raster: Fills enclosed shape with etching.


<p class = "clear-float"></p>

<img src="..\assets\fablight\using_3.png" class="image-float-right" width=50%>

2. In the Edit Tab you can use to make changes to position, rotation, and other properties of your design.

<p class = "clear-float"></p>

<img src="..\assets\fablight\using_4.png" class="image-float-right" width=50%>

3. In the Properties Tab, make sure Database is set to FL4500. 

    Under Catalog, select the correct Units, Type, and Material. Material Type is "Typical"

    Under Sheet Properties, set the appropriate Thickness.

    Leave the other setting at their defaults and press Accept to continue.

<p class = "clear-float"></p>

<img src="..\assets\fablight\using_tabs.png" class="image-float-right" width=50%>

4. The Process Tab specifies your tabs and lead-ins.

    Tabs are small spans that are left uncut to prevent the metal from falling in on itself. The length vary based on material and thickness, but we recommend 0.3mm to start. Try to use at least three, balanced around the center of your cut.

    A lead-in is a short path for the leaser to begin at in order to prevent undesired burning or imperfections form the initial blast of the laser. They are not required

    Leave Kernel Compensation on, then continue.

<p class = "clear-float"></p>

<img src="..\assets\fablight\using_5.png" class="image-float-right" width=50%>

5. Under the Job Tab, you may specify if you'd like to create duplicates of your design to fill in an area.

    Click the Make and Save button to continue.

Finally, save the .fab document to the Green Fablight Flash Drive that should be in either the FabLight PC or FabLight laser cutter itself.

<p class = "clear-float"></p>

## Running the Fablight 4500

<img src="..\assets\fablight\main.png" class="image-float-right" width=20%>

1. Flip the Main Power switch on. After 30 seconds, the front panel should present the Status Screen.

<p class = "clear-float"></p>

2. On the front panel, turn the key clockwise from MAINS to ON, then release it as the unit powers up (the will spring to MAINS) .

    After 30-60 seconds, the Machine Status will change from “Machine offline” to “Machine not homed”, and the screen buttons will turn from gray to blue. 

    Press Home Machine, and Home Machine again in the pop-up window.  After a 15-30 seconds, the machine status will update to “Machine homed”. 

<img src="..\assets\fablight\home.png" class="image-float-right" width=30%>
<img src="..\assets\fablight\key.png" class="image-float-right" width=30%>

<p class = "clear-float"></p>

<img src="..\assets\fablight\home_2.png" class="image-float-right" width=30%>

3. Press Home Machine, then again in the pop-up window.  In 15-30 seconds, Machine Status will update to “Machine homed”. 

<p class = "clear-float"></p>

<img src="..\assets\fablight\usb_drive.png" class="image-float-right" width=30%>

4. Plug the drive into the front panel.

<p class = "clear-float"></p>

<img src="..\assets\fablight\clean.png" class="image-float-right" width=30%>

5. In the drawer opposite the laser cutter, locate the green scrubby pad. Open the laser cutter shield and find the laser nozzle. 

    Gently scrub off any particulate that may have accumulated on the nozzle tip -- a couple seconds of light scrubs will suffice.

<p class = "clear-float"></p>

<img src="..\assets\fablight\clamp.png" class="image-float-right" width=30%>

6. For larger and thicker metal sheets, utilize the left side of the bed. This area offers a more expansive surface suitable for bigger projects, providing optimal support and space for your cutting needs.

    In any case, loosen the four red screws on the left side, secure your metal sheet under these screws, then re-tighten them. 

    This step is extremely important to not just secure your sheet, but grounding it electrically. Do not skip it!

    Then push the bed back into position -- there is a divot that you can feel that the rails should settle into.

<p class = "clear-float"></p>

7. On the display, press Continue, then New Job.

    Select your file from the list of files on the USB drive, then press Select File. 

<img src="..\assets\fablight\preview.png" class="image-float-right" width=30%>

8. Now, select Preview File. Be sure that everything looks as expected. If so, continue by clicking the green check-mark.

<p class = "clear-float"></p>

9. Adjust the x and y axis locations for the laser cutter by dragging the respective two blue bars. You can double click the bars to set a specific axis-value.

10. If all is good, press Run Job on the display, followed by the flashing green Start button just above it.

11. When the job is complete, give the metal at least 30 seconds to cool down, then use a pair of gloves from the computer drawer, open the shield, and remove your piece by unclamping.

12. The tabs may make it hard to break your piece out after cutting -- there is a hammer located nearby.

    You should hold your piece perpendicular to the floor when hammering. Never hammer anything while it is on the print bed!!

13. When you are done, remove your file from the flash drive.

    Then, clean up your material and return the tools to where you found them. 

## In Person Competency Check

1. Run through the above process
2. Clean the machine per instruction below
3. Complete steps 1-2 at least 3 times

### Cleaning the Machine

<iframe width="800" height="640" src="https://www.youtube.com/embed/nHSUXOYKm5Y?si=hgKKRZLjaC9wgh9x" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
