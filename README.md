# more2004
x = 200 c = 200 v = 200 b = 200 def setup():    size(400,400) def draw():     global x,v,c,b     background(255)     ellipse(c,v,30,20)     ellipse(x,b,30,20)     ellipse(c,b,30,20)     ellipse(x,v,30,20)     x -=1     c +=1     b -=1     v +=1     
