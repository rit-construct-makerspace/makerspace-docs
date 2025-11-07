This page details how to manage the machines and process incoming 3D prints for the self-serve print queues of the 1st floor General Makerspace and the Atrium Makerspace.

First, it is recommended to familiarize yourself with what makers see when they send in a print. Check out [this page](../3D%20Printing/Intro%20to%203DPrinterOS.md) for more info.

For more details on the Core ONE 3D printer, check out the [3D Printer Handbook](https://www.prusa3d.com/downloads/manual/prusa3d_manual_coreone_101_en.pdf), also available in print copies in the makerspace.

## Queues and Bed Clearing

When a print is submitted to a queue, the queue constantly looks for an open, compatible machine. If one is found, and the machine is marked as ready-to-print, the print will immediately start. If a printer is viable for multiple queues (for instance, a printer with orange PLA that has prints in the Orange and Any Color queues), the oldest print will be printed first. 

Once a print is started, the bed of the printer is marked as not clear. It will remain in this state until intervention from staff. If power is lost to the computer that runs the 3D printers, all beds will come back marked as not clear as well. 

Idle printers that are not clear will be designated with a **RED** icon in 3DPrinterOS. 

<img src="..\assets\bed not clear.png" class="image-float-right" width=100%>

<p class = "clear-float"></p>

To mark a bed as clear, first we need to actually clear the bed.

The beds of the printers in the SHED are magnetic. To remove the bed, lift up and forwards on it to separate it from the machine. You can then slide it forward and off of the magnets that hold it. 

!!! danger
    The bed will be hot once the print has finished, **especially PETG printers!** Give the bed time to cool down until it reports 30C or lower in 3DPrinterOS. Not only will this prevent injury, but it makes the prints **easier to remove.**

Remove the prints from the bed with a scraper, or for large parts, you can slightly bend the build plate to release the parts. Do not bend too far or it will damage the bed! Be sure to also remove any prime or excess plastic on the bed, as well as any plastic debris inside the printer.

Place the completed print into today's finished prints bin. Atrium finished prints for self-serve PETG should also be brought upstairs to the 1st floor for pickup.

Once the print bed is clear, re-install it by sliding it along the surface of the magnets, until it hits the hard stops in both back corners. 

<img src="..\assets\core one bed install.jpeg" class="image-float-right" width=100%>

<p class = "clear-float"></p>

After installing the print bed, you can hit the "Print bed is clear" toggle to mark the printer as ready to go.

!!! tip
    You can hit the toggle on a printer that is clear to mark it as not clear. This will stop prints from being sent to it from the queue.

## Loading and Reloading Filament

All printers in the SHED are equipped with filament runout detectors, so there is no need to preemptively replace near-empty filament spools. Filament can be loaded and unloaded via the "Filament" tab on the home page. If filament runs out mid-print, the screen will prompt you to load more. The following instructions will assist you with this;

1. Prepare a spool of filament, place it on the spoolholder on the side of the printer with the filament coming up from the spool. Once it is loaded, unsecure the end of the material (held down with tape on new spools) carefully to avoid tangling.
2. Cut the filament to a sharp point and push it through the PTFE tube all the way to the Nextruder. Once it reaches the filament sensor in the print head, the loading process will begin automatically.
3. When the Preheat menu appears, select the filament material and wait for the nozzle to reach the desired temperature. Once it heats up fully, it will push out a bit of material from the nozzle.
4. The printer will ask if the color of the extruded filament is okay. Check if there is filament extruded from the nozzle, and select one of the options:

For the Prusa Mk4, the only difference is you bring the filament down from the top of the machine and into the head.

<img src="..\assets\prusa load filament.png" class="image-float-right" width=100%>

<p class = "clear-float"></p>

!!! Note
    **Dispose of the empty spool once unloaded.**

## Restarting Prints

<img src="..\assets\icons.png" class="image-float-left" width=10%>

On 3DPrinterOS, there are 3 different status icons for a completed job:

1. Completed (Green): A job has finished to 100% of the gcode
2. Aborted (Purple): A job was closed from the browser of 3DPrinterOS by the user or by staff
3. Failed (Red): An issue arose with the printer, or the job was stopped / reset at the printer

Failed and Aborted jobs can have notes attached to them. Both Failed and Aborted jobs should issue a refund automatically. Jobs that have failed due to mechanical issues of the machine (filament runout, snags, layer shifts, etc.) can be restarted from the activity page. Jobs that have failed due to slicing issues or going outside of the default settings (removing a brim, removing support, poor orientation) should be resliced by the user and not attempted to be re-printed, as it may just result in failure again.

<p class = "clear-float"></p>

<img src="..\assets\finding_prints.png" class="image-float-left" width=60%>

You can search for the prints on the Activity page using the search bar to look for: the printer name, the printer material type and color, or a given student's email. This should default to ordering by most recent.

<p class = "clear-float"></p>

<img src="..\assets\restarting_prints.png" class="image-float-left" width=40%>

To restart a print, you can click the 3 dots on any completed job (completed, failed, aborted) to restart. Place it into the AutoQueue of the same material type and color from which it had been printed on. Restarting a print will **NOT** apply a cost to it, so the user won't be billed.

<p class = "clear-float"></p>

## Identifying Failures

<img src="..\assets\issue_1.png" class="image-float-left" width=10%>

**What do we see here?**

1. Tall aspect ratio (small base to tall part)
2. Brim (should help with bed adhesion)
3. Layer orientation might impact design

This part should be cancelled with a note to considering reorienting the part. Cancelling a print will count as an aborted print, issuing a refund. This part did in fact fail due to the limited cross section on the bed versus the height.

<p class = "clear-float"></p>

<img src="..\assets\issue_2.png" class="image-float-left" width=30%>

**What do we see here?**

1. Small aspect ratio (large base and small height)
2. Large support density to a flat plate
3. Lots of wasted material in supports
4. Print extends to almost the machine limits

Supporting up to a large cross section can increase risk of failure. As the bridging occurs to this surface, it can sag, or wrinkle, causing interactions with the nozzle. As materials cool, they tend to shrink towards the center, which can cause warping. On large flat plates, we want to maximize bed adhesion and add a brim. While this may impact aesthetics, it would be less prone to failure by being inverted.

<p class = "clear-float"></p>

<img src="..\assets\issue_3.png" class="image-float-left" width=20%>

**What do we see here?**

1. Tall aspect ratio (small base to tall height, but not as bad as example 1)
2. Large support density to a flat plate
3. This orientation appears chosen due to the size of the geometry fitting in the Z height of the machine
4. Print extends to almost the machine limits

This part did end up failing at least once or twice, due to the supports being damaged or collided with the nozzle. Supports are typically a hollow structure that doesn't have a lot of rigidity. The smaller it becomes, the more prone it is to snapping at a lower point. Once the support has failed, the print can no longer successfully complete. This print should've been sent to the larger Prusa XL print queue and oriented flat against the bed. 

<p class = "clear-float"></p>
