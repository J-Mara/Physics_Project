# Physics_Project

Jordan Maragakis & Dustin Olteanu

Our project is a double pendulum simulator that demonstrates the properties of a chaotic system. It is run on Processing 3 and uses Velocity Verlet approximation to simulate smooth motion with minimal energy loss. 

Please clone the GitHub repo using this command in a ternimal: git clone https://github.com/J-Mara/Physics_Project.git
This will allow you to access the demonstrative video

In the start screen of the simulator, you can select the angles, lengths, and relative masses of both parts of the double pendulum, and you can add a second double pendulum on top of it to watch their paths. The default setting of the second double pendulum is only 1/10 of a degree different from the first one, but they still diverge within a few swings. 

The paths of both double pendulums are traced in the right side window with the respective color of the pendulum.

In the top left side of the left window, there are also three bars tracking the kenetic, potential, and total energy (from left to right) of the white pendulum. In a real double pendulum, the total energy would, of course, stay constant, but in our simulator it will tend to shift a bit due to approximations that need to be made to keep the code running at a decent speed.
