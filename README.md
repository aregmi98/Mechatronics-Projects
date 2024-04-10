In my Mechatronics class, I successfully completed three projects involving the Arduino Uno microcontroller, each demonstrating different functionalities and applications.

1. Pseudo Mobile Robot with Obstacle Detection:

Utilizing an ultrasonic sensor and a DC motor, I constructed a pseudo mobile robot capable of detecting obstacles.
The ultrasonic sensor, positioned at the front of the robot, detects objects in its path.
Depending on the distance of the detected object, the DC motor responds accordingly:
If the object is very far, the motor operates at full speed.
For objects at a medium distance, the motor runs at a reduced speed while continuing in the same direction.
When the object is near, the motor stops.
In the case of very near objects, the motor reverses its direction.
Throughout these operations, a system was implemented to display the operation mode, object distance, and motor speed on a monitor.
The code was developed to interpret sensor readings and control the motor's actions based on detected obstacles.

2. Weather Indicator with Servo Motor and Photocell:

Using a servo motor and a photocell, I designed a weather indicator capable of detecting light levels and indicating weather conditions.
In good weather conditions (bright light), the servo motor points at zero degrees, whereas in bad weather conditions (darkness), it points at 180 degrees.
A continuous rotation of the servo motor indicates shifting weather conditions as light levels change.
The code reads the output from the photocell to determine ambient light levels, adjusting the servo motor's angle accordingly to reflect the current weather conditions.

3. Stepper Motor Control with ELEGOO Remote:

Employing an ELEGOO remote control, I controlled a stepper motor with specific functionalities.
Pressing the appropriate buttons on the remote causes the stepper motor to rotate either clockwise or counterclockwise at a constant speed of 8 rpm.
Additional functionalities include adjusting the motor's speed by pressing the volume buttons on the remote.
Safeguards were implemented to prevent the motor from exceeding specified rpm limits.
The code interprets signals from the ELEGOO remote control and translates them into actions for the stepper motor, ensuring smooth and responsive control.

Overall, these projects demonstrate my ability to design and implement various functionalities using the Arduino Uno microcontroller, showcasing skills in sensor integration, motor control, and responsive system design in the field of mechatronics.
