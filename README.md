def  quadraticFormula1(a,b,c):
    x1 = (-b+((b**2-4*a*c)**1/2))/2*a
    return x1

def  quadraticFormula2(a,b,c):
    x2 = (-b-((b**2-4*a*c)**1/2))/2*a
    return x2

print("The first root of x**2 + 7*x + 10 is", quadraticFormula1(1,7,10) )
print("The second root of x**2 + 7*x + 10 is", quadraticFormula2(1,7,10) )
