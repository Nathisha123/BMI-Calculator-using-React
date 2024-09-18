BMI Calculator
Overview

This is a simple BMI (Body Mass Index) Calculator built using React. It allows users to input their height and weight, calculates their BMI, and provides feedback on their weight status.
Features

   Input fields for height (in cm) and weight (in kg).
    Calculation of BMI based on user input.
    Displays weight status based on BMI value.
    Validation for numeric inputs.
    Clear button to reset the form.

Technologies Used

   React: A JavaScript library for building user interfaces.
    useState: A React Hook for managing state in functional components.
    
  Usage

  Enter your height in centimeters in the "Height" field.
  Enter your weight in kilograms in the "Weight" field.
  Click the "Calculate BMI" button to see your BMI and weight status.
  Click the "Clear BMI" button to reset the form.

Code Explanation

   State Management: The app uses useState to manage height, weight, BMI, BMI status, and error messages.
    BMI Calculation: The calculateBMI function checks if the height and weight inputs are valid, calculates the BMI, and sets the appropriate status.
    Input Validation: Regular expressions ensure that only numeric values are accepted.
    Clear Functionality: The clearAll function resets all fields to their initial state.
