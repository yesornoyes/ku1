import turtle

def draw_star():
    star = turtle.Turtle()
    star.fillcolor("yellow")
    star.begin_fill()

    for _ in range(5):
        star.forward(100)
        star.right(144)

    star.end_fill()
    turtle.done()

# 调用函数进行绘制
draw_star()
