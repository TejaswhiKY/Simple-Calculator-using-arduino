🧮 Arduino Based Calculator (Wokwi Simulation)

A simple calculator built using Arduino Uno, a 4x4 Keypad, and a 16x2 I2C LCD Display.
This project is simulated online using Wokwi.

📌 Project Overview

This calculator performs basic arithmetic operations:

➕ Addition

➖ Subtraction

✖ Multiplication

➗ Division

Users enter numbers using the keypad, and results are displayed on the LCD screen.
🔤 Keypad Layout

[ 1 ] [ 2 ] [ 3 ] [ A ]
[ 4 ] [ 5 ] [ 6 ] [ B ]
[ 7 ] [ 8 ] [ 9 ] [ C ]
[ * ] [ 0 ] [ = ] [ D ]


🔎 Key Functions

A → Addition (+)

B → Subtraction (−)

C → Multiplication (×)

D → Division (÷)

= → Display result

* → Clear / Reset

🛠 Components Used

Arduino Uno

4x4 Matrix Keypad

16x2 LCD Display (I2C)

Jumper wires

Wokwi Online Simulator

🔌 Circuit Connections
📟 LCD (I2C) Connections
LCD Pin	Arduino Pin
GND	GND
VCC	5V
SDA	A4
SCL	A5
🔢 Keypad Connections
Keypad Pin	Arduino Pin
R1	9
R2	8
R3	7
R4	6
C1	5
C2	4
C3	3
C4	2
📚 Libraries Required

The following libraries are used:

Keypad.h

LiquidCrystal_I2C.h

(Wokwi installs them automatically.)

▶️ How to Run the Project (Wokwi)

Go to https://wokwi.com

Create a new Arduino Uno project

Add:

4x4 Keypad

16x2 I2C LCD

Copy and paste the Arduino code into the editor

Click Start Simulation

🧠 How It Works

Enter the first number using the keypad

Press an operator (+, −, ×, ÷)

Enter the second number

Press = to calculate

Result appears on the LCD

Press C to clear and reset

⚠️ Error Handling

Division by zero displays "Error"

Press C to reset the calculator

🚀 Future Improvements

Add decimal point support

Add negative numbers

Add scientific functions (sin, cos, log)

Use OLED display

Save last result in memory
