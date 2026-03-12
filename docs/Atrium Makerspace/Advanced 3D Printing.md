# Advanced 3D Printing

The Atrium makerspace is home to more advanced 3D printers. All 3D printers can be accessed through 3DPrinterOS. Learn how to use 3DPrinterOS at the link below.

[How to use 3DPrinterOS](../​​Resources%20&%20Workshops/3D%20Printing/Intro%20to%203DPrinterOS.md){.md-button}

## BigRep Large-Format 3D Printer

<img src="../assets/bigrep hero shot.jpg" class="image-float-right" width=30%>

The BigRep is the largest 3D printer in the SHED makerspace, capable of making parts up to 1 meter (36 inches) cubed! This machine is ideal for making large, low-fidelity plastic parts like furniture, molds, and aesthetic pieces. It is the same process as a normal FDM 3D printer, just scaled up a bunch. This does mean that you will have to deal with support material, layer lines, etc. like a normal 3D print. 

Support on a BigRep print is very strong and hard to remove, so try to design with as little support needed as possible! 

We generally stock PLA and PETG for the BigRep, other materials available on special order. 

<p class = "clear-float"></p>

## Formlabs SLA Resin 3D Printers

<img src="../assets/formlabs hero shot.webp" class="image-float-right" width=30%>

SLA (aka resin) printing is a process where a laser is fired into a vat of photopolymer to cure it, making incredibly intricate, detailed, and strong parts. It is commonly used for small aesthetic pieces like jewelry, board game pieces like DnD minis, or injection molding-like end-use parts.

In addition to being much more detailed, resin printing enables more complex materials compared to traditional FDM printing. Even the default grey/clear resins have superior mechanical properties to PLA and PETG. 

We offer the following resins;

* Grey, the standard choice., Grey has excellent surface finishes ideal for use as-is, or makes for a great painting base. Learn more in the [Grey Resin Technical Datasheet](https://dental-media.formlabs.com/datasheets/2401898-TDS-ENUS-0.pdf){target="_blank"}. 
* Clear, a translucent material. With enough post-processing, parts can achieve optical clarity good enough for use as lenses. [Formlabs 3D printed an entire camera!](https://formlabs.com/blog/creating-camera-lenses-with-stereolithography/?srsltid=AfmBOopQjqos9XTYXpmZd8jwl_8K6Aq0E8BSQi3ZL2aeEb8M2hWIGM4o){target="_blank"}. Learn more in the [Clear Resin Technical Datasheet](https://formlabs-media.formlabs.com/datasheets/2401900-TDS-ENUS-0.pdf){target="_blank"}.
* High Temp, a material optimized for its thermal resistance. It has a thermal deflection temperature of 238 degrees Celsius at 0.45 MPa. This can easily handle boiling liquids, be used in high-temperature environments like ovens, or even be used for short-run injection molding plates. Learn more in the [High Temp Resin Technical Datasheet](https://formlabs-media.formlabs.com/datasheets/High_Temp_Technical.pdf){target="_blank"}. 
* Tough 1500, a polypropylene-like material that has a high work of fracture, extremely high elongation at break, and excellent thermal and UV resistance. It is a great material for rugged enclosures, jigs, fixtures, and compliant mechanisms. Learn more in the [Tough 1500 Resin Technical Datasheet](https://formlabs-media.formlabs.com/datasheets/Tough_1500_TDS_EN.pdf){target="_blank"}. 
* Elastic 50A (available on special request) is an extremely flexible material, roughly equivalent to a rubber band. This is great for making compliant parts, flexible wearables, gaskets, and more. It does require special care in part design though, since the material is barely sturdy enough to support itself while printing. Learn more in the [Elastic 50A Resin Technical Datasheet](https://formlabs-media.formlabs.com/datasheets/2001420-TDS-ENUS-0.pdf){target="_blank"}.

Other resins are available on special request with a minimum job size.

There are 2 major downsides to resin printing to keep in mind;

1. All models need supports, and a lot of them. Resin prints are very delicate as they are printed, so they are surrounded in an extensive support structure that needs to be manually removed after printing. 
2. Resin prints are solid. Since resin starts as a liquid, you can't have infill like a normal FDM 3D print, or it will trap liquid resin inside. Models must be printed 100% solid, increasing print time and cost. Larger models can be hollowed, but care must be taken to ensure there are enough large drain holes to get all liquid material out of them. 

<p class = "clear-float"></p>

## Formlabs SLS Nylon 3D Printer

<img src="../assets/sls hero shot.jpeg" class="image-float-right" width=30%>

SLS is the newest printing technology added to the SHED makerspace. Raw material (nylon) powder is deposited in a thin layer, and then selectively melted with a laser to form the shape of the part. When the print is completed, unused powder is brushed off to reveal the part. This means that you don't pay for or have to deal with support material. In addition, parts come out with a consistent, aesthetically pleasing sandy finish. 

The biggest advantage to SLS printing is that the finished print is *isotropic*, or consistent in all direction. This means that SLS printed parts can be evaluated computationally through FEA or similar methods to verify mechanical performance, rather than needing to be tested to failure like a traditional FDM print.

The SHED's SLS printer runs Nylon 11, learn more in the [Nylon 11 Powder Technical Datasheet](https://formlabs-media.formlabs.com/datasheets/2101560-TDS-ENUS-0.pdf){target="_blank"}.

Designing for SLS requires some specific consideration, please read the [Fuse Series SLS Design Guide](https://formlabs.com/white-papers/fuse-series-sls-design-guide){target="_blank"} for more information. 

<p class = "clear-float"></p>

## Markforged High-Strength 3D Printer

<img src="../assets/markfroged hero shot.png" class="image-float-right" width=30%>

The Markforged 3D printer is an FDM machine optimized for load-bearing parts. The machine prints with a nylon base material, and then can inject continuous strands of carbon fiber or Kevlar into the material to optimize its mechanical properties. If leveraged properly, this enables 3D printed parts to replace aluminum parts.

Printing with the Markforged machine requires a lot of consultation and file preparation, we suggest reaching out to make@rit.edu to schedule a time to work with staff on preparing your file.

<p class = "clear-float"></p>