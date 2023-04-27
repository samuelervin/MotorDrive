# Micropython DCMotor Project using an L298N motor driver

## Callout: 
This code is not all mine. I started with the below to get an idea of how different micropython was from Arduino motor control. You can see a good wiring diagram here for this project for an ESP32/ESP8266
https://microcontrollerslab.com/micropython-dc-motor-l298n-driver-esp32-esp8266/?unapproved=255869&moderation-hash=647f66869a2eff461a330ae2a6e6506c#comment-255869
## L298N motor driver

- Common motor driver for many DC motor projects.
- Depending on the type it is capable of running two motor outputs.
- Capable of Pulse Width Modulation of the motor/s as well for speed control.
  
## ESP8266 NodeMCU - code works fine just have to use these pins

| Variable Name | Pin Number|
|-----|
| PIN1 | GPIO05 |
| PIN2 | GPIO04 |
| PWM  | GPIO13 |
