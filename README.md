# PizzaStore

## About this project

I followed the tutorial on building a minimal API using ASP.NET and Visual Studio.

[The tutorial is available at the microsoft training website.](https://learn.microsoft.com/en-us/training/modules/build-web-api-minimal-api/)

## Situation

Suppose that you work for a company, and you and your company have heard about the new minimal API.
The task is to create a project for it so that you can discuss whether to use it on your next project.

## Verbs

### GET

This is used when we need to read a resource.

There are two main cases when routing GET requests:

- a route
- a route parameter
    - this is used to find a specific resource
    - e.g., the route `/products/1` means to list a specific record
    - the numerical value can be captured and mapped to a parameter
    - e.g., `(int, id) => data.SingleOrDefault(product => product.id == id)`

### POST

This is used when we need to create a resource.

### PUT

This is used when we need to update a resource.

### Delete

This is used when we need to delete a resource.
