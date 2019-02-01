GraphQL is a query language for your API, and a server-side runtime for executing queries by using a type system you define for your data. GraphQL isn't tied to any specific database or storage engine and is instead backed by your existing code and data.

A GraphQL service is created by defining types and fields on those types, then providing functions for each field on each type.

For examples in https://medium.freecodecamp.org/an-introduction-to-graphql-how-it-works-and-how-to-use-it-91162ecd72d0
<br/>
-- follow below example test inputs
{
  movie(id: 1) {
    name
  }
}

{
  movie(id: 3) {
    name
    id
    year
  }
}

{
  director(id: 1) {
    name
    id,
    age
  }
}

{
  director(id: 1) {
    name
    id,
    age,
    movies{
      name,
      year
    }
  }
}
