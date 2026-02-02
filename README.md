import turtle
x=turtle.Turtle()

def square(angle):
       x.forward(100)
       x.right(angle)
       x.forward(100)
       x.right(angle)
       x.forward(100)
       x.right(angle)
       x.forward(100)
       x.right(angle+10)

for i in range(36):
       square(90)



OUTPUT:
<img width="413" height="371" alt="Screenshot 2026-02-02 130738" src="https://github.com/user-attachments/assets/ae43544c-019e-43de-90c8-4e5ad3fcf9df" />
