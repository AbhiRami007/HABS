# HABS
Vehicle Headlight Automation and Brightness Control System

Existing System:
    The headlight of vehicle will turn on automatically when the vehicle is started.In the northern areas, due to high fog, the chance of accidents increased as the vehicle was invisible. So a rule was passed to make the headlight turned on automatically when vehicle is started. Also, there exist a system that dims the headlight brightness by sensing the intensity of light from the vehicle coming in the opposite direction. A drawback of this system is that it reduces the lifetime of headlight and also the headlight will go dim when light from a vehicle from opposite direction is sensed even in foggy or other areas where high beam light is required.
    
Proposed System:
    The existing system produces a lot of energy wastage by turning the lights on automatically even in the day time. So, a system is proposed that works by sensing the intensity of light in the environment. Using an LDR(Light Dependant Resistor) sensor, the intensity of light is sensed and when the intensity of light falls below a threshold, the headlight will turn on automatically(ie, during night) and when a vehicle with headlight turned on comes in opposite direction, the high beam light is turned off automatically to reduce glare to the driver of the approaching vehicle. Also a Humidity sensor is used which senses the humidity change hence turns on the light automatically during foggy or rainy climates and maintains a high beam. This helps in saving energy and also increases the lifetime of headlight bulbs. An Android application is also associated with the system that gives the status of environmental factors and the headlight by collecting data from the sensors and also notify when a failure occur in the system using IoT.
    
Hardware Requirements:
    1. Arduino Nano 
    2. Jumbo wires
    3. LDR sensor
    4. 5Volt Relay
    5. DHT11 Sensor
    6. Breadboard
    7. Level Shifter
    8. Raspberry Pi module
    9. Headlight unit

Software Requirements:
    Arduino UI


