# BrickBreak
A Breakout Arcade game clone in Unity 2021

================Objective================
Move the bottom bar horizontally to bounce the ball against the
bricks above. Once all bricks are hit, the next level will play.

You have 3 LIVES, every time the ball reaches below the bar,
a heart is lost. If you lose 3 LIVES, you are restarted back
to Level 1 and lose your score.

TO WIN you must make it through 5 Levels without dying and score
as many points as possible to obtain a high score.

Each brick hit rewards points based on their colour
    RED = 10 | YELLOW = 20 | GREEN = 30 | CYAN = 40 | BLUE = 50 | MAGENTA = 100
If the next brick hit is the same colour as the previous brick hit,
then the points of the current brick will double(x2).
EXAMPLE: Hitting RED RED YELLOW will earn, RED(10) + (RED(10) * 2) + YELLOW(20) = 50 points
HOWEVER: Hitting RED YELLOW RED will earn, RED(10) + YELLOW(20) + RED(10) = 40 points

So clearing each level by colour will earn the highest possible score.

===============Controls===============
A | Left
D | Right
P | Pause
