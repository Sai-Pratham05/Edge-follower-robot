# Edge Follower Robot

This project is an Edge Follower Robot using Arduino and infrared sensors. The robot detects the edge of a surface or a line using IR sensors and makes decisions to follow the path without falling off the edge.

## Circuit Diagram

Below is the circuit diagram for the Edge Follower Robot:

![Edge Follower Robot Circuit Diagram]()

## Components Used

- Arduino Uno
- 2 x Infrared (IR) Obstacle Sensors
- L298N Motor Driver
- 2 x DC Motors
- Connecting wires
- Power source

## Working Principle

- The IR sensors detect the edge or line.
- The Arduino processes the sensor data.
- The L298N motor driver controls the motors based on the Arduino's signals.
- The robot turns away from the edge when detected, allowing it to follow the line or stay on the surface.

## How to Build

1. Connect the IR sensors to the Arduino as shown in the diagram.
2. Connect the Arduino output pins to the L298N motor driver.
3. Connect the motors to the L298N.
4. Upload the program to the Arduino.
5. Power up the system and test on a surface with edges or a line.

## License

This project is open source and available under the [MIT License](LICENSE).

---

*Feel free to contribute or open issues for improvements!*
