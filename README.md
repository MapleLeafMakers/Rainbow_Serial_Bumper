# Rainbow Serial Bumper

Just a little bit of extra bling for your [Voron Trident](https://github.com/VoronDesign/Voron-Trident)

![Bling](./Images/tridentbling.gif)



## Bill of Materials

| Component                       | Qty   | Note                                                   |
|---------------------------------|-------|--------------------------------------------------------| 
| M3x8 SHCS                       |  2    | for mounting                                           |
| 2020 M3 T-Nut                   |  2    | for mounting                                           |
| 10mm High Density RGB COB Strip |  50mm | https://www.aliexpress.com/item/1005005486743999.html  |


## Printing
<details>
<summary><b>[a]_main_body.stl</b> <i>(expand for details)</i></summary>

Print in your accent color of choice. Darker colors do a better job of preventing the light from bleeding through, using a high infill percentage can also help.

This part is already oriented correctly for printing and requires no slicer supports.

![Main Body Slicer](Images/[a]_main_body_slicer.png)


After printing remove the support piece.

![Main Body Support Removal](Images/[a]_main_body.gif)
</details>

<details>
<summary><b>[o]_insert_collar.stl</b> <i>(expand for details)</i></summary>

Print in black or another dark color.

This part is already oriented correctly for printing and requires no slicer supports.

![Insert Collar Slicer](Images/[o]_insert_collar_slicer.png)

After printing remove the support pieces.

![Insert Collar Support Removal](Images/[o]_insert_collar.gif)
</details>

<details>
<summary><b>[o]_back_plate.stl</b>  <i>(expand for details)</i></summary>

Print in black or another dark color.

This part is already oriented correctly for printing and requires no slicer supports.

![Back Plate Slicer](Images/[o]_back_plate_slicer.png)
</details>


<details>
<summary><b>[oc]_insert.stl</b>  <i>(expand for <b>important</b> details)</i></summary>

### Step 1 - Adding the text

Engrave the text **1mm** into the surface of the part.  Orca Slicer is shown below, but the process should be similar in other slicers.

The recommended font is [Play Bold](https://fonts.google.com/specimen/Play) (aka "The Voron Font") 

![Insert Step 1-1](Images/[oc]_insert_slicer_1.png)

![Insert Step 1-2](Images/[oc]_insert_slicer_2.png)

![Insert Step 1-3](Images/[oc]_insert_slicer_3.png)

### Step 2 - Preparing to print

This is where the magic happens.  You'll need a black/dark filament, and a clear filament that will stick to eachother.  I used black and clear polymaker PETG.

**Flip the part over 180 degrees.**

![Insert Step 2-1](Images/[oc]_insert_slicer_4.png)

**Slicer Settings**

For best results:
 - 1 perimeter
 - 0 top & bottom laters
 - 100% Aligned Rectilinear infill

Slice the part, and insert a pause *after* 1mm, this is where you will switch from dark to clear filament.

![Insert Step 2-2](Images/[oc]_insert_slicer_5.png)


</details>


## Assembly

**Press the Insert into the Main Body, and then press the collar in the gap.**

![Assembly Step 1](Images/assembly_1.gif)

**Solder the LED wiring, and insert the LED strip, followed by the back plate.**

![Assembly Step 2](Images/assembly_2.gif)

## Installation

Install on the front bed extrusion of your Voron Trident, or anywhere else you think it would look cool.

![Installation](Images/install.gif)

--

**The latest version of this mod can always be found on [GitHub](https://github.com/MapleLeafMakers/Rainbow_Serial_Bumper)**
