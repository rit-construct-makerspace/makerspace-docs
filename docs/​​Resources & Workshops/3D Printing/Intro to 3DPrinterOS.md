# Intro to 3DPrinterOS

3DPrinterOS is the management platform that allows you to access all 3D printers in the SHED. To access 3DPrinterOS, click the link below;

[3DPrinterOS (RIT SSO Link)](https://cloud.3dprinteros.com/ssosaml/rit/auth){:target="_blank" .md-button}

!!! warning
    <img src="../assets/3DPrinterOS SSO.png" class="image-float-right" width=20%>
    You **must** access the printers via SSO (single sign-on) with your RIT account. Do so at the link above, or on the 3DPrinterOS login page, hit "SSO" and select "Rochester Institute of Technology" from the list.

    Creating an account any other way, or using a standard 3DPrinterOS account, will not work. Even if it uses your RIT email address! Attempting to bypass SSO requirements will break the system and you will not be able to access 3D printers.

    The **only** exception to this is dedicated printing accounts for certain classes, clubs, and research groups. If instructed to use this login method instead, log in [at this link]([cloud.3dprinteros.com/](https://cloud.3dprinteros.com/#/sign)){:target="_blank"}
    <p class = "clear-float"></p>

## Navigating 3DPrinterOS

The 3DPrinterOS website is broken into a number of pages, accessible at the top of the screen. Let's go through each of them;

<img src="../assets/3dprinteros navigation.png" class="image-float-left" width=100%>

 <p class = "clear-float"></p>

### Projects

 This is where your files live. You have 1GB of storage space on the 3DPrinterOS cloud for 3D models and prepared machine files (GCode).

 Files can be uploaded with the "Add files" button. Suggested file types are STL and OBJ, but other file types can be uploaded and converted in the cloud.

<img src="../assets/3dprinteros selected file.png" class="image-float-right" width=30%>

 By default, files will go into your "Files" tab. You can organize files into folders, called "Projects", where they will then appear in your Projects tab. To create a Project, hit the "..." menu next to the "Add files" button, and select "Create project". Files can then be moved by selecting the toggle next to their icon, and hitting "Move to project". 

<p class = "clear-float"></p>

A new project is automatically created whenever you make a derivative of a file as well. For instance, converting an uploaded 3MF to an STL will put both the 3MF and the STL into a new project together. 

The projects page is also where you prepare files for 3D printing, see [3D Model Preparation](#3d-model-preparation) below for more information on this.

### Activity

The activity page shows all your past activity on 3DPrinterOS. Submitted prints will be shown here, as well as their status (success, failure, in progress). You can click on a print to get more information. 

By hitting the "..." menu to the right of a job, you can cancel the print (if it has not yet started), restart it, see details (same as clicking) or view any notes from staff on your 3D print. 

<img src="../assets/3dprinteros activity.png" class="image-float-left" width=100%>

<p class = "clear-float"></p>

### Printers

<img src="../assets/3printeros print queues.png" class="image-float-right" width=50%>

The "Printers" tab lets you see print queues you have access to, and where your parts are in queue. 

Parts nearer the top will be printed next. You can see a time estimate next to each print. Your print is the only one(s) that have details visible. 

If you hit the "..." menu you can cancel your own prints if they are not already started.

If you do not see any printers, you probably are missing trainings! Check make.rit.edu for more info.

<p class = "clear-float"></p>

## 3D Model Preparation

!!! note
    To continue in the printing process, you must have an STL. If you upload a different 3D file type, like STEP or 3MF, you will need to convert it to an STL first. To do this, press "..." next to the file name, then "Convert". After about 1 minute, an auto-generated STL of your file will be added to the project containing the original.

After you upload a file, you will likely need to optimize it for 3D printing. Navigate to the file in your **Files** or **Projects** tabs. Hit the *Layout* button. When you open a model, you will see it relative to the bed size of a standard 3D printer in the first floor print farm. 

### Scaling

<img src="../assets/3dprinteros scale.png" class="image-float-right" width=20%>

**STLs are unitless files** so it is possible your model will be the wrong size. So the first thing we should do is check the scale of your mode. To do this, click the "Scale" button in the top right bar. 

!!! info
    If the scale, rotate, and move options are greyed out, that means you do not have the model selected. Click on it, and you should see the options highlight. 

All units in 3DPrinterOS are millimeters. If you know your item's intended size you can enter the X, Y, or Z values in the Scale menu to automatically adjust the size. By default, changing one will cause the other two to proportionally adjust. You can disable this by checking the "Keep Proportions" toggle. 

You can alternatively scale by a percentage, by typing in a percent in the boxes below the millimeter measurements.

If your model is much bigger or smaller than expected, it is likely a units issue. At the bottom of the scaling menu, you can hit "mm -> inch" if your model is way too large, or "inch -> mm" if your model is way too small, to automatically scale by a factor of 25.4, or how many millimeters there are in an inch. 

As you scale, your model will move around. You can use the "On bed" and "Center" buttons to return the model to the middle of the view.

<p class = "clear-float"></p>

### Rotate

<img src="../assets/3dprinteros rotate.png" class="image-float-right" width=50%>

Once your model is scaled, the next most important thing is rotation. Rotation determines how well your print will turn out. You want to minimize overhangs and bridges, and have as much of a flat face as possible touching the build plate.

You can use the "Rotate" tool to move the part in the X, Y, and Z axes of rotation. You can type in a value, or click and drag the rotation arrows on your 3D model to rotate it.

Just like with scaling, you can hit "On bed" and "Center" to return the model to the center of the view. 

If you have a specific face or edge you want to be touching the bed, you can select it with the "Align Face to Bed" tool. Alternatively, you can have the system try to guess what face is best to have facing down with the "Optimal Rotate button". 

<p class = "clear-float"></p>

-----

<img src="../assets/3dprinteros analyze.png" class="image-float-left" width=15%>

Once you have rotated a model, you can check how much support material it will need with the "Analyze" button at the top. If you toggle the "Supports" option in the analyze menu, you will see red shadows on your model where support material is needed. Keep in mind anywhere you see red, there will be support material that will leave a potentially rough interface. 

<p class = "clear-float"></p>

!!! tip
    To give your print the best chance of success, you want to both minimize the need for support, and maximize how much of the print touches the bed of the machine. Try to orient your part to be as pyramid-like as possible - a large, flat, base that tapers up into the air. 

### Saving

Once you are happy with the scale and rotation of the part, it is recommended to hit "On bed" and "Center" one more time, then you can save it with the "Save" button. 

When you save changes in Layout, it does not overwrite the original file. Instead, the new STL will be put into a project folder with the old one. Multiple layouts will result in multiple files. 

## Slicing for Self-Serve

<img src="../assets/3dprinteros slicer.png" class="image-float-right" width=30%>

The following is only for self-serve 3D printers (PLA and PETG standard-size machines). If you are looking to print on [advanced 3D printers](/Atrium%20Makerspace/Advanced%203D%20Printing), go to [Submit STLs for Full-Serve](#submit-stls-for-full-serve) below.

Once your model is all set in Layout, you can move on to slicing. Slicing is the process of converting a 3D model into GCODE, the machine data that our 3D printers can understand. You can slice directly from Layout with the large "Slice" button in the top right, or hit the green "Slice" button next to the STL in your Projects tab.

!!! note
    If you used the Layout tool, make sure you select the proper STL for slicing! 

The first step in slicing is choosing the proper configurations from the top menu. 

* Select **Original Prusa CORE ONE** for printing in PLA.
* Select **Original Prusa MK4** for printing in PETG.

!!! note
    Printing for a class? You may be asked to select a different **Slciing Profile** that matches your class number, to bill the print to the department instead of you. See [No-Cost Class Printing](./Using%20Printers%20for%20Clubs,%20Classes.md#no-cost-class-printing-workflow) for more information!

We recommend printing with the default settings. If you are happy with these settings, hit "Slice" to create your GCODE file, and you can move on to [Submit GCODE for Self-Serve](#submit-gcode-for-self-serve) below. 

!!! danger
    Changing settings from their defaults is permitted, but you do so at your own risk! If your print fails due to modified settings, you may not be refunded, and you may be responsible for damage caused to the printers.

<p class = "clear-float"></p>

## Submit GCODE for Self-Serve

<img src="../assets/3dprinteros gcode preview.png" class="image-float-right" width=30%>

Before submitting your print, we recommend looking at the GCODE file. You can view a GCODE preview by clicking the "Preview" button in your Projects tab. 

In this view, you can see your 3D print as it will print on the printer, including support material. Check to make sure the support material is where you want and expect it to be. 

At the top of the screen, you can also see how much the print will cost, and how long it is estimated to take. 

Once you have reviewed your GCODE, you can move on to printing. Hit the yellow "Print" button next to the GCODE in your Projects tab to open the print dialog. 

<p class = "clear-float"></p>

-----

<img src="../assets/3dprinteros queue.png" class="image-float-left" width=40%>


You are now presented with a list of all self-serve print queues. If you see "There are no available Printers", you are probably missing a training! Check make.rit.edu or stop by the makerspace to talk with staff for assistance. 

!!! warning
    You will be shown *all* self-serve queues, not just ones that match your slicer settings. So if you sliced for PLA and send your GCODE to a PETG printer, the part will be rejected.

Queues are sorted by color and material. To make sure you are printing to the right queue, match the printer type at the top of the screen to the printer type listed on each queue. 

A queue time is next to each option, this is how long the prints ahead of you in queue are. Any option with no time means there is no queue and your print will start immediately.

If you do not care what color your print is, you can select "Any Color" to be routed to the next available color.

Once you choose a printer, hit "**Queue**" (not "Print"!) and answer any questions the system asks. Your print is now in queue to be printed! Keep an eye on your email for more information and to track progress. You can also see print process in the [Activity Page](#activity).

<p class = "clear-float"></p>

!!! note
    Once your print completes, you will receive an email telling you it is ready for pick up. Make sure you pick up your print within 4 business days, or it may be recycled! Self-Serve prints are picked up from the **General Makerspace** on the first floor of the SHED, when the space is open.

## Submit STLs for Full-Serve

<img src="../assets/3dprinteros full serve queue.png" class="image-float-right" width=20%>

!!! tip
    Have a lot of parts to submit? We also accept ZIP files of parts to make it easier to keep track of a large batch of prints!

For more advanced 3D printers, you submit an STL file instead of GCODE file. Once you have your STL scaled, you can submit your STL by hitting the "..." menu next to the file in your Project tab, then hit "Print" to see a list of available machines.

!!! warning
    You will also see the self-serve printers at this stage. Sending your STL to one of these will not result in it being printed. Make sure to choose a printer whose name starts with "Full Serve"

Select the material you want and hit the "**Queue**" button. Fill out the questions that follow to submit your print. Keep an eye on your email, staff will be in contact to confirm pricing and give an estimate lead time. 

When your print completes, it can be picked up from the **Atrium Makerspace** any time the space is open.

<p class = "clear-float"></p>
