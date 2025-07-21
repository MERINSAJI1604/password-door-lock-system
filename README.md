# Password Door Lock System using Arduino

An Arduino-based electronic door locking system that uses a password entered via a keypad. If the correct password is entered, a servo motor rotates to unlock the door.
This is a group project that has been done as part of our coursework.

## 💡 Features
- 4-digit password protection
- Visual feedback using LCD Display (I2C)
- Servo motor control for locking/unlocking
- Can be enhanced with buzzer, alarm, or keypad lockout

## 🛠 Components Used
- Arduino UNO
- 4x4 Keypad
- Servo Motor (SG90)
- I2C LCD Display (16x2)
- Jumper Wires, Breadboard, Power Supply

## ⚙️ Working Principle
1. User enters a password through the keypad.
2. Arduino compares the entered code with a preset password.
3. If matched, the servo motor rotates to unlock the door.
4. If wrong, an error message is shown.

## 📁 Files Included
