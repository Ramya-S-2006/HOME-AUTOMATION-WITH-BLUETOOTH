# HOME-AUTOMATION-WITH-BLUETOOTH

COMPANY: CODTECH IT SOLUTIONS

NAME: RAMYA S

INTERN ID:CT04DH785

DOMAIN: EMBEDDED SYSTEMS

DURATION: 4 WEEKS

MENTOR: NEELA SANTHOSH

DESCRIPTION:
This project is a simple yet effective example of a Bluetooth-controlled home automation system using an Arduino Uno. It allows the user to remotely control three devices: a light, a bulb, and a fan (represented by LEDs and a DC motor in the circuit). The Arduino is connected to the components through digital pins, and commands are sent via serial communication — typically through a Bluetooth module like the HC-05 paired with a smartphone. Each device responds to a specific character command entered through the serial interface. For instance, sending the letter 'A' turns the light on, while 'a' turns it off. Similarly, 'B' and 'b' control the bulb, and 'C' and 'c' control the fan. When the Arduino receives a command, it checks the input and activates or deactivates the corresponding pin, thereby controlling the device. This setup provides a hands-on way to learn digital I/O control, serial communication, and device interfacing with microcontrollers. In real-life applications, this system can be extended to create a full-fledged home automation solution where appliances such as fans, lights, and electronic devices can be controlled from a smartphone. This is particularly useful for elderly or physically challenged individuals who may find it difficult to manually operate switches. It also supports energy management by allowing users to switch off unused devices remotely. The system can be implemented in homes, offices, classrooms, or any space where remote control of electrical devices is beneficial. Overall, this project provides a foundational understanding of how automation systems work and offers a base for developing more advanced smart home technologies.
Explanation of the Circuit and Code:
Hardware Setup:
Three output devices are connected to pins 2 (light), 3 (bulb), and 5 (fan).
Each LED has a current-limiting resistor connected in series.
A DC motor is connected to simulate a fan; proper driver circuitry (like a transistor or motor driver) is implied for actual current handling but not shown in detail here.
Common GND and power supply are shared between Arduino and the breadboard.
Real-Life Applications:
This project is a basic prototype of a Bluetooth-enabled smart home automation system, and has real-world implications such as:
Remote Appliance Control:
You can control home appliances like lights, fans, or bulbs remotely using a smartphone via Bluetooth.
Assistive Technology:
Helps elderly or physically challenged individuals to control electrical devices without moving around.
Energy Management:
Devices can be turned off when not in use via simple commands, reducing power consumption.
Classroom or Office Automation:
Teachers or office administrators can control multiple electronic devices (like fans, lights, projectors) from a single console.
DIY Automation Projects:
Great for learning embedded systems, serial communication, and hardware control in DIY projects and student prototypes.
#OUTPUT:![Image](https://github.com/user-attachments/assets/84ce58c3-a086-4da1-9881-1d2ca44c94a4)
