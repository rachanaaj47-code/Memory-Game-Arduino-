🎮 Arduino Simon Memory Game

An Arduino-based memory game inspired by Simon Says! The player must memorize and repeat an LED sequence that grows with each round. An LCD shows instructions and level progress, while a buzzer provides sound feedback.

🛠️ Components Used

Arduino Uno (or compatible)

16x2 I2C LCD display

4 LEDs (connected to pins 8–11)

4 Push buttons (connected to pins 2–5)

Buzzer (pin 6)

Resistors (220Ω for LEDs, 10kΩ for buttons)

Breadboard and jumper wires

⚡ Features

LCD instructions and live level display

Randomized LED sequences up to 50 levels

Audio feedback with buzzer for presses & errors

Win and game-over animations on LEDs & LCD

Simple restart option by pressing the red button



▶️ How to Play

Power up the Arduino → LCD displays “Welcome to Memory Game”.

Press the red button (pin 2) to start.

Watch the LED sequence carefully (LCD shows “Memorize”).

Repeat the sequence using the buttons.

If correct → you advance to the next level.

If wrong → LCD shows “Game Over” and LEDs flash.

Survive all 20 levels to win 🎉


🔧 Circuit Diagram

LEDs → Pins 8, 9, 10, 11

Buttons → Pins 2, 3, 4, 5 (with INPUT_PULLUP)

Buzzer → Pin 6

LCD (I2C) → SDA (A4), SCL (A5)

🤝 Credits

This project was inspired by a tutorial on YouTube. I have adapted, modified, and extended the code for learning purposes.
