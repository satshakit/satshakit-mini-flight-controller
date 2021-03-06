<h1 style="font-family: courier;" align="center"> satshakit mini flight controller</h1>
<p align="center">
<img src="media/board_first.jpg" width="70%">
<div align="center"><i>An open source & easy to make small flight controller board.</i></div>
</p>  

satshakit mini flight controller
--
satshakit mini flight controller is an **open source, MultiWii compatible, small flight controller board**, that is possibile to **make in a FabLab**. The design derives from **[satshakit fight controller](https://github.com/satshakit/satshakit-flight-controller)**.

Here you can find all of the satshakit boards: **[satshakit organization](https://github.com/satshakit)**.

Features
--

satshakit mini flight controller has been designed aiming to be **easy to make, program and use**, so to be possible to **replicate and customize it** in any other Fab Lab. It has the following features:

- support for [any drone configuration](http://www.multiwii.com/connecting-elements) up to **4 motors**
- support for up to **5 channels** receivers 
- costs about **8€**
- **16mhz crystal** for precise clock, reliability and compatibility
- embedded **power board**
- possibility to connect and use **any IMU working at 5V**
- size of 41x44mm

Due to the small dimensions and its light weight, is recommended to use satshakit mini flight controller in **small DIY drones having sizes between 100 and 200mm** such as the **[satshacopter 150X](https://github.com/satshacopter/satshacopter-150X)**.

<img src="media/board_milled.jpg" width="70%">
<img src="media/board_soldered.jpg" width="70%">

Getting started
--

After you finish to solder a satshakit mini flight controller board, you need to **set its fuses and to program it with MultiWii**. To set the fuses you can easily upload the Arduino Bootloader using Arduino IDE and an **Arduino as ISP**. To do so first upload the Arduino as ISP sketch into an Arduino, and then connect the satshakit flight controller as following (this is the same for the version with the power board and without):

<img src="media/satshakit_mini_fc_programming.png" width="70%">

Once everything is connected, follow these steps to upload Arduino bootloader:

1. open Arduino IDE
2. select proper programmer (for example Arduino as ISP or USBtinyISP)
3. select Arduino UNO as board
4. click on tools->Burn Bootloader

Now you can use again the same connections, Arduino as ISP and Arduino IDE  to **upload your favourite MultiWii** version, this time using **File->Upload using a programmer**.

To connect all the elements fo your drone, you can follow the **satshakit mini flight controller pinout**:

<img src="media/satshakit_mini_fc_pinout.png" width="70%">

Downloads
--

**downloads (right click, download as)**

- [satshakit mini flight controller sch](https://raw.githubusercontent.com/satshakit/satshakit-mini-flight-controller/master/eagle_projects/satshakit_mini_fc.sch)
- [satshakit mini flight controller brd](https://raw.githubusercontent.com/satshakit/satshakit-mini-flight-controller/master/eagle_projects/satshakit_mini_fc.brd)
- [satshakit mini flight controller internal](https://raw.githubusercontent.com/satshakit/satshakit-mini-flight-controller/master/media/satshakit_mini_fc_internal.png)
- [satshakit flight controller cut](https://raw.githubusercontent.com/satshakit/satshakit-mini-flight-controller/master/media/satshakit_mini_fc_cut.png)
- [satshakit mini flight controller BOM xlsx](https://raw.githubusercontent.com/satshakit/satshakit-mini-flight-controller/master/docs/satshakit_mini_fc_BOM.ods)
- [satshakit mini flight controller BOM ods](https://raw.githubusercontent.com/satshakit/satshakit-mini-flight-controller/master/docs/satshakit_mini_fc_BOM.xlsx)

What's in the repo
--

- **[docs](https://github.com/satshakit/satshakit-mini-flight-controller/tree/master/docs)**: BOM files for Farnell
- **[egle projects](https://github.com/satshakit/satshakit-mini-flight-controller/tree/master/eagle_projects)**: eagle projects of the satshakit flight controller
- **[media](https://github.com/satshakit/satshakit-mini-flight-controller/tree/master/media)**: svgs, connections schemas, images for cnc milling machine, other images

Authors
--

- Daniele Ingrassia


Contact
--

- **ingrassiada@gmail.com**
- **[linkedin](http://it.linkedin.com/in/danieleingrassia)**

Thanks
--

[Fablab Kamp-Lintfort](http://fablab.hochschule-rhein-waal.de/index.php/de/)<br />
Hochschule Rhein-Waal<br />
Friedrich-Heinrich-Allee 25, 47475 Kamp-Lintfort, Germany<br />
fablab@hochschule-rhein-waal.de


License
--
This work is licensed under the terms of the open source license: Creative Commons Attribution-ShareAlike 4.0 International ([CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)).

Disclaimer  
--

<div class="align-justify">
This hardware/software is provided "as is", and you use the hardware/software at your own risk. Under no circumstances shall any author be liable for direct, indirect, special, incidental, or consequential damages resulting from the use, misuse, or inability to use this hardware/software, even if the authors have been advised of the possibility of such damages.</div>

