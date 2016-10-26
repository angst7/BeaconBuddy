#BeaconBuddy#

nRF52832 based beacon design

![alt text](BeaconBuddy.png?raw=true "BeaconBuddy rev.c")
Simple reference design in a 1"x1.2" form factor with CR2032 battery holder.  Rev. A Tested to work with examples from the nRF52 SDK v11.0.0, but no
guarantees as to the effectiveness of the antenna.  

This design is related to the [nRF52Beacon] (https://github.com/angst7/nRF52beacon) project with the addition of A BME280 Sensor for pressure, temperature, 
and humidity readings.  It also breaks out GPIO/AIn pin P0.02.

** Revision History ** 
- Rev. A is tested and working, please clone the rev_a branch for that version.
- 10/22/2016: Rev. B removed ST humidity sensor, replaced BMP280 with BME280, and replaced diode battery polarity protection with a FET.
- 10/23/2016: Rev. C adds a reset button, and second LED
- This is the Rev. C version.  It is not yet tested with real hardware, but should be fine.

##License##

This work is licensed under [CC Attribution 3.0 United States](https://creativecommons.org/licenses/by/3.0/us/).