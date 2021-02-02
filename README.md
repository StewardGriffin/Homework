# Homework
Homework Lesson 2
# Aceasta este tema lui Ion Mereuta
# EX1

# Introducem variabilele
a = float(input("Introduceti a: "))
b = float(input("Introduceti b: "))
c = float(input("Introduceti c: "))
# Aflam discriminantul 
import math
delta = math.pow(b, 2) - 4 * a * c
print(f"Discriminantul este {delta}")
# Aflam x1 si x2 in corespondenta cu Discriminantul 
if delta > 0:
    x1 = (b * (-1) + math.sqrt(delta)) / (2 * a)
    x2 = (b * (-1) - math.sqrt(delta)) / (2 * a)
    print(f"x1 = {x1}")
    print(f"x1 = {x2}")
elif delta < 0:
    print("Du-te si invata numere Complexe, pentru ca solutia nu apartine multimii numerelor Reale :)")
else:
    x = (b * (-1)) / (2 * a)
    print(f"x = {x}")
    
    # EX2

# Introducem coordonatele X si Y
print ("Introduceti coordonatele punctului X")
x1 = int(input("x1 = "))
x2 = int(input("x2 = "))
print ("Introduceti coordonatele punctului Y")
y1 = int(input("y1 = "))
y2 = int(input("y2 = "))
# Calculam distanta euclidiana
import math
d = math.sqrt(math.pow((x1 - y1), 2) + math.pow((x2 - y2), 2))
print (f"Distanta Euclidiana este: {d}")
