Things to note make this type of app:

1. Canvas 

2. Deterministic games (it is possible that in different machines the ball will fall in different places, It could be precision errors (hence we avoid decimal numbers, gravity value can be different ))(we will do frame based rendering, instead of time based rendering , because different people can have different time)(if we take time based rendering then all machines will have same speed)
    Clock times
    precision Errors

3. Physics 
    v = u + at (if we write a=9.8 it can be different)
    x = d + vt

4. Collision Physics
    (how velocity changes, horizontal and vertical velocity when they collide )

5. Friction to avoid ball running off
    (to prevent ball running off from canvas)

----------------------------------------------------------

Canvas size : 800 X 800
x,y suppose in real are in Canvas are 400.2 and 300.23 
but we will store it as 4002000 and 3002300
To avoid precision errors, padding and unpadding a number