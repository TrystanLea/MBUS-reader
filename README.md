# M-Bus reader
to go with [emonTX](https://github.com/openenergymonitor/emontx3)

Part of [OpenEnergyMonitor.org](https://openenergymonitor.org) project.

This board allows you to read data from M-bus module in the heat meter. 

The Meter-Bus(M-Bus) is a low cost bus system for remote reading and powering utility meters. It is also the European Standard. 

Circuit diagram used is from [here](https://github.com/rscada/libmbus/tree/master/hardware).
![mbus_levelshifter](https://user-images.githubusercontent.com/29893671/29127304-9c790700-7d18-11e7-85f9-27eb9a11ae67.png)

The 34V is provided to the circuit through a [DC to DC voltage step up boost converter](http://www.ebay.co.uk/itm/XL6009-DC-DC-Voltage-Step-Up-Boost-Converter-replace-LM2577-3-32v-input-UK-Fast-/400858208676). 
