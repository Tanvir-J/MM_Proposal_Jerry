# Micromouse_Proposal_Example

## Overview

The overview should be a general description of your project. This should be a high level overview of your design decisions and how you will implement them, including detailed information on how you will handle difficulties such as software and hardware integration. This should also contain information on the hardware including references to the electrical requirements of all the individual components of your system and how those requirements will be managed. You should also discuss what kind of software you will be running, undergo a brief analysis to show you have the compute power to run your software, and discuss how the software will use the inputs your hardware gives it to complete its task. 

### Software Plan
This should be a more detailed explanation of how your software will work. This should include the programming language(s) you will be using, any libraries, what IDE(s) you will be working with, your approach for testing your software, and how you will be using the inputs from your hardware to complete your task.

### Hardware Plan
This should be a more detailed explanation of how your hardware will work. This should include the electrical requirements of all the individual components of your system and how those requirements will be managed. This should also include a detailed explanation of the hardware components of your system and how they will interact with each other. This should include a detailed explanation of the sensors you will be using, how they work, and how you will be using them to complete your task. This should also include specifications of your components, including the voltage/current ranges they support as well as their physical dimensions (when applicable). 

## Flowchart of System Design

Please include a flowchart of your system design. This should include the hardware and software components of your system and how they interact with each other. This should be a high level overview of your system. We recommend using a flowchart design software such as [draw.io](https://app.diagrams.net/) or [Lucidchart](https://www.lucidchart.com/pages/). However, you can also use any other software or even draw it by hand and take a picture of it. Simple programs such as Google Drawings or Microsoft Paint or Microsoft Office will also work. 

## Parts and Costs

>Note: Please try to get purchases from [SA's list of approved vendors](https://safe.sa.buffalo.edu/vendors/preferred).If you need a part that you cannot get from a company on the list it will be much more difficult to the purchase approved if at all. We recommend you check out [Adafruit](https://www.adafruit.com/) and [DigiKey](https://www.digikey.com/) for parts.

### Purchases

| Item Name w/Link | Cost per Unit | # of Units | Total Cost |
| ---- | ---------------- | ---- | ---------------- |
| [ARDUINO UNO R4 MINIMA](https://www.digikey.com/en/products/detail/arduino/ABX00080/20371542) | $20.00 | 1 | $20.00 |
| [Ultrasonic Distance Sensor - 3V or 5V - HC-SR04 compatible - RCWL-1601](https://www.adafruit.com/product/4007) | $3.95 | 4 | $15.80 |
| [USB Li-Ion Power Bank with 2 x 5V Outputs @ 2.1A - 5000mAh](https://www.adafruit.com/product/4288) | $26.95 | 1 | $26.95 |
| [DC Gearbox Motor - "TT Motor" - 200RPM - 3 to 6VDC](https://www.adafruit.com/product/3777?gad_source=1) | $2.95 | 4 | $11.80 |
| [Adafruit DRV8833 DC/Stepper Motor Driver Breakout Board](https://www.adafruit.com/product/3297) | $5.95 | 2 | $11.90 |
| | | **Total** | **$121.45** |

### Custom Creation

1. Wheels - 3D printed. 
3. Chassis - 3D printed.
4. Compute Casing for Raspberry Pi and battery - 3D printed.

### Parts on Hand

1. Wires
2. Breadboard
3. ...

## 3D Model

This should be a series of images from multiple angles of a to scale model of your robot that includes all major physical components (small components such as fundamental circuit components and wires can be omitted). You may use whatever method of creating this model as long as it is to scale. We recommend using 3D CAD programs such as Autodesk Inventor or Fusion 360. You may also use physical prototyping methods such as foam-core, cardboard, clay, or even Lego. The most important thing is that you get a real-world representation of the actual size of your components in relation to each other. As such, this model does not need to be detailed, as long as the size and shape of parts are correct. 

## Teammates and Responsibilities

### Name 1
Each name should include a brief one paragraph descriptions of the teammates primary responsibilities. 

### Name 2     
Will manage the power supply circuitry and the motor control circuitry. Responsible for ensuring that the Arduino and motor controllers are both properly powered from the battery but are on separate circuits with the proper voltages and currents. 

### Name 3
...

## Milestones

### Milestone Set 1: 11/8/23

* Get GPIO output from the microcontroller to light up LEDs on a breadboard. 
* Get GPIO input from the microcontroller to read button presses on a breadboard.
* Get GPIO input from the microcontroller to read sensor data from the ultrasonic sensors.
* Initial 3D Model for chassis completed.

### Milestone Set 2: 11/22/23
* Get the algorithm working in simulation. 
* Positioning algorithm can properly visualize mouse in simulation.
* Can make the motors spin from the battery.

### Milestone Set 3: 11/29/23
* Microcontroller can control the motors. 
* Microcontroller can read sensor data and calculate the position of the mouse.
* Microcontroller can run the algorithm.

### Milestone Set 4: 1/10/24
* Mouse can move in a straight line a stop when it reaches an obstacle.
* Mouse can turn 90 degrees when told to by the algorithm.
* Mouse can move for 10 minutes straight. 
* Mouse can execute different algorithms based on user inputs from physical buttons on the mouse. 

### Milestone Set 5: 1/24/24
* Mouse can move through a maze randomly without hitting walls.

### Milestone Set 6: 2/7/24
* Mouse can solve the maze. 



