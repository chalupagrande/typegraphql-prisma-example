# TypeGraphQL-Prisma Example

This is a small application to experiment with TypeGraphql-Prisma. Attempting to create a typesafe Graphql API where types can be inferred on both the front and back end. TypeGraphql-Prisma also will generate boilerplate CRUD resolvers for all your DB entities.

## Getting Started

- everything flows from the `schema.prisma` file.

## Making Schema Changes

- update the Schema in the `schema.prisma` file and create migrations to local db
- `yarn generate` to generate the types
- import the types into the rest of the application

## TODO:

- create a front-end and fetch types from the generated backend and generate types
- write a custom resolver.
