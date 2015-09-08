# m8balll
def pict():
  f = "C:\\Users\\PC8\\Desktop\\magic-8-ball-6.jpg"
  p = makePicture (f)
  s = makeStyle (sansSerif , bold,12)
  addTextWithStyle(p, 57, 100, "Concenterate and aske again", s, white)
  repaint (p)
