# Keithley DMM6500

<div class="grid" markdown>

[Multimeter User's Manual](..//assets/dmm6500/DMM6500-900-01B_User_Aug_2019.pdf){target="blank" .md-button}

[Keithley DMM6500 Relevant Documentation](https://www.tek.com/en/products/keithley/digital-multimeter/dmm6500){:target="_blank" .md-button}

</div>

---

## Use Case

<img src="../assets/dmm6500/dmm6500.webp" class="image-float-right" width=40%>
A multimeter allows the user to measure electrical properties of components and circuit points. Examples of these measurements include:

* Direct Current (DC) voltage and current

* Alternating Current (AC) voltage and current

* Resistance

* Capacitance

* Diode voltage drop

* Continuity

* Frequency

* etc.

<p class = "clear-float"></p>

## Quick Guide

### Probes
<img src="../assets/dmm6500/probes_2.webp" class="image-float-right" width=30%>
<img src="../assets/dmm6500/probes_1.webp" class="image-float-right" width=30%>

* The probes in this space have modular tips which can be exchanged for alligator clips or thinner probes

* To use most features which require a high impedance input (voltage, resistance, diode, capacitor, etc.), plug the probes into the colored ports under Input

* To measure current, which requires a low impedance input, plug the red probe into the white port instead

* The Sense 4 Wire ports are used for advanced 4-wire resistance measurements and for the ratio feature. This is unnecessary in most applications.

<p class = "clear-float"></p>

### Basic Measurement Functions
<img src="../assets/dmm6500/measurement.webp" class="image-float-right" width=40%>

* DCV: DC Voltage [Volts]

* ACV: AC Voltage [Volts RMS]

* DCI: DC Current [Amps]

    * (Put the red probe in the white port for this)

* ACI: AC Current [Amps RMS]

    * (Put the red probe in the white port for this)

* 2W Ω: 2-Wire Resistance [Ohms (Ω)]

    * (Use this for measuring resistance generally)

* 4W Ω: 4-Wire resistance [Ohms (Ω)]

    * Useful for measuring low resistances very precisely. This prevents the resistance of the probes from interfering with your measurement.

* Cont: Continuity Check. Produces an audible tone if there is a continuous, low impedance circuit between the probes.

    * Useful for testing if a wire is broken or if a solder connection is properly made

* Freq: Frequency [Hz]

* Period: Period of a periodic signal (inverse of frequency) [seconds]

* Cap: Capacitance [Farads]

* Diode: Diode forward voltage drop [Volts]

* Ratio: Gives the ratio between voltage measured on the input probes and voltage measured on the Sense 4 Wire probes [V/V]

    * This is useful for measuring amplifier gain directly

* Temp: Temperature

* Must use a temperature probe specifically. The probe type can be set in the settings tab (swipe left on the screen

<p class = "clear-float"></p>

### Menu

<img src="../assets/dmm6500/menu.webp" class="image-float-right" width=30%>

Pressing the Menu button from any screen will bring you to the screen shown.

<p class = "clear-float"></p>

### Graph

<img src="../assets/dmm6500/graph.webp" class="image-float-right" width=30%>

From the menu, you can enter the Graph app

* The window size will auto scale by default

* The sampling rate is 1M samples/s

    * The Tektronix oscilloscopes have a sampling rate of 2G samples/s (2,000 times higher sampling rate)

* The figure shows a measurement of a Keithley benchtop power supply set to 3.00V

<p class = "clear-float"></p>
 
## Tips

* Use the Help button to the left of the display while a button on the screen is selected to get more information about it.

* For more advanced features, ask makerspace staff or view Keithley's documentation linked at the top of this page.