# Partial-2-exam
# Triangle 
# 2.py

def triangle(size):
  for x in range(1, size + 1):
    for i in range(x):
      print("T ", end="")
        
        print()
    for x in range (1, size):
      for i in range(size - x):
        print("T ", end="")
        
      print()
      
triangle(8)
