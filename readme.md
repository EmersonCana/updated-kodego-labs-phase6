# Model & Migration Exercise

## Objective

The objective of this exercise is to gain practical experience with Laravel migrations and models, covering creating migrations, dropping migrations, adding columns to existing tables, using other migration commands, and working with databases using Eloquent ORM.

## Prerequisites

- Basic knowledge of PHP and Laravel framework.
- Familiarity with database concepts and SQL.

## Task

1. **Migrations**

   - Understand the purpose of migrations in Laravel and how they are used to manage database schema changes.
   - Research and familiarize yourself with Laravel migration commands.

2. **Creating Migrations**

   - Create a new migration file named `create_products_table`.
   - Define a schema within the migration file to create a `products` table with columns for `id`, `name`, `price`, and `description`.
   - Run the migration to create the `products` table in the database.

3. **Dropping Migrations**

   - Create a new migration file named `drop_products_table`.
   - Define the schema within the migration file to drop the `products` table.
   - Run the migration to drop the `products` table from the database.

4. **Adding Columns to Existing Tables**

   - Create a new migration file named `add_category_to_products_table`.
   - Define the schema within the migration file to add a `category` column to the `products` table.
   - Run the migration to add the `category` column to the `products` table.

5. **Other Migration Commands**

   - Explore other migration commands such as `rollback`, `refresh`, `reset`, and `status`.
   - Test each migration command to understand its functionality and usage.

6. **Database with Eloquent**
   - Create a model named `Product` using the artisan command `php artisan make:model Product`.
   - Define the `Product` model with the corresponding table name and fillable columns.
   - Use Eloquent ORM methods to interact with the `products` table, such as creating, reading, updating, and deleting records.

## Task Details

- Implement each task by creating migration files and models using the provided instructions.
- Test each migration to ensure it successfully modifies the database schema.
- Test each Eloquent ORM method to ensure it correctly interacts with the database.

## Submission

- After completing the exercise, submit your migration files (`create_products_table.php`, `drop_products_table.php`, `add_category_to_products_table.php`) and the `Product.php` model file.
- Provide comments or documentation within your code to explain the purpose of each migration and model method.
