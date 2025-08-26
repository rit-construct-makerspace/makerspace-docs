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

**Dispose of the empty spool once unloaded.**