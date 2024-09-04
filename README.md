# City-Scape
This project is a beginner-level Java application designed to create an animated cityscape scene with dynamic elements. The program uses basic object-oriented programming principles to build a visually engaging simulation of a city, complete with buildings, UFOs flying above the city, and a car moving along the road.


Key Features:
Cityscape Background:

The cityscape consists of several buildings of varying heights and widths. These buildings are rendered using simple shapes to simulate a city skyline.
UFO Animation:

A fleet of UFOs fly over the city, randomly positioned in the sky. The UFOs move continuously and interact with each other through a collision detection mechanism that prevents them from overlapping.
The UFOs' colors change dynamically over time, adding a playful element to their movement.
Car Animation:

A car is animated to move back and forth across the cityscape, simulating a vehicle driving through the city. The movement is smooth and continuous, contributing to the dynamic nature of the scene.
User Interaction:

One UFO can be manually controlled by the user via keyboard input, allowing the UFO to move and even lift the car off the road. This adds an interactive element to the simulation.
Real-Time Animation:

The entire scene is rendered in real-time using the paint method from the Java Swing library. The program runs in an infinite loop, continually updating the positions of the UFOs and the car, creating smooth animation.
Technologies Used:
Java Swing: Used for the graphical interface and rendering of the cityscape.
Object-Oriented Design: Each entity in the cityscape (buildings, UFOs, car) is represented as a class with its own properties and methods.
Event Handling: Keyboard events allow for user interaction with the UFO.
