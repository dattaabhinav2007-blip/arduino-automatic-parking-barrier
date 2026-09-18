# arduino-automatic-parking-barrier
Arduino UNO automatic parking barrier using servo, button, LEDs and buzzer.
# Arduino UNO Automatic Parking Barrier

A simple Arduino UNO-based automatic parking barrier system that uses a push button to control a servo motor barrier, with LEDs and a buzzer providing visual and audible status indications.

## Components

- Arduino UNO
- Servo Motor
- Push Button
- Green LED
- Red LED
- Buzzer
- 220Ω Resistors
- Breadboard
- Jumper Wires

## Pin Configuration

| Component | Arduino Pin |
|---|---|
| Push Button | D3 |
| Green LED | D6 |
| Red LED | D7 |
| Buzzer | D8 |
| Servo Signal | D9 |

## Working

- The red LED indicates that the parking barrier is closed.
- When the push button is pressed, the servo motor rotates to 90° and opens the barrier.
- The green LED turns ON to indicate that the barrier is open.
- The buzzer provides an audible indication when the barrier opens.
- After a predefined delay, the servo returns to 0° and closes the barrier.
- The red LED turns ON again to indicate that the barrier is closed.

## Concepts Used

- Arduino UNO
- Digital Input and Output
- `INPUT_PULLUP`
- Servo Motor Control
- Push Button Interface
- LED Status Indication
- Buzzer Control
- Conditional Statements
- Basic Automation Logic

## Future Improvements

- IR sensor for automatic vehicle detection
- RFID-based vehicle access
- Ultrasonic sensor for vehicle presence detection
- LCD/OLED display for parking status
- Parking slot availability detection
- IoT-based parking monitoring

## Demo-Video: ⏯️ 
"https://drive.google.com/file/d/1GeEyaofN4fkb_JvQcriTds0mtsaFrC4Q/view?usp=drivesdk"

