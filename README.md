<h1 align="center">Obstacle-Avoiding-Robot-Project</h1>

![IMG_3468](https://github.com/nooralobaidi/Obstacle-Avoiding-Robot-Car-Project/assets/112970543/966054f9-8874-4d7f-8250-a3ae33cf695a)

![IMG_3455 2](https://github.com/nooralobaidi/Obstacle-Avoiding-Robot-Car-Project/assets/112970543/4f779a90-aa6b-4bb2-83a2-1e75c393f6d2)


## Project Objective:



## Components Used:
For this project, I used the following components:

- Arduino Board (UNO)
- USB –A to micro-USB cable
- Car Chassis
- L298 motor driver module
- Ultrasonic sensor module
- Servo motor
- 7.5 V Battery
- Connecting wires


## Design and Construction:

I designed the robot by assembling these components. The ultrasonic sensors are placed on the front to detect obstacles. The Arduino controls the motors based on sensor input. I constructed the chassis to accommodate all the parts securely

![image](https://github.com/nooralobaidi/Obstacle-Avoiding-Robot-Car-Project/assets/112970543/87c3638a-653d-40ab-8832-9826c02fd1c3)


## Functionality

My obstacle-avoiding robot is designed to navigate its environment autonomously while efficiently avoiding obstacles. The core functionality of the robot is achieved through a combination of hardware components and software algorithms.

### Obstacle Detection

The robot employs an ultrasonic sensor module connected to analog pins A1 and A2 to detect obstacles. This sensor uses ultrasonic waves to measure distances and calculate the presence of obstacles in the robot's path, with a maximum detection range of 200 centimeters.

### Decision-Making Algorithms

To make informed decisions, the robot utilizes a set of decision-making algorithms. When an obstacle is detected within 35 centimeters, the robot follows a predetermined sequence:

1. **Stop**: It momentarily stops to assess the situation.
2. **Move Backward**: It moves backward for a specific duration to create distance from the obstacle.
3. **Pause**: It pauses again for further evaluation.
4. **Look Around**: The robot uses a servo motor to look right and left, measuring distances to identify an open path.
5. **Turn**: Based on these measurements, it determines whether to turn right or left to circumvent the obstacle.

These intelligent decision-making algorithms ensure that the robot efficiently navigates its environment, avoiding collisions with obstacles.


## Motor Control

Motor control is integral to the robot's mobility. The L298 motor driver module manages two DC motors on the car chassis, enabling the robot to perform the following movements:

- **moveStop()**: Halts both motors.
- **moveForward()**: Advances the robot forward.
- **moveBackward()**: Propels the robot backward.
- **turnRight()**: Executes a right turn.
- **turnLeft()**: Executes a left turn.

These motor control functions are crucial for the robot's maneuverability. They work in conjunction with the obstacle detection and decision-making algorithms to ensure the robot can navigate autonomously and avoid obstacles effectively.

In summary, my obstacle-avoiding robot seamlessly integrates sensor data, decision-making algorithms, and motor control to navigate autonomously and avoid obstacles effectively.

## Challenges Faced

### Battery Capacity

**Challenge:** Initially, I faced a significant challenge with the robot's power source. I started with regular 1.5-volt batteries, using a total of four of them. However, this configuration proved insufficient to power the robot effectively.

**Solution:** To overcome this challenge, I replaced the standard batteries with rechargeable alkaline batteries, each providing 3.7 volts. With two of these batteries in series, I achieved a more reliable power supply that sustained the robot's operations.

### Code Execution Issues

**Challenge:** Another challenge arose when attempting to run the robot's code. It was discovered that a crucial library was inadvertently omitted from the initial code upload.

**Solution:** To address this issue, I promptly included the missing library, ensuring that all the required software components were properly integrated. This allowed the code to execute correctly and control the robot's functions as intended.

In summary, the project encountered several challenges, including battery capacity limitations, code execution issues due to missing libraries, and a hardware problem with the motor functionality. These challenges were effectively addressed by upgrading to rechargeable alkaline batteries, resolving code-related issues, and ensuring the correct hardware connections. These solutions allowed us to overcome these obstacles and enhance the functionality and reliability of our obstacle-avoiding robot.


## Project Results and Robot Performance

My project resulted in a robot that demonstrated effective obstacle avoidance in various environments. When an obstacle was within 35 centimeters, the robot reliably stopped, moved back, and made well-coordinated turns to navigate around it. Overall, it performed well in avoiding collisions.

### Limitations

However, there are some limitations to consider:

1. **Limited Sensor Range**: The robot can't detect obstacles beyond 200 centimeters, potentially leading to collisions in open areas.

2. **Sensor Interference**: In specific conditions, like highly reflective surfaces, sensor accuracy may be impacted.

3. **Battery Life**: The robot's operating time is limited; longer use may require additional battery capacity.

4. **Complex Environments**: In cluttered areas, the robot may struggle to choose the best path.

To better understand the robot's performance, I can share pictures or videos demonstrating its obstacle-avoidance abilities. These visuals can showcase how well it navigates and avoids obstacles.

## Future Improvements

In the future, I plan to enhance our robot project in several key areas:

1. **Extended Sensor Range**: I intend to extend the sensor range to detect obstacles at greater distances, improving the robot's ability to navigate in open areas.

2. **Redundancy with Additional Sensors**: Adding redundancy with additional sensors will enhance obstacle detection reliability and fault tolerance.

3. **Advanced Navigation Algorithms**: Implementing advanced navigation algorithms will result in improved decision-making, allowing the robot to make even more intelligent choices.

4. **Battery Efficiency**: I'll work on improving battery efficiency to extend the robot's operating time between charges.

5. **Enhanced User Interface**: I plan to enhance the smartphone app's user interface for a more user-friendly experience.

6. **Obstacle Mapping**: Exploring obstacle mapping capabilities will allow the robot to create maps of its environment, further improving navigation.

7. **Wireless Connectivity**: I'll consider adding wireless connectivity for remote control and monitoring.

8. **Mechanical Upgrades**: Mechanical upgrades will enhance the robot's durability and mobility.

9. **Autonomous Charging**: Investigating autonomous charging solutions will ensure the robot can recharge itself when needed.

10. **Additional Safety Features**: Lastly, I'll look into adding more safety features to protect the robot and its surroundings.

These improvements will not only make my robot more versatile but also increase its adaptability to various environments and tasks, ultimately enhancing its overall performance and functionality.

