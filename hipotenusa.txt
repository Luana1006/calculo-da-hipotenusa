import math 
cateto_a = int(input("Digite o cateto A: "))
cateto_b = int(input("Digite o cateto B: "))
cata = cateto_a**2  
catb = cateto_b**2
xx = cata+catb
hip = math.sqrt(xx)
print("A hipotenusa é: ", hip)