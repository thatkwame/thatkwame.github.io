# BMI Calculator
This is to calculate the BMI

Formula
```python

  name = input("Enter your name: ")
  weight = int(input("Enter your weight (in kg): "))
  height = int(input("Enter your height (in cm): "))
  conv_height = height/100
  bmi = round(weight/(conv_height**2), 2)
  
  print(f"Hi {name}, your BMI is {bmi}")
  
  if bmi < 18.5:
      print("You are underweight\nHealth Risk: Minimal")
  elif bmi >=18.5 and bmi < 25:
      print("You have a normal weight\nHealth Risk: Minimal")
  elif bmi >=25 and bmi < 30:
      print("You are overweight\nHealth Risk: Increased")
  elif bmi >=30 and bmi < 35:
      print("You are obese\nHealth Risk: High")
  elif bmi >=35 and bmi < 40:
      print("You are severly obese\nHealth Risk: Very High")
  else:
      print("You are morbidly obese\nHealth Risk: Extremely High")
  
  ```
