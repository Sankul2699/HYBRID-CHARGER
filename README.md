# Hybrid Charger

The hybrid solar charger  is the next version of the available solar charger it can charge a battery using both solar power
as well as AC mains supply and ensure the continuous supply of power.

Solar panels generate the most electricity on clear days with abundant sunshine. Commonly, the solar panel gets four to five hours of bright sunlight in a day. If the weather is cloudy, it affects the battery charging process and the battery does not get a full charge.
## Repository Contents
- **simulation** - Contains simulation (solar hybrid charger) in multisim which is available to download
- **images** - Images of the circuit and simulation 
- **presentation** - (Power point presentation) Get to know more about the project
- **schematics** - Contains  circuit diagrams implemented

## Using the simulation

The simulation can be downloaded from the simulation folder.Once downloaded open it using multisim. 
The solar power supply is represented as dc power in left most part of the cicuit. XMM1 (voltmeter) is the place where battery must be placed  inorder to get charged.Voltage available can be checked using XMM1 in v. 
There are two leds green and red.
The RED led indicates the battery getting charged.
The GREEN led indicates that solar power is being used to charge the battery.
That means  RED led ON ,GREEN LED OFF indicates it being charged using the ac power supply. 

- When Solar supply is sufficient that means the dc power is set above 11V.(GREEN,RED LED ON)

![](https://github.com/Sankul2699/HYBRID-CHARGER/blob/master/images/sim%20green.PNG)


- When solar supply not sufficient that means dc power is set less than 10V.(RED LED ON,GREEN LED OFF)

![](https://github.com/Sankul2699/HYBRID-CHARGER/blob/master/images/sim%20green%20red.PNG)
