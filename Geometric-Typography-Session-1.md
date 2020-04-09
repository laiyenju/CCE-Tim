# Geometric Typography Session 1

## Chinese typography of sun

Sun is **日** in Chinese typography, therefore I combined circle and rectangle to present **日**.

![](https://i.imgur.com/DxDLFDr.png)


```python
def setup():
    size(600,600)


def draw():
    background(0)
    
    noStroke()
    fill(255)
    ellipse(width/2, height/2, 120, 120)
    
    noFill()
    stroke(255)
    strokeWeight(50)
    rect(175, 100, 250, 400)

    saveFrame("sun.png")
```

## Chinese typography of sky

Sun is **天** in Chinese typography, therefore I combined triangle and rectangles to present **天**.

![](https://i.imgur.com/V9EQER3.png)


```python
def setup():
    size(600,600)


def draw():
    background(0)
    
    noStroke()
    fill(255)
    rect(200, 100, 200, 70)
    rect(150, 240, 300, 80)
    
    noFill()
    stroke(255)
    strokeWeight(80)
    triangle(300, 250, 170, 450, 430, 450)

    saveFrame("sky.png")
```
