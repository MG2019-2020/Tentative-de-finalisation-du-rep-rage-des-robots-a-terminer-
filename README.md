import random

a=[int(),int(),int(),int(),int()]
for var in a:
    var=random.randint(0,10)
b=[int(),int(),int(),int(),int()]
for var in b:
    var=random.randint(0,10)
c=[int(),int(),int(),int(),int()]
for var in c:
    var=random.randint(0,10)
d=[int(),int(),int(),int(),int()]
for var in d:
    var=random.randint(0,10)
e=[int(),int(),int(),int(),int()]
for var in e:
    var=random.randint(0,10)

graph=[a,b,c,d,e] 
note1 = input("entrer l'ordonnée ou se situe le robot ")
note2 = input("entrer l'absisse du robot")
result= var[int(note1)][int(note2)]
print(result)
