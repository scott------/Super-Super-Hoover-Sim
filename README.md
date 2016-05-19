# Super-Super-Hoover-Sim
Super Super Hover Sim is a program that navigates a imaginary robotic hoover (much like a Roomba) through an equally imaginary room.

To run the simulation download input.txt and supersuperhooversim.html file to your computer.  
Place them both in the same directory (for simplicity).
Open the supersuperhooversim.html in any modern browser.
Click on the choose file and select the aforementioned input.txt file.
The resultant program output is sent to the console.log but will be displayed in the browser for your convenience.

The input file format is:
First line defines the grid size with two ints seperated by a space.
Example grid size: 493 35
The second line is the hoover's starting position given in the same format.
Example hoover starting position: 30 99
Subsequent lines contain the zero or more positions of patches of dirt, given in the same format.
The last line contains the driving instructions that the hoover will follow.  
The driving instructions move the hoover one space per instruction element.
These example driving instructions would attempt to move the rover up twice and left once: NNE
If the rover is already at the left most wall of the grid it will spin its wheels and not be able to move further east.
The hoover loves to clean dirt patches.
