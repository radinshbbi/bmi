# bmi

age = int(input("please enter your age?\n"))
Weight = float(input("please enter your weight?\n"))
Height = float(input("please enter your height?\n"))


bmi = Weight / (Height**2)

print("Calculate BMI for: ",age)
print("Weight: ", Weight)
print("Height: ", Height)

if bmi <= 18.4 :
    print("your bmi:","underweight")
elif bmi >= 18.5 and bmi <= 24.9 :
        print("your bmi:","normal")
elif bmi >= 25.0 and bmi <= 39.9 :
    print("your bmi:","overweight")
else :
     print("your bmi:","obese")
