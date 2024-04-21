# Serialization Exercise

## Objective

The objective of this exercise is to gain practical experience with serialization in Laravel, covering model serialization and serializing associations.

## Prerequisites

- Basic knowledge of PHP and Laravel framework.
- Familiarity with Eloquent ORM and relationships.

## Task

1. **Model Serializer**

   - Implement serialization for the `Product` model to transform model instances into JSON format.
   - Define a custom serializer for the `Product` model that specifies which attributes to include or exclude in the JSON output.
   - Use Laravel's built-in serialization methods or libraries such as Fractal to handle model serialization.

2. **Serializing Associations**
   - Implement serialization for associated data between the `Product` and `Category` models.
   - Serialize the relationship between products and categories to include category information when serializing products.
   - Ensure that the JSON output includes category details for each product.

## Task Details

- Implement serialization for the `Product` model and associated data as instructed.
- Test the serialization methods to ensure that model instances and associated data are serialized correctly.
- You can use Laravel's built-in serialization methods or third-party libraries to handle serialization.

## Submission

- After completing the exercise, submit your modified serialization methods for the `Product` model and associated data.
- Provide comments or documentation within your code to explain the serialization process and any customization made.
