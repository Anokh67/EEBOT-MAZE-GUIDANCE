# EEBOT-MAZE-GUIDANCE

## What This Project Is About
For my COE538 Microprocessor Systems project, I programmed the eebot robot to navigate a maze autonomously. The robot follows a line using photoresistors, makes decisions at intersections, handles dead ends by turning around, and then learns the correct path so it can retrace it back to the start. The entire idea was to demonstrate learning behaviour: the robot explores, remembers its mistakes, and then solves the maze correctly.

## What Components Did I Use

What I Used

The eebot already comes with a lot of hardware, so I mainly focused on programming. Here’s what I worked with:

HCS12 microcontroller
1. 6 guider sensors (CdS photoresistors) for line tracking and junction detection
2. Front and back bumpers to detect dead ends and triggers
3. Two DC motors with PWM control for speed and direction
4. Wheel rotation detectors for precise turning
5. LCD display for showing battery level, sensor readings, and robot state
