# MicroBlocks-SCD30
Library and example code to run the [environmental sensor SCD30](https://www.sensirion.com/en/environmental-sensors/carbon-dioxide-sensors/carbon-dioxide-sensors-scd30/) from within [MicroBlocks](https://microblocks.fun). 

*Now high school students can build quality CO<sub>2</sub> monitoring solutions to reduce Covid risk within the interactive and visual programming environment MicroBlocks (think Scratch for IoT) for many different embedded devices.* 

## SCD30
The SCD30 is an environmental sensor to measure CO<sub>2</sub> in ppm, temperature in °C, and humidity in %.

### Technology
It is a [nondispersive infrared sensor](https://en.wikipedia.org/wiki/Nondispersive_infrared_sensor), short an "NDIR sensor".
NDIR seonsors are spectography-type sensors targeted towards gas molecules, in this case towards CO<sub>2</sub>. They deliver more accurate results than cheaper [MOS](https://en.wikipedia.org/wiki/Carbon_dioxide_sensor) sensors like the [SGP30](https://www.sensirion.com/en/environmental-sensors/gas-sensors/sgp30/) targeting CO<sub>2</sub> equivalent gases like H<sub>2</sub>. The SCD30 sensor has an accuracy of 3% whereas SGP30 only achieves 15%. NDIR sensors are -- unlike MOS based sensors  -- independent of chemical reactions and hence do not have to be recalibrated in the long run. They are a bit more expensive though.

## Context
The corona epidemic is hitting students hard: They risk isolation at home and infection in the class rooms. One puzzle piece to mitigate the risk is to install CO<sub>2</sub> monitors in the class rooms. There are good commercial solutions available -- and hopefully installed by now in many schools. Still, this problem domain should be a good motivation for both teachers and students to delve into MINT and build their own CO<sub>2</sub> appliances using affordable IoT devices like micro:bit, Calliope mini, the AdaFruit Circuit Playground Express, or some ESP32 device. They might even use it and avoid some infections by getting reminded to open the windows when needed.

Here are a few beginner friendly block based platforms which one coud use for programming the SCD30 together with the respective library:

|Platform / Enduser Name|Organisation|Backend Language|SCD30 driver|
| --- | --- | --- | --- | 
|[Vittascience](https://en.vittascience.com)|French Ministry of Education|[MicroPyton](https://micropython.org)|[SCD30](https://github.com/vittascience/microbit-libraries/blob/master/scd30.py)|
|[MakeCode](https://www.microsoft.com/en-us/makecode)|Microsoft|Python/JavaScript|[SCD30](https://github.com/calliope-mini/pxt-SCD30)|
|[MicroBlocks](https://microblocks.fun)|(diverse/non profit)|[gp](https://gpblocks.org/about/)|[SCD30](https://github.com/MarkusGaelli/MicroBlocks-SCD30/blob/main/scd30.ubl)|

Only Microblocks lets you interact directly with the blocks, in the other platforms you need to upload them first.

## Example




