# sketch2math
[https://jtguibas.github.io/sketch2math](https://jtguibas.github.io/sketch2math/)

**convert any sketch into a single mathematical equation** (using circles)

### Screenshot
![screenshot](https://i.imgur.com/F1bohSX.jpg)

unfortunately, the equation isn't multiplied out (it would look a lot cooler but it would also be a lot longer)

### How It Works

Being the bored student I am in math class, I was staring at a few equations until I realized this neat trick.

As you know, equations for circles are usually something like `x^2+y^2=1`--let's convert this to `x^2+y^2-1=0`. The neat thing about this form of a circle equation is that if you multiply it by another circle in that form(e.g., `x^2/4+y^2/4-1=0`), you'll actually be able to graph both of the individual equations at the same time. 

What you'll have is a classic case of concentric circles, graphed in one single equation.

![concentric](https://i.imgur.com/uWlpAJS.png)

This is the essence of the trick here, except it can be used for any number of circles. All I did was make the circles into extremely slim ellipses to disguise them as lines. From there, I can just treat them as line segments. Multiply all your equations, and you'll have your equation!!


### Extras

In the actual demo, the equations are graphed seperately because Desmos cannot handle such big equations. If you can find a powerful grapher than can take LaTeX as an input, please let me know.









