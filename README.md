# Gym Nutrition System

A Python command-line app that generates personalized calorie targets and meal plans based on a user's fitness goal, body metrics, and activity level — with an estimated time-to-goal calculator.

---

## What It Does

You enter your details (weight, height, age, gender, activity level, and fitness goal) and the system calculates exactly how many calories you should eat per day. It then shows you three meal plan options to choose from and estimates how long it will take to reach your target weight.

Three goals are supported: **Weight Loss**, **Muscle Gain**, and **Maintenance.**

---

## Features

- Calculates BMR and TDEE using the Mifflin-St Jeor equation
- Supports weight input in kg or lbs, height in cm or feet/inches
- Generates 3 culturally relevant meal plan options per goal (Breakfast, Lunch, Dinner, Snacks)
- Estimates months needed to reach target weight using caloric deficit/surplus modeling
- Validates all user inputs and enforces a minimum of 1,200 kcal/day for safety
- Built using OOP — Parent class `Client` with three subclasses for each fitness goal

---

## Technologies

- Python 3
- Jupyter Notebook
- OOP (Inheritance, Encapsulation, Polymorphism)

---

## How To Run

```bash
git clone https://github.com/your-username/gym-nutrition-system.git
cd gym-nutrition-system
jupyter notebook meal_generator_final.ipynb
```

Run all cells and follow the prompts in the output.

---

## Sample Output

```
PERSONALIZED NUTRITION REPORT
------------------------------

Name: Ali
Age: 22
Gender: male
Weight: 80.0 kg
Height: 175.0 cm
Activity level: Moderately Active
Goal: Loss
Daily Calorie Target: 2272 kcal

Selected meal plan:
  Breakfast: Boiled Eggs + Brown Bread
  Lunch: Daal + 1 Roti + Cucumber
  Dinner: Chicken Handi (light oil) + Salad
  Snacks: Nuts (small handful)

Estimated time to loss 10.0 kg: ~5.1 months.
------------------------------
```

---

## Author

**Muhammad Mohtashim Aman** — Business Data Analytics Student, COMSATS University Islamabad

> These are general estimates based on standard formulas and are not a substitute for professional dietary advice.
