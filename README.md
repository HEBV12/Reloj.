H = 0

def setup() :
    size(300, 600)

def draw() :
    global H
    background(175)


    ellipse(width/ 2, H, 50, 50)
    fill(232, 5, 24)
    if H > height :
        H = 0
    else:
        H = map(second(), 0, 59, 0, height)


    ellipse(width/ 2, H, 50, 50)
    fill(232, 5, 24)
    if H > height :
        H = 0
    else:
        H = map(minute(), 0, 60, 0, height)


    ellipse(width/ 2, k, 50, 50)
    fill(232, 5, 24)
    if H > height :
        H = 0
    else:
        H = map(hour(), 0, 24, 0, height)
