#BeaconBuddy#

nRF52832 based beacon design

Simple reference design in a 1"x1.2" form factor with CR2032 battery holder.  For maximum battery life, ditch protection 
diode D2 and replace it with a FET (or just a jumper).  Tested to work with examples from the nRF52 SDK v11.0.0, but no
guarantees as to the effectiveness of the antenna.  

This design is related to the [nRF52Beacon] (https://github.com/angst7/nRF52beacon) project with the addition of A BMP280 Sensor for Pressure and temperature 
readings and an Si7020-A20 sensor for Humidity and temperature.  It also breaks out GPIO/AIn pin P0.02.


##License##

This work is licensed under [CC Attribution 3.0 United States](https://creativecommons.org/licenses/by/3.0/us/).