# CRUD with Laravel Exercise

## Objective

The objective of this exercise is to gain practical experience with CRUD operations in Laravel, covering RESTful routing conventions, Laravel resource routing for index, show, create, update, and destroy actions, custom rendering of views, and controller exception handling.

## Prerequisites

- Basic knowledge of PHP and Laravel framework.
- Familiarity with routing and controllers in Laravel.

## Task

1. **RESTful Routing Conventions**

   - Understand the RESTful routing conventions for CRUD operations:
     - GET /resource: Index action to display a list of resources.
     - GET /resource/{id}: Show action to display a specific resource.
     - GET /resource/create: Create action to display a form for creating a new resource.
     - POST /resource: Store action to create a new resource.
     - GET /resource/{id}/edit: Edit action to display a form for editing a resource.
     - PUT/PATCH /resource/{id}: Update action to update a specific resource.
     - DELETE /resource/{id}: Destroy action to delete a specific resource.

2. **Laravel Resource Routing: index and show**

   - Create a resourceful route for the `Product` model using Laravel resource routing.
   - Implement controller methods for index and show actions to display a list of products and details of a specific product.

3. **Laravel Resource Routing: create**

   - Implement a controller method for the create action to display a form for creating a new product.
   - Create a view to render the product creation form.

4. **Laravel Resource Routing: update and destroy**

   - Implement controller methods for the update and destroy actions to update and delete a specific product.
   - Create views to render the product editing form and confirmation for product deletion.

5. **Custom Rendering**

   - Customize the rendering of views for each CRUD action, ensuring a consistent and user-friendly interface.
   - Use Laravel Blade templates and components to enhance the views.

6. **Controller Exception Handling**
   - Implement exception handling in the controller methods to handle errors gracefully.
   - Use try-catch blocks or Laravel's exception handling mechanisms to catch and handle exceptions.

## Task Details

- Implement each task by creating routes, controller methods, and views as instructed.
- Test each CRUD operation to ensure it functions as expected.
- You can use mock data or interact with a database using Eloquent ORM.

## Submission

- After completing the exercise, submit your modified routes, controller, and view files.
- Provide comments or documentation within your code to explain the purpose of each route, controller method, and view.
