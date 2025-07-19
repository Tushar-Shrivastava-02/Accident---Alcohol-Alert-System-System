
#  Accident & Alcohol Alert System

An Arduino-based real-time safety system to detect **vehicle accidents**, **alcohol consumption**, and **fire hazards**, and send **location-based emergency alerts** using GPS and GSM modules.

##  Features

-  **Accident Detection** with accelerometer sensor
-  **Fire Detection** using flame sensor
-  **Alcohol Detection** (MQ3 sensor - optional)
-  **GPS Tracking** using NEO-6M module
-  **GSM Alerts** via SIM800L or SIM900 module
-  Buzzer & LCD feedback
-  Auto-call + SMS to emergency contact
-  Manual reset button for false alerts

---

##  Components Used

| Component         | Description                        |
|------------------|------------------------------------|
| Arduino Uno/Nano | Microcontroller                    |
| SIM800L          | GSM Module                         |
| NEO-6M           | GPS Module                         |
| ADXL335 / MPU6050| Accelerometer                      |
| MQ3              | Alcohol Sensor (Optional)          |
| Flame Sensor     | Analog + Digital                   |
| LCD 16x2 (I2C)   | Display                            |
| Buzzer, Button   | Alerts & Input                     |

---

##  Circuit Diagram



## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Accident-&-Alcohol-Alert-System.git
Open the merged_alert_system.ino file in Arduino IDE.

Install required Arduino libraries:

LiquidCrystal_I2C

AltSoftSerial

TinyGPS++

SoftwareSerial

Upload the sketch to your Arduino board.

Connect hardware as per the schematic and power it up.

SMS & Call Format
Sends Google Maps link with exact GPS location.

Auto-dials the emergency number set in the code.

## Replace this line in code with your phone number:

const String EMERGENCY_PHONE = "+91XXXXXXXXXX";

Testing
Simulate a crash or sudden movement to test accident detection.

Bring flame or alcohol vapors near the respective sensor.

Verify LCD, buzzer, and GSM responses.

 Future Enhancements
Cloud Integration (Blynk, Firebase)

Data logging with SD card

Ignition cut-off feature on alcohol detection

Mobile app alerts




 Author
Tushar Shrivastava
