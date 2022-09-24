# shape-draw-using-turtle


from turtle import Turtle,Screen

timmy=Turtle()
screen=Screen()
def draw(num_side):
  angle =360/num_side
  for i in range(num_side):
      timmy.forward(100)
      timmy.left(angle)
for i in range(3,11):
  draw(i)
screen.exitonclick()
