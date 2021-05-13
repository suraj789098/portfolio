---
title: "Computer Graphics"
date: 2021-05-12T12:09:13+05:30
draft: false
---

Computer graphics is a field of computer science that studies methods for digitally synthesizing and manipulating visual and geometric information using computational techniques. Although the term often refers to the study of three-dimensional computer graphics, it also encompasses two-dimensional graphics and image processing. 

There are many applications of computer graphics like:
1. Print design
2. Digital art
3. Special effects
4. Video games
5. Visual effects
6. Computer-aided design and many more

![](first.jpg)

OpenGL is a cross-language, cross-platform application programming interface for rendering 2D and 3D vector graphics. The API is typically used to interact with a graphic processing unit, to achieve hardware-accelerated rendering. OpenGL is used extensively in the field of computer-aided design, virtual reality, flight simulation, and video games. The OpenGL specification describes an abstract API for drawing 2D and 3D graphics. The API is defined as a set of functions that may be called by the client program. Although the function definitions are superficially similar to those of the C programming language, they are language-independent. 
Codeblocks is a free C/C++ IDE built to meet the most demanding needs of its users. Any kind of functionality can be added by installing/coding a plugin.

OpenGL can be installed and used in code blocks. In Linux operating system, OpenGL is installed using the following steps:
1. Install  Code Blocks Software 
2. Open the terminal and install OpenGL Libraries using the following commands:
     a. sudo apt-get update
     b. sudo apt-get install libglu1-mesa-dev freeglut3-dev mesa-common-dev
     c. sudo apt-get install freeglut3-dev
3. Open code blocks-->settings-->compiler-->linker setting-->other linker options: add -lGL -lGLU -lGLUT  -lm

![](second.png)

As part of the course, we had to complete a mini-project on computer graphics. So I worked on a project involving the simulation of seasons in a year using OpenGL.
We simulated the summer, winter, rainy, and autumn seasons in this project. For the project, we chose a city scene. Using line drawing concepts, we created buildings, schools, shops, and other multi-layered structures. We drew the sky with the sun, moon, and clouds created with the circle drawing technique We drew the trees, grass, people, streetlights, and cars as well. The sky is blue in the summer, with fewer clouds, and the sun is hot. We chose the sunrise scene for the winter season. We drew the snow falling. During the rainy season, the sky became grayer with the addition of more grey clouds. The rain was created with line drawing techniques and animated with a ‘for' loop on vertices. Trees turn orange in the autumn season, and their leaves fall off. Animated people, cars, and clouds were used in all scenes. The dried leaves are allowed to fall from the tree. When we press ‘w,' we are taken to a winter scene, when we press ‘a,' we are taken to an autumn scene, when we press ‘r,' we are taken to a rainy scene, and finally, when we press ‘s,' we are taken to a summer scene. To draw images easily in OpenGL, translation, scaling, and rotating concepts are used. If we want to draw the same object multiple times, such as cars or clouds, we write code to draw a single object and then translate it to a different position by varying the size of the object with translation and scaling. 

Graphical programming is not solely concerned with mathematics or geometry. As a result, it all comes down to imagination. Coordinates are responsible for the changes, transformations, and movements of shapes and vectors. You had to decide on a platform and begin coding your designs. Although the theory is important, practice is the only way to improve your designs. Every day, computer graphics have an impact on almost every aspect of everyone's life.
