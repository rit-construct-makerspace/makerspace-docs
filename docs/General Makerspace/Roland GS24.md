# Roland GS24

<img src="..\assets\gs24 hero.webp" class="image-float-right" width=40%>

## Overview

The GS24 is a vinyl cutter. It can automatically cut stickers, stencils, heat-transfer vinyl, and more based on image files. Designs can be up to 24" wide, and infinitely long! 

Since designs are cut from a sheet of material, only single color designs are possible without manual overlaying of multiple cuts.

Beyond vinyl, the machine can also cut paper, thin rubber, and similar thin complaint materials. It cannot be used to cut fabric, veneer, or rigid plastic sheeting.

!!! info
    We have some basic vinyl options available free-of-charge in the makerspace! You can also provide your own though. 

[GS24 Online Manual](https://files.rolanddga.com/files/gs-24_usersmanual/responsive_html5/index.htm#t=GS-24_index.html){:target="_blank" .md-button}

### Prerequisites for Use

[Click here to view training requirements and progress (make.rit.edu)](https://make.rit.edu/app/makerspace/37/equipmentUserInfo/39){ .md-button }


## Preparing Designs

Ideally, you would use a vector file (SVG, DXF, etc.) for the vinyl cutter. If you have a vector file, follow the steps in **Inkscape SVG Direct Transfer** below. If you have an image file (JPG, PNG), follow the steps in **Tracing a Non-Vector file** below.

If you are resuming a previous project that you have saved as a CST file, open it with *File > Open* in CutStudio directly.

!!! tip
    Making a very simple design, just shapes and text? No need to prep a file! CutStudio has some built-in shape tools you can use directly. 

### (Preferred) Inkscape SVG Direct Transfer

To open your DXF, SVG, etc. in Inkscape, open the software and hit *File > Open...*. If the file is not an SVG, a dialog box may appear for a file conversion before you can continue.

Since our file is already a vector, we can pass it directly to the vinyl cutter's software. Before we do that though, make sure the vector only contains;

* **The shape you want to cut.** Remove any other details! 
* **Solid, line-only shapes.** Remove any fills, patterns, or partial transparency. Remove any embedded images. Make sure all lines have a weight.
* **No Text Objects!** Convert text objects to path objects by selecting them, and hitting *Path > Object to Path*.

Before continuing you should also **check your scale**! To do this, select an object, and at the top, you will see the dimensions. By default, it is in **px** (pixel) units, but you can change to inches or millimeters by clicking the unit drop-down. 

Once you have confirmed everything is correct open **Roland CutStudio** in the background. Back in Inkscape, hit *Extensions > Roland CutStudio > Open in CutStudio*.

### Tracing a Non-Vector File

<iframe width="560" class="image-float-right" height="315" src="https://www.youtube.com/embed/mQjLP4vibVA?si=mX8x4COau3dIz4ce" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

Before continuing, make sure you have a relatively simple image to make tracing easier. Tracing works best if they have clear, distinct colors and obvious edges for the software to pick up on. Import these files by hitting *File > Import*. Multiple files can be cut as part of the same design, and the software will nest them automatically.

To convert your image file into a line for the machine to follow, we have to trace it. To do this;

1. Left-click on your image, then right-click and select "Image Outline".
2. Click "Image Outline" and hit the "Extract Contour Lines" button.
3. Adjust “Alignment Image Density" and “Remove Thin Lines” sliders to cleanly isolate your intended cut lines.

    !!! note
        Make sure to click “Extract Contour Lines” as you make adjustments to update the preview.

4. When satisfied with the images the software has extracted, hit "OK". 
5. If individual lines and points need to be adjusted, double-click on the contour to make it editable. Select individual points to move them. 
6. When finished, click on the “Select” tool and move the contour lines off the base image.
7. To remove the base image, right-click on the image and press “Delete”.

<p class = "clear-float"></p>

### Preparing to Cut

1. Manually move all items as close to the bottom left corner as possible, without overlapping.
2. Draw a box that outlines everything that will be cut. This makes [weeding](#weeding) easier later.
3. Pause now to [load your vinyl](#loading-vinyl), then continue to [import material settings](#material-settings)

Once all previous steps are complete, **you are ready to cut!** Click the "Cutting" button or CTRL+P to begin. Click "OK" when ready to start. 

!!! warning
    As the cut is going, watch that the blade is not cutting through the paper backing of the material. If so, speak to staff about adjusting blade pressure.

### Material Settings

4. Go to *File > Cut Setup*
5. Under "Media", hit "Change..."
6. Hit "Get from Machine" and then OK at the bottom. 
    * The numbers should adjust to the actual dimensions of your material.
7. Hit OK again whe back in Cut settings.
    * You may need to reposition your design to fit in the vinyl.

![Image](./assets/gs24%20mat%20set.webp)

## Loading Vinyl

<img src="..\assets\gs24 load.webp" class="image-float-right" width=30%>

Before continuing, power down the machine.

1. Gently push the cutting carriage to the side and away from your vinyl.
2. Lift the rollers by pushing the loading lever down.
3. Insert your vinyl until the front edge is just past the blade protector strip.
4. The rollers MUST be on the vinyl and under a grit mark!
    * The left roller must be under one of the first 4 on the left.
5. Align the left edge of the material with the guide line nearest to it. 
    * Use the matching guide line on the back to make sure it's straight.
6. Lower the rollers by lifting the lever from before.
7. Power back on the machine, and select the material type on the screen when prompted.

Your materials is now loaded! Return to the computer to print your file.

<p class = "clear-float"></p>

## Remove Finished Cut

<img src="..\assets\gs24 cut guide.webp" class="image-float-right" width=30%>

After cutting is complete;

1. Lift the pinch rollers using the loading lever
2. Gently push the cutting carriage to the side and away from the vinyl
3. Pull the vinyl forward so that your framing box is past the cutting strip
4. Cut the vinyl with scissors or an X-Acto knife, using the knife guide to help guide the cut.

<p class = "clear-float"></p>

## Weeding

<img src="..\assets\gs24 weeding.webp" class="image-float-right" width=30%>

Weeding is the process of removing unwanted vinyl after cutting. Once we remove the unwanted vinyl, we will apply transfer tape to help stabilize our design. Weeding tools are available to borrow, just speak to a member of staff.


* Use tweezers or an X-Acto knife to remove the framing rectangle you prepared earlier, going slowly to ensure your design does not come up.
    * If it starts to come up, hold that part down with the corner or a squeegee or blade and continue on removing the excess material.
* Continue this process for all other negative space and unwanted material.
* If using stick-on or window cling vinyl, slowly apply transfer tape to the surface of your design, using a squeegee to remove bubbles as you go.
    * Use the squeegee to make sure the design has properly adhered to the transfer tape. 
    * This can usually be observed with a change in apparent color of the design underneath the tape.

<p class = "clear-float"></p>

## Apply Stick-On Vinyl

<img src="..\assets\gs24 stick on.webp" class="image-float-right" width=30%>

1. Clean the surface where you will be applying your vinyl.
2. Slowly peel the transfer tape off of the vinyl backing.
    * If individual parts of your design are sticking to the backing instead of the transfer tape, put it back down and use the squeegee to better adhere it to the transfer tape. 
    !!! tip
        Lifting the transfer tape at extreme angles can also help to better release from the backing material. 
3. Carefully position your design over the desired surface.
4. Starting in one corner or edge, use the squeegee to push the design down and adhere it to the surface.
5. When fully applied, use the squeegee to force the vinyl onto the final surface
6. Pull up the transfer tape slowly, ensuring the design does not come up with it. 
    * If it starts to, push it back down with the squeegee and try pulling the transfer at different angles.

<p class = "clear-float"></p>

## Apply Heat Transfer Vinyl

<img src="..\assets\gs24 heat transfer.webp" class="image-float-right" width=30%>

!!! warning
    Not all heat transfer vinyl is the same, review the instructions for your material before proceeding.

1. Position the design over where you want it applied, making sure the clear tape on the vinyl is facing up.
2. Follow the specific directions for your vinyl, entering those settings into the Cricut heat press
3. Once it has heated up, use it to apply a firm pressure on top of your design for the specified amount of time.
    * Once applied, give the design time cool before checking for adherence. 
    * You may need to use a longer time and/or higher temperature if it does not stick at first. Use a scrap piece to check in an inconspicuous area first.
4. Remove the clear backing tape once the design has fully cooled and you ensure it is properly adhered. 

<p class = "clear-float"></p>

## In-Person Competency Check

To demonstrate competency, makers will be asked to create a small sticker. They may choose/make a design of their own, or staff can provide one. 

* Load vinyl
* Demonstrate the software workflow for loading 
* Safely weed the design and apply transfer tape
* Apply the finished sticker to a surface