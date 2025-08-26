This page details how to process incoming 3D prints in the self-serve print queues of the 1st floor General Makerspace.

First, it is recommended to familiarize yourself with what makers see when they send in a print. Check out [this page](../3D%20Printing/Intro%20to%203DPrinterOS.md) for more info.

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

Once the print bed is clear, re-install it by sliding it along the surface of the magnets, until it hits the hard stops in both back corners. 

<img src="..\assets\core one bed install.jpeg" class="image-float-right" width=100%>

<p class = "clear-float"></p>

After installing the print bed, you can hit the "Print bed is clear" toggle to mark the printer as ready to go.

!!! tip
    You can hit the toggle on a printer that is clear to mark it as not clear. This will stop prints from being sent to it from the queue.