#叮当猫的头

import turtle as t

t.speed(10)
t.pensize(8)
t.hideturtle()
t.screensize(500, 500, bg='lightblue')

#猫脸
t.fillcolor('#00A1E8')
t.begin_fill()
t.circle(120)
t.end_fill()

t.fillcolor('white')
t.pensize (2)
t.begin_fill()
t.circle(100)
t.end_fill()

t.fillcolor('red')
t.pensize(5)
t.penup()
t.goto(0,125)
t.pendown()
t.begin_fill()
t.circle(20)
t.end_fill()

t.fillcolor('white')
t.pensize(1)
t.pencolor('red')
t.penup()
t.goto(4,145)
t.pendown()
t.begin_fill()
t.circle(6)
t.end_fill()

#猫眼睛
#左眼睛

t.fillcolor('white')
t.penup()
t.goto(-40,148)
t.pendown()
t.pensize(5)
t.pencolor('black')

t.begin_fill()
a=1
for i in range(120):
    if 0<=i<30 or 60<=i<90:
        a=a+0.06
        t.lt (3)#向左转3度
        t.fd(a)#前进a步
    else:
        a=a-0.06
        t.lt (3)
        t.fd(a)
t.end_fill()

t.penup()
t.goto(-55,170)
t.pendown()
t.pensize(9)
t.goto(-38,180)
t.left(-60)
t.forward(15)

#右眼睛
t.penup ()
t.home()
t.fillcolor('white')
t.penup()
t.goto(40,148)
t.pendown()
t.pensize(5)
t.pencolor('black')

t.begin_fill()
a=1
for i in range(120):
    if 0<=i<30 or 60<=i<90:
        a=a+0.06
        t.lt (3)#向左转3度
        t.fd(a)#前进a步
    else:
        a=a-0.06
        t.lt (3)
        t.fd(a)
t.end_fill()

t.penup ()
t.home()
t.fillcolor('black')
t.penup()
t.goto(28,165)
t.pendown()
t.pensize(5)
t.pencolor('black')
t.begin_fill()
t.circle(16)
t.end_fill()

t.penup ()
t.home()
t.fillcolor('white')
t.penup()
t.goto(30,165)
t.pendown()
t.pensize(5)
t.pencolor('white')
t.begin_fill()
t.circle(6)
t.end_fill()

#胡子

t.penup ()
t.home()
t.pensize(5)
t.pencolor('black')
t.goto(0,125)
t.pendown()
t.left(-90)
t.fd(40)

t.penup ()
t.home()
t.pensize(3)
t.pencolor('black')
t.goto(0,115)
t.pendown()
t.goto(-80,125)

t.penup ()
t.home()
t.pensize(3)
t.pencolor('black')
t.goto(0,115)
t.pendown()
t.goto(80,125)

t.penup ()
t.home()
t.pensize(3)
t.pencolor('black')
t.goto(0,103)
t.pendown()
t.goto(-80,113)

t.penup ()
t.home()
t.pensize(3)
t.pencolor('black')
t.goto(0,103)
t.pendown()
t.goto(80,113)

#第二个胡子
t.penup ()
t.home()
t.pensize(4)
t.pencolor('black')
t.goto(0,90)
t.pendown()
t.forward(80)

t.penup ()
t.home()
t.pensize(4)
t.pencolor('black')
t.goto(0,90)
t.pendown()
t.forward(-80)

#第三个胡子
t.penup ()
t.home()
t.goto(0,65)
t.pensize(7)
t.pencolor('black')
t.pendown()
t.left(96)
t.goto(-75,65)

t.penup()
t.home ()
t.goto(0,65)
t.right(0)
t.pendown ()
t.forward(80)

t.pu()
t.goto(-67, 60)
t.pd()
t.color('black', 'red')
t.pensize(6)
t.seth(-60)
t.begin_fill()
t.circle(80,40)
t.circle(80,80)
t.end_fill()


t.pu()
t.home()
t.goto(-50,40)
t.pd()
t.pensize(1)
t.fillcolor("#eb6e1a")
t.seth(40)
t.begin_fill()
t.circle(-40, 40)
t.circle(-40, 40)
t.seth(40)
t.circle(-40, 40)
t.circle(-40, 40)
t.seth(220)
t.circle(-80, 40)
t.circle(-80, 40)
t.end_fill()
  
# 领带
t.pu()
t.goto(-70, 12)
t.pensize(14)
t.pencolor('red')
t.pd()
t.seth(-20)
t.circle(200, 30)
t.circle(200, 10)
  
# 铃铛
t.pu()
t.goto(0, -46)
t.pd()
t.pensize(3)
t.color("black", '#f8d102')
t.begin_fill()
t.circle(25)
t.end_fill()
  
  
t.pu()
t.goto(-5, -40)
t.pd()
t.pensize(2)
t.color("black", '#79675d')
t.begin_fill()
t.circle(5)
t.end_fill()
  
t.pensize(3)
t.right(115)
t.forward(7)

t.done()








# k-ll
