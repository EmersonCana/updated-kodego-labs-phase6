# Eloquent Relationships Exercise

## Objective

The objective of this exercise is to gain practical experience with Eloquent relationships in Laravel, covering defining associations between models, displaying associated data, deleting associated data, and using nested resource routing.

## Prerequisites

- Basic knowledge of PHP and Laravel framework.
- Familiarity with Eloquent ORM and database relationships.

## Task

1. **Eloquent Associations**

   - Define Eloquent relationships between the `Product` and `Category` models:
     - Each product belongs to a category.
     - Each category has many products.

2. **Displaying Associated Data**

   - Implement functionality to display products associated with a specific category.
   - Create a route that accepts a category ID and displays the products belonging to that category.

3. **Deleting Associated Data**

   - Implement functionality to delete a category and its associated products.
   - Ensure that when a category is deleted, all associated products are also deleted.

4. **Nested Resource Routing**
   - Implement nested resource routing for products within categories.
   - Define routes that allow accessing product-related actions within the context of a specific category.

## Task Details

- Implement each task by defining Eloquent relationships, creating routes, and implementing controller methods as instructed.
- Test each functionality to ensure that associated data is displayed correctly and deleted when necessary.
- Use Laravel's ORM methods and query builder to perform database operations.

## Submission

- After completing the exercise, submit your modified model files, route definitions, and controller methods.
- Provide comments or documentation within your code to explain the purpose of each relationship and implementation detail.
