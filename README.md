# 183DA Design of Robotic Systems: Lab3 Trajectory Planning Using Rapidly-exploring Random Trees (RRT)

In this lab, we built a Rapidly-exploring Random Tree (RRT) to find a path from an arbitrary initial position to a final position in the presence of obstacles. We used a nonholonomic planner designed to capture the true physical motion of the car in a 2-dimension grid world. 

### RRT Trajectory Planning Simulations for a Nonholonomic Car in 2D

![RRT1](https://github.com/nathanzmarch/183DALab3/blob/master/images/RRT1.gif)

![RRT2](https://github.com/nathanzmarch/183DALab3/blob/master/images/RRT2.gif)

![RRT3](https://github.com/nathanzmarch/183DALab3/blob/master/images/RRT3.gif)

## Relevant files
Lab 3.pdf-Please see for more information about how we constructed our NH RRT algorithm.

Trajectory Planning.ipynb-Contains most of the code that implements the algorithm

RRT_includes.py-Helps set up our environment by defining basic functions and classes

## Installing

Install Anaconda Navigator at [Anaconda](https://www.anaconda.com/)

Open Anaconda Prompt type in

```
pip install pygame
```

Then open Anaconda Navigator application and launch Jupyter Notebook. Open Trajectory Planning.ipynb then

```
Cell -> Run All
```

A window should appear and you can start clicking inital and final points to watch the RRT algorithm find a path between them.

### References 
“Chapter 1 – Installing Python and Pygame.” Invent with Python, inventwithpython.com/pygame/chapter1.html.

Chin, Tim. “Robotic Path Planning: RRT and RRT*.” Medium, Medium, 26 Feb. 2019, medium.com/@theclassytim/robotic-path-planning-rrt-and-rrt-212319121378.

Chin, Tim. “Robotic Path Planning: RRT and RRT*.” Medium, Medium, 26 Feb. 2019, medium.com/@theclassytim/robotic-path-planning-rrt-and-rrt-212319121378.

DasSnipezDasSnipez. “Python, Pygame, How to Draw an Arc.” Stack Overflow, 1 Nov. 1963, stackoverflow.com/questions/20850481/python-pygame-how-to-draw-an-arc.

“HexagonExample.” Pygame.org, www.pygame.org/project/241.

Pbpf. “Pbpf/RRT-2.” GitHub, github.com/pbpf/RRT-2.

Pygame :: Anaconda Cloud, anaconda.org/cogsci/pygame.

“PyGame Drawing Basics.” Pygame Drawing Basics, sites.cs.ucsb.edu/~pconrad/cs5nm/topics/pygame/drawing/.

“PyGame Drawing Basics.” Pygame Drawing Basics, sites.cs.ucsb.edu/~pconrad/cs5nm/topics/pygame/drawing/.

Pygame.draw - Pygame v2.0.0.dev5 Documentation, www.pygame.org/docs/ref/draw.html#pygame.draw.arc.

Pygame.gfxdraw - Pygame v2.0.0.dev5 Documentation, www.pygame.org/docs/ref/gfxdraw.html.

“Python Mathematical Functions.” Programiz, www.programiz.com/python-programming/modules/math.
