#BeaconBuddy#

nRF52832 based beacon design

Simple reference design in a 1"x1.2" form factor with CR2032 battery holder.  Rev. A Tested to work with examples from the nRF52 SDK v11.0.0, but no
guarantees as to the effectiveness of the antenna.  

This design is related to the [nRF52Beacon] (https://github.com/angst7/nRF52beacon) project with the addition of A BME280 Sensor for pressure, temperature, 
and humidity readings.  It also breaks out GPIO/AIn pin P0.02.

**10/22/2016:** 
- This is the Rev. B version.  It is not yet tested with real hardware, but should be fine.
- Rev. A is tested and working, please clone the rev_a branch for that version.

##License##

This work is licensed under [CC Attribution 3.0 United States](https://creativecommons.org/licenses/by/3.0/us/).