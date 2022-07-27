# Rainbow_Benzene
This is my first repository
#It looks like octagon

import turtle
colors = ["violet", "indigo", "blue", "green", "yellow", "orange", "red" ]
t = turtle.Pen() #creates turtle object
turtle.bgcolor("black") #color to change screen background
for x in range(360): #it will turn 360 degree
    t.pencolor(colors[x%7]) 
    t.speed(50) #speed of the pen
    t.width(x//100 + 1)
    t.forward(x) #(distance) - method used to draw a straight line
    t.right(45) #(angle) - method to use rotate the turtle
