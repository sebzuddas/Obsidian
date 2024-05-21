# The Bike
## Bike Mechanics
1. The bike shall facilitate the use of sensors via a separately contained compartment.
	1. The compartment shall be easily removable.
	2. The compartment shall be sealable.
		1. The compartment shall be waterproof.
		2. The compartment shall be shockproof.
		3. The compartment shall be dustproof.
	3. The compartment shall be resistant to vibrations. 
		1. The compartment shall have a dampening capacity for vibrations in the [30Hz to 50Hz](http://web.mit.edu/2.tha/www/ppt/Bike-ISEA.pdf) range.
		2. 
2. 

## Bike Electronics
1. The compartment shall be rechargeable via a USB C cable.
2. The compartment shall use buttons for basic user interactivity. 
	1. One button shall be used to turn the module on and off.
	2. One button shall be used to reset the circuitry. 
3. The compartment shall make use of simple LEDs.
	1. The green LED shall indicate nominal sensor function. 
	2. The red LED shall indicate errors and issues. 
	3. Both LEDs shall be switched off whilst cycling. 
4. The compartment shall be compatible for recharging via a solar panel.
	1. *The solar panel shall* 
	2. The compartment shall contain an internal Li-Po battery.
		1. The Li-Po battery shall contain a charge controller capable of handling a 60W charging input. 
		2. The Li-Po battery shall have enough capacity to last for at least 48 hours.
5. The compartment shall be compatible for recharging via European mains electricity. 
	1. The 
6. The electronics shall utilise appropriate battery management. 
	1. The electronics shall engage in a 'sleep mode' after activity ceases. 
	2. The electronics shall engage an 'active mode' when activity is detected. 
		1. Activity shall be detected via the accelerometers. 
		2. 
7. The bike shall utilise sensors to measure the environment.
	1. The environmental sensors shall capture temperature data. 
	2. The environmental sensors shall capture pressure data. 
	3. 
8. The bike shall utilise sensors to measure the bike. 
	1. The bike sensors shall collect acceleration data. 
		1. The accelerometer shall collect stability data. 
		2. The accelerometer shall collect acceleration data. 
	2. The bike sensors shall 


## Bike Software
1. The bike shall use a Raspberry Pi 4 (RasPi 4) for data handling and processing.
	1. The RasPi 4 shall interface with sensors using C++.
		1. The sensors shall be interfaced with the RasPi 4 via an integrated circuit board. 
	2. The RasPi 4 shall preprocess sensor data using C++.
	3. The RasPi 4 shall store sensor data.
		1. RasPi 4 sensor data shall be stored on an [SQLite](https://www.sqlite.org/whentouse.html) database.
			1. SQLite shall store 48 hours of sensor data. **consider data rate**
			2. SQLite database shall be wiped each time it is uploaded.
		2. Data shall be uploaded via 4G and WiFi.


# The Human
1. The human shall use a smartwatch to collect human performance data. 
	1. Human performance data shall be collected via [[Strava API]].
2. The human performance data shall be accessed via [[Strava API]].

# The Drone
1. 


# Intermediate Systems
1. 


# Remote Systems
