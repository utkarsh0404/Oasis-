first I created a BMI Calculation formula: weight in kg divided by height square in meter. 
after that, i created an interpreted function that interprets the BMI value and returns a corresponding category based on commonly accepted BMI categories:
Underweight (< 18.5)
Normal weight (18.5 - 24.9)
Overweight (25.0 - 29.9)
Obese (30.0 and above). 
Then the main function interacts with the user to input weight and height.
It then calculates the BMI using calculate_bmi() and determines the BMI category using interpret_bmi().
Finally, it prints the calculated BMI and its category.
