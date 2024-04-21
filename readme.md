# Controller Exercise

## Objective

The objective of this exercise is to gain practical experience with Laravel controllers, covering creating controllers, routing controllers, passing data to controllers, and using resources with controllers.

## Prerequisites

- Basic knowledge of PHP and Laravel framework.
- Familiarity with routing concepts in Laravel.

## Task

1. **Creating Controllers**

   - Create a new controller named `WelcomeController`.
   - Use the artisan command `php artisan make:controller WelcomeController` to generate the controller file.
   - Implement a method within the controller named `index` to return a view displaying a welcome message.

2. **Routing Controllers**

   - Register a route that points to the `index` method of the `WelcomeController`.
   - Use the route to access the welcome message view.

3. **Passing Data**

   - Modify the `WelcomeController` to accept a parameter in the `index` method.
   - Pass the parameter value to the view and display it along with the welcome message.

4. **Resources and Controllers**
   - Create a resourceful controller named `ProductController` using the artisan command `php artisan make:controller ProductController --resource`.
   - Implement the necessary methods (`index`, `create`, `store`, `show`, `edit`, `update`, `destroy`) within the `ProductController`.
   - Define routes to route CRUD operations to the corresponding methods in the `ProductController`.

## Task Details

- Implement each task in the respective controller files (`WelcomeController.php`, `ProductController.php`) and `web.php` routes file.
- Test each route and controller method to ensure they function as expected.
- You can use mock data or dummy views for testing.

## Submission

- After completing the exercise, submit your modified controller files (`WelcomeController.php`, `ProductController.php`) and `web.php` routes file.
- Provide comments or documentation within your code to explain the purpose of each controller method and route.
