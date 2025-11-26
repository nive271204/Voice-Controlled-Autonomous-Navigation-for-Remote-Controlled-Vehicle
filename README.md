# *Voice-Controlled Autonomous Navigation for Remote-Controlled Vehicle*
The Voice-Controlled Autonomous Navigation System enables a remote-controlled vehicle to operate through simple spoken commands, removing the need for manual joysticks or physical controllers.
Using Arduino, Bluetooth communication, and motor control, the vehicle interprets voice inputs like forward, reverse, left, right, and stop, allowing hands-free navigation.
This system enhances accessibility, improves user experience, and provides a modern, low-cost solution for robotics, education, and assistive mobility.

# *Features*

*1.Input Options*

• Voice input through smartphone app (speech-to-text)

• Text-based control (optional command interface)

• Bluetooth command transfer from mobile to vehicle

*2.Processing*

• Arduino microcontroller receives commands via Bluetooth

• Commands matched with predefined movement instructions

• Microcontroller activates motor driver for precise navigation

• Real-time command execution with low latency

*3.Output Options*

• Vehicle movement: Forward / Reverse / Left / Right

• Instant braking and stopping

• LED indicators for command confirmation

• Smooth and stable motor response

# *How to use*
*STEP 1: PREPARE YOUR HARDWARE*

• Get all required components: Arduino board, HC-05 Bluetooth module, L298N motor driver, motors, and power supply.

• Ensure your smartphone has a working speech-to-text app.

• Assemble your vehicle chassis and mount all electronic modules.

*STEP 2: SET UP THE ARDUINO ENVIRONMENT*

• Install the latest Arduino IDE.

• Connect the Arduino board to your computer via USB.

• Install required libraries (if any).

• Verify your COM port settings.

*STEP 3: IUPLOAD THE CONTROL CODE*

• Open the provided Arduino sketch.

• Check pin configuration for motors and Bluetooth.

• Upload the code to the Arduino board.

• Confirm successful upload.

*STEP 4: CONNECT THE BLUETOOTH MODULE*

• Pair your smartphone with the HC-05 module.

• Default password: 1234 or 0000

• Open your voice-command mobile app (or serial Bluetooth controller).

• Connect to the paired device.

*STEP 5: POWER THE VEHICLE*

• Insert the battery pack into the vehicle.

• Ensure correct voltage for motors and Arduino.

• Switch ON the power supply.

*STEP 6: ISSUE VOICE COMMANDS*

• Speak clear commands like:

“Forward”

“Reverse”

“Left”

“Right”

“Stop”
• The app converts voice to text and sends it via Bluetooth

*STEP 7: VEHICLE EXECUTION*

• Arduino reads the incoming command.

• Command is matched and processed.

• Motor driver initiates movement.

• Real-time directional changes occur smoothly.

*STEP 8: ADJUST SETTINGS IF NEEDED*

• Check Bluetooth range (up to 10 meters).

• Ensure motors are not overloaded.

• Align wheels for better movement.

• Recharge battery when performance slows.

*STEP 9 : TROUBLESHOOT IF NEEDED*

• If vehicle is not responding:

Reconnect smartphone Bluetooth

Check wiring between Arduino → Motor Driver → Motors

Verify power supply
• If commands are misinterpreted:

Use shorter, clear words

Check the speech-to-text app
• If motors jitter or stop:

Check loose connections

Ensure enough battery voltage.

# *Technical Detail*
This application is bulit using:

• Microcontroller: Arduino Uno / Nano

• Communication: HC-05 Bluetooth module

• Motor Control: L293D / L298N motor driver

• Power Supply: 9V/12V battery depending on motors

• Movement System: DC motors with chassis wheels

• Programming Language: Embedded C / Arduino IDE

• Voice Processing: Mobile speech-to-text application

• Real-Time Control: Serial Bluetooth commands


# *Browsing compatability*

*1.Bluetooth Compatibility:*

Supports all major smartphone platforms:

• Android devices (fully supported)

• iOS devices (with compatible Bluetooth SPP apps)

*2.Operational Range:*

• Works within 10 meters line-of-sight

• Minimal latency with stable Bluetooth connection

*3.Hardware Flexibility:*

• Compatible with multiple motor drivers

• Works with ultrasonic sensors (optional upgrade)

• Expandable to autonomous mode with extra modules
# *License*

This project is for personal use only.
