# Geometric Typography Session 1

### Chinese typography of sun


```python
def setup():
    size(600,600)


def draw():
    background(0)
    
    noStroke()
    fill(255)
    ellipse(width/2, height/2, 180, 180)
    
    noFill()
    stroke(255)
    strokeWeight(40)
    rect(150, 150, 300, 300)

    saveFrame("sun.png")
```
