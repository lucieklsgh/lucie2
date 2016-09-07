def TempConvert():
    temp = 'y'
    while temp == 'y' or temp == 'Y':
        Fahrenheit=int(input("Enter temperature in Fahrenheit: "))
        Celsius=int((Fahrenheit - 32)*(5/9))
        print("The Temperature is:", Fahrenheit, "°F =", Celsius, "°C")
        temp = input("Another temperature to convert? Enter 'y' or 'n': ")
TempConvert()