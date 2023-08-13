# Smart-Home





## Description
This project encompasses a Smart Home System with three distinct modules: Door Security, Temperature Monitoring, and Motion-Activated Lighting.

1. **Door Security Module:**
- Utilizes a keypad for password entry, with '*' displayed on an LCD.
- Static 5-character password configured in the code.
- Successful password entry triggers:
  - Servo motor rotation (45 degrees for 10 seconds) for door access, followed by automatic closure.
  - RGB LED turns green for 10 seconds.
  - Buzzer sounds for 1 second.
- Incorrect password entry triggers:
  - RGB LED turns red for 5 seconds.
  - Buzzer sounds twice (0.5 seconds each) with a 0.1-second gap.

2. **Temperature Monitoring Module:**
 - LM35 sensor monitors temperature.
- RGB LED turns red when temperature exceeds 30 degrees Celsius.
- LCD displays temperature as "The temp is X", where X is the temperature reading.

3. **Motion-Activated Lighting Module:**
- Ultrasonic sensor detects distance; LDR sensor detects ambient light.
 - When distance < 15cm and low light is detected:
  - Relay activates, turning on a lamp.
 - Lamp remains on until distance > 15cm (indicating user moved away).

 This Smart Home System ensures enhanced security through password-based door access, proactive temperature monitoring, and efficient lighting management based on motion and lighting conditions.



## Team Members
Kareem Abdel Nabi  
Hasnaa Sayed  
Shrief Mohamed  
## Simulation Link
https://www.tinkercad.com/things/9mamAhiAh1P-copy-of-final-project-finaaaaaaal-/editel?sharecode=sbUNUBsD5VZI68zmm8y_ZOZtVyEzOQU4YGD05-9A5jw


