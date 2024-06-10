# Import-Turtle
Python dilinde import turtle yazımı.
import turtle
yazi=turtle.Turtle()
yazi.speed(60)

yazi.left(220)

yazi.penup() 
yazi.goto(-100,-50)
yazi.pendown()
yazi.left(5)
yazi.color("purple")
for i in range(0,10):
  yazi.right(20)
  yazi.forward(36)
  yazi.circle(15)


yazi.left(150)
for i in range(0,10):
  yazi.right(20)
  yazi.forward(34)
  yazi.circle(15)


yazi.penup() 
yazi.goto(330,-40)
yazi.pendown()


yazi.left(260)
yazi.pensize(7)
for i in range(0,17):
    yazi.right(15)
    yazi.forward(53)
    yazi.color("red")
    yazi.circle(5)
    yazi.color("pink")
    yazi.circle(11)

    
yazi.penup() 
yazi.goto(600,-42)
yazi.pendown()


yazi.left(250)
yazi.color("blue")
for i in range(0,10):
  yazi.right(20)
  yazi.forward(36)
  yazi.circle(7)
  yazi.color("blue")
  yazi.circle(2)
  yazi.color("green")


yazi.left(150)
for i in range(0,10):
  yazi.right(20)
  yazi.forward(34)
  yazi.circle(15)
  

turtle.done()
