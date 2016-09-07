# temp conversion from C to F in a table with increments of 5 - assignment 8.5 


c=0
print("Temperature:" '         Celsius', '          Fahrenheit')
for c in range(0,101,5):
    F=int((c*(9/5))+32)
    print("                       ",c,"               ",F)
