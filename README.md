# HABS
Vehicle Headlight Automation and Brightness Control System

Existing System:
    The headlight of vehicle will turn on automatically when the vehicle is started.In the northern areas, due to high fog, the chance of accidents increased as the vehicle was invisible. So a rule was passed to make the headlight turned on automatically when vehicle is started. Also, there exist a system that dims the headlight brightness by sensing the intensity of light from the vehicle coming in the opposite direction. A drawback of this is that if two vehicle with the system will not work properly and when they come opposite each other, the headlight brightness turns dim and bright sequentially.
    
Proposed System:
    The existing system produces a lot of energy wastage by turning the lights on automatically even in the day time. So, a system is proposed that works by sensing the intensity of light in the environment. Using an LDR(Light Dependant Resistor) sensor, the intensity of light is sensed and when the intensity of light falls below a threshold, the headlight will turn on automatically(ie, during night). Also a Humidity sensor is used which senses the humidity change hence turns on the light automatically during foggy or rainy climates. This helps in saving energy and also increases the lifetime of headlight bulbs.
The LDR sensor senses the intensity of light to reduce the brightness and IR(Infra Red) Obstacle Avoidance Sensor senses the object coming in the opposite direction to control the brightness in the case where the two vehicle have the system.

Hardware Requirements:
    1. Adruino Uno
    2. Jumbo wires
    3. LDR sensor
    4. 5Volt Relay
    5. DHT Sensor
    6. IR Obstacle Avoidance Sensor

Software Requirements:
    Adruino UI


