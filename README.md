# sketch2math
[https://jtguibas.github.io/sketch2math/index.html](https://jtguibas.github.io/sketch2math/index.html)

convert any sketch to a single mathematical equation using a hacky trick  with circles

Screenshot:
![screenshot](https://i.imgur.com/ijyj0rE.png)

### How It Works

Being the bored student I am in math class, I was staring at a few equations until I realized this neat trick.

As you know, equations for circles are usually something like `x^2+y^2=1`, let's convert this to `x^2+y^2-1=0`. The neat thing about this equations is that if you convert them multiply them by another version of a circle (e.g., `x^2/4+y^2/4-1=0`), you'll actually be able to graph both of the individual equations at the same time. 

What you'll have a is a classic case of concentric circles, graphed in one single equation.

![concentric](https://i.imgur.com/uWlpAJS.png)

This is the essence of the trick here, except it can be used for any number of circles. All I did was make the circles extremely elliptic to disguise them as lines. From there, I can just treat them as line segments. Multiply all your equations, and you'll have your equation!!









