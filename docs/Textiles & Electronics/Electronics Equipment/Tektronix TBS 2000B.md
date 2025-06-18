# Tektronix TBS 2000B

<div class="grid" markdown>

[Oscilloscope User's Manual](../assets/tbs2000/TBS2000BSeriesUserManual.pdf){target="blank" .md-button}

[Tektronix Relevant Documentation](https://www.tek.com/en/support/datasheets-manuals-software-downloads?series=TBS2000B%20Digital%20Storage%20Oscilloscope){:target="_blank" .md-button}

</div>

---

## Use Case

<img src="../assets/tbs2000/scope.webp" class="image-float-left" width=40%>
Oscilloscopes (commonly referred to as “scopes”) allow the user to measure and visualize electric voltage signals over time. Use case examples include:

* Analyze the output of an analog circuit

    * Is the amplitude, frequency, shape, etc. as expected?

    * Does this circuit output respond correctly to a given input?

* Test microcontroller timing and responses by probing I/O pins

* Measure and view frequency content of a signal through FFT (Fast Fourier Transform)

* Verify the output of a function generator

<p class = "clear-float"></p>

## Quick Guide

<img src="../assets/tbs2000/guide.png" class="image-float-left" width=30%>

The next section will walk you through how to use an oscilloscope. For help with more advanced features, refer to the Tektronix documentation linked above or ask makerspace staff.

<p class = "clear-float"></p>

### Channels
<img src="../assets/tbs2000/channels.webp" class="image-float-right" width=40%>

* On the bottom section of the control panel, there are four BNC connectors. This is where you will connect your probes. The number and color above the connector indicate the channel number and the display color for the signal measured by that probe.

* Plug the probe's connector into the scope by inserting the connector with the studs aligned and twisting the connector clockwise to secure it.

<p class = "clear-float"></p>

### Vertical (Voltage Scale)

<img src="../assets/tbs2000/vertical.webp" class="image-float-right" width=30%>

* The vertical section allows you to adjust the voltage scale of each your signals.

* The smaller dials labeled position shift where 0V is displayed for each channel, as indicated by the arrows to the left of the display.

* The larger dials labeled scale control the voltage difference between vertical divisions on the display.

    * This scale value is indicated on the bottom left corner of the display (in the figure: channel 1 is set to 100mV/division).

* To enable or disable a channel, press the numbered button associated with that channel twice.

<p class = "clear-float"></p>

### Trigger (When to start recording)

<img src="../assets/tbs2000/trigger.webp" class="image-float-right" width=15%>

* The trigger section allows you to control when the scope starts displaying the measured signal. This is typically when the signal reaches a threshold voltage called the trigger level.

    * The scope will display the signal immediately before and after this trigger occurs.

    * The trigger is only applied to one channel of the user's choice.

* The level dial controls the trigger level, indicated by the arrow on the right side of the display.

* The menu button allows you to set specific properties of the trigger such as the source channel, trigger type, and edge type

    * Auto continuously triggers, whereas normal only triggers when the set trigger criteria are met.

* The value of the trigger level is indicated on the bottom right corner of the display (in the figure: the trigger is sourced from channel 1, and it occurs when the signal goes from a value below 308mV to a value higher than 308mV, AKA a rising edge at 308mV).

<p class = "clear-float"></p>
 
### Horizontal (Time scale)

<img src="../assets/tbs2000/horizontal.webp" class="image-float-right" width=15%>

* The horizontal section allows you to adjust the time scale of all of your signals (not individually).

* The smaller dial labeled position shifts the point on the display that represents time = 0 seconds. This is the point where a trigger occurs, indicated by the arrow on the top of the display.

* The larger dial labeled scale controls the time difference between horizontal division marks.

    * This scale value is indicated in the bottom center box of the display (in the figure: the time scale is set to 10.0μs/division).

<p class = "clear-float"></p>

### Navigation

<img src="../assets/tbs2000/navigation.webp" class="image-float-right" width=30%>

* The trigger section allows you to control when the scope starts displaying the measured signal. This is typically when the signal reaches a threshold voltage called the trigger level.

    * The scope will display the signal immediately before and after this trigger occurs.

    * The trigger is only applied to one channel of the user's choice.

* The level dial controls the trigger level, indicated by the arrow on the right side of the display.

* The menu button allows you to set specific properties of the trigger such as the source channel, trigger type, and edge type

    * Auto continuously triggers, whereas normal only triggers when the set trigger criteria are met.

* The value of the trigger level is indicated on the bottom right corner of the display (in the figure: the trigger is sourced from channel 1, and it occurs when the signal goes from a value below 308mV to a value higher than 308mV, AKA a rising edge at 308mV).

<p class = "clear-float"></p>

## Other Useful Features

<img src="../assets/tbs2000/panel.webp" class="image-float-right" width=40%>

* Press Autoset at the top of the control panel to have the scope automatically adjust its settings for the measured signals on each channel.

* Use the Help button for more information about each control and feature of the scope.

* Use the Measure button to add automatically calculated measurements to the display.

    * The frequency and duty cycle measurements in the figure come from this feature.

* Use the FFT button to show the frequency content of the signal.

The best way to learn this tool is to keep adjusting the settings and pressing buttons!

<p class = "clear-float"></p>
