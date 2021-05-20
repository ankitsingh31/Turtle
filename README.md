# Turtle
Automated UI design using turtle library
import turtle

wn = turtle.Screen()

ankit_design = turtle.Turtle()
ankit_design.speed(10)
dist = 1

while True:
    ankit_design.forward(dist)
    ankit_design.left(120)
    ankit_design.left(1)
    dist = dist+1
ankit_design.done()
wn.exitonclick
