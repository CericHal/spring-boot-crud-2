# Summary of project



## What is JPA

- Java Persistence API (JPA)
- Standard API for Object-to-relational-mapping (ORM)

Only a specification
- Defines a set of interfaces
- requires implementation to be used

## Benefits of JPA

By having standard API, you are not locked to vendor's implementation

More portable and flexible code.

## Various DAO Techniques

Version 1: Use entityManager but leverage native hibernate API

Version 2: Use Entity manager and standard JPA API

Version 3: Spring Data JPA

## Development Process

1. Upate db configs in app.properties
2. Create Employee entity
3. Create DAO interface
4. Create DAO implementation
5. Create REST controller to use DAO