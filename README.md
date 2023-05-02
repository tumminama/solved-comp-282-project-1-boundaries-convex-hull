Download Link: https://assignmentchef.com/product/solved-comp-282-project-1-boundaries-convex-hull
<br>
Idea: You have a set of integer lattice points in the plane that you are attempting to surround with a fence. Obviously, there are many ways to do this. However, only one of these ways has the shortest possible fence. Your program will determine which of the points the fence passes through and when given additional points whether they are inside or outside the fence. For example, given this set of points




You would place the fence as shown below.




This is usually referred to as finding the convex hull of a set of points. In class we will talk about a couple of possible ways to solve the problem: break it down into many smaller problems (determine whether a point is contained inside a triangle) and finding the upper boundry (sort the points left to right, keep a point if it is above the line between the point before and after) and the lower boundry.

Requirements: Write a java program (1 or more java classes) that reads a set of integer lattice points and then accepts additional points and determines whether they are inside or outside the convex hull. There is a sample data file and a sample interaction below. You

You must also have a file called status.txt which contains your name and a short (2-10 sentence) description of the status of your program. This file should be an ascii file. Though you may create it with MS Word (or notepad/wordpad/jGrasp/etc), you should be certain that it is a text file. A sample status.txt file is below.

Details: Your program must compile with the command “javac *.java”. In particular, this means that you should not place your classes into a package (or technically you should place them in the default package).

Your program must run with the command “java Driverl”. In particular, this means that you should have a file Driverl.java which includes a main method.

Your program must read the set of points from a file called “input.txt” which will be formatted as 2 points per line.

Your program must accept user input as 2 integers per line and respond with Inside or Outside until the user enters “quit”. In other words, match the sample below. DO NOT decide that it would be better if some other formatting was used.

You should be using good programming style. At a minimum break the project into appropriate classes, place your name near the top of each file, comment appropriately, be limited to 80 character lines, be limited to 30 line methods (usually shorter), and be properly indented.

Sample input.txt file: 0 10

0 0 1

0 0

-10 0

-1 -10

1 -10

22

-3-3

Sample interaction:

Welcome to Project 1: Boundries

Loading points from input.txt

Test point: &gt; 50 Inside Test point: &gt; 88 Outside Test point: &gt; quit

Sample status.txt file: John Noga – Project 1 The program works as required. It compiles/runs and the output matches the correct format to the letter. However, the style and formatting is incorrect because I DIDN’T: comment it didn’t even put my name in the file), keep the length of lines to 80 characters, and keep the length of methods to 30 lines.