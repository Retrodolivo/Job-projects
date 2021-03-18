# Job-projects
### Description

This repository contains some of my work as an engineer in [Russian Scientific Research Institute](https://www.vniiftri.ru/). My primary goal is to design a measuring device - **microwave wattmeter**.
 
 [**Microwave wattmeter**](https://drive.google.com/file/d/1DkEJPY_jXihFlMOo3NosO_gAjYZUhH1n/view?usp=sharing)
 It is a device which measure power of RF signal passing across waveguide to load.
 ![Wattmeter functional block scheme](img/wattmeter.jpg)
 * 1. *Converter*
 This consist of waveguide and sensor. Sensor is nothing but a thermistor, which located in waveguide. When measured signal passing through termistor the electromagnetic energy is converting to heat. This leads to  resistance changing of thermistor. 
  * 2. *Measurment unit*
 Its job is to calculate electromagnetic power according to the state of sensor. Measurment unit can be based on microcontroller, microprocessor system or PC itself.
 ### Submodules
 * Wattmeter-DAC
 
