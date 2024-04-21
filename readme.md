# Validations Exercise

## Objective

The objective of this exercise is to gain practical experience with data validations in Laravel, covering model validations, custom validations, and controller validations.

## Prerequisites

- Basic knowledge of PHP and Laravel framework.
- Familiarity with models, controllers, and form validation concepts in Laravel.

## Task

1. **Model Validations**

   - Add validation rules to the `Product` model to ensure that certain fields are required and meet specific validation criteria.
   - Define validation rules for fields such as name, price, and description using Laravel's validation syntax.

2. **Custom Validations**

   - Implement a custom validation rule to validate the uniqueness of the product name.
   - Create a custom validation rule class that checks if the product name is unique in the database.
   - Use the custom validation rule in the validation rules array of the `Product` model.

3. **Controller Validations**
   - Implement form validation in the controller methods for creating and updating products.
   - Validate the input data received from form submissions using Laravel's built-in validation methods.
   - Ensure that validation errors are appropriately handled and displayed to the user.

## Task Details

- Implement each task by adding validations to the `Product` model and corresponding controller methods.
- Test each validation scenario to ensure that input data is validated correctly.
- Use Laravel's validation error messages to provide meaningful feedback to users.

## Submission

- After completing the exercise, submit your modified `Product` model file and controller file(s).
- Provide comments or documentation within your code to explain the purpose of each validation rule and how it works.
