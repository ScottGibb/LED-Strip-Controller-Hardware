# LED Strip Controller Hardware

<center>
    <!-- <img src="https://raw.githubusercontent.com/LEDStripController/LEDStripController/master/Hardware/LEDStripController.png" width="50%" height="50%"> -->
</center>

## Summary
 
This repository is concerned with the hardware design of the LED Strip Controller. The hardware design is split into two parts, the PCB and the enclosure. The PCB is designed in KiCad and the enclosure is designed using Fusion 360, the enclosure designs are stored in Thingiverse which is linked below.

As for the PCB designs, the designs are all done in KiCad and come in multiple flavours depending on the requirements of the project. The idea behind this is to allow for the PCB to be used in multiple projects without having to redesign the PCB. The PCBs are designed to be as small as possible and are designed to be used with the ESP based System on Chips or the STM32 based Microcontrollers. Within each design there tends to be a module based PCB using off the shelf components that are plug and play and a component based PCB.

# Repository Structure

As for the repository, it tends to follow the convention of splitting into microcontroller based designs and then into the different designs. The microcontroller based designs are split into ESP based designs and STM32 based designs. Within each of these folders the design is targeted at a specific application. At this point the application will usually follow a Components Based Design, a Veroboard Based Design and a Module based Design. Allowing maximum flexibility for the user.

# Useful Links

- [Thingiverse](https://www.thingiverse.com/scottgibb/designs)