# Arduino LCD Memory Game (Simon Says)

This is a memory game built using Arduino Mega, a 16x2 I2C LCD display, buttons, and a buzzer. It’s a Simon Says-style game that displays a sequence on the screen, which the player must repeat by pressing the right buttons.

## 🧠 Features
- Increasing difficulty
- LCD shows color names (no LEDs needed!)
- Buzzer feedback for success/failure
- Score display

## 🧰 Components Used
- Arduino Mega
- 16x2 I2C LCD
- 4 Push buttons (Red, Green, Blue, Yellow)
- 220Ω Resistors
- Buzzer
- Jumper wires and breadboard

## 🧪 How it works
1. LCD shows color pattern (e.g., RED → BLUE → GREEN)
2. Player must repeat it using buttons
3. If correct: game levels up
4. If wrong: game resets and displays score

## 📸 Images / Demo
Add photos or a video link here

## 🔧 Wiring (Pinout)
| Component | Arduino Pin |
|----------|--------------|
| Button 1 (Red) | 2 |
| Button 2 (Green) | 3 |
| Button 3 (Blue) | 4 |
| Button 4 (Yellow) | 5 |
| Buzzer | 6 |
| LCD SDA | 20 |
| LCD SCL | 21 |

## 👨‍💻 Code
The code is in `Game_code.ino`.

## 🎯 Created for:
Hack Club's [Summer of Making](https://hackclub.com/summer-of-making/)
