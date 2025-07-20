# Operating the Epilog Laser

<div class="grid" markdown>

[Preparing the Files](./Preparing%20Files.md){target="blank" .md-button}

[Using the Epilog Software](./Software.md){:target="_blank" .md-button}

</div>

This page will walk you through preparing the laser cutter to execute a cut. By now, you should have prepared and printed your file from the computer. See the training below for more details on this.

## Epilog Laser Interface Guide
<img src="..\assets\operating\interface.webp" class="image-float-right" width=40%>

All Epilog lasers use the same touchscreen interface, found on the right side of the machine.

The top and bottom navigation guides are always present. On the top, from left to right, is;

* File List: Here files sent from the computer are stored and can be selected.
Delete File: Deletes currently selected file.

* Settings: Internal machine settings, can be ignored.

Along the bottom, the buttons are;

* Reset: Abandons in-progress job, and returns the laser to the park position (usually top left corner)

    * This is the equivalent of an emergency stop on the machine!

* Table: Allows control of the table up and down, as well as auto-focus controls

* Laser Pointer: Enable/disable a visible laser pointer for alignment

* Jog Axes: Allows you to move the X/Y axes of the machines

* Trace: Quickly drive the head of the machine around the perimeter of the job. When paired with the laser, you can use this to check if your project fits on the material.

<p class = "clear-float"></p>

## Jog Axes Menu
<img src="..\assets\operating\jog_axes.webp" class="image-float-right" width=30%>

The jog axes menu is one of the most important ones, so let's look more specifically at this one.

When you are in the menu, you can use the joystick to move the machine head around. The exact position of the laser head will be shown on the screen, and you can move it in small increments with the arrow keys on screen.

Don't worry about driving too far! The laser will stop before crashing into the edges of the machine. You can still damage it by crashing into material, though, so be careful.

The “Move To” command can be used to precisely position at exact coordinates.

The “Centering Point” command can be used to say where a laser cut should start from. This only works when the file is configured as a relative position in Epilog Dashboard.

The “Park Axis” button returns the axes to the park position, usually the top left corner.

The “Auto Focus” button moves the head down in its current position to find the material. 
This feature is not available on the Fusion Pro machine, even though the button is there!
 
<p class = "clear-float"></p>

## File List
<img src="..\assets\operating\file_list.webp" class="image-float-left" width=30%>

The File List shows all files sent from the computer, newest at the top. Files are automatically deleted once cut, and/or when the machine is restarted.

To select a file, simply click on it. The selected file will turn blue. To start the job, press the glowing play/pause button to the left of the joystick to immediately begin.

Long-pressing on a file in the File List will bring up information about it, such as the duration, the processes, and the positioning type (if applicable). If you intend to run the same job repeatedly, you can click the save icon on this screen to stop automatic deletion.

Pressing the play/pause button while the job is running will pause the job. Jobs do not pause immediately, but rather when they finish their current move. On a raster, that is a full-length left-to-right or right-to-left. On a vector, that means it will finish cutting/engraving the current vector element.

<p class = "clear-float"></p>

## Loading Materials

<img src="..\assets\operating\mat_2.png" class="image-float-right" width=30%>
<img src="..\assets\operating\mat_1.png" class="image-float-right" width=30%>

When the machine is idle, open the door and place your material inside on the bed. You can place the material anywhere, but most people push it up against the hard stops in the top left corner of the bed.

The material must lay flat on the bed. A bow of more than 1/4" is not acceptable. You can try to remove the bowing by flipping the material over, or cutting it into smaller pieces in the wood shop. Weights should not be used to try and remove the bowing from material. These weights present an obstacle that the machine can crash into.

<p class = "clear-float"></p>

<img src="..\assets\operating\mat_4.png" class="image-float-right" width=30%>
<img src="..\assets\operating\mat_3.png" class="image-float-right" width=30%>

If your material is very light (fabric, paper, etc.) and you are worried about it being blown out of alignment, ask the staff for magnets to secure it to the bed.

If you want to manually trigger the auto-focus, drive over the center of your material and press “Auto Focus” to determine the material focus. 

<p class = "clear-float"></p>

## Fume Extractors & Air Assist

### Fume Extractor
<img src="..\assets\operating\edge_12.png" class="image-float-right" width=35%>

All 3 laser cutters have a fume extractor, that should automatically turn on when the cut starts.

On the Fusion Edge 12, the fume extractor is in the base of the machine. To verify the fume extractor is ready to operate, the 3 indicators on the front should be flashing. You can tell the fume extractor turns on if the green light is on and there are blue light(s) on in the bar graph while cutting.

On the Fusion Edge 36 and Fusion Pro, the fume extractor is behind the computer. These extractors are ready to operate if there is content on the screen. You can tell the extractor is working if the top number on the screen increases from 0 when the laser runs. If the buttons on the right side of the screen turn red, it is an indicator of an error. Notify staff, but it is usually not critical enough that you have to stop the current job on the laser cutter.

---

### Air Assist
<img src="..\assets\operating\edge_36.png" class="image-float-right" width=35%>
The Fusion Edge laser cutters both require compressed air to properly operate. The Fusion Pro does not. The air controls are behind the laser cutters.

Air is on when the white handle is parallel with the pipe, it is off when the handle is perpendicular. You should also verify air is flowing by the gauge on the end of the pipe reading more than 0.

<img src="..\assets\operating\air_assist.png" class="image-float-left" width=35%>

<p class = "clear-float"></p>

## Laser Fire Hazard

While the laser cutter is running, you must monitor it at all times! The laser cannot be left unattended!

Laser cutters have a high risk of fire. This section will review what to look for and how to respond to it.

It is regular to see smoke and small flashes of flame while laser cutting. These are not of concern.

Sustained fire is the main concern; when something is on fire for extended period, and/or after the laser has moved on from that area. This is most common in plywoods that have lots of binder and glue, but can happen in any material.

If a sustained fire occurs, immediately pause the laser cutter by pressing the button below the touchscreen.

DO NOT turn off the laser cutter or press the emergency stop in the event of a sustained fire. This will disable the fume extractor.

IMMEDIATELY notify staff of a sustained fire. Keep the machine closed.

The laser cutters are designed to contain and safely smother small fires. Opening the lid will expose more oxygen and may increase flames.