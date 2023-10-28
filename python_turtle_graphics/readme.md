## What is Python Turtle Graphics?


**_Turtle graphics_** is a beginner-friendly way to learn programming concepts and create visual designs using a simple graphics library. It gets its name from the concept of a "turtle" with a pen that moves on a canvas to draw shapes. The turtle can be controlled by a set of commands, allowing you to create drawings, patterns, and even simple games.


![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/94p8ncwf5csdf4awfq5u.jpeg)

In simple 
Turtle graphics is a computer programming concept that helps us create drawings and patterns using a virtual "turtle" that moves on the screen.Imagine a canvas or a drawing board, and on this canvas, we have a little "turtle" that we can control.The turtle has a pen attached to it, and it leaves a trail as it moves around the canvas.


![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/3q2j5gs7sy1wok5q8vka.jpeg)

In turtle graphics, you have a turtle, which is a graphical cursor that can be moved around a drawing canvas.
The turtle starts at a specific position, often in the center of the canvas, and has an initial orientation (usually facing upwards).
The turtle can be controlled using a set of commands to move, turn, and draw on the canvas


![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/p15w8ghk0xw862pwssem.jpeg)

## Key Concepts in Turtle Graphics:

_**Turtle:**_ The "turtle" is a virtual drawing tool that can move around a canvas. Think of it as a small robot with a pen attached to its tail.

_**Canvas:**_ The "canvas" is a virtual drawing area where the turtle moves and creates its drawings. It's like a piece of paper where you can draw.

_**Commands:**_ You control the turtle using simple commands, such as "move forward," "turn left," "turn right," "lift the pen," and "lower the pen."

_**Coordinates:**_ The canvas has a coordinate system, like a grid. The turtle moves around using these coordinates. The center is (0, 0), and you can move up, down, left, and right from there.

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/zlxtpylf62chu1obq1hy.jpeg)

## Basic Turtle Commands:

Here are some of the most commonly used turtle commands:

**_- forward(distance):_** Moves the turtle forward by a specified distance.

**_- backward(distance):_** Moves the turtle backward.

**_- left(angle):_** Rotates the turtle to the left by a specified angle.

_**- right(angle):**_ Rotates the turtle to the right.

_**- penup():**_ Lifts the pen, so the turtle won't draw when it moves.

_**- pendown():**_ Lowers the pen, so the turtle will draw.

_**- reset():**_ Clears the canvas and moves the turtle back to its starting position.

_**- penwidth(width):**_ Sets the width of the lines drawn by the turtle.

**_- color(color):_** Sets the color of the turtle's pen.


![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/exso0idmuwr842lrebes.jpeg)


Let's explore more about Turtle Graphics

**_Step 1 : Import the turtle module_**

You need to start by importing the `turtle` module, which provides the tools for turtle graphics.

```javascript
import turtle

```

**Step 2 : Create a turtle**

Next, create a turtle object that will do the drawing for you. You can give it a name, like `my_turtle.`

```javascript
my_turtle = turtle.Turtle()

```

**Step 3 : Move the turtle forward**

Move the turtle forward to draw the first side of the square. To draw a side of a square, you typically need to move the turtle forward by a certain distance. For a simple square, let's assume each side is 100 units long.

```javascript
my_turtle.forward(100)
```

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/pulcb4sbg33obocqqkqe.jpeg)


![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/hft59a1e26ugs3yg79el.jpeg)

**Step 4 : Turn the turtle to the right**

After drawing the first side, you need to turn the turtle to the right by 90 degrees. This prepares it to draw the second side of the square.

```javascript
my_turtle.right(90)
```

**Step 5 : Move forward and draw the second side**

Move the turtle forward again to draw the second side of the square. This side is also 100 units long.

```javascript
my_turtle.forward(100)

```
![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/rhyl5e2sr4u1ypy8k70f.jpeg)

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/8zaoxdlsmqwzegiedode.jpeg)

**Step 6 : Turn the turtle to the right**

Turn the turtle to the right by 90 degrees to prepare it for the third side.

```javascript
my_turtle.right(90)
```

**Step 7 : Move forward and draw the third side**

Move the turtle forward again to draw the third side of the square.

```javascript
my_turtle.forward(100)
```

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/hqz8mbx98upvyok9x9bg.jpeg)

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/k05tiu79rc86cgplllpz.jpeg)

**Step 8 : Turn the turtle to the right**

Turn the turtle to the right by 90 degrees to prepare it for the fourth and final side.

```javascript
my_turtle.right(90)
```
**Step 9 : Move forward and draw the fourth side**

Move the turtle forward to draw the fourth side of the square, completing the square.

```javascript
my_turtle.forward(100)
```

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/ddzl342y2jfnlw3foblg.jpeg)

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/6ikcny5etqdxlxmzdl39.jpeg)
**Step 10 : Complete the drawing**

After drawing the square, you can complete the drawing by closing the turtle graphics window.




```javascript
turtle.done()
```

Complete Program is right here

```javascript
import turtle
my_turtle = turtle.Turtle()
my_turtle.forward(100)
my_turtle.right(90)
my_turtle.forward(100)
my_turtle.right(90)
my_turtle.forward(100)
my_turtle.right(90)
my_turtle.forward(100)
turtle.done()
```
[click here to see the result](https://replit.com/@vayolapradeep00/square#main.py)

When you run this code, you'll see the turtle draw a square on the screen without using a loop. The turtle moves forward, turns right, and repeats this process for each side of the square, resulting in a simple square shape.
