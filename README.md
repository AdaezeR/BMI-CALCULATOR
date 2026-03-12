# BMI-CALCULATOR
This is a simple Python project that calculates Body Mass Index (BMI) using a person's weight and height.
## Project Description

The program calculates BMI using the formula:

BMI = weight / height²

It also classifies the BMI result into categories such as:
- Underweight
- Normal weight
- Overweight
- Obese

## Python Code

```python
name = "Adeola"
weight = 80
height = 1.75

bmi = weight / (height ** 2)

print(f"{name}, your BMI is {bmi:.2f}")

if bmi < 18.5:
    print("Category: Underweight")

elif bmi < 25:
    print("Category: Normal weight")

elif bmi < 30:
    print("Category: Overweight")

else:
    print("Category: Obese")

Example Output:
Adeola, your BMI is 26.12
Category: Overweight

Python Concepts Used:

Variables

Mathematical calculations

Conditional statements (if / elif / else)

String formatting


Author:

Adaeze Rose
