3D Animated Wall Clock
Course: Graphics and Visual Computing
Name: Kritika Kesarwani
Roll No: 30

What I Made

A 3D animated wall clock in Maya with a golden frame, black face, white numbers, and three animated hands that rotate clockwise at the correct speeds.

What I Learned (GVC Concepts)

Modeling: Created clock using cylinders, cubes, cones
Animation: Hands rotate using frame-based expressions
Transformations: Positioned and rotated all objects
Lighting & Shadows: Added light with shadow casting
Materials: Applied colors using Lambert shaders
Scripting: Used Python to automate everything
Rendering: Used Arnold for final output

How to Use It

Open Maya
Open Script Editor 
Go to Python tab
Copy code from clock_30.py
Paste and press Ctrl+Enter
Press Play to see it animate

How It Works


The script creates the clock geometry (frame, face, numbers, hands) and then applies an expression that rotates the hands based on the current frame number. The second hand completes one rotation every 10 seconds, minute hand every 2 minutes, hour hand every 24 minutes.
Numbers are created as 3D text using extrusion.

What's Inside

clock_30.py - Python script
Clock_animation_30.mb - Maya scene file
Screenshots of the clock
Demo video showing animation
Project poster

Challenges I Had

The hands were rotating the wrong way at first, so I had to use negative values in the rotation formula. Also, when the timeline looped, the hands would reset to zero, so I switched to frame-based calculations instead of keyframes.

This Is My Original Work
All code written by me. No external plugins used, just Maya's built-in Python API.
