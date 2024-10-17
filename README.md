We create a form with two inputs for weight (in kilograms) and height (in centimeters).
A button is provided to trigger the calculation.
The BMI and its corresponding category are displayed after the calculation.
JavaScript Part:
An AngularJS app is created using angular.module.
The BmiController controller defines the calculateBMI function.
It uses a formula for BMI calculation (weight / (height * height)).
It then assigns the BMI category based on the calculated value.
