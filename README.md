# Activity18.py
no = eval(input("Enter number of triangles --> "))
for x in range(1, 6):
  for r in range(1, no + 1):
    for y in range(1, x + 1):
      print(" ", end="")
    for z in range(1, x - 1):
      print("*", end="")
    print("*")
print()
